## Proje 3: IMDb Film Veri Analizi Raporu

Bu rapor, geniş bir film veri setinin (yaklaşık 43,000 kayıt) analizi sonucunda film başarısını etkileyen temel faktörleri ve sinema dünyasındaki eğilimleri özetlemektedir.

### Teknik Özet

* **Kullanılan Kütüphaneler:** Pandas, Numpy, Matplotlib.
* **Veri Temizliği:** Kritik sütunlar (`imdbVotes`, `runtime`) sayısal analize uygun hale getirilmiş; eksik puan (`imdbRating`), tür (`genre`) ve yönetmen (`director`) bilgisi olan kayıtlar analizden çıkarılmıştır.

---

## I. Analiz Bulguları ve Film Başarısı

### 1. Film Süresi ve Başarı İlişkisi

| Süre Grubu | Ortalama IMDb Puanı | Bulgular |
| :--- | :--- | :--- |
| **3 saat üstü** | **7.35** | En yüksek ortalama puana sahip grup. |
| **2-3 saat** | 6.97 | Yüksek puan alan ikinci grup. |
| **1-2 saat** | 6.25 | Filmlerin çoğunluğunun bulunduğu, ortalamanın altındaki puan grubudur. |
* **Trend:** Film süresi uzadıkça, ortalama IMDb puanı artma eğilimi göstermektedir.

### 2. Film Türü Popülerliği

* **En Popüler Türler:** Veri setinde en çok yer alan ve arzı en yüksek olan türler sırasıyla **Drama** ve **Comedy**'dir.
* **İçgörü:** Pazarın büyük çoğunluğu dramatik ve komedi yapımları üzerine kuruludur.

---

## II. Yönetime Öneriler (Sinema Stratejisi)

### 1. Yüksek Puan Stratejisi
* **Süre Yatırımı:** Eleştirel başarıyı (yüksek IMDb puanı) hedefleyen projeler için, hikayenin gerektirmesi durumunda, **2 saatten fazla** süreye sahip yapımlar üretmek ortalama puanı artırma potansiyeline sahiptir. Uzun filmlerin daha yüksek beklentiyle izlendiği ve beğenildiğinde yüksek puan aldığı görülmüştür.

### 2. Pazar Odaklılık
* **Tür Önceliği:** Ticari başarı ve geniş kitleye ulaşma hedefi olan projeler için yatırım ve üretim önceliği, pazarın en büyük hacmini oluşturan **Drama** ve **Comedy** türlerine verilmelidir.
## Proje 3: IMDb Film Veri Analizi

Bu depo, veri analizi öğrenim serisinin son projesi olan IMDb Film Veri Analizi çalışmasına ait kodları, bulguları ve nihai rapor özetini içermektedir.

## Proje Amacı

Geniş bir film veri setini analiz ederek film başarısını etkileyen faktörleri (puan, süre, tür, yönetmen) incelemek ve sinema dünyasındaki eğilimleri keşfetmektir.

## Kullanılan Teknolojiler

* **Programlama Dili:** Python
* **Temel Kütüphaneler:** Pandas, Numpy, Matplotlib
* **Sürüm Kontrolü:** Git & GitHub

## Analiz Özeti ve Temel Çıktılar

Analiz sırasında veri temizliği, Keşifsel Veri Analizi (EDA) ve görselleştirme adımları uygulanmıştır.

### Öne Çıkan Bulgular:

1.  **Süre ve Puan İlişkisi:** Film süresi uzadıkça (özellikle 3 saat üzeri yapımlar), ortalama IMDb puanı artma eğilimi göstermektedir (En yüksek ortalama puan: 7.35).
2.  **Popüler Türler:** Veri setindeki arzın büyük bir kısmı **Drama** ve **Comedy** türlerinden oluşmaktadır.
3.  **Başarı Kriteri:** En çok oy alan filmlerin tamamı küresel çapta tanınan (`The Shawshank Redemption`, `The Dark Knight`) yapımlardır.
4.  **Veri Temizliği:** Film süresi (`runtime`) ve oy sayısı (`imdbVotes`) sayısal analize uygun hale getirilmiş; eksik kritik kayıtlar (`imdbRating`, `genre`, `director`) analizden çıkarılmıştır.

### Proje Dosyaları:

| Dosya Adı | Açıklama |
| :--- | :--- |
| `imdb_analysis.ipynb` | Veri yükleme, temizlik, EDA ve görselleştirme adımlarının uygulandığı ana Python Notebook dosyası. |
| `IMDB_ANALIZ_RAPORU.md` | Yönetime sunulan, bulguları ve önerileri özetleyen nihai rapor. |
| `runtime_vs_rating.png` | Film süresi gruplarına göre ortalama puanı gösteren görsel. |
| `top_10_genres.png` | En popüler 10 film türünün dağılımını gösteren görsel. |
| `movies_initial.csv` | Analiz için kullanılan ham veri seti. |

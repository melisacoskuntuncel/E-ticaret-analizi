# E-ticaret-analizi
Online Retail Data Analysis & Customer Segmentation (RFM)
📌 Proje Özeti

Bu projede, bir e-ticaret firmasına ait Online Retail veri seti kullanılarak uçtan uca bir veri analizi süreci gerçekleştirilmiştir.
Proje kapsamında veri temizleme, keşifsel veri analizi (EDA), satış trend analizi ve müşteri segmentasyonu (RFM & K-Means) adımları uygulanmıştır.

Amaç;

Satış performansını analiz etmek

En değerli ürün ve müşterileri belirlemek

Müşterileri davranışlarına göre segmentlere ayırmaktır

📊 Kullanılan Teknolojiler

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook

🧹 Veri Temizleme (Data Cleaning)

Aşağıdaki işlemler uygulanmıştır:

Eksik müşteri ID’si olan kayıtların kaldırılması

Negatif veya sıfır ürün adedi ve fiyatların temizlenmesi

Eksik ürün açıklamalarının StockCode bazlı doldurulması

Tarih alanlarının datetime formatına dönüştürülmesi

Toplam satış tutarının (TotalPrice) hesaplanması

Zaman bazlı değişkenlerin (Yıl, Ay, Gün, Hafta Günü) oluşturulması

Temizlenmiş veri seti ayrıca CSV formatında dışa aktarılmıştır.

📈 Keşifsel Veri Analizi (EDA & Trend Analizi)

EDA sürecinde aşağıdaki analizler yapılmıştır:

Toplam ciro, sipariş sayısı ve müşteri sayısı hesaplandı

Aylık bazda:

Toplam satış tutarı

Satılan ürün adedi

En çok satan 10 ürün (adet bazlı)

En yüksek ciro getiren 10 ürün

Ülkelere göre toplam satış dağılımı

Bu analizler sayesinde satış trendleri ve ürün performansları görselleştirilmiştir.

👥 Müşteri Segmentasyonu – RFM Analizi

Müşteri davranışlarını analiz etmek için RFM (Recency, Frequency, Monetary) modeli uygulanmıştır:

Recency: Son alışverişten geçen gün sayısı

Frequency: Toplam fatura sayısı

Monetary: Toplam harcama tutarı

RFM skorları 1–5 aralığında hesaplanmış ve her müşteri için RFM_Score oluşturulmuştur.

🔗 K-Means ile Segmentleme

RFM değişkenleri ölçeklendirilerek K-Means algoritması uygulanmıştır:

StandardScaler ile normalizasyon

4 farklı müşteri segmenti oluşturuldu

Segmentlerin ortalama Recency, Frequency ve Monetary değerleri analiz edildi

Bu sayede:

Sadık müşteriler

Yeni müşteriler

Düşük değerli müşteriler

Yüksek harcama yapan müşteriler
gibi gruplar net şekilde ayrıştırılmıştır.

🎯 Proje Çıktıları

Satış ve müşteri davranışları hakkında aksiyon alınabilir içgörüler

Pazarlama ve müşteri ilişkileri stratejileri için segment bazlı analiz

Gerçek hayatta e-ticaret firmalarında kullanılabilecek bir analiz altyapısı

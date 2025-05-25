# AirbnbMLproject
Airbnb Fiyat Tahmini Projesi

Proje Hakkında

Projenin temel amacı, New York City'deki Airbnb ilan verilerini kullanarak gözetimli öğrenme algoritmaları ile konaklama fiyatlarını tahmin etmektir.

Kullanılan Araçlar ve Kütüphaneler
Python
pandas, numpy
matplotlib, seaborn
scikit-learn


Proje Adımları

1. Keşifsel Veri Analizi (EDA)

Veri setindeki eksik veriler incelenmiş, gerekli sütunlar düşürülmüş ve verinin genel yapısı anlaşılmıştır. Dağılımlar ve korelasyonlar görselleştirilerek ilişkiler analiz edilmiştir.

2. Veri Ön İşleme

Eksik veriler temizlenmiştir.

Kategorik değişkenler one-hot encoding yöntemiyle sayısallaştırılmıştır.

Veri eğitim ve test olarak bölünmüştür (%80-%20).

3. Modelleme

Random Forest Regressor ve Linear Regression algoritmaları uygulanmıştır.

Her iki model de eğitilmiş ve test verisi üzerinde değerlendirilmiştir.

4. Değerlendirme

Modeller MAE, MSE, RMSE ve R^2 metrikleri ile değerlendirilmiştir.

Random Forest daha düşük hata oranı ile daha iyi performans göstermiştir.

5. Sonuç

Random Forest modeli fiyat tahminleme problemi için daha uygun bulunmuştur. Model, Airbnb gibi platformlar için fiyat belirleme, gelir tahmini ve rekabet analizi gibi işlevlerde kullanılabilir.


Kullanılan Algoritmalar

Random Forest Regressor (Ana model olarak seçildi)

Linear Regression (Karşılaştırma amacıyla)


Geliştirme Önerileri

Daha fazla özellik mühendisliği yapılabilir.

Zaman serisi analizleri dahil edilebilir.

Derin öğrenme algoritmaları ile daha ileri tahminleme denenebilir.

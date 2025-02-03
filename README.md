# 🏡 Ev Fiyat Tahmini | House Price Prediction

Bu proje, California Housing veri setini kullanarak farklı makine öğrenmesi modelleri ile ev fiyatlarını tahmin etmeyi amaçlamaktadır. 

Model performanslarını MSE (Mean Squared Error) ve R² skoru ile değerlendirdim.

📌 Proje İçeriği
✔ Veri Ön İşleme: Eksik verilerin kontrolü, ölçeklendirme (StandardScaler)
✔ Modelleme:
Linear Regression
Ridge Regression (L2 Penalty)
Lasso Regression (L1 Penalty)
ElasticNet Regression (L1 + L2 Penalty)

✔ Model Performans Karşılaştırmaları: MSE ve R² skorlarıyla analiz
✔ Görselleştirme: Model hatalarının ve performans farklarının grafiklerle gösterimi

📊 Sonuçlar ve Değerlendirme
Linear ve Ridge Regression, en düşük hata oranlarına sahip olup en iyi tahminleri sundu.
Lasso Regression, yüksek hata oranı ve düşük R² skoru ile beklenenden daha düşük performans gösterdi.
ElasticNet Regression, Lasso’ya benzer sonuçlar verdi ancak Ridge kadar başarılı olmadı.
Ridge Regression, daha iyi genelleştirme sağladığı için büyük veri setlerinde daha stabil olabilir.

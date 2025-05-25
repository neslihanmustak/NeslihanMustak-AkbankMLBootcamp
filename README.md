# ML-Bootcamp-Project

# 📈 AAPL Hisse Senedi Fiyat Tahmini - ML Bootcamp Projesi

Bu repo, Akbank - Global AI Hub iş birliğiyle gerçekleştirilen **Makine Öğrenmesi Bootcamp** kapsamında hazırlanmıştır. Bu projede, Apple Inc. (AAPL) hisse senedinin geçmiş kapanış fiyatlarına bakılarak ertesi günün kapanış fiyatı tahmin edilmiştir.

---

## 📁 Giriş

Projede kullanılan veri seti:  
🔗 [World Stock Prices - Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/world-stock-prices-daily-updating)

Tahmin probleminin çözümünde zaman serisi verileri için gözetimli öğrenme (Supervised Learning) algoritmaları uygulanmıştır.

Kullanılan modeller:
- Linear Regression ✅
- Ridge Regression
- Lasso Regression
- KNN Regressor

Proje sürecinde, aşağıdaki adımlar takip edilmiştir:
- Veri temizleme ve eksik veri interpolasyonu
- Lag (gecikmeli) öznitelikler oluşturulması
- 4 farklı model ile `TimeSeriesSplit` yöntemiyle çapraz doğrulama
- En iyi modelin seçimi ve değerlendirilmesi
- Gerçek ve tahmin verilerinin görselleştirilmesi

---

## 📊 Metrikler

| Model              | Ortalama MSE | Std Sapma |
|--------------------|--------------|-----------|
| Linear Regression  | 0.3845       | 0.5795    |
| Ridge              | 0.3852       | 0.5791    |
| Lasso              | 5.4371       | 6.4408    |
| KNN                | 796.0470     | 976.8796  |

✅ Final Model: **Linear Regression**  
📉 MSE: *0.3845* (Zaman serisi test verisiyle ölçülmüştür)

> Teknik detaylara ve kullanılan kodlara [Notebook dosyasından](./Neslihan-Mustak-MLBootcamp.ipynb) ulaşabilirsiniz.

---



## 🚀 Sonuç ve Gelecek Çalışmalar

Bu proje, geçmiş fiyatlara bakarak oldukça isabetli tahminler yapabileceğimizi göstermektedir. Gelecekte şu gelişmeler planlanabilir:

- 🔮 LSTM, GRU gibi derin öğrenme modelleri ile sekans tahmini yapılması
- 🌐 Gerçek zamanlı veri ile sürekli tahmin
- 📊 Çoklu hisse senedi karşılaştırmalı analiz
- 💡 Kullanıcı arayüzü ile web tabanlı etkileşimli sistem kurulması

---

Kaggle Linki: [Neslihan-Mustak-MLBootcamp](https://www.kaggle.com/code/neslihanmustak/neslihan-mustak-mlbootcampb2917fc441)
**Teşekkürler! 🙌**

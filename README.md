# My First Dummy Experiment 🍭

Bu proje, Kaggle'dan alınan bir tat tercihi veri seti üzerinde temel veri analizi, kategorik veri dönüştürme (encoding) ve makine öğrenmesi modeli (Random Forest Classifier) eğitimi içermektedir. Projenin amacı, Python ile veri bilimi uygulamaları yaparak yetkinlik kazanmaktır.

---

## 🔍 Proje İçeriği

Notebook'ta gerçekleştirilen adımlar:

- Veri setinin Kaggle'dan indirilmesi ve Pandas ile yüklenmesi
- Eksik verilerin analiz edilmesi
- Kategorik verilerin dönüştürülmesi:
  - `LabelEncoder` ile etiketleme
  - `OneHotEncoder` ile dummy değişken oluşturma
  - `ColumnTransformer` ile karma sütunların işlenmesi
- Özelliklerin (`X`) ve hedef değişkenin (`y`) ayrılması
- Eğitim ve test setine ayırma (`train_test_split`)
- **Random Forest Classifier** modeli ile sınıflandırma
- Modelin eğitilmesi ve test verisi üzerinde tahmin yapılması
- Tahmin sonuçlarının orijinal etiketlere dönüştürülmesi (`inverse_transform`)


# Car Price Prediction with Machine Learning

## Makine Öğrenmesi ile Araç Fiyat Tahmini

## 🇹🇷 Türkçe Açıklama

### Proje Amacı

Bu projede araçların teknik özellikleri ve marka bilgileri kullanılarak araç fiyatlarının (MSRP) tahmin edilmesi amaçlanmıştır. 
Çalışma kapsamında makine öğrenmesi yöntemleri kullanılarak yüksek doğrulukta bir regresyon modeli geliştirilmiştir.

---

### Veri Seti

Veri seti aşağıdaki değişkenleri içermektedir:

* Engine HP (Motor Gücü)
* Year (Üretim Yılı)
* Make (Marka)
* Popularity
* Vehicle Size
* Vehicle Style
* City MPG
* Highway MPG

Hedef değişken:

* **MSRP (Araç Fiyatı)**

---

### Uygulanan Yöntemler

* Veri temizleme ve ön işleme
* Eksik değer analizi
* Label Encoding ile kategorik değişken dönüşümü
* Train/Test ayrımı
* Decision Tree Regression modeli
* Random Forest Regression modeli
* R² performans ölçümü
* 5-Fold Cross Validation

---

### Model Performansı

* **Train R²:** ~0.97
* **Test R²:** ~0.96
* **Mean Cross-Validation R²:** ~0.86–0.87

Sonuçlar modelin güçlü genelleme kabiliyetine sahip olduğunu göstermektedir.

---

### Öne Çıkan Bulgular

* Engine HP fiyat üzerinde en etkili değişkendir.
* Üretim yılı ve marka da fiyat tahmininde önemli rol oynamaktadır.
* Model yalnızca tek bir değişkene bağımlı değildir.
* Cross-validation sonuçları modelin istikrarlı olduğunu göstermektedir.

---

### Kullanılan Teknolojiler

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

# 🇬🇧 English Description

### Project Objective

The goal of this project is to predict car prices (MSRP) using vehicle technical specifications and brand information. 
A machine learning regression model was developed to achieve high predictive performance.

---

### Dataset

The dataset includes the following features:

* Engine HP
* Year
* Make
* Popularity
* Vehicle Size
* Vehicle Style
* City MPG
* Highway MPG

Target variable:

* **MSRP (Car Price)**

---

### Methods Applied

* Data cleaning and preprocessing
* Missing value handling
* Label Encoding for categorical variables
* Train/Test split
* Decision Tree Regression
* Random Forest Regression
* R² performance metric
* 5-Fold Cross Validation

---

### Model Performance

* **Train R²:** ~0.97
* **Test R²:** ~0.96
* **Mean Cross-Validation R²:** ~0.86–0.87

These results indicate strong generalization capability and limited overfitting.

---

### Key Findings

* Engine HP is the most influential feature.
* Year and Make significantly contribute to price prediction.
* The model does not rely solely on a single feature.
* Cross-validation confirms model stability.

---


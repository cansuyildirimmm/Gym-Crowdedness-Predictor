# Gym-Crowdedness-Predictor

Machine learning project for predicting campus gym crowdedness using real-world attendance data.  
Gerçek verilerle kampüs spor salonu yoğunluğunu tahmin etmeye yönelik bir makine öğrenmesi projesi.

---

## 📌 Project Overview | Proje Özeti

**EN:**  
This project focuses on analyzing and predicting the crowdedness of a campus gym using machine learning techniques.  
A **Random Forest Regressor** model is trained on real-world gym attendance data to estimate how crowded the gym will be at different times.

The notebook demonstrates an end-to-end machine learning workflow including data preprocessing, model training, evaluation, and interpretation of results.

**TR:**  
Bu proje, makine öğrenmesi yöntemleri kullanarak kampüs spor salonu yoğunluğunu analiz etmeyi ve tahmin etmeyi amaçlamaktadır.  
Gerçek spor salonu kullanım verileri üzerinde **Random Forest Regressor** modeli eğitilerek farklı zamanlardaki yoğunluk seviyesi tahmin edilmiştir.

Notebook, uçtan uca bir makine öğrenmesi sürecini kapsamaktadır.

---

## 📊 Dataset | Veri Seti

- **Source / Kaynak:**  
  Kaggle – *Crowdedness at the Campus Gym*  
  https://www.kaggle.com/datasets/nsrose7224/crowdedness-at-the-campus-gym

**EN:**  
The dataset includes time-based, environmental, and historical attendance features related to gym usage.  
These variables are used to predict gym crowdedness as a regression problem.

**TR:**  
Veri seti; zaman bilgileri, çevresel değişkenler ve geçmiş spor salonu katılım verilerini içermektedir.  
Bu özellikler kullanılarak spor salonu yoğunluğu bir regresyon problemi olarak ele alınmıştır.

---

## 🧪 Notebook Structure | Notebook İçeriği

Main file: **15-RandomForestRegressor.ipynb**

**EN:**  
The notebook includes the following steps:
1. Data loading and inspection  
2. Data cleaning and preprocessing  
3. Feature selection and preparation  
4. Training the Random Forest Regressor  
5. Model evaluation using regression metrics  
6. Interpretation of results

**TR:**  
Notebook aşağıdaki adımları içermektedir:
1. Veri yükleme ve genel inceleme  
2. Veri temizleme ve ön işleme  
3. Özellik seçimi ve hazırlama  
4. Random Forest Regressor modelinin eğitilmesi  
5. Regresyon metrikleri ile değerlendirme  
6. Sonuçların yorumlanması

---

## 🧠 Machine Learning Model | Kullanılan Model

- **RandomForestRegressor**

**EN:**  
An ensemble learning method that builds multiple decision trees and averages their predictions to improve accuracy and reduce overfitting.

**TR:**  
Birden fazla karar ağacı oluşturarak tahminlerin ortalamasını alan, doğruluğu artıran ve aşırı öğrenmeyi azaltan bir topluluk (ensemble) yöntemidir.

---

## 📈 Evaluation Metrics | Değerlendirme Metrikleri

| Metric | Description (EN) | Açıklama (TR) |
|------|------------------|---------------|
| MAE | Mean absolute prediction error | Ortalama mutlak hata |
| RMSE | Penalizes larger errors | Büyük hatalara daha fazla ceza |
| R² | Explained variance score | Modelin açıklayıcılık gücü |

---

## 🚀 Results | Sonuçlar

**EN:**  
The Random Forest model demonstrated strong performance in predicting gym crowdedness based on the evaluation metrics.  
The results indicate that machine learning can effectively model gym usage patterns.

**TR:**  
Random Forest modeli, değerlendirme metriklerine göre spor salonu yoğunluğunu başarılı bir şekilde tahmin etmiştir.  
Sonuçlar, makine öğrenmesinin spor salonu kullanım alışkanlıklarını modellemede etkili olduğunu göstermektedir.

---

## 🛠️ Technologies & Libraries | Kullanılan Teknolojiler

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📂 How to Run | Çalıştırma Adımları

```bash
# Clone the repository
git clone https://github.com/cansuyildirimmm/Gym-Crowdedness-Predictor.git

# Navigate to project folder
cd Gym-Crowdedness-Predictor

# Install required libraries
pip install -r requirements.txt

# Open the notebook
jupyter notebook 15-RandomForestRegressor.ipynb

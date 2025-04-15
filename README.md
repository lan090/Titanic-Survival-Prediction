# 🚢 Titanic Survival Prediction

Proyek ini bertujuan untuk memprediksi kemungkinan seseorang selamat dalam tragedi tenggelamnya kapal Titanic berdasarkan berbagai fitur seperti umur, jenis kelamin, kelas tiket, dan informasi lainnya yang tersedia dalam dataset.

## 📊 Deskripsi Proyek

Notebook ini berisi analisis data dan penerapan machine learning menggunakan dataset Titanic dari [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic). Dataset ini merupakan salah satu dataset paling populer untuk pemula dalam machine learning, karena struktur datanya sederhana namun tetap mengandung tantangan nyata dalam pemrosesan data dan pemodelan.

## 🔧 Teknologi dan Tools yang Digunakan

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib & Seaborn (Visualisasi Data)
- Scikit-learn (Machine Learning)
- Logistic Regression

## 🔍 Alur Analisis

1. **Eksplorasi Data Awal (EDA)**  
   Mengecek nilai-nilai kosong, struktur data, dan memahami distribusi data.

2. **Pembersihan dan Pra-pemrosesan Data**  
   - Menangani missing values
   - Encoding variabel kategorik
   - Feature engineering untuk meningkatkan kualitas input model

3. **Pembangunan Model**  
   - Pemilihan model Logistic Regression
   - Pembagian data train/test
   - Evaluasi akurasi model

4. **Evaluasi Model**  
   Digunakan metrik akurasi serta confusion matrix untuk melihat performa model dalam klasifikasi penumpang yang selamat atau tidak.

## 📌 Hasil Utama

Model Logistic Regression mampu memberikan prediksi dengan akurasi yang cukup baik untuk masalah klasifikasi biner ini. Model dapat digunakan sebagai baseline dan bisa dikembangkan lebih lanjut menggunakan model yang lebih kompleks seperti Random Forest, SVM, atau XGBoost.

## 🚀 Cara Menjalankan Proyek Ini

1. Pastikan sudah memiliki Python dan Jupyter Notebook (bisa install via Anaconda)
2. Clone repositori ini atau download file `.ipynb`-nya
3. Jalankan Jupyter Notebook dan buka file `titanic-survived-predict.ipynb`
4. Ikuti setiap langkah dari EDA hingga evaluasi model

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

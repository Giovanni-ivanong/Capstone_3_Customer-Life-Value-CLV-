# Capstone Project 3  
## Customer Lifetime Value (CLV) Prediction with Machine Learning

---

### 📌 Deskripsi Proyek  
Proyek ini bertujuan memprediksi Customer Lifetime Value (CLV) pelanggan menggunakan algoritma Machine Learning. CLV adalah metrik penting yang menunjukkan total pendapatan yang dapat diperoleh dari seorang pelanggan selama hubungan bisnis. Dengan mengetahui CLV, perusahaan dapat mengoptimalkan strategi pemasaran, retensi pelanggan, dan alokasi anggaran.

Dataset yang digunakan berasal dari data pelanggan perusahaan asuransi mobil, mencakup informasi demografis, polis asuransi, dan riwayat klaim.

---

### 🎯 Tujuan  
- Mengidentifikasi faktor utama yang mempengaruhi CLV.  
- Membangun model prediksi CLV yang akurat menggunakan algoritma Gradient Boosting dan membandingkannya dengan Random Forest.  
- Memberikan rekomendasi strategis untuk meningkatkan profitabilitas jangka panjang perusahaan.

---

### 🗂 Dataset  
Dataset berisi informasi seperti:  
- Customer Lifetime Value  
- Monthly Premium Auto  
- Number of Policies  
- Total Claim Amount  
- Employment Status  
- Education  
- Marital Status  

---

### ⚙️ Metodologi  

#### 1. Data Understanding & Cleaning  
- Pengecekan missing values dan duplikasi data.  
- Analisis distribusi variabel dan deteksi outlier.  

#### 2. Exploratory Data Analysis (EDA)  
- Analisis hubungan antar variabel numerik dan kategorikal.  
- Visualisasi distribusi CLV berdasarkan faktor-faktor tertentu.  

#### 3. Feature Selection & Engineering  
- Pemilihan fitur relevan berdasarkan korelasi dan hasil uji statistik.  

#### 4. Modeling  
- Algoritma yang digunakan:  
  - Gradient Boosting (baseline & tuning)  
  - Random Forest (baseline)  
- Hyperparameter tuning menggunakan RandomizedSearchCV dan GridSearchCV.  

#### 5. Evaluation  
- Metrik evaluasi: RMSE, MAE, MAPE  
- Analisis residual plot untuk mendeteksi bias model.  

---

### Cara Menjalankan  
1. Pastikan Python 3.x dan library berikut sudah terinstall:  
   `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`  
2. Jalankan skrip preprocessing, modeling, dan evaluasi yang sudah disediakan.  
3. Lihat hasil evaluasi model dan visualisasi untuk analisis lebih lanjut.

---

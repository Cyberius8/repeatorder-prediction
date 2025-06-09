# 🔁 Prediksi Repeat Order Pelanggan E-Commerce

Proyek ini bertujuan untuk membangun model prediksi repeat order pelanggan menggunakan algoritma machine learning berbasis data transaksi historis, serta menyajikan visualisasi segmentasi pelanggan untuk mendukung strategi retensi dan pemasaran.

---

## 🧠 Latar Belakang

Dalam industri e-commerce yang sangat kompetitif, mempertahankan pelanggan jauh lebih hemat biaya dibandingkan mencari pelanggan baru. Menurut McKinsey (2024), biaya akuisisi pelanggan baru bisa 5–7 kali lebih mahal dibanding retensi pelanggan lama. Dengan memanfaatkan data perilaku transaksi, perusahaan dapat memprediksi kemungkinan pelanggan melakukan repeat order dan menyusun strategi yang lebih tepat sasaran.

---

## 🎯 Tujuan Proyek

- Memprediksi kemungkinan repeat order pelanggan berdasarkan data historis.
- Mengarahkan strategi promosi ke pelanggan dengan potensi repeat tinggi.
- Meningkatkan Customer Lifetime Value (CLTV) dan efisiensi anggaran marketing.

---

## 🛠️ Tools & Teknologi

- Python (pandas, scikit-learn, seaborn, matplotlib)
- Jupyter Notebook / Google Colab
- Tableau / Power BI (visualisasi dashboard)
- Excel / Google Sheets (eksplorasi awal)

---

## 🗃️ Struktur Folder

```
project/
│
├── data/                    # Data mentah dan hasil preprocessing
│   ├── olist.csv
│   ├── repeat_order_labels.csv
│   └── rfm_features_train.csv
│
├── notebooks/               # Notebook eksplorasi, modeling, visualisasi
│   ├── 01_EDA_and_Cleaning.ipynb
│   ├── 02_Label.ipynb
│   ├── 03_RFM_Fix.ipynb
│   └── 04_Modeling_Fix.ipynb
│
├── dashboards/              # File Tableau / Power BI
│
├── models/                  # (Opsional) Model pickle/joblib
│
├── outputs/                 # Hasil prediksi dan metrik model
│
└── README.md                # Deskripsi proyek ini
```

---

## 🧪 Model yang Digunakan

| Model               | Keterangan                   |
| ------------------- | ---------------------------- |
| XGBoost             | Model utama terbaik          |
| Random Forest       | Model pembanding kuat        |
| Logistic Regression | Model baseline interpretable |

Evaluasi dilakukan menggunakan:

- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix
- Feature Importance (Random Forest & XGBoost)

---

## 📊 Visualisasi Dashboard

Dashboard interaktif mencakup:

- Dashboard segmentasi dan prediksi pelanggan mencakup:
  - Proporsi repeat vs non-repeat
  - Distribusi RFM dan skor prediksi
  - Target pelanggan prioritas untuk kampanye

---

## 📁 Dataset

Brazilian E-Commerce Public Dataset by Olist
🔗 [https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## ✅ Status Proyek

- [x] EDA & Pembersihan Data
- [x] Modeling Machine Learning
- [x] Evaluasi Model
- [ ] Visualisasi & Insight Bisnis (dalam proses)
- [ ] Dashboard Interaktif (dalam proses)

---

## 👤 Author

Nama: _Gede Darmawan_  
Portfolio: *https://www.linkedin.com/in/darma1/*

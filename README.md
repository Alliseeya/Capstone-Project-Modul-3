# Capstone Project: Uji Regresi Machine Learning untuk Prediksi Customer Lifetime Value (CLV)

## 📌 Overview

Proyek ini merupakan implementasi model Machine Learning untuk memprediksi Customer Lifetime Value (CLV) berdasarkan dataset historis pelanggan. Pemodelan dilakukan menggunakan beberapa teknik regresi seperti Gradient Boosting, Stacking, Voting, dan Feature Selection untuk mengoptimalkan akurasi prediksi.

## 🎯 Objective

Tujuan utama dari proyek ini adalah:

1. Mengoptimalkan prediksi CLV menggunakan model Gradient Boosting dengan teknik hyperparameter tuning.
2. Meningkatkan akurasi dan robustness prediksi dibanding metode konvensional.
3. Mengidentifikasi fitur paling berpengaruh dalam perhitungan CLV.

## 📂 Dataset Description

Dataset yang digunakan berisi informasi historis pelanggan, transaksi, dan perilaku pembelian. Beberapa fitur utama yang dianalisis meliputi:

* `Customer ID`: ID unik pelanggan.
* `Recency`: Waktu sejak transaksi terakhir.
* `Frequency`: Jumlah transaksi dalam periode tertentu.
* `Monetary`: Total nilai transaksi.
* `CLV`: Target prediksi nilai seumur hidup pelanggan.

## 🛠️ Modeling Techniques

Model yang digunakan dalam analisis ini meliputi:

1. **Gradient Boosting** - Model berbasis boosting untuk meningkatkan akurasi prediksi.
2. **Stacking Regressor** - Kombinasi beberapa model untuk mengurangi bias dan varians.
3. **Voting Regressor** - Menggabungkan hasil prediksi beberapa model regresi.
4. **Feature Selection** - Memilih fitur-fitur terbaik untuk optimasi model.

## 📏 Evaluation Metrics

Model dievaluasi menggunakan beberapa metrik berikut:

* **R² Score**: Mengukur seberapa baik prediksi mengikuti nilai aktual.
* **Mean Absolute Error (MAE)**: Mengukur rata-rata selisih absolut antara prediksi dan nilai aktual.

## 🚀 Results

Hasil evaluasi menunjukkan bahwa model Gradient Boosting memiliki performa terbaik dengan R² tertinggi dan MAE terendah, diikuti oleh Stacking dan Voting. Penggunaan Feature Selection juga terbukti mampu meningkatkan akurasi prediksi.

## ⚙️ How to Run

1. Clone repository:

   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan notebook:

   ```bash
   jupyter notebook Capstone_Modul_3_Uji_Regresi_ML_CLV.ipynb
   ```

## 📌 Dependencies

* Python 3.8+
* scikit-learn
* pandas
* numpy
* matplotlib
* seaborn

## 👥 Contributors

* Alisya Ramadhani Fatin

## 📜 License

Proyek ini berlisensi di bawah [MIT License](LICENSE).

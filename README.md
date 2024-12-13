# README - Ujian Akhir Semester Ganjil 2023

## Program Studi Sarjana Teknologi Informasi

### Mata Kuliah: Big Data dan Analitik (TIF522)
**Dosen:** Silmi Fauziati  
**Sifat:** Takehome  
**Batas Pengumpulan:** 13 Desember 2024, pukul 23.00 WIB  
**Tempat Pengumpulan:** eLOK Big Data dan Analitik bagian UAS 2023  

---

## Deskripsi

Folder ini berisi jawaban Ujian Akhir Semester untuk mata kuliah **Big Data dan Analitik**. Setiap jawaban telah dikerjakan berdasarkan soal yang diberikan dengan pendekatan analitik, prediktif, dan eksplorasi data yang mendalam. Berikut adalah rincian setiap nomor soal dan pendekatan yang digunakan:

---

## Struktur Jawaban

### **Nomor 1: Time Series Forecasting**
- **Data:** [Tabel VII.1 PDB](https://www.bi.go.id/SEKI/tabel/TABEL7_1.xls) dari Bank Indonesia.
- **Pendekatan:**
  - Prediktif analitik dengan metode time series forecasting (model SARIMA).
  - Analisis dekomposisi untuk tren, siklus, dan musiman.
  - Uji stasioneritas, analisis ACF dan PACF, serta evaluasi performa (MAPE, RMSE, dll).
- **Hasil:**
  - Prediksi PDB hingga tahun 2030 dengan akurasi MAPE sebesar 9.76%.
  - Visualisasi tren, komponen musiman, dan perbandingan prediksi dengan data asli.

---

### **Nomor 2: Data Mining Classification (Neural Network)**
- **Data:** Dataset karyawan (terlampir).
- **Pendekatan:**
  - Neural Network dengan preprocessing (normalisasi, encoding fitur kategorikal, dan handling multikolinieritas).
  - Struktur model dengan 2 hidden layers, dropout, dan optimasi menggunakan Adam.
  - Evaluasi performa (akurasi, precision, recall, F1-score).
- **Hasil:**
  - Akurasi model mencapai 90%.
  - Faktor penting: pengembangan karier, gaji, dan lama bekerja.

---

### **Nomor 3: Data Mining Classification (Decision Tree)**
- **Data:** [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).
- **Pendekatan:**
  - Eksplorasi data (EDA), handling outlier, dan balancing data menggunakan SMOTE.
  - Decision Tree dengan optimasi hyperparameter (GridSearchCV).
  - Evaluasi dengan K-Fold Cross Validation.
- **Hasil:**
  - Akurasi keseluruhan 88.17%, precision dan recall 0.88.
  - Fitur penting: kadar glukosa, BMI, dan usia.

---

### **Nomor 4: Clustering Data Perilaku Peminjaman**
- **Data:** [Dataset Peminjaman](https://www.kaggle.com/datasets/zaurbegiev/my-dataset/data).
- **Pendekatan:**
  - Preprocessing data (handling outliers, normalisasi, dan reduksi dimensi dengan PCA).
  - Clustering menggunakan K-Means dan evaluasi dengan Silhouette Score.
- **Hasil:**
  - Cluster yang merepresentasikan perilaku peminjam (5 cluster).
  - Silhouette Score sebesar 0.324.

---

### **Nomor 5: Association Rule Mining**
- **Data:** [Online Retail Dataset](https://www.kaggle.com/datasets/ishanshrivastava28/tata-online-retail-dataset?select=Online+Retail+Data+Set.csv).
- **Pendekatan:**
  - Closed Patterns dan Maximal Closed Patterns menggunakan algoritma Apriori/FPGrowth.
  - Analisis pola pembelian dan kombinasi produk.
- **Hasil:**
  - Temuan pola tunggal (misal: Alarm Clock Bakelike Red dengan support 4.17%).
  - Kombinasi produk (misal: Jumbo Bag Red Retrospot dengan Pink Polkadot).

---

### **Nomor 6: Analisis Relasi Panen dengan Musim**
- **Data:** Data harga saham PT Astra Agro Lestari Tbk (Yahoo Finance).
- **Pendekatan:**
  - Analisis musiman, uji statistik (T-test), dan regresi linear.
  - Visualisasi boxplot, grafik musiman, dan dekomposisi data.
- **Hasil:**
  - Tidak ada perbedaan signifikan antara musim hujan dan kemarau.
  - Nilai R-squared sangat rendah (0.0026), menunjukkan musim bukan faktor utama.

---

## Catatan Penting
- Data yang digunakan berbeda sesuai ketentuan soal.
- Semua langkah dan metode yang digunakan telah dijelaskan secara rinci dalam laporan masing-masing soal.
- Jika ada pertanyaan, hubungi melalui eLOK bagian UAS 2023.

---

**Selamat Mengerjakan dan Semoga Sukses!**

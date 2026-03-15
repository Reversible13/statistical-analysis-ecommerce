# Statistical Analysis of E-Commerce Data

## 📊 Ringkasan Proyek
Repositori ini berisi analisis statistika mendalam terhadap data transaksi e-commerce. Fokus utama proyek ini adalah menerapkan uji hipotesis dan pemodelan prediktif untuk mengevaluasi perilaku konsumen dan struktur biaya logistik.

## 🧪 Metodologi Statistika yang Diterapkan

### 1. Deteksi Outlier (Analisis Sebaran)
Menggunakan metode **Interquartile Range (IQR)** untuk mengidentifikasi data ekstrem pada variabel pembayaran dan berat. Langkah ini krusial untuk memastikan bahwa nilai rata-rata (*mean*) tidak terdistorsi oleh data yang tidak wajar.

### 2. Uji Hipotesis (Independent T-Test)
Melakukan pengujian perbedaan rata-rata antara dua kelompok independen (Metode Pembayaran ShopeePay vs COD).
- **Tujuan:** Menentukan apakah perbedaan total belanja antar metode pembayaran bersifat signifikan secara statistik atau hanya kebetulan.
- **Teknik:** Welch's T-Test (untuk varians yang tidak sama).

### 3. Analisis Regresi Linear (Korelasi & Prediksi)
Membangun model korelasi antara berat barang dan ongkos kirim.
- **Coefficient Analysis:** Menghitung biaya marginal setiap penambahan berat barang.
- **R-Squared:** Mengevaluasi seberapa kuat variabel berat mampu menjelaskan variasi pada ongkos kirim.

### 4. Analisis Efisiensi Logistik
Menerapkan teknik *feature engineering* untuk menghitung biaya per gram, memungkinkan perbandingan performa antar kurir secara objektif melalui standarisasi nilai.

## 📉 Visualisasi Utama
- **Box Plot:** Untuk membandingkan distribusi dan mendeteksi outlier secara visual.
- **Regression Plot:** Untuk memetakan hubungan linear antar variabel numerik.
- **Correlation Heatmap:** Untuk melihat keterkaitan antar seluruh variabel dalam dataset.

## 🛠️ Stack Teknologi
- Python (Pandas, NumPy, Scipy.Stats, Scikit-Learn)
- Matplotlib & Seaborn (Data Visualization)

## 👥 Tim Analis
- **Muhammad Maulana Rosyid** - Lead Analyst
- **Rifat Qoyyim Sidik** - Data Researcher
- **Kelompok 1 - Universitas Terbuka (UT)**

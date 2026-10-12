# Walmart Weekly Sales Analysis

Repositori ini berisi proyek analisis data (Data Analysis) menggunakan dataset penjualan mingguan toko Walmart (`Walmart.csv`). Proyek ini mencakup proses eksplorasi data, pembersihan data, penanganan nilai kosong (*missing values*), deteksi pencilan (*outliers*), dan standarisasi fitur numerik.

## 📁 Struktur Proyek
- `Walmart.csv`: Dataset utama yang digunakan untuk analisis.
- Jupyter Notebook / skrip Python yang berisi tahapan:
  1. **Data Loading & Inspection**: Memuat data menggunakan Pandas serta memeriksa informasi dasar dan statistik deskriptif.
  2. **Data Cleaning**: Menangani *missing values* pada fitur numerik dan kategorikal.
  3. **Outlier Detection**: Menggunakan metode *Interquartile Range* (IQR) dan visualisasi *box plot*.
  4. **Feature Scaling**: Melakukan standarisasi pada fitur numerik menggunakan `StandardScaler`.
  5. **Data Duplication Check**: Memeriksa dan membersihkan baris data yang duplikat.

## 🛠️ Teknologi & Pustaka yang Digunakan
- **Python**
- **Pandas** (Manipulasi dan analisis data)
- **NumPy** (Operasi numerik)
- **Matplotlib & Seaborn** (Visualisasi data dan pembuatan grafik statistik)
- **Scikit-Learn** (Preprocessing / Data Scaling)

## 📊 Tahapan Analisis
1. Membaca dataset dan menampilkan ringkasan informasi struktur kolom.
2. Melakukan analisis statistik deskriptif untuk melihat distribusi data (*count, mean, std, min, max*).
3. Mengisi nilai kosong (*missing values*) menggunakan nilai median untuk data numerik dan *modus* untuk data kategorikal.
4. Membuat visualisasi *box plot* dan mendeteksi anomali/pencilan pada data.
5. Melakukan standarisasi data agar memiliki rata-rata 0 dan deviasi standar 1 guna keperluan pemodelan lebih lanjut.

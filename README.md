## Pemanfaatan Decision Tree pada Algoritma Random Forest untuk Klasifikasi Kanker Payudara

Makalah ini membahas penggunaan **Decision Tree** sebagai komponen utama dalam algoritma **Random Forest** untuk melakukan klasifikasi pada dataset kanker payudara. Algoritma ini digunakan untuk meningkatkan akurasi prediksi dengan memanfaatkan keunggulan ensemble learning.

## Penulis

- **Adhimas Aryo Bimo**  
  NIM: 13523052  
  Program Studi Teknik Informatika  
  Sekolah Teknik Elektro dan Informatika, Institut Teknologi Bandung  

## Abstrak

Dalam penelitian ini, Random Forest diterapkan untuk klasifikasi dataset kanker payudara menggunakan pendekatan berikut:
1. **Pembuatan Decision Tree secara Individual**  

Dataset awal memiliki **569 data dengan 30 fitur numerik**, yang diproses menggunakan algoritma Random Forest. Hasil percobaan menunjukkan:
- **Akurasi klasifikasi mencapai 91% pada Decision Tree dan 95% pada Random Forest.**
- **Random Forest mampu menurunkan kesalahan hingga 50%.**

## Pustaka yang Digunakan

- **Python 3.12**  
- **Pustaka Python**:
  - Pandas
  - Matplotlib
  - Scikit-learn
  - NumPy

## Cara Menjalankan Kode

1. Clone repository ini:
   ```bash
   git clone https://github.com/ryonlunar/random-forest-breast-cancer.git
   cd random-forest-breast-cancer

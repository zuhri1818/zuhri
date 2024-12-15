# Proyek Analisis Data E-Commerce

Proyek ini bertujuan untuk menganalisis data transaksi e-commerce untuk mendapatkan wawasan tentang produk, pelanggan, dan lokasi yang paling banyak bertransaksi. Analisis dilakukan menggunakan dataset **ecommerce_data.csv** yang mencakup informasi transaksi pembelian produk secara online.

## Tujuan Proyek
1. Menjawab pertanyaan bisnis mengenai produk paling laris.
2. Menentukan kota dengan transaksi terbanyak.
3. Membuat visualisasi untuk memperjelas temuan-temuan yang ada.
4. Melakukan analisis tambahan menggunakan metode RFM (Recency, Frequency, Monetary) untuk mendalami pola perilaku pelanggan.

## Struktur Direktori
submission/ ├───dashboard/ │ ├───main_data.csv │ └───dashboard.py ├───data/ │ ├───ecommerce_data.csv ├───notebook.ipynb ├───README.md └───requirements.txt └───url.txt

## Penjelasan Berkas

1. **ecommerce_data.csv**:
   - Berisi data transaksi e-commerce yang mencakup informasi ID transaksi, ID produk, kategori produk, jumlah yang dibeli, harga, tanggal transaksi, dan lokasi pelanggan.

2. **notebook.ipynb**:
   - Notebook Jupyter yang berisi analisis data menggunakan Pandas, Matplotlib, dan Seaborn. Berisi proses dari eksplorasi data, analisis, hingga visualisasi.

3. **dashboard.py**:
   - Berkas Python untuk membuat aplikasi dashboard interaktif menggunakan Streamlit. Dashboard ini memungkinkan pengguna untuk mengeksplorasi data secara lebih mendalam.

4. **requirements.txt**:
   - Berisi daftar library yang diperlukan untuk menjalankan proyek ini. Pastikan Anda menginstal library yang terdaftar dengan menjalankan `pip install -r requirements.txt`.

5. **url.txt**:
   - Berisi URL yang mengarah ke aplikasi dashboard yang telah dideploy menggunakan Streamlit.

## Cara Menjalankan Dashboard

1. Install library yang diperlukan dengan menjalankan perintah berikut:
   ```bash
   pip install -r requirements.txt
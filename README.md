# Praktikum-Data-Mining
# TUGAS PRAKTIKUM - DATA MINING


Analisis Data Mining : Visualisasi Tren GDP Per Kapita Global (Dalam Satuan USD) Menggunakan Apache Spark dan Dashboard Interaktif
# 1. Pendahuluan

## A. Latar Belakang & Tujuan
Tugas ini bertujuan untuk menerapkan pipeline analisis Data Mining secara end-to-end. Kami menggunakan dataset GDP per kapita global (~200MB) untuk mensimulasikan karakteristik Data Mining, khususnya pada aspek **Volume, Variety, dan Value**.

## B. Apa yang Akan Dilakukan?
Kami akan memproses data menggunakan **Apache Spark** di Google Colab untuk melakukan pembersihan dan analisis data ekonomi skala besar. Hasil akhir dari proyek ini adalah sebuah laporan ilmiah dan **Dashboard Analitik** berbasis Python.

# 2. Metodologi

Metodologi penelitian ini mengikuti standar pipeline Data Mining
1. **Data Ingestion**: Mengunduh dataset 200MB dari Google Drive menggunakan library `gdown`
2. **Data Preprocessing**: Membersihkan data menggunakan **PySpark** untuk menangani nilai kosong dan konversi tipe data numerik
3. **Advanced Analysis**: Melakukan agregasi data untuk menemukan tren GDP antar negara menggunakan Google Colab
4. **Visualization & Dashboard**: Menyajikan hasil dalam bentuk grafik dan membangun dashboard interaktif (Streamlit/Dash)

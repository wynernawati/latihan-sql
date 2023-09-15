
# Latihan SQL Menggunakan Jupyter Notebook
Ini adalah panduan latihan SQL menggunakan bahasa pemrograman Python dengan data penjualan sebagai studi kasus. Dalam panduan ini, Anda akan belajar cara mengakses dan mengolah data penjualan menggunakan bahasa SQL melalui Python. 
# Persiapan Awal
Sebelum mulai, pastikan Anda memiliki lingkungan Python yang terinstal dan telah menginstal library sqlite3 untuk mengakses database SQLite. Jika belum, Anda dapat menginstalnya dengan perintah berikut:
```
pip install sqlite3
```
# Membuat Koneksi Database
Untuk berinteraksi dengan database SQLite menggunakan Python, Anda perlu membuat koneksi terlebih dahulu. Berikut adalah contoh cara melakukannya:
```
import sqlite3

# Membuat koneksi ke database
conn = sqlite3.connect('data_penjualan.db')

# Membuat objek cursor untuk menjalankan perintah SQL
cursor = conn.cursor()
```
# Melakukan Query SQL
Sekarang Anda dapat menjalankan query SQL pada database penjualan. 
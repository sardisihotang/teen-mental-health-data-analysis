# Teen Mental Health Data Analysis

Tentang Project
Project ini merupakan salah satu latihan analisis data yang saya kerjakan
saat mengikuti pelatihan Data Analyst dari Lembaga Sertifikasi Profesi (LSP)
yang disediakan oleh Universitas Gunadarma pada semester 8.

Pada project ini, saya mencoba mengolah dataset mengenai kesehatan mental
remaja dan penggunaan media sosial. Proses yang saya lakukan mulai dari
memahami data, melakukan data cleaning, menganalisis data, hingga membuat
dashboard untuk menampilkan hasil analisis.

Project ini saya kerjakan sebagai bagian dari proses belajar dan
mengembangkan kemampuan saya di bidang Data Analysis.

# Tujuan Analisis
Tujuan dari analisis ini adalah untuk memahami gambaran penggunaan media
sosial pada remaja serta melihat bagaimana beberapa faktor seperti waktu
tidur, tingkat stres, kecemasan, dan aktivitas sehari-hari berhubungan
dengan label depresi yang terdapat pada dataset.

Melalui analisis ini, saya ingin mencoba menemukan pola yang dapat menjadi
bahan pemahaman awal mengenai kebiasaan digital dan kondisi remaja.

# Tools yang Digunakan
- Microsoft Excel — untuk melihat struktur data dan melakukan pemeriksaan awal.
- Google Colab — untuk proses data cleaning dan analisis menggunakan Python.
- Google Looker Studio — untuk membuat dashboard dan visualisasi data.

# Dataset
Dataset yang digunakan terdiri dari dua versi:

- `Teen_Mental_Health_Dataset.csv` — dataset awal sebelum proses cleaning.
- `Teen_Mental_Health_Cleaned.csv` — dataset setelah proses cleaning.

Dataset berisi informasi mengenai usia, gender, penggunaan media sosial,
waktu tidur, aktivitas fisik, tingkat stres, kecemasan, dan beberapa
indikator lainnya.

# Data Cleaning
Sebelum melakukan analisis, saya melakukan pemeriksaan dan persiapan data
agar data lebih mudah digunakan untuk proses analisis.

Beberapa langkah yang dilakukan:
1. Memeriksa jumlah baris dan kolom pada dataset.
2. Memeriksa tipe data dan nilai pada setiap kolom.
3. Mengecek missing values dan nilai kosong.
4. Memeriksa data duplikat.
5. Memeriksa nilai yang tidak sesuai dengan rentang atau konteks data.
6. Menyiapkan dataset hasil cleaning untuk digunakan dalam analisis dan
   visualisasi.

# Hasil Pemeriksaan Data
| Pemeriksaan    | Dataset Awal | Dataset Cleaned |
|----------------|--------------|-----------------|
| Jumlah baris   | 1.200        | 1.174           |
| Jumlah kolom   | 13           | 13              |
| Missing values | 9            | 1               |
| Baris duplikat identik        | 15              |

Pada dataset awal, ditemukan beberapa missing values, nilai kosong,
dan baris duplikat. Setelah proses cleaning, jumlah data menjadi
1.174 baris dan tidak ditemukan baris duplikat identik.

Saya juga melakukan pengecekan nilai pada kolom usia. Pada dataset awal
terdapat nilai usia yang cukup jauh dari rentang usia remaja, sehingga
perlu diperhatikan dalam proses persiapan data.

# Exploratory Data Analysis (EDA)
Setelah data dipersiapkan, saya melakukan analisis deskriptif untuk
melihat gambaran data dan membandingkan beberapa indikator.

Beberapa hal yang saya analisis antara lain:
- Distribusi usia dan gender.
- Penggunaan media sosial berdasarkan platform.
- Rata-rata waktu tidur.
- Tingkat stres dan kecemasan.
- Perbandingan beberapa indikator berdasarkan depression label.

Saya menggunakan perhitungan seperti jumlah data, rata-rata, dan
perbandingan antar kelompok untuk membantu memahami pola yang ada.

# Insight yang Didapat
Dari hasil analisis awal pada dataset cleaned, terdapat beberapa
temuan menarik:

1. Record dengan `depression_label = 1` memiliki rata-rata penggunaan
   media sosial sekitar 6,72 jam per hari, sedangkan kelompok
   `depression_label = 0` sekitar 4,47 jam.

2. Rata-rata waktu tidur pada kelompok `depression_label = 1` sekitar
   4,76 jam, sedangkan kelompok `depression_label = 0` sekitar 6,48 jam.

3. Rata-rata tingkat stres dan kecemasan pada kelompok
   `depression_label = 1` lebih tinggi dibandingkan kelompok
   `depression_label = 0`.

Dari hasil tersebut, saya melihat bahwa penggunaan media sosial,
waktu tidur, stres, dan kecemasan merupakan beberapa faktor yang
menarik untuk dipelajari lebih lanjut dalam dataset ini.

Namun, hasil ini hanya menunjukkan pola pada data yang dianalisis.
Saya tidak menyimpulkan bahwa penggunaan media sosial secara langsung
menyebabkan depresi.

# Dashboard
Hasil analisis saya visualisasikan menggunakan Google Looker Studio
agar informasi lebih mudah dipahami melalui grafik dan dashboard.

Dashboard:
https://datastudio.google.com/reporting/49887cd1-abb3-402b-8010-83d7c43ddf8a

# Google Colab
Notebook yang digunakan untuk proses data cleaning dan analisis:
https://colab.research.google.com/drive/1EdD2EAChSBEUgaX0_OYhkCcXdS-wj-Tx?usp=sharing

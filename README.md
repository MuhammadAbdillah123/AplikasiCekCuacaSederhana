# AplikasiCekCuacaSederhana

Aplikasi Cek Cuaca adalah sebuah aplikasi berbasis Java yang menggunakan API dari OpenWeatherMap untuk menampilkan informasi cuaca terkini berdasarkan nama kota. Aplikasi ini dilengkapi dengan antarmuka berbasis GUI menggunakan Java Swing, sehingga mudah digunakan.

## Keunggulan Aplikasi

1.*Mendapatkan Informasi Cuaca Terkini*
Menampilkan informasi cuaca seperti deskripsi cuaca, suhu dalam derajat Celsius, dan ikon cuaca berdasarkan data dari OpenWeatherMap.

2.*Penyimpanan dan Pemulihan Data Cuaca*
-*Data cuaca yang telah dicari dapat disimpan dalam format CSV untuk kebutuhan di masa depan.*
-*Pengguna juga dapat memuat kembali data yang telah disimpan sebelumnya.*

3.*Antarmuka Pengguna yang Sederhana dan Intuitif*
Antarmuka aplikasi dirancang agar mudah digunakan oleh siapa saja, dengan fitur dropdown untuk memilih kota, input teks untuk pencarian kota, dan tabel untuk menampilkan hasil cuaca.

4.*Ikon Cuaca Dinamis*
Ikon cuaca ditampilkan bersama dengan deskripsi cuaca untuk memberikan pengalaman visual yang menarik.

5.*Multifungsi dan Responsif*
-*Pencarian cuaca cepat dengan memanfaatkan API HTTP.*
-*Hasil pencarian langsung ditambahkan ke tabel riwayat.*
-*Dukungan untuk menambahkan kota baru ke dalam daftar kota pilihan.*

## Pembuat Aplikasi

 Tugas 6 - Muhammad Abdillah (2210010152)

 ## Fitur

1.*Pencarian Cuaca Berdasarkan Nama Kota*
Pengguna dapat mengetikkan nama kota untuk mendapatkan informasi cuaca terkini.
2.*Tabel Data Cuaca*
Semua hasil pencarian disimpan dalam tabel dengan kolom:
-*Nama Kota*
-*Deskripsi Cuaca*
-*Suhu (°C)*
3.*Penyimpanan dan Pemulihan Data*
-*Data dapat disimpan ke file data_cuaca.csv.*
-*Data yang telah disimpan dapat dimuat kembali ke tabel.*
4.*Antarmuka Visual*
-*Menampilkan ikon cuaca berdasarkan data API.*
-*Tabel riwayat cuaca untuk menyimpan data secara terorganisasi.*

## Cara Menjalankan Aplikasi

1.*Persiapan Lingkungan*
-*Pastikan Anda memiliki JDK (Java Development Kit) yang terinstal di komputer Anda.*
-*Pastikan Anda memiliki koneksi internet yang aktif untuk mengakses API OpenWeatherMap.-
2.*Langkah-Langkah*
-*Unduh atau clone repositori proyek ini.*
-*Buka proyek di IDE seperti NetBeans atau IntelliJ IDEA.*
-*Kompilasi dan jalankan file utama: Tugas6.java.*
3.*Penggunaan API Key OpenWeatherMap*
-*Pastikan Anda memiliki API Key dari OpenWeatherMap.*
-*Ganti nilai apiKey pada fungsi getWeather() dengan API Key Anda.*
4.*Fitur Penyimpanan dan Pemulihan*
-*Klik tombol "Simpan" untuk menyimpan data cuaca ke dalam file CSV.*
-*Klik tombol "Muat Data Cuaca" untuk memuat data dari file CSV ke tabel.*

## Library yang Digunakan

-*Swing: Untuk antarmuka grafis aplikasi.*
-*Java I/O: Untuk membaca dan menulis file CSV.*
-*HttpURLConnection: Untuk berkomunikasi dengan API OpenWeatherMap.*
-*JSON: Untuk parsing data yang diterima dari API.*

## Demo

![Screen Recording 2024-11-16 201136](https://github.com/user-attachments/assets/b233d53f-0f9b-4ca1-a7d8-72aee3f224bf)


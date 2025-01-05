# Aplikasi Pemesanan Tiket Kereta
# Deskripsi
Aplikasi Pemesanan Tiket Kereta adalah aplikasi desktop berbasis Java yang dirancang untuk:
- Memfasilitasi pengguna mencari jadwal tiket kereta, memesan tiket, dan mencetak tiket mereka.
- Memungkinkan admin mengelola data pengguna, jadwal kereta, serta data transaksi.
Aplikasi ini dibangun dengan konsep CRUD (Create, Read, Update, Delete) menggunakan MySQL sebagai database dan framework Swing/AWT untuk antarmuka pengguna.
# Fitur Utama
- Fitur User
1. Login dan Register
    - Pengguna baru dapat mendaftar akun.
    - Pengguna yang telah terdaftar dapat login untuk mengakses fitur.
2. Dashboard User
    - Mencari Jadwal Kereta: Masukkan nama kereta untuk mencari jadwal.
    - Booking Tiket: Memilih kereta, dan melakukan transaksi pemesanan.
    - Cetak Tiket: Pengguna dapat mencetak tiket mereka setelah berhasil memesan.
- Fitur Admin
1. Login Admin
    - Admin dapat login ke panel admin untuk mengelola data.
2. Dashboard Admin
    - Kelola Data User: Tambah, lihat, ubah, atau hapus data pengguna.
    - Kelola Jadwal Kereta: Tambah, lihat, ubah, atau hapus jadwal kereta.
    - Kelola Data Transaksi: Melihat atau mencetak laporan transaksi pengguna.
# Teknologi yang Digunakan
- Bahasa Pemrograman: Java
- Framework: Swing/AWT untuk UI
- Database: MySQL
# Cara Instalasi dan Penggunaan
- Prasyarat
  - Java Development Kit (JDK) versi 8 atau lebih baru.
  - IDE NetBeans 8.2.
- Langkah Instalasi
  - Pastikan Folder project di simpan di direktori D agar meminimalisir eror dan sinkroniasi lokasi file, jika tidak memiliki direktori D harus mengubah path di dalam kode untuk mencocokkan lokasi file yang sesuai dengan direktori yang ada di komputer kalian
    ```sh
    D:\SEMESTER 3\PRAK-BP1\PROJECT_BP1_ADEW
    ```
  - Langkah impor database ke MySQL:
    - Buat database baru dengan nama db_tiketkereta
    - Impor file db_tiketkereta.sql ke database yang baru dibuat menggunakan MySQL (dapat diambil di: )
      ```sh
      D:\SEMESTER 3\PRAK-BP1\DATABASE\db_tiketkereta.sql
      ```
  - Tambahkan library ke proyek di NetBeans:
    - Klik kanan pada proyek Anda di Projects.
    - Pilih Properties > Libraries.
    - Klik tombol Add JAR/Folder, Library dapat di akses/di ambil di
      ```sh
      D:\SEMESTER 3\PRAK-BP1\PLUGIN & LIBRARY\LIBRARY
      ```
  - Penggunaan
    - Jalankan aplikasi melalui NetBeans
    - Klik kanan file login.java/register.java yang ada pada package home (silahkan cek didatabase untuk akun admin)
    - Silahkan nikmati fitur yang tersedia
  # Contact
  Hubungi saya di adewahyuwrpdn@gmail.com jika mengalami eror dan memiliki saran lebih lanjut untuk pengembangan aplikasi ini

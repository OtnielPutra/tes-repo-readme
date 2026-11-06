<p align="center">
██████╗░██████╗░██╗░██████╗███╗░░░███╗░█████╗░
██╔══██╗██╔══██╗██║██╔════╝████╗░████║██╔══██╗
██████╔╝██████╔╝██║╚█████╗░██╔████╔██║███████║
██╔═══╝░██╔══██╗██║░╚═══██╗██║╚██╔╝██║██╔══██║
██║░░░░░██║░░██║██║██████╔╝██║░╚═╝░██║██║░░██║
╚═╝░░░░░╚═╝░░╚═╝╚═╝╚═════╝░╚═╝░░░░░╚═╝╚═╝░░╚═╝
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache_NetBeans-1B6AC6?style=for-the-badge&logo=apachenetbeans&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Laragon-0E9E59?style=for-the-badge&logo=laragon&logoColor=white"/>
  <img src="https://img.shields.io/badge/phpMyAdmin-F89C0E?style=for-the-badge&logo=phpmyadmin&logoColor=white"/>
</p>

----

# KELOMPOK 15 CAPSTONE
| No | Nama | NIM |
|:---:|:---|:---:|
| 1 | Aulia Sheva Savitri | 2509116001 |
| 2 | Muhammad Yusri Jibran Sugiharta Jusuf | 2509116030 |
| 3 | Jihan Shafira Rahmah| 2509116073 |
| 4 | Otniel Putra Wardana | 2509116081 |

</div>

----

<h1 align="center">
  <b>SISTEM INFORMASI MANAJEMEN KONTEN DAN JADWAL TAYANG PRISMA</b>
</h1>


## 1. Deskripsi Singkat

PrismaTV merupakan aplikasi desktop berbasis Java yang dikembangkan menggunakan Java Swing untuk membantu pengelolaan konten dan jadwal penayangan program televisi. Aplikasi ini menyediakan berbagai fitur pengelolaan data, meliputi konten siaran, program TV, kanal televisi, jadwal tayang, mitra, kerja sama, lampiran konten, serta publikasi konten.

Aplikasi menyediakan tiga jenis hak akses, yaitu Admin, Petugas Jadwal, dan Petugas Konten. Admin memiliki akses untuk mengelola akun dan keseluruhan data aplikasi, Petugas Jadwal bertanggung jawab terhadap pengelolaan jadwal penayangan, sedangkan Petugas Konten bertanggung jawab terhadap pengelolaan konten siaran. Seluruh data aplikasi disimpan menggunakan database MySQL dan dihubungkan melalui JDBC sehingga proses pengelolaan dan penyajian informasi dapat dilakukan secara terintegrasi.

## 2. Fitur Utama Program

### 2.1 Login dan Hak Akses

- Pengguna dapat masuk ke aplikasi menggunakan username dan password.
- Sistem melakukan pemeriksaan identitas dan password sebelum memberikan akses.
- Sistem membedakan tiga jenis hak akses, yaitu Admin, Petugas Jadwal, dan Petugas Konten.
- Sistem menampilkan menu sesuai dengan hak akses masing-masing pengguna.
- Setiap pengguna hanya dapat mengakses fitur yang sesuai dengan tanggung jawabnya.

### 2.2 Dashboard

- Menampilkan halaman utama setelah pengguna berhasil login.
- Menampilkan ringkasan jumlah konten, program TV, jadwal tayang, dan kerja sama.
- Menampilkan informasi jadwal tayang terbaru.
- Menampilkan ringkasan kerja sama berdasarkan mitra.

### 2.3 Manajemen Konten

- Menampilkan daftar konten siaran yang tersimpan dalam database.
- Menambahkan data konten baru.
- Mengubah informasi konten yang sudah tersedia.
- Menghapus data konten sesuai kebutuhan.
- Mengelola informasi konten berdasarkan data yang dimasukkan.

### 2.4 Manajemen Program TV

- Menampilkan daftar program televisi yang tersedia.
- Menambahkan program TV baru.
- Mengubah informasi program TV.
- Menghapus data program TV.
- Mengelola informasi program yang digunakan dalam proses penjadwalan dan penayangan.
- Pengelolaan program TV dibatasi berdasarkan hak akses pengguna.

### 2.5 Manajemen Jadwal Tayang

- Menampilkan daftar jadwal penayangan program televisi.
- Menambahkan jadwal tayang baru.
- Mengubah informasi jadwal penayangan.
- Menghapus jadwal tayang.
- Mengelola hubungan antara program TV dan jadwal penayangannya.

### 2.6 Manajemen Publikasi Konten

- Menampilkan daftar publikasi konten.
- Menambahkan data publikasi konten.
- Mengubah informasi publikasi yang sudah tersedia.
- Menghapus data publikasi.
- Mengelola informasi publikasi berdasarkan konten yang akan ditayangkan.

### 2.7 Manajemen Lampiran Konten

- Menampilkan daftar lampiran yang berkaitan dengan konten.
- Menambahkan lampiran pada data konten.
- Mengubah informasi lampiran.
- Menghapus lampiran yang sudah tidak diperlukan.
- Mengelola data pendukung yang berkaitan dengan konten siaran.

### 2.8 Manajemen Data Kanal

- Menampilkan daftar kanal televisi yang tersedia.
- Menambahkan data kanal baru.
- Mengubah informasi kanal.
- Menghapus data kanal.
- Mengelola informasi kanal yang digunakan dalam sistem.

### 2.9 Manajemen Data Mitra

- Menampilkan daftar mitra yang bekerja sama dengan perusahaan.
- Menambahkan data mitra baru.
- Mengubah informasi mitra.
- Menghapus data mitra.
- Mengelola informasi mitra yang berkaitan dengan kegiatan kerja sama.

### 2.10 Manajemen Kerja Sama

- Menampilkan daftar kerja sama dengan mitra.
- Menambahkan data kerja sama baru.
- Mengubah informasi kerja sama.
- Menghapus data kerja sama.
- Mengelola informasi hubungan kerja sama antara perusahaan dan mitra.

### 2.11 Manajemen Akun Pengguna

- Menampilkan daftar akun yang terdaftar dalam sistem.
- Menambahkan akun pengguna baru.
- Mengubah informasi akun pengguna.
- Menghapus akun pengguna.
- Mengatur jenis hak akses berdasarkan peran pengguna.
- Mengelola status akun pengguna, seperti aktif dan nonaktif.

### 2.12 Monitor Data

- Menampilkan data program TV, konten, jadwal tayang, kerja sama, dan mitra.
- Menyediakan tampilan informasi secara terpusat.
- Memungkinkan pengguna melihat data sesuai dengan hak aksesnya.
- Menyediakan akses pemantauan data tanpa melakukan perubahan terhadap data.

### 2.13 Logout

- Menyediakan fitur untuk mengakhiri sesi pengguna.
- Menghapus informasi sesi login yang sedang berlangsung.
- Mengarahkan pengguna kembali ke halaman login setelah logout.

## 3. Tech Stack

| Komponen | Teknologi | Kegunaan |
|---|---|---|
| Bahasa pemrograman | Java | Mengembangkan logika sistem, proses pengolahan data, autentikasi, serta fitur pengelolaan konten dan jadwal tayang. |
| GUI | Java Swing | Membuat antarmuka aplikasi desktop, seperti halaman login, dashboard, formulir, tabel, dan dialog. |
| GUI Builder | Apache NetBeans GUI Builder | Membantu merancang dan mengatur komponen antarmuka Java Swing secara visual. |
| Database | MySQL | Menyimpan data pengguna, konten, program televisi, jadwal tayang, kanal, mitra, publikasi, lampiran, dan kerja sama. |
| Koneksi database | JDBC | Menghubungkan aplikasi Java dengan database MySQL serta menjalankan perintah SQL menggunakan Connection, PreparedStatement, dan ResultSet. |
| Database driver | MySQL Connector | Menyediakan driver JDBC agar aplikasi Java dapat terhubung dengan database MySQL. |
| Build tool | Apache Maven | Mengelola dependensi, konfigurasi proyek, dan proses build aplikasi. |
| Java API | Java Time API | Mengelola data tanggal dan waktu, seperti tanggal penayangan serta waktu mulai dan selesai program. |
| File handling | Java NIO dan Java IO | Membantu proses pengelolaan file, termasuk membaca dan memeriksa keberadaan file lampiran konten. |
| IDE | Apache NetBeans | Digunakan untuk menulis, mengembangkan, menjalankan, dan melakukan debugging program. |
| Local development environment | Laragon | Menyediakan lingkungan lokal untuk menjalankan database selama proses pengembangan aplikasi. |
| Database management | phpMyAdmin | Membantu mengelola database MySQL melalui antarmuka berbasis web. |
| Version control | Git | Melacak perubahan kode dan mengelola riwayat pengembangan proyek. |
| Repository hosting | GitHub | Menyimpan repositori proyek secara daring dan mendukung pengelolaan kode program.

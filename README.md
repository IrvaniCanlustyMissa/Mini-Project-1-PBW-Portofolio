# Project Portofolio Website

Tugas pembuatan website portofolio menggunakan HTML, CSS, Bootstrap 5, dan Vue JS. Website ini menampilkan informasi personal, keahlian, dan sertifikat profesional dengan desain yang responsif dan interaktif.

## Teknologi yang Digunakan
- **HTML**: Digunakan sebagai struktur dasar konten website.
- **CSS**: Digunakan untuk styling custom seperti efek hover pada card, pengaturan spacing, dan scroll behavior yang halus.
- **Bootstrap 5**: Framework CSS utama yang digunakan untuk:
  - **Grid System**: Mengatur tata letak layout agar rapi di berbagai ukuran layar.
  - **Navbar**: Navigasi yang tetap berada di atas.
  - **Components**: Menggunakan card untuk sertifikat, Progress bar untuk skill, dan button untuk aksi.
- **Vue JS**: Digunakan untuk membuat tampilan lebih interaktif dengan metode **Interpolation** (`{{ }}`) dan **Directives** (`v-for`) untuk menampilkan data statis secara lebih terstruktur.

## Penjelasan Fitur & Section

### 1. Home (Hero Section)
- Berisi foto profil, nama, dan perkenalan singkat.
- Dilengkapi dengan tombol media sosial (Instagram & GitHub) yang diletakkan di tengah agar simetris dengan elemen lainnya.
- Data nama dan bio dikelola melalui logika Vue JS agar mudah diperbarui.

### 2. About Me
- **Deskripsi Diri**: Penjelasan mengenai latar belakang pendidikan dan minat di bidang Sistem Informasi.
- **Skills**: Menampilkan daftar keahlian menggunakan Bootstrap Progress Bar untuk memvisualisasikan tingkat kemahiran secara menarik.
- **Layouting**: Menggunakan sistem baris (`row`) dan kolom (`col-md-6`) agar konten terbagi menjadi dua bagian yang sejajar pada tampilan desktop.

### 3. Certificates
- Daftar sertifikat yang disusun menggunakan Bootstrap Grid dan Card Layout.
- Tiap card memiliki efek bayangan (`shadow-sm`) dan transisi hover yang memberikan kesan modern dan profesional.
- Penulisan data sertifikat dilakukan secara efisien menggunakan perulangan (`v-for`) di Vue JS.

### 4. Navbar
- Navigasi responsif yang mendukung perpindahan antar-section dengan halus.
- Memiliki fitur collapsed (hamburger menu) saat dibuka melalui perangkat mobile agar tetap ramah pengguna.

## Struktur File
- `index.html`: Berisi struktur HTML, komponen Bootstrap, dan logika Vue JS.
- `style.css`: Berisi kustomisasi gaya visual tambahan.
- `assets/`: Folder tempat menyimpan gambar (foto profil/sertifikat).

## 3. Tampilan Portofolio

#### A. Halaman Awal

<img width="1366" height="768" alt="tampilan portofolio1" src="https://github.com/user-attachments/assets/1413125b-d7a0-4a4c-881d-87f98b1d7f98" />

### B. Deskripsi Diri

<img width="1366" height="768" alt="tampilan portofolio2" src="https://github.com/user-attachments/assets/b3303287-63d6-4cf1-b02e-5cd1624950c4" />

### C. Certificates

<img width="1366" height="768" alt="tampilan portofolio3" src="https://github.com/user-attachments/assets/8f34b9d8-5c82-4d97-96dd-9b5d51c76330" />

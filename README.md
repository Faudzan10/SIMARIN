**SIMARIN (Sistem Informasi Monitoring Pencemaran Laut dan Penangkapan Ikan Ilegal**


**Deskripsi Singkat Program**

SIMARIN adalah aplikasi berbasis Pemrograman Berorientasi Objek (PBO) yang dirancang untuk memfasilitasi proses pelaporan kasus pencemaran laut dan praktik penangkapan ikan ilegal di wilayah perairan Indonesia.

Aplikasi ini dikembangkan sebagai lanjutan dari proyek Sistem Basis Data (SBD) dengan konsep sistem pelaporan yang melibatkan dua aktor utama, yaitu:

  1. Masyarakat (Pelapor)
     Pengguna umum yang melaporkan kejadian pencemaran lingkungan laut atau kegiatan penangkapan      ikan ilegal yang ditemukan di daerah pesisir atau area perairan tertentu.

  2. Petugas/Admin (Penindak)
     Petugas berwenang yang menerima laporan, menindaklanjuti, memperbarui status laporan, serta      melakukan pengelolaan data akun, lokasi laut, dan tindak lanjut pelaporan.

Tujuan utama aplikasi ini adalah untuk:

  - Menyediakan media pelaporan digital

  - Meningkatkan transparansi dan efektivitas pengawasan laut

  - Mempermudah masyarakat dalam berpartisipasi menjaga lingkungan maritim

  - Mendukung proses tindak lanjut dan dokumentasi oleh petugas pemerintah

Aplikasi ini dikembangkan menggunakan prinsip Object-Oriented Programming (OOP) dengan tujuan menghasilkan sistem yang modular, mudah dikembangkan, dan terstruktur.


**Fitur Program**

👤 Fitur untuk User / Masyarakat

1. Buat Laporan

  - Mengisi data lokasi laut

  - Mengisi data laporan

  - Memilih jenis laporan:

    - Laporan pencemaran laut

    - Laporan penangkapan ikan ilegal

2. Lihat

  - Melihat data akun sendiri

  - Melihat semua laporan yang telah dibuat, ditampilkan beserta informasi tindak lanjut dari       petugas

3. Perbarui

  - Memperbarui laporan yang sudah dibuat

  - Memperbarui data akun pribadi

  - Memperbarui data lokasi laut yang pernah ditambahkan

4. Hapus

  - Menghapus laporan yang telah dibuat

5. Cari

  - Mencari laporan berdasarkan status laporan (misal: pending, diproses, selesai)

  - Mencari tindak lanjut berdasarkan status tindakan petugas

6. Logout

  - Keluar dari aplikasi




**🛡️ Fitur untuk Petugas / Admin**

1. Buat Laporan

  - Menginput lokasi laut

  - Membuat laporan (jika petugas melakukan pelaporan langsung di lapangan)

  - Memilih jenis laporan:

    - Laporan pencemaran laut

    - Laporan penangkapan ikan ilegal

2. Lihat

  - Melihat seluruh tabel yang tersedia dalam sistem (akun, laporan, lokasi laut, tindak lanjut)

3. Perbarui

  - Memperbarui semua laporan dalam basis data

  - Memperbarui semua akun pengguna

  - Memperbarui data tindak lanjut laporan

  - Memperbarui semua data lokasi laut

4. Hapus

  - Menghapus laporan dari database

  - Menghapus akun pengguna

5. Cari

  - Mencari laporan berdasarkan status

  - Mencari tindak lanjut berdasarkan status tindakan

  - Mencari akun pengguna berdasarkan username

6. Logout

  - Keluar dari aplikasi




























--------------------------

**Cara Menggunakan Program**


Cara Menggunakan Program (Menu Masyarakat)

Saat aplikasi dijalankan, pengguna akan diarahkan ke halaman awal yang berisi:

Login → digunakan jika pengguna sudah memiliki akun

-

Sign In / Registrasi → digunakan untuk membuat akun baru

-

Setelah berhasil login, pengguna masuk ke Menu Masyarakat, yang terdiri dari:

-

Buat Laporan

Lihat Laporan

Cari Laporan

Perbarui Laporan

Hapus Laporan

Logout

✅ 1. Buat Laporan

-

Ketika memilih menu Buat Laporan, pengguna akan diarahkan ke halaman pemilihan jenis data yang ingin dibuat:

-

Buat Akun

Buat Lokasi Laut

Buat Laporan

Buat Tindak Lanjut



Buat Jenis Laporan

-

Laporan Pencemaran Laut

Laporan Penangkapan Ikan Ilegal

➤ Input Lokasi Laut

-

Pengguna diminta mengisi data lokasi:

Nama lokasi

Koordinat

Wilayah

Kondisi terakhir

➤ Input Tindak Lanjut

-

Pengguna mengisi data tindak lanjut awal (jika ada):

ID Laporan

Tanggal tindak lanjut

Hasil tindak lanjut

Nominal denda (jika ada)

Status tindakan

➤ Laporan Pencemaran Laut

-

Form berisi:

Sumber limbah

Jenis limbah

Tingkat pencemaran (Ringan / Sedang / Berat)

➤ Laporan Penangkapan Ikan Ilegal

-

Form berisi:

ID laporan

Jenis kapal

Alat tangkap

Zona penangkapan

Pelanggaran

✅ 2. Lihat Laporan

-

Ketika pengguna memilih Lihat Laporan, sistem akan menampilkan pilihan jenis laporan:

Laporan Pencemaran Laut

Laporan Penangkapan Ikan Ilegal

Setelah memilih, sistem menampilkan tabel laporan sesuai kategori disertai data tindak lanjut jika tersedia.

✅ 3. Cari Laporan

-

Pengguna dapat mencari laporan berdasarkan jenisnya:

Cari laporan pencemaran laut

Cari laporan penangkapan ikan ilegal

Pengguna diminta memasukkan ID Laporan, lalu sistem menampilkan data laporan dalam bentuk tabel.

✅ 4. Perbarui Laporan

Pengguna dapat memperbarui data sesuai jenis laporan:

➤ Perbarui Laporan Penangkapan Ikan

-

Input ulang:

ID laporan

Jenis kapal

Alat tangkap

Zona penangkapan

Pelanggaran


➤ Perbarui Laporan Pencemaran Laut

-

Input ulang:

ID laporan

Jenis limbah

Sumber limbah

Tingkat pencemaran


➤ Perbarui Tindak Lanjut

-

Masukkan ID laporan

Data lama muncul dalam tabel

Perbarui data sesuai form


➤ Perbarui Lokasi Laut

-

Masukkan ID lokasi

Data lama tampil

Pengguna memperbarui sesuai kebutuhan


✅ 5. Hapus Laporan

Untuk menghapus laporan:

Pilih jenis laporan
-

Masukkan ID laporan
-

Sistem menghapus data laporan tersebut

✅ 6. Logout

Keluar dari aplikasi dan kembali ke halaman login.

---
title: "JadwalIn College Project"
date: 2025-06-24
description: "JadwalIn, sistem penjadwalan kuliah dan peminjaman ruang kelas untuk mahasiswa, dosen, dan admin Prodi Informatika Universitas Udayana."
categories: [web-development]
tags: [project, github, kuliah]
lang: id
canonical_url: https://redcom1988.github.io/posts/jadwalin-project-id/
---

<div>
  <img src="/assets/img/jadwalin/logo.png" alt="Logo" />
</div>

## 🚀 Pengenalan

**JadwalIn** adalah sistem digital berbasis web untuk membantu proses penjadwalan kuliah dan peminjaman ruang kelas di lingkungan Program Studi Informatika, Universitas Udayana. Website ini dibangun menggunakan Laravel dan React.js, serta menggunakan SQLite sebagai basis data.  

Admin dapat mengelola data jadwal, pengguna, ruang kelas, dan memproses peminjaman ruangan. Dosen dan mahasiswa dapat melihat jadwal, mengajukan perubahan, serta memesan ruang kelas — semua dilakukan secara real-time dengan antarmuka dashboard berdasarkan peran masing-masing.

Ini merupakan proyek akhir untuk mata kuliah Sistem Informasi. Saya bertanggung jawab atas algoritma penjadwalan menggunakan pendekatan constraint programming serta implementasi API untuk backend.

---

## 📸 Pratinjau Fitur

Untuk pengguna yang belum login, hanya halaman login dan registrasi yang tersedia. Setelah login, pengguna akan diarahkan ke dashboard sesuai dengan perannya.

Dosen dapat:

- Melihat jadwal mengajar dan daftar mahasiswa.
- Mengajukan perubahan jadwal kuliah atau ruangan.
- Memesan ruang kelas untuk kegiatan tambahan.

Mahasiswa dapat:

- Melihat jadwal berdasarkan mata kuliah favorit.
- Memesan ruang kelas (misalnya untuk kerja kelompok).
- Melihat status peminjaman dan perubahan jadwal secara real-time.

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/jadwalin/login.png" alt="Halaman Login" />
  <img src="/assets/img/jadwalin/register.png" alt="Halaman Register" />
  <img src="/assets/img/jadwalin/beranda.png" alt="Dashboard Beranda" />
  <img src="/assets/img/jadwalin/view-jadwal.png" alt="Lihat Jadwal" />
  <img src="/assets/img/jadwalin/book-room.png" alt="Peminjaman Ruangan" />
  <img src="/assets/img/jadwalin/report-jadwal.png" alt="Permintaan Perubahan Jadwal Dosen" />
</div>

---

Akun admin memiliki akses penuh terhadap pengelolaan data master dan operasi sistem. Dashboard admin mencakup:

- **Tab Data Master** untuk mengelola dosen, mahasiswa, mata kuliah, dan ruang kelas.
- **Manajemen Jadwal** untuk membuat dan memvalidasi jadwal kuliah.
- **Permintaan Peminjaman** untuk menyetujui atau menolak permohonan peminjaman.
- **Kontrol Akses** untuk mengatur peran dan izin setiap pengguna.

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/jadwalin/beranda.png" alt="Dashboard Admin" />
  <img src="/assets/img/jadwalin/data-mahasiswa.png" alt="Data Mahasiswa" />
  <img src="/assets/img/jadwalin/data-dosen.png" alt="Data Dosen" />
  <img src="/assets/img/jadwalin/data-ruangkelas.png" alt="Data Ruang Kelas" />
  <img src="/assets/img/jadwalin/data-jadwal.png" alt="Data Jadwal" />
  <img src="/assets/img/jadwalin/riwayat-peminjaman.png" alt="Riwayat Peminjaman" />
  <img src="/assets/img/jadwalin/generate-jadwal-mingguan.png" alt="Generate Jadwal Mingguan" />
  <img src="/assets/img/jadwalin/generate-jadwal-pertemuan.png" alt="Generate Jadwal Pertemuan" />
  <img src="/assets/img/jadwalin/akses-user.png" alt="Kontrol Akses Pengguna" />
</div>

---

## 📎 Tautan
- 🔗 [Repo GitHub](https://github.com/EgiKelo9/jadwalin-sisfor)
---
title: "Papikos College Project"
date: 2025-6-11
description: "Papikos, sebuah situs web yang terinspirasi dari Mamikos, membantu pengguna (terutama mahasiswa) mencari daftar kos lengkap dengan sistem pelaporan untuk mencegah aktivitas penipuan."
categories: [web-development]
tags: [project, github, college]
lang: id
canonical_url: https://redcom1988.github.io/posts/papikos-project-id/
---

<div>
  <img src="/assets/img/papikos/Logo.svg" alt="Logo" />
</div>

## 🚀 Pengenalan

**Papikos** adalah situs web pencarian kos yang terinspirasi dari Mamikos. Situs ini memiliki sistem pelaporan untuk mencegah aktivitas atau perilaku penipuan dari pemilik kos, serta sistem percakapan bawaan (tanpa websocket, hanya fetch berulang setiap beberapa detik) untuk mempermudah komunikasi antara pemilik dan penyewa. Website dibangun menggunakan Laravel + React untuk frontend dan backend, serta SQLite sebagai basis data.

Penyewa dapat melihat, memfilter, mencari, menyimpan (bookmark), melaporkan (dengan bukti gambar) daftar kos, memesan jadwal survei, serta mengobrol dengan pemilik kos. Pemilik kos dapat melakukan hal yang sama dan juga menolak laporan palsu, serta membatalkan atau menyelesaikan janji survei. Pemilik juga memiliki dashboard yang menampilkan statistik kamar kos mereka, memungkinkan mereka menambahkan kos baru, serta mengedit/memperbarui kos yang ada. Terakhir, admin memiliki dashboard yang menampilkan semua data pengguna dan kamar, serta laporan yang dapat ditinjau secara individual untuk menentukan status dan tindakan selanjutnya.

Website ini juga mengirim email bulanan berisi tautan pembayaran dari DOKU sebagai bentuk biaya layanan untuk pemilik kos (dilakukan sebagai alternatif gateway pembayaran penuh karena keterbatasan waktu dan tenaga). Website ini juga dilengkapi fitur login, registrasi, lupa kata sandi, dan mode terang/gelap.

Ini adalah proyek akhir untuk mata kuliah pengembangan web yang dikerjakan secara berkelompok. Namun, saya menangani semua aspek (backend, frontend, data, devOps, desain) karena keterbatasan kemampuan anggota kelompok saya.

---

## 📸 Pratinjau Fitur

Untuk pengunjung (pengguna belum login), tersedia halaman landing, pencarian daftar kos, dan detail kos. Untuk pengguna yang sudah login, tersedia fitur simpan bookmark, pemesanan survei, pelaporan daftar kos, dan percakapan dengan pemilik kos.

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/papikos/login.png" alt="Login page" />
  <img src="/assets/img/papikos/register.png" alt="Register page" />
  <img src="/assets/img/papikos/landing-page.png" alt="Landing page" />
  <img src="/assets/img/papikos/browse-listings-page.png" alt="Browse listings page" />
  <img src="/assets/img/papikos/room-listing-page.png" alt="Room listing page" />
  <img src="/assets/img/papikos/report-listing-page.png" alt="Report listing page" />
  <img src="/assets/img/papikos/schedule-survey-page.png" alt="Schedule survey page" />
  <img src="/assets/img/papikos/chat-map.png" alt="Chat and map page" />
  <img src="/assets/img/papikos/bookmarked-listings-page.png" alt="Bookmarked listings page" />
</div>

---

Akun pemilik dan admin memiliki akses ke dashboard. Halaman default dashboard pemilik menampilkan statistik informasi penting seperti jumlah kamar tersedia, kamar terisi, dan janji survei. Sidebar dashboard memiliki beberapa tab, yaitu:
- Tab **my rooms** menampilkan daftar kamar yang dimiliki, dengan opsi melihat, mengedit, dan menambahkan kamar baru.
- Tab **appointments** menampilkan daftar janji survei dengan opsi membatalkan atau menyelesaikan.
- Tab **reports** menampilkan laporan terhadap kamar yang dimiliki dan memungkinkan pemilik membantah laporan dengan bukti dan penjelasan.
- Tab **messages** menampilkan percakapan antara pemilik dan pengguna lainnya.
- Tab **settings** memungkinkan pengelolaan profil, kata sandi, dan tampilan tema.

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/papikos/owner-dashboard.png" alt="Owner dashboard" />
  <img src="/assets/img/papikos/owner-my-rooms.png" alt="Owner my rooms" />
  <img src="/assets/img/papikos/owner-appointments.png" alt="Owner appointments" />
  <img src="/assets/img/papikos/owner-reports.png" alt="Owner reports" />
  <img src="/assets/img/papikos/owner-messages.png" alt="Owner messages" />
  <img src="/assets/img/papikos/owner-settings.png" alt="Owner settings" />
</div>

---

Terakhir, dashboard admin (ditampilkan dalam mode terang) memiliki halaman default yang menampilkan statistik pengguna, kamar, dan laporan. Sidebar dashboard mencakup beberapa tab, yaitu:
- Tab **manage users** menampilkan semua pengguna, dengan opsi menambah, mengedit, dan/atau menghapus pengguna.
- Tab **manage rooms** menampilkan semua daftar kamar, dengan opsi menambah, mengedit, dan/atau menghapus kamar.
- Tab **manage reports** menampilkan semua laporan yang disengketakan, di mana admin dapat meninjau dan mengubah status laporan berdasarkan bukti.
- Tab **messages** menampilkan pesan yang dikirim kepada/dari admin.
- Tab **settings** memungkinkan pengelolaan profil, kata sandi, dan tampilan tema.

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/papikos/admin-dashboard.png" alt="Admin dashboard" />
  <img src="/assets/img/papikos/admin-users.png" alt="Admin users" />
  <img src="/assets/img/papikos/admin-add-user.png" alt="Admin add user" />
  <img src="/assets/img/papikos/admin-rooms.png" alt="Admin rooms" />
  <img src="/assets/img/papikos/admin-reports.png" alt="Admin reports" />
  <img src="/assets/img/papikos/admin-report-action.png" alt="Admin report action" />
</div>

---

## 📎 Tautan
- 🔗 [Repo GitHub](https://github.com/redcom1988/papikos)
- 🔗 [Link Website](https://papikos.genk.top/)

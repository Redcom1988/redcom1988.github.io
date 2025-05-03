---
title: "Proyek Kuliah Ecoscan"
date: 2024-12-22
description: "Ecoscan, sebuah aplikasi seluler berbasis Pfandautomat, memberikan penghargaan kepada pengguna yang mendaur ulang barang-barang yang dapat digunakan kembali seperti kaleng dan botol plastik dengan poin yang dapat ditukarkan menjadi voucher."
categories: [software-development]
tags: [project, github, college]
lang: id
canonical_url: https://redcom1988.github.io/posts/ecoscan-project-id/
---

<div>
  <img src="/assets/img/ecoscan/logo.png" alt="Logo" />
</div>

## 🚀 Pengenalan

Ecoscan adalah aplikasi pengumpulan sampah terinspirasi dari Pfandautomat, di mana pengguna mendapatkan poin dari mendaur ulang botol dan kaleng. Poin tersebut bisa ditukar dengan voucher. Aplikasi ini dibuat menggunakan Flutter (frontend), Express.js (backend), dan MySQL (database), terdiri dari layar user, admin, dan simulasi mesin.
Ini adalah proyek kuliah untuk mata kuliah pengembangan perangkat lunak yang dilakukan berkelompok. Saya bertanggung jawab pada backend, namun karena progress frontend lambat, saya juga membantu di beberapa bagian.

---

## 📸 Pratinjau Fitur

Untuk layar pengguna, ini mencakup beranda, layar berita, pemindai kode QR, layar voucher, dan profil. Beranda terdiri dari korsel kartu berita, riwayat penarikan, pintasan ke penukaran poin, dan riwayat pembelian voucher. Layar berita terdiri dari daftar entri berita. Pemindai kode QR digunakan untuk memindai kode QR yang dikeluarkan oleh mesin setelah memasukkan sampah, setelah itu Anda akan mendapatkan poin tergantung pada sampah yang dimasukkan. Layar Voucher adalah tempat Anda dapat menukarkan poin menjadi voucher. Terakhir adalah profil yang menampilkan profil Anda. (Secara teknis ada satu layar lagi untuk pusat dukungan, tapi saya rasa itu akan terlalu panjang)

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/ecoscan/user-register.png" alt="Fitur 1" />
  <img src="/assets/img/ecoscan/user-login.png" alt="Fitur 2" />
  <img src="/assets/img/ecoscan/user-profile.png" alt="Fitur 3" />
  <img src="/assets/img/ecoscan/user-homepage.png" alt="Fitur 4" />
  <img src="/assets/img/ecoscan/user-withdrawal-history.png" alt="Fitur 5" />
  <img src="/assets/img/ecoscan/user-news.png" alt="Fitur 6" />
  <img src="/assets/img/ecoscan/user-news-detail.png" alt="Fitur 7" />
  <img src="/assets/img/ecoscan/user-qrscan.png" alt="Fitur 8" />
  <img src="/assets/img/ecoscan/user-voucher-buy.png" alt="Fitur 9" />
</div>

---

Untuk layar simulasi mesin, layar ini mencakup entri dengan menu dropdown yang diisi dengan jenis sampah (diambil dari database) dan area teks untuk kuantitas. Setelah dikirim, maka akan muncul kode QR dengan nilai berdasarkan jenis dan kuantitas sampah.

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px;">
  <img src="/assets/img/ecoscan/machine-input.png" alt="Sebelum" />
  <img src="/assets/img/ecoscan/machine-output.png" alt="Sesudah" />
</div>

---

Terakhir, untuk layar admin. Layar ini mencakup layar tiket dukungan, layar berita (atau edukasi), layar voucher, dan profil. Seperti alasan sebelumnya, saya tidak akan menampilkan layar tiket dukungan karena pengguna juga tidak akan menampilkannya (akan membingungkan).

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/ecoscan/admin-education.png" alt="Admin 1" />
  <img src="/assets/img/ecoscan/admin-education-add.png" alt="Admin 2" />
  <img src="/assets/img/ecoscan/admin-education-edit.png" alt="Admin 3" />
  <img src="/assets/img/ecoscan/admin-voucher.png" alt="Admin 4" />
  <img src="/assets/img/ecoscan/admin-voucher-add.png" alt="Admin 5" />
  <img src="/assets/img/ecoscan/admin-voucher-edit.png" alt="Admin 6" />
</div>

---

## 📎 Tautan
- 🔗 [Repo GitHub](https://github.com/redcom1988/eco-scan-app)

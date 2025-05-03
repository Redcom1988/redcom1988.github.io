---
title: "Trivium Personal Project"
date: 2025-2-17
description: "Trivium, sebuah aplikasi trivia berbasis OpenTriviaDB, menghadirkan pengalaman kuis interaktif dengan berbagai kategori dan tingkat kesulitan. Dibuat dengan Kotlin dan Jetpack Compose."
categories: [software-development]
tags: [project, github]
lang: id
canonical_url: https://redcom1988.github.io/posts/trivium-project-id/
---

<div>
  <img src="/assets/img/trivium/logo.png" alt="Logo" />
</div>

## 🚀 Pengenalan

Trivium adalah sebuah aplikasi trivia yang berbasis OpenTriviaDB. Aplikasi ini dibangun menggunakan kotlin android dan jetpack compose untuk front-end. Aplikasi ini memiliki beberapa kategori dan tingkat kesulitan pertanyaan (yang semuanya merupakan pilihan ganda) berdasarkan pilihan OpenTriviaDB.

Ini adalah proyek pribadi dengan kakak saya di mana saya bertanggung jawab atas pengembangan front-end dan UI/UX, sementara kakak saya bertanggung jawab atas pengembangan back-end.

---

## 📸 Pratinjau Fitur

Layar pertama yang ditampilkan adalah layar menu utama, berisi tombol *Play* dan *Achievement*. Tombol *Achievement* akan menampilkan semua pencapaian, baik yang sudah maupun belum diperoleh (dengan yang sudah diperoleh akan disorot).

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px;">
  <img src="/assets/img/trivium/main-menu.jpg" alt="Menu Utama" />
  <img src="/assets/img/trivium/achievement-menu.jpg" alt="Menu Pencapaian" />
</div>

---

Setelah menekan tombol *Play*, pengguna akan diarahkan ke menu permainan yang memungkinkan pemilihan kategori, tingkat kesulitan, serta mode permainan. Penjelasan mengenai mode juga ditampilkan di layar ini. Saat memilih kategori, pengguna akan dibawa ke layar pemilihan kategori yang berisi berbagai pilihan.

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/trivium/play-menu.jpg" alt="Menu Bermain" />
  <img src="/assets/img/trivium/category-select.jpg" alt="Pilih Kategori" />
  <img src="/assets/img/trivium/play-menu-alt.jpg" alt="Menu Bermain Alternatif" />
</div>

---

Saat permainan dimulai, pengguna akan melihat soal dan pilihan jawaban. Pengguna bisa memilih satu jawaban dan mengonfirmasi. Jawaban yang benar akan ditandai hijau, sedangkan jawaban salah (jika dipilih) akan ditandai merah. 

Permainan mencatat skor, streak, dan waktu bermain (yang akan berhenti saat jawaban dikonfirmasi). Terdapat tombol *Give Up* untuk menyerah. Setelah permainan selesai, layar akhir akan menampilkan skor, waktu, akurasi, nilai (misal: 2/20), streak terbaik, dan progres pencapaian. Pengguna dapat memilih untuk bermain lagi atau kembali ke menu utama.

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px;">
  <img src="/assets/img/trivium/game.jpg" alt="Menu Permainan" />
  <img src="/assets/img/trivium/game-correct.jpg" alt="Jawaban Benar" />
  <img src="/assets/img/trivium/game-incorrect.jpg" alt="Jawaban Salah" />
  <img src="/assets/img/trivium/game-end.jpg" alt="Layar Akhir" />
</div>

---

## 📎 Tautan
- 🔗 [GitHub Repo](https://github.com/achmadss/trivium)


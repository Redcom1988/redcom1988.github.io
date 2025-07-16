---
title: "JadwalIn College Project"
date: 2025-06-24
description: "JadwalIn, a class scheduling and room booking system designed for Informatics students, lecturers, and admins at Universitas Udayana."
categories: [web-development]
tags: [project, github, college]
lang: en
canonical_url: https://redcom1988.github.io/posts/jadwalin-project-en/
---

<div>
  <img src="/assets/img/jadwalin/logo.png" alt="Logo" />
</div>

## 🚀 Introduction

**JadwalIn** is a digital class scheduling and room booking system designed to streamline academic operations at the Informatics Study Program, Universitas Udayana. It was built using Laravel and React.js, with SQLite for the database.  

Admins can manage schedules, user roles, room assignments, and handle booking requests. Lecturers and students can view schedules, propose class changes, and request room bookings — all in real-time, through a role-based dashboard interface.

This was a final project for the System Information course. I was responsible for the scheduling algorithm using constraint programming and the API implementation

---

## 📸 Features Preview

For guests (non-logged-in users), only login and register pages are accessible. After login, users are redirected to dashboards according to their roles.

Lecturers can:

- View their teaching schedules and student lists.
- Request class rescheduling or classroom changes.
- Book available rooms for extra sessions.

Students can:

- See their favourited courses in schedule.
- Book available rooms (e.g. for group work).
- View booking status and schedule updates in real-time.

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/jadwalin/login.png" alt="Login page" />
  <img src="/assets/img/jadwalin/register.png" alt="Register page" />
  <img src="/assets/img/jadwalin/beranda.png" alt="Dashboard Home" />
  <img src="/assets/img/jadwalin/view-jadwal.png" alt="View Schedule Page" />
  <img src="/assets/img/jadwalin/book-room.png" alt="Book Room Page" />
  <img src="/assets/img/jadwalin/report-jadwal.png" alt="Lecturer Schedule Change Request Page" />
</div>

---

Admins gain full access to master data and system operations. The admin dashboard includes:

- **Master Data Tabs** to manage lecturers, students, courses, and rooms.
- **Schedule Management** to create and update timetables with validation.
- **Booking Requests** to approve or reject room booking forms.
- **Access Control** to assign roles and permissions.

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/jadwalin/beranda.png" alt="Admin Dashboard" />
  <img src="/assets/img/jadwalin/data-mahasiswa.png" alt="Admin Student Data" />
  <img src="/assets/img/jadwalin/data-dosen.png" alt="Admin Lecturer Data" />
  <img src="/assets/img/jadwalin/data-ruangkelas.png" alt="Admin Room Data" />
  <img src="/assets/img/jadwalin/data-jadwal.png" alt="Admin Schedule Data" />
  <img src="/assets/img/jadwalin/riwayat-peminjaman.png" alt="Admin Booking History" />
  <img src="/assets/img/jadwalin/generate-jadwal-mingguan.png" alt="Generate Weekly Schedule" />
  <img src="/assets/img/jadwalin//generate-jadwal-pertemuan.png" alt="Generate Schedule" />
  <img src="/assets/img/jadwalin/akses-user.png" alt="Admin Access Control" />
</div>

---

## 📎 Links
- 🔗 [GitHub Repo](https://github.com/EgiKelo9/jadwalin-sisfor)

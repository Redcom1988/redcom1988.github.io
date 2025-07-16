---
title: "Papikos College Project"
date: 2025-6-11
description: "Papikos, a website based on mamikos that helps people (primarily students) finding room listings complete with a report system to prevent fraudulent activities."
categories: [web-development]
tags: [project, github, college]
lang: en
canonical_url: https://redcom1988.github.io/posts/papikos-project-en/
---

<div>
  <img src="/assets/img/papikos/Logo.svg" alt="Logo" />
</div>

## 🚀 Introduction

Papikos is a mamikos inspired room listing browser website that includes a report system to prevent fraudulent activities/behavior from room owners, and a built-in chat system (not using websocket but just repeated fetch every few seconds) for easy communication between owners and renters. The website is built using Laravel + React for front-end and back-end with SQLite as database. 

Renters can see, filter, search, bookmark, report, (with image proof) listings, book surveys for selected listings, and also chat with the owner of a selected listing. Owners can do the same but also refute a report in case it was a fake report and cancel/finish booked survey appointments, owners also have a dashboard that shows statistics of their room listings, allows them to create more room listings, and edit/update their listings to their desired result. Lastly admins also have a dashboard that shows all user and room data, and reports that they can review individually to change report status and take action from there.

Website also sends an email every month containing a payment link from doku to behave as a service fee for owners (this was done instead of a proper payment gateway system due to lack of time and manpower). Lastly it includes a login, register, forgot password, and a dark/light mode.

This was a final college project for web development subject done with a group. I was in charge of everything (back-end, front-end, data, devOps, design) due to my groupmates lack of ability.

---

## 📸 Features Preview

For guests (non logged-in users), landing page, browse listing, and listing details page are available. For logged-in users, they gain access to bookmark, book survey appointments, report listings, and chat with listing owner.

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

Owner and admin accounts gain access to a dashboard. Owner dashboard default page contains statistics of relevant owner information (like available owned rooms, occupied rooms, appointments). Dashboard sidebar contains multiple tabs being:
- **My rooms** tab shows owned rooms where owner can see, edit current listings, and/or add new listings.
- **Appointments** tab shows upcoming appointments to owned rooms where owner can cancel or complete appointments.
- **Reports** tab shows reports toward owned rooms where owner can refute/dispute reports by showing proof and reasoning.
- **Messages** tab shows messages sent toward and/or from the user/owner.
- **Settings** tab shows profile, password, and appearance settings.

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/papikos/owner-dashboard.png" alt="Owner dashboard" />
  <img src="/assets/img/papikos/owner-my-rooms.png" alt="Owner my rooms" />
  <img src="/assets/img/papikos/owner-appointments.png" alt="Owner appointments" />
  <img src="/assets/img/papikos/owner-reports.png" alt="Owner reports" />
  <img src="/assets/img/papikos/owner-messages.png" alt="Owner messages" />
  <img src="/assets/img/papikos/owner-settings.png" alt="Owner settings" />
</div>

---

Lastly, admin dashboard (which i'll show in light mode) default page contains statistics of users, rooms, and reports. Dashboard sidebar contains multiple tabs being:
- **Manage users** tab shows all users where admin can see, add, edit, and/or remove users
- **Manage rooms** tab shows all rooms where admin can see, add, edit, and/or remove rooms
- **Manage reports** tab shows all disputed reports where admin can verify and change status of report depending on proof given
- **Messages** tab shows messages sent toward and/or from the user/admin.
- **Settings** tab shows profile, password, and appearance settings.

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/papikos/admin-dashboard.png" alt="Admin dashboard" />
  <img src="/assets/img/papikos/admin-users.png" alt="Admin users" />
  <img src="/assets/img/papikos/admin-add-user.png" alt="Admin add user" />
  <img src="/assets/img/papikos/admin-rooms.png" alt="Admin rooms" />
  <img src="/assets/img/papikos/admin-reports.png" alt="Admin reports" />
  <img src="/assets/img/papikos/admin-report-action.png" alt="Admin report action" />
</div>

---

## 📎 Links
- 🔗 [GitHub Repo](https://github.com/redcom1988/papikos)

---
title: "Trivium Personal Project"
date: 2025-2-17
description: "A trivia application based on OpenTriviaDB."
author: "Adika Setyadharma Susilo"
categories: [software-development]
tags: [project, github]
lang: en
canonical_url: https://redcom1988.github.io/posts/trivium-project-en/
image: "assets/img/trivium/logo.png"
---

## 🚀 Introduction

Trivium is a trivia application based on OpenTriviaDB. The application is built using kotlin android and jetpack compose for front-end. It features multiple categories and difficulties of questions (all of which are multiple choice) based on the OpenTriviaDB selections.

This was a personal project with my brother where I'm in charge of front-end development and UI/UX, meanwhile my brother is in charge of the back-end development.

---

## 📸 Features Preview

For the user screen, it includes a homepage, news screen, QR code scanner, vouchers screen, and profile. Homepage consists of a carousel of news cards, withdrawal history, shortcut to point redeem, and a voucher purchase history. News screen consists of a list of news entries. QR code scanner is used to scan QR codes that gets outputted by the machine after inserting waste, after which you will gain points depending on waste inserted. Vouchers screen is where you can redeem/exchange your points into vouchers. Lastly profile which shows your profile. (There is technically one more screen for support center but I feel like it'd just be too long)

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/ecoscan/user-register.png" alt="Feature 1" />
  <img src="/assets/img/ecoscan/user-login.png" alt="Feature 2" />
  <img src="/assets/img/ecoscan/user-profile.png" alt="Feature 3" />
  <img src="/assets/img/ecoscan/user-homepage.png" alt="Feature 4" />
  <img src="/assets/img/ecoscan/user-withdrawal-history.png" alt="Feature 5" />
  <img src="/assets/img/ecoscan/user-news.png" alt="Feature 6" />
  <img src="/assets/img/ecoscan/user-news-detail.png" alt="Feature 7" />
  <img src="/assets/img/ecoscan/user-qrscan.png" alt="Feature 8" />
  <img src="/assets/img/ecoscan/user-voucher-buy.png" alt="Feature 9" />
</div>

---

For the machine simulation screen, it includes entries with a dropdown menu filled with waste types (taken from database) and a text area for quantity. After submitting, it will make a QR code with value based on waste type and quantity.

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px;">
  <img src="/assets/img/ecoscan/machine-input.png" alt="Before" />
  <img src="/assets/img/ecoscan/machine-output.png" alt="After" />
</div>

---

Lastly, for admin screen. It includes support ticket screen, news (or education) screen, voucher screen, and profile. Like the reason before I wont be showing support ticket screen due to users also not showing it (It'd get confusing).

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/ecoscan/admin-education.png" alt="UI 1" />
  <img src="/assets/img/ecoscan/admin-education-add.png" alt="UI 2" />
  <img src="/assets/img/ecoscan/admin-education-edit.png" alt="UI 3" />
  <img src="/assets/img/ecoscan/admin-voucher.png" alt="UI 4" />
  <img src="/assets/img/ecoscan/admin-voucher-add.png" alt="UI 5" />
  <img src="/assets/img/ecoscan/admin-voucher-edit.png" alt="UI 6" />
</div>

---

## 📎 Links
- 🔗 [GitHub Repo](https://github.com/achmadss/trivium)


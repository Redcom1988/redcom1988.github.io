---
title: "Trivium Personal Project"
date: 2025-2-17
description: "Trivium, a trivia application based on OpenTriviaDB, presents an interactive quiz experience with various categories and difficulty levels. Built with Kotlin and Jetpack Compose."
categories: [software-development]
tags: [project, github]
lang: en
canonical_url: https://redcom1988.github.io/posts/trivium-project-en/
---

<div>
  <img src="/assets/img/trivium/logo.jpg" alt="Logo" />
</div>

## 🚀 Introduction

Trivium is a trivia application based on OpenTriviaDB. The application is built using kotlin android and jetpack compose for front-end. It features multiple categories and difficulties of questions (all of which are multiple choice) based on the OpenTriviaDB selections.

This was a personal project with my brother where I'm in charge of front-end development and UI/UX, meanwhile my brother is in charge of the back-end development.

---

## 📸 Features Preview

The first screen that users will encounter upon opening the app is a main menu screen that contains a play button and an achievement button. Achievement button will show all achievements, obtained or not (with obtained being highlighted).

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px;">
  <img src="/assets/img/trivium/main-menu.jpg" alt="Main Menu" />
  <img src="/assets/img/trivium/achievement-menu.jpg" alt="Achievement Menu" />
</div>

---

Upon pressing start button, user will be redirected to the play menu that contains a category select, difficulty option button, mode option button, and mode description. If user presses the category select, they will be redirected to category select screen where the user can pick 1 of the many categories.

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">
  <img src="/assets/img/trivium/play-menu.jpg" alt="Play Menu" />
  <img src="/assets/img/trivium/category-select.jpg" alt="Category Select" />
  <img src="/assets/img/trivium/play-menu-alt.jpg" alt="Play Menu Alt" />
</div>

---

After the user presses start game, they get redirected to game menu that shows questions and answers (in the form of option buttons). User can pick an option and confirm to lock their answer after which it will show the correct answer highlighted in green, and the wrong answer (if the selected option is wrong) in red. 

The game will keep track of score, streak, and time spent (which will pause after confirming answer). Give up button is used to stop the game. When the user finishes the game, it will show and end screen that shows score, time spent (slightly bugged at the moment), accuracy, marks (i.e. 2/20), best streak, and achievement progress. After which user can choose to play again or go back to the main menu.

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px;">
  <img src="/assets/img/trivium/game.jpg" alt="Game Menu" />
  <img src="/assets/img/trivium/game-correct.jpg" alt="Game Menu Correct" />
  <img src="/assets/img/trivium/game-incorrect.jpg" alt="Game Menu Incorrect" />
  <img src="/assets/img/trivium/game-end.jpg" alt="End Screen" />
</div>

---

## 📎 Links
- 🔗 [GitHub Repo](https://github.com/achmadss/trivium)


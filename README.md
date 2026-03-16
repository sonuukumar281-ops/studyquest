# ⚔️ StudyQuest — Gamified Learning Platform

> Turn studying into an adventure. Earn XP, unlock badges, compete on the leaderboard.

## 🌐 Live Demo
[Click here to play →]( https://sonuukumar281-ops.github.io/studyquest/)

## 🎮 Features
- 📊 **Dashboard** — XP bar, streak tracker, accuracy stats
- 📚 **Subject Library** — Data Structures, C Programming, Aptitude, Mathematics
- ⚡ **Daily Challenge** — Bonus XP every day
- 📅 **Daily Tasks** — 40 MCQ + Subjective questions with smart hints
- 🃏 **Flashcards** — 3D flip cards with spaced repetition
- 🍅 **Pomodoro Timer** — Focus sessions with +25 XP reward
- ⚔️ **Quiz Arena** — Speed mode with combo multipliers and lives
- 🏆 **Leaderboard** — Compete with other students
- 👤 **Profile** — Badges, level roadmap, photo upload
- 🤖 **AI Study Assistant** — Rule-based chatbot for CS + aptitude help

## 🛠️ Tech Stack
| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Auth | Firebase Authentication |
| Storage | localStorage (MVP) |
| Fonts | Orbitron + Exo 2 (Google Fonts) |

## 🚀 How to Run
1. Download `StudyQuest.html`
2. Open it in any modern browser — that's it!
3. No server, no install, no dependencies.

## 🔑 Firebase Setup (for Auth)
1. Go to [console.firebase.google.com](https://console.firebase.google.com)
2. Create a project → Enable Email/Password authentication
3. Paste your Firebase config into the `FIREBASE_CONFIG` section in `StudyQuest.html`

## 🏗️ Project Structure
```
StudyQuest/
├── StudyQuest.html   ← Complete single-file app (HTML + CSS + JS)
├── daily.html        ← Daily Tasks page
└── README.md
```

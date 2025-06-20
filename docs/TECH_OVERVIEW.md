# 🧠 Technical Overview of AliciaCryst.com

This document offers an architectural overview for contributors, focusing on the emotional and technical design behind the shrine.

## 🌐 Site Structure

### HTML Sections:
- `#about` – Alicia's life & identity
- `#poems` – Rotating poetry carousel
- `#letters` – "Letters from Alicia" generator
- `#wall` – Eternal story wall with Firestore
- `#diyas` – Lit diya canvas with animation
- `#footer` – Navigation and contact

## 🔥 Firebase Backend

**Firestore Collections:**
- `stories`: stores visitor-submitted memories
- `stats/visits`: records visit count
- `diyas`: (optional future enhancement)

**Rules (Suggested):**
- Anonymous write, admin-only delete
- Rate-limiting and profanity filters on client

## 🧩 JavaScript Highlights

- Canvas rendering for diya placement and glowing animation
- Like/reaction buttons with optimistic UI
- Typewriter-style letter generator
- Light/dark mode theme toggling
- Profanity filter in both story and diya name input

## 🎨 Design Principles

- Mobile-first, responsive layout
- Accessibility-conscious color and font choices
- Emotional resonance prioritized over utility

## 🛠 Tools

- Vanilla JS (no frontend frameworks)
- Firebase SDK
- Canvas 2D API
- GitHub Discussions + README-driven docs

---
Built in memory of Alicia Cryst, by those who loved her — seen or unseen.

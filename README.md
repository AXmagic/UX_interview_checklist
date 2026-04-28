# 🎙 UX Interview Guide

A single-file, browser-based companion app for UX researchers conducting live user interviews. No backend, no installation — just open in a browser and go.

![HTML](https://img.shields.io/badge/HTML-single%20file-blue?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Language](https://img.shields.io/badge/language-Polish-orange?style=flat-square)

---

## ✨ Features

- **6-phase interview scenario** — Introduction → Context → Pain Points → Alternatives → Concept Validation → Closing
- **Jump to any phase instantly** — sidebar navigation with smooth scroll, designed for fluid conversations that don't follow a linear script
- **Per-question inline notes** — expand a note field under any question with one click
- **Phase-level notes** — a textarea at the bottom of each section for general observations
- **Global Key Insights** — a persistent notepad at the bottom for cross-cutting themes
- **Progress tracking** — per-phase mini progress bars + global progress bar
- **Copy scripts** — one-click copy for verbatim intro and closing scripts
- **Export to .txt** — downloads all checked questions and notes as a timestamped file
- **Reset session** — clears everything with a confirmation dialog
- **Cloud design** — frosted glass UI, airy blue palette, works in light mode

---

## 🚀 Usage

1. Download `index.html`
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. Fill in participant ID and date in the top bar
4. Run your interview — check off questions as you ask them, add notes inline
5. Click **Export** when done to save your notes as a `.txt` file

No internet connection required after the initial font load.

---

## 📋 Interview Phases

| # | Phase | Goal |
|---|-------|------|
| 01 | **Wprowadzenie** | Build rapport, get consent |
| 02 | **Kontekst i nawyki** | Understand current behaviour |
| 03 | **Problemy i bolączki** | Identify pain points (use 5 Whys) |
| 04 | **Alternatywne rozwiązania** | Learn how they cope without your product |
| 05 | **Walidacja pomysłu** | Gather reactions to a concept *(optional)* |
| 06 | **Zakończenie** | Leave the door open, ask for referrals |

---

## 🌐 Live Demo (GitHub Pages)

After forking, enable GitHub Pages:

> **Settings → Pages → Deploy from branch → main → / (root) → Save**

Your app will be live at:
```
https://<your-username>.github.io/<repo-name>/
```

---

## 🗂 File Structure

```
.
└── index.html   # Everything — HTML, CSS, JS in one file
```

---

## 🛠 Built with

- Vanilla HTML / CSS / JavaScript — zero dependencies
- [Lora](https://fonts.google.com/specimen/Lora) — serif display font (Google Fonts)
- [Nunito](https://fonts.google.com/specimen/Nunito) — rounded sans-serif UI font (Google Fonts)
- CSS `backdrop-filter` for frosted glass effect
- `IntersectionObserver` for active phase highlighting
- `navigator.clipboard` for copy-to-clipboard
- `Blob` + `URL.createObjectURL` for client-side export

---

## 📝 License

MIT — free to use, modify, and share.

---

*Designed for UX researchers. Built as a companion to live user interview sessions.*

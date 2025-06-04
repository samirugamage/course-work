# 🎓 Local Course Player

A sleek, Udemy-style **offline video course player** — built with plain HTML + JS, hosted on GitHub Pages, and run directly in your browser.

---

## 🌟 Overview

**Local Course Player** is a single-page web app that lets you browse, watch, and track progress in video courses stored entirely on your **local drive**.  
It runs directly from GitHub Pages and uses your browser’s modern file system access — no server setup, no install, no tracking.

---

## ✨ Features

- 📁 **Browse folder-based courses** (sections + lectures)
- 🎥 **Play `.mp4` videos** with optional `.vtt` subtitles
- ✅ **Manual checkboxes** to mark videos complete
- 🔁 **Auto-progress tracking** if you watch 90% of a video
- 📊 **Live stats**:
  - Percent completed
  - Videos watched / total
  - Minutes watched / total duration
- 📝 **Quiz support** — opens `.html` quizzes in new tabs
- 💾 **Progress saved** automatically in your browser

---

## 🧠 Use Cases

- 🧳 Watch your legally downloaded Udemy or Coursera content offline
- 🏫 Run self-hosted internal training portals (no LMS needed)
- 🎓 Browse academic or research video collections
- 📚 Build personal learning dashboards using file folders

---

## 📂 Expected Folder Structure

CourseFolder/
├── 01. Introduction/
│ ├── 01. Welcome.mp4
│ └── 01. Welcome.vtt # (optional subtitle)
├── 02. Getting Started/
│ ├── 01. Setup.mp4
│ └── quiz.html # (optional quiz page)



- Each **section** is a folder.
- Each **lecture** is a `.mp4` file.
- Subtitle tracks and quizzes are optional.

---

## 🖥️ How to Use

> You’ll need a Chromium-based browser (e.g. **Chrome**, **Edge**, **Brave**) with [File System Access API](https://developer.mozilla.org/en-US/docs/Web/API/File_System_Access_API) support.

### 🔸 Locally:
1. Clone or download this repo
2. Open `index.html` in your browser  


Click "Choose Course Folder"

Browse & play your course 📺


🔐 Privacy First
🛠 100% client-side

📦 No data leaves your device

🔒 Progress is stored only in your browser (via localStorage)


📝 License
MIT — free for personal, educational, or commercial use.

🙌 Credits
Crafted with love by Samiru Gamage
Inspired by the design and structure of modern learning platforms.

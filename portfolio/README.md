# 🚀 Shrutika Kadam — Portfolio Website

A dark, futuristic portfolio built with pure HTML, CSS, and JavaScript. No frameworks needed — just open in a browser!

---

## 📁 Folder Structure

```
portfolio/
├── index.html          ← Main HTML file (open this!)
├── css/
│   └── style.css       ← All styles
├── js/
│   └── main.js         ← Animations, interactions, typing effect
├── assets/             ← Add your images/resume here
└── README.md
```

---

## 🛠️ How to Run

### Option 1 — Open directly
Just double-click `index.html` — it works in any browser.

### Option 2 — VS Code Live Server (recommended)
1. Open the folder in VS Code
2. Install the **Live Server** extension
3. Right-click `index.html` → **Open with Live Server**
4. It opens at `http://localhost:5500`

---

## ✏️ How to Customize

### 1. Add Your Resume
- Place your resume PDF as `assets/resume.pdf`
- The "Download Resume" button already links to it

### 2. Update Project GitHub Links
In `index.html`, find each modal section and replace:
```html
<a href="https://github.com/shrutika3223" target="_blank">
```
with your specific repo URLs.

### 3. Add Profile Photo (Optional)
Replace the emoji in:
```html
<span class="avatar-emoji">👩‍💻</span>
```
with an `<img>` tag pointing to your photo.

### 4. Update Live Demo Links
Search for `href="#"` inside `.modal-actions` and replace with your deployed URLs.

---

## 🎨 Features

- ✅ Particle background with connection lines
- ✅ Typing text effect (cycling roles)
- ✅ Glassmorphism cards throughout
- ✅ Smooth scroll reveal animations
- ✅ Sticky navbar with blur effect
- ✅ Custom cursor glow
- ✅ Project modals (click any project card)
- ✅ Animated skill progress bars
- ✅ Fully responsive (mobile + desktop)
- ✅ Contact form with success state
- ✅ Dark futuristic theme

---

## 🚀 Deploy (Free Options)

1. **GitHub Pages** — Push to GitHub → Settings → Pages → Deploy from main
2. **Netlify** — Drag the folder onto netlify.com/drop
3. **Vercel** — `npx vercel` in the folder

---

Built with ❤️ for Shrutika Kadam's portfolio.

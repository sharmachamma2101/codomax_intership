# 🚀 Modern Developer Portfolio — Codomax Internship

A responsive, high-performance personal developer portfolio built from scratch with **Semantic HTML5**, **Modern Vanilla CSS3**, and **Vanilla JavaScript (ES6+)**.

Designed according to the **Codomax Internship Key Objectives**.

---

## 📋 Objectives & Deliverables Met

| # | Objective | Status | Implementation Details |
|---|-----------|--------|------------------------|
| **1** | **VS Code & Project Folder Setup** | ✅ Completed | Clean project directory architecture with dedicated `assets/images/` and modular file structure. |
| **2** | **HTML & CSS Core Fundamentals** | ✅ Completed | Fully semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) + CSS variables design system. |
| **3** | **Main Portfolio Structure** | ✅ Completed | Glassmorphic sticky navigation, Hero, About, Skills, Projects, Contact, and Footer with Back-to-Top. |
| **4** | **Key Sections Designed** | ✅ Completed | Built responsive **Hero/Home**, **About Me**, **Skills**, and **Contact** sections + interactive **Projects** showcase. |
| **5** | **Personal Info, Profile Image & Styling** | ✅ Completed | Tailored for **Bhoomi Soni**, interactive 3D profile card with photo upload option, tech badges, dark/light theme switcher, and micro-interactions. |

---

## 🎨 Key Features & Highlights

1. **Rich Modern Aesthetics & 3D UI**:
   - Three.js animated interactive particle background with glowing floating orbs.
   - 3D parallax scrolling depth with rotating rings, drifting blobs, and multi-speed layers.
   - Interactive 3D tilt effect on profile card, skill cards, and project cards.
   - Curated HSL cosmic dark palette with seamless **Dark / Light theme switcher** (persisted in `localStorage`).
   - Glassmorphism effects with `backdrop-filter: blur()`.
2. **Dynamic User Experience & Skills Manager**:
   - Real-time animated **Typewriter headline**.
   - **IntersectionObserver** scroll reveal animations for sections and cards.
   - **Active Navigation Scroll Spy** + neon scroll progress bar.
   - **Skill Category Tabs** (Frontend, Backend, Framework / Tools) with empty states.
   - **Interactive Skill Addition System**: Add newly learned skills with custom category, level, color, and note.
   - **Profile Photo Customizer**: Click-to-upload custom profile photo persisted in `localStorage`.
3. **Interactive Utilities**:
   - **One-click "Copy Email"** button with checkmark transition and toast feedback.
   - **Interactive Resume Modal** with printable layout (`window.print()`).
   - **Contact Form Validation** with character counter, field highlighting, loading spinner, and toast notifications.
4. **Mobile Responsive**:
   - Fluid typography and responsive design across desktop, tablet, and mobile.
   - CSS Grid and Flexbox responsive layouts with zero overflow.
   - Animated mobile hamburger drawer with auto-close on selection.

---

## 📁 File Structure

```text
codomax intern/
├── index.html              # Semantic HTML5 with 3D UI, tabs & modals
├── style.css               # Vanilla CSS design system, dark/light variables & 3D styling
├── script.js               # Three.js background, parallax, tilt, skill manager & validation
├── README.md               # Documentation & setup guide
└── assets/
    └── images/
        ├── profile.jpg     # Developer studio portrait
        └── favicon.svg     # Monogram SVG brand favicon
```

---

## 🛠️ How to Run Locally

### Option 1: Direct File Opening
Double-click `index.html` in your file explorer to open it directly in Google Chrome, Microsoft Edge, or any modern web browser.

### Option 2: VS Code Live Server (Recommended)
1. Open the `codomax intern` folder in **Visual Studio Code**.
2. Install the **Live Server** extension (`ritwickdey.LiveServer`).
3. Right-click on `index.html` and select **"Open with Live Server"** (or click "Go Live" at the bottom right).
4. The site will launch automatically at `http://127.0.0.1:5500`.

### Option 3: Local Node / Python Server
```bash
# Using Python 3
python -m http.server 8000
```

---

## 🎓 Concepts Demonstrated

- **Semantic HTML5**: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`.
- **CSS Custom Properties**: Design tokens for theme colors, border-radius, shadows, transitions.
- **CSS Grid & Flexbox**: Two-column responsive hero, auto-fit skill cards grid, form layout.
- **3D & Parallax**: Three.js WebGL particle scene, depth layer transforms on scroll, 3D card tilt.
- **Media Queries**: Responsive breakpoints for seamless viewing on phones, tablets, and monitors.
- **Accessibility & UX**: ARIA attributes, semantic roles, focus outlines, contrast compliance.

---

*Created with ❤️ by **Bhoomi Soni** for the **Codomax Internship Program**.*

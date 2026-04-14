# 🎨 Modern Minimalist Portfolio Template

> A stunning, **Modern Minimalist** single-page portfolio template featuring **Swiss Design principles**, clean typography, and smooth micro-interactions. Perfect for developers, designers, and creatives who want a professional, content-first presence.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

## ✨ Design Philosophy

This template isn't just code; it's a study in **Modern Minimalist** and **Swiss Design** aesthetics, tailored for the tech industry.

### 🎨 Core Style Attributes

| Attribute | Description |
| :--- | :--- |
| **Visual Language** | **Clean Tech & Swiss Style**: Emphasis on grid systems, asymmetry, and negative space to let content breathe. |
| **Typography** | **Hierarchy-Driven**: Uses *DM Sans*, *Inter*, and *Montserrat* for a geometric, highly readable, and modern feel. |
| **Color Palette** | **Professional Neutrals**: Dominantly gray tones (`#F3F4F6`, `#1F2937`) with a striking **Teal Accent** (`#18778C`) for focus points. |
| **Motion** | **Subtle Micro-interactions**: Smooth fade-ins, floating avatar animations, and number counters that engage without distracting. |
| **Layout** | **Responsive Grid**: Fluid CSS Grid and Flexbox layouts that adapt seamlessly from mobile to ultra-wide desktops. |

### 🖌️ Aesthetic Breakdown

*   **Minimalism**: Stripped of unnecessary decorations. Every element serves a functional purpose.
*   **Glassmorphism Hints**: Subtle use of transparency and blur in navigation and cards (optional via CSS).
*   **Card-Based UI**: Projects and skills are presented in clean, shadow-lifted cards for depth.
*   **Iconography**: Integrated **Phosphor Icons** for a consistent, rounded, and friendly visual language.

---

## 🚀 Features

*   **📱 Fully Responsive**: Looks perfect on Mobile, Tablet, and Desktop.
*   **🌌 Dark/Light Ready**: Built on a neutral foundation easy to theme.
*   **⚡ Zero Dependencies**: Pure HTML, CSS, and Vanilla JavaScript. No build steps required.
*   **🔗 Dynamic Integrations**: Ready-to-connect GitHub API hooks for live stats.
*   **🎭 Smooth Animations**: CSS transitions and keyframe animations for a polished feel.
*   **🧩 Modular Structure**: Easy to swap out sections (About, Skills, Contact) without breaking the layout.

---

## 🛠️ Tech Stack

This template relies on modern web standards without the bloat of heavy frameworks.

*   **Structure**: Semantic HTML5
*   **Styling**: Advanced CSS3 (Variables, Grid, Flexbox, Keyframes)
*   **Logic**: Vanilla ES6+ JavaScript
*   **Icons**: Phosphor Icons (via CDN)
*   **Fonts**: Google Fonts (DM Sans, Inter, Montserrat)

---

## 📦 Installation & Usage

Since this is a static template, there is no installation process. Just download and edit.

1.  **Clone or Download**
    ```bash
    git clone https://github.com/yourusername/modern-portfolio-template.git
    cd modern-portfolio-template
    ```

2.  **Customize Content**
    Open `index.html` in your favorite code editor.
    *   Update the **Hero Section** with your name and title.
    *   Modify the **Color Variables** in the `<style>` block to match your brand.
    *   Replace placeholder text in the **About** and **Skills** sections.

3.  **Deploy**
    Drag and drop the folder into **Netlify**, **Vercel**, or push to **GitHub Pages**.

---

## 📁 File Structure

```text
.
├── index.html          # Main HTML structure & embedded CSS/JS
├── assets/             # (Optional) Folder for local images if not using URLs
├── README.md           # Documentation
└── LICENSE             # MIT License
```

---

## 🎨 Customization Guide

### Changing the Color Theme
Locate the `:root` variables in the CSS section of `index.html`:

```css
:root {
  --primary-color: #18778C; /* Change this Teal to your brand color */
  --bg-color: #F9FAFB;
  --text-main: #111827;
  --text-secondary: #6B7280;
}
```

### Swapping Fonts
The template uses Google Fonts. To change them, update the `<link>` in the `<head>` and the `font-family` in CSS:

```css
body {
  font-family: 'Inter', sans-serif; /* Change to 'Roboto', 'Poppins', etc. */
}
```

---

<p align="center">Made with ☕ and Clean Code</p>

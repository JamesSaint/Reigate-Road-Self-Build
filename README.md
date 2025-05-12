# 🏡 Reigate Road Self Build

**A clean, elegant, and modular HTML5/Bootstrap 5 website for documenting, showcasing, and managing a personal self-build project.**

This repository powers the [Reigate Road Self Build site](https://jamessaint.github.io/Reigate-Road-Self-Build/), a minimalist and stylish personal portal focused on clarity, structure, and refined visual consistency. Built with long-term extensibility in mind, it’s designed as a living hub for the self-build journey of James Saint.

---

## 🔍 Features

- **Fully static HTML5**: Fast, secure, and deployment-ready on GitHub Pages or any web host.
- **Bootstrap 5 Framework**: Responsive across all devices, using the latest grid and utility systems.
- **Embedded custom CSS**: Typography, button styles, layout spacing, and visual treatments are tailored using the `style.css` file.
- **Modular boxy layout**: Each section is treated as a modular “card” or “container” for clarity and UX consistency.
- **Titillium Web font**: Used globally for a modern, elegant typeface across all components.
- **Semantic structure**: Uses `<section>`, `<article>`, and ARIA labels for accessibility and SEO readiness.

---

## 📁 Project Structure

```
/
├── index.html                   # Main homepage layout
├── style.css                   # Embedded styling used across all pages
├── /img/                       # Image assets
├── /components/ (optional)    # For reusable HTML snippets (if used)
├── README.md                   # This file
└── .github/workflows/         # Optional: GitHub Pages deployment workflows
```

---

## 🎨 Styling Guide

All styles follow the embedded `style.css` file, which is publicly hosted and source-controlled at:

🔗 [https://github.com/JamesSaint/Reigate-Road-Self-Build/blob/main/style.css](https://github.com/JamesSaint/Reigate-Road-Self-Build/blob/main/style.css)

### Key Styling Notes:

- **Font**: `Titillium Web`, loaded via Google Fonts or bundled.
- **Buttons**: `.btn-sacred` class for consistent gold-accented CTA buttons.
- **Navigation**: Deep violet navbar with gold text for spiritual and elegant contrast.
- **Containers**: Consistent use of `.container`, `.row`, and `.col` for clean grid layout.
- **Responsive**: All layouts are mobile-first and scale gracefully with Bootstrap 5 utilities.
- **Color Palette**:
  - Deep Violet `#3a005a`
  - Gold `#d4af37`
  - White and neutral grey tones for clean spacing

---

## 🚀 Getting Started

### To View Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/JamesSaint/Reigate-Road-Self-Build.git
   cd Reigate-Road-Self-Build
   ```

2. **Open `index.html` in any browser**

   No build process needed — this is a static site.

### To Deploy on GitHub Pages

1. Push your changes to the `main` or `gh-pages` branch.
2. Enable GitHub Pages in the repo settings.
3. Your site will be live at:
   ```
   https://your-username.github.io/Reigate-Road-Self-Build/
   ```

---

## 💡 Customisation & Extension

This site is designed to be a base for expansion — you can:

- Add more pages (e.g., `project-timeline.html`, `gallery.html`, etc.)
- Use modular `<div class="card">` containers for updates
- Embed PDFs, site plans, or forms as needed
- Maintain styling consistency via `style.css` only

---

## 📸 Screenshots

(Optionally, drop in some `img/screenshots/` here if you'd like to showcase sections visually.)

---

## 🙏 Credits

- **Built by**: [James Saint](https://github.com/JamesSaint)
- **Design system**: Custom embedded CSS + Bootstrap 5
- **Font**: [Titillium Web](https://fonts.google.com/specimen/Titillium+Web)
- **Hosted on**: GitHub Pages

---

## 📌 License

This project is open-source and shared under the [MIT License](LICENSE), though elements such as personal branding and content remain proprietary.

---

> “Reigate Road Self Build is more than a website — it's a living record of intention, stewardship, and sacred home creation.”

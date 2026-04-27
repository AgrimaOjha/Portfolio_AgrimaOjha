# 🌸 Agrima Ojha — Personal Portfolio

A dark, cinematic personal portfolio website built with vanilla HTML, CSS, and JavaScript. Designed to make an impression.

**Live Site:** [agrimaojha.github.io/Portfolio_AgrimaOjha](https://agrimaojha.github.io/Portfolio_AgrimaOjha/)

---

## ✨ Features

- Custom animated cursor with a trailing ring
- Smooth scroll-triggered reveal animations
- Infinite marquee tech stack ticker
- Fully responsive layout
- Pink-accented dark theme with ambient glow blobs
- Live clock in the footer
- Zero dependencies — pure HTML/CSS/JS

---

## 🗂 Sections

| Section | Description |
|---|---|
| Hero | Name, tagline, CTA buttons, LeetCode stat |
| Marquee | Scrolling tech stack ticker |
| About | Bio with Agentic AI focus + skill categories |
| Projects | VichaarAI, HydraSol AI, ARIS, SabhaVerse |
| Education & Recognition | Timeline + PM appreciation, certifications |
| Contact | Links to email, LinkedIn, GitHub, phone |

---

## 🚀 Deployment

### Netlify Drop (fastest)
1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Rename `agrima_portfolio.html` → `index.html`
3. Drag and drop onto the page
4. Done — you get a live URL instantly

### GitHub Pages
```bash
mv agrima_portfolio.html index.html

git init
git add index.html
git commit -m "initial portfolio"
git remote add origin https://github.com/agrimaojha/Portfolio_AgrimaOjha.git
git push -u origin main
```
Live at → `https://agrimaojha.github.io/Portfolio_AgrimaOjha/`

---

## 🔧 Customisation

To update your project links, find each project card and replace the `href="#"` placeholders:

```html
<a href="YOUR_GITHUB_LINK" class="project-link">GitHub</a>
<a href="YOUR_DEMO_LINK" class="project-link">Live Demo</a>
```

To update contact links, find the contact section and replace:
```html
<a href="https://linkedin.com/in/YOUR_PROFILE" ...>
<a href="https://github.com/YOUR_USERNAME" ...>
```

---

## 🎨 Design

| Property | Value |
|---|---|
| Background | `#080a0f` |
| Pink accent | `#FF6B9D` |
| Green accent | `#7DF9AA` |
| Blue accent | `#4DC8FF` |
| Heading font | DM Serif Display |
| Body font | Syne |
| Mono font | JetBrains Mono |

---

## 📁 File Structure

```
index.html        ← entire site (single file, no build step)
README.md         ← this file
```

---

Built with 🌸 by Agrima Ojha

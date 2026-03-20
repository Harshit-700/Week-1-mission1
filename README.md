# 🖥️ Prodesk IT — Landing Page

A clean, responsive landing page for **Prodesk IT**, an IT services company. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies beyond Font Awesome icons.

🔗 **Live Demo:** [https://week-1-mission1.vercel.app/](https://week-1-mission1.vercel.app/)

---

## Screenshot of website 

 ![Screenshot](https://github.com/Harshit-700/Week-1-mission1/blob/c2ad055d2ff0a1119a011f9c2b35eae8e29cc58e/Screenshot%20(408).png)

![Screenshot](https://raw.githubusercontent.com/Harshit-700/Week-1-mission1/16dfde4ef8e7610c0bfc737319fca2357e4bf1da/Screenshot%20(409).png)


---

## 📁 Project Structure

```
prodesk-it/
├── index.html       # Main HTML structure
├── style.css        # All styling + dark mode + responsive
└── script.js        # Theme toggle + hamburger menu
```

---

## ✨ Features

- **Responsive Design** — Works across desktop, tablet, and mobile
- **Dark Mode Toggle** — Switch between light 🌙 and dark ☀️ themes with a single click
- **Hamburger Menu** — Collapsible nav on small screens (≤600px)
- **Sticky Header** — Navigation stays visible while scrolling
- **Hover Animations** — Cards lift on hover; buttons scale on interaction
- **Social Footer** — Links to Facebook, X (Twitter), Instagram, and LinkedIn
- **No Build Tools** — Pure HTML/CSS/JS, zero dependencies (except Font Awesome CDN)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/prodesk-it.git
cd prodesk-it
```

### 2. Open in browser

Just open `index.html` directly in your browser — no server required.

```bash
# Or use VS Code Live Server / any static server
npx serve .
```

---

## 🧩 Sections

| Section | Description |
|---------|-------------|
| **Header** | Sticky nav with logo, links, dark mode toggle, and hamburger menu |
| **Hero** | Full-height banner with gradient background and CTA button |
| **Services** | 3-column card grid — SEO, Web Dev, Digital Marketing |
| **Footer** | Copyright text + social media icon links |

---

## 🎨 Design Tokens

| Property | Value |
|----------|-------|
| Primary Font | Arial, sans-serif |
| Primary Color | `#3f76f0` |
| Hero Gradient | `#dbeafe` → `#93c5fd` |
| Background | `#F1EDED` |
| Footer BG | `#202937` |
| Dark BG | `#111827` |

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout |
|------------|--------|
| `> 900px` | 3-column service grid |
| `≤ 900px` | 2-column service grid |
| `≤ 600px` | Single column, hamburger menu |

---

## 🌙 Dark Mode

Click the **🌙** button in the navbar to toggle dark mode. The theme applies across all sections using a `.dark` class on the `<body>` element.

---

## 🛠️ Built With

- **HTML5** — Semantic markup
- **CSS3** — Grid, Flexbox, transitions, media queries
- **Vanilla JavaScript** — DOM manipulation, event listeners
- **[Font Awesome 6](https://fontawesome.com/)** — Social media icons (CDN)
- **[Vercel](https://vercel.com/)** — Deployment

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

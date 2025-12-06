# 🧘 Harmony — A Responsive Guide to Mental Well-being & Breathing

Click **[here to explore the live website](https://ayinuer.github.io/harmony-meditation-site/harmony-meditation-site/index.html)**.

**Project Description:**  
Harmony is a responsive, soothing website designed to offer short, accessible breathing practices that help users anchor calm and reduce daily stress. It follows a mobile-first philosophy, offering a clean, elegant interface with strong UX and modern design principles.

---

## 🖼️ Project Visual Showcase

A key visual showing the site’s adaptability across desktop, tablet, and mobile screens.

![Harmony Responsive Devices Mockup](https://your-image-hosting-service.com/path/to/your/responsive-devices-mockup.png)

---

## 📋 Table of Contents

- [Website Access](#website-access)
- [Goals and Vision](#goals-and-vision)
- [Tech Stack & Design Implementation](#tech-stack--design-implementation)
  - [Tech Stack](#tech-stack)
  - [Color Palette](#color-palette-css-variables)
- [Responsive Design and UX Details](#responsive-design-and-ux-details)
  - [Layout and Structure](#1-layout-and-structure)
  - [Page-Specific UX & Styling](#2-page-specific-ux--styling)
- [User Stories and Acceptance Criteria](#user-stories-and-acceptance-criteria)
- [Known Issues and Future Updates](#known-issues-and-future-updates)
- [Setup and Local Run](#setup-and-local-run)

---

## 🚀 Website Access

| Link Type | URL | Description |
|----------|-----|-------------|
| **Live Demo** | **https://ayinuer.github.io/harmony-meditation-site/harmony-meditation-site/index.html** | Opens the published GitHub Pages site. |
| **Code Repository** | **https://github.com/Ayinuer/harmony-meditation-site** | Full source code for cloning and contribution. |

---

## 🎯 Goals and Vision

| Goal Category | Detailed Description |
|---------------|----------------------|
| **Core Mission** | To make mindfulness a natural part of daily life by providing short, science-backed breathing practices free of jargon and distraction. |
| **Target Audience** | Busy professionals and students (ages 20–45) experiencing moderate stress, and beginners exploring mindful breathing. |
| **User Goals** | 1) Start a practice in under 5 minutes. 2) Understand breathwork techniques easily. 3) Build daily micro-habits. |

---

## 💻 Tech Stack & Design Implementation

### Tech Stack

- **HTML5** — semantic structure for `index.html`, `practice.html`, `about.html`, `contact.html`.
- **CSS3** — modular architecture via `/css/styles.css`.
- **Bootstrap 5.3.3** — responsive grid, layout utilities, and components.
- **Typography:** Taviraj & Inter.
- **Icons:** Font Awesome 6.5.1.

### Color Palette (CSS Variables)

| Variable Name | Color Value | Usage |
|---------------|-------------|--------|
| `--primary` | `#4ca89a` | Buttons, links, primary highlights |
| `--soft-bg` | `#e9f5f2` | Background and soft UI sections |
| `--text-dark` | `#2C3E50` | Body text & headings |
| `--card-bg` | `#ffffff` | Cards and containers |
| `--muted` | `#607D8B` | Secondary text |

---

## 📱 Responsive Design and UX Details

### 1. Layout and Structure

- Mobile-first approach.
- Bootstrap grid with consistent `g-4` spacing.
- Custom hamburger navigation using the checkbox toggle method for lightweight performance.

### 2. Page-Specific UX & Styling

| Page | UX Feature | CSS Detail |
|------|------------|------------|
| **Home** | Gradient overlay for readability | `linear-gradient` over hero image |
| **Practice** | Filter pills (categories) | Hover lift via `transform: translateY(-3px)` |
| **About** | Reordered content on mobile | Bootstrap `order-md-*` |
| **Contact** | Icon-enhanced form inputs | Font Awesome + Bootstrap validation |

### 3. Image Path Strategy
- CSS uses: `url('../assets/...')`
- HTML uses: `src="assets/..."`
- Consistent relative paths ensure GitHub Pages compatibility.

---

## ✅ User Stories and Acceptance Criteria

| User Story | Acceptance Criteria |
|------------|----------------------|
| View value immediately | Clear hero headline + CTA visible on load |
| Know practice duration | Duration badges visible on practice cards |
| Filter practices | Clicking filter pills updates card visibility |
| Learn instructions easily | Step-by-step list reveals on button click |

---

## 🐛 Known Issues & Future Improvements

### Current Issues
- CSS-based filter not scalable for large libraries.
- Mobile scroll shift on some browsers when opening the menu.

### Future Enhancements
- User streak tracking (LocalStorage).
- Optional ambient audio.
- User accounts and saving favorites.

---

## 🛠️ Setup and Local Run

1. `git clone https://github.com/Ayinuer/harmony-meditation-site.git`
2. `cd harmony-meditation-site`
3. Open `index.html` in your browser.

---

**Creator:** Ayinuer Aihaiti  
**License:** © 2025 Harmony — Mental Well-being & Breathing Guide
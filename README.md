# 🧘 Harmony — A Responsive Guide to Mental Well-being & Breathing

[![W3C HTML Status](https://img.shields.io/badge/HTML-Valid-brightgreen.svg)](./VALIDATION_EVIDENCE.md) 
[![W3C CSS Status](https://img.shields.io/badge/CSS-Valid-brightgreen.svg)](./VALIDATION_EVIDENCE.md)
[![License](https://img.shields.io/badge/License-%C2%A9%202025-blue.svg)](https://ayinuer.github.io/harmony-meditation-site/harmony-meditation-site/index.html) 
[![Version Control](https://img.shields.io/badge/Version-Git%20Controlled-E94E31.svg)](https://github.com/Ayinuer/harmony-meditation-site)

Click **[here to explore the live website](https://ayinuer.github.io/harmony-meditation-site/harmony-meditation-site/index.html)**.


**Project Description:** Harmony is a responsive, soothing website designed to offer short, accessible breathing practices that help users anchor calm and reduce daily stress. It follows a mobile-first philosophy, offering a clean, elegant interface with strong UX and modern design principles.

---

## 📋 Table of Contents

* [**🎯 Project Goals & Vision**](#-project-goals--vision)
* [**🖼️ Visual & Technical Showcase**](#%EF%B8%8F-visual--technical-showcase)
    * [1. Responsive Adaptability](#1-responsive-adaptability)
    * [2. Full Site View](#2-full-site-view)
    * [3. Key Feature: Practice Filtering](#3-key-feature-practice-filtering)
* [**💻 Tech Stack & Design System**](#-tech-stack--design-system)
    * [W3C Validation Status](#w3c-validation-status)
    * [Color Palette (CSS Variables)](#color-palette-css-variables)
* [**📱 Responsive Design and UX Details**](#-responsive-design-and-ux-details)
* [**✅ User Stories & Features**](#-user-stories--features)
* [**🛠️ Setup & Local Run**](#-setup--local-run)
* [**🐛 Known Issues & Future Plans**](#-known-issues--future-plans)
* [**🚀 Deployment, Quality & Credits (LO3 & LO4)**](#-deployment-quality--credits-lo3--lo4)

---

## 🎯 Project Goals & Vision

| Category | Detailed Description |
| :--- | :--- |
| **Core Mission** | To demystify mindfulness by offering short, science-backed breathing practices, eliminating jargon to facilitate the building of daily micro-habits. |
| **Target Audience** | Stressed professionals and students (ages 20–45), prioritizing beginners seeking simple, immediate stress-reduction tools. |
| **User Goals** | 1) Initiate a practice in under 5 minutes. 2) Easily grasp breathwork instructions. 3) Consistently integrate the tool into their daily routine. |

---

## 🖼️ Visual & Technical Showcase

This section details the critical design and development work behind the site's most impactful visuals.

### 0. Site Quality & Validation (Screenshots)

These images serve as quick visual evidence of the project's technical quality and adherence to web standards.

#### 🛡️ W3C HTML Validation Result
Screenshot confirming that the main HTML code has successfully passed validation against **World Wide Web Consortium (W3C)** standards. This signifies a commitment to **cross-browser consistency**, **best coding practices**, and a strong foundation for **accessibility**.
![Screenshot of the W3C Validator showing the Harmony index.html page is valid.](harmony-meditation-site/assets/w3c-html-validation.png)

---

### 1. Responsive Adaptability

This visual demonstrates the structural integrity of the site across three major breakpoints (desktop, tablet, and mobile).

![Harmony Responsive Devices Mockup]
![alt text](harmony-meditation-site/assets/responsive-devices-mockup.png)
**Implementation Details:**
* **Mobile-First Development:** The entire site architecture was prioritized for narrow viewports, minimizing reflow and load times for mobile users.
* **Bootstrap Grid System:** **Bootstrap 5.3.3** was implemented for its robust, consistent grid, ensuring elements like the navigation and footer maintain alignment regardless of screen size.
* **Custom Navigation:** The mobile hamburger menu was engineered using a lightweight **pure-CSS checkbox toggle method**, avoiding JavaScript dependencies for faster, more reliable performance.

---

### 2. Full Site View (Four Main Pages)

This series of full-page screenshots provides a complete visual overview of the user interface, demonstrating the consistent design and structure across the primary pages.


#### Home Page (`index.html`)
Showcases the hero section, main mission statement, and key Call-to-Action (CTA) elements.
Full screenshot of the Harmony website Home Page.


![alt text](harmony-meditation-site/assets/home.page.view1.png)


![alt text](harmony-meditation-site/assets/home.page.view2.png)




#### Practice Page (`practice.html`)
Displays the library of breathwork practices, showing the use of filter pills and the card layout for content organization.
Full screenshot of the Harmony website Practice Page.


![alt text](harmony-meditation-site/assets/practice.page.view1.png)


![alt text](harmony-meditation-site/assets/practice.page.view2.png)




#### About Page (`about.html`)
Illustrates the project's purpose and creator information, focusing on typography and content hierarchy.


![Full screenshot of the Harmony website About Page.](harmony-meditation-site/assets/about.page.view.png)




#### Contact Page (`contact.html`)
Highlights the responsive form design and input validation elements using Bootstrap utilities.


![Full screenshot of the Harmony website Contact Page.](harmony-meditation-site/assets/contact.page.view.png)

---

### 3. Key Feature: Practice Filtering

A screenshot showing the 'Practice' page, highlighting the filter controls and interactive practice cards.

![alt text](harmony-meditation-site/assets/practice.page3.png)



**Implementation Details:**
* **Interactive Filtering:** Practices are categorized using filter pills (e.g., "Calm," "Energy"). This functionality utilizes pure CSS and attribute selectors (or lightweight JavaScript if used) to control the visibility of cards, offering a smooth, instant filtering experience.
* **UX Micro-Animation:** A subtle **`transform: translateY(-3px)`** property was applied via CSS to the practice cards on hover, providing clear, tactile visual feedback to the user before they commit to clicking a card.

---

## 💻 Tech Stack & Design System

### Tech Stack

- **HTML5** — semantic structure for `index.html`, `practice.html`, `about.html`, `contact.html`.
- **CSS3** — modular architecture via `/css/styles.css`.
- **Bootstrap 5.3.3** — responsive grid, layout utilities, and components.
- **Typography:** Taviraj & Inter.
- **Icons:** Font Awesome 6.5.1.

### W3C Validation Status
The project's primary stylesheet has been verified to adhere to web standards.

[![Valid CSS!](https://jigsaw.w3.org/css-validator/images/vcss)](https://jigsaw.w3.org/css-validator/validator?uri=https://ayinuer.github.io/harmony-meditation-site/harmony-meditation-site/css/styles.css&profile=css3&usermedium=all)



### Color Palette (CSS Variables)

A visual guide to the colors used across the Harmony website:


![alt text](harmony-meditation-site/assets/colorpalette.jpg)

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

## ✅ User Stories & Features

| User Story | Acceptance Criteria |
| :--- | :--- |
| **As a busy user, I want to view value immediately** | A clear hero headline and Call-to-Action (CTA) are positioned high on the Home page, visible upon initial page load. |
| **As a beginner, I need to know the commitment** | Duration badges are visible on all practice cards, allowing quick decision-making. |
| **As an explorer, I want to quickly find relevant practices** | Clicking filter pills instantly updates the visible practice cards, filtering the library without requiring a page reload. |
| **As a new user, I need to learn instructions easily** | Detailed, step-by-step instructions are hidden and revealed via a button click, promoting focused reading and reducing initial cognitive load. |

---

## 🛠️ Setup & Local Run

To clone and run the project locally, execute the following commands in your terminal:

1.  Clone the repository: `git clone https://github.com/Ayinuer/harmony-meditation-site.git`
2.  Navigate to the directory: `cd harmony-meditation-site`
3.  Open `index.html` in your preferred web browser.

---

## 🐛 Known Issues & Future Plans

### Current Issues
* The current pure CSS filtering mechanism has limited scalability and would need replacement with JavaScript for a massive library.
* A minor mobile viewport scroll shift is observed on some browsers when the custom navigation menu is toggled.

### Future Enhancements
* Implement user streak tracking using **LocalStorage** to encourage daily use.
* Integrate optional ambient audio into practice sessions for enhanced immersion.
* Develop user account functionality to allow saving and tracking favorite practices.

---

## 🚀 Deployment, Quality & Credits (LO3 & LO4)

### 1. Project Quality and Validation Evidence (LO2 Proof)

All core testing evidence is compiled in a separate document:

* **View Full Validation Proof:** **[Click here to view all W3C HTML/CSS and Lighthouse performance test screenshots.](./VALIDATION_EVIDENCE.md)**
    
    * **Lighthouse Performance:** A separate screenshot of the Lighthouse report (Performance, Accessibility, Best Practices, SEO) has been completed and reviewed.

### 2. Deployment and Maintainability (LO3 Proof)

The project was managed using Git for version control and deployed to GitHub Pages.

* **Deployment Status:** The final version deployed to GitHub Pages matches the development version exactly.
* **Code Cleanliness:** All commented-out code was removed before deployment, and clean, commented code remains.
* **Functional Integrity:** All internal links and interactive elements function correctly.

### 3. Attribution and Licensing (LO4 Documentation)

* **Creator:** Ayinuer Aihaiti
* **Proper Attribution:** All external code and assets are used with appropriate attribution and/or license.
* **🤖 Declaration of use of AI:** I utilized **[Specific AI Tool Name, e.g., Gemini, ChatGPT]** for the purpose of [e.g., generating boilerplate text, code explanation, or debugging assistance].
* **License:** © 2025 Harmony — Mental Well-being & Breathing Guide

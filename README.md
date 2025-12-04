# 🧘 Harmony — A Responsive Guide to Mental Well-being & Breathing

**Project Description:** Harmony is a website designed to offer accessible, short-form breathing and mindfulness practices, helping users anchor calm and alleviate the stress of modern life. It follows a mobile-first philosophy, prioritizing a clean, elegant visual experience and superior user experience (UX).

---

## 🚀 Website Access

| Link Type | URL | Description |
| :--- | :--- | :--- |
| **Live Demo** | [Explore the Live Site Here](index.html) | Open the main landing page in your browser. |
| **Code Repository** | **[GitHub Repository: Ayinuer/harmony-meditation-site](https://github.com/Ayinuer/harmony-meditation-site)** | Access and clone the complete project source code. |

---

## 🖼️ Project Visual Showcase

Please replace the placeholders below with the **public URLs** of your images (e.g., links obtained after uploading to GitHub, Imgur, or a similar image host).

### 1. Responsive Devices Mockup

A key visual showing the site's adaptability across desktop, tablet, and mobile screens.

![Harmony Responsive Devices Mockup](https://your-image-hosting-service.com/path/to/your/responsive-devices-mockup.png)

### 2. Key Features Screenshot

A screenshot showcasing the three core value cards from the "Why Choose Harmony?" section on the home page.

![Harmony Key Features Section](https://your-image-hosting-service.com/path/to/your/feature-cards-screenshot.png)

---

## 🎯 Goals and Vision

| Goal Category | Detailed Description |
| :--- | :--- |
| **Core Mission** | To make mindfulness a natural part of daily life by providing short, science-backed breathing practices free of jargon and distraction. |
| **Target Audience** | Primarily busy professionals and students (ages 20-45) experiencing moderate stress, and secondary users who are beginners in mindfulness. |
| **User Goals** | 1. Quickly find and begin a practice lasting five minutes or less. 2. Easily understand complex breath techniques (e.g., 4-7-8, Box Breathing). 3. Be encouraged to form micro-habits of daily, consistent practice. |

---

## 💻 Tech Stack & Design Implementation

### Tech Stack

* **HTML:** Semantic structure for four main pages (`index.html`, `practice.html`, `about.html`, `contact.html`).
* **CSS:** Highly customized styling and architecture managed in `css/styles.css`.
* **Framework:** **Bootstrap v5.3.3**, used for the responsive grid, navigation components, and general UI utility classes.
* **Typography:** **Taviraj** (for elegant headings) and **Inter** (for clean, readable body text).
* **Icons:** **Font Awesome v6.5.1**, used for contact forms and feature icons.

### 🎨 Color Palette (CSS Variables)

The project utilizes CSS Custom Properties (`:root`) for a soothing, consistent look based on a Mint/Teal theme.

| Variable Name | Color Value | Usage Description |
| :--- | :--- | :--- |
| `--primary` | `#4ca89a` (Teal/Mint) | Main brand color for links, buttons, and primary titles. |
| `--soft-bg` | `#e9f5f2` (Light Mint) | Primary page background and secondary sections (e.g., footer). |
| `--text-dark` | `#2C3E50` (Dark Navy) | Headings and main body text for high contrast readability. |
| `--card-bg` | `#ffffff` | Background for navigation and feature/practice cards. |
| `--muted` | `#607D8B` (Blue-Gray) | Soft auxiliary text (e.g., quotes, small footnotes). |

---

## 📱 Responsive Design and UX Details

### 1. Layout and Structure

* **Mobile-First Design:** The entire layout is structured to prioritize the small screen experience first, then scaling up.
* **Grid System:** The **Bootstrap grid** is heavily used for all content sections, utilizing `row g-4` for consistent gutter spacing and easy content reordering.
* **Custom Navigation:** Implemented a pure CSS/HTML **Hamburger Toggle** (`input[type="checkbox"]` hack) to control the slide-in/slide-out mobile menu (`< 900px`), ensuring high mobile performance without JavaScript dependencies.

### 2. Page-Specific UX & Styling

| Page | Key UX Elements | Specific CSS Implementation |
| :--- | :--- | :--- |
| **Home (`index.html`)** | Hero section uses a dark color gradient over the background image to ensure the light text (`--text-light`) remains readable. | Custom `linear-gradient` is applied via CSS directly over `url('../assets/hero.jpg')`. |
| **Practice (`practice.html`)** | Features **Filter Pills** (using `nav-pills`) to allow users to quickly filter practices by focus (e.g., "For Relaxation," "Stress Relief"). | Practice Cards (`.practice-card`) use `transform: translateY(-3px);` on hover for a subtle lift effect. |
| **About (`about.html`)** | The text and photo sections are reordered on mobile using Bootstrap's `order-md-*` classes, ensuring the image is positioned logically across breakpoints. | The `.about-photo` is styled with `border: 4px solid var(--soft-bg);` and `box-shadow` for visual depth. |
| **Contact (`contact.html`)** | The contact form uses **Font Awesome icons** (`<i class="fa fa-user"></i>`) within the input groups to enhance clarity. | Form features built-in **Bootstrap form validation** (`needs-validation`) for immediate user feedback. |

### 3. Image Pathing Strategy (Critical Detail)

All CSS background images and HTML image tags rely on **relative paths**. Given the provided structure:

* **CSS Paths:** Since `styles.css` is in the `css/` folder, it must travel one level up (`..`) to reach the `assets/` folder.
    * **Correct Path Example in CSS:** `url('../assets/hero.jpg')`
* **HTML Paths:** Since `index.html`, `practice.html`, etc., are in the root `spiritual-site/` folder, they access assets directly.
    * **Correct Path Example in HTML:** `<img src="assets/breathing-meditation.jpg">`

---

## ✅ User Stories and Acceptance Criteria

| User Story | Acceptance Criteria |
| :--- | :--- |
| **As a first-time user, I want to see the main value proposition immediately**, so I know what the site is about. | **GIVEN** I am on the Home page (`index.html`) **WHEN** the page loads **THEN** a clear headline and a "Start a Practice" CTA button are prominent in the Hero section. |
| **As a busy user, I want to know how long a practice takes**, so I can fit it into my schedule. | **GIVEN** I view any practice card on the Practice page **WHEN** I read the card summary **THEN** a colored badge clearly displays the **Duration** (e.g., "5 Min," "Repeat Until Calm"). |
| **As a returning user, I want to quickly find a practice for my current need**, so I don't waste time. | **GIVEN** I am on the Practice page (`practice.html`) **WHEN** I click a filter pill (e.g., "Stress Relief") **THEN** only the relevant practice cards are shown. |
| **As a beginner, I want clear, simple instructions** for a complex practice like 4-4-6 Relax Breath. | **GIVEN** I view the Practice page **WHEN** I click the "View Step-by-Step Instructions" button **THEN** a detailed, numbered list of steps is revealed. |

---

## 🛠️ Setup and Local Run

To get a copy of this project up and running locally:

1.  Clone the repository: `git clone https://github.com/Ayinuer/harmony-meditation-site.git`
2.  Navigate to the project directory: `cd harmony-meditation-site`
3.  Open **`index.html`** in your preferred web browser.

***
**Creator:** Ayinuer Aihaiti
**License:** &copy; 2025 Harmony — Mental Well-being & Breathing Guide

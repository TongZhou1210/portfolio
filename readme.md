# Tong Zhou – Portfolio Website

## 📌 Project Overview
This project is **Lab 3: Student Portfolio** for the CST3106 Web Development course.  
The goal is to build a personal portfolio website using **HTML** and **CSS**, enhancing the student’s resume into a professional online portfolio.  
The website will be updated throughout the semester with new projects and activities.

---

## 🏗️ Structure & Features

### 1. Structural Elements
- **Navigation Bar (Header)**  
  Fixed navigation at the top with links to:
    - about me
    - Education
    - Work Experience
    - Portfolio(recurring component for new assignments)
    - Rednote (external blog link)
    - Contacts (email link)

- **Hero Section**
    - Full-screen background (Shanghai skyline image).
    - Semi-transparent dark overlay for contrast.
    - Main heading: “I’M TONG ZHOU”.
    - Subtitle: Brand Manager · Digital Health Student.

- **Footer**  
  Displays copyright with dynamic year.

---

### 2. Overlay Sections (Reusable Components)
Each section is designed as an **overlay card**, activated by navigation links:
- **About Me** – Personal introduction and background.
- **Education** – Degrees and core courses.
- **Work Experience** – Previous roles with responsibilities.
- **Portfolio** – Currently a placeholder; will be updated with projects as the semester progresses.

---

### 3. Visual Design
- **Color Palette** (defined in `styles.css` as CSS variables):
    - `--navy-900`: Dark Navy (background, hero overlay)
    - `--yellow-400`: Accent Yellow (hover, highlights)
    - `--gray-500`: Muted Gray (secondary text)
    - Neutral card background (`--card-bg`) for overlay readability

- **Fonts**
    - **Cormorant Garamond** (headings)
    - **Inter** (body text, navigation)

- **Reusable Components**
    - `.overlay-card` – standardized card style for all sections
    - `.edu-item` – reusable education/work entry style
    - `.job-list` – consistent bullet list styling
    - `.grid-2` – responsive two-column layout for Projects & Activities

---

### 4. Responsiveness
- Responsive navigation and hero text.
- Two-column layouts collapse into a single column on mobile.
- Adjusted padding and margins for smaller screens.

---

## 🚀 How to Run
1. Clone or download the repository.
2. Open `index.html` in any modern browser.
3. Navigate through the site using the top menu.
4. The **Portfolio section** will be updated with new projects as the semester progresses.

---

## 📂 File Structure
```text
portfolio/
├─ index.html                # Main HTML file
├─ styles.css                # Custom styles and design tokens
├─ images/
│  └─ shanghai-ottawa.jpeg   # Hero background image
├─ LICENSE
└─ .gitattributes
---

## ✨ Future Updates
- The **Portfolio section** is a recurring component.  
  It will be **gradually updated throughout the semester** with new projects, assignments, and activities.
- Add screenshots and media for each new project.
- Optional: Add accessibility improvements (focus states, aria-current).

---

© 2025 Tong Zhou. All rights reserved.
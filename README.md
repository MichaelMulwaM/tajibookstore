# Taji Bookstore Project

Hi! Welcome to my Taji Bookstore project. I am a junior web development student, and this is my portfolio project built with **HTML5** and **CSS**.

---

## Project Overview
Taji Bookstore is a responsive landing page for an online bookstore. The main goal of this project was to master pure CSS styling techniques, including:
- A navigation header featuring a cart badge and a theme toggle button.
- A hero section showcasing the store's motto, call-to-action button, and image banner.
- A CSS Grid product catalog displaying featured books with tags, prices in KES, star ratings, and action buttons.
- A custom CSS variable-driven Dark Mode toggle.
- A footer section with social media links and copyright information.

---

## Key Technical Features
* **Custom CSS Variables:** Built color themes using native CSS custom properties for instant background, text, and border switching.
* **Flexbox & CSS Grid Layouts:**
  * **Flexbox:** Used in the navbar, hero section, card footers, and footer controls for alignment.
  * **CSS Grid:** Applied `repeat(auto-fill, minmax(240px, 1fr))` on `.product-grid` to ensure standard responsiveness without hardcoded media queries.
* **Pure CSS Hover Effects:** Added hover micro-interactions to buttons and cards (`transform: translateY(-6px)`) with smooth CSS transitions.
* **Semantic HTML Markup:** Built using structural HTML elements (`<header>`, `<nav>`, `<section>`, `<main>`, `<article>`, `<footer`).

---

## File & Folder Structure
```text
/taji-bookstore
├── index.html        # Main HTML structure
├── style.css         # Custom CSS stylesheet (Variables, Flexbox, Grid, Dark Mode)
└── /images           # Assets folder
    ├── cover2.png
    ├── book1.jpg
    ├── book2.jpg
    ├── book3.jpg
    ├── book4.jpg
    ├── fb-icon.png
    ├── ig-icon.png
    └── x-icon.png

How to Run the Project
- Download or clone this repository to your local machine.
- Ensure index.html, style.css, and the images/ directory are in the same folder root.
- Open index.html in any modern web browser (Chrome, Firefox, Safari, Edge).

Click the Theme Toggle button in the top navigation bar to test light and dark modes.

Concepts Learned This Week
- Defining global CSS variables.
- Managing resets, box models (box-sizing: border-box), and typography defaults across a project.
- Structuring layouts with Flexbox for 1D alignments and CSS Grid for responsive product layouts.
- Understanding CSS specificity.

Challenges & Future Enhancements
- Dark Mode was a pain: Setting up the CSS variables and getting all the background colors, text, and border contrasts to switch properly without looking broken took me a really long time to figure out.
- Buttons don't go anywhere:** The "Get Started" button and the book cards aren't clickable links yet, so clicking them doesn't take you to a detailed book page or any actual destination.
- Cart buttons are useless right now:** Clicking "Add to Cart" doesn't do anything of value—the cart count in the header stays stuck at `(0)`


Created as part of Week 2 Web Development Coursework by Michael Mulwa — 2026.

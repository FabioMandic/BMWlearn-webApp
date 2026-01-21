# 🚘 BMWlearn - Interactive Car Knowledge Hub

**BMWlearn** is a web-based application designed for automotive enthusiasts to explore the history, news, and models of BMW. The project features an interactive **"Guess the Model" game**, a dynamic **searchable car catalog**, and a comprehensive overview of the company's legacy.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

##  Project Overview

This project demonstrates frontend development skills using pure **HTML, CSS, and JavaScript**. It focuses on DOM manipulation, array filtering, and responsive layout design without relying on external frameworks.

### Key Features:

* ** Guess the Model Game:** An interactive mini-game where users must identify a random BMW model from an image. Features instant feedback (Correct/Incorrect) logic.
* ** Dynamic Model Catalog:** A `models.html` page that uses JavaScript to:
    * Render a table of cars from a JSON-like array.
    * **Filter** cars by type (Sedan, SUV, Roadster, Luxury).
    * **Search** cars by name in real-time.
* ** News & History:** Dedicated pages with CSS-styled cards and a timeline layout for BMW's history (3/15 PS, 328, etc.).
* ** Company Info:** Integration of Google Maps iframe to show BMW Headquarters in Munich.

##  Tech Stack & Concepts

* **HTML5:** Semantic structure (header, nav, section, article, aside).
* **CSS3:** Custom styling variables, Flexbox for layouts, hover effects (`transform: scale`), and background image handling.
* **JavaScript (ES6+):**
    * `document.querySelector` & Event Listeners (`click`, `input`, `change`).
    * Array methods: `forEach()`, `filter()`, `map()`.
    * DOM Manipulation: Dynamically creating table rows (`document.createElement`).
    * Math logic: `Math.random()` for the game.

## 📂 Project Structure

```text
├── index.html          # Home page & "Guess the Model" game
├── models.html         # Dynamic searchable table of models
├── history.html        # Timeline of BMW history
├── news.html           # Latest news cards (M2, M4, M5, M8)
├── company.html        # About section & Google Maps
├── styles.css          # Global styles & layout
├── scripts.js          # Logic for game & table filtering
├── images/             # Folder containing car images & logos
└── README.md           # Project documentation

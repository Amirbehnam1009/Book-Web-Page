# 📘 Web Programming Course Website

A responsive and modern single-page website designed for an "Internet Engineering" or "Web Programming" course. This project was the third assignment for the Fall 2022 semester, focusing on advanced CSS and HTML techniques including CSS Grid, Flexbox, animations, and transitions.

👨‍🏫**Under the Supervision of Parham Alvani**  
🍂***Fall 2022***

[![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)


## ✨ Features

The website is structured into seven main sections as per the assignment requirements:

1.  **Responsive CSS Grid Layout:** A fluid 4-row layout built using `calc()`, `float`, and CSS variables for easy maintenance.
2.  **Animated Header:** Features a full-screen centered background image with a white border. The title text slides in on page load, and a call-to-action button has a hover effect.
3.  **Lectures Section:** Displays four semi-transparent course topic cards (HTTP, HTML/CSS, JavaScript, Go) with logos. Cards have a scale-up hover effect and sit on a multi-colored gradient overlay.
4.  **Interactive Book Gallery:** A "Related Books" section where cards flip on hover to reveal the price and a "Details" button. Clicking the button opens a modal popup with more book information and a link to purchase on Amazon.
5.  **Footer:** A two-column footer containing designer information (copyright) and a set of links with hover effects.
6.  **Fixed Navigation Menu:** A custom-styled checkbox acts as a hamburger menu icon. When clicked, it reveals a smooth, sliding navigation menu that links to the main sections of the page. The menu remains fixed on scroll.
7.  **Favicon & Title:** Custom favicon and page title for the browser tab.

## 🛠️ Built With

*   **HTML5** - For semantic structure.
*   **CSS3** - For styling, including:
    *   CSS Grid & Flexbox for layout
    *   CSS Variables for reusable values
    *   Advanced animations and transitions (`@keyframes`, `transform`, `transition`)
    *   Backdrop-filter for transparency effects
*   **GitHub Pages** - For deployment and hosting.

## 📁 Project Structure

```
Book-Web-Page/
├── index.html          # Main HTML file
├── style.css           # Main stylesheet
├── script.js           # JavaScript for modal functionality
├── images/             # Directory for all images
│   ├── background.jpg
│   ├── bg2.jpg
│   ├── http.png
│   ├── html.png
│   ├── js.png
│   ├── go.png
│   ├── book-1.jpg
│   ├── book-2.jpg
│   ├── book-3.jpg
│   └── favicon.ico
└── README.md
```

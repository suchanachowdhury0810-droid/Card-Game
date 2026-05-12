# Card-Game

A sleek, CSS-only interactive user interface component that displays a collection of images as a fanned-out deck of cards. 

## ✨ Features

* **Fanned Deck Layout:** Utilizes CSS `transform: rotate()` and absolute positioning to create a realistic, overlapping card deck aesthetic.
* **Interactive Hover States:** Hovering over any individual card dynamically brings it to the forefront of the stack using `z-index` manipulation.
* **Responsive Centering:** Uses CSS Flexbox to ensure the card deck is perfectly centered on the screen, regardless of viewport size.
* **Zero JavaScript:** The entire visual effect and interaction are achieved cleanly through pure CSS3.

## 🚀 Technologies Used

* **HTML5:** Semantic structure for the card elements.
* **CSS3:** Flexbox for layout, `z-index` for layering, and `transform-origin` with `rotate` for the fanned positioning.

## 📁 Project Structure

```text
├── index.html       # Main HTML document containing the card containers and image links
└── style.css        # Stylesheet handling all positioning, rotation, and hover logic

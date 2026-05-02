# 2048 Game (OOP Implementation)

A classic 2048 puzzle game built with modern JavaScript (ES6+) using Object-Oriented Programming principles. The game features smooth state management, score tracking, and a fully responsive interface.

## 🔗 Live Demo
[Play 2048 Game](https://igols.github.io/2048-game/)

## ✨ Key Features
* **OOP Architecture:** Core logic is encapsulated within a `Game` class for better maintainability.
* **State Management:** Handles different game statuses (`playing`, `win`, `lose`) with dynamic UI updates.
* **Keyboard Controls:** Play using Arrow keys (`Up`, `Down`, `Left`, `Right`).
* **Dynamic Styling:** Automatic tile coloring based on value using SCSS modifiers (e.g., `field-cell--1024`).
* **Score System:** Real-time score calculation during tile merging.

## 🛠 Tech Stack
* **JavaScript (ES6):** Classes, `flat()`, `map/filter` for matrix manipulation.
* **SCSS:** BEM methodology and nested styles.
* **HTML5:** Semantic table-based game field.
* **Gulp/Parcel:** Asset bundling and optimization.

## 🚀 How to Play
1. Press the **Start** button to initialize the grid.
2. Use your **Arrow Keys** to move tiles.
3. When two tiles with the same number touch, they **merge into one!**
4. Reach the **2048** tile to win!

## 💻 Installation & Setup
1. Clone the repo:
   `git clone https://github.com/igols/2048-game.git`
2. Install dependencies:
   `npm install`
3. Run project locally:
   `npm start`
4. Build for production:
   `npm run build`
5. Deploy to GitHub Pages:
   `npm run deploy`

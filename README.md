# 🎌 Sanmoku Narabe (三目並べ)

A minimalist, Japanese-themed take on the classic **Tic-Tac-Toe** game — built with **vanilla HTML, CSS, and JavaScript**.

---

## ✨ Features

* 🎯 Simple 3x3 grid with clean visuals
* 👥 Two-player mode (X vs O)
* 🏆 Win detection for all combinations
* 🟰 Draw detection when the board is full
* 🔄 Restart button to reset the game
* 🇯🇵 Japanese-inspired design with *Permanent Marker* font
* 💡 Interactive hover states and subtle visual effects

---

## 🕹️ How to Play

1. Players take turns clicking empty cells.
2. Player **X** goes first.
3. The first player to get **three in a row** (horizontal, vertical, or diagonal) wins!
4. If all cells are filled and there's no winner, it's a **draw**.
5. Click **"Restart"** to begin a new round.

---

## 🚀 Installation & Setup

To get started:

1. **Clone** or **download** the repository.
2. Ensure the following files are in the same folder:

   * `index.html`
   * `index.js`
   * `styles.css`
3. Open `index.html` in any modern browser.
4. Enjoy the game!

---

## 📁 Project Structure

```
sanmoku-narabe/
├── index.html      # Main HTML layout
├── index.js        # Game logic and interactions  
├── styles.css      # Visual styling and layout
└── README.md       # Project documentation
```

---

## 🔧 Technical Overview

* **HTML**: Semantic structure using custom `cellIndex` attributes.
* **CSS**: Responsive layout via **CSS Grid**, with thematic styling.
* **JavaScript**: Event-driven logic, real-time win/draw detection.
* **Responsive**: Mobile and desktop friendly.

---

## 🧠 Game Logic

The board state is tracked using a simple array.
The win-checking algorithm looks for matches across 8 potential lines:

* 3 horizontal rows
* 3 vertical columns
* 2 diagonals

---

## 🌟 Future Enhancements

Here are a few features planned for future updates:

* 🤖 AI opponent with difficulty levels
* 📊 Score tracking between rounds
* 🎞️ Smooth animations for moves and win sequences
* 🔊 Sound effects
* 🎨 Alternate visual themes

---

## 🌐 Browser Compatibility

Tested and working in all modern browsers that support:

* **CSS Grid**
* **ES6 JavaScript**
* **DOM manipulation**

---

## 🈶 About the Name

**Sanmoku Narabe (三目並べ)**
Literally translates to *"three-in-a-row arrangement"* — the Japanese name for Tic-Tac-Toe.
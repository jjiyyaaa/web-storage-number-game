# 3-Digit Guessing Game (Web Storage Integration)

A lightweight, interactive web-based number guessing game where players challenge themselves to find the correct 3-digit combination of the numbers "1", "2", and "3". This project explicitly demonstrates the implementation of HTML5 Web Storage (`localStorage` and `sessionStorage`) to persist gameplay states and local high scores without a backend server.

Built as a submission project for the **"Belajar Dasar Pemrograman Web"** course at Dicoding Academy.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🎮 How to Play

1. **Start the Match:** Press the **"Bermain"** button to let the system generate a secret random code (e.g., `"231"`, `"132"`).
2. **Formulate Choices:** Guess the exact 3-digit order. 
   - Each digit ("1", "2", or "3") appears **exactly once**.
   - Duplicate submissions like `"111"` or `"223"` are automatically invalid combinations by game rules.
3. **Check Results:** Inputting 3 digits automatically triggers verification. If it's wrong, your session attempt counter increases, and you can clear data or keep trying!

---

## ✨ Key Features

- **State Persistence via Web Storage:**
  - `sessionStorage`: Tracks the hidden correct answer and current wrong attempts during the active browser session. It resets automatically upon closing or reloading the page.
  - `localStorage`: Saves long-term player achievements globally, tracking total successful combinations solved and the highest number of failed attempts on record.
- **Dynamic DOM Manipulations:** Utilizes native JavaScript Event Listeners (`load`, `click`, `beforeunload`) to alter structural elements on-the-fly and toggle interface screens (`hidden` attributes).
- **Fisher-Yates Shuffle Variant:** Implements an array shuffling method algorithmically within `getAnswer()` to produce purely randomized, non-repeating digit answers.
- **Data Flush System:** Contains a **"Hapus semua data"** switch to wipe out all stored application logs completely in one click.

---

## 🛠️ Tech Stack

- **Markup:** HTML5 (Forms, Layout grids, Structural containers)
- **Styling:** Vanilla CSS3 (Inline layouts, Float systems, custom button transitions)
- **Scripting Logic:** Pure Vanilla JavaScript (ES6+)

---

## 🚀 Getting Started

Follow these instructions to experience the game locally:

### Prerequisites
A modern desktop web browser that supports HTML5 Web Storage capabilities (Chrome, Firefox, Safari, Edge).

### Installation & Run
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/web-storage-number-game.git](https://github.com/your-username/web-storage-number-game.git)
2. **Navigate into the project directory:**
    ```bash
    cd web-storage-number-game
3. **Open the project:**
    Simply open the index.html file inside your preferred web browser.

## 📂 Project Structure
├── index.html                  # Single-file entry point containing HTML, CSS, and JS Logic
└── README.md                   # Project documentation

## 👩‍💻 Author
GitHub: @jjiyyaaa

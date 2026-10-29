# 🎮 Simon Says Game | HTML, CSS & JavaScript

A browser-based memory game where you watch a growing sequence of flashing colors and repeat it correctly to reach the next level. Built with **vanilla HTML, CSS and JavaScript**: no frameworks, no libraries.

**[🔗 Live Demo](https://abhishek-singh-techno.github.io/Simon-Says-Game/)**

![Simon Says Game Preview](preview.png)

---

## 🕹️ How to Play

1. Press **any key** to start the game.
2. Watch the button that flashes **white**.
3. Click the buttons in the **same order**. Your clicks flash **green**.
4. Every correct round adds one more step to the sequence.
5. One wrong click and it's **Game Over**. Your final score is shown, and you can press any key to try again.

## ✨ Features

- 🎯 Random color sequence that grows with every level
- 🔢 Live level counter and final score display
- 💡 Visual feedback: white flash for the game, green flash for the player
- 🚨 Red screen flash when you lose
- 🔁 Instant restart with any key press
- 🧹 Clean, readable code with separate HTML, CSS and JS files

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5** | Page structure and game buttons |
| **CSS3** | Layout with Flexbox, button colors, flash effects |
| **JavaScript (ES6)** | Game logic, DOM manipulation, event handling |

## 🧠 What I Learned

- Selecting and updating elements with the **DOM**
- Handling **keyboard and click events** with `addEventListener`
- Managing game state with variables and arrays (`gameSeq`, `userSeq`, `level`)
- Using `setTimeout` to create flash animations and delays
- Breaking a program into small, reusable functions (`levelUp`, `checkAns`, `reset`)

## 📂 Project Structure

```
Simon-Says-Game/
├── index.html
├── SimonSayGame.css
├── SimonSayGame.js
├── preview.png
└── README.md
```

## 🚀 Run Locally

```bash
git clone https://github.com/Abhishek-Singh-techno/Simon-Says-Game.git
cd Simon-Says-Game
# Open index.html in your browser
```

## 🔮 Future Improvements

- Add sound effects for each color
- Add a high score saved with `localStorage`
- Make the layout responsive for mobile and add touch-friendly controls
- Add difficulty levels with faster sequences

## 👨‍💻 About Me

Hi, I'm **Abhishek Singh**, an aspiring front-end developer building projects to strengthen my HTML, CSS and JavaScript skills. I'm open to internship and junior developer opportunities.

📧 [abhishekvishen08@gmail.com](mailto:abhishekvishen08@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/abhishek-singh-307162306/) · 🐙 [GitHub](https://github.com/Abhishek-Singh-techno)

⭐ If you like this project, please give it a star!

# 🎮 TicTacScore

A simple and interactive two-player Tic Tac Toe game built using HTML, CSS, and JavaScript.

Players take turns placing X and O on a 3×3 board. The game automatically detects the winner, highlights the winning combination, and keeps track of the score.

## ✨ Features

* ❌ Player X
* ⭕ Player O
* 🔄 Turn indicator
* 🏆 Automatic winner detection
* 🟢 Winning combination highlight
* 📊 Scoreboard for both players
* 🔁 Reset current game
* 🔄 Reset game and scores
* 🎨 Simple interactive UI

## 🛠️ Technologies

* HTML5
* CSS3
* JavaScript

## 🎮 How to Play

1. Player X starts the game.
2. Players take turns clicking an empty square.
3. The first player to get three symbols in a row wins.
4. The winning combination is highlighted.
5. The winner's score is updated.
6. Click **Reset Game** to start another round.
7. Click **Reset Counter** to reset both players' scores.

## 🏆 Winning Patterns

The game checks all 8 possible winning combinations:

```text
X | X | X
---------
O | O | 
---------
  |   |
```

```text
X | O |
---------
X | O |
---------
X |   |
```

```text
X | O |
---------
O | X |
---------
  |   | X
```

## 📸 Screenshots



<img width="815" height="782" alt="Screenshot 2026-08-12 at 10 15 41 PM" src="https://github.com/user-attachments/assets/4f54e8f2-2281-4789-a508-55ac2c5285c7" />
<img width="815" height="782" alt="Screenshot 2026-08-12 at 10 16 43 PM" src="https://github.com/user-attachments/assets/3a4126be-8ada-449d-b9ad-91858963c847" />



## 🧠 Game Logic

The JavaScript maintains the current player's turn and checks the board after every move.

When a winning combination is detected:

* The three winning cells are highlighted.
* Further moves are disabled.
* The winner is displayed.
* The corresponding player's score is increased.

## 🔄 Reset Options

### Reset Game

Clears the current board and starts a new round while keeping the scores.

### Reset Counter

Clears the board and resets both Player X and Player O scores to zero.

## 🚀 Run Locally

Clone the repository:

```bash
git clone <repository-url>
cd TicTacScore
```

Open `index.html` in your browser.

No backend or installation is required.


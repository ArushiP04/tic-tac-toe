# 🎮 Tic Tac Toe - JavaScript Web Game

This is a classic **Tic Tac Toe** game implemented using **HTML**, **CSS**, and **JavaScript**, featuring:

- Player name input
- Turn-based gameplay
- Winner/tie detection
- Dynamic dialog boxes for result and name input
- Game reset functionality

## 📁 Project Structure

tic-tac-toe/
│
├── index.html # HTML structure of the game
├── style.css # Styling for layout and UI
├── script.js # Game logic using JavaScript
└── README.md # Project documentation

## 🎮 How to Play

1. Open `index.html` in your browser.
2. A dialog will prompt for **Player 1** and **Player 2** names.
3. After entering names, the game board appears.
4. Players take turns placing their symbols (X and O).
5. The game checks for a win or tie after every move.
6. A result dialog appears when the game ends.
7. Click the **Reset** button to play again.

## 🧠 Core Features

- **Modular JavaScript Design**:
  - Uses the **Module Pattern** (IIFE and factory functions) for better structure.
  - Separation of concerns:
    - `Player` factory for managing player data.
    - `gameBoard` for game state.
    - `displayController` for DOM updates.
    - `game` for main logic and flow.

- **Game Logic**:
  - Checks for rows, columns, and diagonals.
  - Identifies ties when all cells are filled.

- **Dialogs**:
  - `names-dialog`: Prompts player names.
  - `result-dialog`: Displays winner or tie message.

- **Reset Functionality**:
  - Clears board and state without page reload.

## 🖼️ Interface Elements

- `main > p`: Displays current turn.
- `.gameboard`: 3x3 grid using `<div>` elements with `data-position`.
- `dialog.names-dialog`: Modal for entering player names.
- `dialog.result-dialog`: Modal for announcing results.

## ✨ Example Technologies Used

- HTML5: Semantic structure
- CSS3: Basic styling and layout
- Vanilla JavaScript: Game logic, DOM manipulation, dialog handling

## 💡 Potential Improvements

- Add animations or transition effects
- Add score tracking
- Make it mobile responsive
- Add computer (AI) opponent

## 📄 License

This project is open-source and free to use for personal or educational purposes.

---

🧠 *"The best way to learn JavaScript is to build games with it!"*


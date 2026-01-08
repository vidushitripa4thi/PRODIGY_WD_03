# Tic-Tac-Toe Web Game

An interactive Tic-Tac-Toe game built with HTML, CSS, and JavaScript. Play against a friend or challenge an AI opponent in this classic strategy game.

## 🎮 Features

- **Two-Player Mode**: Play with a friend on the same device
- **Interactive Gameplay**: Click to place X's and O's
- **Win Detection**: Automatic detection of winning combinations
- **Score Tracking**: Keep track of wins, losses, and draws
- **Reset Functionality**: Start a new game anytime
- **Responsive Design**: Play on any device - desktop, tablet, or mobile
- **Visual Feedback**: Highlights winning combinations

## 💻 Technologies Used

- **HTML5**: Game structure and layout
- **CSS3**: Modern styling and animations
- **JavaScript**: Game logic and interactivity

## 🚀 Live Demo

Open `index.html` in your web browser to start playing!

## 🔧 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/vidushitripa4thi/PRODIGY_WD_03.git
   ```

2. Navigate to the project directory:
   ```bash
   cd PRODIGY_WD_03
   ```

3. Open `index.html` in your browser:
   ```bash
   open index.html
   ```

## 🎯 How to Play

1. Player X starts the game
2. Click on any empty cell to place your mark (X or O)
3. Players alternate turns
4. First player to get 3 marks in a row (horizontal, vertical, or diagonal) wins!
5. If all cells are filled with no winner, the game is a draw
6. Click "Reset" to start a new game

## 📚 Game Logic Implementation

### Key JavaScript Concepts:
- **2D Array**: Game board representation
- **Event Listeners**: Handling user clicks
- **Conditional Logic**: Checking win conditions
- **DOM Manipulation**: Updating the game board visually
- **State Management**: Tracking current player and game status

### Win Conditions:
```javascript
// Rows, Columns, and Diagonals
- Horizontal: [0,1,2], [3,4,5], [6,7,8]
- Vertical: [0,3,6], [1,4,7], [2,5,8]
- Diagonal: [0,4,8], [2,4,6]
```

## 📁 Project Structure

```
PRODIGY_WD_03/
├── index.html    # Main HTML file
├── style.css     # Styling and animations
└── script.js     # Game logic
```

## 🔮 Future Enhancements

- Add AI opponent with different difficulty levels
- Implement online multiplayer functionality
- Add sound effects for moves and wins
- Create customizable themes (dark mode, color schemes)
- Add player name input and leaderboard
- Implement undo/redo functionality
- Add animation effects for winning sequences

## 📖 What I Learned

- Game state management
- Algorithm design for win detection
- Event-driven programming
- User interface design for games
- CSS grid layout for game board
- Handling edge cases (draws, invalid moves)

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

**Vidushi Tripathi**
- GitHub: [@vidushitripa4thi](https://github.com/vidushitripa4thi)

## 🚀 Acknowledgments

Developed as part of the Prodigy InfoTech Web Development Internship (Task 03).

---

*Challenge your friends and enjoy this timeless classic!* 🎲
# X-Tricks – Jack Game (Nand2Tetris Project 9)

**X-Tricks** is a two-player arcade-style game written in Jack, inspired by the classic Tic Tac Toe.  
It runs entirely on the Nand2Tetris platform, using only the built-in OS classes like `Keyboard`, `Screen`, and `Output`.

---

## 🕹️ Game Features

- Fully interactive 2-player experience (keyboard-controlled)
- Dynamic announcements and win/tie detection
- Restart or exit at end of each round
- Bold visual design using `Screen.drawLine`
- Real-time key press handling with the Jack `Keyboard` class
- Classic nostalgic gameplay feel with polished transitions

---

## 📂 Folder Contents

- `XTricks/Main.jack` – Entry point, game controller, player turns & flow  
- `XTricks/XTricks.jack` – Board logic, win conditions, rendering methods  
- `Xtricks review Ohad Swissa.mov` – Full gameplay demo  
- `PDF Document for Project 9 Submission.docx` – Architecture & concept summary

---

## ▶️ How to Play

- Press `SPACE` to start the game  
- Use keys `1–9` to place your move (X or O) on the board  
- Game will detect win or tie and prompt to `Y` (restart) or `N` (exit)

---

## 🧠 Architecture Highlights

### `Main.jack`
- Displays welcome screen and instructions
- Alternates turns and handles input
- Displays announcements and results

### `XTricks.jack`
- Manages board state (array of 9)
- Validates input, draws grid + X/O
- Checks win conditions and resets board

---

## 🎥 Demo Video

Watch the full gameplay demo:  
🎬 [X-Tricks Review (Ohad Swissa)]([https://drive.google.com/your-link-here](https://drive.google.com/file/d/1MaNo4ogTxkE-Ag1O-KDSNp005cfrNbP1/view)) 

---

## 👨‍💻 Author

**Ohad Swissa**  
Honors Student – Computer Science & Entrepreneurship  
Ex-IDF Special Forces Major | Problem Solver  
[LinkedIn](https://www.linkedin.com/in/ohad-swissa-54728a2a6)

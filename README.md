<img width="939" height="831" alt="屏幕截图 2026-06-19 104037" src="https://github.com/user-attachments/assets/1b9e8654-30ed-4c3e-a34c-799a90863292" />
<img width="1573" height="863" alt="屏幕截图 2026-06-19 104149" src="https://github.com/user-attachments/assets/23b87eaa-3e07-45e8-af1a-8c58c0aede7f" />
# This-Will-Revolutionize-Go-
This Will Revolutionize Go/这是一个颠覆围棋的项目 
🧩 This Will Revolutionize Go
A hexagonal, dynamically subdivided twist on the game of Go
This is not your traditional 19×19 grid.
It’s a hexagonal Go variant​ where every board cell is procedurally split into irregular subregions—making each game structurally unique, tactically richer, and visually distinctive.

✨ Key Features
Hexagonal Board​
A symmetric hexagonal grid (radius = 9) replaces the square board.
Procedural Cell Splitting​
Each hexagon is randomly divided into 2–4 sub-cells using one of 6 splitting patterns (T6, R3, TC4, Q3, TP, Q2T1), generating a different board topology every game.
Go Rules, Reimagined​
Standard Go mechanics: placement, connected groups, liberties, capture, and suicide prevention—adapted to the subdivided graph structure.
Automatic Scoring
​Territory counting + living stones, with clear visual breakdown at game end.
Undo & Restart​
Full move history support and instant reset.
Bilingual UI​
Switch seamlessly between English and Chinese.

🚀 How to Play
Open index.htmlin any modern browser (no server required).
Click a sub-cell to place a stone.
Capture opponent groups by removing their last liberty.
Press End Game & Score​ to finalize and view results.

📐 Technical Highlights
Pure HTML5 Canvas + Vanilla JavaScript
Graph-based board representation (nodes + adjacency)
Polygon containment checks for accurate interaction
Deterministic rule enforcement without external dependencies


License: MIT

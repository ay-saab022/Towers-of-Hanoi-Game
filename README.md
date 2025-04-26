# Towers-of-Hanoi-Game

Towers of Hanoi (Terminal Game)

Welcome to the classic Towers of Hanoi puzzle, built as a terminal game in Python!

🧠 Game Objective

Move all the disks from the Left stack to the Right stack, following two simple rules:

You can only move one disk at a time.

You cannot place a larger disk on top of a smaller disk.

The goal is to solve the puzzle in as few moves as possible — ideally in the minimum number of moves:

Minimum Moves To Win = 2ⁿ - 1

n is the number of disks.

▶️ How to Play

Run the game from your terminal.

Choose how many disks you want to play with (minimum 3).

At each turn:

Select the stack to move from.

Select the stack to move to.

Follow the rules to complete the puzzle!

🛠 How to Run

Clone the repository or download the project files.

Open a terminal in the project directory.

Run:
python3 hanoi-game.py

📁 Project Structure

/towers-of-hanoi/
│
├── stack.py        # Stack class used to manage each tower
|
├── node.py         # Node class used by the Stack (if Stack is linked list-based)
|
├── hanoi_game.py   # Main game logic (the file you run)
|
├── README.md       # This file

🚀 Future Plans

Build a web-based version using JavaScript and HTML.

Add animations and drag-and-drop functionality for disks.

Track and display the user's move count live.
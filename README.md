# C++ Small Projects Collection

A collection of lightweight, interactive, terminal-based C++ programs and games. This repository contains practice projects designed to demonstrate basic programming constructs in C++, including control flow, modular design with functions, array manipulation, input validation, and random number generation.

---

## 📋 Table of Contents
1. [Projects Overview](#-projects-overview)
   - [Banking Practice Program](#1-banking-practice-program)
   - [Rock, Paper, Scissors Game](#2-rock-paper-scissors-game)
   - [Tic-Tac-Toe Game](#3-tic-tac-toe-game)
2. [Prerequisites & Compilation](#-prerequisites--compilation)
3. [Running the Executables](#-running-the-executables)
4. [File Directory Structure](#-file-directory-structure)

---

## 🚀 Projects Overview

### 1. Banking Practice Program
* **File:** `BANKING_PRACTICE_PROGRAM.cpp`
* **Description:** A console-based banking application simulating basic teller machine operations.
* **Key Features:**
  - **Check Balance:** Displays the current balance formatted to two decimal places.
  - **Deposits:** Allows deposits and validates that the amount is greater than zero.
  - **Withdrawals:** Performs safety checks for insufficient funds and non-positive inputs.
  - **Interactive Loop:** Uses a `do-while` loop and `switch` statement to keep the application running until the user selects the exit option.
  - **Input Stream Cleansing:** Employs buffer clearing to prevent infinite loops from invalid inputs.

### 2. Rock, Paper, Scissors Game
* **File:** `ROCK_PAPER_SCISSORS.cpp`
* **Description:** A classic Rock, Paper, Scissors game played directly in the command line against a randomized computer opponent.
* **Key Features:**
  - **Input Validation:** Restricts user inputs to only valid keys (`'r'`, `'p'`, `'s'`).
  - **Pseudo-Random Opponent:** Leverages the standard library's random seed (`srand(time(NULL))`) to generate dynamic computer decisions.
  - **Outcome Resolution:** Determines ties, wins, and losses using structured conditional logic.

### 3. Tic-Tac-Toe Game
* **File:** `TIC_TAC_TOE.cpp`
* **Description:** A command-line 3x3 Tic-Tac-Toe game where the player (`X`) goes head-to-head with the computer (`O`).
* **Key Features:**
  - **Visual Board Representation:** Formats and prints a clean ASCII board to the terminal after every move.
  - **Dynamic Board Tracking:** Maintains game state using an array of characters.
  - **Automated Computer Turns:** The computer selects empty spots dynamically using random index selection.
  - **Win/Tie Evaluation:** Systematically evaluates rows, columns, and diagonals for a winning condition or a board-full tie.

---

## 🛠️ Prerequisites & Compilation

To compile and run these projects, you need a C++ compiler installed on your system (such as `g++` via GCC, Clang, or MSVC).

### Compiling via command line (GCC/Clang):

Open your terminal in the repository directory and run the compilation commands below:

```bash
# Compile Banking Practice Program
g++ BANKING_PRACTICE_PROGRAM.cpp -o BANKING_PRACTICE_PROGRAM

# Compile Rock, Paper, Scissors
g++ ROCK_PAPER_SCISSORS.cpp -o ROCK_PAPER_SCISSORS

# Compile Tic-Tac-Toe
g++ TIC_TAC_TOE.cpp -o TIC_TAC_TOE
```

---

## 🎮 Running the Executables

After compilation, launch the executable directly from your shell:

**On Windows:**
```cmd
.\BANKING_PRACTICE_PROGRAM.exe
.\ROCK_PAPER_SCISSORS.exe
.\TIC_TAC_TOE.exe
```

**On Linux / macOS:**
```bash
./BANKING_PRACTICE_PROGRAM
./ROCK_PAPER_SCISSORS
./TIC_TAC_TOE
```

---

## 📂 File Directory Structure

```text
C++_Small-Projects/
├── BANKING_PRACTICE_PROGRAM.cpp    # Banking Simulator Source Code
├── ROCK_PAPER_SCISSORS.cpp         # Rock Paper Scissors Source Code
├── TIC_TAC_TOE.cpp                 # Tic-Tac-Toe Game Source Code
└── README.md                       # Repository Documentation
```

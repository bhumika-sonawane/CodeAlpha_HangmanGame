
# 🎮 Hangman Game Using Python

## 📌 Project Overview

The Hangman Game is a simple, text-based word guessing game developed using Python. In this game, the computer randomly selects a word from a predefined list of five words, and the player must guess the hidden word by entering one letter at a time.

The player is allowed a maximum of six incorrect guesses. The game ends when the player correctly guesses the complete word or uses all six incorrect guesses.

This project was developed as part of the CodeAlpha Python Programming Internship.

## 🎯 Objectives

- Develop a simple interactive game using Python.
- Understand the use of loops and conditional statements.
- Practice working with strings and lists.
- Implement random word selection.
- Improve logical thinking and problem-solving skills.

## ✨ Features

- Random selection from five predefined words.
- Letter-by-letter word guessing.
- Maximum of six incorrect guesses.
- Displays guessed letters and hidden letters.
- Tracks previously guessed letters.
- Prevents repeated guesses from counting as new attempts.
- Validates user input.
- Displays winning and losing messages.
- Simple and user-friendly console interface.

## 🛠️ Technologies Used

- **Programming Language:** Python 3
- **Module:** random
- **Concepts:** Lists, strings, loops, conditional statements, user input, and random selection.

## 📂 Project Structure

```text
CodeAlpha_HangmanGame/
│
├── hangman.py
└── README.md
```

## 💻 Requirements

- Python 3.x
- Any Python-compatible code editor, such as Visual Studio Code, PyCharm, or IDLE.

No external libraries are required.

## 🚀 How to Run the Project

### Step 1: Install Python

Download and install Python from the official website:

https://www.python.org/downloads/

### Step 2: Clone the Repository

Open your terminal and execute:

```bash
git clone https://github.com/YOUR-USERNAME/CodeAlpha_HangmanGame.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### Step 3: Navigate to the Project Folder

```bash
cd CodeAlpha_HangmanGame
```

### Step 4: Run the Program

```bash
python hangman.py
```

If the command above does not work, try:

```bash
python3 hangman.py
```

### Step 5: Play the Game

1. Run the program.
2. Enter one alphabet letter when prompted.
3. Correct guesses reveal the letters in the word.
4. Incorrect guesses increase the number of attempts used.
5. Guess the complete word before using all six incorrect guesses to win.

## 🎮 Sample Output

```text
===================================
       WELCOME TO HANGMAN
===================================
Guess the hidden word one letter at a time.
You have 6 incorrect guesses available.

Word: _ _ _ _ _ _
Incorrect guesses: 0 / 6
Guessed letters: None

Enter a letter: p
Correct guess!
```

**Note:** The actual word and output may vary because the word is selected randomly.

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Using Python's `random` module.
- Implementing `while` and `for` loops.
- Applying `if-else` conditional statements.
- Manipulating strings and lists.
- Validating user input.
- Designing game logic and tracking user attempts.

## 👩‍💻 Author

**Name:** YOUR NAME

## 🏢 Internship

**Organization:** CodeAlpha

**Domain:** Python Programming

**Project:** Hangman Game

---

⭐ If you find this project useful, feel free to explore the source code and try the game!
```

### Before you save it

1. Replace `YOUR NAME` with your name.
2. Replace `YOUR-USERNAME` with your GitHub username.
3. Save the filename exactly as **`README.md`**, not `readme.txt` or `README.md.txt`.
4. Keep `README.md` and `hangman.py` in the same repository.

Once you commit the README, GitHub will automatically display the project description on your repository's home page.
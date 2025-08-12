# 🕹️ Hangman Game – Python Project

## 📌 Project Description

This **Hangman** game is a terminal-based Python application where a player guesses a hidden word one letter at a time. The player has a limited number of incorrect guesses (6 lives) before the game ends in a loss.

The game provides visual feedback via ASCII art and includes user-friendly prompts and error handling. It's designed for beginners learning basic Python concepts like loops, conditionals, lists, and string manipulation.

---

## 💡 Features

- 🎲 **Random Word Selection**: Words are randomly selected from a predefined list (`word_list`) containing challenging and interesting words.
- 🖼️ **ASCII Art**: Uses `hangman_art.py` to display game stages (lives left) and a logo for a polished look.
- 📖 **Progress Display**: Shows the current status of the guessed word using underscores for unknown letters.
- 🔁 **Repeat Guess Handling**: Detects if a user has already guessed a letter.
- 🏁 **Win/Lose Conditions**: Ends the game when the word is fully guessed or all lives are lost.
- 🎮 **User Input**: Accepts user input in a case-insensitive manner.

---

## 🛠️ Technologies Used

- **Language**: Python 3
- **Modules**: `random` (built-in)
- **Files**:
  - `hangman.py`: Main logic of the game
  - `hangman_word.py`: Contains the list of possible words
  - `hangman_art.py`: Contains the ASCII logo and hangman stages

---

## 🚀 How the Game Works

1. A word is randomly selected.
2. The player is shown a series of underscores representing each letter.
3. The player guesses one letter at a time.
4. If the guess is correct, the letter is revealed.
5. If incorrect, a life is lost and the hangman drawing progresses.
6. The game ends in a win if all letters are revealed, or a loss if all lives are used.

---


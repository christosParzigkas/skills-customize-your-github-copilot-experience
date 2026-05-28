
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman game in Python to practice loops, string handling, conditionals, and user input. The program should select a random word and let the player guess letters until they either reveal the word or run out of attempts.

## 📝 Tasks

### 🛠️ Word Selection and Game Setup

#### Description
Create a predefined list of words and randomly select one for the player to guess. Initialize the game state so the player can see blanks for each letter.

#### Requirements
Completed program should:

- Use a list of at least 5 possible words.
- Randomly choose one word at the start of the game.
- Display the hidden word as underscores separated by spaces, for example: `_ _ _ _ _`.
- Initialize an empty list for guessed letters and a counter for remaining attempts.

### 🛠️ Guess Processing and Display

#### Description
Allow the player to guess letters, update the displayed word state, and keep track of correct and incorrect guesses.

#### Requirements
Completed program should:

- Accept single-letter guesses from the player (case-insensitive).
- Reveal correct letters in the hidden word display.
- Show letters guessed so far and remaining attempts.
- Prevent repeated guesses from using additional attempts.
- Example:
	```
	Hidden word: _ _ _ _ _
	Guessed letters: a, e
	Remaining attempts: 5

	Enter a letter: a
	Correct! Hidden word: a _ a _ _
	```

### 🛠️ Win/Lose Logic

#### Description
Finish the game by checking whether the player has guessed the full word or used all available guesses, then display the appropriate result.

#### Requirements
Completed program should:

- End the game when the player guesses every letter correctly.
- End the game when the player runs out of attempts.
- Display a win message with the full word on success.
- Display a lose message with the correct word if attempts are exhausted.

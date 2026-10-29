
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a playable Hangman game in Python. Practice strings, loops, conditionals, user input, and random selection while tracking the player's guesses.

## 📝 Tasks

### 🛠️ Set Up the Game

#### Description
Create the game state and choose a secret word for the player to guess.

#### Requirements
Completed program should:

- Store a predefined list of words and randomly select one at the start of each game.
- Track the letters the player has guessed and the number of incorrect guesses remaining.
- Show the secret word as underscores, revealing letters that have been guessed correctly.

### 🛠️ Play and Finish a Round

#### Description
Prompt the player to guess letters, update the game after each guess, and finish the round when the player wins or runs out of attempts.

#### Requirements
Completed program should:

- Accept a letter guess and reveal matching letters in the secret word.
- Reduce the remaining attempts for an incorrect guess and show the updated progress.
- End when the word is fully revealed or no attempts remain, then display the appropriate win or lose message.

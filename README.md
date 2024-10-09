# Hangman Game

The **Hangman Game** is a text-based Python implementation of the classic word-guessing game where players attempt to guess a hidden word by suggesting letters within a limited number of incorrect guesses. 

## Features
- Randomly selects a word from a predefined list.
- Displays the current state of the guessed word and the number of lives left.
- Visual representation of the hangman based on remaining lives.

## How to Play
1. The game starts by displaying the logo and choosing a random word from the word list.
2. Players must guess letters to fill in the blanks of the chosen word.
3. For each incorrect guess, the player loses one life.
4. The game continues until the player either successfully guesses the word or runs out of lives.

## Example
```bash
Welcome to Hangman!
****************************6/6 LIVES LEFT****************************
Guess a letter: a
Word to guess: _ _ _ _ a _
****************************5/6 LIVES LEFT****************************

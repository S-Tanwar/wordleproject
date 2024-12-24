# Wordle Project

This is a simple implementation of the popular word puzzle game Wordle, where the player has six attempts to guess a five-letter word. After each guess, the game provides feedback on which letters are correct, present but in the wrong position, or not in the word at all.


## Features

- 5x5 grid to input guesses.
- Feedback system using color codes:
  - Green for correct letters in the correct position.
  - Yellow for correct letters in the wrong position.
  -  Gray for incorrect letters.
- Random word selection from a predefined list of words.
- Game over conditions:
  - User guesses the word correctly.
  - User runs out of attempts (6 attempts).


## Tech Stack

- **HTML**: Structure of the game, form for input, and buttons.
- **CSS**: Styling the game, layout, colors for feedback.
- **JavaScript**: Game logic, word checking, and feedback generation.


## How it works?
- The game selects a random word from a predefined list of words.
- You input guesses into a 5x5 grid and submit them.
- After each guess, the game compares it to the randomly selected word and provides feedback.
- You can make up to six guesses to figure out the correct word.
## License

This project is open-source and available under the [MIT](https://choosealicense.com/licenses/mit/)


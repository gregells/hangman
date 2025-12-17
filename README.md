# Hangman
This project is a browser version of the game _Hangman_.

The game adopts the Model-View-Controller (MVC) design pattern for the code's architecture.

[Try it out.](https://gregells.github.io/hangman/)

## Screenshots:
| ![New game](assets/screenshots/1_start.png)  | ![Mid-game](assets/screenshots/2_playing.png) | ![Lost game](assets/screenshots/3_lose.png) | ![Won game](assets/screenshots/4_win.png) |
|:---:|:---:|:---:|:---:|
| New game | Mid-game | Lost game | Won game |

## Technologies Used:
* __HTML__: A single index page that sets up the wireframe of the game.
* __CSS__: To provide the styling using the Tailwind CSS framework.
* __JavaScript__: To handle the game's logic and manipulate the DOM.

## How to Play:
* Guess the randomly selected word letter by letter.
* Guess a letter by clicking on the virtual keyboard, or typing on the physical keyboard.
* Complete the word before getting seven incorrect guesses to win.
* Start a new game by clicking the play again button, or pressing Shift + Enter on the physical keyboard.

## Future Development Plans:
* Add sounds for incorrect guess, correct guess, win & game over.
* Keep track of wins/losses on consecutive games, count streak of consecutive wins.
* Add a points tracker.
* Add a daily mode.

## Known Bugs:
No known bugs at this time.

## Acknowledgements:
Word list sourced from [here](https://github.com/dariusk/corpora/blob/master/data/words/common.json).

SVG files created using https://picsvg.com/.

Sounds taken from:
- Correct guess: https://freesound.org/people/LeonelAle71/sounds/679016/
- Incorrect guess: https://freesound.org/people/BloodPixelHero/sounds/572938/
- Repeat guess: https://freesound.org/people/plasterbrain/sounds/423169/
- Win game: https://freesound.org/people/FoolBoyMedia/sounds/352669/
- Lose game: https://freesound.org/people/themusicalnomad/sounds/253886/
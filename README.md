# Python Animal Guessing Game

A small command-line game where you try to guess a randomly chosen animal in five attempts. It was my first Python project, written to practise loops, conditionals, lists and the `random` module.

## How it works

1. The game picks a random animal from a list (`cat`, `dog`, `lion`, `tiger`).
2. You get **5 attempts** to guess it. Guesses are case-insensitive.
3. After each wrong guess, the remaining attempts are shown.
4. Guess correctly to win; run out of attempts and the answer is revealed.

## Running it

Requires Python 3. No extra packages are needed.

```bash
git clone https://github.com/Adarsh-Aravind/Python-Animal-Guessing-Game.git
cd Python-Animal-Guessing-Game
python animal_guess_game.py
```

## Example

```text
Welcome to the 'Guess the Animal' game! You have 5 attempts to guess the animal.
Guess the animal: dog
Sorry, incorrect guess. You have 4 attempts remaining.
Guess the animal: lion
Congratulations! You guessed the animal - lion.
```

## Ideas for later

- Hints after each wrong guess
- A larger animal list
- Difficulty levels with fewer attempts
- A graphical version

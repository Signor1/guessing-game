# Rust Guessing Game

This is a simple guessing game written in Rust. The program generates a random number between 1 and 100 and prompts the user to guess the number. It provides feedback on whether the guess is too small or too big, and informs the user when they guess the correct number.

## How to Play

1. Clone the repository to your local machine:

   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```
   cd rust-guessing-game
   ```

3. Compile and run the game using Cargo:

   ```
   cargo run
   ```

4. Follow the prompts to guess the secret number.

## Requirements

- Rust (https://www.rust-lang.org/)

## How It Works

- The program generates a random number using the `rand` crate.
- It prompts the user to input their guess.
- The user's guess is compared to the secret number.
- If the guess is too small, the program informs the user.
- If the guess is too big, the program informs the user.
- If the guess is correct, the program congratulates the user and ends.

## Dependencies

- [colored](https://crates.io/crates/colored): For colored terminal output.
- [rand](https://crates.io/crates/rand): For generating random numbers.


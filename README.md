# Hangman Game
 
- This project is a simple Hangman game developed using Vite, React, and TypeScript.
 
## Features:
 
- **Game Start**: A random word is selected when the page loads.
- **Guesses**: Letter guesses can be made via the keyboard.
- **Game States**: Winning and losing states are displayed.
- **Restart**: "Refresh" page and reset the game.

## Installation:
 
Clone the project to your local machine and install dependencies:
 
-  git clone https://github.com/surba778/hangman.git
- cd hangman-game
- npm install
 
## Running:
 
- **To start the development server**:
 
- npm run dev
 
- You can view the game in your browser at http://localhost:3000/
 
## Usage:
 
- **Guess**: Make letter guesses using your keyboard.
- **View Game State**: See winning or losing status on the game screen.
- **Restart**: At the end of the game, Refresh page and start a new game.
 
 
## File Descriptions
 
- App.tsx: Contains the game logic and UI components. The main game loop is managed here.
- getWord(): Selects a random word.
- useState(): Manages state for the game word (wordToGuess) and - guessed letters (guessedLetters).
- useCallback(): Updates guessed letters.
- useEffect(): Listens for keyboard events and manages game restart.
- HangmanDrawing: Updates the hangman drawing based on incorrect guesses.
- HangmanWord: Provides the display of the guessed and hidden word.
- Keyboard: Virtual keyboard component for guessing.

## Roles

- Suresh - Full project
- Samet - Readme file
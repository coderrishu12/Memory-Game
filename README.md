# Magic Match

Welcome to **Magic Match**—a fun and engaging memory card game built with React. The goal of the game is to match pairs of cards by flipping them over two at a time. 

## Features

- **Shuffling Cards**: Randomly shuffles and deals the cards at the start of the game or when a new game is initiated.
- **Card Matching**: Tracks and matches pairs of cards.
- **Turn Counter**: Keeps track of the number of turns taken to complete the game.
- **New Game Button**: Allows you to start a new game anytime.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/magic-match.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd magic-match
    ```

3. **Install dependencies:**

    ```bash
    npm install
    ```

4. **Start the development server:**

    ```bash
    npm start
    ```

   Open `http://localhost:3000` in your browser to play the game.

## File Structure

- `App.js`: The main component that manages the state and logic for the game.
- `components/SingleCard.js`: Component representing an individual card.
- `App.css`: Styles for the application.
- `public/img/`: Directory containing card images.

## Usage

1. **Start a new game** by clicking the "New Game" button.
2. **Flip cards** by clicking on them to reveal their images.
3. **Match pairs** by finding and flipping over two cards with the same image.
4. **Track your progress** with the turn counter at the bottom of the screen.

## Code Overview

Here's a brief overview of the main components in the code:

### `App.js`

- **State Management**: Manages the state of the cards, the choices made by the player, the number of turns, and whether the cards are disabled during comparison.
- **Shuffling Cards**: Randomizes and shuffles the cards and initializes the game state.
- **Handling Choices**: Tracks the player's choices and checks for matches.
- **Effect Hooks**: Utilizes `useEffect` to handle side effects like card comparison and game initialization.

### `SingleCard.js`

This component is responsible for rendering individual cards, handling user interactions, and displaying whether a card is flipped or matched.



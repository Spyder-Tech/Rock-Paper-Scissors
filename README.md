# Rock, Paper, Scissors Game

A simple web-based implementation of the classic Rock, Paper, Scissors game. Play against the computer and see who wins!

## Features

- Choose between rock, paper, or scissors
- Random computer opponent
- Real-time display of choices and results
- Score tracking for player and computer

## How to Play

1. Clone or download this repository.
2. Open the `index.html` file in your web browser.
3. Click on the buttons for "rock", "paper", or "scissors" to make your choice.
4. View the game results, choices, and scores displayed on the page.

## Setup

This project consists of an HTML file that includes the JavaScript code provided. Make sure to have an HTML structure with elements that match the IDs used in the script:

- `playerDisplay`
- `computerDisplay`
- `resultDisplay`
- `playerScoreDisplay`
- `computerScoreDisplay`

Here's a basic example of how your HTML might include these elements:

```html
<div id="playerDisplay"></div>
<div id="computerDisplay"></div>
<div id="resultDisplay"></div>
<div>Player Score: <span id="playerScoreDisplay">0</span></div>
<div>Computer Score: <span id="computerScoreDisplay">0</span></div>

<button onclick="playGame('rock')">Rock</button>
<button onclick="playGame('paper')">Paper</button>
<button onclick="playGame('scissors')">Scissors</button>
```

## Usage

Simply open the HTML file in your web browser and start playing!

## License

This project is for educational purposes. Feel free to modify and expand it.

---

Enjoy playing Rock, Paper, Scissors!

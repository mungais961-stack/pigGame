# Pig Game

A two-player dice game built with HTML, CSS, and vanilla JavaScript. Players take turns rolling a die and try to reach 100 points before their opponent.

## How to play

- Select **Roll dice** to add the result to your current turn's score.
- Rolling a 1 ends your turn, clears your current score, and switches play to the other player. Unheld points are lost.
- Select **Hold** to add your current turn's score to your total and pass play to the other player.
- After holding, the first player whose total is 100 points or more wins. The game ends and announces the winner.
- Select **New game** to reset both players and start over.

## Run the game

No installation or build step is required. Open `index.html` in a web browser, or serve the project directory with a local web server and open the provided address.

## Project files

- `index.html` — game layout and controls
- `style.css` — game styling
- `script.js` — turn, dice, scoring, and winner logic
- `dice-1.png`–`dice-6.png` — die face images
- `pig-game-flowchart.png` — game flowchart

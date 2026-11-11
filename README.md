<div align="center">

# Rock Paper Scissors

**A classic player-versus-computer game with randomized moves and live score tracking.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Play%20Now-176B4D?style=for-the-badge)](https://rock-paper-scissors-game17.vercel.app/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

[Live Demo](https://rock-paper-scissors-game17.vercel.app/) · [Source Code](https://github.com/mdnav/rock-paper-scissors-game) · [Portfolio](https://portfolio1701.vercel.app/)

</div>

---

## Project Overview

Rock Paper Scissors is a browser-based implementation of the classic hand game. The player chooses rock, paper, or scissors; the computer generates a random move; and JavaScript determines the round result using the standard game rules.

The interface displays both choices, provides immediate result feedback, and maintains scores throughout the current browser session.

## Live Application

Play the deployed version: **[Rock Paper Scissors — Live Demo](https://rock-paper-scissors-game17.vercel.app/)**

## Key Features

- **Three player choices:** Rock, Paper, and Scissors.
- **Random computer opponent:** Generates a computer move for every round.
- **Automatic result evaluation:** Determines a win, loss, or draw.
- **Live scoreboard:** Tracks player and computer wins.
- **Round feedback:** Displays the selected moves and the result.
- **Score reset:** Clears both scores and resets the game message.
- **Visual choices:** Uses image assets for the three game options.

## Game Rules

| Player move | Defeats |
|---|---|
| 🪨 Rock | ✂️ Scissors |
| 📄 Paper | 🪨 Rock |
| ✂️ Scissors | 🪨 Rock |

When both sides select the same move, the round ends in a draw. Draws do not increase either score.

## Round Workflow

```text
Player Selects a Move
        |
        v
Computer Generates a Random Move
        |
        v
Compare Both Choices
        |
        +------ Same Choice ------> Draw
        |
        +------ Player Wins ------> Increase Player Score
        |
        +------ Computer Wins ---> Increase Computer Score
        |
        v
Display Round Result
```

## Technology Stack

| Technology | Role |
|---|---|
| HTML5 | Game structure and choice controls |
| CSS3 | Styling and visual presentation |
| JavaScript (ES6) | Random selection, game rules, and score updates |
| Git & GitHub | Version control and source hosting |
| Vercel | Deployment |

## Run Locally

```bash
git clone https://github.com/mdnav/rock-paper-scissors-game.git
cd rock-paper-scissors-game
```

Open `index.html` in a modern web browser. Keep the `images/` directory alongside the HTML file so the game-choice images load correctly.

## Project Structure

```text
rock-paper-scissors-game/
├── index.html       # Game layout and controls
├── style.css        # Game styling
├── app.js           # Computer choice, rules, and scoreboard
├── images/
│   ├── rock.png
│   ├── paper.png
│   └── scissors.png
└── README.md        # Project documentation
```

## Engineering Concepts

- JavaScript functions and conditional logic
- Random number generation with `Math.random()`
- Event listeners and DOM manipulation
- Game-rule evaluation
- Updating application state and score displays
- Separating markup, styling, and behavior

## Current Behavior

- Scores are maintained in JavaScript while the page remains open.
- Refreshing the page starts a new score session.
- The reset control clears both player and computer scores.

## Roadmap

- Best-of-three and best-of-five match modes
- Round history and match statistics
- Optional sound and result animations
- Improved keyboard accessibility
- Additional visual themes

## About the Developer

**Mohammad Naveed**  
B.Tech ECE student focused on software development, Java full-stack engineering, and building practical web applications.

- **Portfolio:** [portfolio1701.vercel.app](https://portfolio1701.vercel.app/)
- **GitHub:** [github.com/mdnav](https://github.com/mdnav)
- **LinkedIn:** [linkedin.com/in/mdnav](https://www.linkedin.com/in/mdnav/)

## Contributing

Suggestions and improvements are welcome. Fork the repository, create a feature branch, commit your changes, and open a pull request.

If you find this project useful, consider giving it a ⭐.

<div align="center">

**Designed and developed by Mohammad Naveed**

</div>

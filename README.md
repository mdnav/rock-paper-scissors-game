<div align="center">

# ✊✋✌️ Rock Paper Scissors

### A classic player-versus-computer game built for the browser

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Play%20Now-0A7A4B?style=for-the-badge)](https://rock-paper-scissors-game17.vercel.app/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**[Live Application](https://rock-paper-scissors-game17.vercel.app/) · [Source Code](https://github.com/mdnav/rock-paper-scissors-game) · [Portfolio](https://portfolio1701.vercel.app/)**

</div>

---

## Overview

Rock Paper Scissors is a lightweight browser game in which a player competes against a computer opponent. The computer randomly selects a move, JavaScript compares both choices using the classic rules, and the interface displays the round result and updated scores.

## Features

- **Three player choices:** Rock, Paper, and Scissors.
- **Computer opponent:** Generates a random move for every round.
- **Automatic result detection:** Determines a win, loss, or draw.
- **Live scoreboard:** Tracks the player's and computer's scores.
- **Reset control:** Resets both scores and displays a new game message.
- **Interactive feedback:** Shows each round's result in the page.

## Game Rules

| Player choice | Beats |
|---|---|
| 🪨 Rock | ✂️ Scissors |
| 📄 Paper | 🪨 Rock |
| ✂️ Scissors | 🪨 Rock |

If both sides choose the same option, the round is a draw.

## Round Workflow

1. Select Rock, Paper, or Scissors.
2. The computer randomly chooses its move.
3. The game compares both choices.
4. The result message is displayed.
5. The winner's score is incremented; draws do not change either score.
6. Continue playing or reset the scoreboard.

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Game structure |
| CSS3 | Styling and layout |
| JavaScript | Random selection, game rules, event handling, and score updates |
| Git and GitHub | Version control and source hosting |
| Vercel | Deployment |

## Run Locally

```bash
git clone https://github.com/mdnav/rock-paper-scissors-game.git
cd rock-paper-scissors-game
```

Open `index.html` in a modern browser. No package installation or build step is required.

## Project Structure

```text
rock-paper-scissors-game/
├── index.html
├── style.css
├── app.js
├── images/
└── README.md
```

## Concepts Demonstrated

- JavaScript functions and conditional statements
- Random number generation
- DOM selection and manipulation
- Event listeners and user interaction
- Score tracking and UI feedback
- Frontend project organization

## Future Improvements

- Best-of-three and best-of-five matches
- Match history and statistics
- Improved animations and sound effects
- Additional game modes

## About the Developer

**Mohammad Naveed** — B.Tech ECE student building web applications and developing skills in Java, Spring Boot, React, REST APIs, databases, and cloud technologies.

- **Portfolio:** https://portfolio1701.vercel.app/
- **GitHub:** https://github.com/mdnav
- **LinkedIn:** https://www.linkedin.com/in/mdnav/

## Contributing

Suggestions are welcome. Fork the repository, create a feature branch, make your changes, and open a pull request.

If you find this project useful, consider giving the repository a ⭐.

<div align="center">

**Built with HTML, CSS, and JavaScript by Mohammad Naveed**

</div>

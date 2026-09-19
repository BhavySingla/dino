# DINO QUEST 🦖

A responsive educational endless runner built from the uploaded Chrome-Dino-style HTML foundation.

## Structure
- `index.html` — game UI and screens
- `css/style.css` — responsive dark theme
- `js/game.js` — canvas engine, physics, obstacles, quizzes, particles, audio, persistence
- `js/questions.js` — editable class-8-and-below question bank
- `assets/` — reserved for optional local art/audio assets
- `original_foundation.html` — the uploaded source retained for reference

## Run on Replit
Create a new HTML/CSS/JS Repl, upload these files preserving the folders, then run the static site. No external dependencies are required.

## Controls
- Desktop: Space / Arrow Up to jump, P to pause, R to restart after game over.
- Mobile: tap the game to jump.
- Quiz choices are tapped/clicked.

## Gameplay
Every five successfully passed obstacles triggers a quiz. Correct answers award bonus points, unlock a level, and increase speed. Wrong answers cost one life. Shield and turbo power-ups can appear during runs. High score and a five-entry local leaderboard are saved in `localStorage`.

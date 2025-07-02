Here's a README for your Cyber_Suduko project based on the features and structure found in your index.html:

---

# Cyber_Suduko

**Antoher suduko alternative**  
A cyberpunk-themed, tournament-style Sudoku web app with high scores, multiple difficulties, and an optional Gemini AI-powered hint system.

## Features

- **Modern Cyberpunk UI:** Vibrant neon colors, glowing effects, and animated elements.
- **Classic Sudoku Gameplay:** 9x9 grid with random puzzle generation and four difficulty levels (Easy, Medium, Hard, Insane).
- **Multiple Game Modes:** Classic Sudoku (Super Sudoku coming soon).
- **Timer:** Track how quickly you solve each puzzle.
- **Validation:** Instantly check your progress for mistakes.
- **AI Hints:** Get strategic, non-spoiler help powered by Gemini AI (requires API key).
- **Solver:** Instantly reveal the solution to any puzzle.
- **High Scores:** Save and display your best times by difficulty, with support for anonymous or named submissions (uses Firebase for storage).
- **Responsive Design:** Works great on desktop and mobile.

## How to Play

1. **Start a New Game:**  
   - Click "New Game" on the menu.
   - Select "Classic Sudoku" (more modes coming soon).
   - Choose your difficulty.

2. **Solve the Puzzle:**  
   - Fill in numbers 1–9 so every row, column, and 3x3 box contains each digit once.
   - Use the "Validate" button to check your progress at any time.

3. **Features During Play:**  
   - **AI Strategy:** Click for a strategic hint (if API is set up).
   - **Solve:** Instantly complete the puzzle if you're stuck.
   - **Timer:** Race against the clock for your best time.

4. **High Scores:**  
   - After solving, enter your name to submit your score.
   - View the top scores by clicking "High Scores" from the main menu.

## Tech Stack

- **HTML/CSS:** All interface and styling in a single HTML file, using custom fonts and CSS variables.
- **JavaScript:** Handles game logic, puzzle generation, UI, and Firebase integration.
- **Firebase:** Stores high scores and handles anonymous authentication.
- **Gemini API (Optional):** For AI-powered hints (requires API key).

## Setup & Deployment

1. **Clone or Download the Repo**
2. **Firebase Integration:**  
   - Edit the Firebase config section in the script (`index.html`), or set up your own project.
   - The default setup uses demo credentials and will not save high scores persistently.
3. **AI Hints (Optional):**  
   - Add your Gemini API key in the `getAIHint()` function inside the script.

4. **Open `index.html` in your browser.**

## Customization

- **Super Sudoku Mode:** Currently marked as "WIP" (work in progress).
- **Styling:** Modify the CSS in the `<style>` tag for your own themes.
- **Puzzle Generation:** Tune the number of clues/holes per difficulty in the JS logic.

## Credits

- Fonts: [Orbitron](https://fonts.google.com/specimen/Orbitron), [Rajdhani](https://fonts.google.com/specimen/Rajdhani) via Google Fonts.
- Placeholder background: [placehold.co](https://placehold.co)
- Built by [GizzZmo](https://github.com/GizzZmo)

## License

MIT License (add a LICENSE file if you wish)

---

Feel free to edit this README to better match your project's vision or add any additional deployment instructions!

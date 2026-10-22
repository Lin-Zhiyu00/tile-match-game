# Tile Match
Assignment 3: An interactive experience

## What is this?
Tile Match is a small tile-matching puzzle game inspired by "Sheep a Sheep".
It is a single-page web app built with plain HTML, CSS and JavaScript — no dependencies, no installation.

## Who is it for?
Casual players who want a quick, relaxing puzzle game.

## How to play
1. The board shows stacks of tiles. Bright tiles are clickable; dim tiles are covered by tiles above them.
2. Click a bright tile to move it to the tray at the bottom.
3. When 3 identical tiles appear in the tray, they are cleared automatically.
4. Clear every tile on the board to win.
5. If the tray fills up with 7 tiles before you can match them, you lose.

## Interaction loop
User clicks a tile → the tile moves to the tray → the game checks for 3 matching symbols → matches disappear / win-lose state updates.

## How to run
Option A (easiest): open the GitHub Pages link (see repository front page).
Option B: download `index.html` and double-click it to open in any modern browser.

## Error handling
- Covered tiles cannot be clicked (they appear dimmed).
- Clicking tiles after the game ends has no effect.
- The Reset button always starts a fresh shuffled game.

## Screenshot
<img width="959" height="502" alt="9a49b72b44c5985fdb31bc9d59ad2b0c" src="https://github.com/user-attachments/assets/cb80f9ec-e83f-4a48-9fd0-2ec17b4bd4c8" />


## Known limitations
- Only 6 tile types and 18 tiles per round.
- No timer, no score, no undo.
- No sound effects.

## Credits
All code written for this assignment. Tile symbols are standard emoji from the system font.

# Fruit Tile Match
An interactive tile-matching browser game for Assignment 3: An interactive experience.

## Project idea
This is a simple relaxing matching game. It is designed for casual players who want a short, playful interactive experience.
The core loop:
1. Player clicks on uncovered, bright fruit tiles
2. Selected tiles move to the bottom tray
3. When 3 identical fruits appear in the tray, they automatically disappear
4. The player wins when all tiles on the board are cleared
5. The player loses if the tray fills up to 7 slots

## How to run
This is a single HTML file with no external dependencies.
1. Download `fruit-tile-match.html`
2. Double-click to open it in any modern web browser (Chrome, Edge, Safari)
3. Click the `NEW GAME` button to restart at any time

## Controls & feedback
- ✅ Only bright, uncovered tiles can be clicked; covered tiles are dimmed to show they are blocked
- ✅ Visual animation when tiles are removed
- ✅ Falling fruit decoration animation in the background
- ✅ Firework effect + text "YOU WIN!" when all tiles are cleared
- ✅ "GAME OVER" message when the tray is full
- ✅ `NEW GAME` button resets the whole board

## Known limitations
- Fixed single level only (no progressive level system)
- Background falling fruits are decorative and cannot be interacted with
- No sound effects

## Credits
- Tile emoji assets: standard Unicode fruit emojis
- Base interaction logic developed for this assignment
- AI assistant helped refine layout, animations, bug fixes and documentation

## Screenshot
![Game screenshot](screenshot.jpg)

## Live Demo (Optional)
If deployed with GitHub Pages, paste your link here.

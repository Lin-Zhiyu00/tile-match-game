# Development Process

## Initial idea
I wanted to make a small browser game inspired by "Sheep a Sheep" (the viral tile-matching game). The core idea: a board of stacked tiles, the player clicks uncovered tiles to move them into a tray, and 3 matching tiles clear automatically.

## Why this idea
- The interaction loop is very clear: click → tile moves → match check → feedback.
- The layered stacking naturally creates a meaningful "blocked" state that the player must understand.
- The game has a built-in error state (tray full) that matches the assignment requirement.
- Emoji tiles mean no external image assets are needed.

## Design decisions and changes
1. First version used a flat grid. I changed to offset positions so upper-layer tiles visibly overlap lower-layer tiles, making the "stacking" obvious.
2. Added drop shadows and hover lift to make tiles feel physical and clickable.
3. Made blocked tiles dim and desaturated so the player can instantly tell which tiles are usable.
4. Added a hint bar under the game to explain the rules without a tutorial screen.

## User trial
I asked one classmate to try the game without explaining the rules first.

Observations:
- They immediately clicked the bright tiles and ignored the dim ones, which confirmed the visual feedback works.
- At first they did not notice the tray at the bottom; after one or two clicks they saw the tile move down and understood.
- They tried clicking a dim tile, saw nothing happen, and immediately understood it was blocked.

Change I made: I added the subtitle "Click an uncovered tile to move it to the tray" above the board, so new players understand the goal faster.

## AI tools usage
I used an AI coding assistant to draft the HTML/CSS/JS structure, then iterated on the visual design.
- Suggestion I kept: using emoji as tile symbols so no image files are required.
- Suggestion I rejected: adding a timer and score system. I kept the game simple because the assignment rewards one well-designed interaction over many half-built features.

## Development history
- Commit 1: Initial working game with basic click, tray, and match logic.
- Commit 2: Visual upgrade with layered offsets, 3D shadows, and animations.
- Commit 3: Added README and PROCESS documentation.

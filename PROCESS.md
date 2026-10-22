# Process documentation | Assignment 3

## Starting idea
I wanted to build a simple tile-match elimination game running in the browser.
The planned interaction loop: click tiles → send them to a tray → match three fruits to clear them, win by clearing the whole board.
My initial prototype had a small number of fruit tiles on the board.

## Design & code changes
1. **First change: increase tile quantity**
When my test user tried the first version, they commented that there were too few fruit cards. The game ended very quickly and felt unfinished. I increased the total pool of fruit tiles multiple times, adjusting the tile bag so there are enough tiles to create a satisfying play session, and the total count is a multiple of three so every fruit can be matched and cleared.
2. Removed the level system. I decided to keep just one fixed playable board, which fits the brief: one carefully designed interaction loop instead of many incomplete features.
3. Added continuous falling fruit background animation as decorative feedback.
4. Fixed bugs: reset freeze on restart, tile counting mismatch that prevented the board from being fully cleared.

## User trial observation
I asked one person to test the game without explaining the rules first.
- Observation: The tester quickly understood clicking bright tiles, but they said the original board was too small and the game was over too fast. They wanted more tiles to make the game longer.
- My decision: I added more fruit tiles and expanded the tile pool, which is the main iteration for this project.
- After adding more tiles, the tester found the pacing much better and could complete a full game naturally.

## AI tool usage
I used AI assistance for this project.
- Things I kept: HTML & CSS layout code, tile click logic, tray matching logic, fireworks and falling fruit animation code, bug fixes for the reset freeze issue.
- Things I rejected / changed: The original multi-level structure the AI suggested. I decided a single fixed board was simpler and better matched the assignment brief.
I did not use any paid APIs, external models or sound services.

## Error handling implemented
- Repeated clicks on the same tile are ignored once it is removed
- Clicks on covered dim tiles have no effect
- NEW GAME button fully resets tiles, tray, animations and game state

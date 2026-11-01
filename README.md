# Six Deep

A candy ball-sort puzzler. Tubes go 6 deep, 10 colors, and every board is
guaranteed solvable.

## How to play

Sort every candy so each tube holds a single color. Tap a tube to lift the
top candy, then tap another tube to pour. You can only pour onto matching
candy or into an empty tube. Tubes hold 6.

New colors join as you climb: 4 colors at levels 1-2, one more every two
levels, up to the full 10 from level 13 on.

## Tech

- Single `index.html`, no build step, no assets, no backend.
- Boards are generated in your browser with a seeded shuffle and verified
  by a built-in depth-first solver before play. Same level, same board,
  on every device.
- Progress, current board, and settings persist in `localStorage`
  under the versioned key `sixdeep.v1`.

A Jade Static Builds game. Built with Muse.

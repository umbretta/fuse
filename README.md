# Fuse

A fireworks puzzle game. Light the fuses in the right order so rockets reach the rack three of a colour at a time. If four rockets are up with no match, you lose.

**Play:** https://umbretta.github.io/fuse/

- 1000 levels, each one harder than the last. Levels are built when you open them: the level number seeds a puzzle, and a search tweaks it until its difficulty, measured by a solver, lands in that level's own band. The bands rise and never overlap, so the order is guaranteed and the same number always gives the same puzzle. All 1000 have been checked to be winnable and in band.
- Chain fuses (from level 25), locked fuses (from 50) and twin fuses (from 100).
- Player profiles saved in your browser. A 6-character transfer code moves your progress to another device.

The whole game is one file, `index.html`, with no build step and no backend.

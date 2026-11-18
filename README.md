# Fuse

A fireworks puzzle game. Light the fuses in the right order so rockets reach the rack three of a colour at a time. If four rockets are up with no match, you lose.

**Play:** https://umbretta.github.io/fuse/

- Endless levels, built when you open them from the level number alone, so every player gets the same puzzle for the same number. Levels 1 to 1000 climb: a search tweaks each seeded puzzle until its difficulty, measured by a solver, lands in that level's own band, and the bands rise without overlapping, so each level is harder than the one before. From level 1001 on, every level is drawn from its own band among the hardest boards the game can build. All levels are checked to be winnable.
- Chain fuses (from level 25), locked fuses (from 50), dud rockets (from 75), twin fuses (from 100), mystery rockets (from 125) and small three-hook racks (from 150).
- Difficulty is scored by traps: the chance that a careful player, who never makes a move that loses on the spot, still ends up stuck.
- Player profiles saved in your browser. A transfer code (6 characters, or 10 past level 1023) moves your progress to another device.

The whole game is one file, `index.html`, with no build step and no backend.

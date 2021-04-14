# Fractalpuzzlejs
This is a fractal, circle grid jigsaw generator, for lasercutting in wood or acrylic or whatever material. You can download index.html and just run it offline from your browser, or try the online version courtesy of github.io at https://proceduraljigsaw.github.io/Fractalpuzzlejs/.

It should be pretty self-explanatory once you play with it. It uses a pseudorandom number generator to generate the puzzles with deterministic behaviour. Two puzzles generated with the same Seed, Rows, Columns and minimum and maximum piece sizes will produce the same result (maybe with a different scale if you tweak the radiuses and such).

I will probably add a choice to use a non-deterministic randomness generator so you get a unique result every time.

SVG can be exported in two ways:

*Overlapping: pieces are individually contoured. This is good if you want to cut them with a CNC or something with thick cutting width.

*Non overlapping: perfect for lasercutting, as the cutting path is created such that no vectors overlap.

Enjoy!

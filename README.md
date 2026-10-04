# Flappy-BirdSDL2

A Flappy Bird style game written in C++ with SDL2, where a Shiba flies between pipes. The window title is "Chim bay".

## Features

- Pipe obstacles, scrolling land, and a Shiba player character (`doge`, `pipe`, `land` classes).
- Menu, pause and replay states, with a game-over screen.
- Day and night backgrounds, plus a dark Shiba sprite.
- Score display with medals (gold, silver, honor) and a best score kept in `res/data/bestScore.txt`.
- Sound effects with a sound toggle (SDL_mixer).

## Tech stack

- C++ with SDL2, SDL2_image, SDL2_ttf and SDL2_mixer
- Visual Studio project (`Project5.vcxproj`)
- Sprites are sourced partly from [NNBnh/flappybirdart](https://github.com/NNBnh/flappybirdart) (see `res/image/Up/`); PSD sources are in `code/res/psd`.

## Getting started

1. Install Visual Studio with the C++ desktop workload.
2. Provide the SDL2, SDL2_image, SDL2_ttf and SDL2_mixer development libraries and point the project's include and library paths at them.
3. Open `Project5.vcxproj`, build, and run from a folder where the `res/` assets are reachable (the code loads them via relative paths such as `res/number/small/1.png`).

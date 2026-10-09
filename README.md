# Living Chess — downloads

Real chess where every piece is a living fantasy character and every capture becomes a cinematic battle.

- **Play in your browser:** https://living-chess-public.netlify.app/
- **Game page:** https://living-chess-public.netlify.app/download/
- **Windows download:** [latest release](https://github.com/ooHulKoo1973/living-chess-download/releases/latest)

This repository holds the desktop releases only.

## Windows

Download `Living-Chess-Setup.exe` from the latest release and run it. The game is not code-signed yet, so Windows
SmartScreen may say it "protected your PC": choose **More info → Run anyway**.

Requirements: Windows 10 or 11 (64-bit), a graphics card with WebGL 2 (any recent PC), about 650 MB of disk space.

## Licences

The chess engine is [Stockfish](https://stockfishchess.org/) 19 (GPL-3.0), shipped unmodified in its
single-threaded WebAssembly build from [Stockfish.js v19.0.0](https://github.com/nmrugg/stockfish.js/tree/v19.0.0)
(source: that tag and [official-stockfish/Stockfish](https://github.com/official-stockfish/Stockfish)); its licence is in
the game folder at `resources/app.asar` → `web/engines/stockfish/COPYING.txt`. The game runs it as a separate
program and talks to it over the UCI protocol. The desktop shell is [Electron](https://www.electronjs.org/) (MIT;
Chromium's licences are in `LICENSES.chromium.html` next to the game).

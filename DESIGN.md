# Design

A back-room scoreboard: dark wood, brass, chalk and paper slips. One file, no build step.

## Where the tokens live

All in `index.html`, in the `:root` block near the top:

- `--room` and `--ink`: the dark room and ink
- `--brass` and `--brass-hi`: brass trim and its highlight
- `--chalk`, `--paper`, `--slip`: chalk text, score paper, betting slips
- `--red`: the one alert color
- `--disp`: Archivo, for display type. `--mono`: IBM Plex Mono, for everything else

More on the look is in the README under "Design notes".

Last verified: 2026-11-24

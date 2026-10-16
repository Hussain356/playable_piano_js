# Playable Piano JS

A playable virtual piano built with HTML, CSS and JavaScript. Play with your computer keyboard or click the keys with your mouse.

**Live demo:** https://hussain356.github.io/playable_piano_js/

## Features

- 17 playable keys (white and black) from C4 to E5
- Play with the keyboard or the mouse
- Notes can overlap, so chords and fast runs work
- Volume slider
- Toggle to show or hide key labels
- Responsive layout for smaller screens

## Key layout

| Key | Note | Key | Note | Key | Note |
|-----|------|-----|------|-----|------|
| `A` | C4  | `F` | F4  | `J` | B4  |
| `W` | C#4 | `T` | F#4 | `K` | C5  |
| `S` | D4  | `G` | G4  | `O` | C#5 |
| `E` | D#4 | `Y` | G#4 | `L` | D5  |
| `D` | E4  | `H` | A4  | `P` | D#5 |
|     |     | `U` | A#4 | `;` | E5  |

## Run locally

No build step or dependencies are needed. Clone the repo and open `index.html` in your browser.

```bash
git clone https://github.com/Hussain356/playable_piano_js.git
cd playable_piano_js
```

## Project structure

```
index.html   page markup and key layout
style.css    styling
script.js    key handling and audio playback
tunes/       one .wav sound file per key
```

## Credits

Based on the Playable Piano tutorial by CodingNepal.

# PO-20 Arcade Course Operator

### ▶ [Play it now](https://corsair-studios.github.io/po-20-arcade-trainer/)

No install — runs in your browser.

A standalone, browser-based training simulator inspired by pocket-sized
arcade-style sequencers. It teaches the core workflow — programming beats,
editing patterns, shaping sound, and arranging songs — through guided
lessons, entirely in the browser.

## Disclaimer

**This project is not affiliated with, endorsed by, or connected to Teenage
Engineering in any way.** "PO", "Pocket Operator", and related marks are the
property of their respective owners. This is an independent, educational
trainer that offers a visual approximation of a device's layout and workflow;
it is **not** an emulation of any proprietary hardware or sound engine and
reproduces no proprietary code, firmware, or audio.

It is provided **free for noncommercial use** — learning, personal study,
hobby projects, and use by educational institutions — under the terms of the
license below. Commercial use is not permitted.

## Features

- Browser-generated chiptune audio — all sixteen voices are individually
  synthesized, from the noise-based drums and plucky bass to the arpeggiators,
  the vibrato / portamento / echo modulation voices, and a wavetable hardsync
- Functional Knob A (pitch) and Knob B (waveform/tone) controls, with per-step
  parameter locks
- 16-step pattern LEDs, playback, and a per-step re-trig multiplier (2/4/8/16)
- Sixteen selectable performance effects — filter sweeps, fill-ins, retrigger,
  glitch, blinds, a rising arpeggio, and channel solos
- Sixteen named chords with a sustained drone mode
- Swing, tempo presets (Hip Hop / Disco / Techno), fine tempo, and master volume
- True multitrack patterns, pattern chains, copy, and a full sixteen-pattern
  demo restored by the factory-reset gesture
- Seven course chapters with twenty-six guided lessons, from first playback
  through building a multitrack song and performing an advanced track
- Responsive layout: on phones, the emulator and trainer panels become a
  horizontal swipe pager with a pinned instruction strip; on larger screens
  they sit side by side
- A restart button that restores the selected lesson's original setup and
  returns to step 1

## Run locally

Open `index.html` in Chrome, Edge, Firefox, or Safari.

For more reliable local browser behavior (audio autoplay, file access), serve
it from a basic web server in this directory:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy as a static site

The project is plain HTML, CSS, and JavaScript. Connect the repository to your
static hosting provider and use the repository root as the published
directory. No build command is required.

## Notes

- All patterns, lesson progress, and settings live only in the open browser
  session — nothing is saved between visits.
- Audio begins after the first user interaction because browsers restrict
  automatic audio playback.
- This is an educational approximation, not an exact emulation of any
  proprietary sound engine.

## License

Licensed under the **PolyForm Noncommercial License 1.0.0** — free to use,
modify, and share for any noncommercial purpose; commercial use is not
permitted. See [LICENSE](LICENSE) for the full terms.

Copyright (c) 2026 Corsair Studios, LLC.

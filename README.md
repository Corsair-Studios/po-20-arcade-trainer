# PO-20 Arcade Course Operator

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

It is provided **free to use** for learning and personal, non-commercial
educational purposes.

## Features

- Browser-generated chiptune audio
- Functional Knob A and Knob B controls
- 16-step pattern LEDs and playback
- Pattern editing and simple pattern chains
- Seven course chapters with eighteen guided lessons
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

See [LICENSE](LICENSE).

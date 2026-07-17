# PO-20 Arcade Course Operator

A standalone browser-based PO-20 Arcade-inspired training simulator with:

- Browser-generated chiptune audio
- Functional Knob A and Knob B controls
- 16-step pattern LEDs and playback
- Pattern editing and simple pattern chains
- Seven course chapters with eighteen guided lessons
- Teenage Engineering-inspired course-module styling
- A restart button that restores the selected lesson's original setup and returns to step 1

## Run locally

Open `index.html` in Chrome, Edge, Firefox, or Safari.

For more reliable local browser behavior, start a basic web server from this directory:

```powershell
py -m http.server 8080
```

Then open `http://localhost:8080`.

## Put it in your requested Windows folder

Extract or copy the project contents to:

```text
D:\ACode\po-20-arcade-trainer
```

## Initialize Git

```powershell
cd D:\ACode\po-20-arcade-trainer
git init
git add .
git commit -m "Initial PO-20 Arcade trainer"
```

## Deploy as a static site

The project is plain HTML, CSS, and JavaScript. Connect the Git repository to your static hosting provider and use the repository root as the published directory. No build command is required.

## Notes

- All patterns, lesson progress, and settings live only in the open browser session.
- Audio begins after the first user interaction because browsers restrict automatic audio playback.
- This is an educational approximation and not an exact emulation of the proprietary PO-20 sound engine.

# Classroom Scientific Calculator

A browser-based scientific calculator for secondary school students. It has the key layouts of three SEAB-approved models, and a PDF workspace where students can annotate worksheets with the calculator beside them.

**Live site:** once GitHub Pages is turned on, the calculator is at `https://<your-username>.github.io/<repo-name>/`.

## Features

### Calculator
- **Three layouts:** Casio fx-97SG X (the default), Casio fx-97SG CW and HP 10s+. Students switch with the buttons at the top.
- **Real proportions:** each calculator keeps its real width-to-height ratio and scales to fit any window, including split screen.
- **Natural textbook display** (fx-97SG X and CW): fractions, roots and powers look as they do in a textbook, with exact answers such as 5/6, 2√2 and π/2. S⇔D switches to decimals.
- **Modes:** Calculate, Statistics (1-variable, linear and quadratic regression), Equation (simultaneous equations with 2–4 unknowns, polynomials up to degree 4) and Base-N.
- **SETUP:** Math or Line input/output, Deg/Rad/Gra, Fix/Sci/Norm, and mixed or improper fractions.
- **SEAB rules:** there is no programming and no numerical integration or differentiation, following SEAB's rules for scientific calculators.
- **Keyboard shortcuts:** digits, + − × ÷, Enter, Backspace and Esc.

### PDF workspace (iPad and desktop)
- **Opening:** "Open PDF" opens the PDF full screen. A floating button at the bottom right shows or hides the calculator beside it.
- **Scrolling:** pages scroll with a finger on iPad, while Apple Pencil writes. A toggle lets fingers write instead.
- **Tools:**
  - pen and highlighter, each with 4 colours and 3 sizes
  - eraser, which removes whole strokes
  - text boxes
  - undo and redo, and zoom
- **Download** saves the annotated PDF.
- **Everything stays on the device:** the PDF and annotations are handled entirely in the browser and are never uploaded anywhere.

## Files

| Path | What it is |
|---|---|
| `index.html` | The app (the page GitHub Pages serves) |
| `lib/` | PDF libraries the app loads for the PDF workspace |
| `offline/scientific-calculator.html` | A self-contained copy with everything built in. It works offline and can be opened by double-clicking. |
| `licenses/` | Licences for the bundled libraries |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Running it

- **Online:** turn on GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root).
- **Locally:** open `offline/scientific-calculator.html` in Safari or Chrome. The PDF workspace needs `index.html` to be served over http(s), so use the offline file when opening from your computer.

## Third-party libraries

- [PDF.js](https://github.com/mozilla/pdf.js) by Mozilla, Apache License 2.0 (`licenses/pdfjs-LICENSE.txt`)
- [pdf-lib](https://github.com/Hopding/pdf-lib) by Andrew Dillon, MIT License (`licenses/pdf-lib-LICENSE.md`)

The key layouts follow the Casio fx-97SG X, fx-97SG CW and HP 10s+ for classroom familiarity. This project is not affiliated with or endorsed by Casio or HP.

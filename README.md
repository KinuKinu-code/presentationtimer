# ⏱️ Presentation Countdown Timer

A lightweight, embeddable countdown timer designed for presentations and slide decks.

## 🚀 Live Demo
Access the live timer here:
`https://kinukinu-code.github.io/presentationtimer/index.html`

## ✨ Features
- **Presets:** Quick options for 1.5m, 2m, 3m, 5m, and 10m limit.
- **Custom Duration:** Option to enter custom minute durations.
- **Visual Progress:** Smooth circular SVG ring with visual status colors (Blue = Running, Amber = Warning, Red = Expired).
- **Bell Chime Sound:** Synthesizes a 4-note Westminster clock chime using the native Web Audio API (no external MP3 files required).
- **Compact Slide Mode:** Minimalist view designed for embedding inside slide presentations.

## 💻 How to Embed in Slides
Use an `<iframe>` inside supported slide software or web view extensions:

```html
<iframe src="https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME/index.html" width="320" height="320" style="border:none;"></iframe>

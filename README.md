# CV (HTML résumé)

A single-file, print-ready curriculum vitae: **one HTML document** with embedded CSS—no build step, no dependencies, and no JavaScript.

## Contents

| File       | Description |
| ---------- | ----------- |
| `CV.html`  | Full résumé markup and styles (A4 layout, sidebar + main column). |

The page expects a profile image at **`avatar3.jpg`** in the same folder as `CV.html`. If that file is missing, the image area will show a broken image in the browser until you add a photo or update the `<img src="...">` path in `CV.html`.

## How to use

1. **Preview:** Open `CV.html` in a web browser (double-click the file or drag it into the window).
2. **PDF / print:** Use the browser’s **Print** dialog (Ctrl+P on Windows). Choose “Save as PDF” or a printer; the stylesheet uses `@page { size: A4 }` and print color adjustment so sidebar colors print more reliably.

## Tech notes

- **Layout:** Flexbox; fixed **210mm × 297mm** container for A4.
- **Styling:** All CSS is in a `<style>` block in the document head.
- **Language:** Page `lang` is English; content includes Vietnamese name text as appropriate for the résumé.

## Repository scope

This repository is intentionally minimal: static HTML/CSS only. There is no package manager, server, or CI configuration.

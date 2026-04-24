# Pixel Art Generator

A lightweight, browser-based pixel art generator built with HTML, CSS and JavaScript. Use the sliders to create a custom grid, pick a color and draw pixel art with mouse or touch. Includes simple erase/paint tools and a clear option.

![App Screenshot](./Screenshot%202024-08-25%20205801.png)

## Demo
Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari). For best results, use a desktop or tablet.

## Features
- Create a custom grid (up to 35x35).
- Draw by clicking and dragging (mouse) or touch-drawing on touch devices.
- Pick any color using the color input.
- Erase or paint modes.
- Clear the grid to start over.

## Controls / How to use
- Grid Width / Grid Height: Use the sliders to set the number of columns and rows. The displayed numeric value updates as you move the sliders.
- Create Grid: Generates the grid with the chosen width and height.
- Clear Grid: Removes the current grid.
- Color Picker: Choose the color to paint with.
- Paint / Erase: Toggle between painting and erasing.

Notes:
- Click (or touch) and drag to paint multiple pixels.
- On some mobile browsers, touch event detection is used; if painting doesn't start immediately, try tapping once then dragging.

## Files
- `index.html` — Application UI and controls.
- `style.css` — Styling for the interface and grid.
- `script.js` — Grid creation and drawing logic.
- `Screenshot 2024-08-25 205801.png` — Screenshot shown above.

## Run locally
1. Clone the repo:

   git clone https://github.com/BinaryVortex/Pixel-Art-Generator-2.git
2. Open the project folder and open `index.html` in your browser, or serve the folder with a simple static server:

   - Python 3: `python -m http.server 8000`
   - Node (http-server): `npx http-server`

Then visit http://localhost:8000 (if using a local server).

## Contribution
Contributions, suggestions and improvements are welcome. Feel free to open issues or submit pull requests.

## License
No license specified. Add a LICENSE file if you want to define terms for reuse.

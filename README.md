# Kandinsky-Stil Kunstgenerator

An interactive web-based art generator inspired by the works of Wassily Kandinsky, a pioneer of abstract art.

![Kandinsky Art Generator](https://github.com/yourusername/kandinsky/raw/main/preview.png)

## Overview

This project generates abstract art in the style of Wassily Kandinsky using HTML Canvas and JavaScript. Users can adjust various parameters to create unique artworks and download their creations.

## Features

- Generate abstract art with shapes, lines, and colors inspired by Kandinsky
- Adjust canvas dimensions (width and height)
- Control the number of shapes
- Choose from different color palettes:
  - Classic Kandinsky
  - Warm tones
  - Cool tones
  - Monochrome
  - Pastel
- Set background color
- Adjust complexity level
- Use predefined presets:
  - Komposition VIII
  - Farbstudie
  - Gelb-Rot-Blau
- Download artwork as PNG

## How to Use

1. Open `Kandinsky.html` in any modern web browser
2. Adjust the parameters using the sliders and controls
3. Click "Neues Kunstwerk generieren" to create a new artwork
4. Click "Bild herunterladen" to save your creation as a PNG file

## Technical Details

The generator uses vanilla JavaScript with the HTML5 Canvas API to draw various geometric shapes with different colors, opacities, and arrangements. The algorithm:

- Creates a background
- Draws random lines
- Adds circles, rectangles, and polygons with varying transparency
- Adds special elements like concentric circles and grid patterns based on complexity level

## License

[MIT License](LICENSE)

## Acknowledgments

Inspired by Wassily Kandinsky (1866-1944), one of the pioneers of abstract art. 
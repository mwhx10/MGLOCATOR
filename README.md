# Mammographic Lesion Clock-Face Locator

A single-page web utility that converts lesion coordinates from craniocaudal (CC) and mediolateral-oblique (MLO) mammographic views into a clock-face position, streamlining breast MRI and mammography reporting.

## Features

- Separate canvases for right and left breasts (CC and MLO)
- Click-based lesion marking with immediate clock-face output
- Draggable angle paddle (0°–90°) with snap-to-angle functionality for precise projection alignment
- Entire application contained in a single `index.html` file; no external build process required

## Quick Start

1. Clone or download this repository.
2. Open `index.html` in any modern web browser.
3. Select the breast side, mark the lesion on both CC and MLO canvases, and review the computed clock-face hour.

## Customization

- Adjust colour variables in the `<style>` section
- Modify canvas dimensions via the `width` and `height` attributes
- Edit the allowable snap angles for the paddle in the `snapAngle()` function

## License

Distributed under the **MIT License**.

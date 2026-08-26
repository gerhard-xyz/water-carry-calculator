# Water Carry Calculator

A lightweight hiking hydration calculator built as a single-page web app using the Esri Calcite design system.

## Overview

This app helps estimate how much water to carry for a hike by factoring in distance, pace, elevation gain, temperature, UV exposure, and personal conditions such as mouth breathing and heavy sweating.

## Features

- calculates estimated water needs in metric or imperial units
- accounts for trail duration and environmental variables
- includes UV and hydration guidance
- responsive, single-page interface

## Stack

- HTML
- CSS
- JavaScript
- Esri Calcite web components
- static single-page app

## Run locally

Because this is a static app, you can either open `index.html` directly in a browser or run a local server:

```bash
cd /Users/laptop/Documents/water-carry-calculator
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Project files

- `index.html` — app layout, styling, and calculator logic
- `favicon.svg` — app icon

## Notes

This is a planning estimate only. Actual hydration needs vary by individual physiology, physical effort, weather, and trail conditions.

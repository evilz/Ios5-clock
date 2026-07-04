# iOS 5 Clock

A premium fullscreen digital clock for the original iPad, inspired by Big Clock, Apple iOS 5, Braun design, and Dieter Rams minimalism.

## Design

- Pure black `#000000` background for maximum contrast.
- Huge white `HH:MM` numerals that dominate the screen.
- Smaller seconds tucked against the lower-right edge of the minutes.
- Thin light-gray date centered beneath the time.
- Helvetica Neue Ultra Light / Helvetica typography stack.
- Softer, less glossy white digits with only a restrained glow.
- Tiny gear icon in the bottom-left corner and fullscreen icon in the bottom-right corner.
- A very discreet weather line beneath the date, powered by Open-Meteo via a CORS-friendly API.
- No menus, panels, or distracting controls.

## Usage

Open `index.html` directly in a browser or serve the repository as a static site. The clock updates once per second and uses the device's local time and date. If location access is allowed in the browser, it also fetches current weather from Open-Meteo without an API key.

## iPad focus

The layout is tuned for the original iPad and iOS 5-era Mobile Safari, while still scaling cleanly for modern browsers and portrait orientation.

## Files

- `index.html` — the complete clock application.
- `AGENTS.md` — project guidance for future coding agents.

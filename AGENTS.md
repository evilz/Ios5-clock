# AGENTS.md

## Project overview
This repository contains a single-page, iPad-focused fullscreen digital clock inspired by Big Clock, Braun minimalism, and Apple iOS 5 design language.

## Design principles
- Keep the interface extremely minimal and high contrast.
- Preserve the pure black background and large Helvetica-style white digits.
- Optimize for the original iPad viewport and iOS 5-era Safari support.
- Avoid unnecessary controls; only tiny corner utility icons should be visible.
- Prefer CSS and vanilla JavaScript over external dependencies.

## Development notes
- `index.html` is intentionally self-contained for easy deployment.
- Maintain legacy-friendly CSS where practical, including `-webkit-` prefixed properties for older Mobile Safari.
- Do not add build tooling unless the app grows beyond a single static page.

## Testing
After visual or code changes, open `index.html` in a browser and verify the clock remains legible in landscape and portrait orientations.

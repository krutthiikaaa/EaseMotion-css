# Prefers Reduced Motion Demo

A standalone accessibility demonstration showing how the CSS media query `@media (prefers-reduced-motion: reduce)` can be used to respect user preferences and disable animations for people who are sensitive to motion.

## Overview

Many users experience discomfort, dizziness, or even seizures when exposed to excessive on-screen motion. Modern operating systems provide a **"Reduce motion"** accessibility setting that web developers can detect using the `prefers-reduced-motion` media query. This demo illustrates the technique in practice.

## Features

- **Accessibility friendly** — Fully respects the user's reduced-motion preference at the OS level.
- **Motion reduction support** — All animations and transitions are gracefully disabled when `prefers-reduced-motion: reduce` is active, without breaking the layout.
- **Original CSS animations** — Custom `fade`, `slide`, and `pulse` keyframe animations written from scratch (no external frameworks).
- **Professional card layout** — Glassmorphism-styled demo card with hover effects and a shimmer button.

## How to Run

1. Open `demo.html` in any modern web browser.
2. To test reduced motion:
   - **Windows:** Settings → Accessibility → Visual effects → turn off "Animation effects".
   - **macOS:** System Settings → Accessibility → Display → enable "Reduce motion".
   - **Linux (GNOME):** Settings → Accessibility → enable "Reduce animation".
   - **iOS:** Settings → Accessibility → Motion → enable "Reduce Motion".
   - **Android:** Settings → Accessibility → enable "Remove animations".

## File Structure

```
prefers-reduced-motion-demo/
├── demo.html   — HTML5 page with the demo card and animated elements
├── style.css   — Original CSS with animations and reduced-motion overrides
└── README.md   — This file
```

## Contribution Notes

This example demonstrates accessibility best practices using `prefers-reduced-motion`. It was created as a standalone submission for the [EaseMotion CSS](https://github.com/krutthiikaaa/EaseMotion-css) project. No existing repository files were modified.

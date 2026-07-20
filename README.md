# Solar System Visualization

A pure CSS animation of the solar system. Planets orbit the sun at relative speeds and distances, and the moon orbits Earth, all rendered without JavaScript or external libraries.

## Why This Project

This project demonstrates how far CSS custom properties, keyframe animations, and absolute positioning can go. It is a lightweight, dependency-free way to visualize orbital mechanics and practice responsive, animation-driven UI design.

## Features

- Pure HTML/CSS solar system animation
- CSS custom properties for orbital timing and planet sizing
- Relative orbital speeds based on real planetary data
- Responsive, centered layout
- No JavaScript dependencies

## Tech Stack

- **HTML5**
- **CSS3** (custom properties, keyframe animations, absolute positioning)

## Project Structure

```
├── index.html        # Solar system markup
├── style_test.css    # Animations and styling
└── script.js         # Placeholder (no logic required)
```

## Quick Start

1. Clone or download the repository.
2. Open `index.html` in any modern web browser.

   ```bash
   # On macOS/Linux
   open index.html

   # On Windows
   start index.html
   ```

3. Watch the planets orbit the sun.

## How It Works

- Each planet is an absolutely positioned element inside a shared solar-system container.
- Orbital paths are created with circular borders, and planets are animated with a rotating `transform`.
- CSS custom properties define the base Earth orbit time; other planets scale from that value to approximate real relative orbital periods.
- The moon is nested inside Earth and has its own faster orbit animation.

## What I Learned

- How to coordinate multiple CSS animations using custom properties.
- Techniques for creating visually engaging motion with only HTML and CSS.
- The value of keeping demos lightweight and dependency-free.

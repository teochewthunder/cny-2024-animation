# CNY 2024 Animation (TBC)
This animation is made using jQuery UI for the Year of the Dragon.

**Objective:**
- To have an animated Chinese character in the background with a "shimmering effect".
- Some text (static) in the foreground.

**Implementation:**
- We have a PNG file of the Chinese character for "dragon".
- One main div has tis image as the background.
- There are several smaller square divs within this big div, each color coded in yellow (with varying opacity) or no color depending on where on the character it falls on. Squares that have 100% occpancy of the character have 100% opacity. Squares that have over 50% occupancy have a slightly lower opacity. Squares with below 50% occpancy have an even lower opacity.
- jQuery UI is used to manipulate these opacities with a random delay.

# Web Dev I Lab Assignment 3: Responsive Personal Portfolio Website (CSS Advanced)

## Description
A mobile-first, one-page responsive personal portfolio website built using semantic HTML5 and modern CSS3 techniques. The project upgrades a basic static layout into an interactive, cross-device web application using **Flexbox**, **CSS Grid**, **relative units (`rem`, `em`, `%`, `vw`, `vh`)**, **CSS transitions**, and **keyframe animations**.

## Key Features Implemented
- **Flexbox Layout:** Used in the sticky navigation header and the hero section to align text and profile artwork cleanly across viewports.
- **CSS Grid Layout:** Applied to the **My Skills** and **My Projects** sections to organize cards into responsive rows and columns.
- **Animations & Hover Effects:**
  - `@keyframes colorShift` animates the hero role title continuously.
  - `@keyframes fadeSlideUp` smoothly reveals sections on page load.
  - Hover transforms (`translateY` and `scale`) and box-shadow transitions on navigation links, skill cards, project cards, and buttons.
- **Relative Units:** Spacing, typography, and container sizing use `rem`, `em`, `%`, `vw`, and `vh` instead of fixed pixel values.

## Steps to View & Test Responsive Behavior
1. Clone or download this repository and open `index.html` in any modern web browser (Chrome, Firefox, Edge, or Safari).
2. Open Browser Developer Tools (`F12` or `Cmd + Option + I` on macOS) and toggle the **Device Toolbar** (`Ctrl + Shift + M` / `Cmd + Shift + M`).
3. Test across the following breakpoints:
   - **Mobile (`< 768px` / `< 48rem`, e.g., `375px` width):** Navigation stacks vertically, hero profile image stacks cleanly above the intro text, and skill/project cards display in a single column.
   - **Tablet (`768px` – `1023px` / `48rem` – `63.9rem`, e.g., `768px` width):** Header aligns horizontally, hero switches to a side-by-side row layout, and skill/project cards arrange into a 2-column grid.
   - **Desktop (`>= 1024px` / `>= 64rem`, e.g., `1280px` width):** Full widescreen container alignment with a 3-column grid for skills and projects.
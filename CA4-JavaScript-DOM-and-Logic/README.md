# CA4 — JavaScript DOM & Logic

## Overview
The final assignment moved from static markup and styling into interactive, stateful behavior with vanilla JavaScript — DOM manipulation, event handling, browser storage, and basic object-oriented design. All JavaScript and CSS live in their own files; no inline scripts or `onclick` attributes were used.

## What's Inside

### Q1 — Live Hex Color Picker
A text input that accepts a hex color code and live-updates a preview square as the user types, with input validation (rejecting malformed hex values and displaying an "INVALID COLOR!" message) and a matching update to the page's text-selection color when a valid value is entered.

### Q2 — Light/Dark Mode Toggle
A themeable page that switches between light and dark modes via CSS custom properties, persists the user's choice in `localStorage`, and falls back to the operating system's preference (`prefers-color-scheme`) on first load. Includes a smooth-scroll call-to-action button and two reusable JS functions for applying each theme.

### Q3 — Student Grade Calculator
A small app where users add students with weighted scores across three subjects. An `Add` button appends each student to an in-memory list backed by a JS class with its own GPA-calculation method (not just DOM text), and a `Finish` button sorts and displays the final ranking by weighted average. Includes a `Reset` flow and full form validation via `required` / `min` / `max` constraints, with `preventDefault` handling the submit event.

## Key Skills
- DOM selection, manipulation, and event listeners
- Real-time input validation and UI updates
- Browser storage (`localStorage`) for persisting user state across sessions
- Media queries in JS (`prefers-color-scheme`) for system-aware defaults
- Object-oriented JavaScript (classes and instance methods)
- Array management and custom sorting logic
- Separation of concerns: HTML, CSS, and JS each in their own files

## What I Learned
This was the first assignment where state and behavior, not just appearance, were the actual deliverable. Building the grade calculator reinforced thinking in terms of data structures (a `Student` class with its own behavior) rather than manipulating the DOM directly, and the theme-toggle exercise was a practical introduction to persisting and respecting user preferences across page loads.

## Folder Structure
```
CA4-JavaScript-DOM-and-Logic/
├── Q1/
├── Q2/
└── Q3/
```

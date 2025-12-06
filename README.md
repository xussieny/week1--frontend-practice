# Mobile Toggle — Responsive Frontend Practice

This is a small, self-contained responsive front-end project demonstrating a mobile-friendly toggle UI and layout patterns. It includes a single-page static prototype with HTML, CSS, and JavaScript that adapts across screen sizes.

**Features:**
- **Toggle UI:** A responsive toggle control that works on touch and mouse input.
- **Responsive layout:** Scales between mobile, tablet, and desktop breakpoints.
- **Minimal JS:** Lightweight scripts in `script.js` to handle interactions.
- **Accessible markup:** Semantic HTML and keyboard-friendly controls.

**Preview:**
- Open `index.html` in your browser or serve the folder with a simple static server to test responsiveness and toggle behavior.

**Technologies:**
- **HTML5** — semantic structure in `index.html`.
- **CSS3** — responsive styles in `styles.css` (media queries, flexible units).
- **Vanilla JavaScript** — interactivity in `script.js`.

**Getting Started**

1. Clone the repo (if you haven't already):

```
git clone https://github.com/xussieny/week1--frontend-practice.git
```

2. Open the project in your browser:

```
# Option A: Open the file directly
start index.html

# Option B: Serve with a quick static server (recommended for CORS / modern APIs)
# Using Python 3:
python -m http.server 8000
# Or using npm http-server (if installed):
npx http-server -p 8000
```

Then visit `http://localhost:8000` (or open the local file) to view the page.

**Project Structure**

- `index.html` — main page and markup.
- `styles.css` — responsive styles and layout rules.
- `script.js` — toggle behavior and any small interaction logic.
- `README.md` — this file.

**Responsive Behavior**

- The layout uses flexible units and media queries to adapt at typical breakpoints (mobile-first).
- The toggle component is sized and spaced appropriately for touch targets on small screens.

**Accessibility Notes**

- Use semantic elements and ARIA where necessary. Ensure the toggle is keyboard-focusable and provides visible focus styles.
- Test with keyboard navigation and a screen reader to ensure state changes are announced.

**Development Tips**

- Keep styles mobile-first and add breakpoint overrides for larger screens.
- Keep JavaScript minimal; prefer CSS transitions for animations when possible.

**Contributing**

- This is a simple practice repo — feel free to fork and experiment. Open a PR if you want me to review changes or add features.

**License**

- This project is provided for practice and learning. Reuse as you like with attribution.

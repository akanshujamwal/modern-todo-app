# Taskline.

**Your day, organized.** A production-grade, single-file todo application with a warm editorial aesthetic and zero dependencies.

---

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

---

## Overview

Taskline is a lightweight, client-side task manager built as a single HTML file. No frameworks, no build steps, no backend — just open and use. Designed with an intentional editorial aesthetic that feels like a well-typeset notebook rather than a generic productivity tool.

---

## Features

| Feature | Description |
|---|---|
| **Add / Edit / Delete** | Full CRUD with inline delete confirmation |
| **Completion Toggle** | Custom animated checkboxes with visual feedback |
| **Smart Filters** | Switch between All, Active, and Completed views |
| **Live Stats** | Real-time count of total, active, and done tasks |
| **Relative Timestamps** | "5m ago", "2h ago" — always know when you added a task |
| **Clear Completed** | One-click cleanup for finished tasks |
| **Session Persistence** | Tasks survive page refreshes via sessionStorage |
| **Keyboard Shortcuts** | `Enter` to add tasks, `Esc` to close modals |
| **XSS Protected** | All user input is sanitized before rendering |

---

## Design Philosophy

Taskline deliberately avoids the generic "AI-generated app" look. The design choices are intentional:

- **Typography** — DM Serif Display paired with Source Sans 3 for a refined editorial feel
- **Palette** — Warm creams, earthy terracotta (`#c45d3e`), and muted sage (`#5a7a64`) instead of the usual blue/purple gradients
- **Motion** — Subtle staggered animations on load, smooth checkbox transitions, and hover micro-interactions
- **Whitespace** — Generous spacing that lets the interface breathe

---

## Responsiveness

Taskline is fully responsive across all breakpoints:

```
320px+   Mobile      → Stacked input, scrollable filters, always-visible actions
640px+   Tablet      → Side-by-side input + button, refined spacing
900px+   Desktop     → Full-width layout with hover-reveal action buttons
Print    Media       → Clean output with interactive elements stripped
```

---

## Getting Started

**Option 1 — Just open it**

```bash
open todo-app.html
```

**Option 2 — Serve locally**

```bash
# Python
python3 -m http.server 3000

# Node
npx serve .
```

Then visit `http://localhost:3000/todo-app.html`

---

## Project Structure

```
.
├── todo-app.html      # The entire application — markup, styles, and logic
└── README.md          # You are here
```

Yes, it's one file. That's the point.

---

## Accessibility

- Semantic HTML with proper `role` attributes (`list`, `listitem`, `tablist`, `tab`, `dialog`)
- ARIA labels on all interactive elements
- `:focus-visible` outlines for keyboard navigation
- Escape key closes modals and cancels confirmations
- Native checkbox behavior preserved under custom styling

---

## Browser Support

| Browser | Supported |
|---|---|
| Chrome 90+ | ✅ |
| Firefox 90+ | ✅ |
| Safari 15+ | ✅ |
| Edge 90+ | ✅ |
| Mobile Safari | ✅ |
| Chrome Android | ✅ |

---

## Technical Notes

- **No dependencies** — zero npm packages, zero CDN libraries (fonts excluded)
- **No build step** — no bundler, transpiler, or compiler required
- **XSS safe** — user input escaped via `textContent` before DOM insertion
- **IIFE scoped** — all JavaScript wrapped in an immediately-invoked function expression to avoid global pollution
- **Event delegation** — single listener on the task list handles all task interactions
- **Print ready** — `@media print` rules produce a clean, ink-friendly output

---

## Customization

All visual tokens are defined as CSS custom properties at the top of the file:

```css
:root {
  --ink: #1a1612;        /* Primary text */
  --paper: #faf8f5;      /* Card backgrounds */
  --cream: #f3efe9;      /* Page background */
  --accent: #c45d3e;     /* Terracotta — primary action color */
  --sage: #5a7a64;       /* Green — completion color */
  --font-display: 'DM Serif Display', Georgia, serif;
  --font-body: 'Source Sans 3', 'Segoe UI', sans-serif;
}
```

Change these and the entire app updates.

---

## License

MIT — do whatever you want with it.

---

<p align="center">
  <em>Built with care, shipped in one file.</em>
</p>

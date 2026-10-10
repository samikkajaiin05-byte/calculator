# Premium Calculator

A polished, responsive calculator built with React, Vite, JavaScript, and CSS. It uses a small safe expression parser rather than `eval()` and supports mouse/touch input plus keyboard controls.

## Features

- Addition, subtraction, multiplication, division
- Decimal input and sign toggle
- Percentage behavior for common calculator workflows
- AC, CE, backspace
- Operator replacement and consecutive-operator handling
- Division-by-zero and invalid-expression protection
- Repeated equals (`5 + 3 = =` → `11`)
- Floating-point cleanup (`0.1 + 0.2` displays `0.3`)
- Responsive desktop/mobile layout with safe-area support
- Accessible semantic buttons, labels, live display, visible keyboard focus
- Reduced-motion support
- No backend, API key, database, or internet runtime dependency

## Requirements

- Node.js 18+ recommended
- npm

## Install and run

```bash
npm install
npm run dev
```

Then open the local Vite address shown in the terminal.

## Production build

```bash
npm run build
```

The production files are generated in `dist/`.

To preview the production build locally:

```bash
npm run preview
```

## Netlify deployment

1. Push this folder to GitHub/GitLab/Bitbucket, or upload the project to Netlify.
2. Set the build command to `npm run build`.
3. Set the publish directory to `dist`.
4. Deploy.

No environment variables are required.

## Keyboard controls

- `0–9` — digits
- `.` — decimal
- `+ - * /` — operators
- `Enter` or `=` — equals
- `Backspace` — delete one character
- `Escape` — AC
- `%` — percentage

## Project structure

```text
premium-calculator/
├── index.html
├── package.json
├── README.md
└── src/
    ├── main.jsx
    └── styles.css
```

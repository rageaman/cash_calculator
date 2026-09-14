# Cash Calculator

A simple browser-based calculator for counting Indian cash by entering the quantity of each note and coin denomination.

## Features

- Calculates the total value of entered cash quantities
- Supports these denominations:
  - ₹2000
  - ₹500
  - ₹200
  - ₹100
  - ₹50
  - ₹20
  - ₹10
  - ₹5
  - ₹2
  - ₹1
- Updates the total when quantities are entered or changed
- Accepts whole-number quantities only
- Responsive layout for desktop and mobile screens
- Keyboard shortcuts for faster entry
- No build tools, dependencies, account, or setup required

## Keyboard Shortcuts

- `Enter` — move to the next denomination
- `Shift + Enter` — move to the previous denomination
- `Ctrl/Cmd + Enter` — calculate the total
- `Escape` — clear the focused field
- `+` / `Arrow Up` — increase the focused quantity by 1
- `-` / `Arrow Down` — decrease the focused quantity by 1
- `Ctrl/Cmd + R` — reset all fields
- `Ctrl/Cmd + Backspace` — clear all fields

## Built With

- HTML5
- CSS3
- JavaScript

## Project Structure

```text
cash_calculator/
├── index.html
└── README.md
```

## Run Locally

No installation or build step is required.

```bash
git clone https://github.com/rageaman/cash_calculator.git
cd cash_calculator
```

Open `index.html` directly in a browser.

Alternatively, run a simple local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Notes

The project is a single-page calculator. The calculation logic and styling are contained in `index.html`.

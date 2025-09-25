# Conference Expense Planner (React + Vite + Tailwind)

A practice project that estimates conference costs (rooms, AV add-ons, meals) with a live total and a four‑column “Show Details” summary.

## Features
- Landing page with hero + CTA
- Product selection page with sections for **Rooms**, **Add-ons**, **Meals**
- Increment/decrement counters for rooms & add-ons; text entry for meal headcounts
- Live subtotal, GST, and total
- **Show Details** modal with a 4‑column table (Selection | Unit Cost | Quantity | Subtotal) and **Total**
- CSV export of the summary

## Tech
- React 18, React Router 6, Vite
- Tailwind CSS 3

## Prerequisites
- Node.js 18+ and npm

## Setup (one-time)
```bash
npm install
```

## Run in dev
```bash
npm run dev
```
Open the printed local URL (usually http://localhost:5173).

## Build for production
```bash
npm run build
npm run preview
```

## Project structure
```
.
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
├── src
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   └── pages
│       ├── LandingPage.jsx
│       └── ProductSelectionPage.jsx
└── README.md
```

## Customization tips
- Replace the landing background image in `LandingPage.jsx` (search for `backgroundImage`).
- Change prices or product lists in `ProductSelectionPage.jsx`: the arrays `ROOMS`, `ADDONS`, `MEALS`.
- Adjust GST by editing `taxRate` in `ProductSelectionPage.jsx`.

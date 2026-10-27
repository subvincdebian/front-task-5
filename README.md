<img src="https://raw.githubusercontent.com/subvincdebian/subvincdebian/main/assets/repo-front-task-5.svg" alt="front-task-5 project overview" width="100%" />

# Frontend Task 5 — React Counter

Frontend coursework introducing React state through a small counter app, with Ukrainian interface copy and a Vite development setup.

## What it demonstrates

- Increment, decrement and reset the counter with React `useState`.
- React and Vite logo links accompany the counter.
- CSS supplies a dark layout, hover effects and a logo animation that respects reduced-motion preferences.

## Stack

React 19, TypeScript 5.7, Vite 6.2 and ESLint 9. Dependencies are pinned by `package-lock.json`.

## Run locally

Use Node.js 22 or newer and npm.

```sh
cd my-app
npm ci
npm run dev
```

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Run TypeScript project checks, then build with Vite |
| `npm run lint` | Run ESLint |
| `npm run preview` | Preview an existing production build |

Run all npm commands from `my-app/`.

## Source map

- [`my-app/src/App.tsx`](my-app/src/App.tsx) — Counter state and interface.
- [`my-app/src/App.css`](my-app/src/App.css) — Counter layout and visual styles.
- [`my-app/src/index.css`](my-app/src/index.css) — Global styles and button focus rules.
- [`my-app/package.json`](my-app/package.json) — Application dependencies and scripts.

## Project scope

Counter state lasts only for the current page session. This is a learning exercise without a backend or persistence. No automated test script is configured.

Original task label: **front-5** — `Frontend Task 5`.

The original Vite setup and optional ESLint guidance remain in the [application README](my-app/README.md).

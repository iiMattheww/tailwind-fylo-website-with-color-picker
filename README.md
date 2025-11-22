# Fylo Landing — Tailwind Practice

A small practice project: a responsive Fylo-style landing page built with Tailwind CSS and Vite. Includes a light/dark theme toggle (stores preference in `localStorage`) and is intended for personal reference and learning.

**Quick Start**
- **Prerequisites:** `node` (v16+) and `npm` installed.
- **Install:**

```
npm install
```

- **Dev server:**

```
npm run dev
```

- **Build:**

```
npm run build
npm run preview
```

**What you'll find**
- **Description:** Responsive landing page with hero, features, testimonials, and footer — based on the "Fylo" design.
- **Dark mode:** Toggle implemented in `src/script.js` and persisted in `localStorage`.
- **Tooling:** Built with `vite` for development and `tailwindcss` for styling.

**Tech stack**
- HTML, JavaScript, Tailwind CSS
- Vite (dev server / build tooling)

**Repository structure (important files)**
- `index.html` — main page
- `src/style.css` — compiled Tailwind stylesheet entry
- `src/script.js` — theme toggle logic
- `src/assets/` — images and icons
- `vite.config.ts` — Vite configuration
- `package.json` — scripts: `dev`, `build`, `preview`

**Usage notes**
- This is a practice project intended for personal reference or a portfolio demo. Feel free to fork, customize styles, or replace images.
- Update the `title`, `author` or `LICENSE` if you publish this to your GitHub profile.

**License**
- See the `LICENSE` file in this repository.

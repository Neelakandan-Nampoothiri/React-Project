# Clientive

A small React + Vite landing page built in the `proj` folder. This workspace uses Vite, React 19, ESLint, and modern React component structure for a marketing-style landing site.

## Key features

- Vite-powered development server with HMR
- React 19 with component-based UI
- Lightweight landing page layout with hero, services, teams, trusted-by, and contact sections
- ESLint support for consistent code quality

## Tech stack

- React 19
- Vite
- ESLint
- @vitejs/plugin-react
- lightningcss
- motion
- react-hot-toast

## Project structure

Important files and folders inside `proj`:

- `index.html` — Vite entry HTML
- `src/main.jsx` — React application bootstrap
- `src/App.jsx` — Root application component
- `src/index.css` — Global styles
- `src/assets/assets.js` — Asset references
- `src/components/` — Reusable UI components

Notable components in `src/components`:

- `Navbar.jsx`
- `Hero.jsx`
- `Services.jsx`
- `ServiceCard.jsx`
- `OurWork.jsx`
- `Teams.jsx`
- `TrustedBy.jsx`
- `ContactUs.jsx`
- `Footer.jsx`
- `ThemeToggleBtn.jsx`
- `Title.jsx`

## Getting started

From the `proj` folder, install dependencies and start the development server.

```bash
cd proj
npm install
npm run dev
```

Then open the local Vite URL shown in your terminal.

## Available scripts

Run these inside `proj`:

- `npm run dev` — start Vite dev server
- `npm run build` — build production output
- `npm run preview` — preview the production build locally
- `npm run lint` — run ESLint across the project
- `npm run start` — preview server on `0.0.0.0` using `$PORT`

## Notes

- ESLint configuration is defined in `proj/eslint.config.js`.
- `proj/vite.config.js` configures Vite and React support.
- Add or update assets via `src/assets/assets.js` and reference them from components.

## Contributing

For fixes or improvements, create a branch and submit a PR against `main`.

## License

No license is included in this repository. Add one before publishing or sharing.

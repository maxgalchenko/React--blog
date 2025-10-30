# React Blog

<div align="center">

[![React](https://img.shields.io/badge/React-16.13.1-61DAFB?logo=react&logoColor=white)](https://react.dev/)
[![React Router](https://img.shields.io/badge/React%20Router-5.x-CA4245?logo=reactrouter&logoColor=white)](https://reactrouter.com/)
[![Sass](https://img.shields.io/badge/Sass-SCSS-CC6699?logo=sass&logoColor=white)](https://sass-lang.com/)
[![Create React App](https://img.shields.io/badge/Create%20React%20App-3.4.1-09D3AC?logo=createreactapp&logoColor=white)](https://create-react-app.dev/)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-181717?logo=github)](https://pages.github.com/)

</div>

## Overview

A simple single‑page blog UI built with React and SCSS. It demonstrates routing, reusable components, and a clean layout suitable for portfolio or learning purposes. Deployed via GitHub Pages.

## Key Features

- Home, Posts, and Post detail navigation (React Router 5)
- Search and category-driven browsing UI
- Responsive SCSS styling with reusable cards and post galleries

## Tech Stack

React 16, Create React App, React Router 5, Sass

## Architecture

SPA built with Create React App. Client-side routing via `react-router-dom` v5, styles authored in SCSS, static assets served from `public/` and `src/blogpostImages/`. Componentized layout with header, hero, galleries, and sidebars.

## Performance & Accessibility

Basic CRA code-splitting, static asset delivery, and SCSS organization. Semantic HTML and keyboard-focusable navigation; tune further for contrast and landmarks as needed.

## Quality

- Linting: ESLint (react-app, airbnb) • Formatting: Prettier
- Type safety: None (JavaScript project)
- Tests: Testing Library deps present; no test files committed
- CI: None • Coverage: N/A

## Prerequisites

- Node.js: `14.x`

## Installation

```bash
git clone https://github.com/maxgalchenko/React--blog.git
cd React--blog
npm install
```

## Quick Start

```bash
# Development
npm start

# Production build
npm run build

# Deploy to GitHub Pages
npm run deploy
```

Open http://localhost:3000

## Available Scripts

- `npm start` – Start the development server (CRA)
- `npm run build` – Build the app for production to `build/`
- `npm test` – Run tests in watch mode (no tests committed)
- `npm run eject` – Eject CRA configuration (one-way)
- `npm run deploy` – Deploy the built app to GitHub Pages

## Screenshots

![Main](public/localhost_3000_React--blog_.png)

---

<div align="center">

**Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)

![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>

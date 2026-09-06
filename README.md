# Akki's Coffee

A coffee-themed React experience built with Vite. The app includes animated typography, coffee videos, falling coffee beans, steam effects, interactive origin cards, a custom coffee cursor, and responsive layouts.

## Requirements

- Node.js 18 or newer
- npm

## Development

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL shown by Vite, usually `http://localhost:5173/`.
UI `https://akkiscoffeewebsite-a1y08el03-portfolio-a81e.vercel.app/`
## Production build

Create an optimized production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## Project structure

```text
src/
	App.jsx          React app entry component
	CoffeeBar.jsx    Main page and interactive behavior
	CoffeeBar.css    Application styles and animations
	main.jsx         React DOM entrypoint
public/
	*.mp4            Coffee video assets served as static files
```

## Deploy to Vercel

Import this repository into Vercel with these settings:

- Framework preset: `Vite`
- Build command: `npm run build`
- Output directory: `dist`
- Install command: `npm install`

The MP4 files belong in `public/` so Vercel serves them from the site root.

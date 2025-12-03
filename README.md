# CineWave
Find your favorite movie or tv show ratings

https://cinewave.netlify.app/

## About
CineWave is a small React + Vite app that displays movies and TV shows, their ratings, details, and related media. It uses The Movie Database (TMDb) APIs (or similar) via axios and presents results with a responsive UI built with Sass.

## Demo
Live demo: https://cinewave.netlify.app/

## Features
- Browse trending, popular and top-rated movies/TV shows
- Search and view details, cast, trailers, and recommendations
- Infinite scroll and lazy-loaded images
- Responsive UI with custom components (carousel, rating circle, video popup)

## Technologies
- React (18)
- Vite
- Redux Toolkit
- Axios
- react-player
- Sass
- react-lazy-load-image-component

(See package.json for full dependency list.)

## Getting Started
Prerequisites:
- Node.js (v14+ recommended)
- npm or yarn

Install dependencies:

```bash
npm install
# or
# yarn
```

Run in development mode (Vite):

```bash
npm run dev
# opens at http://localhost:5173 by default
```

Build for production:

```bash
npm run build
```

Preview production build locally:

```bash
npm run preview
```

## Project Structure (high level)
- src/
  - components/        # Reusable UI components (carousel, movie card, header, etc.)
  - pages/             # Page views (home, details, explore, search)
  - hooks/             # Custom hooks (useFetch)
  - store/             # Redux store and slices
  - utils/             # API helpers
  - assets/            # Images and logos

## Notes
- The app uses Vite's dev server (see `index.html` in the project root which mounts the React app).
- Top-rated section and other endpoints toggle between movie and tv based on UI tabs.

## Contributing
Contributions are welcome. Open an issue or PR with proposed changes.

## License
This repository does not include a license file. Check with the project owner for licensing details.

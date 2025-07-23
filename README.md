# usePopcorn

A React app for searching movies, rating them, and keeping track of your watched list. Built with hooks and custom components.

## Features

- Search movies using the OMDb API
- View movie details and rate them
- Add movies to your watched list
- Persist watched movies using localStorage
- Responsive and modern UI

## Getting Started

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yuktabande/usePopcorn
   cd final
   ```
2. Install dependencies:
   ```sh
   npm install
   ```

### Running the App

Start the development server:
```sh
npm start
```
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### Building for Production

```sh
npm run build
```

## Project Structure

- `src/` — Source code
  - `App.js` — Main app component
  - `StarRating.js` — Custom star rating component
  - `useMovies.js` — Custom hook for fetching movies
  - `useLocalStorageState.js` — Custom hook for localStorage
  - `useKey.js` — Custom hook for keyboard events
  - `index.js`, `index.css` — Entry point and styles
- `public/` — Static assets and HTML template

## Custom Hooks

- `useMovies`: Fetches movies from OMDb API.
- `useLocalStorageState`: Persists state in localStorage.
- `useKey`: Handles keyboard shortcuts.

## License

MIT

---

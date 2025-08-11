# React Movie List

A sleek and responsive **React** application built with **Vite**, allowing users to explore movies, mark favorites, and persist preferences using local storage.

## Features

- Browse a list of movies (can be extended to fetch from APIs)
- Add and remove movies from favorites
- Favorites are saved across sessions using `localStorage`
- Built with fast development experience via **Vite + React Fast Refresh**
- ESLint included for clean and maintainable code

## Live Demo

_(Add a deployment link here if you host the app — e.g., Netlify, Vercel, GitHub Pages)_

## Getting Started

### Prerequisites

- Node.js (v14 or later recommended)
- npm or yarn

### Setup

```bash
git clone https://github.com/imamulkadir/React_MovieList.git
cd React_MovieList
npm install
npm run dev
```

Now open http://localhost:5173 in your browser to explore the app with live reload.

### Build for Production

```bash
npm run build
npm run preview
```

### Project Structure

```
/
├── public/                 # Static assets
├── src/
│   ├── components/         # React components (MovieList, MovieCard, etc.)
│   ├── context/            # Context and custom hooks (MovieContext, useMovieContext)
│   ├── pages/              # Page-level components (e.g., Home.jsx)
│   ├── App.jsx             # Application root
│   └── main.jsx            # Entry point
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

Developed and maintained by: [Imamul Kadir](https://www.linkedin.com/in/imamulkadir)

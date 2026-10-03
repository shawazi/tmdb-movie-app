# TMDB Movie App

A React movie discovery app powered by the TMDB API. Search, browse trending titles, and view details.

## Current State

- **Status:** Working
- **Last real activity:** 2024-07-29 -- CNAME and deployment
- **Deployed:** [movies.shawaz.org](https://movies.shawaz.org) via GitHub Pages

## Features

- Browse and search movies via the TMDB API
- User authentication (email/password and Google sign-in)
- Movie detail pages with descriptions and metadata
- Password reset flow
- Toast notifications

## Setup

### Prerequisites

- Node.js >= 18

### Environment Variables

- `VITE_apiKey`
- `VITE_authDomain`
- `VITE_projectId`
- `VITE_storageBucket`
- `VITE_messagingSenderId`
- `VITE_appId`
- `VITE_measurementId`
- `VITE_MOVIE_API_KEY`

### Run

```bash
npm install
npm run dev
```

### Build

```bash
npm run build
npm run preview
```

### Deploy

```bash
npm run deploy    # builds and pushes to gh-pages branch
```

## Tech Stack

- React 18, React Router
- Vite
- Axios
- Formik + Yup (form validation)

## Where It Needs to Go

- Upgrade dependencies (React 18 / Vite 4 are behind current)
- Add tests

## How to Proceed

1. Create a `.env` file with the variables listed above (get a TMDB API key from themoviedb.org).
2. `npm install && npm run dev`

## Licence

MIT

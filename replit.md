# StreamOtaku - Streaming Media Application

## Overview
StreamOtaku is a streaming media application that allows users to browse and watch movies, TV shows, and anime. Built with React, TypeScript, and Tailwind CSS. Imported from Lovable.

## Recent Changes
- 2026-02-06: Imported from Lovable to Replit environment
- Updated Vite config to bind to 0.0.0.0:5000 for Replit compatibility
- Removed lovable-tagger dependency from vite config

## Project Architecture
- **Frontend Only**: This is a client-side React application with no backend server
- **Framework**: React 18 + TypeScript + Vite
- **Styling**: Tailwind CSS + shadcn/ui components
- **Routing**: react-router-dom v6
- **State/Data**: @tanstack/react-query
- **API**: Uses TMDB API for movie/TV data

## Project Structure
```
src/
  components/       - Reusable UI components (Navbar, MediaCard, HeroSection, etc.)
  components/ui/    - shadcn/ui base components
  pages/            - Route pages (Index, Movies, TVShows, Anime, Search, Watchlist, etc.)
  hooks/            - Custom React hooks
  lib/              - Utility functions and API clients (tmdb.ts, servers.ts, vidlink.ts)
  assets/           - Static assets (logo)
  index.css         - Global styles and Tailwind config
```

## Key Pages
- Home (Index) - Featured content and trending media
- Movies - Browse movies
- TV Shows - Browse TV series
- Anime - Browse anime content
- Search - Search across all media
- Watchlist - User's saved watchlist (localStorage)
- MovieDetails / TVDetails - Detail pages with video player
- WatchPage - Video playback page

## Running
- `npm run dev` starts the Vite dev server on port 5000

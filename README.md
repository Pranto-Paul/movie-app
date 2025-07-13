# Movie App

A modern React + Vite web application to search and discover movies using The Movie Database (TMDb) API, with trending search analytics powered by Appwrite.

## Features

- 🔍 Search thousands of movies instantly
- 📈 View trending movies based on search popularity
- 🎬 Beautiful movie cards with ratings, language, and release year
- ⚡ Fast and responsive UI with Tailwind CSS
- 🗄️ Appwrite backend for tracking trending searches

## Tech Stack

- React
- Vite
- Tailwind CSS
- Appwrite (for trending analytics)
- TMDb API

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Pranto-Paul/movie-app.git
cd movie-app
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Copy `.env.local` and update it with your TMDb API key and Appwrite credentials.

**.env.local**

```env
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_ENDPOINT=your_appwrite_endpoint
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
```

### 4. Run the development server

```bash
npm run dev
```

### 5. Open in browser

Visit [http://localhost:5173](http://localhost:5173)

## Folder Structure

```
src/
  App.jsx
  appwrite.js
  index.css
  main.jsx
  assets/
  components/
    MovieCard.jsx
    Search.jsx
    Spinner.jsx
public/
  hero-bg.png
  hero.png
  logo.png
  no-movie.png
  search.svg
  star.svg
  vite.svg
```

## Customization

- Update styles in `index.css` (uses Tailwind CSS and custom classes)
- Modify backend logic in `appwrite.js`
- UI components are in the `components/` folder

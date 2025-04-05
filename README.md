# 🎬 Movie App

A sleek movie search and favorites app using ReactJS, TMDB API, and localStorage. Search movies, view popular titles, and save your favorites — all in a stylish UI!

## 🚀 Features
- 🔍 Search for movies using **TMDB API**
- 🌟 Mark movies as favorites (saved in **localStorage**)
- 🖼️ Display movie posters, titles, and release years
- 🔄 Responsive and fast user interface

## 🛠️ Tech Stack
- **Frontend:** ReactJS, CSS
- **Routing:** React Router DOM
- **State Management:** React Context API
- **API:** [The Movie Database (TMDB)](https://www.themoviedb.org/)
- **Persistence:** localStorage

##  How It Works
1. On launch, the app loads popular movies from TMDB.
2. User can:
   - Search for specific movies
   - Click the ❤️ icon to favorite/unfavorite
3. Favorites are stored in `localStorage` so they persist across sessions.

## 📸 Screenshots
![Home screenshot](./src/screenshots/home screenshot.png)


## 📁 Folder Structure
src/
├── components/
│   ├── MovieCard.jsx
│   └── NavBar.jsx
├── contexts/
│   └── MovieContext.jsx
├── pages/
│   ├── Home.jsx
│   └── Favorites.jsx
├── services/
│   └── api.js
├── css/
│   ├── App.css
│   ├── Home.css
│   ├── Navbar.css
│   ├── Favorites.css
│   └── MovieCard.css
├── App.jsx
├── main.jsx

##  Getting Started
Clone this repo and run it locally:
```bash
git clone https://github.com/your-username/movie-app.git
cd movie-app
npm install
npm run dev
```
##Future Plan
🌗 Dark/Light mode toggle (coming soon!)
🎭 Filter by genre, rating, release year




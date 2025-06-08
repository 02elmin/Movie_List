# Movie Watchlist App

## Live Demo
You can try out the live version of this project here:  
👉 [https://mubii-app-nadiamariduena.netlify.app/](https://mubii-app-nadiamariduena.netlify.app/) :contentReference[oaicite:0]{index=0}

## Description
A React application that lets you search for movies via The Movie Database (TMDb) API, add them to your **Watchlist** or **Watched** list, and persist your data in `localStorage`. Built with React Hooks and the Context API for clean, global state management. :contentReference[oaicite:1]{index=1}

## Features
- **Movie Search**  
  Query TMDb for movie titles as you type.  
- **Watchlist & Watched**  
  Add or remove movies from your personal Watchlist and mark movies as Watched.  
- **Persistent Storage**  
  All lists are saved in the browser’s `localStorage`, so you won’t lose your data on reload.  
- **Global State**  
  Uses React’s Context API & Hooks (`useState`, `useEffect`, `useContext`) to manage state across components. :contentReference[oaicite:2]{index=2}

## Technologies
- **React** (v18+)  
- **React Hooks**: `useState`, `useEffect`, `useContext`  
- **Context API** for global state  
- **TMDb API** for movie data :contentReference[oaicite:3]{index=3}  
- **CSS Modules** (or your preferred CSS strategy)  
- **localStorage** for client-side persistence  

## Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/02elmin/Movie_List.git
   cd Movie_List/react-movie-watchlist-master

# MoodMix – Frontend 🎧

React frontend for a **mood-based playlist generator**.  
Type how you feel, and MoodMix shows tracks that match your mood.

This repo contains the **client-side app**.  
The backend API (Node/Express) lives in a separate repository.

---

## 🌐 Overview

The user:

1. Types in a mood (for example: `calm`, `angry`, `study`, `hopeful`).
2. Clicks the button to generate a playlist.
3. The frontend calls a custom backend API.
4. The backend returns matching tracks.
5. MoodMix displays the results as responsive “cards” with:
   - song title  
   - artist  
   - album cover  
   - link to play the track

The app also saves past moods / playlists so the user can quickly re-run them.

---

## 🧱 Tech Stack

**Frontend**

- React (functional components + hooks)
- Fetch API for HTTP requests
- LocalStorage for saving recent moods / playlists
- Plain CSS for styling (no UI framework)
- Responsive layout with card-style design

---

## ✨ Features

- **Mood input form** – user types how they feel
- **Preset mood buttons** – quick options like “Chill”, “Focus”, etc.
- **Loading & error states** – shows clear feedback instead of blank screens
- **Track grid** – responsive layout of cards with:
  - album cover image  
  - track name  
  - artist name  
  - external link to listen
- **Saved playlists / history**
  - Uses `localStorage` to remember previous moods
  - User can quickly re-run a past mood without typing again

---

## 🏗 Project Structure

```text
src/
  api/
    playlist.js        // functions to call the backend playlist endpoint
  utils/
    savedPlaylists.js  // helper for saving / loading playlists from localStorage
  App.js               // main app component & layout
  App.css              // styling for the app and track cards
  index.js             // React entry point
  index.css            // base styles

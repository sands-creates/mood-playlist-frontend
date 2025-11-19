R# Mood Playlist – Frontend

React frontend for a mood-based playlist generator.  
Type how you feel, and the app shows tracks that match that mood.

---

## 🧱 Tech Stack

- React (functional components + hooks)
- Fetch API for calling the backend
- LocalStorage for saving recent moods
- Custom CSS for card-style UI and responsive layout

---

## ✨ Features

- Mood input box with quick-select mood buttons
- Loading and error states (no blank screens)
- Grid of track cards with:
  - song title
  - artist
  - album cover
  - link to play the track on the music service
- “Saved moods / playlists” section powered by LocalStorage

---

## 🏗 Project Structure

```text
src/
  api/
    playlist.js        # calls the backend API
  utils/
    savedPlaylists.js  # handles saving / loading playlists
  App.js
  App.css
  index.js

npm install
npm start


4. Scroll down and click **“Commit changes”**.

---

Once you finish the backend steps and/or the README edit, send me a screenshot or just say:

> “Backend pushed”  

and I’ll give you a matching README for the backend and help you with next polish (screenshots, description for your resume, etc.).

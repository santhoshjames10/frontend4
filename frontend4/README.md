Movie App – Built with React and Vite

This is a movie browsing app built using React, Vite, and the TMDb API. It lets users search for movies, view popular ones, and save favorites locally.

What You Can Do

- Search for movies by title
- Add or remove movies from your favorites
- Favorites are saved in localStorage
- Navigate using React Router
- State management with React Context
- Responsive design

How to Set It Up

1. Clone the repo

git clone https://github.com/yourusername/movie-app.git
cd movie-app

2. Install all dependencies

npm install

3. Set your TMDb API key

Open src/api.js and replace the placeholder string with your TMDb API key:

const API_KEY = "your_api_key_here";

You can also use a .env file and load it using import.meta.env.

4. Start the development server

npm run dev

Then open http://localhost:5173 in your browser.

Project Structure

src/
├── api.js                - API calls to TMDb
├── App.jsx               - Main app with routes
├── main.jsx              - App entry point
├── contexts/
│   └── MovieContext.jsx  - Context for favorites
├── Pages/
│   ├── Home.jsx          - Homepage with search
│   └── Favorites.jsx     - Favorites list
├── components/
│   └── MovieCard.jsx     - Movie card component
├── css/
│   ├── Home.css
│   ├── Favorites.css
│   └── Navbar.css

Available Commands

npm run dev     - Run development server
npm run build   - Create production build
npm run preview - Preview the production build

License

MIT License — 2025 Santhosh James
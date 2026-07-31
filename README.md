Note: this is not the project synopsis, just a README. For the synopsis, refer to Synopsis.md
# 🎬 Cine Verse

An animated movie search platform that lets you search for movies and instantly view rich details — poster, plot, cast, genre, release year, and ratings — powered by the TMDB API, with smooth, engaging UI transitions throughout.

## ✨ Features

- 🔍 Real-time movie search with debounced input
- 🎞️ Detailed movie view — poster, plot, cast, genre, rating, release year
- 🎬 Smooth animated transitions for search results, loading, and error states
- 📱 Fully responsive design (desktop and mobile)
- ⚠️ Graceful handling of empty results, invalid queries, and API errors

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript (or React) |
| Data Source | [TMDB API](https://www.themoviedb.org/documentation/api) |
| Animation | CSS Transitions / Framer Motion / GSAP |
| Styling | CSS3 / Tailwind CSS (optional) |

> Note: The data source is currently TMDB and may change depending on project requirements.

## 📸 Demo

[Coming soon]

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) installed (if using a framework like React)
- A free TMDB API key — [get one here](https://www.themoviedb.org/settings/api)

### Installation

```bash
# Clone the repo
git clone https://github.com/mishra-buddh/cine-verse.git

# Navigate into the project folder
cd cine-verse

# Install dependencies
npm install
```

### Environment Setup

Create a `.env` file in the root directory and add your TMDB API key:

```
VITE_TMDB_API_KEY= [your_api_key_here]
```

*(Adjust the variable name/prefix based on your build tool — e.g. `REACT_APP_` for Create React App, `VITE_` for Vite.)*

### Run the App

```bash
npm run dev
```

The app should now be running at `http://localhost:5173` (or whichever port your dev server uses).

## 📁 Project Structure

```
  [Will be updated]
```

## 🔮 Future Enhancements

- User authentication and personalised watchlists
- Advanced filtering (genre, year, rating)
- Trailer integration via YouTube API
- Dark/light theme toggle

## 📄 License

[----------------------------------------------------------------]

## 🙌 Acknowledgements
 
- [TMDB](https://www.themoviedb.org/) for the movie data API

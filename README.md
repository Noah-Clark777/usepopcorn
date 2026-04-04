usePopcorn – Movie Search & Watchlist App

A React-based movie discovery application that allows users to search for films, view detailed information, and manage a personal watchlist.
This project focuses on API integration, asynchronous data handling, and building a responsive, state-driven user interface.

Features:
* Search for movies by title
* View detailed movie information (ratings, plot, runtime)
* Add movies to a watched list
* Track personal ratings and viewing history
* Real-time UI updates based on user input
* Responsive design for all devices


Tech Stack:
* Frontend: React
* State Management: useState / useEffect / custom hooks
* API: Movie API (OMDb or similar)
* Styling: CSS
* Tooling: Vite / Create React App

Architecture & Key Concepts:
* Custom Hooks:
Encapsulated logic for fetching data and managing state (e.g., movie search, watched list).
* Asynchronous Data Fetching:
Uses fetch with async/await to retrieve movie data dynamically.
*State-Driven UI:
UI updates automatically based on search results and user interactions.
* Controlled Components:
Search input is fully controlled for predictable behavior.
*Conditional Rendering:
Handles loading states, errors, and empty results gracefully.
* Component-Based Design:
Structured into reusable components (Search, MovieList, MovieDetails, WatchedList).

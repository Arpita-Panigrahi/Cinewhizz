# Movie Website

A dynamic and modern movie website built using **React.js**. This project allows users to explore, search, and view details of movies by leveraging a third-party API. It was created as a learning project based on the [YouTube tutorial](https://youtu.be/G6D9cBaLViA?si=O3NIThdrOWi5OCVu).

## Features

1. **Discover Trending Movies**  
   - Displays a list of popular or trending movies fetched dynamically from a movie database API.  

2. **Search for Movies**  
   - Allows users to search for specific movies by title using a search bar.  

3. **Responsive User Interface**  
   - Adapts to different screen sizes, ensuring a smooth browsing experience on desktop, tablet, and mobile devices.  

4. **API Integration**  
   - Utilizes a third-party movie database API (e.g., TMDB) for real-time movie data.  

## Technologies Used

- **React.js**: For building the dynamic user interface.  
- **CSS3**: For styling and responsive layouts.  
- **React Hooks**: For managing state and lifecycle.  

## Installation and Usage

1. Clone the repository:  
   ```bash  
   git clone <repository-url>  
   cd movie-website  
   ```  

2. Install the dependencies:  
   ```bash  
   npm install  
   ```  

3. Start the development server:  
   ```bash  
   npm run dev  
   ```  

4. Open the website in your browser at `http://localhost:5173`.  

5. Ensure you have an API key from TMDB (or the relevant API) and update the `API_KEY` variable in the code.  

## Folder Structure

- `src/`  
  - `components/`: Contains reusable components like `Header`, `MovieCard`, and `SearchBar`.  
  - `pages/`: Includes main pages like `Home` and `MovieDetails`.  
  - `services/`: Contains API configuration and Axios instance.  
  - `styles/`: Centralized styling files.  

## React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


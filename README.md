# Movie/TV Show Explorer

Welcome to our Movie/TV Show Explorer, a dynamic single-page web application designed to help you explore movies and TV series with ease. This project utilizes a free API to provide comprehensive details about your favorite movies and TV shows.

## Features

- **Dynamic Single-Page Website:** The application updates content dynamically without full page reloads, providing a fast user experience.
- **Detailed Information:** View descriptions, synopses or plots, ratings, release dates, and casts of movies and TV series.
- **Watch Trailers:** A dedicated button redirects you to YouTube to watch trailers.
- **View Articles:** Another button provides access to related articles about the selected movie or TV series.
- **Live Search Recommendations:** Real-time data manipulation through web sockets delivers instant suggestions as you type in the search bar.
- **Loading Animations:** User-friendly loading animations appear during data transmission delays, ensuring a smooth user experience.
- **Responsive Design:** The user interface is designed to be fully responsive, providing an optimal viewing experience on any device, whether it's a desktop, tablet, or smartphone.
- **API Integration:** Utilizes TMDb API to retrieve detailed information about movies and News API to fetch and display news articles and updates.
- **WebSocket Implementation:** Uses WebSockets to enable real-time search suggestions, providing users with instant feedback as they type their search queries.

## Project Structure

The project consists of the following key files and directories:
- **index.html:** Contains the HTML structure of the web application.
- **styles.css:** Includes the CSS styles for the web application.
- **script.js:** Contains the client-side JavaScript code.
- **server.js:** Contains the server-side code using Express.js and WebSocket.
- **README.md:** Provides information about the project.

## Getting Started

### Prerequisites

Make sure you have Node.js and npm installed on your machine.

### Running the Application

#### Online Setup

1. **Visit the live site:**
   Go to this link --> [Movie/TV Show Explorer](https://raijuro.github.io/-WEBDEV-FINALS/)

2. **Source Code:**
   You can view the source code at [GitHub Repository](https://github.com/raijuro/-WEBDEV-FINALS/)

**Note:**
- The API for the articles (News API) CORS is not available for online deployment as it requires a credit card to utilize.
- The WebSocket feature needs a hosting application such as Heroku, Vercel, or Netlify, which also requires a credit card for the free trial.

#### Local Setup

1. **Download and extract the ZIP file from the repository:**
   - [Download Link](https://github.com/raijuro/-WEBDEV-FINALS/)

2. **Open the folder in VS Code:**
   - Navigate to the folder `-WEBDEV-FINALS-MAIN`.

3. **Run a new terminal and execute:**
    ```sh
    cd ..
    python -m http.server 8000
    ```

4. **Run another new terminal, navigate to the `server` folder and execute:**
    ```sh
    node server.js
    ```

5. **Open your browser and paste the following link:**

http://localhost:8000/-WEBDEV-FINALS-main/

6. **Test the application:**
- Both APIs will work together with the WebSocket.
- Try searching for a movie/TV series, e.g., "Kung Fu Panda".

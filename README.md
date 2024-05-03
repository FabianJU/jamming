# Jamming

Jamming is a React App enabling users to search the Spotify catalog for songs, curate personalized playlists, and save them to their account.

The app uses the Spotify Web API for authentication and data retrieval. The Spotify object contains methods to interact with the Spotify API.

It follows RESTful principles for data operations:

- **Create:** Adding tracks to a playlist involves sending a POST request.
- **Read:** Searching for tracks involves sending a GET request.
- **Update:** While updating playlist title isn't directly supported, users can create a new playlist with the desired title and add tracks to it.
- **Delete:** Removing a track from a playlist involves sending a DELETE request.

## Technologies 
Jamming utilizes React.js for the front-end, allowing users to search the Spotify catalog, create playlists, and save them to their account. The app interacts with the Spotify Web API to fetch data. HTML and CSS are used for styling the user interface.

## Features

1. **Spotify Login:** The first time a user searches for a song, album, or artist, Spotify will ask them to log in or set up a new account.

2. **Search by Song, Album, or Artist:** Users can type the name of a song, artist, or album into the search bar and click the SEARCH button.

3. **Populate Results List:** Jammming displays the list of returned tracks from the user’s query.

4. **Add Song to Custom Playlist:** Users can add a track to their playlist by selecting a + sign on the right side of the track’s display container.

5. **Remove Song from Custom Playlist:** Users can remove a track from their playlist by selecting a - sign on the right side of the track’s display container.

6. **Change Playlist Title:** Users can change the title of their custom playlist.

7. **Save Playlist to Account:** Users can save their custom playlist by clicking a button called SAVE TO SPOTIFY.

## Documentation of Spotify API
[Spotify API Documentation](https://developer.spotify.com/documentation/web-api)

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## What I Learned

Through this project, I gained valuable experience in:

- Making GET and POST requests using the Fetch API in JavaScript.
- Implementing user authentication by directing users to a login page and redirecting them back to the website.
- Understanding and utilizing API documentation effectively.

## Local setup

To set up the project locally from the "jamming" directory, execute the following CLI commands:
### `npm install`
This command installs all Node dependencies for React and other third-party packages used in the project.
### `npm start`
Launches the app in development mode using node server.js. Access it at http://localhost:3000 in your browser. The page automatically reloads on source code edits, and linting errors are displayed in the console.


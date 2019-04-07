# liri-node-app

The LIRI node app is similar to iPhone's SIRI. However, while SIRI is a Speech Interpretation 
and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. 
LIRI will be a command line node app that takes in parameters and gives you back data.

This project is useful because it allows the developer to run JavaScript in the terminal
showing its versatility as a front and back end language. Additionally it allows the user to 
make api calls and receive responses in the terminal. Responses are also loged in the log.txt 
file.

To get started with this application, the user will need to install the following npms:
- dotenv
- fs
- request
- node-spotify-api (The user will also need to obtain their own api key and store it in a 
  .env file)

To get help with this project the user can refer to the documentation in npm and/or the 
spotify api site for developers.

Below are examples of the various functions used in the application.

<h3>spotify-this-song</h3>

![spotify-this-song](/images/spotify-this-song.png)

The spotify-this-song function provides the following information about the selected song:
- Artist(s)
- The song's name
- A preview link of the song from Spotify
- The album that the song is from

<h3>concert-this</h3>

![concert-this](/images/concert-this.png)

The concert-this function provides the following information about the selected band/artist:
- Name of the venue
- Venue location
- Date of the Event (use moment to format this as "MM/DD/YYYY")

<h3>movie-this</h3>

![movie-this](/images/movie-this.png)

The movie-this function provides the following information about the selected movie:
- Title of the movie.
- Year the movie came out.
- IMDB Rating of the movie.
- Rotten Tomatoes Rating of the movie.
- Country where the movie was produced.
- Language of the movie.
- Plot of the movie.
- Actors in the movie.

<h3>do-what-it-says</h3>

![do-what-it-says](/images/do-what-it-says.png)

The do-what-it-says function retrieves the command from another file then runs and returns the 
requested information in the terminal. 

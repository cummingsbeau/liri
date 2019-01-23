# Liri
Video Tutorial: https://drive.google.com/file/d/15gWWmmPtMlrDzQnzltuuAT_65RN6wmFc/view?usp=sharing
# Spotify
`node liri.js spotify-this-song <insert song title>`
This will show the following information:

- Artist(s)
- The song's name
- A preview link of the song from Spotify
- The album that the song is from

If no song is provided then your program will default to "Never going to give you up" by Rick Astley

# Movies
`node liri.js movie-this <insert movie title>`

This will output the following information:

- Title of the movie.
- Year the movie came out.
- IMDB Rating of the movie.
- Country where the movie was produced.
- Language of the movie.
- Plot of the movie.
- Actors in the movie.
- Rotten Tomatoes Rating.
- Rotten Tomatoes URL.

If the user doesn't type a movie in, the program will output data for the movie 'The Bee Movie'

# Bands In Town
`node liri.js concert-this`

This will output the following information:
-Date of the most recent concert.
-Venue name.
-Local time of concert.
-Location of concert.

# Do What It Says
`node liri.js do-what-it-says`

Using the `fs` Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.





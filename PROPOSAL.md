## Your group members

Edward, Jon, Vlad

## Your project idea

A movies and shows watchlist for keeping track of currently watching shows and movies as well as ranking previously watched shows and movies. The user can search from a database of shows and create their own reviews/ratings of shows once they're finished.

## List of models and their properties

### MOVIE

\_id: MOVIE_ID,
MovieTitle: String,
Genre: String[],
VideoLink: URL,
PosterLink: URL,
AverageRating: Number,
Logs: LOG_ID[]

### USER

\_id: USER_ID,
Movies: MOVIE_ID[]
Logs: LOG_ID[]

### LOG

\_id: LOG_ID
Movie: MOVIE_ID
Comments: String,
Rating: Number,
CurrentEpisode: Number

### Scrum manager/project manager's name

### User stories

### Wireframes

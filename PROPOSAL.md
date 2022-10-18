## Your group members

Edward, Jon, Vlad

## Your project idea

A movies for keeping track of currently watching shows and movies as well as ranking previously watched shows and movies. Through an external, third-party API, the user can search a database of movies and create their own reviews/ratings of shows once they're finished, which will then be stored and tracked through our database.

## List of models and their properties

### REEL (MVP)

- \_id: REEL_ID
- Movie: MOVIE_ID
- Review: String,
- Rating: Number,

### MOVIE (STRETCH)

- \_id: MOVIE_ID,
- MovieTitle: String,
- Genre: String[],
- VideoLink: URL,
- PosterLink: URL,
- AverageRating: Number,
- Logs: LOG_ID[]

### USER (STRETCH)

- \_id: USER_ID,
- Movies: MOVIE_ID[]
- Logs: LOG_ID[]

### Scrum manager/project manager's name
TOM THE AIDE

### User stories
MVP:
- aauiwlt: Create, read, update, and delete "reels" for specific movies.
- aauiwlt: See all the reels for specific movies.
- aauiwlt: See all the movies for which I can create reels.

### Wireframes
[The MIRO board.](https://miro.com/app/board/uXjVPNFJ2Pc=/) 

### Your group members
Vlad, Edward, Jon

### Your project idea 
>Brief 2-3 sentence description of your app
An app for keeping track of, ranking, and reviewing previously watched movies. Through an external, third-party API, the user can search a database of movies and create their own reviews/ratings of movies once they're finished, which will then be stored and tracked through our database.

### List of models and their properties

### Review (MVP)
- \_id: Review_ID
- Movie: Movie_ID
- Title: String,
- Body: String
- Rating: Number,
- Author: USER_ID
- Timestamp: True

### USER (STRETCH)
- \_id: User_ID,
- Movies: [
    movie: {
        id: Movie_ID,
        finished: Boolean
    } 
]
- Reviews: [Review_ID]

### Scrum manager/project manager's name
- Edward

### User stories
MVP:
- aauiwlt: Compile a library of movies I've seen and/or movies I would like to watch in the future.
- aauiwlt: Create, read, update, and delete reviews for specific movies.
- aauiwlt: See all the reviews for specific movies.

Stretch:
- aauiwlt: See all reviews written by specific users. 
- aauiwlt: See the library of movies I've built.

### Wireframes
[The MIRO board.](https://miro.com/app/board/uXjVPNFJ2Pc=/) 

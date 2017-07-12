# NodeJS public-movies-api
A very simple REST API with several endpoints that provides movie details for over 3000 movies. Built with NodeJS, as a resource for testing applications.

## Endpoints

#### GET /movies/list/
  Returns all 3365 movies from the database  
  ``` https://nodejs-movies.herokuapp.com/api/movies/list ```
  
#### GET /movies/title/{MOVIE_TITLE}
  Returns a list of movies containing the {MOVIE_TITLE} specified.  
  ``` https://nodejs-movies.herokuapp.com/api/movies/title/star wars ```

#### GET /movies/genre/{GENRE}
  Returns a list of {GENRE} movies.  
  ``` https://nodejs-movies.herokuapp.com/api/movies/genre/comedy ```

#### GET /movies/year/{RELEASE_YEAR}
  Returns a list of movies released in {RELEASE_YEAR}.  
  ``` https://nodejs-movies.herokuapp.com/api/movies/year/1985 ```

#### GET /movies/actor/{ACTOR_NAME}
  Returns a list of movies starring {ACTOR_NAME}.  
  ``` https://nodejs-movies.herokuapp.com/api/movies/actor/tom cruise ```

#### GET /movies/director/{DIRECTOR_NAME}
  Returns a list of movies directed by {DIRECTOR_NAME}.  
  ``` https://nodejs-movies.herokuapp.com/api/movies/director/james cameron ```

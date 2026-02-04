# Watchlist App

Build a small multi-page React app where users track movies they want to
watch in a WatchList. The focus is on using **React Context** to manage shared state.

Each movie should include:

-   `id`
-   `title`
-   `genre`
-   `year`
-   `watched` (boolean)

You should also make use of **react-router** to add multiple pages.  There should be some type of **navbar** so users can move between all pages.

The WatchList should be kept track of in Context.  The user should be able to add Movies, remove Movies, and toggle their watched status.

## Home Page
-   Display a welcome message to the user.
-   Show total movies, total watched, and total remaining.
-   If there are no movies, display a message prompting the user to add a movie.

## Watchlist Page

-   Display all movies with their details and watched status.
-   If there are no movies, display a message like "List is empty"
-   Toggle watched/unwatched and remove movies.

## Add Movie Page

-   Form with inputs for title, genre, and year.
-   Submitting the form should add a new movie (with a unique id and
    `watched: false`).


## Stretch Goals:
-   Add the ability to filter movies by title and genre inside the Watchlist

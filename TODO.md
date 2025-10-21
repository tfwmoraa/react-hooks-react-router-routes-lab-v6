# TODO List for Movie App React Router Implementation

- [x] Update `routes.jsx`: Define routes array with path, element for each page, and errorElement.
- [x] Update `main.jsx`: Import routes, create router, render RouterProvider.
- [x] Update `NavBar.jsx`: Add three NavLinks in order: Home (/), Directors (/directors), Actors (/actors).
- [x] Update `MovieCard.jsx`: Add Link component wrapping the title, with to={`/movie/${id}`}.
- [x] Update `Home.jsx`: Add NavBar in header, fetch movies on mount, render MovieCard list in main.
- [x] Update `Movie.jsx`: Add NavBar in header, use useParams for id, fetch movie, display details in main.
- [x] Update `Directors.jsx`: Add NavBar in header, fetch directors, render articles in main.
- [x] Update `Actors.jsx`: Add NavBar in header, fetch actors, render articles in main.
- [x] Create `ErrorPage.jsx`: Render NavBar and "Oops! Looks like something went wrong." in h1.
- [x] Fix fetch URLs in Movie.jsx: Change port from 3001 to 4000.
- [x] Fix fetch URLs in Directors.jsx: Change port from 3001 to 4000.
- [x] Fix fetch URLs in Actors.jsx: Change port from 3001 to 4000.
- [x] Test the app navigation and data fetching.

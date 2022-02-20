# Movies API Documentation (Fleet Studio)

## Introduction

Movies API is a RESTful API that allows you to access the list of movies.
You can also search for a movie by its title and get its details using it's specific ID.

## Tools and Technologies Used

1. Node.js
2. Express.js
3. MongoDB
4. jsonwebtoken for authentication
5. bcrypt for password hashing
6. body-parser for parsing the request body
7. cors for cross-origin resource sharing
8. morgan for logging

## How to run this application locally?

1. `git clone https://github.com/daspacebar/movie-api-fleet.git`
2. `cd movie-api-fleet`
3. `npm install`
4. `nodemon server.js`

## What this application does?

1. It allows you to access the list of movies.
2. Search for a movie by its title and get its details using it's specific ID.
3. You can also add a new movie to the list.
4. You can also update a movie's details.
5. You can also delete a movie from the list.
6. You can also get the list of movies in a specific language.
7. Users can register and login to the application.

## What are the features I wasn't able to build.

1. The application doesn't allow you to add a new movie to the list with regard to the authentication.
2. Setting favourites, upvote/downvote, and review features are implemented but I'm still yet to learn and understand how to isconnect them and get it all working. You can find the implementation in the root directory's `server` folder.
3. Sorting and Filtering Features based on upvotes/downvotes and release date is not available.

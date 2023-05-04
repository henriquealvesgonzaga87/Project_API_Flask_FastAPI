# Project API Flask FastAPI

This repository contains the code for a REST API built with Flask and FastAPI. The API provides endpoints for interacting with a database of users and their favorite movies.

## Installation

To install the necessary dependencies for this project, run the following command:

```
pip install -r requirements.txt
```

## Usage

To start the API server, run the following command:

```
python main.py
```

This will start the server running on http://localhost:8000.

## API Endpoints

The following API endpoints are available:

### GET /users

Returns a list of all users in the database.

### GET /users/{user_id}

Returns the user with the given ID.

### POST /users

Adds a new user to the database. The request body should contain JSON data representing the new user.

### PUT /users/{user_id}

Updates the user with the given ID. The request body should contain JSON data representing the updated user.

### DELETE /users/{user_id}

Deletes the user with the given ID.

### GET /users/{user_id}/movies

Returns a list of all movies that the user with the given ID has marked as their favorite.

### GET /movies

Returns a list of all movies in the database.

### GET /movies/{movie_id}

Returns the movie with the given ID.

### POST /movies

Adds a new movie to the database. The request body should contain JSON data representing the new movie.

### PUT /movies/{movie_id}

Updates the movie with the given ID. The request body should contain JSON data representing the updated movie.

### DELETE /movies/{movie_id}

Deletes the movie with the given ID.

## Contributing

If you would like to contribute to this project, please open a pull request with your proposed changes.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

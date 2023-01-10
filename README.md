# DockerExercise-aleloup

### About the project ###

This docker exercise is divided in 3 parts :

- web : Web server using GO
- words : Java REST API interrogating the DB
- db : PostgreSQL Database containing the word to display

The two steps to get this exercise done were :

- Create Dockerfiles for all three containers
- Write the Compose file

### Run the app ###

You will need :

- Docker
- docker-compose

Run the following command in your terminal :

`docker-compose up --build`

The project is now running on port 80

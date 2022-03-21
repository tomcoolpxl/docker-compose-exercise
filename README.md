# Docker Compose exercise

This is a Docker compose exercise made for the PXL Docker Compose course.

## Project structure

### Database

A MySQL database consisting of one table with some movies (see database/database.sql).
The database password is movie123.

### Webapp

The webapp retrieves the movies from the database and shows them in a HTML page. This webapp is built using Flask (a Python Microframework) and accessible on port 80.
The app looks for a mysql server with the hostname 'database'. The password is hardcoded in the application (bad practice!).

## Exercise - creating a compose.yaml

Create a compose.yaml file to run the webapp and the database and run the containers. Make sure you can access the web appluication on port 8880 on your local host.

Open your browser and go to http://localhost:8880. You will now see the movies from the database displayed by the webapp.

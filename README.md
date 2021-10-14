Docker challenge - Question 5

# Dockerized WordPress

## How to run

- run `docker-compose up -d` in the root of this folder

- visit `http://localhost/` in your browser

## How to shutdown and cleanup
- shutdown: `docker-compose down`: stops containers but preserves your work
- cleanup: `docker-compose down --volumes`: to remove everything - USE WITH CAUTION



# Developer notes
- Added Environment Variables
- Based on instructions from: https://docs.docker.com/samples/wordpress/
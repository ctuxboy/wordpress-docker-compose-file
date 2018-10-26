# Wordpress Docker YAML file
My personal docker compose yaml file for developing Wordpress websites on My Qnap NAS in Container Station
Included:
- MySQL:5.7
- Wordpress:latest
- Adminer

Adminer is a great alternative for PhpMyAdmin

By default is the WorPress max upload file 2MB in the docker image.
You can change this (ex. 64MB) adding a local file with php environment variables (php.ini) and mountpoint to the Docker image (php.ini)

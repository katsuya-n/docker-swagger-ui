# docker-swagger-ui

# Insttallation
1. You need to write [api.yaml](/swagger/api.yaml).

    If you are busy, I recommend copy [swagger editor sample](https://editor.swagger.io/) and paste in api.yaml.

1. `docker-compose up -d`

    You can change port number 8001 of [docker-compose.yml](/docker-compose.yml), but don't change docker container port number 8080 this time.

1. Open `http://localhost:8001/` and check if you can see swagger-ui page.

# Documentation

- [dev.to article](https://dev.to/k_nakano9/try-using-swagger-ui-m8e)

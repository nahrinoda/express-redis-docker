# Express Redis Docker app

Requirements: [Docker Community Edition](https://www.docker.com/community-edition)

To start the app run: `docker-compose up`.

It will then be started on port 3000.

The reason I used an old school query-param based system is to avoid the boilerplate of using body-parser with POST requests.

# Endpoints

## Hello World

```sh
curl http://localhost:3000
```

## Storing Data
```sh
curl http://localhost:3000/store/my-key\?some\=value\&some-other\=other-value
```

## Fetching Data

```sh
curl http://localhost:3000/my-key
```
# express-redis-docker

<p align="center">
<a href="https://rocketseat.com.br/bootcamp" alt="Bootcamp Rocketseat">
  <img src="https://skylab.rocketseat.com.br/api/files/1560759053914.svg" height="120px"></a></p>

# Rocketseat GoStack - Desafio 03

https://rocketseat.com.br/bootcamp

## Description

API Meetapp for the Rocketseat Bootcamp GoStack.

## Features

- JWT Authentication
- Database Postgres
- Database MongoDB
- Queue with Redis for sendind emails.

## Installing

```
cd gostack-desafio3
docker-compose build
yarn
```

### Running migrations Database

```
docker-compose up
yarn sequelize db:migrate
```

### Setup .env file

Rename the file `.env-example` to `.env` !
Edit the file with your informations!

## Running

`docker-compose up`

## Author

- Lindemberg Nunes de Castro

## License

MIT

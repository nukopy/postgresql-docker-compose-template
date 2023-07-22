# postgresql-docker-compose-template

## Requirements

- Docker Compose

## Run

- Run PostgreSQL container

```sh
docker compose up -d
```

- Enter PostgreSQL container

```sh
docker compose exec db bash
```

- Connect PostgreSQL REPL

```sh
docker compose exec db psql -d sample_db -U myuser
```

- Basic commands in PostgreSQL REPL

```sh
\du                   : show users
select current_user;  : show current user
\l                    : show databases
\c                    : show current database
\d                    : show relations (tables) on specified database
```

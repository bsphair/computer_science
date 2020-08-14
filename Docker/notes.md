# Docker Notes

## Compose

To start containers, compose up like
```bash
$ docker-compose up <container>
```

## psql

### To start psql inside docker container and use a specific database:

```bash
$ docker container exec -it <container id> psql -U <user> -d <database name>
```

### Access postgres

```bash
$ psql -U <user name> -h localhost -p 5432 -d postgres
```

## Load a file into docker container

```bash
$ docker cp <file you want to transfer> <containername>:/<location>
```

## Load file from docker folder into the sql database

```bash
$ psql -U <username> -d <database name> < <file in docker container>
```

## Bash

To use bash in docker

```bash
$ docker exec -it $(docker ps -aqf "name=<database name") bash
```



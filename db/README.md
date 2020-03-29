# rust-mysql

This folder contains the setting and configuration of the database.

You can use the following commands one by one instead of running the docker-compose.

## build the mysql docker

```sh
docker build --tag rust-mysql .
```

## run the mysql docker

```sh
docker run --publish 8000:8080 --detach --name rust-mysql rust-mysql
```

## stop the mysql docker

```sh
docker stop rust-mysql
```

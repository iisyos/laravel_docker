# laravel_docker

First of all, build the docker image:

```bash
docker-compose build
```

Then, run the containers:

```bash
docker-compose up -d
```



I used under command to create a new laravel project:

```bash
docker-compose exec phpfpm composer create-project --prefer-dist laravel/laravel .
```

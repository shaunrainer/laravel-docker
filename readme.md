# Laravel Docker using Microservices
Playing around with a simple laravel app made up of microservices.

Set up
------------

Start of by cloning this repo and goto directory within terminal

Setup laravel auth
```
$ cd auth
$ composer install
$ cp .env.example .env
$ php artisan key:generate
```

Setup laravel content
```
$ cd content
$ composer install
$ cp .env.example .env
```

For this example you will be best copying the .env key across each microservice in the future we will look at just having 1 .env file :)

Start Docker
```
$ docker-composer up -d
```

# Laravel Docker using Microservices
Playing around with a simple laravel app made up of microservices.

Set up
------------

Start of by cloning this repo and goto directory within terminal

Setup laravel auth
```
$ cd auth
$ composer install
```

Setup laravel content
```
$ cd content
$ composer install
```

Start Docker
```
$ docker-composer up -d
```

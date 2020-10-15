# Symfony5 Docker Development Stater Kit

### Installing

run docker and connect to container:
```
 docker-compose up --build
```
```
 docker-compose exec php sh
```

install [Symfony](http://symfony.com/doc/current/setup.html) via composer:
```
# Web application: 
$ composer create-project symfony/website-skeleton .
```
or
```
# API:
$ composer create-project symfony/skeleton .
```

modify DATABASE_URL in .env
```
DATABASE_URL=mysql://root:root@mysql:3306/symfony?serverVersion=5.7
```

Website : localhost
 

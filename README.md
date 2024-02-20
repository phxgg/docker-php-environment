# docker-php-environment

## Description

This is a simple PHP environment with Docker. It is based on the official PHP image and comes with Apache, MySQL and PHPMyAdmin.

## How to use

1. Clone the repository
2. Run `docker-compose up`

Web server: [http://localhost:8000](http://localhost:8000)

PHPMyAdmin: [http://localhost:8081](http://localhost:8081)

MySQL: `localhost:9906`
  - host: `db`
  - database: `phpdb`
  - root user: `root`
  - root password: `toor`
  - database user: `dbuser`
  - database password: `dbpass`

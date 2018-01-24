Docker LEMP
============================

:warning: Test or developed project.

<p align="center"><img width="300px" src="https://atlogex.com/wp-content/uploads/docker-start.jpg"></p>

This is Docker LEMP server Start by [Atlogex](https://atlogex.com/docker-start/).



 Directory Structure
 -------------------

       db_data/                  - mount dir for Database files
       docker/                   - dir for focker config files
           /docker/nginx/        - configeurations files for nginx
           /docker/php-fpm/      - files for build containers php-fpm
       public_html/              - mount dir for project files

 Stack
 -------------------

- [Docker](https://www.docker.com/)
- [Docker-Compose](https://docs.docker.com/compose/install/)



 Install
 -------------------

**Require installed Docker and Docker Compose.*

1. Build containers

> docker-compose build

2. Run containers
> docker-compose up
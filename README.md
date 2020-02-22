# Docker container for NGINX/PHP
[![CircleCI](https://circleci.com/gh/mrsank399/docker-nginx-php.svg?style=shield)](https://circleci.com/gh/mrsank399/docker-nginx-php)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/4fdd5ee3d67b4eb2864d687716068502)](https://www.codacy.com/manual/mrsank/docker-nginx-php_2?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=mrsank399/docker-nginx-php&amp;utm_campaign=Badge_Grade)
The container can be used as a skelton container for the PHP projects. 

## Usage

The file has to be saved onto *example.com* folder so that it will get accessed onto the respective containers.

Once its been done, run the system with the following command:
```
docker-compose up -d
```

The container can be listed with the following command:
```
docker ps
```
The user can be able to ssh onto the container with the following command:
```
docker exec -it #container_id# bash
```

## Author(s)
- Harisankar Ramachandran <hello@harisankar.in>

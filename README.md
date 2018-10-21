# Docker container for NGINX/PHP

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

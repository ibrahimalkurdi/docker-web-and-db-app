# docker-web-and-db-app

This is a basic Docker Compose setup for a web service that contains the following:
**Nginx, PHP, MySQL, PHPAdmin and Wordpress**

## kickoff
```
docker compose up --force-recreate -d
```

## Teirdown
Important: this will delete the containers with their volumes
```
docker compose down --volumes
```

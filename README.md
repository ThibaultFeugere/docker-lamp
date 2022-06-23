# Docker LAMP

Are you tired of having dozens of php versions?

This little Dockerfile and docker-compose should please you

## How it works

You just need to clone this two files :

- Dockerfile
- docker-compose.yml

## Configuration

If you want to change PHP version, you can change this line :

```dockerfile
FROM php:7.3-apache
```

## Docker-compose

Docker-compose is the orchestrator of three services :

- web (with PHP)
- db (database with mysql:8.0)
- PhpMyAdmin 

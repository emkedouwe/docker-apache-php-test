# docker-apache-php-test

## Commands

Start container 
```
docker-compose up -d
```

Stop container 
```
docker-compose down
```

List the active containers
```
docker ps
```

Lists the volumes, which are commonly used for persisting data of Docker containers.
```
docker volume ls
```

Stops one or more containers. 
```
docker stop mycontainer
```

Stop all containers
```
docker stop $(docker ps -a -q)
```

## Links

- [A beginner’s guide to Docker — how to create your first Docker application](https://medium.com/free-code-camp/a-beginners-guide-to-docker-how-to-create-your-first-docker-application-cc03de9b639f)
- [Creating a Docker LAMP (Linux, Apache, PHP & MySQL) Stack](https://quileswest.medium.com/creating-a-docker-lamp-linux-apache-php-mysql-stack-111ad3fb9d56)
- [Setting up a WordPress development environment in Docker](https://developer.yoast.com/blog/set-up-wordpress-development-environment-in-docker/)
- [Build a solid WordPress dev environment with Docker](https://aschmelyun.com/blog/build-a-solid-wordpress-dev-environment-with-docker/)

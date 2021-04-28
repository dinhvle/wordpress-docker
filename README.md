# wordpress-docker
Using Docker to create a WordPress working environment.

## Requirements
You just need Docker/Compose installed

## Getting Started
Build the WordPress project with

```
docker-compose up -d
```

When the containers are built, you can access Wordpress site at

```
localhost:8000
```

## Shutdown and Destroy

You can start and stop containers with

```
docker-compose start
docker-compose stop
```

If you want to remove the containers

```
docker-compose down
```

```
docker-compose down --volumes
``` 
use this to removes the volumes as well.

## Helpful
If you use VSCode and have [Remote-Container](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension, you can connect to the container environment. For example, you can connect to Wordpress container at `/var/www/html/wp-content` to edit plugins or themes. 

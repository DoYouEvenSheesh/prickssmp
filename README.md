# PricksSMP
Docker Compose File of the PricksSMP server.

Requires: Docker, Docker-Compose and maybe git.

How to use:

```
    
    Create a new directory
    Put the contents of the file below in a file called docker-compose.yml
    Run docker compose up -d in that directory
    Done! Point your client at your host's name/IP address and port 25565.

```


To stop,

```
    docker compose stop
```

To access the server console,

```
    docker attach paper
```
and then Control-p Control-q to detach



For more documentation checkout [itzg's docker-minecraft docs](https://docker-minecraft-server.readthedocs.io/en/latest/)


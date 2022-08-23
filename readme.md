> docker-compose up
> docker-compose up --build

```
docker-compose down
```

# Restart policies

- "no" : Never attempt to restart this . container if it stops or crashes
- always : If this container stops for any reason always attempt to restart it
- on-failure: Only restart if the container stops with an error code
- unless-stopped: Always restart unless we (the developers) forcly stop it

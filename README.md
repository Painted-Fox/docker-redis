# docker-redis

A Dockerfile that produces a container that will run [Redis][redis].

[redis]: http://redis.io/

## Image Creation

```
$ sudo docker build -t="redis" .
```

## Container Creation / Running

```
$ sudo docker run -p 6379 redis
```

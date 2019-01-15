# Redis setup by docker

[repository](https://hub.docker.com/_/redis)

```bash
docker pull redis
docker run --name redis -p 6379:6379 -d redis
```
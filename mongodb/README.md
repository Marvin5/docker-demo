# Mongo setup by docker

[Repository](https://hub.docker.com/_/mongo)

```bash
docker pull mongo
docker run --name mongo -d mongo
docker volume create mongodata
docker run -p 27017:27017 -v mongodata:/data/db --name mongo mongo
```
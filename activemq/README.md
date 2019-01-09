# ActiveMQ Setup By Docker

[repository](https://hub.docker.com/r/rmohr/activemq/)

```bash
docker pull rmohr/activemq
docker run -p 61616:61616 -p 8161:8161 -v d:/docker/activemq/conf:/opt/activemq/conf -v d:/docker/activemq/data:/opt/activemq/data --name activemq rmohr/activemq#
# or 
docker run -p 61616:61616 -p 8161:8161 --name activemq rmohr/activemq
```
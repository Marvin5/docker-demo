# ELK setup by docker

## Elasticsearch

```bash
docker pull elasticsearch
docker run -p 9200:9200 -p 9300:9300 --network my-bridge --ip 172.19.0.10 -e "discovery.type=single-node" --name elasticsearch elasticsearch
```

## Kibana

```bash
docker pull kibana
docker run -p 5601:5601 --network my-bridge --ip 172.19.0.11 -v D:\docker\kibana\ --name kibana kibana
```

##
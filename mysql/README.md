# MySQL setup by docker

[repository](https://hub.docker.com/_/mysql)

```bash
docker pull mysql
docker run -p 3306:3306 -v d:/docker/mysql:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=123456 -d --name mysql mysql
```

再进行一些用户的配置
```bash
docker container exec -it mysql bash


```
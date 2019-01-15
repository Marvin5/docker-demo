# Jenkins setup by docker

[Repository](https://hub.docker.com/_/jenkins)

```bash
docker run --name jenkins -p 9090:8080 -p 50000:50000 -v E:\docker\jenkins\:/var/jenkins_home jenkins
```
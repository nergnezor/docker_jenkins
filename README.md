# docker_jenkins
```bash
docker run -u root --rm -d -p 8080:8080 -p 50000:50000 -v c:\src\jenkins:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock --name jenkins nergnezor/jenkins
```

Current build server config:
```bash
docker run -u root --restart always -d -p 8080:8080 -v /var/run/docker.sock:/var/run/docker.sock --name jenkins nergnezor/jenkins
```

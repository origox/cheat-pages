# DOCKER

## Overview

![Image](https://docs.docker.com/engine/article-img/architecture.svg)

## Commands

Start example jenkins image
```
docker run -d -p 49001:8080 -v $HOME/jenkins_home:/var/jenkins_home --name jenkins jenkins/jenkins:2.73.2
```
Remove image
```
docker rmi IMAGE ID
```

Remove all stopped containers 
```
docker rm $(docker ps --no-trunc -aq)
```
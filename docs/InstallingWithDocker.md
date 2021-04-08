# Installing with Docker
This document gives a brief overview of running a local instance of Jenkins inside of a Docker image.

## Prerequesites
- macOS
- [Docker](https://docs.docker.com/docker-for-mac/install/)


## Pull the Jenkins Docker Image

Weekly Release
```
docker pull jenkins/jenkins
```

LTS
```
docker pull jenkins/jenkins:lts
```

## Run the Jenkins Docker Image

```
docker run -p 8080:8080 -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts
```


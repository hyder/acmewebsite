# docker-helloworld

A simple helloworld app for docker

A simple nginx helloworld application that helps you learn docker image pulls. Runs on port :80

To pull this image:
```
docker pull lmukadam/acmewebsite:latest
```

To run this image:
```
docker run -p 80:80/tcp "lmukadam/acmewebsite:latest"
```

Dockerhub link: https://hub.docker.com/r/lmukadam/acmewebsite

Github link: https://github.com/hyder/acmewebsite

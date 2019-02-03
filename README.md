# Docker Jenkins

A docker container with Jenkins inside it.

Latest version of Jenkins is installed in the latest Ubuntu OS.

To use, just build the docker image

To build the image:
```
docker build --tag [your repo]/[image name] .
```

To run the container:
```
docker run -p 8080:8080 -d [your repo]/[image name]
```



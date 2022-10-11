# Assignment1
```bash
docker build -t <image_name> . # build a image from dockerfile in the current directory and tag the image
docker images ls # list all images stored locally
docker push <username>/<image_name> # push the image to registry
docker push <image_name>:<version> # pull an image with a version from registry
docker run -p 80:80 <imagename> # run imagename on host 80 and container 80 ports
docker run -d -p 80:80 <imagename> # run imagename on host 80 and container 80 ports, detached mode
docker ps # list all running containers
docker ps -a # list all the containers incl ones not running
docker rmi <imagename> # remove the image from local machine
docker login # login with docker creds
docker kill <hash> # force shutdown a container
docker rm <hash> # remove a container from local machine
docker images # shows all the images in the local machine
docker volume create <vol> # create a volume
docker volume inspect <vol> # troubleshooting
```

# Assignment2

```bash
docker pull hello-world:latest
docker run hello-world
```

# Assignment3-4

### FastAPI Hello world app

```bash
docker build -t jayjay87/helloworldapp1 .
docker run -d -p 80:80 helloworldapp1
docker push jayjay87/helloworldapp1
```

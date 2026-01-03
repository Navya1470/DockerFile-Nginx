# DockerFile-Nginx
Mall website using docker+nginx

Take an AWS EC2-Instance and install docker in it
take Mall app code from browser and add it in index.html file
open Dockerfile and write dockerfile where we need to use nginx as base image and expose it with port 80 and save it.
build docker image using the created dockerfile 
command:::** docker build -t myfirstapp .**
check the created images with 
docker images
after creating the image, run that image to create a container using below command
command:::** docker run -d --name cont-1 -p 1111:80 myfirstapp**
check the container is created and running with the below command
commmand::: **docker ps or docker ps -a**



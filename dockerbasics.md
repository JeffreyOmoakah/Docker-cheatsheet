//Check Docker version. 
docker --version or docker -v

//Display system-wide information about Docker.
docker info
 
//Download an image from Docker Hub. 
docker pull <image_name>

//List local Docker images. 
docker images or docker image ls

//List running containers. 
docker ps or docker container ls

//List all containers (including stopped ones)
docker ps -a or docker container 1s -a

//Create and start a new container from an image. 
docker run <options> <image_name>
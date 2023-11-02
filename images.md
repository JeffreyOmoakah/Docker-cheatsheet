                                        Images
//Build a Docker image from a Dockerfile 
docker build -t <image_name> <path_to_Dockerfile>

//Remove an image 
docker rmi <image_name>

Remove all unused images.
docker image prune
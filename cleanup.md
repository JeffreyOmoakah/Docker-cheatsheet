                                            Cleanup
//Remove all stopped containers,unused networks, and images.
docker system prune

//Remove all stopped containers
docker container prune

// Remove all unused images
docker image prune

//Remove all unused volumes 
docker volume prune
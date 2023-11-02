                                            Volumes
//Create a named volume
docker volume create <volume_name>

//Mount a volume to a container.
docker run -v <volume_name>:<container_path>

//List volumes
docker volume 1s

//Remove a volume 
docker volume rm <volume_name>
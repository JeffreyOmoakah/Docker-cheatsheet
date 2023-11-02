                            Logs and Debugging
//View container logs.
docker logs <container_name/id>

//Start an interactive shell in a running container. 
docker exec -it <container_name/id> /bin/bash

// Display real-time container resource usage. 
docker stats <container_name/id>
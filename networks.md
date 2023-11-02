                                            Networks
//Create a user-defined network. 
docker network create <network_name>

//List networks. 
docker network ls

//Connect a container to a network.
docker network connect <network_name> <container_name/id>

//Disconnect a container from a network.
docker network disconnect <network_name> <container_name/id>


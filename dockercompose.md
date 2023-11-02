                                Docker Compose
//Start services defined in a Docker Compose file 
docker-compose up

//Stop and remove services defined in a Docker Compose file.
docker-compose down

//List services in a Compose file and their status. 
docker-compose ps

//View logs for a specific service. 
docker-compose logs ‹service_name>

//Run a command in a running service container.
docker-compose exec <service_name> <command>
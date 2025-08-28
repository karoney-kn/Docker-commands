# Docker-commands

# Image Management:

  [1] docker pull <image_name>[:<tag>]: Downloads an image from a Docker registry (e.g., Docker Hub).
  [2] docker build -t <image_name>:<tag> .: Builds a new Docker image from a Dockerfile in the current directory.
  [3] docker images: Lists all Docker images on the local system.
  [4] docker rmi <image_id_or_name>: Removes one or more Docker images.
  [5] docker push <image_name>[:<tag>]: Uploads a Docker image to a registry.
  
# Container Management:

  [1] docker run [OPTIONS] <image_name> [COMMAND] [ARG...]:  Creates and starts a new container from an image.
  [2] docker ps: Lists all running containers.
  [3] docker ps -a: Lists all containers, including stopped ones.
  [4] docker start <container_id_or_name>: Starts a stopped container.
  [5] docker stop <container_id_or_name>: Stops a running container.
  [6] docker restart <container_id_or_name>: Restarts a container.
  [7] docker rm <container_id_or_name>: Removes one or more stopped containers.
  [8] docker exec -it <container_id_or_name> <command>: Executes a command inside a running container.
  [9] docker logs <container_id_or_name>: Fetches the logs of a container.

# Other Useful Commands:

  [1] docker info: Displays system-wide information about Docker.
  [2] docker version: Shows the Docker version information.
  [3] docker network ls: Lists all Docker networks.
  [4] docker volume ls: Lists all Docker volumes.

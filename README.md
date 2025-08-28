# Docker-commands

# Image Management:
<ul>
  <li> docker pull hello-world: Downloads an image from a Docker registry (e.g., Docker Hub).</li>
  <li> docker build -t  .: Builds a new Docker image from a Dockerfile in the current directory.</li>
  <li> docker images: Lists all Docker images on the local system.</li>
  <li> docker rmi <image_id_or_name>: Removes one or more Docker images.</li>
  <li> docker push <image_name>[:<tag>]: Uploads a Docker image to a registry.</li>
</ul>
    
# Container Management:

  <li> docker run [OPTIONS] <image_name> [COMMAND] [ARG...]:  Creates and starts a new container from an image.</li>
  <li> docker ps: Lists all running containers.</li>
  <li> docker ps -a: Lists all containers, including stopped ones.</li>
  <li> docker start <container_id_or_name>: Starts a stopped container.</li>
  <li> docker stop <container_id_or_name>: Stops a running container.</li>
  <li> docker restart <container_id_or_name>: Restarts a container.</li>
  <li> docker rm <container_id_or_name>: Removes one or more stopped containers.</li>
  <li> docker exec -it <container_id_or_name> <command>: Executes a command inside a running container.</li>
  <li>  docker logs <container_id_or_name>: Fetches the logs of a container.</li>
    
# Docker Nginx 
  <li> docker run -p 80:80 nginx : >> you can assign any port you like your nginx to run on</li>
 <li> docker run -p 4000:80 -d nginx : >> run in background ( -d stands for detach)</li> 
 <li> docker run -p 8000:80 -d --name dtest nginx : This is for running docker in background with a specified session name</li> 


# Other Useful Commands:

  <li> docker info: Displays system-wide information about Docker.</li>
  <li> docker version: Shows the Docker version information.</li>
  <li> docker network ls: Lists all Docker networks.</li>
  <li> docker volume ls: Lists all Docker volumes.</li>

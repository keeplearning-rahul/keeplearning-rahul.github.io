| Command | Description | Example |
| --- | --- | --- |
| `docker run <image>` | Creates and runs a new container from an image | `docker run nginx` |
| `docker run --name <name> <image>` | Assigns a name to the container | `docker run --name my_nginx nginx` |
| `docker run -d <image>` | Runs the container in detached mode (in the background) | `docker run -d nginx` |
| `docker run -it <image> <command>` | Runs the container with an interactive terminal | `docker run -it ubuntu bash` |
| `docker run -p <host_port>:<container_port> <image>` | Maps a container's port to the host machine's port | `docker run -p 8080:80 nginx` |
| `docker run -v <host_path>:<container_path> <image>` | Mounts a volume from the host machine to the container | `docker run -v /data:/app/data nginx` |
| `docker run <image>:<tag>` | Runs an image with a specific tag | `docker run nginx:latest` |
| `docker start <container_id/name>` | Starts a stopped container | `docker start container_id` |
| `docker stop <container_id/name>` | Stops a running container | `docker stop container_id` |
| `docker rm <container_id/name>` | Removes a stopped container | `docker rm container_id` |
| `docker rmi <image>` | Removes an image | `docker rmi nginx` |
| `docker pull <image>` | Pulls an image from a registry | `docker pull nginx` |
| `docker push <registry>/<image>` | Pushes an image to a registry | `docker push myregistry.com/nginx` |
| `docker build -t <image_name> <path>` | Builds an image from a Dockerfile | `docker build -t myapp .` |
| `docker logs <container_id/name>` | Retrieves logs from a container | `docker logs container_id` |
| `docker exec -it <container_id/name> <command>` | Runs a command in a running container | `docker exec -it container_id bash` |
| `docker ps` | Lists running containers | `docker ps` |
| `docker ps -a` | Lists all containers (running and stopped) | `docker ps -a` |
| `docker images` | Lists available images | `docker images` |
| `docker network <subcommand>` | Manages Docker networks | `docker network ls` |
| `docker volume <subcommand>` | Manages Docker volumes | `docker volume ls` |
| `docker-compose <subcommand>` | Runs multi-container applications with Docker Compose | `docker-compose up` |

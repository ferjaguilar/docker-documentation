# Docker documentation

### Running containers.
| command | parameters | description |
|--|--|--|
| `docker run` | name_container | Start a container. |
| `docker run` | --name |Name the container.|
| `docker run -it` | name_container  |Start container in interactive mode.|
| `docker run -d` | --name_container |Start a container with a proccess.|
| `docker exec` | command or procces |Execute a command docker or proccess in a container.|
| `docker -p` | localport : dockerport |Publish a port in localhost.|
| `docker cp` |localcontent dockercontainer |Copy localfiles to container.|
| `docker run --rm` | | Delete container when stop. |
| `docker run --env` | | Add a enviromet variable. |

### Management containers.
| command |Parameters| Description |
| -- | -- | -- |
| `docker ps` | |Show to active containers.|
| `docker ps` | -a |Show all containers.|
| `docker inspect` | ID or name |Show all information about the container.|
| `docker rename` | name newname |Rename a container.|
| `docker rm` | ID or name |Remove a disabled container.|
| `docker container prune` ||Remove all disabled container.|
| `docker stop` | ID or name |Kill a container.|

### Volumen
| command |Parameters| Description |
| -- | -- | -- |
| `docker volume ls` | |Show all docker volumens.|
| `docker volume create` | name |Create new volume.|
| `docker --mount` |src=volume,dst=location |Associate volumen and container data.|

### Image
| command |Parameters| Description |
| -- | -- | -- |
| `docker image ls` | |Show all docker images.|
| `docker pull` |image |Download image from DockerHub.|
| `docker build -t` | image:tag |Create new image.|

### Docker Networking
| command |Parameters| Description |
| -- | -- | -- |
| `docker network ls` | |Show all docker networks.|
| `docker network create --attachable` | name |Create new docker network.|
| `docker network inspect` | name |Show all network configs.|
| `docker network connect` | network_name container_name |Connect a container with network.|



### Dockerfile
- **FROM**: Add an image.
- **RUN**: Execute a command.
- **COPY**: Copy files to localpc to docker container.
- **WORDIRK**: Add workdirk.
- **EXPOSE**: Allow expose a port.
- **CMD**: Default command

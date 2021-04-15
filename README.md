# Docker documentation

### Running containers.
| command |Parameters| Description |
| ------------- | ------------------------------ |
| `docker run` | name_container     | Start a container. |
| `docker run` | --name |Name the container.|
| `docker run -it` | name_container  |Start container in interactive mode.|
| `docker run -d` | --name_container |Start a container with a proccess.|
| `docker exec` | command or procces |Execute a command docker or proccess in a container.|

### Management containers.
| command |Parameters| Description |
| ------------- | ------------------------------ |
| `docker ps` | |Show to active containers.|
| `docker ps` | -a |Show all containers.|
| `docker inspect` | ID or name |Show all information about the container.|
| `docker rename` | name newname |Rename a container.|
| `docker rm` | ID or name |Remove a disabled container.|
| `docker container prune` ||Remove all disabled container.|
| `docker stop` | ID or name |Kill a container.|

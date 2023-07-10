# Docker Command

## Manage Docker Containers

List active Docker containers: `$ sudo docker ps`

List all Docker containers:  `$ sudo docker ps -a`

List latest Docker containers:  `$ sudo docker ps -l`

Start a Docker Container:  `$ sudo docker start [container-ID | container-name]`

Stop a Docker Container: `$ sudo docker stop [container-ID | container-name]`

Remove a Docker Container: `$ sudo docker rm [container-ID | container-name]`

## Docker Volume

Create a Docker Volume: `$ sudo docker volume create [volume_name]`

Remove a Docker Volume: `sudo docker volume rm [volume_name]`

## Docker Network 

Connects a container to a network: `docker network connect [network-name]`

Creates a new network: `docker network create [network-name]`

Disconnects a container from the specified network: `docker network disconnect [network-name]`

Outputs detailed information on the specified network or networks: `docker network inspect [network-name]`

Lists all networks in a container: `docker network ls`

Removes all unused networks in a container: `docker network prune`

To obtain more detail on a particular network: `sudo docker network inspect bridge`


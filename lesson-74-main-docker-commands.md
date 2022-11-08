## Difference between container and image

container is a running environment for image.  
port binded to container

## Version and tag

## Frequently used docker commands

- docker pull <image_name>, :version 

eg: docker pull redis:4.0

- docker images : list all images
- docker run <image_name>: start the image in a container, -d: run in detached mode
- docker ps: list all the running containers, -a: list all containers
- docker stop <container_id>
- docker start <container_id>

You can bind container ports to the ports in your local machine 

- docker run -p <local_port>:<container_port> <img_name>

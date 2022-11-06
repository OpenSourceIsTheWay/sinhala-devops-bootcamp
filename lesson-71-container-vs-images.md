container is a layers of images

base image is lINUX BASE image, it's small in size, alphine

application image on top of base image.

docker run postgres:9.6 - pulls the image and runs the container. when pulling, the base images (layers) are downloaded
when upgrading a container, only the changed base images are downloaded again.

docker ps - show all running containers

image - is the actual package, container is the running image (process)

you can also run different versions of the same image at the same time.

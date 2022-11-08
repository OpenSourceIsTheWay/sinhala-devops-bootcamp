containers were there before docker, but docker made containers popular.

docker engine= docker server + API + CLI

server: pull and manage images and containers
API: interacting with Docker Server
CLI: client to execute docker commands

docker server = container runtime + volume + network + build images

container runtime : pulling images and managing container lifecycle
volumes: persisting data
network: configuring network for container communication
build our own Docker images

only need a container runtime -> use containerd, cri-o
only need to build images -> buildah

Docker is supported natively in Linux, but require Docker Desktop in Windows & Mac.

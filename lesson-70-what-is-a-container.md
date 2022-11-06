what is container -> a package with app ,all depens and config

portalble, easily shared and moved around

dev and deployment more efficient

containers live in container repository.

companies have private repos.

Docker containers live in public docker repository, named Docker Hub. It has images for many popular software.

Before containers: different installation on each os, error-prone

After containers: don't need to install dependencies directly on the machine, it's packaged with all needed configuration, command for starting the container is
same across os, run same app with 2 different versions

how containers improve deployments: before containers, devs create artifacts + instructions and hand over to ops team, -> direct deployment on servers and deps version
conflicts, misunderstanding between devs and ops, this causes going back and forth

now: devs package app + configs in a container and hands it over to ops

other container solutions (other than Docker): containerd, cri-o




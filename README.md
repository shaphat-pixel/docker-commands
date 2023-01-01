# docker-commands
This is a repo of important commands in Docker that I think I need to understand or be aware of.

# docker pull NAME_OF_IMAGE
The pull command fetches an image from the Docker registry and saves it to our system.

# docker run name_of_container
The run command is used to run a docker container

# docker ps
The docker ps command shows you all containers that are currently running.

# docker ps -a
The -a variant shows us containers that have exited.

# docker run -it name_of_container sh
The "-it" variant allows us to write additional commands by giving us an interface. We can exit out of the interface by typing "exit"

# docker rm container_id
This command is used to delete a container in other to free up space.

# docker container prune
Deletes all containers that have been exited

# docker run --rm
This automatically deletes a container after it has exited.

# docker rmi
Deletes images that I no longer need.

# ////////////////////////////////////

# DEPLOYING WEB APPLICATIONS WITH DOCKER

# docker run -d -P --name static-site prakhar1989/static-site
"-d" variant makes the container run in detached mode, meaning we can access it outside the terminal.
"-P" variant will publish all exposed ports.
"-name" variant helps us provide a name for our container.

# docker port name_of_container
we write this container in other to view the ports that our container is runnning on.

# docker stop name_of_container
This command stops the web server from running.

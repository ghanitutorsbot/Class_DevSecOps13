
Create an account dockerhub
        Images
        Container

Basics of Docker

    Contanarization vs virtualization

Docker

    Docker is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers

Dockerhub:
        Setup account

Docker Installation:

     Ubuntu
     Windows

-----------------------------------------------------------
Installation Steps:

sudo apt-get update
sudo apt-get remove docker docker-engine docker.io
sudo apt install docker.io -y
sudo systemctl start docker 
sudo systemctl enable docker
sudo groupadd docker
sudo usermod -aG docker $USER
newgrp docker
sudo chmod 666 /var/run/docker.sock

-----------------------------------------------------------


Docker commands

Image - multiple containers 

       docker pull
        docker run
                    - d
                    - p
                    - P
                    - it or -i -t

        docker ps
                ps -a
        
        docker images


        docker start containerid/name
        docker stop containerid/name
        docker restart containerid/name
        docker kill containerid/name
        docker inspect containerid/name
        docker attach containerid/name
        or
        docker exec -it containerid/name /bin/bash
        docker rm containername/id (Container already stopped state)
        docker rename containername newcontainername
        docker port containername/id


        docker logs
        docker commit containerid/name newimagename


--------------------------------------------------------------------------------------------------------



docker cli Commands:
  attach      Attach local standard input, output, and error streams to a running container
  build       Build an image from a Dockerfile
  commit      Create a new image from a container's changes
  exec        Run a command in a running container
  
  history     Show the history of an image
  images      List images
 
  info        Display system-wide information
  inspect     Return low-level information on Docker objects
  kill        Kill one or more running containers
 
  login       Log in to a Docker registry
  logout      Log out from a Docker registry
  logs        Fetch the logs of a container

  port        List port mappings or a specific mapping for the container
  ps          List containers
  pull        Pull an image or a repository from a registry
  push        Push an image or a repository to a registry
  rename      Rename a container
  restart     Restart one or more containers
  rm          Remove one or more containers
  rmi         Remove one or more images
  run         Run a command in a new container
  
  start       Start one or more stopped containers
 
  stop        Stop one or more running containers
  tag         Create a tag TARGET_IMAGE that refers to SOURCE_IMAGE


  -----------------------------------------------------------------------------------------------------
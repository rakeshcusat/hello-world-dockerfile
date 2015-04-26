# hello-world-dockerfile
This repository contains dockerfile examples. It is mainly for the educational purposes. This could be helpful for those people who have just started learning Docker.


# Installation
1. You need to install the required docker [packages](https://docs.docker.com/installation/ubuntulinux/).
1. Copy the `Dockerfile` in the current directory
1. Run `docker build -t hello-world .` This will create the docker image which can be verified by running `docker images`. This command will list all the images present on the host. You will notice `hello-world` image in the list.
1. To run the image just execute `docker run hello-world` and walah it will print `hello-world` on the console.

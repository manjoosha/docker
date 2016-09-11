Installing Docker
================
Install in ubuntu
-----------------
	apt-get install docker.io
Install in centos
-----------------
	apt-get install docker
Docker commands
===============

.. csv-table:: Docker Commands
   :header: "command", "Description"
   :widths: 15, 40
   
	"docker inspect", "to get the ipaddress of the container"
	"docker ps -l", "displays last started container"
	"docker port", "display the port"
	"docker top", "to display the processes inside the container"
	"docker link", "it adds host entries"
	"docker logs", "executes what are the commands are running or inside a container"
	"docker rmi", "remove docker image"
	"docker build", "create your own docker image"
	"docker compose", "executing docker images in an order"

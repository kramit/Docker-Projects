# Docker-Projects

This is a store for my learning how to build containers

## powershellDockerHelloWorld 
This will just print hello world out, but it uses servercore and a powerhsell script loaded into the container to do it

## tfl_status_container

This take my previous TFL status HTML report at https://github.com/kramit/Powershell-scripts/tree/master/TFL and wraps it
up in a loop, this is then put into a severcore container and the loop runs every 10 seconds, this container I have
published to https://hub.docker.com/r/kramit/tfl you can pull it to your local Docker with the command **docker pull kramit/tfl**

One final thing, you need to run this with **windows containers**

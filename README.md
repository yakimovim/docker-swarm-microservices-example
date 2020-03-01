# Example of ASP.NET Core microservices system deployment using Docker Swarm

This repository contains example of microservices system. The system contains two parts:

* Backend service built using ASP.NET Core WebAPI.
* Frontend service built using ASP.NET Core MVC.

Both applications contain Dockerfile files for building images. The example assumes that the names of the images will be `backend` and `frontend`.

`docker-compose.yaml` contains description for Docker Compose. It will run the system there each service will have only one instance.

`docker-swarm.yaml` contains description for Docker Swarm. It allows to have several instance of each service running.

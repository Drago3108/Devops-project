Example App
=========

A simple distributed application running across multiple Docker containers.

Getting started
---------------

Download [Docker Desktop](https://www.docker.com/products/docker-desktop) for Mac or Windows. [Docker Compose](https://docs.docker.com/compose) will be automatically installed. On Linux, make sure you have the latest version of [Compose](https://docs.docker.com/compose/install/). 


## Linux Containers

> If you're using [Docker Desktop on Windows](https://store.docker.com/editions/community/docker-ce-desktop-windows), you can run the Linux version by [switching to Linux containers](https://docs.docker.com/docker-for-windows/#switch-between-windows-and-linux-containers), or run the Windows containers version.

### How to deploy
```
git clone https://github.com/dhamodaranv/Devops-project.git
cd Devops-project
docker-compose up -d
```

The app will be running at [http://localhost:8080](http://localhost:8080). Use `curl` or <b>browser</b> to see the page response.

Notes
-----

## Authors

- Author: Dhamodaran V T [dhamodaranthulasigajendiran@gmail.com](mailto:dhamodaranthulasigajendiran@gmail.com)

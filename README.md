# Docker Express Template

## Pre-requisites
Make sure you have [Docker desktop](https://www.docker.com/products/docker-desktop) installed

## Get started
run command `docker build -t <your username>/<app name> .` in the root directory. Then run `docker run -p 5000:5000 <your username>/<app name>` where the 'image-id' is from the result of the first command.
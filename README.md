# Docker — Docker-izing a NodeJS express JS API

# Building our Docker Image

docker build -t  node-docker .

# Running our Docker Image 

This will start up a Docker container based off our node-docker docker image and expose it on port 9000 on our machine.The -d flag specifies that we wish to run this in a detached mode which means that the docker container will run in the background on our host machine.

docker run -d -p 9000:3000 node-docker

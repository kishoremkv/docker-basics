## To learn about docker 

## Docker Images

## Docker Containers

## Docker Network

## Docker Volumes
- To provide data persistency
- Every time a container stops the entire data will be lost(db container as an example)
- 3 types 
- Host Volumes
- Anonymous Volumes
- Named Volumes -> Mostly used 
- ex: volumes: - db-data:/var/lib/mysql/data
### Dockerfile
- Blue print to build images
Examples: 
- FROM node
- ENV username=usernmae
- RUN mkdir -p /home/app
- COPY . /home/app -> to copy contents into container image
- CMD ["node", "server.js"] -> it is an entry point command to execute in container

### Basic commands
- docker pull <image_name> 
- docker build
- docker network
- docker ps
- docker run
- docker images
- docker --help -> to know more about the above commands

---

### Amazon Elastic Container Repository (ECR) 
- Need to push image to this repository
- We can use Docker hub as alternative



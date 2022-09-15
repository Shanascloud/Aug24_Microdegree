# To Install docker
- yum install docker -y

# to start the docker services
- systemctl start docker
- systemctl enable docker

# to Pull the images from Docker hub 
- docker pull "imagename"

# to see the docker images
- docker images

# to see the docker container running 
- docker ps

# to see all the container running and other stopped container 
- docker ps -a 

# to run the docker images
- docker run "imagename"


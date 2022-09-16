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


# To run the Httpd docker image, if we run without the portno, this will  not work  sine the HTTPD is also running on the port 80

docker run -d -p 80:80 httpd

# To run the tomcat with  docker image -d to riun in detached mode
docker run -d --name mytomcat3 -p 8081:8080 tomcat

# To run the ubuntu docker images, this will enter the ubuntu machine
docker run -it ubuntu



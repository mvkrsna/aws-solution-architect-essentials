Commands to install Docker, java and Other

Installation of Docker:
sudo yum install docker

Starting the docker:
sudo systemctl start docker.service

Check the version of docker installed:
sudo docker version

Check if docker can run the hello-world:
sudo docker run hello-world

To Install and set the nginx: ( we need to set the http port to 80 in the security configurations)
sudo docker run -p 80:80 nginx

# docker-jenkins-build-projects
This is a Jenkins Docker setup using Docker-compose.
The docker compose file will deploy a new version of Jenkins
and save $JENKINS_HOME and Jenkins data outside of the Jenkins container.  

## Login
 username: guest
 password: guest
 email: guest@guest.com

# Deploy
 Run this command in your terminal from the folder where the docker-compose file sits.

 $ docker-compose up -d

 To find the IP address of the container
 $ docker inspect jenkins  

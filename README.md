# docker-jenkins-build-projects
This project deploys Jenkins in a docker container.
There is a setup.sh script to install docker and needed packages
for Ubuntu systems.

The container saves the $JENKINS_HOME and Jenkins data outside of the Jenkins container

The setup.sh script also pulls the plugins dir from a dropbox dir to prevent large files from stay in git.

## Login
* username: guest
* password: guest
* email: guest@guest.com

# Deploy
 Run this command in your terminal from the folder where the docker-compose file sits.

 $ docker-compose up -d

 To find the IP address of the container
 $ docker inspect jenkins  

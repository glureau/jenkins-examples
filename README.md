# Setup a local Jenkins

    docker pull jenkins
    docker run -p 8080:8080 -t -i -d --name jenkins jenkins

Jenkins is now running: http://127.0.0.1:8080/

To get the initial admin password:

    docker exec -i -t jenkins /bin/bash
    $ cat /var/jenkins_home/secrets/initialAdminPassword



### Links
https://hub.docker.com/_/jenkins/

# jenkins-slave for Jenkins Docker Plugin
This is a simple image based on a latest [phusion/baseimage] (https://hub.docker.com/r/phusion/baseimage).

Additional packages installed:
* Latest Java 8 JDK
* Subversion
* wget

This image is dedicate for use with [Docker Plugin] (https://wiki.jenkins-ci.org/display/JENKINS/Docker+Plugin), but id needed you can run it locally:
```
docker run -d matisq/jenkins-slave
```

and connect to it via SSH or using ```docker exe command```
```
docker exec -it [CONTAINER_ID] bash
```

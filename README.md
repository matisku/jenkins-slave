# jenkins-slave for Jenkins Docker Plugin

## Summary
This is a simple image based on a latest [phusion/baseimage] (https://hub.docker.com/r/phusion/baseimage).

Additional packages installed:
* Latest Java 8 JDK
* Subversion
* wget

## Usage
This image is dedicate for use with [Docker Plugin] (https://wiki.jenkins-ci.org/display/JENKINS/Docker+Plugin) or [Yet Another Docker Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Yet+Another+Docker+Plugin), but if needed you can run it locally:
```
docker run -d matisq/jenkins-slave
```

and connect to it via SSH or using ```docker exe ``` command  
```
docker exec -it [CONTAINER_ID] bash
```  
```
ssh jenkins@[CONTAINER_IP]
```

## Metadata
[![](https://images.microbadger.com/badges/image/matisq/jenkins-slave.svg)](http://microbadger.com/images/matisq/jenkins-slave "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/matisq/jenkins-slave.svg)](http://microbadger.com/images/matisq/jenkins-slave "Get your own version badge on microbadger.com")

# jenkins-slave for Jenkins Docker Plugin

## Summary
This is a simple image based on a latest [phusion/baseimage](https://hub.docker.com/r/phusion/baseimage).

Additional packages installed:
* Latest Java 8 JDK
* Subversion
* wget

## Usage
This image is dedicate for use with [Docker Plugin] (https://wiki.jenkins-ci.org/display/JENKINS/Docker+Plugin) or [Yet Another Docker Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Yet+Another+Docker+Plugin), but if needed you can run it locally:
```bash
$ docker run -d -p 222:22 matisq/jenkins-slave
```

and connect to it via SSH or using ```docker exe ``` command  
```bash
$ docker exec -it [CONTAINER_ID] bash
$ ssh -p 222 jenkins@localhost
```

## Metadata 
* [![CircleCI](https://circleci.com/gh/matisku/jenkins-slave.svg?style=svg)](https://circleci.com/gh/matisku/jenkins-slave)  [![Build Status](https://travis-ci.org/matisku/jenkins-slave.svg?branch=master)](https://travis-ci.org/matisku/jenkins-slave)
* [matisq/jenkins-slave](https://hub.docker.com/r/matisq/jenkins-slave/) [![](https://images.microbadger.com/badges/image/matisq/jenkins-slave.svg)](http://microbadger.com/images/matisq/jenkins-slave "Get your own image badge on microbadger.com")


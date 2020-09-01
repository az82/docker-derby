# Apache Derby Docker Image
This repository provides a Docker image for Apache Derby using OpenJDK JRE.

You can find the built images at https://hub.docker.com/r/az82/docker-derby/.

## Software Versions
* Derby: 10.15.2.0 (http://db.apache.org/derby/index.html)
* Base Image: Latest AdoptOpenJDK 11 JRE image with Debian slim (https://github.com/AdoptOpenJDK/openjdk-docker)

## Image Properties
* Exposes port _1527_
* Provides a volume _/dbs_ that will contain the Apache Derby databases
* _derby.log_ is redirected to _stdout_
* Basic health check that verifies that Derby is attached to the listen port

## Build Status
* [Travis CI: ![Build Status](https://travis-ci.org/az82/docker-derby.svg?branch=master)](https://travis-ci.org/az82/docker-derby)

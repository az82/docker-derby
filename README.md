# Apache Derby Docker Image
This repository provides a Docker image for Apache Derby using the OpenJDK JRE and Alpine Linux.

You can find the built images at https://hub.docker.com/r/az82/docker-derby/.

## Software Versions
* Derby: 10.13.1.1 (http://db.apache.org/derby/index.html)
* Base Image: Latest OpenJDK 8 JRE image (https://github.com/docker-library/openjdk)

## Image Properties
* Exposes port _1527_
* Provides a volume _/dbs_ that will contain the Apache Derby databases
* _derby.log_ is redirected to _stdout_

## Build Status
* [Travis CI: ![Build Status](https://travis-ci.org/az82/docker-derby.svg?branch=master)](https://travis-ci.org/az82/docker-derby)

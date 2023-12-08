# Apache Derby Docker Image

> :warning: This image is no longer maintained.

This repository provides Docker images for Apache Derby using OpenJDK JRE.

You can find the built images at https://hub.docker.com/r/az82/docker-derby/.

## Software Versions

* Derby: 10.16.1.1  (http://db.apache.org/derby/index.html)
* Base Image: Latest Eclipse Temurin 17 JRE image with Debian Slim (https://hub.docker.com/_/eclipse-temurin)
* Architectures: linux/amd64,linux/arm64

## Image Properties

* Exposes port _1527_
* Provides a volume _/dbs_ that will contain the Apache Derby databases
* _derby.log_ is redirected to _stdout_
* Basic health check that verifies that Derby is attached to the listen port

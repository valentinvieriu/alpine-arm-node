# alpine-arm-node
[![Build Status](https://travis-ci.org/valentinvieriu/alpine-node-arm.svg?branch=master)](https://travis-ci.org/valentinvieriu/alpine-node-arm)
[![This image on DockerHub](https://img.shields.io/docker/pulls/valentinvieriu/alpine-node-arm.svg)](https://hub.docker.com/r/valentinvieriu/alpine-node-arm/)

Node Docker image for ARM architecture using Alpine as base

## Steps
If you run this on non ARM infrastructure, please run this first

```
docker run --rm --privileged multiarch/qemu-user-static:register --reset
```
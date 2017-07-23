# alpine-arm-node
[ ![Codeship Status for valentinvieriu/alpine-node-arm](https://app.codeship.com/projects/dff9e6c0-36c6-0135-f954-3a25db44eeb9/status?branch=master)](https://app.codeship.com/projects/227247)
[![This image on DockerHub](https://img.shields.io/docker/pulls/valentinvieriu/alpine-node-arm.svg)](https://hub.docker.com/r/valentinvieriu/alpine-node-arm/)

Node Docker image for ARM architecture using Alpine as base

## Steps
If you run this on non ARM infrastructure, please run this first

```
docker run --rm --privileged multiarch/qemu-user-static:register --reset
```
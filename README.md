docker-node-base
================

Dockerfile and script to create a container for running node applications as an unprivileged user.

To build:

    docker build --rm=true --tag=node-base .

Then, use this as the base image in another Dockerfile that adds your application...

For a fun automated alternative to all this work, see [dokku](https://github.com/progrium/dokku)



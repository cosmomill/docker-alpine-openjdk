Alpine Java (openJDK) Docker image
==================================

This image is based on Alpine GNU C library image ([cosmomill/alpine-glibc](https://hub.docker.com/r/cosmomill/alpine-glibc/)), which is only a 5MB image, and contains Java (openJDK).

Usage Example
-------------

This image is intended to be a base image for your projects, so you may use it like this:

```Dockerfile
FROM cosmomill/alpine-openjdk

COPY ./my_app /usr/local/bin/my_app
```

```sh
$ docker build -t my_app .
```

# docker-ubuntu1604
Docker repo for ubuntu 16.04

Creates a plain vanilla Ubuntu 16.04 base image from the [official repository](https://hub.docker.com/_/ubuntu/) 

To build:

`docker build -t ubuntu1604 - < Dockerfile`

Use:

As starting point for images based on Ubuntu 16.04.
Start Dockerfile with:

`FROM mcpayment/ubuntu1604`

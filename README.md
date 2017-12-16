# Ansible Testing - Ubuntu 14.04

*Current Build Status* <br/> [![Build Status](https://travis-ci.org/Artemu/ansible-container-ubuntu_1404.svg?branch=master)](https://travis-ci.org/Artemu/ansible-container-ubuntu_1404)

Builds are performed on the open Travis CI platform. Builds can be publicly accessed.

## Introduction
The following image is designed around the implementation and testing of Ansible roles, specifically for their automated testing within both the Jenkins and Travis env's.

At this point the implementation is restricted to Travis CI for simplification of the initial platform but will be extended to Jenkins at a later stage. Follow future updates for more information around this.

# Usage of the image
When running the build environment, you wish to make use of the image directly from the master build within GitHub. This can be achieved by pulling in the docker image as such:

`docker pull Artemu/ansible-container-ubuntu_1404:latest`

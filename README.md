# Ansible Testing - Ubuntu 14.04

[![Travis Status](https://img.shields.io/travis/Artemu/ansible-container-ubuntu_1404.svg?style=flat-square)](https://travis-ci.org/Artemu/ansible-container-ubuntu_1404) [![Docker Status](https://img.shields.io/docker/build/artemu/ansible-ubuntu_1404.svg?style=flat-square)](https://hub.docker.com/r/artemu/ansible-ubuntu_1404/) [![Docker Automation](https://img.shields.io/docker/automated/artemu/ansible-ubuntu_1404.svg?style=flat-square)](https://hub.docker.com/r/artemu/ansible-ubuntu_1404/)

Builds are performed on the open source Travis CI, as well as pushed to the Docker Hub via automated builds. Builds can be publicly accessed through the shields above, which also list their current build status.

## Introduction
The following image is designed around the implementation and testing of Ansible roles, specifically for their automated testing within both the Jenkins and Travis env's.

At this point the implementation is restricted to Travis CI for simplification of the initial platform but will be extended to Jenkins at a later stage. Follow future updates for more information around this.

See my GitHub profile for additional builds of Ubuntu Distributions, or other operating systems too.

# Usage of the image
When running the build environment, the images can be pulled directly from the Docker Hub.

`docker pull artemu/ansible-ubuntu_1404`

A blog post covering the full testing of an Ansible role has been written, please visit [my blog for more information](/etc/ansible/roles/role_under_test/tests/requirements.yml) detailing this process.

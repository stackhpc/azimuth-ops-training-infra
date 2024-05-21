# Azimuth Operations Training

This repository contains code for deploying a training environment for Azimuth operations into
an OpenStack project.

The training environment is deployed using [Ansible](https://www.ansible.com/) and
[OpenTofu](https://opentofu.org/), and consists of a single Ansible controller VM with multiple
users. Each user gets a checkout of [azimuth-config](https://github.com/stackhpc/azimuth-config)
with an AIO training environment installed and an app cred for provisioning an Azimuth AIO using
the training environment. The AIO can be provisioned automatically or left for the user to deploy.

The repository also contains some exercises for participants to perform on their AIO to
demonstrate some basic operations, such as upgrading Azimuth.

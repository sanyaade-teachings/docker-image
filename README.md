# General purpose Docker image.
Docker image files for virtual nodes without a specific process. It uses the Bash shell as the first process that runs indefinitely and acts as a simple reaper of zombie processes.

The idea behind the image is based on [Phusion](http://www.phusion.nl/) baseimage-docker but heavily modified.

You can use it as a base for your own Docker images. For more info on this
please check the [basedocker-image](https://github.com/phusion/baseimage-docker) README or the source code.

docker-ddns
==================

This Dockerfile builds an image with inadyn for DDNS. Based on Ubuntu 14.04 image.

Quick Start
-----------

It's required to customize the inadyn.conf for your DDNS settings. Please see the document of inadyn and inadyn.conf for details.

    docker run -v /home/yale/docker/ddns:/etc/inadyn -d --name ddns  yaleh/docker-ddns

Volumes to mount

* **/etc/inadyn**: folder for inadyn.conf

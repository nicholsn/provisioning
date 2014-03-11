# Ansible base container
FROM ubuntu:12.04
MAINTAINER Nolan Nichols <nolan.nichols@gmail.com>

RUN apt-get update 
RUN apt-get install -y python-software-properties
RUN add-apt-repository -y ppa:rquillo/ansible
RUN apt-get update
RUN apt-get install -y ansible git
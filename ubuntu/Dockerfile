FROM ubuntu:14.04

RUN apt-get update
RUN apt-get install -y -qq curl git python-pip
WORKDIR /opt
RUN pip install -r requirements.txt


CMD ["/bin/bash"] 

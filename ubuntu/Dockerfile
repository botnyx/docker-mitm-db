FROM ubuntu:14.04
COPY requirements.txt /tmp/requirements.txt
RUN apt-get update
RUN apt-get install -y -qq curl git python-pip
WORKDIR /opt
#RUN pip install -r /tmp/requirements.txt


CMD ["/bin/bash"] 

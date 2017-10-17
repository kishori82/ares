# ARES
This code implements katomicity and erasure code 


1. Installing ZMQ3 go https://github.com/pebbe/zmq3

to install: go get github.com/pebbe/zmq3



2. An online reference
http://zguide.zeromq.org/page:all

3. The zeromq guide for python developers (unfortunately we don't have one for Go developers, but Python would work as a general read)
https://lqhl.me/resources/zguide-py.pdf


4. How to build a docker image
docker build -t ares/core:v1 . -f resources/Dockerfile_ubuntu

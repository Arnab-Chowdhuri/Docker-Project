FROM    ubuntu:22.04
WORKDIR /tmp
ENV     myname Arnab
RUN     apt-get update && apt-get install tree
RUN     echo "My name is $myname" > /tmp/file1
ADD     /my_docker_project/roles.tar.gz .
COPY    /my_docker_project/host_file .

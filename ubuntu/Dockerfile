# Pull base image.
FROM ubuntu:14.04

# 163 sources.list
ADD sources.list /etc/apt/sources.list

# Install.
RUN \
  apt-get update && \
  apt-get -y upgrade 
  apt-get install -y build-essential && \
  apt-get install -y software-properties-common && \
  rm -rf /var/lib/apt/lists/* \
  apt-get clean

# Define default command.
CMD ["bash"]

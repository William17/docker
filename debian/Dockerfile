# Pull base image.
FROM debian:wheezy

# 163 sources.list
ADD sources.list.wheezy /etc/apt/sources.list

RUN apt-get update && \
	apt-get upgrade -y && \
	apt-get install -y  unzip wget python2.7
CMD ["bash"]
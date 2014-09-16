FROM william17/ubuntu:latest
MAINTAINER William Leung<superbill2012@qq.com>
ENV PATH $PATH:/opt/nodejs/bin
ENV VERSION v0.10.31
RUN mkdir -p /opt/nodejs && \
    wget -O - "http://www.nodejs.org/dist/${VERSION}/node-${VERSION}-linux-x64.tar.gz" | tar --strip-components=1 -C /opt/nodejs -x -z && \
    apt-get clean
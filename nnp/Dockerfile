FROM william17/nnp_nginx:latest
MAINTAINER William Leung<superbill2012@qq.com>

RUN \
 	apt-get update && apt-get install -y supervisor && \
    COPY supervisord.conf /etc/supervisor/conf.d/supervisord.conf

VOLUME ["/etc/supervisor/conf.d","/var/log"]

EXPOSE 22

CMD ["/usr/bin/supervisord"]
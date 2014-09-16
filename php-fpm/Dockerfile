FROM william17/debian:latest
MAINTAINER William Leung<superbill2012@qq.com>
RUN apt-key adv --keyserver keyserver.ubuntu.com --recv-keys E9C74FEEA2098A6E && \
	echo "deb http://packages.dotdeb.org/ wheezy-php55 all" > /etc/apt/sources.list.d/php.list && \
	apt-get update && \
	apt-get install -y php5-cli php5-curl php5-fpm php5-gd php5-mcrypt php5-mysql php5-pgsql php5-sqlite
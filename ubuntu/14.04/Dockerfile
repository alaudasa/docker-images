FROM index.alauda.cn/library/ubuntu:14.04

ADD sources.list /etc/apt/sources.list

RUN { \
		echo '[global]'; \
		echo 'trusted-host = pypi.douban.com'; \
		echo 'index-url = http://pypi.douban.com/simple'; \
	} > /etc/pip.conf

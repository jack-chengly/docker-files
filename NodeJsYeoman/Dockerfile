FROM selenium/standalone-chrome-debug:2.53.1
MAINTAINER jack <chengly@shinetechchina.com>

#============== 
# NodeJs and npm 
#============== 

RUN apt-get update -qqy \ 
	&& apt-get -qqy install \ 
	nodejs \ 
	npm \
	git \ 
	&& rm -rf /var/lib/apt/lists/* /var/cache/apt/*
	
RUN npm install -g \
	n \
    && n stable \
    && npm install -g \
    npm \
    yo   
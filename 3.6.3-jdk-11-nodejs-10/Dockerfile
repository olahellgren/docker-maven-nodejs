FROM maven:3.6.3-jdk-11
RUN apt-get install --yes curl \
&& curl --silent --location https://deb.nodesource.com/setup_10.x | bash - \
&& apt-get install --yes nodejs && apt-get install --yes build-essential \
&& npm install -g node-gyp

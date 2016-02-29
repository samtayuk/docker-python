FROM python:3
MAINTAINER Samuel Taylor "samtaylor.uk@gmail.com"

# Install Node Less bower sass
RUN apt-get update \
    && apt-get install -y -q --no-install-recommends npm node-less nodejs-legacy \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* \
    && npm -g install node-sass bower

FROM nginx

MAINTAINER disyam.adityana@gmail.com

RUN apt-get update && \
    apt-get install -y curl git gnupg && \
    curl -sL https://deb.nodesource.com/setup_6.x | bash - && \
    apt-get install -y nodejs
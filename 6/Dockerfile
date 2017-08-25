FROM nginx

MAINTAINER disyam.adityana@gmail.com

RUN apt-get update && \
    apt-get install -y curl git && \
    curl --silent --location https://rpm.nodesource.com/setup_6.x | bash - && \
    apt-get install -y nodejs
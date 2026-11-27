FROM nginx:latest

WORKDIR /app

RUN apt-get update  && \
    apt-get install nano -y && \
    apt-get install vim -y

COPY minhapagina/ /usr/share/nginx/html
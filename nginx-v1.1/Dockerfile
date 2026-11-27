FROM nginx:latest

ENTRYPOINT ["/docker-entrypoint.sh"]



RUN apt-get update  && \
    apt-get install nano -y && \
    apt-get install vim -y

COPY html/ /usr/share/nginx/html

ENTRYPOINT ["/docker-entrypoint.sh"]
CMD ["nginx", "-g", "daemon off;"]
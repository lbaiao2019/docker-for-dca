FROM ubuntu
RUN apt-get update -y
RUN apt-get install -y nginx
RUN apt-get install -y curl
HEALTHCHECK CMD curl --fail http://localhost:80/ || exit 1
CMD [ "nginx", "-g", "daemon off;" ]
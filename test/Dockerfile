FROM ubuntu
RUN apt-get update -y && apt-get install -y nginx
COPY index.html /var/www/html/
CMD ["nginx", "-g", "daemon off;"]

## docker build -t ubuntu-web .
## docker container run -dt --name ubuntu-web -p 8080:80 ubuntu-web:latest

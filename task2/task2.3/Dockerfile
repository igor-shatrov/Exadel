FROM ubuntu:20.04
RUN apt-get -y update
RUN apt-get install -y nginx

ENV DEVOPS="Igor Shatrov Exadel Sandbox 2021"
RUN echo $DEVOPS>/var/www/html/index.nginx-debian.html
CMD ["nginx", "-g", "daemon off;"]
EXPOSE 80
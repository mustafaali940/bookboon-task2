FROM ubuntu
RUN apt update && DEBIAN_FRONTEND="noninteractive" apt-get -y install apache2 && apt install default-jdk -y
CMD ["apachectl -D FOREGROUND"]

FROM mysql:latest

ENV MYSQL_DATABASE=test
ENV MYSQL_USER=alexandra
ENV MYSQL_PASSWORD=parola
ENV MYSQL_HOST=localhost

EXPOSE 3000

COPY test.sql /opt/app-root/src

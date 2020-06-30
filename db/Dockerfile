FROM mysql:5.7

ARG MYSQL_DATABASE

ENV MYSQL_DATABASE=flask_prod

ARG MYSQL_ROOT_PASSWORD 

ENV MYSQL_ROOT_PASSWORD=root

COPY ./CreateTable.sql ./docker-entrypoint-initdb.d/

EXPOSE 3306

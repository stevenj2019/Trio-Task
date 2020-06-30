FROM mysql

CMD mysql -u root -proot -e 'CREATE DATABASE flask-db'

COPY ./db/CreateTable.sql /docker-entrypoint-initdb.d/

EXPOSE 3306

FROM mysql:5.7

ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=digital_library

EXPOSE 3306

COPY database.sql /docker-entrypoint-initdb.d/

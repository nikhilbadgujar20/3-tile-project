FROM mysql:latest

LABEL database="studentapp"

ENV MYSQL_ROOT_PASSWORD=1234

COPY std-db.sql /docker-entrypoint-stddb.d/

CMD ["mysqld"]
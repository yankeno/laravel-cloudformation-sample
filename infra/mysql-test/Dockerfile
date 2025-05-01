FROM mysql/mysql-server:8.0

ENV MYSQL_DATABASE=laravel \
    MYSQL_USER=phper \
    MYSQL_PASSWORD=secret \
    MYSQL_ROOT_PASSWORD=secret \
    TZ=Asia/Tokyo

COPY ./my.cnf /etc/my.cnf
RUN chown mysql:mysql /etc/my.cnf && chmod 644 /etc/my.cnf

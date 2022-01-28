FROM centos:6.9

VOLUME /var/lib/mysql/mysql

COPY config/my.cnf /etc/my.cnf

EXPOSE 3306

CMD service mysqld restart; while true; do sleep 100; done;
FROM mysql:8.0.23

ENV MYSQL_ROOT_PASSWORD=root
ENV TZ=Asia/Tokyo

RUN apt update -qq && apt install -y sudo vim

EXPOSE 3306

COPY ./my.cnf /etc/mysql/conf.d/my.cnf

CMD ["mysqld"]
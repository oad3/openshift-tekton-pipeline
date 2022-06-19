# FROM postgres:11-alpine
# FROM postgres:14-alpine
# FROM ubuntu/postgres:14-22.04_beta

FROM registry.redhat.io/rhscl/postgresql-95-rhel7

# Time Zone
# ENV TZ UTC

# ENV POSTGRESQL_USER postgres
# ENV POSTGRES_PASSWORD postgres
# ENV POSTGRESQL_DATABASE postgres

#RUN    /etc/init.d/postgresql start &&\
#RUN psql --command "CREATE USER docker WITH SUPERUSER PASSWORD 'docker';" &&\
#RUN createdb -O docker docker

#RUN echo "host all  all    0.0.0.0/0  md5" >> /etc/postgresql/9.3/main/pg_hba.conf
#RUN echo "listen_addresses='*'" >> /etc/postgresql/9.3/main/postgresql.conf

EXPOSE 5432


# ¡postgres:11-alpine
# docker build -t oad3jp999/postgresql-server:0.0.1 ./server/
# docker run -d --name postgresql-server -p 5432:5432 oad3jp999/postgresql-server:0.0.1
# docker exec -it postgresql-server /bin/bash
# psql -U postgres -d postgres -h localhost

# ¡ubuntu/postgres:14-22.04_beta
# https://hub.docker.com/r/ubuntu/postgres
# docker build -t oad3jp999/postgresql-server:0.0.2 ./server/
# docker run -d --name postgresql-server2 -p 5432:5432 oad3jp999/postgresql-server:0.0.2
# docker exec -it postgresql-server2 /bin/bash

# docker container export postgresql-server2 > postgresql-server.tar
# cat ./postgresql-server.tar | docker image import - oad3jp999/postgresql-server:0.0.3
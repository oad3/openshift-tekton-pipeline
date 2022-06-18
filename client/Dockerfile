FROM ubuntu:latest

RUN apt-get update && \
    apt-get install -y postgresql-client

ENTRYPOINT tail -f /dev/null

# docker build -t oad3jp999/postgresql-client:0.0.1 ./client/
# docker run -d --name postgresql-client oad3jp999/postgresql-client:0.0.1
# docker exec -it postgresql-client /bin/bash
# psql -h 172.17.0.2 -d postgres -U postgres
# psql -h 172.17.0.2 -d postgres -U postgres


# postgres@7ef98b1b7243:/$ psql -h $PG_PORT_5432_TCP_ADDR -p $PG_PORT_5432_TCP_PORT -d postgres -U postgres --password

FROM postgres:10
COPY ./setup-db.sh /docker-entrypoint-initdb.d/setup-db.sh
RUN chmod 777 /docker-entrypoint-initdb.d/setup-db.sh

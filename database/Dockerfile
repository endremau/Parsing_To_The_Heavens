FROM postgres
ENV POSTGRES_DB netjson_dev
COPY 001_initial_schema.sql /docker-entrypoint-initdb.d/
COPY datadump.sql /docker-entrypoint-initdb.d/
EXPOSE 5432

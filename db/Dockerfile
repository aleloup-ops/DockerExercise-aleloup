FROM postgres:latest

COPY . .

ENV POSTGRES_HOST_AUTH_METHOD trust

COPY words.sql /docker-entrypoint-initdb.d/

EXPOSE 5432
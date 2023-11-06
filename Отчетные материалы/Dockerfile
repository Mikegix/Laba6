FROM postgres:latest
ENV POSTGRES_PASSWORD=pass
ENV POSTGRES_USER=usr
ENV POSTGRES_DB=dbn
COPY init_scripts/init.sql /docker-entrypoint-initdb.d/init.sql
VOLUME /d_data:/var/lib/postgresql/data



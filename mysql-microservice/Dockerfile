FROM mysql:5.7

## The maintainer name and email
MAINTAINER Stephen Mburu <ahoazure@gmail.com>

# database = test and password for root = password
ENV MYSQL_DATABASE=test \
    MYSQL_ROOT_PASSWORD=password

# when container starts, test database schema will be created
COPY ./test-dump.sql /docker-entrypoint-initdb.d/

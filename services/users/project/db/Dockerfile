FROM postgres

# extend the official postgres image by adding an SQL file to the docker-entrypoint-initdb.d
# it enables create.sql to run on init
ADD create.sql /docker-entrypoint-initdb.d

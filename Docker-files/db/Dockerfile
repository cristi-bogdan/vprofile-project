FROM mysql:8.0.36
LABEL "Porject"="Vprofile"
LABEL "Author"="Cristi"

ENV MYSQL_ROOT_PASSWORD="admin" 
ENV MYSQL_DATABASES="vprodbpass"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
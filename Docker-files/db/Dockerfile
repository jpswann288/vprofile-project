FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Jason"

ENV MYSQL_ROOT_PASSWORD="vprodpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docket-entrypoint-initdb.d/db_backup.sql
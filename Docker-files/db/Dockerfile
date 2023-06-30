FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Joccai"

ENV MYSQL_ROOT_PASSWORD="ilestretard"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql 

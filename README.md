# linux-command

ls | grep

lsof -i tcp:8080 

kill pid

pwd

service nginx restart

systemclt restart nginx

ssh-keygen

# mySQL

mysql -u root -p 

show databases;

use database-name;

show tables;

show variables like 'port';

quit；

> Rename a Database

mysqldump -u username -p"password" -R oldDbName > oldDbName.sql

mysqladmin -u username -p"password" create newDbName

mysql -u username -p"password" newDbName < oldDbName.sql





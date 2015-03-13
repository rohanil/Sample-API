# testapi

to create database and table, run following on shell:
mysql -u root <api/restAPI.sql

then go to index.php and chenge $dbusername , $dbpasswd variables according to your database settings.

put whole 'api/' folder under your servers /var/www/html/ directory.

open browser on local and type: server_ip/api/index.php/users
(this will give you users json data included in db)

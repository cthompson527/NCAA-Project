# README #

Progress stopped at https://docs.djangoproject.com/en/1.10/intro/tutorial03/

pip freeze output:
Django==1.10
mysqlclient==1.3.7


## Setup ##
[ ] Run vagrant up && ssh
[ ] vim /etc/mysql/my.cnf (bind-address = 0.0.0.0)
[ ] start mysql (/usr/bin/mysqld_safe and mysql_install_db)
[ ] check mysql (mysql -u root -h 127.0.0.1 -p)
[ ] Create virtualenv environment and source into it
[ ] pip django and mysqlclient
[ ] connect PyCharm to mysql by adding root@10.0.2.2 user

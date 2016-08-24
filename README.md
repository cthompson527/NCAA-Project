# README #

Progress stopped [here](https://docs.djangoproject.com/en/1.10/intro/tutorial03/)

pip freeze output:

Django==1.10

mysqlclient==1.3.7


## Setup ##

1. Run vagrant up && ssh
2. vim /etc/mysql/my.cnf (bind-address = 0.0.0.0)
3. start mysql (/usr/bin/mysqld_safe and mysql_install_db
4. check mysql (mysql -u root -h 127.0.0.1 -p)
5. Create virtualenv environment and source into it
6. pip django and mysqlclient
7. connect PyCharm to mysql by adding root@10.0.2.2 user

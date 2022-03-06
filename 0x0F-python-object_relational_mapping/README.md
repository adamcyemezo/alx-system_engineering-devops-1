#  Python - Object-relational mapping

n this project, you will link two amazing worlds: Databases and Python!

In the first part, you will use the module MySQLdb to connect to a MySQL database and execute your SQL queries.

In the second part, you will use the module SQLAlchemy (don’t ask me how to pronounce it…) an Object Relational Mapper (ORM).

The biggest difference is: no more SQL queries! Indeed, the purpose of an ORM is to abstract the storage to the usage. With an ORM, your biggest concern will be “What can I do with my objects” and not “How this object is stored? where? when?”. You won’t write any SQL queries only Python code. Last thing, your code won’t be “storage type” dependent. You will be able to change your storage easily without re-writing your entire project.

## what are Object-relational Mappers
(<b>ORM:<b>) is a code library that is used to transefer data stored in the Relational database table into object that are more commonly used in application

## Install MySQLdb module version 2.0.x
```bash
sudo apt-get install python3-dev
sudo apt-get install libmysqlclient-dev
sudo apt-get install zlib1g-dev
sudo pip3 install mysqlclient
...
python3
>>> import MySQLdb
>>> MySQLdb.version_info 
(2, 0, 3, 'final', 0)
```
## Install SQLAlchemy module version 1.4.x
```bash
 sudo pip3 install SQLAlchemy
...
 python3
>>> import sqlalchemy
>>> sqlalchemy.__version__ 
'1.4.22'
```
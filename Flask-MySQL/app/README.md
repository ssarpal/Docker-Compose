# Flask MySQL application

Test flask services using the following RestFul API 

Create Database
----------------

After starting docker-compose up, you have to assgin the hostname of mysql-server as assgined in docker-compose.yml

	http://localhost:8082/createdb?hostname=mysqlserver

Create and Initiate Users Table
--------------------------------

	http://localhost:8082/createtbl

Insert New User:
----------------

	http://localhost:8082/insert?username=alice&email=alice@gmail.com&phone=02-9454402334&fax=+4438384
	http://localhost:8082/insert?username=bob&email=bob@gmail.com&phone=02-9454402335&fax=+4438385

	OR, fill up the form and submit ...

	http://localhost:8082/form

Select all Users
----------------

	http://localhost:8082/users

Select specific user
--------------------

	http://localhost:8082/user?username=bob

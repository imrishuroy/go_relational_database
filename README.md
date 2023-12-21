Accessing a relational database
https://go.dev/doc/tutorial/database-access

    docker run --detach --env MYSQL_ROOT_PASSWORD=dummypassword --env MYSQL_USER=imrishuroy --env MYSQL_PASSWORD=123456 --env MYSQL_DATABASE=product_database --name mysql --publish 3306:3306 mysql:8-oracle

    docker exec -it mysql bash

    mysql -u root -p

    Enter password: dummypassword

    mysql> show databases;

    mysql> create database recordings;
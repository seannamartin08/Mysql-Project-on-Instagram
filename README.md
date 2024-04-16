# Mysql-Project-on-Instagram

Creating a MySQL project on the application Instagram 
This application gives us the information on the how many users are registered in it and the information regarding the amount of likes on a post or the type of music used on a highlighted story or caption put on a particular post

Database schema 
User Table: 
create table user2 (Userid varchar(100) primary key,Username varchar (70),Passcode varchar (75),Email varchar(100),Gender char(10)); 
Post Table :
create table post2 (Userid varchar (100) primary key, Postid varchar(100), Caption varchar(100), Music varchar(100), Location varchar(50), Mention varchar(100));
Highlight Story:
create table highlight_story (Location varchar(100),Music varchar(100),Mention varchar(50));
Likes:
create table likes (Userid varchar(100),Postid varchar(50),Active_likes varchar(10));

There are total of 30 Questions 
10 containing single table outputs
10 containing double table outputs
10 containing three table  outputs



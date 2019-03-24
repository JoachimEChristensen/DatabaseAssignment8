# DatabaseAssignment8

## Process
Follow the instructions for setting up a slave database in the attached tutorial from the assignment text. When asked to use a copy of the database, use the following commands:

mysql -e 'create database classicmodels' 

rsync -z root@128.199.77.37:classicmodels.sql  .

mysql classicmodels < classicmodels.sql

When asked for a password when running rsync, use the password attached in the peergrade delivery.

To test the database, use the attached user.

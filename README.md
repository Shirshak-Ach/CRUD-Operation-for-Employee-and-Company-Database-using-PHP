# CRUD-Operation-for-Employee-and-Company-Database-using-PHP
# A project I did when I was studying Web Technologies on Thapathali Campus, TU.

Make sure to create DB and inside that DB create two tables company and employee.

Run this code on terminal :

```
sudo mysql -h 127.0.0.1 -P 3307 -u root -p
```
Inside my sql
```
create database company;
use company;
create table company (Id int auto_increment primary key, Company_name VARCHAR(255), Address VARCHAR(255));
create table employee (Id int auto_increment primary key, Name VARCHAR(255), Salary FLOAT, Date_of_birth DATE, Company VARCHAR(255));
```

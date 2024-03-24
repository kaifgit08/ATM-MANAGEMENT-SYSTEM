# 🏦 Banking System Project

## Setting Up the Database

First, create a database and implement the following code:

```sql
create database banking_system;
use banking_system;
show tables;
create table accounts(
account_number bigint primary key,
full_name varchar(255) not null,
email varchar(255) not null,
balance decimal(10,2) not null,
security_pin char(4) not null
);
create table user(
full_name varchar(255) not null,
email varchar(255) not null primary key,
password varchar(255) not null
);
# Running the BankingApp

After implementing the database schema, run the `BankingApp` which contains the main method in your IDE.

If the application is not running, ensure that the MySQL connector is added to the JRE Classpath.

## 📦 Features

- User Registration & Login
- Account Creation
- Debit and Credit Transactions
- Money Transfer Between Accounts
- Balance Inquiry
- Robust Security Measures

## 🌐 Technologies Used

- Java
- JDBC (Java Database Connectivity)
- MySQL (or your preferred database system)

Feel free to explore and utilize this Banking System Project for your needs!

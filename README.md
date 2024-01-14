# Warbler
### A Twitter Clone

## Application Summary

This project is a simplified twitter clone. The purpose of the project is to familiarize myself with B-Crypt hashing and aunthentication and create effective relationship databases with postgres and sqlalchemy. Data for users and messages 
as well as images were provided by Springboard's Full-Stack Engineer curriculum.

## User Flow

Upon entering the site users will have the ability to login or signup. Either path will use B-Crypt to hash the password in order to register new users or cross-refernce input values with stored hashed data found in the user database. After 
successfully loging in or signing up users will enter a home page that is filled with either the most recent messages posted by all accounts or the most recent messages posted by accounts followed by the user. Users have the ability to like 
messages which will be tracked by the database. The user can also click on usernames to view other accounts' public data. By clicking on the users profile they are taken to the profile page where they can make messages, update profile
information, see list of followed/following accounts, or even delete the account.

## Technologies

A list of dependencies used in the project can be found in the requirement.txt file. The languages used throughout the project include:
- JavaScript
- CSS
- HTML5
- Python
- SQL


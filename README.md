Description:
PHP + MySQL web application to store and display cricket match scores and player stats.

Features:
Store match data in MySQL database
Retrieve and display scores dynamically
Show team and player statistics
Simple HTML & CSS interface

Tech Stack:
PHP
MySQL (CLI)
HTML
CSS

Setup Instructions:
Clone the repository
Create MySQL database via CLI:
CREATE DATABASE cricinfo;
USE cricinfo;
SOURCE cricinfo.sql;

Update database credentials in db/config.php

Start PHP server: php -S localhost:8000

Open browser at: http://localhost:8000

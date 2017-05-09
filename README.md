# EasyPass

EasyPass is a University project completed for the Unit COSC2635 at RMIT University. The aim of this project was to plan, develop and deliver a password free secure application for storage of a users credentials.

## Getting Started

Please use the latest version from the master

### Prerequisites

Ubuntu 14.04,  MySQL 5.6 or later, Apache2, PHP

### Installing
### 1.	Install Lamp Stack in Ubuntu 14.04:

Install apache: 
sudo apt-get update
sudo apt-get install apache2

Install MySQL:
sudo apt-get install mysql-server php5-mysql
sudo mysql_install_db
sudo mysql_secure_installation

Install PHP:
sudo apt-get install php5 libapache2-mod-php5 php5-mcrypt

Edit dir.conf to to request PHP first:
sudo nano /etc/apache2/mods-enabled/dir.conf
<IfModule mod_dir.c>
    DirectoryIndex index.php index.html index.cgi index.pl index.xhtml index.htm
</IfModule>

sudo service apache2 restart

Install PHP modules as required.

### 2.	Copy All files to the webserver directory. 

### 3.	Create the MySQL Database:

create database easypass;

create table user (id int(11) NOT NULL AUTO_INCREMENT, email varchar(111) NOT NULL, password varchar(111) NOT NULL, q1 text DEFAULT NULL, q1a varchar(111) DEFAULT NULL, q2 text DEFAULT NULL, q2a varchar(111) DEFAULT NULL, q3 text DEFAULT NULL, q3a varchar(111) DEFAULT NULL, created_at datetime DEFAULT CURRENT_TIMESTAMP, updated_at datetime DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP, PRIMARY KEY (id));

## Test that the server is working correctly 

Run the application from a web browser to ensure that everything is working correctly.

## Built With

* [Bootstrap]( http://getbootstrap.com/) - Framework
* [CyptoJS]( https://github.com/sytelus/CryptoJS) – Crypto Library

## Authors

Scott
Rhys
Diana
Gerry
Nic

## License

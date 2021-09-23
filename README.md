# php_login_system
A simple login form in PHP for the users.

<h1 align="center">
  Login
</h1>

<p align="center">
  <img width="50%" height="50%" src="https://user-images.githubusercontent.com/54533886/134512071-37d1963a-3f77-4b89-8f45-4468d8f481e5.png">
</p>

<h1 align="center">
  Register
</h1>

<p align="center">
  <img width="50%" height="50%" src="https://user-images.githubusercontent.com/54533886/134512147-fa13878a-4818-41bb-9098-03b097dec7d5.png">
</p>

<h1 align="center">
  Dashboard
</h1>

<p align="center">
  <img width="50%" height="50%" src="https://user-images.githubusercontent.com/54533886/134512563-00d55fb8-1d95-499c-8f7f-42daf3d9b735.png">
</p>

# Steps for Start Up

Follow the steps bellow and everything should work fine:

#01

Start XAMPP, start Apache and MySQL in XAMPP. Then click on Admin next to MySQL.

#02

Create a database in phpmyadmin called php_login_system

#03

Copy, paste and run this code in phpmyadmin sql section for the database:

CREATE TABLE IF NOT EXISTS `users` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `username` varchar(100) NOT NULL,
  `email` varchar(100) NOT NULL,
  `password` varchar(100) NOT NULL,
  `create_at` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
  PRIMARY KEY (`id`)
);

Or

In the sql map you can find a file named users.sql. 
Import the file in the database via the Import TAB for the database.

#04

Open your webbrowser and in the search bar, typ: localhost/php_login_system
to see the project files.

#05

Now you can try out the files on your PC.

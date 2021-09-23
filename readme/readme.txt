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
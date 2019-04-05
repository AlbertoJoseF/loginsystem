# loginsystem
Login system implemented with PHP, Apache web server (using XAMPP) and MySQL database with PHP prepared statements. 

## What you need beforehand:
* XAMPP Apache web server.
* Created DB using phpMyAdmin (accessed through localhost/phpmyadmin).

### For preparing DB and running login system:
* Click on Start for the modules of Apache and MySQL of the XAMPP Control Panel.
* On any browser go to localhost/phpmyadmin.
* Create new database with the "loginsystem" name.
* In the new loiginsystem DB create table with the following characteristics:

```bash
CREATE TABLE `loginsystem`.`users` ( `idUsers` INT NOT NULL AUTO_INCREMENT , `uidUsers` VARCHAR NOT NULL , `emailUsers` VARCHAR NOT NULL , `pwdUsers` VARCHAR NOT NULL , PRIMARY KEY (`idUsers`)) ENGINE = InnoDB;
```

### To run login system:
* Copy all files in folder (preferably named "loginsystem") located in the htdocs folder of the xampp preinstalled directory, i.e. C:\xampp\htdocs\loginsystem.
* On any browser go to localhost/loginsystem.
* Try out the system.

### Notes:
* Preferably use code editor to view PHP code.

### Built using:
* XAMPP (https://www.apachefriends.org/index.html) - Apache Local Web Server
* Visual Studio Code (https://code.visualstudio.com/) - Code editor

### References:
* How To Create A Complete Login System In PHP | Procedural MySQLi | 2018 PHP Tutorial | mmtuts (https://www.youtube.com/watch?v=LC9GaXkdxF8) - Video tutorial [mmtuts] on how to build basic login system 


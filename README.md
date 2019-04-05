# loginsystem
Login system implemented with PHP, Apache web server (using XAMPP) and MySQL database with PHP prepared statements. 

### What you need beforehand:
* XAMPP Apache web server
* Created DB using phpMyAdmin (accessed through localhost/phpmyadmin)

### For preparing DB and running login system:
* Click on Start for the modules of Apache and MySQL of the XAMPP Control Panel.
* On any browser go to localhost/phpmyadmin
* Create new database with the "loginsystem" name.
* In the new loiginsystem DB create table with the following characteristics:

```bash
CREATE TABLE `loginsystem`.`users` ( `idUsers` INT NOT NULL AUTO_INCREMENT , `uidUsers` VARCHAR NOT NULL , `emailUsers` VARCHAR NOT NULL , `pwdUsers` VARCHAR NOT NULL , PRIMARY KEY (`idUsers`)) ENGINE = InnoDB;
```

### To run login system:

* On any browser go to localhost/loginsystem


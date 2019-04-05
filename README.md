# loginsystem
Login system implemented with PHP, Apache web server (using XAMPP) and MySQL database with PHP prepared statements. 

## What you need beforehand:
* XAMPP Apache web server (link for download below).
* Created DB using phpMyAdmin (accessed through localhost/phpmyadmin after installing XAMPP and running its Apache and MySQL modules).

### For preparing DB to running login system:
* Click on Start button for the modules of Apache and MySQL of the XAMPP Control Panel.
* On any browser go to:
```bash
localhost/phpmyadmin
```

* Create new database with the "loginsystem" name.
* In the new loginsystem DB create table with the following characteristics:
```bash
CREATE TABLE `loginsystem`.`users` ( `idUsers` INT NOT NULL AUTO_INCREMENT , `uidUsers` VARCHAR NOT NULL , `emailUsers` VARCHAR NOT NULL , `pwdUsers` VARCHAR NOT NULL , PRIMARY KEY (`idUsers`)) ENGINE = InnoDB;
```

### How to run login system:
* Copy all files and directories of the loginsystem project into new folder (preferably named "loginsystem") located in the htdocs folder of the xampp preinstalled directory, 
i.e.
```bash
C:\xampp\htdocs\loginsystem
```

* Make sure to have the Apache and MySQL modules in the XAMPP Control Panel started (by clicking on their respective Start buttons).

* On any browser go to:
```bash
localhost/loginsystem
```

* Note that if files and directories of project are copied into another subdirectory of the htdocs folder the URL to go to will change.
i.e.
```bash
localhost/someFolder/subdirectory
```

* Try out the system.

### Notes:
* Preferably use code editor to view PHP code.

### Built using:
* XAMPP (https://www.apachefriends.org/index.html) - Apache Local Web Server
* Visual Studio Code (https://code.visualstudio.com/) - Code editor

### References:
* How To Create A Complete Login System In PHP | Procedural MySQLi | 2018 PHP Tutorial | mmtuts (https://www.youtube.com/watch?v=LC9GaXkdxF8) - Video tutorial [mmtuts] on how to build basic login system 


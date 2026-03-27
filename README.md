# INET4031 PHP Crude CRUD App (MariaDB/MySQL DB Version)

## Los Pollos Hermanos Employee Management System
Standard LAMP Stack Application

**Department of Systems Engineering**
*Created by Roscoe Bell, Ridwan Nur, Alieu Sarr*

This application is an employee management system webapp, that allows for users of the application to quickly find, add, and remove users from the database of employees.

### LAMP Component 1: Linux

This application should be run within a Linux environment, necessary specifications for the machine are as follows:
- Suggested # of CPU Cores: 2
- Suggested size of RAM: 2048 MB (~2GB)
- Suggest size of Virtual Hard Disk: 25 GB
- Suggested Network Adapter settings: Use Host-Only Network Host-Only network necessary for SSH-ing into virtual machine, allowing you to utilize your own computer’s terminal instead of the one supplied by the virtual machine.
### LAMP Component 2: Apache

***USING APACHE 2.4***

The files in this directory should be used within the /var/www/html directory to get the application running, and can be cloned using the `Crude_CRUD_9.tar.gz` tarball file for easier transportation to the correct directory.

### LAMP Component 3: MySQL
***USING MYSQL 15.1***

Relies on the employees.sql file in order to create and use the database

```bash
mysql -u <yourusername> -p -t < employees.sql
```

### LAMP Component 4: PHP

This application relies heavily on PHP to function as intended, a couple of apps are needed:
- PHP Version Used: PHP 8.3.6
- PHP-MySQL Connector Version Used: php-mysql, using MariaDB 15.1, Distribution 10.11.14






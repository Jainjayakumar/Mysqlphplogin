# Mysql-php-login
An android login app with Mysql database on server to verify credentials.

## NOTE
The line 75 of main activity java contains url of our localhost/server,which will not work for others.\
Give valid url before running the app.\
url = new URL("http://192.168.42.204/login.inc.php");\

The server should contain two files: config.inc.php & login.inc.php (included in folder php)\
Also configure config.inc.php file with correct credentials.\


This app is developed from the instuctions given in link given. http://androidcss.com/android/android-php-mysql-login-tutorial/

### Server version: 
* Apache/2.4.29 (Ubuntu)
* PHP 7.2.19
* mysql  Ver 14.14 Distrib 5.7.26, for Linux (x86_64)

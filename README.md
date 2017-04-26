## ******Install Apache****** ## 
***
1. Open Terminal (ctrl+alt+t)
2. Type the following code in terminal ```sudo apt-get install apache2```
3. Terminal will ask for a password. Choose and type a password.

***
## ******Install PHP****** ## 
1. Now type the command ```sudo apt-get install php5 libapache2-mod-php5```
2. Restart Apache2. Type the command ```sudo /etc/init.d/apache2 restart```
3. This command will create a file name test.php in Gedit automatically. Type the command ```sudo gedit /var/www/html/test.php```
4. Now type the php code in test.php
5. Open ```http://localhost/test.php```
6. You can see the output of your php code.
***

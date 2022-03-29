# web
virtual machine install linux---40gb
hard disk file type:VMDK是專門為VMWare開發，但其他虛機像Sun xVM，QEMU，VirtualBox，SUSE Studio和.NET DiscUtils也都支持這種格式。

---------------------------------------------------------------
btrfs
total:40gb
efi:550mb
/:34207mb
swap: 8192mb
---------------------------------------------------------------

1)Mint


2)fedora



3)opensuse



4)ubuntu


5)debian




install LAMP
sudo apt install install apache2






apache config
netstat -plnt
cd /etc/apache2/sites-enabled/
cd /var/www/html/

vm network config
http tcp 





sudo apt install apache2
systemctl status apache2

sudo apt install mysql-server mysql-client
systemctl status mysql
sudo mysql_secure_installation
-------------------------------------------------------------------------------------------------------------
Press y|Y for Yes, any other key for No: y

There are three levels of password validation policy:
LOW    Length >= 8
MEDIUM Length >= 8, numeric, mixed case, and special characters
STRONG Length >= 8, numeric, mixed case, special characters and dictionary                  file

Please enter 0 = LOW, 1 = MEDIUM and 2 = STRONG: 2
password:***********

Do you wish to continue with the password provided?(Press y|Y for Yes, any other key for No) : y
By default, a MySQL installation has an anonymous user,
allowing anyone to log into MySQL without having to have
a user account created for them. This is intended only for
testing, and to make the installation go a bit smoother.
You should remove them before moving into a production
environment.

Remove anonymous users? (Press y|Y for Yes, any other key for No) : y
Success.


Normally, root should only be allowed to connect from
'localhost'. This ensures that someone cannot guess at
the root password from the network.

Disallow root login remotely? (Press y|Y for Yes, any other key for No) : y
Success.

By default, MySQL comes with a database named 'test' that
anyone can access. This is also intended only for testing,
and should be removed before moving into a production
environment.


Remove test database and access to it? (Press y|Y for Yes, any other key for No) : y
 - Dropping test database...
Success.

 - Removing privileges on test database...
Success.

Reloading the privilege tables will ensure that all changes
made so far will take effect immediately.

Reload privilege tables now? (Press y|Y for Yes, any other key for No) : y
---------------------------------------------------------------------------------------

sudo mysql -u root
mysql --version


sudo apt install php libapache2-mod-php php-mysql
systemctl status apache2
php -v













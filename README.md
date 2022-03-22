# web
virtual machine install linux---40gb
hard disk file type:VMDK是專門為VMWare開發，但其他虛機像Sun xVM，QEMU，VirtualBox，SUSE Studio和.NET DiscUtils也都支持這種格式。

---------------------------------------------------------------
network type: Bridged
Host-Only: The VM will be assigned one IP, but it's only accessible by the box VM is running on. No other computers can access it.

NAT: Just like your home network with a wireless router, the VM will be assigned in a separate subnet, like 192.168.6.1 is your host computer, and VM is 192.168.6.3, then your VM can access outside network like your host, but no outside access to your VM directly, it's protected.

Bridged: Your VM will be in the same network as your host, if your host IP is 172.16.120.45 then your VM will be like 172.16.120.50. It can be accessed by all computers in your host network.

cmd:$ipconfig
***find u ethernet adapter or u wireless lan adapter wifi, but i prefer ethernet
 IPv4 Address : 140.123.222.175
 Subnet Mask : 255.255.255.0
 Default Gateway : 140.123.222.250
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



















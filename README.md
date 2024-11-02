# freeradius-config
This script will guide you through the installation and configuration of the following components:
- LAMP stack (Linux, Apache, MySQL/MariaDB, PHP)               
* FreeRADIUS for authentication and authorization
- Hotspot Billing software for accounting and authorization.

## Install using GIT
```
sudo apt-get install git
```
```
sudo git clone https://github.com/mahmud1448/smbilling.git
```
```
cd freeradius-config
sudo chmod +x install.sh
sudo ./install.sh
```

## Note
After Successful Installation without error
You have to move the files to root folder, so that you can access it directly without sub-folder e.g http://host-or-ip/
```
sudo mv /var/www/html/phpnuxbill/* /var/www/html
```
Vistit http://host-or-ip/
Replace [host-or-ip] with your ip address or hostname




## Tested
This shell script is tested successfully on

- **Ubuntu 24.04  LTS**
- **Ubuntu 22.04  LTS**
- **Ubuntu 20.04  LTS**
- **Ubuntu 18.04  LTS**
- **Debian 10, 11, 12**


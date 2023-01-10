# File System Heirarchy

## /home(directory)
* home directory for other user
## /root(directory)
* it is home directory for root user
## /boot(directory)
* /boot or 'Boot' folder contains the linux boot configuration files. This is one of the MOST important folder. Removing anything from this directory or a file getting corrupted will result in a OS crash after reboot. You system won't be able to boot without files in the /boot directory.
## /etc(directory)
* It contains all configuration files
## /usr(directory)
* by default software are installed in this directory
## /bin(directory)
* it contains commands used by all users ( **Including root user** )
## /sbin(directory)
* it contains commands by only root users 
## /opt(directory)
* optional application software packages
## /dev(directory)
* /dev is the location of special or device files. It is a very interesting directory that highlights one important aspect of the Linux filesystem - everything is a file or a directory.
Referensi
https://doc.aapanel.com/web/#/3?page_id=178

https://forum.aapanel.com/d/276-how-to-bind-domain-to-my-server-ip-address-dns-configuration-etc/2

Tools
 - Terminus

Install panel in server ubuntu 20.04
```
$ wget -O install.sh http://www.aapanel.com/script/install-ubuntu_6.0_en.sh && sudo bash install.sh 93684c35
```
 > Select y
 > Select n for disable no ssl
 Wait for process completed..
 
 Copy and save file in here:
 Congratulations! Installed successfully!
==================================================================
aaPanel Internet Address: http://your_ip:7800/reff

aaPanel Internal Address: http://your_ip:7800/reff
username: xxxxxx
password: xxxxxx
Warning:
If you cannot access the panel, 
release the following port (7800|888|80|443|20|21) in the security group
==================================================================

for manage Aapanel using command in root mode:
$ bt

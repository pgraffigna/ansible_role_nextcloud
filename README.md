# ansible_nextcloud
Playbook con configuración para desplegar un Servidor Nextcloud.

Testeado con Virtualbox + Ubuntu Server 20.04  

roles:	 
- firewall
- nextcloud

---
Tener en cuenta cambiar el n° de ID en la ruta de configuración de nextcloud.

ruta: /var/snap/nextcloud/ID/nextcloud/config/config.php

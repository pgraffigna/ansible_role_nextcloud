# ansible_role_nextcloud

Playbook para desplegar un Servidor Nextcloud.

Testeado con Vagrant + qemu + ubuntu_2204 + ansible_2.10

---

### Descripción

La idea del proyecto es automatizar vía ansible la instalación/configuración de un servicio [nextcloud](https://docs.nextcloud.com/server/latest/admin_manual/installation/source_installation.html) para pruebas de laboratorio, el repo cuenta con 3 roles:

1. mariadb
2. apache
3. nextcloud
4. redis

### Dependencias

* [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html)
* [Vagrant](https://developer.hashicorp.com/vagrant/install) (opcional)

### Uso

```
git clone https://github.com/pgraffigna/ansible_role_nextcloud.git
cd ansible_role_nextcloud
ansible-playbook main.yml
```

### Extras
* Archivo de configuración (Vagrantfile) para desplegar una VM descartable con ubuntu-22.04 con libvirt como hipervisor.

### Uso Vagrant (opcional)
```
vagrant up
vagrant ssh
```
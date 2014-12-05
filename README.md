Demo for ["Rock validate"](https://github.com/romeOz/rock-validate)
====================

Used Vagrant + Ansible.

###Out of the box:

 * Ubuntu 14.04 64 bit

> If you need to use 32 bit of Ubuntu, then uncomment `config.vm.box_url` the appropriate version in the file [Vagrantfile](https://github.com/romeOz/vagrant-rock-validate/blob/master/Vagrantfile).

 * Nginx 1.6
 * PHP-FPM 5.6
 * Composer
 * Local IP loop on Host machine /etc/hosts and Virtual hosts in Nginx already set up!

See Demo (one of two ways)
-------------------

####1. Docker + Ansible

 * `docker run -d -p 8080:80 romeoz/vagrant-rock-validate`
 * Open demo [http://localhost:8080/](http://localhost:8080/)
 
####2. Vagrant + Ansible

 * `git clone https://github.com/romeOz/vagrant-rock-validate.git`
 * [Install Vagrant](https://www.vagrantup.com/downloads), and additional Vagrant plugins `vagrant plugin install vagrant-hostsupdater vagrant-vbguest vagrant-cachier`
 * `vagrant up`
 * Open demo [http://rock.validate/](http://rock.validate/) or [http://192.168.33.35/](http://192.168.33.35/)

> Work/editing the project can be done via ssh:

```bash
vagrant ssh
cd /var/www/rock-validate
```

Changelog "Rock validate"
-------------------
 * [Release 0.9.2](https://github.com/romeOz/rock-validate/releases/tag/0.9.2)
 * [Release 0.9.1](https://github.com/romeOz/rock-validate/releases/tag/0.9.1)
 * [Release 0.9.0](https://github.com/romeOz/rock-validate/releases/tag/0.9.0)
 
License
-------------------

The Demo for ["Rock validate"](https://github.com/romeOz/rock-validate) is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
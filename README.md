Basic FAQ
=========

How to install
* sudo aptitude install vagrant virtualenv
* git clone https://github.com/Endika/odoo_devel_environment.git
* virtualenv ansible
* sudo pip install ansible
* vagrant up

How to run Odoo service
* vagrant ssh
* sudo service odoo-service start
* http://192.168.0.12:8069

How to show Odoo log
* tail -f /opt/odoo/log/odoo-service.log

How to shutdown machine
* vagrant halt

How to destroy machine
* vagrant destroy

Master password: ```welcome```

;) Good Job

# TODO
* implement samba ansible
* implement nginx ansible


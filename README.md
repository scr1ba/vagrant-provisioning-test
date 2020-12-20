Vagrant box with ubuntu 20.04 provided by Ansible to test playbooks.

To use this all you need is Vagrant installed, as Ansible is installed within the virtual machine and the playbook is run locally.

Just run ``vagrant destroy -f && vagrant up --provider=X`` to destroy and recreate the virtual machine again.

By default, this repository directory will be shared at ``/vagrant``.
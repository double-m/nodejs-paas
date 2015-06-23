## Provision a Node.js service using Vagrant on VirtualBox and Ansible

### Pre-requisites

`vboxheadless`, `vagrant`, `ansible-playbook`

### Start the enviroment

```
$ vagrant up
```

### Useful commands

Connect to the provisioned box:

```
$ vagrant ssh # `ssh -p 2222 vagrant@127.0.0.1` with password "vagrant" in Vagrant 1.6
```

Check the Vagrant and VirtualBox files that aren't under version control:

```
$ ls -l ~/.vagrant.d/boxes|grep trusty64
```

### Documentation

[http://docs.vagrantup.com/v2/provisioning/ansible.html](http://docs.vagrantup.com/v2/provisioning/ansible.html)


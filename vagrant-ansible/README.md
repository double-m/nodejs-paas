## Provisioning of a Node.js service using Vagrant and Ansible

### 0. Pre-requisites

`vboxheadless`, `vagrant`, `ansible-playbook`

```
$ sudo apt-get install virtualbox vagrant ansible
```

### 1. Start the enviroment

```
$ git clone git@github.com:double-m/nodejs-paas.git
$ cd nodejs-paas/vagrant-ansible
$ vagrant up
```

### 2. Provision the PaaS

```
$ vagrant provision
```

### Useful commands

Connect to the provisioned box:

```
$ vagrant ssh # or `ssh -p 2222 vagrant@127.0.0.1` with password "vagrant" in Vagrant 1.6
```

Check the Vagrant and VirtualBox files that aren't under version control:

```
$ ls -l ~/.vagrant.d/boxes|grep trusty64
```

### Documentation

[http://docs.vagrantup.com/v2/provisioning/ansible.html](http://docs.vagrantup.com/v2/provisioning/ansible.html)


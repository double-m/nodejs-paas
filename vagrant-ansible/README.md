## Provision a Node.js service using Vagrant on VirtualBox and Ansible

### Start the enviroment

```
$ vagrant up
```

### Useful commands

Connect to the provisioned box:

```
$ ssh -p 2222 vagrant@127.0.0.1 # password: vagrant
```

Check the Vagrant and VirtualBox files that aren't under version control:

```
$ ls -l ~/.vagrant.d/boxes|grep trusty64
```


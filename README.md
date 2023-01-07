# Windows 2019 Vagrant

## Requirements

 - https://www.vagrantup.com/
 - https://github.com/dotless-de/vagrant-vbguest
 - https://www.virtualbox.org/

Install vbguest plugin
```
$ vagrant plugin install vagrant-vbguest
```

## Init

Start
```
$ vagrant up
```

Stop 

```
$ vagrant halt
```

### Install Steps

* Update Windows 2019
* Update Virtualbox Guest Additions
* Install Google Chrome (Chocolatey)
* Install GIT (Chocolatey)


### Extend trial period

```sh
slmgr -dlv
slmgr -rearm
Restart-Computer
slmgr -dli
```
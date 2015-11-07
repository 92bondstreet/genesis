# genesis

> Host server from 0

**Note: Root only**

## Vagrant

### Dependencies

* [Vagrant](https://www.vagrantup.com/downloads.html)
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

### Usage

```sh
❯ git clone https://github.com/92bondstreet/genesis-vagrant.git
❯ cd genesis-vagrant
❯ vagrant up
❯ vagrant ssh
# switch to root
# default root password is vagrant
❯ su
❯ wget --no-check-certificate https://raw.githubusercontent.com/92bondstreet/genesis-debian/master/genesis.sh
❯ chmod +x ./genesis.sh
❯ sh genesis.sh
```

Then open [http://localhost:8080](http://localhost:8080)


## Production

```sh
❯ wget --no-check-certificate https://raw.githubusercontent.com/92bondstreet/genesis-debian/master/genesis.sh
❯ chmod +x ./genesis.sh
❯ sh genesis.sh --production
```

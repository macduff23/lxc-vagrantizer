# lxc-vagrantize

This repository contains a set of scripts for creating base boxes for usage with
[vagrant-lxc](https://github.com/fgrehm/vagrant-lxc) 1.0+.

It is derived from https://github.com/fgrehm/vagrant-lxc-base-boxes. It is a rewrite in Python.

## What distros / versions can I build with this?

* Debian
  - Jessie, 8
  - Stretch, 9
* Ubuntu
  - 16.04
  - 18.10
* Fedora
  - 29

## Building the boxes

In order to build the boxes you need to have the `lxc` installed.

```sh
git clone https://github.com/godfryd/lxc-vagrantizer
cd lxc-vagrantizer
./lxc-vagrantizer build -s debian -r 8
```

## Pre built base boxes

| Distribution | VagrantCloud box |
| ------------ | ---------------- |
| Debian 8 Jessie | [godfryd/lxc-debian-8](https://vagrantcloud.com/godfryd/lxc-debian-8) |
| Debian 9 Stretch | [godfryd/lxc-debian-9](https://vagrantcloud.com/godfryd/lxc-debian-9) |
| Ubuntu 16.04 | [godfryd/lxc-ubuntu-16.04](https://vagrantcloud.com/godfryd/lxc-ubuntu-16.04) |
| Ubuntu 18.10 | [godfryd/lxc-ubuntu-18.10](https://vagrantcloud.com/godfryd/lxc-ubuntu-18.10) |
| Fedora 29 | [godfryd/lxc-fedora-29](https://vagrantcloud.com/godfryd/lxc-fedora-29) |


## What makes up for a vagrant-lxc base box?

See [vagrant-lxc/BOXES.md](https://github.com/fgrehm/vagrant-lxc/blob/master/BOXES.md)


## Known issues

TBD
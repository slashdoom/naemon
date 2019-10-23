---
title: Repository
weight: 10
disableToc: false
---

### Installing via Repository

Packages are available either using the openSUSE Build Service (below) or via the [Consol repository](http://labs.consol.de/repo/stable/).

#### Debian / Ubuntu

##### Install GPG key

First you import the GPG key.

```
curl -s "https://build.opensuse.org/projects/home:naemon/public_key" | sudo apt-key add -

```

##### Ubuntu

```
echo "deb http://download.opensuse.org/repositories/home:/naemon/xUbuntu_$(lsb_release -rs)/ ./" >> /etc/apt/sources.list.d/naemon-stable.list
apt-get update
```

##### Debian 9

```
echo "deb http://download.opensuse.org/repositories/home:/naemon/Debian_9.0/ ./" >> /etc/apt/sources.list.d/naemon-stable.list
apt-get update
```

##### Debian 8

```
echo "deb http://download.opensuse.org/repositories/home:/naemon/Debian_9.0/ ./" >> /etc/apt/sources.list.d/naemon-stable.list
apt-get update
```

#### Centos / Redhat

When using Centos or Redhat you may have to add the <a href="http://fedoraproject.org/wiki/EPEL/FAQ#Using_EPEL">EPEL</a> repository to resolve all dependencies.

##### 6

```
curl -s https://download.opensuse.org/repositories/home:/naemon/CentOS_6/home:naemon.repo >> /etc/yum.repos.d/naemon-stable.repo
```

##### 7

```
curl -s https://download.opensuse.org/repositories/home:/naemon/CentOS_7/home:naemon.repo >> /etc/yum.repos.d/naemon-stable.repo
```

#### Fedora

##### 27

```
curl -s https://download.opensuse.org/repositories/home:/naemon/Fedora_27/home:naemon.repo >> /etc/yum.repos.d/naemon-stable.repo
```

##### 28

```
curl -s https://download.opensuse.org/repositories/home:/naemon/Fedora_28/home:naemon.repo >> /etc/yum.repos.d/naemon-stable.repo
```

##### 29

```
curl -s https://download.opensuse.org/repositories/home:/naemon/Fedora_29/home:naemon.repo >> /etc/yum.repos.d/naemon-stable.repo
```

#### Suse Linux Enterprise

##### SLES 12 SP1

```
zypper addrepo -f https://download.opensuse.org/repositories/home:/naemon/SLE_12_SP1/home:naemon.repo
```

##### SLES 12 SP2

```
zypper addrepo -f https://download.opensuse.org/repositories/home:/naemon/SLE_12_SP2/home:naemon.repo
```

##### SLES 12 SP3

```
zypper addrepo -f https://download.opensuse.org/repositories/home:/naemon/SLE_12_SP3/home:naemon.repo
```

##### SLES 12 SP4

```
zypper addrepo -f https://download.opensuse.org/repositories/home:/naemon/SLE_12_SP4/home:naemon.repo
```

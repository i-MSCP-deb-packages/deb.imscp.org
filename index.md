---
layout: default
---
This is the [i-MSCP (internet Multi Server Control Panel)](https://i-mscp.net){:target="_blank"} home
for packaging of various softwares into Debian and Ubuntu GNU/Linux systems. The
packages are provided to fullfit i-MSCP softwares and plugins requirements.

Most important changes and news are published through our
[twitter](https://twitter.com/debimscporg) account.

### Packages for Debian/Devuan distributions

All our packages for Debian/Devuan distributions are made available through our
[Debian](https://deb.imscp.org/debian) APT repository.

#### Supported Debian distributions
- Jessie 8.x (amd64, i386)
- Stretch 9.x (amd64, i386)

#### Supported Devuan distributions

- Jessie 1.x (amd64, i386)
- ASCII 2.x (amd64, i386)

#### Repository setup

You can setup the APT repository as follows:
```shell
apt-get -y install apt-transport-https lsb-release ca-certificates
wget -O /etc/apt/trusted.gpg.d/imscp.gpg https://deb.imscp.org/debian/apt.gpg
sh -c 'echo "deb https://deb.imscp.org/debian/ $(lsb_release -sc) main" > /etc/apt/sources.list.d/imscp.list'
apt-get update
```

### Packages for Ubuntu distributions

All our packages for Ubuntu distributions are made available through our
[Ubuntu](https://deb.imscp.org/ubuntu) APT repository.

#### Supported Ubuntu distributions

- Trusty Thar 14.04 (amd64, i386)
- Xenial Xerus 16.04 (amd64, i386)
- Bionic Beaver 18.04 (adm64, i386)

Note that only LTS versions are supported by us.

#### Repository setup

You can setup the APT repository as follows:
```shell
sudo apt-get -y install apt-transport-https lsb-release ca-certificates
sudo wget -O /etc/apt/trusted.gpg.d/imscp.gpg https://deb.imscp.org/ubuntu/apt.gpg
sudo sh -c 'echo "deb https://deb.imscp.org/ubuntu/ $(lsb_release -sc) main" > /etc/apt/sources.list.d/imscp.list'
sudo apt-get update
```
### Bug Reporting

Please report any bug found in our packages by creating an issue in our [Bug Tracker](https://youtrack.i-mscp.net/){:target="_blank"}.

<div class="copyright">Copyright © 2010-2018 Laurent Declercq, i-MSCP™ | All Rights Reserved</div>

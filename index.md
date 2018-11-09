---
layout: default
---
This is the [i-MSCP (internet Multi Server Control Panel)](https://i-mscp.net){:target="_blank"} home
for packaging of various softwares into Debian and Ubuntu GNU/Linux systems. The
packages are provided to fullfit i-MSCP softwares and plugins requirements.

Most important changes and news are published through our
[twitter](https://twitter.com/debimscporg) account.

### Repository setup

You can setup our APT repository for your distribution as follows:

```shell
apt-get -y install apt-transport-https ca-certificates lsb-release wget
wget -O /etc/apt/trusted.gpg.d/imscp.gpg https://deb.imscp.org/imscp.gpg
sh -c 'echo "deb https://deb.imscp.org/$(lsb_release -si | tr '[:upper:]' '[:lower:]') $(lsb_release -sc) main" > /etc/apt/souces.list.d/imscp.list'
apt-get update
```

See below for more details about supported distribution and architectures.

### Packages for Debian/Devuan distributions

All our packages for Debian/Devuan distributions are made available through our
[Debian](https://deb.imscp.org/debian){:target="_blank"} APT repository.

#### Supported distributions

- Debian Jessie 8.x,
- Debian Stretch 9.x
- Devuan Jessie 1.x
- Devuan ASCII 2.x

Supported architectures: amd64, arm64, armhf, i386

### Packages for Ubuntu distributions

All our packages for Ubuntu distributions are made available through our
[Ubuntu](https://deb.imscp.org/ubuntu){:target="_blank"} APT repository.

#### Supported distributions

- Trusty Thar 14.04
- Xenial Xerus 16.04
- Bionic Beaver 18.04

Note that only LTS versions are supported by us.

Supported architectures: amd64, arm64, armhf, i386

### Bug Reporting

Please report any bug found in our packages by creating an issue in our [Bug Tracker](https://youtrack.i-mscp.net/){:target="_blank"}.

<div class="copyright">Copyright © 2010-2018 Laurent Declercq, i-MSCP™ | All Rights Reserved</div>

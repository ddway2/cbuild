[![Build Status](https://travis-ci.org/chybz/cbuild.svg?branch=master)](https://travis-ci.org/chybz/cbuild)

cbuild
======

## Install
### On Debian
Install dependencies
```
sudo apt-get install cmake \
    build-essential \
    debhelper \
    equivs \
    apt-file \
    tinycdb \
    pkg-config \
    rsync \
    git \
    lsb-release \
    lintian \
    sudo \
    apt-utils \
    g++ \
    make \
    binutils \
    autoconf \
    automake \
    autotools-dev \
    libtool \
    zlib1g-dev \
    devscripts \
    dh-autoreconf \
    dh-systemd
```
Install [cpkg system](https://github.com/ddway2/cpkg) 

Git clone project, build and install it !
```
git clone  https://github.com/ddway2/cbuild.git
cd cbuild
cpkg build
cpkg package -P
sudo dpkg -i *.deb
```
Let's Go

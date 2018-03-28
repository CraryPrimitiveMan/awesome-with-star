# Information comes from [moul/awesome-ssh](https://github.com/moul/awesome-ssh)
# Awesome SSH [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of *SSH* [apps](#apps), [libraries](#libraries) and [resources](#resources).

<h2 align="center"><img src="https://raw.githubusercontent.com/moul/awesome-ssh/master/logo.jpg" width="400" /></h2>

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

Please read the [contribution guidelines](CONTRIBUTING.md) if you want to contribute.

**Check out my [blog](http://manfredtouron.tumblr.com) 🦄 or say *hi* on [Twitter](https://twitter.com/moul).**

## Table of Contents

- [Apps](#apps)
  - [`.ssh/config`](#sshconfig)
  - [Tools using the *SSH* protocol](#tools-using-the-ssh-protocol)
  - [Servers](#servers)
  - [Network](#network)
  - [Multiplexers](#multiplexers)
  - [SSH Keys / Authentication](#ssh-keys--authentication)
  - [SSH agent](#ssh-agent)
  - [Tools](#tools)
  - [Automation](#automation)
  - [Web](#web)
  - [Testing / Honeypots](#testing--honeypots)
  - [Alternatives to SSH](#alternatives-to-ssh)
- [Libraries](#libraries)
- [Resources](#resources)
  - [Tutorials](#tutorials)
  - [Security](#security)
  - [Documentation](#documentation)
  - [Community](#community)

## Apps

### `.ssh/config`

* [`assh` a.k.a `advanced-ssh-config`](https://github.com/moul/advanced-ssh-config) [![stars](https://img.shields.io/github/stars/moul/advanced-ssh-config.svg?style=social&label=stars)](https://github.com/moul/advanced-ssh-config) - Transparent wrapper (ProxyCommand) that adds regex, aliases, gateways, includes, dynamic hostnames to *SSH* and `ssh-config`. :star:1064
* [storm](https://github.com/emre/storm) [![stars](https://img.shields.io/github/stars/emre/storm.svg?style=social&label=stars)](https://github.com/emre/storm) - Manage your *SSH* like a boss. :star:3138
* [ansible-ssh-config](https://github.com/gaqzi/ansible-ssh-config) [![stars](https://img.shields.io/github/stars/gaqzi/ansible-ssh-config.svg?style=social&label=stars)](https://github.com/gaqzi/ansible-ssh-config) - Letting *Ansible* manage `ssh_config`. :star:86
* [ec2ssh](https://github.com/mirakui/ec2ssh) [![stars](https://img.shields.io/github/stars/mirakui/ec2ssh.svg?style=social&label=stars)](https://github.com/mirakui/ec2ssh) - A `ssh_config` manager for *AWS EC2*. :star:203
* [ssh-config](https://github.com/dbrady/ssh-config) [![stars](https://img.shields.io/github/stars/dbrady/ssh-config.svg?style=social&label=stars)](https://github.com/dbrady/ssh-config) - A tool to help manage your `.ssh/config` file. :star:79

### Tools using the *SSH* protocol

* [scp](http://linux.die.net/man/1/scp) - Secure remote file copy utility over *SSH*.
* [rsync](https://rsync.samba.org) - Fast incremental transfer utility that supports *SSH*.
* [sftp](https://en.wikipedia.org/wiki/SSH_File_Transfer_Protocol) - File transfer protocol over *SSH*.
* [curl](http://curl.haxx.se) - Command line tool and library to transfer data (support `sftp`).

### Servers

* [ssh2docker](https://github.com/moul/ssh2docker) [![stars](https://img.shields.io/github/stars/moul/ssh2docker.svg?style=social&label=stars)](https://github.com/moul/ssh2docker) - *SSH* server to Docker containers. :star:114
* [whosthere](https://github.com/FiloSottile/whosthere) [![stars](https://img.shields.io/github/stars/FiloSottile/whosthere.svg?style=social&label=stars)](https://github.com/FiloSottile/whosthere) - A *SSH* server that knows who you are. `$ ssh whoami.filippo.io`. :star:1237
* [sshfront](https://github.com/gliderlabs/sshfront) [![stars](https://img.shields.io/github/stars/gliderlabs/sshfront.svg?style=social&label=stars)](https://github.com/gliderlabs/sshfront) - Programmable *SSH* frontend. :star:202
* [ssh-chat](https://github.com/shazow/ssh-chat) [![stars](https://img.shields.io/github/stars/shazow/ssh-chat.svg?style=social&label=stars)](https://github.com/shazow/ssh-chat) - Chat over *SSH*. :star:3002
* [sshcommand](https://github.com/dokku/sshcommand) [![stars](https://img.shields.io/github/stars/dokku/sshcommand.svg?style=social&label=stars)](https://github.com/dokku/sshcommand) - Turn *SSH* into a thin client specifically for your app. :star:294
* [sshmuxd](https://github.com/joushou/sshmuxd) [![stars](https://img.shields.io/github/stars/joushou/sshmuxd.svg?style=social&label=stars)](https://github.com/joushou/sshmuxd) - `sshmux` frontend. :star:721
* [x84](https://github.com/jquast/x84) [![stars](https://img.shields.io/github/stars/jquast/x84.svg?style=social&label=stars)](https://github.com/jquast/x84) - A *python* `telnet`/`ssh` server for modern *UTF-8* and classic *cp437* network virtual terminals. In spirit of classic software such as *ami/x*, *teleguard*, *renegade*, *iniquity*. :star:296
* [teleport](https://github.com/gravitational/teleport) [![stars](https://img.shields.io/github/stars/gravitational/teleport.svg?style=social&label=stars)](https://github.com/gravitational/teleport) - Modern *SSH* server for clusters and teams. :star:5816

### Network

* [Mosh](https://mosh.mit.edu) - The mobile shell.
* [sshfs](https://github.com/libfuse/sshfs) [![stars](https://img.shields.io/github/stars/libfuse/sshfs.svg?style=social&label=stars)](https://github.com/libfuse/sshfs) - Filesystem client based on the *SSH* File Transfer Protocol. :star:1397
* [ngrok](https://github.com/inconshreveable/ngrok) [![stars](https://img.shields.io/github/stars/inconshreveable/ngrok.svg?style=social&label=stars)](https://github.com/inconshreveable/ngrok) - Introspected tunnels to localhost. :star:12936
* [localtunnel](https://github.com/progrium/localtunnel) [![stars](https://img.shields.io/github/stars/progrium/localtunnel.svg?style=social&label=stars)](https://github.com/progrium/localtunnel) - Expose localhost servers to the Internet. :star:3023
* [sshuttle](https://github.com/apenwarr/sshuttle) [![stars](https://img.shields.io/github/stars/apenwarr/sshuttle.svg?style=social&label=stars)](https://github.com/apenwarr/sshuttle) - Transparent proxy server that works as a poor man's *VPN*. Forwards over `ssh`. Doesn't require admin. Works with *Linux* and *MacOS*. Supports *DNS tunneling*. :star:9014
* [sshttp](https://github.com/stealth/sshttp) [![stars](https://img.shields.io/github/stars/stealth/sshttp.svg?style=social&label=stars)](https://github.com/stealth/sshttp) - *SSH*/*HTTP(S)* multiplexer. Run a webserver and a `sshd` on the same port w/o changes. :star:609
* [switcher](https://github.com/jamescun/switcher) [![stars](https://img.shields.io/github/stars/jamescun/switcher.svg?style=social&label=stars)](https://github.com/jamescun/switcher) - Run *SSH* and *HTTP(S)* on the same port. :star:810
* [sslh](https://github.com/yrutschle/sslh) [![stars](https://img.shields.io/github/stars/yrutschle/sslh.svg?style=social&label=stars)](https://github.com/yrutschle/sslh) - Applicative Protocol Multiplexer (i.e: *SSH* + *HTTPS*). :star:1583
* [tund](https://github.com/aphyr/tund) [![stars](https://img.shields.io/github/stars/aphyr/tund.svg?style=social&label=stars)](https://github.com/aphyr/tund) - *SSH* reverse tunnel daemon. :star:352
* [autossh](http://www.harding.motd.ca/autossh/) - Automatically respawn *SSH* session after network interruption.
* [wssh](https://github.com/aluzzardi/wssh) [![stars](https://img.shields.io/github/stars/aluzzardi/wssh.svg?style=social&label=stars)](https://github.com/aluzzardi/wssh) - *SSH* to WebSockets Bridge. :star:1092
* [docker-volume-sshfs](https://github.com/vieux/docker-volume-sshfs) [![stars](https://img.shields.io/github/stars/vieux/docker-volume-sshfs.svg?style=s

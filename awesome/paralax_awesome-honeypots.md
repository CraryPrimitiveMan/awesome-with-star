# Info come from [paralax/awesome-honeypots](https://github.com/paralax/awesome-honeypots)
# Awesome Honeypots  

[![Awesome Honeypots](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome honeypots, tools, components and much more. The list is divided into categories such as web, services, and others, focusing on open source projects.

There is no pre-established order of items in each category, the order is for contribution. If you want to contribute, please read the [guide](CONTRIBUTING.md).

Discover more awesome lists at [sindresorhus/awesome](https://github.com/sindresorhus/awesome).

### Sections

- [Honeypots](#honeypots)
- [Honeyd Tools](#honeyd)
- [Network and Artifact Analysis](#analysis)
- [Data Tools](#visualizers)
- [Guides](#guides)

## Related Lists
- [awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools), useful in network traffic analysis.
- [awesome-malware-analysis](https://github.com/rshipp/awesome-malware-analysis), with some overlap here for artifact analysis.

## <a name="honeypots"></a> Honeypots

- Database Honeypots
    - [MongoDB-HoneyProxy](https://github.com/Plazmaz/MongoDB-HoneyProxy) - A MongoDB honeypot proxy. :star:52
    - [Elastic honey](https://github.com/jordan-wright/elastichoney) - A Simple Elasticsearch Honeypot. :star:102
    - [mysql](https://github.com/schmalle/MysqlPot) - A mysql honeypot, still very very early stage. :star:13
    - [NoSQLpot](https://github.com/torque59/nosqlpot) - The NoSQL Honeypot Framework. :star:86
    - [ESPot](https://github.com/mycert/ESPot) - An Elasticsearch honeypot written in NodeJS, to capture every attempts to exploit CVE-2014-3120. :star:10
    - [Delilah](https://github.com/Novetta/delilah) - An Elasticsearch Honeypot written in Python. :star:28
    - [mysql-honeypotd](https://github.com/sjinks/mysql-honeypotd) - Low interaction MySQL honeypot written in C. :star:3

- Web honeypots
    - [Glastopf](https://github.com/mushorg/glastopf) - Web Application Honeypot. :star:313
    - Snare/Tanner - successors to Glastopf
      - [Snare](https://github.com/mushorg/snare) - Super Next generation Advanced Reactive honEypot :star:71
      - [Tanner](https://github.com/mushorg/tanner) - Evaluating SNARE events :star:41
    - [phpmyadmin_honeypot](https://github.com/gfoss/phpmyadmin_honeypot) - - A simple and effective phpMyAdmin honeypot. :star:37
    - [Nodepot](https://github.com/schmalle/Nodepot)  - A nodejs web application honeypot.
    - [basic-auth-pot](https://github.com/bjeborn/basic-auth-pot) bap - http Basic Authentication honeyPot.
    - [Shadow Daemon](https://shadowd.zecure.org/overview/introduction/) - A modular Web Application Firewall / High-Interaction Honeypot for PHP, Perl & Python apps.
    - [Servletpot](https://github.com/schmalle/servletpot) - Web application Honeypot. :star:7
    - [Google Hack Honeypot](http://ghh.sourceforge.net) - designed to provide reconnaissance against attackers that use search engines as a hacking tool against your resources.
    - [smart-honeypot](https://github.com/freak3dot/smart-honeypot) - PHP Script demonstrating a smart honey pot. :star:11
    - [Bukkit Honeypot](https://github.com/Argomirr/Honeypot) Honeypot - A honeypot plugin for Bukkit.
    - [Laravel Application Honeypot](https://github.com/msurguy/Honeypot) - Honeypot - Simple spam prevention package for Laravel applications. :star:300
    - [stack-honeypot](https://github.com/CHH/stack-honeypot) - Inserts a trap for spam bots into responses. :star:17
    - [EoHoneypotBundle](https://github.com/eymengunay/EoHoneypotBundle) - Honeypot type for Symfony2 forms. :star:22
    - [shockpot](https://github.com/threatstream/shockpot) - WebApp Honeypot for detecting Shell Shock exploit attempts. :star:40
    - [django-admin-honeypot](https://github.com/dmpayton/django-admin-honeypot) - A fake Django admin login screen to notify admins of attempted unauthorized access.  :star:414
    - [WebTrap](https://github.com/IllusiveNetworks-Labs/WebTrap) - Designed to create deceptive webpages to deceive and redirect attackers away from real websites. :star:3
    - WordPress honeypots
        - [HonnyPotter](https://github.com/MartinIngesen/HonnyPotter) - A WordPress login honeypot for collection and analysis of failed login attempts. :star:19
        - [HoneyPress](https://github.com/dustyfresh/HoneyPress) - python based WordPress honeypot in a docker container. :star:52
        - [wp-smart-honeypot](https://github.com/freak3dot/wp-smart-honeypot) - WordPress plugin to reduce comment spam with a smarter honeypot. :star:16
        - [wordpot](https://github.com/gbrindisi/wordpot) - A WordPress Honeypot. :star:111

- Service Honeypots
    - [honeyntp](https://github.com/fygrave/honeyntp) - NTP logger/honeypot. :star:36
    - [honeypot-camera](https://github.com/alexbredo/honeypot-camera) - observation camera honeypot. :star:32
    - [troje](https://github.com/dutchcoders/troje/) - a honeypot built around lxc containers. It will run each connection with the service within a seperate lxc container.
    - [HoneyPy](https://github.com/foospidy/HoneyPy) - A low interaction honeypot. :star:268
    - [Ensnare](https://github.com/ahoernecke/ensnare) - Easy to deploy Ruby honeypot. :star:67
    - [RDPy](https://github.com/citronneur/rdpy) - A Microsoft Remote Desktop Protocol (RDP) honeypot in python. :star:720
    - [Honeyprint](https://github.com/glaslos/honeyprint) - Printer honeypot. :star:8
    - [Tom's Honeypot](https://github.com/inguardians/toms_honeypot) - Low interaction Python honeypot. :star:9
    - [Honeyport](https://github.com/securitygeneration/Honeyport) - A simple honeyport written in Bash and Python. :star:19
    - [AMTHoneypot](https://github.com/packetflare/amthoneypot) - Honeypot for Intel's AMT Firmware Vulnerability CVE-2017-5689. :star:5
    - [Lyrebird](https://hub.docker.com/r/lyrebird/honeypot-base/) - A modern high-interaction honeypot framework.

- Distributed Honeypots
    - [DemonHunter](https://github.com/RevengeComing/DemonHunter) - Low interaction Honepot Server. :star:13

- Anti-honeypot stuff
    - [kippo_detect](https://github.com/andrew-morris/kippo_detect) - This is not a honeypot, but it detects kippo. (This guy has lots of more interesting stuff)

- ICS/SCADA honeypots
    - [Conpot](https://github.com/mushorg/conpot) - ICS/SCADA honeypot. :star:390
    - [gridpot](https://github.com/sk4ld/gridpot) - Open source tools for realistic-behaving electric grid honeynets . :star:28
    - [scada-honeynet](http://www.digitalbond.com/blog/2007/07/24/scada-honeynet-article-in-infragard-publication/) - mimics many of the services from a popular PLC and better helps SCADA researchers understand potential risks of exposed control system devices.
    - [SCADA honeynet](http://scadahoneynet.sourceforge.net) - Building Honeypots for Industrial Networks.
    - [GasPot](https://github.com/sjhilt/GasPot) - Veeder Root Gaurdian AST, common in the oil and gas industry. :star:53

- Other/random
    - [NOVA](https://github.com/DataSoft/Nova) uses honeypots as detectors, looks like a complete system.
    - [Open Canary](https://pypi.python.org/pypi/opencanary) - A low interaction honeypot intended to be run on internal networks.
    - [OFPot](https://github.com/upa/ofpot) - OpenFlow Honeypot, redirects traffic for unused IPs to a honeypot. Built on POX. :star:6
    - [OpenCanary](https://github.com/thinkst/opencanary) - Modular and decentralised honeypot. :star:273
    - [DSHP](https://github.com/naorlivne/dshp) - Damn Simple HoneyPot with pluggable handlers. :star:2

- Botnet C2 tools
    - [Hale](https://github.com/pjlantz/Hale) - Botnet command &amp; control monitor. :star:88
    - [dnsMole](https://code.google.com/archive/p/dns-mole/) -  analyse dn

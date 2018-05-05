# Information comes from [paralax/awesome-honeypots](https://github.com/paralax/awesome-honeypots)
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
    - [MongoDB-HoneyProxy](https://github.com/Plazmaz/MongoDB-HoneyProxy) - A MongoDB honeypot proxy. :star:53
    - [Elastic honey](https://github.com/jordan-wright/elastichoney) - A Simple Elasticsearch Honeypot. :star:108
    - [mysql](https://github.com/schmalle/MysqlPot) - A mysql honeypot, still very very early stage. :star:12
    - [NoSQLpot](https://github.com/torque59/nosqlpot) - The NoSQL Honeypot Framework. :star:86
    - [ESPot](https://github.com/mycert/ESPot) - An Elasticsearch honeypot written in NodeJS, to capture every attempts to exploit CVE-2014-3120. :star:11
    - [Delilah](https://github.com/Novetta/delilah) - An Elasticsearch Honeypot written in Python. :star:29
    - [mysql-honeypotd](https://github.com/sjinks/mysql-honeypotd) - Low interaction MySQL honeypot written in C. :star:3

- Web honeypots
    - [Glastopf](https://github.com/mushorg/glastopf) - Web Application Honeypot. :star:328
    - Snare/Tanner - successors to Glastopf
      - [Snare](https://github.com/mushorg/snare) - Super Next generation Advanced Reactive honEypot :star:86
      - [Tanner](https://github.com/mushorg/tanner) - Evaluating SNARE events :star:52
    - [phpmyadmin_honeypot](https://github.com/gfoss/phpmyadmin_honeypot) - - A simple and effective phpMyAdmin honeypot. :star:44
    - [Nodepot](https://github.com/schmalle/Nodepot)  - A nodejs web application honeypot.
    - [basic-auth-pot](https://github.com/bjeborn/basic-auth-pot) bap - http Basic Authentication honeyPot.
    - [Shadow Daemon](https://shadowd.zecure.org/overview/introduction/) - A modular Web Application Firewall / High-Interaction Honeypot for PHP, Perl & Python apps.
    - [Servletpot](https://github.com/schmalle/servletpot) - Web application Honeypot. :star:7
    - [Google Hack Honeypot](http://ghh.sourceforge.net) - designed to provide reconnaissance against attackers that use search engines as a hacking tool against your resources.
    - [smart-honeypot](https://github.com/freak3dot/smart-honeypot) - PHP Script demonstrating a smart honey pot. :star:11
    - [Bukkit Honeypot](https://github.com/Argomirr/Honeypot) Honeypot - A honeypot plugin for Bukkit.
    - [Laravel Application Honeypot](https://github.com/msurguy/Honeypot) - Honeypot - Simple spam prevention package for Laravel applications. :star:315
    - [stack-honeypot](https://github.com/CHH/stack-honeypot) - Inserts a trap for spam bots into responses. :star:17
    - [EoHoneypotBundle](https://github.com/eymengunay/EoHoneypotBundle) - Honeypot type for Symfony2 forms. :star:22
    - [shockpot](https://github.com/threatstream/shockpot) - WebApp Honeypot for detecting Shell Shock exploit attempts. :star:42
    - [django-admin-honeypot](https://github.com/dmpayton/django-admin-honeypot) - A fake Django admin login screen to notify admins of attempted unauthorized access.  :star:447
    - [WebTrap](https://github.com/IllusiveNetworks-Labs/WebTrap) - Designed to create deceptive webpages to deceive and redirect attackers away from real websites. :star:20
    - WordPress honeypots
        - [HonnyPotter](https://github.com/MartinIngesen/HonnyPotter) - A WordPress login honeypot for collection and analysis of failed login attempts. :star:19
        - [HoneyPress](https://github.com/dustyfresh/HoneyPress) - python based WordPress honeypot in a docker container. :star:53
        - [wp-smart-honeypot](https://github.com/freak3dot/wp-smart-honeypot) - WordPress plugin to reduce comment spam with a smarter honeypot. :star:17
        - [wordpot](https://github.com/gbrindisi/wordpot) - A WordPress Honeypot. :star:111
    - [honeyhttpd](https://github.com/bocajspear1/honeyhttpd) - a Python-based web server honeypot builder. :star:1

- Service Honeypots
    - [honeyntp](https://github.com/fygrave/honeyntp) - NTP logger/honeypot. :star:36
    - [honeypot-camera](https://github.com/alexbredo/honeypot-camera) - observation camera honeypot. :star:35
    - [troje](https://github.com/dutchcoders/troje/) - a honeypot built around lxc containers. It will run each connection with the service within a seperate lxc container.
    - [HoneyPy](https://github.com/foospidy/HoneyPy) - A low interaction honeypot. :star:283
    - [Ensnare](https://github.com/ahoernecke/ensnare) - Easy to deploy Ruby honeypot. :star:67
    - [RDPy](https://github.com/citronneur/rdpy) - A Microsoft Remote Desktop Protocol (RDP) honeypot in python. :star:827
    - [Honeyprint](https://github.com/glaslos/honeyprint) - Printer honeypot. :star:10
    - [Tom's Honeypot](https://github.com/inguardians/toms_honeypot) - Low interaction Python honeypot. :star:11
    - [Honeyport](https://github.com/securitygeneration/Honeyport) - A simple honeyport written in Bash and Python. :star:20
    - [AMTHoneypot](https://github.com/packetflare/amthoneypot) - Honeypot for Intel's AMT Firmware Vulnerability CVE-2017-5689. :star:6
    - [Lyrebird](https://hub.docker.com/r/lyrebird/honeypot-base/) - A modern high-interaction honeypot framework.
    - [Honeygrove](https://github.com/UHH-ISS/honeygrove) - A multi-purpose modular honeypot based on Twisted. :star:1
    - [WebLogic honeypot](https://github.com/Cymmetria/weblogic_honeypot) - low interaction honeypot to detect CVE-2017-10271 in the Oracle WebLogic Server component of Oracle Fusion Middleware. :star:8
    - [MICROS honeypot](https://github.com/Cymmetria/micros_honeypot) -  low interaction honeypot to detect CVE-2018-2636 in the Oracle Hospitality Simphony component of Oracle Hospitality Applications (MICROS). :star:6
    - [honeytrap](https://github.com/honeytrap/honeytrap) - Advanced Honeypot framework written in Go. Can be connected up with other Honeypot software. :star:372
    - [SMB Honeypot](https://github.com/r0hi7/HoneySMB) -  High interaction SMB service Honeypot capable of capturing wannacry like Malware. :star:3

- Distributed Honeypots
    - [DemonHunter](https://github.com/RevengeComing/DemonHunter) - Low interaction Honepot Server. :star:15

- Anti-honeypot stuff
    - [kippo_detect](https://github.com/andrew-morris/kippo_detect) - This is not a honeypot, but it detects kippo. (This guy has lots of more interesting stuff)

- ICS/SCADA honeypots
    - [Conpot](https://github.com/mushorg/conpot) - ICS/SCADA honeypot. :star:429
    - [gridpot](https://github.com/sk4ld/gridpot) - Open source tools for realistic-behaving electric grid honeynets . :star:28
    - [scada-honeynet](http://www.digitalbond.com/blog/2007/07/24/scada-honeynet-article-in-infragard-publication/) - mimics many of the services from a popular PLC and better helps SCADA researchers understand potential risks of exposed control system devices.
    - [SCADA honeynet](http://scadahoneynet.sourceforge.net) - Building Honeypots for Industrial Networks.
    - [GasPot](https://github.com/sjhilt/GasPot) - Veeder Root Gaurdian AST, common in the oil and gas industry. :star:55

- Other/random
    - [NOVA](https://github.com/DataSoft/Nova) uses honeypots as detectors, looks like a complete system.
    - [Open Canary](https://pypi.org/project/opencanary/) - A low interaction honeypot intended to be run on internal networks.
    - [OFPot](https://github.com/upa/ofpot) - OpenFlow Honeypot, redirects traffic for unused IPs to a honeypot. Built on POX. :star:7
    - [OpenCanary](https://github.com/thinkst/opencanary) - Modular and decentralised honeypot. :star:308
    - [DSHP](https://github.com/naorlivne/dshp) - Damn Simple HoneyPot with pluggable handlers. :star:2

- Botnet C2 tools
    - [Hale](https://github.com/pjlantz/Hale) - Botnet command &amp; control monitor. :star:97
    - [dnsMole](https://code.google.com/archive/p/dns-mole/) -  analyse dns traffic, and to potentionaly detect botnet C&C server and infected hosts.

- IPv6 attack detection tool
    - [ipv6-attack-detector](https://github.com/mzweilin/ipv6-attack-detector/)  - Google Summer of Code 2012 project, supported by The Honeynet Project organization.

- Dynamic code instrumentation toolkit
    - [Frida](https://www.frida.re) - Inject JavaScript to explore native apps on Windows, Mac, Linux, iOS and Android.

- Tool to convert website to server honeypots
    - [HIHAT](http://hihat.sourceforge.net/) - Transform arbitrary PHP applications into web-based high-interaction Honeypots.

- Malware collector
    - [Kippo-Malware](http://bruteforcelab.com/kippo-malware) - Python script that will download all malicious files stored as URLs in a Kippo SSH honeypot database.

- Distributed sensor deployment
    - [Smarthoneypot](https://smarthoneypot.com/) - custom honeypot intelligence system that is simple to deploy and easy to manage.
    - [Modern Honey Network](https://github.com/threatstream/mhn) - Multi-snort and honeypot sensor management, uses a network of VMs, small footprint SNORT installations, stealthy dionaeas, and a centralized server for management. :star:1422
    - [ADHD](https://sourceforge.net/projects/adhd/) -  Active Defense Harbinger Distribution (ADHD) is a Linux distro based on Ubuntu LTS. It comes with many tools aimed at active defense preinstalled and configured.

- Network Analysis Tool
    - [Tracexploit](https://code.google.com/archive/p/tracexploit/) - replay network packets.

- Log anonymizer
    - [LogAnon](http://code.google.com/archive/p/loganon/) - log anonymization library that helps having anonymous logs consistent between logs and network captures.

- Low interaction honeypot (router back door)
    - [Honeypot-32764](https://github.com/knalli/honeypot-for-tcp-32764) - Honeypot for router backdoor (TCP 32764). :star:8

- honeynet farm traffic redirector
    - [Honeymole](https://web.archive.org/web/20120122130150/http://www.honeynet.org.pt/index.php/HoneyMole) - eploy multiple sensors that redirect traffic to a centralized collection of honeypots.

- HTTPS Proxy
    - [mitmproxy](https://mitmproxy.org/) - allows traffic flows to be intercepted, inspected, modified and replayed.

- System instrumentation
    - [Sysdig](https://sysdig.com/opensource/) - open source, system-level exploration: capture system state and activity from a running Linux instance, then save, filter and analyze.
    - [Fibratus](https://github.com/rabbitstack/fibratus) - tool for exploration and tracing of the Windows kernel. :star:410

- Honeypot for USB-spreading malware
    - [Ghost-usb](https://github.com/honeynet/ghost-usb-honeypot) -  honeypot for malware that propagates via USB storage devices. :star:49
    - [Honeystick](http://www.ukhoneynet.org/research/honeystick-howto/)  - low interaction honeypot on USB stick

- Data Collection
    - [Kippo2MySQL](http://bruteforcelab.com/kippo2mysql) -  extracts some very basic stats from Kippo’s text-based log files (a mess to analyze!) and inserts them in a MySQL database.
    - [Kippo2ElasticSearch](http://bruteforcelab.com/kippo2elasticsearch) - Python script to transfer data from a Kippo SSH honeypot MySQL database to an ElasticSearch instance (server or cluster).

- Passive network audit framework parser
    - [pnaf](https://github.com/jusafing/pnaf) - Passive Network Audit Framework. :star:15

- VM monitoring and tools
    - [vmscope](https://cs.gmu.edu/~xwangc/Publications/RAID07-VMscope.pdf) - Monitoring of VM-based.
    - [vmitools](http://libvmi.com/) - C library with Python bindings that makes it easy to monitor the low-level details of a running virtual machine.
    - [Antivmdetect](https://github.com/nsmfoo/antivmdetection) - Script to create templates to use with VirtualBox to make vm detection harder. :star:253
    - [VMCloak](https://github.com/jbremer/vmcloak) - Automated Virtual Machine Generation and Cloaking for Cuckoo Sandbox. :star:235

- Binary debugger
    - [Hexgolems - Schem Debugger Frontend](https://github.com/hexgolems/schem) - A debugger frontend. :star:143
    - [Hexgolems - Pint Debugger Backend](https://github.com/hexgolems/pint) - A debugger backend and LUA wrapper for PIN. :star:28

- Mobile Analysis Tool
    - [APKinspector](https://github.com/honeynet/apkinspector/) - APKinspector is a powerful GUI tool for analysts to analyze the Android applications.
    - [Androguard](https://github.com/androguard/androguard) - Reverse engineering, Malware and goodware analysis of Android applications ... and more. :star:1950

- Low interaction honeypot
    - [Honeyperl](https://sourceforge.net/projects/honeyperl/) - Honeypot software based in Perl with plugins developed for many functions like : wingates, telnet, squid, smtp, etc.

- Honeynet data fusion
    - [HFlow2](https://projects.honeynet.org/hflow) -  data coalesing tool for honeynet/network analysis.

- Server
    - [LaBrea](http://labrea.sourceforge.net/labrea-info.html) - takes over unused IP addresses, and creates virtual servers that are attractive to worms, hackers, and other denizens of the Internet.
    - [Honeysink](http://www.honeynet.org/node/773) - open source network sinkhole that provides a mechanism for detection and prevention of malicious traffic on a given network.
    - [KFSensor](http://www.keyfocus.net/kfsensor/) - Windows based honeypot Intrusion Detection System (IDS).
    - [Honeyd](https://github.com/provos/honeyd) Also see [more honeyd tools](#honeyd).
    - [UDPot Honeypot](https://github.com/jekil/UDPot) - Simple UDP / DNS honeypot scripts. :star:25
    - [Conpot](http://conpot.org/) - ow interactive server side Industrial Control Systems honeypot.
    - [Bifrozt](https://github.com/Ziemeck/bifrozt-ansible) - Automatic deploy bifrozt with ansible. :star:3
    - [Bait and Switch](http://baitnswitch.sourceforge.net) - redirects all hostile traffic to a honeypot that is partially mirroring your production system.
    - [Artillery](https://github.com/trustedsec/artillery/) - open-source blue team tool designed to protect Linux and Windows operating systems through multiple methods.
    - [slipm-honeypot](https://github.com/rshipp/slipm-honeypot) - A simple low-interaction port monitoring honeypot. :star:6
    - [HoneyWRT](https://github.com/CanadianJeff/honeywrt) - low interaction Python honeypot designed to mimic services or ports that might get targeted by attackers. :star:12
    - [Amun](http://amunhoney.sourceforge.net) - vulnerability emulation honeypot.
    - [TelnetHoney](https://github.com/AnguisCaptor/TelnetHoney) - A simple telnet honeypot. :star:4
    - [Hontel](https://github.com/stamparm/hontel) - Telnet Honeypot. :star:86

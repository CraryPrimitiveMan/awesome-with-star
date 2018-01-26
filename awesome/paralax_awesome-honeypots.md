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
    - [MongoDB-HoneyProxy](https://github.com/Plazmaz/MongoDB-HoneyProxy) - A MongoDB honeypot proxy. :star:52
    - [Elastic honey](https://github.com/jordan-wright/elastichoney) - A Simple Elasticsearch Honeypot. :star:102
    - [mysql](https://github.com/schmalle/MysqlPot) - A mysql honeypot, still very very early stage. :star:12
    - [NoSQLpot](https://github.com/torque59/nosqlpot) - The NoSQL Honeypot Framework. :star:86
    - [ESPot](https://github.com/mycert/ESPot) - An Elasticsearch honeypot written in NodeJS, to capture every attempts to exploit CVE-2014-3120. :star:10
    - [Delilah](https://github.com/Novetta/delilah) - An Elasticsearch Honeypot written in Python. :star:28
    - [mysql-honeypotd](https://github.com/sjinks/mysql-honeypotd) - Low interaction MySQL honeypot written in C. :star:3

- Web honeypots
    - [Glastopf](https://github.com/mushorg/glastopf) - Web Application Honeypot. :star:314
    - Snare/Tanner - successors to Glastopf
      - [Snare](https://github.com/mushorg/snare) - Super Next generation Advanced Reactive honEypot :star:73
      - [Tanner](https://github.com/mushorg/tanner) - Evaluating SNARE events :star:42
    - [phpmyadmin_honeypot](https://github.com/gfoss/phpmyadmin_honeypot) - - A simple and effective phpMyAdmin honeypot. :star:37
    - [Nodepot](https://github.com/schmalle/Nodepot)  - A nodejs web application honeypot.
    - [basic-auth-pot](https://github.com/bjeborn/basic-auth-pot) bap - http Basic Authentication honeyPot.
    - [Shadow Daemon](https://shadowd.zecure.org/overview/introduction/) - A modular Web Application Firewall / High-Interaction Honeypot for PHP, Perl & Python apps.
    - [Servletpot](https://github.com/schmalle/servletpot) - Web application Honeypot. :star:7
    - [Google Hack Honeypot](http://ghh.sourceforge.net) - designed to provide reconnaissance against attackers that use search engines as a hacking tool against your resources.
    - [smart-honeypot](https://github.com/freak3dot/smart-honeypot) - PHP Script demonstrating a smart honey pot. :star:11
    - [Bukkit Honeypot](https://github.com/Argomirr/Honeypot) Honeypot - A honeypot plugin for Bukkit.
    - [Laravel Application Honeypot](https://github.com/msurguy/Honeypot) - Honeypot - Simple spam prevention package for Laravel applications. :star:301
    - [stack-honeypot](https://github.com/CHH/stack-honeypot) - Inserts a trap for spam bots into responses. :star:17
    - [EoHoneypotBundle](https://github.com/eymengunay/EoHoneypotBundle) - Honeypot type for Symfony2 forms. :star:22
    - [shockpot](https://github.com/threatstream/shockpot) - WebApp Honeypot for detecting Shell Shock exploit attempts. :star:41
    - [django-admin-honeypot](https://github.com/dmpayton/django-admin-honeypot) - A fake Django admin login screen to notify admins of attempted unauthorized access.  :star:415
    - [WebTrap](https://github.com/IllusiveNetworks-Labs/WebTrap) - Designed to create deceptive webpages to deceive and redirect attackers away from real websites. :star:16
    - WordPress honeypots
        - [HonnyPotter](https://github.com/MartinIngesen/HonnyPotter) - A WordPress login honeypot for collection and analysis of failed login attempts. :star:19
        - [HoneyPress](https://github.com/dustyfresh/HoneyPress) - python based WordPress honeypot in a docker container. :star:51
        - [wp-smart-honeypot](https://github.com/freak3dot/wp-smart-honeypot) - WordPress plugin to reduce comment spam with a smarter honeypot. :star:17
        - [wordpot](https://github.com/gbrindisi/wordpot) - A WordPress Honeypot. :star:111
    - [honeyhttpd](https://github.com/bocajspear1/honeyhttpd) - a Python-based web server honeypot builder. :star:1

- Service Honeypots
    - [honeyntp](https://github.com/fygrave/honeyntp) - NTP logger/honeypot. :star:36
    - [honeypot-camera](https://github.com/alexbredo/honeypot-camera) - observation camera honeypot. :star:32
    - [troje](https://github.com/dutchcoders/troje/) - a honeypot built around lxc containers. It will run each connection with the service within a seperate lxc container.
    - [HoneyPy](https://github.com/foospidy/HoneyPy) - A low interaction honeypot. :star:268
    - [Ensnare](https://github.com/ahoernecke/ensnare) - Easy to deploy Ruby honeypot. :star:67
    - [RDPy](https://github.com/citronneur/rdpy) - A Microsoft Remote Desktop Protocol (RDP) honeypot in python. :star:725
    - [Honeyprint](https://github.com/glaslos/honeyprint) - Printer honeypot. :star:8
    - [Tom's Honeypot](https://github.com/inguardians/toms_honeypot) - Low interaction Python honeypot. :star:9
    - [Honeyport](https://github.com/securitygeneration/Honeyport) - A simple honeyport written in Bash and Python. :star:19
    - [AMTHoneypot](https://github.com/packetflare/amthoneypot) - Honeypot for Intel's AMT Firmware Vulnerability CVE-2017-5689. :star:5
    - [Lyrebird](https://hub.docker.com/r/lyrebird/honeypot-base/) - A modern high-interaction honeypot framework.
    - [Honeygrove](https://github.com/UHH-ISS/honeygrove) - A multi-purpose modular honeypot based on Twisted.

- Distributed Honeypots
    - [DemonHunter](https://github.com/RevengeComing/DemonHunter) - Low interaction Honepot Server. :star:13

- Anti-honeypot stuff
    - [kippo_detect](https://github.com/andrew-morris/kippo_detect) - This is not a honeypot, but it detects kippo. (This guy has lots of more interesting stuff)

- ICS/SCADA honeypots
    - [Conpot](https://github.com/mushorg/conpot) - ICS/SCADA honeypot. :star:397
    - [gridpot](https://github.com/sk4ld/gridpot) - Open source tools for realistic-behaving electric grid honeynets . :star:28
    - [scada-honeynet](http://www.digitalbond.com/blog/2007/07/24/scada-honeynet-article-in-infragard-publication/) - mimics many of the services from a popular PLC and better helps SCADA researchers understand potential risks of exposed control system devices.
    - [SCADA honeynet](http://scadahoneynet.sourceforge.net) - Building Honeypots for Industrial Networks.
    - [GasPot](https://github.com/sjhilt/GasPot) - Veeder Root Gaurdian AST, common in the oil and gas industry. :star:54

- Other/random
    - [NOVA](https://github.com/DataSoft/Nova) uses honeypots as detectors, looks like a complete system.
    - [Open Canary](https://pypi.python.org/pypi/opencanary) - A low interaction honeypot intended to be run on internal networks.
    - [OFPot](https://github.com/upa/ofpot) - OpenFlow Honeypot, redirects traffic for unused IPs to a honeypot. Built on POX. :star:6
    - [OpenCanary](https://github.com/thinkst/opencanary) - Modular and decentralised honeypot. :star:278
    - [DSHP](https://github.com/naorlivne/dshp) - Damn Simple HoneyPot with pluggable handlers. :star:2

- Botnet C2 tools
    - [Hale](https://github.com/pjlantz/Hale) - Botnet command &amp; control monitor. :star:88
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
    - [Modern Honey Network](https://github.com/threatstream/mhn) - Multi-snort and honeypot sensor management, uses a network of VMs, small footprint SNORT installations, stealthy dionaeas, and a centralized server for management. :star:1337
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
    - [Sysdig](https://www.sysdig.org) - open source, system-level exploration: capture system state and activity from a running Linux instance, then save, filter and analyze.
    - [Fibratus](https://github.com/rabbitstack/fibratus) - tool for exploration and tracing of the Windows kernel. :star:401

- Honeypot for USB-spreading malware
    - [Ghost-usb](https://github.com/honeynet/ghost-usb-honeypot) -  honeypot for malware that propagates via USB storage devices. :star:46
    - [Honeystick](http://www.ukhoneynet.org/research/honeystick-howto/)  - low interaction honeypot on USB stick

- Data Collection
    - [Kippo2MySQL](http://bruteforcelab.com/kippo2mysql) -  extracts some very basic stats from Kippo’s text-based log files (a mess to analyze!) and inserts them in a MySQL database.
    - [Kippo2ElasticSearch](http://bruteforcelab.com/kippo2elasticsearch) - Python script to transfer data from a Kippo SSH honeypot MySQL database to an ElasticSearch instance (server or cluster).

- Passive network audit framework parser
    - [pnaf](https://github.com/jusafing/pnaf) - Passive Network Audit Framework. :star:13

- VM monitoring and tools
    - [vmscope](https://cs.gmu.edu/~xwangc/Publications/RAID07-VMscope.pdf) - Monitoring of VM-based.
    - [vmitools](http://libvmi.com/) - C library with Python bindings that makes it easy to monitor the low-level details of a running virtual machine.
    - [Antivmdetect](https://github.com/nsmfoo/antivmdetection) - Script to create templates to use with VirtualBox to make vm detection harder. :star:225
    - [VMCloak](https://github.com/jbremer/vmcloak) - Automated Virtual Machine Generation and Cloaking for Cuckoo Sandbox. :star:215

- Binary debugger
    - [Hexgolems - Schem Debugger Frontend](https://github.com/hexgolems/schem) - A debugger frontend. :star:139
    - [Hexgolems - Pint Debugger Backend](https://github.com/hexgolems/pint) - A debugger backend and LUA wrapper for PIN. :star:28

- Mobile Analysis Tool
    - [APKinspector](https://github.com/honeynet/apkinspector/) - APKinspector is a powerful GUI tool for analysts to analyze the Android applications.
    - [Androguard](https://github.com/androguard/androguard) - Reverse engineering, Malware and goodware analysis of Android applications ... and more. :star:1835

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
    - [Beeswarm](http://www.beeswarm-ids.org/) - Honeypot deployment made easy.
    - [Bait and Switch](http://baitnswitch.sourceforge.net) - redirects all hostile traffic to a honeypot that is partially mirroring your production system.
    - [Artillery](https://github.com/trustedsec/artillery/) - open-source blue team tool designed to protect Linux and Windows operating systems through multiple methods.
    - [slipm-honeypot](https://github.com/rshipp/slipm-honeypot) - A simple low-interaction port monitoring honeypot. :star:6
    - [HoneyWRT](https://github.com/CanadianJeff/honeywrt) - low interaction Python honeypot designed to mimic services or ports that might get targeted by attackers. :star:12
    - [Amun](http://amunhoney.sourceforge.net) - vulnerability emulation honeypot.
    - [TelnetHoney](https://github.com/AnguisCaptor/TelnetHoney) - A simple telnet honeypot. :star:4
    - [Hontel](https://github.com/stamparm/hontel) - Telnet Honeypot. :star:80
    - [MTPot](https://github.com/Cymmetria/MTPot) - Open Source Telnet Honeypot, focused on Mirai malware. :star:82
    - [Heralding](https://github.com/johnnykv/heralding) - A credentials catching honeypot. :star:143
    - [vnclowpot](https://github.com/magisterquis/vnclowpot) - A low interaction VNC honeypot. :star:8
    - [SIREN](https://github.com/blaverick62/SIREN) - Semi-Intelligent HoneyPot Network - HoneyNet Intelligent Virtual Environment. :star:4
    - [telnetlogger](https://github.com/robertdavidgraham/telnetlogger) - A Telnet honeypot designed to track the Mirai botnet. :star:170
    - [honeytrap](https://github.com/tillmannw/honeytrap) - a low-interaction honeypot and network security tool written to catch attacks against TCP and UDP services.  :star:63
    - [mwcollectd](https://www.openhub.net/p/mwcollectd) - a versatile malware collection daemon, uniting the best features of nepenthes and honeytrap.
    - [portlurker](https://github.com/bartnv/portlurker) - Port listener / honeypot in Rust with protocol guessing and safe string display. :star:3
    - [arctic-swallow](https://github.com/ajackal/arctic-swallow) - a low interaction honeypot.
    - [glutton](https://github.com/mushorg/glutton) - All eating honeypot. :star:68

- IDS signature generation
    - [Honeycomb](http://www.icir.org/christian/honeycomb/) - Automated signature creation using honeypots.

- Lookup service for AS-numbers and prefixes
    - [CC2ASN](http://www.cc2asn.com/) - A simple lookup service for AS-numbers and prefixes belonging to any given country in the world.

- Web interface (for Thug)
    - [Rumal](https://github.com/thugs-rumal/) - Thug's Rumāl: a Thug's dress & weapon.

- Data Collection / Data Sharing
    - [HPfriends](http://hpfriends.honeycloud.net/#/home) - Honeypot data-sharing platform.
      - [hpfriends - real-time social data-sharing](http://heipei.github.io/sigint-hpfriends/) - Presentation about HPFriends feed system 
    - [HPFeeds](https://github.com/rep/hpfeeds/) - lightweight authenticated publish-subscribe protocol.

- central management tool
    - [PHARM](http://www.nepenthespharm.com/) - Manage , Report, Analyze your distributed Nepenthes instances.

- Network connection analyzer
    - [Impost](http://impost.sourceforge.net/) - a network security auditing tool designed to analyze the forensics behind compromised and/or vulnerable daemons. 

- Honeypot deployment
    - [Modern Honeynet Network](http://threatstream.github.io/mhn/) - makes deploying and managing secure honeypots extremely simple.

- Honeypot extensions to Wireshark
    - [Whireshark Extensions](https://www.honeynet.org/project/WiresharkExtensions) - support applying Snort IDS rules and signatures against pcap files.


- Client
    - [Pwnypot](https://github.com/shjalayeri/pwnypot) - High Interaction Client Honeypot :star:28
    - [MonkeySpider](http://monkeyspider.sourceforge.net)
    - [Capture-HPC-NG](https://github.com/CERT-Polska/HSN-Capture-HPC-NG) :star:8
    - [URLQuery](https://urlquery.net/)
    - [Trigona](https://www.honeynet.org/project/Trigona)
    - [Thug](https://buffer.github.io/thug/)
    - [Shelia](http://www.cs.vu.nl/~herbertb/misc/shelia/)
    - [PhoneyC](https://github.com/honeynet/phoneyc) :star:19
    - [Jsunpack-n](https://github.com/urule99/jsunpack-n) :star:89
    - [HoneyC](https://projects.honeynet.org/honeyc)
    - [HoneyBOT](http://www.atomicsoftwaresolutions.com/)
    - [CWSandbox / GFI Sandbox](https://www.gfi.com/products-and-solutions/all-products)
    - [Capture-HPC-Linux](https://redmine.honeynet.org/projects/linux-capture-hpc/wiki)
    - [Capture-HPC](https://projects.honeynet.org/capture-hpc) - a high interaction client honeypot (also called honeyclient).
    - [YALIH (Yet Another Low Interaction Honeyclient)](https://github.com/Masood-M/yalih) - a low Interaction Client honeypot designed to detect malicious websites through signature, anomaly and pattern matching techniques :star:42

- Binary Management and Analysis Framework
    - [Viper](http://viper.li/)

- Honeypot
    - [Single-honeypot](https://sourceforge.net/projects/single-honeypot/)
    - [Honeyd For Windows](http://www.securityprofiling.com/honeyd/honeyd.shtml)
    - [IMHoneypot](https://github.com/mushorg/imhoneypot) :star:8
    - [Deception Toolkit](http://www.all.net/dtk/dtk.html)

- PDF document inspector
    - [peepdf](https://github.com/jesparza/peepdf) :star:288

- Distribution system
    - [Thug Distributed Task Queuing](https://thug-distributed.readthedocs.io/en/latest/index.html)

- HoneyClient Management
    - [HoneyWeb](https://code.google.com/archive/p/gsoc-honeyweb/)

- Hybrid low/high interaction honeypot
    - [HoneyBrid](http://honeybrid.sourceforge.net)

- SSH Honeypots
    - [Kojoney](http://kojoney.sourceforge.net/)
    - [Kojoney2](https://github.com/madirish/kojoney2) - low interaction SSH honeypot written in Python. Based on Kojoney by Jose Antonio Coret :star:30
    - [Kippo](https://github.com/desaster/kippo) - Medium interaction SSH honeypot :star:1001
       - [LongTail Log Analysis @ Marist College](http://longtail.it.marist.edu/honey/) - analyzed SSH honeypot logs
    - [Cowrie](https://github.com/micheloosterhof/cowrie) - Cowrie SSH Honeypot (based on kippo)
    - [sshlowpot](https://github.com/magisterquis/sshlowpot) - Yet another no-frills low-interaction ssh honeypot in Go.     :star:5
    - [sshhipot](https://github.com/magisterquis/sshhipot) - High-interaction MitM SSH honeypot :star:114
    - [DShield docker](https://github.com/xme/dshield-docker) - Docker container running cowrie with DShield output enabled. :star:3
    - [hornet](https://github.com/czardoz/hornet) - Medium interaction SSH Honeypot that supports multiple virtual hosts :star:18
    - [ssh-honeypot](https://github.com/droberson/ssh-honeypot) - Fake sshd that logs ip addresses, usernames, and passwords. :star:143
    - [Kippo_JunOS](https://github.com/gregcmartin/Kippo_JunOS) - Kippo configured to be a backdoored netscreen. :star:10
    - [ssh-honeypotd](https://github.com/sjinks/ssh-honeypotd) - A low-interaction SSH honeypot written in C. :star:4
    - [sshesame](https://github.com/jaksi/sshesame) - A fake SSH server that lets everyone in and logs their activity. :star:822
    - [sshsyrup](https://github.com/mkishere/sshsyrup) - A simple SSH Honeypot with features to capture terminal activity and upload to asciinema.org :star:3

- Distributed sensor project
    - [DShield Web Honeypot Project](https://sites.google.com/site/webhoneypotsite/)
    - [Distributed Web Honeypot Project](http://projects.webappsec.org/w/page/29606603/Distributed%20Web%20Honeypots)

- A pcap analyzer
    - [Honeysnap](https://projects.honeynet.org/honeysnap/)

- Client Web crawler
    - [HoneySpider Network](https://github.com/CERT-Polska/hsn2-bundle) :star:21

- Network traffic redirector
    - [Honeywall](https://projects.honeynet.org/honeywall/)

- Honeypot Distribution with mixed content
    - [HoneyDrive](http://bruteforcelab.com/honeydrive)

- Honeypot sensor
    - [Honeeepi] (https://redmine.honeynet.org/projects/honeeepi/wiki) - Honeeepi is a honeypot sensor on Raspberry Pi which based on customized Raspbian OS.

- File carving
    - [TestDisk & PhotoRec](https://www.cgsecurity.org/)

- Sebek
    - [Sebek](https://projects.honeynet.org/sebek/) - data capture
    - [Qebek](https://projects.honeynet.org/sebek/wiki/Qebek) - QEMU based Sebek. As Sebek, it is data capture tool for high interaction honeypot.
    - [xebek](https://code.google.com/archive/p/xebek/) - Sebek on Xen

- SSH proxy
    - [HonSSH](https://github.com/tnich/honssh) :star:254

- Behavioral analysis tool for win32
    - [Capture BAT](https://www.honeynet.org/node/315)

- Live CD
    - [DAVIX](http://www.secviz.org/node/89)

- Spamtrap
    - [Mailoney](https://github.com/awhitehatter/mailoney) - SMTP honeypot, Open Relay, Cred Harvester written in python. :star:121
    - [Spamhole](http://www.spamhole.net/)
    - [spamd](http://man.openbsd.org/cgi-bin/man.cgi?query=spamd%26apropos=0%26sektion=0%26manpath=OpenBSD+Current%26arch=i386%26format=html)
    - [Mail::SMTP::Honeypot](http://search.cpan.org/~miker/Mail-SMTP-Honeypot-0.11/Honeypot.pm) - perl module that appears to provide the functionality of a standard SMTP server
    - [honeypot](https://github.com/jadb/honeypot) - The Project Honey Pot un-official PHP SDK :star:1
    - [SpamHAT](https://github.com/miguelraulb/spamhat) - Spam Honeypot Tool :star:14
    - [SendMeSpamIDS.py](https://github.com/johestephan/SendMeSpamIDS.py) Simple SMTP fetch all IDS and analyzer
    - [Shiva](https://github.com/shiva-spampot/shiva) - Spam Honeypot with Intelligent Virtual Analyzer :star:99
        - [Shiva The Spam Honeypot Tips And Tricks For Getting It Up And Running](https://www.pentestpartners.com/security-blog/shiva-the-spam-honeypot-tips-and-tricks-for-getting-it-up-and-running/)

- Distributed spam tracking
    - [Project Honeypot](https://www.projecthoneypot.org)

- Commercial honeynet
    - [HONEYPOINT SECURITY SERVER](http://microsolved.com/HoneyPoint-server.html) - distributed honeypot, includes IT and SCADA emulators.
    - [Cymmetria Mazerunner](https://cymmetria.com/product/mazerunner/) - MazeRunner leads attackers away from real targets and creates a footprint of the attack.


- Server (Bluetooth)
    - [Bluepot](https://github.com/andrewmichaelsmith/bluepot) :star:81

- Dynamic analysis of Android apps
    - [Droidbox](https://code.google.com/archive/p/droidbox/)

- Dockerized Low Interaction packaging
    - [Manuka](https://github.com/andrewmichaelsmith/manuka) - Docker based honeypot (Dionaea & Kippo). :star:11
    - [Dockerized Thug](https://hub.docker.com/r/honeynet/thug/) - A dockerized [Thug](https://github.com/buffer/thug) to analyze malicious web content.
    - [Dockerpot](https://github.com/mrschyte/dockerpot) - A docker based honeypot. :star:106
    - [Docker honeynet](https://github.com/sreinhardt/Docker-Honeynet) - Several Honeynet tools set up for Docker containers. :star:12
    - [mhn-core-docker](https://github.com/MattCarothers/mhn-core-docker) - Core elements of the Modern Honey Network implemented in Docker. :star:10

- Network analysis
    - [Quechua](https://bitbucket.org/zaccone/quechua)

- SIP Server
    - [Artemnesia VoIP](http://artemisa.sourceforge.net)

    
- IOT Honeypot
    - [HoneyThing](https://github.com/omererdem/honeything) - TR-069 Honeypot :star:53

- Honeytokens
    - [Honeyλ](https://github.com/0x4D31/honeylambda) - honeyLambda 'serverless trap' is a simple, serverless application designed to create and monitor URL honeytokens, on top of AWS Lambda and Amazon API Gateway. :star:347
    - [Honeybits](https://github.com/0x4D31/honeybits) - A simple tool designed to enhance the effectiveness of your traps by spreading breadcrumbs & honeytokens across your production servers and workstations to lure the attacker toward your honeypots. :star:89
    - [CanaryTokens](https://github.com/thinkst/canarytokens) - 
    - [dcept](https://github.com/secureworks/dcept) - A tool for deploying and detecting use of Active Directory honeytokens. :star:382

## <a name="honeyd"></a> Honeyd Tools

- Honeyd plugin
    - [Honeycomb](http://www.honeyd.org/tools.php)

- Honeyd viewer
    - [Honeyview](http://honeyview.sourceforge.net/)

- Honeyd to MySQL connector
    - [Honeyd2MySQL](http://bruteforcelab.com/honeyd2mysql)

- A script to visualize statistics from honeyd
    - [Honeyd-Viz](http://bruteforcelab.com/honeyd-viz)

- Honeyd UI
    - [Honeyd configuration GUI](http://www.citi.umich.edu/u/provos/honeyd/ch01-results/1/) - application used to configure
the honeyd daemon and generate configuration files

- Honeyd stats
    - [Honeydsum.pl](https://github.com/DataSoft/Honeyd/blob/master/scripts/misc/honeydsum-v0.3/honeydsum.pl)



## <a name="analysis"></a> Network and Artifact Analysis

- Sandbox
    - [RFISandbox](https://monkey.org/~jose/software/rfi-sandbox/) - a PHP 5.x script sandbox built on top of [funcall](https://pecl.php.net/package/funcall)
    - [dorothy2](https://github.com/m4rco-/dorothy2) - A malware/botnet analysis framework written in Ruby :star:174
    - [COMODO automated sandbox](https://help.comodo.com/topic-72-1-451-4768-.html)
    - [Argos](http://www.few.vu.nl/argos/) - An emulator for capturing zero-day attacks
    - [libemu](https://github.com/buffer/libemu) - Shellcode emulation library, useful for shellcode detection. :star:31
    - [Pylibemu](https://github.com/buffer/pylibemu) - A Libemu Cython wrapper. :star:92
    - [imalse](https://github.com/hbhzwj/imalse) - Integrated MALware Simulator and Emulator. :star:6
    - [Cuckoo](https://cuckoosandbox.org/) - he leading open source automated malware analysis system.

- Sandbox-as-a-Service
    - [malwr.com](https://malwr.com/) - free malware analysis service and community.
    - [detux.org](https://detux.org) - Multiplatform Linux Sandbox.
    - [linux.huntingmalware.com](https://linux.huntingmalware.com) - Multiplatform Linux Sandbox based on Cuckoo v2.
    - [Joebox Cloud](https://jbxcloud.joesecurity.org/login) - analyzes the behavior of malicious files including PEs, PDFs, DOCs, PPTs, XLSs, APKs, URLs and MachOs on Windows, Android and Mac OS X for suspicious activities.
    - [VirusTotal](https://www.virustotal.com/)
    - [Hybrid Analysis](https://www.hybrid-analysis.com) - a free malware analysis service powered by Payload Security that detects and analyzes unknown threats using a unique Hybrid Analysis technology.

## <a name="visualizers"></a> Data Tools

- Front Ends
    - [Tango](https://github.com/aplura/Tango) - Honeypot Intelligence with Splunk. :star:199
    - [Django-kippo](https://github.com/jedie/django-kippo) - Django App for kippo SSH Honeypot. :star:10
    - [Wordpot-Frontend](https://github.com/GovCERT-CZ/Wordpot-Frontend) - a full featured script to visualize statistics from a Wordpot honeypot.
    - [Shockpot-Frontend](https://github.com/GovCERT-CZ/Shockpot-Frontend) - a full featured script to visualize statistics from a Shockpot honeypot. 
    - [honeypotDisplay](https://github.com/Joss-Steward/honeypotDisplay) - A flask website which displays data I've gathered with my SSH Honeypot.  :star:2
    - [honeyalarmg2](https://github.com/schmalle/honeyalarmg2) - Simplified UI for showing honeypot alarms. :star:3
    - [DionaeaFR](https://github.com/rubenespadas/DionaeaFR) - Front Web to Dionaea low-interaction honeypot. :star:37

- Visualization
    - [Kippo-Graph](http://bruteforcelab.com/kippo-graph) - a full featured script to visualize statistics from a Kippo SSH honeypot.
    - [Kippo stats](https://github.com/mfontani/kippo-stats) - Mojolicious app to display statistics for your kippo SSH honeypot.  :star:17
    - [HoneyStats](https://sourceforge.net/projects/honeystats/) - A statistical view of the recorded activity on a Honeynet. 
    - [HoneyMap](https://github.com/fw42/honeymap) - Real-time websocket stream of GPS events on a fancy SVG world map.  :star:188
    - [HoneyMalt](https://github.com/SneakersInc/HoneyMalt) - Maltego tranforms for mapping Honeypot systems. :star:10
    - [Glastopf Analytics](https://github.com/katkad/Glastopf-Analytics) - easy honeypot statistics
    - [Afterglow Cloud](https://github.com/ayrus/afterglow-cloud) :star:14
    - [Afterglow](http://afterglow.sourceforge.net/)
    - [ovizart](https://github.com/oguzy/ovizart) - visual analysis for network traffic.  :star:44
    - [HpfeedsHoneyGraph](https://github.com/yuchincheng/HpfeedsHoneyGraph) - a visualization app to visualize hpfeeds logs. :star:9
    - [Acapulco](https://github.com/hgascon/acapulco) - Automated Attack Community Graph Construction. :star:8
    - [Sebek Dataviz](http://www.honeynet.org/gsoc/project4) - Sebek data visualization.
    - [The Intelligent HoneyNet](https://github.com/jpyorre/IntelligentHoneyNet) - The Intelligent Honey Net Project attempts to create actionable information from honeypots. :star:35

## <a name="guides"></a>Guides

- [T-Pot: A Multi-Honeypot Platform](https://dtag-dev-sec.github.io/mediator/feature/2015/03/17/concept.html)
- [Honeypot (Dionaea and kippo) setup script](https://github.com/andrewmichaelsmith/honeypot-setup-script/)

- Deployment
    - [Dionaea and EC2 in 20 Minutes](http://andrewmichaelsmith.com/2012/03/dionaea-honeypot-on-ec2-in-20-minutes/) - a tutorial on setting up Dionaea on an EC2 instance
    - [honeypotpi](https://github.com/free5ty1e/honeypotpi) - Script for turning a Raspberry Pi into a HoneyPot Pi :star:14
    - [Using a Raspberry Pi honeypot to contribute data to DShield/ISC](https://isc.sans.edu/diary/22680) - The Raspberry Pi based system will allow us to maintain one code base that will make it easier to collect rich logs beyond firewall logs.

- Research Paper
    - [vEYE](https://link.springer.com/article/10.1007%2Fs10115-008-0137-3) - behavioral footprinting for self-propagating worm detection and profiling.


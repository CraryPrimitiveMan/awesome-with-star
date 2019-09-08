# Information comes from [paralax/awesome-honeypots](https://github.com/paralax/awesome-honeypots)
# Awesome Honeypots [![Awesome Honeypots](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome honeypots, plus related components and much more, divided into categories such as Web, services, and others, with a focus on free and open source projects.

There is no pre-established order of items in each category, the order is for contribution. If you want to contribute, please read the [guide](CONTRIBUTING.md).

Discover more awesome lists at [sindresorhus/awesome](https://github.com/sindresorhus/awesome).

# Contents

- [Related Lists](#related-lists)
- [Honeypots](#honeypots)
- [Honeyd Tools](#honeyd-tools)
- [Network and Artifact Analysis](#network-and-artifact-analysis)
- [Data Tools](#data-tools)
- [Guides](#guides)

## Related Lists

- [awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools) - Useful in network traffic analysis. :star:1710
- [awesome-malware-analysis](https://github.com/rshipp/awesome-malware-analysis) - Some overlap here for artifact analysis. :star:5197

## Honeypots

- Database Honeypots
    - [Delilah](https://github.com/SecurityTW/delilah) - Elasticsearch Honeypot written in Python (originally from Novetta). :star:3
    - [ESPot](https://github.com/mycert/ESPot) - Elasticsearch honeypot written in NodeJS, to capture every attempts to exploit CVE-2014-3120. :star:15
    - [Elastic honey](https://github.com/jordan-wright/elastichoney) - Simple Elasticsearch Honeypot. :star:127
    - [HoneyMysql](https://github.com/xiaoxiaoleo/HoneyMysql) - Simple Mysql honeypot project. :star:4
    - [MongoDB-HoneyProxy](https://github.com/Plazmaz/MongoDB-HoneyProxy) - MongoDB honeypot proxy. :star:63
    - [MongoDB-HoneyProxyPy](https://github.com/jwxa2015/MongoDB-HoneyProxyPy) - MongoDB honeypot proxy by python3. :star:2
    - [NoSQLpot](https://github.com/torque59/nosqlpot) - Honeypot framework built on a NoSQL-style database. :star:96
    - [mysql-honeypotd](https://github.com/sjinks/mysql-honeypotd) - Low interaction MySQL honeypot written in C. :star:5
    - [MysqlPot](https://github.com/schmalle/MysqlPot) - MySQL honeypot, still very early stage. :star:19
    - [pghoney](https://github.com/betheroot/pghoney) - Low-interaction Postgres Honeypot. :star:6
    - [sticky_elephant](https://github.com/betheroot/sticky_elephant) - Medium interaction postgresql honeypot. :star:6

- Web honeypots
    - [Bukkit Honeypot](https://github.com/Argomirr/Honeypot) - Honeypot plugin for Bukkit. :star:7
    - [EoHoneypotBundle](https://github.com/eymengunay/EoHoneypotBundle) - Honeypot type for Symfony2 forms. :star:27
    - [Glastopf](https://github.com/mushorg/glastopf) - Web Application Honeypot. :star:387
    - [Google Hack Honeypot](http://ghh.sourceforge.net) - Designed to provide reconnaissance against attackers that use search engines as a hacking tool against your resources.
    - [Laravel Application Honeypot](https://github.com/msurguy/Honeypot) - Simple spam prevention package for Laravel applications. :star:379
    - [Nodepot](https://github.com/schmalle/Nodepot) - NodeJS web application honeypot. :star:28
    - [Servletpot](https://github.com/schmalle/servletpot) - Web application Honeypot. :star:11
    - [Shadow Daemon](https://shadowd.zecure.org/overview/introduction/) - Modular Web Application Firewall / High-Interaction Honeypot for PHP, Perl, and Python apps.
    - [StrutsHoneypot](https://github.com/Cymmetria/StrutsHoneypot) - Struts Apache 2 based honeypot as well as a detection module for Apache 2 servers. :star:65
    - [WebTrap](https://github.com/IllusiveNetworks-Labs/WebTrap) - Designed to create deceptive webpages to deceive and redirect attackers away from real websites. :star:32
    - [basic-auth-pot (bap)](https://github.com/bjeborn/basic-auth-pot) - HTTP Basic Authentication honeypot. :star:12
    - [bwpot](https://github.com/graneed/bwpot) - Breakable Web applications honeyPot. :star:19
    - [django-admin-honeypot](https://github.com/dmpayton/django-admin-honeypot) - Fake Django admin login screen to notify admins of attempted unauthorized access. :star:570
    - [drupo](https://github.com/d1str0/drupot) - Drupal Honeypot. :star:52
    - [honeyhttpd](https://github.com/bocajspear1/honeyhttpd) - Python-based web server honeypot builder. :star:7
    - [phpmyadmin_honeypot](https://github.com/gfoss/phpmyadmin_honeypot) - Simple and effective phpMyAdmin honeypot. :star:50
    - [shockpot](https://github.com/threatstream/shockpot) - WebApp Honeypot for detecting Shell Shock exploit attempts. :star:47
    - [smart-honeypot](https://github.com/freak3dot/smart-honeypot) - PHP Script demonstrating a smart honey pot. :star:13
    - Snare/Tanner - successors to Glastopf
        - [Snare](https://github.com/mushorg/snare) - Super Next generation Advanced Reactive honeypot. :star:182
        - [Tanner](https://github.com/mushorg/tanner) - Evaluating SNARE events. :star:93
    - [stack-honeypot](https://github.com/CHH/stack-honeypot) - Inserts a trap for spam bots into responses. :star:18
    - [tomcat-manager-honeypot](https://github.com/helospark/tomcat-manager-honeypot) - Honeypot that mimics Tomcat manager endpoints. Logs requests and saves attacker's WAR file for later study :star:3
    - WordPress honeypots
        - [HonnyPotter](https://github.com/MartinIngesen/HonnyPotter) - WordPress login honeypot for collection and analysis of failed login attempts. :star:19
        - [HoneyPress](https://github.com/dustyfresh/HoneyPress) - Python based WordPress honeypot in a Docker container. :star:57
        - [wp-smart-honeypot](https://github.com/freak3dot/wp-smart-honeypot) - WordPress plugin to reduce comment spam with a smarter honeypot. :star:22
        - [wordpot](https://github.com/gbrindisi/wordpot) - WordPress Honeypot. :star:129

- Service Honeypots
    - [AMTHoneypot](https://github.com/packetflare/amthoneypot) - Honeypot for Intel's AMT Firmware Vulnerability CVE-2017-5689. :star:10
    - [Ensnare](https://github.com/ahoernecke/ensnare) - Easy to deploy Ruby honeypot. :star:66
    - [HoneyPy](https://github.com/foospidy/HoneyPy) - Low interaction honeypot. :star:372
    - [Honeygrove](https://github.com/UHH-ISS/honeygrove) - Multi-purpose modular honeypot based on Twisted. :star:8
    - [Honeyport](https://github.com/securitygeneration/Honeyport) - Simple honeyport written in Bash and Python. :star:27
    - [Honeyprint](https://github.com/glaslos/honeyprint) - Printer honeypot. :star:14
    - [Lyrebird](https://hub.docker.com/r/lyrebird/honeypot-base/) - Modern high-interaction honeypot framework.
    - [MICROS honeypot](https://github.com/Cymmetria/micros_honeypot) -  Low interaction honeypot to detect CVE-2018-2636 in the Oracle Hospitality Simphony component of Oracle Hospitality Applications (MICROS). :star:9
    - [RDPy](https://github.com/citronneur/rdpy) - Microsoft Remote Desktop Protocol (RDP) honeypot implemented in Python. :star:1123
    - [SMB Honeypot](https://github.com/r0hi7/HoneySMB) - High interaction SMB service honeypot capable of capturing wannacry-like Malware. :star:16
    - [Tom's Honeypot](https://github.com/inguardians/toms_honeypot) - Low interaction Python honeypot. :star:13
    - [WebLogic honeypot](https://github.com/Cymmetria/weblogic_honeypot) - Low interaction honeypot to detect CVE-2017-10271 in the Oracle WebLogic Server component of Oracle Fusion Middleware. :star:13
    - [WhiteFace Honeypot](https://github.com/csirtgadgets/csirtg-honeypot) - Twisted based honeypot for WhiteFace. :star:3
    - [honeycomb_plugins](https://github.com/Cymmetria/honeycomb_plugins) - Plugin repository for Honeycomb, the honeypot framework by Cymmetria. :star:18
    - [honeyntp](https://github.com/fygrave/honeyntp) - NTP logger/honeypot. :star:43
    - [honeypot-camera](https://github.com/alexbredo/honeypot-camera) - Observation camera honeypot. :star:39
    - [honeypot-ftp](https://github.com/alexbredo/honeypot-ftp) - FTP Honeypot. :star:6
    - [honeytrap](https://github.com/honeytrap/honeytrap) - Advanced Honeypot framework written in Go that can be connected with other honeypot software. :star:637
    - [pyrdp](https://github.com/gosecure/pyrdp) - RDP man-in-the-middle and library for Python 3 with the ability to watch connections live or after the fact. :star:276
    - [troje](https://github.com/dutchcoders/troje/) - Honeypot that runs each connection with the service within a seperate LXC container. :star:39

- Distributed Honeypots
    - [DemonHunter](https://github.com/RevengeComing/DemonHunter) - Low interaction honeypot server. :star:28

- Anti-honeypot stuff
    - [kippo_detect](https://github.com/andrew-morris/kippo_detect) - Offensive component that detects the presence of the kippo honeypot. :star:45

- ICS/SCADA honeypots
    - [Conpot](https://github.com/mushorg/conpot) - ICS/SCADA honeypot. :star:671
    - [GasPot](https://github.com/sjhilt/GasPot) - Veeder Root Gaurdian AST, common in the oil and gas industry. :star:75
    - [SCADA honeynet](http://scadahoneynet.sourceforge.net) - Building Honeypots for Industrial Networks.
    - [gridpot](https://github.com/sk4ld/gridpot) - Open source tools for realistic-behaving electric grid honeynets. :star:36
    - [scada-honeynet](http://www.digitalbond.com/blog/2007/07/24/scada-honeynet-article-in-infragard-publication/) - Mimics many of the services from a popular PLC and better helps SCADA researchers understand potential risks of exposed control system devices.

- Other/random
    - [Damn Simple Honeypot (DSHP)](https://github.com/naorlivne/dshp) - Honeypot framework with pluggable handlers. :star:7
    - [NOVA](https://github.com/DataSoft/Nova) - Uses honeypots as detectors, looks like a complete system. :star:57
    - [OpenFlow Honeypot (OFPot)](https://github.com/upa/ofpot) - Redirects traffic for unused IPs to a honeypot, built on POX. :star:13
    - [OpenCanary](https://github.com/thinkst/opencanary) - Modular and decentralised honeypot daemon that runs several canary versions of services that alerts when a service is (ab)used. :star:530
    - [ciscoasa_honeypot](https://github.com/cymmetria/ciscoasa_honeypot) A low interaction honeypot for the Cisco ASA component capable of detecting CVE-2018-0101, a DoS and remote code execution vulnerability. 
    - [miniprint](https://github.com/sa7mon/miniprint) - A medium interaction printer honeypot. :star:160

- Botnet C2 tools
    - [Hale](https://github.com/pjlantz/Hale) - Botnet command and control monitor. :star:128
    - [dnsMole](https://code.google.com/archive/p/dns-mole/) - Analyses DNS traffic and potentionaly detect botnet command and control server activity, along with infected hosts.

- IPv6 attack detection tool
    - [ipv6-attack-detector](https://github.com/mzweilin/ipv6-attack-detector/) - Google Summer of Code 2012 project, supported by The Honeynet Project organization. :star:24

- Dynamic code instrumentation toolkit
    - [Frida](https://www.frida.re) - Inject JavaScript to explore native apps on Windows, Mac, Linux, iOS and Android.

- Tool to convert website to server honeypots
    - [HIHAT](http://hihat.sourceforge.net/) - Transform arbitrary PHP applications into web-based high-interaction Honeypots.

- Malware collector
    - [Kippo-Malware](https://bruteforcelab.com/kippo-malware) - Python script that will download all malicious files stored as URLs in a Kippo SSH honeypot database.

- Distributed sensor deployment
    - [Modern Honey Network](https://github.com/threatstream/mhn) - Multi-snort and honeypot sensor management, uses a network of VMs, small footprint SNORT installations, stealthy dionaeas, and a centralized server for management. :star:1759

- Network Analysis Tool
    - [Tracexploit](https://code.google.com/archive/p/tracexploit/) - Replay network packets.

- Log anonymizer
    - [LogAnon](http://code.google.com/archive/p/loganon/) - Log anonymization library that helps having anonymous logs consistent between logs and network captures.

- Low interaction honeypot (router back door)
    - [Honeypot-32764](https://github.com/knalli/honeypot-for-tcp-32764) - Honeypot for router backdoor (TCP 32764). :star:9
    - [WAPot](https://github.com/lcashdol/WAPot) - Honeypot that can be used to observe traffic directed at home routers. :star:3

- honeynet farm traffic redirector
    - [Honeymole](https://web.archive.org/web/20100326040550/http://www.honeynet.org.pt:80/index.php/HoneyMole) - Deploy multiple sensors that redirect traffic to a centralized collection of honeypots.

- HTTPS Proxy
    - [mitmproxy](https://mitmproxy.org/) - Allows traffic flows to be intercepted, inspected, modified, and replayed.

- System instrumentation
    - [Sysdig](https://sysdig.com/opensource/) - Open source, system-level exploration allows one to capture system state and activity from a running GNU/Linux instance, then save, filter, and analyze the results.
    - [Fibratus](https://github.com/rabbitstack/fibratus) - Tool for exploration and tracing of the Windows kernel. :star:498

- Honeypot for USB-spreading malware
    - [Ghost-usb](https://github.com/honeynet/ghost-usb-honeypot) - Honeypot for malware that propagates via USB storage devices. :star:52

- Data Collection
    - [Kippo2MySQL](https://bruteforcelab.com/kippo2mysql) - Extracts some very basic stats from Kippo’s text-based log files and inserts them in a MySQL database.
    - [Kippo2ElasticSearch](https://bruteforcelab.com/kippo2elasticsearch) - Python script to transfer data from a Kippo SSH honeypot MySQL database to an ElasticSearch instance (server or cluster).

- Passive network audit framework parser
    - [Passive Network Audit Framework (pnaf)](https://github.com/jusafing/pnaf) - Framework that combines multiple passive and automated analysis techniques in order to provide a security assessment of network platforms. :star:22

- VM monitoring and tools
    - [Antivmdetect](https://github.com/nsmfoo/antivmdetection) - Script to create templates to use with VirtualBox to make VM detection harder. :star:357
    - [VMCloak](https://github.com/hatching/vmcloak) - Automated Virtual Machine Generation and Cloaking for Cuckoo Sandbox. :star:294
    - [vmitools](http://libvmi.com/) - C library with Python bindings that makes it easy to monitor the low-level details of a running virtual machine.

- Binary debugger
    - [Hexgolems - Pint Debugger Backend](https://github.com/hexgolems/pint) - Debugger backend and LUA wrapper for PIN. :star:28
    - [Hexgolems - Schem Debugger Frontend](https://github.com/hexgolems/schem) - Debugger frontend. :star:141

- Mobile Analysis Tool
    - [Androguard](https://github.com/androguard/androguard) - Reverse engineering, Malware and goodware analysis of Android applications and more. :star:2651
    - [APKinspector](https://github.com/honeynet/apkinspector/) - Powerful GUI tool for analysts to analyze the Android applications. :star:660

- Low interaction honeypot
    - [Honeyperl](https://sourceforge.net/projects/honeyperl/) - Honeypot software based in Perl with plugins developed for many functions like : wingates, telnet, squid, smtp, etc.
    - [T-Pot](https://github.com/dtag-dev-sec/tpotce) - All in one honeypot appliance from telecom provider T-Mobile :star:1151

- Honeynet data fusion
    - [HFlow2](https://projects.honeynet.org/hflow) - Data coalesing tool for honeynet/network analysis.

- Server
    - [Amun](http://amunhoney.sourceforge.net) - Vulnerability emulation honeypot.
    - [Artillery](https://github.com/trustedsec/artillery/) - Open-source blue team tool designed to protect Linux and Windows operating systems through multiple methods. :star:289
    - [Bait and Switch](http://baitnswitch.sourceforge.net) - Redirects all hostile traffic to a honeypot that is partially mirroring your production system.
    - [Bifrozt](https://github.com/Ziemeck/bifrozt-ansible) - Automatic deploy bifrozt with ansible. :star:3
    - [Conpot](http://conpot.org/) - Low interactive server side Industrial Control Systems honeypot.
    - [Heralding](https://github.com/johnnykv/heralding) - Credentials catching honeypot. :star:208
    - [HoneyWRT](https://github.com/CanadianJeff/honeywrt) - Low interaction Python honeypot designed to mimic services or ports that might get targeted by attackers. :star:14
    - [Honeyd](https://github.com/provos/honeyd) - See [honeyd tools](#honeyd-tools). :star:1
    - [Honeysink](http://www.honeynet.org/node/773) - Open source network sinkhole that provides a mechanism for detection and prevention of malicious traffic on a given network.
    - [Hontel](https://github.com/stamparm/hontel) - Telnet Honeypot. :star:121
    - [KFSensor](http://www.keyfocus.net/kfsensor/) - Windows based honeypot Intrusion Detection System (IDS).
    - [LaBrea](http://labrea.sourceforge.net/labrea-info.html) - Takes over unused IP addresses, and creates virtual servers that are attractive to worms, hackers, and other denizens of the Internet.
    - [MTPot](https://github.com/Cymmetria/MTPot) - Open Source Telnet Honeypot, focused on Mirai malware. :star:92
    - [SIREN](https://github.com/blaverick62/SIREN) - Semi-Intelligent HoneyPot Network - HoneyNet Intelligent Virtual Environment. :star:9
    - [TelnetHoney](https://github.com/balte/TelnetHoney) - Simple telnet honeypot.
    - [UDPot Honeypot](https://github.com/jekil/UDPot) - Simple UDP/DNS honeypot scripts. :star:26
    - [Yet Another Fake Honeypot (YAFH)](https://github.com/fnzv/YAFH) - Simple honeypot written in Go. :star:5
    - [arctic-swallow](https://github.com/ajackal/arctic-swallow) - Low interaction honeypot. :star:1
    - [glutton](https://github.com/mushorg/glutton) - All eating honeypot. :star:126
    - [go-HoneyPot](https://github.com/Mojachieee/go-HoneyPot) - Honeypot server written in Go. :star:36
    - [go-emulators](https://github.com/kingtuna/go-emulators) - Honeypot Golang emulators. :star:8
    - [honeymail](https://github.com/sec51/honeymail) - SMTP honeypot written in Golang. :star:3
    - [honeytrap](https://github.com/tillmannw/honeytrap) - Low-interaction honeypot and network security tool written to catch attacks against TCP and UDP services. :star:70
    - [imap-honey](https://github.com/yvesago/imap-honey) - IMAP honeypot written in Golang. :star:12
    - [mwcollectd](https://www.openhub.net/p/mwcollectd) - Versatile malware collection daemon, uniting the best features of nepenthes and honeytrap.
    - [potd](https://github.com/lnslbrty/potd) - Highly scalable low- to medium-interaction SSH/TCP honeypot designed for OpenWrt/IoT devices leveraging several Linux kernel features, such as namespaces, seccomp and thread capabilities. :star:20
    - [portlurker](https://github.com/bartnv/portlurker) - Port listener in Rust with protocol guessing and safe string display. :star:7
    - [slipm-honeypot](https://github.com/rshipp/slipm-honeypot) - Simple low-interaction port monitoring honeypot. :star:8
    - [telnet-iot-honeypot](https://github.com/Phype/telnet-iot-honeypot) - Python telnet honeypot for catching botnet binaries. :star:171
    - [telnetlogger](https://github.com/robertdavidgraham/telnetlogger) - Telnet honeypot designed to track the Mirai botnet. :star:194
    - [vnclowpot](https://github.com/magisterquis/vnclowpot) - Low interaction VNC honeypot. :star:16


- IDS signature generation
    - [Honeycomb](http://www.icir.org/christian/honeycomb/) - Automated signature creation using honeypots.

- Lookup service for AS-numbers and prefixes
    - [CC2ASN](http://www.cc2asn.com/) - Simple lookup service for AS-numbers and prefixes belonging to any given country in the world.

- Data Collection / Data Sharing
    - [HPfriends](http://hpfriends.honeycloud.net/#/home) - Honeypot data-sharing platform.
        - [hpfriends - real-time social data-sharing](https://heipei.io/sigint-hpfriends/) - Presentation about HPFriends feed system 
    - [HPFeeds](https://github.com/rep/hpfeeds/) - Lightweight authenticated publish-subscribe protocol. :star:168

- Central management tool
    - [PHARM](http://www.nepenthespharm.com/) - Manage, report, and analyze your distributed Nepenthes instances.

- Network connection analyzer
    - [Impost](http://impost.sourceforge.net/) - Network security auditing tool designed to analyze the forensics behind compromised and/or vulnerable daemons. 

- Honeypot deployment
    - [Modern Honeynet Network](http://threatstream.github.io/mhn/) - Streamlines deployment and management of secure honeypots.

- Honeypot extensions to Wireshark
    - [Whireshark Extensions](https://www.honeynet.org/project/WiresharkExtensions) - Apply Snort IDS rules and signatures against packet capture files using Wireshark.


- Client
    - [CWSandbox / GFI Sandbox](https://www.gfi.com/products-and-solutions/all-products)
    - [Capture-HPC-Linux](https://redmine.honeynet.org/projects/linux-capture-hpc/wiki)
    - [Capture-HPC-NG](https://github.com/CERT-Polska/HSN-Capture-HPC-NG) :star:9
    - [Capture-HPC](https://projects.honeynet.org/capture-hpc) - High interaction client honeypot (also called honeyclient).
    - [HoneyBOT](http://www.atomicsoftwaresolutions.com/)
    - [HoneyC](https://projects.honeynet.org/honeyc)
    - [HoneySpider Network](https://github.com/CERT-Polska/hsn2-bundle) - Highly-scalable system integrating multiple client honeypots to detect malicious websites. :star:25
    - [HoneyWeb](https://code.google.com/archive/p/gsoc-honeyweb/) - Web interface created to manage and remotely share Honeyclients resources. 
    - [Jsunpack-n](https://github.com/urule99/jsunpack-n) :star:114
    - [MonkeySpider](http://monkeyspider.sourceforge.net)
    - [PhoneyC](https://github.com/honeynet/phoneyc) - Python honeyclient (later replaced by Thug). :star:25
    - [Pwnypot](https://github.com/shjalayeri/pwnypot) - High Interaction Client Honeypot. :star:37
    - [Rumal](https://github.com/thugs-rumal/) - Thug's Rumāl: a Thug's dress and weapon.
    - [Shelia](https://www.cs.vu.nl/~herbertb/misc/shelia/) - Client-side honeypot for attack detection.
    - [Thug](https://buffer.github.io/thug/) - Python-based low-interaction honeyclient.
    - [Thug Distributed Task Queuing](https://thug-distributed.readthedocs.io/en/latest/index.html)
    - [Trigona](https://www.honeynet.org/project/Trigona)
    - [URLQuery](https://urlquery.net/)
    - [YALIH (Yet Another Low Interaction Honeyclient)](https://github.com/Masood-M/yalih) - Low-interaction client honeypot designed to detect malicious websites through signature, anomaly, and pattern matching techniques. :star:52

- Honeypot
    - [Deception Toolkit](http://www.all.net/dtk/dtk.html)
    - [IMHoneypot](https://github.com/mushorg/imhoneypot) :star:8

- PDF document inspector
    - [peepdf](https://github.com/jesparza/peepdf) - Powerful Python tool to analyze PDF documents. :star:482

- Hybrid low/high interaction honeypot
    - [HoneyBrid](http://honeybrid.sourceforge.net)

- SSH Honeypots
    - [Blacknet](https://github.com/morian/blacknet) - Multi-head SSH honeypot system. :star:4
    - [Cowrie](https://github.com/cowrie/cowrie) - Cowrie SSH Honeypot (based on kippo). :star:2564
    - [DShield docker](https://github.com/xme/dshield-docker) - Docker container running cowrie with DShield output enabled. :star:4
    - [HonSSH](https://github.com/tnich/honssh) - Logs all SSH communications between a client and server. :star:310
    - [HUDINX](https://github.com/Cryptix720/HUDINX) - Tiny interaction SSH honeypot engineered in Python to log brute force attacks and, most importantly, the entire shell interaction performed by the attacker. :star:1
    - [Kippo](https://github.com/desaster/kippo) - Medium interaction SSH honeypot. :star:1206
    - [Kippo_JunOS](https://github.com/gregcmartin/Kippo_JunOS) - Kippo configured to be a backdoored netscreen. :star:10
    - [Kojoney2](https://github.com/madirish/kojoney2) - Low interaction SSH honeypot written in Python and based on Kojoney by Jose Antonio Coret. :star:33
    - [Kojoney](http://kojoney.sourceforge.net/) - Python-based Low interaction honeypot that emulates an SSH server implemented with Twisted Conch.
    - [LongTail Log Analysis @ Marist College](http://longtail.it.marist.edu/honey/) - Analyzed SSH honeypot logs.
    - [Malbait](https://github.com/batchmcnulty/Malbait) - Simple TCP/UDP honeypot implemented in Perl. :star:1
    - [MockSSH](https://github.com/ncouture/MockSSH) - Mock an SSH server and define all commands it supports (Python, Twisted). :star:99
    - [cowrie2neo](https://github.com/xlfe/cowrie2neo) - Parse cowrie honeypot logs into a neo4j database. :star:2
    - [go-sshoney](https://github.com/ashmckenzie/go-sshoney) - SSH Honeypot. :star:17
    - [go0r](https://github.com/fzerorubigd/go0r) - Simple ssh honeypot in Golang. :star:27
    - [gohoney](https://github.com/PaulMaddox/gohoney) - SSH honeypot written in Go. :star:9
    - [hived](https://github.com/sahilm/hived) - Golang-based honeypot. :star:2
    - [hnypots-agent)](https://github.com/joshrendek/hnypots-agent) - SSH Server in Go that logs username and password combinations. :star:35
    - [honeypot.go](https://github.com/mdp/honeypot.go) - SSH Honeypot written in Go. :star:18
    - [honeyssh](https://github.com/ppacher/honeyssh) - Credential dumping SSH honeypot with statistics. :star:6
    - [hornet](https://github.com/czardoz/hornet) - Medium interaction SSH honeypot that supports multiple virtual hosts. :star:20
    - [ssh-auth-logger](https://github.com/JustinAzoff/ssh-auth-logger) - Low/zero interaction SSH authentication logging honeypot. :star:5
    - [ssh-honeypot](https://github.com/droberson/ssh-honeypot) - Fake sshd that logs IP addresses, usernames, and passwords. :star:259
    - [ssh-honeypot](https://github.com/amv42/sshd-honeypot) - Modified version of the OpenSSH deamon that forwards commands to Cowrie where all commands are interpreted and returned. :star:17
    - [ssh-honeypotd](https://github.com/sjinks/ssh-honeypotd) - Low-interaction SSH honeypot written in C. :star:4
    - [sshForShits](https://github.com/traetox/sshForShits) - Framework for a high interaction SSH honeypot. :star:35
    - [sshesame](https://github.com/jaksi/sshesame) - Fake SSH server that lets everyone in and logs their activity. :star:946
    - [sshhipot](https://github.com/magisterquis/sshhipot) - High-interaction MitM SSH honeypot. :star:139
    - [sshlowpot](https://github.com/magisterquis/sshlowpot) - Yet another no-frills low-interaction SSH honeypot in Go. :star:9
    - [sshsyrup](https://github.com/mkishere/sshsyrup) - Simple SSH Honeypot with features to capture terminal activity and upload to asciinema.org. :star:81
    - [twisted-honeypots](https://github.com/lanjelot/twisted-honeypots) - SSH, FTP and Telnet honeypots based on Twisted. :star:51

- Distributed sensor project
    - [DShield Web Honeypot Project](https://sites.google.com/site/webhoneypotsite/)

- A pcap analyzer
    - [Honeysnap](https://projects.honeynet.org/honeysnap/)

- Network traffic redirector
    - [Honeywall](https://projects.honeynet.org/honeywall/)

- Honeypot Distribution with mixed content
    - [HoneyDrive](https://bruteforcelab.com/honeydrive)

- Honeypot sensor
    - [Honeeepi](https://redmine.honeynet.org/projects/honeeepi/wiki) - Honeypot sensor on a Raspberry Pi based on a customized Raspbian OS.

- File carving
    - [TestDisk & PhotoRec](https://www.cgsecurity.org/)

- Behavioral analysis tool for win32
    - [Capture BAT](https://www.honeynet.org/node/315)

- Live CD
    - [DAVIX](https://www.secviz.org/node/89) - The DAVIX Live CD.

- Spamtrap
    - [Mail::SMTP::Honeypot](https://metacpan.org/pod/release/MIKER/Mail-SMTP-Honeypot-0.11/Honeypot.pm) - Perl module that appears to provide the functionality of a standard SMTP server.
    - [Mailoney](https://github.com/awhitehatter/mailoney) - SMTP honeypot, Open Relay, Cred Harvester written in python. :star:166
    - [SendMeSpamIDS.py](https://github.com/johestephan/VerySimpleHoneypot) - Simple SMTP fetch all IDS and analyzer. :star:10
    - [Shiva](https://github.com/shiva-spampot/shiva) - Spam Honeypot with Intelligent Virtual Analyzer. :star:114
        - [Shiva The Spam Honeypot Tips And Tricks For Getting It Up And Running](https://www.pentestpartners.com/security-blog/shiva-the-spam-honeypot-tips-and-tricks-for-getting-it-up-and-running/)
    - [SpamHAT](https://github.com/miguelraulb/spamhat) - Spam Honeypot Tool. :star:14
    - [Spamhole](http://www.spamhole.net/)
    - [honeypot](https://github.com/jadb/honeypot) - The Project Honey Pot un-official PHP SDK. :star:1
    - [spamd](http://man.openbsd.org/cgi-bin/man.cgi?query=spamd%26apropos=0%26sektion=0%26manpath=OpenBSD+Current%26arch=i386%26format=html)

- Commercial honeynet
    - [Cymmetria Mazerunner](ttps://cymmetria.com/products/mazerunner/) - Leads attackers away from real targets and creates a footprint of the attack.

- Server (Bluetooth)
    - [Bluepot](https://github.com/andrewmichaelsmith/bluepot) :star:94

- Dynamic analysis of Android apps
    - [Droidbox](https://code.google.com/archive/p/droidbox/)

- Dockerized Low Interaction packaging
    - [Docker honeynet](https://github.com/sreinhardt/Docker-Honeynet) - Several Honeynet tools set up for Docker containers. :star:16
    - [Dockerized Thug](https://hub.docker.com/r/honeynet/thug/) - Dockerized [Thug](https://github.com/buffer/thug) to analyze malicious web content.
    - [Dockerpot](https://github.com/mrschyte/dockerpot) - Docker based honeypot. :star:126
    - [Manuka](https://github.com/andrewmichaelsmith/manuka) - Docker based honeypot (Dionaea and Kippo). :star:13
    - [mhn-core-docker](https://github.com/MattCarothers/mhn-core-docker) - Core elements of the Modern Honey Network implemented in Docker. :star:20

- Network analysis
    - [Quechua](https://bitbucket.org/zaccone/quechua)

- SIP Server
    - [Artemnesia VoIP](http://artemisa.sourceforge.net)

- IOT Honeypot
    - [HoneyThing](https://github.com/omererdem/honeything) - TR-069 Honeypot. :star:77
    - [Kako](https://github.com/darkarnium/kako) - Honeypots for a number of well known and deployed embedded device vulnerabilities. :star:8

- Honeytokens
    - [CanaryTokens](https://github.com/thinkst/canarytokens) - Self-hostable honeytoken generator and reporting dashboard; demo version available at [CanaryTokens.org](https://canarytokens.org/generate). :star:364
    - [Honeybits](https://github.com/0x4D31/honeybits) - Simple tool designed to enhance the effectiveness of your traps by spreading breadcrumbs and honeytokens across your production servers and workstations to lure the attacker toward your honeypots. :star:184
    - [Honeyλ (HoneyLambda)](https://github.com/0x4D31/honeylambda) - Simple, serverless application designed to create and monitor URL honeytokens, on top of AWS Lambda and Amazon API Gateway. :star:427
    - [dcept](https://github.com/secureworks/dcept) - Tool for deploying and detecting use of Active Directory honeytokens. :star:427
    - [honeyku](https://github.com/0x4D31/honeyku) - Heroku-based web honeypot that can be used to create and monitor fake HTTP endpoints (i.e. honeytokens). :star:43

## Honeyd Tools

- Honeyd plugin
    - [Honeycomb](http://www.honeyd.org/tools.php)

- Honeyd viewer
    - [Honeyview](http://honeyview.sourceforge.net/)

- Honeyd to MySQL connector
    - [Honeyd2MySQL](https://bruteforcelab.com/honeyd2mysql)

- A script to visualize statistics from honeyd
    - [Honeyd-Viz](https://bruteforcelab.com/honeyd-viz)

- Honeyd stats
    - [Honeydsum.pl](https://github.com/DataSoft/Honeyd/blob/master/scripts/misc/honeydsum-v0.3/honeydsum.pl) :star:187



## Network and Artifact Analysis

- Sandbox
    - [Argos](http://www.few.vu.nl/argos/) - Emulator for capturing zero-day attacks.
    - [COMODO automated sandbox](https://help.comodo.com/topic-72-1-451-4768-.html)
    - [Cuckoo](https://cuckoosandbox.org/) - Leading open source automated malware analysis system.
    - [Pylibemu](https://github.com/buffer/pylibemu) - Libemu Cython wrapper. :star:102
    - [RFISandbox](https://monkey.org/~jose/software/rfi-sandbox/) - PHP 5.x script sandbox built on top of [funcall](https://pecl.php.net/package/funcall).
    - [dorothy2](https://github.com/m4rco-/dorothy2) - Malware/botnet analysis framework written in Ruby. :star:183
    - [imalse](https://github.com/hbhzwj/imalse) - Integrated MALware Simulator and Emulator. :star:10
    - [libemu](https://github.com/buffer/libemu) - Shellcode emulation library, useful for shellcode detection. :star:49


- Sandbox-as-a-Service
    - [Hybrid Analysis](https://www.hybrid-analysis.com) - Free malware analysis service powered by Payload Security that detects and analyzes unknown threats using a unique Hybrid Analysis technology.
    - [Joebox Cloud](https://jbxcloud.joesecurity.org/login) - Analyzes the behavior of malicious files including PEs, PDFs, DOCs, PPTs, XLSs, APKs, URLs and MachOs on Windows, Android and Mac OS X for suspicious activities.
    - [VirusTotal](https://www.virustotal.com/) - Analyze suspicious files and URLs to detect types of malware, and automatically share them with the security community.
    - [malwr.com](https://malwr.com/) - Free malware analysis service and community.

## Data Tools

- Front Ends
    - [DionaeaFR](https://github.com/rubenespadas/DionaeaFR) - Front Web to Dionaea low-interaction honeypot. :star:46
    - [Django-kippo](https://github.com/jedie/django-kippo) - Django App for kippo SSH Honeypot. :star:10
    - [Shockpot-Frontend](https://github.com/GovCERT-CZ/Shockpot-Frontend) - Full featured script to visualize statistics from a Shockpot honeypot. 
    - [Tango](https://github.com/aplura/Tango) - Honeypot Intelligence with Splunk. :star:225
    - [Wordpot-Frontend](https://github.com/GovCERT-CZ/Wordpot-Frontend) - Full featured script to visualize statistics from a Wordpot honeypot. :star:1
    - [honeyalarmg2](https://github.com/schmalle/honeyalarmg2) - Simplified UI for showing honeypot alarms. :star:3
    - [honeypotDisplay](https://github.com/Joss-Steward/honeypotDisplay) - Flask website which displays data gathered from an SSH Honeypot.  :star:2

- Visualization
    - [Acapulco](https://github.com/hgascon/acapulco) - Automated Attack Community Graph Construction. :star:9
    - [Afterglow Cloud](https://github.com/ayrus/afterglow-cloud) :star:14
    - [Afterglow](http://afterglow.sourceforge.net/)
    - [Glastopf Analytics](https://github.com/katkad/Glastopf-Analytics) - Easy honeypot statistics.
    - [HoneyMalt](https://github.com/SneakersInc/HoneyMalt) - Maltego tranforms for mapping Honeypot systems. :star:11
    - [HoneyMap](https://github.com/fw42/honeymap) - Real-time websocket stream of GPS events on a fancy SVG world map. :star:204
    - [HoneyStats](https://sourceforge.net/projects/honeystats/) - Statistical view of the recorded activity on a Honeynet.
    - [HpfeedsHoneyGraph](https://github.com/yuchincheng/HpfeedsHoneyGraph) - Visualization app to visualize hpfeeds logs. :star:10
    - [Kippo stats](https://github.com/mfontani/kippo-stats) - Mojolicious app to display statistics for your kippo SSH honeypot. :star:19
    - [Kippo-Graph](https://bruteforcelab.com/kippo-graph) - Full featured script to visualize statistics from a Kippo SSH honeypot.
    - [The Intelligent HoneyNet](https://github.com/jpyorre/IntelligentHoneyNet) - Create actionable information from honeypots. :star:48
    - [ovizart](https://github.com/oguzy/ovizart) - Visual analysis for network traffic. :star:45

## Guides

- [T-Pot: A Multi-Honeypot Platform](https://dtag-dev-sec.github.io/mediator/feature/2015/03/17/concept.html)
- [Honeypot (Dionaea and kippo) setup script](https://github.com/andrewmichaelsmith/honeypot-setup-script/) :star:71

- Deployment
    - [Dionaea and EC2 in 20 Minutes](http://andrewmichaelsmith.com/2012/03/dionaea-honeypot-on-ec2-in-20-minutes/) - Tutorial on setting up Dionaea on an EC2 instance.
    - [Using a Raspberry Pi honeypot to contribute data to DShield/ISC](https://isc.sans.edu/diary/22680) - The Raspberry Pi based system will allow us to maintain one code base that will make it easier to collect rich logs beyond firewall logs.
    - [honeypotpi](https://github.com/free5ty1e/honeypotpi) - Script for turning a Raspberry Pi into a HoneyPot Pi. :star:17

- Research Papers
    - [Honeypot research papers](https://github.com/shbhmsingh72/Honeypot-Research-Papers) - PDFs of research papers on honeypots. :star:3
    - [vEYE](https://link.springer.com/article/10.1007%2Fs10115-008-0137-3) - Behavioral footprinting for self-propagating worm detection and profiling.


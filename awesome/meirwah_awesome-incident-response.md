# Information comes from [meirwah/awesome-incident-response](https://github.com/meirwah/awesome-incident-response)
# awesome-incident-response
A curated list of tools and resources for security incident response, aimed to help security analysts and [DFIR](http://www.acronymfinder.com/Digital-Forensics%2c-Incident-Response-(DFIR).html) teams.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Contents

- [Adversary Emulation](#adversary-emulation)
- [All in one tools](#all-in-one-tools)
- [Books](#books)
- [Communities](#communities)
- [Disk Image Creation Tools](#disk-image-creation-tools)
- [Evidence Collection](#evidence-collection)
- [Incident Management](#incident-management)
- [Linux Distributions](#linux-distributions)
- [Linux Evidence Collection](#linux-evidence-collection)
- [Log Analysis Tools](#log-analysis-tools)
- [Memory Analysis Tools](#memory-analysis-tools)
- [Memory Imaging Tools](#memory-imaging-tools)
- [OSX Evidence Collection](#osx-evidence-collection)
- [Other lists](#other-lists)
- [Other tools](#other-tools)
- [Playbooks](#playbooks)
- [Process Dump Tools](#process-dump-tools)
- [Sandboxing/reversing tools](#sandboxingreversing-tools)
- [Timeline tools](#timeline-tools)
- [Videos](#videos)
- [Windows Evidence Collection](#windows-evidence-collection)

## IR tools Collection

### Adversary Emulation

* [APTSimulator](https://github.com/NextronSystems/APTSimulator) - A Windows Batch script that uses a set of tools and output files to make a system look as if it was compromised. :star:677
* [Atomic Red Team (ART)](https://github.com/redcanaryco/atomic-red-team) - Small and highly portable detection tests mapped to the Mitre ATT&CK Framework. :star:1041
* [AutoTTP](https://github.com/jymcheong/AutoTTP) - Automated Tactics Techniques & Procedures. Re-running complex sequences manually for regression tests, product evaluations, generate data for researchers. :star:83
* [Blue Team Training Toolkit (BT3)](https://www.bt3.no/) - Software for defensive security training, which will bring your network analysis training sessions, incident response drills and red team engagements to a new level. 
* [Caldera](https://github.com/mitre/caldera) - an automated adversary emulation system that performs post-compromise adversarial behavior within Windows Enterprise networks. It generates plans during operation using a planning system and a pre-configured adversary model based on the Adversarial Tactics, Techniques & Common Knowledge (ATT&CK™) project. :star:596
* [DumpsterFire](https://github.com/TryCatchHCF/DumpsterFire) - The DumpsterFire Toolset is a modular, menu-driven, cross-platform tool for building repeatable, time-delayed, distributed security events. Easily create custom event chains for Blue Team drills and sensor /   alert mapping. Red Teams can create decoy incidents, distractions, and lures to support and scale their operations. :star:448
* [Metta](https://github.com/uber-common/metta) - An information security preparedness tool to do adversarial simulation. :star:475
* [Network Flight Simulator](https://github.com/alphasoc/flightsim) - flightsim is a lightweight utility used to generate malicious network traffic and help security teams to evaluate security controls and network visibility. :star:170
* [Red Team Automation (RTA)](https://github.com/endgameinc/RTA) - RTA provides a framework of scripts designed to allow blue teams to test their detection capabilities against malicious tradecraft, modeled after MITRE ATT&CK. :star:341
* [RedHunt-OS](https://github.com/redhuntlabs/RedHunt-OS) - A virtual machine for adversary emulation and threat hunting. :star:403

### All in one Tools

* [Belkasoft Evidence Center](https://belkasoft.com/ec) -  The toolkit will quickly extract digital evidence from multiple sources by analyzing hard drives, drive images, memory dumps, iOS, Blackberry and Android backups, UFED, JTAG and chip-off dumps
* [CimSweep](https://github.com/PowerShellMafia/CimSweep) - CimSweep is a suite of CIM/WMI-based tools that enable the ability to perform incident response and hunting operations remotely across all versions of Windows :star:372
* [CIRTkit](https://github.com/byt3smith/CIRTKit) - CIRTKit is not just a collection of tools, but also a framework to aid in the ongoing unification of Incident Response and Forensics investigation processes :star:39
* [Cyber Triage](http://www.cybertriage.com) - Cyber Triage remotely collects and analyzes endpoint data to help determine if it is compromised.  It’s agentless approach and focus on ease of use and automation allows companies to respond without major infrastructure changes and without a team of forensics experts.  Its results are used to decide if the system should be erased or investigated further. 
* [Digital Forensics Framework](http://www.arxsys.fr/discover/) - DFF is an Open Source computer forensics platform built on top of a dedicated Application Programming Interface (API). DFF proposes an alternative to the aging digital forensics solutions used today. Designed for simple use and automation, the DFF interface guides the user through the main steps of a digital investigation so it can be used by both professional and non-expert to quickly and easily conduct a digital investigations and perform incident response
* [Doorman](https://github.com/mwielgoszewski/doorman) - Doorman is an osquery fleet manager that allows remote management of osquery configurations retrieved by nodes. It takes advantage of osquery's TLS configuration, logger, and distributed read/write endpoints, to give administrators visibility across a fleet of devices with minimal overhead and intrusiveness :star:366
* [Envdb](https://github.com/mephux/envdb) - Envdb turns your production, dev, cloud, etc environments into a database cluster you can search using osquery as the foundation. It wraps the osquery process with a (cluster) node agent that can communicate back to a central location :star:520
* [Falcon Orchestrator](https://github.com/CrowdStrike/falcon-orchestrator) - Falcon Orchestrator by CrowdStrike is an extendable Windows-based application that provides workflow automation, case management and security response functionality. :star:104
* [GRR Rapid Response](https://github.com/google/grr) - GRR Rapid Response is an incident response framework focused on remote live forensics. It consists of a python agent (client) that is installed on target systems, and a python server infrastructure that can manage and talk to the agent :star:2648
* [Kolide Fleet](https://kolide.com/fleet) - Kolide Fleet is a state of the art host monitoring platform tailored for security experts. Leveraging Facebook's battle-tested osquery project, Kolide delivers fast answers to big questions.
* [Limacharlie](https://github.com/refractionpoint/limacharlie) - an endpoint security platform. It is itself a collection of small projects all working together, and gives you a cross-platform (Windows, OSX, Linux, Android and iOS) low-level environment allowing you to manage and push additional modules into memory to extend its functionality :star:2
* [MIG](http://mig.mozilla.org/) - Mozilla Investigator (MIG) is a platform to perform investigative surgery on remote endpoints. It enables investigators to obtain information from large numbers of systems in parallel, thus accelerating investigation of incidents and day-to-day operations security
* [MozDef](https://github.com/mozilla/MozDef) - The Mozilla Defense Platform (MozDef) seeks to automate the security incident handling process and facilitate the real-time activities of incident handlers :star:1544
* [nightHawk](https://github.com/biggiesmallsAG/nightHawkResponse) - the nightHawk Response Platform is an application built for asynchronus forensic data presentation using ElasticSearch as the backend. It's designed to ingest Redline collections. :star:474
* [Open Computer Forensics Architecture](http://sourceforge.net/projects/ocfa/) - Open Computer Forensics Architecture (OCFA) is another popular distributed open-source computer forensics framework. This framework was built on Linux platform and uses postgreSQL database for storing data
* [Osquery](https://osquery.io/) - with osquery you can easily ask questions about your Linux and OSX infrastructure. Whether your goal is intrusion detection, infrastructure reliability, or compliance, osquery gives you the ability to empower and inform a broad set of organizations within your company. Queries in the *incident-response pack* help you detect and respond to breaches
* [Redline](https://www.fireeye.com/services/freeware/redline.html) - provides host investigative capabilities to users to find signs of malicious activity through memory and file analysis, and the development of a threat assessment profile
* [The Sleuth Kit & Autopsy](http://www.sleuthkit.org) - The Sleuth Kit is a Unix and Windows based tool which helps in forensic analysis of computers. It comes with various tools which helps in digital forensics. These tools help in analyzing disk images, performing in-depth analysis of file systems, and various other things
* [TheHive](https://thehive-project.org/) - TheHive is a scalable 3-in-1 open source and free solution designed to make life easier for SOCs, CSIRTs, CERTs and any information security practitioner dealing with security incidents that need to be investigated and acted upon swiftly.
* [X-Ways Forensics](http://www.x-ways.net/forensics/) - X-Ways is a forensics tool for Disk cloning and imaging. It can be used to find deleted files and disk analysis
* [Zentral](https://github.com/zentralopensource/zentral) - combines osquery's powerful endpoint inventory features with a flexible notification and action framework. This enables one to identify and react to changes on OS X and Linux clients. :star:281

### Books

* [Dfir intro](https://medium.com/@sroberts/introduction-to-dfir-d35d5de4c180/) - By Scott J. Roberts
* [The Practice of Network Security Monitoring: Understanding Incident Detection and Response](http://www.amazon.com/gp/product/1593275099) - Richard Bejtlich's book on IR

### Communities

* [augmentd](http://augmentd.co/) - Community driven site provididing a list of searches that can be implemented in and executed with a variety of common security tools.
* [Sans DFIR mailing list](https://lists.sans.org/mailman/listinfo/dfir) - Mailing list by SANS for DFIR
* [Slack DFIR channel](https://dfircommunity.slack.com) - Slack DFIR Communitiy channel - [Signup here](https://rishi28.typeform.com/to/sTbTI8)

### Disk Image Creation Tools

* [AccessData FTK Imager](http://accessdata.com/product-download/?/support/adownloads#FTKImager) - AccessData FTK Imager is a forensics tool whose main purpose is to preview recoverable data from a disk of any kind. FTK Imager can also acquire live memory and paging file on 32bit and 64bit systems
* [Bitscout](https://github.com/vitaly-kamluk/bitscout) - Bitscout by Vitaly Kamluk helps you build your fully-trusted customizable LiveCD/LiveUSB image to be used for remote digital forensics (or perhaps any other task of your choice). It is meant to be transparent and monitorable by the owner of the system, forensically sound, customizable and compact. :star:260
* [GetData Forensic Imager](http://www.forensicimager.com/) - GetData Forensic Imager is a Windows based program that will acquire, convert, or verify a forensic image in one of the following common forensic file formats
* [Guymager](http://guymager.sourceforge.net) - Guymager is a free forensic imager for media acquisition on Linux
* [Magnet ACQUIRE](https://www.magnetforensics.com/magnet-acquire/) - ACQUIRE by Magnet Forensics allows various types of disk acquisitions to be performed on Windows, Linux, and OS X as well as mobile operating systems.

### Evidence Collection

* [bulk_extractor](https://github.com/simsong/bulk_extractor) - bulk_extractor is a computer forensics tool that scans a disk image, a file, or a directory of files and extracts useful information without parsing the file system or file system structures. Because of ignoring the file system structure, the program distinguishes itself in terms of speed and thoroughness :star:282
* [Cold Disk Quick Response](https://github.com/rough007/CDQR) - uses a streamlined list of parsers to quickly analyze a forenisic image file (dd, E01, .vmdk, etc) and output nine reports :star:134
* [ir-rescue](https://github.com/diogo-fernan/ir-rescue) - *ir-rescue* is a Windows Batch script and a Unix Bash script to comprehensively collect host forensic data during incident response. :star:141
* [Live Response Collection](https://www.brimorlabs.com/tools/) - The Live Response collection by BriMor Labs is an automated tool that collects volatile data from Windows, OSX, and *nix based operating systems

### Incident Management

* [CyberCPR](https://www.cybercpr.com) - A community and commercial incident management tool with Need-to-Know built in to support GDPR compliance while handling sensitive incidents
* [Cyphon](https://www.cyphon.io/) - Cyphon eliminates the headaches of incident management by streamlining a multitude of related tasks through a single platform. It receives, processes and triages events to provide an all-encompassing solution for your analytic workflow — aggregating data, bundling and prioritizing alerts, and empowering analysts to investigate and document incidents.
* [Demisto](https://www.demisto.com/product/) - Demisto community edition(free) offers full Incident lifecycle management, Incident Closure Reports, team assignments and collaboration, and many integrations to enhance automations (like Active Directory, PagerDuty, Jira and much more...)
* [FIR](https://github.com/certsocietegenerale/FIR/) - Fast Incident Response (FIR) is an cybersecurity incident management platform designed with agility and speed in mind. It allows for easy creation, tracking, and reporting of cybersecurity incidents and is useful for CSIRTs, CERTs and SOCs alike
* [RTIR](https://www.bestpractical.com/rtir/) - Request Tracker for Incident Response (RTIR) is the premier open source incident handling system targeted for computer security teams. We worked with over a dozen CERT and CSIRT teams around the world to help you handle the ever-increasing volume of incident reports. RTIR builds on all the features of Request Tracker
* [SCOT](http://getscot.sandia.gov/) - Sandia Cyber Omni Tracker (SCOT) is an Incident Response collaboration and knowledge capture tool focused on flexibility and ease of use. Our goal is to add value to the incident response process without burdening the user
* [threat_note](https://github.com/defpoint/threat_note) - A lightweight investigation notebook that allows security researchers the ability to register and retrieve indicators related to their research   :star:287

### Linux Distributions

* [ADIA](https://forensics.cert.org/#ADIA) - The Appliance for Digital Investigation and Analysis (ADIA) is a VMware-based appliance used for digital investigation and acquisition and is built entirely from public domain software. Among the tools contained in ADIA are Autopsy, the Sleuth Kit, the Digital Forensics Framework, log2timeline, Xplico, and Wireshark. Most of the system maintenance uses Webmin. It is designed for small-to-medium sized digital investigations and acquisitions. The appliance runs under Linux, Windows, and Mac OS. Both i386 (32-bit) and x86_64 (64-bit) versions are available.
* [CAINE](http://www.caine-live.net/index.html) - The Computer Aided Investigative Environment (CAINE) contains numerous tools that help investigators during their analysis, including forensic evidence collection
* [CCF-VM](https://github.com/rough007/CCF-VM) - CyLR CDQR Forensics Virtual Machine (CCF-VM): An all-in-one solution to parsing collected data, making it easily searchable with built-in common searches, enable searching of single and multiple hosts simultaneously :star:114
* [DEFT](http://www.deftlinux.net/) - The Digital Evidence & Forensics Toolkit (DEFT) is a Linux distribution made for computer forensic evidence collection. It comes bundled with the Digital Advanced Response Toolkit (DART) for Windows. A light version of DEFT, called DEFT Zero, is also available, which is focused primarily on forensically sound evidence collection
* [NST - Network Security Toolkit](https://sourceforge.net/projects/nst/files/latest/download?source=files) - Linux distribution that includes a vast collection of best-of-breed open source network security applications useful to the network security professional
* [PALADIN](https://sumuri.com/software/paladin/) - PALADIN is a modified Linux distribution to perform various forenics task in a forensically sound manner. It comes with many open source forensics tools included
* [Security Onion](https://github.com/Security-Onion-Solutions/security-onion) - Security Onion is a special Linux distro aimed at network security monitoring featuring advanced analysis tools :star:1442
* [SIFT Workstation](http://digital-forensics.sans.org/community/downloads) - The SANS Investigative Forensic Toolkit (SIFT) Workstation demonstrates that advanced incident response capabilities and deep dive digital forensic techniques to intrusions can be accomplished using cutting-edge open-source tools that are freely available and frequently updated

### Linux Evidence Collection

* [FastIR Collector Linux](https://github.com/SekoiaLab/Fastir_Collector_Linux) - FastIR for Linux collects different artefacts on live Linux and records the results in csv files :star:82

### Log Analysis Tools

* [Lorg](https://github.com/jensvoid/lorg) - a tool for advanced HTTPD logfile security analysis and forensics :star:137
* [Logdissect](https://github.com/dogoncouch/logdissect) - A CLI utility and Python API for analyzing log files and other data. :star:19

### Memory Analysis Tools


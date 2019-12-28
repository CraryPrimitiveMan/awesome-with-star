# Information comes from [apsdehal/awesome-ctf](https://github.com/apsdehal/awesome-ctf)
# Awesome CTF [![Build Status](https://travis-ci.org/apsdehal/awesome-ctf.svg?branch=master)](https://travis-ci.org/apsdehal/awesome-ctf) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of [Capture The Flag](https://en.wikipedia.org/wiki/Capture_the_flag#Computer_security) (CTF) frameworks, libraries, resources, softwares and tutorials. This list aims to help starters as well as seasoned CTF players to find everything related to CTFs at one place.

### Contributing

Please take a quick look at the [contribution guidelines](https://github.com/apsdehal/ctf-tools/blob/master/CONTRIBUTING.md) first.

#### _If you know a tool that isn't present here, feel free to open a pull request._

### Why?

It takes time to build up collection of tools used in CTF and remember them all. This repo helps to keep all these scattered tools at one place.

### Contents

- [Awesome CTF](#awesome-ctf)
  - [Create](#create)
    - [Forensics](#forensics)
    - [Platforms](#platforms)
    - [Steganography](#steganography)
    - [Web](#web)
  - [Solve](#solve)
    - [Attacks](#attacks)
    - [Bruteforcers](#bruteforcers)
    - [Cryptography](#crypto)
    - [Exploits](#exploits)
    - [Forensics](#forensics-1)
    - [Networking](#networking)
    - [Reversing](#reversing)
    - [Services](#services)
    - [Steganography](#steganography-1)
    - [Web](#web-1)

- [Resources](#resources)
  - [Operating Systems](#operating-systems)
  - [Starter Packs](#starter-packs)
  - [Tutorials](#tutorials)
  - [Wargames](#wargames)
  - [Websites](#websites)
  - [Wikis](#wikis)
  - [Writeups Collections](#writeups-collections)


# Create

*Tools used for creating CTF challenges*

- [Kali Linux CTF Blueprints](https://doc.lagout.org/security/Packt.Kali.Linux.CTF.Blueprints.Jul.2014.ISBN.1783985984.pdf) - Online book on building, testing, and customizing your own Capture the Flag challenges.


## Forensics

*Tools used for creating Forensics challenges*

- [Dnscat2](https://github.com/iagox86/dnscat2) - Hosts communication through DNS. :star:1830
- [Registry Dumper](http://www.kahusecurity.com/posts/registry_dumper_find_and_dump_hidden_registry_keys.html) - Dump your registry.

## Platforms

*Projects that can be used to host a CTF*

- [CTFd](https://github.com/isislab/CTFd) - Platform to host jeopardy style CTFs from ISISLab, NYU Tandon. :star:2391
- [FBCTF](https://github.com/facebook/fbctf) - Platform to host Capture the Flag competitions from Facebook. :star:6149
- [Haaukins](https://github.com/aau-network-security/haaukins)- A Highly Accessible and Automated Virtualization Platform for Security Education.
- [HackTheArch](https://github.com/mcpa-stlouis/hack-the-arch) - CTF scoring platform. :star:52
- [Mellivora](https://github.com/Nakiami/mellivora) - A CTF engine written in PHP. :star:310
- [NightShade](https://github.com/UnrealAkama/NightShade) - A simple security CTF framework. :star:84
- [OpenCTF](https://github.com/easyctf/openctf) - CTF in a box. Minimal setup required. :star:78
- [PicoCTF](https://github.com/picoCTF/picoCTF) - The platform used to run picoCTF. A great framework to host any CTF. :star:128
- [PyChallFactory](https://github.com/pdautry/py_chall_factory) - Small framework to create/manage/package jeopardy CTF challenges. :star:47
- [RootTheBox](https://github.com/moloch--/RootTheBox) - A Game of Hackers (CTF Scoreboard & Game Manager). :star:401
- [Scorebot](https://github.com/legitbs/scorebot) - Platform for CTFs by Legitbs (Defcon). :star:44
- [SecGen](https://github.com/cliffe/SecGen) - Security Scenario Generator. Creates randomly vulnerable virtual machines. :star:1715

## Steganography

*Tools used to create stego challenges*

Check solve section for steganography.

## Web

*Tools used for creating Web challenges*

*JavaScript Obfustcators*

- [Metasploit JavaScript Obfuscator](https://github.com/rapid7/metasploit-framework/wiki/How-to-obfuscate-JavaScript-in-Metasploit) :star:19198
- [Uglify](https://github.com/mishoo/UglifyJS) :star:8163


# Solve

*Tools used for solving CTF challenges*

## Attacks

*Tools used for performing various kinds of attacks*

- [Bettercap](https://github.com/bettercap/bettercap) - Framework to perform MITM (Man in the Middle) attacks. :star:6556
- [Yersinia](https://github.com/tomac/yersinia) - Attack various protocols on layer 2. :star:315

## Crypto

*Tools used for solving Crypto challenges*

- [CyberChef](https://gchq.github.io/CyberChef) - Web app for analysing and decoding data.
- [FeatherDuster](https://github.com/nccgroup/featherduster) - An automated, modular cryptanalysis tool. :star:814
- [Hash Extender](https://github.com/iagox86/hash_extender) - A utility tool for performing hash length extension attacks. :star:576
- [padding-oracle-attacker](https://github.com/KishanBagaria/padding-oracle-attacker) - A CLI tool to execute padding oracle attacks. :star:11
- [PkCrack](https://www.unix-ag.uni-kl.de/~conrad/krypto/pkcrack.html) - A tool for Breaking PkZip-encryption.
- [RSACTFTool](https://github.com/Ganapati/RsaCtfTool) - A tool for recovering RSA private key with various attack. :star:1296
- [RSATool](https://github.com/ius/rsatool) - Generate private key with knowledge of p and q. :star:325
- [XORTool](https://github.com/hellman/xortool) - A tool to analyze multi-byte xor cipher. :star:808

## Bruteforcers

*Tools used for various kind of bruteforcing (passwords etc.)*

- [Hashcat](https://hashcat.net/hashcat/) - Password Cracker
- [Hydra](https://tools.kali.org/password-attacks/hydra) - A parallelized login cracker which supports numerous protocols to attack
- [John The Jumbo](https://github.com/magnumripper/JohnTheRipper) - Community enhanced version of John the Ripper. :star:3228
- [John The Ripper](http://www.openwall.com/john/) - Password Cracker.
- [Nozzlr](https://github.com/intrd/nozzlr) - Nozzlr is a bruteforce framework, trully modular and script-friendly. :star:47
- [Ophcrack](http://ophcrack.sourceforge.net/) - Windows password cracker based on rainbow tables.
- [Patator](https://github.com/lanjelot/patator) - Patator is a multi-purpose brute-forcer, with a modular design. :star:1930

## Exploits

*Tools used for solving Exploits challenges*

- [DLLInjector](https://github.com/OpenSecurityResearch/dllinjector) - Inject dlls in processes. :star:370
- [libformatstr](https://github.com/hellman/libformatstr) - Simplify format string exploitation. :star:301
- [Metasploit](http://www.metasploit.com/) - Penetration testing software.
  - [Cheatsheet](https://www.comparitech.com/net-admin/metasploit-cheat-sheet/)
- [one_gadget](https://github.com/david942j/one_gadget) -  A tool to find the one gadget `execve('/bin/sh', NULL, NULL)` call. :star:954
  - `gem install one_gadget`
- [Pwntools](https://github.com/Gallopsled/pwntools) - CTF Framework for writing exploits. :star:6027
- [Qira](https://github.com/BinaryAnalysisPlatform/qira) - QEMU Interactive Runtime Analyser. :star:2568
- [ROP Gadget](https://github.com/JonathanSalwan/ROPgadget) - Framework for ROP exploitation. :star:2145
- [V0lt](https://github.com/P1kachu/v0lt) - Security CTF Toolkit. :star:309

## Forensics

*Tools used for solving Forensics challenges*

- [Aircrack-Ng](http://www.aircrack-ng.org/) - Crack 802.11 WEP and WPA-PSK keys.
  - `apt-get install aircrack-ng`
- [Audacity](http://sourceforge.net/projects/audacity/) - Analyze sound files (mp3, m4a, whatever).
  - `apt-get install audacity`
- [Bkhive and Samdump2](http://sourceforge.net/projects/ophcrack/files/samdump2/) - Dump SYSTEM and SAM files.
  - `apt-get install samdump2 bkhive`
- [CFF Explorer](http://www.ntcore.com/exsuite.php) - PE Editor.
- [Creddump](https://github.com/moyix/creddump) - Dump windows credentials. :star:156
- [DVCS Ripper](https://github.com/kost/dvcs-ripper) - Rips web accessible (distributed) version control systems. :star:984
- [Exif Tool](http://www.sno.phy.queensu.ca/~phil/exiftool/) - Read, write and edit file metadata.
- [Extundelete](http://extundelete.sourceforge.net/) - Used for recovering lost data from mountable images.
- [Fibratus](https://github.com/rabbitstack/fibratus) - Tool for exploration and tracing of the Windows kernel. :star:512
- [Foremost](http://foremost.sourceforge.net/) - Extract particular kind of files using headers.
  - `apt-get install foremost`
- [Fsck.ext4](http://linux.die.net/man/8/fsck.ext3) - Used to fix corrupt filesystems.
- [Malzilla](http://malzilla.sourceforge.net/) - Malware hunting tool.
- [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) - Network Forensic Analysis Tool.
- [PDF Streams Inflater](http://malzilla.sourceforge.net/downloads.html) - Find and extract zlib files compressed in PDF files.
- [Pngcheck](http://www.libpng.org/pub/png/apps/pngcheck.html) - Verifies the integrity of PNG and dump all of the chunk-level information in human-readable form.
  - `apt-get install pngcheck`
- [ResourcesExtract](http://www.nirsoft.net/utils/resources_extract.html) - Extract various filetypes from exes.
- [Shellbags](https://github.com/williballenthin/shellbags) - Investigate NT\_USER.dat files. :star:100
- [Snow](https://sbmlabs.com/notes/snow_whitespace_steganography_tool) - A Whitespace Steganography Tool.
- [USBRip](https://github.com/snovvcrash/usbrip) - Simple CLI forensics tool for tracking USB device artifacts (history of USB events) on GNU/Linux. :star:765
- [Volatility](https://github.com/volatilityfoundation/volatility) - To investigate memory dumps. :star:3296

*Registry Viewers*
- [OfflineRegistryView](https://www.nirsoft.net/utils/offline_registry_view.html) - Simple tool for Windows that allows you to read offline Registry files from external drive and view the desired Registry key in .reg file format.
- [Registry Viewer®](https://accessdata.com/product-download/registry-viewer-2-0-0) - Used to view Windows registries.

## Networking

*Tools used for solving Networking challenges*

- [Masscan](https://github.com/robertdavidgraham/masscan) - Mass IP port scanner, TCP port scanner. :star:11574
- [Monit](https://linoxide.com/monitoring-2/monit-linux/) - A linux tool to check a host on the network (and other non-network activities). 
- [Nipe](https://github.com/GouveaHeitor/nipe) - Nipe is a script to make Tor Network your default gateway. :star:734
- [Nmap](https://nmap.org/) - An open source utility for network discovery and security auditing.
- [Wireshark](https://www.wireshark.org/) - Analyze the network dumps.
  - `apt-get install wireshark`
- [Zeek](https://www.zeek.org) - An open-source network security monitor.
- [Zmap](https://zmap.io/) - An open-source network scanner.

## Reversing

*Tools used for solving Reversing challenges*

- [Androguard](https://github.com/androguard/androguard) - Reverse engineer Android applications. :star:2833
- [Angr](https://github.com/angr/angr) - platform-agnostic binary analysis framework. :star:3969
- [Apk2Gold](https://github.com/lxdvs/apk2gold) - Yet another Android decompiler. :star:550
- [ApkTool](http://ibotpeaches.github.io/Apktool/) - Android Decompiler.
- [Barf](https://github.com/programa-stic/barf-project) - Binary Analysis and Reverse engineering Framework. :star:1167
- [Binary Ninja](https://binary.ninja/) - Binary analysis framework.
- [BinUtils](http://www.gnu.org/software/binutils/binutils.html) - Collection of binary tools.
- [BinWalk](https://github.com/devttys0/binwalk) - Analyze, reverse engineer, and extract firmware images. :star:5241
- [Boomerang](https://github.com/nemerle/boomerang) - Decompile x86 binaries to C. :star:227
- [ctf_import](https://github.com/docileninja/ctf_import) – run basic functions from stripped binaries cross platform.
- [cwe_checker](https://github.com/fkie-cad/cwe_checker) - cwe_checker finds vulnerable patterns in binary executables. :star:192
- [demovfuscator](https://github.com/kirschju/demovfuscator) - A work-in-progress deobfuscator for movfuscated binaries. :star:502
- [Frida](https://github.com/frida/) - Dynamic Code Injection.
- [GDB](https://www.gnu.org/software/gdb/) - The GNU project debugger.
- [GEF](https://github.com/hugsy/gef) - GDB plugin. :star:2576
- [Ghidra](https://ghidra-sre.org/) - Open Source suite of reverse engineering tools.  Similar to IDA Pro.
- [Hopper](http://www.hopperapp.com/) - Reverse engineering tool (disassembler) for OSX and Linux.
- [IDA Pro](https://www.hex-rays.com/products/ida/) - Most used Reversing software.
- [Jadx](https://github.com/skylot/jadx) - Decompile Android files. :star:20838
- [Java Decompilers](http://www.javadecompilers.com) - An online decompiler for Java and Android APKs.
- [Krakatau](https://github.com/Storyyeller/Krakatau) - Java decompiler and disassembler. :star:1086
- [Objection](https://github.com/sensepost/objection) - Runtime Mobile Exploration. :star:2078
- [PEDA](https://github.com/longld/peda) - GDB plugin (only python2.7). :star:3803
- [Pin](https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool) - A dynamic binary instrumentaion tool by Intel.
- [PINCE](https://github.com/korcankaraokcu/PINCE) - GDB front-end/reverse engineering tool, focused on game-hacking and automation. :star:760
- [PinCTF](https://github.com/ChrisTheCoolHut/PinCTF) - A tool which uses intel pin for Side Channel Analysis. :star:302
- [Plasma](https://github.com/joelpx/plasma) - An interactive disassembler for x86/ARM/MIPS which can generate indented pseudo-code with colored syntax. :star:2814
- [Pwndbg](https://github.com/pwndbg/pwndbg) - A GDB plugin that provides a suite of utilities to hack around GDB easily.  :star:2458
- [radare2](https://github.com/radare/radare2) - A portable reversing framework. :star:11657
- [Triton](https://github.com/JonathanSalwan/Triton/) - Dynamic Binary Analysis (DBA) framework. :star:1410
- [Uncompyle](https://github.com/gstarnberger/uncompyle) - Decompile Python 2.7 binaries (.pyc). :star:390
- [WinDbg](http://www.windbg.org/) - Windows debugger distributed by Microsoft.
- [Xocopy](http://reverse.lostrealm.com/tools/xocopy.html) - Program that can copy executables with execute, but no read permission.
- [Z3](https://github.com/Z3Prover/z3) - A theorem prover from Microsoft Research. :star:4955

*JavaScript Deobfuscators*

- [Detox](http://relentless-coding.org/projects/jsdetox/install) - A Javascript malware analysis tool.
- [Revelo](http://www.kahusecurity.com/posts/revelo_javascript_deobfuscator.html) - Analyze obfuscated Javascript code.

*SWF Analyzers*
- [RABCDAsm](https://github.com/CyberShadow/RABCDAsm) - Collection of utilities including an ActionScript 3 assembler/disassembler. :star:348
- [Swftools](http://www.swftools.org/) - Collection of utilities to work with SWF files.
- [Xxxswf](https://bitbucket.org/Alexander_Hanel/xxxswf) -  A Python script for analyzing Flash files.

## Services

*Various kind of useful services available around the internet*

- [CSWSH](http://cow.cat/cswsh.html) - Cross-Site WebSocket Hijacking Tester.
- [Request Bin](https://requestbin.com/) - Lets you inspect http requests to a particular url.

## Steganography

*Tools used for solving Steganography challenges*

- [AperiSolve](https://aperisolve.fr/) - Aperi'Solve is a platform which performs layer analysis on image (open-source).
- [Convert](http://www.imagemagick.org/script/convert.php) - Convert images b/w formats and apply filters.
- [Exif](http://manpages.ubuntu.com/manpages/trusty/man1/exif.1.html) - Shows EXIF information in JPEG files.
- [Exiftool](https://linux.die.net/man/1/exiftool) - Read and write meta information in files.
- [Exiv2](http://www.exiv2.org/manpage.html) - Image metadata manipulation tool.
- [Image Steganography](https://sourceforge.net/projects/image-steg/) - Embeds text and files in images with optional encryption. Easy-to-use UI.
- [Image Steganography Online](https://incoherency.co.uk/image-steganography) - This is a client-side Javascript tool to steganographically hide images inside the lower "bits" of other images
- [ImageMagick](http://www.imagemagick.org/script/index.php) - Tool for manipulating images.
- [Outguess](https://www.freebsd.org/cgi/man.cgi?query=outguess+&apropos=0&sektion=0&manpath=FreeBSD+Ports+5.1-RELEASE&format=html) - Universal steganographic tool.
- [Pngtools](https://packages.debian.org/sid/pngtools) - For various analysis related to PNGs.
  - `apt-get install pngtools`
- [SmartDeblur](https://github.com/Y-Vladimir/SmartDeblur) - Used to deblur and fix defocused images. :star:1874
- [Steganabara](https://www.openhub.net/p/steganabara) -  Tool for stegano analysis written in Java.
- [Stegbreak](https://linux.die.net/man/1/stegbreak) - Launches brute-force dictionary attacks on JPG image.
- [StegCracker](https://github.com/Paradoxis/StegCracker) - Steganography brute-force utility to uncover hidden data inside files. :star:235
- [stegextract](https://github.com/evyatarmeged/stegextract) - Detect hidden files and text in images. :star:54
- [Steghide](http://steghide.sourceforge.net/) - Hide data in various kind of images.
- [Stegsolve](http://www.caesum.com/handbook/Stegsolve.jar) - Apply various steganography techniques to images.
- [Zsteg](https://github.com/zed-0xff/zsteg/) - PNG/BMP analysis. :star:482

## Web

*Tools used for solving Web challenges*

- [BurpSuite](https://portswigger.net/burp) - A graphical tool to testing website security. 
- [Commix](https://github.com/commixproject/commix) - Automated All-in-One OS Command Injection and Exploitation Tool. :star:2175
- [Hackbar](https://addons.mozilla.org/en-US/firefox/addon/hackbartool/) - Firefox addon for easy web exploitation.
- [OWASP ZAP](https://www.owasp.org/index.php/Projects/OWASP_Zed_Attack_Proxy_Project) - Intercepting proxy to replay, debug, and fuzz HTTP requests and responses
- [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en) - Add on for chrome for debugging network requests.
- [Raccoon](https://github.com/evyatarmeged/Raccoon) - A high performance offensive security tool for reconnaissance and vulnerability scanning. :star:1654
- [SQLMap](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tool. :star:15996
  ```pip install sqlmap```
- [W3af](https://github.com/andresriancho/w3af) -  Web Application Attack and Audit Framework. :star:2977
- [XSSer](http://xsser.sourceforge.net/) - Automated XSS testor.


# Resources

*Where to discover about CTF*

## Operating Systems

*Penetration testing and security lab Operating Systems*

- [Android Tamer](https://androidtamer.com/) - Based on Debian.
- [BackBox](https://backbox.org/) - Based on Ubuntu.
- [BlackArch Linux](https://blackarch.org/) - Based on Arch Linux.
- [Fedora Security Lab](https://labs.fedoraproject.org/security/) - Based on Fedora.
- [Kali Linux](https://www.kali.org/) - Based on Debian.
- [Parrot Security OS](https://www.parrotsec.org/) - Based on Debian.
- [Pentoo](http://www.pentoo.ch/) - Based on Gentoo.
- [URIX OS](http://urix.us/) - Based on openSUSE.
- [Wifislax](http://www.wifislax.com/) - Based on Slackware.

*Malware analysts and reverse-engineering*

- [Flare VM](https://github.com/fireeye/flare-vm/) - Based on Windows. :star:1755
- [REMnux](https://remnux.org/) - Based on Debian.

## Starter Packs

*Collections of installer scripts, useful tools*

- [CTF Tools](https://github.com/zardus/ctf-tools) - Collection of setup scripts to install various security research tools. :star:4454
- [LazyKali](https://github.com/jlevitsk/lazykali) - A 2016 refresh of LazyKali which simplifies install of tools and configuration. :star:31

## Tutorials

*Tutorials to learn how to play CTFs*

- [CTF Field Guide](https://trailofbits.github.io/ctf/) - Field Guide by Trails of Bits.
- [CTF Resources](http://ctfs.github.io/resources/) -  Start Guide maintained by community.
- [Damn Vulnerable Web Application](http://www.dvwa.co.uk/) PHP/MySQL web application that is damn vulnerable.
- [How to Get Started in CTF](https://www.endgame.com/blog/how-get-started-ctf) - Short guideline for CTF beginners by Endgame
- [LiveOverFlow](https://www.youtube.com/channel/UClcE-kVhqyiHCcjYwcpfj9w) - Video tutorials on Exploitation.
- [MIPT CTF](https://github.com/xairy/mipt-ctf) - A small course for beginners in CTFs (in Russian). :star:196

## Wargames

*Always online CTFs*

- [Backdoor](https://backdoor.sdslabs.co/) - Security Platform by SDSLabs.
- [Crackmes](https://crackmes.one/) - Reverse Engineering Challenges.
- [Exploit Exercises](https://exploit-exercises.lains.space/) - Variety of VMs to learn variety of computer security issues.
- [Exploit.Education](http://exploit.education) - Variety of VMs to learn variety of computer security issues.
- [Gracker](https://github.com/Samuirai/gracker) - Binary challenges having a slow learning curve, and write-ups for each level. :star:4
- [Hack The Box](https://www.hackthebox.eu) - Weekly CTFs for all types of security enthusiasts.
- [Hack This Site](https://www.hackthissite.org/) - Training ground for hackers.
- [Hacking-Lab](https://hacking-lab.com/) - Ethical hacking, computer network and security challenge platform.
- [Hone Your Ninja Skills](https://honeyourskills.ninja/) - Web challenges starting from basic ones.
- [IO](http://io.netgarage.org/) - Wargame for binary challenges.
- [Microcorruption](https://microcorruption.com) - Embedded security CTF.
- [Over The Wire](http://overthewire.org/wargames/) - Wargame maintained by OvertheWire Community.
- [PentesterLab](https://pentesterlab.com/) - Variety of VM and online challenges (paid).
- [PWN Challenge](http://pwn.eonew.cn/) - Binary Exploitation Wargame.
- [Pwnable.kr](http://pwnable.kr/) - Pwn Game.
- [Pwnable.tw](https://pwnable.tw/) - Binary wargame.
- [Pwnable.xyz](https://pwnable.xyz/) - Binary Exploitation Wargame.
- [Reversin.kr](http://reversing.kr/) - Reversing challenge.
- [Ringzer0Team](https://ringzer0team.com/) - Ringzer0 Team Online CTF.
- [Root-Me](https://www.root-me.org/) - Hacking and Information Security learning platform.
- [ROP Wargames](https://github.com/xelenonz/game) - ROP Wargames. :star:12
- [SANS HHC](https://holidayhackchallenge.com/past-challenges/) - Challenges with a holiday theme
  released annually and maintained by SANS.
- [SmashTheStack](http://smashthestack.org/) - A variety of wargames maintained by the SmashTheStack Community.
- [Viblo CTF](https://ctf.viblo.asia) - Various amazing CTF challenges, in many different categories. Has both Practice mode and Contest mode.
- [VulnHub](https://www.vulnhub.com/) - VM-based for practical in digital security, computer application & network administration.
- [W3Challs](https://w3challs.com) - A penetration testing training platform, which offers various computer challenges, in various categories.
- [WebHacking](http://webhacking.kr) - Hacking challenges for web.

*Self-hosted CTFs*

- [Juice Shop CTF](https://github.com/bkimminich/juice-shop-ctf) - Scripts and tools for hosting a CTF on [OWASP Juice Shop](https://www.owasp.org/index.php/OWASP_Juice_Shop_Project) easily. :star:162

## Websites

*Various general websites about and on CTF*

- [CTF Time](https://ctftime.org/) - General information on CTF occuring around the worlds.
- [Reddit Security CTF](http://www.reddit.com/r/securityctf) - Reddit CTF category.

## Wikis

*Various Wikis available for learning about CTFs*

- [Bamboofox](https://bamboofox.github.io/) - Chinese resources to learn CTF.
- [bi0s Wiki](https://teambi0s.gitlab.io/bi0s-wiki/) - Wiki from team bi0s.
- [ISIS Lab](https://github.com/isislab/Project-Ideas/wiki) - CTF Wiki by Isis lab. :star:347
- [OpenToAll](https://github.com/OpenToAllCTF/Tips) - CTF tips by OTA CTF team members. :star:70

## Writeups Collections

*Collections of CTF write-ups*

- [0e85dc6eaf](https://github.com/0e85dc6eaf/CTF-Writeups) - Write-ups for CTF challenges by 0e85dc6eaf :star:63
- [Captf](http://captf.com/) - Dumped CTF challenges and materials by psifertex.
- [CTF write-ups (community)](https://github.com/ctfs/) - CTF challenges + write-ups archive maintained by the community.
- [CTFTime Scrapper](https://github.com/abdilahrf/CTFWriteupScrapper) - Scraps all writeup from CTF Time and organize which to read first. :star:20
- [HackThisSite](https://github.com/HackThisSite/CTF-Writeups) - CTF write-ups repo maintained by HackThisSite team. :star:88
- [Mzfr](https://github.com/mzfr/ctf-writeups/) - CTF competition write-ups by mzfr :star:87
- [pwntools writeups](https://github.com/Gallopsled/pwntools-write-ups) - A collection of CTF write-ups all using pwntools. :star:357
- [SababaSec](https://github.com/SababaSec/ctf-writeups) - A collection of CTF write-ups by the SababaSec team :star:7
- [Shell Storm](http://shell-storm.org/repo/CTF/) - CTF challenge archive maintained by Jonathan Salwan.
- [Smoke Leet Everyday](https://github.com/smokeleeteveryday/CTF_WRITEUPS) - CTF write-ups repo maintained by SmokeLeetEveryday team. :star:168

### LICENSE

CC0 :)


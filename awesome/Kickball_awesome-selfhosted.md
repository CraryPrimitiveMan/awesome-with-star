# Information comes from [Kickball/awesome-selfhosted](https://github.com/Kickball/awesome-selfhosted)
# Awesome-Selfhosted

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![](https://img.shields.io/travis/Kickball/awesome-selfhosted/monthly-check?label=link%20checks)](https://github.com/Kickball/awesome-selfhosted/issues/1767)

Selfhosting is the process of locally hosting and managing applications instead of renting from SaaS providers.

This is a list of [Free](https://en.wikipedia.org/wiki/Free_software) Software [network services](https://en.wikipedia.org/wiki/Network_service) and [web applications](https://en.wikipedia.org/wiki/Web_application) which can be hosted locally. Non-Free software is listed on the [Non-Free](non-free.md) page.

See [Contributing](.github/CONTRIBUTING.md).

--------------------

- List of Software
  - [Analytics](#analytics)
  - [Archiving and Digital Preservation (DP)](#archiving-and-digital-preservation-dp)
  - [Automation](#automation)
  - [Blogging Platforms](#blogging-platforms)
  - [Bookmarks and Link Sharing](#bookmarks-and-link-sharing)
  - [Calendaring and Contacts Management](#calendaring-and-contacts-management)
  - [Communication systems](#communication-systems)
    - [Custom communication systems](#custom-communication-systems)
    - [Email](#email)
      - [Complete solutions](#complete-solutions)
      - [Mail Transfer Agents](#mail-transfer-agents)
      - [Mail Delivery Agents](#mail-delivery-agents)
      - [Mailing lists and newsletters](#mailing-lists-and-newsletters)
      - [Webmail clients](#webmail-clients)
    - [IRC](#irc)
    - [SIP/IPBX](#sip)
    - [Social Networks and Forums](#social-networks-and-forums)
    - [XMPP](#xmpp)
      - [XMPP Servers](#xmpp-servers)
      - [XMPP Web Clients](#xmpp-web-clients)
  - [Conference Management](#conference-management)
  - [Content Management Systems (CMS)](#content-management-systems-cms)
    - [E-commerce](#e-commerce)
  - [DNS](#dns)
  - [Document Management](#document-management)
  - [E-books and Integrated Library Systems (ILS)](#e-books-and-integrated-library-systems-ils)
  - [Federated Identity/Authentication](#federated-identityauthentication)
  - [Feed Readers](#feed-readers)
  - [File Sharing and Synchronization](#file-sharing-and-synchronization)
    - [Distributed filesystems](#distributed-filesystems)
    - [File transfer/synchronization](#file-transfersynchronization)
    - [Peer-to-peer filesharing](#peer-to-peer-filesharing)
    - [Object storage/file servers](#object-storagefile-servers)
    - [Single-click/drag-n-drop upload](#single-clickdrag-n-drop-upload)
    - [Web based file managers](#web-based-file-managers)
  - [Games](#games)
  - [Gateways](#gateways)
  - [Groupware](#groupware)
  - [Human Resources Management (HRM)](#human-resources-management-hrm)
  - [Internet of Things (IoT)](#internet-of-things-iot)
  - [Knowledge Management Tools](#knowledge-management-tools)
  - [Learning and Courses](#learning-and-courses)
  - [Maps and Global Positioning System (GPS)](#maps-and-global-positioning-system-gps)
  - [Media Streaming](#media-streaming)
    - [Multimedia Streaming](#multimedia-streaming)
    - [Audio Streaming](#audio-streaming)
    - [Video Streaming](#video-streaming)
  - [Misc/Other](#miscother)
  - [Money, Budgeting and Management](#money-budgeting-and-management)
  - [Monitoring](#monitoring)
  - [Note-taking and Editors](#note-taking-and-editors)
  - [Office Suites](#office-suites)
  - [Password Managers](#password-managers)
  - [Pastebins](#pastebins)
  - [Personal Dashboards](#personal-dashboards)
  - [Photo and Video Galleries](#photo-and-video-galleries)
  - [Polls and Events](#polls-and-events)
    - [Booking and Scheduling](#booking-and-scheduling)
  - [Proxy](#proxy)
  - [Read it Later Lists](#read-it-later-lists)
  - [Resource Planning](#resource-planning)
    - [Enterprise Resource Planning](#enterprise-resource-planning)
  - [Search Engines](#search-engines)
  - [Software Development](#software-development)
    - [Project Management](#project-management)
    - [Bug Trackers](#bug-trackers)
    - [IDE/Tools](#idetools)
    - [Continuous Integration](#continuous-integration)
    - [UX testing](#ux-testing)
    - [FaaS/Serverless](#faasserverless)
    - [API Management](#api-management)
    - [Documentation Generators](#documentation-generators)
    - [Localization](#localization)
  - [Static site generators](#static-site-generators)
  - [Task management/To-do lists](#task-managementto-do-lists)
  - [Ticketing](#ticketing)
  - [URL Shorteners](#url-shorteners)
  - [VPN](#vpn)
  - [Web servers](#web-servers)
  - [Wikis](#wikis)
- [Self-hosting Solutions](#self-hosting-solutions)
- [List of Licenses](#list-of-licenses)
- [External links](#external-links)
- [Contributing](#contributing)
- [License](#license)

--------------------

<!-- BEGIN SOFTWARE LIST -->

## Analytics
For personal analytics/dashboards, see [Personal Dashboards](#personal-dashboards)

**[`^        back to top        ^`](#)**

_Web Analytics_

- [AWStats](http://www.awstats.org/) - Generates web, streaming, ftp or mail server statistics graphically. ([Source Code](https://github.com/eldy/awstats)) `GPL-3.0` `Perl`
- [Countly](https://count.ly) - Real time mobile and web analytics, crash reporting and push notifications platform. ([Source Code](https://github.com/countly)) `AGPL-3.0` `Javascript`
- [Druid](http://druid.io/) - Distributed, column-oriented, real-time analytics data store. ([Source Code](https://github.com/druid-io/druid)) `Apache-2.0` `Java`
- [Fathom Analytics](https://usefathom.com) - Simple & trustworthy website analytics. ([Source Code](https://github.com/usefathom/fathom)) `MIT` `Go`
- [GoAccess](http://goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal. ([Source Code](https://github.com/allinurl/goaccess)) `GPL-2.0` `C`
- [Hastic](https://hastic.io) - Hackable time series pattern recognition tool with UI for Grafana. ([Source Code](https://github.com/hastic)) `Apache-2.0` `Python/Nodejs`
- [KISSS](https://kis3.dev) - Very minimalistic (KISS) website statistics tool. ([Source Code](https://github.com/kis3/kis3)) `MIT` `Go`
- [Matomo](https://matomo.org/) - Leading open-source analytics platform that gives you more than just powerful analytics, formerly known as Piwik. ([Source Code](https://github.com/matomo-org/)) `GPL-3.0` `PHP`
- [Open Web Analytics](http://www.openwebanalytics.com/) - Google Analytics and Piwik alternative. ([Source Code](https://github.com/padams/Open-Web-Analytics)) `GPL-2.0` `PHP`
- [Rakam](https://rakam.io/) - Custom analytics platform that allows you to create your own analytics services. Integrate with any data source (web, mobile, IoT etc.), analyze data with SQL and create dashboards. ([Source Code](https://github.com/rakam-io/rakam)) `Apache-2.0` `Java`
- [Serposcope](https://serposcope.serphacker.com/) - Serposcope is a free and open-source rank tracker to monitor websites ranking in Google and improve your SEO performances. ([Source Code](https://github.com/serphacker/serposcope)) `MIT` `Java`
- [Snowplow](http://snowplowanalytics.com/) - Have every single event, from your websites, mobile apps, desktop applications and server-side systems, stored in your own data warehouse and available to action in real-time. ([Source Code](https://github.com/snowplow/)) `Apache-2.0` `Scala`
- [Suet](https://suet.co/) `⚠` - Detailed analytics and reporting for your Mailgun transactional emails. ([Source Code](https://github.com/kehers/suet)) `GPL-3.0` `Nodejs`

_Business Intelligence_

- [Metabase](http://www.metabase.com/) - Simple Dashboarding and GUI Query tool, Nightly Emails and Slack Integration w/ PostgreSQL, MySQL, Redshift and other DBs. ([Source Code](https://github.com/metabase/metabase)) `AGPL-3.0` `Clojure`
- [Redash](http://redash.io) - connect to over 18 types of databases (SQL and "NoSQL"), query your data, visualize it and create dashboards. Everything has a URL that can be shared. Slack and HipChat integration. ([Demo](https://demo.redash.io), [Source Code](https://github.com/getredash/redash)) `BSD-2-Clause` `Python`
- [Superset](http://superset.apache.org/) - Modern, enterprise-ready business intelligence web application. ([Source Code](https://github.com/apache/incubator-superset)) `Apache-2.0` `Python`

_Social Media_

- [IG Monitoring](https://igmonitoring.com) -  `⚠` Instagram Analytics and Stats. ([Demo](https://demo.igmonitoring.com), [Source Code](https://github.com/jakim/ig-monitoring)) `MIT` `PHP`

## Archiving and Digital Preservation (DP)

**[`^        back to top        ^`](#)**

Some [Content Management System](#content-management-systems-cms) solutions also feature archiving and digital preservation.

- [Access to Memory (AtoM)](https://www.accesstomemory.org/) - Web-based, open source application for standards-based archival description and access in a multilingual, multi-repository environment. ([Demo](https://demo.accesstomemory.org/), [Source Code](https://github.com/artefactual/atom)) `AGPL-3.0-only` `PHP`
- [Archivematica](https://www.archivematica.org/) - Mature digital preservation system designed to maintain standards-based, long-term access to collections of digital objects. ([Demo](http://sandbox.archivematica.org/administration/accounts/login/), [Source Code](https://github.com/artefactual/archivematica)) `AGPL-3.0-only` `Python`
- [ArchiveBox](https://archivebox.io/) - Self-hosted "wayback machine" that creates HTML & screenshot archives of sites from your bookmarks, browsing history, RSS feeds, or other sources. ([Demo](https://archive.sweeting.me), [Source Code](https://github.com/pirate/bookmark-archiver)) `MIT` `Python`
- [ArchivesSpace](https://archivesspace.org/) - Archives information management application for managing and providing Web access to archives, manuscripts and digital objects. ([Demo](https://archivesspace.org/application/demo/), [Source Code](https://github.com/archivesspace/archivesspace)) `ECL-2.0` `Ruby`
- [Collective Access: Providence](http://collectiveaccess.org/) - Highly configurable Web-based framework for management, description, and discovery of digital and physical collections supporting a variety of metadata standards, data types, and media formats. ([Source Code](https://github.com/collectiveaccess/providence)) `GPL-3.0-only` `PHP`

## Automation

**[`^        back to top        ^`](#)**

- [Alltube](http://www.alltubedownload.net) - Web interface for [youtube-dl](https://github.com/rg3/youtube-dl), a program to download videos and audio from [more than 100 websites](https://rg3.github.io/youtube-dl/supportedsites.html). ([Source Code](https://github.com/Rudloff/alltube)) `GPL-3.0` `PHP`
- [AmIUnique](https://amiunique.org/) - Learn how identifiable you are on the Internet (browser fingerprinting tool). ([Source Code](https://github.com/DIVERSIFY-project/amiunique)) `MIT` `Java`
- [Beehive](https://github.com/muesli/beehive) - Flexible event and agent system, which allows you to create your own agents that perform automated tasks triggered by events and filters. `AGPL-3.0` `Go` :star:3861
- [CouchPotato](https://couchpota.to/) - CouchPotato is an automatic Video Library Manager for Movies. Automatic torrent/nzb searching, downloading, and processing at the qualities you want. ([Source Code](https://github.com/CouchPotato/CouchPotatoServer)) `GPL-3.0` `Python`
- [Episodes](https://github.com/guptachetan1997/Episodes) `⚠` - Self Hosted TV show Episode tracker and recommender built using django, bootstrap4. `MIT` `Python`
- [feed2toot](https://feed2toot.readthedocs.io/) - Feed2toot parses a RSS feed, extracts the last entries and sends them to Mastodon. ([Source Code](https://gitlab.com/chaica/feed2toot)) `GPL-3.0` `Python`
- [feedmixer](https://github.com/cristoper/feedmixer) - FeedMixer is a WSGI (Python3) micro web service which takes a list of feed URLs and returns a new feed consisting of the most recent n entries from each given feed(Returns Atom, RSS, or JSON). ([Demo](https://mretc.net/feedmixer/json?f=http://hnrss.org/newest&f=http://americancynic.net/atom.xml&n=1)) `WTFPL` `Python` :star:22
- [FHEM](https://fhem.de/fhem.html) - FHEM is used to automate common tasks in the household like switching lamps and heating. It can also be used to log events like temperature or power consumption. You can control it via web or smartphone frontends, telnet or TCP/IP directly. ([Source Code](https://svn.fhem.de/trac)) `GPL-3.0` `Perl`
- [Gekko](https://gekko.wizb.it/) - Gekko is a Bitcoin TA trading and backtesting bot which support multiple exchanges and cryptocurrencies. ([Source Code](https://github.com/askmike/gekko)) `MIT` `Nodejs`
- [Gladys](https://gladysproject.com) - Gladys is an open-source home assistant which runs on your Raspberry Pi. ([Source Code](https://github.com/GladysProject/Gladys)) `MIT` `Nodejs`
- [Headphones](https://github.com/rembo10/headphones) - Automated music downloader for NZB and Torrent, written in Python. It supports SABnzbd, NZBget, Transmission, µTorrent, Deluge and Blackhole. `GPL-3.0` `Python` :star:2809
- [Healthchecks](https://healthchecks.io/) - Django app which listens for pings and sends alerts when pings are late. ([Source Code](https://github.com/healthchecks/healthchecks)) `BSD-3-Clause` `Python`
- [Home Assistant](https://home-assistant.io/) - Open-source home automation platform. ([Demo](https://home-assistant.io/demo/), [Source Code](https://github.com/home-assistant/home-assistant)) `MIT` `Python`
- [homebank-converter](https://github.com/Binnette/homebank-converter) - Web app to convert an export bank file to compatible Homebank csv. ([Demo](http://binnette.github.io/homebank-converter/)) `AGPL-3.0` `HTML5` :star:20
- [HRConvert2](https://www.honestrepair.net/index.php/hrconvert2/) - Drag-and-drop file conversion server with session based authentication, automatic temporary file maintenance, and logging capability. ([Demo](https://www.honestrepair.net/index.php/convert/), [Source Code](https://github.com/zelon88/HRConvert2)) `GPL-3.0` `PHP`
- [Huginn](https://github.com/cantino/huginn) - Allows you to build agents that monitor and act on your behalf. `MIT` `Ruby` :star:22049
- [Http2pic](https://http2pic.haschek.at/) - Website screenshots/renderer. It uses the wkhtmltox to render websites with various options. ([Source Code](https://github.com/chrisiaut/http2pic)) `Apache 2.0` `PHP/Javascript`
- [Kibitzr](https://kibitzr.github.io) - Lightweight personal web assistant with powerful integrations. ([Source Code](https://github.com/kibitzr/kibitzr)) `MIT` `Python`
- [LazyLibrarian](https://gitlab.com/LazyLibrarian/LazyLibrarian) `⚠` - LazyLibrarian is a program to follow authors and grab metadata for all your digital reading needs. It uses a combination of Goodreads Librarything and optionally GoogleBooks as sources for author info and book info. `GPL-3.0` `Python`
- [Leon](https://getleon.ai) - Open-source personal assistant who can live on your server. ([Demo](https://www.youtube.com/watch?v=p7GRGiicO1c), [Source Code](https://github.com/leon-ai/leon)) `MIT` `Node.js`
- [Lidarr](https://lidarr.audio/) - Lidarr is a music collection manager for Usenet and BitTorrent users. ([Source Code](https://github.com/Lidarr/Lidarr)) `GPL-3.0` `C#`
- [Medusa](https://github.com/pymedusa/SickRage) - Automatic Video Library Manager for TV Shows. It watches for new episodes of your favorite shows, and when they are posted it does its magic. `GPL-3.0` `Python` :star:940
- [Node RED](http://nodered.org/) - Browser-based flow editor that helps you wiring hardware devices, APIs and online services to create IoT solutions. ([Source Code](https://github.com/node-red/node-red)) `Apache-2.0` `Nodejs`
- [openHAB](http://www.openhab.org) - Vendor and technology agnostic open source software for home automation. ([Source Code](https://github.com/openhab/openhab)) `EPL-1.0` `Java`
- [PolitePol](https://github.com/taroved/pol) - Online tool for creation of RSS feeds for any web page. ([Demo](http://politepol.com)) `MIT` `Python` :star:116
- [Poffer](http://poffer.gabinaureche.com) `⚠` - Tool that makes it easier to share the content you like thanks to Pocket+Buffer. ([Source Code](https://github.com/Zhouzi/Poffer)) `MIT` `Nodejs`
- [pyLoad](https://pyload.net/) - Lightweight, customizable and remotely manageable downloader for 1-click-hosting sites like rapidshare.com or uploaded.to. ([Source Code](https://github.com/pyload/pyload)) `GPL-3.0` `Python`
- [Radarr](https://radarr.video/) - Radarr is an independent fork of Sonarr reworked for automatically downloading movies via Usenet and BitTorrent, à la Couchpotato. ([Source Code](https://github.com/Radarr/Radarr)) `GPL-3.0` `C#`
- [RSS-Bridge](https://github.com/sebsauvage/rss-bridge) - rss-bridge is a PHP project capable of generating ATOM feeds for websites which don't have one. `Public domain` `PHP` :star:1749
- [RSS Fulltext Proxy](https://github.com/Kombustor/rss-fulltext-proxy) - Mirrors RSS feeds to return the full content of the items, extracted from the website. `MIT` `NodeJS` :star:30
- [RSS Merger](https://github.com/taophp/rss-merger) - PHP script which will take multiple RSS / Atom feeds as input and merge them into a single RSS feed. `GPL-2.0` `PHP` :star:19
- [SickRage](http://sickrage.github.io/) - SickRage is an automatic Video Library Manager for TV Shows. Automatic torrent/nzb searching, downloading, and processing at the qualities you want. ([Source Code](https://github.com/SickRage/SickRage)) `GPL-3.0` `Python`
- [Sonarr](https://sonarr.tv/) - Automatic TV Shows downloader and manager for Usenet and BitTorrent. It can grab, sort and rename new episodes and automatically upgrade the quality of files already downloaded when a better quality format becomes available. ([Source Code](https://github.com/Sonarr/Sonarr)) `GPL-3.0` `C#`
- [TriggerHappy](https://trigger-happy.readthedocs.io/en/latest/) - Open source clone of IFTTT, a bridge between your internet services. ([Source Code](https://github.com/foxmask/django-th)) `BSD-3-Clause` `Python`
- [WebUI-aria2](https://github.com/ziahamza/webui-aria2) - Interface to interact with the aria2 downloader. Very simple to use, just download and open index.html in any web browser. ([Demo](http://ziahamza.github.io/webui-aria2/)) `MIT` `HTML5` :star:6738
- [WTFDYUM](https://www.wtfdyu.me/) `⚠` - Why The Fuck Did You Unfollow Me - Find out who stops following you on Twitter. ([Source Code](https://github.com/jchampemont/WTFDYUM)) `Apache-2.0` `Java`
- [Zenbot 3](https://github.com/carlos8f/zenbot) - Zenbot is a lightweight, extendable, artificially intelligent trading bot for Bitcoin, Ether, Litecoin, and more. `MIT` `Node.js` :star:6042

## Blogging Platforms

**[`^        back to top        ^`](#)**

See also [Static Site Generators](#static-site-generators), [Content Management Systems](#content-management-systems-cms) and [WeblogMatrix](http://www.weblogmatrix.org/)

- [Anchor CMS](https://anchorcms.com/) - Free, lightweight, faster-than-a-bullet, simple blogging system, made for art–directed posts. ([Source Code](https://github.com/anchorcms/anchor-cms)) `GPL-3.0` `PHP`
- [Antville](https://antville.org) - Free, open source project aimed at the development of a high performance, feature rich weblog hosting software. ([Source Code](https://github.com/antville/antville)) `Apache-2.0` `Javascript`
- [Blogotext](http://lehollandaisvolant.net/blogotext/) - Free blog-engine written in PHP and using SQLite. This offers you both an unmatched simplicity during installation and great performances. ([Source Code](https://github.com/timovn/blogotext)) `MIT` `PHP`
- [Bludit](https://www.bludit.com/) `⚠` - Simple application to build a site or blog in seconds. Bludit uses flat-files (text files in JSON format) to store posts and pages. ([Demo](https://demo.bludit.com/), [Source Code](https://github.com/dignajar/bludit)) `MIT` `PHP`
- [Cadmus](https://github.com/liamdemafelix/cadmus) - Cadmus is an extremely lightweight, flat-file blogging platform powered by Markdown. `MIT` `PHP` :star:6
- [Chyrp Lite](http://chyrplite.net) - Extra-awesome, extra-lightweight blog engine. ([Source Code](https://github.com/xenocrat/chyrp-lite)) `BSD-3-Clause` `PHP`
- [Dante Stories](https://dante-stories.herokuapp.com/) - A self hosted Medium platform built with Ruby on Rails. ([Source Code](https://github.com/michelson/dante-stories)) `MIT` `Ruby`
- [Dotclear](http://dotclear.org/) - Take control over your blog. ([Source Code](https://hg.dotclear.org/dotclear)) `GPL-2.0` `PHP`
- [Formtools](https://formtools.org/) - Powerful, flexible, free and open source PHP/MySQL script to manage your forms and data. ([Source Code](https://github.com/formtools)) `GPL-2.0` `PHP`
- [Ghost](https://ghost.org/) - Just a blogging platform. ([Source Code](https://github.com/TryGhost/Ghost)) `MIT` `Nodejs`
- [Hexo](https://hexo.io/) - Fast, simple and powerful blog framework, powered by Node.js. ([Source Code](https://github.com/hexojs/hexo)) `MIT` `Nodejs`
- [Hotglue](https://hotglue.me/) - Freehand CMS which allows to construct websites directly in a web-browser. It uses flat files for storage and provides an intuitive GUI. ([Demo](https://hotglue.me/demo/), [Source Code](https://github.com/k0a1a/hotglue2)) `GPL-3.0` `PHP`
- [htmly](https://www.htmly.com/) - Databaseless Blogging Platform (Flat-File Blog). ([Demo](https://www.htmly.com/demo/), [Source Code](https://github.com/danpros/htmly)) `GPL-2.0` `PHP`
- [Known](https://withknown.com/) - Single website for all your content. ([Source Code](https://github.com/idno/idno)) `Apache-2.0` `PHP`
- [Noddity](http://noddity.com/) - It's a blog, it's a wiki, it's a fast CMS. ([Source Code](https://github.com/TehShrike/noddity)) `WTFPL` `Nodejs`
- [Plume](https://joinplu.me/) - Federated blogging engine, based on ActivityPub. ([Source Code](https://github.com/Plume-org/Plume)) `AGPL-3.0` `Ruby`
- [PluXml](http://www.pluxml.org/) - XML-based blog/CMS platform. ([Source Code](https://github.com/pluxml/PluXml)) `GPL-1.0` `PHP`
- [Postleaf](https://www.postleaf.org/) - Open source blogging platform with inline editing, handlebar templates, and a beautiful user interface. ([Source Code](https://github.com/Postleaf/postleaf)) `MIT` `Nodejs`
- [Solo](http://b3log.org/) - Blogging system written in Java, feel free to create your or your team own blog. ([Demo](http://88250.b3log.org/), [Source Code](https://github.com/b3log/solo)) `Apache-2.0` `Java`


## Bookmarks and Link Sharing

**[`^        back to top        ^`](#)**

- [dyu/bookmarks](https://github.com/dyu/bookmarks) - Single-threaded/process bookmark app powered by leveldb and uWebSockets. Supports importing from Delicious and Chrome. ([Demo](https://dyuproject.com/bookmarks/)) `Apache-2.0` `Java` :star:65
- [Espial](https://github.com/jonschoning/espial) - An open-source, web-based bookmarking server. `AGPL-3.0` `Haskell` :star:88
- [Firefox Auth Server](https://docs.services.mozilla.com/howtos/run-fxa.html) - This project implements the core server-side API for Firefox Accounts. ([Source Code](https://github.com/mozilla/fxa-auth-server)) `MPL-2.0` `Nodejs`
  - [Firefox Content Server](https://docs.services.mozilla.com/howtos/run-fxa.html) - Static server that hosts Firefox Account sign up, sign in, email verification, etc. flows. ([Source Code](https://github.com/mozilla/fxa-content-server)) `MPL-2.0` `Java`
  - [Firefox Sync Server](https://docs.services.mozilla.com/howtos/run-sync-1.5.html) - Sync Firefox bookmarks, passwords, history, tabs, preferences. ([Source Code](https://github.com/mozilla-services/syncserver)) `MPL-2.0` `Python`
- [Geekmarks](https://geekmarks.dmitryfrank.com/) - Personal bookmarking service focused on speed and organization using hierarchical tags. ([Source Code](https://github.com/dimonomid/geekmarks)) `BSD-2-Clause` `Go`
- [golinks](https://github.com/prologic/golinks) - Web application that allows you to create smart bookmarks, commands and aliases by pointing your web browser's default search engine at a running instance. Similar to bunny1 or yubnub. ([Demo](https://search.mills.io)) `MIT` `Go` :star:93
- [Lobsters](https://lobste.rs) - Run your own link aggregation site. ([Source Code](https://github.com/jcs/lobsters)) `BSD-3-Clause` `Ruby`
- [No Fuss Bookmarks](http://nofussbm.herokuapp.com/signup.html) - Very simple software and service to store bookmarks especially designed for hackers (that don't need fancy interfaces, but nice API). ([Source Code](https://github.com/mapio/nofussbm)) `GPL-3.0` `Python`
- [Pinry](http://getpinry.com/) - The tiling image board system for people who want to save, tag, and share images, videos, and webpages. ([Source Code](https://github.com/pinry/pinry)) `BSD-2-Clause` `Python`
- [Shaarli](https://github.com/shaarli/Shaarli) - Personal, minimalist, super-fast, no-database bookmarking and link sharing platform. ([Demo](https://demo.shaarli.org)) `Zlib` `PHP` :star:1541
- [Shiori](https://github.com/RadhiFadlillah/shiori) - Simple bookmark manager built with Go. `MIT` `Go` :star:2102
- [unmark](https://github.com/plainmade/unmark) - Open source to do app for links. `MIT` `PHP` :star:1195
- [xBrowserSync](https://www.xbrowsersync.org) - Open source tool for syncing browser data between browsers and devices. ([Source Code](https://github.com/xBrowserSync)) `MIT` `Nodejs`
- [ymarks](https://bitbucket.org/ymarks/ymarks-server) - Keep your browser's bookmarks synchronized without limiting yourself to one provider. `WTFPL` `C`


## Calendaring and Contacts Management

**[`^        back to top        ^`](#)**

Some [Groupware](#groupware) solutions also feature calendar/address book editing and synchronization.

See https://en.wikipedia.org/wiki/Comparison_of_CalDAV_and_CardDAV_implementations

_CalDAV or CardDAV servers_

- [Baïkal](http://sabre.io/baikal/) - Lightweight CalDAV and CardDAV server based on sabre/dav. ([Source Code](https://github.com/sabre-io/Baikal)) `GPL-3.0` `PHP`
- [CalendarServer](https://www.calendarserver.org/) - Apple, Inc.'s standards-compliant server implementing the CalDAV and CardDAV protocols shipped with macOS Server. ([Source Code](https://github.com/apple/ccs-calendarserver)) `Apache-2.0` `Python`
- [calypso](https://keithp.com/calypso/) - Python-based CalDAV and CardDAV server, forked from Radicale. ([Source Code](https://keithp.com/git/calypso.git)) `GPL-3.0` `Python`
- [DAViCal](https://www.davical.org/) - Server for calendar sharing (CalDAV) that uses a PostgreSQL database as a data store. ([Source Code](https://gitlab.com/davical-project/davical)) `GPL-2.0` `PHP`
- [DecSync CC](https://f-droid.org/packages/org.decsync.cc/) - Serverless contacts, calendar synchronization using your own file syncing method i.e Syncthing, Nextcloud etc. ([Source Code](https://github.com/39aldo39/DecSyncCC)) `GPL-3.0` `Kotlin`
- [EteSync Server](https://www.etesync.com) - End-to-end encrypted and journaled personal information server supporting calendar and contact data, offering its own clients. ([Source Code](https://github.com/etesync/server-skeleton)) `AGPL-3.0` `Python/Django`
- [Radicale](http://radicale.org/) - Simple calendar and contact server with extremely low administrative overhead. ([Source Code](https://github.com/Kozea/Radicale)) `GPL-3.0` `Python`
- [SabreDAV](http://sabre.io/) - Open source CardDAV, CalDAV, and WebDAV framework and server. ([Source Code](https://github.com/sabre-io/dav)) `MIT` `PHP`
- [Xandikos](https://www.xandikos.org/) - Open source CardDAV, CalDAV and WebDAV server with minimal administrative overhead, backed by a Git repository. ([Source Code](https://github.com/jelmer/xandikos)) `GPL-3.0` `Python`

_CalDAV or CardDAV clients._

- [AgenDAV](http://agendav.org/) - Multilanguage CalDAV web client with a rich AJAX interface and shared calendars support. ([Source Code](https://github.com/agendav/agendav)) `GPL-3.0` `PHP`
- [DAVDroid](https://www.davdroid.com/) - Open-source CalDAV/CardDAV suite and sync app for Android. ([Source Code](https://gitlab.com/bitfireAT/davdroid)) `GPL-3.0` `Java`
- [InfCloud](https://www.inf-it.com/open-source/clients/infcloud/) - Open source CalDAV/CardDAV web client implementation. ([Demo](https://www.inf-it.com/infcloud/), [Source Code](https://www.inf-it.com/InfCloud_0.13.1.zip)) `AGPL-3.0` `Javascript`
- [EteSync Web](https://www.etesync.com/faq/#web-client) - EteSync's official Web-based client (i.e., their Web app). ([Demo](https://client.etesync.com/), [Source Code](https://github.com/etesync/etesync-web)) `AGPL-3.0` `TypeScript`

## Communication systems

**[`^        back to top        ^`](#)**

### Custom communication systems

- [Centrifugo](https://github.com/centrifugal/centrifugo) - Language-agnostic real-time messaging (Websocket or SockJS) server. ([Demo](https://github.com/centrifugal/centrifugo#demo)) `MIT` `Go` :star:3731
- [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server. `GPL-2.0` `Go` :star:193
- [Freenet](https://freenetproject.org/index.html) - Anonymously share files, browse and publish "freesites" (web sites accessible only through Freenet) and chat on forums. ([Source Code](https://github.com/freenet/fred)) `GPL-2.0` `Java`
- [Friends](http://moose-team.github.io/friends/) - P2P chat powered by the web. ([Source Code](https://github.com/moose-team/friends)) `MIT` `Nodejs`
- [GNUnet](https://gnunet.org/) - Free software framework for decentralized, peer-to-peer networking. ([Source Code](https://gnunet.org/git/)) `GPL-3.0` `C`
- [Gotify](https://gotify.net/) - Self-hosted notification server with Android and CLI clients, similar to PushBullet. ([Source Code](https://github.com/gotify/server), [Clients](https://github.com/gotify/android)) `MIT` `Go`
- [Hawkpost](https://hawkpost.co) - HawkPost is a web app that lets you create unique links that you can share with a person that desires to send you important information but doesn't know how to encrypt it. The message is encrypted in their browser and sent to your email address. ([Source Code](https://github.com/whitesmith/hawkpost)) `MIT` `Python`
- [Hubl.in](https://hubl.in/) - WebRTC powered video conference, chat and collaborative editor. ([Source Code](https://github.com/linagora/hublin)) `AGPL-3.0` `Nodejs`
- [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - Jitsi Meet is an OpenSource (MIT) WebRTC Javascript application that uses Jitsi Videobridge to provide high quality, scalable video conferences. ([Source Code](https://github.com/jitsi/jitsi-meet)) `MIT` `Javascript`
- [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - WebRTC compatible Selective Forwarding Unit (SFU) that allows for multiuser video communication. ([Source Code](https://github.com/jitsi/jitsi-videobridge)) `Apache-2.0` `Java`
- [Kandan](http://getkandan.com/) - Kandan is an Open Source Alternative to HipChat. ([Source Code](https://github.com/kandanapp/kandan)) `AGPL-3.0` `Ruby`
- [KChat](https://github.com/php-kchat/kchat) - PHP Based Live Chat Application. `Apache-2.0` `PHP` :star:28
- [Lets-Chat](http://sdelements.github.io/lets-chat/) - Self hosted chat suite written in Node. ([Source Code](https://github.com/sdelements/lets-chat)) `MIT` `Nodejs`
- [Live Helper Chat](http://livehelperchat.com/) - Live Support chat for your website. ([Source Code](https://github.com/LiveHelperChat/livehelperchat)) `Apache-2.0` `PHP`
- [Mattermost](http://www.mattermost.org/) - Open-source, on-prem Slack-alternative. It can be integrated with [Gitlab](https://about.gitlab.com/). ([Source Code](https://github.com/mattermost/mattermost-server)) `AGPL-3.0/Apache` `Go`
- [MiAOU](https://dystroy.org/miaou/login) - Multi-room persistent chat server. ([Source Code](https://github.com/Canop/miaou)) `MIT` `Nodejs`
- [Mibew](https://mibew.org) - Mibew Messenger is an open-source live support application written in PHP and MySQL. It enables one-on-one chat assistance in real-time directly from your website. ([Demo](https://mibew.org/demo2), [Source Code](https://github.com/Mibew/mibew)) `Apache-2.0` `PHP`
- [Mumble](http://wiki.mumble.info/wiki/Main_Page) - Low-latency, high quality voice/text chat software. ([Source Code](https://github.com/mumble-voip/mumble), [Clients](https://wiki.mumble.info/wiki/3rd_Party_Applications)) `BSD-3-Clause` `C++`
- [Node-Chat](https://github.com/IgorAntun/node-chat) - Not-so-basic open-source chat with admin features. `MIT` `Nodejs` :star:515
- [Rallly](http://rallly.co) - Rallly is a free collaborative scheduling service. ([Source Code](https://github.com/lukevella/Rallly)) `CC-BY-SA-4.0` `Nodejs`
- [RetroShare](http://retroshare.org) - Secured and decentralized communication system. Offers decentralized chat, forums, messaging, file transfer. ([Source Code](https://github.com/RetroShare/RetroShare)) `GPL-2.0` `С++`
- [Jami](https://jami.net/) - Free and universal communication platform which preserves the user's privacy and freedoms (formerly GNU Ring). ([Source Code](https://git.ring.cx/savoirfairelinux/ring-project)) `GPL-3.0` `C++`
- [Rocket.Chat](https://rocket.chat/) - Teamchat solution similar to Gitter.im or Slack. ([Source Code](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs`
- [Spectrum 2](http://spectrum.im/) - Spectrum 2 is an open source instant messaging transport.  It allows users to chat together even when they are using different IM networks. ([Source Code](https://github.com/hanzz/spectrum2)) `GPL-3.0` `C++`
- [Spreed](https://www.spreed.me/) - WebRTC audio/video calls, conferencing server, and web client. ([Source Code](https://github.com/strukturag/spreed-webrtc)) `AGPL-3.0` `Go`
- [Synapse](http://matrix.org/docs/projects/server/synapse.html) - Server for [Matrix](https://matrix.org/), an open standard for decentralized persistent communication. ([Source Code](https://github.com/matrix-org/synapse)) `Apache-2.0` `Python`
  - [Matrix Console Web](http://matrix.org/docs/projects/client/matrix-console.html) - Web client meant to be a showcase of Matrix capabilities, and reference implementation of the Matrix standard. ([Source Code](https://github.com/matrix-org/matrix-angular-sdk)) `Apache-2.0` `Javascript`
  - [Riot.im](http://riot.im) - Fully-featured Matrix client for Web, iOS & Android. ([Source Code](https://github.com/vector-im/riot-web)) `Apache-2.0` `Javascript`
- [Syndie](https://syndie.de) - Syndie is a libre system for operating distributed forums. `CC0-1.0` `Java`
- [TextBelt](https://github.com/typpo/textbelt) `⚠` - Outgoing SMS API that uses carrier-specific gateways to deliver your text messages for free, and without ads. `MIT` `Javascript`
- [Tox](https://tox.chat/) - Distributed, secure messenger with audio and video chat capabilities. ([Source Code](https://github.com/irungentoo/toxcore)) `GPL-3.0` `C`
- [Tuber](https://blog.trailofbits.com/2015/12/15/self-hosted-video-chat-with-tuber/) - Peer-to-peer video chat that works. ([Source Code](https://github.com/trailofbits/tubertc)) `MIT` `Javascript`
- [ZeroNet](https://zeronet.io/) `⚠` - Open, free, and uncensorable websites, using Bitcoin cryptography and BitTorrent network. ([Source Code](https://github.com/HelloZeroNet/ZeroNet)) `GNU` `Python`
- [Zulip](https://zulip.org) - Zulip is a powerful, open source group chat application. ([Source Code](https://github.com/zulip/zulip)) `Apache/Other` `Python`

### Email

**[`^        back to top        ^`](#)**

#### Complete solutions

_Simple deployment of a mail server, e.g. for inexperienced or impatient admins._

- [docker-mailserver](https://github.com/tomav/docker-mailserver) - Fullstack but simple mail server (smtp, imap, antispam, antivirus, etc.). Only configuration files, no SQL database. Keep it simple and versioned. Easy to deploy and upgrade. `MIT` `Docker` :star:4445
- [Inboxen](https://inboxen.org) - Inboxen is a service that provides you with an infinite number of unique inboxes. ([Source Code](https://github.com/Inboxen/Inboxen)) `GPL-3.0` `Python`
- [homebox](https://github.com/progmaticltd/homebox) - A suite of Ansible scripts to deploy a fully functional mail server on Debian. Unobtrusive and automatic as much as possible, focusing on stability and security. `GPL-3.0` `Shell` :star:129
- [iRedMail](http://www.iredmail.org/) - Full-featured mail server solution based on Postfix and Dovecot. ([Source Code](https://bitbucket.org/zhb/iredmail/commits/)) `GPL-3.0` `Shell`
- [Mailcow](https://mailcow.email/) - Mail server suite based on Dovecot, Postfix and other open source software, that provides a modern Web UI for administration. ([Source Code](https://github.com/andryyy/mailcow)) `GPL-2.0` `PHP`
- [Mailu](https://mailu.io/) - Mailu is a simple yet full-featured mail server as a set of Docker images. ([Demo](https://github.com/Mailu/Mailu/wiki/Demo-server), [Source Code](https://github.com/Mailu/Mailu)) `MIT` `Docker/Python`
- [Mail-in-a-Box](https://mailinabox.email/) - Turns any Ubuntu server into a fully functional mail server with one command. ([Source Code](https://github.com/mail-in-a-box/mailinabox)) `CC0-1.0` `Shell`
- [Modoboa](http://modoboa.org/en/) - Modoboa is a mail hosting and management platform including a modern and simplified Web User Interface. ([Source Code](https://github.com/tonioo/modoboa)) `MIT` `Python`
- [Qmailtoaster](http://www.qmailtoaster.com/) - Stable, full-featured, easy-to-install mail server based on qmail. ([Source Code](https://github.com/QMailToaster/)) `Multiple` `Linux`
- [Simple NixOS Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - A complete mailserver solution leveraging the Nix Ecosystem. `GPL-3.0` `Nix`

#### Mail Transfer Agents

_MTAs / SMTP servers_

- [chasquid](https://blitiri.com.ar/p/chasquid/) - SMTP (email) server with a focus on simplicity, security, and ease of operation. ([Source Code](https://blitiri.com.ar/git/r/chasquid/)) `Apache-2.0` `Go`
- [Courier MTA](http://www.courier-mta.org/) - Fast, scalable, enterprise mail/groupware server providing ESMTP, IMAP, POP3, webmail, mailing list, basic web-based calendaring and scheduling services. ([Source Code](http://www.courier-mta.org/repo.html)) `GPL-3.0` `C`
- [Exim](https://www.exim.org/) - Message transfer agent (MTA) developed at the University of Cambridge. ([Source Code](http://git.exim.org/exim.git)) `GPL-3.0` `C`
- [Haraka](http://haraka.github.io/) - High-performance, pluginable SMTP server written in Javascript. ([Source Code](https://github.com/haraka/Haraka)) `MIT` `Javascript`
- [MailCatcher](http://mailcatcher.me/) - Ruby gem that deploys a simply SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development. ([Source Code](https://github.com/sj26/mailcatcher)) `MIT` `Ruby`
- [Maildrop](https://gitlab.com/markbeeson/maildrop) - Disposable email SMTP server, also useful for development. `MIT` `Scala`
- [MailHog](https://github.com/mailhog/MailHog) - Small Golang executable which runs an SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development. `MIT` `Go` :star:5245
- [OpenSMTPD](https://opensmtpd.org/) - Secure SMTP server implementation from the OpenBSD project. ([Source Code](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/smtpd/)) `ISC` `C`
- [Postfix](http://www.postfix.org/) - Fast, easy to administer, and secure Sendmail replacement. `IPL-1.0` `C`
- [Qmail](https://cr.yp.to/qmail.html) - Secure Sendmail replacement. ([Source Code](https://sources.debian.net/src/netqmail/1.06-5/)) `CC0-1.0` `C`
- [Sendmail](http://www.sendmail.com/sm/open_source/) - Message transfer agent (MTA). `Sendmail` `C`
- [Slimta](http://slimta.org) - Mail Transfer Library built on Python. ([Source Code](https://github.com/slimta/python-slimta)) `MIT` `Python`

#### Mail Delivery Agents

_MDAs - IMAP/POP3 software_

- [Cyrus IMAP/POP3](http://cyrusimap.org/) - Intended to be run on sealed servers, where normal users are not permitted to log in. ([Source Code](https://github.com/cyrusimap/cyrus-imapd )) `BSD-3-Clause-Attribution` `C`
- [Dovecot](http://www.dovecot.org/) - IMAP and POP3 server written primarily with security in mind. ([Source Code](https://github.com/dovecot/core)) `MIT/LGPL-2.1` `C`
- [Piler](http://www.mailpiler.org/wiki/start) - feature rich open source email archiving solution. ([Source Code](https://bitbucket.org/jsuto/piler)) `GPL-3.0` `C`

#### Mailing lists and Newsletters

_Mailing lists servers and mass mailing software - one message to many recipients._

- [Dada Mail](http://dadamailproject.com/) - Web-based list management system that can be used for announcement lists and/or discussion lists. ([Source Code](https://github.com/justingit/dada-mail)) `GPL-2.0` `Perl`
- [Mail For Good](https://github.com/freeCodeCamp/mail-for-good) `⚠` - Open source email campaign management tool for nonprofits. `BSD-3-Clause` `Javascript`
- [Mailman](https://www.gnu.org/software/mailman/) - The Gnu mailing list server. `GPL-3.0` `Python`
- [Mailtrain](https://mailtrain.org/) - self hosted newsletter application built on Node.js (v5+) and MySQL (v5.5+ or MariaDB). ([Source Code](https://github.com/andris9/mailtrain)) `GPL-3.0` `Nodejs`
- [MailyHerald](http://mailyherald.org/) - Self-hosted Mailchimp alternative that you can easily integrate with your site. Helps you send and manage your application mailings. It support email marketing and conducting the daily stream of notifications you send to your users. ([Source Code](https://github.com/Sology/maily_herald)) `LGPL-3.0` `Ruby`
- [Mautic](https://www.mautic.org/) - Mautic is marketing automation software (email, social and more). ([Source Code](https://github.com/mautic/mautic)) `GPL-3.0` `PHP`
- [phpList](https://phplist.org) - Newsletter and email marketing with advanced management of subscribers, bounces, and plugins. ([Source Code](https://github.com/phpList/)) `AGPL-3.0` `PHP`
- [Postal](https://github.com/atech/postal) - Fully featured open source mail delivery platform for incoming and outgoing e-mail. `MIT` `Ruby` :star:9179
- [Schleuder](https://schleuder.nadir.org/) - GPG-enabled mailing list manager with resending-capabilities. ([Source Code](https://0xacab.org/schleuder/schleuder/tree/master)) `GPL-3.0` `Ruby`
- [Sympa](https://www.sympa.org/) - Mailing list manager. `GPL-2.0` `Perl`

#### Webmail clients

- [Afterlogic WebMail Lite](http://www.afterlogic.org/webmail-lite) - Fast and easy-to-use webmail front-end for your existing IMAP mail server, Plesk or cPanel. ([Demo](https://lite.afterlogic.com/), [Source Code](https://github.com/afterlogic/webmail-lite)) `AGPL-3.0` `PHP`
- [Cypht](http://cypht.org/index.html) - Feed reader for your email accounts. ([Source Code](https://github.com/jasonmunro/hm3)) `GPL-2.0` `PHP`
- [Disposable Mailbox](https://github.com/synox/disposable-mailbox) - Simple disposable mailbox web-app based on a catch-all IMAP mailbox. ([Demo](https://bhadoomail.com/)) `GPL-3.0` `PHP` :star:243
- [IMP](https://www.horde.org/apps/imp/) - HORDE application that provides webmail access to IMAP and POP3 accounts. ([Demo](http://demo.horde.org/), [Source Code](https://www.horde.org/download/imp)) `GPL-2.0` `PHP`
- [MailCare](https://mailcare.io) - Open source disposable email address service. ([Source Code](https://github.com/mailcare/mailcare)) `MIT` `PHP`
- [Mailpile](https://www.mailpile.is/) - Webmail client with search, filtering, encryption features and more. ([Source Code](https://github.com/mailpile/Mailpile)) `AGPL-3.0` `Python`
- [RainLoop](http://www.rainloop.net/) - Simple, modern and fast webmail with IMAP/SMTP Support and multi accounting. ([Demo](http://demo.rainloop.net/), [Source Code](https://github.com/RainLoop/rainloop-webmail)). `AGPL-3.0` `PHP`
- [Roundcube](https://roundcube.net) - Browser-based IMAP client with an application-like user interface. ([Source Code](https://github.com/roundcube/roundcubemail)) `GPL-3.0` `PHP`
- [SquirrelMail](http://squirrelmail.org) - Another browser-based IMAP client. ([Source Code](https://sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPL-2.0` `PHP`

### IRC

**[`^        back to top        ^`](#)**

_[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) communication software_

- [Convos](http://convos.by/) - Always online web IRC client. ([Demo](http://demo.convos.by), [Source Code](http://github.com/nordaaker/convos)) `Artistic-2.0` `Perl`
- [Dispatch](https://github.com/khlieng/dispatch) - A self-hosted web IRC client written in Go. ([Demo](https://dispatch.khlieng.com/connect)) `MIT` `Go` :star:531
- [Kiwi IRC](https://kiwiirc.com/) - A responsive web IRC client with theming support. ([Demo](https://kiwiirc.com/nextclient/)), ([Source Code](https://github.com/kiwiirc/kiwiirc)) `Apache-2.0` `Nodejs`
- [The Lounge](https://thelounge.github.io/) - A self-hosted web IRC client. ([Demo](https://demo.thelounge.chat/), [Source Code](https://github.com/thelounge/lounge)) `MIT` `Nodejs`
- [Quassel IRC](http://quassel-irc.org/) - distributed IRC client, meaning that one (or multiple) client(s) can attach to and detach from a central core. ([Source Code](https://github.com/quassel/quassel)) `GPL-2.0` `C++`
- [Robust IRC](https://robustirc.net/) - RobustIRC is IRC without netsplits. Distributed IRC server, based on RobustSession protocol. ([Source Code](https://github.com/robustirc/robustirc)) `BSD-3-Clause` `Go`
- [Weechat](https://weechat.org/) - Fast, light and extensible chat client. `GPL-3.0` `C`
  - [Glowing Bear](https://github.com/glowing-bear/glowing-bear/) - A web frontend for WeeChat. ([Demo](https://www.glowing-bear.org)) `GPL-3.0` `JavaScript` :star:752
- [ZNC](http://wiki.znc.in/ZNC) - Advanced IRC bouncer. ([Source Code](https://github.com/znc/znc)) `Apache-2.0` `C++`

### SIP

**[`^        back to top        ^`](#)**

_[SIP](https://en.wikipedia.org/wiki/Session_Initiation_Protocol)/[IPBX](https://en.wikipedia.org/wiki/IP_PBX) telephony software_

- [Asterisk](http://www.asterisk.org/) - Easy to use but advanced IP PBX system, VoIP gateway and conference server. `GPL-2.0` `C`
- [ASTPP](https://www.astppbilling.org/) - is an Open Source VoIP Billing Solution for Freeswitch. It supports prepaid and postpaid billing with call rating and credit control. It also provides many other features. ([Source Code](https://github.com/iNextrix/ASTPP)) `AGPL-3.0` `PHP`
- [Freepbx](http://www.freepbx.org) - Web-based open source GUI that controls and manages Asterisk. ([Source Code](http://git.freepbx.org/projects/FREEPBX)) `GPL-2.0` `PHP`
- [FreeSWITCH](https://freeswitch.org/) - Scalable open source cross-platform telephony platform. ([Source Code](https://freeswitch.org/stash/projects/FS/repos/freeswitch/browse)) `MPL-2.0` `C`
- [FusionPBX](https://www.fusionpbx.com/) - Open source project that provides a customizable and flexible web interface to the very powerful and highly scalable multi-platform voice switch called FreeSWITCH. ([Source Code](https://github.com/fusionpbx/fusionpbx)) `MPL-1.1` `PHP`
- [Homer](https://www.sipcapture.org/) - Troubleshooting and monitoring VoIP calls. ([Source Code](https://github.com/sipcapture/homer)) `AGPL-3.0` `Angular/C`
- [Kamailio](http://www.kamailio.org/w/) - Modular SIP server (registrar/proxy/router/etc). ([Source Code](https://github.com/kamailio/kamailio)) `GPL-2.0` `C`
- [Kazoo](http://2600hz.org/) - KAZOO is an open-source, highly scalable software platform designed to provide carrier-grade VoIP switch functions and features. ([Source Code](https://github.com/2600hz/KAZOO)) `MPL-1.1` `Erlang`
- [Ostel](https://dev.guardianproject.info/projects/ostel/wiki/Server_Documentation) - Secure SIP telephony setup with ZRTP encryption. `GPL-3.0` `Ruby`
- [Tapir](http://www.sip3.io/) - Troubleshooting and real-time monitoring of VoIP-based systems. ([Source Code](https://github.com/sip3io/tapir)) `Apache-2.0` `Java/Kotlin`
- [Wazo](http://wazo.community/) - Full-featured IPBX solution built atop Asterisk with integrated Web administration interface and REST-ful API. ([Source Code](https://github.com/wazo-pbx)) `GPL-3.0` `Python/PHP`

### Social Networks and Forums

**[`^        back to top        ^`](#)**

- [Abilian SBE](https://github.com/abilian/abilian-sbe) - Open Source Collaboration and Social Networking framework and platform. `LGPL-2.1` `Python` :star:33
- [Anahita](https://www.getanahita.com/) - Open Source Social Networking Framework and Platform. ([Source Code](https://github.com/anahitasocial)) `GPL-3.0` `PHP`
- [bbPress](https://bbpress.org/) - bbPress is forum software with a twist from the creators of WordPress. Easily setup discussion forums inside your WordPress.org powered site. ([Source Code](https://bbpress.trac.wordpress.org/browser/trunk)) `GPL-2.0` `PHP`
- [Bootcamp](http://trybootcamp.vitorfs.com) - Enterprise social network. ([Source Code](https://github.com/vitorfs/bootcamp)) `MIT` `Python`
- [Buddycloud](http://buddycloud.com/) - Tools, libraries, services and a community to build user-to-user, group and social messaging into your app. Saves time. Scales up. Supports you. ([Source Code](https://github.com/buddycloud)) `Apache-2.0` `Java`
- [BuddyPress](https://buddypress.org/about/) - Powerful plugin that takes your WordPress.org powered site beyond the blog with social-network features like user profiles, activity streams, user groups, and more. ([Source Code](https://github.com/buddypress/BuddyPress)) `GPL-2.0` `PHP`
- [cartulary](https://github.com/daveajones/cartulary) - RSS reader, readability tool, article archiver, microblogger, social graph manager and reading list manager. `CDDL-1.0` `PHP` :star:130
- [Commento](https://gitlab.com/commento/commento-ce) - Commento is a discussion platform that you can embed on your blog, news articles, and any place where you want your readers to add comments. `MIT` `GO`
- [diaspora*](https://diasporafoundation.org/) - Distributed social networking server. ([Demo](https://podupti.me/go.php), [Source Code](https://github.com/diaspora/diaspora)) `AGPL-3.0` `Ruby`
- [Discourse](http://www.discourse.org/) - Advanced forum / community solution based on Ruby and JS. ([Demo](https://try.discourse.org/), [Source Code](https://github.com/discourse/discourse)) `GPL-2.0` `Ruby`
- [dyu/comments](https://github.com/dyu/comments) - Real-time, markdown-enabled comment engine powered by leveldb. ([Demo](https://dyu.github.io/comments/real-time/)) `Apache-2.0` `Java` :star:50
- [Elgg](https://elgg.org/) - Powerful open source social networking engine. ([Source Code](https://github.com/Elgg/Elgg)) `GPL-2.0` `PHP`
- [Flarum](http://flarum.org) - Delightfully simple forums. Flarum is the next-generation forum software that makes online discussion fun again. ([Source Code](https://github.com/flarum/flarum)) `MIT` `PHP`
- [flaskbb](https://flaskbb.org/) - FlaskBB is forum software written in Python using the microframework Flask. You can easily create new topics, posts and send other users private messages. It also includes basic administration and moderation tools. ([Source Code](https://github.com/sh4nks/flaskbb)) `BSD-3-Clause` `Python`
- [FluxBB](http://fluxbb.org/) - Fast, light, user-friendly forum software for your website. ([Source Code](https://github.com/fluxbb/fluxbb)) `GPL-2.0` `PHP`
- [Friendica](https://friendi.ca/) - Social Communication Server. ([Source Code](https://github.com/friendica/friendica)) `AGPL-3.0` `PHP`
- [GNU social](https://gnu.io/social/) - Social communication software for both public and private communications. ([Source Code](https://git.gnu.io/gnu/gnu-social)) `AGPL-3.0` `PHP`
- [Hubzilla](https://hubzilla.org) - Decentralized identity, privacy, publishing, sharing, cloud storage, and communications/social platform. ([Source Code](https://framagit.org/hubzilla/core)) `MIT` `PHP`
- [HumHub](https://www.humhub.org/) - Flexible kit for private social networks. ([Source Code](https://github.com/humhub/humhub)) `AGPL-3.0` `PHP`
- [Isso](http://posativ.org/isso/) - Lightweight commenting server written in Python and Javascript. It aims to be a drop-in replacement for Disqus. ([Source Code](https://github.com/posativ/isso)) `MIT` `Python`
- [Lemmy](https://dev.lemmy.ml/#/) - A link aggregator / reddit clone for the fediverse. Reddit alternative built in Rust. ([Source Code](https://github.com/dessalines/lemmy)) `AGPL-3.0` `Rust`
- [Loomio](https://www.loomio.org/) - Loomio is a collaborative decision-making tool that makes it easy for anyone to participate in decisions which affect them. ([Source Code](https://github.com/loomio/loomio)) `AGPL-3.0` `Ruby`
- [Mastodon](https://joinmastodon.org/) - Federated microblogging server, an alternative to GNU social. ([Source Code](https://github.com/tootsuite/mastodon)) `AGPL-3.0` `Ruby`
- [Movim](https://movim.eu/) - Modern, federated social network based on XMPP, with a fully featured group-chat, subscriptions and microblogging. ([Source Code](https://github.com/movim/movim)) `AGPL-3.0` `PHP`
- [MyBB](http://www.mybb.com/) - Free, extensible forum software package. ([Source Code](https://github.com/mybb/mybb)) `LGPL-3.0` `PHP`
- [Newebe](http://newebe.org/) - Distributed Social Network. ([Source Code](https://github.com/gelnior/newebe)) `AGPL-3.0` `Python`
- [NodeBB](https://nodebb.org/) - Node.js based forum software built for the modern web. ([Source Code](https://github.com/NodeBB/NodeBB)) `GPL-3.0` `Nodejs`
- [Orange Forum](http://www.goodoldweb.com/) - Orange Forum is an easy to deploy forum that has minimal dependencies and uses very little javascript. ([Demo](https://groups.goodoldweb.com/), [Source Code](https://github.com/s-gv/orangeforum)) `BSD-3-Clause` `Go`
- [OSSN](https://www.opensource-socialnetwork.org/) - Open Source Social Network (OSSN) is a social networking software written in PHP. It allows you to make a social networking website and helps your members build social relationships, with people who share similar professional or personal interests. ([Source Code](https://github.com/opensource-socialnetwork/opensource-socialnetwork)) `GPL-2.0` `PHP`
- [Oxwall](http://www.oxwall.org/) - Oxwall is used for a wide range of projects starting from family sites and custom social networks to collaboration tools and enterprise community solutions. ([Source Code](https://bitbucket.org/oxwall/public)) `CPAL-1.0` `PHP`
- [phpBB](https://www.phpbb.com/) - Flat-forum bulletin board software solution that can be used to stay in touch with a group of people or can power your entire website. ([Source Code](https://github.com/phpbb/phpbb)) `GPL-2.0` `PHP`
- [PixelFed](https://pixelfed.social) - Pixelfed is an open-source, federated platform alternate to Instagram. ([Source Code](http://github.com/pixelfed/pixelfed)) `AGPL-3.0` `PHP\HTML\Vue`
- [Pleroma](https://pleroma.social) - Federated microblogging server, Mastodon, GNU social, & ActivityPub compatible. ([Source Code](https://git.pleroma.social/pleroma/pleroma)) `AGPL-3.0` `Elixir`
- [PPnet](https://github.com/pixelpark/ppnet) - Create and host your own social network. `MIT` `Javascript` :star:115
- [Pump.io](http://pump.io/) - Stream server that does most of what people really want from a social network. ([Source Code](https://github.com/e14n/pump.io)) `Apache-2.0` `Nodejs`
- [remark42](https://remark42.com/) - A lightweight and simple comment engine, which doesn't spy on users. It can be embedded into blogs, articles or any other place where readers add comments. ([Demo](https://remark42.com/demo/), [Source Code](https://github.com/umputun/remark)) `MIT` `Go`
- [Scoold](https://scoold.com) - Stack Overflow in a JAR. An enterprise-ready Q&A platform with full-text search, SAML, LDAP integration and social login support. ([Demo](https://live.scoold.com), [Source Code](https://github.com/Erudika/scoold)) `Apache-2.0` `Java`
- [Simple Machines Forum](https://www.simplemachines.org/) - Free, professional grade software package that allows you to set up your own online community within minutes. ([Source Code](https://github.com/SimpleMachines/SMF2.1)) `BSD-3-Clause` `PHP`
- [Socialhome](https://socialhome.network) - Federated and decentralized profile builder and social network engine. ([Demo](https://socialhome.network/), [Source Code](https://github.com/jaywink/socialhome)) `AGPL-3.0` `Python`
- [Symphony](https://hacpai.com/) - Modern community (forum/SNS/blog) platform written in Java. ([Source Code](https://github.com/b3log/symphony)) `GPL-3.0` `Java`
- [Talkyard](https://www.talkyard.io/) - Create a community, where your users can suggest ideas and get questions answered. And have friendly open-ended discussions and chat (Slack/StackOverflow/Discourse/Reddit/Disqus hybrid). ([Demo](https://www.talkyard.io/forum/latest), [Source Code](https://github.com/debiki/talkyard)) `AGPL-3.0` `Scala`
- [Tokumei](https://tokumei.co/) - Anonymous microblogging platform. ([Source Code](https://gitlab.com/tokumei/tokumei)) `ISC` `rc`
- [Thredded](https://thredded.org) - Forums, feature-rich and simple. ([Demo](https://thredded.org/thredded), [Source Code](https://github.com/thredded/thredded)) `MIT` `Ruby`
- [twister](http://twister.net.co/) - Fully decentralized P2P microblogging platform leveraging the free software implementations of Bitcoin and BitTorrent protocols. ([Source Code](https://github.com/miguelfreitas/twister-core)) `MIT` `C++`
- [Vanilla Forums](https://vanillaforums.org/) - Simple and flexible forum software. ([Source Code](https://github.com/vanilla/vanilla)) `GPL-2.0` `PHP`

### XMPP

**[`^        back to top        ^`](#)**

_[Extensible Messaging and Presence Protocol](https://en.wikipedia.org/wiki/XMPP) software_

#### XMPP Servers

- [ejabberd](https://www.ejabberd.im/) - XMPP instant messaging server. ([Source Code](https://github.com/processone/ejabberd)) `GPL-2.0` `Erlang`
- [Kontalk](http://kontalk.org/) - Kontalk is an Open Source Messenger, similar to WhatsApp (app for android only currently), including end-to-end encryption, server is based on Tigase XMPP Server. ([Source Code](https://github.com/kontalk)) `GPL-3.0` `Java`
- [Metronome IM](https://metronome.im/) - Fork of Prosody IM. ([Source Code](https://github.com/maranda/metronome)) `MIT` `Lua`
- [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) - Mobile messaging platform with a focus on performance and scalability. ([Source Code](https://github.com/esl/MongooseIM)) `GPL-2.0` `Erlang`
- [Openfire](http://www.igniterealtime.org/projects/openfire/) - Real time collaboration (RTC) server. ([Source Code](https://github.com/igniterealtime/Openfire)) `Apache-2.0` `Java`
- [Prosody IM](http://prosody.im/) - Feature-rich and easy to configure XMPP server. ([Source Code](http://hg.prosody.im/)) `MIT` `Lua`
- [Tigase](http://www.tigase.net/content/tigase-xmpp-server) - XMPP server implementation in Java. `GPL-3.0` `Java`

#### XMPP Web Clients

- [Candy](http://candy-chat.github.io/candy/) - Multi user XMPP client written in Javascript. ([Source Code](https://github.com/candy-chat/candy)) `MIT` `Javascript`
- [Converse.js](https://conversejs.org/) - Free and open-source XMPP chat client in your browser. ([Source Code](https://github.com/jcbrand/converse.js)) `MPL-2.0` `Javascript`
- [JSXC](https://jsxc.org) - Real-time XMPP web chat application with video calls, file transfer and encrypted communication. There are also versions for Nextcloud/Owncloud and SOGo. ([Source Code](https://github.com/jsxc/jsxc)) `MIT` `Javascript`
- [Kaiwa](http://getkaiwa.com/) - Web based chat client in the style of common paid alternatives. ([Source Code](https://github.com/digicoop/kaiwa)) `MIT` `Nodejs`
- [Salut à Toi](http://www.salut-a-toi.org/) - Multipurpose, multi frontend, libre and decentralized communication tool. ([Source Code](http://repos.goffi.org/sat)) `AGPL-3.0` `Python`
  - [Libervia](http://wiki.goffi.org/wiki/Libervia/en) - Web frontend from Salut à Toi. ([Source Code](http://repos.goffi.org/libervia)) `AGPL-3.0` `Python`

## Conference Management

**[`^        back to top        ^`](#)**

- [BigBlueButton](https://bigbluebutton.org/) - Supports real-time sharing of audio, video, slides (with whiteboard controls), chat, and the screen. Instructors can engage remote students with polling, emojis, and breakout rooms. ([Demo](https://demo.bigbluebutton.org/gl), [Source Code](https://github.com/bigbluebutton/bigbluebutton)) `LGPL-3.0` `Java`
- [Conference Organizing Distribution (COD)](http://usecod.com/) - Create conference and event websites built on top of Drupal. ([Source Code](http://cgit.drupalcode.org/cod)) `GPL-1.0` `PHP`
- [frab](https://frab.github.io/frab/) - web-based conference planning and management system. It helps to collect submissions, to manage talks and speakers and to create a schedule. ([Source Code](https://github.com/frab/frab)) `MIT` `Ruby`
- [indico](https://getindico.io/) - A feature-rich event management system, made @ CERN, the place where the Web was born. ([Demo](https://sandbox.getindico.io/), [Source code](https://github.com/indico/indico)) `MIT` `Python`
- [Open Conference Systems (OCS)](https://pkp.sfu.ca/ocs/) - is a free Web publishing tool that will create a complete Web presence for your scholarly conference. ([Demo](https://pkp.sfu.ca/ocs/ocs_demo/), [Source Code](https://github.com/pkp/ocs)) `GPL-1.0` `PHP`
- [OpenCFP](https://github.com/opencfp/opencfp) - OpenCFP is a PHP-based conference talk submission system. `MIT` `PHP` :star:492
- [OpenConferenceWare](http://openconferenceware.org/) - An open source web application for supporting conference-like events. This customizable, general-purpose platform provides proposals, sessions, schedules, tracks, user profiles. ([Source Code](https://github.com/osbridge/openconferenceware)) `MIT` `Ruby`
- [osem](http://osem.io/) - Event management tailored to free Software conferences. ([Demo](http://demo.osem.io/), [Source Code](https://github.com/openSUSE/osem)) `MIT` `Ruby`
- [pretalx](https://pretalx.org) - Web-based event management, including running a Call for Papers, reviewing submissions, and scheduling talks. Exports and imports for various related tools. ([Source Code](https://github.com/pretalx/pretalx)) `Apache-2.0` `Python`

## Content Management Systems (CMS)

**[`^        back to top        ^`](#)**

CMS are a practical way to setup a website with many features. CMS often come with third party plugins, themes and functionality that is easy to add and customize to your needs. See also [Blogging Platforms](#blogging-platforms) and [Static Site Generators](#static-site-generators)

- [APIQ CMS](https://github.com/apiqcms/kms) - Simple and powerful Ruby on Rails CMS for developers. `MIT` `Ruby` :star:334
- [Apostrophe](http://apostrophecms.org/) - Node.js CMS with a focus on extensible in-context editing tools. ([Demo](http://demo.apostrophecms.org/), [Source Code](https://github.com/punkave/apostrophe)) `MIT` `Nodejs`
- [Backdrop CMS](https://backdropcms.org/) - The comprehensive CMS for small to medium sized businesses and non-profits. ([Source Code](https://github.com/backdrop/backdrop)) `GPL-2.0` `PHP`
- [Baun](https://bauncms.com/) - Modern, lightweight, extensible CMS for PHP. ([Source Code](https://github.com/BaunCMS/Baun)) `MIT` `PHP`
- [BigTree CMS](https://www.bigtreecms.org/) - Straightforward, well documented, and capable written with PHP and MySQL. ([Source Code](https://github.com/bigtreecms/BigTree-CMS)) `LGPL-2.1` `PHP`
- [Bolt CMS](https://bolt.cm/) - Open source Content Management Tool, which strives to be as simple and straightforward as possible. ([Demo](https://try.bolt.cm/), [Source Code](https://github.com/bolt/bolt)) `MIT` `PHP`
- [CMS Made Simple](http://www.cmsmadesimple.org/) - Open source content management system, faster and easier management of website contents, scalable for small businesses to large corporations. ([Source Code](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL-1.0` `PHP`
- [Cockpit](http://getcockpit.com) - Simple Content Platform to manage any structured content. ([Source Code](https://github.com/agentejo/cockpit)) `MIT` `PHP`
- [Concrete 5 CMS](http://www.concrete5.org/) - Open source content management system. ([Source Code](https://github.com/concrete5/concrete5)) `MIT` `PHP`
- [Contao](https://contao.org/) - Contao is a powerful open source CMS that allows you to create professional websites and scalable web applications. ([Source Code](https://github.com/contao/contao/)) `LGPL-3.0` `PHP`
- [CouchCMS](http://www.couchcms.com/) - Simple Open-Source CMS for designers. ([Source Code](https://github.com/CouchCMS/CouchCMS)) `CPAL-1.0` `PHP`
- [Directus](http://getdirectus.com/) - Directus is a powerful and intuitive headless CMS for managing SQL databases with custom architectures. Built around a robust and extensible API, this decoupled content management framework is perfect for websites, apps, or multi-client projects. ([Source Code](https://github.com/directus/directus)) `GPL-3.0` `PHP`
- [Drupal](https://www.drupal.org/) - Advanced open source content management platform. ([Source Code](http://cgit.drupalcode.org/drupal)) `GPL-2.0` `PHP`
- [eLabFTW](http://www.elabftw.net) - Online lab notebook for research labs. Store experiments, use a database to find reagents or protocols, use trusted timestamping to legally timestamp an experiment, export as pdf or zip archive, share with collaborators…. ([Demo](https://demo.elabftw.net), [Source Code](https://github.com/elabftw/elabftw)) `AGPL-3.0` `PHP`
- [Expressa](https://github.com/thomas4019/expressa) - Content Management System for powering database driven websites using JSON schemas. Provides permission management and automatic REST APIs. `MIT` `Nodejs` :star:281
- [GetSimple CMS](http://get-simple.info/) - The Simplest Content Management System. Ever. ([Source Code](https://github.com/GetSimpleCMS/GetSimpleCMS)) `GPL-3.0` `PHP`
- [ImpressPages CMS](https://www.impresspages.org/) - Easy code meets easy admin. ([Demo](https://www.impresspages.org/demo), [Source Code](https://github.com/impresspages/ImpressPages)) `GPL-3.0/MIT` `PHP`
- [Joomla!](https://www.joomla.org/) - Advanced Content Management System (CMS). ([Source Code](https://github.com/joomla/joomla-cms)) `GPL-2.0` `PHP`
- [KeystoneJS](http://keystonejs.com/) - CMS and Web Application Platform. ([Demo](http://demo.keystonejs.com/), [Source Code](https://github.com/keystonejs/keystone)) `MIT` `Nodejs`
- [MODX](http://modx.com/) - MODX is an advanced content management and publishing platform. The current version is called 'Revolution'. ([Source Code](https://github.com/modxcms/revolution)) `GPL-2.0` `PHP`
- [Neos](https://www.neos.io) - Neos or TYPO3 Neos (for version 1) is a modern, open source CMS. ([Source Code](https://git.typo3.org/Packages/TYPO3.Neos.git)) `GPL-3.0` `PHP`
- [Noosfero](http://noosfero.org/) - Noosfero is a web platform for social and solidarity economy networks with blog, e-Portfolios, CMS, RSS, thematic discussion, events agenda and collective intelligence for solidarity economy in the same system. ([Source Code](https://gitlab.com/noosfero/noosfero)) `AGPL-3.0` `Ruby`
- [october](http://octobercms.com/) - Free, open-source, self-hosted CMS platform. ([Source Code](https://github.com/octobercms/october)) `MIT` `PHP`
- [Omeka](http://omeka.org) - Create complex narratives and share rich collections, adhering to Dublin Core standards with Omeka on your server, designed for scholars, museums, libraries, archives, and enthusiasts. ([Demo](http://omeka.org/showcase/), [Source Code](https://github.com/omeka/Omeka)) `GPL-3.0` `PHP`
- [Pagekit](https://pagekit.com/) - New modern CMS to create and share. ([Source Code](https://github.com/pagekit/pagekit)) `MIT` `PHP`
- [Pico](http://picocms.org/) - Stupidly simple, blazing fast, flat file CMS. ([Source Code](https://github.com/picocms/Pico)) `MIT` `PHP`
- [Pimcore](https://www.pimcore.org/) - Multi-Channel Experience and Engagement Management Platform. ([Source Code](https://github.com/pimcore/pimcore)) `GPL-3.0-or-later` `PHP`
- [Plone](https://plone.org/) - Powerful open-source CMS system. ([Source Code](https://github.com/plone)) `ZPL-2.0` `Python`
- [ProcessWire](https://processwire.com/) - ProcessWire is an open source content management system (CMS) and web application framework aimed at the needs of designers, developers and their clients. ([Source Code](https://github.com/ryancramerdesign/ProcessWire)) `MPL-2.0` `PHP`
- [PropertyWebBuilder](http://propertywebbuilder.com) - The ultimate Ruby on Rails engine for creating real estate websites. ([Demo](https://propertywebbuilder.herokuapp.com), [Source Code](https://github.com/etewiah/property_web_builder)) `MIT` `Ruby`
- [Publify](https://github.com/publify/publify) - Simple but full featured web publishing software. `MIT` `Ruby` :star:1753
- [REDAXO](https://www.redaxo.org) - Simple, flexible and useful content management system (documentation only available in German). ([Source Code](https://github.com/redaxo/redaxo)) `MIT` `PHP`
- [Redaxscript](https://redaxscript.com) - Ultra lightweight CMS for MySQL, SQLite and PostgreSQL. ([Demo](https://demo.redaxscript.com/login), [Source Code](https://github.com/redaxmedia/redaxscript)) `GPL-3.0` `PHP`
- [Roadiz](https://www.roadiz.io/) -  Modern CMS based on a node system which can handle many types of services. ([Source Code](https://github.com/roadiz/roadiz)) `MIT` `PHP`
- [SilverStripe](https://www.silverstripe.org) - Easy to use CMS with powerful MVC framework underlying. ([Demo](http://demo.silverstripe.org/), [Source Code](https://github.com/silverstripe)) `BSD-3-Clause` `PHP`
- [SPIP](http://www.spip.net/fr) - Publication system for the Internet aimed at collaborative work, multilingual environments, and simplicity of use for web authors. ([Source Code](https://core.spip.net/projects/spip/repository)) `GPL-2.0` `PHP`
- [Squidex](http://squidex.io) - Headless CMS, based on MongoDB, CQRS and Event Sourcing. ([Demo](http://cloud.squidex.io), [Source Code](https://github.com/Squidex/squidex)) `MIT` `.NET`
- [Strapi](https://strapi.io/) - The most advanced open-source Content Management Framework (headless-CMS) to build powerful API with no effort. ([Source Code](https://github.com/strapi/strapi)) `MIT` `Nodejs`
- [Subrion](http://www.subrion.org) - Subrion is a free open source content management system that allows you to build websites for any purpose. Yes, from blog to corporate mega portal. ([Demo](http://demos.subrion.com), [Source Code](https://github.com/intelliants/subrion)) `GPL-3.0` `PHP`
- [Textpattern](http://textpattern.com/) - Flexible, elegant and easy-to-use CMS. ([Demo](http://textpattern.co/demo), [Source Code](https://github.com/textpattern/textpattern)) `GPL-2.0` `PHP`
- [TYPO3](https://typo3.org/) - Powerful and advanced CMS with a large community. ([Source Code](https://github.com/TYPO3/TYPO3.CMS)) `GPL-2.0` `PHP`
- [Umbraco](https://umbraco.com/) - The friendly CMS. Free and open source with an amazing community. ([Source Code](https://github.com/umbraco/Umbraco-CMS)) `MIT` `.NET`
- [Wagtail](https://wagtail.io/) - Django content management system focused on flexibility and user experience. ([Source Code](https://github.com/wagtail/wagtail)) `BSD-3-Clause` `Python`
- [WonderCMS](http://www.wondercms.com) - WonderCMS is the smallest flat file CMS since 2008. ([Demo](https://www.wondercms.com/demo), [Source Code](https://github.com/robiso/wondercms)) `MIT` `PHP`
- [WordPress](https://wordpress.org/) - The worlds most-used blogging and CMS engine. ([Source Code](https://github.com/WordPress/WordPress)) `GPL-2.0` `PHP`

_Recipe management_

- [OpenEats](https://github.com/open-eats/OpenEats) - Recipe management site that allows users to create, store, share and rate recipes, create grocery lists, and more. ([Demo](https://open-eats.github.io/)) `MIT` `Python` :star:217

### E-commerce

- [Attendize](https://www.attendize.com/) - Ticket selling and event management platform. ([Source Code](https://github.com/attendize/attendize)) `AAL` `PHP`
- [Bagisto](https://bagisto.com/en/) - Leading Laravel open source e-commerce framework with multi-inventory sources, taxation, localization, dropshipping and more exciting features. ([Demo](https://demo.bagisto.com/), [Source Code](https://github.com/bagisto/bagisto)) `MIT` `PHP`
- [CoreShop](https://www.coreshop.org) - CoreShop is a e-commerce plugin for Pimcore. ([Source Code](https://github.com/coreshop/CoreShop)) `GPL-3.0` `PHP`
- [Drupal Commerce](https://drupalcommerce.org) - Drupal Commerce is a popular e-commerce module for Drupal CMS, with support for dozens of payment, shipping, and shopping related modules. ([Source Code](https://github.com/drupalcommerce/commerce)) `GPL-2.0` `PHP`
- [Magento](https://magento.com/) - Leading provider of open omnichannel innovation. ([Demo](https://magento.com/schedule-a-demo), [Source Code](https://github.com/magento/magento2)) `OSL-3.0` `PHP`
- [Microweber](https://microweber.com/) - Drag and Drop CMS and online shop. ([Demo](http://demo.microweber.org/), [Source Code](https://github.com/microweber/microweber)) `Apache-2.0` `PHP`
- [OpenBazaar](https://www.openbazaar.org) - Decentralized marketplace using cryptocurrency. ([Source Code](https://github.com/openbazaar/openbazaar-go)) `MIT` `Go`
- [OpenCart](https://www.opencart.com) - Free open source shopping cart solution. ([Source Code](https://github.com/opencart/opencart)) `GPL-3.0` `PHP`
- [Open Classifieds](http://open-classifieds.com/) - Free open-source, self-hosted CMS for classifieds sites. ([Source Code](https://github.com/open-classifieds/openclassifieds2)) `GPL-3.0` `PHP`
- [Open Source POS](https://www.opensourcepos.org/) - Open Source Point of Sale is a web based point of sale system. ([Source Code](https://github.com/opensourcepos/opensourcepos)) `MIT` `PHP`
- [Osclass](https://osclass.org/) - One-stop shop to building your own classifieds marketplace. ([Source Code](https://github.com/osclass/Osclass)) `Apache-2.0` `PHP`
- [OXID eShop](http://oxidforge.org) - OXID eShop is a flexible open source e-commerce software with a wide range of functionalities. ([Demo](http://demoshop.oxid-esales.com/community-edition/), [Source Code](https://github.com/OXID-eSales/oxideshop_ce)) `GPL-3.0` `PHP`
- [Open Food Network](https://openfoodnetwork.org/) - Online marketplace for local food. It enables a network of independent online food stores that connect farmers and food hubs with individuals and local businesses. ([Source Code](https://github.com/openfoodfoundation/openfoodnetwork)) `AGPL-3.0` `Ruby`
- [PrestaShop](https://www.prestashop.com/) - PrestaShop offers a free, open-source and fully scalable e-commerce solution. ([Demo](http://demo.prestashop.com/), [Source Code](https://github.com/PrestaShop/PrestaShop)) `OSL-3.0` `PHP`
- [Pretix](https://pretix.eu/) - Django based ticket sales platform for events. ([Source Code](https://github.com/pretix)) `Apache-2.0` `Python`
- [Reaction Commerce](https://reactioncommerce.com/) - Customizable, real-time reactive, JavaScript commerce platform. ([Source Code](https://github.com/reactioncommerce/reaction)) `GPL-3.0` `Nodejs`
- [Saleor](http://getsaleor.com/) - Django based open-sourced e-commerce storefront. ([Demo](https://demo.getsaleor.com/), [Source Code](https://github.com/mirumee/saleor)) `BSD-3-Clause` `Python`
- [Sharetribe](https://www.sharetribe.com) - An open source platform to create your own peer-to-peer marketplace, also available with SaaS model. ([Source Code](https://github.com/sharetribe/sharetribe)) `MIT` `Ruby`
- [Shuup](https://www.shuup.com/) - Django powered fully customizable open source e-commerce framework for small and large sites. ([Source Code](https://github.com/shuup/shuup)) `AGPL-3.0` `Python`
- [Shopware Community Edition](https://shopware.com/community/) - PHP based open source e-commerce software made in Germany. ([Demo](https://www.shopwaredemo.de/), [Source Code](https://github.com/shopware/shopware)) `AGPL-3.0` `PHP`
- [Sylius](http://sylius.org/) - Symfony2 powered open source full-stack platform for eCommerce. ([Demo](http://sylius.org/demo), [Source Code](https://github.com/Sylius/Sylius)) `MIT` `PHP`
- [Thelia](http://thelia.net/) - Thelia is an open source and flexible e-commerce solution. ([Demo](http://demo.thelia.net/), [Source Code](https://github.com/thelia/thelia)) `LGPL-3.0` `PHP`
- [WooCommerce](https://www.woothemes.com/woocommerce/) - WordPress based e-commerce solution. ([Source Code](https://github.com/woothemes/woocommerce)) `GPL-3.0` `PHP`

## DNS

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#dns

- [CoreDNS](https://coredns.io/) - Plugin driven DNS Server with support for proxying to Google's DNS-over-HTTPS. ([Source Code](https://github.com/coredns/coredns)) `Apache-2.0` `Go`
- [nsupdate.info](https://www.nsupdate.info/) - nsupdate.info is a dynamic DNS service. ([Demo](https://www.nsupdate.info/account/register/), [Source Code](https://github.com/nsupdate-info/nsupdate.info)) `BSD-3-Clause` `Python`
- [SPF Toolbox](http://spftoolbox.com) - Application to look up DNS records such as SPF, MX, Whois, and more. ([Source Code](https://github.com/charlesabarnes/SPFtoolbox)) `MIT` `PHP`

## Document Management

**[`^        back to top        ^`](#)**

- [CaseBox](https://www.casebox.org) - Manage all your organization's information in one system. ([Source Code](https://github.com/KETSE/casebox)) `AGPL-3.0` `PHP/Java`
- [EdPaper](https://github.com/Edraens/EdPaper) - PDF organizer with users management. `MIT` `PHP` :star:43
- [Mayan EDMS](http://www.mayan-edms.com) - Free Open Source Electronic Document Management System. An electronic vault for your documents with preview generation, OCR, and automatic categorization among other features. ([Source Code](https://gitlab.com/mayan-edms/mayan-edms)) `Apache-2.0` `Python`
- [Paperless](https://github.com/danielquinn/paperless) - Scan, index, and archive all of your paper documents. `GPL-3.0` `Python` :star:5845
- [Teedy](https://teedy.io/) - (Ex SismicsDocs) Lightweight document management system packed with all the features you can expect from big expensive solutions. ([Source Code](https://github.com/sismics/docs)), ([Demo](https://demo.teedy.io/)) `GPL-2.0` `Java`

## E-books and Integrated Library Systems (ILS)

**[`^        back to top        ^`](#)**

_Personal e-book management software._

- [Calibre](https://calibre-ebook.com/) - E-book library manager that can view, convert, and catalog e-books in most of the major e-book formats and provides a built-in Web server for remote clients. ([Demo](https://calibre-ebook.com/demo), [Source code](https://launchpad.net/calibre)) `GPL-3.0` `Python`
  - [BicBucStriim](http://projekte.textmulch.de/bicbucstriim/) - Provides web-based access to your Calibre Library's e-book collection. ([Source Code](https://github.com/rvolz/BicBucStriim)) `MIT` `PHP`
  - [Calibre Web](https://github.com/janeczku/calibre-web) - Web app providing a clean interface for browsing, reading and downloading eBooks using an existing Calibre database. `GPL-3.0` `Python` :star:2045
  - [COPS](https://blog.slucas.fr/en/oss/calibre-opds-php-server) - Lightweight e-book server alternative to Calibre content server or [Calibre2OPDS](https://calibre2opds.com/2011/11/03/new-site-for-calibre2opds/). ([Demo](http://cops-demo.slucas.fr/index.php), [Source Code](https://github.com/seblucas/cops)) `GPL-2.0` `PHP`
  - [Polar Bookshelf](https://getpolarized.io/) - Polar is a personal knowledge repository for PDF and web content supporting incremental reading and document annotation. ([Source Code](https://github.com/burtonator/polar-bookshelf)) `GPL` `Javascript`

_Enterprise-class library management software._

- [Evergreen](https://evergreen-ils.org) - Highly-scalable software for libraries that helps library patrons find library materials, and helps libraries manage, catalog, and circulate those materials. ([Source Code](https://github.com/evergreen-library-system/Evergreen)) `GPL-2.0` `PL/pgSQL`
- [Koha](https://koha-community.org/) - Enterprise-class ILS with modules for acquisitions, circulation, cataloging, label printing, offline circulation for when Internet access is not available, and much more. ([Demo](https://koha-community.org/demo/), [Source Code](https://github.com/Koha-Community/Koha)) `GPL-3.0` `Perl`

## Federated Identity/Authentication

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#identity-management

## Feed Readers

**[`^        back to top        ^`](#)**

- [CommaFeed](https://www.commafeed.com/) - Google Reader inspired self-hosted RSS reader. ([Source Code](https://github.com/Athou/commafeed)) `Apache-2.0` `Java`
- [Feedbin](https://feedbin.com/) - Simple, fast and nice looking RSS reader. ([Source Code](https://github.com/feedbin/feedbin)) `MIT` `Ruby`
- [FeedHQ](https://feedhq.org/) - FeedHQ is a web-based feed reader. ([Source Code](https://github.com/feedhq/feedhq)) `BSD-3-Clause` `Python`
- [FreshRSS](http://freshrss.org/) - Self-hostable RSS feed aggregator. ([Demo](http://demo.freshrss.org/i/), [Source Code](https://github.com/FreshRSS/FreshRSS), [Mobile app](https://github.com/Alkarex/EasyRSS)) `AGPL-3.0` `PHP`
- [JARR](http://1pxsolidblack.pl/jarr-en.html) - JARR (Just Another RSS Reader) is a web-based news aggregator and reader (fork of Newspipe). ([Demo](https://jarr.info/login?next=%2F), [Source Code](https://github.com/jaesivsm/JARR)) `AGPL-3.0` `Python`
- [Kriss Feed](http://tontof.net/kriss/feed/) - Simple and smart (or stupid) feed reader. ([Demo](http://tontof.net/feed/), [Source Code](https://github.com/tontof/kriss_feed)) `CC0-1.0` `PHP`
- [Leed](https://github.com/LeedRSS/Leed) - Leed (for Light Feed) is a Free and minimalist RSS aggregator. ([Source Code](https://github.com/ldleman/Leed)) `AGPL-3.0` `PHP` :star:150
- [Leselys](https://github.com/socketubs/leselys) - Your very elegant RSS reader. `AGPL-3.0` `Python` :star:220
- [Lite-Reader](https://github.com/cubny/lite-reader) - Read your feeds on your own machine with a simple and lite application. ([Demo](http://cubny.com/lite-reader/)) `BSD-3-Clause` `PHP` :star:25
- [Moonmoon](http://moonmoon.org/) - simple feed aggregator (planet like): it only aggregates feeds and spits them out in one single page. ([Source Code](https://github.com/mauricesvay/moonmoon)) `BSD-3-Clause` `PHP`
- [Miniflux](https://miniflux.net/) - Miniflux 2 is a minimalist and open source news reader, written in Go and PostgreSQL. ([Source Code](https://github.com/miniflux/miniflux)) `Apache-2.0` `Go`
- [NewsBlur](http://www.newsblur.com/) - NewsBlur is a personal news reader that brings people together to talk about the world. A new sound of an old instrument. ([Source Code](https://github.com/samuelclay/NewsBlur)) `MIT` `Python`
- [Newspipe](http://newspipe.io/) - Newspipe is a web news aggregator and reader. ([Demo](https://www.newspipe.org/signup), [Source Code](https://github.com/newspipe/newspipe)) `AGPL-3.0` `Python`
- [Nunux Reader](http://reader.nunux.org/) - Simple, fast and reactive RSS reader. ([Source Code](https://github.com/ncarlier/nunux-reader)) `GPL-3.0` `Nodejs`
- [Reader-Self](http://readerself.com/) - Self-hosted rss reader (php / mysql or sqlite) - Google Reader alternative. ([Source Code](https://github.com/readerself/readerself)) `GPL-3.0` `PHP`
- [RSS2EMail](http://www.allthingsrss.com/rss2email/) - Fetches RSS/Atom-feeds and pushes new Content to any email-receiver, supports OPML. ([Source Code](https://github.com/wking/rss2email)) `GPL-2.0` `Python`
- [RSS Monster](https://github.com/pietheinstrengholt/rssmonster) - RSS Monster is an easy to use web-based RSS aggregator and reader compatible with the Fever API, created as an alternative for Google Reader. `MIT` `PHP` :star:275
- [Screaming Liquid Tiger](https://github.com/herrbischoff/screaming-liquid-tiger) - Simple script to automatically generate valid RSS and Atom feeds from a list of media files in the same folder. `MIT` `PHP` :star:127
- [Selfoss](http://selfoss.aditu.de/) - New multipurpose rss reader, live stream, mashup, aggregation web application. ([Source Code](https://github.com/SSilence/selfoss)) `AGPL-3.0` `PHP`
- [Sismics Reader](http://sismics.com/reader/) - Free and open source feeds reader, including all major Google Reader features. ([Demo](https://www.sismics.com/reader/#!/demo), [Source Code](https://github.com/sismics/reader)) `GPL-2.0` `Java`
- [Stringer](https://github.com/swanson/stringer) - Work-in-progress self-hosted, anti-social RSS reader. `MIT` `Ruby` :star:3067
- [Temboz](https://github.com/fazalmajid/temboz) - Two-column feed reader emphasizing filtering capabilities to manage information overload. `MIT` `Python` :star:22
- [Tiny Tiny RSS](https://tt-rss.org) - Open source web-based news feed (RSS/Atom) reader and aggregator. ([Demo](http://framanews.org/), [Source Code](https://git.tt-rss.org/fox/tt-rss)) `GPL-3.0` `PHP`
  - [gritttt-rss](http://gritttt-rss.nicolashoening.de/) - More features for Tiny Tiny RSS. ([Source Code](https://github.com/nhoening/gritttt-rss)) `BSD-2-Clause` `Python`
  - [ttrss-mobile](https://github.com/mboinet/ttrss-mobile) - Mobile webapp for Tiny Tiny RSS. `AGPL-3.0` `Javascript` :star:182
  - [ttrss-reader](https://github.com/kucrut/ttrss-reader) - Light and responsive client for TTRSS. `GPL-2.0` `Javascript` :star:35
- [Winds](https://getstream.io/winds/) `⚠` - Open source and beautiful RSS reader built using React/Redux/Sails/Node and Stream. It showcases personalized feeds powered by the Stream API. ([Demo](https://winds.getstream.io/), [Source Code](https://github.com/GetStream/Winds)) `BSD-3-Clause` `Nodejs`

## File Sharing and Synchronization

**[`^        back to top        ^`](#)**

Some [Groupware](#groupware) solutions also feature file sharing and synchronization.

#### Distributed filesystems

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#distributed-filesystems

#### File transfer/synchronization

- [Git Annex](https://git-annex.branchable.com/) - File synchronization between computers, servers, external drives. ([Source Code](https://git.joeyh.name/index.cgi/git-annex.git/)) `GPL-3.0` `Haskell`
- [Kinto](https://kinto.readthedocs.org) - Kinto is a minimalist JSON storage service with synchronisation and sharing abilities. ([Source Code](https://github.com/Kinto)) `Apache-2.0` `Python`
- [Nextcloud](https://nextcloud.com/) - Access and share your files, calendars, contacts, mail and [more](https://apps.nextcloud.com/) from any device, on your terms. ([Demo](https://demo.nextcloud.com/), [Source Code](https://github.com/nextcloud/server)) `AGPL-3.0` `PHP`
- [OpenSSH/SFTP](http://www.openssh.com/) - Secure File Transfer Program. ([Source Code](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.bin/ssh)) `BSD-2-Clause` `C`
- [ownCloud](https://owncloud.org/) - All-in-one solution for saving, synchronizing, viewing, editing and sharing files, calendars, address books and more. ([Source Code](https://github.com/owncloud/core), [Clients](https://github.com/owncloud/core/wiki/Apps)) `AGPL-3.0` `PHP`
- [Pydio](https://pydio.com/) - Turn any web server into a powerful file management system and an alternative to mainstream cloud storage providers. ([Source Code](https://github.com/pydio/pydio-core)) `AGPL-3.0` `PHP`
- [Samba](https://www.samba.org/) - Samba is the standard Windows interoperability suite of programs for Linux and Unix. It provides secure, stable and fast file and print services for all clients using the SMB/CIFS protocol. ([Source Code](https://git.samba.org/samba.git/)) `GPL-3.0` `C`
- [Seafile](https://www.seafile.com/en/home/) - File hosting and sharing solution primary for teams and organizations. ([Demo](https://seacloud.cc/demo), [Source Code](https://github.com/haiwen/seafile)) `GPL-2.0` `C`
- [SparkleShare](http://sparkleshare.org/) - Self hosted, instant, secure file sync. ([Source Code](https://github.com/hbons/SparkleShare)) `GPL-3.0` `C#`
- [Syncany](https://www.syncany.org/) - Secure file sync software for arbitrary storage backends, an open-source cloud storage and filesharing application. Securely synchronize your files to any kind of storage. `GPL-3.0` `Java`
- [Syncthing](https://syncthing.net/) - Syncthing is an open source peer-to-peer file synchronisation tool. ([Source Code](https://github.com/syncthing/syncthing)) `MPL-2.0` `Go`
- [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - Unison is a file-synchronization tool for OSX, Unix, and Windows. `GPL-3.0` `OCaml`
- [Z-Push](http://z-push.org/) - Implementation of Microsoft’s [ActiveSync](https://en.wikipedia.org/wiki/ActiveSync) protocol. ([Source Code](https://stash.z-hub.io/projects/ZP/repos/z-push)) `AGPL-3.0` `PHP`

#### Peer-to-peer filesharing

- [bittorrent-tracker](https://webtorrent.io/) - Simple, robust, BitTorrent tracker (client and server) implementation. ([Source Code](https://github.com/feross/bittorrent-tracker)) `MIT` `Nodejs`
- [cloud-torrent](https://github.com/jpillora/cloud-torrent) - Torrent Web Client with HTTP retrievable or streamable downloaded files. `AGPL-3.0` `Go` :star:3681
- [Dat Project](https://datproject.org) - Powerful decentralized file sharing applications built from a large ecosystem of modules. ([Source Code](https://github.com/datproject)) `MIT` `Nodejs`
- [FilePizza](http://file.pizza/) - Peer-to-peer file transfers in your browser. ([Source Code](https://github.com/kern/filepizza)) `BSD-3-Clause` `Nodejs`
- [Firefox Send](https://github.com/mozilla/send) - A file sharing experiment which allows you to send encrypted files to other users. `MPL-2.0` `Nodejs` :star:8230
- [instant.io](https://github.com/feross/instant.io) - Streaming file transfer over WebTorrent. ([Demo](https://instant.io)) `MIT` `Nodejs` :star:2274
- [Magnetico](https://github.com/boramalper/magnetico) - Magnetico is the first autonomous (self-hosted) BitTorrent DHT search engine suite that is designed for end-users. `AGPL-3.0` `Python` :star:2053
- [Magnetissimo](https://github.com/sergiotapia/magnetissimo) - Search engine that indexes all popular torrent sites. `MIT` `Elixir` :star:2368
- [Opentracker](http://erdgeist.org/arts/software/opentracker/) - Open and free bittorrent tracker. It aims for minimal resource usage and is intended to run at your wlan router. ([Source Code](http://erdgeist.org/gitweb/opentracker/)) `Beerware` `C`
- [peerflix-server](https://github.com/asapach/peerflix-server) - Downloads torrent files and provides a direct link download or a direct link stream. `MIT` `Nodejs` :star:931
- [qBittorrent](https://www.qbittorrent.org/) - Free cross-platform bittorrent client with a feature rich Web UI for remote access. ([Source Code](https://github.com/qbittorrent/qBittorrent)) `GPL-2.0` `C++`
- [rartracker](https://github.com/swetorrentking/rartracker) - Complete private bittorrent tracker. `WTFPL` `PHP` :star:161
- [Transmission](https://transmissionbt.com/) - Fast, easy, Free Bittorrent client. ([Source Code](https://github.com/transmission/transmission)) `GPL-3.0` `C`

#### Object storage/file servers

- [Minio](https://minio.io/) - Minio is an open source object storage server compatible with Amazon S3 APIs. ([Source Code](https://github.com/minio/minio)) `Apache-2.0` `Go`
- [Zenko CloudServer](https://www.zenko.io/cloudserver) - Zenko CloudServer, an open-source Node.js implementation of a server handling the Amazon S3 protocol. ([Source Code](https://github.com/scality/S3)) `Apache-2.0` `Nodejs`

#### Single-click/drag-n-drop upload

- [BoZoN](https://github.com/broncowdd/BoZoN) - Minimalist Drag and drop file sharing app. `AGPL-3.0` `PHP` :star:264
- [Coquelicot](https://coquelicot.potager.org/) - Coquelicot is a “one-click” file sharing web application with a focus on protecting users’ privacy. ([Source Code](https://coquelicot.potager.org/gitweb/?p=coquelicot.git)) `AGPL-3.0` `Ruby`
- [droppy](https://github.com/silverwind/droppy) - droppy is a self-hosted cloud server with an interface similar to desktop file managers and has capabilities to edit files on-the-fly as well as view and playback media directly in the browser. ([Demo](http://droppy.silverwind.io/)) `BSD-2-Clause` `Nodejs` :star:742
- [elixire](https://elixi.re) - Simple yet advanced screenshot uploading and link shortening service. ([Source Code](https://gitlab.com/elixire/elixire), [Clients](https://gitlab.com/elixire/elixiremanager)) `AGPL-3.0` `Python`
- [fibridge](https://github.com/anderspitman/fibridge-proxy-rs) - Stream huge files out of your browser without having to upload. ([Demo](https://fbrg.xyz/)) `MIT` `Rust` :star:20
- [FileShelter](https://github.com/epoupon/fileshelter) - FileShelter is a self-hosted software that allows you to easily share files over the Internet. ([Demo](http://fileshelter.demo.poupon.io/)) `GPL-3.0` `C++` :star:73
- [Files Sharing](https://github.com/axeloz/filesharing) - Open Source and self-hosted files sharing application based on unique and temporary links. `GPL-3.0` `PHP` :star:10
- [img.bi](https://github.com/imgbi/img.bi) - img.bi is a secure image hosting. Images are encrypted using AES-256 with random key in browser before upload. `GPL-3.0` `Nodejs` :star:192
- [imgpush](https://github.com/hauxir/imgpush) - imgpush is a self-hosted file upload service that can easily be integrated into other webapps. `MIT` `Python` :star:59
- [ipfs.pics](https://github.com/ipfspics/server) - ipfs.pics is a distributed image hosting website. `AGPL-3.0` `PHP` :star:1014
- [Jirafeau](https://gitlab.com/mojo42/Jirafeau) - Jirafeau is a web site permitting to upload a file in a simple way and give an unique link to it. ([Demo](http://jirafeau.net/)) `AGPL-3.0` `PHP`
- [linx](https://github.com/andreimarcu/linx-server) - File sharing application and pastebin with API, auto-expiry, deletion keys, and web seed support. ([Demo](https://linx.li/)) `GPL-3.0` `Go` :star:610
- [lufi](https://git.framasoft.org/luc/lufi) - Let's Upload that FIle, client-side encrypted. ([Demo](https://demo.lufi.io), [Source Code](https://git.framasoft.org/luc/lufi/tree/master)) `AGPL-3.0` `Perl`
- [lutim](https://github.com/ldidry/lutim) - Let's Upload That Image. `AGPL-3.0` `Perl` :star:157
- [OnionShare](https://github.com/micahflee/onionshare) - Securely and anonymously share a file of any size. `GPL-2.0` `Python` :star:3226
- [PictShare](https://www.pictshare.net/) - PictShare is a multi lingual, open source image hosting service with a simple resizing and upload API. ([Source Code](https://github.com/chrisiaut/pictshare)) `Apache-2.0` `PHP`
- [Plik](https://github.com/root-gg/plik) - Plik is a scalable and friendly temporary file upload system. ([Demo](https://plik.root.gg/)) `MIT` `Go` :star:357
- [Pomf](https://github.com/Pomf/Pomf) - Simple file uploading and sharing, source for the now shut down site Pomf.se. `MIT` `PHP` :star:372
- [ProjectSend](http://www.projectsend.org/) - Upload files and assign them to specific clients you create. Give access to those files to your clients. ([Source Code](https://github.com/ignacionelson/ProjectSend)) `GPL-2.0` `PHP`
- [PsiTransfer](https://github.com/psi-4ward/psitransfer) - Simple open source self-hosted file sharing solution with robust up-/download-resume and password protection. `BSD-2-Clause` `Nodejs` :star:488
- [Sharry](https://github.com/eikek/sharry) - Share files easily over the internet between authenticated and anonymous users (both ways) with resumable up- and downloads. `GPL-3.0` `Scala/Java` :star:39
- [Uguu](https://uguu.se/) - Stores files and deletes after X amount of time. ([Source Code](https://github.com/nokonoko/uguu)) `MIT` `PHP`
- [Up1](https://github.com/Upload/Up1) - Client-side Encrypted Image Host. `MIT` `Nodejs` :star:603
- [uPste](https://u.pste.pw) - Private file hosting application with an emphasis on serving technology communities. ([Source Code](https://github.com/TheReverend403/uPste)) `AGPL-3.0` `PHP`
- [XBackBone](https://github.com/SergiX44/XBackBone) - A simple, fast, lightweight and powerful ShareX (a free and open-source screenshot utility for Windows) PHP backend. `AGPL-3.0` `PHP` :star:31
- [YouTransfer](http://www.youtransfer.io) - YouTransfer is a simple but elegant self-hosted file transfer and sharing solution. ([Demo](http://demo.youtransfer.io/), [Source Code](https://github.com/remie/YouTransfer)) `Apache-2.0` `Nodejs`

_Command-line file upload_

- [Beauties](https://github.com/dsx/beauties) - Minimalist file sharing written in Go, to be used primarily from Unix shell (e.g. with curl). Can be built as a Debian package for easy install. `MIT` `Go` :star:13
- [transfer.sh](https://transfer.sh) - Easy file sharing from the command line. ([Source Code](https://github.com/dutchcoders/transfer.sh)) `MIT` `Go`

#### Web based file managers

- [Apaxy](https://oupala.github.io/apaxy/) - Theme built to enhance the experience of browsing web directories, using the mod_autoindex Apache module and some CSS to override the default style of a directory listing. ([Source Code](https://github.com/AdamWhitcroft/Apaxy)) `Unlicense` `HTML`
- [DirectoryLister](http://www.directorylister.com/) - Simple PHP based directory lister that lists a directory and all it's sub-directories and allows you to navigate there within. ([Source Code](https://github.com/DirectoryLister/DirectoryLister)) `MIT` `PHP`
- [Encode Explorer](http://encode-explorer.siineiolekala.net/) - Encode Explorer is a single page file browser, it is simple and functional. ([Demo](http://encode-explorer.siineiolekala.net/explorer/index.php), [Source Code](https://github.com/marekrei/encode-explorer)) `MIT` `PHP`
- [explorer](https://soyuka.github.io/explorer/) - Highly-configurable directory listing made with nodejs. ([Source Code](https://github.com/soyuka/explorer)) `MIT` `Nodejs`
- [filebrowser](https://filebrowser.xyz/) - Web File Manager which can be used as a middleware or standalone app. ([Source Code](https://github.com/filebrowser/filebrowser)) `Apache-2.0` `Go/VueJS`
- [Filestash](https://www.filestash.app/) - A web file manager that lets you manage your data anywhere it is located: FTP, SFTP, WebDAV, Git, S3, Minio, Dropbox, or Google Drive . ([Demo](https://demo.filestash.app/), [Source Code](https://github.com/mickael-kerjean/filestash)) `AGPL-3.0` `Go`
- [goBrowser](https://github.com/xataz/gobrowser) - Simple http file browser. `GPL-3.0` `Go` :star:74
- [Gossa](https://github.com/pldubouilh/gossa) - Gossa is a light and simple webserver for your files. `MIT` `Go` :star:166
- [h5ai](https://larsjung.de/h5ai/) - Modern file indexer for HTTP web servers with focus on your files. Directories are displayed in a appealing way and browsing them is enhanced by different views, a breadcrumb and a tree overview. ([Demo](https://larsjung.de/h5ai/demo/), [Source Code](https://github.com/lrsjng/h5ai)) `MIT` `PHP`
- [IFM](https://github.com/misterunknown/ifm) - Single script file manager. `MIT` `PHP` :star:160
- [ResourceSpace](https://www.resourcespace.com) - ResourceSpace open source digital asset management software is the simple, fast, and free way to organise your digital assets. ([Demo](https://www.resourcespace.com/trial), [Source Code](https://www.resourcespace.com/svn)) `Other` `PHP`
- [s3server](https://github.com/jessfraz/s3server) - Simple HTTP interface to index and browse files in a public S3 or Google Cloud Storage bucket. ([Demo](https://gifs.jessfraz.com/)) `MIT` `Go` :star:125
- [Sprut.io](https://sprut.io) - 2 panel file manager with drag and drop features, code editor, text search, hotkeys. ([Demo](https://demo.sprut.io:9443), [Source Code](https://github.com/LTD-Beget/sprutio)) `GPL-3.0` `Python`
- [Surfer](https://github.com/nebulade/surfer) - Simple static file server with webui to manage files. `MIT` `Nodejs` :star:23
- [TagSpaces](https://www.tagspaces.org/) - TagSpaces is an offline, cross-platform file manager and organiser that also can function as a note taking app. The WebDAV version of the application can be installed on top of a WebDAV servers such as Nextcloud or ownCloud. ([Demo](http://demo.tagspaces.org), [Source Code](https://github.com/tagspaces/tagspaces)) `AGPL-3.0` `Javascript`

## Games

**[`^        back to top        ^`](#)**

_Games, game servers and control panels._

- [A Dark Room](https://github.com/doublespeakgames/adarkroom) - Minimalist text adventure game for your browser. ([Demo](http://adarkroom.doublespeakgames.com/)) `MPL-2.0` `HTML5` :star:4506
- [Agar.IO Clone](https://github.com/huytd/agar.io-clone) - Agar.io clone written with Socket.IO and HTML5 canvas. `MIT` `Nodejs` :star:2445
- [battlecraft](https://github.com/jbreindel/battlecraft) - Fully distributed multiplayer browser game. ([Demo](http://battlecraft.online)) `Apache-2.0` `Erlang` :star:15
- [Clumsy Bird](https://github.com/ellisonleao/clumsy-bird) - MelonJS port of the famous Flappy Bird Game. ([Demo](http://ellisonleao.github.io/clumsy-bird/)) `MIT` `Nodejs` :star:1224
- [elevatorsaga](http://play.elevatorsaga.com/) - The elevator programming game. ([Source Code](https://github.com/magwo/elevatorsaga)) `MIT` `Javascript`
- [Hextris](https://github.com/Hextris/hextris) - Fast paced HTML5 puzzle game inspired by Tetris. ([Demo](https://hextris.github.io/hextris)) `GPL-3.0` `HTML5` :star:1507
- [Lila](https://lichess.org/) - The forever free, adless and open source chess server powering lichess.org, with official iOS and Android client apps. ([Source Code](https://github.com/ornicar/lila)) `AGPL-3.0` `Scala`
- [Posio](https://github.com/abrenaut/posio) - Geography multiplayer game. `MIT` `Python` :star:394
- [RconCli](https://github.com/gorcon/rcon-cli) - CLI for executing queries on a remote Valve Source dedicated server using the RCON Protocol. `MIT` `Go` :star:2
- [SourceBans++](https://sbpp.github.io) - Admin, ban, and communication management system for games running on the Source engine. ([Source Code](https://github.com/sbpp/sourcebans-pp)) `CC-BY-SA-4.0` `PHP`
- [Spyfall](https://github.com/mpcovcd/spyfall) - Fan made web version of the Spyfall party game. ([Demo](http://spyfall.crabhat.com/)) `MIT` `HTML/Javascript` :star:343
- [Teeworlds](https://www.teeworlds.com) - Open source 2D retro multiplayer shooter. ([Source Code](https://github.com/teeworlds/teeworlds)) `BSD-3-Clause/Other` `C++`
- [TournamentMango](http://tournamentmango.com/) - TournamentMango is an open source tournament bracket and user management system. You can build an archive of players and keep track of all their scores over time as well as their regular characters, games, and aliases. ([Source Code](https://github.com/seiyria/tournamentmango)) `MIT` `Javascript`

## Gateways

**[`^        back to top        ^`](#)**

- [GateOne](http://liftoffsoftware.com/Products/GateOne) - Gate One is an HTML5 web-based terminal emulator and SSH client. ([Source Code](https://github.com/liftoff/GateOne)) `AGPL-3.0` `Python`
- [Guacamole](http://guac-dev.org/) - Guacamole is a clientless remote desktop gateway. It supports standard protocols like VNC and RDP. ([Source Code](https://github.com/glyptodon/)) `Apache-2.0` `Java/C`
- [oneye](https://oneye-project.org/) - Cloud software to access your data from everywhere with any browser. ([Demo](https://wiki.oneye-project.org/0.9:demo), [Source Code](https://github.com/oneye/oneye)) `AGPL-3.0` `PHP`
- [OS.js](https://os.js.org/) - Desktop implementation for your browser with a fully-fledged window manager, Application APIs, GUI toolkits and filesystem abstraction. ([Demo](https://demo.os-js.org/), [Source Code](https://github.com/os-js/OS.js)) `BSD-2-Clause` `Nodejs`

## Groupware

**[`^        back to top        ^`](#)**

- [Citadel](http://www.citadel.org/doku.php) - Groupware including email, calendar/scheduling, address books, forums, mailing lists, IM, wiki and blog engines, RSS aggregation and more. ([Source Code](http://www.citadel.org/doku.php/installation:source)) `GPL-3.0` `C`
- [Cozy Cloud](https://cozy.io) - Personal cloud where you can read your emails or manage and sync your contact, files or calendars, with an app store full of community contributions. ([Source Code](https://github.com/cozy)) `GPL-3.0` `Nodejs`
- [egroupware](http://www.egroupware.org/) - Software suite including calendars, address books, notepad, project management tools, client relationship management tools (CRM), knowledge management tools, a wiki and a CMS. ([Source Code](https://github.com/EGroupware/egroupware)) `GPL-2.0` `PHP`
- [EspoCRM](https://www.espocrm.com/) - CRM with a frontend designed as a single page application, and a REST API. ([Demo](http://demo.espocrm.de/basic/), [Source Code](https://github.com/espocrm/espocrm)) `GPL-3.0` `PHP`
- [Horde](http://www.horde.org/) - The Horde Project is about creating high quality Open Source applications and libraries, based on PHP and the Horde Framework. ([Demo](http://demo.horde.org/login.php), [Source Code](https://github.com/horde/horde)) `GPL-2.0` `PHP`
- [HRCloud2](https://www.honestrepair.net/index.php/hrcloud2/) - Full-featured home hosted Cloud Drive, Personal Assistant, App Launcher, File Converter, Streamer, Share Tool and more. ([Source Code](https://github.com/zelon88/HRCloud2)) `GPL-3.0` `PHP`
- [Kolab](https://kolab.org/) - Kolab community is a unified communication and collaboration system. ([Source Code](https://git.kolab.org/)) `GPL-2.0/LGPL-2.1/GPL-3.0` `C++/Python/PHP`
- [Kopano](https://kopano.com/) - Groupware suite including e-mail, calendars, tasks, todos and notes. Featuring a modern WebApp, DeskApp and mobile access over Z-Push/ActiveSync. ([Demo](http://demo.kopano.com), [Source Code](https://stash.kopano.io)) `AGPL-3.0` `C/Python/PHP`
- [Openmeetings](https://openmeetings.apache.org/index.html) - Openmeetings provides video conferencing, instant messaging, white board, collaborative document editing and other groupware tools using API functions of the Red5 Streaming Server for Remoting and Streaming. ([Source Code](https://openmeetings.apache.org/scm.html)) `Apache-2.0` `Java`
- [SOGo](https://sogo.nu/) - SOGo offers multiple ways to access the calendaring and messaging data. CalDAV, CardDAV, GroupDAV, as well as ActiveSync, including native Outlook compatibility and Web interface. ([Demo](http://demo.sogo.nu/SOGo/), [Source Code](https://github.com/inverse-inc/sogo)) `LGPL-2.1` `Objective-C`
- [SuiteCRM](http://www.suitecrm.com/) - The award-winning, enterprise-class open source CRM. ([Source Code](https://github.com/salesagility/SuiteCRM)) `AGPL-3.0` `PHP`
- [Tine 2.0](https://www.tine20.org) - Contacts, Calendar, Tasks, WebDAV, ActiveSync, VOIP, Mail-Client, CRM, Sales, Projects, Timetracker. ([Demo](https://demo.tine20.net), [Source Code](https://packages.tine20.com/maintenance/source/)) `AGPL-3.0/Other` `PHP`
- [Zimbra Collaboration](https://www.zimbra.com/) - Email, calendar, collaboration server with Web interface and lots of integrations. ([Source Code](https://github.com/zimbra)) `GPL-2.0/CPAL-1.0` `Java`

## Human Resources Management (HRM)

**[`^        back to top        ^`](#)**

- [admidio](https://www.admidio.org/) - Admidio is a free open source user management system for websites of organizations and groups. The system has a flexible role model so that it’s possible to reflect the structure and permissions of your organization. ([Demo](https://www.admidio.org/demo/), [Source Code](https://github.com/Admidio/admidio)) `GPL-2.0` `PHP`
- [IceHrm](https://icehrm.com/) - IceHrm employee management system allows companies to centralize confidential employee information. ([Demo](https://icehrm.com/demo.php), [Source Code](https://github.com/gamonoid/icehrm)) `Apache-2.0` `PHP`
- [OrangeHRM](https://www.orangehrm.com/) - OrangeHRM is a comprehensive HRM system that captures all the essential functionalities required for any enterprise. ([Source Code](https://sourceforge.net/projects/orangehrm/)) `GPL-2.0` `PHP`
- [Sentrifugo](http://www.sentrifugo.com/) - Sentrifugo is a HRM system that can be easily configured to meet your organizational needs. ([Source Code](https://github.com/sapplica/sentrifugo)) `GPL-3.0` `PHP`
- [TimeOff.Management](https://timeoff.management) - Simple yet powerful absence management software for small and medium size business. ([Demo](https://app.timeoff.management), [Source Code](https://github.com/timeoff-management/application)) `MIT` `Nodejs`

## Internet Of Things (IoT)

**[`^        back to top        ^`](#)**

- [DeviceHive](https://www.devicehive.com/) - Open Source IoT Platform with a wide range of integration options. ([Demo](https://playground.devicehive.com/), [Source Code](https://github.com/devicehive/devicehive-java-server)) `Apache-2.0` `Java`
- [Domoticz](https://www.domoticz.com/) - Home Automation System that lets you monitor and configure various devices like: Lights, Switches, various sensors/meters like Temperature, Rain, Wind, UV, Electra, Gas, Water and much more. ([Source Code](https://github.com/domoticz/domoticz), [Clients](https://github.com/domoticz/domoticz-android)) `GPL-3.0` `C/C++`
- [Thingsboard](https://thingsboard.io/) - Open-source IoT Platform - Device management, data collection, processing and visualization. ([Demo](https://demo.thingsboard.io/signup), [Source Code](https://github.com/thingsboard/thingsboard)) `Apache-2.0` `Java`
- [Thingspeak](https://thingspeak.com/) - Open source “Internet of Things” application and API to store and retrieve data from things using HTTP. ([Demo](https://thingspeak.com/channels/public), [Source Code](https://github.com/iobridge/thingspeak)) `GPL-3.0` `Ruby`

## Knowledge Management Tools

**[`^        back to top        ^`](#)**

- [Mindmaps](https://github.com/drichard/mindmaps) - Open source, offline capable, mind mapping application. ([Demo](http://drichard.org/mindmaps/)) `AGPL-3.0` `HTML5` :star:1681
- [My Mind](https://github.com/ondras/my-mind) - Web application for creating and managing mind maps. ([Demo](https://my-mind.github.io/?url=examples%2Ffeatures.mymind)) `MIT` `Javascript` :star:2214
- [TagTool](https://letstag.it) - Collaborative knowledge management tool. Create word clouds and link the elements. ([Demo](https://demo.letstag.it), [Source Code](https://gitlab.com/tagtool/tagtool)) `MIT` `Python`
- [Weaviate](https://github.com/semi-technologies/weaviate) - GraphQL based Knowledge Graph. ([Demo](https://semi.technology)) `BSD-3-Clause` `Go` :star:144

## Learning and Courses

**[`^        back to top        ^`](#)**

- [Canvas LMS](https://www.canvaslms.com/) - Canvas is the trusted, open-source learning management system (LMS) that is revolutionizing the way we educate. ([Demo](https://canvas.instructure.com/register), [Source Code](https://github.com/instructure/canvas-lms)) `AGPL-3.0` `Ruby`
- [Chamilo LMS](https://chamilo.org/) - Chamilo LMS allows you to create a virtual campus for the provision of online or semi-online training. ([Source Code](https://github.com/chamilo/chamilo-lms)) `GPL-3.0` `PHP`
- [edX](https://www.edx.org/) - The Open edX platform is open-source code that powers edX.org. ([Source Code](https://github.com/edx/)) `AGPL-3.0` `Python`
- [ILIAS](http://www.ilias.de) - ILIAS is the Learning Management System that can cope with anything you throw at it. ([Demo](http://demo.ilias.de), [Source Code](https://github.com/ILIAS-eLearning/ILIAS)) `GPL-3.0` `PHP`
- [Mahara](https://mahara.org/) - Open Source fully featured web application to build students electronic portfolio. ([Source Code](https://github.com/MaharaProject/mahara)) `GPL-3.0` `PHP`
- [Moodle](https://moodle.org/) - Moodle is a learning and courses platform with one of the largest open source communities worldwide. ([Demo](https://moodle.org/demo/), [Source Code](https://git.moodle.org/gw)) `GPL-3.0` `PHP`
- [Open eClass](http://www.openeclass.org/) - Open eClass is an advanced e-learning solution that can enhance the teaching and learning process. ([Demo](http://demo.openeclass.org/), [Source Code](https://github.com/gunet/openeclass)) `GPL-2.0` `PHP`
- [OpenOLAT](https://www.openolat.com/?lang=en) - OpenOLAT is a web-based learning management system for teaching, education, assessment and communication. ([Demo](https://learn.olat.com), [Source Code](https://github.com/OpenOLAT/OpenOLAT)) `Apache-2.0` `Java` 
- [RELATE](https://documen.tician.de/relate/) - RELATE is a web-based courseware package, includes features such as: flexible rules, statistics, multi-course support, class calendar. ([Source Code](https://github.com/inducer/relate)) `MIT` `Python`
- [RosarioSIS](https://www.rosariosis.org/) - RosarioSIS, free Student Information System for school management. ([Demo](https://www.rosariosis.org/demo/), [Source Code](https://gitlab.com/francoisjacquet/rosariosis/)) `GPL-2.0` `PHP`
- [Sakai](https://www.sakaiproject.org/) - The Sakai project provides a flexible and feature-rich environment for teaching, learning, research and other collaboration. ([Demo](https://www.sakaiproject.org/try-sakai), [Source Code](https://github.com/sakaiproject/sakai)) `ECL-2.0` `Java`
- [SchoolTool](http://schooltool.org/) - SchoolTool is free administrative software for schools. It includes demographics, gradebook, attendance, calendaring, reporting and more for primary and secondary schools. ([Source Code](http://bazaar.launchpad.net/~schooltool-owners/schooltool/2.8/files)) `GPL-2.0` `Python`

## Maps and Global Positioning System (GPS)

**[`^        back to top        ^`](#)**

- [Graphhopper](https://graphhopper.com/) - Fast routing library and server using OpenStreetMap. ([Source Code](https://github.com/graphhopper/graphhopper)) `Apache-2.0` `Java`
- [MapBBCodeShare](https://github.com/MapBBCode/share.mapbbcode.org) - Tool for sharing custom OSM maps. Support for annotated markers, polygons, lines, multi-format import/export, multiple layers, shortlinks. ([Demo](http://share.mapbbcode.org/)) `WTFPL/Other` `PHP` :star:36
- [Nominatim](https://nominatim.org/) - Server application for reverse geocoding (address -> coordinates) on OpenStreetMap data. ([Source Code](https://github.com/openstreetmap/Nominatim)) `GPL-2.0` `C`
- [OpenGTS](http://www.opengts.org/) - Entry-level fleet tracking system. Supports variety of tracking devices and protocols. Comes with rich web-interface and reporting features. ([Demo](http://track.opengts.org/track/Track), [Source Code](https://sourceforge.net/projects/opengts/files/server-base/)) `Apache-2.0` `Java`
- [OpenStreetMap](http://www.openstreetmap.org/) - OpenStreetMap is a map of the world, created by people like you and free to use under an open license. ([Source Code](https://github.com/openstreetmap/openstreetmap-website)) `GPL-2.0` `Ruby`
- [Orion](https://github.com/LINKIWI/orion-web) - Powerful OwnTracks API-compliant location data visualization frontend for the web. ([Demo](https://linkiwi.github.io/orion-web/)) `MIT` `Python/Nodejs` :star:79
- [OwnTracks Recorder](https://github.com/owntracks/recorder) `⚠` - Store and access data published by [OwnTracks](http://owntracks.org/) location tracking apps. `GPL-2.0` `C`/`Lua`
- [TileServer GL](http://tileserver.readthedocs.io/) - Vector and raster maps with GL styles. Server side rendering by Mapbox GL Native. Map tile server for Mapbox GL JS, Android, iOS, Leaflet, OpenLayers, GIS via WMTS, etc. ([Source Code](https://github.com/klokantech/tileserver-gl)) `BSD-2-Clause` `Nodejs`
- [TileServer PHP](https://github.com/klokantech/tileserver-php) - Serve map tiles from any PHP hosting. `BSD-2-Clause` `PHP` :star:362
- [Traccar](https://www.traccar.org/) - Java application to track GPS positions. Supports loads of tracking devices and protocols, has an Android and iOS App. Has a web interface to view your trips. ([Demo](http://demo.traccar.org/), [Source Code](https://github.com/traccar)) `Apache-2.0` `Java`
- [uMap](https://umap.openstreetmap.fr/en/) - Create maps with OpenStreetMap layers in a minute and embed them in your site. ([Source Code](https://github.com/umap-project/umap)) `WTFPL` `Python`

## Media Streaming

**[`^        back to top        ^`](#)**

See also <https://en.wikipedia.org/wiki/List_of_streaming_media_systems>, <https://en.wikipedia.org/wiki/Comparison_of_streaming_media_systems>

### Multimedia Streaming

- [Darwin Streaming Server](https://macosforge.github.io/dss/) - High performance server for streaming QuickTime and MPEG-4 media over RTP and RTSP protocols. Originated as Apple’s QTSS. ([Source Code](https://github.com/macosforge/dss)) `APSL-2.0` `C++`
- [Gerbera](https://gerbera.io/) - Gerbera is an UPnP Media Server. It allows you to stream your digital media throughout your home network and listen to/watch it on a variety of UPnP compatible devices. ([Source Code](https://github.com/gerbera/gerbera)) `GPL-2.0` `C++`
- [homehost](https://github.com/ridhwaans/homehost) `⚠` - Self-hosted React + Redux app that streams your media collection (music, movies, books, podcasts, comics etc). `MIT` `Nodejs`
- [Icecast 2](http://www.icecast.org/) - streaming audio/video server which can be used to create an Internet radio station or a privately running jukebox and many things in between. ([Source Code](https://git.xiph.org/?p=icecast-server.git;a=summary), [Clients](http://www.icecast.org/apps/)) `GPL-2.0` `C`
- [Jellyfin](https://jellyfin.media) - Streaming audio/video server with a slick UI and robust transcoding capabilities (fork of Emby). ([Source Code](https://github.com/jellyfin/jellyfin)) `GPL-2.0` `C#`
- [MistServer](http://mistserver.org/) - Streaming media server that works well in any streaming environment. ([Source Code](https://github.com/DDVTECH/mistserver)) `AGPL-3.0` `C++`
- [ReadyMedia](http://sourceforge.net/projects/minidlna/) - Simple media server software, with the aim of being fully compliant with DLNA/UPnP-AV clients. Formerly known as MiniDLNA. ([Source Code](https://sourceforge.net/p/minidlna/git/ci/master/tree/)) `GPL-2.0` `C`
- [Rygel](https://wiki.gnome.org/action/show/Projects/Rygel) - Rygel is a UPnP AV MediaServer that allows you to easily share audio, video, and pictures. Media player software may use Rygel to become a MediaRenderer that may be controlled remotely by a UPnP or DLNA Controller. ([Source Code](https://gitlab.gnome.org/GNOME/rygel/)) `GPL-3.0` `C`
- [üWave](http://u-wave.net/) `⚠` - üWave is a self-hosted collaborative listening platform. Users take turns playing media—songs, talks, gameplay videos, or anything else—from a variety of media sources like YouTube and SoundCloud. ([Demo](https://wlk.yt/), [Source Code](https://github.com/u-wave)) `MIT` `Nodejs`


### Audio Streaming

- [Ampache](http://ampache.org/) - Web based audio/video streaming application. ([Demo](http://play.dogmazic.net/), [Source Code](https://github.com/ampache/ampache)) `AGPL-3.0` `PHP`
- [Airsonic](https://airsonic.github.io/) - Open-source web-based media streamer and jukebox. A fork of Subsonic's last open-source release, before it switched licenses. ([Source Code](https://github.com/airsonic/airsonic), [Clients](https://airsonic.github.io/docs/apps/)) `GPL-3.0` `Java`
- [AzuraCast](https://www.azuracast.com/) - A modern and accessible self-hosted web radio management suite. ([Source Code](https://github.com/AzuraCast/AzuraCast)) `Apache-2.0` `PHP`
- [Beets](http://beets.io/) - Music library manager and MusicBrainz tagger (command-line and Web interface). ([Source Code](https://github.com/beetbox/beets)) `MIT` `Python`
- [CherryMusic](http://www.fomori.org/cherrymusic/) - Minimalistic Web-Mediaplayer. ([Source Code](https://github.com/devsnd/cherrymusic)) `GPL-3.0` `Python`
- [cloudtunes](https://github.com/jkbrzt/cloudtunes) `⚠` - Web-based music player for the cloud. `MIT` `Python`
- [Compactd](https://github.com/compactd/compactd) - Remote music player that supports adding content. `MIT` `Nodejs` :star:58
- [FriendsRadio](https://github.com/xouabita/friends-radio) `⚠` - Share music with your friends from Youtube and Soundcloud. ([Demo](https://friends-radio.herokuapp.com/)) `MIT` `Nodejs`
- [Funkwhale](https://funkwhale.audio/) - A modern, web-based, convivial, multi-user and free music server. ([Demo](https://demo.funkwhale.audio/), [Source Code](https://code.eliotberriot.com/funkwhale/funkwhale)) `BSD-3-Clause` `Python/Django`
- [GNU FM](https://gnu.io/fm/) - Running music community websites, alternative to last.fm. ([Source Code](http://git.savannah.gnu.org/cgit/librefm.git/)) `AGPL-3.0` `PHP`
- [Groove Basin](https://github.com/andrewrk/groovebasin) - Music player server with a web-based user interface inspired by Amarok 1.4. `MIT` `Nodejs` :star:1724
- [koel](http://koel.phanan.net/) - Personal music streaming server that works. ([Source Code](https://github.com/phanan/koel)) `MIT` `PHP`
- [LibreTime](http://libretime.org) - Simple, open source platform that lets you broadcast streaming radio on the web (fork of [Airtime](https://github.com/sourcefabric/Airtime)). ([Source Code](https://github.com/LibreTime/libretime)) `AGPL-3.0` `PHP`
- [LMS](https://github.com/epoupon/lms) - Access your self-hosted music using a web interface. ([Demo](http://lms.demo.poupon.io/)) `GPL-3.0` `C++` :star:55
- [Mopidy](http://mopidy.readthedocs.org/) - Extensible music server. Offers a superset of the mpd API, as well as integration with 3rd party services like Spotify, SoundCloud etc. ([Source Code](https://github.com/mopidy/mopidy)) `Apache-2.0` `Python`
  - [Moped](https://github.com/martijnboland/moped) - Responsive HTML5 + Javascript client for the Mopidy music server. `MIT` `HTML5` :star:417
  - [Mopidy MusicBox](https://github.com/pimusicbox/mopidy-musicbox-webclient) - Web Client for Mopidy Music Server. `Apache-2.0` `HTML5` :star:338
  - [Mopidy-Party](https://github.com/Lesterpig/mopidy-party) - Mopidy web extension designed for party! Let your guests manage the sound. `Apache-2.0` `Python` :star:70
- [mpd](http://www.musicpd.org/) - Daemon to remotely play music, stream music, handle and organize playlists. Many clients available. ([Source Code](https://github.com/MusicPlayerDaemon/MPD)) `GPL-2.0` `C++`
  - [ympd](http://www.ympd.org/) - Standalone MPD Web GUI written in C, utilizing Websockets and Bootstrap/JS. ([Source Code](https://github.com/notandy/ympd)) `GPL-2.0` `C`
- [mStream](http://mstream.io/) - Music streaming server with GUI management tools. Runs on Mac, Windows, and Linux. ([Demo](https://darncoyotes.mstream.io/), [Source Code](https://github.com/IrosTheBeggar/mStream)) `GPL-2.0` `Nodejs`
- [Music Browser](https://github.com/henrik242/musicbrowser) - Browser and streamer for your music collection. It is runs on most operating systems, and is light enough to run flawlessly on NAS devices. `GPL-3.0` `PHP` :star:20
- [musikcube](https://musikcube.com/) - Streaming audio server with Linux/macOS/Windows/Android clients. ([Source Code](https://github.com/clangen/musikcube)) `BSD-3-Clause` `C++`
- [Polaris](https://github.com/agersant/polaris) - Music browsing and streaming application optimized for large music collections, ease of use and high performance. `MIT` `Rust` :star:329
- [Sonerezh](https://www.sonerezh.bzh/) - Self-hosted, web-based application for stream your music, everywhere. ([Demo](https://www.sonerezh.bzh/demo/), [Source Code](https://github.com/sonerezh/sonerezh)) `GPL-3.0` `PHP`
- [Volumio](https://volumio.org/) - A free and open source linux distribution, designed and fine-tuned exclusively for music playback. ([Source Code](https://github.com/volumio/Volumio2)) `GPLv3` `NodeJS`

### Video Streaming

- [crtmpserver](https://packages.debian.org/stable/crtmpserver) - High performance RTMP/RTSP streaming server. `GPL-3.0` `C++`
- [CyTube](https://github.com/calzoneman/sync) - CyTube is a web application providing media synchronization, chat, and more for an arbitrary number of channels. ([Demo](http://cytu.be)) `MIT` `Nodejs` :star:832
- [Hellowlol HTPC Manager fork](https://github.com/Hellowlol/HTPC-Manager) - Fully responsive interface to manage all your favorite media on your HTPC. `MIT` `Python` :star:321
- [Myflix](https://github.com/pastapojken/Myflix) - Self-hosted, super lightweight Netflix alternative. `MIT` `Shell` :star:182
- [Odd Networks](http://oddnetworks.com) - Open source video management system (VMS) and API for collections and videos with supporting SDKs for Roku, Apple iOS/tvOS, Google Android, and Amazon FireTV. ([Source Code](https://github.com/oddnetworks/oddworks)) `MIT` `Nodejs`
- [Open Streaming Platform](https://gitlab.com/Deamos/flask-nginx-rtmp-manager) - Self-Hosted alternative to Twitch and Youtube Live for live and on-demand video streaming. ([Demo](https://osptest.divby0.net)) `MIT` `Python` 
- [PeerTube](https://joinpeertube.org/en/) - Decentralized video streaming platform using P2P (BitTorrent) directly in the web browser. ([Source Code](https://github.com/Chocobozzz/PeerTube)) `AGPL-3.0` `Nodejs`
- [Rapidbay](https://github.com/hauxir/rapidbay/) - Self-hosted torrent videostreaming service/torrent client that allows searching and playing videos from torrents in the browser or from a Chromecast/AppleTV/Smart TV. `MIT` `Python/Docker` :star:62
- [Restreamer](https://datarhei.github.io/restreamer/) - Restreamer allows you to do h.264 real-time video streaming on your website without a streaming provider. ([Source Code](https://github.com/datarhei/restreamer)) `Apache-2.0` `Nodejs/Docker`
- [ShinobiCE](https://gitlab.com/Shinobi-Systems/ShinobiCE) - Open Source CCTV software written in Node with both IP and local camera support. `AGPL-3.0/GPL-3.0` `Nodejs`
- [Streama](https://streamaserver.org/) - Self hosted streaming media server. ([Source Code](https://github.com/streamaserver/streama)) `MIT` `Java`
- [VideoLAN Client (VLC)](https://www.videolan.org/) - Cross-platform multimedia player client and server supporting most multimedia files as well as DVDs, Audio CDs, VCDs, and various streaming protocols. ([Source Code](https://github.com/videolan/vlc)) `Multiple` `C`
- [Zoneminder](https://www.zoneminder.com/) - Closed-circuit television (CCTV) software application which supports IP, USB and Analog cameras. ([Source Code](https://github.com/ZoneMinder/ZoneMinder)) `GPL-2.0` `PHP`

## Misc/Other

**[`^        back to top        ^`](#)**

- [411](https://demo.fouroneone.io/) - Alert Management Web Application. ([Source Code](https://github.com/etsy/411)) `MIT` `PHP`
- [AlertHub](https://github.com/Ardakilic/alerthub) `⚠` - AlertHub is a simple tool to get alerted from GitHub releases. `MIT` `Nodejs`
- [Anchr](https://anchr.io) - Anchr is a toolbox for tiny tasks on the internet, including bookmark collections, URL shortening and (encrypted) image uploads. ([Source Code](https://github.com/n1try/anchr)) `GPL-3.0` `Nodejs`
- [Anuko](https://www.anuko.com/time_tracker/index.htm) - Anuko provides simple time and project tracking on a selfhosted basis. ([Demo](https://timetracker.anuko.com/), [Source Code](https://github.com/anuko/timetracker)) `Other` `PHP`
- [asciiflow](http://asciiflow.com/) - Flow Diagram Drawing Tool. ([Source Code](https://github.com/lewish/asciiflow2)) `GPL-3.0` `Java/JavaScript`
- [blynk](http://www.blynk.cc/) - Platform with iOS and Android apps to control Arduino, ESP8266, Raspberry Pi and similar microcontroller boards over the Internet. ([Source Code](https://github.com/blynkkk/blynk-server)) `AGPL-3.0` `Java`
- [CUPS](https://www.cups.org/) - The Common Unix Print System uses Internet Printing Protocol (IPP) to support printing to local and network printers. ([Source Code](https://github.com/apple/cups)) `GPL-2.0` `C`
- [DomainMOD](https://domainmod.org) - Application to manage your domains and other internet assets in a central location. DomainMOD includes a Data Warehouse framework that allows you to import your WHM/cPanel web server data so that you can view, export, and report on your data. ([Demo](https://demo.domainmod.org), [Source Code](https://github.com/domainmod/domainmod)) `GPL-3.0` `PHP`
- [EasyBook Project](http://easybook-project.org/) - Book publishing as easy as it should be. ([Source Code](https://github.com/javiereguiluz/easybook)) `MIT` `PHP`
- [Flox](https://github.com/devfake/flox) `⚠` - Self hosted movie, TV series and anime watch list with a 3-point rating system. Uses The Movie Database backend for information. ([Demo](http://80.240.132.120/flox-demo/public/)) `MIT` `PHP`
- [formspree](https://formspree.io/) `⚠` - Just send your form to our URL and we'll forward it to your email. No PHP, Javascript or sign up required. ([Demo](http://test.formspree.io/), [Source Code](https://github.com/formspree/formspree)) `AGPL-3.0` `Python`
- [GeneWeb](https://geneweb.tuxfamily.org/wiki/GeneWeb) - GeneWeb is an open source genealogy software written in OCaml. It comes with a Web interface and can be used off-line or as a Web service. ([Demo](https://demo.geneweb.tuxfamily.org/gw7/), [Source Code](https://github.com/geneweb/geneweb)) `GPL-2.0` `OCAML`
- [How Secure Is My Password](https://github.com/howsecureismypassword/hsimp) - Rather than just saying a password is "weak" or "strong", How Secure is My Password? lets your users know how long it would take someone to crack their password. ([Demo](https://howsecureismypassword.net/)) `MIT` `Javascript` :star:357
- [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper) `⚠` - Hassle-Free Way to Self-Host Google Fonts. Get eot, ttf, svg, woff and woff2 files + CSS snippets. ([Demo](https://google-webfonts-helper.herokuapp.com/)) `MIT` `Nodejs`
- [ytdl-webserver](https://github.com/Algram/ytdl-webserver) - Docker-ready webserver for downloading youtube videos. `MIT` `Nodejs` :star:1162
- [Kimai](http://www.kimai.org/) - Simple time and project tracking. ([Demo](http://www.kimai.org/demo/), [Source Code](https://github.com/kimai/kimai)) `GPL-3.0` `PHP`
- [King Phisher](https://github.com/securestate/king-phisher) - King Phisher is a tool for testing and promoting user awareness by simulating real world phishing attacks. `BSD-3-Clause` `Python` :star:948
- [Maily Form](https://github.com/jlelse/Maily-Form) - Self-hosted service you can use to place forms on static sites. It uses nodemailer and you can host it with Docker. `GPL-3.0` `Nodejs/Docker` :star:23
- [Monica](https://monicahq.com/) - Personal relationship manager, and a new kind of CRM to organize interactions with your friends and family. ([Source Code](https://github.com/monicahq/monica)) `AGPL-3.0` `PHP`
- [Musical Artifacts](https://musical-artifacts.com/) - Helping to catalog, preserve and free the artifacts you need to produce music. ([Source Code](https://github.com/lfzawacki/musical-artifacts)) `MIT` `Ruby`
- [nnmm](https://github.com/Mechazawa/nnmm) - Super tiny pastebin/url minifier "microservice". `Beerware` `PHP` :star:39
- [Notica](https://notica.us) - Lets you send browser notifications from your terminal to your desktop or phone. No installation or registration is required. ([Source Code](https://github.com/tannercollin/Notica)) `MIT` `Nodejs`
- [Ombi](https://ombi.io/) - A content request system for Plex/Emby, connects to SickRage, CouchPotato, Sonarr, with a growing feature set. ([Demo](https://demo.ombi.io/), [Source Code](https://github.com/tidusjar/Ombi)) `GPL-2.0` `C#`
- [PassCheck](https://passcheck.xyz/) - A web application featuring some handy password tools, including a password generator, strength checker and HaveIBeenPwned breach checker. ([Source Code](https://github.com/apacketofsweets/PassCheck)) `MIT` `JavaScript`
- [ReleaseBell](https://releasebell.com/) - Send release notifications for starred Github repos. ([Source Code](https://git.cloudron.io/cloudron/releasebell)) `MIT` `Nodejs` 
- [revealjs](https://revealjs.com) - Framework for easily creating beautiful presentations using HTML. ([Demo](https://revealjs.com/), [Source Code](https://github.com/hakimel/reveal.js)) `MIT` `JavaScript`
- [SANE Network Scanning](http://sane-project.org/) - Allow remote clients to access image acquisition devices (scanners) available on the local host. ([Source Code](http://www.sane-project.org/cvs.html)) `GPL-2.0` `C`
- [Trello Burndown](https://github.com/swordbeta/trello-burndown) `⚠` - Easy to use SCRUM burndown chart for Trello boards. `MIT` `Go/Docker`
- [Ulterius](https://ulterius.io) - Ulterius is an open-source remote desktop software with lots of awesome functions. ([Demo](https://rainway.io/register/), [Source Code](https://github.com/Ulterius/server)) `MPL-2.0` `C#`
- [ViMbAdmin](http://www.vimbadmin.net/) - Provides a web based virtual mailbox administration system to allow mail administrators to easily manage domains, mailboxes and aliases. ([Demo](http://www.vimbadmin.net/demo/auth/login), [Source Code](https://github.com/opensolutions/ViMbAdmin)) `GPL-3.0` `PHP`
- [visualCaptcha](http://visualcaptcha.net/) - Configurable captcha solution, focusing on accessibility and simplicity whilst maintaining security. ([Demo](http://demo.visualcaptcha.net/), [Source Code](https://github.com/emotionLoop/visualCaptcha)) `MIT` `PHP/Nodejs/Ruby/Python`
- [Web fonts repository](https://github.com/Finesse/web-fonts-repository) - A simple webfont hosting. Google Fonts alternative for your own fonts. `MIT` `PHP` :star:24
- [webtrees](https://www.webtrees.net) - Webtrees is the web's leading on-line collaborative genealogy application. ([Demo](https://dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo), [Source Code](https://github.com/fisharebest/webtrees)) `GPL-3.0` `PHP`

## Money, Budgeting and Management

**[`^        back to top        ^`](#)**

See also https://github.com/n1trux/awesome-sysadmin#it-asset-management

- [Akaunting](https://akaunting.com/) - Akaunting is a free, online and open source accounting software designed for small businesses and freelancers. ([Source Code](https://github.com/akaunting/akaunting)) `GPL-3.0` `PHP`
- [BTCPay Server](https://btcpayserver.org/) - A self-hosted Bitcoin and other cryptocurrencies payment processor. ([Demo](https://mainnet.demo.btcpayserver.org/), [Source Code](https://github.com/btcpayserver/)) `MIT` `C#`
- [Benedetto](https://github.com/arecker/bennedetto) - Bennedetto is a simple, turn-based budget management app. `GPL-3.0` `Python` :star:299
- [Boodle](https://github.com/manuel-uberti/boodle) - Simple accounting single-page application in Clojure and ClojureScript. `EPL-1.0` `Clojure` :star:129
- [Budget App](https://github.com/paukiatwee/budgetapp) - Budget App is an open source personal budgeting application. `Apache-2.0` `Java` :star:212
- [Dot Ledger](https://www.dotledger.com/) - Web-based personal finance management tool. ([Demo](https://demo.dotledger.com/), [Source Code](https://github.com/dotledger/dotledger)) `Apache-2.0` `Ruby`
- [Economizzer](http://www.economizzer.org/) - An easy and secure system for you to manage your personal money and achieve your goals, and can be accessed by computer, tablet or smartphone. ([Demo](https://github.com/gugoan/economizzer#live-demo), [Source Code](https://github.com/gugoan/economizzer)) `MIT` `PHP`
- [ExMoney](https://github.com/gaynetdinov/ex_money) - Self-hosted personal finance app. `ISC` `Elixir` :star:118
- [Firefly III](https://firefly-iii.org/) - Firefly III is a modern financial manager. It helps you to keep track of your money and make budget forecasts. It supports credit cards, has an advanced rule engine and can import data from many banks. It's powered by Laravel and requires PHP7.2. ([Demo](https://demo.firefly-iii.org/), [Source Code](https://github.com/firefly-iii/firefly-iii)) `GPL-3.0` `PHP`
- [Fava](https://beancount.github.io/fava/) - Fava is the web frontend of Beancount, a text based double-entry accounting system. ([Demo](https://fava.pythonanywhere.com/example-with-budgets/income_statement/), [Source Code](https://github.com/beancount/fava)) `MIT` `Python`
- [Galette](http://galette.eu/dc/) - Galette is a membership management web application towards non profit organizations. ([Source Code](http://git.tuxfamily.org/galette/galette.git/)) `GPL-3.0` `PHP`
- [GRR](http://grr.devome.com/?lang=en) - Assets management and booking for small/medium companies. ([Source Code](https://github.com/JeromeDevome/GRR)) `GPL-2.0` `PHP`
- [Hospital Run](http://hospitalrun.io/) - Hospital Run is offline enabled hospital management software. ([Source Code](https://github.com/HospitalRun/hospitalrun-server), [Demo](http://hospitalrun.io/demo/)) `GPL-3.0` `Nodejs`
- [Inventaire](https://inventaire.io/welcome) - Collaborative resources mapper project, while yet only focused on exploring books mapping with wikidata and ISBNs. ([Source Code](https://github.com/inventaire/inventaire)) `AGPL-3.0` `Nodejs`
- [Invoice Ninja](https://www.invoiceninja.org/) - Powerful tool to invoice clients online. ([Demo](https://app.invoiceninja.com/invoices/create), [Source Code](https://github.com/invoiceninja/invoiceninja)) `AAL` `PHP`
- [InvoicePlane](https://invoiceplane.com/) - Manage quotes, invoices, payments and customers for your small business. ([Demo](https://demo.invoiceplane.com), [Source Code](https://github.com/InvoicePlane/InvoicePlane)) `MIT` `PHP`
- [IHateMoney](http://ihatemoney.org/) - Manage your shared expenses, easily. ([Demo](https://ihatemoney.org/demo/), [Source Code](https://github.com/spiral-project/ihatemoney)) `BSD-3-Clause` `Python`
- [Kresus](https://kresus.org/) - Open source personal finance manager. ([Demo](https://kresus.org/en/demo.html), [Source Code](https://github.com/kresusapp/kresus)) `MIT` `Nodejs`
- [PartKeepr](https://www.partkeepr.org) - PartKeepr is an electronic part inventory management software. It helps you to keep track of your available parts and assist you with re-ordering parts. ([Demo](https://demo.partkeepr.org/), [Source Code](https://github.com/partkeepr/PartKeepr)) `GPL-3.0` `PHP`
- [SilverStrike](https://silverstrike.org/) - Personal finance management made easy. ([Demo](https://demo.silverstrike.org/), [Source Code](https://github.com/agstrike/silverstrike)) `MIT` `Python/Django`
- [StockazNG](https://dev.sigpipe.me/dashie/StockazNG) - Asset Management System. `MIT` `Python`

## Monitoring

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#monitoring and https://github.com/n1trux/awesome-sysadmin#metric--metric-collection

## Note-taking and Editors

**[`^        back to top        ^`](#)**

*See also [Wikis](#wikis)*

- [BulletNotes](https://bulletnotes.io/) - Workflowy / Dynalist clone with Kanban (Trello) and Calendar functionality. Organize everything. ([Source Code](https://gitlab.com/NickBusey/BulletNotes)) `MIT` `Nodejs`
- [Boostnote](https://boostnote.io/) - The note-taking app for programmers that focuses on markdown, snippets, and customizability. ([Source Code](https://github.com/BoostIO/Boostnote)) `GPL-3.0` `JavaScript`
- [CodiMD](https://demo.codimd.org/) - Realtime collaborative markdown notes on all platforms, formerly HackMD CE. ([Source Code](https://github.com/hackmdio/codimd)) `AGPL-3.0` `Node.js`
- [dillinger](http://dillinger.io/) - The last Markdown editor, ever. ([Source Code](https://github.com/joemccann/dillinger)) `MIT` `Nodejs`
- [Dnote](https://dnote.io) - A simple and encrypted notebook for developers. Protect your privacy and stay focused. ([Source Code](https://github.com/dnote/dnote)) `AGPL-3.0` `Go`
- [DocPHT](https://docpht.org/) - With DocPHT you can take notes and quickly document anything and without the use of any database. ([Demo](https://demo.docpht.org/), [Source Code](https://github.com/kenlog/docpht)) `MIT` `PHP`
- [draw.io](https://draw.io) - Diagram software for making flowcharts, process diagrams, org charts, UML, ER and network diagrams. ([Source Code](https://github.com/jgraph/drawio)) `Apache-2.0` `JavaScript`
- [Joplin](https://joplin.cozic.net/) - Joplin is a note taking application with Markdown editor and encryption support for mobile and desktop platforms. Runs client-side and syncs through self hosted Nextcloud or similar. Consider it like open source alternative to Evernote. ([Source Code](https://github.com/laurent22/joplin)) `MIT` `Nodejs`
- [Leanote](http://leanote.org/) - Leanote, Not Just A Notepad! Open source cloud notepad. ([Demo](https://leanote.com/note), [Source Code](https://github.com/leanote/leanote)) `GPL-2.0` `Go`
- [Markdown Edit](http://georgeosddev.github.com/markdown-edit/) - Online markdown editor/viewer. ([Source Code](https://github.com/georgeOsdDev/markdown-edit)) `MIT` `HTML5`
- [Meemo](https://meemo.minimal-space.de/) - Personal notes stream with Markdown support. ([Source Code](https://github.com/nebulade/meemo)) `MIT` `Nodejs`
- [minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad) - Minimalist notepad.cc clone. `Apache-2.0` `PHP` :star:164
- [MiniNote](https://github.com/n1try/mininote) - Simple Markdown note-taking app with persistence. `MIT` `Nodejs` :star:139
- [OpenNote](https://github.com/FoxUSA/OpenNote) - OpenNote was built to be an open web-based alternative to Microsoft OneNote (T) and EverNote. ([Demo](https://foxusa.github.io/OpenNote/OpenNote/#/folder)) `MIT` `HTML5` :star:1376
- [Paperwork](http://paperwork.rocks) - OpenSource note-taking and archiving alternative to Evernote, Microsoft OneNote and Google Keep. ([Source Code](https://github.com/twostairs/paperwork)) `MIT` `PHP`
- [savepad](https://github.com/shelltr/textpad) - Minimalist notepad based on notepad.cc. `MIT` `PHP` :star:12
- [ShareLaTex](https://www.sharelatex.com/) - Web-based collaborative LaTeX editor. ([Source Code](https://github.com/sharelatex/sharelatex)) `AGPL-3.0` `Ruby`
- [Standard Notes](https://standardnotes.org) - Simple and private notes app. Protect your privacy while getting more done. That's Standard Notes. ([Demo](https://app.standardnotes.org/), [Source Code](https://github.com/standardnotes)) `GPL-3.0` `Ruby`
- [turndown](https://domchristie.github.io/turndown/) - HTML to Markdown converter written in JavaScript. ([Source Code](https://github.com/domchristie/turndown)) `MIT` `Javascript`
- [Trilium Notes](https://github.com/zadam/trilium) - Trilium Notes is a hierarchical note taking application with focus on building large personal knowledge bases. `AGPL-3.0` `Nodejs` :star:5559
- [Turtl](https://turtl.it/) - Totally private personal database and note taking app. ([Source Code](https://github.com/turtl)) `GPL-3.0` `CommonLisp`

## Office Suites

**[`^        back to top        ^`](#)**

- [ Collabora Online Development Edition](https://www.collaboraoffice.com/code) - Collabora Online Development Edition (CODE) is a powerful LibreOffice-based online office that supports all major document, spreadsheet and presentation file formats, which you can integrate in your own infrastructure. ([Source Code](https://cgit.freedesktop.org/libreoffice/online/)) `MPL-2.0` `C++`
- [CryptPad](https://cryptpad.fr/) - CryptPad is the zero knowledge realtime collaborative editor (rich-text, files, source-code, ...). ([Source Code](https://github.com/xwiki-labs/cryptpad)) `AGPL-3.0` `Nodejs`
- [EtherCalc](https://ethercalc.org/) - Web spreadsheet. ([Source Code](https://github.com/audreyt/ethercalc)) `CPAL-1.0/Other` `Nodejs`
- [EtherDraw](https://github.com/JohnMcLear/draw) - Intuitive collaborative drawing web based tool. `Apache-2.0` `Nodejs` :star:441
- [Etherpad](http://etherpad.org/) - Etherpad is a highly customizable Open Source online editor providing collaborative editing in really real-time. ([Demo](https://demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60), [Source Code](https://github.com/ether/etherpad-lite)) `Apache-2.0` `Nodejs`
- [Infinoted](https://github.com/gobby/gobby/wiki/Dedicated%20Server) - Server for [Gobby](https://github.com/gobby/gobby/wiki), a multi-platform collaborative text editor. ([Source Code](https://github.com/gobby/gobby)) `MIT` `C++` :star:445
- [ONLYOFFICE](https://helpcenter.onlyoffice.com/faq/server-opensource.aspx) - Office suite that enables you to manage documents, projects, team and customer relations in one place. ([Source Code](https://github.com/ONLYOFFICE/DocumentServer)) `AGPL-3.0` `Nodejs`
- [PHPOffice](https://github.com/PHPOffice) - PHPOffice contains libraries which permits to write and read files from most office suites. `LGPL-3.0` `PHP`
- [WebODF](http://webodf.org/) - Tools and libraries to view and edit Open Document Format (ODF) files. ([Source Code](https://github.com/kogmbh/WebODF)) `AGPL-3.0` `HTML5`

## Password Managers

**[`^        back to top        ^`](#)**

- [Bitwarden](https://bitwarden.com/) - Password manager with webapp, browser extension, and mobile app. ([Source Code](https://github.com/bitwarden/core)) `AGPL-3.0` `C#`
- [keeweb](https://keeweb.info/) - This webapp is a browser and desktop password manager compatible with KeePass databases. ([Source Code](https://github.com/keeweb/keeweb)) `MIT` `HTML5`
- [Passbolt](https://www.passbolt.com/) - Password manager dedicated for managing passwords in a collaborative way on any Web server, using a MySQL database backend. ([Source Code](https://github.com/passbolt/passbolt_api)) `AGPL-3.0` `PHP`
- [PassIt](https://passit.io/) - Simple password manage with sharing features by group and user, but no administration interface. ([Demo](https://app.passit.io/), [Source Code](https://gitlab.com/passit)) `AGPL-3.0` `Python`
- [Psono](https://psono.com/) - A promising password managers fully featured for teams. ([Demo](https://www.psono.pw), [Source Code](https://gitlab.com/psono)) `Apache-2.0` `Python`
- [sysPass](http://www.syspass.org/) - Multiuser password management system. ([Demo](http://demo.syspass.org/), [Source Code](https://github.com/nuxsmin/sysPass)) `GPL-3.0` `PHP`
- [Teampass](http://teampass.net/) - Password manager dedicated for managing passwords in a collaborative way. One symmetric key is used to encrypt all shared/team passwords and stored server side in a file and the database. works on any server Apache, MySQL and PHP. ([Source Code](https://github.com/nilsteampassnet/TeamPass)) `GPL-3.0` `PHP`

## Pastebins

**[`^        back to top        ^`](#)**

- [0bin](https://github.com/sametmax/0bin) - Client side encrypted pastebin. `WTFPL` `Python` :star:830
- [bepasty](https://bepasty-server.readthedocs.io/en/latest/) - A pastebin for all kinds of files. ([Source Code](https://github.com/bepasty/bepasty-server)) `BSD-2-Clause` `Python`
- [bin](https://github.com/w4/bin) - a paste bin. ([Demo](https://bin.doyle.la)) `WTFPL/0BSD` `Rust` :star:31
- [CoderVault](https://github.com/codervault) - Open source, self-hosted, snippet manager. ([Source Code](https://github.com/codervault/codervault)) `MIT` `Ruby`
- [cryptonote](https://cryptonote.me/) - Simple open source web application that lets users encrypt and share messages that can only be read once. ([Source Code](https://github.com/alainmeier/cryptonote)) `MIT` `Ruby`
- [EdPaste](https://github.com/Edraens/EdPaste) - Self-hosted pastebin written in Laravel (PHP Framework). ([Demo](https://paste.edra.ovh/)) `MIT` `PHP` :star:26
- [fiche](https://github.com/solusipse/fiche) - Command line pastebin, all you need is netcat. ([Demo](http://termbin.com/)) `MIT` `C` :star:674
- [Fugacious](https://fugacio.us) - Open source short-term secure messaging (OSSSM). ([Source Code](https://github.com/fugacious/fugacious)) `CC0-1.0` `Ruby`
- [GIST](https://gitnet.fr/deblan/gist) - GIST is an open-source application to share code. ([Demo](https://gist.deblan.org/)) `GPL-3.0` `PHP`
- [hastebin](http://hastebin.com/about.md) - Open source pastebin written in node.js. ([Demo](http://hastebin.com/), [Source Code](https://github.com/seejohnrun/haste-server)) `MIT` `Nodejs`
- [Modern Paste](https://github.com/LINKIWI/modern-paste) - Modern pastebin with a contemporary, minimalistic user interface backed by a robust feature set. `MIT` `Python` :star:233
- [mojopaste](http://search.cpan.org/dist/App-mojopaste/) - Perl based pastebin. ([Demo](http://p.thorsen.pm/), [Source Code](https://github.com/jhthorsen/app-mojopaste)) `Artistic-2.0` `Perl`
- [NoteHub](https://github.com/chmllr/NoteHub) - Free and Hassle-free Pastebin for Markdown Pages. Simple, clean, password provided, generated-short link. `MIT` `Nodejs` :star:253
- [Paste](https://phpaste.sourceforge.io/) - Paste is forked from the original source pastebin.com used before it was bought. ([Source Code](https://github.com/jordansamuel/PASTE)) `GPL-3.0` `PHP`
- [pastebin](https://github.com/prologic/pastebin) - Simple pastebin service with convenient api and CLI. ([Demo](https://paste.mills.io)) `MIT` `Go` :star:24
- [Pastebin](https://github.com/ewhal/Pastebin) - Modern self-hosted pastebin service with a restful API. `MIT` `Go` :star:88
- [pb](https://github.com/ptpb/pb) - Lightweight pastebin (and url shortener) built using flask. `GPL-3.0` `Python` :star:396
- [pbnh](https://github.com/bhanderson/pbnh) - Pastebin inspired from project pb and hastebin, with an API and a SQL-based backend. `MIT` `Python` :star:9
- [PrivateBin](https://privatebin.info/) - PrivateBin is a minimalist, opensource online pastebin/discussion board where the server has zero knowledge of hosted data. ([Demo](https://privatebin.net/), [Source Code](https://github.com/PrivateBin/PrivateBin)) `Zlib` `PHP`
- [SharpPaste](https://github.com/phonicmouse/SharpPaste) - Cross-platform C# pastebin with client-side AES-256 encryption that just works. ([Demo](https://sharppaste.nl/)) `MIT` `C#/NancyFX` :star:24
- [Snibox](https://snibox.github.io/) - Code snippets manager with attractive tag-oriented interface. ([Demo](https://snibox-demo.herokuapp.com/), [Source Code](https://github.com/snibox/snibox)) `MIT` `Ruby`
- [snipt](https://snipt.net/) - Long-term memory for coders. Share and store code snippets. ([Source Code](https://github.com/nicksergeant/snipt)) `MIT` `Python`
- [Stikked](https://github.com/claudehohl/Stikked) - Advanced and beautiful pastebin. ([Demo](https://paste.scratchbook.ch/)) `GPL-3.0` `PHP` :star:753
- [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age) - Very simple (to deploy and to use) secret message service using Hashicorp Vault as a secrets storage. `MIT` `Go` :star:234
- [tastebin](https://github.com/andreineculau/tastebin) - Updated version of hastebin plus additional features. `Apache-2.0` `Nodejs` :star:25

## Personal Dashboards

**[`^        back to top        ^`](#)**

See also _[Monitoring](#monitoring)_

- [Baby Buddy](https://github.com/cdubz/babybuddy) - Helps caregivers track baby sleep, feedings, diaper changes, and tummy time. ([Demo](https://babybuddy.herokuapp.com/)) `BSD-2-Clause` `Python` :star:783
- [Dj Diabetes](https://github.com/foxmask/dj-diabetes) - My Glucose Manager - follow your daily health. `BSD-3-Clause` `Python` :star:72
- [Habitica](https://habitica.com/) - Habit tracker app which treats your goals like a Role Playing Game. Previously called HabitRPG. ([Source Code](https://github.com/HabitRPG/habitrpg)) `GPL-3.0/CC-BY-NC-SA-3.0/CC-BY-SA-3.0` `Nodejs`
- [Heimdall](https://heimdall.site/) - Heimdall is an elegant solution to organise all your web applications. ([Source Code](https://github.com/linuxserver/Heimdall)) `MIT` `PHP`
- [Homepage](https://github.com/tomershvueli/homepage) - Simple, standalone, self-hosted PHP page that is your window to your server and the web. `MIT` `PHP` :star:162
- [iDashboard-PHP](https://github.com/causefx/iDashboard-PHP) - HTPC Dashboard to load website services. `MIT` `PHP` :star:111
- [Organizr](https://github.com/causefx/Organizr) - Organizr aims to be your one stop shop for your Servers Frontend. `GPL-3.0` `PHP` :star:2143
- [simple-dash](https://github.com/Swagielka/simple-dash) - A simple, fully responsive Dashboard to forward to the services of your choice. ([Demo](https://swagielka.github.io/simple-dash/)) `MIT` `Javascript` :star:110
- [Tipboard](http://allegro.tech/tipboard/) - In-house, tasty, local dashboarding system. ([Source Code](https://github.com/allegro/tipboard)) `Apache-2.0` `Python`
- [wger](https://wger.de/) - Web-based personal workout, fitness and weight logger/tracker. It can also be used as a simple gym management utility and offers a full REST API as well. ([Demo](https://wger.de), [Source Code](https://github.com/rolandgeider/wger)) `AGPL-3.0` `Python`

## Photo and Video Galleries

**[`^        back to top        ^`](#)**

- [Chevereto Free](https://chevereto.com/free) - Powerful and fast image hosting script that allows you to create your very own full featured image hosting website in just minutes. ([Source Code](https://github.com/Chevereto/Chevereto-Free)) `AGPL-3.0` `PHP`
- [Coppermine](http://coppermine-gallery.net/) - Multilingual photo gallery that integrates with various bulletin boards. Includes upload approval and password protected albums. ([Demo](http://coppermine-gallery.net/demo/cpg15x/), [Source Code](https://github.com/coppermine-gallery/cpg1.6.x)) `GPL-3.0` `PHP`
- [CumulusClips](http://cumulusclips.org/) - Your own video sharing website with CumulusClips video sharing script. You can build a YouTube clone where users can upload, rate, comment on videos, and much more. ([Demo](https://tube.devosi.org/)) `GPL-2.0` `PHP`
- [Gallery CSS](https://benschwarz.github.io/gallery-css/) - Gallery.css is all CSS. Think: Simple, maintainable and understandable galleries without the use of Javascript. ([Source Code](https://github.com/benschwarz/gallery-css)) `MIT` `CSS`
- [Lychee](https://lycheeorg.github.io/) - Open source grid and album based photo-management-system. ([Source Code](https://github.com/LycheeOrg/Lychee)) `MIT` `PHP`
- [MediaDrop](https://mediadrop.video/) - Video, audio and podcast publication platform. ([Source Code](https://github.com/mediadrop/mediadrop)) `GPL-3.0` `Python`
- [Mediagoblin](http://mediagoblin.org) - Free software media publishing platform that anyone can run. You can think of it as a decentralized alternative to Flickr, YouTube, SoundCloud, etc. ([Source Code](https://savannah.gnu.org/projects/mediagoblin)) `AGPL-3.0` `Python`
- [MinigalNano](https://github.com/sebsauvage/MinigalNano) - MinigalNano is a very simple image gallery. It adheres to the KISS principle and is very easy to install. MinigalNano does not have a web admin interface: You just upload your images in the photo folder on your server (using FTP, SFTP). `AGPL-3.0` `PHP` :star:132
- [OwnPhotos](https://github.com/hooram/ownphotos) - Self hosted wannabe Google Photos clone, with a slight focus on cool graphs. `MIT` `Python` :star:1197
- [Photato](https://github.com/trebonius0/Photato) - Self-hosted photo gallery, accessible through a responsive WebUI. Directly uses and indexes a specific folder in the filesystem. `AGPL-3.0` `Java` :star:100
- [Photofloat](http://blog.zx2c4.com/567) - Web 2.0 Photo Gallery Done Right via Static JSON and Dynamic Javascript. ([Demo](http://photos.jasondonenfeld.com/)) `GPL-2.0` `Python`
- [PhotoLight](https://github.com/thibaud-rohmer/PhotoLight) - The easiest photo gallery there is. `GPL-3.0` `PHP` :star:26
- [Photonix](https://photonix.org/) - A new web-based photo management application with object recognition, location awareness, color analysis and other ML algorithms. ([Demo](https://demo.photonix.org/), [Source Code](https://github.com/damianmoore/photonix)) `AGPL-3.0` `Python`
- [PhotoPrism](https://photoprism.org) - Personal photo management powered by Go and Google TensorFlow.  Browse, organize, and share your personal photo collection, using the latest technologies to automatically tag and find pictures. ([Source Code](https://github.com/photoprism/photoprism)) `MIT` `Go`
- [Photoshow](http://www.photoshow-gallery.com/) - Responsive Web Gallery. ([Source Code](https://github.com/thibaud-rohmer/PhotoShow)) `GPL-3.0` `PHP`
- [Piwigo](http://piwigo.org/) - Photo gallery software for the web, built by an active community of users and developers. ([Demo](http://piwigo.org/demo/), [Source Code](https://github.com/Piwigo/Piwigo)) `GPL-2.0` `PHP`
- [Plumi](http://blog.plumi.org/) - Create your own sophisticated video-sharing site. ([Source Code](https://github.com/plumi/plumi.app)) `GPL-2.0` `Python`
- [Quru Image Server](https://quruimageserver.com/) - High performance dynamically resizing image server offering directory based access control cropping, rotation, color management and other tools. ([Demo](https://quruimageserver.com), [Source Code](https://github.com/quru/qis)) `AGPL-3.0` `Python`
- [sigal](https://github.com/saimn/sigal) - Yet another simple static gallery generator. `MIT` `Python` :star:563
- [UberGallery](http://www.ubergallery.net) - UberGallery is an easy to use, simple to manage, web photo gallery. UberGallery does not require a database and supports JPEG, GIF and PNG file types. Simply upload your images and UberGallery will automatically generate thumbnails and output HTML. ([Source Code](https://github.com/UberGallery/UberGallery)) `MIT` `PHP`
- [Videobin](http://videobin.org/code) - Simple video upload and sharing service with transcoding. ([Demo](http://videobin.org/), [Source Code](https://r-w-x.org/videobin.git)) `GPL-3.0` `Python`
- [Zenphoto](http://www.zenphoto.org/) - Open-source gallery and CMS project. ([Source Code](https://github.com/zenphoto/zenphoto)) `GPL-2.0` `PHP`

## Polls and Events

**[`^        back to top        ^`](#)**

- [Calagator](http://calagator.org/) - Event aggregator. ([Source Code](https://github.com/calagator/calagator)) `MIT` `Ruby`
- [Clerk](https://github.com/chr15m/Clerk) - Simple event logger to keep track of periodic events, habits, etc. as they occur. `GPL-3.0` `PHP` :star:17
- [dudle](http://primelife.ercim.eu/results/opensource/63-dudle) - Online scheduling application. ([Demo](https://dudle.inf.tu-dresden.de/), [Source Code](https://github.com/kellerben/dudle)) `AGPL-3.0` `Ruby`
- [Fider](http://getfider.com) - Open source alternative to UserVoice for customer feedback. ([Demo](https://demo.fider.io), [Source Code](https://github.com/getfider/fider)) `MIT` `Go`
- [Framadate](https://framadate.org/) - Online service for planning an appointment or make a decision quickly and easily: Make a poll, Define dates or subjects to choose, Send the poll link to your friends or colleagues, Discuss and make a decision. ([Demo](https://framadate.org/aqg259dth55iuhwm), [Source Code](https://git.framasoft.org/framasoft/framadate)) `CECILL-B` `PHP`
- [Kyélà](http://kyela.net/) - Participation polls for group events. ([Demo](https://kyela.net/concert/), [Source Code](https://github.com/abienvenu/Kyela)) `AGPL-3.0` `PHP`
- [LimeSurvey](https://www.limesurvey.org) - Feature-rich Open Source web based polling software. Supports extensive survey logic. ([Demo](https://demo.limesurvey.org), [Source code](https://github.com/LimeSurvey/LimeSurvey)) `GPL-2.0` `PHP`
- [Nuages](https://nuages.domainepublic.net/) - Collaborative meeting poll system, similar to doodle or rdvz. ([Source Code](http://git.domainepublic.net/?p=nuages.git;a=tree)) `GPL-3.0` `Python`
- [PHPBack](http://www.phpback.org) - The open source feedback system. ([Demo](http://www.phpback.org/demo/), [Source Code](https://github.com/ivandiazwm/phpback)) `GPL-3.0` `PHP`

### Booking and Scheduling

- [Alf.io](https://alf.io/) - The open source ticket reservation system. ([Demo](https://demo.alf.io/authentication), [Source Code](https://github.com/alfio-event/alf.io)) `GPL-3.0` `Java`
- [Booked](https://www.bookedscheduler.com/) - A web-based calendar and resource scheduling system that allows administered management of reservations on any number of resources. ([Demo](https://demo.bookedscheduler.com/Web/), [Source Code](https://sourceforge.net/projects/phpscheduleit/)) `GPL-3.0` `PHP`
- [Easy!Appointments](http://easyappointments.org/) - A highly customizable web application that allows your customers to book appointments with you via the web. ([Demo](http://easyappointments.org/demo/), [Source Code](https://github.com/alextselegidis/easyappointments)) `GPL-3.0` `PHP`

## Proxy

**[`^        back to top        ^`](#)**

- [http2-serverpush-proxy](https://github.com/n1try/http2-serverpush-proxy) - Reverse proxy that helps to automatically utilize HTTP/2.0's server push mechanism for static websites. Available as middleware and standalone application. `MIT` `Nodejs` :star:21
- [imgproxy](https://github.com/DarthSim/imgproxy) - Fast and secure standalone server for resizing and converting remote images. It works great when you need to resize multiple images on the fly without preparing a ton of cached resized images or re-doing it every time the design changes. `MIT` `Go/Docker` :star:2470
- [iodine](http://code.kryo.se/iodine/) - IPv4 over DNS tunnel solution, enabling you to start up a socks5 proxy listener. ([Source Code](https://github.com/yarrick/iodine)) `ISC` `C`
- [microproxy](https://github.com/thekvs/microproxy) - lightweight non-caching HTTP/HTTPS proxy server. `MIT` `Go` :star:82
- [miniProxy](https://joshdick.github.io/miniProxy/) - Simple web proxy written in PHP that can allow you to bypass Internet content filters, or to browse the internet anonymously. Only one php file. ([Source Code](https://github.com/joshdick/miniProxy)) `GPL-3.0` `PHP`
- [Oranjeproxy](http://lehollandaisvolant.net/tout/oranjeproxy/) - Anonymizing web proxy. ([Source Code](https://github.com/AmauryCarrade/OranjeProxy)) `GPL-2.0` `PHP`
- [PHP-Proxy](https://www.php-proxy.com/) - Web proxy script built specifically to be fast, easy to modify and to support video sites such as YouTube. ([Demo](https://unblockvideos.com/), [Source Code](https://github.com/Athlon1600/php-proxy-app)) `MIT` `PHP`
- [Pomerium](https://pomerium.io) - An identity-aware reverse proxy, successor to now obsolete oauth_proxy. It inserts an OAuth step before proxying your request to the backend, so that you can safely expose your self-hosted websites to public Internet. ([Source Code](https://github.com/pomerium/pomerium)) `Apache-2.0` `Go`
- [Pound](http://www.apsis.ch/pound/) - Light-weight reverse proxy and load balancer for HTTP/HTTPS. `GPL-2.0` `C`
- [Privoxy](http://www.privoxy.org) - Non-caching web proxy with advanced filtering capabilities for enhancing privacy, modifying web page data and HTTP headers, controlling access, and removing ads and other obnoxious Internet junk. `GPL-2.0` `C`
- [Redbird](https://github.com/OptimalBits/redbird) - A modern reverse proxy for node that includes cluster, HTTP2, LetsEncrypt, and Docker support. `BSD-2-Clause` `Javascript` :star:3909
- [socks5-proxy-server](https://github.com/nskondratev/socks5-proxy-server) - SOCKS5 proxy server with built-in authentication and Telegram-bot for user management and user statistics on data spent (handy when you pay per GB of data). It is dockerised and simple to install. `Apache-2.0` `NodeJS` :star:4
- [SOCKS5Engine](https://github.com/VeeSecurity/SOCKS5Engine) - Lightweight & resource-efficient SOCKS5 proxy server, optimized for high-load. `AGPL-3.0` `Go` :star:9
- [Squid](http://www.squid-cache.org/) - Caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages. ([Source Code](https://code.launchpad.net/squid)) `GPL-2.0` `C`
- [Swiperproxy](https://swiperproxy.github.io/) - Lightning-fast, open source web proxy that is easy for you to run and customize. ([Source Code](https://github.com/swiperproxy/swiperproxy)) `MIT` `Python`
- [Tinyproxy](https://tinyproxy.github.io/) - Light-weight HTTP/HTTPS proxy daemon. ([Source Code](https://github.com/tinyproxy/tinyproxy)) `GPL-2.0` `C`
- [Traefik](https://traefik.io/) - Træfɪk is a modern HTTP reverse proxy and load balancer made to deploy microservices with ease. It supports several backends (Docker, Swarm, Mesos/Marathon, …) to manage its configuration automatically and dynamically. ([Source Code](https://github.com/containous/traefik)) `MIT` `Go`

## Read it Later Lists

**[`^        back to top        ^`](#)**

- [Nunux Keeper](http://keeper.nunux.org/) - Your personal content curation service. ([Source Code](https://github.com/ncarlier/nunux-keeper)) `GPL-3.0` `Nodejs`
- [Wallabag](https://www.wallabag.org) - Wallabag, formerly Poche, is a web application allowing you to save articles to read them later with improved readability. ([Demo](http://demo.wallabag.org/), [Source Code](https://github.com/wallabag/wallabag)) `MIT` `PHP`

## Resource Planning

**[`^        back to top        ^`](#)**

- [farmOS](http://farmos.org/) - Web-based farm record keeping application. ([Source Code](https://github.com/farmOS/farmOS)) `GPL-2.0` `PHP`
- [Grocy](https://grocy.info/) - grocy is a web-based selfhosted groceries management solution for your home, available in English, German, Italian and Norwegian. ([Demo](https://demo-en.grocy.info/stockoverview), [Source Code](https://github.com/berrnd/grocy)) `MIT` `PHP`
- [Tania](https://github.com/Tanibox/tania-core) - Tania is a free and open source farming management system for everyone. You can manage your areas, reservoirs, farm tasks, inventories, and the crop growing progress. `Apache-2.0` `Go` :star:214

### Enterprise Resource Planning

- [ERPNext](https://erpnext.com) - Free open source ERP system. ([Demo](https://demo.erpnext.com), [Source Code](https://github.com/frappe/erpnext)) `GPL-3.0` `Python`
- [LedgerSMB](https://ledgersmb.org/) - Integrated accounting and ERP system for small and midsize businesses, with double entry accounting, budgeting, invoicing, quotations, projects, orders and inventory management, shipping and more. ([Demo](https://demo.cloud.efficito.com/erp/1.5/login.pl), [Source Code](https://github.com/ledgersmb/LedgerSMB)) `GPL-2.0` `Perl`
- [Odoo](http://odoo.com) - Free open source ERP system. ([Demo](https://demo.odoo.com/), [Source Code](https://github.com/odoo/odoo)) `LGPL-3.0` `Python`
- [Tryton](http://www.tryton.org/) - Free open source business solution. ([Demo](http://www.tryton.org/download.html), [Source Code](https://hg.tryton.org/)) `GPL-3.0` `Python`

## Search Engines

**[`^        back to top        ^`](#)**

- [Ambar](https://ambar.cloud) - Document Search Engine (OCR, Store & Search). ([Demo](https://app.ambar.cloud/), [Source Code](https://github.com/RD17/ambar)) `MIT` `Nodejs/Python`
- [Gigablast](http://www.gigablast.com/) - open source search engine. ([Source Code](https://github.com/gigablast/open-source-search-engine)) `Apache-2.0` `C++`
- [Searx](https://asciimoo.github.io/searx/) - Privacy-respecting, hackable metasearch engine. ([Demo](https://searx.me/), [Source Code](https://github.com/asciimoo/searx)) `AGPL-3.0` `Python`
- [Yacy](http://yacy.net/en/index.html) - Peer based, decentralized search engine server. ([Demo](http://search.yacy.net/), [Source Code](https://github.com/yacy/yacy_search_server)) `GPL-2.0` `Java`

## Software Development

**[`^        back to top        ^`](#)**

### Project Management

_See also [Ticketing](#ticketing), [Task management/To-do lists](#task-managementto-do-lists), [awesome-sysadmin/Code Review](https://github.com/n1trux/awesome-sysadmin#code-review)_

- [Bonobo Git Server](https://bonobogitserver.com/) - Set up your own self hosted git server on IIS for Windows. Manage users and have full control over your repositories with a nice user friendly graphical interface. ([Source Code](https://github.com/jakubgarfield/Bonobo-Git-Server)) `MIT` `C#`
- [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - Distributed version control system featuring wiki and bug tracker. `BSD-2-Clause-FreeBSD` `C`
- [Goodwork](https://github.com/iluminar/goodwork) - Self hosted project management and collaboration tool powered by Laravel & VueJS. ([Demo](https://goodworkfor.life/)) `MIT` `PHP` :star:623
- [Gitblit](http://gitblit.com/) - Pure Java stack for managing, viewing, and serving Git repositories. ([Source Code](https://github.com/gitblit/gitblit)) `Apache-2.0` `Java`
- [gitbucket](https://gitbucket.github.io/gitbucket-news/) - The easily installable GitHub clone powered by Scala. ([Source Code](https://github.com/gitbucket/gitbucket)) `Apache-2.0` `Scala/Java`
- [Gitea](https://gitea.io) - Community managed fork of Gogs, lightweight code hosting solution. ([Demo](https://try.gitea.io), [Source Code](https://github.com/go-gitea/gitea)) `MIT` `Go`
- [GitLab](http://gitlab.org/) - Self Hosted Git repository management, code reviews, issue tracking, activity feeds and wikis. ([Demo](https://gitlab.com/), [Source Code](https://gitlab.com/gitlab-org/gitlab-ce)) `MIT` `Ruby`
- [Gitlist](http://gitlist.org/) - Web-based git repository browser - GitList allows you to browse repositories using your favorite browser, viewing files under different revisions, commit history and diffs. ([Source Code](https://github.com/klaussilveira/gitlist)) `BSD-3-Clause` `PHP`
- [Gitolite](http://gitolite.com/gitolite/index.html) - Gitolite allows you to setup git hosting on a central server, with fine-grained access control and many more powerful features. ([Source Code](https://github.com/sitaramc/gitolite)) `GPL-2.0` `Perl`
- [GitPrep](http://gitprep.yukikimoto.com/) - Portable Github clone. ([Demo](http://perlcodesample.sakura.ne.jp/gitprep/gitprep.cgi), [Source Code](https://github.com/yuki-kimoto/gitprep)) `Artistic-2.0` `Perl`
- [Git WebUI](https://github.com/alberthier/git-webui) - Standalone web based user interface for git repositories. `Apache-2.0` `Python` :star:679
- [Gogs](https://gogs.io/) - Painless self-hosted Git Service written in Go. ([Demo](https://try.gogs.io/), [Source Code](https://github.com/gogits/gogs)) `MIT` `Go`
- [Kallithea](https://kallithea-scm.org/) - Source code management system that supports two leading version control systems, Mercurial and Git, with a web interface. ([Source Code](https://kallithea-scm.org/repos/kallithea)) `GPL-3.0` `Python`
- [Klaus](https://github.com/jonashaag/klaus) - Simple, easy-to-set-up Git web viewer that Just Works. `ISC` `Python` :star:532
- [Lavagna](http://lavagna.io) - Lavagna is an open-source issue/project management tool designed for small teams. Lightweight, pure Java, easy to install, easy to use. ([Source Code](https://github.com/digitalfondue/lavagna)) `GPL-3.0` `Java`
- [Octobox](https://octobox.io/) `⚠` - Take back control of your GitHub Notifications. ([Source Code](https://github.com/octobox/octobox)) `AGPL-3.0` `Ruby`
- [OpenProject](https://www.openproject.org) - OpenProject is a web-based project management system. ([Source Code](https://github.com/opf/openproject)) `GPL-3.0` `Ruby`
- [Phabricator](http://phabricator.org/) - Collection of web applications that help build better software. ([Demo](https://secure.phabricator.com/), [Source Code](https://github.com/phacility/phabricator)) `Apache-2.0` `PHP`
- [Phproject](http://www.phproject.org/) - High performance full-featured project management system. ([Demo](http://demo.phproject.org/), [Source Code](https://github.com/Alanaktion/phproject)) `GPL-3.0` `PHP`
- [ProjeQtOr](https://www.projeqtor.org/) - A complete, mature, multi-user project management system with extensive functionality for all phases of a project. ([Demo](https://demo.projeqtor.org/), [Source Code](https://sourceforge.net/p/projectorria/code/HEAD/tree/branches/)) `AGPL-3.0` `PHP`
- [Redmine](http://www.redmine.org/) - Redmine is a flexible project management web application. ([Demo](http://demo.redmine.org/), [Source Code](https://svn.redmine.org/redmine/)) `GPL-2.0` `Ruby`
- [RhodeCode](https://rhodecode.com/) - RhodeCode is an open source platform for software development teams. It unifies and simplifies repository management for Git, Subversion, and Mercurial. ([Demo](https://try.rhodecode.com/), [Source Code](https://code.rhodecode.com/)) `AGPL-3.0` `Python`
- [SCM Manager](https://www.scm-manager.org/) - The easiest way to share and manage your Git, Mercurial and Subversion repositories over http. ([Source Code](https://bitbucket.org/sdorra/scm-manager/src)) `BSD-3-Clause` `Java`
- [Taiga](https://taiga.io/) - Agile Project Management Tool based on the Kanban and Scrum methods. ([Source Code](https://github.com/taigaio)) `AGPL-3.0` `Python`
- [Trac](http://trac.edgewall.org/) - Trac is an enhanced wiki and issue tracking system for software development projects. `BSD-3-Clause` `Python`
- [Tuleap](https://www.tuleap.org/) - Tuleap is a libre suite to plan, track, code and collaborate on software projects. ([Source Code](https://tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)) `GPL-2.0` `PHP`

### Bug Trackers

See **[Ticketing](#ticketing)**

### IDE/Tools

- [Babelfish](https://doc.bblf.sh) - Self-hosted server for source code parsing. It can parse any file, in any supported language, extract an Abstract Syntax Tree from it, and convert it to a Universal Abstract Syntax Tree which can enable further analysis and transformation. ([Source Code](https://github.com/bblfsh/bblfshd)) `GPL-3.0` `Go`
- [Code-Server](https://coder.com/) - Visual Studio Code in the browser, hosted on a remote server. ([Source Code](https://github.com/cdr/code-server)) `MIT` `Nodejs/Docker`
- [Eclipse Che](http://www.eclipse.org/che/) - Open source workspace server and cloud IDE. ([Source Code](https://github.com/eclipse/che)) `EPL-1.0` `Docker/Java`
- [ICEcoder](https://icecoder.net/) - ICEcoder is a web IDE / browser based code editor, which allows you to develop websites directly within the web browser. ([Demo](http://demo.icecoder.net/ICEcoder/), [Source Code](https://github.com/icecoder/ICEcoder)) `MIT` `PHP`
- [JS Bin](http://jsbin.com/) - Open source collaborative web development debugging tool. ([Source Code](https://github.com/jsbin/jsbin)) `MIT` `Nodejs`
- [Judge0 API](https://api.judge0.com) - Open source API to compile and run source code. ([Source Code](https://github.com/judge0/api)) `GPL-3.0` `Ruby`
- [Koding](http://www.koding.com/) - The simplest way to manage your entire Dev Infrastructure. ([Source Code](https://github.com/koding/koding)) `Apache-2.0` `Nodejs`
- [Microglark](http://micro.glark.io) - Hacky minimalistic remote pair programming editor. ([Source Code](https://github.com/Bluefinch/microglark)) `AGPL-3.0` `Nodejs`
- [Regexr](http://regexr.com/) - RegExr is a HTML/JS based tool for creating, testing, and learning about Regular Expressions. ([Source Code](https://github.com/gskinner/regexr)) `MIT` `Nodejs`
- [RequestBin](https://github.com/Runscope/requestbin) - Inspect HTTP requests. Debug webhooks. `MIT` `python` :star:1761
- [RStudio Server](https://www.rstudio.com/products/rstudio/#Server) - Web browser based IDE for R. ([Source Code](https://github.com/rstudio/rstudio)) `AGPL-3.0` `Java/C++`
- [sourcegraph](https://sourcegraph.com) - Sourcegraph is a fast, open-source, fully-featured code search and navigation engine written in Go. ([Source Code](https://github.com/sourcegraph/sourcegraph)) `Apache-2.0` `Go`
- [Wide](https://github.com/b3log/wide) - Web-based IDE for Teams using Go programming language/Golang. ([Demo](http://wide.b3log.org/signup)) `Apache-2.0` `Go` :star:3576

### Continuous Integration

_See [awesome-sysadmin/Continuous Integration & Continuous Deployment](https://github.com/n1trux/awesome-sysadmin#continuous-integration--continuous-deployment)_

### UX testing

- [Uier](https://github.com/sjoerdvanderhoorn/Uier) - Codeless or low-code User Experience test editing and management using Selenium to perform testing or UI automation. Uier tends to be a free self hostable alternative to Applitools, Endtest, Ghost Inspector, Usetrace, Screenster and many others. `Apache-2.0` `Nodejs` :star:10
- [Selenoid](http://aerokube.com/selenoid/latest/) - Lightweight Selenium hub implementation launching browsers within Docker containers. ([Source Code](https://github.com/aerokube/selenoid)) `Apache-2.0` `Go`
- [Zalenium](https://github.com/zalando/zalenium) - Allows anyone to have a disposable and flexible Docker-based Selenium Grid infrastructure featuring video recording, live preview and online/offline dashboards. `Apache-2.0` `Java/Shell` :star:1870

### FaaS/Serverless

*[Serverless computing on Wikipedia](https://en.wikipedia.org/wiki/Serverless_computing)*

- [fx](https://github.com/metrue/fx) - fx is a tool to help you do Function as a Service with painless on your own servers. `MIT` `Go` :star:1265
- [IronFunctions](https://github.com/iron-io/functions) - The serverless microservices platform by [iron.io](https://www.iron.io/). `Apache-2.0` `Go` :star:2634
- [LocalStack](https://localstack.cloud/) - LocalStack is a fully functional local AWS cloud stack. This includes Lambda for serverless computation. ([Source Code](https://github.com/localstack/localstack)) `Apache-2.0` `Python/Other`
- [OpenFaaS](https://www.openfaas.com/) - Serverless Functions Made Simple for Docker & Kubernetes. ([Source Code](https://github.com/openfaas/faas)) `MIT` `Go`

### API Management

- [DreamFactory](https://www.dreamfactory.com/) - Turns any SQL/NoSQL/Structured data into Restful API. ([Source Code](https://github.com/dreamfactorysoftware/dreamfactory)) `Apache-2.0` `PHP`
- [Endpoint](https://github.com/LINKIWI/endpoint) - Super simple mock HTTP API endpoints that return static JSON data, for testing webhooks and client libraries in development. `MIT` `Nodejs` :star:101
- [Fusio](http://www.fusio-project.org/) - Open-source API management platform which helps to build and manage REST APIs. ([Demo](http://fusio-project.org/demo), [Source Code](https://github.com/apioo/fusio)) `AGPL-3.0` `PHP`
- [Hapttic](https://github.com/jsoendermann/hapttic) - Simple HTTP server that forwards all requests to a shell script to handle webhooks you receive. `Apache-2.0` `Go` :star:82
- [Kong](https://konghq.com/kong/) - The World’s Most Popular Open Source Microservice API Gateway and Platform. ([Source Code](https://github.com/Kong/kong)) `Apache-2.0` `Lua`
- [Para](http://www.paraio.org) - Flexible and modular backend framework/server for object persistence, API development and authentication. ([Source Code](https://github.com/erudika/para)) `Apache-2.0` `Java`
- [Tyk](https://tyk.io) - Fast and scalable open source API Gateway. Out of the box, Tyk offers an API Management Platform with an API Gateway, API Analytics, Developer Portal and API Management Dashboard. ([Source Code](https://github.com/TykTechnologies/tyk)) `MPL-2.0` `Go`

### Documentation Generators

See also [Static site generators](#static-site-generators)

- [Docstore](http://haldean.org/) - Static document hosting without any server-side processing, does not require you to recompile every time you change an article. Clone the repository and add articles in the text/ directory to get started. ([Source Code](https://github.com/haldean/docstore)) `BSD-3-Clause` `Javascript`
- [Flatdoc](http://ricostacruz.com/flatdoc/) - Small Javascript file that fetches Markdown files and renders them as full pages. `MIT` `Javascript`
- [markdown-tree](https://github.com/mil/markdown-tree) - Serve a hierarchy / tree directory of markdown files. Use intended for small sites built in markdown. `MIT` `Ruby` :star:86
- [Read the Docs](https://docs.readthedocs.org/en/latest/install.html) - Host documentation, making it fully searchable and easy to find; import your docs using any major version control system, including Mercurial, Git, Subversion, and Bazaar. ([Demo](https://readthedocs.org/projects/), [Source Code](https://github.com/rtfd/readthedocs.org)) `MIT` `Python`

### Localization

- [Accent](https://www.accent.reviews/) - Open-source, self-hosted, developer-oriented translation tool. ([Source Code](https://github.com/mirego/accent)) `BSD-3-Clause` `Elixir`
- [Pootle](http://pootle.translatehouse.org) - Online translation and localization tool. ([Source Code](https://github.com/translate/pootle)) `GPL-3.0` `Python`
- [Weblate](https://weblate.org) - Web-based translation tool with tight version control integration. ([Demo](https://demo.weblate.org), [Source Code](https://github.com/WeblateOrg/weblate)) `GPL-3.0` `Python`
- [Zanata](http://zanata.org) - Web-based translation platform for translators, content creators and developers to manage localisation projects. ([Source Code](https://github.com/zanata/zanata-platform)) `GPL-2.0` `Java`

## Static site generators

**[`^        back to top        ^`](#)**

See https://staticsitegenerators.net and https://www.staticgen.com

## Task management/To-do lists

**[`^        back to top        ^`](#)**

*See also [Project Management](#project-management) and [Ticketing](#ticketing).*

- [Crepido](https://github.com/arshad/crepido) - Create (kanban) boards to track users and projects from flat markdown files. `MIT` `Nodejs` :star:152
- [Kanboard](http://kanboard.net/) - Simple and open source visual task board. ([Source Code](https://github.com/kanboard/kanboard)) `MIT` `PHP`
- [myTinyTodo](http://www.mytinytodo.net/) - Simple way to manage your todo list in AJAX style. Uses PHP, jQuery, SQLite/MySQL. GTD compliant. ([Demo](http://www.mytinytodo.net/demo/), [Source Code](https://bitbucket.org/maxpozdeev/mytinytodo)) `GPL-2.0` `PHP`
- [PHP Task/Todo list](https://github.com/lgg/tasks.php) - Simple task/todo list that uses a JSON text file for the tasks. `MIT` `PHP` :star:10
- [Restyaboard](http://restya.com/board/) - Open source Trello-like kanban board. ([Demo](http://restya.com/board/demo.html), [Source Code](https://github.com/RestyaPlatform/board)) `OSL-3.0` `PHP`
- [scrumblr](http://scrumblr.ca/) - Collaborative Online Scrum Tool Using Websockets, Node.js, jQuery, and CSS3. ([Demo](http://scrumblr.ca/demo), [Source Code](https://github.com/ocdtrekkie/scrumblr/tree/sandstorm)) `GPL-3.0` `Nodejs`
- [TaskBoard](http://taskboard.matthewross.me/) - Kanban-inspired app for keeping track of things that need to get done. ([Demo](https://taskboard.matthewross.me/demo.html), [Source Code](https://github.com/kiswa/TaskBoard)) `MIT` `PHP`
- [Taskfreak](http://www.taskfreak.com/original) - Simple but efficient web based task manager written in PHP. `GPL-3.0` `PHP`
- [Tasks](https://github.com/m1guelpf/tasks) - Simple tasks and notes manager written in PHP, jQuery and Bootstrap using a custom flat file database. `MPL-2.0` `PHP` :star:77
- [Tasks](https://github.com/thewhitetulip/Tasks) - Kanban based to-do list manager written in Go. `MIT` `Go` :star:434
- [tasks.php](https://github.com/RaymiiOrg/tasks.php) - Simple task/todo list manager. `MIT` `PHP` :star:42
- [Taskwarrior](https://taskwarrior.org/) - Taskwarrior is Free and Open Source Software that manages your TODO list from your command line. It is flexible, fast, efficient, and unobtrusive. It does its job then gets out of your way. ([Source Code](https://taskwarrior.org/download/#git)) `MIT` `C++`
- [Tinyissue](https://github.com/satrun77/tinyissue) - Simple Issue Tracking for Teams. `MIT` `PHP` :star:48
- [todo](https://github.com/prologic/todo) - Simple todo list manager. ([Demo](https://todo.mills.io)) `MIT` `Go` :star:25
- [todoMini](https://www.todomini.app/) - Mobile friendly zero-feature TODO list web app. Unix philosophy. ([Demo](https://appmini.github.io/todoMini/?demo), [Source Code](https://github.com/appMini/todoMini)) `GPL-3.0` `PHP/Clojure`
- [Tracks](http://www.getontracks.org/) - Web-based application to help you implement David Allen’s [Getting Things Done™](https://en.wikipedia.org/wiki/Getting_Things_Done) methodology. ([Source Code](https://github.com/TracksApp/tracks)) `GPL-2.0` `Ruby`
- [Volition](https://github.com/usevolition/volition) - Opinionated open-source task management. `MIT` `Ruby` :star:80
- [Wekan](https://wekan.github.io/) - Open-source Trello-like kanban. ([Demo](https://oasis.sandstorm.io/appdemo/m86q05rdvj14yvn78ghaxynqz7u2svw6rnttptxx49g1785cdv1h), [Source Code](https://github.com/wekan/wekan)) `MIT` `Nodejs`

## Ticketing

**[`^        back to top        ^`](#)**

*See also [Task management/To-do lists](#task-managementto-do-lists) and [Project Management](#project-management)*

- [Bugzilla](https://www.bugzilla.org/) - General-purpose bugtracker and testing tool originally developed and used by the Mozilla project. `MPL-2.0` `Perl`
- [Bumpy Booby](http://bumpy-booby.derivoile.fr/) - Simple, responsive and highly customizable PHP bug tracking system. ([Source Code](https://github.com/piero-la-lune/Bumpy-Booby)) `MIT` `PHP`
- [Cerb](http://www.cerberusweb.com/) - Group-based e-mail management project. ([Source Code](https://github.com/wgm/cerb)) `DPL` `PHP`
- [Deskulu](https://github.com/Taskulu/deskulu) - Opensource helpdesk and ticketing system based on Drupal 7. ([Demo](https://help.taskulu.com)) `GPL-2.0` `PHP` :star:478
- [DiamanteDesk](http://diamantedesk.com/) - DiamanteDesk is FREE Open Source easy-to-use help-desk solution. ([Demo](http://diamantedesk.com/demo/), [Source Code](https://github.com/eltrino/diamantedesk-application)) `OSL-3.0` `PHP`
- [django-todo](http://django-todo.org/) - django-todo is a pluggable, multi-user, multi-group, multi-list todo and ticketing system - a reusable app designed to be dropped into any existing Django project. ([Source Code](https://github.com/shacker/django-todo)) `BSD-3-Clause` `Python/Django`
- [Flyspray](http://www.flyspray.org/) - Uncomplicated, web-based bug tracking system. ([Source Code](https://github.com/Flyspray/flyspray)) `GPL-2.0` `PHP`
- [FreeScout](https://github.com/freescout-helpdesk/freescout) - Open source clone of Help Scout: email-based customer support application, help desk and shared mailbox. `AGPL-3.0` `PHP` :star:479
- [Helpy](https://helpy.io) - Helpy is a modern, open source helpdesk customer support application. Features include knowledgebase, community discussions and support tickets integrated with email. ([Demo](https://demo.helpy.io), [Source Code](https://github.com/helpyio/helpy)) `MIT` `Ruby`
- [HuBoard](https://github.com/huboard/huboard) `⚠` - Instant project management for your GitHub issues (Connects directly GitHub API). `MIT` `Ruby`
- [MantisBT](https://www.mantisbt.org/) - Self hosted bug tracker, fits best for software development. ([Demo](https://www.mantisbt.org/bugs/my_view_page.php)), ([Source Code](https://github.com/mantisbt/mantisbt)) `GPL-2.0` `PHP`
- [OpenSupports](https://www.opensupports.com/) - Multi language ticket system with FAQ, role management, metrics and canned response features. ([Demo](https://www.opensupports.com/demo/), [Source Code](https://github.com/opensupports/opensupports)) `GPL-3.0` `PHP`
- [osTicket](http://osticket.com/) - Manage, organize and archive all your support requests and responses in one place. ([Source Code](https://github.com/osTicket/osTicket)) `GPL-2.0` `PHP`
- [OTRS](http://www.otrs.com/) - Trouble ticket system for assigning tickets to incoming queries and tracking further communications. ([Source Code](https://github.com/OTRS/otrs)) `AGPL-3.0` `Perl`
- [Request Tracker](https://www.bestpractical.com/rt/) - An enterprise-grade issue tracking system. ([Source Code](https://github.com/bestpractical/rt)) `GPL-2.0` `Perl`
- [Sentry On-Premise](https://github.com/getsentry/onpremise) - A powerful error tracking platform with wide language support and a robust API. ([Source Code](https://github.com/getsentry/sentry)) `BSD-3-Clause` `Python/Django` :star:1804
- [SIT](https://sit.fyi/) - SCM-agnostic, file-based, offline-first, immutable issue tracker. ([Source Code](https://github.com/sit-fyi/sit)) `MIT` `Apache-2.0` `Rust`.
- [TheBugGenie](http://www.thebuggenie.org) - friendly project management and issue tracking tool, with extensive user rights system. ([Source Code](https://github.com/thebuggenie/thebuggenie)) `MPL-2.0` `PHP`
- [Zammad](https://zammad.org/) - Easy to use but powerful open-source support and ticketing system. ([Source Code](https://github.com/zammad/zammad)) `AGPL-3.0` `Ruby`

## URL Shorteners

**[`^        back to top        ^`](#)**

- [devShort](https://github.com/flokX/devShort) - A simple and privacy-friendly URL shortener for web developers, admins and all professionals. ([Demo](https://devshort.florian-kaldowski.de)) `MIT` `PHP` :star:15
- [Kutt](https://kutt.it) - A modern URL shortener with support for custom domains. ([Source Code](https://github.com/thedevs-network/kutt)) `MIT` `Nodejs`
- [Link-shortener-bot](https://github.com/tommyku/link-shortener-front-end) `⚠` - URL shortener using a Telegram Bot. ([Demo](http://t.me/GiveMeShortLinkBot)) `MIT` `Ruby`
- [Linkr](https://github.com/LINKIWI/linkr) - Beautiful, fast URL shortening. `MIT` `Python/Nodejs` :star:98
- [liteshort](https://github.com/132ikl/liteshort) - User-friendly, actually lightweight, and configurable URL shortener. ([Demo](https://ls.ikl.sh)) `MIT` `Python` :star:15
- [Lstu](https://github.com/ldidry/lstu) - _Let's SHorten That Url_ - Lightweight URL shortener. `WTFPL` `Perl` :star:113
- [Nimbus](https://github.com/ethanal/nimbus) - URL shortener and file sharer with a drag-and-drop OS X menu bar client and web interface. `MIT` `Python` :star:199
- [Polr](https://project.polr.me/) - Modern, minimalist, modular, and lightweight URL shortener. ([Source Code](https://github.com/Cydrobolt/polr)) `GPL-2.0` `PHP`
- [reduc.io](https://github.com/ziyasal/reducio) - URL shortener service written in Scala, using Akka-Http and Redis. `MIT` `Scala` :star:43
- [schort](https://github.com/sqozz/schort) - No login, no javascript, just short links. ([Demo](https://s.wx0.de)) `CC0-1.0` `Python` :star:20
- [shorturl](https://github.com/prologic/shorturl) - Simple URL shortener with very tiny URLs. ([Demo](https://url.mills.io)) `MIT` `Go` :star:47
- [shuri](https://github.com/pips-/shuri) - SHort URI - Lightweight URL shortener. `MIT` `PHP` :star:12
- [Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener) - KISS URL shortener, public or private (with account). Minimalist and lightweight. No dependencies. ([Demo](https://u.azlux.fr)) `MIT` `PHP` :star:11
- [url-shortener](https://github.com/cagataycali/url-shortener) `⚠` - Shitty url shortener, emoji and AI powered. `MIT` `Nodejs`
- [URL-Shortener](https://github.com/sapioit/URL-shortener) - Make your long links short and only uses lowercase, so you can write and spell them faster. ([Demo](http://scurtez.cf)) `GPL-3.0` `PHP` :star:2
- [YOURLS](http://yourls.org/) - YOURLS is a set of PHP scripts that will allow you to run Your Own URL Shortener. Features include password protection, URL customization, bookmarklets, statistics, API, plugins, jsonp. ([Source Code](https://github.com/YOURLS/YOURLS)) `MIT` `PHP`

## VPN

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#vpn

## Web servers

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#web

## Wikis

**[`^        back to top        ^`](#)**

See also [Documentation Generators](#documentation-generators), [Wikimatrix](http://www.wikimatrix.org/), [Wiki Engines on WikiIndex](http://wikiindex.org/Category:Wiki_Engine), [List of wiki software on wikipedia](https://en.wikipedia.org/wiki/List_of_wiki_software), [Comparison of wiki software on wikipedia](https://en.wikipedia.org/wiki/Comparison_of_wiki_software).

- [BookStack](https://www.bookstackapp.com/) - BookStack is a simple, self-hosted, easy-to-use platform for organizing and storing information. It allows for documentation to be stored in a book like fashion. ([Demo](https://www.bookstackapp.com/#demo), [Source Code](https://github.com/ssddanbrown/BookStack)) `MIT` `PHP`
- [Cowyo](https://github.com/schollz/cowyo) - Cowyo is a feature-rich wiki for minimalists. ([Demo](https://cowyo.com)) `MIT` `Go` :star:568
- [django-wiki](https://github.com/django-wiki/django-wiki) - Wiki system with complex functionality for simple integration and a superb interface. Store your knowledge with style: Use django models. ([Demo](https://demo.django-wiki.org/)) `GPL-3.0` `Python` :star:1162
- [Documize](https://documize.com) - Modern Docs + Wiki software with built-in workflow, single binary executable, just bring MySQL/Percona. ([Source Code](https://github.com/documize/community)) `AGPL-3.0` `Go`
- [Dokuwiki](https://www.dokuwiki.org/DokuWiki) - Easy to use, lightweight, standards-compliant wiki engine with a simple syntax allowing reading the data outside the wiki. All data is stored in plain files, therefore no database is required. ([Source Code](https://github.com/splitbrain/dokuwiki)) `GPL-2.0` `PHP`
- [Gitit](https://github.com/jgm/gitit) - Wiki program that stores pages and uploaded files in a git repository, which can then be modified using the VCS command line tools or the wiki's web interface. `GPL-2.0` `Haskell` :star:1686
- [Gollum](https://github.com/gollum/gollum) - Simple, Git-powered wiki with a sweet API and local frontend. `MIT` `Ruby` :star:10127
- [jingo](https://github.com/claudioc/jingo) - Git based wiki engine written for node.js, with a decent design, a search capability and good typography. ([Demo](http://jingo.cica.li:6067/wiki/home)) `MIT` `Nodejs` :star:917
- [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki) - MediaWiki is a free and open-source wiki software package written in PHP. It serves as the platform for Wikipedia and the other Wikimedia projects, used by hundreds of millions of people each month. ([Source Code](https://phabricator.wikimedia.org/diffusion/MW/)) `GPL-2.0` `PHP`
- [MoinMoin](https://moinmo.in/) - Advanced, easy to use and extensible WikiEngine with a large community of users. ([Source Code](http://hg.moinmo.in/moin)) `GPL-2.0` `Python`
- [Olelo](https://github.com/minad/olelo) - Olelo is a wiki that stores pages in a Git repository, supports many markup styles and has an extensible, hackable architecture. ([Demo](http://gitwiki.org/)) `MIT` `Ruby` :star:240
- [Outline](https://www.getoutline.com/) `⚠` - An open, extensible, wiki for your team built using React and Node.js. ([Source Code](https://github.com/outline/outline)) `BSD-3-Clause` `Nodejs`
- [Pepperminty Wiki](https://github.com/sbrl/Pepperminty-Wiki) - Complete markdown-powered wiki contained in a single PHP file. ([Demo](https://starbeamrainbowlabs.com/labs/peppermint/build/)) `MPL-2.0` `PHP` :star:43
- [PineDocs](https://github.com/xy2z/PineDocs) - Simple, fast, customizable and lightweight site for browsing files. `GPL-3.0` `PHP` :star:13
- [PmWiki](http://www.pmwiki.org) - Wiki-based system for collaborative creation and maintenance of websites. `GPL-3.0` `PHP`
- [Raneto](http://raneto.com/) - Raneto is an open source Knowledgebase platform that uses static Markdown files to power your Knowledgebase. `MIT` `Nodejs`
- [Realms](http://realms.io/) - Git-backed wiki inspired by Gollum. ([Source Code](https://github.com/scragg0x/realms-wiki)) `GPL-2.0` `Python`
- [TiddlyWiki](http://tiddlywiki.com/) - Reusable non-linear personal web notebook. ([Source Code](https://github.com/Jermolene/TiddlyWiki5)) `BSD-3-Clause` `Nodejs`
- [Tiki](https://tiki.org) - Wiki CMS Groupware with the most built-in features. ([Demo](https://tiki.org/Demo), [Source Code](https://sourceforge.net/p/tikiwiki/code/HEAD/tree/)) `LGPL-2.1` `PHP`
- [TWiki](http://twiki.org/) - TWiki is a Perl-based structured wiki application, typically used to run a collaboration platform, knowledge or document management system, a knowledge base, or team portal. ([Demo](http://twiki.org/cgi-bin/view/Sandbox/WebHome), [Source Code](http://svn.twiki.org/svn/twiki/)) `GPL-1.0` `Perl`
- [wiki](https://github.com/prologic/wiki) - Simple Markdown based wiki engine. ([Demo](https://wiki.mills.io)) `MIT` `Go` :star:41
- [Wiki.js](https://wiki.js.org/) - Modern, lightweight and powerful wiki app built on NodeJS, Git and Markdown. ([Demo](https://docs.requarks.io)) `AGPL-3.0` `Nodejs`
- [WiKiss](http://wikiss.tuxfamily.org/) - Wiki, simple to use and install. ([Source Code](https://svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)) `GPL-2.0` `PHP`
- [XWiki](http://www.xwiki.org) - Second generation wiki that allows the user to extend its functionalities with a powerful extension-based architecture. ([Demo](http://playground.xwiki.org), [Source Code](https://github.com/xwiki/xwiki-platform)) `LGPL-2.1` `Java`

## Self-hosting Solutions

**[`^        back to top        ^`](#)**

- [1Backend](https://github.com/1backend/1backend) - Self-host web apps, microservices and lambdas on your server. Advanced features enable service reuse and composition. `AGPL-3.0` `Go` :star:1812
- [Ansible-NAS](https://github.com/DaveStephens/ansible-nas) - Build a full-featured home server with this playbook and an Ubuntu box. `MIT` `YAML/Docker` :star:423
- [DietPi](http://dietpi.com/) - Minimal Debian OS optimized for single-board computers, which allows you to easily install and manage several services for selfhosting at home. ([Source Code](https://github.com/Fourdee/DietPi)) `GPL-2.0` `Shell`
- [DockSTARTer](https://dockstarter.com/) - DockSTARTer helps you get started with home server apps running in Docker. ([Source Code](https://github.com/GhostWriters/DockSTARTer)) `MIT` `Shell`
- [DPlatform](https://dfabric.github.io/DPlatform-Shell/) - Deploy self-hosted apps easily: simple, bloat-free, independent installation. ([Source Code](https://github.com/j8r/DPlatform)) `MIT` `Shell`
- [FreedomBone](https://freedombone.net/) - Home server configuration based on Debian. ([Source Code](https://code.freedombone.net/bashrc/freedombone)) `AGPL-3.0` `Shell`
- [FreedomBox](https://wiki.debian.org/FreedomBox) - Community project to develop, design and promote personal servers running free software for private, personal, communications. `GPL-3.0` `Python/Other`
- [FreeNAS](https://www.freenas.org/) - Network-attached storage (NAS) software based on FreeBSD and the OpenZFS file system. Support for SMB, AFP, NFS, iSCSI, SSH, rsync and FTP/TFTP protocols. Advanced features include full-disk encryption and plug-ins. ([Source Code](https://github.com/freenas/freenas)) `BSD-3-Clause` `Python/Other`
- [HomelabOS](https://gitlab.com/NickBusey/HomelabOS) - Your very own offline-first privacy-centric open-source data-center. `MIT` `Docker`
- [OpenMediaVault](http://www.openmediavault.org/) - OpenMediaVault is the next generation network attached storage (NAS) solution based on Debian Linux. It contains services like SSH, (S)FTP, SMB/CIFS, DAAP media server, RSync, BitTorrent client and many more. ([Source Code](https://github.com/openmediavault/openmediavault)) `GPL-3.0` `PHP`
- [Piratebox](https://piratebox.cc/start) - DIY anonymous offline file-sharing and communications system built with free software and inexpensive off-the-shelf hardware. ([Source Code](https://github.com/PirateBox-Dev)). `GPL-3.0` `Python/Other`
- [Puffin](https://github.com/puffinrocks/puffin) - Lightweight webapp catalog based on containers, with user interface à la mobile app store. `AGPL-3.0` `Python/Docker` :star:73
- [Sandstorm](https://sandstorm.io/) - Personal server for running self-hosted apps easily and securely. ([Demo](https://demo.sandstorm.io/), [Source Code](https://github.com/sandstorm-io/sandstorm)) `Apache-2.0` `C++/Other`
- [sovereign](https://github.com/sovereign/sovereign) - Set of Ansible playbooks to build and maintain your own private cloud: email, calendar, contacts, file sync, IRC bouncer, VPN, and more. `GPL-3.0` `YAML/Other` :star:7493
- [Syncloud](https://syncloud.org/) - Your own online file storage, social network or email server. ([Source Code](https://github.com/syncloud/platform)) `GPL-3.0` `Python/Other`
- [UBOS](http://ubos.net/) - Linux distro that runs on indie boxes (personal servers and IoT devices). Single-command installation and management of apps - Jenkins, Mediawiki, Owncloud, WordPress, etc., and other features. `GPL-3.0` `Perl/Other`
- [WikiSuite](http://WikiSuite.org) - The most comprehensive and integrated Free / Libre / Open Source software suite ever developed. ([Source Code](http://wikisuite.org/Source-Code)) `Multiple` `ClearOS`
- [YunoHost](https://yunohost.org/) - Server operating system aiming to make self-hosting accessible to everyone. ([Demo](https://yunohost.org/#/try), [Source Code](https://github.com/YunoHost)) `AGPL-3.0` `Python/Other`

<!-- END SOFTWARE LIST -->

--------------------

## List of Licenses

**[`^        back to top        ^`](#)**

- `⚠ ` - Depends on a third party network service
- `0BSD` - [BSD Zero-Clause Licence](https://opensource.org/licenses/0BSD)
- `AAL` - [Attribution Assurance License](https://opensource.org/licenses/AAL)
- `AGPL-3.0` - [GNU Affero General Public License 3.0](https://www.gnu.org/licenses/agpl-3.0)
- `AGPL-3.0-only` - [GNU Affero General Public License 3.0 only](https://spdx.org/licenses/AGPL-3.0-only.html)
- `Apache-2.0` - [Apache, Version 2.0](http://www.apache.org/licenses/)
- `APSL-2.0` - [Apple Public Source License, Version 2.0](https://opensource.org/licenses/APSL-2.0)
- `Artistic-2.0` - [Artistic License Version 2.0](http://opensource.org/licenses/Artistic-2.0)
- `Beerware` - [Beerware License](https://spdx.org/licenses/Beerware.html)
- `BSD-2-Clause` - [BSD 2-clause "Simplified"](https://opensource.org/licenses/BSD-2-Clause)
- `BSD-2-Clause-FreeBSD` - [BSD 2-Clause FreeBSD License](https://www.freebsd.org/copyright/freebsd-license.html)
- `BSD-3-Clause` - [BSD 3-Clause "New" or "Revised"](https://opensource.org/licenses/BSD-3-Clause)
- `BSD-3-Clause-Attribution` - [BSD with attribution](https://fedoraproject.org/wiki/Licensing/BSD_with_Attribution)
- `CC-BY-NC-SA-3.0` - [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 International License](https://creativecommons.org/licenses/by-nc-sa/3.0/)
- `CC-BY-SA-3.0` - [Creative Commons Attribution-ShareAlike 3.0 International License](https://creativecommons.org/licenses/by-sa/3.0/)
- `CC-BY-SA-4.0` - [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/)
- `CC0-1.0` - [Public Domain](https://creativecommons.org/about/cc0/)
- `CDDL-1.0` - [Common Development and Distribution License](https://opensource.org/licenses/CDDL-1.0)
- `CECILL-B` - [CEA CNRS INRIA Logiciel Libre](http://www.cecill.info/licences/Licence_CeCILL-B_V1-en.txt)
- `CPAL-1.0` - [Common Public Attribution License Version 1.0](http://opensource.org/licenses/CPAL-1.0)
- `DPL` - [Devblocks Public License 1.0](https://cerb.ai/license/)
- `ECL-2.0` - [Educational Community License, Version 2.0 ](http://opensource.org/licenses/ECL-2.0)
- `EPL-1.0` - [Eclipse Public License, Version 1.0](https://www.eclipse.org/legal/epl-v10.html)
- `GPL-1.0` - [GNU General Public License](https://www.gnu.org/licenses/gpl-1.0)
- `GPL-2.0` - [GNU General Public License 2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
- `GPL-3.0` - [GNU General Public License 3.0](http://www.gnu.org/licenses/gpl-3.0.en.html)
- `GPL-3.0-only` - [GNU General Public License 3.0](https://spdx.org/licenses/GPL-3.0-only.html)
- `IPL-1.0` - [IBM Public License](https://opensource.org/licenses/IPL-1.0)
- `ISC` - [Internet Systems Consortium License](https://www.isc.org/downloads/software-support-policy/isc-license/)
- `LGPL-2.1` - [Lesser General Public License 2.1](http://opensource.org/licenses/LGPL-2.1)
- `LGPL-3.0` - [Lesser General Public License 3.0](http://opensource.org/licenses/LGPL-3.0)
- `MIT` - [MIT License](http://opensource.org/licenses/MIT)
- `MPL-1.1` - [Mozilla Public License Version 1.1](https://www.mozilla.org/media/MPL/1.1/index.txt)
- `MPL-2.0` - [Mozilla Public License](https://www.mozilla.org/MPL/2.0/index.txt)
- `Multiple` - Various different licenses, for different components of the project's software.
- `OSL-3.0` - [Open Software License 3.0](https://opensource.org/licenses/osl-3.0.php)
- `Other` - Non-standard license, usually unique to the project itself.
- `Sendmail` - [Sendmail License](https://www.sendmail.com/pdfs/open_source/sendmail_license.pdf)
- `Unlicense` - [The Unlicense](http://unlicense.org/)
- `WTFPL` - [Do What the Fuck You Want to Public License](http://www.wtfpl.net/about/)
- `Zlib` - [Zlib/libpng License](https://opensource.org/licenses/Zlib)
- `ZPL-2.0` - [Zope Public License 2.0](http://opensource.org/licenses/ZPL-2.0)

--------------------

## External links

**[`^        back to top        ^`](#)**

- [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata) - Curated list of awesome big data frameworks, resources and other awesomeness. :star:7869
- [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) - List of high quality, topic-centric public data sources. :star:34786
- [Awesome Sysadmin](https://github.com/n1trux/awesome-sysadmin) - Curated list of amazingly awesome open source sysadmin resources. :star:8616
- Lists of software aimed at privacy and decentralization in some form: [PRISM Break](https://prism-break.org/en/), [privacytools.io](https://www.privacytools.io/), [Alternative Internet](https://redecentralize.github.io/alternative-internet/), [Libre Projects](http://libreprojects.net/)
- Dynamic Domain Name services: [Afraid.org](https://freedns.afraid.org/domain/registry/), [Pagekite](https://pagekite.net/)
- Communities/forums: [/r/selfhosted](https://www.reddit.com/r/selfhosted), [IndieWeb](https://indieweb.org/)
- Mirrors: [GitHub.com](https://github.com/Kickball/awesome-selfhosted), [Gitlab.com](https://gitlab.com/nodiscc/awesome-selfhosted)

--------------------

## Contributing

Contributing guidelines can be found [here](.github/CONTRIBUTING.md).

## Authors

The list of authors can be found [here](AUTHORS.md).

## License

This list is under the [Creative Commons Attribution-ShareAlike 3.0 Unported](LICENSE) License.


# Information comes from [CUTR-at-USF/awesome-transit](https://github.com/CUTR-at-USF/awesome-transit)
# awesome-transit [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

##### Community list of transit APIs, apps, datasets, research, and software :bus::star2::train::star2::steam_locomotive:

Have something to add or change? Open a [pull request](https://github.com/CUTR-at-USF/awesome-transit/pulls) or [issue](https://github.com/CUTR-at-USF/awesome-transit/issues).

------------------------------

### Table of Contents

- [Getting started](#getting-started)
- [Community](#community)
- [Data](#data)
- [Software for Creating APIs](#software-for-creating-apis)
- [Agency Tools](#agency-tools)
- [Hardware](#hardware)
- [Apps](#apps)
  - [Web Apps](#web-apps)
  - [Native Apps (open source)](#native-apps-open-source)
  - [Native Apps (closed source)](#native-apps-closed-source)
- [Visualizations](#visualizations)
- [GTFS](#gtfs)
  - [GTFS Libraries](#gtfs-libraries)
  - [GTFS Converters](#gtfs-converters)
  - [GTFS Data Collection and Maintenance Tools](#gtfs-data-collection-and-maintenance-tools)
  - [GTFS Analysis Tools](#gtfs-analysis-tools)
   - [GTFS Validators](#gtfs-validators)
- [GTFS Realtime](#gtfs-realtime)
  - [GTFS Realtime Libraries & Demo Apps](#gtfs-realtime-libraries--demo-apps)
  - [GTFS Realtime Validators](#gtfs-realtime-validators)
  - [GTFS Realtime (and Other Real-time API) Archival Tools](#gtfs-realtime-and-other-real-time-api-archival-tools)
  - [GTFS Realtime Convertors](#gtfs-realtime-convertors)
  - [GTFS Realtime Utilities](#gtfs-realtime-utilities)
- [SIRI](#siri)
- [Other multimodal data formats](#other-multimodal-data-formats)
- [Resources](#resources)

### Getting started

If this is your first time dealing with transit data, you might find these links useful:

- [GTFS](https://developers.google.com/transit/gtfs/) - A GTFS feed is a group of text files that contains infrequently changing transit data, like stops, routes, trips, and other schedule data. Transit agencies typically update their GTFS feed every few months.
- [GTFS Realtime](https://developers.google.com/transit/gtfs-realtime/) - GTFS Realtime consists of three binary files that contain realtime vehicle positions, realtime arrival information, and service alerts. Transit agencies typically update these files every minute.
- [TransitFeeds](https://transitfeeds.com/) - List of GTFS/GTFS-realtime data feeds from around the world. If you're trying to get realtime data for some agency, this is a good place to start.
- [World Bank - "Intro. to GTFS" online course](https://olc.worldbank.org/content/introduction-general-transit-feed-specification-gtfs-and-informal-transit-system-mapping) - A free, online, self-paced course for learning about GTFS and GTFS-realtime.


### Community

Places to ask questions and find other community resources.

- [TransitWiki](http://transitwiki.org) - A community wiki for transit planners. Like this repo, but better.
- [GTFS Slack chat](http://gtfs.herokuapp.com/)
- [Transit Developers mailing list](https://groups.google.com/forum/#!forum/transit-developers)
- OneBusAway
  - [OneBusAway User mailing list](http://groups.google.com/group/onebusaway-users)
  - [OneBusAway Developers mailing list](http://groups.google.com/group/onebusaway-developers)
  - [OneBusAway API mailing list](http://groups.google.com/group/onebusaway-api)
  - [OneBusAway Slack chat](https://onebusaway.herokuapp.com/)

### Data

Places to access collections of GTFS and other transit and multimodal data

#### 3rd party GTFS URL directories
- [Transitland](https://transit.land/) - Community editable list of many transit agency GTFS datasets. Also provides an API to access the data as JSON/GeoJSON and a playground to try out the data.
- [TransitFeeds](http://transitfeeds.com/) - List of GTFS and [GTFS-RT](http://transitfeeds.com/search?q=gtfsrt) feeds. [Archives and validates](http://transitfeeds.com/p/capital-metro/24) the GTFS feeds and allows you to preview both [GTFS](http://transitfeeds.com/p/capital-metro/24/20151015) and [GTFS-RT](http://transitfeeds.com/p/capital-metro/495) through the browser.
- [~~GTFS Data Exchange~~ (Deprecated)](http://www.gtfs-data-exchange.com/agencies) - Formerly the definitive directory of GTFS feed URLs. Shutdown in 2016. But 93 GB of data from 2008 to 2016 is available upon request.

#### Transit agency data archives
- [CapMetrics](https://github.com/scascketta/CapMetrics) - Historical vehicle locations for Austin's transit agency (CapMetro). Data is collected by [capmetricsd](https://github.com/scascketta/capmetricsd), a Go daemon. :star:14

#### U.S. Federal Government
- [National Transit Database](https://www.transit.dot.gov/ntd) - Information and statistics on the transit systems of the United States, run by the Federal Transit Administration.

#### Proprietary (non-standard) vendor APIs
- [Transport API](https://www.transportapi.com/) - REST API for aggregated transit data for the United Kingdom.  Fee-based access.
- [TransLoc OpenAPI](https://market.mashape.com/transloc/openapi-1-2) - REST API for real-time vehicle, route, stop, and arrival data for over 60 transit systems in the United States that have purchased TransLoc's AVL hardware and software.
- [NextBus API](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) - REST API for real-time vehicle, route, stop, and arrival data for agencies that have puchased NextBus's hardware and/or software.
- [Navitia.io](http://www.navitia.io/) - REST API for journey planning, stop schedules, isocrhons and lot more on US and EU. [Navitia](https://github.com/CanalTP/navitia) is the opensource engine behind the live API.
- [CityBikes](http://api.citybik.es) - REST API for aggregated bikeshare data from around the world. Powered by [pyBikes](https://github.com/eskerda/pybikes).

### Software for Creating APIs

Software that you can set up to provide an API to transit and multimodal data.

- [OneBusAway](http://onebusaway.org/) - A Java app that consumes GTFS and GTFS-Realtime (along with [other formats](https://github.com/OneBusAway/onebusaway-application-modules/wiki/Real-Time-Data-Configuration-Guide)) and turns them into an easy to use [REST API](http://developer.onebusaway.org/modules/onebusaway-application-modules/current/api/where/index.html).
- [OpenTripPlanner](http://www.opentripplanner.org/) - An open source platform for multi-modal and multi-agency journey planning, as well as returning information about a multi-modal graph (using data sources such as GTFS and [OpenStreetMap](http://www.openstreetmap.org/)).
- [TransitClock](http://thetransitclock.org) - Java application that can consume raw vehicle positions and generate prediction times in formats such as GTFS-realtime.  Formerly known as "Transitime".
- [Linked Connections](http://linkedconnections.org/) - An open-source, scalable intermodal route planning engine, which allows clients to execute the route planning algorithm (as opposed to the server). Uses GTFS data.
- [TransiCast](http://www.transicast.com/) - Provides public transportation data for North America in a single, integrated call and response format. The data is provided in stream-parsable XML and JSON formats.  Open-source on [Google Code](https://code.google.com/archive/p/rasa/).  Hosted version at www.transitcast.com [requires payment](http://www.transicast.com/coststructure.html).
- [gtfs-server](https://github.com/denysvitali/gtfs-server) - A web server, written in Rust that uses PostGIS as a backend to serve GTFS data via a HTTP endpoint :star:1
- [Navitia](https://github.com/CanalTP/navitia) is the opensource engine behind the [Navitia.io](http://www.navitia.io/) live API.
- [pyBikes](https://github.com/eskerda/pybikes) - Software powering [CityBikes](http://api.citybik.es) for worldwide bikeshare system info :star:319

### Agency Tools

Tools for transit agencies.  See also [GTFS Tools](#gtfs-tools) for tools specific to GTFS.

- [Remix](http://getremix.com/) - A webapp that lets transit agencies easily plan routes.
- [AC Transit RestroomFinder](https://github.com/actransitorg/ACTransit.RestroomFinder) - Pinpoints the nearest authorized restroom for bus operator and field staff, using GPS and on-screen map. :star:1
- [AC Transit Training and Education Department (TED) application](https://github.com/actransitorg/ACTransit.Training) - This application supports the District's training operations for transportation and maintenance employees, primarily in the positions of Bus Operators and Heavy Duty Coach Mechanics (Apprentice and Journey), although the system supports new courses and apprenticeship programs. :star:7
- [AC Transit Customer Relations application (CusRel)](https://github.com/actransitorg/ACTransit.CusRel) - Public transit ticketing system for customer issues and feedback with: inter-departmental routing with notifications, department/person assigments, simple workflow, ticket searching, pre-canned reports, daily reminders and more.
- [TransAM](http://camsys.software/products/transam) - An open-source asset management platform for public transportation agencies.  Open-source [on Github](https://github.com/camsys/transam_core).
- [RidePilot](https://github.com/camsys/ridepilot) - An open-source Computer Aided Scheduling and Dispatch (CASD) software system to meet the needs of small scale human service transportation agencies (for more info see [Cambridge Systematics's marketing site](http://camsys.software/products/ridepilot)). :star:6

### Hardware

Experimental and production transit hardware.

- [Bus Tracking GPS](https://github.com/herrdragon/busTrackingGps) - Code for Miami prototype of a cheap open-source solution to track transit buses. :star:13

### Apps

Apps people use when taking transit.

#### Web Apps

- [TransitScreen](http://transitscreen.com/) - Custom realtime displays of all local transportation choices
- [Instabus](http://instabus.org) - Realtime map of Austin's (CapMetro) public transit. Has no server/backend dependency at all and runs completely on GitHub pages.
- [Maryland MTA Real-time Vehicle Tracking](http://realtimemap.mta.maryland.gov/hiwire?.a=iRealTimeDisplay)
- [OpenTripPlanner Client GWT](https://github.com/mecatran/OpenTripPlanner-client-gwt) - A Google Web Toolkit-based web interface for OpenTripPlanner :star:5
- [OpenTripPlanner.js](https://github.com/conveyal/otp.js) - A Javascript-based client for OpenTripPlanner :star:15
- [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) - A Java-based web application for producing GTFS-realtime Service Alerts. :star:1
- [HRT BUS Web app](https://github.com/Code4HR/hrt-bus-api) - HRT Bus API publishes real time bus data from Hampton Roads Transit through an application programming interface for developers to make apps from it. :star:15
- [Transit-Map](https://github.com/vasile/transit-map) - Web app that animates vehicles (markers) on a map using the public transport timetables to interpolate their positions along the routes (polylines). :star:263
- [Bikeshare Map](http://bikes.oobrien.com/) - Status of all worldwide bikeshare stations
- [Bongo](http://ebongo.org) - Real-time Transit Tracking for Iowa City, Coralville and the University of Iowa. Awesome because it combines three disparate transit systems into one UI.
- [Transitive.js](https://github.com/conveyal/transitive.js) - Creates a customizable web map layer of transit routes using Leaflet or D3. :star:570
- [Brand New Subway](http://jpwright.net/subway/) - An interactive transportation planning game that lets players alter the NYC subway system to their heart's content.
- [CityMapper Webapp](https://citymapper.com/nyc) - Really polished webapp with trip planner and route status for over 30 of cities.
- [Google I/O Transport Tracker](https://github.com/googlemaps/transport-tracker) - Shows shuttle arrival times for Google I/O conference, based on the open-source [transport-tracker project](https://github.com/googlemaps/transport-tracker).  Note: To implement this yourself, you need a [Google Maps APIs Premium Plan license](https://developers.google.com/maps/pricing-and-plans/). :star:248
- [YourStop](http://yourstop.info) - Mobile friendly web app which consumes GTFS feeds and displays both live and scheduled trips for stops. Launched with MBTA, YRT/Viva and Maryland MTA.
- [1-Click](http://camsys.software/products/1-click) - A virtual “trip aggregator” that assembles information on a wide variety of available modes: public transit, private, rail, rideshare, carpool, volunteer, paratransit, and walking and biking. Open-source [on Github](https://github.com/camsys/oneclick).
 
#### Native Apps (open source)

- OneBusAway Apps - [Android](https://play.google.com/store/apps/details?id=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [Fire Phone](http://www.amazon.com/gp/mas/dl/android?p=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [iOS](https://itunes.apple.com/us/app/onebusaway/id329380089)  [*(source code)*](https://github.com/OneBusAway/onebusaway-iphone), [Windows Phone](https://www.microsoft.com/en-us/store/apps/onebusaway/9nblggh0cbd9) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows-phone), [Windows 8](https://www.microsoft.com/en-us/store/apps/onebusaway/9wzdncrdm5pc) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows8), [Google Glass GDK](https://github.com/OneBusAway/onebusaway-android/pull/219) [*(source code)*](https://github.com/OneBusAway/onebusaway-android/pull/219)
- [OpenTripPlanner Android](https://github.com/CUTR-at-USF/OpenTripPlanner-for-Android/wiki) - An Android app for [OpenTripPlanner](http://www.opentripplanner.org/)
- [OpenTripPlanner iOS](https://github.com/opentripplanner/OpenTripPlanner-iOS) - An iOS app for [OpenTripPlanner](http://www.opentripplanner.org/)
- [Transportr](https://github.com/grote/Transportr) An Android app that uses [public-transport-enabler](https://github.com/schildbach/public-transport-enabler) in order to connect to many different transport networks worldwide.

#### Native Apps (closed source)

- [ally](http://www.allyapp.com/)
- [Transit](http://transitapp.com/)
- [CityMapper](https://citymapper.com/)
- [Moovit](http://moovitapp.com/)
- [Tiramisu Transit](http://www.tiramisutransit.com/)
- [TransLoc Rider](http://translocrider.com/) - Real-time transit maps for over 100 transit systems.
- [Transit Display](http://transitdisplay.com/) - Multimodal and real-time transit display software.

### Visualizations

- [Visualizing MBTA Data](http://mbtaviz.github.io/) - Interactive graphs that show how people use Boston's subway system.
- [MIT COAXS](http://mittransportanalyst.github.io/) - Co-creative Planning of Transit Corridors using Accessibility-Based Stakeholder Engagement (shows route scenarios using [OpenTripPlanner Analyst](http://www.opentripplanner.org/analyst/)).
- [TRAVIC Transit Visualization Client](http://tracker.geops.ch/) - Visualizes vehicles moving based on static GTFS data (and sometimes realtime data). Supports over 260 cities.  Github account for geOps organization is [here](https://github.com/geops).
- [Muni, this moment](http://allthebuses.com/) - Realtime map of all the buses in San Francisco.
- [MTA Frequency](http://www.tyleragreen.com/maps/new_york/) - Frequency visualization of subways and buses in New York City built using [Transitland](https://transit.land/).
- [Veridict LiveMap](https://livemap.veridict.com/) - Millions of individually tracked public transport units across the entire world. Based on a number of sources, including GTFS and GTFS-RT. 
- [Graphs in Transit](https://gtfs-graph.herokuapp.com/) - Graph centrality metrics displayed over rapid transit networks for New York City, Boston, and Paris.
- [SEPTA Rail OTP Report](https://github.com/fulldecent/septa-regionalrail-otp) - An online on-time performance reporing & drill down tool using GTFS. :star:5
- [TransitFlow](https://github.com/transitland/transitland-processing-animation) Animate GTFS data around the world using Processing and Transitland.
- [gtfspy-webviz](https://github.com/CxAalto/gtfspy-webviz) - Web application for animation and visualization of GTFS data using the [gtfspy](https://github.com/CxAalto/gtfspy) Python3 library. :star:11
- [Mapnificent](https://www.mapnificent.net/) - Shows areas you can reach with public transport in a given time. Open-source [on GitHub](https://github.com/mapnificent/mapnificent), live at https://www.mapnificent.net/.
- [Toronto Transit Explorer](https://github.com/sidewalklabs/totx) - A Java application that visualizes transit, biking and walking accessibility across the city of Toronto. Live version hosted [here](https://totx.sidewalklabs.com/). Uses a modified version of [R5](https://github.com/conveyal/r5) for routing. :star:12

### GTFS

- [GTFS Spec](https://developers.google.com/transit/gtfs/) - Specification for the General Transit Data Feed, or GTFS.
- [GTFS Best Practices](http://gtfs.org/best-practices/) - Best practices for producers of a GTFS feed.

#### GTFS Libraries

Software that makes it easy to consume GTFS data in a variety of languages.

- [Mapzen GTFS](https://github.com/transitland/mapzen-gtfs) - A Python GTFS library that supports reading individual GTFS tables, or constructing a graph to represent each agency in a feed. :star:18
- [gtfsdb](https://github.com/OpenTransitTools/gtfsdb) - Python library for converting GTFS files into a relational database. :star:67
- [OneBusAway GTFS Modules](https://github.com/OneBusAway/onebusaway-gtfs-modules/wiki) - A Java-based library for reading, writing, and transforming public transit data in the GTFS format, including database support.
- [GTFS to SQL](https://github.com/TransitFeeds/GtfsToSql) - Parses a GTFS feed into an SQL database (used in [TransitFeeds.com](http://transitfeeds.com/))
- [SQL to GTFS](https://github.com/TransitFeeds/SqlToGtfs) - Convert an SQLite file generated with "GtfsToSql" back to a zipped GTFS file. :star:4
- [Go GTFS Parser](https://github.com/geops/gtfsparser) - A GTFS parsing library for Go :star:26
- [GTFS Feed Parser](https://github.com/OsmSharp/GTFS) - .Net/Mono implementation of a GTFS parser :star:32
- [Node-GTFS](https://github.com/brendannee/node-gtfs) - Loads transit data from [GTFS Data Exchange](http://www.gtfs-data-exchange.com/), unzips it and stores it to a MongoDB database and provides some methods to query for agencies, routes, stops and times. :star:241
- [GTFS-viz](https://github.com/vasile/GTFS-viz) - Ruby script that converts a set of GTFS files into a SQLite database + GeoJSONs (needed by the [Transit Map](https://github.com/vasile/transit-map) web application)
- [gtfs-sequelize](https://github.com/evansiroky/gtfs-sequelize) - Node.js library modeling the static GTFS using [sequelize.js](http://sequelizejs.com/). :star:11
- [gtfslib-python](https://github.com/afimb/gtfslib-python) -  An open source library in python for reading GTFS files and computing various stats and indicators about Public Transport networks. :star:30
- [multigtfs](https://github.com/tulsawebdevs/django-multi-gtfs) - A Django application to import and export GTFS :star:37
- [GTFSTK](https://github.com/araichev/gtfstk) - A Python 3 toolkit for analyzing GTFS data in memory. Uses Pandas and Shapely for speed. :star:34
- [gtfs-schema](https://github.com/tyleragreen/gtfs-schema) - PostgreSQL schema for GTFS feeds. :star:1
- [partridge](https://github.com/remix/partridge) - A fast, forgiving Python GTFS reader built on pandas DataFrames. :star:37
- [gtfspy](https://github.com/CxAalto/gtfspy) - Public transport network analysis and travel time computations using Python3 and SQLite.  Used by [gtfspy-webviz](https://github.com/CxAalto/gtfspy-webviz). :star:20
- [RRRR Rapid Real-time Routing](https://github.com/bliksemlabs/rrrr) - RRRR (usually pronounced R4) is a C-language implementation of the RAPTOR public transit routing algorithm. :star:104
- [R5: Rapid Realistic Routing on Real-world and Reimagined networks](https://github.com/conveyal/r5) - A Java-based routing engine for multimodal (transit/bike/walk/car) networks. It currently plans many trips over a time window for analytics purposes, but may eventually support point-to-point journey planning. :star:51
- [gtfsman](https://github.com/geops/gtfsman) - Repository-like tool in Python to manage and update a huge number of GTFS feeds. :star:14
- [go gtfsparser](https://github.com/geops/gtfsparser) - A GTFS parsing library implemented in Go. :star:26

#### GTFS Converters

Converters from various static schedule formats to and from GTFS. 

- [Transmodel and IFF to GTFS](https://github.com/bliksemlabs/bliksemintegration) - Imports and syncs (Transmodel) BISON Koppelvlak1, IFF (a format written by HP/EDS, somewhat similiar to ATCO CIF) to import timetables of the railway networks. The internal pseudo-NETeX datastructure allows to export to GTFS and there are proof-of-concepts to export to other formats such as NETeX, GTFS and IFF. :star:2
- [Open-Transport SYNTHESE Convertors](https://github.com/Open-Transport/synthese/wiki) - Converts French-Transmodel, SIRI, NETeX, HAFAS, HASTUS, VDV452, and more.
- [Chouette](http://www.chouette.mobi/) - Converts French-Transmodel, SIRI, NETeX. See Chouette.mobi website for more info.
- [osm2gtfs](https://github.com/grote/osm2gtfs) - Turn OpenStreetMap data and schedule information into GTFS. :star:33
- [GTFS-OSM-Sync](https://github.com/CUTR-at-USF/gtfs-osm-sync) - A Java tool for synchronizing data in GTFS format with [OpenStreetMap.org](http://www.openstreetmap.org/). :star:57
- [onebusaway-gtfs-to-barefoot](https://github.com/OneBusAway/onebusaway-gtfs-to-barefoot) - A Java tool to create a [Barefoot](https://github.com/bmwcarit/barefoot) mapfile from a GTFS file.
- [osmtogtfs](https://github.com/hiposfer/osmtogtfs) - Python 3 script that exports GTFS feed from OpenStreetMap data. :star:3
- [transloc-gtfs-rectifier](https://github.com/laidig/transloc-gtfs-rectifier) - Python application that attempts to assign GTFS stop_ids to [TransLoc](http://transloc.com/) IDs using [TransLoc's API](https://market.mashape.com/transloc/openapi-1-2) ([TransLoc](http://transloc.com/) doesn't provide GTFS `stop_ids` in their API). :star:1
- [Hafas2GTFS](https://github.com/geops/hafas2gtfs) - Hafas2GTFS converter written in Python, optimized for SBB HAFAS feeds. :star:11

#### GTFS Data Collection and Maintenance Tools

- [bus-router](https://github.com/atlregional/bus-router) - Python script that generates missing shapes.txt for GTFS using routing from [Google Maps Directions API](https://developers.google.com/maps/documentation/directions/) or [OSRM](https://github.com/Project-OSRM/osrm-backend/wiki/Server-api). :star:21
- [GTFS Editor](https://github.com/conveyal/gtfs-editor) A (self-hosted) web-based GTFS editing framework.
- [GTFS Editor for Vagrant](https://github.com/laidig/vagrant-gtfs-editor) Quickly set up the GTFS editor (above) using [Vagrant](https://www.vagrantup.com/)
- [static-GTFS-manager](https://github.com/WRI-Cities/static-GTFS-manager) - A (self-hosted) browser-based user interface for creating, editing, exporting of static GTFS feeds (see [related post](https://groups.google.com/forum/#!topic/transit-developers/GFz5rTJTB0I)).  Live demo [here](https://thawing-mountain-46422.herokuapp.com/). :star:11
- [TransitWand](http://transitwand.com/) - An open source web and mobile application for collecting transit data. Use it to create GTFS feeds, capture passenger counts or generate GIS datasets.
- [Gtfs Data Manager](https://github.com/conveyal/gtfs-data-manager) - A workflow tool for managing large amounts of GTFS data and importing them into OpenTripPlanner. :star:25
- [GTFS.html](https://gtfs.pleasantprogrammer.com) - An entirely browser-based tool to view GTFS feeds. Use it to view routes, stops, timetables, etc.

#### GTFS Analysis Tools

- [Peartree](https://github.com/kuanb/peartree) A Python library for converting transit data into a directed graph for network analysis.
 
#### GTFS Validators

- [feedValidator](https://github.com/google/transitfeed/wiki/FeedValidator) - Google supported Python-based GTFS validator.
- [gtfs-validator](https://github.com/conveyal/gtfs-validator) - A GTFS validator based on the OneBusAway GTFS Modules, runs in Java and is faster than the Google provided one.  :star:16
- [gtfs-lib](https://github.com/conveyal/gtfs-lib/) - Conveyal's successor to gtfs-validator, a library for loading and saving GTFS feeds of arbitrary size with disk-backed storage.
- [GTFS Data Package Specification](https://github.com/Stephen-Gates/GTFS) - A [Data Package specification](http://specs.frictionlessdata.io/data-packages/) with validation accomplished with [Good Tables](http://goodtables.okfnlabs.org/). Includes a data package, schemas, tests, and uses South East Queensland GTFS data as an example. :star:11
- [Web GTFS Meta-Validator (hosted by Omni)](http://gtfsvalidator.omnimodal.io) - A web-based GTFS validator that runs both [feedValidator](https://github.com/google/transitfeed/wiki/FeedValidator) and [gtfs-validator](https://github.com/conveyal/gtfs-validator) on uploaded GTFS files.

#### GTFS Realtime

- [GTFS-realtime documentation](https://github.com/google/transit/tree/master/gtfs-realtime)
- [GTFS-realtime Autodoc](https://laidig.github.io/gtfs-rt-autodoc/index.html) - Automatically generated documentation for GTFS-realtime, generated from the official [GTFS-realtime protocol buffer specification](https://github.com/google/transit/blob/master/gtfs-realtime/proto/gtfs-realtime.proto) and including some extensions. 

#### GTFS Realtime Libraries & Demo Apps

- [gtfs-realtime-bindings](https://github.com/google/gtfs-realtime-bindings) - The official bindings for Java, .NET, Node.js, Python, and Ruby generated from the official [GTFS-realtime protocol buffer specification](https://github.com/google/transit/blob/master/gtfs-realtime/proto/gtfs-realtime.proto). :star:146
- [GTFS-realtime Exporter](https://github.com/OneBusAway/onebusaway-gtfs-realtime-exporter/wiki) - A Java-based tool that assists in producing and sharing a GTFS-relatime feed.
- [GTFS-realtime Alerts Producer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-alerts-producer-demo/wiki) - A Java-based demo project for producing GTFS-realtime Service Alerts.
- [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) - A Java-based web application for producing GTFS-realtime Service Alerts. :star:1
- [GTFS-realtime TripUpdates & VehiclePositions Producer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-trip-updates-producer-demo/wiki) - A Java-based demo project for producing GTFS-realtime TripUpdates (estimated arrivals) and Vehicle Positions.
- [GTFS-realtime Vehicle Positions Consumer/Visualizer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-visualizer/wiki) - A Java-based demo project for consuming a GTFS-realtime Vehicle Positions feed and displaying this info on a map.

#### GTFS Realtime Validators

- [gtfs-realtime-validator](https://github.com/CUTR-at-USF/gtfs-realtime-validator) - A GTFS-realtime validation tool developed by the Center for Urban Transportation Research at the University of South Florida.  Also includes an integrated version of the [gtfs-validator](https://github.com/conveyal/gtfs-validator) tool. :star:24
- [Web gtfs-realtime-validator (hosted by TransitScreen)](http://gtfsrealtimevalidator.transitscreen.com/) - A hosted version of the [gtfs-realtime-validator](https://github.com/CUTR-at-USF/gtfs-realtime-validator).

#### GTFS Realtime (and Other Real-time API) Archival Tools

- [GTFS-realtime to SQL](https://github.com/TransitFeeds/GtfsRealTimeToSql) - Parses a GTFS-RealTime feed into an SQL database (used in [TransitFeeds.com](http://transitfeeds.com/))
- [gtfsrdb](https://github.com/CUTR-at-USF/gtfsrdb) - A Python tool that supports reading and archiving GTFS-realtime feeds into a database :star:8
- [retro-gtfs](https://github.com/SAUSy-Lab/retro-gtfs) - A Python application that collects real-time data from the Nextbus API and archives it into the GTFS format (i.e., retrospective GTFS). :star:19

#### GTFS Realtime Convertors

- [SIRI to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-siri-cli/wiki) - A Java-based command-line utility to convert from the [SIRI format](http://user47094.vs.easily.co.uk/siri/) to GTFS-realtime
- [OrbCAD SQL Server to GTFS-realtime](https://github.com/CUTR-at-USF/HART-GTFS-realtimeGenerator/) - A Java-based command-line utility that extracts vehicle positions and trip updates information from an OrbCAD SQL Server and exports them to the GTFS-realtime TripUpdates and VehiclePositions formats.
- [NextBus API to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-nextbus-cli/wiki) - A Java-based command-line utility to convert from the [NextBus API format](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) to GTFS-realtime.  Note that NextBus now directly offers a GTFS-realtime API for their products.  See [Cubic site](http://nextbus.cubic.com/Products/Real-Time-Rider-Information) and [this FAQ](https://medium.com/omnimodal/want-more-riders-open-up-your-nextbus-api-with-gtfs-realtime-7387c80f31e1#.pkuzizhl5).
- [Syncromatics API to GTFS-realtime](https://github.com/CUTR-at-USF/bullrunner-gtfs-realtime-generator) - A Java-based command-line utility to convert from the [Syncromatics API](http://www.syncromatics.com/) format to GTFS-realtime TripUpdates and VehiclePositons.
- [KV6,15,17, and ARNU to GTFS-realtime](https://github.com/bliksemlabs/bliksemintegration-realtime) - Java-based tool to process incoming KV6,15,17 and ARNU and match them to static transit data present in a RID integration database. It then proceeds to export this data as ARNU RITinfo, GTFS(realtime) and KV78turbo
- [WMATA BusPositions API to GTFS-realtime](https://github.com/kurtraschke/wmata-gtfsrealtime) - Java-based tool to convert from WMATA's [BusPositions API](https://developer.wmata.com/docs/services/54763629281d83086473f231/operations/5476362a281d830c946a3d68) and Alert RSS feeds from [MetroAlerts](http://www.wmata.com/rider_tools/metro_service_status/rail_bus.cfm?) to GTFS-realtime TripUpdates, VehiclePositions, and Alerts feeds. :star:10
- [SEPTA API to GTFS-realtime](https://github.com/kurtraschke/septa-gtfsrealtime) - Java-based tool to convert [SEPTA's](http://www.septa.org/) [real-time bus and rail data](http://www3.septa.org/hackathon/) to GTFS-realtime :star:1
- [CTA API to GTFS-realtime](https://github.com/kurtraschke/ctatt-gtfsrealtime) - Java-based tool to convert [CTA's](http://www.transitchicago.com/) [Train Tracker data](http://www.transitchicago.com/developers/traintracker.aspx) to GTFS-realtime. :star:3
- [Detroit DOT to GTFS-realtime](https://github.com/prashtx/ddot-avl) - Extract real-time info from [DDOT's](http://www.detroitmi.gov/How-Do-I/Locate-Transportation/Bus-Schedules) TransitMaster installation (database) and convert to GTFS-realtime :star:2
- [Live Transit Event Trigger](https://github.com/ipublic/live_transit_event_trigger) - Extracts data from [Ride On's](http://www.montgomerycountymd.gov/dot-transit/) OrbCAD database and export as GTFS-realtime. :star:3
- [SoundTransit to GTFS-realtime](https://github.com/bdferris/onebusaway-sound-transit-realtime) - Convert text file feed from [Sound Transit](http://www.soundtransit.org/) to GTFS-realtime :star:2
- [Civic Transit](https://github.com/jestin/CivicTransit) - Screen-scrapes [KCATA’s](http://www.kcata.org/) TransitMaster WebWatch installation to produce a GTFS-realtime feed. :star:3
- [GTFS-realtime VehiclePositions to GTFS-realtime TripUpdates (TransitClock)](http://thetransitclock.org) - Java application that can consume raw vehicle positions and generate prediction times in formats such as GTFS-realtime.  Formerly known as "Transitime".

#### GTFS Realtime Utilities

- [gtfs-rt-dump](https://github.com/kurtraschke/gtfs-rt-dump) - Converts protocol buffer format to plain text for easy viewing of a GTFS-realtime feed in plain text (for debugging purposes)
- [GTFS-realtime Printer](https://github.com/laidig/gtfs-rt-printer) Java-based utility to print out information from a GTFS-realtime file or URL.
- [GTFS-realtime Munin Plugin](https://github.com/OneBusAway/onebusaway-gtfs-realtime-munin-plugin) - Provides a [Munin](http://munin-monitoring.org/) plugin for logging information about a GTFS-realtime feed. :star:1
- [GTFS-realtime Nagio Plugin](https://github.com/OneBusAway/onebusaway-gtfs-realtime-nagios-plugin) - Provides a [Nagios](https://www.nagios.org/) plugin for monitoring a GTFS-realtime feed :star:1
- [GTFS-realtime-test-service](https://github.com/CUTR-at-USF/gtfs-realtime-test-service) - A tool for mocking GTFS-realtime feed content (e.g., for use in testing a GTFS-realtime consuming application)

### SIRI

- [SIRI API](https://github.com/OneBusAway/onebusaway/wiki/SIRI-Resources) - Java classes generated from the v1.0 and v1.3 [SIRI](http://user47094.vs.easily.co.uk/siri/) schemas.
- [SIRI 2.0 API](https://github.com/laidig/siri-20-java) - Java classes generated from the v2.0 [SIRI](http://user47094.vs.easily.co.uk/siri/) schemas. :star:3
- [SIRI to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-siri-cli/wiki) - A Java-based command-line utility to convert from the [SIRI format](http://user47094.vs.easily.co.uk/siri/) to GTFS-realtime.
- [SIRI 2.0 Autodoc](https://laidig.github.io/siri-20-java/doc/) - Automatically generated documentation from the (incredibly well) annotated SIRI 2.0 Schema Definition. 
- [King County Metro Legacy AVL to SIRI](https://github.com/bdferris/onebusaway-king-county-metro/tree/master/onebusaway-king-county-metro-legacy-avl-to-siri) - Java-based tool to convert [King County Metro's](http://metro.kingcounty.gov/) Legacy AVL format to SIRI.
- [SIRI REST Client](https://github.com/CUTR-at-USF/SiriRestClient/wiki) - An open-source Android library for interacting with the RESTful SIRI interface for real-time transit data, such as that currently being used by the [MTA Bus Time API](http://bustime.mta.info/wiki/Developers/SIRIIntro).
- [SIRI 1.3 POJOs (Android-compatible)](https://github.com/CUTR-at-USF/onebusaway-siri-api-v13-pojos/wiki) - Android-compatible Plain Old Java Objects (POJOSs) used for data binding (deserliazing XML/JSON) responses for SIRI v1.3 APIs.  Used by the [SIRI REST Client](https://github.com/CUTR-at-USF/SiriRestClient/wiki).
- [pysiri2validator](https://github.com/laidig/pysiri2validator) - Simple validator for SIRI 2.0 written in Python 3.

### Other multimodal data formats

- [NeTex](http://netex-cen.eu/) - A general purpose XML format designed for the exchange of complex static transport data among distributed systems managed by the [CEN standards process](https://www.cen.eu/work/ENdev/how/Pages/default.aspx).
- [General Bikeshare Feed Specification (GBFS)](https://github.com/NABSA/gbfs) - Open data standard for real-time bikeshare information developed by members of the [North American Bikeshare Association (NABSA)](http://nabsa.net/). :star:178
- [GTFS-ride](https://github.com/ODOT-PTS/GTFS-ride) - An open, fixed-route transit ridership data standard developed through a partnership between the Oregon Department of Transportation and Oregon State University. :star:20
- [Managed and Tolled Lanes Feed Specification (MTLFS)](https://github.com/vta/Managed-and-Tolled-Lanes-Feed-Specification) - Proposal for a schema that comprise the Managed and Tolled Lanes Tolling Feed Specification (MTLFS) and defines the fields used in all of those files developed by [Santa Clara Valley Transportation Authority](http://www.vta.org/). :star:5
- [GTFS-plus](https://github.com/osplanning-data-standards/GTFS-PLUS) - A GTFS-based transit network format for *vehicle and capacity data* suitable for dynamic transit modeling developed by Puget Sound Regional Council, UrbanLabs LLC, LMZ LLC, and San Francisco County Transportation Authority. :star:12
- [Dyno-Demand](https://github.com/osplanning-data-standards/dyno-demand) - A GTFS-based travel demand data format focusing on individual passenger *demand* suitable for dynamic network modeling developed by San Francisco County Transportation Authority, LMZ LLC, and UrbanLabs LLC. :star:1
- [Dyno-Path](https://github.com/osplanning-data-standards/dyno-path) - (Under development - see [this post](https://github.com/osplanning-data-standards/GTFS-PLUS/pull/52#issuecomment-331231000)) Data for individual passenger *trajectories*. :star:1
- [GTFS-stat](https://github.com/osplanning-data-standards/GTFS-STAT) - An extension to a GTFS transit network with additional files that contain performance data developed by UrbanLabs LLC and San Francisco County Transportation Authority. :star:2
- [TIDES project](https://groups.google.com/forum/#!forum/tidesproject) -  Transit ITS Data Exchange Specification (TIDES) is a proposed effort to create standard data structures, APIs, and data management tools for historical transit ITS data including AVL, APC and AFC Data.
- [SAE Shared and Digital Mobility Committee](http://articles.sae.org/15799/) - Appears to be working on a data standard for car share and transportation network companies (TNCs) / rideshare.
- [Alliance for Parking Data Standards (APDS)](https://www.allianceforparkingdatastandards.org/) - Formed by the [International Parking Institute (IPI)](https://www.parking.org/), the [British Parking Association (BPA)](http://www.britishparking.co.uk/), and the [European Parking Association (EPA)](http://www.europeanparking.eu/), APDS is a not-for-profit organization with the mission to develop, promote, manage, and maintain a uniform global standard that will allow organizations to share parking data across platforms worldwide.

### Resources

On-line courses, blog posts, and reports related to open transit data.

#### On-line courses

- [World Bank - "Intro. to GTFS" online course](https://olc.worldbank.org/content/introduction-general-transit-feed-specification-gtfs-and-informal-transit-system-mapping) - A free, online, self-paced course for learning about GTFS and GTFS-realtime.

#### Blog posts

- [When(ish) is my bus? Data and code](https://github.com/mjskay/when-ish-is-my-bus) - The data and code (R) behind Whenish is my bus? Data includes three days of historical vehicle positions and the survey results. :star:20
- ["Legacy AVL system? It's okay, join the club." by Kurt Raschke](https://kurtraschke.com/2015/01/legacy-avl-export) - Discussion of options for transforming legacy AVL system data into the GTFS-realtime format.
- ["GTFS Best Practices now available!" by Sean Barbeau](https://medium.com/@sjbarbeau/gtfs-best-practices-now-available-88ac67194233) - Discusses some of the challenges of an open data format like GTFS and the GTFS Best Practices that were launched in early 2017 to help address data quality.
- ["What's new in GTFS-realtime v2.0" by Sean Barbeau](https://medium.com/@sjbarbeau/whats-new-in-gtfs-realtime-v2-0-cd45e6a861e9) - Discuss the shortfalls in GTFS-realtime v1.0 and the improvements in v2.0.
- ["AVL, CAD, and Real-Time Passenger Info for Beginners" by Tony Laidig](http://transitdata.net/avl-cad-and-real-time-passenger-info-for-beginners/) - Provides a general introduction to technology used to track vehicles.

#### Academic papers

- [Tang et al. - "Ridership effects of real-time bus information system: A case study in the City of Chicago"](https://www.sciencedirect.com/science/article/pii/S0968090X12000022) - Experiment in Chicago, IL showed modest increase in ridership when riders had access to real-time info via text message or email.
- [Kay et al. - "When(ish) is my bus? User-centered Visualizations of Uncertainty in Everyday, Mobile Predictive Systems"](http://faculty.washington.edu/jhullman/busUncertaintyVis.pdf) - Paper attempts to answr the question of "how do we communicate uncertainty in transit predictions?" Explains the problem, existing solutions and designs a [better interface for letting users know when to arrive at the bus stop](https://github.com/mjskay/when-ish-is-my-bus/blob/master/quantile-dotplots.md#quantile-dotplots).
- [Watkins et al. - "Where Is My Bus? Impact of mobile real-time information on the perceived and actual wait time of transit riders"](https://www.sciencedirect.com/science/article/pii/S0965856411001030) - Experiments in Seattl,e WA showed that riders perceived shorter bus wait times when they had access to real-time info via mobile apps.
- [Brakewood et al. - “An experiment evaluating the impacts of real-time transit information on bus riders in Tampa, Florida”](https://www.sciencedirect.com/science/article/pii/S0965856414002146) - Controlled experiment in Tampa, FL showed that riders with access to real-time info via mobile apps perceived nearly 2 minute reduction in wait times compared to riders without real-time info.  Riders with real-time info also had decreases in anxiety and frustration and better reception of agency.
- [Brakewood et al. - "The impact of real-time information on bus ridership in New York City"](https://www.sciencedirect.com/science/article/pii/S0968090X15000297) - Experiment in NYC showed that ridership increased on long routes when real-time info was made available to riders.

#### Government reports
- [APTA Policy Development and Research - Public Transportation Embracing Open Data](http://www.apta.com/resources/reportsandpublications/Documents/APTA-Embracing-Open-Data.pdf) - APTA's discussion of the benefits and challenges of open transit data (a short summary of the below TCRP report).
- [TCRP Synthesis 115 - Open Data: Challenges and Opportunities for Transit Agencies](http://onlinepubs.trb.org/Onlinepubs/tcrp/tcrp_syn_115.pdf) - A comprehensive report looking at the benefits and challenges of open transit data.

#### Community-maintained lists
- [Vendors Providing GTFS Creation/Maintenance services](https://docs.google.com/spreadsheets/u/1/d/1Gc9mu4BIYC8ORpv2IbbVnT3q8VQ3xkeY7Hz068vT_GQ/pubhtml) - Add new vendors [here](http://goo.gl/forms/YDbPSPmufS).
- [Entities Providing Transportation Software Development Consulting Services](https://docs.google.com/spreadsheets/u/1/d/1n44CNMCK1vt1nyrsdYz-KD_hYxUMNIm6Me69M6ROBIg/pubhtml) - Add new entities [here](http://goo.gl/forms/cc6kcVERuP).

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Luqmaan Dawoodjee](https://github.com/luqmaan) and the [Center for Urban Transportation Research](https://www.cutr.usf.edu/) at the [University of South Florida](http://www.usf.edu/) have waived all copyright and related or neighboring rights to this work.

## About

Originally created by [Luqmaan Dawoodjee](https://github.com/luqmaan), now maintained by the [Center for Urban Transportation Research](https://www.cutr.usf.edu/) at the [University of South Florida](http://www.usf.edu/).

This list is intended as a community resource for informational use only - listing of a project/product does not imply endorsement.



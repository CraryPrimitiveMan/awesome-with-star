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
  - [GTFS Tools](#gtfs-tools)
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
- [pyBikes](https://github.com/eskerda/pybikes) - Software powering [CityBikes](http://api.citybik.es) for worldwide bikeshare system info :star:310

### Agency Tools

Tools for transit agencies.

- [Remix](http://getremix.com/) - A webapp that lets transit agencies easily plan routes.

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
- [Transit-Map](https://github.com/vasile/transit-map) - Web app that animates vehicles (markers) on a map using the public transport timetables to interpolate their positions along the routes (polylines). :star:262
- [Bikeshare Map](http://bikes.oobrien.com/) - Status of all worldwide bikeshare stations
- [Bongo](http://ebongo.org) - Real-time Transit Tracking for Iowa City, Coralville and the University of Iowa. Awesome because it combines three disparate transit systems into one UI.
- [Transitive.js](https://github.com/conveyal/transitive.js) - Creates a customizable web map layer of transit routes using Leaflet or D3. :star:564
- [Brand New Subway](http://jpwright.net/subway/) - An interactive transportation planning game that lets players alter the NYC subway system to their heart's content.
- [CityMapper Webapp](https://citymapper.com/nyc) - Really polished webapp with trip planner and route status for over 30 of cities.
- [Google I/O Transport Tracker](https://github.com/googlemaps/transport-tracker) - Shows shuttle arrival times for Google I/O conference, based on the open-source [transport-tracker project](https://github.com/googlemaps/transport-tracker).  Note: To implement this yourself, you need a [Google Maps APIs Premium Plan license](https://developers.google.com/maps/pricing-and-plans/). :star:221
- [YourStop](http://yourstop.info) - Mobile friendly web app which consumes GTFS feeds and displays both live and scheduled trips for stops. Launched with MBTA, YRT/Viva and Maryland MTA. 
 
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

### GTFS

- [GTFS Spec](https://developers.google.com/transit/gtfs/) - Specification for the General Transit Data Feed, or GTFS.
- [GTFS Best Practices](http://gtfs.org/best-practices/) - Best practices for producers of a GTFS feed.

#### GTFS Libraries

Software that makes it easy to consume GTFS data in a variety of languages.


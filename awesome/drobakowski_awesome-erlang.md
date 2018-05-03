# Information comes from [drobakowski/awesome-erlang](https://github.com/drobakowski/awesome-erlang)
# Awesome Erlang [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Analytics](https://ga-beacon.appspot.com/UA-82766782-1/awesome-erlang?flat&useReferer)](https://github.com/drobakowski/awesome-erlang)
A curated list of amazingly awesome Erlang libraries, resources and shiny thing inspired by [awesome-elixir](https://github.com/h4cc/awesome-elixir).

- [Awesome Erlang](#awesome-Erlang)
    - [Package Management](#package-management)
    - [Release Management](#release-management)
    - [Configuration Management](#configuration-management)
    - [Codebase Maintenance](#codebase-maintenance)
    - [Web Frameworks](#web-frameworks)
    - [Web Framework Components](#web-framework-components)
    - [HTTP](#http)
    - [Testing](#testing)
    - [Logging](#logging)
    - [Monitoring](#monitoring)
    - [Deployment](#deployment)
    - [Distributed Systems](#distributed-systems)
    - [Code Analysis](#code-analysis)
    - [Build Tools](#build-tools)
    - [Geolocation](#geolocation)
    - [Debugging](#debugging)
    - [Actors](#actors)
    - [Date and Time](#date-and-time)
    - [ORM and Datamapping](#orm-and-datamapping)
    - [Queue](#queue)
    - [Authentication](#authentication)
    - [Text and Numbers](#text-and-numbers)
    - [REST and API](#rest-and-api)
    - [Caching](#caching)
    - [Third Party APIs](#third-party-apis)
    - [Networking](#networking)
    - [Internet of Things](#internet-of-things)
    - [Algorithms and Datastructures](#algorithms-and-datastructures)
    - [Translations and Internationalizations](#translations-and-internationalizations)
    - [Miscellaneous](#miscellaneous)
- [Resources](#resources)
    - [Websites](#websites)
    - [Books](#books)
    - [Web Reading](#web-reading)
    - [Erlang Reading](#Erlang-reading)
    - [Screencasts](#screencasts)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Package Management
*Libraries and tools for package and dependency management.*

* [hex.pm](https://hex.pm/) - A package manager for the Erlang ecosystem.

## Release Management
*Libraries and tools for release management.*

* [relx](https://github.com/erlware/relx) - A release assembler for Erlang. :star:501

## Configuration Management
*Libraries and tools related to configuration management.*

* [stillir](https://github.com/heroku/stillir) - Cache environment variables as Erlang app variables. :star:37

## Codebase Maintenance
*Libraries and tools to maintain a clean codebase.*

* [elvis](https://github.com/inaka/elvis) - Erlang Style Reviewer. :star:298

## Web Frameworks
*Web development frameworks.*

* [Axiom](https://github.com/tsujigiri/axiom) - A micro-framework, inspired by Ruby's [Sinatra](https://github.com/sinatra/sinatra). :star:244
* [ChicagoBoss](https://github.com/ChicagoBoss/ChicagoBoss) - A server framework inspired by Rails and written in Erlang. :star:1715
* [cowboy](https://github.com/ninenines/cowboy) - A simple HTTP server. :star:4914
* [Giallo](https://github.com/kivra/giallo) - A small and flexible web framework on top of [Cowboy](https://github.com/ninenines/cowboy). :star:62
* [MochiWeb](https://github.com/mochi/mochiweb) - An Erlang library for building lightweight HTTP servers. :star:1599
* [N2O](https://github.com/synrc/n2o) - WebSocket Application Server. :star:1098
* [Nitrogen](https://github.com/nitrogen/nitrogen) - Framework to build web applications (including front-end) in pure Erlang. :star:839
* [Zotonic](https://github.com/zotonic/zotonic) - High speed, real-time web framework and content management system. :star:557

## Web Framework Components
*Standalone component from web development frameworks.*

* [cb_admin](https://github.com/ChicagoBoss/cb_admin) - An admin interface for Chicago Boss. :star:72
* [cb_websocket_controller](https://github.com/dkuhlman/cb_websocket_controller) - A template for implementing a Websocket controller for ChicagoBoss. :star:7
* [giallo_session](https://github.com/kivra/giallo_session) - A session management library for the Giallo web framework. :star:10
* [simple_bridge](https://github.com/nitrogen/simple_bridge) - An abstraction layer providing a unified interface to popular Erlang web servers (Cowboy, Inets, Mochiweb, Webmachine, and Yaws). :star:92

## HTTP
*Libraries for working with HTTP and scraping websites.*

* [bullet](https://github.com/ninenines/bullet) - Simple, reliable, efficient streaming for Cowboy. :star:291
* [gun](https://github.com/ninenines/gun) - Erlang HTTP client with support for HTTP/1.1, SPDY and Websocket. :star:423
* [hackney](https://github.com/benoitc/hackney) - Simple HTTP client in Erlang. :star:821
* [ibrowse](https://github.com/cmullaparthi/ibrowse) - Erlang HTTP client. :star:474
* [lhttpc](https://github.com/esl/lhttpc) - A lightweight HTTP/1.1 client implemented in Erlang. :star:121
* [shotgun](https://github.com/inaka/shotgun) - For the times you need more than just a gun. :star:119

## Testing
*Libraries for testing codebases and generating test data.*

* [PropEr](https://github.com/manopapad/proper) - A QuickCheck-inspired property-based testing tool for Erlang. :star:572
* [tracerl](https://github.com/esl/tracerl) - Dynamic tracing tests and utilities for Erlang/OTP :star:16

## Logging
*Libraries for generating and working with log files.*

* [lager](https://github.com/basho/lager) - A logging framework for Erlang/OTP. :star:24
* [lager_amqp_backend](https://github.com/jbrisbin/lager_amqp_backend) - AMQP RabbitMQ Lager backend. :star:33
* [lager_hipchat](https://github.com/synlay/lager_hipchat) - HipChat backend for lager. :star:6
* [lager_loggly](https://github.com/kivra/lager_loggly) - Loggly backend for lager. :star:16
* [lager_smtp](https://github.com/blinkov/lager_smtp) - SMTP backend for lager. :star:13
* [logplex](https://github.com/heroku/logplex) - Heroku log router. :star:835

## Monitoring
*Libraries for gathering metrics and monitoring.*

* [entop](https://github.com/mazenharake/entop) - A top-like Erlang node monitoring tool. :star:245
* [eper](https://github.com/massemanet/eper) - A loose collection of Erlang Performance related tools. :star:422
* [Exometer](https://github.com/Feuerlabs/exometer) - An Erlang instrumentation package. :star:441
* [folsom](https://github.com/boundary/folsom) - An Erlang based metrics system inspired by Coda Hale's [metrics](https://github.com/codahale/metrics). :star:554
* [statsderl](https://github.com/lpgauth/statsderl) - A statsd Erlang client. :star:82
* [vmstats](https://github.com/ferd/vmstats) - Tiny Erlang app that works in conjunction with statsderl in order to generate information on the Erlang VM for graphite logs. :star:180

## Deployment
*Libraries and tools related to deployment of Erlang/OTP applications.*

* [docker-erlang](https://github.com/synlay/docker-erlang) - Basic Docker Container Images for Erlang/OTP. :star:4

## Distributed Systems
*Tools for stress/load testing, latency issues, etc. across microservices.*

* [Typhoon](https://github.com/zalando/typhoon) - Stress and load testing tool for distributed systems that simulates traffic from a test cluster toward a system-under-test (SUT) and visualizes related latencies.

## Code Analysis
*Libraries and tools for analysing, parsing and manipulation codebases.*

* [Concuerror](https://github.com/parapluu/Concuerror) - Concuerror is a systematic testing tool for concurrent Erlang programs. :star:153
* [eflame](https://github.com/proger/eflame) - A Flame Graph profiler for Erlang. :star:262

## Build Tools
*Project build and automation tools.*

* [rebar](https://github.com/rebar/rebar) - Erlang build tool that makes it easy to compile and test Erlang applications, port drivers and releases. :star:924
* [rebar3](https://github.com/rebar/rebar3) - A build tool for Erlang which can manage Erlang packages from [Hex.pm](https://hex.pm/). See more at [rebar3.org](https://www.rebar3.org/)
* [sync](https://github.com/rustyio/sync) - On-the-fly recompiling for Erlang. :star:632

## Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [erl-rstar](https://github.com/armon/erl-rstar) - An Erlang implementation of the R*-tree spacial data structure. :star:39
* [GeoCouch](https://github.com/couchbase/geocouch) - A spatial extension for Couchbase and Apache CouchDB. :star:477
* [Teles](https://github.com/armon/teles) - An Erlang network service for manipulating geographic data. :star:12

## Debugging
*Libraries and tools for debugging code and applications.*

* [tx](https://github.com/kvakvs/tx) - An HTML Erlang term viewer, starts own webserver and displays any term you give it from your Erlang node. :star:64

## Actors
*Libraries and tools for working with actors and such.*

* [poolboy](https://github.com/devinus/poolboy) - A hunky Erlang worker pool factory. :star:1035

## Date and Time
*Libraries for working with dates and times.*

* [erlang_localtime](https://github.com/dmitryme/erlang_localtime) - Erlang library for conversion from one local time to another. :star:40
* [qdate](https://github.com/choptastic/qdate) - Erlang date, time, and timezone management: formatting, conversion, and date arithmetic. :star:201

## ORM and Datamapping
*Libraries that implement object-relational mapping or datamapping techniques.*

* [boss_db](https://github.com/ErlyORM/boss_db) - A sharded, caching, pooling, evented ORM for Erlang. :star:253
* [epgsql](https://github.com/epgsql/epgsql) - PostgreSQL Driver for Erlang. :star:232
* [mysql-otp](https://github.com/mysql-otp/mysql-otp) - MySQL/OTP – MySQL driver for Erlang/OTP. :star:235
* [pgsql_migration](https://github.com/artemeff/pgsql_migration) – PostgreSQL migrations for Erlang.

## Queue
*Libraries for working with event and task queues.*

* [dq](https://github.com/darach/dq) - Distributed Fault Tolerant Queue library. :star:26
* [ebqueue](https://github.com/rgrinberg/ebqueue) - Tiny simple blocking queue in erlang. :star:5
* [pqueue](https://github.com/okeuday/pqueue) - Erlang Priority Queues. :star:101
* [tinymq](https://github.com/ChicagoBoss/tinymq) - A diminutive, in-memory message queue for Erlang. :star:100

## Authentication
*Libraries for implementing authentications schemes.*

* [oauth2](https://github.com/kivra/oauth2) - Erlang Oauth2 implementation. :star:195

## Text and Numbers
*Libraries for parsing and manipulating text and numbers.*

* [eql](https://github.com/artemeff/eql) - Erlang with SQL or not. :star:74
* [jiffy](https://github.com/davisp/jiffy) - JSON NIFs for Erlang. :star:654
* [jsx](https://github.com/talentdeficit/jsx) - An erlang application for consuming, producing and manipulating json. :star:563
* [miffy](https://github.com/expelledboy/miffy) - Jiffy wrapper which returns pretty maps. :star:2
* [qsp](https://github.com/artemeff/qsp) - Enhanced query string parser for Erlang. :star:15
* [rec2json](https://github.com/lordnull/rec2json) - Generate JSON encoder/decoder from record specs. :star:33

## REST and API
*Libraries and web tools for developing REST-ful APIs.*

* [leptus](https://github.com/s1n4/leptus) - Leptus is an Erlang REST framework that runs on top of cowboy. :star:256

## Caching
*Libraries for caching data.*

* [cache](https://github.com/fogfish/cache) - In-memory Segmented Cache :star:97

## Third Party APIs
*Libraries for accessing third party APIs.*

* [restc](https://github.com/kivra/restclient) - An Erlang REST client :star:67
* [oauth2c](https://github.com/kivra/oauth2_client) - An Erlang oAuth 2 client (uses restc)

## Networking
*Libraries and tools for using network related stuff.*

* [barrel_tcp](https://github.com/benoitc-attic/barrel_tcp) - barrel_tcp is a generic TCP acceptor pool with low latency in Erlang. :star:84
* [gen_rpc](https://github.com/priestjim/gen_rpc) - A scalable RPC library for Erlang-VM based languages. :star:154
* [gen_tcp_server](https://github.com/rpt/gen_tcp_server) - A library that takes the concept of gen_server and introduces the same mechanics for operating a TCP server. :star:9
* [gossiperl](https://github.com/gossiperl/gossiperl) - Language agnostic gossip middleware and message bus written in Erlang. :star:36
* [nat_upnp](https://github.com/benoitc/nat_upnp) - Erlang library to map your internal port to an external using UNP IGD. :star:37
* [ranch](https://github.com/ninenines/ranch) - Socket acceptor pool for TCP protocols. :star:789

## Internet of Things
*Libraries and tools for interacting with the physical world.*
* [lemma_erlang](https://github.com/noam-io/lemma_erlang) - A lemma for IDEO's Noam internet-of-things prototyping platform. :star:3

## Algorithms and Datastructures
*Libraries and implementations of algorithms and datastructures.*

* [datum](https://github.com/fogfish/datum) - A pure functional and generic programming for Erlang :star:61
* [erlando](https://github.com/travelping/erlando) - A set of syntax extensions like currying and monads for Erlang. :star:2
* [statebox](https://github.com/mochi/statebox) - Erlang state "monad" with merge/conflict-resolution capabilities. :star:234
* [riak_dt](https://github.com/basho/riak_dt) - Erlang library of state based CRDTs. :star:237

## Translations and Internationalizations
*Libraries providing translations or internationalizations.*

## Miscellaneous
*Useful libraries or tools that don't fit in the categories above.*

* [erlang-history](https://github.com/ferd/erlang-history) - Hacks to add shell history to Erlang's shell. :star:477
* [erld](https://github.com/ShoreTel-Inc/erld) - erld is a small program designed to solve the problem of running Erlang programs as a UNIX daemon. :star:193

# Resources
Various resources, such as books, websites and articles, for improving your Erlang development skills and knowledge.

## Websites
*Useful web and Erlang-related websites and newsletters.*

* [Erlang Bookmarks](https://github.com/0xAX/erlang-bookmarks/wiki/Erlang-bookmarks) - All about erlang programming language [powerd by community]. :star:1009
* [Erlang Central](https://erlangcentral.org/) - An awesome collections of erlang resource along with live community chat for discussing and seeking help.
* [Planet Erlang](http://www.planeterlang.com/) - Planet site/RSS feed of blog posts covering topics across the Erlang ecosystem.
* [Spawned Shelter](http://spawnedshelter.com/) - Erlang Spawned Shelter. A collection of the best articles, videos and presentations related to Erlang.

## Books
*Fantastic books and e-books.*

* [Erlang and Elixir for Imperative Programmers](https://leanpub.com/erlangandelixirforimperativeprogrammers) - Introduction to Erlang and Elixir in the context of functional concepts by Wolfgang Loder (2016)
* [Learn You Some Erlang](http://learnyousomeerlang.com/) - Learn you some Erlang - for great good! A very thorough resource covering everything from beginning Erlang programming to large-scale development and deployment.
* [Stuff Goes Bad - ERLANG IN ANGER](http://www.erlang-in-anger.com/) - This book intends to be a little guide about how to be the Erlang medic in a time of war.

## Web Reading
*General web-development-related reading materials.*

## Erlang Reading
*Erlang-releated reading materials.*

* [The Joy of Erlang; Or, How To Ride A Toruk](http://www.evanmiller.org/joy-of-erlang.html) - The Joy of Erlang; Or, How To Ride A Toruk A fast track introduction to Erlang that teaches the language by walking through a few example projects.

## Screencasts
*Cool video tutorials.*

# Contributing
Please see [CONTRIBUTING](https://github.com/drobakowski/awesome-erlang/blob/master/CONTRIBUTING.md) for details.


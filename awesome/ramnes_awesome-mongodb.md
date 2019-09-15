# Information comes from [ramnes/awesome-mongodb](https://github.com/ramnes/awesome-mongodb)
![Awesome MongoDB](logo.png)

# Awesome MongoDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![Build status](https://img.shields.io/travis/ramnes/awesome-mongodb.svg)](https://travis-ci.org/ramnes/awesome-mongodb)

> A curated list of awesome MongoDB resources, libraries, tools and applications

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing. Feel free to improve this list by [contributing](CONTRIBUTING.md)!

## Table of Contents
 - [Resources](#resources)
   - [Documentation](#documentation)
   - [Articles](#articles)
   - [Books](#books)
   - [Talks](#talks)
   - [Tutorials](#tutorials)
   - [More](#more)
 - [Libraries](#libraries)
   - [C](#c)
   - [C++](#c-1)
   - [C#/.NET](#cnet)
   - [Delphi](#delphi)
   - [Elixir](#elixir)
   - [Erlang](#erlang)
   - [Go](#go)
   - [Haskell](#haskell)
   - [Java](#java)
   - [JavaScript](#javascript)
   - [Julia](#julia)
   - [Lisp](#lisp)
   - [Mathematica](#mathematica)
   - [Perl](#perl)
   - [PHP](#php)
   - [Python](#python)
   - [R](#r)
   - [Ruby](#ruby)
   - [Rust](#rust)
   - [Scala](#scala)
 - [Tools](#tools)
   - [Administration](#administration)
   - [Data](#data)
   - [Deployment](#deployment)
   - [Desktop](#desktop)
   - [Development](#development)
   - [Monitoring](#monitoring)
   - [Shell](#shell)
   - [Web](#web)
 - [Applications](#applications)

## Resources
### Documentation
 - [MongoDB introduction](https://docs.mongodb.com/manual/introduction/)
 - [MongoDB documentation](https://docs.mongodb.com/manual/)
 - [MongoDB tutorials](https://docs.mongodb.com/manual/tutorial/)
 - [More MongoDB tutorials (by Studio 3T)](https://studio3t.com/knowledge-base/categories/mongodb-tutorials/)

### Articles

 - [14 Things I Wish I'd Known When Starting with MongoDB (Phil Factor)](https://www.infoq.com/articles/Starting-With-MongoDB/)
 - [A Custom WordPress Dashboard with MongoDB Atlas, Microsoft Azure, & Serverless Functions (Ahmad Awais)](https://ahmadawais.com/wordpress-mongodb-atlas-microsoft-azure-serverless-functions/)
 - [Five Things About Scaling MongoDB (A. Jesse Jiryu Davis, MongoDB Inc.)](https://emptysqua.re/blog/five-things/) - Scale 101
 - [Optimizing MongoDB Compound Indexes (A. Jesse Jiryu Davis, MongoDB Inc.)](https://emptysqua.re/blog/optimizing-mongodb-compound-indexes/) - Everything you need/have to know about indexes
 - [Server Discovery And Monitoring In PyMongo, Perl, And C (A. Jesse Jiryu Davis, MongoDB Inc.) ](https://emptysqua.re/blog/server-discovery-and-monitoring-in-pymongo-perl-and-c/)
 - [Monitoring MongoDB performance metrics (Jean-Mathieu Saponaro, Datadog)](https://www.datadoghq.com/blog/monitoring-mongodb-performance-metrics-wiredtiger/)

### Books
 - [50 Tips and Tricks for MongoDB Developers](http://shop.oreilly.com/product/0636920019893.do) - Advanced MongoDB tips and tricks, given by a MongoDB inc. engineer
 - [Builder Book](https://builderbook.org/book) - Learn how to build a full stack JavaScript web app from scratch
 - [MongoDB Applied Design Patterns (Rick Copeland)](http://shop.oreilly.com/product/0636920027041.do)
 - [The Little MongoDB Book](https://www.openmymind.net/2011/3/28/The-Little-MongoDB-Book/) - Basic introduction

### Talks
 - [MongoDB Schema Design (Tugdual Grall, MongoDB Inc.)](https://www.youtube.com/watch?v=csKBT8zkRf0) [47']
 - [Partial and Fuzzy Matching with MongoDB (John Page, MongoDB Inc.)](https://www.youtube.com/watch?v=hXbLHInH5qU) [35']
 - [Scaling MongoDB on Amazon Web Services (Michael Saffitz, Apptentive)](https://www.youtube.com/watch?v=bkjVhEQocFI) [50']

### Tutorials
 - [Create a TV Show Tracker Using AngularJS, Node.js, and MongoDB](http://sahatyalkabov.com/create-a-tv-show-tracker-using-angularjs-nodejs-and-mongodb/) - Build a REST API using Mongoose to create and retrieve data
 - [Kubernetes examples](https://github.com/kubernetes/examples/tree/master/staging/nodesjs-mongodb) - Deployment tutorial of a basic Node.js and MongoDB web stack on Kubernetes :star:2439
 - [Deploy a Highly-Available MongoDB Replica Set on AWS](https://eladnava.com/deploy-a-highly-available-mongodb-replica-set-on-aws/)

### More
 - [MongoDB source code](https://github.com/mongodb/mongo) :star:16711
 - [MongoDB University](https://university.mongodb.com/) - Certifications and free online courses

## Libraries
### C
 - [mongo-c-driver](https://github.com/mongodb/mongo-c-driver) - Official C driver :star:551

### C++
 - [mongo-cxx-driver](https://github.com/mongodb/mongo-cxx-driver) - Official C++ driver :star:655

### C#/.NET ###
 - [mongo-csharp-driver](https://github.com/mongodb/mongo-csharp-driver) - Official C# driver :star:2235
 - [mongo-queue-csharp](https://github.com/dominionenterprises/mongo-queue-csharp) - C# message queue on top of MongoDB :star:1
 - [MongoDB Messaging](https://github.com/loresoft/MongoDB.Messaging) - Lightweight queue pub/sub processing library :star:45
 - [MongoRepository](https://github.com/RobThree/MongoRepository) - Repository abstraction layer on top of the C# driver :star:269

### Delphi
 - [TMongoWire](https://github.com/stijnsanders/TMongoWire) - Minimal community Delphi driver :star:83

### Elixir
 - [mongodb](https://github.com/ankhers/mongodb) - Community Elixir driver :star:386
 - [mongodb_ecto](https://github.com/ankhers/mongodb_ecto) - Adapter for the Ecto database wrapper :star:301

### Erlang
 - [mongodb-erlang](https://github.com/comtihon/mongodb-erlang) - Community Erlang driver :star:301

### Go
 - [Bongo](https://github.com/go-bongo/bongo) - ODM based on mgo :star:351
 - [mgo](https://github.com/globalsign/mgo) - Community Go driver :star:1672
 - [minquery](https://github.com/icza/minquery) - MongoDB cursor that paginates :star:50
 - [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - Official Go driver :star:3325

### Haskell
 - [mongodb](https://github.com/mongodb-haskell/mongodb/) - Community Haskell driver :star:112

### Java
 - [Jongo](https://github.com/bguerout/jongo) - Query in Java as in Mongo shell :star:549
 - [Hibernate OGM](https://github.com/hibernate/hibernate-ogm) - The power and simplicity of JPA for NoSQL datastores :star:281
 - [mongo-java-driver](https://github.com/mongodb/mongo-java-driver) - Official Java driver :star:2223
 - [mongo-queue-java](https://github.com/gaillard/mongo-queue-java) - Java message queue on top of MongoDB :star:31
 - [mongoFS](https://github.com/dbuschman7/mongoFS) - An enhancement of GridFS to allow for more features and capabilities :star:18
 - [Mongojack](https://github.com/mongojack/mongojack) - Based on Jackson, allows you to easily handle your mongo objects as POJOs :star:220
 - [Morphia](https://github.com/MorphiaOrg/morphia) - Java ODM :star:1419
 - [Morphium](https://github.com/sboesebeck/morphium) - Java ODM and caching layer :star:49
 - [Mungbean](https://github.com/jannehietamaki/mungbean) - Community driver for languages running on the JVM :star:20
 - [Spring Data MongoDB](https://github.com/spring-projects/spring-data-mongodb) - Spring based, object-document support and repositories :star:1055

### JavaScript
 - [Camo](https://github.com/scottwrobinson/camo) - Class-based ES6 ODM for Mongo-like databases :star:487
 - [MEAN.JS](https://github.com/meanjs/mean) - Full stack based on MongoDB, Express, AngularJS, and Node.js :star:4774
 - [MERN (mern-starter)](https://github.com/Hashnode/mern-starter) - Full stack based on MongoDB, Express, React and Node.js :star:5245
 - [Meteor](https://github.com/meteor/meteor) - Real-time/reactive client-server framework based on MongoDB, with lots of features :star:41326
 - [Mongoose](https://github.com/Automattic/mongoose) - Node.js asynchronous ODM :star:19418
 - [CASL Mongoose](https://github.com/stalniy/casl/tree/master/packages/casl-mongoose) - Permissions management library integrated with Mongoose :star:1531
 - [mongration](https://github.com/awapps/mongration) - Node.js migration framework :star:67
 - [Moonridge](https://github.com/capaj/Moonridge) - Framework with live querying on top of Mongoose and socket.io :star:63
 - [node-mongodb-native](https://github.com/mongodb/node-mongodb-native) - Official Node.js driver :star:8127

### Julia
 - [Mongo.jl](https://github.com/Lytol/Mongo.jl) - C driver bindings :star:26

### Lisp
 - [cl-mongo](https://github.com/fons/cl-mongo) - Community Common Lisp interface :star:120
 - [mongo-cl-driver](https://github.com/archimag/mongo-cl-driver) Community Common Lisp driver
 - [mongo-el](https://github.com/m2ym/mongo-el) - Community Emacs Lisp driver :star:42

### Mathematica
 - [MongoDBLink](https://github.com/zbjornson/MongoDBLink) - Community Mathematica driver :star:17

### Perl
 - [mongo-perl-driver](https://github.com/mongodb/mongo-perl-driver) - Official Perl driver :star:198

### PHP
 - [Doctrine MongoDB](https://github.com/doctrine/mongodb) - Wrapper around the native PHP Mongo PECL extension to provide additional functionality :star:415
 - [eloquent-mongodb-repository](https://github.com/LaravelRepository/eloquent-mongodb-repository) - Repository implementation built on top of laravel-mongodb :star:11
 - [laravel-mongodb](https://github.com/jenssegers/laravel-mongodb) - Eloquent model and query builder for Laravel :star:4354
 - [mongodb-repository](https://github.com/PHPRepository/mongodb-repository) - Repository implementation :star:8
 - [PHPMongo ODM](https://github.com/sokil/php-mongo) - ODM based on the PHP Mongo PECL extension :star:209
 - [PHPMongo Migrator](https://github.com/sokil/php-mongo-migrator) - Migration tool based on PHPMongo ODM :star:23
 - [pecl/mongodb](https://github.com/mongodb/mongo-php-driver) - Official PHP driver :star:643
 - [yadm](https://github.com/formapro/yadm) - Fast schemaless ODM :star:88

### Python
 - [Flask-Stupe](https://github.com/numberly/flask-stupe) - Flask extension that adds PyMongo support to Flask :star:29
 - [Mongo-Thingy](https://github.com/numberly/mongo-thingy) - Idiomatic and friendly-yet-powerful ODM (schemaless) :star:29
 - [MongoEngine](https://github.com/MongoEngine/mongoengine) - ODM on top of PyMongo :star:2894
 - [MongoLog](https://github.com/puentesarrin/mongodb-log) - MongoDB logging handler :star:119
 - [Motor](https://github.com/mongodb/motor) - Non-blocking Python driver for Tornado or asyncio :star:1311
 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - Official (and recommended) Python driver :star:2865
 - [minimongo](https://github.com/slacy/minimongo) - A lightweight, schemaless, Pythonic Object-Oriented interface :star:314
 - [scrapy-mongodb](https://github.com/sebdah/scrapy-mongodb) - MongoDB pipeline for Scrapy :star:308
 - [μMongo](https://github.com/Scille/umongo) - Driver-independent (async/sync) ODM based on marshmallow :star:189

### R
 - [mongolite](https://github.com/jeroen/mongolite) - Fast and simple client for R :star:219

### Ruby
 - [awesome_explain](https://github.com/sandboxws/awesome_explain) - A simple global method to explain Mongoid queries :star:2
 - [mongo-ruby-driver](https://github.com/mongodb/mongo-ruby-driver) - Official Ruby driver :star:1373
 - [Mongoid](https://github.com/mongodb/mongoid) - ODM framework :star:3748

### Rust
 - [mongo-rust-driver-prototype](https://github.com/mongodb-labs/mongo-rust-driver-prototype) - Prototype driver for Rust 1.x and MongoDB 3.0.x :star:389

### Scala
 - [mongo-scala-driver](https://github.com/mongodb/mongo-scala-driver) - Official Scala driver :star:272
 - [ReactiveMongo](https://github.com/ReactiveMongo/ReactiveMongo) - Non-blocking Scala driver :star:800
 - [Spark-MongoDB](https://github.com/Stratio/Spark-MongoDB) - Read/write data with Spark SQL :star:301

## Tools
### Administration
 - [mongoctl](https://github.com/mongolab/mongoctl) - Manage MongoDB servers and replica sets using JSON configurations :star:171
 - [MongoDB Smasher](https://github.com/duckie/mongo_smasher) - Generate randomized datasets and benchmark your setup :star:28
 - [mongodb-tools](https://github.com/jwilder/mongodb-tools) - Three neat Python scripts to work with collections and indexes :star:278
 - [mtools](https://github.com/rueckstiess/mtools) - Collection of scripts to set up test environments and visualize log files :star:1394
 - [nginx-gridfs](https://github.com/mdirolf/nginx-gridfs) - Nginx module for serving files from GridFS :star:800
 - [nginx-mongodb-rest](https://github.com/minhajuddin/nginx-mongodb-rest) - REST client written as an Nginx module :star:31
 - [pt-mongodb-query-digest](https://www.percona.com/doc/percona-toolkit/LATEST/pt-mongodb-query-digest.html) - Aggregates queries from query profiler and reports query usage statistics
 - [pt-mongodb-summary](https://www.percona.com/doc/percona-toolkit/LATEST/pt-mongodb-summary.html) - MongoDB cluster status overview command line tool

Services:

 - [Compose](https://www.compose.com/) - IBM DBaaS offer (has other database types too)
 - [mLab](https://mlab.com/) - Fully managed DBaaS (formerly MongoLab)
 - [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) - MongoDB Inc. DBaaS offer (works with AWS, Azure, or GCP)
 - [MongoDB Cloud Manager](https://www.mongodb.com/cloud/cloud-manager) - MongoDB Inc. databases management offer
 - [ObjectRocket](https://www.objectrocket.com/) - Rackspace DBaaS offer (has other database types too)
 - [Scalegrid](https://scalegrid.io) - Fully managed DBaaS (with option to bring your own Azure/AWS account)

### Data
 - [mongo_fdw](https://github.com/EnterpriseDB/mongo_fdw) - PostgreSQL foreign data wrapper :star:177
 - [mongo-hadoop](https://github.com/mongodb/mongo-hadoop) - Hadoop connector :star:1453
 - [Mongolastic](https://github.com/ozlerhakan/mongolastic) - MongoDB to Elasticsearch (and vice-versa) migration tool :star:114
 - [MongoMultiMaster](https://github.com/rick446/mmm) - Multi-master replication :star:60
 - [MoSQL](https://github.com/stripe/mosql) - MongoDB to PostgreSQL streaming replication :star:1539

### Deployment
 - [ansible-role-mongodb](https://github.com/UnderGreen/ansible-role-mongodb) - Ansible role :star:212
 - [chef-mongodb](https://github.com/edelight/chef-mongodb) - Chef cookbook :star:375
 - [Dockerfile](https://github.com/dockerfile/mongodb) :star:272
 - [Helm Chart](https://github.com/helm/charts/tree/master/stable/mongodb) :star:9985
 - [puppet-mongodb](https://github.com/voxpupuli/puppet-mongodb) - Puppet module (formerly puppetlabs-mongodb) :star:88

### Desktop
 - [dbKoda](https://www.dbkoda.com) - Cross-platform and open-source IDE
 - [MongoHub](https://github.com/jeromelebel/MongoHub-Mac) - Mac native client :star:2439
 - [Mongotron](http://mongotron.io/) - Cross-platform and open-source client built with Electron
 - [NoSQLBooster](https://nosqlbooster.com) - Feature-rich but easy-to-use cross-platform IDE (formerly MongoBooster)
 - [Nosqlclient](https://github.com/nosqlclient/nosqlclient) - Cross-platform, self hosted and easy to use management tool (formerly Mongoclient) :star:2962
 - [Robo 3T](https://github.com/Studio3T/robomongo) - Free, native and cross-platform shell-centric GUI (formerly Robomongo) :star:7611
 - [Studio 3T](https://studio3t.com/) - Cross-platform GUI, stable and powerful (formerly MongoChef)

### Development
 - [DB — AI Playground](https://play.db-ai.co) - Online playground to write, debug and share aggregations and queries
 - [mgodatagen](https://github.com/feliixx/mgodatagen) - Random data generator :star:87
 - [Mongo Playground](https://mongoplayground.net) - Online query playground
 - [Mongo Seeding](https://github.com/pkosiec/mongo-seeding) - Node.js library, CLI and Docker image for populating databases using JS and JSON files :star:145
 - [Mongoeye](https://github.com/mongoeye/mongoeye) - Schema and data analyzer: explore data in your collections :star:82
 - [Variety](https://github.com/variety/variety) - Schema analyzer: see what fields are in your collection and what's their content :star:1370

Services:

 - [MongoDB Stitch](https://www.mongodb.com/cloud/stitch) - MongoDB Inc. serverless platform offer

### Monitoring
 - [check_mongodb](https://github.com/dalenys/check_mongodb) - Nagios plugin (in Bash) :star:16
 - [mongo-monitor](https://github.com/dwmkerr/mongo-monitor) - Simple monitoring CLI :star:52
 - [mongo-munin](https://github.com/erh/mongo-munin) - Collection of Munin plugins :star:148
 - [Mongoop](https://github.com/Lujeni/mongoop) - Long operations monitoring and alerting :star:36
 - [mongomon](https://github.com/pcdummy/mongomon) - More Munin plugins :star:24
 - [Motop](https://github.com/tart/motop) - MongoDB top clone :star:64
 - [mtop](https://github.com/beaufour/mtop) - Another top clone :star:49
 - [nagios-plugin-mongodb](https://github.com/mzupan/nagios-plugin-mongodb) - Nagios plugin (in Python) :star:339
 - [Percona Monitoring and Management](https://www.percona.com/software/database-tools/percona-monitoring-and-management) - Free and open-source platform for managing and monitoring databases performances

Services:

 - [Datadog](https://www.datadoghq.com/blog/monitor-mongodb-performance-with-datadog/) - SaaS-based monitoring
 - [VividCortex](https://www.vividcortex.com) - SaaS-based query performance analytics and monitoring

### Shell
 - [mongo-hacker](https://github.com/TylerBrock/mongo-hacker) - MongoDB shell enhancements :star:1628

### Web
 - [adminMongo](https://github.com/mrvautin/adminMongo) - Web-based user interface to handle connections and databases needs :star:3033
 - [mongo-express](https://github.com/mongo-express/mongo-express) - Web-based admin interface built with Express :star:3369
 - [mongoadmin](https://github.com/thomasst/mongoadmin) - Admin interface built with Django :star:256
 - [Mongoku](https://github.com/huggingface/Mongoku) - MongoDB client for the web :star:694
 - [mongri](https://github.com/dongri/mongri) - Web-based user interface written in JavaScript :star:70
 - [Rockmongo](https://github.com/iwind/rockmongo) - PHPMyAdmin for MongoDB, sort of :star:948

Services:

 - [HumongouS.io](https://www.humongous.io) - Easy online GUI and data-visualization dashboards
 - [MongoDB Compass](https://www.mongodb.com/products/compass) - MongoDB Inc. online GUI and data-visualization platform (has a community version)

## Applications

Those open-source applications have MongoDB somewhere in their stack:

 - [Builder Book App](https://github.com/builderbook/builderbook) - Web app to publish books or documentation built with React and Express :star:1482
 - [CodeCombat](https://github.com/codecombat/codecombat) - Multiplayer programming game for learning how to code :star:6875
 - [Countly](https://github.com/countly/countly-server) - Mobile & web analytics and marketing platform built with Node.js :star:4150
 - [GrandNode](https://github.com/grandnode/grandnode) - Multi-platform e-commerce shopping cart built with ASP.NET :star:806
 - [Leanote](https://github.com/leanote/leanote) - Evernote clone built with Go :star:8704
 - [NodeBB](https://github.com/NodeBB/NodeBB) - Node.js based forum software ("built for the modern web") :star:10413
 - [Reaction](https://github.com/reactioncommerce/reaction) - Event-driven, real-time commerce platform built with ES6 :star:9233
 - [SaaS Boilerplate](https://github.com/async-labs/saas) - Boilerplate for SaaS products, built with TypeScript, React and Express :star:1115
 - [uptime](https://github.com/fzaninotto/uptime) - Remote monitoring application built with Node.js and Bootstrap :star:3530

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Guillaume Gelin](https://github.com/ramnes) has waived all copyright and related or neighboring rights to this work.


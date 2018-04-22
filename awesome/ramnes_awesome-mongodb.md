# Information comes from [ramnes/awesome-mongodb](https://github.com/ramnes/awesome-mongodb)
![Awesome MongoDB](logo.png)

# Awesome MongoDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![Build status](https://img.shields.io/travis/ramnes/awesome-mongodb.svg)](https://travis-ci.org/ramnes/awesome-mongodb)
[![Issue closure](https://img.shields.io/issuestats/i/github/ramnes/awesome-mongodb.svg)](http://issuestats.com/github/ramnes/awesome-mongodb)
[![Pull closure](https://img.shields.io/issuestats/p/github/ramnes/awesome-mongodb.svg)](http://issuestats.com/github/ramnes/awesome-mongodb)

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
   - [Big Data](#big-data)
   - [Deployment](#deployment)
   - [Desktop](#desktop)
   - [Monitoring](#monitoring)
   - [Shell](#shell)
   - [Web](#web)
 - [Applications](#applications)

## Resources
### Documentation
 - [MongoDB introduction](https://docs.mongodb.com/manual/introduction/)
 - [MongoDB documentation](https://docs.mongodb.com/manual/)
 - [MongoDB tutorials](https://docs.mongodb.com/manual/tutorial/)

### Articles
 - [Five Things About Scaling MongoDB (A. Jesse Jiryu Davis, MongoDB Inc.)](https://emptysqua.re/blog/five-things/) - Scale 101
 - [Optimizing MongoDB Compound Indexes (A. Jesse Jiryu Davis, MongoDB Inc.)](https://emptysqua.re/blog/optimizing-mongodb-compound-indexes/) - Everything you need/have to know about indexes
 - [Server Discovery And Monitoring In PyMongo, Perl, And C (A. Jesse Jiryu Davis, MongoDB Inc.) ](https://emptysqua.re/blog/server-discovery-and-monitoring-in-pymongo-perl-and-c/)
 - [Monitoring MongoDB performance metrics (Jean-Mathieu Saponaro, Datadog)](https://www.datadoghq.com/blog/monitoring-mongodb-performance-metrics-wiredtiger/)

### Books
 - [MongoDB Applied Design Patterns (Rick Copeland)](http://shop.oreilly.com/product/0636920027041.do)
 - [The Little MongoDB Book](http://openmymind.net/2011/3/28/The-Little-MongoDB-Book/) - Basic introduction to MongoDB

### Talks
 - [MongoDB Schema Design (Tugdual Grall, MongoDB Inc.)](https://www.youtube.com/watch?v=csKBT8zkRf0) [47']
 - [Partial and Fuzzy Matching with MongoDB (John Page, MongoDB Inc.)](https://www.youtube.com/watch?v=hXbLHInH5qU) [35']
 - [Scaling MongoDB on Amazon Web Services (Michael Saffitz, Apptentive)](https://www.youtube.com/watch?v=bkjVhEQocFI) [50']

### Tutorials
 - [Create a TV Show Tracker Using AngularJS, Node.js, and MongoDB](http://sahatyalkabov.com/create-a-tv-show-tracker-using-angularjs-nodejs-and-mongodb/) - Build a REST API using Mongoose to create and retrieve data from MongoDB
 - [Kubernetes examples](https://github.com/kubernetes/kubernetes/tree/master/examples/nodesjs-mongodb) - Deployment tutorial of a basic Node.js and MongoDB web stack on Kubernetes

### More
 - [MongoDB source code](https://github.com/mongodb/mongo) :star:13559
 - [MongoDB University](https://university.mongodb.com/) - Certifications and free online courses
 - [MongoDB Cloud Manager](https://www.mongodb.com/cloud/) - MongoDB Inc. cloud offer
 - [mLab](https://mlab.com/) - Fully managed MongoDB-as-a-Service (formerly MongoLab)
 - [Scalegrid](https://scalegrid.io) - Fully managed MongoDB-as-a-Service (with option to bring your own Azure/AWS account)

## Libraries
### C
 - [mongo-c-driver](https://github.com/mongodb/mongo-c-driver) - Official C driver :star:393

### C++
 - [mongo-cxx-driver](https://github.com/mongodb/mongo-cxx-driver) - Official C++ driver :star:455

### C#/.NET ###
 - [mongo-csharp-driver](https://github.com/mongodb/mongo-csharp-driver) - Official C# driver :star:1838
 - [mongo-queue-csharp](https://github.com/dominionenterprises/mongo-queue-csharp) - C# message queue backed by MongoDB
 - [MongoDB Messaging](https://github.com/loresoft/MongoDB.Messaging) - Lightweight queue pub/sub processing library :star:40
 - [MongoRepository](https://github.com/RobThree/MongoRepository) - Repository abstraction layer on top of the C# driver :star:222

### Delphi
 - [TMongoWire](https://github.com/stijnsanders/TMongoWire) - Minimal community Delphi driver :star:74

### Elixir
 - [mongodb](https://github.com/ankhers/mongodb) - Community Elixir driver :star:260
 - [mongodb_ecto](https://github.com/ankhers/mongodb_ecto) - Adapter for the Ecto database wrapper :star:258

### Erlang
 - [mongodb-erlang](https://github.com/comtihon/mongodb-erlang) - Community Erlang driver :star:264

### Go
 - [mgo](https://github.com/go-mgo/mgo) - Community Go driver :star:2043

### Haskell
 - [mongodb](https://github.com/mongodb-haskell/mongodb/) - Community Haskell driver

### Java
 - [Jongo](https://github.com/bguerout/jongo) - Query in Java as in Mongo shell :star:494
 - [Hibernate OGM](https://github.com/hibernate/hibernate-ogm) - The power and simplicity of JPA for NoSQL datastores :star:259
 - [mongo-java-driver](https://github.com/mongodb/mongo-java-driver) - Official Java driver :star:1963
 - [mongo-queue-java](https://github.com/gaillard/mongo-queue-java) - Java message queue backed by MongoDB :star:28
 - [mongoFS](https://github.com/dbuschman7/mongoFS) - An enhancement of MongoDB's GridFS to allow for more features and capabilities :star:18
 - [Mongojack](https://github.com/mongojack/mongojack) - Based on Jackson, allows you to easily handle your mongo objects as POJOs :star:198
 - [Morphia](https://github.com/mongodb/morphia) - Official Java ODM :star:1263
 - [Morphium](https://github.com/sboesebeck/morphium) - Java ODM and caching layer :star:45
 - [Mungbean](https://github.com/jannehietamaki/mungbean) - Community driver for languages running on the JVM :star:20
 - [Spring Data MongoDB](https://github.com/spring-projects/spring-data-mongodb) - Spring based, object-document support and repositories for MongoDB :star:846

### JavaScript
 - [Camo](https://github.com/scottwrobinson/camo) - Class-based ES6 ODM for Mongo-like databases :star:415
 - [MEAN.JS](https://github.com/meanjs/mean) - Full-Stack based on MongoDB, Express, AngularJS, and Node.js :star:4549
 - [MERN (mern-starter)](https://github.com/Hashnode/mern-starter) - Full-Stack based on MongoDB, Express, React and Node.js :star:4603
 - [Meteor](https://github.com/meteor/meteor) - Real-time/reactive client-server framework, based on MongoDB, with lots of features :star:39634
 - [Mongoose](https://github.com/Automattic/mongoose) - Node.js asynchronous ODM :star:15486
 - [mongration](https://github.com/awapps/mongration) - Node.js migration framework :star:52
 - [Moonridge](https://github.com/capaj/Moonridge) - Framework with live querying on top of Mongoose and socket.io :star:57
 - [node-mongodb-native](https://github.com/mongodb/node-mongodb-native) - Official Node.js driver :star:6802

### Julia
 - [Mongo.jl](https://github.com/Lytol/Mongo.jl) - Bindings on MongoDB official C driver :star:27

### Lisp
 - [cl-mongo](https://github.com/fons/cl-mongo) - Community Common Lisp interface :star:114
 - [mongo-cl-driver](https://github.com/archimag/mongo-cl-driver) Community Common Lisp driver
 - [mongo-el](https://github.com/m2ym/mongo-el) - Community Emacs Lisp driver :star:42

### Mathematica
 - [MongoDBLink](https://github.com/zbjornson/MongoDBLink) - Community Mathematica driver :star:15

### Perl
 - [mongo-perl-driver](https://github.com/mongodb/mongo-perl-driver) - Official Perl driver :star:190

### PHP
 - [Doctrine MongoDB](https://github.com/doctrine/mongodb) - Wrapper around the native PHP Mongo PECL extension to provide additional functionality :star:343
 - [eloquent-mongodb-repository](https://github.com/LaravelRepository/eloquent-mongodb-repository) - Repository implementation built on top of laravel-mongodb :star:11
 - [laravel-mongodb](https://github.com/jenssegers/laravel-mongodb) - Eloquent model and query builder for Laravel :star:3284
 - [mongodb-repository](https://github.com/PHPRepository/mongodb-repository) - Repository implementation :star:6
 - [pecl/mongodb](https://github.com/mongodb/mongo-php-driver) - Official PHP driver :star:492

### Python
 - [Flask-Stupe](https://github.com/numberly/flask-stupe) - Flask extension that adds PyMongo support to Flask :star:14
 - [MongoEngine](https://github.com/MongoEngine/mongoengine) - Python ODM on top of PyMongo :star:2210
 - [MongoLog](https://github.com/puentesarrin/mongodb-log) - MongoDB logging handler :star:107
 - [Mongo-Thingy](https://github.com/numberly/mongo-thingy) - The most Pythonic and friendly-yet-powerful way to use MongoDB :star:18
 - [Motor](https://github.com/mongodb/motor) - Non-blocking Python driver for Tornado or asyncio :star:951
 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - Official (and recommended) Python driver :star:2324
 - [minimongo](https://github.com/slacy/minimongo) - A lightweight, schemaless, Pythonic Object-Oriented interface :star:303
 - [scrapy-mongodb](https://github.com/sebdah/scrapy-mongodb) - MongoDB pipeline for Scrapy :star:253
 - [μMongo](https://github.com/Scille/umongo) - Driver-independent (async/sync) ODM based on marshmallow :star:92

### R
 - [mongolite](https://github.com/jeroen/mongolite) - Fast and Simple MongoDB Client for R :star:164

### Ruby
 - [mongo-ruby-driver](https://github.com/mongodb/mongo-ruby-driver) - Official Ruby driver :star:1337
 - [Mongoid](https://github.com/mongodb/mongoid) - Ruby ODM framework :star:3603

### Rust
 - [mongo-rust-driver-prototype](https://github.com/mongodb-labs/mongo-rust-driver-prototype) - Prototype driver written for Rust 1.x and MongoDB 3.0.x :star:239

### Scala
 - [mongo-scala-driver](https://github.com/mongodb/mongo-scala-driver) - Official Scala driver :star:204
 - [ReactiveMongo](https://github.com/ReactiveMongo/ReactiveMongo) - Non-blocking Scala driver :star:754
 - [Spark-MongoDB](https://github.com/Stratio/Spark-MongoDB) - Read/write data with Spark SQL :star:295

## Tools
### Administration
 - [mgodatagen](https://github.com/feliixx/mgodatagen) - Random data generator for MongoDB :star:20
 - [mongo_fdw](https://github.com/EnterpriseDB/mongo_fdw) - PostgreSQL foreign data wrapper for MongoDB :star:130
 - [mongoctl](https://github.com/mongolab/mongoctl) - Manage MongoDB servers and replica sets using JSON configurations :star:167
 - [MongoDB Smasher](https://github.com/duckie/mongo_smasher) - Generate randomized datasets and benchmark your MongoDB setup :star:19
 - [mongodb-tools](https://github.com/jwilder/mongodb-tools) - Three neat Python scripts to work with collections and indexes :star:250
 - [Mongoeye](https://github.com/mongoeye/mongoeye) - Schema and data analyzer: explore data in your collections :star:23
 - [Mongolastic](https://github.com/ozlerhakan/mongolastic) - A dataset migration tool from MongoDB to Elasticsearch and vice versa :star:80
 - [MongoMultiMaster](https://github.com/rick446/mmm) - Multi-Master MongoDB replication :star:54
 - [MoSQL](https://github.com/stripe/mosql) - MongoDB to PostgreSQL streaming replication :star:1448
 - [mtools](https://github.com/rueckstiess/mtools) - Collection of scripts to set up MongoDB test environments and parse and visualize MongoDB log files :star:1088
 - [nginx-gridfs](https://github.com/mdirolf/nginx-gridfs) - Nginx module for serving files from MongoDB's GridFS :star:767
 - [nginx-mongodb-rest](https://github.com/minhajuddin/nginx-mongodb-rest) - MongoDB REST client written as an Nginx module :star:31
 - [pt-mongodb-query-digest](https://www.percona.com/doc/percona-toolkit/LATEST/pt-mongodb-query-digest.html) - Aggregates queries from query profiler and reports query usage statistics
 - [pt-mongodb-summary](https://www.percona.com/doc/percona-toolkit/LATEST/pt-mongodb-summary.html) - MongoDB cluster status overview command line tool
 - [Variety](https://github.com/variety/variety) - Schema analyzer: see what fields are in your collection and what's their content :star:1141

### Big Data
 - [mongo-hadoop](https://github.com/mongodb/mongo-hadoop) - MongoDB connector for Hadoop :star:1340

### Deployment
 - [ansible-role-mongodb](https://github.com/UnderGreen/ansible-role-mongodb) - Ansible role :star:143
 - [chef-mongodb](https://github.com/edelight/chef-mongodb) - Chef cookbook :star:380
 - [Dockerfile](https://github.com/dockerfile/mongodb) :star:246
 - [Helm Chart](https://github.com/kubernetes/charts/tree/master/stable/mongodb) - Bootstraps a MongoDB deployment on a Kubernetes cluster using the Helm package manager.
 - [puppet-mongodb](https://github.com/voxpupuli/puppet-mongodb) - Puppet module (formerly puppetlabs-mongodb)

### Desktop
 - [MongoHub](https://github.com/jeromelebel/MongoHub-Mac) - Mac native client :star:2298
 - [Mongotron](http://mongotron.io/) - Cross-platform, open-source MongoDB client built with Electron
 - [NoSQLBooster](https://nosqlbooster.com) - Feature-rich but easy-to-use cross-platform MongoDB manager (formerly MongoBooster)
 - [Robo 3T](https://github.com/Studio3T/robomongo) - Free, native and cross-platform MongoDB manager (formerly Robomongo)
 - [Studio 3T](https://studio3t.com/) - Cross-platform MongoDB manager, stable and powerful (formerly MongoChef)

### Monitoring
 - [check_mongodb](https://github.com/dalenys/check_mongodb) - Nagios plugin (in Bash)
 - [Datadog](https://www.datadoghq.com/blog/monitor-mongodb-performance-with-datadog/) - SaaS-based MongoDB monitoring
 - [Mongoop](https://github.com/Lujeni/mongoop) - Long operations monitoring and alerting :star:33
 - [Motop](https://github.com/tart/motop) - MongoDB top clone :star:61
 - [mtop](https://github.com/beaufour/mtop) - Another top clone :star:50
 - [mongo-munin](https://github.com/erh/mongo-munin) - Collection of Munin plugins :star:148
 - [mongomon](https://github.com/pcdummy/mongomon) - More Munin plugins :star:26
 - [nagios-plugin-mongodb](https://github.com/mzupan/nagios-plugin-mongodb) - Nagios plugin (in Python)
 - [PMM](https://www.percona.com/software/database-tools/percona-monitoring-and-management) - Percona Monitoring and Management, a free and open-source platform for managing and monitoring MongoDB performance

### Shell
 - [mongo-hacker](https://github.com/TylerBrock/mongo-hacker) - MongoDB shell enhancements :star:1408

### Web
 - [adminMongo](https://github.com/mrvautin/adminMongo) - Web-based user interface to handle connections and databases needs :star:1454
 - [Compass](https://www.mongodb.com/products/compass) - MongoDB Inc. commercial online GUI and data-visualization platform
 - [HumongouS.io](https://www.humongous.io) - Easy online GUI and data-visualization dashboards
 - [mongo-express](https://github.com/mongo-express/mongo-express) - Web-based admin interface written with Node.js, Express and Bootstrap3 :star:2631
 - [mongoadmin](https://github.com/thomasst/mongoadmin) - Admin interface for MongoDB built using Django and Bootstrap :star:258
 - [mongri](https://github.com/dongri/mongri) - Web-based user interface for MongoDB (written in JavaScript)
 - [Rockmongo](https://github.com/iwind/rockmongo) - PHPMyAdmin for MongoDB, sort of :star:822

## Applications
 - [CodeCombat](https://github.com/codecombat/codecombat) - Multiplayer programming game for learning how to code :star:6187
 - [Countly](https://github.com/countly/countly-server) - Mobile & web analytics and marketing platform built on Node.js and MongoDB  :star:2643
 - [Leanote](https://github.com/leanote/leanote) - Evernote clone built with Go and MongoDB :star:6977
 - [NodeBB](https://github.com/NodeBB/NodeBB) - Node.js and MongoDB based forum software ("built for the modern web")
 - [Quokka](https://github.com/rochacbruno/quokka) - Python CMS built on top of Flask and MongoDB :star:1847
 - [Reaction](https://github.com/reactioncommerce/reaction) - Event-driven, real-time commerce platform built with ES6 and MongoDB :star:6973
 - [uptime](https://github.com/fzaninotto/uptime) - Remote monitoring application using Node.js, MongoDB, and Bootstrap :star:3422

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Guillaume Gelin](https://github.com/ramnes) has waived all copyright and related or neighboring rights to this work.


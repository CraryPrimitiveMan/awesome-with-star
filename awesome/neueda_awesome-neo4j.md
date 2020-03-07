# Information comes from [neueda/awesome-neo4j](https://github.com/neueda/awesome-neo4j)
Awesome Neo4j
==============
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://api.travis-ci.org/neueda/awesome-neo4j.svg?branch=master )](https://travis-ci.org/neueda/awesome-neo4j)

A curated list of awesome [Neo4j](https://neo4j.com/) resources.  
Inspired by the `awesome-*` trend on GitHub.

The goal is to build a categorized community-driven collection of very well-known resources.  
Sharing, suggestions and contributions are always welcome!

Thanks to all [contributors](https://github.com/Neueda/awesome-neo4j/graphs/contributors).

Maintained by [Neueda R&D](http://labs.neueda.com/).

Table of Contents
=================

  * [Basics](#basics)
  * [Connectors](#connectors)
    * [Bolt](#bolt)
    * [REST API](#rest-api)
      * [Java](#java)
      * [Ruby](#ruby)
      * [Python](#python)
      * [PHP](#php)
      * [Other](#other)
  * [Cloud](#cloud)
  * [Packages](#packages)
  * [Docker](#docker)
  * [Full\-text search](#full-text-search)
  * [Import](#import)
  * [Benchmarking](#benchmarking)
  * [Extensions](#extensions)
  * [Stored Procedures](#stored-procedures)
  * [Development](#development)
  * [Editors](#editors)
  * [Shell](#shell)
  * [Visualization](#visualization)
  * [Tools](#tools)
  * [Resources](#resources)
    * [Learn](#learn)
    * [Certification](#certification)
    * [Bolt](#bolt-1)
    * [Books](#books)
    * [Miscellaneous](#miscellaneous)
  * [License](#license)

Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc.go)

# Basics

- [Official documentation](https://neo4j.com/docs/)
- [Cypher Refcard](https://neo4j.com/docs/cypher-refcard/current/)
- [Developer resources](https://neo4j.com/developer/get-started/)
- [Gists](http://graphgist.neo4j.com/) - With Neo4j GraphGists you can describe and model your domain in a simple text file and render it as a rich, interactive page in any browser. Perfect to document a specific domain, use-case, question or graph problem.
- [Neo4j Examples](https://github.com/neo4j-examples) - Examples for Neo4j and Library Usage.

# Related project

- [openCypher](http://www.opencypher.org/) - openCypher is an open source project to bring a new public implementation of the industry’s most widely adopted graph query language: Cypher.
- [Bolt Protocol](https://boltprotocol.org) - The Bolt network protocol is a highly efficient, lightweight client-server protocol designed for database applications.

# Connectors

## Bolt

- [neo4j-java-driver](https://github.com/neo4j/neo4j-java-driver) - Java driver for Neo4j binary protocol. :star:209
- [neo4j-python-driver](https://github.com/neo4j/neo4j-python-driver) - Python driver for Neo4j binary protocol. :star:478
- [neo4j-javascript-driver](https://github.com/neo4j/neo4j-javascript-driver) - JavaScript driver for Neo4j binary protocol. :star:574
- [neo4j-dotnet-driver](https://github.com/neo4j/neo4j-dotnet-driver) - .Net driver for Neo4j (Bolt). :star:120
- [neo4j-bolt-php](https://github.com/graphaware/neo4j-bolt-php) - PHP driver for Neo4j binary protocol. :star:40
- [libneo4j-client](https://github.com/cleishm/libneo4j-client) - libneo4j-client is a client library written in C for Neo4j. It is not intended as a complete driver, but rather as a foundation on which basic tools and drivers for various languages may be built. libneo4j-client takes care of all the detail of establishing a session with a Neo4j server, sending statements for evaluation, and retrieving results. :star:96
- [neo4j-spark-connector](https://github.com/neo4j-contrib/neo4j-spark-connector) - Neo4j-Spark-Connector based on Neo4j 3.0's Bolt protocol :star:193
- [neo4j-elixir-driver](https://github.com/mschae/boltex) - Elixir driver for the neo4j bolt protocol :star:26
- [neo4j-elixir-wrapper](https://github.com/florinpatrascu/bolt_sips) - Neo4j driver for Elixir, wrapped around the Bolt protocol. Fork of the Boltex. :star:171

## REST API

### Java

- [neo4j-ogm](https://github.com/neo4j/neo4j-ogm) - Object-Graph Mapping Library for Neo4j. :star:234
- [spring-data-neo4j](https://github.com/spring-projects/spring-data-neo4j) - Provides support to increase developer productivity in Java when using the neo4j graph database. :star:589
- [neo4j-jdbc](https://github.com/neo4j-contrib/neo4j-jdbc) - Neo4j JDBC driver. :star:90
- [jcypher](https://github.com/Wolfgang-Schuetzelhofer/jcypher) - Java access to Neo4J graph databases at multiple levels of abstraction. :star:80

### Ruby

- [neo4jrb](https://github.com/neo4jrb/neo4j) - An active model wrapper for the Neo4j Graph Database for Ruby. :star:1287
- [neography](https://github.com/maxdemarzi/neography) - A thin Ruby wrapper to the Neo4j Rest API. :star:610

### Python

- [py2neo](https://github.com/nigelsmall/py2neo) - Py2neo is a comprehensive toolkit for working with Neo4j from within Python applications or from the command line. :star:55
- [neomodel](https://github.com/neo4j-contrib/neomodel) - An Object Graph Mapper (OGM) for the neo4j graph database, built on the awesome py2neo. :star:546

### PHP

- [Neo4j-PHP-OGM](https://github.com/graphaware/neo4j-php-ogm) - Doctrine style Object Graph Mapper for Neo4j :star:146
- [neo4jphp](https://github.com/jadell/neo4jphp) - PHP wrapper of the Neo4j REST interface. :star:542
- [NeoEloquent](https://github.com/Vinelab/NeoEloquent) - A Neo4j ORM - Based on Eloquent. :star:504
- [neo4j-php-client](https://github.com/graphaware/neo4j-php-client/tree/4.0) - PHP Client for Neo4j leveraging the Http and Bolt protocols. :star:252
- [Spider](https://github.com/spider/spider) - A simple, flexible, and beautiful graph-data abstraction for php. :star:24

### Other

- [node-neo4j](https://github.com/thingdom/node-neo4j) - REST API client for Node. :star:935
- [Neo4jClient](https://github.com/Readify/Neo4jClient) - .NET client binding. :star:315
- [neoism](https://github.com/jmcvetta/neoism) - Client for Golang. :star:362
- [neocons](https://github.com/michaelklishin/neocons) - A feature rich idiomatic Clojure client for the REST API. :star:191
- [RNeo4j](https://github.com/nicolewhite/RNeo4j) - Driver for R. :star:233
- [AnormCypher](https://github.com/AnormCypher/AnormCypher) - Scala library based on Anorm in the Play Framework. :star:128

# Cloud

- [GrapheneDB](https://www.graphenedb.com/) - The world's first fully managed
Neo4j graph database.
- [GraphStory](https://www.graphstory.com/) - Neo4j enterprise cloud provider

# Packages

- [Debian Packages](http://debian.neo4j.org/)
- [Yum Repo](http://yum.neo4j.org/stable/)

# Docker

- [docker-neo4j](https://github.com/neo4j/docker-neo4j) - Docker Images for the Neo4j Graph Database. :star:166
- [docker-neo4j-cluster](https://github.com/ekino/docker-neo4j-cluster) - Up & Running Neo4j cluster in no time. :star:39

# Full-text search

- [GraphAware Neo4j Elasticsearch Integration](https://github.com/graphaware/neo4j-to-elasticsearch) - GraphAware Framework Module for Integrating Neo4j with Elasticsearch. :star:212
- [GraphAware Graph-Aided Search](https://github.com/graphaware/graph-aided-search) - Elasticsearch plugin offering Neo4j integration for Personalized Search. :star:139
- [neo4j-elasticsearch](https://github.com/neo4j-contrib/neo4j-elasticsearch) - Neo4j ElasticSearch Integration. :star:157

# Import

- [GraphAware Neo4j Importer](https://github.com/graphaware/neo4j-importer) - Java importer skeleton for complicated, business-logic-heavy high-performance Neo4j imports directly from SQL databases, CSV files, etc. :star:19
- [neo4j-csv-firehose](https://github.com/sarmbruster/neo4j-csv-firehose) - Enables Neo4j’s `LOAD CSV` Cypher command to load from other datasources as well. :star:11
- [neo4j-rdbms-import](https://github.com/jexp/neo4j-rdbms-import) - An automatic importer for relational databases into Neo4j. :star:35
- [Doc manager for Neo4j](https://github.com/neo4j-contrib/neo4j_doc_manager) - The Neo4j Doc Manager takes MongoDB documents and makes it easy to query them for relationships by making them available in a Neo4j graph structure, following the format specified by Mongo Connector. :star:88
- [neoloadcsvskelgen](https://github.com/wadael/neoloadcsvskelgen) - Will output a skeleton of LOAD CSV Cypher code, from very little input (filename, separator, hints). Save time, avoid typos.  :star:1

# Benchmarking

- [neoprofiler](https://github.com/moxious/neoprofiler) - Neo4J database profiling utility. :star:29

# Extensions

- [GraphAware Neo4j UUID](https://github.com/graphaware/neo4j-uuid) - GraphAware Runtime Module that assigns a UUID to all nodes in the graph transparently. :star:89
- [GraphAware Neo4j ChangeFeed](https://github.com/graphaware/neo4j-changefeed) - A GraphAware Framework Runtime Module allowing users to find out what were the latest changes performed on the graph. :star:15
- [GraphAware Neo4j TimeTree](https://github.com/graphaware/neo4j-timetree) - Java and REST APIs for working with time-representing tree in Neo4j. :star:186
- [GraphAware Neo4j Recommendation Engine](https://github.com/graphaware/neo4j-reco) - Neo4j-based recommendation engine module with real-time and pre-computed recommendations. :star:335
- [GraphAware Neo4j Algorithms](https://github.com/graphaware/neo4j-algorithms) - Custom graph algorithms for Neo4j with own Java and REST APIs. :star:32
- [GraphAware Neo4j Warmup](https://github.com/graphaware/neo4j-warmup) - Simple library that warms up Neo4j caches with a single REST call. :star:10
- [GraphAware Neo4j RestTest](https://github.com/graphaware/neo4j-resttest) - GraphAware RestTest is a simple library for testing code that talks to Neo4j running in standalone server mode. :star:13
- [GraphAware Neo4j Expire](https://github.com/graphaware/neo4j-expire) - GraphAware Expire is a simple library that automatically deletes nodes and relationships from the database when they've reached their expiration date or time-to-live (TTL). :star:29
- [Spatial](https://github.com/neo4j-contrib/spatial) - Neo4j Spatial is a library of utilities for Neo4j that faciliates the enabling of spatial operations on data. :star:656
- [Graphify](https://github.com/Graphify/graphify) - Graphify is a Neo4j unmanaged extension used for document and text classification using graph-based hierarchical pattern recognition. :star:376
- [neo4j-tx-participation](https://github.com/jexp/neo4j-tx-participation) - This is a Neo4j Server Extension to make Neo4j REST-API participate in transactions started by the transactional Cypher endpoint. :star:3

# Stored Procedures

- [Apoc : Awesome Procedures on Cypher](https://github.com/neo4j-contrib/neo4j-apoc-procedures) - Collection of useful procedures for Neo4j 3.x :star:1095
- [Graphgen](https://github.com/graphaware/neo4j-graphgen-procedure) - Neo4j procedure for generating test data easily with Cypher :star:7

# Development

- [Maven repositories](https://m2.neo4j.org/index.html) - Neo4j Maven repositories (releases, snapshots).
- [GraphAware Neo4j Framework](https://github.com/graphaware/neo4j-framework)- GraphAware Framework speeds up development with Neo4j by providing a platform for building useful generic as well as domain-specific functionality, analytical capabilities, (iterative) graph algorithms, etc.
- [cypher-dsl](https://github.com/neo4j-contrib/cypher-dsl) - A Java DSL for the Cypher Query Language and an optional Query DSL mode. :star:83
- [Liquigraph](https://github.com/liquigraph/liquigraph) - Database migrations management tool, based on how Liquibase works. :star:90
- [blueprints](https://github.com/tinkerpop/blueprints) - Blueprints is a collection of interfaces, implementations, ouplementations, and test suites for the property graph data model. Blueprints is analogous to the JDBC, but for graph databases. :star:1303
- [structr](https://github.com/structr/structr) - Graph Application Platform based on Neo4j. :star:569
- [Reco4PHP](https://github.com/graphaware/reco4php) - Neo4j based Recommendation Engine Framework for PHP. :star:120

# Editors

- [jetbrains-plugin-graph-database-support](https://github.com/neueda/jetbrains-plugin-graph-database-support) - Graph Databases support for Jetbrains family IDE's. :star:136
- [cypher-vim-syntax](https://github.com/neo4j-contrib/cypher-vim-syntax) - Very basic Vim syntax for Cypher. :star:31

# Shell

- [cycli](https://github.com/nicolewhite/cycli) - A Command Line Interface for Cypher. :star:268
- [neo4j-shell-tools](https://github.com/jexp/neo4j-shell-tools) - A bunch of import/export tools for the neo4j-shell. :star:273

# Visualization

- [neoclipse](https://github.com/neo4j-contrib/neoclipse) - Neoclipse is a tool to view, edit and explore Neo4j databases. :star:204
- [Gephi](https://github.com/gephi/gephi) - Gephi is an award-winning open-source platform for visualizing and manipulating large graphs. :star:3709
- [Linkurious](https://linkurio.us/) - Linkurious helps search and visualize your graph data through a simple web-based interface.
- [yFiles for HTML](https://www.yworks.com/products/yfiles-for-html) - yFiles is a commercial generic graph visualization programming library that comes with [a demo to visualize your neo4j databases in JavaScript](http://live.yworks.com/demos/#neo4j). It's also the basis for the [free neo4j Graph Explorer app](https://www.yworks.com/neo4j-explorer/).

# Tools

- [Graphgen](http://graphgen.graphaware.com) - Graph Generation engine based on the Cypher DSL.
- [store-utils](https://github.com/jexp/store-utils) - Utilities to compact, copy, fix, analyse Neo4j stores. :star:81
- [ineo](https://github.com/cohesivestack/ineo)- A simple but useful Neo4j instance manager.
- [yFiles neo4j Graph Explorer](https://www.yworks.com/blog/neo4j-node-design) - A simple, free online tool to visualize your graph data and database schema.

## Learn

- [Getting Started with Neo4j](https://neo4j.com/graphacademy/online-training/getting-started-graph-databases-using-neo4j/)
- [Neo4j in Production](https://neo4j.com/graphacademy/online-training/neo4j-production/)
- [Neo4j Koans](https://github.com/jimwebber/neo4j-tutorial) - A koan-style tutorial in Java for Neo4j. :star:314

## Certification

- [Neo4j Certification](https://neo4j.com/graphacademy/neo4j-certification/) - Become a Neo4j-Certified Professional.

## Miscellaneous

- [Neo4j's Idea board](https://trello.com/b/2zFtvDnV/public-idea-board)
- [Hardware Sizing Calculator](https://neo4j.com/hardware-sizing-calculator/)

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Neueda R&D](https://github.com/Neueda) has waived all copyright and related or neighboring rights to this work.


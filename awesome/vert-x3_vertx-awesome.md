# Information comes from [vert-x3/vertx-awesome](https://github.com/vert-x3/vertx-awesome)
# Awesome Vert.x [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="logo-sm.png" align="right" width="250">](http://vertx.io)

*Awesome Vert.x* is a list of awesome frameworks, libraries or other components for use with or that use
[Vert.x](https://github.com/eclipse/vert.x) version 3.

If you want your component to appear here send a pull request to this repository to add it.

Please note that we can't vouch for the stability or production-worthiness of everything on this list unless it has
the icon <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px">
next to it. This icon means the component is part of the official
[Vert.x stack](http://vert-x3.github.io/docs/).

For Vert.x version 2 check [this page](./vert-x2.md).

## Contents

- [Books](#books)
- [Build tools](#build-tools)
- [Web Frameworks](#web-frameworks)
- [Authentication Authorisation](#authentication-authorisation)
- [Database Clients](#database-clients)
- [Integration](#integration)
- [Middleware](#middleware)
- [Language Support](#language-support)
- [Reactive](#reactive)
- [Sync Thread Non Block](#sync-thread-non-block)
- [Vert.x Event Bus Clients](#vertx-event-bus-clients)
- [Cluster Managers](#cluster-managers)
- [Cloud Support](#cloud-support)
- [Docker](#docker)
- [Microservices](#microservices)
- [Search Engines](#search-engines)
- [Service Factory](#service-factory)
- [Config](#config)
- [Dependency Injection](#dependency-injection)
- [Testing](#testing)
- [Development Tools](#development-tools)
- [Miscellaneous](#miscellaneous)
- [Distribution](#distribution)
- [Examples](#examples)
- [Deployment](#deployment)
- [Utilities](#utilities)
- [Front-End](#front-end)

## Books

* [A gentle guide to asynchronous programming with Eclipse Vert.x for Java developers](http://vertx.io/docs/guide-for-java-devs/) by Julien Ponge, Thomas Segismont and Julien Viet
* [Building Reactive Microservices in Java](https://developers.redhat.com/promotions/building-reactive-microservices-in-java/) by Clément Escoffier

## Build tools

* [Vert.x Maven plugin](https://github.com/fabric8io/vertx-maven-plugin) :star:21
* [Vert.x Gradle plugin](https://plugins.gradle.org/plugin/io.vertx.vertx-plugin)

## Web Frameworks

* [Vert.x Web](https://github.com/vert-x3/vertx-web)  <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Full featured web toolkit for Vert.x.
* [Vert.x Jersey](https://github.com/englishtown/vertx-jersey) - Create JAX-RS [Jersey](https://jersey.java.net/) resources in Vert.x. :star:133
* [Kovert](https://github.com/kohesive/kovert) - Invisible REST framework for Kotlin + Vert.x Web. :star:111
* [Handlers](https://github.com/spriet2000/vertx-handlers-http) - Open web framework for Vert.x. :star:6
* [QBit](https://github.com/advantageous/qbit) - REST and WebSocket method call marshaling and reactive library. :star:621
* [vertx-rest-storage](https://github.com/swisspush/vertx-rest-storage) - Persistence for REST resources in the filesystem or a redis database. :star:14
* [Jubilee](https://github.com/isaiah/jubilee) - A rack compatible Ruby HTTP server built on Vert.x 3. :star:339
* [Knot.x](https://github.com/Cognifide/knotx) - Efficient & high-performance integration platform for modern websites built on Vert.x 3. :star:90
* [Vert.x Jspare](https://github.com/jspare-projects/vertx-jspare) - Improving your Vert.x 3 experience with Jspare Framework. :star:9
* [Irked](https://github.com/GreenfieldTech/irked) - Annotations-based configuration for Vert.x 3 Web and controller framework. :star:8
* [REST.VertX](https://github.com/zandero/rest.vertx) - Lightweight JAX-RS (RestEasy) like annotation processor for Vert.x verticals. :star:50
* [Atmosphere Vert.x](https://github.com/Atmosphere/atmosphere-vertx) - Realtime Client Server Framework for the JVM, supporting WebSockets and Server Sent Events with Cross-Browser Fallbacks. :star:31

## Authentication Authorisation

* [Vert.x Auth JDBC](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-jdbc)  <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x authentication/authorisation JDBC based.
* [Vert.x Auth JWT](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-jwt)  <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation based on JSON Web Tokens.
* [Vert.x Auth Shiro](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-shiro)  <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x AuthN/AuthZ based on [Apache Shiro](http://shiro.apache.org/).
* [Vert.x-Pac4j](https://github.com/pac4j/vertx-pac4j) - Vert.x authentication/authorisation implemented using [pac4j](http://www.pac4j.org/). :star:80

## Database Clients

*Clients for connecting to databases*

* Relational Databases
  * [JDBC](https://github.com/vert-x3/vertx-jdbc-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Asynchronous interface around a JDBC datasource.
  * [MySQL](https://github.com/vert-x3/vertx-mysql-postgresql-client) - Asynchronous client for MySQL. :star:41
  * [PostgreSQL](https://github.com/vert-x3/vertx-mysql-postgresql-client) - Asynchronous client for PostgreSQL. :star:41
  * [PostgreSQL](https://github.com/vietj/reactive-pg-client) - Reactive PostgreSQL Client. :star:110
  * [database](https://github.com/susom/database) - Client for Oracle, PostgreSQL, SQL Server, HyperSQL, etc. designed for security, correctness, and ease of use. :star:22
  * [jOOQ](https://github.com/jklingsporn/vertx-jooq) - Doing typesafe, asynchronous SQL and generate code using jOOQ. :star:89

* NoSQL Databases
  * [MongoDB](https://github.com/vert-x3/vertx-mongo-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - An asynchronous client for interacting with a MongoDB database.
  * [Redis](https://github.com/vert-x3/vertx-redis-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Asynchronous API to interact with Redis.
  * [Cassandra](https://github.com/englishtown/vertx-cassandra) - Asynchronous API to interact with Cassandra and Cassandra Mapping. :star:34
  * [OrientDB](https://github.com/cstamas/vertx-orientdb) - Non-blocking OrientDB server integration. :star:7
  * [Bitsy](https://github.com/cstamas/vertx-bitsy) - Non-blocking Bitsy Graph server integration. :star:1
  * [MarkLogic](https://github.com/etourdot/vertx-marklogic) - Asynchronous client for Marklogic Database Server. :star:1

* [vertx-pojo-mapper](https://github.com/BraintagsGmbH/vertx-pojo-mapper) - Non-blocking POJO mapping for MySQL and MongoDB. :star:40
* [vertx-mysql-binlog-client](https://github.com/guoyu511/vertx-mysql-binlog-client) - A Vert.x client for tapping into MySQL replication stream. :star:14

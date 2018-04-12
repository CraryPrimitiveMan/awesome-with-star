# Information comes from [mfornos/awesome-microservices](https://github.com/mfornos/awesome-microservices)
# Awesome Microservices [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of Microservice Architecture related principles and technologies.

**Table of Contents**

- [Platforms](#platforms)
- [Frameworks / Runtimes](#frameworks--runtimes)
- [Service Toolkits](#service-toolkits)
  - [Polyglot](#polyglot)
  - [C](#c)
  - [C++](#c-1)
  - [C#](#csharp)
  - [D](#d)
  - [Erlang VM](#erlang-vm)
  - [Go](#go)
  - [Haskell](#haskell)
  - [Java VM](#java-vm)
  - [Node.js](#nodejs)
  - [Perl](#perl)
  - [PHP](#php)
  - [Python](#python)
  - [Ruby](#ruby)
- [Capabilities](#capabilities)
  - [API Gateways / Edge Services](#api-gateways--edge-services)
  - [Configuration and Discovery](#configuration-and-discovery)
  - [Coordination and Governance](#coordination-and-governance)
  - [Elasticity](#elasticity)
  - [Job Schedulers / Workload Automation](#job-schedulers--workload-automation)
  - [Logging](#logging)
  - [Messaging](#messaging)
  - [Monitoring and Debugging](#monitoring-and-debugging)
  - [Reactivity](#reactivity)
  - [Resilience](#resilience)
  - [Security](#security)
  - [Serialization](#serialization)
  - [Storage](#storage)
  - [Testing](#testing)
- [Continuous Integration and Continuous Delivery](#continuous-integration-and-continuous-delivery)
- [Documentation & Modeling](#documentation--modeling)
  - [REST APIs](#rest-apis)
- [Standards / Recommendations](#standards--recommendations)
  - [World Wide Web](#world-wide-web)
  - [HTTP/1.1](#http11)
  - [HTTP/2](#http2)
  - [CoAP](#coap)
  - [RPC](#rpc)
  - [Messaging](#messaging-1)
  - [Security](#security-1)
  - [Service Discovery](#service-discovery)
  - [Data Formats](#data-formats)
  - [Vocabularies](#vocabularies)
  - [Unicode](#unicode)
- [Real Life Stories](#real-life-stories)
- [Enterprise & Verticals](#enterprise--verticals)
- [Theory](#theory)
  - [Articles & Papers](#articles--papers)
  - [Talks](#talks)
  - [Tutorials](#tutorials)
  - [Books](#books)
  - [Sites](#sites)
- [Emerging Technologies](#emerging-technologies)
- [License](#license)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)


## Platforms

- [Cocaine](https://github.com/cocaine) - A cloud platform enabling you to build your own PaaS clouds.
- [Deis](http://deis.io/) - Open source application platform for public and private clouds.
- [Fabric8](http://fabric8.io/) - Open source microservices platform based on Docker, Kubernetes and Jenkins. Makes it easy to create, edit, deploy and manage microservices and go faster.
- [Hook.io](https://hook.io) - Open source provider of microservice and webhook hosting.
- [Lightbend ![c]](https://www.lightbend.com/) - Platform for building scalable reactive systems on the JVM.
- [Mantl](https://github.com/mantl/mantl) - Platform for rapidly deploying globally distributed services. :star:3019
- [Netflix OSS](https://netflix.github.io/) - Netflix open source software ecosystem.
- [OpenWhisk](http://openwhisk.org/) - Serverless, open source cloud platform that executes functions in response to events at any scale.
- [STUPS](https://stups.io/) - A set of tools and components by Zalando to provide a convenient and audit-compliant PaaS for multiple autonomous teams on top of AWS.
- [VAMP ![c]](http://vamp.io/) - Build, deploy and manage microservices with power and ease.

## Frameworks / Runtimes

- [Akka](http://akka.io/) - Toolkit and runtime for building highly concurrent, distributed, and resilient message-driven applications on the JVM.
- [Baratine](http://baratine.io/) - Platform for building a network of loosely-coupled POJO microservices.
- [Erlang/OTP](https://github.com/erlang/otp) - Programming language used to build massively scalable soft real-time systems with requirements on high availability. :star:6565
- [Finagle](http://twitter.github.io/finagle) - Extensible RPC system for the JVM, used to construct high-concurrency servers.
- [GPars](https://github.com/GPars/GPars) - Concurrency and parallelism framework for the JVM. :star:175
- [Grenache](https://github.com/bitfinexcom/grenache) - A Bittorent-DHT based microservices framework supporting REQ/REP and PUB/SUB patterns over multiple transports. :star:115
- [Ice](https://zeroc.com/) - Comprehensive RPC framework with support for C++, C#, Java, JavaScript, Python, and more.
- [Lagom](https://github.com/lagom/lagom) - Reactive microservices for the JVM. :star:1820
- [Light Java](https://github.com/networknt/light-java) - A fast, lightweight and more productive microservices framework. :star:717
- [Microserver](https://github.com/aol/micro-server) - Java 8 native, zero configuration, standards based, battle hardened library to run Java REST microservices. :star:827
- [Orbit](https://github.com/orbit/orbit) - Modern framework for JVM languages that makes it easier to build and maintain distributed and scalable online services. :star:1228
- [Quasar](https://github.com/puniverse/quasar) - Fibers, channels and actors for the JVM. :star:3049
- [ScaleCube](https://github.com/scalecube/scalecube) - Toolkit for building reactive microservices for the JVM: low-latency, high-throughput, scalable and resilient. :star:143
- [Vert.X](http://vertx.io/) - Toolkit for building reactive applications on the JVM.
- [Vert.X Toolbox](https://github.com/vert-x3/vertx-microservices-toolbox) - A set of Vert.x components to build reactive microservice applications. :star:58
- [Wangle](https://github.com/facebook/wangle) - A framework providing a set of common client/server abstractions for building services in a consistent, modular, and composable way. :star:1878
- [WildFly Swarm](http://wildfly-swarm.io/) - Microservices starting with just enough Java EE runtime, based on [Eclipse MicroProfile](https://projects.eclipse.org/proposals/eclipse-microprofile).

## Service Toolkits

### Polyglot

- [Apex](https://github.com/apex/apex) - Tool for deploying and managing AWS Lambda functions. With shims for languages not yet supported by Lambda, you can use Golang out of the box. :star:6874
- [CoAP](http://coap.technology/impls.html) - Constrained application protocol implementations.
- [GRPC](http://www.grpc.io/) - A high performance, open source, general RPC framework that puts mobile and HTTP/2 first. Libraries in C, C++, Java, Go, Node.js, Python, Ruby, Objective-C, PHP and C#.
- [Hprose](http://github.com/hprose) - A very newbility RPC Library, support 25+ languages now.

### C

- [Kore](https://kore.io/) - Easy to use web application framework for writing scalable web APIs in C.
- [Libasyncd](https://github.com/wolkykim/libasyncd/) - Embeddable event-based asynchronous HTTP server library for C.
- [Libslack](http://libslack.org/) -  Provides a generic agent oriented programming model, run time selection of locking strategies, functions that make writing daemons trivial and simplify the implementation of network servers and clients, &c.
- [Lwan](http://lwan.ws/) - High-performance and scalable web server.
- [Onion](https://github.com/davidmoreno/onion) - C library to create simple HTTP servers and web applications. :star:1357
- [RIBS2](https://github.com/Adaptv/ribs2) - Library which allows building high-performance internet serving systems. :star:117

### C++
<!-- #c-1 anchor -->

- [AnyRPC](https://github.com/sgieseking/anyrpc) - Provides a common system to work with a number of different remote procedure call standards, including: JSON-RPC, XML-RPC, MessagePack-RPC. :star:21
- [Cap’n Proto RPC](https://capnproto.org/cxxrpc.html) - The Cap’n Proto C++ RPC implementation.
- [C++ Micro Services](http://cppmicroservices.org/) - An OSGi-like C++ dynamic module system and service registry.
- [Enduro/X](https://github.com/endurox-dev/endurox/) - XATMI based service framework for GNU/Linux.
- [Pion](https://github.com/splunk/pion) - C++ framework for building lightweight HTTP interfaces. :star:263
- [Pistache](https://github.com/oktal/pistache) - A high-performance REST toolkit written in C++. :star:771
- [Poco](http://pocoproject.org/) - C++ class libraries for building network-based applications and servers.
- [Restbed](https://github.com/Corvusoft/restbed) - Brings asynchronous RESTful functionality to C++11 applications. :star:699
- [Served](https://github.com/datasift/served) - C++ library for building high-performance RESTful web servers. :star:371
- [ULib](https://github.com/stefanocasazza/ULib) - Highly optimized class framework for writing C++ applications. :star:653

### CSharp

- [Akka.NET](http://getakka.net/) - Toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications on .NET & Mono.
- [Nancy](http://nancyfx.org/) - Lightweight web framework.

### D

- [Vibe.d](http://vibed.org/) - Asynchronous I/O that doesn’t get in your way, written in D.

### Erlang VM

#### Elixir

- [Phoenix](http://www.phoenixframework.org/) - Framework for building HTML5 apps, API backends and distributed systems.
- [Plug](https://github.com/elixir-lang/plug) - A specification and conveniences for composable modules between web applications. :star:1720

#### Erlang

- [Cowboy](https://github.com/ninenines/cowboy) - Small, fast, modular HTTP server written in Erlang. :star:4870
- [Mochiweb](https://github.com/mochi/mochiweb) - Erlang library for building lightweight HTTP servers. :star:1594

### Go

- [Echo](https://echo.labstack.com/) - Fast and unfancy HTTP server framework for Go. Up to 10x faster than the rest.
- [Gizmo](https://github.com/nytimes/gizmo) - Microservices toolkit. :star:2159
- [Goa](https://github.com/goadesign/goa) - Design-based HTTP microservices in Go. :star:2722
- [Gocraft](https://github.com/gocraft/web) - A toolkit for building web apps. Includes routing, middleware stacks, logging and monitoring. :star:1301
- [Goji](https://goji.io/) - Minimalistic and flexible request multiplexer for Go.
- [Go kit](https://github.com/go-kit/kit) - Distributed programming toolkit for microservices in the modern enterprise. :star:9624
- [Go-micro](https://github.com/micro/go-micro) - A pluggable RPC microservice framework. :star:3338
- [Gopencils](https://github.com/bndr/gopencils) - Easily consume REST APIs with Go. :star:410
- [Gorilla](http://www.gorillatoolkit.org/) - Web toolkit for the Go programming language.
- [Iris](https://github.com/kataras/iris) - Fast, simple and efficient micro web framework for Go. :star:9851
- [Kite](https://github.com/koding/kite) - Microservices framework in Go. :star:1887
- [Libchan](https://github.com/docker/libchan) - Ultra-lightweight networking library which lets network services communicate in the same way that goroutines communicate using channels. :star:2291
- [Micro](https://github.com/micro/micro) - A microservices toolchain in Go. :star:4266
- [Nano](https://github.com/pasztorpisti/nano) - A minimalistic, transport-agnostic and testing-friendly microservice framework. :star:3
- [Negroni](https://github.com/codegangsta/negroni) - Idiomatic HTTP middleware for Golang. :star:5451
- [Neutrino](https://github.com/neutrinoapp/neutrino) - Realtime/REST backend service. :star:138
- [RPCX](https://github.com/smallnest/rpcx) - A distributed RPC service framework based on NET/RPC like Alibaba Dubbo and Weibo Motan. :star:2186
- [Sleepy](https://github.com/dougblack/sleepy) - REST for go. :star:669
- [Vamp-router](https://github.com/magneticio/vamp-router) - Service routing, load balancing and filtering application. :star:87
- [Zerver](https://github.com/cosiner/zerver) - RESTful API framework. :star:140

### Haskell

- [Scotty](https://github.com/scotty-web/scotty) - Micro web framework inspired by Ruby's Sinatra, using WAI and Warp. :star:1188
- [Servant](https://github.com/haskell-servant/servant) - Type-level web DSL. :star:941
- [Yesod](https://github.com/yesodweb/yesod) - The Haskell RESTful web framework. :star:1911

### Java VM

#### Clojure

- [Compojure](https://github.com/weavejester/compojure) - A concise routing library for Ring/Clojure. :star:3376
- [Duct](https://github.com/weavejester/duct) - Minimal framework for building web applications in Clojure, with a strong emphasis on simplicity. :star:658
- [Friboo](https://github.com/zalando/friboo) - Utility library for writing microservices in Clojure, with support for Swagger and OAuth. :star:113
- [Liberator](http://clojure-liberator.github.io/liberator/) - Library that helps you expose your data as resources while automatically complying with all the relevant requirements of the HTTP specification.
- [Modularity](https://modularity.org/) - JUXT's Clojure-based modular system.
- [System](https://github.com/danielsz/system) - Built on top of Stuart Sierra's component library, offers a set of readymade components. :star:534
- [Tesla](https://github.com/otto-de/tesla-microservice) - Common basis for some of Otto.de's Clojure microservices. :star:177

#### Java

- [Airlift](https://github.com/airlift/airlift) - Framework for building REST services in Java. :star:229
- [Disruptor](https://github.com/LMAX-Exchange/disruptor) - High-performance inter-thread messaging library. :star:7478
- [Dropwizard](https://dropwizard.github.io/) - Java framework for developing ops-friendly, high-performance, RESTful web services.
- [HTTP Remoting](https://github.com/palantir/http-remoting) - Libraries for defining and creating RESTish/RPC servers and clients based on Feign or Retrofit as a client and Dropwizard/Jersey with JAX-RS service definitions as a server. :star:42
- [Ja-micro](https://github.com/Sixt/ja-micro) - Lightweight Java framework for building microservices (compatible with go-micro). :star:595
- [Jersey](https://jersey.github.io/) - RESTful services in Java. JAX-RS reference implementation.
- [MSF4J](https://github.com/wso2/msf4j) - High throughput & low memory footprint Java microservices framework. :star:269
- [QBit](https://github.com/advantageous/qbit) - Reactive programming library for building microservices. :star:613
- [Ratpack](https://ratpack.io/) - Set of Java libraries that facilitate fast, efficient, evolvable and well tested HTTP applications. specific support for the Groovy language is provided.
- [Restlet](http://restlet.com/) - Helps Java developers build web APIs that follow the REST architecture style.
- [Spark](http://sparkjava.com/) - A micro-framework for creating web applications in Java 8 with minimal effort.
- [Spring Boot](http://projects.spring.io/spring-boot/) - Makes it easy to create stand-alone, production-grade Spring based applications.

#### Scala

- [Akka HTTP](http://doc.akka.io/docs/akka-http/current/scala.html) - Open source toolkit for building REST/HTTP-based integration layers on top of Scala and Akka.
- [Colossus](https://github.com/tumblr/colossus) - I/O and microservice library for Scala. :star:1050
- [Finatra](http://twitter.github.io/finatra/) - Fast, testable, Scala HTTP services built on Twitter-Server and Finagle.
- [Http4s](http://http4s.org/) - A minimal, idiomatic Scala interface for HTTP
- [Play](https://www.playframework.com/) - The high velocity web framework for Java and Scala.
- [Scalatra](http://www.scalatra.org/) - Simple, accessible and free web micro-framework.
- [Skinny Micro](https://github.com/skinny-framework/skinny-micro) - Micro-web framework to build servlet applications in Scala. :star:53
- [Squbs](http://paypal.github.io/squbs/) - A suite of components enabling standardization and operationalization of Akka and Akka HTTP applications/services in a large scale, managed, cloud environment.

### Node.js

- [Actionhero](http://www.actionherojs.com/) - Multi-transport Node.js API server with integrated cluster capabilities and delayed tasks.
- [Baucis](https://github.com/wprl/baucis) - To build and maintain scalable HATEOAS/Level 3 REST APIs. :star:638
- [Cote](https://github.com/dashersw/cote) - A Node.js library for building zero-configuration microservices. :star:731
- [Express](http://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js
- [FeathersJS](http://feathersjs.com/) - An open source REST and realtime API layer for modern applications.
- [Graft](https://github.com/GraftJS/graft) - Full-stack javascript through microservices. :star:223
- [Hapi](http://hapijs.com/) - A rich framework for building applications and services.
- [Hudson Taylor](https://github.com/hudson-taylor/hudson-taylor) - Set of libraries for building automatically documented, well validated services. :star:31
- [Koa](http://koajs.com/) - Next generation web framework for Node.js
- [Loopback](http://loopback.io/) - Node.js framework for creating APIs and easily connecting to backend data sources.
- [Micro](http://github.com/zeithq/micro) - Asynchronous HTTP microservices. :star:6379
- [Micro Panda](https://github.com/zhaoyao91/micro-panda) - Node.js toolkit to help build microservices. :star:6
- [Micro-Whalla](https://github.com/czerwonkabartosz/Micro-Whalla) - A simple, fast framework for writing microservices in Node.js communicate using RPC / IPC. :star:40
- [Moleculer](http://moleculer.services/) - Fast & powerful microservices framework for NodeJS.
- [Restify](http://restify.com/) - Node.js module built specifically to enable you to build correct REST web services.
- [Seneca](http://senecajs.org/) - A microservices toolkit for Node.js
- [Serverless](https://github.com/serverless/serverless) - Build and maintain web, mobile and IoT applications running on AWS Lambda and API Gateway (formerly known as JAWS). :star:22825
- [Steriods Framework](https://github.com/99xt/steroidslibrary) - Steroids framework simplifies the development of microservices with [Serverless](https://github.com/serverless/serverless) using TypeScript by enabling the developer to emphasize more on business/domain logic rather than focusing too much on technical details. :star:20
- [StdLib](https://stdlib.com/) - Standard library for microservices.

### Perl

- [Cro](http://cro.services/) - Libraries for creating reactive distributed systems using Perl 6.
- [Mojolicious](http://mojolicio.us/) - Next generation web framework for Perl.

### PHP

- [API Platform](https://api-platform.com/) - API-first web framework on top of Symfony with JSON-LD, Schema.org and Hydra support.
- [Fat-Free](https://fatfreeframework.com/) - A powerful yet easy-to-use PHP micro-framework.
- [Flight](https://github.com/mikecao/flight) - An extensible micro-framework. :star:1899
- [Kraken](http://kraken-php.com/) - Asynchronous and fault-tolerant PHP framework for distributed applications.
- [Lumen](https://lumen.laravel.com/) - Stunningly fast micro-framework.
- [Phalcon](https://phalconphp.com/) - Full-stack PHP framework delivered as a C-extension.
- [Silex](http://silex.sensiolabs.org/) - Micro-framework based on the Symfony components.
- [Slim](http://www.slimframework.com/) - Micro-framework that helps you quickly write simple yet powerful web applications and APIs.
- [Upswarm](https://github.com/Zizaco/upswarm) - Multi-processed, async, fault-tolerant micro-framework for writing service-oriented applications. :star:48

### Python

- [Aiohttp](http://aiohttp.readthedocs.io/en/stable/) - HTTP client/server for asyncio.
- [API Star](https://github.com/tomchristie/apistar) - A fast and expressive API framework, designed for Python 3. :star:3796
- [Flask](http://flask.pocoo.org/) - Python framework for microservices based on Werkzeug and Jinja 2.
- [Nameko](https://github.com/onefinestay/nameko) - Python framework for building microservices. :star:1876
- [Sanic](https://github.com/channelcat/sanic) - Sanic is a Flask-like Python 3.5+ web server that's written to go fast. :star:8998
- [Tornado](http://www.tornadoweb.org/) - Web framework and asynchronous networking library.
- [Twisted](https://twistedmatrix.com/trac/) - Event-driven network programming engine.
- [Web.py](https://github.com/webpy/webpy/) - Minimalist web framework for Python.
- [Zappa](https://github.com/Miserlou/Zappa) - Framework for building and deploying server-less Python event-driven and web applications. :star:6743

### Ruby

- [Hanami](https://github.com/hanami) - A modern web framework for Ruby.
- [Praxis](https://github.com/rightscale/praxis) - Framework for both designing and implementing APIs. :star:293
- [Rails API](http://edgeguides.rubyonrails.org/api_app.html) - Rails as an API only.
- [Scorched](https://github.com/wardrop/Scorched) - Light-weight web framework for Ruby. :star:239
- [Sinatra](http://www.sinatrarb.com/) - Sinatra is a DSL for quickly creating web applications in Ruby with minimal effort.

## Capabilities

### API Gateways / Edge Services

- [Amalgam8](https://github.com/amalgam8) - Content-based routing fabric for polyglot microservices.
- [Annon](https://github.com/nebo15/annon.api) - Open source API gateway with built-in API management, authentication and status pages written in Elixir. :star:75
- [Caddy](https://caddyserver.com/) - Extensible HTTP/2 web server with automatic HTTPS.
- [Camel](http://camel.apache.org/) - Empowers you to define routing and mediation rules in a variety of domain-specific languages, including a Java-based fluent API, Spring or Blueprint XML configuration files, and a Scala DSL.
- [Envoy](https://github.com/lyft/envoy) - Open source edge and service proxy, from the developers at Lyft. :star:4497
- [Fabio](https://github.com/eBay/fabio) - A fast, modern, zero-conf load balancing HTTP/S router for deploying microservices managed by Consul. :star:4674
- [HAProxy](http://www.haproxy.org/) - Reliable, high Performance TCP/HTTP load balancer.
- [Istio](https://istio.io/) - An open platform to connect, manage, and secure microservices.
- [Janus](https://github.com/hellofresh/janus) - An API Gateway written in Go. :star:1064
- [Keepalived](http://www.keepalived.org/) - Simple and robust facilities for loadbalancing and high-availability to Linux system and Linux based infrastructures.
- [Kong](https://getkong.org/) - Open source management layer for APIs.
- [Linkerd](https://linkerd.io/) - Resilient service mesh for cloud native apps.
- [Neutrino](https://github.com/eBay/Neutrino) - Extensible software load balancer. :star:240
- [OpenResty](http://openresty.org/) - Fast web application server built on top of Nginx.
- [Skipper](https://github.com/zalando/skipper) - HTTP router useful for decoupling routing from service logic. :star:1019
- [Spring Cloud Gateway](https://cloud.spring.io/spring-cloud-gateway/) - API Gateway on top of Spring MVC. Aims to provide a simple, yet effective way to route to APIs.
- [Tengine](http://tengine.taobao.org/) - A distribution of Nginx with some advanced features.
- [Træfɪk](http://traefik.io/) - A modern HTTP reverse proxy and load balancer made to deploy microservices with ease.
- [Traffic Server](https://github.com/apache/trafficserver) - High-performance building block for cloud services. :star:685
- [Tyk](https://tyk.io/) - Open source, fast and scalable API gateway, portal and API management platform.
- [Vulcand](https://github.com/vulcand/vulcand) - Programmatic load balancer backed by Etcd. :star:2605
- [Zuul](https://github.com/Netflix/zuul) - An edge service that provides dynamic routing, monitoring, resiliency, security, and more. :star:4125

### Configuration and Discovery

- [Consul](https://www.consul.io/) - Service discovery and configuration made easy. Distributed, highly available, and datacenter-aware.
- [ContainerPilot](https://github.com/joyent/containerpilot) - Service for autodiscovery and configuration of applications running in containers. :star:889
- [Denominator](https://github.com/Netflix/denominator) - Portably control DNS clouds using java or bash. :star:472
- [Doozer](https://github.com/ha/doozerd) - Highly-available, completely consistent store for small amounts of data. When the data changes, it can notify connected clients immediately. :star:2970
- [Etcd](https://github.com/coreos/etcd) - Highly-available key-value store for shared configuration and service discovery. :star:17735
- [Eureka](https://github.com/Netflix/eureka/wiki/Eureka-at-a-glance) - REST based service that is primarily used in the AWS cloud for locating services for the purpose of load balancing and failover of middle-tier servers.
- [Microphone](https://github.com/rogeralsing/Microphone) - Lightweight .NET framework to run self hosting REST services using Web Api or NancyFx on top of a Consul or Etcd cluster. :star:432
- [Registrator](https://github.com/gliderlabs/registrator) - Service registry bridge for Docker. Supports pluggable service registries, which currently includes Consul, Etcd and SkyDNS 2. :star:3546
- [Shaman](https://github.com/nanopack/shaman) - Small, lightweight, api-driven DNS server. :star:309
- [SkyDNS](https://github.com/skynetservices/skydns) - Distributed service for announcement and discovery of services built on top of etcd. It utilizes DNS queries to discover available services. :star:1753
- [SmartStack](https://github.com/airbnb/smartstack-cookbook) - Airbnb's automated service discovery and registration framework. :star:205
- [Spring Cloud Config](http://cloud.spring.io/spring-cloud-config/) - Provides server and client-side support for externalized configuration in a distributed system.
- [ZooKeeper](https://zookeeper.apache.org/) - Open source server which enables highly reliable distributed coordination.

### Coordination and Governance

- [AWS Step Functions ![c]](https://aws.amazon.com/step-functions/) - Coordinate the components of distributed applications and microservices using visual workflows.
- [Azuqua ![c]](https://azuqua.com/) - Orchestration and governance platform for distributed applications.
- [Conductor](https://github.com/Netflix/conductor) - A microservices orchestration engine. :star:1037
- [Fission Workflows](https://github.com/fission/fission-workflows) - Workflow-based, reliable function composition for serverless functions. :star:123

### Elasticity

- [Galaxy](http://www.paralleluniverse.co/galaxy/) - Open source high-performance in-memory data-grid.
- [Grape](http://reverbrain.com/grape/) - Realtime processing pipeline.
- [Hazelcast](http://hazelcast.org/) - Open source in-memory data-grid. Allows you to distribute data and computation across servers, clusters and geographies, and to manage very large data sets or high data ingest rates. Mature technology.
- [Helix](http://helix.apache.org/) - Generic cluster management framework used for the automatic management of partitioned, replicated and distributed resources hosted on a cluster of nodes.
- [Ignite](http://ignite.apache.org/) - High-performance, integrated and distributed in-memory platform for computing and transacting on large-scale data sets in real-time, orders of magnitude faster than possible with traditional disk-based or flash technologies.
- [Marathon](https://mesosphere.github.io/marathon/) - Deploy and manage containers (including Docker) on top of Apache Mesos at scale.
- [Mesos](https://mesos.apache.org/) - Abstracts CPU, memory, storage, and other compute resources away from machines (physical or virtual), enabling fault-tolerant and elastic distributed systems to easily be built and run effectively.
- [Nomad](https://www.nomadproject.io/) - Distributed, highly available, datacenter-aware scheduler.
- [Onyx](https://github.com/onyx-platform/onyx) - Distributed, masterless, high performance, fault tolerant data processing for Clojure. :star:1714
- [Ordasity](https://github.com/boundary/ordasity) - Designed to spread persistent or long-lived workloads across several machines. :star:346
- [Redisson](https://github.com/mrniko/redisson) - Distributed and scalable Java data structures on top of Redis server. :star:4872
- [Serf](https://www.serfdom.io/) - Decentralized solution for cluster membership, failure detection and orchestration.

### Job Schedulers / Workload Automation

- [Celery](http://www.celeryproject.org) - Asynchronous task queue/job queue based on distributed message passing. Focused on real-time operation and supports scheduling.
- [Chronos](https://github.com/mesos/chronos) - Fault tolerant job scheduler for Mesos which handles dependencies and ISO8601 based schedules. :star:3941
- [Fenzo](https://github.com/Netflix/Fenzo) - Extensible scheduler for Mesos frameworks. :star:617
- [JobScheduler](http://www.sos-berlin.com/jobscheduler) - Open Source solution for enterprise-level workload automation. It is used to launch executable files and shell scripts and to run database procedures automatically.
- [Rundeck](http://rundeck.org/) - Job scheduler and runbook automation. Enable self-service access to existing scripts and tools.
- [Schedulix](http://www.schedulix.org/en) - Open source enterprise job scheduling system lays down ground-breaking standards for the professional automation of IT processes in advanced system environments.

### Logging

- [Bunyan](https://github.com/trentm/node-bunyan) - Simple and fast JSON logging library for Node.js services. :star:4982
- [Fluentd](http://www.fluentd.org/) - Open source data collector for unified logging layer.
- [Graylog](https://www.graylog.org/) - Fully integrated open source log management platform.
- [Kibana](https://www.elastic.co/products/kibana) - Flexible analytics and visualization platform.
- [Logstash](https://www.elastic.co/products/logstash) - Tool for managing events and logs.
- [Suro](https://github.com/Netflix/suro/wiki) - Distributed data pipeline which enables services for moving, aggregating, routing, storing data.

### Messaging

- [ØMQ](http://zeromq.org/) - Brokerless intelligent transport layer.
- [ActiveMQ](http://activemq.apache.org/) - Powerful open source messaging and integration patterns server.
- [Aeron](https://github.com/real-logic/Aeron) - Efficient reliable UDP unicast, UDP multicast, and IPC message transport. :star:3307
- [Apollo](http://activemq.apache.org/apollo/) - Faster, more reliable, easier to maintain messaging broker built from the foundations of the original ActiveMQ.

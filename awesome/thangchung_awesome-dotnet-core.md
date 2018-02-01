# Information comes from [thangchung/awesome-dotnet-core](https://github.com/thangchung/awesome-dotnet-core)
# Awesome .NET Core [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A collection of awesome [.NET Core](#frameworks-libraries-and-tools) frameworks, libraries, tools, resources and software.

Inspired by [awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet),  [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks).

Contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/thangchung/awesome-dotnet-core/blob/master/contributing.md) pages first. We accept proprietary and commercial software too.

Thanks to all [contributors](https://github.com/thangchung/awesome-dotnet-core/graphs/contributors), you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

## Contents

* [General](#general)
* [Frameworks, Libraries and Tools](#frameworks-libraries-and-tools)
  * [API](#api)
  * [Application Frameworks](#application-frameworks)
  * [Application Templates](#application-templates)
  * [Authentication and Authorization](#authentication-and-authorization)
  * [Blockchain](#blockchain)
  * [Build Automation](#build-automation)
  * [Bundling and Minification](#bundling-and-minification)
  * [Caching](#caching)
  * [CMS](#cms)
  * [Code Analysis and Metrics](#code-analysis-and-metrics)  
  * [Compression](#compression)
  * [Compilers, Transpilers and Languages](#compilers-transpilers-and-languages)
  * [Cryptography](#cryptography)
  * [Database](#database)
  * [Database Drivers](#database-drivers)
  * [Date and Time](#date-and-time)
  * [Distributed Computing](#distributed-computing)
  * [E-Commerce and Payments](#e-commerce-and-payments)
  * [Exceptions](#exceptions)
  * [Functional Programming](#functional-programming)
  * [Graphics](#graphics)
  * [GUI](#gui)
  * [IDE](#ide)
  * [Internationalization](#internationalization)
  * [IOC](#ioc)
  * [Logging](#logging)
  * [Machine Learning and Data Science](#machine-learning-and-data-science)
  * [Mail](#mail)
  * [Mathematics](#mathematics)
  * [Misc](#misc)
  * [ORM](#orm)
  * [Profiling](#profiling)
  * [Queue and Messaging](#queue-and-messaging)
  * [Scheduler and Job](#scheduler-and-job)
  * [SDKs](#sdks)
  * [Security](#security)
  * [Searching](#searching)
  * [Serialization](#serialization)
  * [Testing](#testing)
  * [Tools](#tools)
  * [Web Framework](#web-framework)
  * [Web Socket](#web-socket)
  * [Windows Service](#windows-service)
  * [Workflow](#workflow)
* [Starter Kits](#starter-kits)
* [Sample Projects](#sample-projects)
* [Articles](#articles)
* [Books](#books)
* [Videos](#videos)
* [Podcasts](#podcasts)
* [Community](#community)

## General

* [ASP.NET Core Documentation](https://docs.asp.net/en/latest/) - The official ASP.NET Core documentation site.
* [.NET Core Documentation](https://docs.microsoft.com/en-us/dotnet/articles/welcome) - Home of the technical documentation for .NET Core, C#, F# and Visual Basic, including basic concepts, getting started instructions, tutorials and samples.
* [.NET Core SDK](https://www.microsoft.com/net/core) - .NET Core SDK is a general purpose development platform maintained by Microsoft and the .NET community on [GitHub](https://github.com/dotnet/core).
* [.NET Platform Standard](https://github.com/dotnet/corefx/blob/master/Documentation/architecture/net-platform-standard.md) - The differrent between the old version and the new version of .NET.
* [Introducing .NET Standard 2.0](https://blogs.msdn.microsoft.com/dotnet/2016/09/26/introducing-net-standard) - The description of what will be going on for .NET Standard 2.0 and the roadmap for some missing parts of the current .NET Standard.

## Frameworks, Libraries and Tools

### API
* [autorest](https://github.com/Azure/autorest) - Swagger (OpenAPI) Specification code generator featuring C# and Razor templates. Supports C#, Java, Node.js, TypeScript, Python and Ruby. `4.5.x or above` :star:1597
* [CondenserDotNet](https://github.com/Drawaes/CondenserDotNet) - API Condenser / Reverse Proxy using Kestrel and Consul, Including light weight consul library. :star:52
* [Flurl](https://github.com/tmenier/Flurl) - Fluent URL builder and testable HTTP for .NET [http://tmenier.github.io/Flurl](http://tmenier.github.io/Flurl). :star:835
* GraphQL
  * [graphql-convention](https://github.com/graphql-dotnet/conventions) - This library is a complementary layer on top that allows you to automatically wrap your .NET classes into GraphQL schema definitions using existing property getters and methods as field resolvers :star:64
  * [graphiql-dotnet](https://github.com/JosephWoodward/graphiql-dotnet) - GraphiQL middleware for ASP.NET Core. :star:48
  * [graphql-dotnetcore](https://github.com/mkmarek/graphql-dotnetcore) - GraphQL for .NET Core based on [https://github.com/graphql/graphql-js](https://github.com/graphql/graphql-js). :star:76
  * [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) - GraphQL for .NET. :star:1652
  * [FSharp.Data.GraphQL](https://github.com/fsprojects/FSharp.Data.GraphQL) - FSharp implementation of Facebook GraphQL query language [https://fsprojects.github.io/FSharp.Data.GraphQL](https://fsprojects.github.io/FSharp.Data.GraphQL). :star:121
  * [parser](https://github.com/graphql-dotnet/parser) - A lexer and parser for GraphQL in .NET. :star:52
* [halcyon](https://github.com/visualeyes/halcyon) - HAL implementation for ASP.NET. :star:35
* [JSON API .NET Core](https://github.com/Research-Institute/json-api-dotnet-core) - Framework for building json:api compliant APIs with the goal of eliminating RESTful boilerplate. :star:106
* [LightNode](https://github.com/neuecc/LightNode) - Micro RPC/REST Framework built on OWIN [http://neuecc.github.io/LightNode](http://neuecc.github.io/LightNode). :star:121
* [NSwag](https://github.com/NSwag/NSwag) - The Swagger API toolchain for .NET, Web API and TypeScript [http://NSwag.org](http://NSwag.org). :star:952
* [refit](https://github.com/paulcbetts/refit) - The automatic type-safe REST library for Xamarin and .NET [http://paulcbetts.github.io/refit/](http://paulcbetts.github.io/refit/). :star:2239
* [RESTClient .NET](https://bitbucket.org/MelbourneDeveloper/restclient-.net) - Simple REST Client for all .NET platforms.
* [RestEase](https://github.com/canton7/RestEase) - Easy-to-use typesafe REST API client library, which is simple and customisable. :star:271
* [Swashbuckle](https://github.com/domaindrivendev/Ahoy) - Seamlessly adds a swagger to WebApi projects. :star:1124
* [WebAPIContrib for ASP.NET CORE](https://github.com/WebApiContrib/WebAPIContrib.Core) - Community Contributions for ASP.NET Core. :star:252

### Application Frameworks
* [ABP](https://github.com/aspnetboilerplate/aspnetboilerplate) - ASP.NET Boilerplate is a general purpose application framework especially designed for new modern web applications. It uses already familiar tools and implements best practices arround them to provide you a SOLID development experience. :star:3981
* [Aeron.NET](https://github.com/AdaptiveConsulting/Aeron.NET) - Efficient reliable UDP unicast, UDP multicast, and IPC message transport - .NET port of Aeron. :star:170
* [akka.net](https://github.com/akkadotnet/akka.net) - Toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications on .NET & Mono. :star:2633
* [ASP.NET MVC](https://github.com/aspnet/Mvc) - Model view controller framework for building dynamic web sites with clean separation of concerns, including the merged MVC, Web API, and Web Pages w/ Razor. :star:4987
* [CQRSlite](https://github.com/gautema/CQRSlite) - Lightweight framework for helping writing CQRS and Eventsourcing applications in C#. :star:483
* [DotNetty](https://github.com/Azure/DotNetty) - Port of netty, event-driven asynchronous network application framework. :star:1351
* [EmbedIO](https://github.com/unosquare/embedio) - A tiny, cross-platform, module based web server for .NET Framework and .NET Core. :star:309
* [ExtCore](https://github.com/ExtCore) - Free, open source and cross-platform framework for creating modular and extendable web applications based on ASP.NET Core 1.0.
* [Halibut](https://github.com/OctopusDeploy/Halibut) - A secure communication stack for .NET using JSON-RPC over SSL. :star:149
* [grpc](https://github.com/grpc/grpc/tree/master/src/csharp) - Remote Procedure Calls (RPCs) provide a useful abstraction for building distributed applications and services. The libraries in this repository provide a concrete implementation of the gRPC protocol, layered over HTTP/2. These libraries enable communication between clients and servers using any combination of the supported languages.
* [Nancy](https://github.com/NancyFx/Nancy) - Lightweight, low-ceremony, framework for building HTTP based services on .NET and Mono. :star:5890
* [orleans](https://github.com/dotnet/orleans) - Framework that provides a straight-forward approach to building distributed high-scale computing applications, without the need to learn and apply complex concurrency or other scaling patterns. :star:3521
* [protoactor-dotnet](https://github.com/AsynkronIT/protoactor-dotnet) - Ultra fast distributed actors for Golang and C# [http://proto.actor](http://proto.actor). :star:540
* [RService.io](https://github.com/Stoom/RService.IO) - ASP.Net Core RESTful microservice framework that focusing on speed and ease of use. :star:30
* [ServiceStack](https://github.com/ServiceStack/ServiceStack) - Thoughtfully architected, obscenely fast, thoroughly enjoyable web services for all [https://servicestack.net](https://servicestack.net). :star:4108
* [Steeltoe OSS](https://github.com/SteelToeOSS) - .NET toolkit for common microservice patterns.

### Application Templates
* [ASP.NET Core Boilerplate](https://github.com/ASP-NET-Core-Boilerplate/Templates) - A professional ASP.NET MVC template for building secure, fast, robust and adaptable web applications or sites. It provides the minimum amount of code required on top of the default MVC template provided by Microsoft. :star:1081
* [ASP.NET-MVC-Template](https://github.com/NikolayIT/ASP.NET-MVC-Template) - A ready-to-use templates for ASP.NET MVC 5 and ASP.NET Core with repositories, services, models mapping and DI and StyleCop warnings fixed. :star:140
* [AddFeatureFolders](https://github.com/OdeToCode/AddFeatureFolders) - Enable feature folders for MVC controllers and views in ASP.NET Core. :star:81
* [Angular Visual Studio Webpack Starter](https://github.com/damienbod/AngularWebpackVisualStudio) - Template for Webpack, Visual Studio, ASP.NET Core and Angular. Both the client and the server side of the application are implemented inside one ASP.NET Core project which makes it easier to deploy. :star:424
* [JavaScriptServices](https://github.com/aspnet/JavaScriptServices) - Microsoft ASP.NET Core JavaScript Services. :star:2761
* [kendo-ui-core](https://github.com/telerik/kendo-ui-core) - An HTML5, jQuery-based widget library for building modern web apps. [http://www.telerik.com/kendo-ui](http://www.telerik.com/kendo-ui). :star:1880
* [QuickApp](https://github.com/emonney/QuickApp) - ASP.NET Core / Angular4 startup project template with complete login, user and role management. :star:337
* [Scaffolder](https://github.com/dncuug/scaffolder) - Lets you create extensible data-driven Web applications by automatically generated UI for each table in the database and  lets create a applications for viewing and editing data based on the schema of the data.  :star:88
* [Serenity](https://github.com/volkanceylan/Serenity) - Serenity is an ASP.NET MVC / TypeScript application platform designed to simplify and shorten development of data-centric business applications with a service based architecture. :star:1300
* [Toucan](https://github.com/mrellipse/toucan) - Boilerplate for building single page apps. Server is multi-project .Net Core solution designed around SOLID principles. Client is TypeScript 2, Vuejs 2, Vuex 2. :star:82

### Authentication and Authorization
* [AspNet.Security.OpenIdConnect.Server](https://github.com/aspnet-contrib/AspNet.Security.OpenIdConnect.Server) - OpenID Connect/OAuth2 server framework for OWIN/Katana and ASP.NET Core. :star:366
* [Auth0](https://github.com/auth0/auth0.net) - Hosted, enterprise-grade platform for modern identity. :star:69
* [Identity](https://github.com/aspnet/Identity) - ASP.NET Core Identity is the membership system for building ASP.NET Core web applications, including membership, login, and user data. :star:1464
* [IdentityServer](https://github.com/IdentityServer/IdentityServer4) - IdentityServer for ASP.NET Core 1.0 & 2.0 :star:2382
  * [IdentityServer4.EntityFramework](https://github.com/IdentityServer/IdentityServer4.EntityFramework) - EntityFramework persistence layer :star:108
  * [IdentityServer4.MongoDB](https://github.com/diogodamiani/IdentityServer4.MongoDB) - MongoDB persistence layer :star:29
  * [IdentityServer4.EntityFrameworkCore](https://github.com/2020IP/TwentyTwenty.IdentityServer4.EntityFrameworkCore) - Entity Framework Core persistence layer :star:42
  * [IdentityServer4.Templates](https://github.com/IdentityServer/IdentityServer4.Templates) - dotnet cli templates for IdentityServer4. :star:39
* [openiddict](https://github.com/openiddict/openiddict-core) - Easy-to-use OpenID Connect server for ASP.NET Core. :star:591
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - Build [simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore) with Stormpath and ASP.NET Core. :star:50
* [stuntman](https://github.com/ritterim/stuntman) - Library for impersonating users during development leveraging ASP.NET Identity. :star:200

### Blockchain
* [NBitcoin](https://github.com/MetacoSA/NBitcoin) - Comprehensive Bitcoin library for the .NET framework. :star:789
* [Nethereum](https://github.com/Nethereum) - Bringing the love of Ethereum to .NET.

### Build Automation
* [cake-build](https://github.com/cake-build/cake) - Cross platform build automation system. [http://cakebuild.net](http://cakebuild.net). :star:1580
* [Colorful.Console](https://github.com/tomakita/Colorful.Console) - Style your C# console output! [http://colorfulconsole.com](http://colorfulconsole.com). :star:361
* [dotnet-docker](https://github.com/dotnet/dotnet-docker) - The base Docker images for working with .NET Core and the .NET Core Tools. :star:424
* [go-dotnet](https://github.com/matiasinsaurralde/go-dotnet) - Go wrapper for the .NET Core Runtime. :star:183
* [msbuild](https://github.com/Microsoft/msbuild) - The Microsoft Build Engine is a platform for building applications. :star:3331
* [vsts-agent](https://github.com/Microsoft/vsts-agent/blob/master/README.md) - Visual Studio Team Services Build and Release Agent.

### Bundling and Minification
* [BundlerMinifier](https://github.com/madskristensen/BundlerMinifier) - Visual Studio extension that let's you configure bundling and minification of JS, CSS and HTML files. :star:261
* [JavaScriptViewEngine](https://github.com/pauldotknopf/JavaScriptViewEngine) - ASP.NET MVC ViewEngine for rendering markup in a JavaScript environment. Ideal for React and Angular server-side rendering. :star:57
* [Smidge](https://github.com/Shazwazza/Smidge/) - Lightweight runtime CSS/JavaScript file minification, combination, compression & management library for ASP.NET Core.
* [Web Markup Minifier](https://github.com/Taritsyn/WebMarkupMin) - .NET library that contains a set of markup minifiers. The objective of this project is to improve the performance of web applications by reducing the size of HTML, XHTML and XML code. :star:136

### Caching
* [CacheManager](https://github.com/MichaCo/CacheManager) - Open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features. [http://cachemanager.michaco.net](http://cachemanager.michaco.net)
* [Foundatio](https://github.com/exceptionless/Foundatio) - Pluggable foundation blocks for building distributed apps. :star:690
* [Microsoft Caching](https://github.com/aspnet/Caching) - Libraries for in-memory caching and distributed caching. :star:344
* [Stack Exchange Redis](https://github.com/StackExchange/StackExchange.Redis) - High performance general purpose redis client for .NET languages (C# etc). :star:2560

### CMS
* [Blogifier.Core](https://github.com/blogifierdotnet/Blogifier.Core) - ASP.NET applications to provide common blogging functionality. :star:125
* [Lynicon](https://github.com/jamesej/lyniconanc) - O/S ASP.Net Core/.Net Core CMS with paid for modules: JSON content, works with variety of data stores, c# content types :star:35
* [Orchard Core CMS](https://github.com/OrchardCMS/OrchardCore) - Open Source Content Management System built with ASP.NET Core on top of a Modular and Extensible Application Framework. :star:1425
* [NetCoreCMS](https://github.com/OnnoRokomSoftware/NetCoreCMS) - An Open source ASP.NET Core 2.0 CMS. It currently supports MySQL and planned to implement MSSQL, SQLite and PostgreSQL. Also it is a modular CMS supports theme, skin, custom layout, widgets, multiple language (En, BN). :star:43
* [Platformus](https://github.com/Platformus) - Free, open source and cross-platform CMS based on ASP.NET Core 1.0 and ExtCore framework.
* [SimpleContent](https://github.com/joeaudette/cloudscribe.SimpleContent) - Simple, yet flexible content and blog engine for ASP.NET Core that can work with or without a database. :star:176
* [Squidex](https://github.com/Squidex/squidex) - Headless CMS, based on MongoDB, CQRS and Event Sourcing. :star:221
* [Weapsy](https://github.com/Weapsy/Weapsy) - Open source ASP.NET Core CMS based on DDD and CQRS. It supports MSSQL, MySQL, SQLite and PostgreSQL out of the box. :star:404

### Code Analysis and Metrics
* [App.Metrics](https://github.com/alhardy/AppMetrics) - App Metrics is an open-source and cross-platform .NET library used to record and report metrics within an application and reports it's health. See the [docs](https://alhardy.github.io/app-metrics-docs/) for me details. :star:565
* [AspNet.Metrics](https://github.com/alhardy/aspnet-metrics) - Capturing CLR, application-level web request metrics. Middleware and extensions using [Metrics.Net](https://github.com/Recognos/Metrics.NET). :star:10
* [Audit.NET](https://github.com/thepirat000/Audit.NET) - Small framework to audit .NET object changes. :star:401
* [BenchmarkDotNet](https://github.com/PerfDotNet/BenchmarkDotNet) - Powerful .NET library for benchmarking. :star:2554
* [Foundatio](https://github.com/exceptionless/Foundatio#metrics) - A common interface with in memory, redis, StatsD, and Metrics.NET implementations. :star:690
* [NBench](https://github.com/petabridge/NBench) - Performance benchmarking and testing framework for .NET applications. :star:397
* [OpenCover](https://github.com/OpenCover/opencover) - Code coverage tool for .NET 2 and above (WINDOWS OS only), support for 32 and 64 processes with both branch and sequence points. :star:854
* [RefactoringEssentials](https://github.com/icsharpcode/RefactoringEssentials) - Refactoring Essentials for Visual Studio. :star:550

### Compression
* [lz4net](https://github.com/MiloszKrajewski/lz4net) - Ultra fast compression algorithm for all .NET platforms. :star:205
* [sharpcompress](https://github.com/adamhathcock/sharpcompress) - Fully managed C# library to deal with many compression types and formats. :star:645

### Compilers, Transpilers and Languages
* [roslyn](https://github.com/dotnet/roslyn) - The .NET Compiler Platform ("Roslyn") provides open-source C# and Visual Basic compilers with rich code analysis APIs. :star:8766
* [Sprache](https://github.com/sprache/Sprache) - Tiny C# Monadic Parser Framework. :star:981

### Cryptography
* [BCrypt.NET-Core](https://github.com/neoKushan/BCrypt.Net-Core) - .NET Core port of BCrypt.NET used to store passwords securely. :star:58
* [BouncyCastle PCL](https://github.com/onovotny/BouncyCastle-PCL) - The Bouncy Castle Crypto package is a C# implementation of cryptographic algorithms and protocols. :star:87

### Database
* [DBreeze](https://github.com/hhblaze/DBreeze) - C# .NET MONO NOSQL (key value store embedded) ACID multi-paradigm database management system. :star:181
* [NoDb](https://github.com/joeaudette/NoDb) - "no database" file system storage for .NET Core/ASP.NET Core because not every project needs a database. :star:117
* [marten](https://github.com/JasperFx/marten) - Postgresql as a Document Database and Event Store for .NET Applications [http://jasperfx.github.io/marten](http://jasperfx.github.io/marten). :star:694
* [yessql](https://github.com/sebastienros/yessql) - .NET document database working on any RDBMS. :star:383

### Database Drivers
* [cassandra-csharp-driver](https://github.com/datastax/csharp-driver) - DataStax C# Driver for Apache Cassandra. :star:266
* [confluent-kafka-dotnet](https://github.com/confluentinc/confluent-kafka-dotnet) - Confluent's Apache Kafka .NET client. :star:375
* [LiteDB](https://github.com/mbdavid/LiteDB) - .NET NoSQL Document Store in a single data file - [http://www.litedb.org](http://www.litedb.org). :star:2620
* [MongoDB.Driver](https://github.com/mongodb/mongo-csharp-driver) - .NET Driver for MongoDB. :star:1777
* [mysql-connector-net](https://github.com/mysql/mysql-connector-net/tree/7.0) - Connector/Net is a fully-managed ADO.NET driver for MySQL. [https://dev.mysql.com/downloads/connector/net](https://dev.mysql.com/downloads/connector/net/)
* [Neo4jClient](https://github.com/Readify/Neo4jClient/tree/DotNetCore) - .NET client binding for Neo4j.
* [npgsql](https://github.com/npgsql/npgsql) - .NET data provider for PostgreSQL. It allows any program developed for .NET framework to access a PostgreSQL database server. It is implemented in 100% C# code. PostgreSQL versions since 9.1 are officially supported, others may work. [http://www.npgsql.org](http://www.npgsql.org)
* [ravendb](https://github.com/ayende/ravendb/tree/v4.0) - Linq enabled document database for .NET.
* [RethinkDb.Driver](https://github.com/bchavez/RethinkDb.Driver) - C#/.NET RethinkDB driver with 100% ReQL API coverage. :star:239
* [progaudi.tarantool](https://github.com/progaudi/progaudi.tarantool) - .NET client for Tarantool NoSql database. :star:25

### Date and Time
* [Exceptionless.DateTimeExtensions](https://github.com/exceptionless/Exceptionless.DateTimeExtensions) - DateTimeRange, Business Day and various DateTime, DateTimeOffset, TimeSpan extension methods. :star:36
* [FluentDateTime](https://github.com/FluentDateTime/FluentDateTime) - Allows you to write cleaner DateTime expressions and operation. Partially inspired by Ruby DateTime Extensions. :star:120
* [nodatime](https://github.com/nodatime/nodatime) - Better date and time API for .NET [http://nodatime.org](http://nodatime.org). :star:809

### Distributed Computing
* [Foundatio](https://github.com/exceptionless/Foundatio) - Pluggable foundation blocks for building distributed apps. :star:690

### E-Commerce and Payments
* [SimplCommerce](https://github.com/simplcommerce/SimplCommerce) - Super simple ecommerce system built on .NET Core. :star:1025
* [Stripe](https://github.com/ServiceStack/Stripe) - Typed .NET clients for stripe.com REST APIs. :star:126

### Exceptions
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) - Exceptionless .NET Client :star:147

### Functional Programming
* [CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions) - Functional Extensions for C#. :star:186
* [Giraffe](https://github.com/dustinmoris/Giraffe) - A native functional ASP.NET Core web framework for F# developers. :star:585
* [language-ext](https://github.com/louthy/language-ext) - C# functional language extensions and 'Erlang like' concurrency system. :star:1817
* [NetMQ.ReactiveExtensions](https://github.com/NetMQ/NetMQ.ReactiveExtensions) - Effortlessly send messages anywhere on the network using Reactive Extensions (RX). Transport protocol is ZeroMQ. :star:40
* [Optional](https://github.com/nlkl/Optional) - A robust option type for C#. :star:255
* [reactive-streams-dotnet](https://github.com/reactive-streams/reactive-streams-dotnet) - [Reactive Streams](http://www.reactive-streams.org/) for .NET. :star:97
* [ReactiveUI](https://github.com/reactiveui/ReactiveUI) - A MVVM framework that integrates with the Reactive Extensions for .NET to create elegant, testable User Interfaces that run on any mobile or desktop platform. :star:3499
* [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET) - The [Reactive Extensions](http://reactivex.io) for .NET. :star:2392
* [Qactive](https://github.com/RxDave/Qactive) - Reactive queryable observable framework. `4.x.x or above` :star:92
* [sodium](https://github.com/SodiumFRP/sodium/tree/master/c%23) - Functional Reactive Programming (FRP) Library. `4.x.x or above`

### Graphics
* [ImageProcessor](https://github.com/JimBobSquarePants/ImageProcessor) - A fluent wrapper around System.Drawing for the processing of image files [http://imageprocessor.org](http://imageprocessor.org). `4.5.x or above` :star:1810
* [ImageSharp](https://github.com/JimBobSquarePants/ImageSharp) - Cross-platform library for processing of image files written in C# [http://imageprocessor.org](http://imageprocessor.org). :star:1543
* [QRCoder](https://github.com/codebude/QRCoder) - A pure C# Open Source QR Code implementation. :star:675
* [Structure.Sketching](https://github.com/JaCraig/Structure.Sketching) - Image processing library for use in .NET applications that supports .NET Core. :star:47
* [veldrid](https://github.com/mellinoe/veldrid) - A low-level, hardware-accelerated 3D graphics library for .NET. :star:301

### GUI
* [Avalonia](https://github.com/AvaloniaUI/Avalonia) - A multi-platform .NET UI framework (formerly known as Perspex). :star:3392
* [AvaloniaEdit](https://github.com/AvaloniaUI/AvaloniaEdit/) - The Avalonia-based text editor component forked from [AvalonEdit](https://github.com/icsharpcode/AvalonEdit) :star:545
* [WinApi](https://github.com/prasannavl/WinApi) - A simple, direct, ultra-thin CLR library for high-performance Win32 Native Interop with automation, windowing, DirectX, OpenGL and Skia helpers. :star:194

### IDE
* [Mono](https://github.com/mono/monodevelop) - MonoDevelop enables developers to quickly write desktop and web applications on Linux, Windows and Mac OS X. It also makes it easy for developers to port .NET applications created with Visual Studio to Linux and Mac OS X maintaining a single code base for all platforms. :star:1984
* [rider](https://www.jetbrains.com/rider/) - Cross-platform C# IDE based on the IntelliJ platform and ReSharper.
* [Omnisharp](http://www.omnisharp.net/) - Family of Open Source projects, each with one goal: To enable a great .NET experience in YOUR editor of choice.
* [SharpDevelop](https://github.com/icsharpcode/SharpDevelop) - SharpDevelop is a free Integrated Development Environment (IDE) for C#, VB.NET, Boo, IronPython, IronRuby and F# projects on Microsoft's .NET platform. It is written (almost) entirely in C#, and comes with features you would expect in an IDE plus a few more. :star:1200
* [Visual Studio Code](https://github.com/Microsoft/vscode) - New type of tool that combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. Code provides comprehensive editing and debugging support, an extensibility model, and lightweight integration with existing tools. :star:43254
* [Visual Studio Community](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx) - Free editor for individual developers, open source projects, academic research, education, and small professional teams.

### Internationalization
* [Localization](https://github.com/aspnet/Localization) - Localization abstractions and implementations for ASP.NET Core applications. :star:114

### IOC
* [AutoDI](https://github.com/Keboo/AutoDI) - Super-fast compile-time dependency injection using IL weaving. :star:11
* [Autofac](https://github.com/autofac/Autofac) - Addictive .NET IoC container. :star:1858
* [Castle.Windsor](https://github.com/castleproject/Windsor) Castle Windsor is a best of breed, mature Inversion of Control container available for .NET.
* [DryIoc](https://bitbucket.org/dadhi/dryioc) - Fast, small, full-featured IoC Container for .NET.
* [LightInject](https://github.com/seesharper/LightInject) - Ultra lightweight IoC container [http://www.lightinject.net](http://www.lightinject.net). :star:273
* [SimpleInjector](https://github.com/simpleinjector/SimpleInjector) - Easy, flexible, and fast Dependency Injection library that promotes best practice to steer developers towards the pit of success. :star:546
* [Stashbox](https://github.com/z4kn4fein/stashbox) - A lightweight, portable dependency injection framework for .NET based solutions. :star:17
* [StructureMap](https://github.com/structuremap/structuremap) - Dependency Injection/Inversion of Control tool for .NET. :star:791

### Logging
* [common-logging](https://github.com/net-commons/common-logging) - Portable logging abstraction for .NET [http://net-commons.github.io/common-logging](http://net-commons.github.io/common-logging). :star:527
* [dnxcore-logging-logstash](https://github.com/jvandevelde/dnxcore-logging-logstash) - Logstash logging extension for .NET Core applications with UDP and Redis transports. :star:5
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) - Exceptionless .NET Client :star:147
* [Foundatio](https://github.com/exceptionless/Foundatio#logging) - A fluent logging api that can be used to log messages throughout your application. :star:690
* [LibLog](https://github.com/damianh/LibLog) - Single file for you to either copy/paste or install via nuget, into your library/ framework/ application to provide a logging abstraction. :star:592
* [log4net](https://github.com/apache/logging-log4net) - log4net is a port of the excellent Apache log4j™ framework to the Microsoft® .NET runtime. :star:136
* [NLog](https://github.com/NLog/NLog) - Advanced .NET, Silverlight and Xamarin Logging. :star:2831
* [Q42.Logging.ApplicationInsights](https://github.com/Q42/Q42.Logging.ApplicationInsights) - Log appender for the build in ASP.NET Core logging to send all logs to Application Insights. :star:2
* [serilog](https://github.com/serilog/serilog) - Simple .NET logging with fully-structured events. :star:1731

### Machine Learning and Data Science
* [Spreads](https://github.com/Spreads/Spreads/) - Series and Panels for Real-time and Exploratory Analysis of Data Streams.

### Mail
* [MailBody](https://github.com/doxakis/MailBody) - Create transactional email with a fluent interface (.NET). :star:71
* [MailKit](https://github.com/jstedfast/MailKit) - Cross-platform .NET library for IMAP, POP3, and SMTP. :star:1793
* [MailMergeLib](https://github.com/axuno/MailMergeLib) - SMTP mail client library which provides comfortable mail merge capabilities for text, inline images and attachments, as well as good throughput and fault tolerance for sending mail messages. :star:43
* [MimeKit](https://github.com/jstedfast/MimeKit) - Cross-platform .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools. :star:687
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net/tree/dotnet-core) - C# library that moves your stylesheets to inline style attributes, for maximum compatibility with E-mail clients.
* [SendGrid Client](https://github.com/0xdeafcafe/sendgrid-dotnet) - C# library for the SendGrid v3 mail endpoint. :star:14
* [StrongGrid](https://github.com/Jericho/StrongGrid) - Client for SendGrid's v3 API. Not only allows you to send emails, but also allows you to bulk import contacts, manage lists and segments, create custom fields for your lists, etc. Also includes a parser for SendGrid Webhooks. :star:37

### Mathematics
* [UnitConversion](https://github.com/Stratajet/UnitConversion) - Expansible Unit Conversion Library for .NET Core and .NET Framework. :star:33

### Misc
* [AngleSharp](https://github.com/AngleSharp/AngleSharp) - The ultimate angle brackets parser library. It parses HTML5, MathML, SVG and CSS to construct a DOM based on the official W3C specification. Comparable to beautifulsoup4 of python. :star:1794
* [aspnetcore-health](https://github.com/lurumad/aspnetcore-health) - Enables load balancers to monitor the status of deployed Web applications. :star:40
* [AutoMapper](https://github.com/AutoMapper/AutoMapper) - Convention-based object-object mapper in .NET. :star:5173
* [Castle.Core](https://github.com/castleproject/Core) - Castle Core, including Castle DynamicProxy, Logging Services and DictionaryAdapter [http://www.castleproject.org](http://www.castleproject.org). :star:651
* [Chessie](https://github.com/fsprojects/Chessie) - Railway-oriented programming for .NET [http://fsprojects.github.io/Chessie](http://fsprojects.github.io/Chessie). :star:114
* [CommonMark.NET](https://github.com/Knagis/CommonMark.NET) - The implementation of CommonMark specification in C# for converting Markdown documents to HTML. :star:736
* [datatables](https://github.com/ALMMa/datatables.aspnet/tree/dev) - Microsoft ASP.NET server-side support and helpers for jQuery DataTables.
* [Enums.NET](https://github.com/TylerBrinkley/Enums.NET) - Enums.NET is a high-performance type-safe .NET enum utility library :star:495
* [FluentFTP](https://github.com/robinrodricks/FluentFTP/) - FTP and FTPS client, with extensive FTP commands, SSL/TLS connections, hashing/checksums and more.
* [httpclient-interception](https://github.com/justeat/httpclient-interception) - .NET Standard library for intercepting server-side HTTP dependencies. :star:22
* [Humanizer](https://github.com/Humanizr/Humanizer) - Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities. :star:3047
* [LibSass Host](https://github.com/Taritsyn/LibSassHost) - .NET wrapper around the [libSass](http://sass-lang.com/libsass) library with the ability to support a virtual file system. :star:20
* [markdig](https://github.com/lunet-io/markdig) - Fast, powerfull, CommonMark compliant, extensible Markdown processor for .NET. :star:794
* [NReco.LambdaParser](https://github.com/nreco/lambdaparser) - Parses string expressions (formulas, methods calls, conditions) to LINQ expression tree that can be compiled to lambda and evaluated. :star:59
* [NReco.PivotData](https://www.nuget.org/packages/NReco.PivotData) - In-memory data cube with OLAP operations and PivotTable data model.
* [Ocelot](https://github.com/TomPallister/Ocelot) - API Gateway created using .NET Core. :star:995
* [readline](https://github.com/tsolarin/readline) - Pure C# GNU-Readline like library for .NET/.NET Core. :star:433
* [reCAPTCHA](https://github.com/PaulMiami/reCAPTCHA) - reCAPTCHA 2.0 for ASP.NET Core. :star:56
* [Relinq](https://github.com/re-motion/Relinq) - With re-linq, it's now easier than ever to create full-featured LINQ providers. :star:217
* [ReverseMarkdown](https://github.com/mysticmind/reversemarkdown-net) - Html to Markdown converter library. :star:27
* [PdfReport.Core](https://github.com/VahidN/PdfReport.Core) - PdfReport.Core is a code first reporting engine, which is built on top of the iTextSharp.LGPLv2.Core and EPPlus.Core libraries. :star:77
* [Polly](https://github.com/App-vNext/Polly) - .NET 3.5 / 4.0 / 4.5 / PCL library that allows developers to express transient exception and fault handling policies such as Retry, Retry Forever, Wait and Retry or Circuit Breaker in a fluent manner. :star:3506
* [Scrutor](https://github.com/khellang/Scrutor) - Assembly scanning extensions for Microsoft.Extensions.DependencyInjection. :star:211
* [SmartFormat.NET](https://github.com/scottrippey/SmartFormat.NET) - An extensible replacement for string.Format. :star:337
* [System.Linq.Dynamic.Core](https://github.com/StefH/System.Linq.Dynamic.Core) - The .NET Standard (.NET Core) version from the System Linq Dynamic functionality. :star:163
* Validation
  * [FluentValidation](https://github.com/JeremySkinner/FluentValidation) - Small validation library for .NET that uses a fluent interface and lambda expressions for building validation rules. :star:2908
  * [Valit](https://github.com/valit-stack/Valit) - A dead simple validation for .NET Core. No more if-statements all around your code. Write nice and clean fluent validators instead! :star:122
* [warden-stack](https://github.com/warden-stack) - "health checks" for your applications, resources and infrastructure. Keep your Warden on the watch.

### ORM
* [Entity Framework Core](https://github.com/aspnet/EntityFramework) - Familiar developer experience to previous versions of EF, including LINQ, POCO, and Code First support. :star:5448
  * [LINQKit](https://github.com/scottksmith95/LINQKit) - A free set of extensions for LINQ to SQL and Entity Framework power users. :star:346
  * [Pomelo.EntityFrameworkCore.MySql](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MySql) - Entity Framework Core provider for MySql built on top of mysql-net/MySqlConnector. :star:516
* [Dapper](https://github.com/StackExchange/Dapper) - Simple object mapper for .NET. :star:7934
  * [Dapper-FluentMap](https://github.com/henkmollema/Dapper-FluentMap) - Provides a simple API to fluently map POCO properties to database columns when using Dapper. :star:130
  * [Dommel](https://github.com/henkmollema/Dommel) - Simple CRUD operations for Dapper. :star:88
  * [MicroOrm.Dapper.Repositories](https://github.com/phnx47/MicroOrm.Dapper.Repositories) - CRUD for Dapper. :star:154
* [EntityFramework-Plus](https://github.com/zzzprojects/EntityFramework-Plus) - Entity Framework Utilities | Bulk Operations | Batch Delete | Batch Update | Query Cache | Query Filter | Query Future | Query Include | Audit :star:688
* [Limebean](https://nick-lucas.github.io/LimeBean/) - Hybrid-ORM, designed to be simple to use and not totally hide SQL, while having all the nice things you expect from an ORM. Inspired by RedBeanPHP.
* [LINQ to DB (linq2db)](https://linq2db.github.io/) - The fastest LINQ database access library offering a simple, lightweight, fast, and type-safe layer between your POCO objects and your database for more than 10 database engines with full SQL support.
* [NEventStore](https://github.com/NEventStore/NEventStore/tree/feature/dotnetcore) - Persistence library used to abstract different storage implementations when using event sourcing as storage mechanism. This library is developed with a specific focus on DDD/CQRS applications.
* [NPoco](https://github.com/schotime/NPoco) - Simple microORM that maps the results of a query onto a POCO object. Project based on Schotime's branch of PetaPoco. :star:554
* [NReco.Data](https://github.com/nreco/data) - Lightweight provider-independent DAL for SQL commands generation, CRUD operations and simple POCO mapping. :star:71
* [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite) - Light, simple and fast convention-based POCO ORM. :star:1057
* [SqlFu](https://github.com/sapiens/SqlFu) - Fast and versatile Micro-ORM. :star:206

### Profiling
* [Glimpse](http://getglimpse.com) - Lightweight, open-source, real-time diagnostics and insights profiler for .NET.
* [MiniProfiler](https://github.com/MiniProfiler/dotnet) - A simple but effective mini-profiler for ASP.NET websites. :star:1066
* [roslyn-analyzers](https://github.com/dotnet/roslyn-analyzers) - Number of Roslyn diagnostic analyzers initially developed to help flesh out the design and implementation of the static analysis APIs. :star:292

### Queue and Messaging
* [emitter](https://emitter.io/) - Free open source real-time messaging service that connects all devices. This publish-subscribe messaging API is built for speed and security.
* [EventStore](https://github.com/EventStore/EventStore) - The open-source, functional database with Complex Event Processing in JavaScript. [https://geteventstore.com](https://geteventstore.com)
* [Foundatio](https://github.com/exceptionless/Foundatio#queues) - A common interface with in memory, redis and azure implementations. :star:690
* [MediatR](https://github.com/jbogard/MediatR) - Simple, unambitious mediator implementation in .NET. :star:1598
 * [MediatR.Extensions.Microsoft.DependencyInjection](https://github.com/jbogard/MediatR.Extensions.Microsoft.DependencyInjection) - MediatR extensions for Microsoft.Extensions.DependencyInjection. :star:22
* [Mediator.Net](https://github.com/mayuanyang/Mediator.Net) - A simple mediator for .Net for sending command, publishing event and request response with pipelines supported. :star:87
* [MicroBus](https://github.com/Lavinski/Enexure.MicroBus) - Simple in process mediator for .NET. :star:123
* [netmq](https://github.com/zeromq/netmq) - 100% native C# implementation of ZeroMQ for .NET. :star:1256
* [rabbitmq-dotnet-client](https://github.com/rabbitmq/rabbitmq-dotnet-client) - RabbitMQ .NET client [https://www.rabbitmq.com](https://www.rabbitmq.com). :star:544
* [RawRabbit](https://github.com/pardahlman/RawRabbit) - Modern .NET framework for communication over RabbitMq. :star:309
* [Rebus](https://github.com/rebus-org/Rebus) - Simple and lean service bus implementation for .NET. :star:716
* [Restbus](http://restbus.org) - Messaging library for RabbitMq.
* [Tossit](https://github.com/turgayozgur/tossit) - Simple, easy to use library for distributed job/worker logic. Distributed messages handled by built in RabbitMQ implementation. :star:30

### Scheduler and Job
* [Chroniton.NetCore](https://github.com/leosperry/Chroniton) - Lightweight robust library for running tasks(jobs) on schedules. :star:107
* [FluentScheduler](https://github.com/fluentscheduler/FluentScheduler) - Automated job scheduler with fluent interface. :star:1159
* [HangfireIO](https://github.com/HangfireIO/Hangfire) - Easy way to perform fire-and-forget, delayed and recurring tasks inside ASP.NET apps [http://hangfire.io](http://hangfire.io). :star:3320
* [LiquidState](https://github.com/prasannavl/LiquidState) - Efficient asynchronous and synchronous state machines for .NET :star:91
* [quartznet](https://github.com/quartznet/quartznet/) - Quartz Enterprise Scheduler .NET [http://www.quartz-scheduler.net](http://www.quartz-scheduler.net).
* [stateless](https://github.com/dotnet-state-machine/stateless) - Simple library for creating state machines in C# code. :star:1951

### SDKs
* [AWS SDK](https://github.com/aws/aws-sdk-net) - The Amazon Web Services (AWS) .NET Core SDK components. Each AWS service has its own NuGet package. :star:795
* [azure-event-hubs-dotnet](https://github.com/azure/azure-event-hubs-dotnet) - .NET Standard client library for Azure Event Hubs. :star:48
* Blockchain clients
  * [Bittrex.Net](https://github.com/JKorf/Bittrex.Net) - C# .Net wrapper for the Bittrex web API including all features easily accessible and usable. :star:66
  * [Binance.Net](https://github.com/JKorf/Binance.Net) - .Net API wrapper for the Binance web API. :star:17
* [consuldotnet](https://github.com/PlayFab/consuldotnet/tree/develop) - .NET API for Consul.
* [DarkSkyCore](https://github.com/amweiss/dark-sky-core) - A .NET Standard wrapper for the [Dark Sky API](https://darksky.net/dev/docs). :star:19
* [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) - .NET (C#) Client Library for Docker API. :star:447
* [Microphone](https://github.com/rogeralsing/Microphone) - Lightweight framework to run self hosting REST services using Web Api or NancyFx ontop of a Consul or ETCD cluster. :star:421
* [NetTelegramBotApi](https://github.com/justdmitry/NetTelegramBotApi) - C# client library for building Telegram bot [https://core.telegram.org/bots/api](https://core.telegram.org/bots/api). :star:46
* [octokit.net](https://github.com/octokit/octokit.net) - GitHub API client library for .NET. :star:1398
* [Open-XML-SDK](https://github.com/OfficeDev/Open-XML-SDK) - The Open XML SDK provides tools for working with Office Word, Excel, and PowerPoint documents. :star:1511
* [PreStorm](https://github.com/jshirota/PreStorm) - Parallel REST Client for ArcGIS Server. :star:11
* [SendGrid-csharp](https://github.com/sendgrid/sendgrid-csharp) - C# client library for using the full SendGrid API. :star:428
* [statsd-csharp-client](https://github.com/Pereingo/statsd-csharp-client) - .NET Standard compatible C# client to interface with Etsy's excellent [statsd](https://github.com/etsy/statsd) server. :star:97
* [tweetinvi](https://github.com/linvi/tweetinvi) - Intuitive .NET C# library to access the Twitter REST and STREAM API. :star:431

### Security
* [HtmlSanitizer](https://github.com/mganss/HtmlSanitizer) - Cleans HTML to avoid XSS attacks. :star:388
* [jose-jwt](https://github.com/dvsekhvalnov/jose-jwt) - Library for processing JOSE objects (JWT, JWA, JWS and related). :star:379
* [NWebsec](https://github.com/NWebsec/NWebsec) - Security libraries for ASP.NET [https://www.nwebsec.com](https://www.nwebsec.com). :star:231
* [roslyn-security-guard](https://github.com/dotnet-security-guard/roslyn-security-guard) - Roslyn analyzers that aim to help security audit on .NET applications. :star:172
* [OwaspHeaders](https://github.com/GaProgMan/OwaspHeaders.Core) - .NET Core middleware for injecting the Owasp recommended HTTP Headers for increased security. :star:14
* [Security](https://github.com/aspnet/Security) - Middleware for security and authorization of web apps. :star:812

### Searching
* [AutoComplete](https://github.com/omerfarukz/autocomplete) - Persistent, simple, powerful and portable autocomplete library. :star:27
* [Elasticsearch.Net & NEST](https://github.com/elastic/elasticsearch-net) - Repository for both NEST and Elasticsearch.NET, the two official elasticsearch .NET clients. :star:1679
* [ElasticsearchCRUD](https://github.com/damienbod/ElasticsearchCRUD) - Elasticsearch .NET API. :star:92
* [SolrExpress](https://github.com/solr-express/solr-express) - Simple and lightweight query .NET library for Solr, in a controlled, buildable and fail fast way. :star:48

### Serialization
* [bond](https://github.com/Microsoft/bond) - Cross-platform framework for working with schematized data. It supports cross-language de/serialization and powerful generic mechanisms for efficiently manipulating data. Bond is broadly used at Microsoft in high scale services. :star:1684
* [Channels](https://github.com/davidfowl/Channels) - Push based .NET Streams. :star:291
* [CsvHelper](https://github.com/JoshClose/CsvHelper) - Library to help reading and writing CSV files [http://csvhelper.com](http://csvhelper.com). :star:1643
* [Edi.Net](https://github.com/indice-co/EDI.Net) - EDI Serializer/Deserializer. Supports EDIFact, X12 and TRADACOMS format. :star:79
* [ExtendedXmlSerializer](https://github.com/wojtpl2/ExtendedXmlSerializer) - Extended Xml Serializer for .NET. :star:51
* [Jil](https://github.com/kevin-montrose/Jil) - Fast .NET JSON (De)Serializer, Built On Sigil. :star:1658
* [msgpack-cli](https://github.com/msgpack/msgpack-cli) - MessagePack implementation for Common Language Infrastructure / [msgpack.org](http://msgpack.org). :star:534
* [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) - Popular high-performance JSON framework for .NET. :star:5152
* [protobuf-net](https://github.com/mgravell/protobuf-net/) - Protocol Buffers library for idiomatic .NET.
* [Schema.NET](https://github.com/RehanSaeed/Schema.NET) - Schema.org objects turned into strongly typed C# POCO classes for use in .NET. All classes can be serialized into JSON/JSON-LD and XML, typically used to represent structured data in the head section of html page. :star:104
* [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text) - JSON, JSV and CSV Text Serializers. :star:887
* [TinyCsvParser](https://github.com/bytefish/TinyCsvParser) - Easy to use, easy to extend and high-performance library for CSV parsing with .NET. :star:53
* [Wire](https://github.com/rogeralsing/Wire) - Binary serializer for POCO objects. :star:311
* [YamlDotNet](https://github.com/aaubry/YamlDotNet) - .NET :star:580
* [ZeroFormatter](https://github.com/neuecc/ZeroFormatter) - Fast binary (de)serializer for .NET. :star:985
* [YAXLib](https://github.com/sinairv/YAXLib) - XML Serialization Library for the .NET Framework and .NET Core. Extremely flexible and powerful. :star:72

### Testing
* [Bogus](https://github.com/bchavez/Bogus) - Simple and sane fake data generator for C#. Based on and ported from the famed faker.js. :star:855
* [GenFu](https://github.com/MisterJames/GenFu) - Library you can use to generate realistic test data. :star:317
* [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy) - The easy mocking library for .NET. :star:728
* [FluentAssertions](https://github.com/dennisdoomen/FluentAssertions) - Set of .NET extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style test. :star:16
* [moq.netcore](https://github.com/Moq/moq4) - Most popular and friendly mocking framework for .NET. :star:2163
* [MSpec](https://github.com/machine/machine.specifications) - Popular testing framework for writing BDD-style tests. :star:700
* [MyTested.AspNetCore.Mvc](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc) - Fluent testing :star:723
  framework for ASP.NET Core MVC.
* [Netling](https://github.com/hallatore/Netling) - Load tester client for easy web testing. :star:815
* [NSpec](https://github.com/nspec/NSpec) - Battle hardened testing framework for C# that's heavily inspired by Mocha and RSpec. :star:200
* [NSubstitute](https://github.com/nsubstitute/NSubstitute) - A friendly substitute for .NET mocking frameworks. :star:928
* [nunit](https://github.com/nunit/dotnet-test-nunit) - NUnit test runner for .NET Core. :star:65
* [shouldly](https://github.com/shouldly/shouldly) - Should testing for .NET - the way Asserting *Should* be! [http://shouldly.readthedocs.org/en/latest](http://shouldly.readthedocs.org/en/latest)
* [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore) - Pragmatic BDD solution for .NET. It uses the Gherkin specification language and integrates to Visual Studio.
* [Storyteller](https://github.com/storyteller/Storyteller) - Executable Specifications for .NET [http://storyteller.github.io](http://storyteller.github.io). :star:207
* [Stubbery](https://markvincze.github.io/Stubbery/) - A simple library for creating and running Api stubs in .NET.
* [TestStack.BDDfy](https://github.com/TestStack/TestStack.BDDfy) - The simplest BDD framework EVER! :star:236
* [xBehave.net](https://github.com/xbehave/xbehave.net) - An xUnit.net extension for describing your tests using natural language. [http://xbehave.github.io](http://xbehave.github.io)
* [xUnit.net](https://github.com/xunit/xunit) - A free, open source, community-focused unit testing tool for the .NET Framework. [https://xunit.github.io/](https://xunit.github.io/)

### Tools
* [CatLight](https://catlight.io) - Status notifier for developers that monitors builds and tasks in the project. Built using .Net Core and Electron.
* [docfx](https://github.com/dotnet/docfx) - Tools for building and publishing API documentation for .NET projects [http://dotnet.github.io/docfx](http://dotnet.github.io/docfx)
* [dotnetfiddle](https://dotnetfiddle.net) - .NET sandbox for developers to quickly try out code and share code snippets.
* [EntryPoint](https://github.com/Nick-Lucas/EntryPoint) - Composable CLI (Command Line) Argument Parser for .Net Core & .Net Framework 4.5+. :star:95
* [gitignore.io](https://github.com/joeblau/gitignore.io) - Create useful .gitignore files for your project [https://www.gitignore.io](https://www.gitignore.io). :star:2892
* [GitInfo](https://github.com/kzu/GitInfo) - Git and SemVer Info from MSBuild, C# and VB. :star:77
* [ICanHasDotnetCore](https://github.com/OctopusDeploy/ICanHasDotnetCore) - Scans uploaded packages.config files or GitHub repository and determines whether the nuget packages target .NET Standard [https://icanhasdot.net](https://icanhasdot.net). :star:45
* [json2csharp](http://json2csharp.com) - Generate C# classes from JSON.
* [letsencrypt-win-simple](https://github.com/Lone-Coder/letsencrypt-win-simple) - A Simple ACME Client for Windows. :star:1699
* [NuGetPackageExplorer](https://github.com/NuGetPackageExplorer/NuGetPackageExplorer) - Create, update and deploy Nuget Packages with a GUI. :star:714
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through `projects.json` files efficiently with the OctoLinker browser extension for GitHub. :star:2511
* [Opserver](https://github.com/opserver/Opserver) - Stack Exchange's Monitoring System. :star:3284
* [ShareX](https://github.com/ShareX/ShareX) - Free and open source program that lets you capture or record any area of your screen and share it with a single press of a key. It also allows uploading images, text or other types of files to over 80 supported destinations you can choose from. [https://getsharex.com](https://getsharex.com)
* [X.Web.Sitemap](https://github.com/dncuug/X.Web.Sitemap) – Simple sitemap generator for .NET and .NET Core
* [X.Web.RSS](https://github.com/dncuug/X.Web.RSS) – Simple RSS Feed generator for .NET and .NET Core

### Web Framework
* [Blazor](https://github.com/SteveSanderson/Blazor) - UI framework running .NET in the browser via WebAssembly. :star:1809
* [ReactJS.NET](https://github.com/reactjs/React.NET) - .NET library for JSX compilation and server-side rendering of React components. :star:1315
* [redux.NET](https://github.com/GuillaumeSalles/redux.NET) - Predictable state container for .NET apps. Inspired by [https://github.com/reactjs/redux](https://github.com/reactjs/redux). :star:480

### Web Socket
* [SignalR Server](https://github.com/aspnet/signalr) - Real-time web functionality for web apps, including server-side push. :star:1394
* [SuperSocket](https://github.com/kerryjiang/SuperSocket) - Light weight, cross platform and extensible socket server application framework. :star:1158
* [WampSharp](https://github.com/Code-Sharp/WampSharp) - C# implementation of [The Web Application Messaging Protocol](http://wamp-proto.org/) - Protocol that provides messaging patterns of Remote Procedure Calls and Publish/Subscribe over WebSockets.

### Windows Service
* [dotnet-win32-service](https://github.com/dasMulli/dotnet-win32-service) - Set up and run as Windows Service directly from .NET Core. :star:241
* [Topshelf](https://github.com/Topshelf/Topshelf) - Easy service hosting framework for building Windows services using .NET. `4.5.x or above` :star:2244

### Workflow
* [CoreWF](https://github.com/dmetzgar/corewf/) - Port of Windows Workflow Foundation (WF) to .NET Core.
* [workflow-core](https://github.com/danielgerlag/workflow-core) - Lightweight workflow engine for .NET Standard. :star:242

## Starter Kits
* [Arch](https://github.com/Arch) - The collection of .NET Core libraries that are created by software architects who embrace all the new stuff in .NET Core.
* [AspNetCore-Angular2-Universal](https://github.com/MarkPieszak/aspnetcore-angular2-universal) - Cross-platform - w/ server-side rendering for SEO, Bootstrap, i18n internationalization (ngx-translate), Webpack, TypeScript, unit testing w/ Karma, WebAPI REST setup, SignalR, Swagger docs, and more! :star:922
* [ASP.NET Core Starter Kit](https://github.com/kriasoft/aspnet-starter-kit) - Opinionated boilerplate for web development based on .NET Core, Kestrel, GraphQL on the backend and Babel, Webpack, React and Redux on the frontend. This boilerplate comes in both C# and F# flavors. :star:863
* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) - ASP.NET Boilerplate is a starting point for new modern web applications using best practices and most popular tools. It's aimed to be a SOLID model, a general-purpose application framework and a project template. `4.5.x or above` :star:3981
* [aspnetcore-spa generator](https://github.com/aspnet/JavaScriptServices) - Yeoman generator to build a brand-new ASP.NET Core single page application that uses Angular 2 / React / React With Redux / Knockout / Aurelia on the client. :star:2761
* [ASP.Net Core Vue Starter](https://github.com/MarkPieszak/aspnetcore-Vue-starter) - Asp.NETCore 2.0 Vue 2 (ES6) SPA Starter kit, contains routing, Vuex, and more!. :star:335
* [bitwarden-core](https://github.com/bitwarden/core) - The core infrastructure backend (API, database, etc) [https://bitwarden.com](https://bitwarden.com). :star:1105
* [dotNetify](https://github.com/dsuryd/dotNetify) - Simple, lightweight, yet powerful way to build real-time HTML5/C# .NET web apps. :star:365
* [generator-aspnet](https://github.com/OmniSharp/generator-aspnet) - yo generator for ASP.NET Core. :star:878
* [react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate) - Starting point for building isomorphic React applications with ASP.NET Core 1, leveraging existing techniques. :star:256
* [saaskit](https://github.com/saaskit/saaskit) - Developer toolkit for building SaaS applications. :star:581

## Sample Projects
* [AlbumViewerVNext](https://github.com/RickStrahl/AlbumViewerVNext) - West Wind Album Viewer ASP.NET 5 Sample. :star:304
* [allReady](https://github.com/HTBox/allReady) - Open-source solution focused on increasing awareness, efficiency and impact of preparedness campaigns as they are delivered by humanitarian and disaster response organizations in local communities. [http://www.htbox.org/projects/allready](http://www.htbox.org/projects/allready)
* [AspNet5GeoElasticsearch](https://github.com/damienbod/AspNet5GeoElasticsearch) - ASP.NET Core MVC Geo Elasticsearch Swashbuckle Swagger. :star:24
* [aspnet-servicediscovery-patterns](https://github.com/cecilphillip/aspnet-servicediscovery-patterns) - Samples of implementing Service Discovery patterns with ASP.NET Core. :star:134
* [AspNetAuthorizationWorkshop](https://github.com/blowdart/AspNetAuthorizationWorkshop) - A workshop for moving through the various new pieces in ASP.NET Core Authorization :star:605
* [BikeSharing360 Suite of Apps from Microsoft](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/) Presented December Connect 2016 Conference, a compreshsive set of interworking apps for both enterprise users and the consumers (bike riders):
 [Mobile Apps](https://github.com/Microsoft/BikeSharing360_MobileApps), [Backend Services](https://github.com/Microsoft/BikeSharing360_BackendServices), [Websites](https://github.com/Microsoft/BikeSharing360_Websites), [Single Container Apps](https://github.com/Microsoft/BikeSharing360_SingleContainer), [Multi Container Apps](https://github.com/Microsoft/BikeSharing360_MultiContainer), [Cognitive Services Kiosk App](https://github.com/Microsoft/BikeSharing360_CognitiveServicesKioskApp),
 [Azure Bot App](https://github.com/Microsoft/BikeSharing360_BotApps).
* [cloudscribe](https://github.com/joeaudette/cloudscribe) - ASP.NET Core Multi-tenant web application foundation. :star:550
* [CoreCodeCamp](https://github.com/shawnwildermuth/CoreCodeCamp) - An Open Source Website for running small, local development events. :star:37
* [distributed-playground](https://github.com/jvandevelde/distributed-playground) - Distributed service playground with Vagrant, Consul, Docker & ASP.NET Core. :star:17
* [DotNetClub](https://github.com/scheshan/DotNetClub) - Tiny club written in ASP.NET Core. :star:206
* [Entropy](https://github.com/aspnet/Entropy) - Chaotic experimental playground for new features and ideas - check here for small and simple samples for individual features. :star:335
* [EquinoxProject](https://github.com/EduardoPires/EquinoxProject) - Full ASP.NET Core 2.0 application with DDD, CQRS and Event Sourcing. :star:958
* [eShopOnContainers](https://github.com/dotnet/eShopOnContainers) - Microservices Architecture and Containers based Reference Application. :star:4583
* [guidance-identity-management-for-multitenant-apps](https://github.com/Azure-Samples/guidance-identity-management-for-multitenant-apps) - How to manage user identities in a multitenant app on Microsoft Azure, using Azure Active Directory for authentication. :star:45
* [magazine-website](https://github.com/thangchung/magazine-website) - Magazine website (using .NET Core, ASP.NET Core, EF Core) with DDD, CQRS, microservices, asynchronous programming applied. :star:79
* [MegaMine](https://github.com/Nootus/MegaMine) - Open source mining solution that helps miners in extracting Gold, Quartz, Granite etc. This solution is built using ASP.NET Core and AngularJS utilizing multiple light weight components in a Microservices way. :star:19
* [minicompiler](https://github.com/ealsur/minicompiler) - Minification, bundling and compiling sample. :star:7
* [MusicStore](https://github.com/aspnet/MusicStore) - Sample MusicStore application that uses MVC and Entity Framework. :star:1211
* [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) - NLayerAppV3 N-Layered Architecture with .NET Core Preview 2. :star:27
* [Orchard Core - Modular and Multi-tenant applications](https://github.com/OrchardCMS/OrchardCore.Samples) - Use Orchard Core Framework to create Modular and Multi-tenant applications. :star:29
* [ReactiveTraderCloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - Real-time trading platform demo showcasing reactive programming principles applied across the full application stack. :star:783
* [PhotoGallery](https://github.com/chsakell/aspnet5-angular2-typescript) - Cross-platform Single Page Applications with ASP.NET Core, Angular 2 & TypeScript [http://wp.me/p3mRWu-11L](http://wp.me/p3mRWu-11L). :star:333
* [Practical ASP.NET Core](https://github.com/dodyg/practical-aspnetcore) - A daily updated micro samples of ASP.NET Core features and facilities. :star:1064
* [JustA.ML](https://github.com/mustakimali/JustA.ML) - A web application that lets you share files/URL/text between your devices written in ASP.NET Core 2.0. Open source, live at [https://justa.ml](https://justa.ml)

## Articles
* Basic knowledge
  * [A guide to the .NET Core projects on GitHub](https://blog.rendle.io/a-guide-to-the-net-projects-on-github/)
  * [Microsoft architectual overview of comprehensive BikeSharing360 suite of demo apps with related videos](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/)
  * [Porting a .NET Framework library to .NET Core](https://www.codeproject.com/Articles/1190475/Porting-a-NET-Framework-library-to-NET-Core)
  * [The 68 things the CLR does before executing a single line of your code](http://mattwarren.org/2017/02/07/The-68-things-the-CLR-does-before-executing-a-single-line-of-your-code/)
  * The comparison between .NET Core and Nodejs at [here](https://manuel-rauber.com/2016/03/07/node-js-asp-net-core-1-0-a-usage-comparison/), [here](https://gist.github.com/ilyaigpetrov/f6df3e6f825ae1b5c7e2) and [here](https://github.com/thinktecture/nodejs-aspnetcore-webapi)
  * [Understanding ASP.NET Core Initialization](http://developer.telerik.com/featured/understanding-asp-net-core-initialization/)
  * [Why you should join .NET Core and ASP.NET Core train](https://codingblast.com/why-you-should-join-asp-net-core/)
* Cloud Development
  * [Configuring the AWS SDK in .NET Core](https://aws.amazon.com/blogs/developer/configuring-aws-sdk-with-net-core/)
  * [Serverless Architecture using C# and AWS Amazon Gateway Api/Lambda](https://www.codeproject.com/Articles/1178781/Serverless-Architecture-using-Csharp-and-AWS-Amazo)
  * [Using C# and .NET Core in Amazon Web Services (AWS) Lambda](https://aws.amazon.com/blogs/compute/announcing-c-sharp-support-for-aws-lambda/)
* Configuration and deployment
  * [.NET project structure](https://gist.github.com/davidfowl/ed7564297c61fe9ab814)
  * [Adding Travis CI builds to a .NET Core app](http://andrewlock.net/adding-travis-ci-to-a-net-core-app/)
  * [ASP.NET Core 1.0 - Configure ApplicationInsights](http://social.technet.microsoft.com/wiki/contents/articles/35918.asp-net-core-1-0-configure-applicationinsights.aspx)
  * [haproxy, nginx, Angular 2, ASP.NET Core, Redis and Docker](http://tattoocoder.azurewebsites.net/legion-of-heroes-haproxy-nginx-angular2-aspnetcore-redis-docker/)
  * [Project.json to MSBuild conversion guide](http://www.natemcmaster.com/blog/2017/01/19/project-json-to-csproj/)
  * [Publishing a .NET project with Appveyor and NuGet](https://few-lines-of-code.blogspot.com/2016/03/publishing-net-project-with-appveyor.html)
  * [The New Configuration Model in ASP.NET Core](http://developer.telerik.com/featured/new-configuration-model-asp-net-core/)
* Entity Framework Core
  * [.NET Core Data Access](https://blogs.msdn.microsoft.com/dotnet/2016/11/09/net-core-data-access/)
  * [A very good example about EF Core](https://github.com/rowanmiller/Demo-EFCore) :star:96
* Miraculous
  * [Getting started with Orchard Core as a NuGet package](http://www.ideliverable.com/blog/getting-started-with-orchard-core-as-a-nuget-package)
  * [How to export HTML to PDF in ASP.NET Core](https://code.msdn.microsoft.com/How-to-export-HTML-to-PDF-c5afd0ce)
  * [Vue.js server side rendering with ASP.NET Core](http://mgyongyosi.com/2016/Vuejs-server-side-rendering-with-aspnet-core/)
* Security
  * [.NET Continuous Delivery Microservices](http://stackshare.io/tomstaijen/net-continuous-delivery-microservices)
  * [ASP.NET Core 2.0 Authentication and Authorization System Demystified](https://digitalmccullough.com/posts/aspnetcore-auth-system-demystified.html)
  * [A walk-through for an ASP.NET Authorization Lab](https://github.com/blowdart/AspNetAuthorizationWorkshop) :star:605
  * [Authentication in ASP.NET Core](https://stormpath.com/blog/authentication-asp-net-core)
* Testing
  * [Selenium with .NET Core](http://www.dotnetcatch.com/2016/11/23/selenium-with-net-core/)

## Books
* [.NET Core in Action](https://manning.com/books/dotnet-core-in-action)
* [ASP.NET Core Application Development: Building an application in four sprints (Developer Reference)](https://www.amazon.com/ASP-NET-Core-Application-Development-application/dp/1509304061)
* [ASP.NET Core in Action](https://www.manning.com/books/asp-dot-net-core-in-action)
* [ASP.NET Core 1.0 High Performance](https://www.amazon.com/ASP-NET-Core-1-0-High-Performance/dp/1785881892)
* [Building Microservices with ASP.NET Core: Develop, Test, and Deploy Cross-Platform Services in the Cloud](https://www.amazon.com/Building-Microservices-ASP-NET-Core-Cross-Platform/dp/1491961732)
* [C# 6 and .NET Core 1.0: Modern Cross-Platform Development](https://www.amazon.com/NET-Core-1-0-Cross-Platform-Development/dp/1785285696)
* [Dependency Injection in .NET Core, 2nd edition](https://www.manning.com/books/dependency-injection-in-dot-net-second-edition)
* [Microservices in .NET Core: with C#, the Nancy framework, and OWIN middleware](https://www.amazon.com/Microservices-NET-Core-framework-middleware/dp/1617293377)
* [Professional C# 6 and .NET Core 1.0](https://www.amazon.com/Professional-NET-Core-Christian-Nagel/dp/111909660X)
* [The little ASP.NET Core](https://www.recaffeinate.co/book)

## Videos
* [Channel9](https://channel9.msdn.com)
 * [ASP.NET Monsters](https://channel9.msdn.com/Series/aspnetmonsters)
* [Visual Studio](https://www.youtube.com/user/VisualStudio/channels)
* [.NET World](https://www.youtube.com/channel/UClW5uIyHKPhfSEloQxn7b0Q)

## Podcasts
* [.NET Rocks](https://www.dotnetrocks.com)
* [Static Void Podcast](https://www.staticvoidpodcast.com)
* [The sound of .NET](http://thesoundof.net/?q=.NET+Core)

## Community
* [ASP.NET](https://forums.asp.net)
* [.NET Foundation](http://forums.dotnetfoundation.org)
* [Channel9](https://channel9.msdn.com/Forums)
* [Slack](http://tattoocoder.com/aspnet-slack-sign-up)
* Stack Overflow
  *  [.NET Core](https://stackoverflow.com/questions/tagged/.net-core)
  *  [CoreCLR](https://stackoverflow.com/questions/tagged/coreclr)
  *  [ASP.NET Core](https://stackoverflow.com/questions/tagged/asp.net-core)
  *  [ASP.NET Core MVC](https://stackoverflow.com/questions/tagged/asp.net-core-mvc)
  *  [ASP.NET Core 1.0](https://stackoverflow.com/questions/tagged/asp.net-core-1.0)
  *  [Entity Framework Core](https://stackoverflow.com/questions/tagged/entity-framework-core)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [thangchung](http://weblogs.asp.net/thangchung) has waived all copyright and related or neighboring rights to this work.


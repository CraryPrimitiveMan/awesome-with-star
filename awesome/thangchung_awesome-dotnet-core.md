# Information comes from [thangchung/awesome-dotnet-core](https://github.com/thangchung/awesome-dotnet-core)
# Awesome .NET Core [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Inspired by [awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet),  [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks).

Contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/thangchung/awesome-dotnet-core/blob/master/contributing.md) pages first. We accept proprietary and commercial software too.

Thanks to all [contributors](https://github.com/thangchung/awesome-dotnet-core/graphs/contributors), you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

Check out my [blog](https://medium.com/@thangchung) or say hi on [Twitter](https://twitter.com/thangchung)!

## Contents

* [General](#general)
* [Frameworks, Libraries and Tools](#frameworks-libraries-and-tools)
  * [API](#api)
  * [Application Frameworks](#application-frameworks)
  * [Application Templates](#application-templates)
  * [Authentication and Authorization](#authentication-and-authorization)
  * [Blockchain](#blockchain)
  * [Bot](#bot)
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
  * [Database Tools and Utilities](#database-tools-and-utilities)
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
  * [Networking](#networking)
  * [Misc](#misc)
  * [Office](#office)
  * [ORM](#orm)
  * [Profiling](#profiling)
  * [Queue and Messaging](#queue-and-messaging)
  * [Query Builders](#query-builders)
  * [Scheduler and Job](#scheduler-and-job)
  * [SDKs](#sdks)
  * [Security](#security)
  * [Searching](#searching)
  * [Serialization](#serialization)
  * [Template Engine](#template-engine)
  * [Testing](#testing)
  * [Tools](#tools)
  * [Web Framework](#web-framework)
  * [Web Socket](#web-socket)
  * [Windows Service](#windows-service)
  * [Workflow](#workflow)
* [Roadmaps](#roadmaps)
* [Starter Kits](#starter-kits)
* [Sample Projects](#sample-projects)
* [Articles](#articles)
* [Books](#books)
* [Cheat Sheets](#cheat-sheets)
* [Videos](#videos)
* [Podcasts](#podcasts)
* [Community](#community)

## General

* [ASP.NET Core Documentation](https://docs.asp.net/en/latest/) - The official ASP.NET Core documentation site.
* [.NET Core Documentation](https://docs.microsoft.com/en-us/dotnet/articles/welcome) - Home of the technical documentation for .NET Core, C#, F# and Visual Basic, including basic concepts, getting started instructions, tutorials and samples.
* [.NET Core SDK](https://www.microsoft.com/net/core) - .NET Core SDK is a general purpose development platform maintained by Microsoft and the .NET community on [GitHub](https://github.com/dotnet/core).
* [.NET Platform Standard](https://github.com/dotnet/corefx/blob/1719a3fe2a5c81b67a4909787da4a02fb0d0d419/Documentation/architecture/net-platform-standard.md) - The differrent between the old version and the new version of .NET. :star:17240
* [Introducing .NET Standard 2.0](https://blogs.msdn.microsoft.com/dotnet/2016/09/26/introducing-net-standard) - The description of what will be going on for .NET Standard 2.0 and the roadmap for some missing parts of the current .NET Standard.
* [Clean Code .NET/.NET Core](https://github.com/thangchung/clean-code-dotnet) - Clean Code concepts adapted for .NET / .NET Core. :star:1194

## Frameworks, Libraries and Tools

### API

* [autorest](https://github.com/Azure/autorest) - Swagger (OpenAPI) Specification code generator featuring C# and Razor templates. Supports C#, Java, Node.js, TypeScript, Python and Ruby. `4.5.x or above` :star:2496
* [aspnet-api-versioning](https://github.com/Microsoft/aspnet-api-versioning) - set of libraries which add service API versioning to ASP.NET Web API, OData with ASP.NET Web API, and ASP.NET Core. :star:1375
* [AspNetCoreRateLimit](https://github.com/stefanprodan/AspNetCoreRateLimit) - ASP.NET Core rate limiting middleware. :star:903
* [CondenserDotNet](https://github.com/Drawaes/CondenserDotNet) - API Condenser / Reverse Proxy using Kestrel and Consul, Including light weight consul library. :star:118
* [Flurl](https://github.com/tmenier/Flurl) - Fluent URL builder and testable HTTP for .NET [https://flurl.dev](https://flurl.dev). :star:1792
* GraphQL
  * [Dapper.GraphQL](https://github.com/landmarkhw/Dapper.GraphQL) - A library designed to integrate the Dapper and graphql-dotnet projects with ease-of-use in mind and performance as the primary concern. :star:164
  * [graphql-aspnetcore](https://github.com/JuergenGutsch/graphql-aspnetcore) - ASP.NET Core MiddleWare to create a GraphQL end-point. :star:123
  * [graphql-convention](https://github.com/graphql-dotnet/conventions) - This library is a complementary layer on top that allows you to automatically wrap your .NET classes into GraphQL schema definitions using existing property getters and methods as field resolvers :star:156
  * [graphiql-dotnet](https://github.com/JosephWoodward/graphiql-dotnet) - GraphiQL middleware for ASP.NET Core. :star:116
  * [graphql-dotnetcore](https://github.com/mkmarek/graphql-dotnetcore) - GraphQL for .NET Core based on [https://github.com/graphql/graphql-js](https://github.com/graphql/graphql-js). :star:92
  * [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) - GraphQL for .NET. :star:3529
  * [graphql-dotnet-server](https://github.com/graphql-dotnet/server) - GraphQL for .NET - Subscription Transport WebSockets. :star:204
  * [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) - GraphQL server for .Net Core and .NET Framework. :star:536
  * [FSharp.Data.GraphQL](https://github.com/fsprojects/FSharp.Data.GraphQL) - FSharp implementation of Facebook GraphQL query language [https://fsprojects.github.io/FSharp.Data.GraphQL](https://fsprojects.github.io/FSharp.Data.GraphQL). :star:240
  * [parser](https://github.com/graphql-dotnet/parser) - A lexer and parser for GraphQL in .NET. :star:101
  * [tanka-graphql](https://github.com/pekkah/tanka-graphql) - GraphQL execution and server libraries supporting SignalR, Apollo, schema manipulation and other features familiar from Apollo and graphql-js :star:27
* [halcyon](https://github.com/visualeyes/halcyon) - HAL implementation for ASP.NET. :star:63
* [JSON API .NET Core](https://github.com/Research-Institute/json-api-dotnet-core) - Framework for building json:api compliant APIs with the goal of eliminating RESTful boilerplate. :star:335
* [LightNode](https://github.com/neuecc/LightNode) - Micro RPC/REST Framework built on OWIN [http://neuecc.github.io/LightNode](http://neuecc.github.io/LightNode). :star:148
* [NetCoreStack.Proxy](https://github.com/NetCoreStack/Proxy) - The type-safe, distributed REST library for .NET Standard 2.0 (NetCoreStack Flying Proxy) :star:34
* [NSwag](https://github.com/RSuter/NSwag) - The Swagger/OpenAPI toolchain for .NET, Web API and TypeScript. [http://NSwag.org](http://NSwag.org). :star:2765
* [OData](https://github.com/OData/WebApi/tree/feature/netcore) - The Open Data Protocol (OData) enables the creation of HTTP-based data services, which allow resources identified using Uniform Resource Identifiers (URIs) and defined in an abstract data model, to be published and edited by Web clients using simple HTTP messages. :star:617
* [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator) - OpenAPI Generator allows generation of API client libraries (e.g. C#, TypeScript, etc), server stubs (ASP.NET Core, NancyFx, etc), documentation and configuration automatically given an OpenAPI Spec (v2, v3). :star:2997
* [refit](https://github.com/paulcbetts/refit) - The automatic type-safe REST library for Xamarin and .NET. :star:3439
* [RestClient.Net](https://github.com/MelbourneDeveloper/RestClient.Net) - Cross Platform REST Client for all C# platforms :star:20
* [RestEase](https://github.com/canton7/RestEase) - Easy-to-use typesafe REST API client library, which is simple and customisable. :star:487
* [RestLess](https://github.com/letsar/RestLess) - The automatic type-safe-reflectionless REST API client library for .Net Standard. :star:89
* [Restier](https://github.com/OData/RESTier) - RESTier is a RESTful API development framework for building standardized, OData V4 based RESTful services on .NET platform. :star:279
* [Restsharp](https://github.com/restsharp/RestSharp) - Simple REST and HTTP API Client for .NET :star:6619
* [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore) - Seamlessly adds a swagger to WebApi projects. :star:2524
  * [MicroElements.Swashbuckle.FluentValidation](https://github.com/micro-elements/MicroElements.Swashbuckle.FluentValidation) - Adds FluentValidation rules to swagger. :star:84
  * [Swashbuckle.AspNetCore.Filters](https://github.com/mattfrear/Swashbuckle.AspNetCore.Filters) - A bunch of useful filters for Swashbuckle.AspNetCore. :star:155
* [WebAPIContrib for ASP.NET CORE](https://github.com/WebApiContrib/WebAPIContrib.Core) - Community Contributions for ASP.NET Core. :star:383

### Application Frameworks
* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) - ASP.NET Boilerplate is a general purpose application framework especially designed for new modern web applications. It uses already familiar tools and implements best practices arround them to provide you a SOLID development experience. :star:7259
* [Abp vNext](https://github.com/abpframework/abp) - Abp vNext is the next generation of the open source [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) framework. It's a complete architecture and strong infrastructure to create modern web applications! :star:2016
Follows best practices and conventions to provide you a SOLID development experience.
* [AsyncEx](https://github.com/StephenCleary/AsyncEx) - A helper library for async/await. :star:1793
* [Aeron.NET](https://github.com/AdaptiveConsulting/Aeron.NET) - Efficient reliable UDP unicast, UDP multicast, and IPC message transport - .NET port of Aeron. :star:281
* [akka.net](https://github.com/akkadotnet/akka.net) - Toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications on .NET & Mono. :star:3348
* [Aggregates.NET](https://github.com/volak/Aggregates.NET) - Aggregates.NET is a framework to help developers integrate the excellent NServiceBus and EventStore libraries together. :star:182
* [ASP.NET MVC](https://github.com/aspnet/Mvc) - Model view controller framework for building dynamic web sites with clean separation of concerns, including the merged MVC, Web API, and Web Pages w/ Razor. :star:5762
* [Butterfly Server .NET](https://github.com/firesharkstudios/butterfly-server-dotnet) - Allows building real-time web apps and native apps with minimal effort. Define a Web API and Subscription API that automatically synchronizes datasets across connected clients. :star:180
* [CAP](https://github.com/dotnetcore/CAP) - An EventBus with local persistent message functionality for system integration in SOA or Microservice architecture. :star:2991
* [Carter](https://github.com/CarterCommunity/Carter) - Carter is a library that allows Nancy-esque routing for use with ASP.Net Core. :star:377
* [Chromely](https://github.com/mattkol/Chromely) - Lightweight Alternative to Electron.NET, Electron for .NET/.NET Core. :star:1613
* [Cinchoo ETL](https://github.com/Cinchoo/ChoETL) - ETL Framework for .NET (Parser / Writer for CSV, Flat, Xml, JSON, Key-Value formatted files). :star:191
* [CQRSlite](https://github.com/gautema/CQRSlite) - Lightweight framework for helping writing CQRS and Eventsourcing applications in C#. :star:710
* [dataaccess_aspnetcore](https://github.com/digipolisantwerp/dataaccess_aspnetcore) - The DataAccess Toolbox contains the base classes for data access in ASP.NET Core with Entity Framework Core 1.0 using the unit-of-work and repository pattern. :star:93
* [DNTFrameworkCore](https://github.com/rabbal/DNTFrameworkCore) - Lightweight and Extensible Infrastructure for Building High Quality Web Applications Based on ASP.NET Core. :star:100
* [DotNetCorePlugins](https://github.com/natemcmaster/DotNetCorePlugins) - .NET Core library for loading assemblies as a plugin. :star:374
* [DotnetSpider](https://github.com/dotnetcore/DotnetSpider) - DotnetSpider, a .NET Standard web crawling library similar to WebMagic and Scrapy. It is a lightweight ,efficient and fast high-level web crawling & scraping framework for .NET. :star:2096
* [DotNetty](https://github.com/Azure/DotNetty) - Port of netty, event-driven asynchronous network application framework. :star:2555
* [dotvvm](https://github.com/riganti/dotvvm) - Open source MVVM framework for Web Apps. :star:411
* [ElectronNET](https://github.com/ElectronNET/Electron.NET) - Build cross platform desktop apps with ASP.NET NET Core. :star:3614
* [EmbedIO](https://github.com/unosquare/embedio) - A tiny, cross-platform, module based web server for .NET Framework and .NET Core. :star:691
* [Ether.Network](https://github.com/aloisdg/Ether.Network) - Ether.Network is an open source networking library that allow developers to create simple, fast and scalable socket server or client applications over the TCP/IP protocol.
* [EventFlow](https://github.com/eventflow/EventFlow) - Async/await first CQRS+ES and DDD framework for .NET. :star:1223
* [ExcelDataReader](https://github.com/ExcelDataReader/ExcelDataReader) - Lightweight and fast library written in C# for reading Microsoft Excel files. :star:1869
* [ExtCore](https://github.com/ExtCore) - Free, open source and cross-platform framework for creating modular and extendable web applications based on ASP.NET Core 1.0.
* [Finbuckle.MultiTenant](https://github.com/Finbuckle/Finbuckle.MultiTenant) - Finbuckle.MultiTenant is a .NET Standard library for multitenant support designed for ASP.NET 2.0+. It provides functionality for tenant resolution, per-tenant app configuration, and per-tenant data isolation. :star:144
* [fission](https://github.com/fission/fission) - Fast Serverless Functions for Kubernetes. :star:4563
* [grpc](https://github.com/grpc/grpc/tree/master/src/csharp) - Remote Procedure Calls (RPCs) provide a useful abstraction for building distributed applications and services. The libraries in this repository provide a concrete implementation of the gRPC protocol, layered over HTTP/2. These libraries enable communication between clients and servers using any combination of the supported languages. :star:22728
* [Halibut](https://github.com/OctopusDeploy/Halibut) - A secure communication stack for .NET using JSON-RPC over SSL. :star:191
* [MagicOnion](https://github.com/neuecc/MagicOnion) - gRPC based HTTP/2 RPC Streaming Framework for .NET, .NET Core and Unity. :star:1193
* [MassTransit](https://github.com/MassTransit/MassTransit) - Distributed Application Framework for .NET.  :star:2201
* [microdot](https://github.com/gigya/microdot) - An open source .NET microservices framework. :star:969
* [MoreLINQ](https://github.com/morelinq/MoreLINQ) - Extensions to LINQ to Objects. :star:1707
* [Nancy](https://github.com/NancyFx/Nancy) - Lightweight, low-ceremony, framework for building HTTP based services on .NET and Mono. :star:6854
* [opencvsharp](https://github.com/shimat/opencvsharp) - .NET Framework wrapper for OpenCV. :star:1784
* [orleans](https://github.com/dotnet/orleans) - Framework that provides a straight-forward approach to building distributed high-scale computing applications, without the need to learn and apply complex concurrency or other scaling patterns. :star:5294
* [protoactor-dotnet](https://github.com/AsynkronIT/protoactor-dotnet) - Ultra fast distributed actors for Golang and C# [http://proto.actor](http://proto.actor). :star:864
* [resin](https://github.com/kreeben/resin) - 16-bit wide vector space search engine with HTTP API and pluggable read/write pipelines. :star:496
* [RService.io](https://github.com/Stoom/RService.IO) - ASP.Net Core RESTful microservice framework that focusing on speed and ease of use. :star:44
* [ServiceStack](https://github.com/ServiceStack/ServiceStack) - Thoughtfully architected, obscenely fast, thoroughly enjoyable web services for all [https://servicestack.net](https://servicestack.net). :star:4561
* [Steeltoe OSS](https://github.com/SteelToeOSS) - .NET toolkit for common microservice patterns.
* [Strathweb.TypedRouting.AspNetCore](https://github.com/filipw/Strathweb.TypedRouting.AspNetCore) - A library enabling strongly typed routing in ASP.NET Core MVC projects. :star:59
* [Xer.Cqrs](https://github.com/jeyjeyemem/Xer.Cqrs) - A simple library for creating applications based on the CQRS pattern with support for attribute routing and hosted handlers. Developed in C# targeting .NET Standard 1.0. :star:89
* [X.PagedList](https://github.com/dncuug/X.PagedList) - Library for easily paging through any IEnumerable/IQueryable in ASP.NET/ASP.NET Core. :star:513

### Application Templates
* [.NET Boxed](https://github.com/Dotnet-Boxed/Templates) - Project templates with batteries included, providing the minimum amount of code required to get you going. Includes ASP.NET Core API and GraphQL Templates. :star:1782
* [aspnet-core-react-template](https://github.com/bradymholt/aspnet-core-react-template) - ASP.NET Core 2.0 / React SPA Template App. :star:388
* [AspNetCoreSpa](https://github.com/asadsahi/AspNetCoreSpa) - Asp.Net Core 2+ & Angular 6 SPA with Angular CLI full featured application. :star:889
* [ASP.NET-MVC-Template](https://github.com/NikolayIT/ASP.NET-MVC-Template) - A ready-to-use templates for ASP.NET MVC 5 and ASP.NET Core with repositories, services, models mapping and DI and StyleCop warnings fixed. :star:275
* [AddFeatureFolders](https://github.com/OdeToCode/AddFeatureFolders) - Enable feature folders for MVC controllers and views in ASP.NET Core. :star:194
* [Angular Visual Studio Webpack Starter](https://github.com/damienbod/AngularWebpackVisualStudio) - Template for Webpack, Visual Studio, ASP.NET Core and Angular. Both the client and the server side of the application are implemented inside one ASP.NET Core project which makes it easier to deploy. :star:486
* [DNTFrameworkCoreTemplate](https://github.com/rabbal/DNTFrameworkCoreTemplate) - Boilerplate project templates based on [DNTFrameworkCore](https://github.com/rabbal/DNTFrameworkCore) :star:100
* [dotnet new caju](https://github.com/ivanpaulovich/dotnet-new-caju) - dotnet new templates with awesome architecture styles! Increases productivity to design layered applications based on Hexagonal, Clean or Event Sourcing architectures styles. It supports multiple data access frameworks (MongoDB, EntityFramework, Dapper or Kafka) and it is completely testable. :star:155
* [JavaScriptServices](https://github.com/aspnet/JavaScriptServices) - Microsoft ASP.NET Core JavaScript Services. :star:3168
* [kendo-ui-core](https://github.com/telerik/kendo-ui-core) - An HTML5, jQuery-based widget library for building modern web apps. [http://www.telerik.com/kendo-ui](http://www.telerik.com/kendo-ui). :star:2180
* [QuickApp](https://github.com/emonney/QuickApp) - ASP.NET Core / Angular4 startup project template with complete login, user and role management. :star:761
* [Serenity](https://github.com/volkanceylan/Serenity) - Serenity is an ASP.NET MVC / TypeScript application platform designed to simplify and shorten development of data-centric business applications with a service based architecture. :star:1730
* [Toucan](https://github.com/mrellipse/toucan) - Boilerplate for building single page apps. Server is multi-project .Net Core solution designed around SOLID principles. Client is TypeScript 2, Vuejs 2, Vuex 2. :star:203

### Authentication and Authorization
* [AspNet.Security.OpenIdConnect.Server](https://github.com/aspnet-contrib/AspNet.Security.OpenIdConnect.Server) - OpenID Connect/OAuth2 server framework for OWIN/Katana and ASP.NET Core. :star:506
* [Auth0](https://github.com/auth0/auth0.net) - Hosted, enterprise-grade platform for modern identity. :star:139
* [Casbin.NET](https://github.com/casbin-net/Casbin.NET) - Authorization library that supports access control models like ACL, RBAC, ABAC in C# :star:153
* [Cierge](https://github.com/PwdLess/Cierge) - Cierge is an OpenID Connect server that handles user signup, login, profiles, management, social logins, and more. Instead of storing passwords, Cirege uses magic links/codes and external logins to authenticate your users. :star:1232
* [Identity](https://github.com/aspnet/Identity) - ASP.NET Core Identity is the membership system for building ASP.NET Core web applications, including membership, login, and user data. :star:1868
* [IdentityServer](https://github.com/IdentityServer/IdentityServer4) - IdentityServer for ASP.NET Core 1.0 & 2.0 :star:4941
  * [IdentityServer4.EntityFramework](https://github.com/IdentityServer/IdentityServer4.EntityFramework) - EntityFramework persistence layer :star:211
  * [IdentityServer4.MongoDB](https://github.com/diogodamiani/IdentityServer4.MongoDB) - MongoDB persistence layer :star:71
  * [IdentityServer4.EntityFrameworkCore](https://github.com/2020IP/TwentyTwenty.IdentityServer4.EntityFrameworkCore) - Entity Framework Core persistence layer :star:41
  * [IdentityServer4.Templates](https://github.com/IdentityServer/IdentityServer4.Templates) - dotnet cli templates for IdentityServer4. :star:238
* [openiddict](https://github.com/openiddict/openiddict-core) - Easy-to-use OpenID Connect server for ASP.NET Core. :star:934
  * [oidc-debugger](https://github.com/nbarbettini/oidc-debugger) - OAuth 2.0 and OpenID Connect debugging tool. :star:55
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - Build [simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore) with Stormpath and ASP.NET Core.  :star:55
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - Build [simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore) with Stormpath and ASP.NET Core.(Deprecated: It will longer get updated as of March 2017 after joining OKTA)  :star:55
* [stuntman](https://github.com/ritterim/stuntman) - Library for impersonating users during development leveraging ASP.NET Identity. :star:246

### Blockchain
* [BTCPayServer](https://github.com/btcpayserver/btcpayserver) - A cross platform, self-hosted server compatible with Bitpay API. :star:1075
* [Meadow](https://github.com/MeadowSuite/Meadow) - An integrated Ethereum implementation and tool suite focused on Solidity testing and development. :star:78
* [NBitcoin](https://github.com/MetacoSA/NBitcoin) - Comprehensive Bitcoin library for the .NET framework. :star:1357
* [NBlockchain](https://github.com/danielgerlag/NBlockchain) - .NET standard library for building blockchain enabled applications :star:40
* [NBXplorer](https://github.com/dgarage/NBXplorer) - A Bitcoin and Altcoin lightweight block explorer. :star:138
* [NEO](https://github.com/neo-project/neo) - Open Network For Smart Economy. :star:2870
* [Nethereum](https://github.com/Nethereum) - Bringing the love of Ethereum to .NET.
* [Nethermind](https://github.com/NethermindEth/nethermind) - .NET Core Ethereum client :star:112
* [StratisBitcoinFullNode](https://github.com/stratisproject/StratisBitcoinFullNode) - Simple and affordable end-to-end solutions for development, testing and deployment of native C# blockchain applications on the .Net framework. :star:688
* [Trezor.Net](https://github.com/MelbourneDeveloper/Trezor.Net) - Cross platform C# library for talking to the Trezor Hardwarewallet :star:22
* [WalletWasabi](https://github.com/zkSNACKs/WalletWasabi) - Privacy focused, ZeroLink compliant Bitcoin wallet. :star:680

### Bot
* [BotSharp](https://github.com/SciSharp/BotSharp) - The Open Source AI Chatbot Platform Builder in 100% C# Running in .NET Core with Machine Learning algorithm. :star:719
* [NadekoBot](https://github.com/Kwoth/NadekoBot) - Open source, general-purpose Discord chat bot written in C#.
* [Telegram.Bot](https://github.com/TelegramBots/Telegram.Bot) - C# Telegram Bot API library. :star:1078
* [Funogram](https://github.com/Dolfik1/Funogram) - F# Telegram Bot Api library. :star:36

### Build Automation
* [cake-build](https://github.com/cake-build/cake) - Cross platform build automation system. :star:2309
* [CatLight](https://catlight.io) - Status notifier for developers that monitors builds and tasks in the project. Built using .Net Core and Electron.
* [Colorful.Console](https://github.com/tomakita/Colorful.Console) - Style your C# console output! :star:701
* [dotnet-docker](https://github.com/dotnet/dotnet-docker) - The base Docker images for working with .NET Core and the .NET Core Tools. :star:1782
* [Dockerize.NET](https://github.com/brthor/Dockerize.NET) - .NET Cli Tool to package your .NET Core Application into a docker image: 'dotnet dockerize' :star:143
* [FlubuCore](https://github.com/flubu-core/flubu.core) - A cross platform build and deployment automation system for building projects and executing deployment scripts using C# code. :star:382
* [GitInfo](https://github.com/kzu/GitInfo) - Git and SemVer Info from MSBuild, C# and VB. :star:178
* [GitVersioning](https://github.com/AArnott/Nerdbank.GitVersioning) - Stamp your assemblies and NuGet packages with a version from a single, simple version.txt file and include git commit IDs for non-official builds. :star:315
* [go-dotnet](https://github.com/matiasinsaurralde/go-dotnet) - Go wrapper for the .NET Core Runtime. :star:303
* [Image2Docker](https://github.com/docker/communitytools-image2docker-win) - PowerShell module which ports existing Windows application workloads to Docker. :star:277
* [LocalAppVeyor](https://github.com/joaope/LocalAppVeyor) - Run your AppVeyor builds, locally. :star:90
* [msbuild](https://github.com/Microsoft/msbuild) - The Microsoft Build Engine is a platform for building applications. :star:4004
* [Nuke](https://github.com/nuke-build/nuke) - Cross-platform build automation system. :star:472
* [Opserver](https://github.com/opserver/Opserver) - Stack Exchange's Monitoring System. :star:3806
* [vsts-agent](https://github.com/Microsoft/vsts-agent/blob/master/README.md) - Visual Studio Team Services Build and Release Agent. :star:761

### Bundling and Minification
* [BundlerMinifier](https://github.com/madskristensen/BundlerMinifier) - Visual Studio extension that let's you configure bundling and minification of JS, CSS and HTML files. :star:386
* [JavaScriptViewEngine](https://github.com/pauldotknopf/JavaScriptViewEngine) - ASP.NET MVC ViewEngine for rendering markup in a JavaScript environment. Ideal for React and Angular server-side rendering. :star:65
* [Smidge](https://github.com/Shazwazza/Smidge/) - Lightweight runtime CSS/JavaScript file minification, combination, compression & management library for ASP.NET Core. :star:222
* [Web Markup Minifier](https://github.com/Taritsyn/WebMarkupMin) - .NET library that contains a set of markup minifiers. The objective of this project is to improve the performance of web applications by reducing the size of HTML, XHTML and XML code. :star:232

### Caching
* [CacheManager](https://github.com/MichaCo/CacheManager) - Open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features. [http://cachemanager.michaco.net](http://cachemanager.michaco.net)
* [EasyCaching](https://github.com/dotnetcore/EasyCaching) - Open source caching library that contains basic usages and some advanced usages of caching which can help us to handle caching more easier. :star:580
* [Faster](https://github.com/Microsoft/FASTER/tree/master/cs) - Fast key-value store from Microsoft Research. :star:3631
* [Foundatio](https://github.com/exceptionless/Foundatio) - Pluggable foundation blocks for building distributed apps. :star:1095
* [Microsoft Caching](https://github.com/aspnet/Caching) - Libraries for in-memory caching and distributed caching. :star:470
* [Stack Exchange Redis](https://github.com/StackExchange/StackExchange.Redis) - High performance general purpose redis client for .NET languages (C# etc). :star:3700

### CMS
* [Awesome-CMS-Core](https://github.com/SaiGonSoftware/Awesome-CMS-Core) - Awesome CMS Core is an open source CMS built using ASP.Net Core & ReactJS with module seperation concern in mind and provide lastest trend of technology like .Net Core, React, Webpack, SASS, Background Job, Message Queue. :star:240
* [Blogifier.Core](https://github.com/blogifierdotnet/Blogifier.Core) - ASP.NET applications to provide common blogging functionality. :star:401
* [Cofoundry](https://github.com/cofoundry-cms/cofoundry) - Open source .NET Core CMS and modular application framework. Code-first, unobtrusive and extensible. :star:415
* [CoreWiki](https://github.com/csharpfritz/CoreWiki) - Simple ASP.NET Core wiki that we are working on during live coding streams. :star:264
* [Lynicon](https://github.com/jamesej/lyniconanc) - O/S ASP.Net Core/.Net Core CMS with paid for modules: JSON content, works with variety of data stores, c# content types :star:139
* [Miniblog](https://github.com/madskristensen/Miniblog.Core) - An ASP.NET Core blogging engine. :star:753
* [NetCoreCMS](https://github.com/OnnoRokomSoftware/NetCoreCMS) - An Open source ASP.NET Core 2.0 CMS. It currently supports MySQL and planned to implement MSSQL, SQLite and PostgreSQL. Also it is a modular CMS supports theme, skin, custom layout, widgets, multiple language (En, BN). :star:135
* [Orchard Core CMS](https://github.com/OrchardCMS/OrchardCore) - Open Source Content Management System built with ASP.NET Core on top of a Modular and Extensible Application Framework. :star:2951
* [Piranha CMS](https://github.com/piranhacms/piranha.core) - A Lightweight & Unobtrusive Open Source CMS for ASP.NET Core and Entity Framework Core. :star:577
* [Platformus](https://github.com/Platformus) - Free, open source and cross-platform CMS based on ASP.NET Core 1.0 and ExtCore framework.
* [SimpleContent](https://github.com/joeaudette/cloudscribe.SimpleContent) - Simple, yet flexible content and blog engine for ASP.NET Core that can work with or without a database. :star:260
* [Squidex](https://github.com/Squidex/squidex) - Headless CMS, based on MongoDB, CQRS and Event Sourcing. :star:731
* [Swastika I/O Core CMS](https://github.com/Swastika-IO/Swastika-IO-Core) - Open source ASP.NET Core 2.x CMS. It currently supports MS SQL and planned to implement MSSQL, SQLite in the near future. It has many built-in features out of the box like multilanguage support, theme, template... :star:104
* [Weapsy](https://github.com/Weapsy/Weapsy) - Open source ASP.NET Core CMS based on DDD and CQRS. It supports MSSQL, MySQL, SQLite and PostgreSQL out of the box. :star:695
* [Wyam](https://github.com/Wyamio/Wyam) - Modular static content and static site generator. :star:1090
* [ZKEACMS](https://github.com/SeriaWei/ZKEACMS.Core) - Visual design, build site onlie by drag and drop. :star:1724

### Code Analysis and Metrics
* [awesome-static-analysis](https://github.com/mre/awesome-static-analysis) - Curated list of static analysis tools, linters and code quality checkers for various programming languages. :star:5918
* Code Analysis
  * [DevSkim](https://github.com/Microsoft/DevSkim) - A set of IDE plugins and rules that provide security "linting" capabilities. :star:289
  * [RefactoringEssentials](https://github.com/icsharpcode/RefactoringEssentials) - Refactoring Essentials for Visual Studio. :star:615
  * [roslyn-analyzers](https://github.com/dotnet/roslyn-analyzers) - .NET Compiler Platform ("Roslyn") Analyzers. :star:613
  * [StyleCopAnalyzers](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) - StyleCop rules using the .NET Compiler Platform. :star:1334
* Metrics
  * [AppMetrics](https://github.com/alhardy/AppMetrics) - App Metrics is an open-source and cross-platform .NET library used to record and report metrics within an application and reports it's health. :star:1312
  * [Audit.NET](https://github.com/thepirat000/Audit.NET) - Small framework to audit .NET object changes. :star:884
  * [BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet) - Powerful .NET library for benchmarking. :star:4385
  * [coverlet](https://github.com/tonerdo/coverlet) - Cross platform code coverage library for .NET Core. :star:1312
  * [Foundatio](https://github.com/exceptionless/Foundatio#metrics) - A common interface with in memory, redis, StatsD, and Metrics.NET implementations. :star:1095
  * [MiniCover](https://github.com/lucaslorentz/minicover) - Minimalist Code Coverage Tool for .NET Core. :star:159
  * [NBench](https://github.com/petabridge/NBench) - Performance benchmarking and testing framework for .NET applications. :star:460
  * [Nexogen.Libraries.Metrics](https://github.com/nexogen-international/Nexogen.Libraries.Metrics) - Library for collecting application metrics in .NET and exporting them to Prometheus. :star:49
  * [OpenCover](https://github.com/OpenCover/opencover) - Code coverage tool for .NET 2 and above (WINDOWS OS only), support for 32 and 64 processes with both branch and sequence points. :star:1095
  * [PerformanceMonitor](https://github.com/dotnet-architecture/PerformanceMonitor) - .NET Core Application Performance Monitor. :star:116
  * [prometheus-net](https://github.com/prometheus-net/prometheus-net) - .NET Client for [https://prometheus.io](https://prometheus.io). :star:363
  * [Prometheus.Client](https://github.com/PrometheusClientNet/Prometheus.Client) - .NET Client for [Prometheus](https://prometheus.io). :star:45
  	* [Prometheus.Client.MetricPusher](https://github.com/PrometheusClientNet/Prometheus.Client.MetricPusher) -  Push metrics to a PushGateaway for the Prometheus.Client. :star:5
  	* [Prometheus.Client.AspNetCore](https://github.com/PrometheusClientNet/Prometheus.Client.AspNetCore) -  Middleware for the Prometheus.Client. :star:2
  	* [Prometheus.Client.MetricServer](https://github.com/PrometheusClientNet/Prometheus.Client.MetricServer) -  MetricServer for the Prometheus.Client. :star:8
  	* [Prometheus.Client.HttpRequestDurations](https://github.com/PrometheusClientNet/Prometheus.Client.HttpRequestDurations) -  Metrics logging of request durations for the Prometheus.Client. :star:6

### Compression
* [lz4net](https://github.com/MiloszKrajewski/K4os.Compression.LZ4) - Ultra fast compression algorithm for all .NET platforms. :star:128
* [sharpcompress](https://github.com/adamhathcock/sharpcompress) - Fully managed C# library to deal with many compression types and formats. :star:1079

### Compilers, Transpilers and Languages
* [Fable](https://github.com/fable-compiler/Fable) - F# to JavaScript Compiler. :star:1672
* [fparsec](https://github.com/stephan-tolksdorf/fparsec) - A parser combinatory library for F# and C#. :star:224
* [IL2C](https://github.com/kekyo/IL2C) - A translator for ECMA-335 CIL/MSIL to C language. :star:182
* [Mond](https://github.com/Rohansi/Mond) - A dynamically typed scripting language written in C# with a REPL, debugger, and simple embedding API. :star:182
* [peachpie](https://github.com/peachpiecompiler/peachpie) - Open-source PHP compiler to .NET. :star:1334
* [Pidgin](https://github.com/benjamin-hodgson/Pidgin) - A lightweight, fast and flexible parsing library for C#, developed at Stack Overflow. :star:277
* [roslyn](https://github.com/dotnet/roslyn) - The .NET Compiler Platform ("Roslyn") provides open-source C# and Visual Basic compilers with rich code analysis APIs. :star:11779
* [Sprache](https://github.com/sprache/Sprache) - Tiny C# Monadic Parser Framework. :star:1390

### Cryptography
* [BCrypt.Net](https://github.com/BcryptNet/bcrypt.net) - Bringing updates to the original bcrypt package. :star:261
* [BCrypt.NET-Core](https://github.com/neoKushan/BCrypt.Net-Core) - .NET Core port of BCrypt.NET used to store passwords securely. :star:147
* [BouncyCastle PCL](https://github.com/onovotny/BouncyCastle-PCL) - The Bouncy Castle Crypto package is a C# implementation of cryptographic algorithms and protocols. :star:94
* [multiformats](https://github.com/multiformats/cs-multihash) - A general purpose hashing library, but a library to encode/decode Multihashes which is a "container" describing what hash algorithm the digest is calculated with. :star:32
* [nsec](https://github.com/ektrah/nsec) - NSec is a new cryptographic library for .NET Core based on libsodium. :star:150

### Database
* [DBreeze](https://github.com/hhblaze/DBreeze) - C# .NET MONO NOSQL (key value store embedded) ACID multi-paradigm database management system. :star:300
* [JsonFlatFileDataStore](https://github.com/ttu/json-flatfile-datastore) - Simple JSON flat file data store with support for typed and dynamic data. :star:127
* [LiteDB](https://github.com/mbdavid/LiteDB) - .NET NoSQL Document Store in a single data file - [http://www.litedb.org](http://www.litedb.org). :star:4183
* [NoDb](https://github.com/joeaudette/NoDb) - "no database" file system storage for .NET Core/ASP.NET Core because not every project needs a database. :star:146
* [marten](https://github.com/JasperFx/marten) - Postgresql as a Document Database and Event Store for .NET Applications [http://jasperfx.github.io/marten](http://jasperfx.github.io/marten). :star:1053
* [StringDB](https://github.com/SirJosh3917/StringDB) - StringDB is a modular, key/value pair archival DB designed to consume *tiny* amounts of ram & produce *tiny* databases. :star:19
* [yessql](https://github.com/sebastienros/yessql) - .NET document database working on any RDBMS. :star:560

### Database Drivers
* [cassandra-csharp-driver](https://github.com/datastax/csharp-driver) - DataStax C# Driver for Apache Cassandra. :star:362
* [confluent-kafka-dotnet](https://github.com/confluentinc/confluent-kafka-dotnet) - Confluent's Apache Kafka .NET client. :star:1125
* [couchbase-lite-net](https://github.com/couchbase/couchbase-lite-net) - A lightweight, document-oriented (NoSQL), syncable database engine for .NET. :star:338
* [MongoDB.Driver](https://github.com/mongodb/mongo-csharp-driver) - .NET Driver for MongoDB. :star:2219
* MySQL
  * [mysql-connector-net](https://github.com/mysql/mysql-connector-net/tree/8.0) - Connector/Net is a fully-managed ADO.NET driver for MySQL. :star:154
  * [MySqlConnector](https://github.com/mysql-net/MySqlConnector) - Async MySQL Connector for .NET and .NET Core. :star:668
* Neo4j
  * [neo4j-dotnet-driver](https://github.com/neo4j/neo4j-dotnet-driver) - Neo4j Bolt driver for .NET. :star:100
  * [Neo4jClient](https://github.com/Readify/Neo4jClient) - .NET client binding for Neo4j. :star:294
* [npgsql](https://github.com/npgsql/npgsql) - .NET data provider for PostgreSQL. It allows any program developed for .NET framework to access a PostgreSQL database server. It is implemented in 100% C# code. PostgreSQL versions since 9.1 are officially supported, others may work. [http://www.npgsql.org](http://www.npgsql.org)
* [ravendb](https://github.com/ayende/ravendb/tree/v4.0) - Linq enabled document database for .NET. :star:285
* [RethinkDb.Driver](https://github.com/bchavez/RethinkDb.Driver) - C#/.NET RethinkDB driver with 100% ReQL API coverage. :star:302
* [progaudi.tarantool](https://github.com/progaudi/progaudi.tarantool) - .NET client for Tarantool NoSql database. :star:39

### Database Tools and Utilities
* [DbUp](https://github.com/DbUp/DbUp) - .NET library that helps you to deploy changes to SQL Server databases. It tracks which SQL scripts have been run already, and runs the change scripts that are needed to get your database up to date. :star:1018
* [Evolve](https://github.com/lecaillon/Evolve) - Simple database migration tool that uses plain SQL scripts. Inspired by Flyway. :star:252
* [fluentmigrator](https://github.com/fluentmigrator/fluentmigrator) - Migration framework for .NET much like Ruby on Rails Migrations. :star:1983
* [monitor-table-change-with-sqltabledependency](https://github.com/christiandelbianco/monitor-table-change-with-sqltabledependency) - Get SQL Server notification on record table change. :star:292
* [NReco.PivotData](https://www.nuget.org/packages/NReco.PivotData) - In-memory data cube with OLAP operations and PivotTable data model.
* [roundhouse](https://github.com/chucknorris/roundhouse) - Database Migration Utility for .NET using sql files and versioning based on source control. :star:658
* [SharpRepository](https://github.com/SharpRepository/SharpRepository) - SharpRepository is a generic repository written in C# which includes support for various relational, document and object databases including Entity Framework, RavenDB, MongoDb and Db4o. SharpRepository includes Xml and InMemory repository implementations as well. :star:445
* [TrackableEntities.Core](https://github.com/TrackableEntities/TrackableEntities.Core) - Change-tracking across service boundaries with .NET Core. :star:40
* [Mongo.Migration](https://github.com/SRoddis/Mongo.Migration) - Mongo.Migration is designed for the [MongoDB C# Driver]( https://github.com/mongodb/mongo-csharp-driver) to migrate your documents easily and on-the-fly. No more downtime for schema-migrations. Just write small and simple migrations. [Link]( https://github.com/SRoddis/Mongo.Migration)

### Date and Time
* [Exceptionless.DateTimeExtensions](https://github.com/exceptionless/Exceptionless.DateTimeExtensions) - DateTimeRange, Business Day and various DateTime, DateTimeOffset, TimeSpan extension methods. :star:83
* [FluentDateTime](https://github.com/FluentDateTime/FluentDateTime) - Allows you to write cleaner DateTime expressions and operation. Partially inspired by Ruby DateTime Extensions. :star:236
* [nodatime](https://github.com/nodatime/nodatime) - Better date and time API for .NET [http://nodatime.org](http://nodatime.org). :star:1335

### Distributed Computing
* [AspNetCore.Diagnostics.HealthChecks](https://github.com/xabaril/AspNetCore.Diagnostics.HealthChecks) - Enterprise HealthChecks for ASP.NET Core Diagnostics Package :star:795
  - [BeatPulse](https://github.com/Xabaril/BeatPulse) - Enable load balancers to montior the status of deployed Web applications :star:585
* [Foundatio](https://github.com/exceptionless/Foundatio) - Pluggable foundation blocks for building distributed apps :star:1095
* [Rafty](https://github.com/ThreeMammals/Rafty) - RAFT consensus in .NET Core :star:125
* [Obvs](https://github.com/christopherread/Obvs) - An observable microservice bus .NET library that wraps the underlying transport in simple Rx based interfaces :star:236
* [Ocelot](https://github.com/ThreeMammals/Ocelot) - API Gateway created using .NET Core :star:4040
* [OpenTracing](https://github.com/opentracing/opentracing-csharp) - Vendor-neutral APIs and instrumentation for distributed tracing :star:319
* [Polly](https://github.com/App-vNext/Polly) - .NET 3.5 / 4.0 / 4.5 / PCL library that allows developers to express transient exception and fault handling policies such as Retry, Retry Forever, Wait and Retry or Circuit Breaker in a fluent manner :star:6379
* [ProxyKit](https://github.com/damianh/ProxyKit) - Toolkit to create code-first HTTP reverse proxies on ASP.NET Core :star:674

### E-Commerce and Payments
* [nopCommerce](https://github.com/nopSolutions/nopCommerce) - Free open-source ecommerce shopping cart (ASP.NET MVC / ASP.NET Core MVC ) with a vast community and a market place full of new features, themes and plugins. :star:3842
* [GrandNode](https://github.com/grandnode/grandnode) - Multi-platform, free, open source ecommerce shopping cart based on ASP.NET Core 2.1 and MongoDB derived from [nopCommerce](https://github.com/nopSolutions/nopCommerce). :star:779
* [PayPal](https://github.com/paypal/PayPal-NET-SDK) - .NET SDK for PayPal's RESTful APIs. :star:448
* [SimplCommerce](https://github.com/simplcommerce/SimplCommerce) - Super simple ecommerce system built on .NET Core. :star:2241
* [Stripe](https://github.com/ServiceStack/Stripe) - Typed .NET clients for stripe.com REST APIs. :star:163


### Exceptions
* [Demystifier](https://github.com/benaadams/Ben.Demystifier) - High performance understanding for stack traces (Make error logs more productive). :star:1298
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) - Exceptionless .NET Client :star:262
* [GlobalExceptionHandlerDotNet](https://github.com/JosephWoodward/GlobalExceptionHandlerDotNet) - GlobalExceptionHandlerDotNet allows you to configure exception handling as a convention with your ASP.NET Core application pipeline as opposed to explicitly handling them within each controller action. :star:168

### Functional Programming
* [CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions) - Functional Extensions for C#. :star:494
* [DynamicData](https://github.com/RolandPheasant/DynamicData) - Reactive collections based on Rx.NET. :star:773
* [echo-process](https://github.com/louthy/echo-process) - Actor library for C# with additional modules that support persistence to Redis, as well as JS integration. :star:60
* [FsCheck](https://github.com/fscheck/FsCheck) - Random Testing for .NET. :star:679
* [Giraffe](https://github.com/dustinmoris/Giraffe) - A native functional ASP.NET Core web framework for F# developers. :star:1173
* [language-ext](https://github.com/louthy/language-ext) - C# functional language extensions and 'Erlang like' concurrency system. :star:2527
* [LaYumba.Functional](https://github.com/la-yumba/functional-csharp-code) - Utility library for programming functionally in C#. :star:257
* [NetMQ.ReactiveExtensions](https://github.com/NetMQ/NetMQ.ReactiveExtensions) - Effortlessly send messages anywhere on the network using Reactive Extensions (RX). Transport protocol is ZeroMQ. :star:52
* [Optional](https://github.com/nlkl/Optional) - A robust option type for C#. :star:522
* [reactive-streams-dotnet](https://github.com/reactive-streams/reactive-streams-dotnet) - [Reactive Streams](http://www.reactive-streams.org/) for .NET. :star:141
* [ReactiveUI](https://github.com/reactiveui/ReactiveUI) - A MVVM framework that integrates with the Reactive Extensions for .NET to create elegant, testable User Interfaces that run on any mobile or desktop platform. :star:4792
* [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET) - The [Reactive Extensions](http://reactivex.io) for .NET. :star:3815
* [Qactive](https://github.com/RxDave/Qactive) - Reactive queryable observable framework. `4.x.x or above` :star:132
* [sodium](https://github.com/SodiumFRP/sodium/tree/master/) - Functional Reactive Programming (FRP) Library. `4.x.x or above` :star:719

### Graphics
* [GLFWDotNet](https://github.com/smack0007/GLFWDotNet) - .NET bindings for GLFW. :star:26
* [ImageProcessor](https://github.com/JimBobSquarePants/ImageProcessor) - A fluent wrapper around System.Drawing for the processing of image files [http://imageprocessor.org](http://imageprocessor.org). `4.5.x or above` :star:2135
* [ImageSharp](https://github.com/SixLabors/ImageSharp) - Cross-platform library for processing of image files written in C#. :star:3254
* [LibVLCSharp](https://github.com/videolan/libvlcsharp): .NET/Mono bindings for libvlc, the multimedia framework powering the VLC applications made by VideoLAN.
* [Magick.NET](https://github.com/dlemstra/Magick.NET) - The .NET library for ImageMagick. :star:1038
* [MagicScaler](https://github.com/saucecontrol/PhotoSauce) - MagicScaler high-performance, high-quality image processing pipeline for .NET :star:112
* [QRCoder](https://github.com/codebude/QRCoder) - A pure C# Open Source QR Code implementation. :star:1507
* [SharpBgfx](https://github.com/MikePopoloski/SharpBgfx) - C# bindings for the bgfx graphics library. :star:131
* [Structure.Sketching](https://github.com/JaCraig/Structure.Sketching) - Image processing library for use in .NET applications that supports .NET Core. :star:68
* [veldrid](https://github.com/mellinoe/veldrid) - A low-level, hardware-accelerated 3D graphics library for .NET. :star:925

### GUI
* [Avalonia](https://github.com/AvaloniaUI/Avalonia) - A multi-platform .NET UI framework (formerly known as Perspex). :star:6985
* [AvaloniaEdit](https://github.com/AvaloniaUI/AvaloniaEdit/) - The Avalonia-based text editor component forked from [AvalonEdit](https://github.com/icsharpcode/AvalonEdit) :star:790
* [ShellProgressBar](https://github.com/Mpdreamz/shellprogressbar) - library to create progress bars in console programs :star:624
* [Qml.Net](https://github.com/pauldotknopf/Qml.Net) - A cross-platform Qml/.NET integration for Mono/.NET/.NET Core. :star:744
* [WinApi](https://github.com/prasannavl/WinApi) - A simple, direct, ultra-thin CLR library for high-performance Win32 Native Interop with automation, windowing, DirectX, OpenGL and Skia helpers. :star:466

### IDE
* [Mono](https://github.com/mono/monodevelop) - MonoDevelop enables developers to quickly write desktop and web applications on Linux, Windows and Mac OS X. It also makes it easy for developers to port .NET applications created with Visual Studio to Linux and Mac OS X maintaining a single code base for all platforms. :star:2394
* [rider](https://www.jetbrains.com/rider/) - Cross-platform C# IDE based on the IntelliJ platform and ReSharper.
* [Omnisharp](http://www.omnisharp.net/) - Family of Open Source projects, each with one goal: To enable a great .NET experience in YOUR editor of choice.
* [SharpDevelop](https://github.com/icsharpcode/SharpDevelop) - SharpDevelop is a free Integrated Development Environment (IDE) for C#, VB.NET, Boo, IronPython, IronRuby and F# projects on Microsoft's .NET platform. It is written (almost) entirely in C#, and comes with features you would expect in an IDE plus a few more. :star:1459
* [Visual Studio Code](https://github.com/Microsoft/vscode) - New type of tool that combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. Code provides comprehensive editing and debugging support, an extensibility model, and lightweight integration with existing tools. :star:81753
* [Visual Studio Community](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx) - Free editor for individual developers, open source projects, academic research, education, and small professional teams.

### Internationalization
* [Localization](https://github.com/aspnet/Localization) - Localization abstractions and implementations for ASP.NET Core applications. :star:153
* [NetCoreStack.Localization](https://github.com/NetCoreStack/Localization) - Database Resource Localization for .NET Core with Entity Framework and In Memory Cache :star:56
* [Westwind.Globalization](https://github.com/RickStrahl/Westwind.Globalization) - Database driven resource localization for .NET applications. :star:428

### IOC
* [AutoDI](https://github.com/Keboo/AutoDI) - Super-fast compile-time dependency injection using IL weaving. :star:62
* [Autofac](https://github.com/autofac/Autofac) - Addictive .NET IoC container. :star:2695
* [Castle.Windsor](https://github.com/castleproject/Windsor) Castle Windsor is a best of breed, mature Inversion of Control container available for .NET.
* [DryIoc](https://github.com/dadhi/DryIoc) - Fast, small, full-featured IoC Container for .NET. :star:275
* [Grace](https://github.com/ipjohnson/Grace) - Grace is a feature rich Dependency Injection Container designed with ease of use and performance in mind. :star:190
* [Inyector](https://github.com/davidrevoledo/Inyector) - Dependency Injection Automation for AspNetCore  :star:12
* [Lamar](https://github.com/jasperfx/lamar) - Dependency Injection/Inversion of Control tool for .NET. (Previously StructureMap) :star:206
* [LightInject](https://github.com/seesharper/LightInject) - Ultra lightweight IoC container [http://www.lightinject.net](http://www.lightinject.net). :star:389
* [SimpleInjector](https://github.com/simpleinjector/SimpleInjector) - Easy, flexible, and fast Dependency Injection library that promotes best practice to steer developers towards the pit of success. :star:815
* [Stashbox](https://github.com/z4kn4fein/stashbox) - A lightweight, portable dependency injection framework for .NET based solutions. :star:66

### Logging
* [common-logging](https://github.com/net-commons/common-logging) - Portable logging abstraction for .NET [http://net-commons.github.io/common-logging](http://net-commons.github.io/common-logging). :star:607
* [dnxcore-logging-logstash](https://github.com/jvandevelde/dnxcore-logging-logstash) - Logstash logging extension for .NET Core applications with UDP and Redis transports. :star:6
* [Exceptionless](https://github.com/exceptionless/Exceptionless.Net) - Exceptionless .NET Client :star:262
* [Foundatio](https://github.com/exceptionless/Foundatio#logging) - A fluent logging api that can be used to log messages throughout your application. :star:1095
* [LibLog](https://github.com/damianh/LibLog) - Single file for you to either copy/paste or install via nuget, into your library/ framework/ application to provide a logging abstraction. :star:854
* [log4net](https://github.com/apache/logging-log4net) - log4net is a port of the excellent Apache log4j™ framework to the Microsoft® .NET runtime. :star:375
* [NLog](https://github.com/NLog/NLog) - Advanced .NET, Silverlight and Xamarin Logging. :star:3987
* [Q42.Logging.ApplicationInsights](https://github.com/Q42/Q42.Logging.ApplicationInsights) - Log appender for the build in ASP.NET Core logging to send all logs to Application Insights. :star:2
* [serilog](https://github.com/serilog/serilog) - Simple .NET logging with fully-structured events. :star:2965
  * [serilog-aspnetcore](https://github.com/serilog/serilog-aspnetcore) - Serilog integration for ASP.NET Core 2+. :star:322
  * [Serilog.Exceptions](https://github.com/RehanSaeed/Serilog.Exceptions) - Serilog.Exceptions is an add-on to [Serilog](https://serilog.net/) to log exception details and custom properties that are not output in Exception.ToString(). :star:157
  * [Serilog.Settings.Configuration](https://github.com/serilog/serilog-settings-configuration) - A Serilog configuration provider that reads from Microsoft.Extensions.Configuration. :star:107
* [SEQ](https://getseq.net) - Seq collects data over HTTP, while your applications use the best available structured logging APIs for your platform.

### Machine Learning and Data Science
* [Accord](https://github.com/accord-net/framework) - Machine learning, computer vision, statistics and general scientific computing for .NET. :star:3522
* [ML.NET](https://github.com/dotnet/machinelearning) - Cross-platform open-source machine learning framework which makes machine learning accessible to .NET developers [http://dot.net/ml](http://dot.net/ml). :star:6336
* [Spreads](https://github.com/Spreads/Spreads/) - Series and Panels for Real-time and Exploratory Analysis of Data Streams. :star:302
* [TensorFlowSharp](https://github.com/migueldeicaza/TensorFlowSharp) - TensorFlow API for .NET languages. :star:2708
* [WaveFunctionCollapse](https://github.com/mxgmn/WaveFunctionCollapse) - itmap & tilemap generation from a single example with the help of ideas from quantum mechanics. :star:12501
* [SiaNet](https://github.com/SciSharp/SiaNet) - A C# deep learning library, human friendly, CUDA/OpenCL supported, well structured, easy to extend  :star:310

### Mail
* [FluentEmail](https://github.com/lukencode/FluentEmail) - All in one email sender for .NET and .NET Core :star:851
* [MailBody](https://github.com/doxakis/MailBody) - Create transactional email with a fluent interface (.NET). :star:134
* [MailKit](https://github.com/jstedfast/MailKit) - Cross-platform .NET library for IMAP, POP3, and SMTP. :star:2794
* [MailMergeLib](https://github.com/axuno/MailMergeLib) - SMTP mail client library which provides comfortable mail merge capabilities for text, inline images and attachments, as well as good throughput and fault tolerance for sending mail messages. :star:73
* [MimeKit](https://github.com/jstedfast/MimeKit) - Cross-platform .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools. :star:932
* [netDumbster](https://github.com/cmendible/netDumbster) - a .Net Fake SMTP Server used for testing. Clone of the popular Dumbster. :star:73
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net) - C# library that moves your stylesheets to inline style attributes, for maximum compatibility with E-mail clients. :star:424
* [SendGrid Client](https://github.com/0xdeafcafe/sendgrid-dotnet) - C# library for the SendGrid v3 mail endpoint. :star:15
* [SmtpServer](https://github.com/cosullivan/SmtpServer) - Library to create your own SMTP server. :star:230
* [StrongGrid](https://github.com/Jericho/StrongGrid) - Client for SendGrid's v3 API. Not only allows you to send emails, but also allows you to bulk import contacts, manage lists and segments, create custom fields for your lists, etc. Also includes a parser for SendGrid Webhooks. :star:82

### Mathematics
* [UnitConversion](https://github.com/Stratajet/UnitConversion) - Expansible Unit Conversion Library for .NET Core and .NET Framework. :star:103
* [AutoDiff](https://github.com/alexshtf/autodiff) - A library that provides fast, accurate and automatic differentiation (computes derivative / gradient) of mathematical functions. :star:34

### Misc
* [AdvanceDLSupport](https://github.com/Firwood-Software/AdvanceDLSupport) - Library to improvie P/Invoke-ing native code. Interact with native objects as if they were first class objects. :star:311
* [AngleSharp](https://github.com/AngleSharp/AngleSharp) - The ultimate angle brackets parser library. It parses HTML5, MathML, SVG and CSS to construct a DOM based on the official W3C specification. Comparable to beautifulsoup4 of python. :star:2712
* [AgileMapper](https://github.com/agileobjects/AgileMapper) - AgileMapper is a zero-configuration, highly-configurable object-object mapper with viewable execution plans. :star:212
* [AspNetCore Extension Library](https://github.com/sgjsakura/AspNetCore) - ASP.NET Core Extension Library. :star:125
* [AutoMapper](https://github.com/AutoMapper/AutoMapper) - Convention-based object-object mapper in .NET. :star:6578
* [Baget](https://github.com/loic-sharma/BaGet) - A lightweight NuGet server. :star:524
* [Bleak](https://github.com/Akaion/Bleak) - A Windows native DLL injection library. :star:358
* [Bullseye](https://github.com/adamralph/bullseye/) - A .NET package for describing and running targets and their dependencies. :star:205
* [Castle.Core](https://github.com/castleproject/Core) - Castle Core, including Castle DynamicProxy, Logging Services and DictionaryAdapter [http://www.castleproject.org](http://www.castleproject.org). :star:953
* [Chessie](https://github.com/fsprojects/Chessie) - Railway-oriented programming for .NET [http://fsprojects.github.io/Chessie](http://fsprojects.github.io/Chessie). :star:154
* [CliWrap](https://github.com/Tyrrrz/CliWrap) - Wrapper for command line interfaces. :star:362
* [commanddotnet](https://github.com/bilal-fazlani/commanddotnet) - Model your command line application interface in a class. :star:116
* [CommonMark.NET](https://github.com/Knagis/CommonMark.NET) - The implementation of CommonMark specification in C# for converting Markdown documents to HTML. :star:902
* [ConsoleTableExt](https://github.com/minhhungit/ConsoleTableExt) - Fluent library to create table for .NET console application. :star:105
* [CoordinateSharp](https://github.com/Tronald/CoordinateSharp) - A library that can quickly format and convert geographic coordinates as well as provide location based sun and moon information (sunset, sunrise, moon illumination, etc...).  :star:115
* [datatables](https://github.com/ALMMa/datatables.aspnet/tree/dev) - Microsoft ASP.NET server-side support and helpers for jQuery DataTables. :star:268
* [DinkToPdf](https://github.com/rdvojmoc/DinkToPdf) - C# .NET Core wrapper for wkhtmltopdf library that uses Webkit engine to convert HTML pages to PDF. :star:390
* [dotnet-env](https://github.com/tonerdo/dotnet-env) - A .NET library to load environment variables from .env files. :star:107
* [DotNet.Glob](https://github.com/dazinator/DotNet.Glob) - A fast globbing library for .NET / .NETStandard applications. Outperforms Regex. :star:152
* [Dotnet outdated](https://github.com/jerriep/dotnet-outdated) - A .NET Core global tool to display outdated NuGet packages in a project. :star:445
* [Dotnet Script](https://github.com/filipw/dotnet-script) - Run C# scripts from the .NET CLI. :star:1014
* [Dotnet Serve](https://github.com/natemcmaster/dotnet-serve) - Simple command-line HTTP server for .NET Core CLI. :star:321
* [Eighty](https://github.com/benjamin-hodgson/Eighty) - A simple HTML generation library :star:21
* [Enums.NET](https://github.com/TylerBrinkley/Enums.NET) - Enums.NET is a high-performance type-safe .NET enum utility library :star:823
* [FastExpressionCompiler](https://github.com/dadhi/FastExpressionCompiler) - Fast ExpressionTree compiler to delegate. :star:394
* [FluentFTP](https://github.com/robinrodricks/FluentFTP/) - FTP and FTPS client, with extensive FTP commands, SSL/TLS connections, hashing/checksums and more. :star:1057
* [Fody](https://github.com/Fody/Fody) - Extensible tool for weaving .net assemblies :star:2709
* [HdrHistogram.NET](https://github.com/HdrHistogram/HdrHistogram.NET) - High Dynamic Range (HDR) Histogram. :star:102
* [httpclient-interception](https://github.com/justeat/httpclient-interception) - .NET Standard library for intercepting server-side HTTP dependencies. :star:77
* [Humanizer](https://github.com/Humanizr/Humanizer) - Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities. :star:4173
* [Humidifier](https://github.com/jakejscott/Humidifier) - Write and maintain AWS Cloudformation templates using C#. :star:36
* [LibSass Host](https://github.com/Taritsyn/LibSassHost) - .NET wrapper around the [libSass](http://sass-lang.com/libsass) library with the ability to support a virtual file system. :star:40
* [markdig](https://github.com/lunet-io/markdig) - Fast, powerfull, CommonMark compliant, extensible Markdown processor for .NET. :star:1610
* [NReco.LambdaParser](https://github.com/nreco/lambdaparser) - Parses string expressions (formulas, methods calls, conditions) to LINQ expression tree that can be compiled to lambda and evaluated. :star:125
* [NuGet Trends](https://github.com/NuGetTrends/nuget-trends) - Website with statistics of NuGet packages download count. :star:30
* [Otp.NET](https://github.com/kspearrin/Otp.NET) - An implementation TOTP RFC 6238 and HOTP RFC 4226 in C#. :star:204
* [pose](https://github.com/tonerdo/pose) - Replace any .NET method (including static and non-virtual) with a delegate :star:650
* [PuppeteerSharp](https://github.com/kblok/puppeteer-sharp) - Puppeteer Sharp is a .NET port of the official Node.JS Puppeteer API. :star:808
* [readline](https://github.com/tsolarin/readline) - Pure C# GNU-Readline like library for .NET/.NET Core. :star:661
* [ReflectionMagic](https://github.com/ReflectionMagic/ReflectionMagic) - Framework to drastically simplify your private reflection code using C# dynamic :star:170
* [Relinq](https://github.com/re-motion/Relinq) - With re-linq, it's now easier than ever to create full-featured LINQ providers. :star:366
* [ReverseMarkdown](https://github.com/mysticmind/reversemarkdown-net) - Html to Markdown converter library. :star:70
* [PdfReport.Core](https://github.com/VahidN/PdfReport.Core) - PdfReport.Core is a code first reporting engine, which is built on top of the iTextSharp.LGPLv2.Core and EPPlus.Core libraries. :star:201
* [Scientist](https://github.com/github/Scientist.net) - .NET library for carefully refactoring critical paths. It's a port of GitHub's Ruby Scientist library. :star:1079
* [Scrutor](https://github.com/khellang/Scrutor) - Assembly scanning extensions for Microsoft.Extensions.DependencyInjection. :star:789
* [SmartFormat.NET](https://github.com/scottrippey/SmartFormat.NET) - An extensible replacement for string.Format. :star:491
* Stocks
  * [Trady](https://github.com/lppkarl/Trady) - Handy library for computing technical indicators, and it targets to be an automated trading system that provides stock data feeding, indicator computing, strategy building and automatic trading. :star:282
* [System.Linq.Dynamic.Core](https://github.com/StefH/System.Linq.Dynamic.Core) - The .NET Standard (.NET Core) version from the System Linq Dynamic functionality. :star:526
* [UnitsNet](https://github.com/angularsen/UnitsNet) - Units.NET gives you all the common units of measurement and the conversions between them. :star:418
* Validation
  * [FluentValidation](https://github.com/JeremySkinner/FluentValidation) - Small validation library for .NET that uses a fluent interface and lambda expressions for building validation rules. :star:4642
  * [Guard](https://github.com/safakgur/guard) - A high-performance, extensible argument validation library. :star:210
  * [Valit](https://github.com/valit-stack/Valit) - A dead simple validation for .NET Core. No more if-statements all around your code. Write nice and clean fluent validators instead! :star:258
* [warden-stack](https://github.com/warden-stack) - "health checks" for your applications, resources and infrastructure. Keep your Warden on the watch.
* [WebEssentials.AspNetCore.ServiceWorker](https://github.com/madskristensen/WebEssentials.AspNetCore.ServiceWorker) - ASP.NET Core Progressive Web Apps. :star:210
* [Xabe.FFmpeg](https://github.com/tomaszzmuda/Xabe.FFmpeg) - .NET Standard wrapper for FFmpeg. It allows to process media without know how FFmpeg works, and can be used to pass customized arguments to FFmpeg from C# application. :star:170
* [YoutubeExplode](https://github.com/Tyrrrz/YoutubeExplode) - Ultimate library for extracting metadata and downloading Youtube videos and playlists. :star:716

### Networking
* [AspNetCore.Proxy](https://github.com/twitchax/AspNetCore.Proxy) - ASP.NET Core Proxies made easy. :star:65
* [CurlThin](https://github.com/stil/CurlThin) - Lightweight cURL binding library for C# with support for multiple simultaneous transfers through curl_multi interface. :star:20
* [NETStandard.HttpListener](https://github.com/StefH/NETStandard.HttpListener) - HttpListener for .NET Core (NETStandard). :star:23
* [Networker](https://github.com/MarkioE/Networker) - A simple to use TCP and UDP networking library for .NET, designed to be flexible, scalable and FAST. :star:319

### Office
* [EPPlus](https://github.com/JanKallman/EPPlus) - Create advanced Excel spreadsheets using .NET. :star:2456
* [npoi](https://github.com/tonyqus/npoi) - .NET library that can read/write Office formats without Microsoft Office installed. No COM+, no interop. :star:2539
* [Open-XML-SDK](https://github.com/OfficeDev/Open-XML-SDK) - The Open XML SDK provides tools for working with Office Word, Excel, and PowerPoint documents. :star:2093

### Operating System
* [CosmosOS](https://github.com/CosmosOS/Cosmos) - Cosmos is an operating system "construction kit". Build your own OS using managed languages such as C#, VB.NET, and more! :star:1714

### ORM
* [Chloe](https://github.com/shuxinqin/Chloe) - A lightweight and high-performance Object/Relational Mapping(ORM) library for .NET. :star:1017
* [Entity Framework Core](https://github.com/aspnet/EntityFramework) - Familiar developer experience to previous versions of EF, including LINQ, POCO, and Code First support. :star:7982
  * [EFCore.BulkExtensions](https://github.com/borisdj/EFCore.BulkExtensions) - EntityFrameworkCore Bulk Batch Extensions for Insert Update Delete Read (CRUD) ops :star:809
  * [EntityFramework-Plus](https://github.com/zzzprojects/EntityFramework-Plus) - Entity Framework Utilities | Bulk Operations | Batch Delete | Batch Update | Query Cache | Query Filter | Query Future | Query Include | Audit. :star:1240
  * [EntityFramework.Triggers](https://github.com/NickStrupat/EntityFramework.Triggers) - Trigger events for EF. :star:251
  * [EntityFramework.Rx](https://github.com/NickStrupat/EntityFramework.Rx) - Reactive **hot** observables of your EF operations. :star:105
  * [Npgsql.EntityFrameworkCore.PostgreSQL](https://github.com/npgsql/Npgsql.EntityFrameworkCore.PostgreSQL) - Entity Framework Core provider for PostgreSQL. :star:539
  * [EntityFramework.PrimaryKey](https://github.com/NickStrupat/EntityFramework.PrimaryKey) - Easily get the primary key of any entity (including composite keys). :star:36
  * [EntityFramework.TypedOriginalValues](https://github.com/NickStrupat/EntityFramework.TypedOriginalValues) - Get a proxy object of the orginal values of your entity (typed access to Property("...").OriginalValue). :star:26
  * [EntityFramework.VersionedProperties](https://github.com/NickStrupat/EntityFramework.VersionedProperties) - Classes which auto-magically keep an audit history of the changes to the specified property. :star:25
  * [LINQKit](https://github.com/scottksmith95/LINQKit) - A free set of extensions for LINQ to SQL and Entity Framework power users. :star:607
  * [Pomelo.EntityFrameworkCore.MySql](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MySql) - Entity Framework Core provider for MySql built on top of mysql-net/MySqlConnector. :star:1229
* [Dapper](https://github.com/StackExchange/Dapper) - Simple object mapper for .NET. :star:11168
  * [Dapper-FluentMap](https://github.com/henkmollema/Dapper-FluentMap) - Provides a simple API to fluently map POCO properties to database columns when using Dapper. :star:231
  * [Dommel](https://github.com/henkmollema/Dommel) - Simple CRUD operations for Dapper. :star:178
  * [MicroOrm.Dapper.Repositories](https://github.com/phnx47/MicroOrm.Dapper.Repositories) - CRUD for Dapper. :star:301
* [FreeSql](https://github.com/2881099/FreeSql) - a convenient ORM in dotnet,supports Mysql, Postgresql, SqlServer, Oracle and Sqlite. :star:896
* [Limebean](https://nick-lucas.github.io/LimeBean/) - Hybrid-ORM, designed to be simple to use and not totally hide SQL, while having all the nice things you expect from an ORM. Inspired by RedBeanPHP.
* [LINQ to DB (linq2db)](https://linq2db.github.io/) - The fastest LINQ database access library offering a simple, lightweight, fast, and type-safe layer between your POCO objects and your database for more than 10 database engines with full SQL support.
* [nhibernate-core](https://github.com/nhibernate/nhibernate-core) - NHibernate Object Relational Mapper. :star:1646
* [NEventStore](https://github.com/NEventStore/NEventStore) - Persistence library used to abstract different storage implementations when using event sourcing as storage mechanism. This library is developed with a specific focus on DDD/CQRS applications. :star:1378
* [NPoco](https://github.com/schotime/NPoco) - Simple microORM that maps the results of a query onto a POCO object. Project based on Schotime's branch of PetaPoco. :star:682
* [NReco.Data](https://github.com/nreco/data) - Lightweight provider-independent DAL for SQL commands generation, CRUD operations and simple POCO mapping. :star:121
* [PetaPoco](https://github.com/CollaboratingPlatypus/PetaPoco) - A tiny ORM-ish thing for your POCO's. :star:1568
* [querybuilder](https://github.com/sqlkata/querybuilder) - SqlKata Query Builder is a powerful Sql Query Builder written in C#. :star:1046
* [RepoDb](https://github.com/mikependon/RepoDb) - A dynamic, lightweight, efficient and very fast Hybrid ORM library for .NET. :star:171
* [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite) - Light, simple and fast convention-based POCO ORM. :star:1329
* [SqlFu](https://github.com/sapiens/SqlFu) - Fast and versatile Micro-ORM. :star:222
* [SmartSql](https://github.com/Ahoo-Wang/SmartSql) - SmartSql = MyBatis + Cache(Memory | Redis) + ZooKeeper + R/W Splitting +Dynamic Repository .... :star:530
* [SQLStreamStore](https://github.com/SQLStreamStore/SQLStreamStore) - Stream Store library targeting SQL based implementations for .NET. :star:219

### Profiling
* [Glimpse](https://github.com/Glimpse/Glimpse.Prototype) - Lightweight, open-source, real-time diagnostics and insights profiler for .NET. `Unstable version` :star:148
* [MiniProfiler](https://github.com/MiniProfiler/dotnet) - A simple but effective mini-profiler for ASP.NET websites. :star:1687

### Query Builders
* [SqlKata](https://github.com/sqlkata/querybuilder) - Elegant Sql Query Builder, that supports complex queries, joins, sub queries, nested where conditions, vendor engine targets and more :star:1046

### Queue and Messaging
* [emitter](https://emitter.io/) - Free open source real-time messaging service that connects all devices. This publish-subscribe messaging API is built for speed and security.
* [EventStore](https://github.com/EventStore/EventStore) - The open-source, functional database with Complex Event Processing in JavaScript. :star:3409
* [Foundatio](https://github.com/exceptionless/Foundatio#queues) - A common interface with in memory, redis and azure implementations. :star:1095
* [MediatR](https://github.com/jbogard/MediatR) - Simple, unambitious mediator implementation in .NET. :star:3654
 * [MediatR.Extensions.Microsoft.DependencyInjection](https://github.com/jbogard/MediatR.Extensions.Microsoft.DependencyInjection) - MediatR extensions for Microsoft.Extensions.DependencyInjection. :star:79
* [Mediator.Net](https://github.com/mayuanyang/Mediator.Net) - A simple mediator for .Net for sending command, publishing event and request response with pipelines supported. :star:164
* [MicroBus](https://github.com/Lavinski/Enexure.MicroBus) - Simple in process mediator for .NET. :star:158
* [MQTTnet](https://github.com/chkr1011/MQTTnet) - MQTTnet is a high performance .NET library for MQTT based communication. :star:1015
* [netmq](https://github.com/zeromq/netmq) - 100% native C# implementation of ZeroMQ for .NET. :star:1734
* [OpenCQRS](https://github.com/OpenCQRS/OpenCQRS) - .NET Core library for DDD, CQRS and Event Sourcing with Azure Service Bus integration. Supported database providers for the Command and the Event stores are: DocumentDB, MongoDB, SQL Server, MySQL, PostgreSQL and SQLite. :star:296
* [rabbitmq-dotnet-client](https://github.com/rabbitmq/rabbitmq-dotnet-client) - RabbitMQ .NET client [https://www.rabbitmq.com](https://www.rabbitmq.com). :star:1002
* [RawRabbit](https://github.com/pardahlman/RawRabbit) - Modern .NET framework for communication over RabbitMq. :star:558
* [Rebus](https://github.com/rebus-org/Rebus) - Simple and lean service bus implementation for .NET. :star:1109
* [Restbus](http://restbus.org) - Messaging library for RabbitMq.
* [Tossit](https://github.com/turgayozgur/tossit) - Simple, easy to use library for distributed job/worker logic. Distributed messages handled by built in RabbitMQ implementation. :star:49

### Reporting
* [FastReport](https://github.com/FastReports/FastReport) - The open source report generator for .NET Core 2.x/.Net Framework 4.x. FastReport can be used in MVC, Web API applications. :star:651

### Scheduler and Job
* [Chroniton.NetCore](https://github.com/leosperry/Chroniton) - Lightweight robust library for running tasks(jobs) on schedules. :star:143
* [Coravel](https://github.com/jamesmh/coravel) - .Net Core meets Laravel: Scheduling, Queuing, etc. :star:835
* [FluentScheduler](https://github.com/fluentscheduler/FluentScheduler) - Automated job scheduler with fluent interface. :star:1709
* [Gofer.NET](https://github.com/brthor/Gofer.NET) - Easy C# API for Distributed Background Tasks/Jobs for .NET Core. Inspired by celery for python. :star:251
* [HangfireIO](https://github.com/HangfireIO/Hangfire) - Easy way to perform fire-and-forget, delayed and recurring tasks inside ASP.NET apps [http://hangfire.io](http://hangfire.io). :star:5009
* [LiquidState](https://github.com/prasannavl/LiquidState) - Efficient asynchronous and synchronous state machines for .NET. :star:148
* [NCrontab](https://github.com/atifaziz/NCrontab) - Crontab for .NET. :star:328
* [quartznet](https://github.com/quartznet/quartznet/) - Quartz Enterprise Scheduler .NET [http://www.quartz-scheduler.net](http://www.quartz-scheduler.net). :star:3392
* [stateless](https://github.com/dotnet-state-machine/stateless) - Simple library for creating state machines in C# code. :star:2903

### SDKs
* [AWS SDK](https://github.com/aws/aws-sdk-net) - The Amazon Web Services (AWS) .NET Core SDK components. Each AWS service has its own NuGet package. :star:1275
* [azure-event-hubs-dotnet](https://github.com/azure/azure-event-hubs-dotnet) - .NET Standard client library for Azure Event Hubs. :star:80
* Blockchain clients
  * [Bittrex.Net](https://github.com/JKorf/Bittrex.Net) - C# .Net wrapper for the Bittrex web API including all features easily accessible and usable. :star:113
  * [Binance.Net](https://github.com/JKorf/Binance.Net) - .Net API wrapper for the Binance web API. :star:119
* [CakeMail.RestClient](https://github.com/Jericho/CakeMail.RestClient) - Client for CakeMail's API. Allows you to send transactional emails, bulk emails, manage lists and contacts, etc. :star:6
* [consuldotnet](https://github.com/PlayFab/consuldotnet/tree/develop) - .NET API for Consul. :star:630
* [csharp-nats](https://github.com/nats-io/csharp-nats) - C# .NET client for the NATS messaging system. :star:254
* [DarkSkyCore](https://github.com/amweiss/dark-sky-core) - A .NET Standard wrapper for the [Dark Sky API](https://darksky.net/dev/docs). :star:41
* [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) - .NET (C#) Client Library for Docker API. :star:906
* [firebase-admin-dotnet](https://github.com/firebase/firebase-admin-dotnet) - Firebase Admin .NET SDK :star:84
* [google-cloud-dotnet](https://github.com/GoogleCloudPlatform/google-cloud-dotnet) - Google Cloud Client Libraries for .NET. :star:474
* [Manatee.Trello](https://github.com/gregsdennis/Manatee.Trello) - A fully object-oriented .Net wrapper for Trello's RESTful API written in C#. :star:82
* [Microphone](https://github.com/rogeralsing/Microphone) - Lightweight framework to run self hosting REST services using Web Api or NancyFx ontop of a Consul or ETCD cluster. :star:458
* [octokit.net](https://github.com/octokit/octokit.net) - GitHub API client library for .NET. :star:1725
* [PreStorm](https://github.com/jshirota/PreStorm) - Parallel REST Client for ArcGIS Server. :star:14
* [SendGrid-csharp](https://github.com/sendgrid/sendgrid-csharp) - C# client library for using the full SendGrid API. :star:646
* [statsd-csharp-client](https://github.com/Pereingo/statsd-csharp-client) - .NET Standard compatible C# client to interface with Etsy's excellent [statsd](https://github.com/etsy/statsd) server. :star:108
* [tweetinvi](https://github.com/linvi/tweetinvi) - Intuitive .NET C# library to access the Twitter REST and STREAM API. :star:624

### Security
* [aspnetcore-security-headers](https://github.com/juunas11/aspnetcore-security-headers) - Middleware for adding security headers to an ASP.NET Core application. :star:128
* [HtmlSanitizer](https://github.com/mganss/HtmlSanitizer) - Cleans HTML to avoid XSS attacks. :star:650
* [jose-jwt](https://github.com/dvsekhvalnov/jose-jwt) - Library for processing JOSE objects (JWT, JWA, JWS and related). :star:586
* [Jwt.Net](https://github.com/jwt-dotnet/jwt) - Jwt.Net, a JWT (JSON Web Token) implementation for .NET. :star:1157
* [JWT Simple Server](https://github.com/Xabaril/JWTSimpleServer) - A lightweight, dynamic jwt server for ASP.NET Core. :star:137
* [NWebsec](https://github.com/NWebsec/NWebsec) - Security libraries for ASP.NET [http://www.nwebsec.com](http://www.nwebsec.com). :star:363
* [reCAPTCHA](https://github.com/PaulMiami/reCAPTCHA) - reCAPTCHA 2.0 for ASP.NET Core. :star:103
* [roslyn-security-guard](https://github.com/dotnet-security-guard/roslyn-security-guard) - Roslyn analyzers that aim to help security audit on .NET applications. :star:214
* [OwaspHeaders](https://github.com/GaProgMan/OwaspHeaders.Core) - .NET Core middleware for injecting the Owasp recommended HTTP Headers for increased security. :star:92
* [Security](https://github.com/aspnet/Security) - Middleware for security and authorization of web apps. :star:1158
* [SecurityHeaders](https://github.com/andrewlock/NetEscapades.AspNetCore.SecurityHeaders) - Small package to allow adding security headers to ASP.NET Core websites. :star:128

### Searching
* [Algolia.Search](https://github.com/algolia/algoliasearch-client-csharp) - Repository for the official Algolia .NET client. :star:71
* [AutoComplete](https://github.com/omerfarukz/autocomplete) - Persistent, simple, powerful and portable autocomplete library. :star:125
* [Elasticsearch.Net & NEST](https://github.com/elastic/elasticsearch-net) - Repository for both NEST and Elasticsearch.NET, the two official elasticsearch .NET clients. :star:2419
* [ElasticsearchCRUD](https://github.com/damienbod/ElasticsearchCRUD) - Elasticsearch .NET API. :star:120
* [SearchExtensions](https://github.com/ninjanye/SearchExtensions) - Advanced search capabilities for IQueryable interfaces, such as Entity Framework queries. :star:152
* [SimMetrics.Net](https://github.com/StefH/SimMetrics.Net) - A Similarity Metric Library, e.g. from edit distance's (Levenshtein, Gotoh, Jaro etc) to other metrics, (e.g Soundex, Chapman) :star:51
* [SolrExpress](https://github.com/solr-express/solr-express) - Simple and lightweight query .NET library for Solr, in a controlled, buildable and fail fast way. :star:62

### Serialization
* [BinarySerializer](https://github.com/jefffhaynes/BinarySerializer) - Serialization for custom packet and protocol formats, supports bit-twiddling. :star:118
* [bond](https://github.com/Microsoft/bond) - Cross-platform framework for working with schematized data. It supports cross-language de/serialization and powerful generic mechanisms for efficiently manipulating data. Bond is broadly used at Microsoft in high scale services. :star:2002
* [Channels](https://github.com/davidfowl/Channels) - Push based .NET Streams. :star:294
* [CsvHelper](https://github.com/JoshClose/CsvHelper) - Library to help reading and writing CSV files. :star:2433
* [Edi.Net](https://github.com/indice-co/EDI.Net) - EDI Serializer/Deserializer. Supports EDIFact, X12 and TRADACOMS format. :star:172
* [ExtendedXmlSerializer](https://github.com/wojtpl2/ExtendedXmlSerializer) - Extended Xml Serializer for .NET. :star:122
* [Jil](https://github.com/kevin-montrose/Jil) - Fast .NET JSON (De)Serializer, Built On Sigil. :star:1914
* MessagePack 
  * [msgpack-cli](https://github.com/msgpack/msgpack-cli) - MessagePack implementation for Common Language Infrastructure / [msgpack.org](http://msgpack.org). :star:677
  * [MessagePack-CSharp](https://github.com/neuecc/MessagePack-CSharp) - Extremely Fast MessagePack Serializer for C#(.NET, .NET Core, Unity, Xamarin). :star:2029
* [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) - Popular high-performance JSON framework for .NET. :star:7151
* [protobuf-net](https://github.com/mgravell/protobuf-net/) - Protocol Buffers library for idiomatic .NET. :star:2543
* [Schema.NET](https://github.com/RehanSaeed/Schema.NET) - Schema.org objects turned into strongly typed C# POCO classes for use in .NET. All classes can be serialized into JSON/JSON-LD and XML, typically used to represent structured data in the head section of html page. :star:207
* [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text) - JSON, JSV and CSV Text Serializers. :star:1042
* [TinyCsvParser](https://github.com/bytefish/TinyCsvParser) - Easy to use, easy to extend and high-performance library for CSV parsing with .NET. :star:146
* [Wire](https://github.com/rogeralsing/Wire) - Binary serializer for POCO objects. :star:357
* [YamlDotNet](https://github.com/aaubry/YamlDotNet) - .NET :star:935
* [ZeroFormatter](https://github.com/neuecc/ZeroFormatter) - Fast binary (de)serializer for .NET. :star:1752
* [Utf8Json](https://github.com/neuecc/Utf8Json) - Definitely Fastest and Zero Allocation JSON Serializer for C#(NET, .NET Core, Unity, Xamarin). :star:1332
* [YAXLib](https://github.com/sinairv/YAXLib) - XML Serialization Library for the .NET Framework and .NET Core. Extremely flexible and powerful. :star:105

### Template Engine
* [dotliquid](https://github.com/dotliquid/dotliquid) - .NET Port of Tobias Lütke's Liquid template language. :star:649
* [fluid](https://github.com/sebastienros/fluid) - Open-source .NET template engine that is as close as possible to the Liquid template language. :star:251
* [Portable.Xaml](https://github.com/cwensley/Portable.Xaml) - Portable .NET library for reading/writing xaml files. :star:122
* [Razor](https://github.com/aspnet/Razor) - Parser and code generator for CSHTML files used in view pages for MVC web apps. :star:879
* [RazorLight](https://github.com/toddams/RazorLight) - Template engine based on Microsoft's Razor parsing engine for .NET Core. :star:667
* [Scriban](https://github.com/lunet-io/scriban) - A fast, powerful, safe and lightweight text templating language and engine for .NET. :star:514

### Testing
* [Bogus](https://github.com/bchavez/Bogus) - Simple and sane fake data generator for C#. Based on and ported from the famed faker.js. :star:2180
* [CoreBDD](https://github.com/stevenknox/CoreBDD) - BDD framework for xUnit.net :star:8
* [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy) - The easy mocking library for .NET. :star:880
* [FluentAssertions](https://github.com/dennisdoomen/FluentAssertions) - Set of .NET extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style test. :star:29
* [GenFu](https://github.com/MisterJames/GenFu) - Library you can use to generate realistic test data. :star:501
* [LightBDD](https://github.com/LightBDD/LightBDD) - BDD framework allowing to create easy to read and maintain tests. :star:125
* [mockhttp](https://github.com/richardszalay/mockhttp) - Testing layer for Microsoft's HttpClient library. :star:422
* [moq.netcore](https://github.com/Moq/moq4) - Most popular and friendly mocking framework for .NET. :star:3065
* [MSpec](https://github.com/machine/machine.specifications) - Popular testing framework for writing BDD-style tests. :star:761
* [MyTested.AspNetCore.Mvc](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc) - Fluent testing :star:970
  framework for ASP.NET Core MVC.
* [Netling](https://github.com/hallatore/Netling) - Load tester client for easy web testing. :star:1045
* [NSpec](https://github.com/nspec/NSpec) - Battle hardened testing framework for C# that's heavily inspired by Mocha and RSpec. :star:224
* [NSubstitute](https://github.com/nsubstitute/NSubstitute) - A friendly substitute for .NET mocking frameworks. :star:1224
* [nunit](https://github.com/nunit/dotnet-test-nunit) - NUnit test runner for .NET Core. :star:64
* [shouldly](https://github.com/shouldly/shouldly) - Should testing for .NET - the way Asserting *Should* be! [http://shouldly.readthedocs.org/en/latest](http://shouldly.readthedocs.org/en/latest)
* [SpecFlow](https://github.com/techtalk/SpecFlow) - Pragmatic BDD solution for .NET. It uses the Gherkin specification language and integrates to Visual Studio. :star:1469
* [Storyteller](https://github.com/storyteller/Storyteller) - Executable Specifications for .NET [http://storyteller.github.io](http://storyteller.github.io). :star:237
* [Stubbery](https://markvincze.github.io/Stubbery/) - A simple library for creating and running Api stubs in .NET.
* [Testavior](https://github.com/geeklearningio/Testavior) - Testavior is a lightweight solution to help you develop Behavior Tests for ASP.NET Core. :star:37
* [TestStack.BDDfy](https://github.com/TestStack/TestStack.BDDfy) - The simplest BDD framework EVER! :star:316
* [xBehave.net](https://github.com/xbehave/xbehave.net) - An xUnit.net extension for describing your tests using natural language. [http://xbehave.github.io](http://xbehave.github.io)
* [xUnit.net](https://github.com/xunit/xunit) - A free, open source, community-focused unit testing tool for the .NET Framework. :star:2224

### Tools
* [CommandLineUtils](https://github.com/natemcmaster/CommandLineUtils) - Command line parsing and utilities for .NET Core and .NET Framework. :star:959
* [docfx](https://github.com/dotnet/docfx) - Tools for building and publishing API documentation for .NET projects [http://dotnet.github.io/docfx](http://dotnet.github.io/docfx)
* [dotnetfiddle](https://dotnetfiddle.net) - .NET sandbox for developers to quickly try out code and share code snippets.
* [dotnet-tools](https://github.com/natemcmaster/dotnet-tools) - A list of tool extensions for .NET Core Command Line (dotnet CLI). :star:959
  * [LibMan CLI](https://github.com/aspnet/LibraryManager) - Client-side content manager for web apps. :star:238
* [EntryPoint](https://github.com/Nick-Lucas/EntryPoint) - Composable CLI (Command Line) Argument Parser for .Net Core & .Net Framework 4.5+. :star:121
* [Fake JSON Server](https://github.com/ttu/dotnet-fake-json-server) - Fake REST API for prototyping or as a CRUD Back End. No need to define types, uses dynamic typing. Data is stored to a single JSON file. Has authentication, WebSocket notifications, async long running operations, random generation for errors/delays and experimental GraphQL support. :star:169
* [gitignore.io](https://github.com/joeblau/gitignore.io) - Create useful .gitignore files for your project [https://www.gitignore.io](https://www.gitignore.io). :star:4806
* [ICanHasDotnetCore](https://github.com/OctopusDeploy/ICanHasDotnetCore) - Scans uploaded packages.config files or GitHub repository and determines whether the nuget packages target .NET Standard [https://icanhasdot.net](https://icanhasdot.net). :star:61
* [json2csharp](http://json2csharp.com) - Generate C# classes from JSON.
* [letsencrypt-win-simple](https://github.com/Lone-Coder/letsencrypt-win-simple) - A Simple ACME Client for Windows. :star:3089
* [Linq_Faster](https://github.com/jackmott/LinqFaster) - Linq-like extension functions for Arrays, Span<T>, and List<T> that are faster and allocate less. :star:453
 
* [mRemoteNG](https://github.com/mRemoteNG/mRemoteNG) - The next generation of mRemote, open source, tabbed, multi-protocol, remote connections manager :star:3471
* [NJsonSchema](https://github.com/RSuter/NJsonSchema) - NJsonSchema is a .NET library to read, generate and validate JSON Schema draft v4+ schemas. :star:534
* [NuKeeper](https://github.com/NuKeeperDotNet/NuKeeper) - Automagically update nuget packages in .NET projects. :star:283
* [NuGetPackageExplorer](https://github.com/NuGetPackageExplorer/NuGetPackageExplorer) - Create, update and deploy Nuget Packages with a GUI. :star:1303
* [NugetVisualizer](https://github.com/sepharg/NugetVisualizer) - Visualize all of the nuget packages and their corresponding versions for a set of given git repositories or folders. :star:15
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through `projects.json` files efficiently with the OctoLinker browser extension for GitHub. :star:3829
* [posh-dotnet](https://github.com/bergmeister/posh-dotnet) - `PowerShell` tab completion for the [dotnet CLI](https://github.com/dotnet/cli). :star:20
* [Rin](https://github.com/mayuki/Rin) - Request/response Inspector middleware for ASP.NET Core. like Glimpse. :star:198
* [scoop](https://github.com/lukesampson/scoop) - A command-line installer for Windows. :star:8321
* [SerilogAnalyzer](https://github.com/Suchiman/SerilogAnalyzer) - Roslyn-based analysis for code using the Serilog logging library. Checks for common mistakes and usage problems. :star:150
* [SharpZipLib](https://github.com/icsharpcode/SharpZipLib) - #ziplib is a Zip, GZip, Tar and BZip2 library written entirely in C# for the .NET platform. :star:1854
* [ShareX](https://github.com/ShareX/ShareX) - Free and open source program that lets you capture or record any area of your screen and share it with a single press of a key. It also allows uploading images, text or other types of files to over 80 supported destinations you can choose from. [https://getsharex.com](https://getsharex.com)
* [SharpLab](https://github.com/ashmind/SharpLab) - .NET code playground that shows intermediate steps and results of code compilation. [https://sharplab.io](https://sharplab.io)
* [sourcelink](https://github.com/dotnet/sourcelink) - SourceLink is a language- and source-control agnostic system for providing first-class source debugging experiences for binaries. :star:449
* [X.Web.Sitemap](https://github.com/dncuug/X.Web.Sitemap) – Simple sitemap generator for .NET and .NET Core
* [X.Web.RSS](https://github.com/dncuug/X.Web.RSS) – Simple RSS Feed generator for .NET and .NET Core
* [SmartCode](https://github.com/Ahoo-Wang/SmartCode) – SmartCode= IDataSource -> IBuildTask -> IOutput => Build Everything!!! (Including [Code generator]) :star:323

### Web Framework
* WebAssembly
  * [Blazor](https://github.com/SteveSanderson/Blazor) - UI framework running .NET in the browser via WebAssembly. :star:1768
    * [Blazor Redux](https://github.com/torhovland/blazor-redux) - Connecting a Redux state store with Blazor. :star:339
  * [Ooui](https://github.com/praeclarum/Ooui) - Small cross-platform UI library that brings the simplicity of native UI development to the web. :star:1260
* [ReactJS.NET](https://github.com/reactjs/React.NET) - .NET library for JSX compilation and server-side rendering of React components. :star:1782
* [redux.NET](https://github.com/GuillaumeSalles/redux.NET) - Predictable state container for .NET apps. Inspired by [https://github.com/reactjs/redux](https://github.com/reactjs/redux). :star:621

### Web Socket
* [Fleck](https://github.com/statianzo/Fleck) - Fleck is a WebSocket server implementation in C#. Fleck requires no inheritance, container, or additional references. :star:1319
* [SignalR Server](https://github.com/aspnet/signalr) - Real-time web functionality for web apps, including server-side push. :star:2411
* [SuperSocket](https://github.com/kerryjiang/SuperSocket) - Light weight, cross platform and extensible socket server application framework. :star:2036
* [WampSharp](https://github.com/Code-Sharp/WampSharp) - C# implementation of [The Web Application Messaging Protocol](http://wamp-proto.org/) - Protocol that provides messaging patterns of Remote Procedure Calls and Publish/Subscribe over WebSockets.
* [websocket-manager](https://github.com/radu-matei/websocket-manager) - Real-Time library for ASP .NET Core. :star:336

### Windows Service
* [dotnet-win32-service](https://github.com/dasMulli/dotnet-win32-service) - Set up and run as Windows Service directly from .NET Core. :star:403
* [Topshelf](https://github.com/Topshelf/Topshelf) - Easy service hosting framework for building Windows services using .NET. :star:2978

### Workflow
* [CoreWF](https://github.com/dmetzgar/corewf/) - Port of Windows Workflow Foundation (WF) to .NET Core. :star:378
* [workflow-core](https://github.com/danielgerlag/workflow-core) - Lightweight workflow engine for .NET Standard. :star:1399
* [WorkflowEngine.NET](https://github.com/optimajet/WorkflowEngine.NET) - Component that adds workflow in your application. :star:435
* [Wexflow](https://github.com/aelassas/Wexflow) - A high performance, extensible, modular and cross-platform workflow engine. :star:1318

## Roadmaps
* [ASP.NET Core Developer Roadmap](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap) - Roadmap to becoming an ASP.NET Core developer in 2019. :star:2004

## Starter Kits
* [Arch](https://github.com/Arch) - The collection of .NET Core libraries that are created by software architects who embrace all the new stuff in .NET Core.
  * [AutoHistory](https://github.com/Arch/AutoHistory) - A plugin for Microsoft.EntityFrameworkCore to support automatically recording data changes history. :star:280
* [AspNetCore-Angular2-Universal](https://github.com/MarkPieszak/aspnetcore-angular2-universal) - Cross-platform - w/ server-side rendering for SEO, Bootstrap, i18n internationalization (ngx-translate), Webpack, TypeScript, unit testing w/ Karma, WebAPI REST setup, SignalR, Swagger docs, and more! :star:1391
* [ASP.NET Core Starter Kit](https://github.com/kriasoft/aspnet-starter-kit) - Opinionated boilerplate for web development based on .NET Core, Kestrel, GraphQL on the backend and Babel, Webpack, React and Redux on the frontend. This boilerplate comes in both C# and F# flavors. :star:1015
* [aspnetcore-spa generator](https://github.com/aspnet/JavaScriptServices) - Yeoman generator to build a brand-new ASP.NET Core single page application that uses Angular 2 / React / React With Redux / Knockout / Aurelia on the client. :star:3168
* [ASP.Net Core Vue Starter](https://github.com/MarkPieszak/aspnetcore-Vue-starter) - Asp.NETCore 2.0 Vue 2 (ES6) SPA Starter kit, contains routing, Vuex, and more!. :star:1021
* [bitwarden-core](https://github.com/bitwarden/core) - The core infrastructure backend (API, database, etc) [https://bitwarden.com](https://bitwarden.com). :star:3657
* [dotNetify](https://github.com/dsuryd/dotNetify) - Simple, lightweight, yet powerful way to build real-time HTML5/C# .NET web apps. :star:747
* [generator-aspnet](https://github.com/OmniSharp/generator-aspnet) - yo generator for ASP.NET Core. :star:899
* [Nucleus](https://github.com/alirizaadiyahsi/Nucleus) - Vue startup application template that uses ASP.NET Core API layered architecture at the back-end and JWT based authentication :star:114
* [react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate) - Starting point for building isomorphic React applications with ASP.NET Core 1, leveraging existing techniques. :star:280
* [saaskit](https://github.com/saaskit/saaskit) - Developer toolkit for building SaaS applications. :star:759
* [serverlessDotNetStarter](https://github.com/pharindoko/serverlessDotNetStarter) starter kit for development and deployment of lambda functions in the AWS cloud based on serverless framework.

## Sample Projects
* Microservices & Service Mesh
  * [coolstore-microservices ](https://github.com/vietnam-devs/coolstore-microservices) - A Kubernetes-based polyglot microservices application with Istio service mesh :star:971
  * [distributed-playground](https://github.com/jvandevelde/distributed-playground) - Distributed service playground with Vagrant, Consul, Docker & ASP.NET Core. :star:31
  * [DNC-DShop](https://github.com/devmentors) - Distributed .NET Core project and free course. (DDD, CQRS, RabbitMQ, MongoDB, Redis, Monitoring, Logging, CI, CD)
  * [dotnetcore-microservices-poc](https://github.com/asc-lab/dotnetcore-microservices-poc) -  simplified insurance sales system made in a microservices architecture using .NET Core (EF Core, MediatR, Marten, Eureka, Ocelot, RabbitMQ, Polly, ElasticSearch, Dapper) with blog post series. :star:487
  * [eShopOnContainers](https://github.com/dotnet/eShopOnContainers) - Microservices Architecture and Containers based Reference Application. :star:10986
  * [InMemoryCQRSReplication](https://github.com/Aaronontheweb/InMemoryCQRSReplication) - Akka.NET Reference Architecture - CQRS + Sharding + In-Memory Replication :star:59
  * [magazine-website](https://github.com/thangchung/magazine-website) - Magazine website (using .NET Core, ASP.NET Core, EF Core) with DDD, CQRS, microservices, asynchronous programming applied. :star:125
  * [microservices-in-dotnetcore](https://github.com/horsdal/microservices-in-dotnetcore) - The code sample from my microservices book -[https://manning.com/books/microservices-in-net-core](https://manning.com/books/microservices-in-net-core)
  * [ReactiveTraderCloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - Real-time trading platform demo showcasing reactive programming principles applied across the full application stack. :star:1180
* Monoliths
  * [AlbumViewerVNext](https://github.com/RickStrahl/AlbumViewerVNext) - West Wind Album Viewer ASP.NET 5 Sample. :star:406
  * [allReady](https://github.com/HTBox/allReady) - Open-source solution focused on increasing awareness, efficiency and impact of preparedness campaigns as they are delivered by humanitarian and disaster response organizations in local communities. [http://www.htbox.org/projects/allready](http://www.htbox.org/projects/allready)
  * [AspNet5GeoElasticsearch](https://github.com/damienbod/AspNet5GeoElasticsearch) - ASP.NET Core MVC Geo Elasticsearch Swashbuckle Swagger. :star:35
  * [aspnet-servicediscovery-patterns](https://github.com/cecilphillip/aspnet-servicediscovery-patterns) - Samples of implementing Service Discovery patterns with ASP.NET Core. :star:217
  * [AspNetAuthorizationWorkshop](https://github.com/blowdart/AspNetAuthorizationWorkshop) - A workshop for moving through the various new pieces in ASP.NET Core Authorization :star:926
  * [BikeSharing360 Suite of Apps from Microsoft](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/) Presented December Connect 2016 Conference, a compreshsive set of interworking apps for both enterprise users and the consumers (bike riders): [Mobile Apps](https://github.com/Microsoft/BikeSharing360_MobileApps), [Backend Services](https://github.com/Microsoft/BikeSharing360_BackendServices), [Websites](https://github.com/Microsoft/BikeSharing360_Websites), [Single Container Apps](https://github.com/Microsoft/BikeSharing360_SingleContainer), [Multi Container Apps](https://github.com/Microsoft/BikeSharing360_MultiContainer), [Cognitive Services Kiosk App](https://github.com/Microsoft/BikeSharing360_CognitiveServicesKioskApp),
 [Azure Bot App](https://github.com/Microsoft/BikeSharing360_BotApps).
  * [cloudscribe](https://github.com/cloudscribe/cloudscribe) - ASP.NET Core Multi-tenant web application foundation. :star:796
  * [CoreCodeCamp](https://github.com/shawnwildermuth/CoreCodeCamp) - An Open Source Website for running small, local development events. :star:57
  * [DotNetClub](https://github.com/scheshan/DotNetClub) - Tiny club written in ASP.NET Core. :star:240
  * [eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb) - A layered application architecture with monolithic deployment model. :star:3201
  * [Entropy](https://github.com/aspnet/Entropy) - Chaotic experimental playground for new features and ideas - check here for small and simple samples for individual features. :star:462
  * [EquinoxProject](https://github.com/EduardoPires/EquinoxProject) - Full ASP.NET Core 2.0 application with DDD, CQRS and Event Sourcing. :star:2828
  * [GenVue](https://github.com/herbat73/GenVue) - a hostable, web application that lets confidential users upload and share private files build on Vue.js, Vuetifyjs and NetCore WebAPI stack :star:84
  * [guidance-identity-management-for-multitenant-apps](https://github.com/Azure-Samples/guidance-identity-management-for-multitenant-apps) - How to manage user identities in a multitenant app on Microsoft Azure, using Azure Active Directory for authentication. :star:57
  * [JustA.ML](https://github.com/mustakimali/JustA.ML) - A web application that lets you share files/URL/text between your devices written in ASP.NET Core 2.0. Open source, live at [https://justa.ml](https://justa.ml)
  * [MegaMine](https://github.com/Nootus/MegaMine) - Open source mining solution that helps miners in extracting Gold, Quartz, Granite etc. This solution is built using ASP.NET Core and AngularJS utilizing multiple light weight components in a Microservices way. :star:24
  * [minicompiler](https://github.com/ealsur/minicompiler) - Minification, bundling and compiling sample. :star:9
  * [MusicStore](https://github.com/aspnet/MusicStore) - Sample MusicStore application that uses MVC and Entity Framework. :star:1358
  * [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) - NLayerAppV3 N-Layered Architecture with .NET Core Preview 2. :star:112
  * [NorthwindTraders](https://github.com/JasonGT/NorthwindTraders) - Northwind Traders is a sample application built using ASP.NET Core and Entity Framework Core. :star:2497
  * [Orchard Core - Modular and Multi-tenant applications](https://github.com/OrchardCMS/OrchardCore.Samples) - Use Orchard Core Framework to create Modular and Multi-tenant applications. :star:104
  * [PhotoGallery](https://github.com/chsakell/aspnet5-angular2-typescript) - Cross-platform Single Page Applications with ASP.NET Core, Angular 2 & TypeScript [http://wp.me/p3mRWu-11L](http://wp.me/p3mRWu-11L). :star:360
  * [Practical ASP.NET Core](https://github.com/dodyg/practical-aspnetcore) - A daily updated micro samples of ASP.NET Core features and facilities. :star:2902
  * [Sample .NET Core CQRS REST API](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) - .NET Core REST API CQRS implementation with raw SQL and DDD using Clean Architecture. :star:223
  * [StarWars](https://github.com/JacekKosciesza/StarWars) - GraphQL 'Star Wars' example using GraphQL for .NET, ASP.NET Core, Entity Framework Core. :star:452
 
## Articles
* Basic knowledge
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
  * [A very good example about EF Core](https://github.com/rowanmiller/Demo-EFCore) :star:111
  * [Connect to Postgres with EF Core](http://en.otomatikmuhendis.com/2017/05/05/connect-to-postgres-with-ef-core/)
* Miraculous
  * [Getting started with Orchard Core as a NuGet package](http://www.ideliverable.com/blog/getting-started-with-orchard-core-as-a-nuget-package)
  * [How to export HTML to PDF in ASP.NET Core](https://code.msdn.microsoft.com/How-to-export-HTML-to-PDF-c5afd0ce)
  * [Vue.js server side rendering with ASP.NET Core](http://mgyongyosi.com/2016/Vuejs-server-side-rendering-with-aspnet-core/)
* Security
  * [.NET Continuous Delivery Microservices](http://stackshare.io/tomstaijen/net-continuous-delivery-microservices)
  * [ASP.NET Core 2.0 Authentication and Authorization System Demystified](https://digitalmccullough.com/posts/aspnetcore-auth-system-demystified.html)
  * [A walk-through for an ASP.NET Authorization Lab](https://github.com/blowdart/AspNetAuthorizationWorkshop) :star:926
  * [Authentication in ASP.NET Core](https://stormpath.com/blog/authentication-asp-net-core)
* Testing
  * [Selenium with .NET Core](http://www.dotnetcatch.com/2016/11/23/selenium-with-net-core/)
- [InfoQ .NET articles](https://www.infoq.com/dotnet) -  Collection of best .NET articles on InfoQ site

## Books
* [.NET Core in Action](https://manning.com/books/dotnet-core-in-action)
* [ASP.NET Core Application Development: Building an application in four sprints (Developer Reference)](https://www.amazon.com/ASP-NET-Core-Application-Development-application/dp/1509304061)
* [ASP.NET Core in Action](https://www.manning.com/books/asp-net-core-in-action)
* [ASP.NET Core 1.0 High Performance](https://www.amazon.com/ASP-NET-Core-1-0-High-Performance/dp/1785881892)
* [Building Microservices with ASP.NET Core: Develop, Test, and Deploy Cross-Platform Services in the Cloud](https://www.amazon.com/Building-Microservices-ASP-NET-Core-Cross-Platform/dp/1491961732)
* [C# 6 and .NET Core 1.0: Modern Cross-Platform Development](https://www.amazon.com/NET-Core-1-0-Cross-Platform-Development/dp/1785285696)
* [C# in Depth 4](https://www.amazon.com/C-Depth-Jon-Skeet/dp/1617294535)
* [Dependency Injection in .NET Core, 2nd edition](https://www.manning.com/books/dependency-injection-in-dot-net-second-edition)
* [Essencial C# 7.0](https://www.amazon.com/Essential-7-0-Addison-Wesley-Microsoft-Technology/dp/1509303588)
* [Exploring .NET Core with Microservices, ASP.NET Core, and Entity Framework Core - free eBook sampler](https://www.manning.com/books/exploring-dot-net-core)
* [Microservices in .NET Core: with C#, the Nancy framework, and OWIN middleware](https://www.amazon.com/Microservices-NET-Core-framework-middleware/dp/1617293377)
* [Professional C# 6 and .NET Core 1.0](https://www.amazon.com/Professional-NET-Core-Christian-Nagel/dp/111909660X)
* [The little ASP.NET Core](https://www.recaffeinate.co/book)

## Cheat Sheets
* [dotnet cli Cheat Sheet](http://en.otomatikmuhendis.com/2018/07/02/cheat-sheet-for-dotnet-cli/)

## Videos
* [Channel9](https://channel9.msdn.com) - MSDN
* [Channel9](https://www.youtube.com/channel/UCsMica-v34Irf9KVTh6xx-g) - YouTube
 * [ASP.NET Monsters](https://channel9.msdn.com/Series/aspnetmonsters)
* [Visual Studio](https://www.youtube.com/user/VisualStudio/channels)

## Podcasts
* [.NET Rocks](https://www.dotnetrocks.com)
* [Merge Conflict](http://www.mergeconflict.fm/)
* [The sound of .NET](http://thesoundof.net/?q=.NET+Core)

## Community
* [.NET Foundation](http://forums.dotnetfoundation.org)
* [.NET Blog](https://devblogs.microsoft.com/dotnet/)
* [/r/CoolGithubProjects](https://www.reddit.com/r/coolgithubprojects)
* [ASP.NET](https://forums.asp.net)
* [Channel9](https://channel9.msdn.com)
* [Awesome .NET open source & community resources](https://discoverdot.net)
* [Slack](http://tattoocoder.com/aspnet-slack-sign-up)
* [BuiltWithDot.Net](https://builtwithdot.net)
* Stack Overflow
  *  [.NET Core](https://stackoverflow.com/questions/tagged/.net-core)
  *  [CoreCLR](https://stackoverflow.com/questions/tagged/coreclr)
  *  [ASP.NET Core](https://stackoverflow.com/questions/tagged/asp.net-core)
  *  [ASP.NET Core MVC](https://stackoverflow.com/questions/tagged/asp.net-core-mvc)
  *  [ASP.NET Core 1.0](https://stackoverflow.com/questions/tagged/asp.net-core-1.0)
  *  [Entity Framework Core](https://stackoverflow.com/questions/tagged/entity-framework-core)
* [Trending .NET repositories on GitHub today](https://github.com/trending?l=csharp)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [thangchung](http://weblogs.asp.net/thangchung) has waived all copyright and related or neighboring rights to this work.


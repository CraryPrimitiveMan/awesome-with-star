# Information comes from [Urigo/awesome-meteor](https://github.com/Urigo/awesome-meteor)
# Awesome Meteor [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Meteor Packages, libraries and software.

The official Meteor resources page can be found [here](https://www.meteor.com/tools/resources)

- [Awesome Meteor](#awesome-meteor)
    - [Getting Started](#getting-started)
    - [Collections](#collections)
    - [Forms and Templates](#forms-and-templates)
    - [Users and Authentication](#users-and-authentication)
    - [REST](#rest)
    - [Files](#files)
    - [Routers](#routers)
    - [Debugging Tools](#debugging-tools)
    - [Editor Plugins](#editor-plugins)
    - [Search, sort and paginate](#search-sort-paginate)
    - [Mobile](#mobile)
    - [Offline](#offline)
    - [Testing](#testing)
    - [SEO](#seo)
    - [Data Visualization](#data-visualization)
    - [Analytics](#analytics)
    - [Cron Jobs](#cron-jobs)
    - [Payments](#payments)
    - [Administration](#administration)
    - [Performance](#performance)
    - [Monitoring](#monitoring)
    - [Deployment](#deployment)
    - [Front End Frameworks](#front-end-frameworks)
    - [Alternative Databases](#alternative-databases)
    - [Boilerplate](#boilerplate)
    - [Open Source Apps](#open-source-apps)
    - [Package managers](#package-managers)
    - [Internationalization](#internationalization)
    - [Scaffolding](#scaffolding)
    - [Tooling](#tooling)
- [Resources](#resources)
    - [Books](#books)
    - [Courses](#courses)
    - [Tutorials](#tutorials)
    - [Blogs](#blogs)
    - [Websites](#websites)
    - [Weekly](#weekly)
    - [Twitter](#twitter)
    - [Job Boards](#job-boards)
- [Built With Meteor](#built-with-meteor)    
- [Contributing](#contributing)

- - -


## Getting Started

*Where to start*

* [Official Meteor tutorial](https://www.meteor.com/try)
* [Discover Meteor Book](https://www.discovermeteor.com/)
* [Official Guide](http://guide.meteor.com/)
* [Why Meteor](https://wiki.dandascalescu.com/essays/why_meteor) to begin with, and [Meteor vs. the MEAN stack](https://wiki.dandascalescu.com/essays/meteor_js_vs_the_mean_stack)

## Collections

*Helpers and expensions for collections*

* [node-simple-schema](https://github.com/aldeed/node-simple-schema/) - A JavaScript schema validation package that supports direct validation of MongoDB update modifier objects :star:438
* [aldeed:collection2](https://github.com/aldeed/meteor-collection2/) - Automatic validation of insert and update operations on the client and server. :star:1006
* [dburles:collection-helpers](https://github.com/dburles/meteor-collection-helpers/) – Transform your collections with helpers that you define.
* [matb33:collection-hooks](https://github.com/matb33/meteor-collection-hooks/) - Extends Mongo.Collection with before/after hooks for insert/update/remove/find/findOne. :star:627
* [reywood:publish-composite](https://github.com/englue/meteor-publish-composite) - publish a set of related documents from various collections using a reactive join :star:537
* [jagi:astronomy](https://github.com/jagi/meteor-astronomy/) - The Model layer for Meteor :star:596
* [cultofcoders:grapher](https://github.com/cult-of-coders/grapher) - Grapher: Meteor Collection Joins + Reactive GraphQL like queries :star:227


## REST

*REST support for Meteor*

* [simple:rest](https://github.com/stubailo/meteor-rest) - automatically make your Meteor app accessible over HTTP and DDP alike. :star:370
* [nimble:restivus](https://github.com/kahmali/meteor-restivus) - Make REST endpoints for your Meteor app with incredible ease. :star:548

## Forms and Templates

*Helpers for templates*

* [aldeed:autoform](https://github.com/aldeed/meteor-autoform) - UI components and helpers to easily create basic forms with automatic insert and update events, and automatic reactive validation. :star:1450
* [aldeed:template-extension](https://github.com/aldeed/meteor-template-extension) - A Meteor package: Replace already defined templates, inherit helpers and events from other templates. :star:219
* [kadira:blaze-layout](https://github.com/kadirahq/blaze-layout) - Layout Manager for Blaze (works well with Meteor FlowRouter) :star:202
* [dispatch:scrollview](https://github.com/DispatchMe/meteor-scrollview) - A high performance infinite scrollview for meteor :star:26
* [themeteorites:blaze-magic-events](https://github.com/themeteorites/blaze-magic-events) - A new way of binding event handlers to html elements for Meteor's Blaze :star:26
* [manuel:viewmodel](https://github.com/ManuelDeLeon/viewmodel) - MVVM for Meteor :star:206
* [webix:webix](https://github.com/dandv/meteor-webix) - Meteor.js - Webix UI integration :star:340
* [uniforms](https://github.com/vazco/uniforms) - Bunch of React components and helpers to easily generate and validate forms. [Seamlessly integrate with `aldeed:simple-schema` and `simpl-schema`](https://github.com/vazco/uniforms/blob/master/INTRODUCTION.md#quick-start). :star:796

## Users and Authentication

*Tools for handling users and authentication*

* [accounts-base](https://guide.meteor.com/accounts.html) - Meteor's user account system.
* [alanning:roles](https://github.com/alanning/meteor-roles) - Roles support for the built-in accounts packages. :star:886

## Payments

*Tools for handling payments in Meteor*

* [Stripe](https://atmospherejs.com/mrgalaxy/stripe) - payment gateway for Stripe
* [PayPal](https://atmospherejs.com/mrt/paypal) - payment gateway for PayPal
* [BrainTree](https://atmospherejs.com/patrickml/braintree) - payment gateway for BrainTree
* [Instamojo](https://atmospherejs.com/instamojo/instamojo) - payment gateway for Instamojo

## Administration

*Tools for administrating your Meteor apps*

* [Meteor Candy](https://www.meteorcandy.com/) - Fastest and easier way to add an admin panel to your app
* [yogiben:admin](https://github.com/yogiben/meteor-admin) - A complete admin dashboard solution :star:835
* [houston:admin](https://github.com/gterrono/houston) - A zero-config, Django Admin-like admin for Meteor :star:819


## Monitoring

*Tools for monitoring your Meteor apps*

* [kschingiz:meteor-elastic-apm](https://github.com/kschingiz/meteor-elastic-apm) - Perfomance Monitoring for Meteor based on Elastic APM :star:41
* [monti-apm-agent](https://github.com/monti-apm/monti-apm-agent) - Performance Monitoring for Meteor :star:18
* [meteorhacks:kadira](https://github.com/meteorhacks/kadira) - Performance Monitoring for Meteor :star:211


## Performance

*Tools for speeding up your Meteor apps*

* [cultofcoders:redis-oplog](https://github.com/cult-of-coders/redis-oplog) - Redis Oplog implementation to fully replace MongoDB Oplog in Meteor :star:304
* [staringatlights:fast-render](https://github.com/abecks/meteor-fast-render) - An active fork of fast-render :star:46
* [meteorhacks:fast-render](https://github.com/kadirahq/fast-render) - Render you app even before the DDP connection is live :star:580
* [epotek:method-cache](https://github.com/e-Potek/method-cache) - Meteor method caching using DataLoader :star:6


## Deployment

*Tools for deploying and maintaining Meteor apps*

* [meteor-up](https://github.com/arunoda/meteor-up) – Meteor Deployments.
* [meteor-google-cloud](https://github.com/EducationLink/meteor-google-cloud) - Automate Meteor deployments on Google Cloud App Engine Flexible :star:23
* [mup-aws-beanstalk](https://github.com/zodern/mup-aws-beanstalk) - Deploy Meteor apps to AWS Elastic Beanstalk using Meteor Up :star:103
* [meteor-azure](https://github.com/fractal-code/meteor-azure) - Automate Meteor deployments on Azure App Service :star:67
* [pm2-meteor](https://github.com/andruschka/pm2-meteor) - Simplest way to deploy, scale and run Meteor Apps with PM2. :star:158
* [meteorhacks:cluster](https://github.com/meteorhacks/cluster) - Clustering solution for Meteor with load balancing and service discovery :star:640
* [davidyaha:collection2-migrations](https://github.com/davidyaha/meteor-collection2-migrations) - Auto DB migrations with collection2 and simple schema on Meteor :star:36
* [percolate:migrations](https://github.com/percolatestudio/meteor-migrations) - Simple migration system for Meteor :star:235
* [demeteorizer](https://github.com/onmodulus/demeteorizer) - Converts a Meteor app into a "standard" Node.js application :star:721
* [When a Meteor finally hits production](https://medium.com/@davidyahalomi/when-a-meteor-finally-hits-production-6c37b81f795b) - Blog post about deploying Meteor apps


## Routers

*Routers for Blaze*

* [iron:router](https://github.com/iron-meteor/iron-router) - A client and server side router designed specifically for Meteor. :star:2025
* [kadira:flow-router](https://github.com/kadirahq/flow-router) - Client Side Router for Meteor. :star:1109
* [ostrio:flow-router-extra](https://github.com/VeliovGroup/flow-router) - Carefully extended `flow-router` package. Up-to-date version with support of latest Meteor's releases. :star:162
* [meteorhacks:picker](https://github.com/meteorhacks/picker) - Server Side Router for Meteor. :star:176
* [msavin:parrot](https://github.com/msavin/Parrot) - Web router specially designed for building SPAs using Meteor :star:76

## Offline

*Tools for Meteor offline support*

* [ground:db](https://github.com/GroundMeteor/db) - GroundDB is a thin layer providing Meteor offline database and methods. :star:561
* [npdev:collections](https://github.com/CaptainN/npdev-collections) - An easy way to create offline collections with SSR for Meteor :star:11

## Testing

*Testing tools*

* [Meteor Testing Manual](http://www.meteortesting.com/)
* [mike:mocha](https://github.com/mad-eye/meteor-mocha-web/) – Run mocha tests within the Meteor framework.
* [hubroedu:mocha](https://github.com/hubroedu/meteor-mocha/) - Decaffed cultofcoders:mocha fork.  :star:2
* [xolvio:chimp](https://github.com/xolvio/chimp) - Testing so easy, a primate could do it! Supports mocha, Cucumber, jasmine, and chai. :star:779
* [velocity:html-reporter](https://github.com/meteor-velocity/html-reporter) - HTML reporter for Meteor velocity testing framework. :star:24
* [Gagarin](https://github.com/anticoders/gagarin) - Another testing framework for your meteor apps. :star:154

## SEO

*Search Engine Optimization tools*

* [ostrio:spiderable-middleware](https://github.com/VeliovGroup/spiderable-middleware/) - Prerendering (*a.k.a. Spiderable*) with support of ES6 (ECMAScript2015) - Meteor app crawled perfectly by search engines. :star:13

## Files

*Handling files in Meteor*

* [ostrio:files](https://github.com/VeliovGroup/Meteor-Files) - Upload files via DDP, HTTP and WebRTC/DC. To Meteor server FS, AWS, GridFS, DropBox or Google Drive. Fast, secure and robust. :star:946
* [netanelgilad:excel](https://github.com/netanelgilad/meteor-excel) - Parsing and generating excel files (xlsx, xls). :star:55

## Search, sort and paginate

*Search, sort and paginate related tools*

* [tmeasday:publish-counts](https://github.com/percolatestudio/publish-counts) - Publish the count of a cursor, in real time. :star:200
* [percolate:find-from-publication](https://github.com/versolearning/find-from-publication) - Enable finding all documents that have been published by a given publication. :star:42
* [meteorhacks:search-source](https://github.com/meteorhacks/search-source) - Reactive Data Source for Search :star:148
* [matteodem:easy-search](https://github.com/matteodem/meteor-easy-search) - Easy-to-use search with Blaze Components (+ Elastic Search Support) :star:429
* [alethes:pages](https://github.com/alethes/meteor-pages) - Out of the box Meteor pagination :star:408
* [Discover Meteor Blog about pagination](https://www.discovermeteor.com/blog/pagination-problems-meteor/)

## Mobile

*Mobile Development*

* [meteoric:ionic](https://github.com/meteoric/meteor-ionic) - Ionic components for Meteor. :star:1559
* [driftyco:ionic](https://github.com/driftyco/ionic) - Official Ionic support for Meteor. :star:39170
* [raix:push](https://github.com/raix/push) - Push notifications for cordova (ios, android) browser (Chrome, Safari, Firefox). :star:518
* [martijnwalraven:meteor-ios](https://github.com/martijnwalraven/meteor-ios) - Integrates native iOS apps with the Meteor platform through DDP. :star:754
* [delight-im/Android-DDP](https://github.com/delight-im/Android-DDP) - DDP for clients on Android. :star:267
* [okland:accounts-phone](https://github.com/okland/accounts-phone) - A login service based on mobile phone number for Meteor. :star:113
* [okland:camera-ui](https://github.com/okland/camera-ui) - Meteor package for taking photos with user interface, one function call on desktop and mobile. Allows to choose between camera to photoLibrary on mobile. :star:27
* [percolatestudio/cordova-plugin-safe-reload](https://github.com/percolatestudio/cordova-plugin-safe-reload) - Cordova plugin to watch and recover after a broken Meteor Hot Code Push. :star:15

## Data Visualization

*Data Visualization in Meteor: charts, maps, tables, etc.*

* [AnyChart-Meteor](https://github.com/AnyChart/AnyChart-Meteor) - This package provides a simple way to use AnyChart JavaScript charting component in Meteor. :star:18
* [aldeed:tabular](https://github.com/aldeed/meteor-tabular) - Reactive datatables for large or small datasets. :star:359
* [luixal:blaze-paginated-custom-list](https://github.com/luixal/meteor-blaze-paginated-custom-list) - Reactive and paginated item list.
* [luixal:meteor-apexcharts](https://github.com/luixal/meteor-apexcharts) - Reactive ApexCharts library packaged for Meteor. :star:1

## Analytics

*Analytics*

* [okgrow:analytics](https://github.com/okgrow/analytics/) - Google Analytics, Mixpanel, KISSmetrics (and more) integration for meteor. :star:211

## Cron Jobs

*Cron Jobs in Meteor*

* [msavin:sjobs](https://github.com/msavin/stevejobs/) - A Meteor-first jobs queue / task scheduler :star:173
* [percolate:synced-cron](https://github.com/percolatestudio/meteor-synced-cron) - Cron system for Meteor. It supports syncronizing jobs between multiple processes. :star:494
* [vsivsi:job-collection](https://github.com/vsivsi/meteor-job-collection/) - A persistent and reactive job queue for Meteor, supporting distributed workers that can run anywhere. :star:387
* [ostrio:cron-jobs](https://github.com/VeliovGroup/Meteor-CRON-jobs) - Package with similar API to native `setTimeout` and `setInterval` methods, but synced between all running Meteor (NodeJS) instances. :star:17

## Debugging Tools

*Debugging Tools*

* [msavin:mongol](https://github.com/msavin/Mongol/) - Visual Editing Tool for Meteor for MongoDB Collections. :star:844
* [msavin:jetsetter](https://github.com/msavin/JetSetter) - Visual Get/Set Tool for Meteor Session Variables. :star:187
* [meteorhacks:kadira-debug](https://github.com/kadirahq/meteor-debug) - Full Stack Debugging Solution for Meteor. :star:156
* [babrahams:constellation](https://github.com/JackAdams/constellation-distro/) - An extensible dev console for Meteor. :star:34
* [Meteor DDP Monitor](https://github.com/thebakeryio/meteor-ddp-monitor) - Chrome Dev tools extension for monitoring Meteor DDP traffic :star:249

## Package Managers

*Using package managers in Meteor*

* [meteorhacks:npm](https://github.com/meteorhacks/npm/) - Use Npm Modules with Your Meteor App. :star:520
* [cosmos:browserify](https://github.com/elidoran/cosmos-browserify) - Browserify npm modules for client side in Meteor packages. :star:79

## Scaffolding

*Scaffolding*

* [Meteor Kitchen](http://www.meteorkitchen.com/) - Code generator for Meteor
* [iron-cli](https://github.com/iron-meteor/iron-cli) - A scaffolding command line tool for Meteor applications :star:645
* [Differential - meteor-boilerplate](https://github.com/Differential/meteor-boilerplate) :star:900
* [meteoris2](https://github.com/radiegtya/meteoris2) :star:249
* [Base](https://github.com/themeteorchef/base) :star:660

## Tooling

* [ESLint-plugin-Meteor](https://github.com/dferber90/eslint-plugin-meteor/) - ESLint plugin for Meteor :star:104

## Boilerplate

* [matteodem - meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) :star:853
* [React with Webpack + Meteor as a backend](http://julian.io/react-with-webpack-meteor-as-a-backend/)

## Open source apps

* [Nosqlclient](https://github.com/nosqlclient/nosqlclient) - MongoDB management tool :star:2982
* [VulcanJS](https://github.com/VulcanJS/Vulcan) - A toolkit to quickly build apps with React, GraphQL & Meteor :star:7632
* [Microscope](https://github.com/DiscoverMeteor/Microscope) - The Discover Meteor book's example app :star:916
* [Wekan](https://github.com/wekan/wekan) - Open source Trello-like kanban :star:14997
* [Reaction Commerce](https://github.com/reactioncommerce/reaction) - Open source Commerce platform developed with Meteor :star:9311
* [Crowducate Platform](https://github.com/Crowducate/crowducate-platform) - Open source education platform Powered by meteor :star:190
* [Orion CMS](http://orionjs.org/)
* [Rocket.Chat](https://rocket.chat/)

## Front End Frameworks

*Alternative Front End Frameworks to Blaze*

* [React](http://react-in-meteor.readthedocs.org/en/latest/) - Working with React and Meteor
* [Vue](https://github.com/Akryum/meteor-vue-component) - Working with Vue and Meteor (plus single-file components & apollo support) :star:850
* [Svelte](https://github.com/meteor-svelte/meteor-svelte) - Build cybernetically enhanced web apps with Meteor and Svelte :star:46
* [Angular 2](https://github.com/Urigo/angular2-meteor) - Working with Angular 2 and Meteor :star:313
* [Angular](https://github.com/Urigo/angular-meteor) - Working with Angular and Meteor :star:2371
* [Famo.us](https://github.com/gadicc/meteor-famous-views/) - Famo.us and Meteor :star:342
* [frozeman:build-client](https://github.com/frozeman/meteor-build-client) - A tool to bundle the client part of a Meteor app. :star:253
* [Asteroid](https://github.com/mondora/asteroid) - An alternative client for a Meteor backend :star:737
* [ddp.js](https://github.com/mondora/ddp.js) - Isomorphic JavaScript DDP client :star:207

## Alternative Databases

*Alternative Databases for MongoDB*

* [meteor-pg](https://github.com/Richie765/meteor-pg) - New and improved PostgreSQL support for Meteor :star:21
* [ostrio:neo4jdriver](https://github.com/VeliovGroup/ostrio-neo4jdriver/) - Neo4j Driver for Meteor, with support of GrapheneDB :star:54
* [numtel:pg](https://github.com/numtel/meteor-pg) - Reactive PostgreSQL for Meteor :star:299
* [numtel:mysql](https://github.com/numtel/meteor-mysql) - Reactive MySQL for Meteor :star:350
* [simple:rethink](https://github.com/Slava/meteor-rethinkdb) - RethinkDB integration for Meteor :star:310

# Resources

*Where to discover new Meteor things*

## Books

* [Meteor Explained](https://gumroad.com/l/meteor-explained)
* [Meteor Tips](http://meteortips.com/)
* [Meteor Cookbook](https://github.com/awatson1978/meteor-cookbook) :star:1667
* [Secure Meteor](https://www.securemeteor.com/)

## Courses

* [EventedMind](https://www.eventedmind.com/)
* [Udemy — Meteor: Build a real-time web app using only JavaScript](https://www.udemy.com/meteor-course/)
* [Udemy - A Beginner's Guide to the Meteor JavaScript Framework](https://www.udemy.com/meteorjs/)
* [tuts+ - Single Page Web Apps with Meteor](http://code.tutsplus.com/courses/single-page-web-apps-with-meteor)
* [DevFreeCasts.org](http://devfreecasts.org/meteor/)
* [MeteorTuts](http://meteor-tuts.com/)

## Tutorials

* [Building a CMS-powered blog in Meteor](https://buttercms.com/blog/meteor-cms-blog-tutorial)
* [scotch.io - Building a Slack Clone in Meteor](https://scotch.io/tutorials/building-a-slack-clone-in-meteor-js-getting-started)
* [Rocket-Chat Slack Clone](https://rocket.chat/)
* [Meteor Learning](https://github.com/ericdouglas/Meteor-Learning) - List of resources to learn :star:1623
* [Phusion Passenger: Meteor tutorial](https://github.com/phusion/passenger/wiki/Phusion-Passenger:-Meteor-tutorial) :star:4472

## Blogs

* [Official Meteor blog](http://blog.meteor.com)
* [The Meteor podcast](http://podcast.crater.io)
* [Blog about Optimistic UIs With Meteor Latency Compensation](http://info.meteor.com/blog/optimistic-ui-with-meteor-latency-compensation)

## Websites

* [Official website](https://www.meteor.com/)
* [Official Documentation](http://docs.meteor.com/)
* [Official Guide](http://guide.meteor.com/)
* [Atmosphere](https://atmospherejs.com/) - The catalog of Meteor packages, resources and tools.
* [BulletProof Meteor](https://bulletproofmeteor.com/) - Online course for Meteor performance in production, by Arunoda Susiripala
* [Meteorpedia](http://www.meteorpedia.com) ([infrequently](http://www.meteorpedia.com/special/RecentChanges/) updated)
* [DiscoverMeteor Encyclopedia](https://www.discovermeteor.com/encyclopedia)
* [Roadmap](https://trello.com/b/hjBDflxp/meteor-roadmap)
* [Meetups](http://meteor.meetup.com/)
* [Reddit](https://www.reddit.com/r/meteor)
* [YouTube](https://www.youtube.com/channel/UC3fBiJrFFMhKlsWM46AsAYw) videos from meetups around the world
* [Unofficial Meteor FAQ](https://github.com/oortcloud/unofficial-meteor-faq) :star:977
* [The Meteor Chef](https://themeteorchef.com)

### Q&A

* [Stack Overflow](http://stackoverflow.com/questions/tagged/meteor?sort=newest&pagesize=15)
* [Meteor forums](https://forums.meteor.com/)
* [Gitter IM channel](https://gitter.im/meteor/meteor)
* [The Meteor Chef Slack channel](https://themeteorchef.slack.com)
* IRC - #meteor on freenode


## Weekly

* [Meteor-Blog](http://info.meteor.com/blog)
* [Meteor Weekly](https://goodbits.io)
* [This Week In Meteor](https://goodbits.io)

## Twitter

* [Official Meteor](https://twitter.com/meteorjs)

## Job Boards

* [We Work Meteor](https://www.weworkmeteor.com/)

## Built With Meteor

*Commercial Grade Applications Built With Meteor*

* [Qualia](https://www.qualia.com/) - Real Estate Startup
* [Code Signal](https://codesignal.com/) - Skills-based assessment platform
 

# [Contributing](https://github.com/urigo/awesome-meteor/blob/master/CONTRIBUTING.md)

Your contributions are always welcome!

Thank you @gillesfabio for creating this repo!


# Information comes from [friendsofcake/awesome-cakephp](https://github.com/friendsofcake/awesome-cakephp)
# Awesome CakePHP [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of amazingly awesome **CakePHP 3.x** plugins, resources and shiny things.

If you are looking for CakePHP 2.x resources please visit:
- the [CakePHP 2.x version](https://github.com/FriendsOfCake/awesome-cakephp/tree/cake2) of this awesome list
- this wiki with a [list of not-yet upgraded plugins](https://github.com/FriendsOfCake/awesome-cakephp/wiki#plugins-not-yet-upgraded-from-2x-to-3x)

Additional lists you might find useful:
- [CakePHP Plugins](https://plugins.cakephp.org)
- [Awesome PHP](https://github.com/ziadoz/awesome-php) :star:19046
- [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness) :star:21630

> For those wondering; this list differs from plugins.cakephp.org by supporting
> plugin subparts (instead of only the whole plugin/repo), more granular
> grouping and the primary focus on task specific functionality.

## Table of Contents

- [Plugins](#plugins)
	- [APM](#apm)
	- [Asset Management](#asset-management)
	- [Auditing / Logging](#auditing--logging)
	- [Authentication and Authorization](#authentication-and-authorization)
	- [Caching](#caching)
	- [Code Analysis](#code-analysis)
	- [Debugging](#debugging)
	- [Dependency Injection](#dependency-injection)
	- [E-commerce](#e-commerce)
	- [Email](#email)
	- [Environment](#environment)
	- [Files](#files)
	- [Filtering and Validation](#filtering-and-validation)
	- [Geolocation](#geolocation)
	- [I18n](#i18n)
	- [Imagery](#imagery)
	- [Libs](#libs)
	- [Markup](#markup)
	- [Migration](#migration)
	- [Miscellaneous](#miscellaneous)
	- [Navigation](#navigation)
	- [NoSQL](#nosql)
	- [Notifications](#notifications)
	- [ORM and Datamapping](#orm-and-datamapping)
	- [PDF](#pdf)
	- [Queue](#queue)
	- [REST and API](#rest-and-api)
	- [Search](#search)
	- [Security](#security)
	- [SEO](#seo)
	- [Skeleton](#skeleton)
	- [Social](#social)
	- [Templating](#templating)
	- [Testing](#testing)
	- [Third Party APIs](#third-party-apis)
- [Software](#software)
	- [Development Environment](#development-environment)
- [Web Applications](#web-applications)
	- [CMS and applications built on CakePHP](#cms-and-applications-built-on-cakephp)
	- [Demo](#demo)
- [Resources](#resources)
	- [Help](#help)
	- [CakePHP Websites](#cakephp-websites)
	- [CakePHP Books and Articles](#cakephp-books-and-articles)
	- [CakePHP Videos](#cakephp-videos)
	- [CakePHP Tutorials](#cakephp-tutorials)
	- [CakePHP Reading and Listening](#cakephp-reading-and-listening)
	- [CakePHP Internals Reading](#cakephp-internals-reading)
- [Conferences](#conferences)
- [Contributing](#contributing)

# Plugins

## APM
*Plugins for Application Performance Monitoring.*

- [NewRelic plugin](https://github.com/jippi/cakephp-newrelic/tree/cake3) - A complete plugin that enables full New Relic integration for a CakePHP application, including CLI naming, exceptions sending, custom timings, etc. It does not depend on New Relic agent.

- [Brunitto/NewRelic plugin](https://github.com/brunitto/cakephp-new-relic) - A simple plugin that enables just name transaction and browser timing for a CakePHP 3 application using the New Relic PHP agent. :star:8

## Asset Management
*Tools for managing, compressing and minifying website assets.*

- [AssetCompress plugin](https://github.com/markstory/asset_compress) - A complete asset manager for CakePHP. :star:364
- [Assets plugin](https://github.com/mirko-pagliai/cakephp-assets) - Dynamic and "on the fly" asset files.
- [Less plugin](https://github.com/elboletaire/less-cake-plugin) - Less parser plugin for CakePHP. :star:17
- [MinifyHtml plugin](https://github.com/WyriHaximus/MinifyHtml) - Compress HTML output. :star:15

## Auditing / Logging
*Plugins for auditing and logging.*

- [AuditStash plugin](https://github.com/lorenzo/audit-stash) - Flexible and rock solid audit log tracking. :star:52
- [DatabaseLog plugin](https://github.com/dereuromark/CakePHP-DatabaseLog) - Simple and stand-alone logging to database instead of files. :star:26
- [Muffin/Footprint plugin](https://github.com/UseMuffin/Footprint) - Plugin to allow passing currently logged in user to model layer. :star:57
- [Version plugin](https://github.com/josegonzalez/cakephp-version) - A plugin that facilitates versioned database entities. :star:45

## Authentication and Authorization
*Plugins and libraries for implementing authentication and authorization.*

- [Acl plugin](https://github.com/cakephp/acl/) - Managing ACL as database approach.
- [ADmad/HybridAuth plugin](https://github.com/ADmad/CakePHP-HybridAuth) - A plugin which allows using the [HybridAuth](https://github.com/hybridauth/hybridauth) social sign on library with CakePHP. :star:78
- [ADmad/JwtAuth plugin](https://github.com/ADmad/cakephp-jwt-auth) - A plugin for authenticating using JSON Web Tokens. :star:113
- [CakeDC/NavAuth plugin](https://github.com/CakeDC/cakephp-nav-auth) - A plugin for authenticating against Navision® service using SOAP or OData services. It includes NTLM authentication and more. :star:9
- [CakeDC/Users plugin](https://github.com/CakeDC/users) - Complete user management (admin panel, remember me, etc), Social login (FB, Twitter, LinkedIn, Google, Instagram), RBAC, API and more. :star:437
- [CookieAuth plugin](https://github.com/Xety/Cake3-CookieAuth) - A simple Cake 3 plugin to automatically authenticate users with Cookies. :star:18
- [HierAuth plugin](https://github.com/btaens/cakephp-hier-auth) - A CakePHP plugin for hierarchical, role based, simple authorization. :star:6
- [Muffin/OAuth2 plugin](https://github.com/usemuffin/oauth2) - OAuth2 authentication using the [`league/oauth2-client`](https://github.com/thephpleague/oauth2-client). :star:24
- [Muffin/Tokenize plugin](https://github.com/UseMuffin/Tokenize) - Event driven behavior for easily generating single-use security tokens. :star:8
- [MultiTenant plugin](https://github.com/pronique/multitenant) - Easily build SaaS enabled web applications. :star:29
- [TinyAuth plugin](https://github.com/dereuromark/cakephp-tinyauth) - Authentication and role based (single/multi) authorization as very light-weight approach. :star:82
- [Tools:Passwordable](https://github.com/dereuromark/cakephp-tools) - Containing [Passwordable behavior](https://github.com/dereuromark/cakephp-tools/blob/master/docs/Behavior/Passwordable.md) for a DRY approach on password hashing. :star:291
- [TwoFactorAuth plugin](https://github.com/andrej-griniuk/cakephp-two-factor-auth) - Allows two factor authentication using Google Authenticator or similar app to generate one-time codes. Based on [RobThree/TwoFactorAuth](https://github.com/RobThree/TwoFactorAuth) library. :star:22
- [UserPermissions plugin](https://github.com/AlessandroMinoccheri/UserPermissions) -  Allow groups of users or single users to view a specific page. :star:17

## Caching
*Plugins for caching data.*

- [Cache plugin](https://github.com/dereuromark/cakephp-cache) - For caching views (HTML, CSV, JSON, XML, ...) as static cache files. :star:17

## Code Analysis
*Plugins for analysing, parsing and manipulation codebases.*

- [IdeHelper plugin](https://github.com/dereuromark/cakephp-ide-helper) - Helps to make IDE support better by adding annotations to your existing code similar to what baking does to new code. :star:81
- [TestHelper plugin](https://github.com/dereuromark/cakephp-test-helper) - Provides testing enhancements and TDD support as browser backend. :star:2

## Debugging
*Plugins for debugging.*

- [Airbrake plugin](https://github.com/chrisShick/AirbrakeCake) A plugin to seamlessly integrate Airbrake with CakePHP for errors and exceptions.
- [DebugKit plugin](https://github.com/cakephp/debug_kit) - The de-facto standard for debugging. :star:856
- [ErrorEmail plugin](https://github.com/ebrigham1/cakephp-error-email) - A plugin to email exception/error information to your dev team. :star:9
- [Execution order](https://github.com/dereuromark/executionorder) - A demo app to display the execution order of files, methods and callbacks. :star:14
- [Psa/FixtureCheck plugin](https://github.com/World-Architects/cakephp-fixture-check) - A plugin to help detect mismatches in live DB and fixtures in order to make fixture based tests more reliable and deployments safer. :star:2
- [Sentry plugin](https://github.com/Connehito/cake-sentry) A plugin to seamlessly integrate Sentry with CakePHP for errors and exceptions.
- [Setup plugin](https://github.com/dereuromark/cakephp-setup) - A lightweight setup plugin containing debugging and maintenance tools. :star:30
- [Whoops plugin](https://github.com/dereuromark/cakephp-whoops) - PHP errors and exceptions for cool kids with [filp/whoops](https://github.com/filp/whoops). :star:7

## Dependency Injection
*Plugins that implement the dependency injection design pattern.*

- [PimpleDi plugin](https://github.com/rochamarcelo/cake-pimple-di) Allows dependency injection based on Pimple library.
- [PipingBag plugin](https://github.com/lorenzo/piping-bag) - Dependency injection container plugin that adds the ability to configure object instances and their dependencies before they are used, and to store them into a container class for easy access. :star:33

## E-commerce
*Plugins and applications for taking payments and building online e-commerce stores.*

- [PaypalWPP plugin](https://github.com/cpierce/paypal-wpp) - A package for communicating with Paypal Web Payments Pro for transactions and information about your account. :star:2

## Email
*Plugins for sending and parsing email.*

- [EmailQueue plugin](https://github.com/lorenzo/cakephp-email-queue) - Email queue plugin with a preview and sender shell. :star:43
- [Gourmet/Email plugin](https://github.com/gourmet/email) - Email helper, layout and more. :star:17
- [Mailgun plugin](https://github.com/narendravaghela/cakephp-mailgun) - Email transport plugin for sending email via Mailgun. :star:13
- [SparkPost plugin](https://github.com/syntaxera/cakephp-sparkpost-plugin) - Email transport plugin for sending email via the SparkPost API. :star:11

## Environment
*Plugins for environment.*

- [Environments plugin](https://github.com/josegonzalez/cakephp-environments) - Plugin to handle environments. :star:47
- [Gourmet/Aroma plugin](https://github.com/gourmet/aroma) - Database based configuration. :star:11
- [Settings plugin](https://github.com/cakemanager/cakephp-settings) - A plugin to manage your settings via your database. :star:22
- [Setup plugin](https://github.com/dereuromark/cakephp-setup) - Plugin to handle very basic environments. :star:30

## Files
*Plugins for file manipulation.*

- [FileStorage plugin](https://github.com/burzum/cakephp-file-storage) - Abstract file storage and upload plugin. :star:185
- [FlyPie plugin](https://github.com/WyriHaximus/FlyPie) - Abstract filesystem access using Flysystem. :star:29
- [FriendsOfCake/Upload plugin](https://github.com/FriendsOfCake/cakephp-upload) - A customisable plugin that uses [Flysystem](http://flysystem.thephpleague.com/) to write to multiple backends (Dropbox, FTP, S3, Local, etc.). :star:523
- [Image plugin](https://github.com/josbeir/image) - Image behavior that works much like Cake's built in TranslateBehavior. :star:19
- [Proffer plugin](https://github.com/davidyell/CakePHP3-Proffer) - A customisable upload plugin with thumbnail generation. :star:109
- [Upload plugin](https://github.com/Xety/Cake3-Upload) - A little plugin to upload file. :star:27

## Filtering and Validation
*Plugins for filtering and validating data.*

- [Gourmet/Filters plugin](https://github.com/gourmet/filters) - Extra dispatcher filters (maintenance, robots, ip, etc). :star:9
- [Gourmet/Validation plugin](https://github.com/gourmet/validation) - Extra validation providers (Respect, IsoCodes, etc.) and rules. :star:5
- [HtmlPurifier plugin](https://github.com/burzum/cakephp-html-purifier) - Purifier Plugin that features a trait, behavior and helper to allow you to get sanitization and filtering where you need it. You can configure multiple sets of filter rules as well. :star:37
- [HtmlPurifier plugin](https://github.com/chrisShick/CakePHP3-HtmlPurifier) - Purifier Plugin Behavior that cleanses data before it is marshaled into the entity and/or before saving. :star:11

## Geolocation
*Plugins for geocoding addresses and working with latitudes and longitudes.*

- [Geo plugin](https://github.com/dereuromark/cakephp-geo) - Containing [Geocoder behavior](http://www.dereuromark.de/2012/06/12/geocoding-with-cakephp/) and [GoogleMaps helper](http://www.dereuromark.de/2010/12/21/googlemapsv3-cakephp-helper/). :star:33

## I18n
*Plugins for I18n (Internationalization) and L10n (Localization).*

- [ADmad/I18n plugin](https://github.com/ADmad/cakephp-i18n) - A plugin with I18n related tools. :star:26
- [Localized plugin](https://github.com/cakephp/localized) - Localized validation and ready-to-use translation PO files. :star:205
- [ShadowTranslate plugin](https://github.com/AD7six/cakephp-shadow-translate) - A plugin with shadow table based replacement for core's Translate behavior. :star:39
- [Transifex plugin](https://github.com/dereuromark/cakephp-transifex) - Managing i18n PO files and translations via Transifex API. :star:14
- [Translate plugin](https://github.com/dereuromark/cakephp-translate) - Manage translations of your static content the easy way via web backend, incl. import from POT files, auto-suggest and auto-translate via API. :star:12
- [Translation plugin](https://github.com/ava007/wnk_translation) - Extract pot files, translate string (manually, google, community), export translations to pot files. :star:4

## Imagery
*Plugins for manipulating images.*

- [ADmad/Glide plugin](https://github.com/ADmad/cakephp-glide) - A plugin for using [Glide](http://glide.thephpleague.com/) image manipulation library. :star:30
- [HtmlToImageView plugin](https://github.com/andrej-griniuk/cakephp-html-to-image-view) - Render HTML view as image (jpg or png) using [wkhtmltoimage](https://wkhtmltopdf.org). :star:1
- [Imagine plugin](https://github.com/burzum/cakephp-imagine-plugin) - An image manipulation plugin and wrapper around [Imagine](https://github.com/avalanche123/Imagine). :star:134
- [Thumber plugin](https://github.com/mirko-pagliai/cakephp-thumber) - A plugin to create thumbnails using [intervention/image](https://github.com/Intervention/image). :star:4

## Libs
*Useful libraries or tools that don't fit in any of the other categories.*

- [Aura.Intl](https://github.com/auraphp/Aura.Intl) - A powerful I18n library - used in CakePHP 3.x core. :star:74
- [Capcake](https://github.com/jadb/capcake) - Deploy CakePHP applications using Capistrano. :star:117
- [Chronos](https://github.com/cakephp/chronos) - A simple standalone DateTime API extension (successor of Carbon). :star:606
- [Composer Installers](https://github.com/composer/installers) - A multi framework Composer library installer. :star:927
- [Composer](https://getcomposer.org/)/[Packagist](https://packagist.org/) - A package and dependency manager.
- [Graphviz](https://github.com/alexandresalome/graphviz) - A Graphviz library. :star:54
- [Jenkins](http://jenkins-ci.org/) - The free alternative for private (GitHub) repos.
- [Rocketeer](https://github.com/rocketeers/rocketeer) - PHP task runner and deployment package. :star:2616
- [Travis CI](https://travis-ci.org/) - A continuous integration platform - de-facto standard for testing (GitHub) repos.
- [YamlRoute](https://github.com/makallio85/yaml-route) - Configure routes with simple YAML files. :star:5

## Markup
*Plugins for working with markup.*

- [Gourmet/CommonMark plugin](https://github.com/gourmet/common-mark) - Adds [CommonMark](http://commonmark.org/) Markdown parsing. :star:7
- [Markup plugin](https://github.com/dereuromark/cakephp-markup) - Allows to use PHP or JS based syntax highlighting. :star:1

## Migration
*Plugins and resources around migration and upgrading.*

- [Migrations plugin](https://github.com/cakephp/migrations) - (DB) Migration plugin. :star:86
- [Upgrade app](https://github.com/cakephp/upgrade) - Official upgrade app for 2.x=>3.x. :star:74
- [Upgrade app (extended)](https://github.com/dereuromark/upgrade) - An extended upgrade app for 2.x=>3.x and between 3.x. :star:12
- [Upgrade/Migration Guide](http://book.cakephp.org/3.0/en/appendices.html) - Official migration guide.

## Miscellaneous
*Misc plugins and libraries.*

- [ActionsClass plugin](https://github.com/HavokInspiration/cakephp-actions-class) - Gives you the ability to manage your Controller actions as single classes. :star:8
- [Ajax plugin](https://github.com/dereuromark/cakephp-ajax) - A plugin to ease handling AJAX requests. :star:36
- [CakeAdmin plugin](https://github.com/cakemanager/cakephp-cakeadmin) - A non-stable user management plugin with a built-in admin area. :star:27
- [CakeDC/Enum](https://github.com/CakeDC/enum) - A plugin to add enumeration list support to your app. :star:21
- [CakeMiddlewares](https://github.com/chrisShick/CakeMiddlewares) - A collection of Cakephp Middlewares. :star:2
- [Comments plugin](https://github.com/Kareylo/CakePHP-Comments) - A fully customizable Comments plugin. :star:4
- [CurrencyConverter plugin](https://github.com/AlessandroMinoccheri/cakephp-currency-converter) - A plugin to convert currency into another one. :star:5
- [Dashboard plugin](https://github.com/gourmet/dashboard) - Build beautiful dashboards for your cakes. :star:17
- [DatabaseBackup plugin](https://github.com/mirko-pagliai/cakephp-database-backup) - A plugin to export, import and manage database backups. :star:7
- [Feedback plugin](https://github.com/dereuromark/cakephp-feedback) - Allow visitors to send quick and easy feedback incl. a screenshot via sidebar form. :star:2
- [Flash plugin](https://github.com/dereuromark/cakephp-flash) - More powerful flash messages for your application. :star:7
- [Hashid plugin](https://github.com/dereuromark/cakephp-hashid) - Allows to use hashids to not expose the database ids to the user. :star:34
- [Interval plugin](https://github.com/LubosRemplik/CakePHP-Interval) - Converts seconds to human readable string (string to seconds), uses business hours (1 week = 5 days, 1 day = 8 hours).
- [Robotusers/Tactician plugin](https://github.com/robotusers/cakephp-tactician) - Tools for Tactician command bus integration. :star:6
- [Setup:Maintenance](https://github.com/dereuromark/cakephp-setup/blob/master/docs/Maintenance/Maintenance.md) - Maintenance shell to go into maintenance mode for all requests with optional IP whitelisting.
- [Shim plugin](https://github.com/dereuromark/cakephp-shim) - A plugin containing useful shims and improvements as basis for your application. :star:31
- [TokenVerify plugin](https://github.com/mosaxiv/cakephp-token-verify) - Easily issue tokens that can be used for mail authentication. :star:7
- [Tools plugin](https://github.com/dereuromark/cakephp-tools) - Containing lots of useful libs, helpers, behaviors, components, shells and more. :star:291
- [Travis](https://github.com/FriendsOfCake/travis) - Easy travis setup for CakePHP plugins. :star:38
- [UserTools plugin](https://github.com/burzum/cakephp-user-tools) - User tools for login, registration, password reset and more. Works out of the box CRUD like and is highly configurable. :star:44
- [Utils plugin](https://github.com/cakemanager/cakephp-utils) - Containing useful components (Authorizer, Menu) and behaviors (WhoDidIt, Uploadable, Metas, Stateable). :star:24
- [Wrench plugin](https://github.com/HavokInspiration/wrench) - Maintenance Mode plugin. Easily extensible and customizable. :star:21
- [Yaml plugin](https://github.com/guemidiborhane/Cake-Yaml) - For using YAML config files instead of PHP arrays. :star:9

## Navigation
*Tools for building navigation structures.*

- [Icings/Menu plugin](https://github.com/icings/menu) - A [KnpMenu](https://github.com/KnpLabs/KnpMenu) seasoned menu plugin for CakePHP. :star:4

## NoSQL
*Plugins for working with "NoSQL" backends.*

- [Monga plugin](https://github.com/lewestopher/cakephp-monga) - Provides access to MongoDB datasource using [`thephpleague/monga`](https://github.com/thephpleague/monga). :star:13

## Notifications
*Plugins for working with notification software.*

- [ker0x/CakeGcm plugin](https://github.com/ker0x/CakeGCM) - A plugin to send downstream messages to an Android or iOS device through Google Cloud Messaging. :star:8
- [Notifier plugin](https://github.com/cakemanager/cakephp-notifier) - A plugin that makes creating and reading notifications easy. :star:52
- [ker0x/Push plugin](https://github.com/ker0x/cakephp-push) - A plugin to send push notifications through services like Firebase Cloud Messaging. :star:8

## ORM and Datamapping
*Plugins that implement object-relational mapping or data-mapping techniques.*

- [ADmad/Sequence plugin](https://github.com/ADmad/cakephp-sequence) - Behavior for maintaining ordered list of records. :star:27
- [Duplicatable plugin](https://github.com/riesenia/cakephp-duplicatable) - Behavior for duplicating entities including related data. :star:29
- [JeremyHarris/LazyLoad plugin](https://github.com/jeremyharris/cakephp-lazyload) - An association lazy loader for entities. :star:49
- [Money plugin](https://github.com/gourmet/money) - Money data type for CakePHP entities using [sebastianbergmann/money](https://github.com/sebastianbergmann/money). :star:6
- [Muffin/Orderly plugin](https://github.com/usemuffin/orderly) - Allows setting default order for your tables. :star:18
- [Muffin/Trash plugin](https://github.com/usemuffin/trash) - Soft-delete behavior for CakePHP. :star:60
- [PersistRelatedData plugin](https://github.com/riesenia/persist-related-data) - Behavior for persisting selected fields of related models. :star:10
- [Robotusers/Excel plugin](https://github.com/robotusers/cakephp-excel) - ORM wrapper for PHPExcel. :star:12
- [Robotusers/TableInheritance plugin](https://github.com/robotusers/cakephp-table-inheritance) - Singe Table Inheritance (STI) plugin. :star:3
- [RowLocker plugin](https://github.com/lorenzo/row-locker) - Exclusive locks for rows in your tables. :star:20
- [Serializeable Data Types plugin](https://github.com/burzum/cakephp-serialize-data-types) - Serialize DB content as JSON or using phps serializing functions. :star:2
- [Webservices ORM plugin](https://github.com/usemuffin/webservice) - An ORM like interface for webservices. :star:63

## PDF
*Plugins and software for working with PDF files.*

- [CakePdf plugin](https://github.com/FriendsOfCake/CakePdf) - A plugin around PDF generation. :star:314

## Queue
*Plugins for working with event and task queues.*

- [CakeResque plugin](https://github.com/wa0x6e/Cake-Resque) - A plugin for Resque, a library for creating background jobs. :star:162
- [CakeQueuesadilla plugin](https://github.com/josegonzalez/cakephp-queuesadilla) - A plugin that provides queueing integration with a variety of backends (BeanstalkD, MySQL, Redis, etc.). :star:17
- [Gearman plugin](https://github.com/cvo-technologies/cakephp-gearman) - A plugin for offloading CakePHP tasks to a Gearman Job Server. :star:11
- [Queue plugin](https://github.com/dereuromark/cakephp-queue) - A minimal and dependency-free queue solution. :star:181

## REST and API
*Plugins and web tools for developing REST-ful APIs.*

- [Alt3/Swagger plugin](https://github.com/alt3/cakephp-swagger) - Swagger 2.0 documentation for your CakePHP APIs using swagger-php and swagger-ui. :star:37
- [Alt3/ValidationExposer plugin](https://github.com/alt3/cakephp-validation-exposer) - Easily expose your application's validation rules. :star:9
- [ApiPagination plugin](https://github.com/bcrowe/cakephp-api-pagination) - Injects pagination information from CakePHP's Paginator into serialized JsonView and XmlView responses. :star:26
- [CakeDC/Api plugin](https://github.com/CakeDC/cakephp-api) - All-in-one solution to provide a complete API. It includes versioning, renderers, CRUD, authentication, extensions (paginate, filter, HATEOAS), and much more. :star:34
- [Cors plugin](https://github.com/ozee31/cakephp-cors) - Activate CORS with Middleware. :star:21
- [Cors plugin](https://github.com/snelg/cakephp-cors) - A lightweight plugin for adding CORS headers to specified endpoints. :star:19
- [CrudJsonApi plugin](https://github.com/FriendsOfCake/crud-json-api) - Crud listener for building [JSON API](http://jsonapi.org/) compliant APIs. :star:25
- [FractalTransformerView plugin](https://github.com/andrej-griniuk/cakephp-fractal-transformer-view) - A plugin which allows using [Fractal transformers](http://fractal.thephpleague.com/transformers/) for your API output. :star:13
- [JsonApi plugin](https://github.com/josbeir/cakephp-json-api) - Implements the [JSON API](http://jsonapi.org/) format. :star:25
- [RestApi plugin](https://github.com/multidots/cakephp-rest-api) - Provides basic support for building REST API services. :star:57

## Search
*Plugins and software for indexing and performing search queries on data.*


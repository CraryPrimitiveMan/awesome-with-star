# Information comes from [ziadoz/awesome-php](https://github.com/ziadoz/awesome-php)
# Awesome PHP [![Build Status](https://api.travis-ci.org/ziadoz/awesome-php.svg?branch=master)](https://travis-ci.org/ziadoz/awesome-php)

A curated list of amazingly awesome PHP libraries, resources and shiny things.

## Contributing and Collaborating
Please see [CONTRIBUTING](https://github.com/ziadoz/awesome-php/blob/master/CONTRIBUTING.md), [CODE-OF-CONDUCT](https://github.com/ziadoz/awesome-php/blob/master/CODE-OF-CONDUCT.md) and [COLLABORATING](https://github.com/ziadoz/awesome-php/blob/master/COLLABORATING.md) for details.

## Table of Contents
- [Awesome PHP](#awesome-php)
    - [Composer Repositories](#composer-repositories)
    - [Dependency Management](#dependency-management)
    - [Dependency Management Extras](#dependency-management-extras)
    - [Frameworks](#frameworks)
    - [Framework Extras](#framework-extras)
    - [Components](#components)
    - [Micro Frameworks](#micro-frameworks)
    - [Micro Framework Extras](#micro-framework-extras)
    - [Routers](#routers)
    - [Templating](#templating)
    - [Static Site Generators](#static-site-generators)
    - [HTTP](#http)
    - [Middlewares](#middlewares)
    - [URL](#url)
    - [Email](#email)
    - [Files](#files)
    - [Streams](#streams)
    - [Dependency Injection](#dependency-injection)
    - [Imagery](#imagery)
    - [Testing](#testing)
    - [Continuous Integration](#continuous-integration)
    - [Documentation](#documentation)
    - [Security](#security)
    - [Passwords](#passwords)
    - [Code Analysis](#code-analysis)
    - [Code Quality](#code-quality)
    - [Static Analysis](#static-analysis)
    - [Architectural](#architectural)
    - [Debugging and Profiling](#debugging-and-profiling)
    - [Build Tools](#build-tools)
    - [Task Runners](#task-runners)
    - [Navigation](#navigation)
    - [Asset Management](#asset-management)
    - [Geolocation](#geolocation)
    - [Date and Time](#date-and-time)
    - [Event](#event)
    - [Logging](#logging)
    - [E-commerce](#e-commerce)
    - [PDF](#pdf)
    - [Office](#office)
    - [Database](#database)
    - [Migrations](#migrations)
    - [NoSQL](#nosql)
    - [Queue](#queue)
    - [Search](#search)
    - [Command Line](#command-line)
    - [Authentication and Authorization](#authentication-and-authorization)
    - [Markup](#markup)
    - [Strings](#strings)
    - [Numbers](#numbers)
    - [Filtering and Validation](#filtering-and-validation)
    - [API](#api)
    - [Caching](#caching)
    - [Data Structure and Storage](#data-structure-and-storage)
    - [Notifications](#notifications)
    - [Deployment](#deployment)
    - [Internationalisation and Localisation](#internationalisation-and-localisation)
    - [Third Party APIs](#third-party-apis)
    - [Extensions](#extensions)
    - [Miscellaneous](#miscellaneous)
- [Software](#software)
    - [PHP Installation](#php-installation)
    - [Development Environment](#development-environment)
    - [Virtual Machines](#virtual-machines)
    - [Text Editors and IDEs](#text-editors-and-ides)
    - [Web Applications](#web-applications)
    - [Infrastructure](#infrastructure)
- [Resources](#resources)
    - [PHP Websites](#php-websites)
    - [Other Websites](#other-websites)
    - [PHP Books](#php-books)
    - [PHP Videos](#php-videos)
    - [PHP Podcasts](#php-podcasts)
    - [PHP Reading](#php-reading)
    - [PHP Internals Reading](#php-internals-reading)
- [Contributing](#contributing)

### Composer Repositories
*Composer Repositories.*

* [Firegento](http://packages.firegento.com/) - Magento Module Composer Repository.
* [Packagist](https://packagist.org/) - The PHP Package Repository.
* [PaketHub](https://pakethub.com/) - All-in-One PHP Package Repository.
* [Private Packagist](https://packagist.com/) - Composer package archive as a service for PHP.
* [WordPress Packagist](https://wpackagist.org/) - Manage your plugins with Composer.
* [Zend Framework Packages](https://packages.zendframework.com/) - Zend Framework Composer Repository.

### Dependency Management
*Libraries for dependency and package management.*

* [Composer Installers](https://github.com/composer/installers) - A  multi framework Composer library installer. :star:835
* [Composer](https://getcomposer.org/) - A package and dependency manager.
* [Melody](http://melody.sensiolabs.org/) - A tool to build one file Composer scripts.
* [Pickle](https://github.com/FriendsOfPHP/pickle) - A PHP extension installer. :star:1033

### Dependency Management Extras
*Extras related to dependency management.*

* [Composed](https://github.com/joshdifabio/composed) - A library to parse your project's Composer environment at runtime. :star:27
* [Composer Checker](https://github.com/silpion/composer-checker) - A tool to validate Composer configurations. :star:12
* [Composer Merge Plugin](https://github.com/wikimedia/composer-merge-plugin) - A composer plugin to merge several composer.json files. :star:376
* [Composition](https://github.com/bamarni/composition) - A library to check your Composer environment at runtime. :star:105
* [NameSpacer](https://github.com/ralphschindler/Namespacer) - A library to convert from underscores to namespaces. :star:59
* [Patch Installer](https://github.com/goatherd/patch-installer) - A library to install patches using Composer. :star:50
* [Prestissimo](https://github.com/hirak/prestissimo) - A composer plugin which enables parallel install process. :star:3450
* [Satis](https://github.com/composer/satis) - A static Composer repository generator. :star:1650
* [tooly](https://github.com/tommy-muehle/tooly-composer-script) - A library to manage PHAR files in project using Composer. :star:67
* [Toran Proxy](https://toranproxy.com) - A static Composer repository and proxy.

### Frameworks
*Web development frameworks.*

* [Aura Framework](http://auraphp.com/framework/) - A framework built from independent components.
* [CakePHP](https://cakephp.org/) - A rapid application development framework (CP).
* [Laravel 5](https://laravel.com/) - Another PHP framework (L5).
* [Nette](https://nette.org) - Another framework comprised of individual components.
* [Phalcon](https://phalconphp.com/en/) - A framework implemented as a C extension.
* [PPI Framework 2](https://github.com/ppi) - An interoperability framework.
* [Symfony](https://symfony.com/) - A framework comprised of individual components (SF).
* [Yii2](https://github.com/yiisoft/yii2/) - Another PHP framework.
* [Zend Framework 2](https://framework.zend.com) - Another framework comprised of individual components (ZF2).
* [Ice](https://www.iceframework.org/) - Another simple and fast PHP framework delivered as C-extension.

### Framework Extras
*Extras related to web development frameworks.*

* [CakePHP CRUD](https://github.com/friendsofcake/crud) - A Rapid Application Development (RAD) plugin for CakePHP. :star:294
* [Knp RAD Components](http://rad.knplabs.com/) - A set of Rapid Application Development (RAD) components for Symfony.
* [Symfony CMF](https://github.com/symfony-cmf/symfony-cmf) - A Content Management Framework to create custom CMS. :star:737

### Components
*Standalone components from web development frameworks and development groups.*

* [Aura](http://auraphp.com/) - Independent components, fully decoupled from each other and from any framework.
* [CakePHP Plugins](https://plugins.cakephp.org/) - A directory of CakePHP plugins.
* [Hoa Project](https://hoa-project.net/En/) - Another package of PHP components.
* [League of Extraordinary Packages](https://thephpleague.com/) - A PHP package development group.
* [Symfony Components](http://symfony.com/doc/master/components/index.html) - The components that make Symfony.
* [Zend Framework 2 Components](https://docs.zendframework.com/) - The components that make Zend Framework.

### Micro Frameworks
*Micro frameworks and routers.*

* [Bullet PHP](http://bulletphp.com/) - A micro framework for building REST APIs.
* [Lumen](https://lumen.laravel.com) - A micro-framework by Laravel.
* [Proton](https://github.com/alexbilbie/Proton) - A StackPHP compatible micro framework. :star:273
* [Radar](https://github.com/radarphp/Radar.Adr) - An Action-Domain-Responder implementation for PHP. :star:43
* [Silex](https://silex.symfony.com/) - A micro framework built around Symfony components.
* [Slim](https://www.slimframework.com/) - Another simple micro framework.

### Micro Framework Extras
*Extras related to micro frameworks and routers.*

* [Silex Skeleton](https://github.com/silexphp/Silex-Skeleton) - A project skeleton for Silex. :star:828
* [Silex Web Profiler](https://github.com/silexphp/Silex-WebProfiler) - A web debug toolbar for Silex. :star:203
* [Slim Skeleton](https://github.com/slimphp/Slim-Skeleton) - A skeleton for Slim. :star:772
* [Slim View](https://github.com/slimphp/Slim-Views) - A collection of custom views for Slim. :star:313

### Routers
*Libraries for handling application routing.*

* [Aura.Router](https://github.com/auraphp/Aura.Router) - A full-featured routing library. :star:347
* [Fast Route](https://github.com/nikic/FastRoute) - A fast routing library. :star:2729
* [Klein](https://github.com/klein/klein.php) - A flexible router. :star:2226
* [Pux](https://github.com/c9s/Pux) - Another fast routing library. :star:1234
* [Route](https://github.com/thephpleague/route) - A routing library built on top of Fast Route. :star:307

### Templating
*Libraries and tools for templating and lexing.*

* [Aura.View](https://github.com/auraphp/Aura.View) - Provides TemplateView and TwoStepView using PHP as the tempting language, with support for partials, sections, and helpers. :star:63
* [Foil](https://github.com/FoilPHP/Foil) - Another native PHP templating library. :star:154
* [Lex](https://github.com/pyrocms/lex) - A lightweight template parser. :star:99
* [MtHaml](https://github.com/arnaud-lb/MtHaml) - A PHP implementation of the HAML template language. :star:344
* [Mustache](https://github.com/bobthecow/mustache.php) - A PHP implementation of the Mustache template language. :star:2638
* [Phly Mustache](https://github.com/phly/phly_mustache) - Another PHP implementation of the Mustache template language. :star:126
* [PHPTAL](http://phptal.org/) - A PHP implementation of the [TAL](https://en.wikipedia.org/wiki/Template_Attribute_Language) templating language.
* [Plates](http://platesphp.com/) - A native PHP templating library.
* [Smarty](https://www.smarty.net/) - A template engine to complement PHP.
* [Twig](https://twig.symfony.com/) - A comprehensive templating language.
* [Tale Jade](https://github.com/Talesoft/tale-jade) - A PHP implementation of the Jade template language. :star:87

### Static Site Generators
*Tools for pre-processing content to generate web pages.*

* [Couscous](http://couscous.io) - Couscous turns Markdown documentation into beautiful websites. It's GitHub Pages on steroids.
* [Phrozn](https://github.com/Pawka/phrozn) - Another tool that converts Textile, Markdown and Twig into HTML. :star:476
* [Sculpin](https://sculpin.io) - A tool that converts Markdown and Twig into static HTML.
* [Spress](http://spress.yosymfony.com) - An extensible tool that converts Markdown and Twig into HTML.

### HTTP
*Libraries for working with HTTP.*

* [Buzz](https://github.com/kriswallsmith/Buzz) - Another HTTP client. :star:1415
* [Guzzle]( https://github.com/guzzle/guzzle) - A comprehensive HTTP client.
* [HTTPFul](https://github.com/nategood/httpful) - A chainable HTTP client. :star:1440
* [HTTPlug](http://httplug.io) - An HTTP client abstraction without binding to a specific implementation.
* [PHP VCR](http://php-vcr.github.io/) - A library for recording and replaying HTTP requests.
* [Requests](https://github.com/rmccue/Requests) - A simple HTTP library. :star:2855
* [Retrofit](https://github.com/tebru/retrofit-php) - A library to ease creation of REST API clients. :star:111
* [zend-diactoros](https://github.com/zendframework/zend-diactoros) - PSR-7 HTTP Message implementation. :star:615

### Scraping
*Libraries for scraping websites.*

* [Embed](https://github.com/oscarotero/Embed) - An information extractor from any web service or page. :star:1173
* [Goutte](https://github.com/FriendsOfPHP/Goutte) - A simple web scraper. :star:6107
* [PHP Spider](https://github.com/mvdbos/php-spider) - A configurable and extensible PHP web spider. :star:961

### Middlewares
*Libraries for building application using middlewares.*

* [Expressive](https://zendframework.github.io/zend-expressive/) - PSR-7 Middleware framework from Zend.
* [PSR7-Middlewares](https://github.com/oscarotero/psr7-middlewares) - Inspiring collection of handy middlewares. :star:660
* [Relay](https://github.com/relayphp/Relay.Relay) - A PHP 5.5 PSR-7 middleware dispatcher. :star:186
* [Stack](https://github.com/stackphp) - A library of stackable middleware for Silex/Symfony.
* [zend-stratigility](https://github.com/zendframework/zend-stratigility) - Middleware for PHP built on top of PSR-7. :star:208

### URL
*Libraries for parsing URLs.*

* [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) - A domain suffix parser library. :star:511
* [Purl](https://github.com/jwage/purl) - A URL manipulation library. :star:740
* [sabre/uri](https://github.com/sabre-io/uri) - A functional URI manipulation library. :star:140
* [Uri](https://github.com/thephpleague/uri) - Another URL manipulation library. :star:292

### Email
*Libraries for sending and parsing email.*

* [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles) - A library to inline CSS in email templates. :star:2189
* [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) - An email reply parser library. :star:462
* [Email Validator](https://github.com/nojacko/email-validator) - A small email address validation library. :star:89
* [Fetch](https://github.com/tedious/Fetch) - An IMAP library. :star:449
* [Mautic](https://github.com/mautic/mautic) - Email marketing automation :star:2211
* [PHPMailer](https://github.com/PHPMailer/PHPMailer) - Another mailer solution. :star:10529
* [Stampie](https://github.com/Stampie/Stampie) - A library for email services such as [SendGrid](https://sendgrid.com/), [PostMark](https://postmarkapp.com), [MailGun](https://www.mailgun.com/) and [Mandrill](http://www.mandrill.com). :star:240
* [SwiftMailer](https://swiftmailer.symfony.com) - A mailer solution.

### Files
*Libraries for file manipulation and MIME type detection.*

* [Apache MIME Types](https://github.com/dflydev/dflydev-apache-mime-types) - A library that parses Apache MIME types. :star:46
* [Canal](https://github.com/dflydev/dflydev-canal) - A library to determine internet media types. :star:31
* [CSV](https://github.com/thephpleague/csv) - A CSV data manipulation library. :star:1439
* [Ferret](https://github.com/versionable/Ferret) - A MIME detection library. :star:19
* [Flysystem](https://github.com/thephpleague/Flysystem) - Another filesystem abstraction layer. :star:4976
* [Gaufrette](https://github.com/KnpLabs/Gaufrette) - A filesystem abstraction layer. :star:1913
* [Hoa Mime](https://github.com/hoaproject/Mime) - Another MIME detection library. :star:81
* [Lurker](https://github.com/henrikbjorn/Lurker) - A resource tracking library. :star:5
* [PHP FFmpeg](https://github.com/PHP-FFmpeg/PHP-FFmpeg/) - A wrapper for the [FFmpeg](http://www.ffmpeg.org/) video library.
* [UnifiedArchive](https://github.com/wapmorgan/UnifiedArchive) - A unified reader and writer of compressed archives. :star:109

### Streams
*Libraries for working with streams.*

* [Streamer](https://github.com/fzaninotto/Streamer) - A simple object-orientated stream wrapper library. :star:240

### Dependency Injection
*Libraries that implement the dependency injection design pattern.*

* [Aura.Di](https://github.com/auraphp/Aura.Di) - A serializable dependency injection container with constructor and setter injection, interface and trait awareness, configuration inheritance, and much more. :star:271
* [Acclimate](https://github.com/AcclimateContainer/acclimate-container) - A common interface to dependency injection containers and service locators. :star:192
* [Auryn](https://github.com/rdlowrey/Auryn) - A recursive dependency injector. :star:544
* [Container](https://github.com/thephpleague/container) - Another flexible dependency injection container. :star:351
* [Disco](https://github.com/bitExpert/disco) - A PSR-11 compatible, annotation-based dependency injection container. :star:107
* [PHP-DI](http://php-di.org/) - A dependency injection container that supports autowiring.
* [Pimple](https://pimple.symfony.com/) - A tiny dependency injection container.
* [Symfony DI](https://github.com/symfony/dependency-injection) - A dependency injection container component (SF). :star:576

### Imagery
*Libraries for manipulating images.*

* [Color Extractor](https://github.com/thephpleague/color-extractor) - A library for extracting colours from images. :star:808
* [GIF Creator](https://github.com/Sybio/GifCreator) - A library to create GIF animations from multiple images. :star:247
* [GIF Frame Extractor](https://github.com/Sybio/GifFrameExtractor) - A library to extract GIF animation frame information. :star:106
* [Glide](https://github.com/thephpleague/glide) - An on-demand image manipulation library. :star:1271
* [Image Hash](https://github.com/jenssegers/imagehash) - A library for generating perceptual image hashes. :star:995
* [Image Optimizer](https://github.com/psliwa/image-optimizer) - A library for optimizing images. :star:471
* [Image With Text](https://github.com/nmcteam/image-with-text) - A library for embedding text into images. :star:107
* [Imagine](http://imagine.readthedocs.io/en/latest/index.html) - An image manipulation library.
* [Intervention Image](https://github.com/Intervention/image) - Another image manipulation library. :star:6465
* [PHP Image Workshop](https://github.com/Sybio/ImageWorkshop) - Another image manipulation library. :star:782

### Testing
*Libraries for testing codebases and generating test data.*

* [Alice](https://github.com/nelmio/alice) - An expressive fixture generation library. :star:1537
* [AspectMock](https://github.com/Codeception/AspectMock) - A mocking framework for PHPUnit/Codeception. :star:607
* [Atoum](https://github.com/atoum/atoum) - A simple testing library. :star:1153
* [Behat](http://docs.behat.org/en/v2.5/) - A behaviour driven development (BDD) testing framework.
* [Codeception](https://github.com/Codeception/Codeception) - A full stack testing framework. :star:3186
* [DBUnit](https://github.com/sebastianbergmann/dbunit) - A database testing library for PHPUnit. :star:184
* [Faker](https://github.com/fzaninotto/Faker) - A fake data generator library. :star:13894
* [HTTP Mock](https://github.com/InterNations/http-mock) - A library for mocking HTTP requests in unit tests. :star:305
* [Kahlan](https://github.com/kahlan/kahlan) - Full stack Unit/BDD testing framework with built-in stub, mock and code-coverage support. :star:838
* [Mink](http://mink.behat.org/en/latest/) - Web acceptance testing.
* [Mockery](https://github.com/mockery/mockery) - A mock object library for testing. :star:3829
* [ParaTest](https://github.com/brianium/paratest) - A parallel testing library for PHPUnit. :star:625
* [Peridot](https://github.com/peridot-php/peridot) - An event driven test framework. :star:281
* [Phake](https://github.com/mlively/Phake) - Another mock object library for testing. :star:420
* [Pho](https://github.com/danielstjules/pho) - Another behaviour driven development testing framework. :star:282
* [PHP-Mock](https://github.com/php-mock/php-mock) - A mock library for built-in PHP functions (e.g. time()). :star:173
* [PHPSpec](https://github.com/phpspec/phpspec) - A design by specification unit testing library. :star:1351
* [PHPT](https://qa.php.net/write-test.php) - A test tool used by PHP itself.
* [PHPUnit](https://github.com/sebastianbergmann/phpunit) - A unit testing framework. :star:8343
* [Prophecy](https://github.com/phpspec/prophecy) - A highly opinionated mocking framework. :star:2475
* [Samsui](https://github.com/mauris/samsui) - Another fake data generator library. :star:30
* [VFS Stream](https://github.com/mikey179/vfsStream) - A virtual filesystem stream wrapper for testing. :star:921
* [VFS](https://github.com/adlawson/php-vfs) - Another virtual filesystem for testing. :star:298

### Continuous Integration
*Libraries and applications for continuous integration.*

* [CircleCI](https://circleci.com) - A continuous integration platform.
* [GitlabCi](https://about.gitlab.com/gitlab-ci/) - Let GitLab CI test, build, deploy your code. TravisCi like.
* [Jenkins](https://jenkins.io/index.html) - A continous integration platform with [PHP support](http://jenkins-php.org/index.html).
* [JoliCi](https://github.com/jolicode/JoliCi) - A continuous integration client written in PHP and powered by Docker. :star:658
* [PHPCI](https://www.phptesting.org/) - An open source continuous integration platform for PHP.
* [SemaphoreCI](https://semaphoreci.com/) - A continuous integration platform for open source and private projects.
* [Shippable](https://app.shippable.com/) - A docker based continious integration platform for open source and private projects.
* [Sismo](https://sismo.symfony.com/) - A continuous testing server library.
* [Travis CI](https://travis-ci.org/) - A continuous integration platform.
* [Wercker](http://www.wercker.com/) - A continuous integration platform

### Documentation
*Libraries for generating project documentation.*

* [APIGen](https://github.com/apigen/apigen) - Another API documentation generator. :star:1687
* [daux.io](https://github.com/justinwalsh/daux.io) - A documentation generator which uses Markdown files. :star:4677
* [PHP Documentor 2](https://github.com/phpDocumentor/phpDocumentor2) - A documentation generator. :star:2115
* [phpDox](http://phpdox.de/) - A documentation generator for PHP projects (that is not limited to API documentation).
* [Sami](https://github.com/FriendsOfPHP/Sami) - An API documentation generator. :star:1774

### Security
*Libraries for generating secure random numbers, encrypting data and scanning for vulnerabilities.*

* [Halite](https://paragonie.com/project/halite) - A simple library for encryption using [libsodium](https://github.com/jedisct1/libsodium).
* [HTML Purifier](https://github.com/ezyang/htmlpurifier) - A standards compliant HTML filter. :star:1151
* [IniScan](https://github.com/psecio/iniscan) - A tool that scans PHP INI files for security. :star:1271
* [Optimus](https://github.com/jenssegers/optimus) - Id obfuscation based on Knuth's multiplicative hashing method. :star:746
* [PHP Encryption](https://github.com/defuse/php-encryption) - Secure PHP Encryption Library. :star:1555
* [PHP IDS](https://github.com/PHPIDS/PHPIDS) - A structured PHP security layer. :star:581
* [PHP SSH](https://github.com/Herzult/php-ssh) - An experimental object orientated SSH wrapper library. :star:304
* [PHPSecLib](http://phpseclib.sourceforge.net/) - A pure PHP secure communications library.
* [random_compat](https://github.com/paragonie/random_compat) - PHP 5.x support for `random_bytes()` and `random_int()` :star:2097
* [RandomLib](https://github.com/ircmaxell/RandomLib) - A library for generating random numbers and strings. :star:671
* [SecurityMultiTool](https://github.com/padraic/SecurityMultiTool) - A PHP security library. :star:122
* [SensioLabs Security Check](https://security.sensiolabs.org/) - A web tool to check your Composer dependencies for security advisories.
* [TCrypto](https://github.com/timoh6/TCrypto) - A simple encrypted key-value storage library. :star:52
* [VAddy](https://vaddy.net/) - A continuous security testing platform for web applications.
* [Zed](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - An integrated penetration testing tool for web applications.

### Passwords
*Libraries and tools for working with and storing passwords.*

* [GenPhrase](https://github.com/timoh6/GenPhrase) - A library for generating secure random passphrases. :star:68
* [Password Compat](https://github.com/ircmaxell/password_compat) - A compatibility library for the new PHP 5.5 password functions. :star:1984
* [Password Policy](https://github.com/ircmaxell/password-policy) - A password policy library for PHP and JavaScript. :star:55
* [Password Validator](https://github.com/jeremykendall/password-validator) - A library for validating and upgrading password hashes. :star:139
* [Password-Generator](https://github.com/hackzilla/password-generator) - PHP library to generate random passwords. :star:99
* [PHP Password Lib](https://github.com/ircmaxell/PHP-PasswordLib) - A library for generating and validating passwords. :star:366
* [phpass](http://www.openwall.com/phpass/) - A portable password hashing framework.
* [Zxcvbn PHP](https://github.com/bjeavons/zxcvbn-php) - A realistic PHP password strength estimate library based on Zxcvbn JS. :star:413

### Code Analysis
*Libraries and tools for analysing, parsing and manipulating codebases.*

* [Better Reflection](https://github.com/Roave/BetterReflection) - AST-based reflection library that allows analysis and manipulation of code :star:483
* [Code Climate](https://codeclimate.com) - An automated code review.
* [PHP Parser](https://github.com/nikic/PHP-Parser) - A PHP parser written in PHP. :star:4651
* [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) - A command line utility that compares two source sets and determines the appropriate semantic versioning to apply. :star:381
* [PHPLOC](https://github.com/sebastianbergmann/phploc) - A tool for quickly measuring the size of a PHP project. :star:1431
* [PHPQA](https://github.com/EdgedesignCZ/phpqa) - A tool for running QA tools (phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics). :star:212
* [Qafoo Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer) - A tool to visualize metrics and source code. :star:415
* [Scrutinizer](https://scrutinizer-ci.com/) - A web tool to [scrutinise PHP code](https://github.com/scrutinizer-ci/php-analyzer).
* [UBench](https://github.com/devster/ubench) - A simple micro benchmark library. :star:451

### Code Quality
*Libraries for managing code quality, formatting and linting.*

* [PHP CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) - A library that detects PHP, CSS and JS coding standard violations. :star:4524
* [PHP CS Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) - A coding standards fixer library. :star:5522
* [PHP Mess Detector](https://phpmd.org/) - A library that scans code for bugs, sub-optimal code, unused parameters and more.
* [PHPCheckstyle](https://github.com/PHPCheckstyle/phpcheckstyle) - A tool to help adhere to certain coding conventions. :star:111
* [PHPCPD](https://github.com/sebastianbergmann/phpcpd) - A library that detects copied and pasted code. :star:1416

### Static Analysis
*Libraries for performing static analysis of PHP code.*

* [Exakat](https://github.com/exakat/exakat) - A static analysis engine for PHP. :star:113
* [Mondrian](https://github.com/Trismegiste/Mondrian) - A code analysis tool using Graph Theory. :star:344
* [phan](https://github.com/phan/phan) - A static analyzer based on PHP 7+ and the php-ast extension. :star:2648
* [PHPCompatibility](https://github.com/wimg/PHPCompatibility) - A PHP compatibility checker for PHP CodeSniffer. :star:787
* [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - A tool to create customisable dependency graphs. :star:294
* [PHP Metrics](https://github.com/phpmetrics/PhpMetrics) - A static metric library. :star:1399
* [PHP Migration](https://github.com/monque/PHP-Migration) - A static analyzer for PHP version migration. :star:121
* [PHPStan](https://github.com/phpstan/phpstan) - A PHP Static Analysis Tool. :star:3233
* [Pslam](https://github.com/vimeo/psalm) - A static analysis tool for finding errors in PHP applications. :star:686

### Architectural
*Libraries related to design patterns, programming approaches and ways to organize code.*

* [Compose](https://github.com/igorw/compose) - A function composition library. :star:79
* [Design Patterns PHP](https://github.com/domnikl/DesignPatternsPHP) - A repository of software patterns implemented in PHP. :star:14319
* [Finite](http://yohan.giarel.li/Finite/) - A simple PHP finite state machine.
* [Functional PHP](https://github.com/lstrojny/functional-php) - A functional programming library. :star:1153
* [Galapagos](https://github.com/endel/galapagos) - Evolutionary language transformation. :star:11
* [Iter](https://github.com/nikic/iter) - A library that provides iteration primitives using generators. :star:637
* [Monad PHP](https://github.com/ircmaxell/monad-php) - A simple Monad library. :star:230
* [Patchwork](http://patchwork2.org/) - A library for redefining userland functions.
* [PHP Option](https://github.com/schmittjoh/php-option) - An option type library. :star:688
* [Pipeline](https://github.com/thephpleague/pipeline) - A pipeline pattern implementation. :star:456
* [Ruler](https://github.com/bobthecow/Ruler) - A simple stateless production rules engine. :star:771
* [RulerZ](https://github.com/K-Phoen/rulerz) - A powerful rule engine and implementation of the Specification pattern. :star:596

### Debugging and Profiling
*Libraries and tools for debugging and profiling code.*

* [APM](http://pecl.php.net/package/APM) - Monitoring extension collecting errors and statistics into SQLite/MySQL/StatsD.
* [Barbushin PHP Console](https://github.com/barbushin/php-console) - Another web debugging console using Google Chrome. :star:1087
* [Blackfire.io](https://blackfire.io) - A low-overhead code profiler.
* [Kint](https://github.com/kint-php/kint) - A debugging and profiling tool. :star:2045
* [PHP Console](https://github.com/Seldaek/php-console) - A web debugging console. :star:445
* [PHP Debug Bar](http://phpdebugbar.com/) - A debugging toolbar.
* [PHPBench](https://github.com/phpbench/phpbench) - A benchmarking Framework. :star:665
* [Tideways.io](https://tideways.io/) - Monitoring and profiling tool
* [Tracy](https://github.com/nette/tracy) - A simple error detection, logging and time measuring library. :star:890
* [xDebug](https://github.com/xdebug/xdebug) - A debug and profile tool for PHP. :star:1340
* [XHProf](https://github.com/phacility/xhprof) - A profiling tool originally developed by Facebook. :star:2084
* [Z-Ray](http://www.zend.com/en/products/server/z-ray) - A debug and profile tool for Zend Server.

### Build Tools
*Project build and automation tools.*

* [Bob](https://github.com/CHH/bob) - A simple project automation tool. :star:100
* [Box](https://github.com/box-project/box2) - A utility to build PHAR files. :star:1109
* [Construct](https://github.com/jonathantorres/construct) - A PHP project/micro-package generator. :star:244
* [Phake](https://github.com/jaz303/phake) - A rake PHP clone library. :star:380
* [Phing](https://www.phing.info/) - A PHP project build system inspired by Apache Ant.

### Task Runners
*Libraries for automating and running tasks.*

* [Bldr](http://bldr.io/) - A PHP Task runner built on Symfony components.
* [Jobby](https://github.com/jobbyphp/jobby) - A PHP cron job manager without modifying crontab. :star:689
* [Robo](https://github.com/consolidation/Robo) - A PHP Task runner with object-orientated configurations. :star:1927
* [Task](http://taskphp.github.io/) - A pure PHP task runner inspired by Grunt and Gulp.

### Navigation
*Tools for building navigation structures.*

* [KnpMenu](https://github.com/KnpLabs/KnpMenu) - A menu library. :star:573

### Asset Management
*Tools for managing, compressing and minifying website assets.*

* [JShrink](https://github.com/tedious/JShrink) - A JavaScript minifier library. :star:514
* [Munee](https://github.com/meenie/munee) - An asset optimiser library. :star:868
* [Puli](https://github.com/puli/repository) - A library for determining assets absolute paths. :star:440
* [BowerPHP](https://github.com/Bee-Lab/bowerphp) - A PHP implementation of Bower. A package manager for the web :star:479

### Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [GeoCoder](http://geocoder-php.org/) - A geocoding library.
* [GeoJSON](https://github.com/jmikola/geojson) - A GeoJSON implementation. :star:135
* [GeoTools](https://github.com/thephpleague/geotools) - A library of geo-related tools. :star:868
* [PHPGeo](https://github.com/mjaschen/phpgeo) - A simple geo library. :star:929

### Date and Time
*Libraries for working with dates and times.*

* [CalendR](http://yohan.giarel.li/CalendR/) - A calendar management library.
* [Carbon](https://github.com/briannesbitt/Carbon) - A simple DateTime API extension. :star:7544
* [Chronos](https://github.com/cakephp/chronos) - A DateTime API extension supporting both mutable and immutable date/time. :star:485
* [Moment.php](https://github.com/fightbulc/moment.php) - Moment.js inspired PHP DateTime handler with i18n support. :star:673
* [Yasumi](https://github.com/azuyalabs/yasumi) - An library to help you calculate the dates and names of holidays. :star:407

### Event
*Libraries that are event-driven or implement non-blocking event loops.*

* [Amp](https://github.com/amphp/amp) - An event driven non-blocking I/O library. :star:1242
* [Broadway](https://github.com/broadway/broadway) - An event source and CQRS library. :star:1022
* [Cake Event](https://github.com/cakephp/event) - An event dispatcher library (CP). :star:11
* [Elephant.io](https://github.com/Wisembly/Elephant.io) - Yet another web socket library. :star:973
* [Evenement](https://github.com/igorw/evenement) - An event dispatcher library. :star:631
* [Event](https://github.com/thephpleague/event) - An event library with a focus on domain events. :star:382
* [Hoa EventSource](https://github.com/hoaproject/Eventsource) - An event source library. :star:74
* [Hoa WebSocket](https://github.com/hoaproject/Websocket) - Another web socket library. :star:394
* [Prooph Event Store](https://github.com/prooph/event-store) - An event source component to persist event messages :star:304
* [Ratchet](https://github.com/ratchetphp/Ratchet) - A web socket library. :star:3987
* [React](https://github.com/reactphp/react) - An event driven non-blocking I/O library. :star:5855
* [Rx.PHP](https://github.com/asm89/Rx.PHP) - A reactive extension library. :star:214
* [Workerman](https://github.com/walkor/Workerman) - An event driven non-blocking I/O library. :star:5798

### Logging
*Libraries for generating and working with log files.*

* [Monolog](https://github.com/Seldaek/monolog) - A comprehensive logger. :star:8468

### E-commerce
*Libraries and applications for taking payments and building online e-commerce stores.*

* [Money](https://github.com/moneyphp/money) - A PHP implementation of Fowler's money pattern. :star:1772
* [OmniPay](https://github.com/thephpleague/omnipay) - A framework agnostic multi-gateway payment processing library. :star:3955
* [Payum](https://github.com/payum/payum) - A payment abstraction library. :star:1129
* [Shopware](https://github.com/shopware/shopware) - Highly customizable e-commerce software :star:798
* [Swap](https://github.com/florianv/swap) - An exchange rates library. :star:879
* [Sylius](http://sylius.org/) - An open source e-commerce solution.

### PDF
*Libraries and software for working with PDF files.*

* [Dompdf](https://github.com/dompdf/dompdf) - A HTML to PDF converter. :star:4429
* [PHPPdf](https://github.com/psliwa/PHPPdf) - A library for generating PDFs and images from XML. :star:310
* [Snappy](https://github.com/KnpLabs/snappy) - A PDF and image generation library. :star:2635
* [WKHTMLToPDF](https://github.com/wkhtmltopdf/wkhtmltopdf) - A tool to convert HTML to PDF. :star:6331

### Office
*Libraries for working with office suite documents.*

* [ExcelAnt](https://github.com/Wisembly/ExcelAnt) - A library for manipulating Microsoft Excel documents. :star:58
* [PHPPowerPoint](https://github.com/PHPOffice/PHPPresentation) - A library for working with Microsoft PowerPoint Presentations. :star:670
* [PHPWord](https://github.com/PHPOffice/PHPWord) - A library for working with Microsoft Word documents. :star:3024
* [PHPSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet) - A pure PHP library for reading and writing spreadsheet files (successor of PHPExcel)

### Database
*Libraries for interacting with databases using object-relational mapping (ORM) or datamapping techniques.*

* [Atlas.Orm](https://github.com/atlasphp/Atlas.Orm) - A data mapper implementation for your persistence model in PHP. :star:338
* [Aura.Sql](https://github.com/auraphp/Aura.Sql) - Provides an extension to the native PDO along with a profiler and connection locator. :star:407
* [Aura.SqlQuery](https://github.com/auraphp/Aura.SqlQuery) - Independent query builders for MySQL, PostgreSQL, SQLite, and Microsoft SQL Server. :star:262
* [Baum](https://github.com/etrepat/baum) - A nested set implementation for Eloquent. :star:1676
* [Cake ORM](https://github.com/cakephp/orm) - Object-Relational Mapper, implemented using the DataMapper pattern (CP). :star:124
* [Doctrine Extensions](https://github.com/Atlantic18/DoctrineExtensions) - A collection of Doctrine behavioural extensions. :star:2021
* [Doctrine](http://www.doctrine-project.org/) - A comprehensive DBAL and ORM.
* [Eloquent](https://github.com/illuminate/database) - A simple ORM (L5). :star:1361
* [LazyRecord](https://github.com/corneltek/LazyRecord) - A fast ORM designed for simplicity, extendability and performance. :star:3
* [Pomm](https://github.com/chanmix51/Pomm) - An Object Model Manager for PostgreSQL. :star:156
* [Propel](http://propelorm.org/) - A fast ORM, migration library and query builder.
* [ProxyManager](https://github.com/Ocramius/ProxyManager) - A set of utilities to generate proxy objects for data mappers. :star:1145
* [RedBean](https://redbeanphp.com/index.php) - A lightweight, configuration-less ORM.
* [Spot2](https://github.com/spotorm/spot2) - A MySQL datamapper ORM. :star:534

### Migrations
Libraries to help manage database schemas and migrations.

* [Doctrine Migrations](http://docs.doctrine-project.org/projects/doctrine-migrations/en/latest/toc.html) - A migration library for Doctrine.
* [Migrations](https://github.com/icomefromthenet/Migrations) - A migration management library. :star:36
* [Phinx](https://github.com/cakephp/phinx) - Another database migration library. :star:3304
* [PHPMig](https://github.com/davedevelopment/phpmig) - Another migration management library. :star:458
* [Ruckusing](https://github.com/ruckus/ruckusing-migrations) - Database migrations for PHP ala ActiveRecord Migrations with support for MySQL, Postgres, SQLite. :star:481

### NoSQL
*Libraries for working with "NoSQL" backends.*

* [Monga](https://github.com/thephpleague/monga) - A MongoDB abstraction library. :star:307
* [MongoQB](https://github.com/alexbilbie/MongoQB) - A MongoDB query builder library. :star:194
* [PHPMongo](https://github.com/sokil/php-mongo) - A MongoDB ORM. :star:170
* [Predis](https://github.com/nrk/predis) - A feature complete Redis library. :star:4143

### Queue
*Libraries for working with event and task queues.*

* [Bernard](https://github.com/bernardphp/bernard) - A multibackend abstraction library. :star:890
* [BunnyPHP](https://github.com/jakubkulhan/bunny) - A performant pure-PHP AMQP (RabbitMQ) sync and also async (ReactPHP) library. :star:348
* [Pheanstalk](https://github.com/pda/pheanstalk) - A Beanstalkd client library. :star:1300
* [PHP AMQP](https://github.com/php-amqplib/php-amqplib) - A pure PHP AMQP library. :star:2013
* [Tarantool Queue](https://github.com/tarantool-php/queue) - PHP bindings for Tarantool Queue. :star:38
* [Thumper](https://github.com/php-amqplib/Thumper) - A RabbitMQ pattern library. :star:245

### Search
*Libraries and software for indexing and performing search queries on data.*

* [Elastica](https://github.com/ruflin/Elastica) - A client library for ElasticSearch. :star:1597
* [ElasticSearch PHP](https://github.com/elastic/elasticsearch-php) - The official client library for [ElasticSearch](https://www.elastic.co/). :star:2182
* [Solarium](http://www.solarium-project.org/) - A client library for [Solr](http://lucene.apache.org/solr/).
* [Sphinx Search](https://github.com/ripaclub/sphinxsearch) - Sphinx Search library provides SphinxQL indexing and searching features :star:53
* [SphinxQL query builder](http://foolcode.github.io/SphinxQL-Query-Builder/) - A query library for the [Sphinx](http://sphinxsearch.com/) search engine.

### Command Line
*Libraries related to the command line.*

* [Aura.Cli](https://github.com/auraphp/Aura.Cli) - Provides the equivalent of request ( Context ) and response ( Stdio ) objects for the command line interface, including Getopt support, and an independent Help object for describing commands. :star:95
* [Boris](https://github.com/borisrepl/boris) - A tiny PHP REPL. :star:2155
* [Cilex](https://github.com/Cilex/Cilex) - A micro framework for building command line tools. :star:613
* [CLI Menu](https://github.com/php-school/cli-menu) - A library for building CLI menus. :star:901
* [CLIFramework](https://github.com/c9s/CLIFramework) - A command-line framework supports zsh/bash completion generation, subcommands and option constraints. It also powers phpbrew. :star:330
* [CLImate](https://github.com/thephpleague/climate) - A library for outputting colours and special formatting. :star:1293
* [Commando](https://github.com/nategood/commando) - Another simple command line opt parser. :star:681
* [Cron Expression](https://github.com/mtdowling/cron-expression) - A library to calculate cron run dates. :star:2200
* [GetOpt](https://github.com/getopt-php/getopt-php) - A command line opt parser. :star:162
* [GetOptionKit](https://github.com/c9s/GetOptionKit) - Another command line opt parser. :star:112
* [Hoa Console](https://github.com/hoaproject/Console) - Another command line library. :star:258
* [OptParse](https://github.com/CHH/optparse) - Another command line opt parser. :star:17
* [Pecan](https://github.com/mcrumm/pecan) - An event-driven, non-blocking shell. :star:43
* [PsySH](https://github.com/bobthecow/psysh) - Another PHP REPL. :star:3579
* [ShellWrap](https://github.com/MrRio/shellwrap) - A simple command line wrapper library. :star:689

### Authentication and Authorization
*Libraries for implementing user authentication and authorization.*

* [Aura.Auth](https://github.com/auraphp/Aura.Auth) - Provides authentication functionality and session tracking using various adapters. :star:97
* [Hawk](https://github.com/dflydev/dflydev-hawk) - A Hawk HTTP authentication library. :star:64
* [SocialConnect Auth](https://github.com/socialConnect/auth) - An open source social sign (OAuth1\OAuth2\OpenID\OpenIDConnect). :star:271
* [Json Web Token](https://github.com/lcobucci/jwt) - Json Tokens to authenticate and transmit information. :star:2055
* [OAuth 1.0 Client](https://github.com/thephpleague/oauth1-client) - An OAuth 1.0 client library. :star:223
* [OAuth 2.0 Client](https://github.com/thephpleague/oauth2-client) - An OAuth 2.0 client library. :star:1887
* [OAuth2 Server](http://bshaffer.github.io/oauth2-server-php-docs/) - Another OAuth2 server implementation.
* [OAuth2 Server](http://oauth2.thephpleague.com/) - An OAuth2 authentication server, resource server and client library.
* [Opauth](https://github.com/opauth/opauth) - A multi-provider authentication framework. :star:1610
* [PHP oAuthLib](https://github.com/Lusitanian/PHPoAuthLib) - Another OAuth library. :star:989
* [Sentinel Social](https://cartalyst.com/manual/sentinel-social/2.0) - A library for social network authentication.
* [Sentinel](https://cartalyst.com/manual/sentinel/2.0) - A framework agnostic authentication & authorisation library.
* [TwitterOAuth](https://github.com/abraham/twitteroauth) - A Twitter OAuth library. :star:3558
* [TwitterSDK](https://github.com/lyrixx/twitter-sdk) - A fully tested Twitter SDK. :star:37

### Markup
*Libraries for working with markup.*

* [Cebe Markdown](https://github.com/cebe/markdown) - An fast and extensible Markdown parser. :star:719
* [Ciconia](https://github.com/kzykhys/Ciconia) - Another Markdown parser that supports Github flavoured Markdown. :star:378
* [CommonMark PHP](https://github.com/thephpleague/commonmark) - A Markdown parser which supports the full [CommonMark spec](http://spec.commonmark.org/). :star:919
* [Decoda](https://github.com/milesj/decoda) - A lightweight markup parser library. :star:172
* [Emoji](https://github.com/heyupdate/Emoji) - A library that converts unicode characters and names into emoji images. :star:36
* [HTML to Markdown](https://github.com/thephpleague/html-to-markdown) - Converts HTML into Markdown. :star:706
* [HTML5 PHP](https://github.com/Masterminds/html5-php) - An HTML5 parser and serializer library. :star:541
* [Parsedown](https://github.com/erusev/parsedown) - Another Markdown parser. :star:6181
* [PHP Markdown](https://github.com/michelf/php-markdown) - A Markdown parser. :star:2624

### Strings
*Libraries for parsing and manipulating strings.*

* [Agent](https://github.com/jenssegers/agent) - A PHP desktop/mobile user agent parser, based on Mobiledetect. :star:1880
* [ANSI to HTML5](https://github.com/sensiolabs/ansi-to-html) - An ANSI to HTML5 converter library. :star:120
* [Color Jizz](https://github.com/mikeemoo/ColorJizz-PHP) - A library for manipulating and converting colours. :star:238
* [Device Detector](https://github.com/piwik/device-detector) - Another library for parsing user agent strings. :star:985
* [Hoa String](https://github.com/hoaproject/Ustring) - Another UTF-8 string library. :star:117
* [Jieba-PHP](https://github.com/fukuball/jieba-php) - A PHP port of Python's jieba. Chinese text segmentation for natural language processing. :star:512
* [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) - A lightweight PHP class for detecting mobile devices (including tablets). :star:7628
* [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) - A portable library for working with UTF-8 strings. :star:62
* [Slugify](https://github.com/cocur/slugify) - A library to convert strings to slugs. :star:1360
* [SQL Formatter](https://github.com/jdorn/sql-formatter/) - A library for formatting SQL statements.
* [Stringy](https://github.com/danielstjules/Stringy) - A string manipulation library with multibyte support. :star:2062
* [Text](https://github.com/kzykhys/Text) - A text manipulation library. :star:46
* [UA Parser](https://github.com/tobie/ua-parser/tree/master/php) - A library for parsing user agent strings.
* [URLify](https://github.com/jbroadway/urlify) - A PHP port of Django's URLify.js. :star:536
* [UUID](https://github.com/ramsey/uuid) - A library for generating UUIDs. :star:4220

### Numbers
*Libraries for working with numbers.*

* [ByteUnits](https://github.com/gabrielelana/byte-units) - A library to parse, format and convert byte units in binary and metric systems. :star:57
* [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) - A PHP implementation of Google's phone number handling library. :star:2189
* [Math](https://github.com/moontoast/math) - A library for working with large numbers. :star:96
* [Numbers PHP](https://github.com/powder96/numbers.php) - A library for working with numbers. :star:155
* [PHP Conversion](https://github.com/Crisu83/php-conversion) - Another library for converting between units of measure. :star:89
* [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure) - A library for converting between units of measure. :star:7

### Filtering and Validation
*Libraries for filtering and validating data.*

* [Aura.Filter](https://github.com/auraphp/Aura.Filter) - Provides tools to validate and sanitize objects and arrays. :star:109
* [Cake Validation](https://github.com/cakephp/validation) - Another validation library (CP). :star:20
* [DMS Filter](https://github.com/rdohms/DMS-Filter) - An annotation filtering library. :star:78
* [Filterus](https://github.com/ircmaxell/filterus) - A simple PHP filtering library. :star:393
* [ISO-codes](https://github.com/ronanguilloux/IsoCodes) - A library for validating inputs according standards from ISO, International Finance, Public Administrations, GS1, Book Industry, Phone numbers & Zipcodes for many countries :star:497
* [MetaYaml](https://github.com/romaricdrigon/MetaYaml) - A schema validation library that supports YAML, JSON and XML. :star:66
* [Respect Validation](https://github.com/Respect/Validation) - A simple validation library. :star:4377
* [Upload](https://github.com/brandonsavage/Upload) - A library for handling file uploads and validation. :star:1461
* [Valitron](https://github.com/vlucas/valitron) - Another validation library. :star:945
* [Volan](https://github.com/serkin/Volan) - Another simplified validation library. :star:36

### API
*Libraries and web tools for developing APIs.*

* [API Platform](https://api-platform.com ) - Expose in minutes an hypermedia REST API that embraces JSON-LD, Hydra format.
* [Apigility](https://github.com/zfcampus/zf-apigility-skeleton) - An API builder built with Zend Framework 2. :star:465
* [Drest](https://github.com/leedavis81/drest) - A library for exposing Doctrine entities as REST resource endpoints. :star:84
* [HAL](https://github.com/blongden/hal) - A Hypertext Application Language (HAL) builder library. :star:190
* [Hateoas](https://github.com/willdurand/Hateoas) - A HATEOAS REST web service library. :star:810
* [Negotiation](https://github.com/willdurand/Negotiation) - A content negotiation library. :star:565
* [Restler](https://github.com/Luracast/Restler) - A lightweight framework to expose PHP methods as RESTful web API. :star:1230
* [wsdl2phpgenerator](https://github.com/wsdl2phpgenerator/wsdl2phpgenerator) - A tool to generate PHP classes from SOAP WSDL files. :star:636

### Caching
*Libraries for caching data.*

* [Alternative PHP Cache (APC)](http://php.net/manual/en/book.apc.php) - Open opcode cache for PHP.
* [APIx Cache](https://github.com/apix/cache) - A thin PSR-6 cache wrapper to various caching backends emphasising cache tagging and indexing. :star:70
* [CacheTool](https://github.com/gordalina/cachetool) - A tool to clear APC/opcode caches from the command line. :star:534
* [Cake Cache](https://github.com/cakephp/cache) - A caching library (CP). :star:14
* [Doctrine Cache](https://github.com/doctrine/cache) - A caching library. :star:1165
* [Metaphore](https://github.com/sobstel/metaphore) - Cache slam defense using a semaphore to prevent dogpile effect. :star:80
* [Stash](https://github.com/tedious/Stash) - Another library for caching. :star:868
* [Zend Cache](https://github.com/zendframework/zend-cache) - Another caching library (ZF2). :star:41

### Data Structure and Storage
*Libraries that implement data structure or storage techniques.*

* [Ardent](https://github.com/morrisonlevi/Ardent) - A library of data structures. :star:597
* [Cake Collection](https://github.com/cakephp/collection) - A simple collections library (CP). :star:34
* [Collections](https://github.com/italolelis/collections) - Collections Abstraction library for PHP. :star:54
* [Fractal](https://github.com/thephpleague/fractal) - A library for converting complex data structures to JSON output. :star:2298
* [Ginq](https://github.com/akanehara/ginq) - Another PHP library based on .NET's LINQ. :star:157
* [JsonMapper](https://github.com/cweiske/jsonmapper) - A library that maps nested JSON structures onto PHP classes. :star:749
* [Knapsack](https://github.com/DusanKasan/Knapsack) - Collection library inspired by Clojure's sequences. :star:376
* [PHP Collections](https://github.com/schmittjoh/php-collection) - A simple collections library. :star:412
* [PINQ](https://github.com/TimeToogo/Pinq) - A PHP library based on .NET's LINQ (Language Integrated Query). :star:407
* [Porter](https://github.com/ScriptFUSION/Porter) - Data import abstraction framework. :star:362
* [Serializer](https://github.com/schmittjoh/serializer) - A library for serialising and de-serialising data. :star:835
* [Totem](https://github.com/Wisembly/Totem) - A library to manage and create data changesets. :star:73
* [YaLinqo](https://github.com/Athari/YaLinqo) - Yet Another LINQ to Objects for PHP. :star:288
* [Zend Serializer](https://github.com/zendframework/zend-serializer) - Another library for serialising and de-serialising data (ZF2). :star:19

### Notifications
*Libraries for working with notification software.*

* [JoliNotif](https://github.com/jolicode/JoliNotif) - A cross-platform library for desktop notification (support for Growl, notify-send, toaster, etc)
* [Nod](https://github.com/filp/nod) - A notification library (e.g., Growl). :star:51
* [Notification Pusher](https://github.com/Ph3nol/NotificationPusher) - A standalone library for device push notifications. :star:961
* [Notificato](https://github.com/mac-cain13/notificato) - A library for handling push notifications. :star:203
* [Notificator](https://github.com/namshi/notificator) - A lightweight notification library. :star:151
* [Php-pushwoosh](https://github.com/gomoob/php-pushwoosh) - A PHP Library to easily send push notifications with the Pushwoosh REST Web Services. :star:48

### Deployment
*Libraries for project deployment.*

* [Deployer](https://github.com/deployphp/deployer) - A deployment tool. :star:5316
* [Envoy](https://github.com/laravel/envoy) - A tool to run SSH tasks with PHP. :star:1011
* [Plum](https://github.com/aerialls/Plum) - A deployer library. :star:89
* [Pomander](https://github.com/tamagokun/pomander) - A deployment tool for PHP applications. :star:204
* [Rocketeer](https://github.com/rocketeers/rocketeer) - A fast and easy deployer for the PHP world. :star:2569

### Internationalisation and Localisation
*Libraries for Internationalization (I18n) and Localization (L10n).*

* [Aura.Intl](https://github.com/auraphp/Aura.Intl) - Provides internationalization (I18N) tools, specifically package-oriented per-locale message translation. :star:74
* [Cake I18n](https://github.com/cakephp/i18n) - Message translation and localization for dates and numbers (CP)

### Third Party APIs
*Libraries for accessing third party APIs.*

* [Amazon Web Service SDK](https://github.com/aws/aws-sdk-php) - The official PHP AWS SDK library. :star:2942
* [Campaign Monitor](http://campaignmonitor.github.io/createsend-php/) - The official Campaign Monitor PHP library.
* [Digital Ocean](https://github.com/toin0u/DigitalOcean) - A library to interface with the Digital Ocean API. :star:156
* [Dropbox SDK](https://github.com/dropbox/dropbox-sdk-php) - The official PHP Dropbox SDK library. :star:219
* [Github](https://github.com/dsyph3r/github-api3-php) - A library to interface with the Github API. :star:63
* [Mailgun](https://github.com/mailgun/mailgun-php) The official Mailgun PHP API.
* [PHP Github API](https://github.com/KnpLabs/php-github-api) - Another library to interface with the Github API. :star:1216
* [S3 Stream Wrapper](https://github.com/gwkunze/S3StreamWrapper) - A stream wrapper library for Amazon S3. :star:19
* [Stripe](https://github.com/stripe/stripe-php) - The official Stripe PHP library. :star:1420
* [Twilio](https://github.com/twilio/twilio-php) - The official Twilio PHP REST API. :star:901
* [Twitter OAuth](https://github.com/widop/twitter-oauth) - A library to interface with Twitter's OAuth workflow. :star:7
* [Twitter REST](https://github.com/widop/twitter-rest) - A library to interact with Twitter's REST API. :star:25

### Extensions
*Libraries to help build PHP extensions.*

* [PHP CPP](http://www.php-cpp.com/) - A C++ library for developing PHP extensions.
* [Zephir](https://github.com/phalcon/zephir) - A compiled language between PHP and C++ for developing PHP extensions. :star:2218

### Miscellaneous
*Useful libraries or tools that don't fit in the categories above.*

* [Annotations](https://github.com/doctrine/annotations) - An annotations library (part of Doctrine). :star:1108
* [BotMan](https://github.com/botman/botman) - A framework agnostic PHP library to build cross-platform chat bots. :star:3430
* [Cake Utility](https://github.com/cakephp/utility) - Utility classes such as Inflector, String, Hash, Security and Xml (CP). :star:37
* [Chief](https://github.com/adamnicholson/Chief) - A command bus library. :star:38
* [ClassPreloader](https://github.com/ClassPreloader/ClassPreloader) - A library for optimising autoloading. :star:244
* [Country List](https://github.com/umpirsky/country-list) - A list of all countries with names and ISO 3166-1 codes. :star:3213
* [Embera](https://github.com/mpratt/Embera) - An Oembed consumer library. :star:156
* [Essence](https://github.com/essence/essence) - A library for extracting web media. :star:630
* [Flux](https://github.com/selvinortiz/flux) - A regular expression building library. :star:328
* [Graphviz](https://github.com/alexandresalome/graphviz) - A Graphviz library. :star:52
* [Hprose-PHP](https://github.com/hprose/hprose-php) - A very newbility RPC Library, support 25+ languages now. :star:1094
* [JSON Lint](https://github.com/Seldaek/jsonlint) - A JSON lint utility. :star:348
* [JSONPCallbackValidator](https://github.com/willdurand/JsonpCallbackValidator) - A library for validating JSONP callbacks. :star:177
* [Jumper](https://github.com/kakawait/Jumper) - A remote service executor library. :star:42
* [LadyBug](https://github.com/raulfraile/Ladybug) - A dumper library. :star:445
* [Lambda PHP](https://github.com/igorw/lambda-php) - A Lambda calculus interpreter in PHP. :star:19
* [LiteCQRS](https://github.com/beberlei/litecqrs-php) - A CQRS (Command Query Responsibility Separation) library. :star:506
* [Metrics](https://github.com/beberlei/metrics) - A simple metrics API library. :star:235
* [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - Helper for Google's noCAPTCHA (reCAPTCHA). :star:198
* [Nmap](https://github.com/willdurand/nmap) - A PHP wrapper around [Nmap](https://nmap.org/). :star:85
* [Opengraph](https://github.com/euskadi31/Opengraph) - An opengraph library. :star:82
* [Pagerfanta](https://github.com/whiteoctober/Pagerfanta) - A pagination library. :star:859
* [PHP Expression](https://github.com/Kitano/php-expression) - A PHP expression language. :star:32
* [PHP PassBook](https://github.com/eymengunay/php-passbook) - A PHP library for iOS PassBook. :star:200
* [PHP-GPIO](https://github.com/ronanguilloux/php-gpio) - A library for playing with the Raspberry PI's GPIO pins. :star:218
* [PHP-ML](https://github.com/php-ai/php-ml) - A library for Machine Learning in PHP. :star:5341
* [PHPCR](https://github.com/phpcr/phpcr) - A PHP port of the Java Content Repository (JCR). :star:385
* [PHPStack](http://dunkels.com/adam/phpstack/) - A TCP/IP stack proof of concept written in PHP.
* [print_o](https://github.com/koriym/print_o) - An object graph visualizer. :star:71
* [Procrastinator](https://github.com/lstrojny/Procrastinator) - A library for running time consuming tasks. :star:46
* [Prooph Service Bus](https://github.com/prooph/service-bus) - Lightweight message bus supporting CQRS and Micro Services :star:328
* [RMT](https://github.com/liip/RMT) - A library for versioning and releasing software. :star:362
* [sabre/vobject](https://github.com/sabre-io/vobject) - A library for parsing VCard and iCalendar objects. :star:364
* [Slimdump](https://github.com/webfactory/slimdump) - An easy dumper tool for MySQL. :star:56
* [Spork](https://github.com/kriswallsmith/spork) - A process forking library. :star:585
* [Sslurp](https://github.com/EvanDotPro/Sslurp) - A library that makes dealing with SSL suck less. :star:61
* [SuperClosure](https://github.com/jeremeamia/super_closure) - A library that allows Closures to be serialized. :star:826
* [Symfony VarDumper](http://symfony.com/doc/current/components/var_dumper.html) - A variable dumper component (SF).
* [Underscore](http://anahkiasen.github.io/underscore-php/) - A PHP port of the Underscore JS library.
* [Whoops](https://github.com/filp/whoops) - A pretty error handling library. :star:5910

# Software
*Software for creating a development environment.*

### PHP Installation
*Tools to help install and manage PHP on your computer.*

* [HomeBrew PHP](https://github.com/Homebrew/homebrew-php) - A PHP tap for HomeBrew. :star:2667
* [HomeBrew](https://brew.sh/) - A package manager for OSX.
* [PHP Brew](https://github.com/phpbrew/phpbrew) - A PHP version manager and installer. :star:3332
* [PHP Build](https://github.com/php-build/php-build) - Another PHP version installer. :star:739
* [PHP Env](https://github.com/CHH/phpenv) - Another PHP version manager. :star:544
* [PHP OSX](https://php-osx.liip.ch/) - A PHP installer for OSX.
* [PHP Switch](https://github.com/jubianchi/phpswitch) - Another version manager. :star:92
* [VirtPHP](http://virtphp.org/) - A tool for creating and managing isolated PHP environments.

### Development Environment
*Software and tools for creating a sandboxed development environment.*

* [Ansible](https://www.ansible.com/) - A radically simple orchestration framework.
* [Phansible](http://phansible.com/) - A web tool for building PHP development virtual machines with Ansible.
* [Protobox](http://getprotobox.com/) - Another web tool for building PHP development virtual machines.
* [PuPHPet](https://puphpet.com/) - A web tool for building PHP development virtual machines.
* [Puppet](https://puppet.com/) - A server automation framework and application.
* [Vagrant](https://www.vagrantup.com/) - A portable development environment utility.
* [Docker](https://www.docker.com/) - A containerization platform.

### Virtual Machines
*Alternative PHP virtual machines.*

* [Hack](http://hacklang.org/) - A programming language for HHVM that interoperates seamlessly with PHP.
* [HHVM](https://github.com/facebook/hhvm) - A Virtual Machine, Runtime and JIT for PHP by Facebook. :star:15127
* [HippyVM](https://github.com/hippyvm/hippyvm) - Another PHP virtual machine. :star:859

### Text Editors and IDEs
*Text Editors and Integrated Development Environments (IDE) with support for PHP.*

* [Atom](https://atom.io/) - A hackable text editor.
* [Atom IDE](https://ide.atom.io/) - An IDE extension for Atom.
* [Eclipse for PHP Developers](https://www.eclipse.org/downloads/) - A PHP IDE based on the Eclipse platform.
* [Netbeans](https://netbeans.org) - An IDE with support for PHP and HTML5.
* [PhpStorm](http://www.jetbrains.com/phpstorm/) - A commercial PHP IDE.
* [VS Code](https://code.visualstudio.com/) - An open source code editor.

### Web Applications
*Web-based applications and tools.*

* [3V4L](https://3v4l.org/) - An online PHP & HHVM shell.
* [DBV](https://dbv.vizuina.com/) - A database version control application.
* [PHP Queue](https://github.com/CoderKungfu/php-queue) - An application for managing queueing backends. :star:590
* [MailCatcher](https://github.com/sj26/mailcatcher) - A web tool for capturing and viewing emails. :star:4218
* [Cachet](https://github.com/cachethq/cachet) - The open source status page system. :star:7655
* [phpBeanstalkdAdmin](https://github.com/mnapoli/phpBeanstalkdAdmin) - Monitoring and administration interface for Beanstalkd. :star:126
* [phpRedisAdmin](https://github.com/ErikDubbelboer/phpRedisAdmin) - A simple web interface to manage [Redis](https://redis.io/) databases. :star:1744
* [phpPgAdmin](https://github.com/phppgadmin/phppgadmin) - A web-based administration tool for PostgreSQL. :star:262
* [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) - A web interface for MySQL/MariaDB. :star:2873
* [Adminer](https://www.adminer.org/) - Database management in a single PHP file.
* [Grav](https://github.com/getgrav/grav) - A modern flat-file CMS. :star:8501
* [Lychee](https://github.com/electerious/Lychee) - An easy to use and great looking photo-management-system. :star:4163

### Infrastructure
*Infrastructure for providing PHP applications and services.*

* [appserver.io](https://appserver.io/) - A multithreaded application server for PHP, written in PHP.
* [php-pm](https://github.com/php-pm/php-pm) - A process manager, supercharger and load balancer for PHP applications. :star:4771

# Resources
Various resources, such as books, websites and articles, for improving your PHP development skills and knowledge.

### PHP Websites
*Useful PHP-related websites.*

* [Nomad PHP](https://nomadphp.com/) - A online PHP learning resource.
* [PHP Best Practices](https://phpbestpractices.org/) - A PHP best practice guide.
* [PHP FIG](http://www.php-fig.org/) - The PHP Framework Interoperability Group.
* [PHP Mentoring](https://php-mentoring.org/) - Peer to peer PHP mentorship organization.
* [PHP Package Development Standards](http://php-pds.com) - Package development standards for PHP.
* [PHP School](https://www.phpschool.io/) - Open Source Learning for PHP.
* [PHP Security](http://phpsecurity.readthedocs.io/en/latest/index.html) - A guide to PHP security.
* [PHP The Right Way](http://www.phptherightway.com/) - A PHP best practice quick reference guide.
* [PHP UG](http://php.ug) - A website to help people locate their nearest PHP user group (UG).
* [PHP Versions](http://phpversions.info/) - Lists which versions of PHP are available on several popular web hosts.
* [PHP Weekly](http://www.phpweekly.com/archive.html) - A weekly PHP newsletter.
* [PHPTrends](https://phptrends.com/) - An overview of fastest growing PHP libraries.
* [Securing PHP](http://securingphp.com/) - A newsletter about PHP security and library recommendations.
* [Seven PHP](https://7php.com/) - A website that interviews members of the PHP community.
* [PHP Annotated Monthly](https://blog.jetbrains.com/phpstorm/category/php-annotated-monthly/) - A monthly digest of PHP news.

### Other Websites
*Useful websites related to web development.*

* [Atlassian Git Tutorials](https://www.atlassian.com/git) - A series of Git tutorials.
* [Hg Init](http://hginit.com/) - A series of Mercurial tutorials.
* [Learning Linux](https://linuxjourney.com/) - A website for learning Linux.
* [Semantic Versioning](https://semver.org/) - A website explaining semantic versioning.
* [Servers for Hackers](https://serversforhackers.com/) - A newsletter about server management.
* [The Open Web Application Security Project (OWASP)](https://www.owasp.org/index.php/Main_Page) - An open software security community.
* [WebSec IO](https://websec.io/) - A web security community resource.

### PHP Books
*Fantastic PHP-related books.*

* [Functional Programming in PHP](https://www.functionalphp.com/) - This book will show you how to leverage these new PHP5.3+ features by understanding functional programming principles
* [Grumpy PHPUnit](https://leanpub.com/grumpy-phpunit) - A book about unit testing with PHPUnit by Chris Hartjes.
* [Mastering Object-Orientated PHP](https://www.brandonsavage.net/) - A book about object-orientated PHP by Brandon Savage.
* [Modern PHP New Features and Good Practices](http://shop.oreilly.com/product/0636920033868.do) - A book about new PHP features and best practices by Josh Lockhart.
* [Modernizing Legacy Applications in PHP](https://leanpub.com/mlaphp) - A book about modernizing legacy PHP applications by Paul M. Jones.
* [PHP 7 Upgrade Guide](https://leanpub.com/php7) - An ebook covering all of the features and changes in PHP 7 by Colin O'Dell.
* [PHP Pandas](https://daylerees.com/php-pandas/) - A book about learning to write PHP by Dayle Rees.
* [Scaling PHP Applications](http://www.scalingphpbook.com) - An ebook about scaling PHP applications by Steve Corona.
* [Securing PHP: Core Concepts](https://leanpub.com/securingphp-coreconcepts) - A book about common security terms and practices for PHP by Chris Cornutt.
* [Signaling PHP](https://leanpub.com/signalingphp) - A book about catching PCNTL signals in CLI scripts by Cal Evans.
* [The Grumpy Programmer's Guide to Building Testable PHP Applications](https://leanpub.com/grumpy-testing) - A book about building testing PHP applications by Chris Hartjes.
* [XML Parsing with PHP](https://www.phparch.com/books/xml-parsing-with-php/) - This book covers parsing and validating XML documents, leveraging XPath expressions, and working with namespaces as well as how to create and modify XML files programmatically.
* [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - Real examples written in PHP showcasing DDD Architectural Styles.

### Other Books
*Books related to general computing and web development.*

* [Elasticsearch: The Definitive Guide](https://www.elastic.co/guide/index.html) - A guide to working with Elasticsearch by Clinton Gormley and Zachary Tong.
* [Eloquent JavaScript](http://eloquentjavascript.net/) - A book about JavaScript programming by Marijn Haverbeke.
* [Head First Design Patterns](http://www.headfirstlabs.com/books/hfdp/) - A book that expains software design patterns.
* [Pro Git](https://git-scm.com/book/en/v2) - A book about Git by Scott Chacon and Ben Straub.
* [The Linux Command Line](http://linuxcommand.org/tlcl.php) - A book about the Linux command line by William Shotts.
* [The Tangled Web — Securing Web Applications](https://www.amazon.com/Tangled-Web-Securing-Modern-Applications/dp/1593273886) - A book about securing web applications by Michal Zalewski.
* [Understanding Computation](http://computationbook.com) - A book about computation theory by Tom Stuart.
* [Vagrant Cookbook](https://leanpub.com/vagrantcookbook) - A book about creating Vagrant environments by Erika Heidi.

### PHP Videos
*Fantastic PHP-related videos.*

* [Nomad PHP Lightning Talks](https://www.youtube.com/c/nomadphp) - 10 to 15 minute Lightning Talks by PHP community members.
* [PHP UK Conference](https://www.youtube.com/user/phpukconference/videos) - A collection of videos from the PHP UK Conference.
* [Programming with Anthony](https://www.youtube.com/playlist?list=PLM-218uGSX3DQ3KsB5NJnuOqPqc5CW2kW) - A video series by Anthony Ferrara.
* [Taking PHP Seriously](https://www.infoq.com/presentations/php-history) - A talk outlining PHP's strengths by Keith Adams of Facebook.

### PHP Podcasts
*Podcasts with a focus on PHP topics.*

* [PHP Town Hall](https://phptownhall.com/) - A casual PHP podcast by Ben Edmunds and Phil Sturgeon.
* [Voices of the ElePHPant](https://voicesoftheelephpant.com/) Interviews with the people that make the PHP community special.
* [PHP Roundtable](https://www.phproundtable.com/) - The PHP Roundtable is a casual gathering of developers discussing topics that PHP nerds care about.
* [Voices of the ElePHPant](https://voicesoftheelephpant.com/) - Interviews with members of PHP community.

### PHP Reading
*PHP-releated reading materials.*

* [Composer Primer](https://daylerees.com/composer-primer/) - A Composer primer.
* [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html) - An article about Composer stability flags.
* [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html) - An article about Composer versioning.
* [Create Your Own PHP Framework](http://fabien.potencier.org/create-your-own-framework-on-top-of-the-symfony2-components-part-1.html) - A series of articles on how to make your own PHP framework by Fabien Potencier.
* [Don't Worry About BREACH](https://blog.ircmaxell.com/2013/08/dont-worry-about-breach.html) - An article about the BREACH hack and CSRF tokens.
* [On PHP 5.3, Lambda Functions and Closures](http://fabien.potencier.org/on-php-5-3-lambda-functions-and-closures.html) - An article about lambda functions and closures.
* [PHP Is Much Better Than You Think](http://fabien.potencier.org/php-is-much-better-than-you-think.html) - An article about the PHP language and ecosystem.
* [PHP Package Checklist](http://phppackagechecklist.com/) - A checklist for successful PHP package development.
* [PHP Sucks! But I Like It!](https://blog.ircmaxell.com/2012/04/php-sucks-but-i-like-it.html) - An article about the pros and cons of PHP.
* [Preventing CSRF Attacks](https://blog.ircmaxell.com/2013/02/preventing-csrf-attacks.html) - An article on preventing CSRF attacks.
* [Seven Ways to Screw Up BCrypt](https://blog.ircmaxell.com/2012/12/seven-ways-to-screw-up-bcrypt.html) - An article about correct BCrypt implementation.
* [Use Env](https://seancoates.com/blogs/use-env/) - An article about using the unix environment helper.

### PHP Internals Reading
*Reading materials related to the PHP internals or performance.*

* [Disproving the Single Quotes Myth](http://nikic.github.io/2012/01/09/Disproving-the-Single-Quotes-Performance-Myth.html) - An article about performance of single and double quoted strings.
* [How Big Are PHP Arrays (And Values) Really?](http://nikic.github.io/2011/12/12/How-big-are-PHP-arrays-really-Hint-BIG.html) - An article about array internals.
* [How Foreach Works](https://stackoverflow.com/questions/10057671/how-does-php-foreach-actually-work/14854568#14854568) - A detailed StackOverflow answer about foreach.
* [How Long is a Piece of String](http://blog.golemon.com/2006/06/how-long-is-piece-of-string.html) - An article about string internals.
* [PHP Evaluation Order](https://gist.github.com/nikic/6699370) - An article about evaluation order in PHP.
* [PHP Internals Book](http://www.phpinternalsbook.com) - An online book about PHP internals, written by three core developers.
* [PHP RFCs](https://wiki.php.net/rfc) - The home of PHP RFCs (Request for Comments).
* [Print vs Echo, Which One is Faster?](http://fabien.potencier.org/print-vs-echo-which-one-is-faster.html) - An article about print and echo performance.
* [The PHP Ternary Operator. Fast or Not?](http://fabien.potencier.org/the-php-ternary-operator-fast-or-not.html) - An article ternary performance.
* [Understanding OpCodes](http://blog.golemon.com/2008/01/understanding-opcodes.html) - An article about opcodes.
* [When Does Foreach Copy?](http://nikic.github.io/2011/11/11/PHP-Internals-When-does-foreach-copy.html) - An article about the internals of foreach.
* [Why Objects (Usually) Use Less Memory Than Arrays](https://gist.github.com/nikic/5015323) - An article about object and array internals.
* [You're Being Lied To](http://blog.golemon.com/2007/01/youre-being-lied-to.html) - An article about internal ZVALs.
* Collecting Garbage: [1](http://php.net/manual/en/features.gc.refcounting-basics.php) [2](http://php.net/manual/en/features.gc.collecting-cycles.php) [3](http://php.net/manual/en/features.gc.performance-considerations.php) - A series about the PHP garbage collection internals.
* PHP Source Code for Developers: [1](https://blog.ircmaxell.com/2012/03/phps-source-code-for-php-developers.html) [2](http://nikic.github.io/2012/03/16/Understanding-PHPs-internal-function-definitions.html) [3](https://blog.ircmaxell.com/2012/03/phps-source-code-for-php-developers_21.html) [4](http://nikic.github.io/2012/03/28/Understanding-PHPs-internal-array-implementation.html) - A series about the PHP source code.

### PHP Magazines
*Fantastic PHP-related magazines.*

* [php[architect]](https://www.phparch.com/magazine/) - A monthly magazine dedicated to PHP.


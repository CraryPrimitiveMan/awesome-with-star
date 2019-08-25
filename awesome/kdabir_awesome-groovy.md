# Information comes from [kdabir/awesome-groovy](https://github.com/kdabir/awesome-groovy)
Awesome Groovy [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
==============

Curated list of awesome groovy libraries, frameworks and resources. Inspired by many other awesome-* repositories. This awesome collection is also available on [Groovy.ZEEF.com](https://groovy.zeef.com/kunal.dabir).


- [Awesome Groovy](#awesome-groovy)
    - [Build Tools, Setup and CI](#build-tools-setup-and-ci)
    - [Concurrency](#concurrency)
    - [Database](#database)
    - [Desktop App Frameworks](#rich-applications)
    - [HTTP](#http)
    - [IDE and Editor Support](#ide-and-editor-support)
    - [Testing](#testing)
    - [Code analysis](#code-analysis)
    - [Web Frameworks](#web-frameworks)
    - [Transpilers](#transpilers)
    - [Static Web](#static-web)
    - [Language Utilities](#language-utilities)
    - [File System Utilities](#file-system-utilities)
    - [File Format DSL](#file-format-dsl)
    - [Scripting Tools](#scripting-tools)
    - [Rule Engines](#rule-engines)
- [Resources](#resources)
- [Contributing](#contributing)
- [Credits](#credits)

## Build tools, setup and CI
* [Gradle](https://www.gradle.org/) - A powerful build system for the JVM
* [GMavenPlus](https://github.com/groovy/GMavenPlus) - A rewrite of GMaven, a Maven plugin for Groovy :star:181
* [SDKMAN](https://sdkman.io) - The Software Development Kit Manager (Previously known as GVM)
* [Lazybones](https://github.com/pledbrook/lazybones) - A simple project creation tool that uses packaged project templates. :star:573
* [Jenkins job-dsl-plugin](https://github.com/jenkinsci/job-dsl-plugin) - A Groovy DSL for Jenkins Jobs :star:1538
* [travis-groovy](https://github.com/kdabir/travis-groovy) - execute groovy scripts on travis-ci :star:3

## IDE and Editor Support
* [IntelliJ IDEA](http://www.jetbrains.com/idea/) - The Most Intelligent IDE for the Java Platform
* [Groovy Grails Tool Suite](https://marketplace.eclipse.org/content/groovygrails-tool-suite-ggts-eclipse) -  Eclipse-based IDE optimized for developing, debugging and executing Groovy and Grails applications
* [Groovy Web Console](http://groovyconsole.appspot.com) - The online Groovy console
* [LightTable Plugin](https://github.com/rundis/LightTable-Groovy) - LightTable Support :star:27
* [Sublime Text 2/3](https://gist.github.com/kdabir/2203530) - Run groovy scripts from Sublime Text

## Web Frameworks

* [Grails](https://github.com/grails/grails) - A powerful web application framework based on the Groovy language :star:456
* [Gaelyk](https://github.com/gaelyk/gaelyk) - A lightweight Groovy toolkit for Google App Engine Java :star:230
* [Glide](https://github.com/kdabir/glide) - Create awesome apps on Google App Engine in a snap :star:47
* [Ratpack](https://github.com/ratpack/ratpack) - A toolkit for JVM web applications :star:1813
* [gServ](https://github.com/javaConductor/gserv) - A Groovy toolkit for creating SPAs and REST based micro-services without the need for a container (Tomcat, JBoss, etc.). :star:45
* [Spring-Boot](https://projects.spring.io/spring-boot) - Spring Boot makes it easy to create stand-alone, production-grade Spring based Applications that can you can "just run"
* [Micronaut](http://micronaut.io/) - A brand new microservices framework created by the Grails team

## Database
* [Gmongo](https://github.com/poiati/gmongo) - A Groovy wrapper to the mongodb Java driver :star:179
* [Gstorm](https://github.com/kdabir/gstorm) - A simple ORM for simple databases and CSV files to be used in groovy scripts :star:73
* [Tayra](https://github.com/EqualExperts/Tayra) - Incremental backup tool for MongoDB :star:142
* [Groovy-liquibase](https://github.com/tlberglund/groovy-liquibase) - Yet Another Groovy DSL for Liquibase :star:85
* [Effigy](https://github.com/cjstehno/effigy) - Groovy annotation-driven JDBC row mapping framework (abandoned) :star:6
* [elasticsearch-groovy](https://github.com/elastic/elasticsearch-groovy) - Elasticsearch Groovy client :star:40

## Rich Application

* [Griffon](http://griffon-framework.org/) - Griffon is an application framework for developing desktop applications in the JVM
* [GroovyFx](http://groovyfx.org/) - GroovyFX provides a Groovy binding for JavaFX 2.0.

## HTTP
* [Http-Builder](https://github.com/jgritman/httpbuilder) - HTTPBuilder is the easiest way to manipulate HTTP-based resources from the JVM :star:279
* [HTTP Builder NG](https://github.com/http-builder-ng/http-builder-ng) - HTTP Builder NG is a modern Groovy DSL for making http requests. :star:144
* [HTTP Builder NG Gradle Plugin](https://github.com/http-builder-ng/gradle-http-plugin) - Gradle plugin providing HTTP Builder NG support in a Gradle build configuration. :star:16
* [AsyncRestClient](https://github.com/eginez/AsyncRestClient) - Combine the power of RESTClient with RxGroovy for async http calls :star:4
* [Groovy-wslite](https://github.com/jwagenleitner/groovy-wslite) - Lightweight SOAP and REST webservice clients for Groovy :star:375

## Testing
* [Spock](https://github.com/spockframework/spock) - The Enterprise-ready testing and specification framework. :star:2430
* [Geb](https://github.com/geb/geb) - Very Groovy Browser Automation :star:973
* [Betamax](https://github.com/betamaxteam/betamax) - Betamax is a tool for mocking external HTTP resources such as web services and REST APIs in your tests. :star:443
* [HTTP Mock Server](https://github.com/TouK/http-mock-server) - HTTP Mock Server allows to mock HTTP request using groovy closures. :star:10
* [Ersatz Mock Server](https://github.com/cjstehno/ersatz) - A simple and expressive simulated HTTP server for testing client code with configurable responses. :star:34
* [Dru](https://agorapulse.github.io/dru/) - Data Reconstruction Utility loads data from external sources JSON, YML for easy testing GORM, DynamoDB or just plain POJOs.
* [Gru](https://agorapulse.github.io/gru/) - Groovy HTTP Testing Framework for running integration and semi-ingetration tests for any HTTP backend with native unit test support for Grails and Spring MVC.

## Concurrency
* [GPars](https://github.com/GPars/GPars) - The GPars concurrency and parallelism framework for the JVM :star:209
* [RxGroovy](https://github.com/ReactiveX/RxGroovy) - RxJava bindings for Groovy :star:144
* [Vertx](https://vertx.io/) - Vert.x is a lightweight, high performance application platform for the JVM

## Code Analysis
* [CodeNarc](http://codenarc.sourceforge.net/) - Static analysis tool for Groovy
* [Sonar-Groovy](https://github.com/pmayweg/sonar-groovy) - SonarQube Groovy plugin :star:47

## Transpilers
* [Grooscript](https://github.com/chiquitinxx/grooscript) - Converts your Groovy code to Javascript :star:206

## Static Web
* [Grain](https://github.com/sysgears/grain) - Static Web Site Building Framework For Groovy :star:146
* [Gaiden](https://github.com/kobo/gaiden) - Gaiden is a tool that makes it easy to create documentation with Markdown. :star:148

## Language Utilities
* [Functionalgroovy](https://github.com/mperry/functionalgroovy) - Functional programming in Groovy :star:62
* [Groovy-stream](https://github.com/timyates/groovy-stream) - A collection of classes to give a fluent builder for Streams (Lazy Groovy Generators) :star:67
* [Flipside](https://github.com/johnnywey/flipside) - Simple Groovy options library :star:23
* [groovy-common-extensions](https://github.com/timyates/groovy-common-extensions) - Lets you add things commonly useful to the Groovy language via the extension system :star:69
* [groovy-extra-list-behaviour](https://github.com/dnahodil/groovy-extra-list-behaviour) - Adds extra methods to Lists via the extension system :star:1
* [GPerfUtils](https://github.com/gperfutils) - Groovy-based tools verifying performance of your code
  * [gprof](https://github.com/gperfutils/gprof) - The profiling module for Groovy :star:30
  * [gbench](https://github.com/gperfutils/gbench) - The benchmarking module for Groovy :star:27
* [Fuzzy-CSV](https://github.com/kayr/fuzzy-csv) - Simple lightweight data processing library, useful for shaping/processing your tabular data before its consumed by another service or library. :star:4

## File System Utilities
* [Groovy-Vfs](https://github.com/ysb33r/groovy-vfs) - A DSL for Groovy on top of Apache VFS2 :star:60
* [Directree](https://github.com/kdabir/directree) - A Simple DSL to create Directory Tree with Text Files :star:11

## File Format DSL
* [document-builder](https://github.com/craigburke/document-builder) - A document builder for Groovy for PDF or Word documents. :star:89
* [spreadsheet-builder](http://spreadsheet.dsl.builders/) - Spreadsheet builder provides convenient way how to create MS Excel OfficeOpenXML Documents (XSLX)
* [GroovyCSV](http://xlson.com/groovycsv/) - A simple CSV parsing library for groovy

## Scripting Tools
* [EasyDokkaPlugin](https://github.com/Vorlonsoft/EasyDokkaPlugin) - Gradle script plugin to generate documentation by Dokka documentation engine for Java and Kotlin :star:7
* [GradleMavenPush](https://github.com/Vorlonsoft/GradleMavenPush) - Gradle script plugin to upload Gradle Artifacts to Maven repositories :star:15
* [picocli](https://github.com/remkop/picocli) - Parser library and framework for CLI. Usage help with ANSI colors. Autocomplete. Nested subcommands and more. :star:1419
* [sshoogr](https://github.com/aestasit/sshoogr) - DSL library for working with remote servers through SSH. :star:304


## Rule Engines
* [grules](https://github.com/zhaber/grules) - rule engine for data preprocessing :star:34
* [n-cube](https://github.com/jdereg/n-cube) - a Rules Engine, Decision Table, Decision Tree, Templating Engine, and Enterprise Spreadsheet, built as a hyper-space. :star:129

# Resources

## Official Resources
* [The official groovy home](http://www.groovy-lang.org/) - Groovy's new home
* [Groovy's source](https://github.com/apache/groovy) - Groovy's source code mirrored on Github :star:3350
* [Groovy mailing lists](http://www.groovy-lang.org/mailing-lists.html) - Note the new mailing list
* [Official Documentation](http://www.groovy-lang.org/documentation.html) - the definitive source of groovy documentation

## Try Groovy in Browser
* [Groovy Web Console](http://groovyconsole.appspot.com/)
* [Groovy Playground](https://groovy-playground.appspot.com/)

## Groovy Code Examples
* [MrHaKi's Goodness](http://mrhaki.blogspot.com/) - Look out for entries titled "Groovy Goodness" , "Grails Goodness", Gradle Goodness"
* [PLEAC Groovy](http://pleac.sourceforge.net/pleac_groovy/) - Groovy is one of the 3 languages out of 32, having completed 100% of PLEAC examples.

## Staying up to date
* [Groovy Calamari](http://groovycalamari.com/) - Weekly curated publication about the Groovy Ecosystem
* [Groovy Weekly](http://glaforge.appspot.com/category/Groovy%20Weekly) - Groovy weekly newsletter
* [Grails Diary](https://grydeske.dk/news/index) - Particulary useful for Grails developers
* [Groovy Podcast](https://nofluffjuststuff.com/groovypodcast) - Ken Kousen and Baruch Sadogursky discuss news and insight from the Groovy ecosystem.

## Interactive Learning
* [Groovy-Koans](http://nadavc.github.io/groovykoans/) - Collection of small exercises in the form of unit tests

## Blogs of core committer
* [Guillaume Laforge's blog](http://glaforge.appspot.com/)
* [Cédric Champeau's blog](http://melix.github.io/blog/)
* [Jochen Theodorou's blog](http://blackdragsview.blogspot.com/)
* [Grails Team blog](http://grailsblog.objectcomputing.com/)

## Conferences
* [Greachconf](http://greachconf.com)
* [GR8Conf Europe](https://gr8conf.eu)
* [GR8Conf USA](http://gr8conf.us)

# Contributing

Fork this repository, edit this file and send a pull request.

## Using awesome.groovy script

You can use the `awesome.groovy` script to search awesome projects on github and generate the entry prepoulated with project name, repo url and description in markdown format. All you need to do is place it under right group in the markdown list in `README.md`.

### Examples

to find out repos where language is groovy and whose name contain gpars and

    ./awesome.groovy -l groovy gpars

to find out repos by user 'kdabir' and name contains glide

    ./awesome.groovy -u kdabir glide

to find out repos whose name contains glide

    ./awesome.groovy glide

If you are lazy to download the repo, an easy way is:

    groovy "https://git.io/awesome" -l groovy glide

# Credits

To all the awesome-* repos out there and their aggreators like [this](https://github.com/erichs/awesome-awesome) and [this](https://github.com/bayandin/awesome-awesomeness).


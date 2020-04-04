# Information comes from [veelenga/awesome-crystal](https://github.com/veelenga/awesome-crystal)
<p align="center"><img src="logo/logotype_horizontal.png" alt="awesome-crystal"></p>

# Awesome Crystal
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Build Status](https://api.travis-ci.org/veelenga/awesome-crystal.svg)](https://travis-ci.org/veelenga/awesome-crystal)

A curated list of awesome Crystal code and resources. Inspired by [awesome](https://github.com/sindresorhus/awesome) and [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).
The goal is to have projects mostly stable and useful for the community.

Search [Crystal Shards](https://crystalshards.xyz) or follow announcements [Crystal [ANN]](https://crystal-ann.com) for more.

Contributions are welcome. Please take a quick look at the [contribution guidelines](https://github.com/veelenga/awesome-crystal/blob/master/.github/CONTRIBUTING.md) first.

* [Awesome Crystal](#awesome-crystal)
  * [Algorithms and Data structures](#algorithms-and-data-structures)
  * [Api Builders](#api-builders)
  * [Blockchain](#blockchain)
  * [C Bindings](#c-bindings)
  * [Caching](#caching)
  * [CLI Builders](#cli-builders)
  * [CLI Utils](#cli-utils)
  * [Code Analysis and Metrics](#code-analysis-and-metrics)
  * [Compression](#compression)
  * [Configuration](#configuration)
  * [Converters](#converters)
  * [Cryptography](#cryptography)
  * [Data Formats](#data-formats)
  * [Data Generators](#data-generators)
  * [Database Drivers/Clients](#database-driversclients)
  * [Database Tools](#database-tools)
  * [Debugging](#debugging)
  * [Dependency Injection](#dependency-injection)
  * [Development Tools](#development-tools)
  * [Email](#email)
  * [Environment Management](#environment-management)
  * [Examples and funny stuff](#examples-and-funny-stuff)
  * [Feature Flipping](#feature-flipping)
  * [Framework Components](#framework-components)
  * [Game Development](#game-development)
  * [HTML Builders](#html-builders)
  * [HTML/XML parsing](#htmlxml-parsing)
  * [HTTP](#http)
  * [Image Processing](#image-processing)
  * [Implementations/Compilers](#implementationscompilers)
  * [Logging and monitoring](#logging-and-monitoring)
  * [Machine Learning](#machine-learning)
  * [Markdown/Text Processors](#markdowntext-processors)
  * [Misc](#misc)
  * [Network Protocols](#network-protocols)
  * [Networking](#networking)
  * [ORM/ODM Extensions](#ormodm-extensions)
  * [Package Management](#package-management)
  * [Processes and Threads](#processes-and-threads)
  * [Project Generators](#project-generators)
  * [Queues and Messaging](#queues-and-messaging)
  * [Routing](#routing)
  * [Scheduling](#scheduling)
  * [Science and Data analysis](#science-and-data-analysis)
  * [Search](#search)
  * [Serverless Computing](#serverless-computing)
  * [System](#system)
  * [Task management](#task-management)
  * [Template Engine](#template-engine)
  * [Testing](#testing)
  * [Third-party APIs](#third-party-apis)
  * [Validation](#validation)
  * [Web Frameworks](#web-frameworks)
  * [Web Servers](#web-servers)
* [Community](#community)
  * [Unofficial](#unofficial)
* [Resources](#resources)
  * [Official Documentation Translations](#official-documentation-translations)
* [Services and Apps](#services-and-apps)
* [Tools](#tools)
  * [DevOps](#devops)
  * [Editor Plugins](#editor-plugins)
  * [Shell Plugins](#shell-plugins)

## Algorithms and Data structures
 * [bisect](https://github.com/spider-gazelle/bisect) - Inserting values into a sorted array :star:7
 * [crie](https://github.com/c910335/crie) - Compile-time Trie :star:7
 * [CrOTP](https://github.com/philnash/crotp) - HOTP and TOTP implementation for two factor authentication :star:42
 * [crystal-diff](https://github.com/MakeNowJust/crystal-diff) - A Crystal sequence differencing implementation :star:29
 * [crystal-linked-list](https://github.com/abvdasker/crystal-linked-list) - Implementation of Linked List :star:9
 * [crystaledge](https://github.com/unn4m3d/crystaledge) - A pure Vector Math library :star:19
 * [crystalg](https://github.com/TobiasGSmollett/crystalg) - A Generic Algorithm Library :star:19
 * [crystalline](https://github.com/jtomschroeder/crystalline) - A collection of containers and algorithms :star:107
 * [edits.cr](https://github.com/tcrouch/edits.cr) - Collection of edit distance algorithms :star:13
 * [fzy](https://github.com/hugopl/fzy) - A Crystal port of awesome Fzy project fuzzy finder algorithm :star:14
 * [graphlb](https://github.com/mettuaditya/graphlb) - Collection of graph datastructure and algorithms :star:10
 * [hash_ring](https://github.com/TobiasGSmollett/hash_ring) - An Implementation of Consistent Hash Ring :star:7
 * [haversine](https://github.com/geocrystal/haversine) - An Implementation of the Haversine formula :star:9
 * [kd_tree](https://github.com/geocrystal/kd_tree) - An implementation of "K-Dimensional Tree" and "N-Nearest Neighbors" :star:8
 * [ksuid.cr](https://github.com/Sija/ksuid.cr) - K-Sortable Globally Unique IDs :star:9
 * [markov](https://github.com/mccallofthewild/markov) - Build Markov Chains and run Markov Processes :star:16
 * [multiset.cr](https://github.com/tcrouch/multiset.cr) - Implementation of a multiset :star:2
 * [oak](https://github.com/obsidian/oak) - A flexible Radix Tree implementation :star:9
 * [radix](https://github.com/luislavena/radix) - Radix Tree implementation :star:78
 * [ternary_search_tree](https://github.com/johnjansen/ternary_search_tree) - Ternary Search Tree :star:3

## Api Builders
 * [kemal-rest-api](https://github.com/blocknotes/kemal-rest-api) - A library to create RESTful API with Kemal :star:50

## Blockchain
 * [Cocol](https://github.com/cocol-project/cocol) - A minimal blockchain testbed :star:17
 * [secp256k1.cr](https://github.com/q9f/secp256k1.cr) - Elliptic curve used in the public-private-key cryptography :star:15
 * [SushiChain](https://github.com/SushiChain/SushiChain) - A custom blockchain platform :star:169

## C bindings
 * [asound-cr](https://github.com/TamasSzekeres/asound-cr) - Bindings for ALSA/libasound :star:5
 * [cairo-cr](https://github.com/TamasSzekeres/cairo-cr) - Bindings for [Cairo](https://cairographics.org/) graphics library :star:18
 * [clang.cr](https://github.com/crystal-lang/clang.cr) - Libclang bindings :star:28
 * [crt.cr](https://github.com/maiha/crt.cr) - Bindings for libncursesw and crt :star:25
 * [crystal-gsl](https://github.com/ruivieira/crystal-gsl) - GNU Scientific Library bindings :star:13
 * [crystal-hunspell](https://github.com/mamantoha/crystal-hunspell) - Bindings for [Hunspell](https://hunspell.github.io/)
 * [curl-crystal](https://github.com/blocknotes/curl-crystal) - Bindings for [libcurl](https://curl.haxx.se/libcurl/)
 * [duktape.cr](https://github.com/jessedoyle/duktape.cr) - Bindings for the [Duktape](https://github.com/svaarala/duktape) javascript engine :star:98
 * [gphoto2.cr](https://github.com/Sija/gphoto2.cr) - Bindings for the [libgphoto2](http://www.gphoto.org/) library :star:12
 * [icu.cr](https://github.com/olbat/icu.cr) - Bindings for the [ICU](http://site.icu-project.org/) library :star:7
 * [libnotify.cr](https://github.com/splattael/libnotify.cr) - Bindings for Libnotify :star:20
 * [pcap.cr](https://github.com/maiha/pcap.cr) - Bindings for libpcap :star:19
 * [pledge.cr](https://github.com/chris-huxtable/pledge.cr) - Bindings for OpenBSD's `pledge(2)` :star:4
 * [soundfile](https://github.com/mjago/soundfile) - Bindings for [libsndfile](http://www.mega-nerd.com/libsndfile/) library :star:5
 * [ssh2.cr](https://github.com/spider-gazelle/ssh2.cr) - Bindings for libssh2 library :star:14
 * [syslog.cr](https://github.com/chris-huxtable/syslog.cr) - Bindings for `syslog` :star:7
 * [x11-cr](https://github.com/TamasSzekeres/x11-cr) - X11 bindings :star:25
 * [x_do.cr](https://github.com/woodruffw/x_do.cr) - Bindings for libxdo ([`xdotool`](https://github.com/jordansissel/xdotool)) :star:1184

## Caching
 * [bloom_filter](https://github.com/crystal-community/bloom_filter) - Implementation of Bloom filter :star:31
 * [bojack](https://github.com/marceloboeira/bojack) - A non-reliable in-memory key-value store :star:99
 * [crystal-memcached](https://github.com/comandeo/crystal-memcached) - Implementation of a memcached client :star:26
 * [Nuummite](https://github.com/CodeSteak/Nuummite) - A tiny persistent embedded key-value store :star:25

## CLI Builders
 * [admiral](https://github.com/jwaldrip/admiral.cr) - A robust DSL for writing command line interfaces :star:97
 * [cli](https://github.com/mosop/cli) - Library for building command-line interface applications :star:91
 * [clicr](https://github.com/j8r/clicr) -  A simple declarative command line interface builder :star:23
 * [clim](https://github.com/at-grandpa/clim) - Slim command line interface builder :star:77
 * [commander](https://github.com/mrrooijen/commander) - Command-line interface builder :star:95
 * [optarg](https://github.com/mosop/optarg) - Yet another library for parsing command-line options and arguments :star:22
 * [OptionParser](https://crystal-lang.org/api/OptionParser.html) - command-line options processing (Crystal stdlib)
 * [Phreak](https://github.com/shinzlet/phreak) - A highly flexible Crystal CLI builder in the style of OptionParser :star:19

## CLI Utils
 * [cride](https://github.com/j8r/cride) - A light CLI text editor/IDE :star:32
 * [oq](https://github.com/Blacksmoke16/oq) - A performant, and portable jq wrapper to facilitate the consumption and output of formats other than JSON; using [jq](https://github.com/stedolan/jq) filters to transform the data. :star:75
 * [progress_bar.cr](https://github.com/TPei/progress_bar.cr) - A simple and customizable progress bar :star:9
 * [tablo](https://github.com/hutou/tablo) - A flexible terminal table generator :star:13
 * [tallboy](https://github.com/epoch/tallboy) - Generate ASCII character tables with support for spanning cells over multiple columns :star:22
 * [terminal_table.cr](https://github.com/benoist/terminal_table.cr) - Simple ASCII table generator :star:21
 * [terminimal](https://github.com/aca-labs/terminimal) - A tiny CLI toolkit for building terminal apps for humans :star:8
 * [todo](https://git.sceptique.eu/Sceptique/todo) - Todo list working in command line

## Code Analysis and Metrics
 * [ameba](https://github.com/crystal-ameba/ameba) - A static code analysis tool :star:275

## Compression
 * [Crystar](https://github.com/naqvis/crystar) - Readers and writers of Tar archive format :star:20
 * [Gzip](https://crystal-lang.org/api/Gzip.html) - readers and writers of gzip format (Crystal stdlib)
 * [snappy](https://github.com/naqvis/snappy) -  Snappy compression format reader/writer for Crystal :star:10
 * [Zip](https://crystal-lang.org/api/Zip.html) - readers and writers of zip format (Crystal stdlib)
 * [Zlib](https://crystal-lang.org/api/Zlib.html) - readers and writers of zlib format (Crystal stdlib)
 * [zstd.cr](https://github.com/didactic-drunk/zstd.cr) - Bindings for [Zstandard](https://github.com/facebook/zstd) compression library :star:13

## Configuration
 * [cr-dotenv](https://github.com/gdotdesign/cr-dotenv) - Loads .env file :star:69
 * [envyable](https://github.com/philnash/envyable.cr) -  A simple YAML to ENV config loader :star:4
 * [habitat](https://github.com/luckyframework/habitat) - Type safe configuration for your classes and modules :star:49
 * [totem](https://github.com/icyleaf/totem) - Load and parse a configuration in JSON, YAML, dotenv formats :star:39

## Converters
 * [base62.cr](https://github.com/Sija/base62.cr) - Base62 encoder/decoder, well suited for url-shortening :star:7
 * [money](https://github.com/crystal-money/money) - Handling money and currency conversion with ease (almost complete port of [RubyMoney](https://github.com/RubyMoney/money)) :star:2259
 * [ms](https://github.com/SuperPaintman/ms) - Library to easily convert various time formats to milliseconds and milliseconds to human readable format :star:14
 * [sass.cr](https://github.com/straight-shoota/sass.cr) - Compile SASS/SCSS to CSS ([libsass](https://github.com/sass/libsass/) binding) :star:4105
 * [time_format.cr](https://github.com/vladfaust/time_format.cr) - Convert time in human readable format with ease :star:3
 * [turkish-number](https://github.com/izniburak/turkish-number) - Turn integers into the Turkish words :star:7
 * [wkhtmltopdf-crystal](https://github.com/blocknotes/wkhtmltopdf-crystal) - Bindings / wrapper for libwkhtmltox (HTML to PDF / image converter) :star:16

## Cryptography
 * [cmac](https://github.com/spider-gazelle/cmac) - Crystal implementation of Cipher-based Message Authentication Code (CMAC) :star:2
 * [openssl.cr](https://github.com/z64/openssl.cr) - This library provides binding for OpenSSL library
 * [sodium.cr](https://github.com/didactic-drunk/sodium.cr) - Crystal wrapper for the libsodium crypto API :star:13

## Data Formats
 * [BinData](https://github.com/spider-gazelle/bindata) - Binary data parser helper with an [ASN.1](https://en.wikipedia.org/wiki/Abstract_Syntax_Notation_One) parser :star:23
 * [config.cr](https://github.com/chris-huxtable/config.cr) - Easy to use configuration format parser :star:7
 * [crinder](https://github.com/c910335/crinder) - Class based json renderer :star:22
 * [CSV](https://crystal-lang.org/api/CSV.html) - parsing and generating for comma-separated values (Crystal stdlib)
 * [front_matter.cr](https://github.com/chris-huxtable/front_matter.cr) - Separates a files front matter from its content :star:2
 * [geoip2.cr](https://github.com/delef/geoip2.cr) - GeoIP2 reader :star:10
 * [HAR](https://github.com/NeuraLegion/har) - HAR (HTTP Archive) parser :star:15
 * [INI](https://crystal-lang.org/api/INI.html) - INI file parser (Crystal stdlib)
 * [JSON](https://crystal-lang.org/api/JSON.html) - parsing and generating JSON documents (Crystal stdlib)
 * [JSON tools](https://github.com/impatienttraveller/json-tools) - An implementation of JSON Patch and Pointer RFC's :star:14
 * [JSON::OnSteroids](https://github.com/anykeyh/json_on_steroids) - handle and mutate JSON document easily :star:10
 * [maxminddb.cr](https://github.com/delef/maxminddb.cr) - MaxMindDB reader :star:19
 * [toml.cr](https://github.com/crystal-community/toml.cr) - TOML parser :star:40
 * [XML](https://crystal-lang.org/api/XML.html) - parsing and generating XML documents (Crystal stdlib)
 * [YAML](https://crystal-lang.org/api/YAML.html) - parsing and generating YAML documents (Crystal stdlib)

## Data Generators
 * [faker](https://github.com/askn/faker) - A library for generating fake data :star:119
 * [hashids.cr](https://github.com/splattael/hashids.cr) - A library to generate YouTube-like ids from one or many numbers :star:33
 * [prime](https://github.com/wontruefree/prime) - A prime number generator :star:1

## Database Drivers/Clients
 * [couchdb.cr](https://github.com/TechMagister/couchdb.cr) - CouchDB client :star:11
 * [crystal-db](https://github.com/crystal-lang/crystal-db) - Common db api :star:183
 * [crystal-mysql](https://github.com/crystal-lang/crystal-mysql) - MySQL connector for Crystal :star:78
 * [crystal-pg](https://github.com/will/crystal-pg) - A Postgres driver :star:337
 * [crystal-redis](https://github.com/stefanwille/crystal-redis) - Full featured Redis client :star:316
 * [crystal-rethinkdb](https://github.com/kingsleyh/crystal-rethinkdb) - Driver for RethinkDB / RebirthDB :star:12
 * [crystal-sqlite3](https://github.com/crystal-lang/crystal-sqlite3) - SQLite3 bindings :star:81
 * [eventql-crystal](https://github.com/measurechina/eventql-crystal) - EventQL driver :star:7
 * [leveldb](https://github.com/crystal-community/leveldb) - Crystal bindings for LevelDB :star:30
 * [mongo.cr](https://github.com/ambercommunity/mongo.cr) - Binding for MongoDB C driver :star:8
 * [rocksdb.cr](https://github.com/maiha/rocksdb.cr) - RocksDB client :star:29

## Database Tools
 * [migrate](https://github.com/vladfaust/migrate.cr) - A simpler database migration tool with transactions :star:24
 * [queryit](https://github.com/hugopl/queryit) - A setupless terminal based SQL query runner. :star:8

## Debugging
 * [debug.cr](https://github.com/Sija/debug.cr) - `debug!(…)` macro for `pp`-style debugging :star:61

## Dependency Injection
 * [Crystal-DI](https://github.com/funk-yourself/crystal-di) - Lightweight DI Container :star:28
 * [HardWire](https://github.com/jerometwell/hardwire) - A compile-time non-intrusive dependency injection system. :star:12
 * [syringe](https://github.com/Bonemind/syringe) - A simple and basic dependency injection shard for crystal :star:4

## Development Tools
 * [kemal-watcher](https://github.com/faustinoaq/kemal-watcher) - Kemal plugin to watch files and live-reload the browser :star:18
 * [sentry-run](https://github.com/faustinoaq/sentry-run) - Reload code changes using Sentry.run :star:11
 * [Warden](https://github.com/diggersheep/warden) - Watches files, run command and a git command if succeed on file changes :star:10
 * [watcher](https://github.com/faustinoaq/watcher) - Watch file changes using File.stat :star:19

## Email
 * [carbon](https://github.com/luckyframework/carbon) - Fun, testable, and adapter-based email library :star:55
 * [crystal-email](https://github.com/arcage/crystal-email) - Simple e-mail sending library :star:78
 * [CrystalEmail](https://git.sceptique.eu/Sceptique/CrystalEmail) - A RFC compliant Email validator
 * [sendgrid.cr](https://github.com/dlanileonardo/sendgrid.cr) - Simple Sendgrid Client :star:7

## Environment Management
 * [asdf-crystal](https://github.com/marciogm/asdf-crystal) - Plugin for asdf version manager :star:26
 * [crenv](https://github.com/pine/crenv) - Crystal version manager :star:219
 * [rcm.cr](https://github.com/maiha/rcm.cr) - Redis Cluster Manager :star:41

## Examples and funny stuff
 * [blackjack-cr](https://github.com/gdonald/blackjack-cr) - Console Blackjack :star:3
 * [clamp](https://github.com/johnjansen/clamp) - Clamp any Comparable :star:1
 * [crystal-patterns](https://github.com/crystal-community/crystal-patterns) - Examples of GOF patters :star:201
 * [crystalworld](https://github.com/vladfaust/crystalworld) - [realworld.io](https://realworld.io) back-end API implementation :star:33
 * [exercism-crystal](https://github.com/exercism/crystal) - Exercism exercises :star:58
 * [try.cr](https://github.com/maiha/try.cr) - Try monad :star:23

## Feature Flipping
 * [can_use](https://github.com/rodrigopinto/can_use) - It is a minimalist feature toggle/flag for crystal based on yaml :star:7
 * [flipper](https://github.com/metaware/flipper) - Feature flipping/flags/rollouts. Supports multiple backends :star:18

## Framework Components
 * [device_detector](https://github.com/creadone/device_detector) - Shard for detect device by user agent string :star:13
 * [Exception Page](https://github.com/crystal-loot/exception_page) - An exceptional exception page for Crystal web libraries and frameworks :star:44
 * [graphql-crystal](https://github.com/ziprandom/graphql-crystal) - [Graphql](http://graphql.org) implementation :star:192
 * [kave](https://github.com/jwoertink/kave) - Kemal API Version Extension :star:30
 * [kemal-session](https://github.com/kemalcr/kemal-session) - Session handler for Kemal :star:41
 * [mochi](https://github.com/gitlato/mochi) - Authentication shard inspired by Devise supporting: Authenticable, Confirmable, Invitable & more :star:13
 * [multi-auth](https://github.com/msa7/multi_auth) - Standardized multi-provider OAuth2 authentication (inspired by omniauth) :star:75
 * [praetorian](https://github.com/ilanusse/praetorian) - Minimalist authorization library inspired by Pundit :star:47
 * [request_id](https://github.com/SuperPaintman/request-id) - Middleware for generates / pick up a unique request ID for Crystal servers :star:6
 * [response_time](https://github.com/SuperPaintman/response-time) - Response time for Crystal servers (pure http server, kemal, etc.) :star:8
 * [shrine.cr](https://github.com/jetrockets/shrine.cr) - File Attachment toolkit for Crystal applications. Heavily inspired by Shrine for Ruby :star:46
 * [tourmaline](https://github.com/watzon/tourmaline) - Telegram bot framework with an API loosely based on [telegraf.js](https://telegraf.js.org/)

## Game Development
 * [CrSFML](https://github.com/oprypin/crsfml) - Bindings to [SFML](https://www.sfml-dev.org/) multimedia/game library :star:237
 * [crystal-chipmunk](https://github.com/oprypin/crystal-chipmunk) - Bindings for [Chipmunk](http://chipmunk-physics.net/), a fast and lightweight 2D game physics library :star:31
 * [glove](https://github.com/ddfreyne/glove) - A library for gaming development :star:67

## HTML Builders
 * [form_builder.cr](https://github.com/westonganger/form_builder.cr) - Dead simple HTML form builder for Crystal with built-in support for many popular UI libraries such as Bootstrap :star:19
 * [html_builder](https://github.com/crystal-lang/html_builder) - DSL for creating HTML :star:38

## HTML/XML Parsing
 * [gumbo-crystal](https://github.com/blocknotes/gumbo-crystal) - Bindings for [Gumbo](https://github.com/google/gumbo-parser), an HTML5 parsing library made by Google :star:2
 * [hq.cr](https://github.com/maiha/hq.cr) - Simple wrapper for crystal-xml :star:7
 * [myhtml](https://github.com/kostya/myhtml) - Fast HTML5 Parser that includes CSS selectors :star:114

## HTTP
 * [Cable](https://github.com/cable-cr/cable) - An ActionCable "port" to Crystal, framework agnostic, 100% compatible with the ActionCable JS Client :star:48
 * [cossack](https://github.com/crystal-community/cossack) - Simple flexible HTTP client :star:93
 * [crest](https://github.com/mamantoha/crest) - Simple HTTP and REST client, inspired by the Ruby's RestClient gem :star:138
 * [crul](https://github.com/porras/crul) - Command line HTTP client :star:105
 * [cryload](https://github.com/sdogruyol/cryload) - HTTP benchmarking tool :star:112
 * [halite](https://github.com/icyleaf/halite) - Crystal HTTP Requests with a chainable REST API, built-in sessions and loggers :star:134
 * [helmet](https://github.com/EvanHahn/crystal-helmet) - Set security-related HTTP headers :star:25
 * [http-multiserver.cr](https://github.com/vladfaust/http-multiserver.cr) - Mounting multiple servers via routes (a.k.a. URL mapping) :star:17
 * [http-params-serializable](https://github.com/vladfaust/http-params-serializable) - HTTP params (de)serialization, applicable to URL queries and URL-encoded forms :star:16
 * [http-protection](https://github.com/rogeriozambon/http-protection) - Protection against typical web attacks :star:49
 * [http2](https://github.com/ysbaddaden/http2) - HTTP/2 Protocol Implementation :star:80
 * [HTTP::Client](https://crystal-lang.org/api/HTTP/Client.html) - HTTP client (Crystal stdlib)
 * [HTTP::Server](https://crystal-lang.org/api/HTTP/Server.html) - HTTP server (Crystal stdlib)
 * [HTTP::WebSocket](https://crystal-lang.org/api/HTTP/WebSocket.html) - HTTP WebSocket client (Crystal stdlib)
 * [keyer_cr](https://github.com/danielpclark/keyer_cr) - Adds HTTP GET/POST parameter parsing as a Hash-like object
 * [proxy-fetcher.cr](https://github.com/nbulaj/proxy-fetcher.cr) - Proxy lists fetching & validating library :star:6
 * [resp-crystal](https://github.com/soveran/resp-crystal) - Lightweight RESP client :star:10
 * [sse.cr](https://github.com/y2k2mt/sse.cr) - [Server-Sent Events](https://www.w3.org/TR/2009/WD-eventsource-20090421) client :star:6

## Image processing
 * [libpixel.cr](https://github.com/libpixel/libpixel.cr) :star:10
 * [magickwand-crystal](https://github.com/blocknotes/magickwand-crystal) - Bindings for [MagickWand](https://www.imagemagick.org/script/magick-wand.php), the C interface for ImageMagick processing libraries :star:54
 * [stumpy_png](https://github.com/stumpycr/stumpy_png) - Read and write PNG images :star:79

## Implementations/Compilers
 * [charly](https://github.com/charly-lang) - Charly Programming Language
 * [cltk](https://github.com/ziprandom/cltk) - A crystal port of the Ruby Language Toolkit :star:64
 * [cppize](https://github.com/unn4m3d/cppize) - Crystal-to-C++ transpiler :star:28
 * [crisp](https://github.com/rhysd/Crisp) - Lisp dialect implemented with Crystal :star:26
 * [crow](https://github.com/geppetto-apps/crow) - Transpile/compile Crystal to [Flow](https://flow.org/)
 * [LinCAS-lang](https://github.com/LinCAS-lang) - A programming language for scientific computation
 * [mint-lang](https://github.com/mint-lang/mint) - A refreshing programming language for the front-end web :star:2294
 * [myst-lang](https://github.com/myst-lang/) - A practical, dynamic language designed to be written and understood as easily and efficiently as possible
 * [runic-lang](https://github.com/runic-lang) - In-design toy language

## Logging and monitoring
 * [crafana](https://github.com/spoved/crafana.cr) - A [Grafana](https://grafana.com/) library to help autogenerate dashboards :star:15
 * [crometheus](https://gitlab.com/ezrast/crometheus) - A [Prometheus](https://prometheus.io/) client library
 * [crylog](https://github.com/blacksmoke16/crylog) - Flexible logging framework based on Monolog :star:16
 * [fluent-logger-crystal](https://github.com/TobiasGSmollett/fluent-logger-crystal) - A structured logger for [Fluentd](https://www.fluentd.org/)
 * [Logger](https://crystal-lang.org/api/Logger.html) - logging utility (Crystal stdlib)
 * [statsd.cr](https://github.com/miketheman/statsd.cr) - [Statsd](https://github.com/etsy/statsd) client library :star:24
 * [syslog.cr](https://github.com/comandeo/syslog.cr) - Implementation of Syslog client :star:14

## Machine Learning
 * [ai4cr](https://github.com/drhuffman12/ai4cr) - Artificial Intelligence (based on https://github.com/SergioFierens/ai4r) :star:16
 * [Cadmium](https://github.com/cadmiumcr/cadmium) - NLP library based heavily on [natural](https://github.com/NaturalNode/natural) :star:9104
 * [crystal-fann](https://github.com/NeuraLegion/crystal-fann) - FANN (Fast Artifical Neural Network) binding :star:76
 * [mxnet.cr](https://github.com/toddsundsted/mxnet.cr) - Bindings for [MXNet](https://mxnet.incubator.apache.org/)
 * [shainet](https://github.com/NeuraLegion/shainet) - SHAInet (Neural Network in pure crystal) :star:122
 * [tensorflow.cr](https://github.com/fazibear/tensorflow.cr) - Bindings for [TensorFlow](https://github.com/tensorflow/tensorflow) :star:142813

## Markdown/Text Processors
 * [html-pipeline](https://github.com/huacnlee/html-pipeline) - HTML processing filters and utilities :star:8
 * [markd](https://github.com/icyleaf/markd) - Yet another markdown parser built for speed, Compliant to CommonMark specification :star:55

## Misc
 * [aasm.cr](https://github.com/veelenga/aasm.cr) - Easy to use finite state machine for Crystal classes :star:38
 * [any_hash.cr](https://github.com/Sija/any_hash.cr) - Recursive Hash with better JSON::Any included :star:24
 * [atomic_write.cr](https://github.com/chris-huxtable/atomic_write.cr) - Library for writing or apppending files atomically :star:8
 * [burocracia.cr](https://github.com/vnbrs/burocracia.cr) - burocracia.cr the dependecyless shard to validate, generate and format Brazilian burocracias such as CPF, CNPJ and CEP :star:20
 * [callbacks](https://github.com/vladfaust/callbacks.cr) - Expressive callbacks module :star:9
 * [circuit_breaker](https://github.com/TPei/circuit_breaker) - Implementation of the circuit breaker pattern :star:21
 * [containerregistry.cr](https://github.com/naqvis/containerregistry.cr) - Library for working with container registries :star:2
 * [CrSerializer](https://github.com/blacksmoke16/CrSerializer) - Extensible annotation based serialization/deserialization library :star:33
 * [CrSignals](https://github.com/firejox/CrSignals) - Signals/slots notification library :star:7
 * [crystal-binary_parser](https://github.com/DanSnow/crystal-binary_parser) - Binary parser :star:17
 * [crystal-web-framework-stars](https://github.com/isaced/crystal-web-framework-stars) - Web frameworks for Crystal, most starred on Github :star:9
 * [crz](https://github.com/dhruvrajvanshi/crz) - Functional programming library :star:65
 * [emoji.cr](https://github.com/veelenga/emoji.cr) - Emoji library :star:38
 * [hoop](https://github.com/0x73/hoop) - Building native OSX apps :star:197
 * [i18n.cr](https://github.com/vladfaust/i18n.cr) - Internationalization shard :star:18
 * [immutable](https://github.com/lucaong/immutable) - Implementation of thread-safe, persistent, immutable collections :star:168
 * [inflector.cr](https://github.com/phoffer/inflector.cr) - Singularize, pluralize, camelize, etc (port from ActiveSupport) :star:30
 * [iterm2](https://github.com/toddsundsted/iterm2) - Display images within the terminal using the ITerm2 Inline Images Protocol
 * [lirith](https://github.com/lirith-engine/lirith) - Graphics engine :star:30
 * [m3u8](https://github.com/akiicat/m3u8) - Generate and parse m3u8 playlists for HTTP Live Streaming :star:9
 * [message_verifier.cr](https://github.com/danielwestendorf/message_verifier.cr) - Verify and generate Rails `ActiveSupport::MessageVerifier` signed tokens :star:13
 * [monads](https://github.com/alex-lairan/monads) - Monad implementation :star:28
 * [pangu.cr](https://github.com/isaced/pangu.cr) - Paranoid text spacing in Crystal :star:1
 * [pinger](https://github.com/spider-gazelle/pinger) - Ping IP addresses and DNS entries without requiring sudo :star:5
 * [port_midi](https://github.com/jimm/crystal_port_midi) - Crystal C bindings for the PortMIDI cross-platform MIDI I/O library :star:2
 * [retriable.cr](https://github.com/Sija/retriable.cr) - Simple DSL to retry failed code blocks :star:18
 * [tren](https://github.com/sdogruyol/tren) - Give your SQL some love :star:90
 * [ulid](https://github.com/SuperPaintman/ulid) - Universally Unique Lexicographically Sortable Identifier (ULID) :star:24
 * [zaru_crystal](https://github.com/szTheory/zaru_crystal) - Filename sanitization :star:2

## Network Protocols
 * [amqp-client.cr](https://github.com/cloudamqp/amqp-client.cr) - AMQP 0-9.1, a messaging protocol, implemented by eg. RabbitMQ :star:23
 * [bson.cr](https://github.com/jeromegn/bson.cr) - Native BSON implementation :star:24
 * [connect-proxy](https://github.com/spider-gazelle/connect-proxy) - Connect method style of HTTP tunnelling / HTTP proxy :star:2
 * [cr-xmpp](https://github.com/naqvis/cr-xmpp) - XMPP/Jabber Library :star:8
 * [Crirc](https://github.com/Meoowww/Crirc) - IRC protocol implementation (Client, Server, Bots) :star:17
 * [crystal-dns](https://gitlab.com/jgillich/crystal-dns) - DNS protocol implementation and resolver
 * [crystal-json-socket](https://github.com/foi/crystal-json-socket) - JSON-socket client & server implementation. Inspired by and compatible with [node-json-socket](https://github.com/sebastianseilund/node-json-socket/) and [ruby-json-socket](https://github.com/foi/ruby-json-socket) :star:3
 * [crystal-snmp](https://github.com/spider-gazelle/crystal-snmp) - An SNMP implementation with version 1, 2c and 3 support :star:6
 * [fast_irc.cr](https://github.com/RX14/fast_irc.cr) - Fast IRC parser/generator :star:12
 * [gopher.cr](https://github.com/anicholson/gopher.cr) - Gopher server toolkit :star:6
 * [jwt](https://github.com/crystal-community/jwt) - Implementation of JWT (JSON Web Token) :star:140
 * [msgpack-crystal](https://github.com/crystal-community/msgpack-crystal) - MessagePack library :star:112
 * [OAuth](https://crystal-lang.org/api/OAuth.html) - OAuth consumer (Crystal stdlib)
 * [OAuth2](https://crystal-lang.org/api/OAuth2.html) - OAuth2 client (Crystal stdlib)
 * [OpenSSL](https://crystal-lang.org/api/OpenSSL.html) - bindings to libssl (Crystal stdlib)
 * [telnet.cr](https://github.com/spider-gazelle/telnet.cr) - Telnet protocol :star:4
 * [transfer_more](https://git.sceptique.eu/Sceptique/transfer_more) - Clone of transfer.sh to uploads files

## Networking
 * [ipaddress.cr](https://github.com/Sija/ipaddress.cr) - Library to handle IPv4 and IPv6 addresses :star:30

## ORM/ODM Extensions
 * [avram](https://github.com/luckyframework/avram) - A database wrapper for reading, writing, and migrating Postgres databases. :star:61
 * [clear](https://github.com/anykeyh/clear) - ORM specialized to PostgreSQL only but with advanced features :star:177
 * [crecto](https://github.com/Crecto/crecto) - Database wrapper, based on Ecto :star:308
 * [granite](https://github.com/amberframework/granite) - ORM for Postgres, Mysql, Sqlite :star:204
 * [jennifer.cr](https://github.com/imdrasil/jennifer.cr) - Active Record pattern implementation with flexible query chainable builder and migration system :star:260
 * [ohm-crystal](https://github.com/soveran/ohm-crystal) - Object-hash mapping library for Redis :star:62
 * [onyx-sql](https://github.com/onyxframework/sql) - DB-agnostic SQL ORM with beautiful DSL and type-safe Query builder :star:88
 * [redis-tsv.cr](https://github.com/maiha/redis-tsv.cr) - Import and export data from Redis in TSV format :star:4
 * [rethinkdb-orm](https://github.com/spider-gazelle/rethinkdb-orm) - ORM for RethinkDB / RebirthDB :star:9
 * [stal-crystal](https://github.com/soveran/stal-crystal) - Set algebra solver for Redis :star:4
 * [topaz](https://github.com/topaz-crystal/topaz) - A simple and useful db wrapper :star:55

## Package Management
 * [shards](https://github.com/crystal-lang/shards) - Dependency manager for the Crystal :star:589

## Processes and Threads
 * [await_async](https://github.com/anykeyh/await_async) - Add keywords await & async in Crystal Lang :star:55
 * [crystal-futures](https://github.com/dhruvrajvanshi/crystal-futures) - Future type implementation :star:50
 * [neph](https://github.com/tbrand/neph) - A modern command line job processor that can execute jobs concurrently :star:166
 * [promise](https://github.com/spider-gazelle/promise) - A Promise implementation with type inference :star:25

## Project Generators
 * [crystal_lib](https://github.com/crystal-lang/crystal_lib) - Automatic binding generator for native libraries :star:114
 * [fez](https://github.com/jwoertink/fez) - A Kemal application generator :star:34
 * [kgen](https://github.com/kemalyst/kemalyst-generator) - Kemalyst command line tool for console, init, generate (scaffolding), and watch. :star:12
 * [libgen](https://github.com/olbat/libgen) - Automatic bindings generator configured using JSON/YAML files :star:49
 * [wasp](https://github.com/icyleaf/wasp) - Static Site Generator :star:15

## Queues and Messaging
 * [dispatch](https://github.com/bmulvihill/dispatch) - In memory asynchronous job processing :star:27
 * [mosquito](https://github.com/robacarp/mosquito/) - Redis backed periodic and ad hoc job processing :star:110
 * [NATS.io](https://github.com/nats-io/nats.cr) - NATS client :star:26
 * [sidekiq.cr](https://github.com/mperham/sidekiq.cr) - Simple, efficient job processing :star:626

## Routing
 * [orion](https://github.com/obsidian/orion) - A minimal, rails-esque routing library :star:79
 * [router.cr](https://github.com/tbrand/router.cr) - Minimum but powerful http router for HTTP::Server :star:217
 * [toro](https://github.com/soveran/toro) - Tree Oriented Routing :star:87

## Scheduling
 * [crystime](https://gitlab.com/crystallabs/crystime) - Advanced time, calendar, schedule, and remind library
 * [schedule.cr](https://github.com/hugoabonizio/schedule.cr) - Run periodic tasks :star:58
 * [tasker](https://github.com/spider-gazelle/tasker) - A high precision scheduler including timezone aware cron jobs :star:28

## Science and Data analysis
 * [ishi](https://github.com/toddsundsted/ishi) - Graph plotting package with a small API and sensible defaults powered by gnuplot :star:2
 * [linalg](https://github.com/konovod/linalg) - Linear algebra library inspired by MATLAB and SciPy.linalg :star:34
 * [num.cr](https://github.com/crystal-data/num.cr) - Numerical computing library supporting N-Dimensional data :star:39
 * [predict.cr](https://github.com/RX14/predict.cr) - Satellite prediction library using the sgp4 model :star:12

## Search
 * [hermes](https://github.com/imdrasil/hermes.cr) - Data Mapper pattern implementation for ElastiSearch :star:26
 * [query-builder](https://github.com/izniburak/query-builder) - Sql Query Builder library :star:47
 * [soegen](https://github.com/Ragmaanir/soegen) - Elasticsearch client for Crystal similar to the stretcher gem for ruby :star:19

## Serverless Computing
 * [crystal_openfaas](https://github.com/TPei/crystal_openfaas/) - Template to enable crystal as first class citizens in OpenFaaS :star:17
 * [FaaStRuby](https://faastruby.io) - Serverless Software Development Platform for Ruby and Crystal.
 * [gcf.cr](https://github.com/sam0x17/gcf.cr) - Managed execution of Crystal in Google Cloud Functions :star:48

## System
 * [baked_file_system](https://github.com/schovi/baked_file_system) - Virtual file system implementation :star:121
 * [hardware](https://github.com/crystal-community/hardware) - Get CPU, Memory and Network informations of the running OS and its processes :star:38

## Task management
 * [cake](https://github.com/axvm/cake) - Production-ready Make-like utility tool :star:45
 * [sam](https://github.com/imdrasil/sam.cr) - Another one Rake-like task manager with namespacing and arguments system :star:63

## Template Engine
 * [crinja](https://github.com/straight-shoota/crinja) - An implementation of the [Jinja2 template engine](http://jinja.pocoo.org/)
 * [crustache](https://github.com/MakeNowJust/crustache) - [{{Mustache}}](https://mustache.github.io) for Crystal :star:57
 * [ECR (Embedded Crystal)](https://crystal-lang.org/api/ECR.html) - compile time template language which uses plain crystal expressions (Crystal stdlib)
 * [Jbuilder](https://github.com/shootingfly/jbuilder) - Generate JSON objects with a Builder-style DSL, inspired by jbuilder :star:28
 * [Kilt](https://github.com/jeromegn/kilt) - Abstraction layer for template engines :star:117
 * [Slang](https://github.com/jeromegn/slang) - Lightweight, terse, templating language inspired by Ruby's Slim :star:177
 * [teeplate](https://github.com/mosop/teeplate) - A library for rendering multiple template files :star:12
 * [Water](https://github.com/shootingfly/water) - A library for writing HTML in plain Crystal :star:8

## Testing
 * [crotest](https://github.com/emancu/crotest) - A tiny and simple test framework :star:22
 * [crytic](https://github.com/hanneskaeufler/crytic) - Mutation testing framework :star:44
 * [LuckyFlow](https://github.com/luckyframework/lucky_flow) - Automated browser tests similar to Capybara :star:39
 * [mass-spec](https://github.com/c910335/mass-spec) - Web API testing library :star:6
 * [microtest](https://github.com/Ragmaanir/microtest) - Small opinionated testing library focusing on power asserts :star:17
 * [minitest.cr](https://github.com/ysbaddaden/minitest.cr) - Library for unit tests and assertions :star:112
 * [mocks.cr](https://github.com/waterlink/mocks.cr) - Mocking library for Crystal :star:42
 * [Spec](https://crystal-lang.org/api/Spec.html) - spec framework (Crystal stdlib)
 * [spectator](https://gitlab.com/arctic-fox/spectator) - Feature rich spec framework that uses the modern expect syntax
 * [timecop.cr](https://github.com/crystal-community/timecop.cr) - Library for mocking with `Time.now`. Inspired by the [timecop ruby gem](https://github.com/travisjeffery/timecop) :star:2942
 * [vcr](https://github.com/spoved/vcr.cr) - A HTTP capture and replay implementation for crystal :star:38
 * [webdriver_pump](https://github.com/bwilczek/webdriver_pump) - Page Object library. Inspired by Ruby's [WatirPump](https://github.com/bwilczek/watir_pump) :star:13
 * [webmock.cr](https://github.com/manastech/webmock.cr) - Library for stubbing `HTTP::Client` requests :star:83

## Third-party APIs
 * [aws-credentials](https://github.com/y2k2mt/aws-credentials) - Get AWS credentials in various ways :star:2
 * [aws-signer.cr](https://github.com/beanieboi/aws-signer.cr) - This library signs your HTTP requests using AWS v4 :star:7
 * [awscr-s3](https://github.com/taylorfinnell/awscr-s3) - AWS S3 interface :star:60
 * [awscr-signer](https://github.com/taylorfinnell/awscr-signer) - Sign HTTP::Request objects and generate presigned post forms :star:10
 * [bugsnag.cr](https://github.com/gewo/bugsnag.cr) - Bugsnag exception notifier and sidekiq middleware :star:5
 * [crystal-consul](https://github.com/rogerwelin/crystal-consul) - Consul API client :star:12
 * [crystal-darksky](https://github.com/sb89/crystal-darksky) - Wrapper for the [Dark Sky](https://darksky.net) API :star:5
 * [crystal-github](https://github.com/felipeelias/crystal-github) - Wrapper for the [Github](https://github.com/) API :star:6
 * [crystal-swapi](https://github.com/sb89/crystal-swapi) - Star Wars API (SWAPI) wrapper :star:2
 * [crystal_slack](https://github.com/manastech/crystal_slack) - A tool that parses Slack slash commands or send incoming web hooks :star:18
 * [discordcr](https://github.com/meew0/discordcr) - A minimalist Discord API library :star:115
 * [GDAX](https://github.com/mccallofthewild/gdax) - GDAX REST and WebSocket API Wrapper with request signing :star:6
 * [gitlab.cr](https://github.com/icyleaf/gitlab.cr) - GitLab API wrapper :star:21
 * [google_maps_api](https://github.com/fridgerator/google_maps_api) - Google Maps API :star:14
 * [host_meta](https://github.com/toddsundsted/host_meta) - A Web Host Metadata (https://tools.ietf.org/html/rfc6415) client
 * [kube-client.cr](https://github.com/spoved/kube-client.cr) - Kubernetes API Client :star:4
 * [mixpanel-crystal](https://github.com/petoem/mixpanel-crystal) - A library for sending events to Mixpanel
 * [mollie.cr](https://github.com/tilishop/mollie.cr) - [Mollie](https://www.mollie.com/en/) Payments API wrapper (Creditcard, PayPal, Apple Pay, Sofort, Klarna, ...)
 * [pinboard.cr](https://github.com/oz/pinboard.cr) - [Pinboard](https://pinboard.in) API :star:5
 * [raven.cr](https://github.com/sija/raven.cr) - Raven is a client for [Sentry](https://github.com/getsentry/sentry) :star:24442
 * [twitter-crystal](https://github.com/sferik/twitter-crystal) - A library to access the Twitter API :star:73
 * [web_finger](https://github.com/toddsundsted/web_finger) - A WebFinger (https://tools.ietf.org/html/rfc7033) client :star:1
 * [ynab.cr](https://github.com/jaredsmithse/ynab.cr) - A library to interact with your YNAB data :star:2

## Validation
 * [accord](https://github.com/neovintage/accord) - Shareable validation library for Crystal Objects :star:22
 * [assert](https://github.com/blacksmoke16/assert) - Extensible annotation based object validation library :star:11
 * [denetmen](https://github.com/izniburak/denetmen) - Micro check library that patches Crystal stdlib :star:25
 * [validations](https://github.com/vladfaust/validations.cr) - Validations mixin :star:10
 * [validator](https://github.com/Nicolab/crystal-validator) - Data check and validation :star:8

## Web Frameworks
 * [amber](https://github.com/amberframework/amber) - Open source efficient and cohesive web application framework :star:1978
 * [athena](https://github.com/blacksmoke16/athena) - Modular, annotation based, API oriented framework with built in param conversion :star:67
 * [grip](https://github.com/grip-framework/grip) - A microframework for building RESTful web applications, with ease and joy :star:37
 * [kemal](https://github.com/kemalcr/kemal) - Lightning Fast, Super Simple web framework. Inspired by Sinatra :star:2778
 * [lucky](https://github.com/luckyframework/lucky) - Catch bugs early, forget about most performance issues, and spend more time on code instead of debugging and writing tests :star:1663
 * [Shivneri](https://github.com/ujjwalguptaofficial/shivneri) - Component based MVC web framework for crystal targeting good code structures, modularity & performance :star:10
 * [spider-gazelle](https://github.com/spider-gazelle/spider-gazelle) - A Rails esque web framework with a focus on speed and extensibility :star:93

## Web Servers
 * [serve](https://github.com/SuperPaintman/serve) - Command line static HTTP server :star:22

# Community
 * [Crystal weekly newsletters](http://crystalweekly.com/)
 * [Gitter](https://gitter.im/crystal-lang/crystal)
 * [Google Group](https://groups.google.com/forum/?fromgroups#!forum/crystal-lang)
 * [IRC](http://irc.lc/freenode/crystal-lang) - #crystal-lang on Freenode
 * [Metaruby](https://metaruby.com/c/crystal-forum) - Crystal Forum on Metaruby
 * [Reddit](https://www.reddit.com/r/crystal_programming/)
 * [Stackoverflow](https://stackoverflow.com/tags/crystal-lang/info)

## Unofficial
 * [Chinese-speaking Telegram Group](https://t.me/crystal_cn) - 来吧！TG 中文圈的朋友们！
 * [Crystal Programming Discord Server](https://discord.gg/YS7YvQy) - Unofficial Discord server dedicated to the Crystal Programming Language
 * [Portuguese-speaking Telegram Group](https://t.me/crystalbrasil) - Bem vindos ao Crystal Brasil!
 * [Russian-speaking Telegram Group](https://t.me/crystal_ru) - Добро пожаловать, товарищ!

# Resources
 * [Crystal for Rubyists](http://www.crystalforrubyists.com/) - Free book to bootstrap your Crystal journey
 * [Crystal Mastery](https://crystalmastery.io/) - Screencasts for learning Crystal
 * [crystal-lang.org](https://crystal-lang.org) - Official language site
 * [devdocs.io](https://devdocs.io/crystal/) - API Documentation Browser with Crystal support
 * [getgood.at](https://getgood.at/in-a-day/crystal) - Learn Crystal in a Day
 * [Programming Crystal](https://pragprog.com/book/crystal/programming-crystal) - PragProg book to start your Crystal journey

## Official Documentation Translations
 * [br.crystal-lang.org](http://br.crystal-lang.org/) - Brazilian
 * [ja.crystal-lang.org](http://ja.crystal-lang.org/) - Japanese
 * [kr.crystal-lang.org](https://kr.crystal-lang.org/) - Korean
 * [ru.crystal-lang.org](http://ru.crystal-lang.org/) - Russian
 * [tw.crystal-lang.org](http://tw.crystal-lang.org/) - Chinese Traditional

# Services and Apps
 * [carc.in](https://carc.in/) - A web service that runs your code and displays the result
 * [cry](https://github.com/elorest/cry) - Ability to execute crystal code in a fashion similar to Ruby's pry edit :star:22
 * [Crystal [ANN]](https://crystal-ann.com) - Announce new project, blog post, version update or any other Crystal work
 * [crystalshards.herokuapp.com](https://crystalshards.herokuapp.com/), [crystalshards.xyz](http://crystalshards.xyz/) - Web services that list all available Crystal shards
 * [Crystular](http://www.crystular.org) - Regular expression tester
 * [DeBot](https://github.com/jhass/DeBot) - IRC bot written in Crystal :star:35
 * [Fluence](https://github.com/docelic/fluence) - WYSIWYG wiki using markdown and Git :star:33
 * [icr](https://github.com/crystal-community/icr) - Interactive console for Crystal (like IRB for Ruby) :star:415
 * [Invidious](https://github.com/omarroth/invidious) - Invidious is an alternative front-end to YouTube :star:2824
 * [mpngin](https://github.com/thewalkingtoast/mpngin) - A URL shortener with simple stats :star:28
 * [quicktype](https://quicktype.io/) - Generate models and serializers from JSON, JSON Schema, GraphQL, and TypeScript
 * [shards.info](http://shards.info/) - Web service that lists all repositories on GitHub that have Crystal code in them. The sources are available on [GitHub](https://github.com/mamantoha/shards-info) :star:19
 * [wikicr](https://git.sceptique.eu/Sceptique/wikicr) - Wiki using git to manage revisions

# Tools
 * [ast_helper](https://github.com/bcardiff/crystal-ast-helper) - Helper tool to debug parser and formatter :star:15
 * [crystal-base](https://github.com/ruivieira/crystal-base) - CentOS base docker image for Crystal development :star:1
 * [crystal-ctags](https://github.com/SuperPaintman/crystal-ctags) - Ctags generator for Crystal :star:12
 * [crystal-dash-docset](https://github.com/Sija/crystal-dash-docset) - [Dash](https://kapeli.com/dash) docset generator :star:6
 * [public_suffix](https://github.com/toddsundsted/public_suffix) - A small library designed to make the Public Suffix List (https://publicsuffix.org/) easier to use :star:1

## DevOps
 * [ansible-crystal](https://github.com/CorbanR/ansible-crystal) - Ansible playbook for installing crystal :star:6
 * [crystal-cookbook](https://github.com/vjdhama/crystal-cookbook) - Chef cookbook for installing crystal :star:5
 * [DPPM](https://github.com/DFabric/dppm) - An easy, universal way to install and manage applications as packages (mostly Linux) :star:65

## Editor Plugins
 * Atom
   * [crystal-tools](https://atom.io/packages/crystal-tools) - Enables built in tools in Crystal compiler
   * [language-crystal-actual](https://atom.io/packages/language-crystal-actual) - Crystal language support in Atom
 * Emacs
   * [emacs-crystal-mode](https://github.com/dotmilk/emacs-crystal-mode) - Crystal language support for Emacs :star:17
   * [play-crystal.el](https://github.com/veelenga/play-crystal.el) - [play.crystal-lang.org](https://play.crystal-lang.org/#/cr) integration in Emacs :star:5
 * [scry](https://github.com/crystal-lang-tools/scry) - Code analysis server for Crystal implementing the [Language Server Protocol](https://microsoft.github.io/language-server-protocol/)
 * Spacemacs
   * [crystal-spacemacs-layer](https://github.com/juanedi/crystal-spacemacs-layer) - Spacemacs contribution layer for Crystal :star:12
 * Sublime
   * [sublime-crystal](https://github.com/crystal-lang-tools/sublime-crystal) - Crystal syntax highlighting for sublime Text :star:74
 * TextMate
   * [Crystal.tmbundle](https://github.com/crystal-lang-tools/Crystal.tmbundle) - Crystal syntax highlighting, compile, format command, snippets :star:13
 * Vim
   * [vim-crystal](https://github.com/rhysd/vim-crystal) - Vim filetype support for Crystal :star:301
   * [vim-slang](https://github.com/elorest/vim-slang) - Vim filetype support for Slang Templating Engine :star:9
 * Visual Studio Code
   * [vscode-crystal](https://github.com/g3ortega/vscode-crystal) - Crystal language support in VSCode :star:11
   * [vscode-crystal-ide](https://github.com/crystal-lang-tools/crystal-ide) - Crystal IDE powered by [Language Server Protocol](https://code.visualstudio.com/blogs/2016/06/27/common-language-protocol)
   * [vscode-crystal-lang](https://github.com/crystal-lang-tools/vscode-crystal-lang) - Formatter, linter and syntax highlighting for `cr` and `ecr` files :star:148

## Shell plugins
 * [crun](https://github.com/Val/crun) - Crystal Run : shebang wrapper for Crystal :star:25
 * [crystal-zsh](https://github.com/veelenga/crystal-zsh) - .oh-my-zsh plugin :star:21


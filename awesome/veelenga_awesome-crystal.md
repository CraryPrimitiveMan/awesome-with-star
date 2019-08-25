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
  * [Configuration](#configuration)
  * [Converters](#converters)
  * [Cryptography](#cryptography)
  * [Data Formats](#data-formats)
  * [Data Generators](#data-generators)
  * [Database Drivers/Clients](#database-driversclients)
  * [Database Tools](#database-tools)
  * [Dependency Injection](#dependency-injection)
  * [Development Tools](#development-tools)
  * [Email](#email)
  * [Environment Management](#environment-management)
  * [Examples and funny stuff](#examples-and-funny-stuff)
  * [Feature Flipping](#feature-flipping)
  * [Framework Components](#framework-components)
  * [Game Development](#game-development)
  * [GUI library](#gui-library)
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
 * [aho_corasick](https://github.com/chenkovsky/aho_corasick) - AhoCorasick algorithm :star:5
 * [bisect](https://github.com/spider-gazelle/bisect) - Inserting values into a sorted array :star:5
 * [bitfields](https://github.com/elorest/bitfields) - Pure Crystal implementation of BitFields. Handles encoding/decoding of bytes. :star:15
 * [CrOTP](https://github.com/philnash/crotp) - HOTP and TOTP implementation for two factor authentication :star:37
 * [crystal-diff](https://github.com/MakeNowJust/crystal-diff) - A Crystal sequence differencing implementation :star:26
 * [crystal-linked-list](https://github.com/abvdasker/crystal-linked-list) - Implementation of Linked List :star:6
 * [crystaledge](https://github.com/unn4m3d/crystaledge) - A pure Vector Math library :star:15
 * [crystalg](https://github.com/TobiasGSmollett/crystalg) - A Generic Algorithm Library :star:17
 * [crystalline](https://github.com/jtomschroeder/crystalline) - A collection of containers and algorithms :star:101
 * [delimiter_tree](https://github.com/drujensen/delimiter_tree) - A tree structure that is built using a delimiter :star:8
 * [edits.cr](https://github.com/tcrouch/edits.cr) - Collection of edit distance algorithms :star:10
 * [graphlb](https://github.com/mettuaditya/graphlb) - Collection of graph datastructure and algorithms :star:7
 * [hash_ring](https://github.com/TobiasGSmollett/hash_ring) - An Implementation of Consistent Hash Ring :star:4
 * [haversine](https://github.com/mamantoha/haversine) - An Implementation of the Haversine formula :star:4
 * [kd_tree](https://github.com/mamantoha/kd_tree) - An implementation of "K-Dimensional Tree" and "N-Nearest Neighbors" :star:5
 * [ksuid.cr](https://github.com/Sija/ksuid.cr) - K-Sortable Globally Unique IDs :star:6
 * [markov](https://github.com/mccallofthewild/markov) - Build Markov Chains and run Markov Processes :star:15
 * [multiset.cr](https://github.com/tcrouch/multiset.cr) - Implementation of a multiset :star:1
 * [murmur3](https://github.com/kuende/murmur3) - Implementation of Murmur3 hash algorithm used by Cassandra :star:4
 * [oak](https://github.com/obsidian/oak) - A flexible Radix Tree implementation :star:8
 * [radix](https://github.com/luislavena/radix) - Radix Tree implementation :star:67
 * [ternary_search_tree](https://github.com/johnjansen/ternary_search_tree) - Ternary Search Tree :star:2

## Api Builders
 * [kemal-rest-api](https://github.com/blocknotes/kemal-rest-api) - A library to create RESTful API with Kemal :star:45

## Blockchain
 * [SushiChain](https://github.com/SushiChain/SushiChain) - A custom blockchain platform :star:149

## C bindings
 * [asound-cr](https://github.com/TamasSzekeres/asound-cr) - Bindings for ALSA/libasound :star:4
 * [cairo-cr](https://github.com/TamasSzekeres/cairo-cr) - Bindings for [Cairo](https://cairographics.org/) graphics library :star:10
 * [clang.cr](https://github.com/ysbaddaden/clang.cr) - Libclang bindings :star:27
 * [crass](https://github.com/vonKingsley/crass) - Bindings for libsass :star:10
 * [crt.cr](https://github.com/maiha/crt.cr) - Bindings for libncursesw and crt :star:20
 * [crystal-gsl](https://github.com/ruivieira/crystal-gsl) - GNU Scientific Library bindings :star:12
 * [crystal-hunspell](https://github.com/mamantoha/crystal-hunspell) - Bindings for [Hunspell](https://hunspell.github.io/)
 * [curl-crystal](https://github.com/blocknotes/curl-crystal) - Bindings for [libcurl](https://curl.haxx.se/libcurl/)
 * [duktape.cr](https://github.com/jessedoyle/duktape.cr) - Bindings for the [Duktape](https://github.com/svaarala/duktape) javascript engine :star:84
 * [gphoto2.cr](https://github.com/Sija/gphoto2.cr) - Bindings for the [libgphoto2](http://www.gphoto.org/) library :star:10
 * [icu.cr](https://github.com/olbat/icu.cr) - Bindings for the [ICU](http://site.icu-project.org/) library :star:6
 * [libnotify.cr](https://github.com/splattael/libnotify.cr) - Bindings for Libnotify :star:19
 * [pcap.cr](https://github.com/maiha/pcap.cr) - Bindings for libpcap :star:19
 * [pledge.cr](https://github.com/chris-huxtable/pledge.cr) - Bindings for OpenBSD's `pledge(2)` :star:1
 * [posix](https://github.com/ysbaddaden/posix) - POSIX/C bindings :star:25
 * [soundfile](https://github.com/mjago/soundfile) - Bindings for [libsndfile](http://www.mega-nerd.com/libsndfile/) library :star:3
 * [ssh2.cr](https://github.com/spider-gazelle/ssh2.cr) - Bindings for libssh2 library :star:7
 * [syslog.cr](https://github.com/chris-huxtable/syslog.cr) - Bindings for `syslog` :star:5
 * [termbox-crystal](https://github.com/andrewsuzuki/termbox-crystal) - Bindings and extension library for [termbox](https://github.com/nsf/termbox) (terminal UI library) :star:1524
 * [x11-cr](https://github.com/TamasSzekeres/x11-cr) - X11 bindings :star:19
 * [x_do.cr](https://github.com/woodruffw/x_do.cr) - Bindings for libxdo ([`xdotool`](https://github.com/jordansissel/xdotool)) :star:1008
 * [zstd-cr](https://github.com/BlackHabanero/zstd-cr) - Bindings for [Zstandard](https://github.com/facebook/zstd) compression library :star:4

## Caching
 * [bloom_filter](https://github.com/crystal-community/bloom_filter) - Implementation of Bloom filter :star:26
 * [bojack](https://github.com/marceloboeira/bojack) - A non-reliable in-memory key-value store :star:93
 * [cache-hash](https://github.com/samueleaton/cache-hash) - A key/value store where entries expire after a specified interval :star:16
 * [crystal-memcached](https://github.com/comandeo/crystal-memcached) - Implementation of a memcached client :star:27
 * [Nuummite](https://github.com/CodeSteak/Nuummite) - A tiny persistent embedded key-value store :star:24

## CLI Builders
 * [admiral](https://github.com/jwaldrip/admiral.cr) - A robust DSL for writing command line interfaces :star:91
 * [cli](https://github.com/mosop/cli) - Library for building command-line interface applications :star:85
 * [clicr](https://github.com/j8r/clicr) -  A simple declarative command line interface builder :star:19
 * [clim](https://github.com/at-grandpa/clim) - Slim command line interface builder :star:64
 * [commander](https://github.com/mrrooijen/commander) - Command-line interface builder :star:84
 * [completion](https://github.com/f/completion) - Easy command line completion engine :star:63
 * [optarg](https://github.com/mosop/optarg) - Yet another library for parsing command-line options and arguments :star:19
 * [OptionParser](https://crystal-lang.org/api/OptionParser.html) - command-line options processing (Crystal stdlib)

## CLI Utils
 * [cride](https://github.com/j8r/cride) - A light CLI text editor/IDE :star:28
 * [progress_bar.cr](https://github.com/TPei/progress_bar.cr) - A simple and customizable progress bar :star:8
 * [tallboy](https://github.com/epoch/tallboy) - Generate ASCII character tables with support for spanning cells over multiple columns :star:15
 * [terminal_table.cr](https://github.com/benoist/terminal_table.cr) - Simple ASCII table generator :star:21
 * [terminimal](https://github.com/aca-labs/terminimal) - A tiny CLI toolkit for building terminal apps for humans :star:4
 * [todo](https://git.sceptique.eu/Sceptique/todo) - Todo list working in command line

## Code Analysis and Metrics
 * [ameba](https://github.com/crystal-ameba/ameba) - A static code analysis tool :star:226
 * [trashman](https://github.com/Groogy/trashman) - A simple memory profiler for Crystal applications :star:18

## Configuration
 * [cr-dotenv](https://github.com/gdotdesign/cr-dotenv) - Loads .env file :star:52
 * [envyable](https://github.com/philnash/envyable.cr) -  A simple YAML to ENV config loader :star:4
 * [habitat](https://github.com/luckyframework/habitat) - Type safe configuration for your classes and modules :star:39
 * [totem](https://github.com/icyleaf/totem) - Load and parse a configuration in JSON, YAML, dotenv formats :star:25

## Converters
 * [base62.cr](https://github.com/Sija/base62.cr) - Base62 encoder/decoder, well suited for url-shortening :star:3
 * [money](https://github.com/crystal-money/money) - Handling money and currency conversion with ease (almost complete port of [RubyMoney](https://github.com/RubyMoney/money)) :star:2171
 * [moola](https://github.com/dorkrawk/moola) - Library for dealing with money and conversion (inspired by [RubyMoney](https://github.com/RubyMoney/money)) :star:2171
 * [ms](https://github.com/SuperPaintman/ms) - Library to easily convert various time formats to milliseconds and milliseconds to human readable format :star:14
 * [sass.cr](https://github.com/straight-shoota/sass.cr) - Compile SASS/SCSS to CSS ([libsass](https://github.com/sass/libsass/) binding) :star:4020
 * [time_format.cr](https://github.com/vladfaust/time_format.cr) - Convert time in human readable format with ease :star:3
 * [turkish-number](https://github.com/izniburak/turkish-number) - Turn integers into the Turkish words :star:7
 * [wkhtmltopdf-crystal](https://github.com/blocknotes/wkhtmltopdf-crystal) - Bindings / wrapper for libwkhtmltox (HTML to PDF / image converter) :star:11

## Cryptography
 * [openssl.cr](https://github.com/z64/openssl.cr) - This library provides binding for OpenSSL library
 * [sodium.cr](https://github.com/didactic-drunk/sodium.cr) - Crystal wrapper for the libsodium crypto API :star:6

## Data Formats
 * [BinData](https://github.com/spider-gazelle/bindata) - Binary data parser helper with an [ASN.1](https://en.wikipedia.org/wiki/Abstract_Syntax_Notation_One) parser :star:16
 * [config.cr](https://github.com/chris-huxtable/config.cr) - Easy to use configuration format parser :star:2
 * [crinder](https://github.com/c910335/crinder) - Class based json renderer :star:18
 * [Crystar](https://github.com/naqvis/crystar) - Readers and writers of Tar archive format :star:10
 * [CSV](https://crystal-lang.org/api/CSV.html) - parsing and generating for comma-separated values (Crystal stdlib)
 * [front_matter.cr](https://github.com/chris-huxtable/front_matter.cr) - Separates a files front matter from its content
 * [geoip2.cr](https://github.com/delef/geoip2.cr) - GeoIP2 reader :star:4
 * [Gzip](https://crystal-lang.org/api/Gzip.html) - readers and writers of gzip format (Crystal stdlib)
 * [INI](https://crystal-lang.org/api/INI.html) - INI file parser (Crystal stdlib)
 * [JSON](https://crystal-lang.org/api/JSON.html) - parsing and generating JSON documents (Crystal stdlib)
 * [JSON tools](https://github.com/impatienttraveller/json-tools) - An implementation of JSON Patch and Pointer RFC's :star:12
 * [maxminddb.cr](https://github.com/delef/maxminddb.cr) - MaxMindDB reader :star:17
 * [toml.cr](https://github.com/crystal-community/toml.cr) - TOML parser :star:37
 * [XML](https://crystal-lang.org/api/XML.html) - parsing and generating XML documents (Crystal stdlib)
 * [YAML](https://crystal-lang.org/api/YAML.html) - parsing and generating YAML documents (Crystal stdlib)
 * [Zip](https://crystal-lang.org/api/Zip.html) - readers and writers of zip format (Crystal stdlib)
 * [Zlib](https://crystal-lang.org/api/Zlib.html) - readers and writers of zlib format (Crystal stdlib)
 * [zq](https://github.com/colstrom/zq) - Command-line ZPL processor :star:2

## Data Generators
 * [faker](https://github.com/askn/faker) - A library for generating fake data :star:111
 * [hashids.cr](https://github.com/splattael/hashids.cr) - A library to generate YouTube-like ids from one or many numbers :star:32

## Database Drivers/Clients
 * [couchdb.cr](https://github.com/TechMagister/couchdb.cr) - CouchDB client :star:8
 * [crystal-db](https://github.com/crystal-lang/crystal-db) - Common db api :star:157
 * [crystal-monetdb-libmapi](https://github.com/puppetpies/crystal-monetdb-libmapi) - Bindings for MonetDB :star:1
 * [crystal-mysql](https://github.com/crystal-lang/crystal-mysql) - MySQL connector for Crystal :star:67
 * [crystal-pg](https://github.com/will/crystal-pg) - A Postgres driver :star:321
 * [crystal-redis](https://github.com/stefanwille/crystal-redis) - Full featured Redis client :star:295
 * [crystal-rethinkdb](https://github.com/kingsleyh/crystal-rethinkdb) - Driver for RethinkDB / RebirthDB :star:9
 * [crystal-sqlite3](https://github.com/crystal-lang/crystal-sqlite3) - SQLite3 bindings :star:73
 * [eventql-crystal](https://github.com/measurechina/eventql-crystal) - EventQL driver :star:7
 * [leveldb](https://github.com/crystal-community/leveldb) - Crystal bindings for LevelDB :star:29
 * [mongo.cr](https://github.com/ambercommunity/mongo.cr) - Binding for MongoDB C driver :star:7
 * [rocksdb.cr](https://github.com/maiha/rocksdb.cr) - RocksDB client :star:25
 * [tarantool-crystal](https://github.com/vladfaust/tarantool-crystal) - Tarantool driver :star:13

## Database Tools
 * [micrate](https://github.com/juanedi/micrate) - Database migration tool :star:102
 * [migrate](https://github.com/vladfaust/migrate.cr) - A simpler database migration tool with transactions :star:20
 * [migro](https://github.com/aisrael/migro) - A database migration tool that allows migrations to be specified in either YAML or raw SQL :star:7

## Dependency Injection
* [syringe](https://github.com/Bonemind/syringe) - A simple and basic dependency injection shard for crystal :star:3

## Development Tools
 * [docker-crystal](https://github.com/aca-labs/docker-crystal) - Docker wrapper for the Crystal CLI :star:10
 * [guardian](https://github.com/f/guardian) - File change watcher for Crystal and Non-Crystal libs :star:241
 * [kemal-watcher](https://github.com/faustinoaq/kemal-watcher) - Kemal plugin to watch files and live-reload the browser :star:15
 * [sentry](https://github.com/samueleaton/sentry) - Watches src files, rebuilds/reruns application on file changes :star:198
 * [sentry-run](https://github.com/faustinoaq/sentry-run) - Reload code changes using Sentry.run :star:10
 * [Warden](https://github.com/diggersheep/warden) - Watches files, run command and a git command if succeed on file changes :star:9
 * [watcher](https://github.com/faustinoaq/watcher) - Watch file changes using File.stat :star:18

## Email
 * [carbon](https://github.com/luckyframework/carbon) - Fun, testable, and adapter-based email library :star:42
 * [crystal-email](https://github.com/arcage/crystal-email) - Simple e-mail sending library :star:75
 * [CrystalEmail](https://git.sceptique.eu/Sceptique/CrystalEmail) - A RFC compliant Email validator
 * [devmail](https://github.com/tijn/devmail) - A combined SMTP/POP3-server with volatile mail storage :star:18
 * [sendgrid.cr](https://github.com/dlanileonardo/sendgrid.cr) - Simple Sendgrid Client :star:5

## Environment Management
 * [asdf-crystal](https://github.com/marciogm/asdf-crystal) - Plugin for asdf version manager :star:17
 * [crenv](https://github.com/pine/crenv) - Crystal version manager :star:193
 * [rcm.cr](https://github.com/maiha/rcm.cr) - Redis Cluster Manager :star:39

## Examples and funny stuff
 * [battlesnake_crystal](https://github.com/nbw/battlesnake_crystal) - Tron snake for [battlesnake](https://www.battlesnake.io/) competition :star:5
 * [blackjack-cr](https://github.com/gdonald/blackjack-cr) - Console Blackjack :star:2
 * [breakout.cr](https://github.com/petoem/breakout.cr) - Breakout game written using crsfml :star:10
 * [chuck-norris-holy-quotes](https://github.com/codenoid/chuck-norris-holy-quotes) - Chuck Norris holy quotes :star:5
 * [clamp](https://github.com/johnjansen/clamp) - Clamp any Comparable :star:1
 * [crsfml-examples](https://github.com/oprypin/crsfml-examples) - Simple games made with CrSFML :star:47
 * [crystal-benchmarks-game](https://github.com/kostya/crystal-benchmarks-game) - The Computer Language Benchmarks Game :star:78
 * [crystal-by-example](https://github.com/askn/crystal-by-example) - Crystal By Example :star:422
 * [Crystal-Maze](https://github.com/Demonstrandum/Crystal-Maze) - A* Path finding for PNG mazes :star:17
 * [crystal-mysql-crud-example](https://github.com/codenoid/crystal-mysql-crud-example) - Crystal MySQL CRUD example :star:1
 * [crystal-patterns](https://github.com/crystal-community/crystal-patterns) - Examples of GOF patters :star:177
 * [crystalized_ruby](https://github.com/phoffer/crystalized_ruby) - Native Ruby extensions written in Crystal :star:135
 * [crystalworld](https://github.com/vladfaust/crystalworld) - [realworld.io](https://realworld.io) back-end API implementation :star:32
 * [exercism-crystal](https://github.com/exercism/crystal) - Exercism exercises :star:54
 * [jihantoro-cr-mysql](https://github.com/codenoid/jihantoro-cr-mysql) - Crystal MySQL from scratch sample app
 * [jihantoro.sd](https://github.com/codenoid/jihantoro.sd) - Crystal & Kemal version of Serdar Dogruyol blog :star:3
 * [kemal-chat](https://github.com/sdogruyol/kemal-chat) - Build realtime applications with Kemal and WebSocket :star:53
 * [kemal-heroku-example](https://github.com/cagataycali/kemal-heroku-example) - This repository shows, how you can publish your open source apps which powered kemal framework publish as heroku app in seconds :star:3
 * [kemal-mysql-blog](https://github.com/codenoid/kemal-mysql-blog) - Blog written with Crystal, Kemal and MySQL :star:7
 * [kemal-react-chat](https://github.com/f/kemal-react-chat) - Build Realtime Web applications with Kemal and React :star:59
 * [kemal-vue-chat](https://github.com/ChangJoo-Park/kemal-vue-chat) - Build Realtime Web applications with Kemal and Vue.js :star:32
 * [lattice-core-card-game](https://github.com/jasonl99/card_game) - A demo web app for (WebSocket-based) lattice-core :star:139
 * [medley](https://github.com/jwoertink/medley) - A mixture of music related methods :star:13
 * [os-crystal](https://github.com/lbguilherme/os-crystal) - x86 Kernel implemented in Crystal :star:49
 * [realtime-todo-app](https://github.com/Angarsk8/realtime-todo-app) - Realtime Todo application developed with Kemal, Websockets, React, ES2015 and PostgreSQL :star:17
 * [rocky](https://github.com/codingphasedotcom/rocky) - React Over Crystal Kemal and Yarn :star:96
 * [try.cr](https://github.com/maiha/try.cr) - Try monad :star:23

## Feature Flipping
 * [can_use](https://github.com/rodrigopinto/can_use) - It is a minimalist feature toggle/flag for crystal based on yaml :star:5
 * [flipper](https://github.com/metaware/flipper) - Feature flipping/flags/rollouts. Supports multiple backends :star:17

## Framework Components
 * [cr-melon](https://github.com/gdotdesign/cr-melon) - Class based Http APIs :star:11
 * [Crystal-DI](https://github.com/funk-yourself/crystal-di) - Lightweight DI Container :star:25
 * [crystal-mime](https://github.com/spalger/crystal-mime) - Mimetypes for Crystal :star:20
 * [device_detector](https://github.com/creadone/device_detector) - Shard for detect device by user agent string :star:10
 * [Exception Page](https://github.com/crystal-loot/exception_page) - An exceptional exception page for Crystal web libraries and frameworks :star:41
 * [graphql-crystal](https://github.com/ziprandom/graphql-crystal) - [Graphql](http://graphql.org) implementation :star:168
 * [kave](https://github.com/jwoertink/kave) - Kemal API Version Extension :star:29
 * [kemal-auth-token](https://github.com/akwiatkowski/kemal-auth-token) - Kemal middleware to authentication via HTTP header token using JWT :star:22
 * [kemal-monetdb](https://github.com/puppetpies/kemal-monetdb) - MonetDB Data connection for Kemal
 * [kemal-session](https://github.com/kemalcr/kemal-session) - Session handler for Kemal :star:37
 * [mime-types.cr](https://github.com/jwaldrip/mime-types.cr) - A port of the Ruby MIME-types library :star:10
 * [multi-auth](https://github.com/msa7/multi_auth) - Standardized multi-provider OAuth2 authentication (inspired by omniauth) :star:68
 * [praetorian](https://github.com/ilanusse/praetorian) - Minimalist authorization library inspired by Pundit :star:43
 * [request_id](https://github.com/SuperPaintman/request-id) - Middleware for generates / pick up a unique request ID for Crystal servers :star:5
 * [response_time](https://github.com/SuperPaintman/response-time) - Response time for Crystal servers (pure http server, kemal, etc.) :star:8
 * [spec-kemal](https://github.com/kemalcr/spec-kemal) - Easy testing for Kemal :star:40
 * [tourmaline](https://github.com/watzon/tourmaline) - Telegram bot framework with an API loosely based on [telegraf.js](https://telegraf.js.org/)

## Game Development
 * [cray](https://gitlab.com/Zatherz/cray) - Bindings for [raylib](http://www.raylib.com/), an easy-to-use game development library
 * [CrSFML](https://github.com/oprypin/crsfml) - Bindings to [SFML](https://www.sfml-dev.org/) multimedia/game library :star:224
 * [crystal-chipmunk](https://github.com/oprypin/crystal-chipmunk) - Bindings for [Chipmunk](http://chipmunk-physics.net/), a fast and lightweight 2D game physics library :star:28
 * [glove](https://github.com/ddfreyne/glove) - A library for gaming development :star:58
 * [inari](https://github.com/ddfreyne/inari) - A collection of games using Glove as the game engine :star:14
 * [mos_game](https://github.com/bararchy/mos_game) - Mini Offline Singleplayer game :star:15

## GUI library
 * [hedron](https://github.com/Qwerp-Derp/hedron) - An extendable GUI library, with markup language capabilities :star:79
 * [libui.cr](https://github.com/Fusion/libui.cr) - Bindings for [libui](https://github.com/andlabs/libui) :star:8871
 * [qt5.cr](https://github.com/Papierkorb/qt5.cr) - Qt5 bindings for Crystal, based on Bindgen :star:135

## HTML Builders
 * [form_builder.cr](https://github.com/westonganger/form_builder.cr) - Dead simple HTML form builder for Crystal with built-in support for many popular UI libraries such as Bootstrap :star:14
 * [html_builder](https://github.com/crystal-lang/html_builder) - DSL for creating HTML :star:36

## HTML/XML Parsing
 * [crystagiri](https://github.com/madeindjs/Crystagiri) - An Html Reader / parser like [Nokogiri](https://github.com/sparklemotion/nokogiri) Ruby gem :star:105
 * [gumbo-crystal](https://github.com/blocknotes/gumbo-crystal) - Bindings for [Gumbo](https://github.com/google/gumbo-parser), an HTML5 parsing library made by Google :star:1
 * [hq.cr](https://github.com/maiha/hq.cr) - Simple wrapper for crystal-xml :star:6
 * [myhtml](https://github.com/kostya/myhtml) - Fast HTML5 Parser that includes CSS selectors :star:97

## HTTP
 * [arachnid](https://github.com/watzon/arachnid) - Powerful web scraping framework :star:48
 * [Cable](https://github.com/cable-cr/cable) - An ActionCable "port" to Crystal, framework agnostic, 100% compatible with the ActionCable JS Client :star:42
 * [cossack](https://github.com/crystal-community/cossack) - Simple flexible HTTP client :star:93
 * [crest](https://github.com/mamantoha/crest) - Simple HTTP and REST client, inspired by the Ruby's RestClient gem :star:113
 * [crul](https://github.com/porras/crul) - Command line HTTP client :star:103
 * [cryload](https://github.com/sdogruyol/cryload) - HTTP benchmarking tool :star:110
 * [halite](https://github.com/icyleaf/halite) - Crystal HTTP Requests with a chainable REST API, built-in sessions and loggers :star:120
 * [helmet](https://github.com/EvanHahn/crystal-helmet) - Set security-related HTTP headers :star:20
 * [http-multiserver.cr](https://github.com/vladfaust/http-multiserver.cr) - Mounting multiple servers via routes (a.k.a. URL mapping) :star:16
 * [http-params-serializable](https://github.com/vladfaust/http-params-serializable) - HTTP params (de)serialization, applicable to URL queries and URL-encoded forms :star:14
 * [http-protection](https://github.com/rogeriozambon/http-protection) - Protection against typical web attacks :star:42
 * [http2](https://github.com/ysbaddaden/http2) - HTTP/2 Protocol Implementation :star:71
 * [HTTP::Client](https://crystal-lang.org/api/HTTP/Client.html) - HTTP client (Crystal stdlib)
 * [HTTP::Server](https://crystal-lang.org/api/HTTP/Server.html) - HTTP server (Crystal stdlib)
 * [HTTP::WebSocket](https://crystal-lang.org/api/HTTP/WebSocket.html) - HTTP WebSocket client (Crystal stdlib)
 * [keyer_cr](https://github.com/danielpclark/keyer_cr) - Adds HTTP GET/POST parameter parsing as a Hash-like object
 * [ngrok.cr](https://github.com/watzon/ngrok.cr) - Ngrok wrapper :star:14
 * [params](https://github.com/vladfaust/params.cr) - The strongly-typed HTTP params parsing module :star:14
 * [resp-crystal](https://github.com/soveran/resp-crystal) - Lightweight RESP client :star:7
 * [sse.cr](https://github.com/y2k2mt/sse.cr) - [Server-Sent Events](https://www.w3.org/TR/2009/WD-eventsource-20090421) client :star:3

## Image processing
 * [magickwand-crystal](https://github.com/blocknotes/magickwand-crystal) - Bindings for [MagickWand](https://www.imagemagick.org/script/magick-wand.php), the C interface for ImageMagick processing libraries :star:47
 * [stumpy_gif](https://github.com/stumpycr/stumpy_gif) - Write (animated) GIF images :star:8
 * [stumpy_png](https://github.com/stumpycr/stumpy_png) - Read and write PNG images :star:70

## Implementations/Compilers
 * [charly](https://github.com/charly-lang) - Charly Programming Language
 * [cibyl](https://github.com/senselogic/CIBYL) - Lightweight curly-bracket language which compiles to Ruby and Crystal :star:34
 * [cltk](https://github.com/ziprandom/cltk) - A crystal port of the Ruby Language Toolkit :star:59
 * [cppize](https://github.com/unn4m3d/cppize) - Crystal-to-C++ transpiler :star:28
 * [crisp](https://github.com/rhysd/Crisp) - Lisp dialect implemented with Crystal :star:24
 * [crow](https://github.com/geppetto-apps/crow) - Transpile/compile Crystal to [Flow](https://flow.org/)
 * [LinCAS-lang](https://github.com/LinCAS-lang) - A programming language for scientific computation
 * [mint-lang](https://github.com/mint-lang/mint) - A refreshing programming language for the front-end web :star:1287
 * [myst-lang](https://github.com/myst-lang/) - A practical, dynamic language designed to be written and understood as easily and efficiently as possible
 * [NuummiteOS](https://github.com/TheKernelCorp/NuummiteOS) - An OS written in Crystal as a Proof of Concept :star:62
 * [runic-lang](https://github.com/runic-lang) - In-design toy language

## Logging and monitoring
 * [crafana](https://github.com/spoved/crafana.cr) - A [Grafana](https://grafana.com/) library to help autogenerate dashboards :star:7
 * [crometheus](https://gitlab.com/ezrast/crometheus) - A [Prometheus](https://prometheus.io/) client library
 * [crystal-logreader](https://github.com/arcage/crystal-logreader) - Tailing log file :star:1
 * [fluent-logger-crystal](https://github.com/TobiasGSmollett/fluent-logger-crystal) - A structured logger for [Fluentd](https://www.fluentd.org/)
 * [instana](https://github.com/instana/crystal-sensor) - A metrics and distributed trace collector for [Instana](https://www.instana.com/)
 * [katip](https://github.com/guvencenanguvenal/katip) - JSONbase logger :star:21
 * [Logger](https://crystal-lang.org/api/Logger.html) - logging utility (Crystal stdlib)
 * [statsd.cr](https://github.com/miketheman/statsd.cr) - [Statsd](https://github.com/etsy/statsd) client library :star:23
 * [syslog.cr](https://github.com/comandeo/syslog.cr) - Implementation of Syslog client :star:12

## Machine Learning
 * [ai4cr](https://github.com/drhuffman12/ai4cr) - Artificial Intelligence (based on https://github.com/SergioFierens/ai4r) :star:14
 * [Cadmium](https://github.com/watzon/cadmium) - NLP library based heavily on [natural](https://github.com/NaturalNode/natural) :star:8758
 * [crystal-fann](https://github.com/NeuraLegion/crystal-fann) - FANN (Fast Artifical Neural Network) binding :star:73
 * [crystal-learn](https://github.com/pbrusco/crystal-learn) - Sklearn-like machine-learning library :star:33
 * [shainet](https://github.com/NeuraLegion/shainet) - SHAInet (Neural Network in pure crystal) :star:100
 * [tensorflow.cr](https://github.com/fazibear/tensorflow.cr) - Bindings for [TensorFlow](https://github.com/tensorflow/tensorflow) :star:133017

## Markdown/Text Processors
 * [html-pipeline](https://github.com/huacnlee/html-pipeline) - HTML processing filters and utilities :star:7
 * [markd](https://github.com/icyleaf/markd) - Yet another markdown parser built for speed, Compliant to CommonMark specification :star:33

## Misc
 * [aasm.cr](https://github.com/veelenga/aasm.cr) - Easy to use finite state machine for Crystal classes :star:33
 * [any_hash.cr](https://github.com/Sija/any_hash.cr) - Recursive Hash with better JSON::Any included :star:20
 * [atomic_write.cr](https://github.com/chris-huxtable/atomic_write.cr) - Library for writing or apppending files atomically :star:7
 * [burocracia.cr](https://github.com/vnbrs/burocracia.cr) - burocracia.cr the dependecyless shard to validate, generate and format Brazilian burocracias such as CPF, CNPJ and CEP :star:19
 * [callbacks](https://github.com/vladfaust/callbacks.cr) - Expressive callbacks module :star:7
 * [circuit_breaker](https://github.com/TPei/circuit_breaker) - Implementation of the circuit breaker pattern :star:19
 * [compiled_license](https://github.com/elorest/compiled_license) - Compiles licenses into binary for complience with MIT when copying binary to system or container without the code :star:3
 * [crystal-binary_parser](https://github.com/DanSnow/crystal-binary_parser) - Binary parser :star:14
 * [crystal-web-framework-stars](https://github.com/isaced/crystal-web-framework-stars) - Web frameworks for Crystal, most starred on Github :star:3
 * [crz](https://github.com/dhruvrajvanshi/crz) - Functional programming library :star:60
 * [emoji.cr](https://github.com/veelenga/emoji.cr) - Emoji library :star:33
 * [hoop](https://github.com/0x73/hoop) - Building native OSX apps :star:196
 * [i18n.cr](https://github.com/vladfaust/i18n.cr) - Internationalization shard :star:17
 * [immutable](https://github.com/lucaong/immutable) - Implementation of thread-safe, persistent, immutable collections :star:153
 * [inflector.cr](https://github.com/phoffer/inflector.cr) - Singularize, pluralize, camelize, etc (port from ActiveSupport) :star:30
 * [lirith](https://github.com/lirith-engine/lirith) - Graphics engine :star:24
 * [m3u8](https://github.com/akiicat/m3u8) - Generate and parse m3u8 playlists for HTTP Live Streaming :star:4
 * [manual-generator](https://github.com/blocknotes/manual-generator) - Tool to generate PDF manuals from documentation sites
 * [message_verifier.cr](https://github.com/danielwestendorf/message_verifier.cr) - Verify and generate Rails `ActiveSupport::MessageVerifier` signed tokens :star:13
 * [monads](https://github.com/alex-lairan/monads) - Monad implementation :star:16
 * [pangu.cr](https://github.com/isaced/pangu.cr) - Paranoid text spacing in Crystal :star:1
 * [pinger](https://github.com/spider-gazelle/pinger) - Ping IP addresses and DNS entries without requiring sudo :star:5
 * [port_midi](https://github.com/jimm/crystal_port_midi) - Crystal C bindings for the PortMIDI cross-platform MIDI I/O library :star:2
 * [raytracer](https://github.com/l3kn/raytracer) - CPU Raytracer with examples :star:36
 * [retriable.cr](https://github.com/Sija/retriable.cr) - Simple DSL to retry failed code blocks :star:12
 * [tren](https://github.com/sdogruyol/tren) - Give your SQL some love :star:89
 * [ulid](https://github.com/SuperPaintman/ulid) - Universally Unique Lexicographically Sortable Identifier (ULID) :star:18

## Network Protocols
 * [bson.cr](https://github.com/jeromegn/bson.cr) - Native BSON implementation :star:20
 * [Crirc](https://github.com/Meoowww/Crirc) - IRC protocol implementation (Client, Server, Bots) :star:16
 * [crystal-json-socket](https://github.com/foi/crystal-json-socket) - JSON-socket client & server implementation. Inspired by and compatible with [node-json-socket](https://github.com/sebastianseilund/node-json-socket/) and [ruby-json-socket](https://github.com/foi/ruby-json-socket) :star:2
 * [crystal-snmp](https://github.com/spider-gazelle/crystal-snmp) - An SNMP implementation with version 1, 2c and 3 support :star:2
 * [fast_irc.cr](https://github.com/RX14/fast_irc.cr) - Fast IRC parser/generator :star:11
 * [gopher.cr](https://github.com/anicholson/gopher.cr) - Gopher server toolkit :star:3
 * [jwt](https://github.com/crystal-community/jwt) - Implementation of JWT (JSON Web Token) :star:123
 * [msgpack-crystal](https://github.com/crystal-community/msgpack-crystal) - MessagePack library :star:102
 * [OAuth](https://crystal-lang.org/api/OAuth.html) - OAuth consumer (Crystal stdlib)
 * [OAuth2](https://crystal-lang.org/api/OAuth2.html) - OAuth2 client (Crystal stdlib)
 * [OpenSSL](https://crystal-lang.org/api/OpenSSL.html) - bindings to libssl (Crystal stdlib)
 * [Socks](https://github.com/wontruefree/socks) - SOCKS proxy :star:12
 * [transfer_more](https://git.sceptique.eu/Sceptique/transfer_more) - Clone of transfer.sh to uploads files

## Networking
 * [ipaddress.cr](https://github.com/Sija/ipaddress.cr) - Library to handle IPv4 and IPv6 addresses :star:25

## ORM/ODM Extensions
 * [clear](https://github.com/anykeyh/clear) - ORM specialized to PostgreSQL only but with advanced features :star:124
 * [granite](https://github.com/amberframework/granite) - ORM for Postgres, Mysql, Sqlite :star:178
 * [jennifer.cr](https://github.com/imdrasil/jennifer.cr) - Active Record pattern implementation with flexible query chainable builder and migration system :star:220
 * [ohm-crystal](https://github.com/soveran/ohm-crystal) - Object-hash mapping library for Redis :star:55
 * [onyx-sql](https://github.com/onyxframework/sql) - DB-agnostic SQL ORM with beautiful DSL and type-safe Query builder :star:84
 * [record](https://github.com/luckyframework/record) - Type safe querying, saving and updating :star:51
 * [redis-tsv.cr](https://github.com/maiha/redis-tsv.cr) - Import and export data from Redis in TSV format :star:4
 * [rethinkdb-orm](https://github.com/spider-gazelle/rethinkdb-orm) - ORM for RethinkDB / RebirthDB :star:4
 * [stal-crystal](https://github.com/soveran/stal-crystal) - Set algebra solver for Redis :star:3
 * [topaz](https://github.com/topaz-crystal/topaz) - A simple and useful db wrapper :star:55

## Package Management
 * [CRelease](https://github.com/elorest/crelease) - Version and git tag manager that makes shard releases easy :star:15
 * [shards](https://github.com/crystal-lang/shards) - Dependency manager for the Crystal :star:554

## Processes and Threads
 * [await_async](https://github.com/anykeyh/await_async) - Add keywords await & async in Crystal Lang :star:43
 * [crystal-futures](https://github.com/dhruvrajvanshi/crystal-futures) - Future type implementation :star:50
 * [neph](https://github.com/tbrand/neph) - A modern command line job processor that can execute jobs concurrently :star:151
 * [promise](https://github.com/spider-gazelle/promise) - A Promise implementation with type inference :star:15

## Project Generators
 * [bindgencr](https://github.com/TechMagister/bindgencr) - Generator of bindings based on castxml output :star:1
 * [crystal_lib](https://github.com/crystal-lang/crystal_lib) - Automatic binding generator for native libraries :star:107
 * [fez](https://github.com/jwoertink/fez) - A Kemal application generator :star:35
 * [kgen](https://github.com/kemalyst/kemalyst-generator) - Kemalyst command line tool for console, init, generate (scaffolding), and watch. :star:12
 * [libgen](https://github.com/olbat/libgen) - Automatic bindings generator configured using JSON/YAML files :star:38
 * [wasp](https://github.com/icyleaf/wasp) - Static Site Generator :star:13

## Queues and Messaging
 * [amqp.cr](https://github.com/datanoise/amqp.cr) - AMQP 0.9.1 client with RabbitMQ extensions :star:52
 * [dispatch](https://github.com/bmulvihill/dispatch) - In memory asynchronous job processing :star:21
 * [mosquito](https://github.com/robacarp/mosquito/) - Redis backed periodic and ad hoc job processing :star:87
 * [sidekiq.cr](https://github.com/mperham/sidekiq.cr) - Simple, efficient job processing :star:576

## Routing
 * [crouter](https://github.com/jreinert/crouter) - A standalone router :star:49
 * [orion](https://github.com/obsidian/orion) - A minimal, rails-esque routing library :star:63
 * [router.cr](https://github.com/tbrand/router.cr) - Minimum but powerful http router for HTTP::Server :star:195
 * [toro](https://github.com/soveran/toro) - Tree Oriented Routing :star:69

## Scheduling
 * [cron_scheduler](https://github.com/kostya/cron_scheduler) - Job scheduler with crontab patterns :star:33
 * [crystime](https://gitlab.com/crystallabs/crystime) - Advanced time, calendar, schedule, and remind library
 * [schedule.cr](https://github.com/hugoabonizio/schedule.cr) - Run periodic tasks :star:55
 * [tasker](https://github.com/spider-gazelle/tasker) - A high precision scheduler including timezone aware cron jobs :star:11

## Science and Data analysis
 * [linalg](https://github.com/konovod/linalg) - Linear algebra library inspired by MATLAB and SciPy.linalg :star:31
 * [predict.cr](https://github.com/RX14/predict.cr) - Satellite prediction library using the sgp4 model :star:11
 * [stats](https://git.sceptique.eu/Sceptique/stats) - An expressive implementation of statistical distributions

## Search
 * [hermes](https://github.com/imdrasil/hermes.cr) - Data Mapper pattern implementation for ElastiSearch :star:21
 * [query-builder](https://github.com/izniburak/query-builder) - Sql Query Builder library :star:45
 * [query.cr](https://github.com/waterlink/query.cr) - Query abstraction :star:13
 * [soegen](https://github.com/Ragmaanir/soegen) - Elasticsearch client for Crystal similar to the stretcher gem for ruby :star:18

## Serverless Computing
 * [crystal_openfaas](https://github.com/TPei/crystal_openfaas/) - Template to enable crystal as first class citizens in OpenFaaS :star:9
 * [FaaStRuby](https://faastruby.io) - Serverless Software Development Platform for Ruby and Crystal.
 * [gcf.cr](https://github.com/sam0x17/gcf.cr) - Managed execution of Crystal in Google Cloud Functions :star:47

## System
 * [baked_file_system](https://github.com/schovi/baked_file_system) - Virtual file system implementation :star:106
 * [hardware](https://github.com/crystal-community/hardware) - Get CPU, Memory and Network informations of the running OS and its processes :star:32
 * [rcpu](https://github.com/ddfreyne/rcpu) - A virtual machine emulator and assembler :star:37

## Task management
 * [cake](https://github.com/axvm/cake) - Production-ready Make-like utility tool :star:33
 * [sam](https://github.com/imdrasil/sam.cr) - Another one Rake-like task manager with namespacing and arguments system :star:44

## Template Engine
 * [crinja](https://github.com/straight-shoota/crinja) - An implementation of the [Jinja2 template engine](http://jinja.pocoo.org/)
 * [crustache](https://github.com/MakeNowJust/crustache) - [{{Mustache}}](https://mustache.github.io) for Crystal :star:53
 * [ECR (Embedded Crystal)](https://crystal-lang.org/api/ECR.html) - compile time template language which uses plain crystal expressions (Crystal stdlib)
 * [Kilt](https://github.com/jeromegn/kilt) - Abstraction layer for template engines :star:104
 * [Slang](https://github.com/jeromegn/slang) - Lightweight, terse, templating language inspired by Ruby's Slim :star:160
 * [teeplate](https://github.com/mosop/teeplate) - A library for rendering multiple template files :star:9
 * [temel](https://github.com/f/temel) - Extensible HTML::Builder alternative for Crystal, supports custom tag definitions :star:46

## Testing
 * [coverage](https://github.com/anykeyh/crystal-coverage) – Generate cover report for your crystal code
 * [crotest](https://github.com/emancu/crotest) - A tiny and simple test framework :star:20
 * [crystal-clear](https://github.com/Groogy/crystal-clear) - Design by Contract Library :star:32
 * [crytic](https://github.com/hanneskaeufler/crytic) - Mutation testing framework :star:38
 * [LuckyFlow](https://github.com/luckyframework/lucky_flow) - Automated browser tests similar to Capybara :star:34
 * [mass-spec](https://github.com/c910335/mass-spec) - Web API testing library :star:4
 * [microtest](https://github.com/Ragmaanir/microtest) - Small opinionated testing library focusing on power asserts :star:17
 * [minitest.cr](https://github.com/ysbaddaden/minitest.cr) - Library for unit tests and assertions :star:93
 * [mocks.cr](https://github.com/waterlink/mocks.cr) - Mocking library for Crystal :star:34
 * [Spec](https://crystal-lang.org/api/Spec.html) - spec framework (Crystal stdlib)
 * [spectator](https://gitlab.com/arctic-fox/spectator) - Feature rich spec framework that uses the modern expect syntax
 * [timecop.cr](https://github.com/crystal-community/timecop.cr) - Library for mocking with `Time.now`. Inspired by the [timecop ruby gem](https://github.com/travisjeffery/timecop) :star:2865
 * [vcr](https://github.com/spoved/vcr.cr) - A HTTP capture and replay implementation for crystal :star:26
 * [webdriver_pump](https://github.com/bwilczek/webdriver_pump) - Page Object library. Inspired by Ruby's [WatirPump](https://github.com/bwilczek/watir_pump) :star:12
 * [webmock.cr](https://github.com/manastech/webmock.cr) - Library for stubbing `HTTP::Client` requests :star:72

## Third-party APIs
 * [aws-credentials](https://github.com/y2k2mt/aws-credentials) - Get AWS credentials in various ways :star:2
 * [aws-signer.cr](https://github.com/beanieboi/aws-signer.cr) - This library signs your HTTP requests using AWS v4 :star:7
 * [awscr-s3](https://github.com/taylorfinnell/awscr-s3) - AWS S3 interface :star:48
 * [awscr-signer](https://github.com/taylorfinnell/awscr-signer) - Sign HTTP::Request objects and generate presigned post forms :star:10
 * [bugsnag.cr](https://github.com/gewo/bugsnag.cr) - Bugsnag exception notifier and sidekiq middleware :star:5
 * [crystal-darksky](https://github.com/sb89/crystal-darksky) - Wrapper for the [Dark Sky](https://darksky.net) API :star:5
 * [crystal-github](https://github.com/felipeelias/crystal-github) - Wrapper for the [Github](https://github.com/) API :star:5
 * [crystal-monzo](https://github.com/barisbalic/crystal-monzo) - A client for the [Monzo API](https://monzo.com/docs/)
 * [crystal-swapi](https://github.com/sb89/crystal-swapi) - Star Wars API (SWAPI) wrapper :star:2
 * [crystal_slack](https://github.com/manastech/crystal_slack) - A tool that parses Slack slash commands or send incoming web hooks :star:15
 * [discordcr](https://github.com/meew0/discordcr) - A minimalist Discord API library :star:98
 * [GDAX](https://github.com/mccallofthewild/gdax) - GDAX REST and WebSocket API Wrapper with request signing :star:4
 * [gitlab.cr](https://github.com/icyleaf/gitlab.cr) - GitLab API wrapper :star:18
 * [google_maps_api](https://github.com/fridgerator/google_maps_api) - Google Maps API :star:12
 * [hncr](https://github.com/Gangwolf/hncr) - A Hacker News API wrapper :star:2
 * [kube-client.cr](https://github.com/spoved/kube-client.cr) - Kubernetes API Client :star:1
 * [mixpanel-crystal](https://github.com/petoem/mixpanel-crystal) - A library for sending events to Mixpanel
 * [nexmo-crystal](https://github.com/timcraft/nexmo-crystal) - [Nexmo REST API](https://developer.nexmo.com/) client :star:1
 * [open_exchange_rates](https://github.com/osfx/open_exchange_rates) - A library to access [Open Exchange Rates](https://openexchangerates.org/) API :star:11
 * [pinboard.cr](https://github.com/oz/pinboard.cr) - [Pinboard](https://pinboard.in) API :star:4
 * [raven.cr](https://github.com/sija/raven.cr) - Raven is a client for [Sentry](https://github.com/getsentry/sentry) :star:21883
 * [slack.cr](https://github.com/DougEverly/slack.cr) - A Slack [Real Time Messaging API](https://api.slack.com/rtm) WebSocket client library :star:14
 * [telegram_bot](https://github.com/hangyas/telegram_bot) - A wrapper for the Telegram Bot API :star:68
 * [twitter-crystal](https://github.com/sferik/twitter-crystal) - A library to access the Twitter API :star:69
 * [ynab.cr](https://github.com/jaredsmithse/ynab.cr) - A library to interact with your YNAB data :star:2

## Validation
 * [accord](https://github.com/neovintage/accord) - Shareable validation library for Crystal Objects :star:20
 * [CrSerializer](https://github.com/blacksmoke16/CrSerializer) - Extensible annotation based serialization/deserialization/validation library :star:25
 * [denetmen](https://github.com/izniburak/denetmen) - Micro check library that patches Crystal stdlib :star:24
 * [validations](https://github.com/vladfaust/validations.cr) - Validations mixin :star:8

## Web Frameworks
 * [amber](https://github.com/amberframework/amber) - Open source efficient and cohesive web application framework :star:1813
 * [athena](https://github.com/blacksmoke16/athena) - Modular, annotation based, API oriented framework with built in param conversion :star:48
 * [kemal](https://github.com/kemalcr/kemal) - Lightning Fast, Super Simple web framework. Inspired by Sinatra :star:2642
 * [lattice-core](https://github.com/jasonl99/lattice-core) - A WebSocket-first object-oriented framework (based on Kemal) :star:55
 * [lucky](https://github.com/luckyframework/lucky) - Catch bugs early, forget about most performance issues, and spend more time on code instead of debugging and writing tests :star:1467
 * [onyx-rest](https://github.com/onyxframework/rest) - REST API framework with type-safe params and separate business and rendering layers, based on [onyx-http](https://github.com/onyxframework/http) :star:124
 * [raze](https://github.com/samueleaton/raze) - Modular, light web framework :star:155
 * [spider-gazelle](https://github.com/spider-gazelle/spider-gazelle) - A Rails esque web framework with a focus on speed and extensibility :star:67

## Web Servers
 * [fast-http-server](https://github.com/sdogruyol/fast-http-server) - Super fast, zero configuration command line HTTP Server :star:138
 * [prax.cr](https://github.com/ysbaddaden/prax.cr) - Rack proxy server for development :star:128
 * [salt](https://github.com/icyleaf/salt) - A Human Friendly Interface for HTTP server :star:19
 * [serve](https://github.com/SuperPaintman/serve) - Command line static HTTP server :star:19

# Community
 * [Crystal weekly newsletters](http://crystalweekly.com/)
 * [Gitter](https://gitter.im/crystal-lang/crystal)
 * [Google Group](https://groups.google.com/forum/?fromgroups#!forum/crystal-lang)
 * [IRC](http://irc.lc/freenode/crystal-lang) - #crystal-lang on Freenode
 * [Metaruby](https://metaruby.com/c/crystal-forum) - Crystal Forum on Metaruby
 * [Reddit](https://www.reddit.com/r/crystal_programming/)
 * [Stackoverflow](https://stackoverflow.com/tags/crystal-lang/info)

## Unofficial
 * [Russian-speaking Telegram Group](https://t.me/crystal_ru) - Добро пожаловать, товарищ!

# Resources
 * [Crystal for Rubyists](http://www.crystalforrubyists.com/) - Free book to bootstrap your Crystal journey
 * [Crystal Mastery](https://crystalmastery.io/) - Screencasts for learning Crystal
 * [crystal-lang.org](https://crystal-lang.org) - Official language site
 * [devdocs.io](https://devdocs.io/crystal/) - API Documentation Browser with Crystal support
 * [getgood.at](https://getgood.at/crystal/in-a-day) - Learn Crystal in a Day
 * [Programming Crystal](https://pragprog.com/book/crystal/programming-crystal) - PragProg book to start your Crystal journey

## Official Documentation Translations
 * [br.crystal-lang.org](http://br.crystal-lang.org/) - Brazilian
 * [ja.crystal-lang.org](http://ja.crystal-lang.org/) - Japanese
 * [kr.crystal-lang.org](https://kr.crystal-lang.org/) - Korean
 * [ru.crystal-lang.org](http://ru.crystal-lang.org/) - Russian
 * [tw.crystal-lang.org](http://tw.crystal-lang.org/) - Chinese Traditional

# Services and Apps
 * [carc.in](https://carc.in/) - A web service that runs your code and displays the result
 * [cry](https://github.com/elorest/cry) - Ability to execute crystal code in a fashion similar to Ruby's pry edit :star:16
 * [Crystal [ANN]](https://crystal-ann.com) - Announce new project, blog post, version update or any other Crystal work
 * [crystalshards.herokuapp.com](https://crystalshards.herokuapp.com/), [crystalshards.xyz](http://crystalshards.xyz/) - Web services that list all available Crystal shards
 * [Crystular](http://www.crystular.org) - Regular expression tester
 * [DeBot](https://github.com/jhass/DeBot) - IRC bot written in Crystal :star:34
 * [Fluence](https://github.com/crystallabs/fluence) - WYSIWYG wiki using markdown and Git :star:26
 * [icr](https://github.com/crystal-community/icr) - Interactive console for Crystal (like IRB for Ruby) :star:377
 * [Invidious](https://github.com/omarroth/invidious) - Invidious is an alternative front-end to YouTube :star:1131
 * [mpngin](https://github.com/thewalkingtoast/mpngin) - A URL shortener with simple stats :star:19
 * [nes](https://github.com/romeroadrian/nes.cr) - A NES emulator :star:41
 * [quicktype](https://quicktype.io/) - Generate models and serializers from JSON, JSON Schema, GraphQL, and TypeScript
 * [shards.info](http://shards.info/) - Web service that lists all repositories on GitHub that have Crystal code in them. The sources are available on [GitHub](https://github.com/mamantoha/shards-info) :star:15
 * [wikicr](https://git.sceptique.eu/Sceptique/wikicr) - Wiki using git to manage revisions

# Tools
 * [ast_helper](https://github.com/bcardiff/crystal-ast-helper) - Helper tool to debug parser and formatter :star:12
 * [crystal-base](https://github.com/ruivieira/crystal-base) - CentOS base docker image for Crystal development :star:1
 * [crystal-ctags](https://github.com/SuperPaintman/crystal-ctags) - Ctags generator for Crystal :star:10
 * [crystal-dash-docset](https://github.com/Sija/crystal-dash-docset) - [Dash](https://kapeli.com/dash) docset generator :star:6
 * [helptransl8](https://github.com/papilip/helptransl8) - Tool for document translators :star:6

## DevOps
 * [ansible-crystal](https://github.com/CorbanR/ansible-crystal) - Ansible playbook for installing crystal :star:6
 * [capistrano-kemal](https://github.com/bitfex/capistrano-kemal) - Capistrano Plugin for Kemal :star:5
 * [crystal-cookbook](https://github.com/vjdhama/crystal-cookbook) - Chef cookbook for installing crystal :star:5
 * [DPPM](https://github.com/DFabric/dppm) - An easy, universal way to install and manage applications as packages (mostly Linux) :star:51

## Editor Plugins
 * Atom
   * [crystal-tools](https://atom.io/packages/crystal-tools) - Enables built in tools in Crystal compiler
   * [language-crystal-actual](https://atom.io/packages/language-crystal-actual) - Crystal language support in Atom
 * Emacs
   * [emacs-crystal-mode](https://github.com/dotmilk/emacs-crystal-mode) - Crystal language support for Emacs :star:16
   * [play-crystal.el](https://github.com/veelenga/play-crystal.el) - [play.crystal-lang.org](https://play.crystal-lang.org/#/cr) integration in Emacs :star:5
 * [scry](https://github.com/crystal-lang-tools/scry) - Code analysis server for Crystal implementing the [Language Server Protocol](https://microsoft.github.io/language-server-protocol/)
 * Spacemacs
   * [crystal-spacemacs-layer](https://github.com/juanedi/crystal-spacemacs-layer) - Spacemacs contribution layer for Crystal :star:11
 * Sublime
   * [sublime-crystal](https://github.com/crystal-lang-tools/sublime-crystal) - Crystal syntax highlighting for sublime Text :star:68
 * TextMate
   * [Crystal.tmbundle](https://github.com/crystal-lang-tools/Crystal.tmbundle) - Crystal syntax highlighting, compile, format command, snippets :star:13
 * Vim
   * [carcin.vim](https://github.com/MakeNowJust/carcin.vim) - Vim plugin to provide utility functions for carc.in :star:4
   * [vim-crystal](https://github.com/rhysd/vim-crystal) - Vim filetype support for Crystal :star:268
   * [vim-slang](https://github.com/elorest/vim-slang) - Vim filetype support for Slang Templating Engine :star:9
 * Visual Studio Code
   * [vscode-crystal](https://github.com/g3ortega/vscode-crystal) - Crystal language support in VSCode :star:11
   * [vscode-crystal-ide](https://github.com/crystal-lang-tools/crystal-ide) - Crystal IDE powered by [Language Server Protocol](https://code.visualstudio.com/blogs/2016/06/27/common-language-protocol)
   * [vscode-crystal-lang](https://github.com/crystal-lang-tools/vscode-crystal-lang) - Formatter, linter and syntax highlighting for `cr` and `ecr` files :star:126

## Shell plugins
 * [crun](https://github.com/Val/crun) - Crystal Run : shebang wrapper for Crystal :star:17
 * [crystal-zsh](https://github.com/veelenga/crystal-zsh) - .oh-my-zsh plugin :star:20


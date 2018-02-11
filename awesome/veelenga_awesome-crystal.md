# Information comes from [veelenga/awesome-crystal](https://github.com/veelenga/awesome-crystal)
# Awesome Crystal
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://api.travis-ci.org/veelenga/awesome-crystal.svg)](https://travis-ci.org/veelenga/awesome-crystal)

A curated list of awesome Crystal code and resources. Inspired by [awesome](https://github.com/sindresorhus/awesome) and [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).
The goal is to have projects mostly stable and useful for the community.

Search [Crystal Shards](https://crystalshards.xyz) or follow announcements [Crystal [ANN]](https://crystal-ann.com) for more.

Contributions are welcome. Please take a quick look at the [contribution guidelines](https://github.com/veelenga/awesome-crystal/blob/master/.github/CONTRIBUTING.md) first.

* [Awesome Crystal](#awesome-crystal)
  * [Algorithms and Data structures](#algorithms-and-data-structures)
  * [Api Builders](#api-builders)
  * [C Bindings](#c-bindings)
  * [Caching](#caching)
  * [Cli Builders](#cli-builders)
  * [Cli Utils](#cli-utils)
  * [Configuration](#configuration)
  * [Converters](#converters)
  * [Data Generators](#data-generators)
  * [Database Drivers/Clients](#database-driversclients)
  * [Database Tools](#database-tools)
  * [Development Tools](#development-tools)
  * [Email](#email)
  * [Environment Management](#environment-management)
  * [Examples and funny stuff](#examples-and-funny-stuff)
  * [Feature Flipping](#feature-flipping)
  * [Framework Components](#framework-components)
  * [Game Development](#game-development)
  * [GUI library](#gui-library)
  * [HTML/XML parsing](#htmlxml-parsing)
  * [HTTP](#http)
  * [Image Processing](#image-processing)
  * [Implementations/Compilers](#implementationscompilers)
  * [Logging and monitoring](#logging-and-monitoring)
  * [Machine Learning](#machine-learning)
  * [Markdown/Text Processors](#markdowntext-processors)
  * [Misc](#misc)
  * [Networking](#networking)
  * [ORM/ODM Extensions](#ormodm-extensions)
  * [Package Management](#package-management)
  * [Processes and Threads](#processes-and-threads)
  * [Project Generators](#project-generators)
  * [Queue](#queue)
  * [Routing](#routing)
  * [Scheduling](#scheduling)
  * [Science and Data analysis](#science-and-data-analysis)
  * [Search](#search)
  * [Task management](#task-management)
  * [Template Engine](#template-engine)
  * [Testing](#testing)
  * [Third-party APIs](#third-party-apis)
  * [Virtualization](#virtualization)
  * [Web Frameworks](#web-frameworks)
  * [Web Servers](#web-servers)
* [Community](#community)
* [Resources](#resources)
  * [Official Documentation Translations](#official-documentation-translations)
* [Services and Apps](#services-and-apps)
* [Tools](#tools)
  * [DevOps](#devops)
  * [Editor Plugins](#editor-plugins)
  * [Shell Plugins](#shell-plugins)

## Algorithms and Data structures
 * [aho_corasick](https://github.com/chenkovsky/aho_corasick) - AhoCorasick algorithm :star:1
 * [crystal-diff](https://github.com/MakeNowJust/crystal-diff) - A Crystal sequence differencing implementation :star:18
 * [crystal-linked-list](https://github.com/abvdasker/crystal-linked-list) - Implementation of Linked List :star:5
 * [crystaledge](https://github.com/unn4m3d/crystaledge) - A pure Vector Math library :star:7
 * [crystalg](https://github.com/TobiasGSmollett/crystalg) - A Generic Algorithm Library :star:11
 * [crystalline](https://github.com/jtomschroeder/crystalline) - A collection of containers and algorithms :star:82
 * [delimiter_tree](https://github.com/drujensen/delimiter_tree) - A tree structure that is built using a delimiter :star:7
 * [edits.cr](https://github.com/tcrouch/edits.cr) - Collection of edit distance algorithms :star:7
 * [hash_ring](https://github.com/TobiasGSmollett/hash_ring) - An Implementation of Consistent Hash Ring
 * [markov](https://github.com/mccallofthewild/markov) - Build Markov Chains and run Markov Processes :star:8
 * [miller_rabin](https://github.com/kuende/miller_rabin) - Implements [Miller-Rabin](https://en.wikibooks.org/wiki/Algorithm_Implementation/Mathematics/Primality_Testing) algorithm to check if a number is prime
 * [multiset.cr](https://github.com/tcrouch/multiset.cr) - Implementation of a multiset :star:1
 * [murmur3](https://github.com/kuende/murmur3) - Implementation of Murmur3 hash algorithm used by Cassandra :star:2
 * [oak](https://github.com/obsidian/oak) - A flexible Radix Tree implementation :star:3
 * [radix](https://github.com/luislavena/radix) - Radix Tree implementation :star:35
 * [ternary_search_tree](https://github.com/johnjansen/ternary_search_tree) - Ternary Search Tree :star:1
 * [text](https://github.com/johnjansen/text) - A collection of text algorithms :star:14

## Api Builders
 * [kemal-rest-api](https://github.com/blocknotes/kemal-rest-api) - A library to create RESTful API with Kemal :star:21

## C bindings
 * [asound-cr](https://github.com/TamasSzekeres/asound-cr) - Bindings for ALSA/libasound :star:3
 * [cairo-cr](https://github.com/TamasSzekeres/cairo-cr) - Bindings for [Cairo](https://cairographics.org/) graphics library :star:5
 * [clang.cr](https://github.com/ysbaddaden/clang.cr) - Libclang bindings :star:14
 * [crass](https://github.com/vonKingsley/crass) - Bindings for libsass :star:8
 * [crt.cr](https://github.com/maiha/crt.cr) - Bindings for libncursesw and crt :star:15
 * [crystal-gsl](https://github.com/ruivieira/crystal-gsl) - GNU Scientific Library bindings :star:10
 * [curl-crystal](https://github.com/blocknotes/curl-crystal) - Bindings for [libcurl](https://curl.haxx.se/libcurl/)
 * [duktape.cr](https://github.com/jessedoyle/duktape.cr) - Bindings for the [Duktape](https://github.com/svaarala/duktape) javascript engine :star:61
 * [gphoto2.cr](https://github.com/Sija/gphoto2.cr) - Bindings for the [libgphoto2](http://www.gphoto.org/) library :star:8
 * [icu.cr](https://github.com/olbat/icu.cr) - Bindings for the [ICU](http://site.icu-project.org/) library :star:2
 * [java.cr](https://github.com/ysbaddaden/java.cr) - Java Native Interface (JNI) bindings (and generator)
 * [libnotify.cr](https://github.com/splattael/libnotify.cr) - Bindings for Libnotify :star:12
 * [pcap.cr](https://github.com/maiha/pcap.cr) - Bindings for libpcap :star:14
 * [posix](https://github.com/ysbaddaden/posix) - POSIX/C bindings :star:18
 * [soundfile](https://github.com/mjago/soundfile) - Bindings for [libsndfile](http://www.mega-nerd.com/libsndfile/) library :star:1
 * [ssh2.cr](https://github.com/datanoise/ssh2.cr) - Bindings for libssh2 library :star:25
 * [termbox-crystal](https://github.com/andrewsuzuki/termbox-crystal) - Bindings and extension library for [termbox](https://github.com/nsf/termbox) (terminal UI library)
 * [x11-cr](https://github.com/TamasSzekeres/x11-cr) - X11 bindings :star:10
 * [x_do.cr](https://github.com/woodruffw/x_do.cr) - Bindings for libxdo ([`xdotool`](https://github.com/jordansissel/xdotool))

## Caching
 * [bloom_filter](https://github.com/crystal-community/bloom_filter) - Implementation of Bloom filter :star:19
 * [bojack](https://github.com/marceloboeira/bojack) - A non-reliable in-memory key-value store :star:62
 * [cache-hash](https://github.com/samueleaton/cache-hash) - A key/value store where entries expire after a specified interval :star:12
 * [crystal-memcached](https://github.com/comandeo/crystal-memcached) - Implementation of a memcached client :star:21
 * [Nuummite](https://github.com/CodeSteak/Nuummite) - A tiny persistent embedded key-value store :star:9

## Cli Builders
 * [admiral](https://github.com/jwaldrip/admiral.cr) - A robust DSL for writing command line interfaces :star:52
 * [cli](https://github.com/mosop/cli) - Library for building command-line interface applications :star:52
 * [clim](https://github.com/at-grandpa/clim) - Slim command line interface builder :star:22
 * [commander](https://github.com/mrrooijen/commander) - Command-line interface builder :star:70
 * [completion](https://github.com/f/completion) - Easy command line completion engine :star:45
 * [optarg](https://github.com/mosop/optarg) - Yet another library for parsing command-line options and arguments :star:12

## Cli Utils
 * [dl](https://github.com/creadone/dl) - Simple utility for download files by URLs from list :star:2
 * [noteesh](https://github.com/arandilopez/noteesh) - Notes and Todo list in command line :star:3
 * [progress](https://github.com/askn/progress) - [==..] Progress bar :star:95
 * [progress_bar.cr](https://github.com/TPei/progress_bar.cr) - A simple and customizable progress bar :star:2
 * [spinner](https://github.com/askn/spinner) - Terminal Spinner :star:39
 * [terminal_table.cr](https://github.com/benoist/terminal_table.cr) - Simple ASCII table generator :star:17
 * [todo](https://github.com/Nephos/todo) - Todo list working in command line :star:2

## Configuration
 * [cr-dotenv](https://github.com/gdotdesign/cr-dotenv) - Loads .env file :star:32
 * [crystal-toml](https://github.com/manastech/crystal-toml) - TOML parser :star:30
 * [dockerfile.cr](https://github.com/keplersj/dockerfile.cr) - Dockerfile Parsing Library :star:1
 * [habitat](https://github.com/luckyframework/habitat) - Type safe configuration for your classes and modules :star:16
 * [zq](https://github.com/colstrom/zq) - Command-line ZPL processor :star:2

## Converters
 * [human_file_size.cr](https://github.com/johnjansen/human_file_size.cr) - JSON & YAML mapping converter for human file sizes in serialized data
 * [moola](https://github.com/dorkrawk/moola) - Library for dealing with money and conversion (inspired by [RubyMoney](https://github.com/RubyMoney/money))
 * [ms](https://github.com/SuperPaintman/ms) - Library to easily convert various time formats to milliseconds and milliseconds to human readable format :star:12
 * [sass.cr](https://github.com/straight-shoota/sass.cr) - Compile SASS/SCSS to CSS ([libsass](https://github.com/sass/libsass/) binding)
 * [time_format.cr](https://github.com/vladfaust/time_format.cr) - Convert time in human readable format with ease
 * [turkish-number](https://github.com/izniburak/turkish-number) - Turn integers into the Turkish words :star:6
 * [wkhtmltopdf-crystal](https://github.com/blocknotes/wkhtmltopdf-crystal) - Bindings / wrapper for libwkhtmltox (HTML to PDF / image converter)

## Data Generators
 * [faker](https://github.com/askn/faker) - A library for generating fake data :star:77
 * [hashids.cr](https://github.com/splattael/hashids.cr) - A library to generate YouTube-like ids from one or many numbers :star:24

## Database Drivers/Clients
 * [arangocr](https://github.com/solisoft/arangocr) - ArangoDB client :star:11
 * [crystal-db](https://github.com/crystal-lang/crystal-db) - Common db api :star:101
 * [crystal-monetdb-libmapi](https://github.com/puppetpies/crystal-monetdb-libmapi) - Bindings for MonetDB :star:1
 * [crystal-mysql](https://github.com/crystal-lang/crystal-mysql) - MySQL connector for Crystal :star:41
 * [crystal-pg](https://github.com/will/crystal-pg) - A Postgres driver :star:244
 * [crystal-redis](https://github.com/stefanwille/crystal-redis) - Full featured Redis client :star:202
 * [crystal-sqlite3](https://github.com/crystal-lang/crystal-sqlite3) - SQLite3 bindings :star:48
 * [eventql-crystal](https://github.com/measurechina/eventql-crystal) - EventQL driver :star:6
 * [leveldb](https://github.com/crystal-community/leveldb) - Crystal bindings for LevelDB :star:21
 * [mongo.cr](https://github.com/datanoise/mongo.cr) - Binding for MongoDB C driver :star:69
 * [rethinkdb.cr](https://github.com/CubosTecnologia/rethinkdb.cr) - RethinkDB Driver :star:29
 * [rocksdb.cr](https://github.com/maiha/rocksdb.cr) - RocksDB client :star:13

## Database Tools
 * [crecto-admin](https://github.com/Crecto/crecto-admin) - Admin dashboard for Crecto and your database :star:15
 * [micrate](https://github.com/juanedi/micrate) - Database migration tool :star:82
 * [migrate](https://github.com/vladfaust/migrate.cr) - A simpler database migration tool with transactions :star:7

## Development Tools
 * [guardian](https://github.com/f/guardian) - File change watcher for Crystal and Non-Crystal libs :star:197
 * [kemal-watcher](https://github.com/faustinoaq/kemal-watcher) - Kemal plugin to watch files and live-reload the browser :star:6
 * [sentry](https://github.com/samueleaton/sentry) - Watches src files, rebuilds/reruns application on file changes :star:106
 * [sentry-run](https://github.com/faustinoaq/sentry-run) - Reload code changes using Sentry.run :star:3
 * [Warden](https://github.com/diggersheep/warden) - Watches files, run command and a git command if succeed on file changes :star:7
 * [watcher](https://github.com/faustinoaq/watcher) - Watch file changes using File.stat :star:6

## Email
 * [crystal-email](https://github.com/arcage/crystal-email) - Simple e-mail sending library :star:45
 * [CrystalEmail](https://github.com/Nephos/CrystalEmail) - A RFC compliant Email validator :star:13
 * [devmail](https://github.com/tijn/devmail) - A combined SMTP/POP3-server with volatile mail storage :star:12
 * [sendgrid.cr](https://github.com/dlanileonardo/sendgrid.cr) - Simple Sendgrid Client :star:6

## Environment Management
 * [asdf-crystal](https://github.com/marciogm/asdf-crystal) - Plugin for asdf version manager :star:8
 * [crenv](https://github.com/pine/crenv) - Crystal version manager :star:142
 * [rcm.cr](https://github.com/maiha/rcm.cr) - Redis Cluster Manager :star:24

## Examples and funny stuff
 * [breakout.cr](https://github.com/petoem/breakout.cr) - Breakout game written using crsfml :star:7
 * [chuck-norris-holy-quotes](https://github.com/codenoid/chuck-norris-holy-quotes) - Chuck Norris holy quotes :star:4
 * [clamp](https://github.com/johnjansen/clamp) - Clamp any Comparable :star:1
 * [crsfml-examples](https://github.com/oprypin/crsfml-examples) - Simple games made with CrSFML :star:34
 * [crystal-benchmarks-game](https://github.com/kostya/crystal-benchmarks-game) - The Computer Language Benchmarks Game :star:57
 * [crystal-by-example](https://github.com/askn/crystal-by-example) - Crystal By Example :star:284
 * [Crystal-Maze](https://github.com/Demonstrandum/Crystal-Maze) - A* Path finding for PNG mazes :star:12
 * [crystal-mysql-crud-example](https://github.com/codenoid/crystal-mysql-crud-example) - Crystal MySQL CRUD example
 * [crystal-patterns](https://github.com/crystal-community/crystal-patterns) - Examples of GOF patters :star:86
 * [crystalized_ruby](https://github.com/phoffer/crystalized_ruby) - Native Ruby extensions written in Crystal :star:112
 * [exercism-crystal](https://github.com/exercism/crystal) - Exercism exercises :star:37
 * [jihantoro-cr-mysql](https://github.com/codenoid/jihantoro-cr-mysql) - Crystal MySQL from scratch sample app
 * [jihantoro.sd](https://github.com/codenoid/jihantoro.sd) - Crystal & Kemal version of Serdar Dogruyol blog
 * [kemal-chat](https://github.com/sdogruyol/kemal-chat) - Build realtime applications with Kemal and WebSocket :star:36
 * [kemal-heroku-example](https://github.com/cagataycali/kemal-heroku-example) - This repository shows, how you can publish your open source apps which powered kemal framework publish as heroku app in seconds :star:2
 * [kemal-mysql-blog](https://github.com/codenoid/kemal-mysql-blog) - Blog written with Crystal, Kemal and MySQL :star:3
 * [kemal-react-chat](https://github.com/f/kemal-react-chat) - Build Realtime Web applications with Kemal and React :star:55
 * [kemal-vue-chat](https://github.com/ChangJoo-Park/kemal-vue-chat) - Build Realtime Web applications with Kemal and Vue.js :star:18
 * [lattice-core-card-game](https://github.com/jasonl99/card_game) - A demo web app for (WebSocket-based) lattice-core :star:141
 * [medley](https://github.com/jwoertink/medley) - A mixture of music related methods :star:9
 * [os-crystal](https://github.com/lbguilherme/os-crystal) - x86 Kernel implemented in Crystal :star:34
 * [realtime-todo-app](https://github.com/Angarsk8/realtime-todo-app) - Realtime Todo application developed with Kemal, Websockets, React, ES2015 and PostgreSQL :star:15
 * [rocky](https://github.com/codingphasedotcom/rocky) - React Over Crystal Kemal and Yarn :star:84
 * [try.cr](https://github.com/maiha/try.cr) - Try monad :star:17

## Feature Flipping
 * [flipper](https://github.com/metaware/flipper) - Feature flipping/flags/rollouts. Supports multiple backends :star:10

## Framework Components
 * [cr-melon](https://github.com/gdotdesign/cr-melon) - Class based Http APIs :star:6
 * [Crystal-DI](https://github.com/funk-yourself/crystal-di) - Lightweight DI Container :star:12
 * [crystal-mime](https://github.com/spalger/crystal-mime) - Mimetypes for Crystal :star:17
 * [graphql-crystal](https://github.com/ziprandom/graphql-crystal) - [Graphql](http://graphql.org) implementation :star:82
 * [kave](https://github.com/jwoertink/kave) - Kemal API Version Extension :star:19
 * [kemal-auth-token](https://github.com/akwiatkowski/kemal-auth-token) - Kemal middleware to authentication via HTTP header token using JWT :star:18
 * [kemal-monetdb](https://github.com/puppetpies/kemal-monetdb) - MonetDB Data connection for Kemal
 * [kemal-session](https://github.com/kemalcr/kemal-session) - Session handler for Kemal :star:24
 * [mime-types.cr](https://github.com/jwaldrip/mime-types.cr) - A port of the Ruby MIME-types library :star:6
 * [multi-auth](https://github.com/msa7/multi_auth) - Standardized multi-provider OAuth2 authentication (inspired by omniauth)
 * [phoenix.cr](https://github.com/dtcristo/phoenix.cr) - Phoenix Channels client :star:19
 * [request_id](https://github.com/SuperPaintman/request-id) - Middleware for generates / pick up a unique request ID for Crystal servers :star:1
 * [response_time](https://github.com/SuperPaintman/response-time) - Response time for Crystal servers (pure http server, kemal, etc.)
 * [spec-kemal](https://github.com/kemalcr/spec-kemal) - Easy testing for Kemal :star:35
 * [tele-broadcast.cr](https://github.com/vladfaust/tele-broadcast.cr) - Broadcasting module for tele.cr :star:1

## Game Development
 * [CrSFML](https://github.com/oprypin/crsfml) - Bindings to [SFML](https://www.sfml-dev.org/) multimedia/game library :star:172
 * [crystal-chipmunk](https://github.com/oprypin/crystal-chipmunk) - Bindings for [Chipmunk](http://chipmunk-physics.net/), a fast and lightweight 2D game physics library :star:15
 * [glove](https://github.com/ddfreyne/glove) - A library for gaming development :star:37
 * [inari](https://github.com/ddfreyne/inari) - A collection of games using Glove as the game engine :star:10
 * [mos_game](https://github.com/bararchy/mos_game) - Mini Offline Singleplayer game :star:9

## GUI library
 * [libui.cr](https://github.com/Fusion/libui.cr) - Bindings for [libui](https://github.com/andlabs/libui) :star:4877
 * [qt5.cr](https://github.com/Papierkorb/qt5.cr) - Qt5 bindings for Crystal, based on Bindgen :star:69

## HTML/XML Parsing
 * [crystagiri](https://github.com/madeindjs/Crystagiri) - An Html Reader / parser like [Nokogiri](https://github.com/sparklemotion/nokogiri) Ruby gem :star:63
 * [gumbo-crystal](https://github.com/blocknotes/gumbo-crystal) - Bindings for [Gumbo](https://github.com/google/gumbo-parser), an HTML5 parsing library made by Google :star:1
 * [hq.cr](https://github.com/maiha/hq.cr) - Simple wrapper for crystal-xml :star:6
 * [modest](https://github.com/kostya/modest) - CSS selectors for HTML5 Parser myhtml :star:37
 * [myhtml](https://github.com/kostya/myhtml) - Fast HTML5 Parser :star:38

## HTTP
 * [cossack](https://github.com/crystal-community/cossack) - Simple flexible HTTP client :star:74
 * [crest](https://github.com/mamantoha/crest) - Simple HTTP and REST client, inspired by the Ruby's RestClient gem :star:34
 * [crul](https://github.com/porras/crul) - Command line HTTP client :star:94
 * [cryload](https://github.com/sdogruyol/cryload) - HTTP benchmarking tool :star:111
 * [halite](https://github.com/icyleaf/halite) - Yet another simple HTTP and REST client with a chainable API, built-in sessions and timeouts :star:36
 * [helmet](https://github.com/EvanHahn/crystal-helmet) - Set security-related HTTP headers :star:14
 * [http-multiserver.cr](https://github.com/vladfaust/http-multiserver.cr) - Mounting multiple servers via routes (a.k.a. URL mapping)
 * [http-protection](https://github.com/rogeriozambon/http-protection) - Protection against typical web attacks :star:33
 * [http2](https://github.com/ysbaddaden/http2) - HTTP/2 Protocol Implementation :star:48
 * [http_distributor](https://github.com/Nephos/http_distributor) - HTTP server which allows sneaky http requests :star:2
 * [http_parser.cr](https://github.com/kostya/http_parser.cr) - Wrapper for [Http Parser lib](https://github.com/nodejs/http-parser) :star:3784
 * [keyer_cr](https://github.com/danielpclark/keyer_cr) - Adds HTTP GET/POST parameter parsing as a Hash-like object
 * [resp-crystal](https://github.com/soveran/resp-crystal) - Lightweight RESP client :star:5

## Image processing
 * [magickwand-crystal](https://github.com/blocknotes/magickwand-crystal) - Bindings for [MagickWand](https://www.imagemagick.org/script/magick-wand.php), the C interface for ImageMagick processing libraries :star:27
 * [stumpy_gif](https://github.com/stumpycr/stumpy_gif) - Write (animated) GIF images :star:8
 * [stumpy_png](https://github.com/stumpycr/stumpy_png) - Read and write PNG images :star:35

## Implementations/Compilers
 * [charly](https://github.com/charly-lang) - Charly Programming Language
 * [cltk](https://github.com/ziprandom/cltk) - A crystal port of the Ruby Language Toolkit :star:42
 * [cppize](https://github.com/unn4m3d/cppize) - Crystal-to-C++ transpiler :star:21
 * [crisp](https://github.com/rhysd/Crisp) - Lisp dialect implemented with Crystal :star:19
 * [crow](https://github.com/geppetto-apps/crow) - Transpile/compile Crystal to [Flow](https://flow.org/)
 * [myst-lang](https://github.com/myst-lang/) - A practical, dynamic language designed to be written and understood as easily and efficiently as possible
 * [NuummiteOS](https://github.com/TheKernelCorp/NuummiteOS) - An OS written in Crystal as a Proof of Concept :star:47
 * [zir](https://github.com/tbrand/zir) - Realizes to write macros in any scripts into any languages :star:14

## Logging and monitoring
 * [crometheus](https://gitlab.com/ezrast/crometheus) - A [Prometheus](https://prometheus.io/) client library
 * [crystal-logreader](https://github.com/arcage/crystal-logreader) - Tailing log file
 * [fluent-logger-crystal](https://github.com/TobiasGSmollett/fluent-logger-crystal) - A structured logger for [Fluentd](https://www.fluentd.org/)
 * [katip](https://github.com/guvencenanguvenal/katip) - JSONbase logger :star:19
 * [statsd.cr](https://github.com/miketheman/statsd.cr) - [Statsd](https://github.com/etsy/statsd) client library :star:13
 * [syslog.cr](https://github.com/comandeo/syslog.cr) - Implementation of Syslog client :star:6

## Machine Learning
 * [ai4cr](https://github.com/drhuffman12/ai4cr) - Artificial Intelligence (based on https://github.com/SergioFierens/ai4r)
 * [crystal-fann](https://github.com/NeuraLegion/crystal-fann) - FANN (Fast Artifical Neural Network) binding :star:65
 * [crystal-learn](https://github.com/pbrusco/crystal-learn) - Sklearn-like machine-learning library :star:30
 * [grey_matter](https://github.com/dorkrawk/grey_matter) - A basic artificial neural network library :star:8
 * [shainet](https://github.com/NeuraLegion/shainet) - SHAInet (Neural Network in pure crystal)
 * [tensorflow.cr](https://github.com/fazibear/tensorflow.cr) - Bindings for [TensorFlow](https://github.com/tensorflow/tensorflow) :star:88994

## Markdown/Text Processors
 * [html-pipeline](https://github.com/huacnlee/html-pipeline) - HTML processing filters and utilities :star:5
 * [markd](https://github.com/icyleaf/markd) - Yet another markdown parser built for speed, Compliant to CommonMark specification :star:10
 * [remarkdown](https://github.com/huacnlee/remarkdown) - GFM for Crystal :star:4

## Misc
 * [aasm.cr](https://github.com/veelenga/aasm.cr) - Easy to use finite state machine for Crystal classes :star:25
 * [accord](https://github.com/neovintage/accord) - Sharable validations for Crystal objects :star:16
 * [any_hash.cr](https://github.com/Sija/any_hash.cr) - Recursive Hash with better JSON::Any included :star:12
 * [circuit_breaker](https://github.com/TPei/circuit_breaker) - Implementation of the circuit breaker pattern :star:15
 * [crystal-binary_parser](https://github.com/DanSnow/crystal-binary_parser) - Binary parser :star:6
 * [crystal-futures](https://github.com/dhruvrajvanshi/crystal-futures) - Future type implementation :star:43
 * [crz](https://github.com/dhruvrajvanshi/crz) - Functional programming library :star:22
 * [denetmen](https://github.com/izniburak/denetmen) - Useful micro validator / check library :star:21
 * [emoji.cr](https://github.com/veelenga/emoji.cr) - Emoji library :star:14
 * [hoop](https://github.com/0x73/hoop) - Building native OSX apps :star:175
 * [html_builder](https://github.com/crystal-lang/html_builder) - DSL for creating HTML :star:29
 * [i18n.cr](https://github.com/vladfaust/i18n.cr) - Internationalization shard :star:5
 * [immutable](https://github.com/lucaong/immutable) - Implementation of thread-safe, persistent, immutable collections :star:132
 * [inflector.cr](https://github.com/phoffer/inflector.cr) - Singularize, pluralize, camelize, etc (port from ActiveSupport)
 * [lirith](https://github.com/lirith-engine/lirith) - Graphics engine :star:17
 * [m3u8](https://github.com/akiicat/m3u8) - Generate and parse m3u8 playlists for HTTP Live Streaming :star:2
 * [manual-generator](https://github.com/blocknotes/manual-generator) - Tool to generate PDF manuals from documentation sites
 * [raytracer](https://github.com/l3kn/raytracer) - CPU Raytracer with examples :star:26
 * [syscall.cr](https://github.com/kubo39/syscall.cr) - Raw syscall interface :star:12
 * [tren](https://github.com/sdogruyol/tren) - Give your SQL some love :star:84
 * [ulid](https://github.com/SuperPaintman/ulid) - Universally Unique Lexicographically Sortable Identifier (ULID)
 * [wikicr](https://github.com/Nephos/wikicr) - Wiki using git to manage revisions :star:7

## Networking
 * [amqp.cr](https://github.com/datanoise/amqp.cr) - AMQP 0.9.1 client with RabbitMQ extensions :star:35
 * [bson.cr](https://github.com/jeromegn/bson.cr) - Native BSON implementation :star:12
 * [Crirc](https://github.com/Meoowww/Crirc) - IRC protocol implementation (Client, Server, Bots)
 * [fast_irc.cr](https://github.com/RX14/fast_irc.cr) - Fast IRC parser/generator :star:7
 * [ipaddress.cr](https://github.com/Sija/ipaddress.cr) - Library to handle IPv4 and IPv6 addresses :star:11
 * [jwt](https://github.com/crystal-community/jwt) - Implementation of JWT (JSON Web Token)
 * [msgpack-crystal](https://github.com/crystal-community/msgpack-crystal) - MessagePack library :star:68
 * [transfer_more](https://github.com/Nephos/transfer_more) - Clone of transfer.sh to uploads files :star:11

## ORM/ODM Extensions
 * [active_record.cr](https://github.com/waterlink/active_record.cr) - Active Record pattern implementation :star:170
 * [clear](https://github.com/anykeyh/clear) - ORM specialized to PostgreSQL only but with advanced features :star:16
 * [core](https://github.com/vladfaust/core.cr) - Pure, transparent and efficient ORM :star:30
 * [crecto](https://github.com/Crecto/crecto) - Database wrapper, based on Ecto :star:190
 * [granite-orm](https://github.com/amberframework/granite-orm) - ORM for Postgres, Mysql, Sqlite :star:92
 * [jennifer.cr](https://github.com/imdrasil/jennifer.cr) - Active Record pattern implementation with flexible query chainable builder and migration system :star:105
 * [ohm-crystal](https://github.com/soveran/ohm-crystal) - Object-hash mapping library for Redis :star:45
 * [record](https://github.com/luckyframework/record) - Type safe querying, saving and updating :star:30
 * [redis-tsv.cr](https://github.com/maiha/redis-tsv.cr) - Import and export data from Redis in TSV format :star:4
 * [stal-crystal](https://github.com/soveran/stal-crystal) - Set algebra solver for Redis :star:3
 * [topaz](https://github.com/topaz-crystal/topaz) - A simple and useful db wrapper :star:54

## Package Management
 * [CRelease](https://github.com/elorest/crelease) - Version and git tag manager that makes shard releases easy :star:11
 * [shards](https://github.com/crystal-lang/shards) - Dependency manager for the Crystal :star:413

## Processes and Threads
 * [neph](https://github.com/tbrand/neph) - A modern command line job processor that can execute jobs concurrently :star:86
 * [promise](https://github.com/jwaldrip/promise.cr) - A Promise Implementation :star:25

## Project Generators
 * [bindgencr](https://github.com/TechMagister/bindgencr) - Generator of bindings based on castxml output
 * [crystal_lib](https://github.com/crystal-lang/crystal_lib) - Automatic binding generator for native libraries :star:81
 * [fez](https://github.com/jwoertink/fez) - A Kemal application generator :star:31
 * [kgen](https://github.com/kemalyst/kemalyst-generator) - Kemalyst command line tool for console, init, generate (scaffolding), and watch. :star:11
 * [libgen](https://github.com/olbat/libgen) - Automatic bindings generator configured using JSON/YAML files :star:17
 * [wasp](https://github.com/icyleaf/wasp) - Static Site Generator :star:3

## Queue
 * [dispatch](https://github.com/bmulvihill/dispatch) - In memory asynchronous job processing :star:7
 * [sidekiq.cr](https://github.com/mperham/sidekiq.cr) - Simple, efficient job processing :star:433

## Routing
 * [crouter](https://github.com/jreinert/crouter) - A standalone router :star:44
 * [orion](https://github.com/obsidian/orion) - A minimal, rails-esque routing library :star:35
 * [router.cr](https://github.com/tbrand/router.cr) - Minimum but powerful http router for HTTP::Server :star:103
 * [toro](https://github.com/soveran/toro) - Tree Oriented Routing :star:60

## Scheduling
 * [cron_scheduler](https://github.com/kostya/cron_scheduler) - Job scheduler with crontab patterns :star:22
 * [quartz](https://github.com/andrewhamon/quartz) - Crystal clear timers :star:3
 * [schedule.cr](https://github.com/hugoabonizio/schedule.cr) - Run periodic tasks :star:38

## Science and Data analysis
 * [linalg](https://github.com/konovod/linalg) - Linear algebra library inspired by MATLAB and SciPy.linalg :star:9
 * [predict.cr](https://github.com/RX14/predict.cr) - Satellite prediction library using the sgp4 model :star:6
 * [scorystal](https://github.com/asafschers/scorystal) - Scoring API for PMML - supports RF and GBM :star:3
 * [stats](https://github.com/Nephos/stats) - An expressive implementation of statistical distributions :star:11

## Search
 * [hermes](https://github.com/imdrasil/hermes.cr) - Data Mapper pattern implementation for ElastiSearch :star:12
 * [query-builder](https://github.com/izniburak/query-builder) - Sql Query Builder library :star:36
 * [query.cr](https://github.com/waterlink/query.cr) - Query abstraction :star:10
 * [soegen](https://github.com/Ragmaanir/soegen) - Elasticsearch client for Crystal similar to the stretcher gem for ruby :star:15

## Task management
 * [cake](https://github.com/axvm/cake) - Production-ready Make-like utility tool :star:9
 * [sam](https://github.com/imdrasil/sam.cr) - Another one Rake-like task manager with namespacing and arguments system :star:18

## Template Engine
 * [crikey](https://github.com/domgetter/crikey) - Templating engine inspired by [Hiccup](https://github.com/weavejester/hiccup) :star:1702
 * [crinja](https://github.com/straight-shoota/crinja) - An implementation of the [Jinja2 template engine](http://jinja.pocoo.org/)
 * [crustache](https://github.com/MakeNowJust/crustache) - [{{Mustache}}](https://mustache.github.io) for Crystal :star:35
 * [Kilt](https://github.com/jeromegn/kilt) - Abstraction layer for template engines :star:75
 * [Slang](https://github.com/jeromegn/slang) - Lightweight, terse, templating language inspired by Ruby's Slim :star:104
 * [teeplate](https://github.com/mosop/teeplate) - A library for rendering multiple template files :star:5
 * [temel](https://github.com/f/temel) - Extensible HTML::Builder alternative for Crystal, supports custom tag definitions :star:38

## Testing
 * [crotest](https://github.com/emancu/crotest) - A tiny and simple test framework :star:19
 * [microtest](https://github.com/Ragmaanir/microtest) - Small opinionated testing library focusing on power asserts :star:13
 * [minitest.cr](https://github.com/ysbaddaden/minitest.cr) - Library for unit tests and assertions :star:69
 * [mocks.cr](https://github.com/waterlink/mocks.cr) - Mocking library for Crystal :star:24
 * [spec2-mocks](https://github.com/waterlink/spec2-mocks.cr) - An adapter of mocks.cr for spec2.cr :star:7
 * [spec2.cr](https://github.com/waterlink/spec2.cr) - Enhanced testing library :star:78
 * [timecop.cr](https://github.com/TobiasGSmollett/timecop.cr) - Library for mocking with `Time.now`. Inspired by [timecop ruby gem](https://github.com/travisjeffery/timecop) :star:2551
 * [webmock.cr](https://github.com/manastech/webmock.cr) - Library for stubbing `HTTP::Client` requests :star:46

## Third-party APIs
 * [aws-signer.cr](https://github.com/beanieboi/aws-signer.cr) - This library signs your HTTP requests using AWS v4 :star:6
 * [awscr-s3](https://github.com/taylorfinnell/awscr-s3) - AWS S3 interface :star:26
 * [awscr-signer](https://github.com/taylorfinnell/awscr-signer) - Sign HTTP::Request objects and generate presigned post forms :star:4
 * [bugsnag.cr](https://github.com/gewo/bugsnag.cr) - Bugsnag exception notifier and sidekiq middleware :star:2
 * [crystal-darksky](https://github.com/sb89/crystal-darksky) - Wrapper for the [Dark Sky](https://darksky.net) API :star:4
 * [crystal-github](https://github.com/felipeelias/crystal-github) - Wrapper for the [Github](https://github.com/) API :star:2
 * [crystal-monzo](https://github.com/barisbalic/crystal-monzo) - A client for the [Monzo API](https://monzo.com/docs/)
 * [crystal-swapi](https://github.com/sb89/crystal-swapi) - Star Wars API (SWAPI) wrapper :star:1
 * [crystal_slack](https://github.com/manastech/crystal_slack) - A tool that parses Slack slash commands or send incoming web hooks :star:11
 * [dotacr](https://github.com/azah/dotacr) - Wrapper for Valve's DotA API :star:7
 * [GDAX](https://github.com/mccallofthewild/gdax) - GDAX REST and WebSocket API Wrapper with request signing :star:2
 * [gitlab.cr](https://github.com/icyleaf/gitlab.cr) - GitLab API wrapper :star:9
 * [google_maps_api](https://github.com/fridgerator/google_maps_api) - Google Maps API :star:9
 * [hncr](https://github.com/Gangwolf/hncr) - A Hacker News API wrapper :star:1
 * [mixpanel-crystal](https://github.com/petoem/mixpanel-crystal) - A library for sending events to Mixpanel
 * [nexmo-crystal](https://github.com/timcraft/nexmo-crystal) - [Nexmo REST API](https://developer.nexmo.com/) client :star:1
 * [ocean_kit](https://github.com/osfx/ocean_kit) - [Digital Ocean v2 API](https://developers.digitalocean.com/documentation/v2/) client :star:4
 * [open_exchange_rates](https://github.com/osfx/open_exchange_rates) - A library to access [Open Exchange Rates](https://openexchangerates.org/) API :star:9
 * [pinboard.cr](https://github.com/oz/pinboard.cr) - [Pinboard](https://pinboard.in) API :star:2
 * [raven.cr](https://github.com/sija/raven.cr) - Raven is a client for [Sentry](https://github.com/getsentry/sentry) :star:15652
 * [slack.cr](https://github.com/DougEverly/slack.cr) - A Slack [Real Time Messaging API](https://api.slack.com/rtm) WebSocket client library :star:9
 * [spotify.cr](https://github.com/marceloboeira/spotify.cr) - A library to access the Spotify API :star:28
 * [tele.cr](https://github.com/vladfaust/tele.cr) - A *convenient* wrapper for the Telegram Bot API :star:15
 * [telegram_bot](https://github.com/hangyas/telegram_bot) - A wrapper for the Telegram Bot API :star:50

## Virtualization
 * [baked_file_system](https://github.com/schovi/baked_file_system) - Virtual file system implementation :star:65
 * [rcpu](https://github.com/ddfreyne/rcpu) - A virtual machine emulator and assembler :star:33

## Web Frameworks
 * [amber](https://github.com/amberframework/amber) - Open source efficient and cohesive web application framework :star:819
 * [kemal](https://github.com/kemalcr/kemal) - Lightning Fast, Super Simple web framework. Inspired by Sinatra :star:2075
 * [lattice-core](https://github.com/jasonl99/lattice-core) - A WebSocket-first object-oriented framework (based on Kemal)
 * [lucky](https://github.com/luckyframework/lucky) - Catch bugs early, forget about most performance issues, and spend more time on code instead of debugging and writing tests :star:686
 * [prism](https://github.com/vladfaust/prism) - Light, modular web framework :star:9
 * [raze](https://github.com/samueleaton/raze) - Modular, light web framework :star:79

## Web Servers
 * [fast-http-server](https://github.com/sdogruyol/fast-http-server) - Super fast, zero configuration command line HTTP Server :star:121
 * [prax.cr](https://github.com/ysbaddaden/prax.cr) - Rack proxy server for development :star:105
 * [serve](https://github.com/SuperPaintman/serve) - Command line static HTTP server :star:13

# Community
 * [Crystal weekly newsletters](http://crystalweekly.com/)
 * [Gitter](https://gitter.im/crystal-lang/crystal)
 * [Google Group](https://groups.google.com/forum/?fromgroups#!forum/crystal-lang)
 * [IRC](http://irc.lc/freenode/crystal-lang) - #crystal-lang on Freenode
 * [Metaruby](https://metaruby.com/c/crystal-forum) - Crystal Forum on Metaruby
 * [Reddit](https://www.reddit.com/r/crystal_programming/)
 * [Stackoverflow](https://stackoverflow.com/tags/crystal-lang/info)

# Resources
 * [Crystal for Rubyists](http://www.crystalforrubyists.com/) - free book to bootstrap your Crystal journey
 * [crystal-lang.org](https://crystal-lang.org) - Official language site
 * [devdocs.io](https://devdocs.io/crystal/) - API Documentation Browser with Crystal support

## Official Documentation Translations
 * [br.crystal-lang.org](http://br.crystal-lang.org/) - Brazilian
 * [ja.crystal-lang.org](http://ja.crystal-lang.org/) - Japanese
 * [kr.crystal-lang.org](https://kr.crystal-lang.org/) - Korean
 * [ru.crystal-lang.org](http://ru.crystal-lang.org/) - Russian
 * [tw.crystal-lang.org](http://tw.crystal-lang.org/) - Chinese Traditional

# Services and Apps
 * [carc.in](https://carc.in/) - A web service that runs your code and displays the result
 * [Crank](https://github.com/arktisklada/crank) - A Procfile-based application manager (like Foreman)
 * [cry](https://github.com/elorest/cry) - Ability to execute crystal code in a fashion similar to Ruby's pry edit :star:9
 * [Crystal [ANN]](https://crystal-ann.com) - Announce new project, blog post, version update or any other Crystal work
 * [crystalshards.herokuapp.com](https://crystalshards.herokuapp.com/), [crystalshards.xyz](http://crystalshards.xyz/) - Web services that list all available Crystal shards
 * [DeBot](https://github.com/jhass/DeBot) - IRC bot written in Crystal :star:30
 * [Ficha](https://github.com/codenoid/ficha) - A super secret chat app, for any body who needs privacy :star:17
 * [Firegrid](https://github.com/foliea/firegrid) - Click anywhere with only a few key strokes :star:4
 * [icr](https://github.com/crystal-community/icr) - Interactive console for Crystal (like IRB for Ruby)
 * [nes](https://github.com/romeroadrian/nes.cr) - A NES emulator :star:37
 * [shards.rocks](https://shards.rocks/) - Service that manages dependencies inspired by [Gemnasium](https://gemnasium.com/) and [David](https://david-dm.org/)
 * [soundmemes.cr](https://github.com/vladfaust/soundmemes.cr) - Telegram Bot built on top of tele.cr :star:5
 * [torrent](https://github.com/Papierkorb/torrent) - A BitTorrent client :star:25

# Tools
 * [crystal-base](https://github.com/ruivieira/crystal-base) - CentOS base docker image for Crystal development
 * [crystal-ctags](https://github.com/SuperPaintman/crystal-ctags) - Ctags generator for Crystal :star:5
 * [crystal-dash-docset](https://github.com/Sija/crystal-dash-docset) - [Dash](https://kapeli.com/dash) docset generator :star:4
 * [helptransl8](https://github.com/papilip/helptransl8) - Tool for document translators :star:5

## DevOps
 * [ansible-crystal](https://github.com/CorbanR/ansible-crystal) - Ansible playbook for installing crystal
 * [crystal-cookbook](https://github.com/vjdhama/crystal-cookbook) - Chef cookbook for installing crystal :star:5

## Editor Plugins
 * Atom
   * [crystal-tools](https://atom.io/packages/crystal-tools) - Enables built in tools in Crystal compiler
   * [language-crystal-actual](https://atom.io/packages/language-crystal-actual) - Crystal language support in Atom
   * [linter-crystal](https://atom.io/packages/linter-crystal) - Lint Crystal using the Crystal compiler in Atom
 * Emacs
   * [emacs-crystal-mode](https://github.com/dotmilk/emacs-crystal-mode) - Crystal language support for Emacs :star:15
   * [play-crystal.el](https://github.com/veelenga/play-crystal.el) - [play.crystal-lang.org](https://play.crystal-lang.org/#/cr) integration in Emacs :star:5
 * Spacemacs
   * [crystal-spacemacs-layer](https://github.com/juanedi/crystal-spacemacs-layer) - Spacemacs contribution layer for Crystal :star:9
 * Sublime
   * [sublime-crystal](https://github.com/crystal-lang-tools/sublime-crystal) - Crystal syntax highlighting for sublime Text :star:51
 * TextMate
   * [Crystal.tmbundle](https://github.com/crystal-lang-tools/Crystal.tmbundle) - Crystal syntax highlighting, compile, format command, snippets :star:6
 * Vim
   * [carcin.vim](https://github.com/MakeNowJust/carcin.vim) - Vim plugin to provide utility functions for carc.in :star:4
   * [vim-crystal](https://github.com/rhysd/vim-crystal) - Vim filetype support for Crystal :star:202
   * [vim-slang](https://github.com/elorest/vim-slang) - Vim filetype support for Slang Templating Engine :star:6
 * Visual Studio Code
   * [vscode-crystal](https://github.com/g3ortega/vscode-crystal) - Crystal language support in VSCode :star:10
   * [vscode-crystal-ide](https://github.com/crystal-lang-tools/crystal-ide) - Crystal IDE powered by [Language Server Protocol](https://code.visualstudio.com/blogs/2016/06/27/common-language-protocol)
   * [vscode-crystal-lang](https://github.com/crystal-lang-tools/vscode-crystal-lang) - Formatter, linter and syntax highlighting for `cr` and `ecr` files :star:54

## Shell plugins
 * [crystal-zsh](https://github.com/veelenga/crystal-zsh) - .oh-my-zsh plugin :star:19


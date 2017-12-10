# Info come from [avelino/awesome-go](https://github.com/avelino/awesome-go)
# Awesome Go 

[![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack Widget](https://s3.eu-central-1.amazonaws.com/ngtuna/join-us-on-slack.png)](http://gophers.slack.com/messages/awesome)

A curated list of awesome Go frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

### Contents

- [Awesome Go](#awesome-go)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [Date and Time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Files](#files)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [IoT](#iot-internet-of-things)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Query Language](#query-language)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        - [Routers](#routers)
    - [Windows](#windows)
    - [XML](#xml)

- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
	- [Go Generate Tools](#go-generate-tools)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)

- [Server Applications](#server-applications)

- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Gophers](#gophers)
    - [Meetups](#meetups)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)

## Audio and Music

*Libraries for manipulating audio.*

* [flac](https://github.com/eaburns/flac) - Native Go FLAC decoder. :star:71
* [flac](https://github.com/mewkiz/flac) - Native Go FLAC decoder. :star:54
* [gaad](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser. :star:35
* [go-sox](https://github.com/krig/go-sox) - libsox bindings for go. :star:57
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) - libmediainfo bindings for go. :star:16
* [gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go. :star:3
* [id3v2](https://github.com/bogem/id3v2) - Fast and stable ID3 parsing and writing library for Go. :star:51
* [malgo](https://github.com/gen2brain/malgo) - Mini audio library. :star:13
* [mix](https://github.com/go-mix/mix) - Sequence-based Go-native audio mixer for music apps. :star:69
* [mp3](https://github.com/tcolgate/mp3) - Native Go MP3 decoder. :star:64
* [music-theory](https://github.com/go-music-theory/music-theory) - Music theory models in Go. :star:183
* [PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library. :star:165
* [portmidi](https://github.com/rakyll/portmidi) - Go bindings for PortMidi. :star:151
* [taglib](https://github.com/wtolson/go-taglib) - Go bindings for taglib. :star:53
* [vorbis](https://github.com/mccoyst/vorbis) - "Native" Go Vorbis decoder (uses CGO, but has no dependencies). :star:19
* [waveform](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams. :star:198

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* [authboss](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time. :star:1264
* [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC.
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) - provides parser of cookies.txt file format.
* [Go-AWS-Auth](https://github.com/smartystreets/go-aws-auth) - AWS (Amazon Web Services) request signing library. :star:181
* [go-jose](https://github.com/square/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. :star:771
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - Standalone, specification-compliant,  OAuth2 server written in Golang. :star:719
* [gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers. :star:788
* [gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang. :star:631
* [goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box. :star:1460
* [httpauth](https://github.com/goji/httpauth) - HTTP Authentication middleware. :star:127
* [jwt](https://github.com/robbert229/jwt) - Clean and easy to use implementation of JSON Web Tokens (JWT). :star:26
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options. :star:87
* [jwt-go](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT). :star:2850
* [loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam. :star:517
* [oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support. :star:1357
* [osin](https://github.com/RangelReale/osin) - Golang OAuth2 server library. :star:1284
* [permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt. :star:247
* [securecookie](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding. :star:10
* [session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE). :star:46
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - Go session management using the SessionGate Redis module. :star:3
* [sessions](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers. :star:26
* [yubigo](https://github.com/GeertJohan/yubigo) - Yubikey client package that provides a simple API to integrate the Yubico Yubikey into a go application. :star:81

## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [argparse](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module. :star:5
* [argv](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax. :star:3
* [cli](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags. :star:321
* [cli](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go. :star:18
* [cli-init](https://github.com/tcnksm/gcli) - The easy way to start building Golang command line applications. :star:764
* [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command. :star:126
* [cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions. :star:5849
* [complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion. :star:389
* [docopt.go](https://github.com/docopt/docopt.go) - Command-line arguments parser that will make you smile. :star:872
* [drive](https://github.com/odeke-em/drive) - Google Drive client for the commandline. :star:3720
* [env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs. :star:9
* [flag](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go supporting subcommand. :star:72
* [go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go. :star:449
* [go-flags](https://github.com/jessevdk/go-flags) - go command line option parser. :star:926
* [kingpin](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands. :star:1606
* [liner](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces. :star:411
* [mitchellh/cli](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces. :star:704
* [mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation. :star:470
* [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags. :star:285
* [readline](https://github.com/chzyer/readline) - Pure golang implementation that provides most features in GNU-Readline under MIT license. :star:1030
* [sflags](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries. :star:44
* [ukautz/clif](https://github.com/ukautz/clif) - Small command line interface framework. :star:79
* [urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli). :star:7028
* [wlog](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency. :star:22
* [wmenu](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompts users to make choices. :star:37

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [aurora](https://github.com/logrusorgru/aurora) - ANSI terminal colors that supports fmt.Printf/Sprintf. :star:259
* [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output. :star:223
* [color](https://github.com/fatih/color) - Versatile package for colored terminal output. :star:1991
* [colourize](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals. :star:12
* [go-ataman](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals. :star:5
* [go-colorable](https://github.com/mattn/go-colorable) - Colorable writer for windows. :star:222
* [go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals. :star:163
* [go-isatty](https://github.com/mattn/go-isatty) - isatty for golang. :star:192
* [gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces. :star:2076
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
* [mpb](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications. :star:130
* [progressbar](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS. :star:215
* [termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces. :star:2535
* [termtables](https://github.com/apcera/termtables) - Go port of the Ruby library [terminal-tables](https://github.com/tj/terminal-table) for simple ASCII table generation as well as providing markdown and HTML output. :star:112
* [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib). :star:6696
* [tui-go](https://github.com/marcusolsson/tui-go) - Go UI library for building rich terminal applications. :star:1089
* [uilive](https://github.com/gosuri/uilive) - Library for updating terminal output in realtime. :star:600
* [uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications. :star:1038
* [uitable](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data. :star:403

## Configuration

*Libraries for configuration parsing.*

* [config](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing. :star:138
* [configure](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables. :star:30
* [env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults). :star:361
* [envcfg](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs. :star:84
* [envconf](https://github.com/ian-kent/envconf) - Configuration from environment. :star:5
* [envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables. :star:110
* [envh](https://github.com/antham/envh) - Helpers to manage environment variables. :star:83
* [gcfg](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections. :star:73
* [goConfig](https://github.com/crgimenes/goConfig) - Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file. :star:53
* [godotenv](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`). :star:855
* [gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy. :star:49
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
* [hjson](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments. :star:107
* [ingo](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file. :star:15
* [ini](https://github.com/go-ini/ini) - Go package to read and write INI files. :star:755
* [joshbetz/config](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP. :star:149
* [mini](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files. :star:15
* [store](https://github.com/tucnak/store) - Lightweight configuration manager for Go. :star:215
* [viper](https://github.com/spf13/viper) - Go configuration with fangs. :star:4130
* [xdg](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html). :star:1

## Continuous Integration

*Tools for help with continuous integration.*

* [drone](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go. :star:12328
* [goveralls](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system. :star:432
* [overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls. :star:73
* [roveralls](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool. :star:1

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* [c6](https://github.com/c9s/c6) - High performance SASS compatible-implementation compiler written in Go. :star:390
* [gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor. :star:395
* [go-libsass](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project. :star:67

## Data Structures

*Generic datastructures and algorithms in Go.*

* [binpacker](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream. :star:62
* [bit](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions. :star:6
* [bitset](https://github.com/willf/bitset) - Go package implementing bitsets. :star:319
* [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go.
* [bloom](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation. :star:2
* [boomfilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams. :star:874
* [concurrent-writer](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`. :star:5
* [count-min-log](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory). :star:35
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. :star:255
* [encoding](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go. :star:80
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree. :star:26
* [go-datastructures](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures. :star:3737
* [go-ef](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding. :star:5
* [go-geoindex](https://github.com/hailocab/go-geoindex) - In-memory geo index. :star:264
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding. :star:72
* [gods](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc. :star:3395
* [golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go. :star:643
* [goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go. :star:6
* [goskiplist](https://github.com/ryszard/goskiplist) - Skip list implementation in Go. :star:141
* [gota](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go. :star:404
* [hilbert](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves. :star:111
* [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction. :star:556
* [levenshtein](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. :star:8
* [levenshtein](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go. :star:12
* [mafsa](https://github.com/smartystreets/mafsa) - MA-FSA implementation with Minimal Perfect Hashing. :star:258
* [merkletree](https://github.com/cbergoon/merkletree) - Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures. :star:20
* [roaring](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets. :star:314
* [skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go. :star:41
* [trie](https://github.com/derekparker/trie) - Trie implementation in Go. :star:215
* [ttlcache](https://github.com/diegobernardes/ttlcache) - In-memory LRU string-interface{} map with expiration for golang.
* [willf/bloom](https://github.com/willf/bloom) - Go package implementing Bloom filters. :star:378

## Database

*Databases implemented in Go.*

* [badger](https://github.com/dgraph-io/badger) - Fast key-value store in Go. :star:2771
* [BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data. :star:1287
* [bolt](https://github.com/boltdb/bolt) - Low-level key/value database for Go. :star:7437
* [buntdb](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support. :star:1647
* [cache2go](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts. :star:370
* [cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore. :star:11925
* [couchcache](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server. :star:27
* [dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database. :star:4231
* [diskv](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store. :star:501
* [eliasdb](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language. :star:451
* [forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB. :star:28
* [GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC. :star:291
* [geocache](https://github.com/melihmucuk/geocache) - In-memory cache that is suitable for geolocation based applications. :star:72
* [go-cache](https://github.com/pmylund/go-cache) - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go. :star:1880
* [groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. :star:5967
* [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
* [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB. :star:2327
* [levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB. :star:315
* [moss](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go. :star:395
* [piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures. :star:143
* [prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database. :star:13389
* [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite. :star:3377
* [Scribble](https://github.com/nanobox-io/golang-scribble) - Tiny flat file JSON store. :star:92
* [tempdb](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items. :star:7
* [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1. :star:10911
* [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang. :star:1974
* [Tile38](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing. :star:3613

*Database schema migration.*

* [darwin](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go. :star:51
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library. :star:4
* [gondolier](https://github.com/emvicom/gondolier) - Gondolier is a library to auto migrate database schemas using structs. :star:10
* [goose](https://github.com/steinbacher/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. :star:54
* [gormigrate](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM. :star:72
* [migrate](https://github.com/mattes/migrate) - Database migrations. CLI and Golang library. :star:1802
* [pravasan](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc. :star:18
* [soda](https://github.com/markbates/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata. :star:809

*Database tools.*

* [chproxy](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database. :star:70
* [go-mysql](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication. :star:761
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically. :star:1040
* [kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang. :star:3130
* [myreplication](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Supports statement and row based replication. :star:87
* [orchestrator](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer. :star:960
* [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser. :star:4700
* [pREST](https://github.com/nuveo/prest) - Serve a RESTful API from any PostgreSQL database.
* [rwdb](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup. :star:8
* [vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. :star:5265

*SQL query builder, libraries for building and using SQL.*

* [dat](https://github.com/mgutz/dat) - Go Postgres Data Access Toolkit. :star:480
* [Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease. :star:321
* [goqu](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library. :star:360
* [igor](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax. :star:63
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities. :star:190
* [scaneo](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs. :star:121
* [sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance. :star:89
* [Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries. :star:1310
* [xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [avatica](https://github.com/Boostport/avatica) - Apache Phoenix/Avatica SQL driver for database/sql. :star:36
    * [bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go. :star:5
    * [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go. :star:70
    * [go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql. :star:63
    * [go-bqstreamer](https://github.com/rounds/go-bqstreamer) - BigQuery fast and concurrent stream insert.
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go. :star:643
    * [go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql. :star:254
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go. :star:4538
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql. :star:2147
    * [gofreetds](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org). :star:55
    * [pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql. :star:1178
    * [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql. :star:3347

* NoSQL Databases
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language. :star:239
    * [arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB. :star:54
    * [asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go. :star:2
    * [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends.
    * [dsc](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files. :star:4
    * [dynago](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB. :star:49
    * [go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go. :star:254
    * [go-couchdb](https://github.com/fjl/go-couchdb) - Yet another CouchDB HTTP API wrapper for Go. :star:44
    * [gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK. :star:234
    * [gocql](http://gocql.github.io) - Go language driver for Apache Cassandra.
    * [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language.
    * [gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB.
    * [goriak](https://github.com/zegl/goriak) - Go language driver for Riak KV. :star:19
    * [mgo](https://godoc.org/labix.org/v2/mgo) - MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
    * [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang. :star:22
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang. :star:66
    * [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang. :star:309
    * [redigo](https://github.com/garyburd/redigo) - Redigo is a Go client for the Redis database. :star:3790
    * [redis](https://github.com/go-redis/redis) - Redis client for Golang. :star:2589
    * [redis](https://github.com/hoisie/redis) - Simple, powerful Redis client for Go. :star:551
    * [redis](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services. :star:150
    * [xredis](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client. :star:7

* Search and Analytic Databases.
    * [bleve](https://github.com/blevesearch/bleve) - Modern text indexing library for go. :star:3669
    * [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go. :star:2054
    * [elasticsql](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go. :star:122
    * [elastigo](https://github.com/mattbaird/elastigo) - Elasticsearch client library. :star:890
    * [goes](https://github.com/belogik/goes) - Library to interact with Elasticsearch. :star:78
    * [riot](https://github.com/go-ego/riot) - Go Open Source, Distributed, Simple and efficient Search Engine :star:3155
    * [skizze](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage. :star:45

## Date and Time

*Libraries for working with dates and times.*

* [carbon](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library. :star:150
* [date](https://github.com/rickb777/date) - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day. :star:8
* [dateparse](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance. :star:71
* [durafmt](https://github.com/hako/durafmt) - Time duration formatting library for Go. :star:167
* [feiertage](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving... :star:8
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang). :star:29
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) - Calculate the sunrise and sunset times for a given location. :star:2
* [goweek](https://github.com/grsmv/goweek) - Library for working with week entity in golang. :star:12
* [now](https://github.com/jinzhu/now) - Now is a time toolkit for golang. :star:1040
* [NullTime](https://github.com/kirillDanshin/nulltime) - Nullable `time.Time`. :star:4
* [timeutil](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package. :star:140
* [tuesday](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function. :star:3

## Distributed Systems

*Packages that help with building Distributed Systems.*

* [celeriac](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go. :star:28
* [digota](https://github.com/digota/digota) - grpc ecommerce microservice. :star:166
* [drmaa](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard. :star:19
* [emitter-io](https://github.com/emitter-io/emitter) - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love. :star:174
* [flowgraph](https://github.com/vectaport/flowgraph) - MPI-style ready-send coordination layer. :star:33
* [gleam](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed. :star:1028
* [glow](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go. :star:1839
* [go-jump](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function. :star:135
* [go-kit](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc. :star:8547
* [gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load. :star:417
* [grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC. :star:4422
* [hprose](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now. :star:664
* [jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0. :star:42
* [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation. :star:19
* [KrakenD](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway framework with middlewares. :star:189
* [micro](https://github.com/micro/micro) - Pluggable microservice toolkit and distributed systems platform. :star:3798
* [NATS](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems. :star:3595
* [raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp. :star:1475
* [raft](https://github.com/coreos/etcd/tree/master/raft) - Go implementation of the Raft consensus protocol, by CoreOS.
* [ringpop-go](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications. :star:373
* [rpcx](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo. :star:1737
* [sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)). :star:235
* [tendermint](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols. :star:981
* [torrent](https://github.com/anacrolix/torrent) - BitTorrent client package. :star:1916
    * [dht](https://godoc.org/github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation.
    * [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client. :star:293

## Email

*Libraries that implement email creation and sending.*

* [douceur](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails. :star:108
* [email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go. :star:822
* [go-dkim](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email. :star:32
* [go-imap](https://github.com/emersion/go-imap) - IMAP library for clients and servers. :star:325
* [go-message](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages. :star:31
* [Gomail](https://github.com/go-gomail/gomail/) - Gomail is a very simple and powerful package to send emails.
* [Hectane](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API. :star:131
* [hermes](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails. :star:1066
* [MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface. :star:2819
* [SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email. :star:305
* [smtp](https://github.com/mailhog/smtp) - SMTP server protocol state machine. :star:36

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* [agora](https://github.com/PuerkitoBio/agora) - Dynamically typed, embeddable programming language in Go.
* [anko](https://github.com/mattn/anko) - Scriptable interpreter written in Go. :star:481
* [binder](https://github.com/alexeyco/binder) - Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua). :star:6
* [gisp](https://github.com/jcla1/gisp) - Simple LISP in Go. :star:380
* [go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go. :star:526
* [go-lua](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go. :star:1131
* [go-php](https://github.com/deuill/go-php) - PHP bindings for Go. :star:389
* [go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API. :star:571
* [golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API. :star:367
* [gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go. :star:1898
* [ngaro](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro. :star:8
* [otto](https://github.com/robertkrimen/otto) - JavaScript interpreter written in Go. :star:3361
* [purl](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go. :star:19

## Files

*Libraries for  handling files and file systems.*

* [afero](https://github.com/spf13/afero) - FileSystem Abstraction System for Go. :star:1224
* [go-csv-tag](https://github.com/artonge/go-csv-tag) - Load csv file using tag. :star:15
* [go-gtfs](https://github.com/artonge/go-gtfs) - Load gtfs files in go. :star:5
* [notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal. :star:281
* [skywalker](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease. :star:15
* [tarfs](https://github.com/posener/tarfs) - Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files. :star:15

## Financial

*Packages for accounting and finance.*

* [accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang. :star:332
* [decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers. :star:712
* [go-finance](https://github.com/FlashBoys/go-finance) - Comprehensive financial markets data in Go. :star:509
* [go-money](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern. :star:369
* [ofxgo](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client). :star:24
* [vat](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates. :star:39

## Forms

*Libraries for working with forms.*

* [bind](https://github.com/robfig/bind) - Bind form data to any Go values. :star:17
* [binding](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct. :star:629
* [conform](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags. :star:105
* [form](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. :star:216
* [formam](https://github.com/monoculum/formam) - decode form's values into a struct. :star:85
* [forms](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. :star:76
* [gorilla/csrf](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services. :star:247
* [nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go. :star:802

## Game Development

*Awesome game development libraries.*

* [Azul3D](https://github.com/azul3d/engine) - 3D game engine written in Go. :star:324
* [Ebiten](https://github.com/hajimehoshi/ebiten) - simple 2D game library in Go. :star:512
* [engo](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm. :star:691
* [GarageEngine](https://github.com/vova616/GarageEngine) - 2d game engine written in Go working on OpenGL. :star:282
* [glop](https://github.com/runningwild/glop) - Glop (Game Library Of Power) is a fairly simple cross-platform game library. :star:78
* [go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm. :star:223
* [go-collada](https://github.com/GlenKelley/go-collada) - Go package for working with the Collada file format. :star:11
* [go-sdl2](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/). :star:715
* [go3d](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go. :star:130
* [gonet](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang. :star:876
* [goworld](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping :star:425
* [Leaf](https://github.com/name5566/leaf) - Lightweight game server framework. :star:1720
* [nano](https://github.com/lonnng/nano) - Lightweight, facility, high performance golang based game server framework :star:331
* [Oak](https://github.com/oakmound/oak) - Pure Go game engine. :star:414
* [Pixel](https://github.com/faiface/pixel) - Hand-crafted 2D game library in Go. :star:811
* [raylib-go](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming. :star:186
* [termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox. :star:818

## Generation and Generics

*Tools to enhance the language with features like generics via code generation.*

* [efaceconv](https://github.com/t0pep0/efaceconv) - Code generation tool for high performance conversion from interface{} to immutable type without allocations. :star:25
* [gen](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality. :star:844
* [go-enum](https://github.com/abice/go-enum) - Code generation for enums from code comments. :star:24
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go.
* [goderive](https://github.com/awalterschulze/goderive) - Derives functions from input types. :star:484
* [interfaces](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions. :star:124
* [jennifer](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates. :star:553
* [pkgreflect](https://github.com/ungerik/pkgreflect) - Go preprocessor for package scoped reflection. :star:61

## Go Compilers

*Tools for compiling Go to other languages.*

* [gopherjs](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript. :star:5908
* [llgo](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go. :star:856
* [tardisgo](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler. :star:358

## Goroutines

*Tools for managing and working with Goroutines.*

* [go-floc](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease. :star:104
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order. :star:58
* [GoSlaves](https://github.com/themester/GoSlaves) - Simple and Asynchronous Goroutine pool library. :star:10
* [goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker. :star:1854
* [grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool. :star:265
* [pool](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation. :star:329
* [semaphore](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context. :star:14
* [tunny](https://github.com/Jeffail/tunny) - Goroutine pool for golang. :star:636
* [worker-pool](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool. :star:6
* [workerpool](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued. :star:8

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* [app](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. :star:1919
* [go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron). :star:978
* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK.
* [go-qml](https://github.com/go-qml/qml) - QML support for the Go language. :star:1831
* [go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform. :star:804
* [goqt](https://github.com/visualfc/goqt) - Golang bindings to the Qt cross-platform application framework. :star:1321
* [gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3. :star:322
* [gowd](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform. :star:69
* [qt](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi). :star:3265
* [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform. :star:4611
* [walk](https://github.com/lxn/walk) - Windows application library kit for Go. :star:2212
* [webview](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). :star:485

*Interaction*

* [gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go. :star:400
* [robotgo](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other. :star:2294
* [systray](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area. :star:282
* [trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar. :star:112


## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## Images

*Libraries for manipulating images.*

* [bild](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go. :star:1595
* [bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips. :star:412
* [geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string. :star:928
* [gg](https://github.com/fogleman/gg) - 2D rendering in pure Go. :star:1126
* [gift](https://github.com/disintegration/gift) - Package of image processing filters. :star:976
* [go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library. :star:65
* [go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library. :star:40
* [go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go. :star:237
* [go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV.
* [go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go. :star:21
* [gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+. :star:477
* [govatar](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars. :star:210
* [imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API. :star:651
* [imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing. :star:1486
* [imaging](https://github.com/disintegration/imaging) - Simple Go image processing package. :star:1353
* [img](https://github.com/hawx/img) - Selection of image manipulation tools. :star:109
* [ln](https://github.com/fogleman/ln) - 3D line art rendering in Go. :star:2067
* [mpo](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos. :star:3
* [picfit](https://github.com/thoas/picfit) - An image resizing server written in Go. :star:772
* [pt](https://github.com/fogleman/pt) - Path tracing engine written in Go. :star:1494
* [resize](https://github.com/nfnt/resize) - Image resizing for Go with common interpolation methods. :star:1621
* [rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD. :star:138
* [smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes. :star:990
* [svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation. :star:947
* [tga](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder. :star:15

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* [connectordb](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT. :star:83
* [devices](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io. :star:192
* [eywa](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices. :star:12
* [flogo](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration. :star:322
* [gatt](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals. :star:584
* [gobot](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things.
* [mainflux](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server. :star:305
* [sensorbee](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT. :star:122

## Logging

*Libraries for generating and working with log files.*

* [distillog](https://github.com/amoghe/distillog) - distilled levelled logging (think of it as stdlib + log levels). :star:1
* [glg](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go. :star:4
* [glog](https://github.com/golang/glog) - Leveled execution logs for Go. :star:1612
* [go-cronowriter](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog. :star:4
* [go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers. :star:14
* [go-log](https://github.com/ian-kent/go-log) - Log4j implementation in Go. :star:24
* [go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers. :star:169
* [gologger](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch. :star:27
* [gomol](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs. :star:8
* [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.
* [journald](https://github.com/ssgreg/journald) - Go implementation of systemd Journal's native API for logging. :star:1
* [log](https://github.com/apex/log) - Structured logging package for Go. :star:472
* [log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go. :star:226
* [log](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation. :star:13
* [log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang. :star:73
* [log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go. :star:660
* [logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging. :star:4
* [logex](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib. :star:30
* [logger](https://github.com/azer/logger) - Minimalistic logging library for Go. :star:94
* [logo](https://github.com/mbndr/logo) - Golang logger to different configurable writers. :star:1
* [logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go. :star:6078
* [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). :star:17
* [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger. :star:182
* [logxi](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy. :star:314
* [lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser. :star:653
* [mlog](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. :star:12
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail). :star:76
* [seelog](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting. :star:1028
* [spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging. :star:1702
* [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. :star:43
* [tail](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program. :star:881
* [xlog](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format. :star:1
* [xlog](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching. :star:117
* [zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go. :star:3074
* [zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger. :star:588

## Machine Learning

*Libraries for Machine Learning.*

* [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang. :star:515
* [CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. :star:565
* [fonet](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go. :star:4
* [gago](https://github.com/MaxHalford/gago) - Multi-population, flexible, parallel genetic algorithm. :star:398
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms. :star:8
* [go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library. :star:92
* [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang. :star:154
* [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang. :star:49
* [gobrain](https://github.com/goml/gobrain) - Neural Networks written in go. :star:222
* [godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods. :star:17
* [goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go. :star:59
* [GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go. :star:4929
* [golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go. :star:33
* [goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go. :star:794
* [goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go. :star:92
* [gorgonia](https://github.com/chewxy/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms. :star:1505
* [goscore](https://github.com/asafschers/goscore) - Go Scoring API for PMML. :star:7
* [gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library. :star:392
* [libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14. :star:53
* [mlgo](https://github.com/NullHypothesis/mlgo) - This project aims to provide minimalistic machine learning algorithms in Go. :star:3
* [neat](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT). :star:34
* [neural-go](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation. :star:54
* [probab](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go. :star:7
* [regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine. :star:180
* [shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go. :star:109
* [tfgo](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python. :star:647

## Messaging

*Libraries that implement messaging systems.*

* [Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go. :star:2308
* [dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus. :star:186
* [drone-line](https://github.com/appleboy/drone-line) - Sending [Line](https://business.line.me/en/services/bot) notifications using a binary, docker or Drone CI. :star:44
* [emitter](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins. :star:166
* [event](https://github.com/agoalofalife/event) - Implementation of the pattern observer. :star:7
* [EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility. :star:314
* [gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go. :star:4
* [Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io). :star:249
* [go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec. :star:33
* [go-nsq](https://github.com/nsqio/go-nsq) - the official Go package for NSQ. :star:931
* [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework. :star:1958
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service. :star:4
* [Gollum](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations. :star:569
* [golongpoll](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple. :star:354
* [goose](https://github.com/ian-kent/goose) - Server Sent Events in Go. :star:31
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster. :star:1611
* [gorush](https://github.com/appleboy/gorush) - Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm). :star:1593
* [guble](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence. :star:114
* [machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing. :star:1870
* [mangos](https://github.com/go-mangos/mangos) - Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability. :star:1258
* [melody](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling. :star:752
* [messagebus](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD. :star:5
* [NATS Go Client](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library.
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel. :star:19
* [oplog](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs. :star:84
* [pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go.
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue. :star:32
* [sarama](https://github.com/Shopify/sarama) - Go library for Apache Kafka. :star:2342
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices. :star:936
* [zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). :star:583

## Miscellaneous

*These libraries were placed here because none of the other categories seemed to fit.*

* [alice](https://github.com/magic003/alice) - Additive dependency injection container for Golang. :star:8
* [antch](https://github.com/antchfx/antch) - A fast, powerful and extensible web crawling & scraping framework. :star:19
* [archiver](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives. :star:722
* [autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields. :star:18
* [avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation. :star:3
* [banner](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications. :star:150
* [battery](https://github.com/distatus/battery) - Cross-platform, normalized battery information library. :star:83
* [bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go. :star:44
* [browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/). :star:26
* [captcha](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation. :star:5
* [conv](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types. :star:309
* [datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter. :star:20
* [errors](https://github.com/pkg/errors) - Package that provides simple error handling primitives. :star:2500
* [go-chat-bot](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go. :star:278
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang. :star:413
* [go-multierror](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error. :star:361
* [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
* [go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang. :star:547
* [go-sarah](https://github.com/oklahomer/go-sarah) - Framework to build bot for desired chat services including LINE, Slack, Gitter and more. :star:74
* [go-unarr](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives. :star:18
* [go.uuid](https://github.com/satori/go.uuid) - Implementation of Universally Unique Identifier (UUID). Supported both creation and parsing of UUIDs. :star:1562
* [gofakeit](https://github.com/brianvoe/gofakeit) - Random data generator written in go. :star:58
* [goid](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs. :star:11
* [gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). :star:2166
* [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS. :star:1069
* [gountries](https://github.com/pariz/gountries) - Package that exposes country and subdivision data. :star:144
* [hanu](https://github.com/sbstjn/hanu) - Framework for writing Slack bots. :star:38
* [health](https://github.com/dimiro1/health) - Easy to use, extensible health check library. :star:260
* [healthcheck](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services. :star:19
* [hostutils](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list.
* [indigo](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58. :star:24
* [jobs](https://github.com/albrow/jobs) - Persistent and flexible background jobs library. :star:411
* [lk](https://github.com/hyperboloide/lk) - A simple licensing library for golang. :star:26
* [margelet](https://github.com/zhulik/margelet) - Framework for building Telegram bots. :star:49
* [persian](https://github.com/mavihq/persian) - Some utilities for Persian language in go. :star:3
* [secdl](https://github.com/xor-gate/secdl) - Lighttpd ModSecDownload algorithm ported to go to secure download urls. :star:5
* [shellwords](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell. :star:1
* [shortid](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs. :star:183
* [slacker](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots. :star:135
* [stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... :star:81
* [turtle](https://github.com/hackebrot/turtle) - Emojis for Go. :star:30
* [uuid](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier. :star:3
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and ouput handling.
* [werr](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called. :star:5
* [xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber. :star:28
* [xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages. :star:412

## Natural Language Processing

*Libraries for working with human languages.*

* [dpar](https://github.com/danieldk/dpar/) - Transition-based statistical dependency parser.
* [go-eco](https://github.com/ThePaw/go-eco) - Similarity, dissimilarity and distance matrices; diversity, equitability and inequality measures; species richness estimators; coenocline models. :star:3
* [go-i18n](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text.
* [go-mystem](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer. :star:11
* [go-nlp](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work. :star:70
* [go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm. :star:42
* [go-unidecode](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text. :star:19
* [go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings. :star:22
* [gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm. :star:426
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2. :star:12
* [gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go. :star:57
* [gse](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other. :star:149
* [icu](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1. :star:16
* [libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. :star:9
* [MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. :star:53
* [nlp](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp. :star:307
* [nlp](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis). :star:70
* [paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm. :star:23
* [petrovich](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case. :star:6
* [porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm. :star:6
* [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer.
* [prose](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. :star:488
* [RAKE.go](https://github.com/Obaied/RAKE.go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE). :star:21
* [segment](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)
* [sentences](https://github.com/neurosnap/sentences) - Sentence tokenizer:  converts text into a list of sentences. :star:219
* [shamoji](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go. :star:2
* [snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). :star:16
* [stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers. :star:36
* [textcat](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text. :star:51
* [whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc). :star:253
* [when](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules. :star:758

## Networking

*Libraries for working with various layers of the network.*

* [arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826. :star:116
* [buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy. :star:184
* [canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252). :star:88
* [cidranger](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go. :star:226
* [dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. :star:30
* [dns](https://github.com/miekg/dns) - Go library for working with DNS. :star:2463
* [ether](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames. :star:46
* [ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. :star:121
* [fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http. :star:5393
* [ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959). :star:282
* [go-getter](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL. :star:429
* [go-stun](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389). :star:185
* [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language. :star:1105
* [golibwireshark](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data. :star:9
* [gopacket](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings. :star:1603
* [gopcap](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap. :star:287
* [goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet. :star:7
* [gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions. :star:254
* [gotcp](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications. :star:305
* [grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads. :star:244
* [graval](https://github.com/koofr/graval) - Experimental FTP server framework. :star:17
* [jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices. :star:69
* [kcp-go](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol. :star:950
* [kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol. :star:7016
* [lhttp](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily. :star:360
* [linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces. :star:32
* [llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response. :star:4
* [mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang. :star:367
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* [portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it. :star:32
* [publicip](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress). :star:12
* [raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface. :star:129
* [sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt. :star:428
* [ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh). :star:570
* [sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance. :star:95
* [stun](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol.
* [tcp_server](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster. :star:155
* [utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation. :star:119
* [water](https://github.com/songgao/water) - Simple TUN/TAP library. :star:337
* [winrm](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines. :star:137
* [xtcp](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication,graceful shutdown,custom protocol. :star:27
* [YANNFF](https://github.com/intel-go/yanff) - Framework for rapid development of performant network functions for cloud and bare-metal. :star:198

## OpenGL

*Libraries for using OpenGL in Go.*

* [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow). :star:414
* [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3. :star:428
* [goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). :star:106
* [goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events. :star:42
* [mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM. :star:191

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3.
* [go-pg](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance. :star:1312
* [go-queryset](https://github.com/jirfag/go-queryset) - 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM. :star:234
* [go-store](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go. :star:85
* [gomodel](https://github.com/cosiner/gomodel) - Lightweight, fast, orm-like library helps interactive with database. :star:56
* [GORM](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly. :star:7257
* [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go. :star:2619
* [lore](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go. :star:3
* [Marlow](https://github.com/dadleyy/marlow) - Generated ORM from project structs for compile time safety assurances. :star:15
* [pop/soda](https://github.com/markbates/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. :star:407
* [QBS](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM. :star:474
* [reform](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation. :star:578
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema. :star:854
* [upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. :star:1072
* [Xorm](https://github.com/go-xorm/xorm) - Simple and powerful ORM for Go. :star:2582
* [Zoom](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis. :star:179

## Package Management

*Libraries for package and dependency management.*

* [dep](https://github.com/golang/dep) - Go dependency tool. :star:6257
* [gigo](https://github.com/LyricalSecurity/gigo) - PIP-like dependency tool for golang, with support for private repositories and hashes. :star:187
* [glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip. :star:5833
* [godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies. :star:5083
* [gom](https://github.com/mattn/gom) - Go Manager - bundle for go. :star:1290
* [goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler.
* [gop](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH :star:34
* [gopm](https://github.com/gpmgo/gopm) - Go Package Manager. :star:1601
* [govendor](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file. :star:2769
* [gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go. :star:1181
* [gvt](https://github.com/FiloSottile/gvt) - `gvt` is a simple vendoring tool made for Go native vendoring (aka GO15VENDOREXPERIMENT), based on gb-vendor. :star:706
* [johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git. :star:215
* [nut](https://github.com/jingweno/nut) - Vendor Go dependencies. :star:247
* [VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments. :star:105

## Query Language

* [graphql](https://github.com/tmc/graphql) - graphql parser + utilities. :star:43
* [graphql](https://github.com/sevki/graphql) - GraphQL implementation in go. :star:33
* [graphql](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use. :star:923
* [graphql-go](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go. :star:2262
* [jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang. :star:117

## Resource Embedding

* [esc](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them. :star:256
* [fileb0x](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use. :star:183
* [go-embed](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable. :star:9
* [go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go. :star:131
* [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy. :star:1118
* [statics](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks. :star:46
* [statik](https://github.com/rakyll/statik) - Embeds static files into a Go executable. :star:846
* [templify](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries. :star:6
* [vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem. :star:219

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [blas](https://github.com/ziutek/blas) - Implementation of BLAS (Basic Linear Algebra Subprograms). :star:114
* [chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types. :star:456
* [evaler](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator. :star:30
* [ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages. :star:204
* [geom](https://github.com/skelterjohn/geom) - 2D geometry for golang. :star:33
* [go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go. :star:501
* [go-fn](https://github.com/ematvey/go-fn) - Mathematical functions written in Go language, that are not covered by math pkg. :star:6
* [go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language. :star:3
* [go.matrix](https://github.com/skelterjohn/go.matrix) - linear algebra for go (has been stalled). :star:300
* [gocomplex](https://github.com/varver/gocomplex) - Complex number library for the Go programming language. :star:3
* [goent](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures :star:3
* [gofrac](https://github.com/anschelsc/gofrac) - (goinstallable) fractions library for go with support for basic arithmetic. :star:6
* [gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams. :star:103
* [gonum/mat64](https://github.com/gonum/matrix) - The general purpose package for matrix computation. Package mat64 provides basic linear algebra operations for float64 matrices. :star:464
* [gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go. :star:697
* [goraph](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorith visualization). :star:429
* [gosl](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more. :star:965
* [gostat](https://github.com/ematvey/gostat) - Statistics library for the go language. :star:22
* [graph](https://github.com/yourbasic/graph) - Library of basic graph algorithms. :star:21
* [ode](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions. :star:4
* [pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go. :star:32
* [PiHex](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi. :star:3
* [sparse](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries. :star:19
* [stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library. :star:804
* [streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data. :star:1305
* [vectormath](https://github.com/spate/vectormath) - Vectormath for Go, an adaptation of the scalar C functions from Sony's Vector Math library, as found in the Bullet-2.79 source code (currently inactive). :star:59

## Security

*Libraries that are used to help make your application more secure.*

* [acmetool](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal. :star:1379
* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) - Auto
  provision Let's Encrypt certificates and start a TLS server.
* [BadActor](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban. :star:211
* [go-yara](https://github.com/hillu/go-yara) - Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)". :star:67
* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords. :star:6
* [lego](https://github.com/xenolf/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt). :star:2204
* [memguard](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory. :star:684
* [nacl](https://github.com/kevinburke/nacl) - Go implementation of the NaCL set of API's. :star:336
* [passlib](https://github.com/hlandau/passlib) - Futureproof password hashing library. :star:171
* [secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins. :star:819
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in. :star:122
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys. :star:111

## Serialization

*Libraries and tools for binary serialization.*

* [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang.
* [bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go. :star:57
* [colfer](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format. :star:302
* [csvutil](https://github.com/jszwec/csvutil) - High Performance, idiomatic CSV record encoding and decoding to native Go structures. :star:166
* [go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go. :star:254
* [go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support. :star:853
* [gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets. :star:1332
* [goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers. :star:2356
* [jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json". :star:1678
* [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures. :star:1170
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions. :star:76
* [structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures. :star:65

## Server Applications

* [algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. :star:391
* [Caddy](https://github.com/mholt/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use. :star:15085
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [devd](https://github.com/cortesi/devd) - Local webserver for developers. :star:2459
* [etcd](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery. :star:15864
* [Fider](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback. :star:172
* [minio](https://github.com/minio/minio) - Minio is a distributed object storage server. :star:9331
* [nsq](http://nsq.io/) - A realtime distributed messaging platform.
* [yakvs](https://github.com/sci4me/yakvs) - Small, networked, in-memory key-value store. :star:21

## Template Engines

*Libraries and tools for templating and lexing.*

* [ace](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold. :star:640
* [amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade.
* [damsel](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others.
* [ego](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.
* [fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/).
* [gofpdf](https://github.com/jung-kurt/gofpdf) - PDF document generator with high level support for text, drawing and images.
* [grender](https://github.com/dannyvankooten/grender) - small wrapper around html/template for file-based templates that support extending other template files.
* [hero](https://github.com/shiyanhui/hero) - Hero is a handy, fast and powerful go template engine.
* [jet](https://github.com/CloudyKit/jet) - Jet template engine.
* [kasia.go](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation.
* [liquid](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates.
* [mustache](https://github.com/hoisie/mustache) - Go implementation of the Mustache template language.
* [pongo2](https://github.com/flosch/pongo2) - Django-like template-engine for Go.
* [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.
* [raymond](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go.
* [Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang.
* [Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/).
* [velvet](https://github.com/gobuffalo/velvet) - Complete handlebars implementation in Go.

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.
    * [badio](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package.
    * [baloo](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy.
    * [bro](https://github.com/marioidival/bro) - Watch files in directory and run tests for them.
    * [cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework.
    * [dbcleaner](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby.
    * [dsunit](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files.
    * [frisby](https://github.com/verdverm/frisby) - REST API testing framework.
    * [ginkgo](http://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
    * [go-carpet](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal.
    * [go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code.
    * [go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests.
    * [goblin](https://github.com/franela/goblin) - Mocha like testing framework fo Go.
    * [gocheck](http://labix.org/gocheck) - More advanced testing framework alternative to gotest.
    * [GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload.
    * [godog](https://github.com/DATA-DOG/godog) - Cucumber or Behat like BDD framework for Go.
    * [gofight](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework.
    * [gomega](http://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
    * [GoSpec](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language.
    * [gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
    * [gosuite](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests.
    * [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
    * [httpexpect](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.
    * [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
    * [testfixtures](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications.
    * [Testify](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package.
    * [wstest](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler.

* Mock
    * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects.
    * [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions.
    * [go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes.
    * [gock](https://github.com/h2non/gock) - Versatile HTTP mocking made easy.
    * [gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language.
    * [govcr](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing.
    * [minimock](https://github.com/gojuno/minimock) - Mock generator for Go interfaces.
    * [mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter.

* Fuzzing and delta-debugging/reducing/shrinking.
    * [go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing system.
    * [gofuzz](https://github.com/google/gofuzz) - Library for populating go objects with random values.
    * [Tavor](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework.

* Selenium and browser control tools.
    * [cdp](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.
    * [chromedp](https://github.com/knq/chromedp) - Way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.
    * [ggr](https://github.com/aandryashin/ggr) - Lightweight server that routes and proxies Selenium Wedriver requests to multiple Selenium hubs.
    * [selenoid](https://github.com/aandryashin/selenoid) - alternative Selenium hub server that launches browsers within containers.

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
    * [align](https://github.com/Guitarbum722/align) - A general purpose application that aligns text.
    * [allot](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots.
    * [bbConvert](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags.
    * [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go.
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer.
    * [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers
    * [doi](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go.
    * [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go.
    * [enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/).
    * [genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings.
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
    * [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection).
    * [go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format.
    * [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language.
    * [go-pkg-rss](https://github.com/jteeuwen/go-pkg-rss) - This package reads RSS and Atom feeds and provides a caching mechanism that adheres to the feed specs.
    * [go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string.
    * [go-slugify](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support.
    * [go-vcard](https://github.com/emersion/go-vcard) - Parse and format vCard.
    * [gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go.
    * [gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language.
    * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - Format bytes to string.
    * [gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts.
    * [goq](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery).
    * [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
    * [goregen](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions.
    * [gotext](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go.
    * [guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text.
    * [inject](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector.
    * [mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
    * [sh](https://github.com/mvdan/sh) - Shell parser and formatter.
    * [slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support.
    * [Slugify](https://github.com/avelino/slugify) - Go slugify application that handles string.
    * [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).
* Utility
    * [gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go.
    * [kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms.
    * [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes.
    * [parth](https://github.com/codemodus/parth) - URL path segmentation parsing.
    * [radix](https://github.com/yourbasic/radix) - fast string sorting algorithm.
    * [xj2go](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct.
    * [xurls](https://github.com/mvdan/xurls) - Extract urls from text.

## Third-party APIs

*Libraries for accessing third party APIs.*

* [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
* [anaconda](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API.
* [aws-sdk-go](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language.
* [brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API.
* [cachet](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/).
* [circleci](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API.
* [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API.
* [discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API.
* [ethrpc](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API.
* [facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API.
* [fcm](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging.
* [gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API.
* [gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface.
* [gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging.
* [geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](http://open.mapquestapi.com/nominatim/), [OpenCage](http://geocoder.opencagedata.com/api.html), [HERE](https://developer.here.com/rest-apis/documentation/geocoder), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.
* [ghost](https://github.com/neuegram/ghost) - Go Library for accessing the Snapchat API.
* [github](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3.
* [githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4.
* [go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API.
* [go-imgur](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com)
* [go-jira](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
* [go-marathon](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS.
* [go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api).
* [go-sptrans](https://github.com/sergioaugrod/go-sptrans) - Go client library for the SPTrans Olho Vivo API.
* [go-telegraph](https://github.com/toby3d/go-telegraph) - Telegraph publishing platform API client.
* [go-tgbot](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware.
* [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github.
* [go-twitch](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API.
* [go-twitter](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs.
* [go-unsplash](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API.
* [go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API.
* [goamz](https://github.com/mitchellh/goamz) - Popular fork of [goamz](https://launchpad.net/goamz) which adds some missing API calls to certain packages.
* [golyrics](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website.
* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library.
* [google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go.
* [google-analytics](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting.
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library.
* [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
* [gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
* [govkbot](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library.
* [hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API.
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP.
* [Medium](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API.
* [megos](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster.
* [micha](https://github.com/onrik/micha) - Go Library for Telegram bot api.
* [minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage.
* [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
* [patreon-go](https://github.com/mxpv/patreon-go) - Go library for Patreon API.
* [paypal](https://github.com/logpacker/paypalsdk) - Wrapper for PayPal payment API.
* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK.
* [pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API.
* [rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP.
* [shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API.
* [slack](https://github.com/nlopes/slack) - Slack API in Go.
* [smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API.
* [spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API.
* [steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers.
* [stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API.
* [tbot](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http.
* [telebot](https://github.com/tucnak/telebot) - Telegram bot framework written in Go.
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client.
* [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API.
* [TheMovieDb](https://github.com/jbrodriguez/go-tmdb) - Simple golang package to communicate with [themoviedb.org](https://themoviedb.org).
* [translate](https://github.com/poorny/translate) - Go online translation package.
* [Trello](https://github.com/adlio/trello) - Go wrapper for the Trello API.
* [tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API.
* [webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket.
* [zooz](https://github.com/gojuno/go-zooz) - Go client for the Zooz API.

## Utilities

*General utilities and tools to make your life easier.*

* [abutil](https://github.com/bahlo/abutil) - Collection of often-used Golang helpers.
* [apm](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API.
* [boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates.
* [chyle](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities.
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go.
* [clockwerk](http://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.
* [command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher.
* [coop](https://github.com/rakyll/coop) - Cheat sheet for some of the common concurrent flows in Go.
* [copy-pasta](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage.
* [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics.
* [Death](https://github.com/vrecan/death) - Managing go application shutdown with signals.
* [Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go.
* [delve](https://github.com/derekparker/delve) - Go debugger.
* [dlog](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls.
* [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy.
* [evaluator](https://github.com/nullne/evaluator) - Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend.
* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files.
* [fastlz](https://github.com/digitalcrab/fastlz) - Wrap over [FastLz](http://fastlz.org/) (free, open-source, portable real-time compression library) for GoLang.
* [filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature.
* [filler](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag.
* [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go.
* [generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex.
* [gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library.
* [git-time-metric](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git.
* [GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code.
* [go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code.
* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).
* [go-cron](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
* [go-debug](https://github.com/tj/go-debug) - Conditional debug logging for Golang libraries & applications.
* [go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go.
* [go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
* [go-httpheader](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields.
* [go-rate](https://github.com/beefsack/go-rate) - Timed rate limiter for Go.
* [go-respond](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses.
* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go.
* [go-torch](https://github.com/uber/go-torch) - Stochastic flame graph profiler for Go programs.
* [go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
* [go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities.
* [goback](https://github.com/carlescere/goback) - Go simple exponential backoff package.
* [godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons.
* [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox.
* [gohper](https://github.com/cosiner/gohper) - Various tools/modules help for development.
* [gojq](https://github.com/elgs/gojq) - JSON query in Golang.
* [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON.
* [golarm](https://github.com/msempere/golarm) - Fire alarms with system events.
* [golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks.
* [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.
* [goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images.
* [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible.
* [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report.
* [goreq](https://github.com/franela/goreq) - Minimal and simple request library for Go language.
* [goreq](https://github.com/smallnest/goreq) - Enhanced simplified HTTP client based on gorequest.
* [gorequest](https://github.com/parnurzeal/gorequest) - Simplified HTTP client with rich features for Go.
* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features.
* [gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go.
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.
* [gpath](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection.
* [grequests](https://github.com/levigross/grequests) - Elegant and simple `net/http` wrapper that follows Python's requests library.
* [gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
* [htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility.
* [httpcontrol](https://github.com/facebookgo/httpcontrol) - Package httpcontrol allows for HTTP transport level control around timeouts and retries.
* [hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal.
* [hystrix-go](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.
* [immortal](https://github.com/immortal/immortal) - *nix cross-platform (OS agnostic) supervisor.
* [intrinsic](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code.
* [JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference.
* [jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON.
* [jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects.
* [jsonhal](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses.
* [kazaam](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents.
* [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go.
* [mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
* [mergo](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
* [minify](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.
* [mmake](https://github.com/tj/mmake) - Modern Make.
* [moldova](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template.
* [mp](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON.
* [mssqlx](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.
* [multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers.
* [myhttp](https://github.com/inancgumus/myhttp) - Simple API to make HTTP GET requests with timeout support.
* [netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services.
* [ngrok](https://github.com/inconshreveable/ngrok) - Introspected tunnels to localhost.
* [okrun](https://github.com/xta/okrun) - go run error steamroller.
* [onecache](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).
* [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.
* [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool.
* [pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency.
* [pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API.
* [profile](https://github.com/pkg/profile) - Simple profiling support package for Go.
* [rclient](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs.
* [realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths.
* [repeat](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating.
* [request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™.
* [rerate](https://github.com/abo/rerate) - Redis-based rate counter and rate limiter for Go.
* [rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes.
* [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.
* [retry](https://github.com/kamilsk/retry) - Functional mechanism based on context to perform actions repetitively until successful.
* [robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics.
* [scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy.
* [sling](https://github.com/dghubble/sling) - Go HTTP requests builder for API clients.
* [spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options.
* [sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package.
* [Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB.
* [structs](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs.
* [Task](https://github.com/go-task/task) - simple "Make" alternative.
* [toolbox](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.
* [ugo](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go.
* [UNIS](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go.
* [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases.
* [util](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...).
* [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection.
* [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang.
* [xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.

## Validation

*Libraries for validation.*

* [govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs.
* [govalidator](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation.
* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.
* [validate](https://github.com/markbates/validate) - This package provides a framework for writing validations for Go applications.
* [validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.

## Version Control

*Libraries for version control.*

* [gh](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks.
* [git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2.
* [go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go.
* [hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.

## Video

*Libraries for manipulating video.*

* [gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries.
* [go-astisub](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
* [go-astits](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO.
* [goav](https://github.com/giorgisio/goav) - Comphrensive Go bindings for FFmpeg.
* [gst](https://github.com/ziutek/gst) - Go bindings for GStreamer.
* [libgosubs](https://github.com/wargarblgarbl/libgosubs) - Subtitle format support for go. Supports .srt, .ttml, and .ass.
* [v4l](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go.

## Web Frameworks

*Full stack web frameworks.*

* [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
* [Air](https://github.com/sheng/air) - Ideal RESTful web framework for Go.
* [Beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language.
* [Buffalo](http://gobuffalo.io) - Bringing the productivity of Rails to Go!
* [Echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework.
* [Fireball](https://github.com/zpatrick/fireball) - More "natural" feeling web framework.
* [Florest](https://github.com/jabong/florest-core) - High-performance workflow based REST API framework.
* [Gem](https://github.com/go-gem/gem) - Simple and fast web framework, friendly to REST API.
* [Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
* [Gizmo](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times.
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API.
* [go-relax](https://github.com/codehack/go-relax) - Framework of pluggable components to build RESTful API's.
* [go-rest](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go.
* [goa](https://github.com/raphael/goa) - Framework for developing microservices based on the design of Ruby's Praxis.
* [Goat](https://github.com/bahlo/goat) - Minimalistic REST API server in Go.
* [Golf](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library.
* [Gondola](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster.
* [gongular](https://github.com/mustafaakin/gongular) - Fast Go web framework with input mapping/validation and (DI) Dependency Injection.
* [Macaron](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go.
* [mango](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333.
* [Microservice](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang.
* [neo](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API.
* [Resoursea](https://github.com/resoursea/api) - REST framework for quickly writing resource based services.
* [REST Layer](http://rest-layer.io) - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
* [Revel](https://github.com/revel/revel) - High-productivity web framework for the Go language.
* [rex](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`.
* [sawsij](https://github.com/jaybill/sawsij) - lightweight, open-source web framework for building high-performance, data-driven web applications.
* [tango](https://github.com/lunny/tango) - Micro & pluggable web framework for Go.
* [tigertonic](https://github.com/rcrowley/go-tigertonic) - Go framework for building JSON web services inspired by Dropwizard.
* [traffic](https://github.com/pilu/traffic) - Sinatra inspired regexp/pattern mux and web framework for Go.
* [utron](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang).
* [violetear](https://github.com/nbari/violetear) - Go HTTP router.
* [YARF](https://github.com/yarf-framework/yarf) - Fast micro-framework designed to build REST APIs and web services in a fast and simple way.
* [Zerver](https://github.com/cosiner/zerver) - Zerver is an expressive, modular, feature completed RESTful framework.

### Middlewares

#### Actual middlewares

* [CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API.
* [formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST.
* [Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go.
* [Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler.
* [XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends.

#### Libraries for creating HTTP middlewares

* [alice](https://github.com/justinas/alice) - Painless middleware chaining for Go.
* [catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain").
* [chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware").
* [go-wrap](https://github.com/go-on/wrap) - Small middlewares package for net/http.
* [gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.
* [interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang.
* [muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http.
* [negroni](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang.
* [render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses.
* [renderer](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go.
* [rye](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.
* [stats](https://github.com/thoas/stats) - Go middleware that stores various information about your web application.
* [Volatile](https://github.com/volatile/core) - Minimalist middleware stack promoting flexibility, good practices and clean code.

### Routers

* [alien](https://github.com/gernest/alien) - Lightweight and fast http router from outer space.
* [Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer.
* [Bxog](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.
* [chi](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context.
* [fasthttprouter](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`.
* [FastRouter](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go.
* [gocraft/web](https://github.com/gocraft/web) - Mux and middleware package in Go.
* [Goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`.
* [GoRouter](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`.
* [gowww/router](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface.
* [httprouter](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework.
* [httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.
* [lars](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.
* [medeina](https://github.com/imdario/medeina) - Medeina is a HTTP routing tree based on HttpRouter, inspired by Roda and Cuba.
* [mux](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang.
* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.
* [pat](https://github.com/bmizerany/pat) - Sinatra style pattern muxer for Go’s net/http library, by the author of Sinatra.
* [pure](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation.
* [Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers.
* [vestigo](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications.
* [xmux](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support.
* [zeus](https://github.com/daryl/zeus) - Very simple and fast HTTP router for Go.

## Windows

* [d3d9](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9.
* [go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang.

## XML

*Libraries and tools for manipulating XML.*

* [go-pkg-xmlx](https://github.com/jteeuwen/go-pkg-xmlx) - Extension to the standard Go XML package. Maintains a node tree that allows forward/backwards browsing and exposes some simple single/multi-node search functions.
* [XML-Comp](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags.
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module.
* [xpath](https://github.com/antchfx/xpath) - XPath package for Go.
* [xquery](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression.

# Tools

*Go software and plugins.*

## Code Analysis

* [apicompat](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes.
* [dupl](https://github.com/mibk/dupl) - Tool for code clone detection.
* [errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs.
* [gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time.
* [Go Metalinter](https://github.com/alecthomas/gometalinter) - Metalinter is a tool to automatically apply all static analysis tool and report their output in normalized form.
* [go-checkstyle](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style refered to some points in Go Code Review Comments.
* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.
* [go-outdated](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages.
* [goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer.
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [GoLint](https://github.com/golang/lint) - Golint is a linter for Go source code.
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple is a linter for Go source code that specialises on simplifying code.
* [gostatus](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages.
* [interfacer](https://github.com/mvdan/interfacer) - Linter that suggests interface types.
* [lint](https://github.com/surullabs/lint) - Run linters as part of go test.
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) - tarp finds functions and methods without direct unit tests in Go source code.
* [unconvert](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source.
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - unused checks Go code for unused constants, variables, functions and types.
* [validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags.

## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
* [go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.
* [go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.
* [Goclipse](https://github.com/GoClipse/goclipse) - Eclipse plugin for Go.
* [gocode](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language.
* [GoSublime](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 2 providing code completion and other IDE-like features.
* [velour](https://github.com/velour/velour) - IRC client for the acme editor.
* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save.
* [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim.
* [vscode-go](https://github.com/Microsoft/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
* [Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes.

## Go Generate Tools

* [generic](https://github.com/usk81/generic) - flexible data type for Go.
* [genny](https://github.com/cheekybits/genny) - Elegant generics for Go.
* [gonerics](http://github.com/bouk/gonerics) - Idiomatic Generics in Go.
* [gotests](https://github.com/cweill/gotests) - Generate Go tests from your source code.
* [re2dfa](https://github.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code.

## Go Tools

* [colorgo](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output.
* [depth](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports.
* [gb](https://getgb.io/) - An easy to use project based build tool for the Go programming language.
* [go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format.
* [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo.
* [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.
* [richgo](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations.
* [rts](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses.

## Software Packages

*Software written in Go.*

### DevOps Tools

* [aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool.
* [aurora](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console.
* [awsenv](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile.
* [Banshee](https://github.com/eleme/banshee) - Anomalies detection system for periodic metrics.
* [Blast](https://github.com/dave/blast) - A simple tool for API load testing and batch jobs.
* [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool.
* [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework.
* [dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart).
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.
* [drone-scp](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI.
* [Dropship](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn.
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.
* [Gitea](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven.
* [Go Metrics](https://github.com/rcrowley/go-metrics) - Go port of Coda Hale's Metrics library: https://github.com/codahale/metrics.
* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update.
* [gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go.
* [godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application.
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
* [govvv](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries.
* [gox](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool.
* [goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging.
* [grapes](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease.
* [GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions.
* [Hey](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application.
* [kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler.
* [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.
* [manssh](https://github.com/xwjdsh/manssh) - manssh is a command line tool for managing your ssh alias config easily.
* [Moby](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems.
* [Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data.
* [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.
* [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
* [Pewpew](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester.
* [Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies.
* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker).
* [sg](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the reponse code and data between each call for specific server stress based on its previous response.
* [skm](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily!
* [StatusOK](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.
* [traefik](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends.
* [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
* [webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.
* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
* [winrm-cli](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines.

### Other Software
* [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets.
* [boxed](https://github.com/tejo/boxed) - Dropbox based blog engine.
* [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go.
* [Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
* [Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections.
* [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.
* [DDNS](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend.
* [Docker](http://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* [Documize](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools.
* [fleet](https://github.com/coreos/fleet) - Distributed init System.
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH.
* [gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go.
* [GoDNS](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at funciton list.
* [Gogland](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
* [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
* [hugo](http://gohugo.io/) - Fast and Modern Static Website Engine.
* [ide](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go.
* [ipe](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO.
* [JayDiff](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go.
* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [Leaps](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms.
* [limetext](http://limetext.org/) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
* [mockingjay](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.
* [myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go.
* [naclpipe](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go.
* [nes](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go.
* [orange-cat](https://github.com/noraesae/orange-cat) - Markdown previewer written in Go.
* [Orbit](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates.
* [peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.
* [Postman](https://github.com/zachlatta/postman) - Command-line utility for batch-sending email.
* [restic](https://github.com/restic/restic) - De-duplicating backup program.
* [rkt](https://github.com/coreos/rkt) - App Container runtime that integrates with init systems, is compatible with other container formats like Docker, and supports alternative execution engines like KVM.
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
* [shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control).
* [snap](https://github.com/intelsdi-x/snap) - Powerful telemetry framework.
* [Snitch](https://github.com/lucasgomide/snitch) - Simple way to notify your team and many tools when someone has deployed any application via Tsuru.
* [Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* [Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging.
* [toto](https://github.com/blogcin/ToTo) - Simple proxy server written in Go language, can be used together with browser.
* [toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests.
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [vFlow](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.
* [websysd](https://github.com/ian-kent/websysd) - Web based process manager (like Marathon or Upstart).
* [wellington](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass).

# Resources

*Where to discover new Go libraries.*

## Benchmarks

* [autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions.
* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.
* [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.
* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison.
* [go-type-assertion-benchmark](https://github.com/hgfischer/go-type-assertion-benchmark) - Naive performance test of two ways to do type assertion in Go.
* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark.
* [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods.
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language.
* [golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks) - Tiny collection of Go micro benchmarks. The intent is to compare some language features to others.
* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.
* [gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs.
* [kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark.
* [skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark.
* [speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language.

## Conferences

* [Capital Go](http://www.capitalgolang.com) - Washington, D.C., USA
* [dotGo](http://www.dotgo.eu) - Paris, France
* [GoCon](http://gocon.connpass.com/) - Tokyo, Japan
* [GolangUK](http://golanguk.com/) - London, UK
* [GopherChina](http://gopherchina.org) - Shanghai, China
* [GopherCon](http://www.gophercon.com/) - Denver, USA
* [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, BR
* [GopherCon Dubai](http://www.gophercon.ae/) - Dubai, UAE
* [GopherCon India](http://www.gophercon.in/) - Pune, India
* [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore
* [GothamGo](http://gothamgo.com/) - New York City, USA

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go Bootcamp](http://golangbootcamp.com)
* [GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books.
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)

## Gophers

* [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) - Go gopher Vector Data [.ai, .svg]
* [gopher-logos](https://github.com/GolangUA/gopher-logos) - adorable gopher logos
* [gopher-stickers](https://github.com/tenntenn/gopher-stickers)
* [gopher-vector](https://github.com/golang-samples/gopher-vector)
* [gophericons](https://github.com/shalakhin/gophericons)
* [gopherize.me](https://github.com/matryer/gopherize.me) - Gopherize yourself
* [gophers](https://github.com/ashleymcnamara/gophers) - Gopher artworks by Ashley McNamara
* [gophers](https://github.com/egonelbre/gophers) - Free gophers
* [gophers](https://github.com/rogeralsing/gophers) - random gopher graphics

## Meetups

* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
* [GoJakarta](https://www.meetup.com/GoJakarta/)
* [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
* [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
* [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
* [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
* [Golang Boston](https://www.meetup.com/bostongo/)
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
* [Golang Pune](https://www.meetup.com/Golang-Pune/)
* [Golang Singapore](https://www.meetup.com/golangsg/)
* [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
* [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
* [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
* [Golang Москва](https://www.meetup.com/Golang-Moscow/)
* [Golang Питер](https://www.meetup.com/Golang-Peter/)
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*Add the group of your city/country here (send **PR**)*

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

## Websites

* [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists.
* [Flipboard - Go Magazine](https://flipboard.com/section/the-golang-magazine-bVP7nS) - Collection of Go articles and tutorials.
* [Go Blog](http://blog.golang.org) - The official Go blog.
* [Go Challenge](http://golang-challenge.org/) - Learn Go by solving problems and getting feedback from Go experts.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.
* [Go Report Card](https://goreportcard.com) - A report card for your Go package.
* [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go.
* [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
* [Golang Flow](http://golangflow.io) - Post Updates, News, Packages and more.
* [Golang News](https://golangnews.com) - Links and news about Go programming.
* [golang-graphics](https://github.com/mholt/golang-graphics) - Collection of Go images, graphics, and art.
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [r/Golang](https://www.reddit.com/r/golang) - News about Go.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.

### Tutorials

* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go.
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang.
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card.
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* [Working with Go](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers.


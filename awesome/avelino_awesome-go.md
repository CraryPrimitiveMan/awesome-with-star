# Information comes from [avelino/awesome-go](https://github.com/avelino/awesome-go)
# Awesome Go

[![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](http://gophers.slack.com/messages/awesome) [![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)

[![patreon avelino](https://c5.patreon.com/external/logo/become_a_patron_button@2x.png)](https://www.patreon.com/avelinosource) financial support to Awesome Go

A curated list of awesome Go frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

### Contents

- [Awesome Go](#awesome-go)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Bot Building](#bot-building)
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
    - [Error Handling](#error-handling)
    - [Files](#files)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Functional](#functional)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Geographic](#geographic)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [IoT](#iot-internet-of-things)
    - [Job Scheduler](#job-scheduler)
    - [JSON](#json)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Microsoft Office](#microsoft-office)
        - [Microsoft Excel](#microsoft-excel)
    - [Miscellaneous](#miscellaneous)
        - [Dependency Injection](#dependency-injection)
        - [Project Layout](#project-layout)
        - [Strings](#strings)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
        - [HTTP Clients](#http-clients)
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
    - [UUID](#uuid)
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

* [EasyMIDI](https://github.com/algoGuy/EasyMIDI) - EasyMidi is a simple and reliable library for working with standard midi file (SMF). :star:22
* [flac](https://github.com/eaburns/flac) - No-frills native Go FLAC decoder that decodes FLAC files into byte slices. :star:83
* [flac](https://github.com/mewkiz/flac) - Native Go FLAC encoder/decoder with support for FLAC streams. :star:102
* [gaad](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser. :star:56
* [go-sox](https://github.com/krig/go-sox) - libsox bindings for go. :star:93
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) - libmediainfo bindings for go. :star:24
* [gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go. :star:8
* [id3v2](https://github.com/bogem/id3v2) - Fast and stable ID3 parsing and writing library for Go. :star:109
* [malgo](https://github.com/gen2brain/malgo) - Mini audio library. :star:71
* [minimp3](https://github.com/tosone/minimp3) - Lightweight MP3 decoder library. :star:25
* [mix](https://github.com/go-mix/mix) - Sequence-based Go-native audio mixer for music apps. :star:98
* [mp3](https://github.com/tcolgate/mp3) - Native Go MP3 decoder. :star:90
* [music-theory](https://github.com/go-music-theory/music-theory) - Music theory models in Go. :star:256
* [Oto](https://github.com/hajimehoshi/oto) - A low-level library to play sound on multiple platforms. :star:435
* [PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library. :star:302
* [portmidi](https://github.com/rakyll/portmidi) - Go bindings for PortMidi. :star:207
* [taglib](https://github.com/wtolson/go-taglib) - Go bindings for taglib. :star:66
* [vorbis](https://github.com/mccoyst/vorbis) - "Native" Go Vorbis decoder (uses CGO, but has no dependencies). :star:22
* [waveform](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams. :star:248

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* [authboss](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time. :star:1935
* [branca](https://github.com/hako/branca) - Golang implementation of Branca Tokens. :star:76
* [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC. :star:4961
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) - provides parser of cookies.txt file format. :star:2
* [go-jose](https://github.com/square/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. :star:1125
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - Standalone, specification-compliant,  OAuth2 server written in Golang. :star:1281
* [gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers. :star:1042
* [gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang. :star:911
* [goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box. :star:2270
* [httpauth](https://github.com/goji/httpauth) - HTTP Authentication middleware. :star:180
* [jwt](https://github.com/robbert229/jwt) - Clean and easy to use implementation of JSON Web Tokens (JWT). :star:71
* [jwt](https://github.com/pascaldekloe/jwt) - Lightweight JSON Web Token (JWT) library. :star:92
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options. :star:153
* [jwt-go](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT). :star:6001
* [loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam. :star:818
* [oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support. :star:2384
* [osin](https://github.com/openshift/osin) - Golang OAuth2 server library. :star:1545
* [paseto](https://github.com/o1egl/paseto) - Golang implementation of Platform-Agnostic Security Tokens (PASETO). :star:242
* [permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt. :star:351
* [rbac](https://github.com/zpatrick/rbac) - Minimalistic RBAC package for Go applications. :star:27
* [scs](https://github.com/alexedwards/scs) - Session Manager for HTTP servers. :star:529
* [securecookie](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding. :star:32
* [session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE). :star:91
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - Go session management using the SessionGate Redis module. :star:8
* [sessions](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers. :star:47
* [signedvalue](https://github.com/sashka/signedvalue) - Signed and timestamped strings compatible with [Tornado's](https://github.com/tornadoweb/tornado) `create_signed_value`, `decode_signed_value`, and therefore `set_secure_cookie` and `get_secure_cookie`. :star:7
* [sjwt](https://github.com/brianvoe/sjwt) - Simple jwt generator and parser. :star:32

## Bot Building

*Libraries for building and working with bots.*

* [go-chat-bot](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go. :star:469
* [go-sarah](https://github.com/oklahomer/go-sarah) - Framework to build bot for desired chat services including LINE, Slack, Gitter and more. :star:137
* [go-tgbot](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware. :star:85
* [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) - A golang implementation of a console-based trading bot for cryptocurrency exchanges. :star:221
* [govkbot](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library. :star:24
* [hanu](https://github.com/sbstjn/hanu) - Framework for writing Slack bots. :star:109
* [Kelp](https://github.com/stellar/kelp) - official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies. :star:162
* [margelet](https://github.com/zhulik/margelet) - Framework for building Telegram bots. :star:56
* [micha](https://github.com/onrik/micha) - Go Library for Telegram bot api. :star:10
* [slacker](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots. :star:310
* [slackscot](https://github.com/alexandre-normand/slackscot) - Another framework for building Slack bots. :star:10
* [tbot](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http. :star:219
* [telebot](https://github.com/tucnak/telebot) - Telegram bot framework written in Go. :star:947
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client. :star:1629
* [Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging. :star:167

## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [argparse](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module. :star:108
* [argv](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax. :star:17
* [cli](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags. :star:478
* [cli](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go. :star:57
* [cli-init](https://github.com/tcnksm/gcli) - The easy way to start building Golang command line applications. :star:869
* [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command. :star:165
* [cmdr](https://github.com/hedzr/cmdr) - A POSIX/GNU style, getopt-like command-line UI Go library. :star:14
* [cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions. :star:13342
* [commandeer](https://github.com/jaffee/commandeer) - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags. :star:92
* [complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion. :star:618
* [docopt.go](https://github.com/docopt/docopt.go) - Command-line arguments parser that will make you smile. :star:1175
* [env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs. :star:42
* [flag](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go supporting subcommand. :star:100
* [flaggy](https://github.com/integrii/flaggy) - A robust and idiomatic flags package with excellent subcommand support. :star:452
* [flagvar](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package. :star:31
* [go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go. :star:659
* [go-commander](https://github.com/yitsushi/go-commander) - Go library to simplify CLI workflow. :star:15
* [go-flags](https://github.com/jessevdk/go-flags) - go command line option parser. :star:1508
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) - Go option parser inspired on the flexibility of Perl’s GetOpt::Long. :star:8
* [gocmd](https://github.com/devfacet/gocmd) - Go library for building command line applications. :star:33
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - cli application framework with auto configuration and dependency injection. :star:87
* [job](https://github.com/liujianping/job) - JOB, make your short-term command as a long-term job. :star:50
* [kingpin](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands. :star:2533
* [liner](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces. :star:587
* [mitchellh/cli](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces. :star:1001
* [mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation. :star:624
* [ops](https://github.com/nanovms/ops) - Unikernel Builder/Orchestrator. :star:263
* [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags. :star:750
* [readline](https://github.com/chzyer/readline) - Pure golang implementation that provides most features in GNU-Readline under MIT license. :star:1371
* [sand](https://github.com/Zaba505/sand) - Simple API for creating interpreters and so much more. :star:5
* [sflags](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries. :star:90
* [strumt](https://github.com/antham/strumt) - Library to create prompt chain. :star:27
* [ts](https://github.com/liujianping/ts) - Timestamp convert & compare tool. :star:4
* [ukautz/clif](https://github.com/ukautz/clif) - Small command line interface framework. :star:97
* [urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli). :star:11384
* [wlog](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency. :star:35
* [wmenu](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompts users to make choices. :star:85

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [asciigraph](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies. :star:1145
* [aurora](https://github.com/logrusorgru/aurora) - ANSI terminal colors that supports fmt.Printf/Sprintf. :star:635
* [cfmt](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes. :star:67
* [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output. :star:305
* [color](https://github.com/fatih/color) - Versatile package for colored terminal output. :star:3020
* [colourize](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals. :star:16
* [ctc](https://github.com/wzshiming/ctc) - The non-invasive cross-platform terminal color library does not need to modify the Print method. :star:10
* [go-ataman](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals. :star:8
* [go-colorable](https://github.com/mattn/go-colorable) - Colorable writer for windows. :star:375
* [go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals. :star:196
* [go-isatty](https://github.com/mattn/go-isatty) - isatty for golang. :star:345
* [go-prompt](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit). :star:2337
* [gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces. :star:5385
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text. :star:307
* [gookit/color](https://github.com/gookit/color) - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows. :star:202
* [mpb](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications. :star:698
* [progressbar](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS. :star:576
* [simpletable](https://github.com/alexeyco/simpletable) - Simple tables in terminal with Go. :star:166
* [tabby](https://github.com/cheynewallace/tabby) - A tiny library for super simple Golang tables. :star:248
* [tabular](https://github.com/InVisionApp/tabular) - Print ASCII tables from command line utilities without the need to pass large sets of data to the API. :star:29
* [termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces. :star:3488
* [termdash](https://github.com/mum4k/termdash) - Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui). :star:809
* [termtables](https://github.com/apcera/termtables) - Go port of the Ruby library [terminal-tables](https://github.com/tj/terminal-table) for simple ASCII table generation as well as providing markdown and HTML output. :star:215
* [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib). :star:8932
* [uilive](https://github.com/gosuri/uilive) - Library for updating terminal output in realtime. :star:832
* [uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications. :star:1543
* [uitable](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data. :star:504

## Configuration

*Libraries for configuration parsing.*

* [config](https://github.com/JeremyLoy/config) - Cloud native application configuration. Bind ENV to structs in only two lines. :star:190
* [config](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing. :star:210
* [configure](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables. :star:48
* [confita](https://github.com/heetch/confita) - Load configuration in cascade from multiple backends into a struct. :star:238
* [conflate](https://github.com/the4thamigo-uk/conflate) - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema. :star:8
* [env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults). :star:872
* [envcfg](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs. :star:89
* [envconf](https://github.com/ian-kent/envconf) - Configuration from environment. :star:7
* [envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables. :star:145
* [envh](https://github.com/antham/envh) - Helpers to manage environment variables. :star:92
* [gcfg](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections. :star:116
* [go-up](https://github.com/ufoscout/go-up) - A simple configuration library with recursive placeholders resolution and no magic. :star:24
* [goConfig](https://github.com/crgimenes/goConfig) - Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file. :star:110
* [godotenv](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`). :star:2128
* [gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy. :star:57
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization. :star:32
* [gookit/config](https://github.com/gookit/config) - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge. :star:84
* [harvester](https://github.com/beatlabs/harvester) - Harvester, a easy to use static and dynamic configuration package supportig seeding, env vars and Consul integration. :star:40
* [hjson](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments. :star:172
* [ingo](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file. :star:24
* [ini](https://github.com/go-ini/ini) - Go package to read and write INI files. :star:1597
* [joshbetz/config](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP. :star:192
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - Go library for managing configuration data from environment variables. :star:2409
* [koanf](https://github.com/knadh/koanf) - Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line. :star:85
* [konfig](https://github.com/lalamove/konfig) - Composable, observable and performant config handling for Go for the distributed processing era. :star:514
* [mini](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files. :star:19
* [sprbox](https://github.com/oblq/sprbox) - Build-environment aware toolbox factory and agnostic config parser (YAML, TOML, JSON and Environment vars). :star:3
* [store](https://github.com/tucnak/store) - Lightweight configuration manager for Go. :star:241
* [viper](https://github.com/spf13/viper) - Go configuration with fangs. :star:9341
* [xdg](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html). :star:37

## Continuous Integration

*Tools for help with continuous integration.*

* [drone](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go. :star:19051
* [duci](https://github.com/duck8823/duci) - A simple ci server no needs domain specific languages. :star:44
* [gomason](https://github.com/nikogura/gomason) - Test, Build, Sign, and Publish your go binaries from a clean workspace. :star:33
* [goveralls](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system. :star:580
* [overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls. :star:98
* [roveralls](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool. :star:12

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* [gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor. :star:423
* [go-libsass](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project. :star:130

## Data Structures

*Generic datastructures and algorithms in Go.*

* [algorithms](https://github.com/shady831213/algorithms) - Algorithms and data structures.CLRS study. :star:241
* [binpacker](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream. :star:125
* [bit](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions. :star:54
* [bitset](https://github.com/willf/bitset) - Go package implementing bitsets. :star:481
* [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go. :star:128
* [bloom](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation. :star:39
* [boomfilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams. :star:1161
* [concurrent-writer](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`. :star:24
* [conjungo](https://github.com/InVisionApp/conjungo) - A small, powerful and flexible merge library. :star:78
* [count-min-log](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory). :star:43
* [crunch](https://github.com/superwhiskers/crunch) - Go package implementing buffers for handling various datatypes easily. :star:19
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. :star:515
* [deque](https://github.com/edwingeng/deque) - A highly optimized double-ended queue. :star:7
* [deque](https://github.com/gammazero/deque) - Fast ring-buffer deque (double-ended queue). :star:65
* [dict](https://github.com/srfrog/dict) - Python-like dictionaries (dict) for Go. :star:9
* [encoding](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go. :star:94
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree. :star:89
* [go-datastructures](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures. :star:5129
* [go-ef](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding. :star:11
* [go-geoindex](https://github.com/hailocab/go-geoindex) - In-memory geo index. :star:312
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) - Fast in-memory key:value store/cache library. Pointer caches. :star:35
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding. :star:100
* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) - Concurrent FIFO queue. :star:26
* [gods](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc. :star:6403
* [golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go. :star:1171
* [goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go. :star:16
* [goskiplist](https://github.com/ryszard/goskiplist) - Skip list implementation in Go. :star:195
* [gota](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go. :star:880
* [hide](https://github.com/emvi/hide) - ID type with marshalling to/from hash to prevent sending IDs to clients. :star:7
* [hilbert](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves. :star:183
* [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction. :star:661
* [levenshtein](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. :star:32
* [levenshtein](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go. :star:55
* [mafsa](https://github.com/smartystreets/mafsa) - MA-FSA implementation with Minimal Perfect Hashing. :star:273
* [merkletree](https://github.com/cbergoon/merkletree) - Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures. :star:144
* [mspm](https://github.com/BlackRabbitt/mspm) - Multi-String Pattern Matching Algorithm for information retrieval. :star:7
* [null](https://github.com/emvi/null) - Nullable Go types that can be marshalled/unmarshalled to/from JSON. :star:5
* [parsefields](https://github.com/MonaxGT/parsefields) - Tools for parse JSON-like logs for collecting unique fields and events. :star:3
* [pipeline](https://github.com/hyfather/pipeline) - An implementation of pipelines with fan-in and fan-out. :star:15
* [ptrie](https://github.com/viant/ptrie) - An implementation of prefix tree.
* [ring](https://github.com/TheTannerRyan/ring) - Go implementation of a high performance, thread safe bloom filter. :star:88
* [roaring](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets. :star:663
* [set](https://github.com/StudioSol/set) - Simple set data structure implementation in Go using LinkedHashMap. :star:6
* [skiplist](https://github.com/MauriceGit/skiplist) - Very fast Go Skiplist implementation. :star:101
* [skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go. :star:64
* [timedmap](https://github.com/zekroTJA/timedmap) - Map with expiring key-value pairs. :star:1
* [treap](https://github.com/perdata/treap) - Persistent, fast ordered map using tree heaps. :star:7
* [trie](https://github.com/derekparker/trie) - Trie implementation in Go. :star:423
* [ttlcache](https://github.com/diegobernardes/ttlcache) - In-memory LRU string-interface{} map with expiration for golang. :star:97
* [typ](https://github.com/gurukami/typ) - Null Types, Safe primitive type conversion and fetching value from complex structures. :star:9
* [willf/bloom](https://github.com/willf/bloom) - Go package implementing Bloom filters. :star:668

## Database

*Databases implemented in Go.*

* [badger](https://github.com/dgraph-io/badger) - Fast key-value store in Go. :star:6284
* [bcache](https://github.com/iwanbk/bcache) - Eventually consistent distributed in-memory  cache Go library. :star:29
* [BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data. :star:2458
* [bolt](https://github.com/boltdb/bolt) - Low-level key/value database for Go. :star:9986
* [buntdb](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support. :star:2438
* [cache](https://github.com/akyoto/cache) - In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage. :star:16
* [cache2go](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts. :star:1050
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - BigCache with clustering support and individual item expiration. :star:30
* [cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore. :star:16784
* [couchcache](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server. :star:40
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - CovenantSQL is a SQL database on blockchain. :star:876
* [dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database. :star:10434
* [diskv](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store. :star:752
* [eliasdb](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language. :star:532
* [fastcache](https://github.com/VictoriaMetrics/fastcache) - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead. :star:489
* [GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC. :star:898
* [go-cache](https://github.com/pmylund/go-cache) - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications. :star:2907
* [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go. :star:3172
* [gorocksdb](https://github.com/kapitan-k/gorocksdb) - Gorocksdb is a wrapper for [RocksDB](https://rocksdb.org) written in Go. :star:8
* [groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. :star:7663
* [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics. :star:17120
* [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB. :star:3078
* [levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB. :star:364
* [moss](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go. :star:717
* [nutsdb](https://github.com/xujiajun/nutsdb) - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set. :star:891
* [piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures. :star:171
* [prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database. :star:25594
* [pudge](https://github.com/recoilme/pudge) - Fast and simple  key/value store written using Go's standard library. :star:218
* [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite. :star:4699
* [Scribble](https://github.com/nanobox-io/golang-scribble) - Tiny flat file JSON store. :star:60
* [slowpoke](https://github.com/recoilme/slowpoke) - Key-value store with persistence. :star:86
* [tempdb](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items. :star:13
* [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1. :star:20092
* [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang. :star:2366
* [Vasto](https://github.com/chrislusf/vasto) - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption. :star:148
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL. :star:1017

*Database schema migration.*

* [avro](https://github.com/khezen/avro) - Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes. :star:6
* [darwin](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go. :star:83
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library. :star:20
* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) - A Go package to help write migrations with go-pg/pg. :star:23
* [gondolier](https://github.com/emvi/gondolier) - Database migration library using struct decorators. :star:26
* [goose](https://github.com/steinbacher/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. :star:119
* [gormigrate](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM. :star:333
* [migrate](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library. :star:2735
* [migrator](https://github.com/lopezator/migrator) - Dead simple Go database migration library. :star:31
* [pravasan](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc. :star:24
* [soda](https://github.com/gobuffalo/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. :star:678
* [sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata. :star:1411

*Database tools.*

* [chproxy](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database. :star:306
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - Collects small insterts and sends big requests to ClickHouse servers. :star:138
* [datagen](https://github.com/codingconcepts/datagen) - A fast data generator that's multi-table aware and supports multi-row DML. :star:8
* [dbbench](https://github.com/sj14/dbbench) - Database benchmarking tool with support for several databases and scripts. :star:30
* [go-mysql](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication. :star:1892
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically. :star:2402
* [kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang. :star:4610
* [myreplication](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Supports statement and row based replication. :star:141
* [octillery](https://github.com/knocknote/octillery) - Go package for sharding databases ( Supports every ORM or raw SQL ). :star:54
* [orchestrator](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer. :star:3033
* [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser. :star:5989
* [prep](https://github.com/hexdigest/prep) - Use prepared SQL statements without changing your code. :star:24
* [pREST](https://github.com/nuveo/prest) - Serve a RESTful API from any PostgreSQL database. :star:2089
* [rwdb](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup. :star:10
* [vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. :star:8453

*SQL query builder, libraries for building and using SQL.*

* [Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease. :star:439
* [gendry](https://github.com/didi/gendry) - Non-invasive SQL builder and powerful data binder. :star:759
* [godbal](https://github.com/xujiajun/godbal) - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily. :star:50
* [goqu](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library. :star:637
* [igor](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax. :star:78
* [ormlite](https://github.com/pupizoid/ormlite) - Lightweight package containing some ORM-like features and helpers for sqlite databases.
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities. :star:435
* [scaneo](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs. :star:149
* [sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance. :star:177
* [Squalus](https://gitlab.com/qosenergy/squalus) - Thin layer over the Go SQL package that makes it easier to perform queries.
* [Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries. :star:2322
* [xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server. :star:2187

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [avatica](https://github.com/apache/calcite-avatica-go) - Apache Avatica/Phoenix SQL driver for database/sql. :star:35
    * [bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go. :star:12
    * [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go. :star:104
    * [go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql. :star:91
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go. :star:1023
    * [go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql. :star:406
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go. :star:8114
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql. :star:3428
    * [gofreetds](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org). :star:90
    * [goracle](https://github.com/go-goracle/goracle) - Oracle driver for Go, using the ODPI-C driver. :star:239
    * [pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql. :star:1961
    * [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql. :star:5190

* NoSQL Databases
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language. :star:305
    * [arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB. :star:65
    * [asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go. :star:4
    * [dynago](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB. :star:64
    * [forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB. :star:29
    * [go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go. :star:292
    * [go-couchdb](https://github.com/fjl/go-couchdb) - Yet another CouchDB HTTP API wrapper for Go. :star:51
    * [go-pilosa](https://github.com/pilosa/go-pilosa) - Go client library for Pilosa. :star:31
    * [go-rejson](https://github.com/nitishm/go-rejson) - Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease. :star:90
    * [gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK. :star:291
    * [gocql](http://gocql.github.io) - Go language driver for Apache Cassandra.
    * [godis](https://github.com/piaohao/godis) - redis client implement by golang, inspired by jedis. :star:60
    * [godscache](https://github.com/defcronyke/godscache) - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached. :star:6
    * [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language. :star:1095
    * [gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB. :star:1461
    * [goriak](https://github.com/zegl/goriak) - Go language driver for Riak KV. :star:24
    * [mgo](https://github.com/globalsign/mgo) - (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms. :star:1645
    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language. :star:3114
    * [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang. :star:24
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang. :star:72
    * [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang. :star:357
    * [redeo](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services. :star:259
    * [redigo](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database. :star:6294
    * [redis](https://github.com/go-redis/redis) - Redis client for Golang. :star:6513
    * [xredis](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client. :star:9

* Search and Analytic Databases.
    * [bleve](https://github.com/blevesearch/bleve) - Modern text indexing library for go. :star:5846
    * [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go. :star:4147
    * [elasticsql](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go. :star:397
    * [elastigo](https://github.com/mattbaird/elastigo) - Elasticsearch client library. :star:951
    * [go-elasticsearch](https://github.com/elastic/go-elasticsearch) - Official Elasticsearch client for Go. :star:1583
    * [goes](https://github.com/OwnLocal/goes) - Library to interact with Elasticsearch. :star:24
    * [riot](https://github.com/go-ego/riot) - Go Open Source, Distributed, Simple and efficient Search Engine. :star:4700
    * [skizze](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage. :star:68

* Multiple Backends.
    * [cachego](https://github.com/fabiorphp/cachego) - Golang Cache component for multiple drivers. :star:110
    * [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends. :star:12693
    * [dsc](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files. :star:14
    * [gokv](https://github.com/philippgille/gokv) - Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more). :star:85

## Date and Time

*Libraries for working with dates and times.*

* [carbon](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library. :star:339
* [date](https://github.com/rickb777/date) - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day. :star:28
* [dateparse](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance. :star:896
* [durafmt](https://github.com/hako/durafmt) - Time duration formatting library for Go. :star:241
* [feiertage](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving... :star:22
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang). :star:64
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) - Calculate the sunrise and sunset times for a given location. :star:13
* [goweek](https://github.com/grsmv/goweek) - Library for working with week entity in golang. :star:18
* [iso8601](https://github.com/relvacode/iso8601) - Efficiently parse ISO8601 date-times without regex. :star:68
* [kair](https://github.com/GuilhermeCaruso/kair) - Date and Time - Golang Formatting Library. :star:11
* [now](https://github.com/jinzhu/now) - Now is a time toolkit for golang. :star:2187
* [NullTime](https://github.com/kirillDanshin/nulltime) - Nullable `time.Time`. :star:9
* [strftime](https://github.com/awoodbeck/strftime) - C99-compatible strftime formatter. :star:5
* [timespan](https://github.com/SaidinWoT/timespan) - For interacting with intervals of time, defined as a start time and a duration. :star:60
* [timeutil](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package. :star:169
* [tuesday](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function. :star:7

## Distributed Systems

*Packages that help with building Distributed Systems.*

* [celeriac](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go. :star:52
* [consistent](https://github.com/buraksezer/consistent) - Consistent hashing with bounded loads. :star:190
* [dht](https://github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation. :star:128
* [digota](https://github.com/digota/digota) - grpc ecommerce microservice. :star:299
* [dot](https://github.com/dotchain/dot/) - distributed sync using operational transformation/OT. :star:23
* [doublejump](https://github.com/edwingeng/doublejump) - A revamped Google's jump consistent hash. :star:40
* [dragonboat](https://github.com/lni/dragonboat) - A feature complete and high performance multi-group Raft library in Go. :star:2539
* [drmaa](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard. :star:25
* [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed distributed locking implementation.
* [dynatomic](https://github.com/tylfin/dynatomic) - A library for using DynamoDB as an atomic counter. :star:8
* [emitter-io](https://github.com/emitter-io/emitter) - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love. :star:1935
* [flowgraph](https://github.com/vectaport/flowgraph) - flow-based programming package. :star:18
* [gleam](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed. :star:2100
* [glow](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go. :star:2527
* [go-health](https://github.com/InVisionApp/go-health) - Library for enabling asynchronous dependency health checks in your service. :star:478
* [go-jump](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function. :star:254
* [go-kit](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc. :star:14452
* [gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load. :star:553
* [grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC. :star:9112
* [hprose](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now. :star:1005
* [jaeger](https://github.com/jaegertracing/jaeger) - A distributed tracing system. :star:8671
* [jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0. :star:113
* [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation. :star:102
* [KrakenD](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway framework with middlewares. :star:1753
* [micro](https://github.com/micro/micro) - Pluggable microservice toolkit and distributed systems platform. :star:6599
* [NATS](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems. :star:6346
* [outboxer](https://github.com/italolelis/outboxer) - Outboxer is a go library that implements the outbox pattern. :star:5
* [pglock](https://cirello.io/pglock) - PostgreSQL-backed distributed locking implementation.
* [raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp. :star:2843
* [raft](https://github.com/coreos/etcd/tree/master/raft) - Go implementation of the Raft consensus protocol, by CoreOS. :star:26542
* [redis-lock](https://github.com/bsm/redis-lock) - Simplified distributed locking implementation using Redis. :star:147
* [resgate](https://resgate.io/) - Realtime API Gateway for building REST, real time, and RPC APIs, where all clients are synchronized seamlessly.
* [ringpop-go](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications. :star:574
* [rpcx](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo. :star:3802
* [sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)). :star:300
* [tendermint](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols. :star:3138
* [torrent](https://github.com/anacrolix/torrent) - BitTorrent client package. :star:2844

## Email

*Libraries and tools that implement email creation and sending.*

* [chasquid](https://blitiri.com.ar/p/chasquid) - SMTP server written in Go.
* [douceur](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails. :star:162
* [email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go. :star:1094
* [go-dkim](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email. :star:46
* [go-imap](https://github.com/emersion/go-imap) - IMAP library for clients and servers. :star:733
* [go-message](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages. :star:112
* [go-premailer](https://github.com/vanng822/go-premailer) - Inline styling for HTML mail in Go. :star:35
* [Gomail](https://github.com/go-gomail/gomail/) - Gomail is a very simple and powerful package to send emails. :star:2359
* [Hectane](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API. :star:168
* [hermes](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails. :star:1617
* [MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface. :star:5170
* [SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email. :star:521
* [smtp](https://github.com/mailhog/smtp) - SMTP server protocol state machine. :star:51

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* [agora](https://github.com/PuerkitoBio/agora) - Dynamically typed, embeddable programming language in Go. :star:321
* [anko](https://github.com/mattn/anko) - Scriptable interpreter written in Go. :star:922
* [binder](https://github.com/alexeyco/binder) - Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua). :star:29
* [expr](https://github.com/antonmedv/expr) - an engine that can evaluate expressions. :star:703
* [gentee](https://github.com/gentee/gentee) - Embeddable scripting programming language. :star:27
* [gisp](https://github.com/jcla1/gisp) - Simple LISP in Go. :star:429
* [go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go. :star:653
* [go-lua](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go. :star:1671
* [go-php](https://github.com/deuill/go-php) - PHP bindings for Go. :star:682
* [go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API. :star:906
* [golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API. :star:441
* [gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go. :star:2963
* [gval](https://github.com/PaesslerAG/gval) - A highly customizable expression language written in Go. :star:136
* [ngaro](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro. :star:19
* [otto](https://github.com/robertkrimen/otto) - JavaScript interpreter written in Go. :star:4729
* [purl](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go. :star:27
* [tengo](https://github.com/d5/tengo) - Bytecode compiled script language for Go. :star:1303

## Error Handling

*Libraries for handling errors.*

* [errlog](https://github.com/snwfdhmp/errlog) - Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place. :star:152
* [errors](https://github.com/pkg/errors) - Package that provides simple error handling primitives. :star:4900
* [errorx](https://github.com/joomcode/errorx) - A feature rich error package with stack traces, composition of errors and more. :star:556
* [go-multierror](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error. :star:729
* [tracerr](https://github.com/ztrue/tracerr) - Golang errors with stack trace and source fragments. :star:496
* [werr](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called. :star:11

## Files

*Libraries for handling files and file systems.*

* [afero](https://github.com/spf13/afero) - FileSystem Abstraction System for Go. :star:2234
* [checksum](https://github.com/codingsince1985/checksum) - Compute message digest, like MD5 and SHA256, for large files. :star:6
* [flop](https://github.com/homedepot/flop) - File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html). :star:9
* [go-csv-tag](https://github.com/artonge/go-csv-tag) - Load csv file using tag. :star:48
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - Copy files for humans. :star:11
* [go-exiftool](https://github.com/barasher/go-exiftool) - Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...). :star:3
* [go-gtfs](https://github.com/artonge/go-gtfs) - Load gtfs files in go. :star:15
* [notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal. :star:495
* [opc](https://github.com/qmuntal/opc) - Load Open Packaging Conventions (OPC) files for Go. :star:57
* [pdfcpu](https://github.com/hhrutter/pdfcpu) - PDF processor. :star:947
* [skywalker](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease. :star:48
* [stl](https://gitlab.com/russoj88/stl) - Modules to read and write STL (stereolithography) files.  Concurrent algorithm for reading.
* [tarfs](https://github.com/posener/tarfs) - Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files. :star:35
* [vfs](https://github.com/C2FO/vfs) - A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS. :star:22

## Financial

*Packages for accounting and finance.*

* [accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang. :star:488
* [currency](https://github.com/bnkamalesh/currency) - High performant & accurate currency computation package. :star:9
* [decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers. :star:1600
* [go-finance](https://github.com/FlashBoys/go-finance) - Comprehensive financial markets data in Go. :star:536
* [go-finance](https://github.com/alpeb/go-finance) - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations. :star:42
* [go-money](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern. :star:620
* [ofxgo](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client). :star:62
* [orderbook](https://github.com/i25959341/orderbook) - Matching Engine for Limit Order Book in Golang. :star:69
* [techan](https://github.com/sdcoffey/techan) - Technical analysis library with advanced market analysis and trading strategies. :star:158
* [transaction](https://github.com/claygod/transaction) - Embedded transactional database of accounts, running in multithreaded mode. :star:55
* [vat](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates. :star:60

## Forms

*Libraries for working with forms.*

* [bind](https://github.com/robfig/bind) - Bind form data to any Go values. :star:23
* [binding](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct. :star:754
* [conform](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags. :star:173
* [form](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. :star:349
* [formam](https://github.com/monoculum/formam) - decode form's values into a struct. :star:127
* [forms](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. :star:105
* [gorilla/csrf](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services. :star:435
* [nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go. :star:971

## Functional

*Packages to support functional programming in Go.*

* [fpGo](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang. :star:107
* [fuego](https://github.com/seborama/fuego) - Functional Experiment in Go. :star:39
* [go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities. :star:1068

## Game Development

*Awesome game development libraries.*

* [Azul3D](https://github.com/azul3d/engine) - 3D game engine written in Go. :star:426
* [Ebiten](https://github.com/hajimehoshi/ebiten) - dead simple 2D game library in Go. :star:1852
* [engo](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm. :star:1081
* [g3n](https://github.com/g3n/engine) - Go 3D Game Engine. :star:753
* [GarageEngine](https://github.com/vova616/GarageEngine) - 2d game engine written in Go working on OpenGL. :star:313
* [glop](https://github.com/runningwild/glop) - Glop (Game Library Of Power) is a fairly simple cross-platform game library. :star:77
* [go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm. :star:326
* [go-collada](https://github.com/GlenKelley/go-collada) - Go package for working with the Collada file format. :star:12
* [go-sdl2](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/). :star:1159
* [go3d](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go. :star:164
* [gonet](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang. :star:1049
* [goworld](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping. :star:1195
* [Leaf](https://github.com/name5566/leaf) - Lightweight game server framework. :star:3064
* [nano](https://github.com/lonng/nano) - Lightweight, facility, high performance golang based game server framework. :star:997
* [Oak](https://github.com/oakmound/oak) - Pure Go game engine. :star:627
* [Pitaya](https://github.com/topfreegames/pitaya) - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. :star:300
* [Pixel](https://github.com/faiface/pixel) - Hand-crafted 2D game library in Go. :star:2437
* [raylib-go](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming. :star:382
* [termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox. :star:1023

## Generation and Generics

*Tools to enhance the language with features like generics via code generation.*

* [efaceconv](https://github.com/t0pep0/efaceconv) - Code generation tool for high performance conversion from interface{} to immutable type without allocations. :star:43
* [gen](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality. :star:1036
* [generis](https://github.com/senselogic/GENERIS) - Code generation tool providing generics, free-form macros, conditional compilation and HTML templating. :star:18
* [go-enum](https://github.com/abice/go-enum) - Code generation for enums from code comments. :star:86
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go. :star:1797
* [goderive](https://github.com/awalterschulze/goderive) - Derives functions from input types. :star:745
* [gotype](https://github.com/wzshiming/gotype) - Golang source code parsing, usage like reflect package. :star:22
* [GoWrap](https://github.com/hexdigest/gowrap) - Generate decorators for Go interfaces using simple templates. :star:263
* [interfaces](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions. :star:188
* [jennifer](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates. :star:1275
* [pkgreflect](https://github.com/ungerik/pkgreflect) - Go preprocessor for package scoped reflection. :star:87

## Geographic

*Geographic tools and servers*

* [geocache](https://github.com/melihmucuk/geocache) - In-memory cache that is suitable for geolocation based applications. :star:111
* [geoserver](https://github.com/hishamkaram/geoserver) - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API. :star:25
* [gismanager](https://github.com/hishamkaram/gismanager) - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver. :star:19
* [osm](https://github.com/paulmach/osm) - Library for reading, writing and working with OpenStreetMap data and APIs. :star:68
* [pbf](https://github.com/maguro/pbf) - OpenStreetMap PBF golang encoder/decoder. :star:16
* [S2 geometry](https://github.com/golang/geo) - S2 geometry library in Go. :star:886
* [Tile38](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing. :star:6333

## Go Compilers

*Tools for compiling Go to other languages.*

* [c4go](https://github.com/Konstantin8105/c4go) - Transpile C code to Go code. :star:156
* [f4go](https://github.com/Konstantin8105/f4go) - Transpile FORTRAN 77 code to Go code. :star:11
* [gopherjs](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript. :star:8544
* [llgo](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go. :star:990
* [tardisgo](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler. :star:393

## Goroutines

*Tools for managing and working with Goroutines.*

* [ants](https://github.com/panjf2000/ants) - A high-performance goroutine pool for golang. :star:1888
* [artifex](https://github.com/borderstech/artifex) - Simple in-memory job queue for Golang using worker-based dispatching. :star:12
* [async](https://github.com/studiosol/async) - A safe way to execute functions asynchronously, recovering them in case of panic. :star:23
* [breaker](https://github.com/kamilsk/breaker) - Flexible mechanism to make execution flow interruptible. :star:34
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - CyclicBarrier for golang. :star:36
* [go-floc](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease. :star:167
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order. :star:104
* [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) - Manage a pool of goroutines using this lightweight library with a simple API. :star:5
* [go-trylock](https://github.com/subchen/go-trylock) - TryLock support on read-write lock for Golang. :star:4
* [gollback](https://github.com/vardius/gollback) - asynchronous simple function utilities, for managing execution of closures and callbacks. :star:27
* [GoSlaves](https://github.com/themester/GoSlaves) - Simple and Asynchronous Goroutine pool library. :star:75
* [goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker. :star:2251
* [gpool](https://github.com/Sherifabdlnaby/gpool) - manages a resizeable pool of context-aware goroutines to bound concurrency. :star:56
* [grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool. :star:500
* [Hunch](https://github.com/AaronJan/Hunch) - Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive. :star:13
* [oversight](https://cirello.io/oversight) - Oversight is a complete implementation of the Erlang supervision trees.
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) - Run functions in parallel. :star:25
* [pool](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation. :star:482
* [queue](https://github.com/AnikHasibul/queue) - Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more. :star:2
* [routine](https://github.com/x-mod/routine) - go routine control with context, support: Main, Go, Pool and some useful Executors. :star:3
* [semaphore](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context. :star:75
* [semaphore](https://github.com/marusama/semaphore) - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations). :star:72
* [stl](https://github.com/ssgreg/stl) - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism. :star:8
* [threadpool](https://github.com/shettyh/threadpool) - Golang threadpool implementation. :star:19
* [tunny](https://github.com/Jeffail/tunny) - Goroutine pool for golang. :star:1345
* [worker-pool](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool. :star:45
* [workerpool](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued. :star:138

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* [app](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. :star:2954
* [fyne](https://github.com/fyne-io/fyne) - Cross platform native GUIs designed for Go, rendered using EFL. Supports: Linux, macOS, Windows. :star:6283
* [go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron). :star:2666
* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK.
* [go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform. :star:1449
* [gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3. :star:772
* [gowd](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform. :star:210
* [qt](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi). :star:6059
* [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform. :star:6950
* [Wails](https://wails.app) - Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer.
* [walk](https://github.com/lxn/walk) - Windows application library kit for Go. :star:3693
* [webview](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). :star:4661

*Interaction*

* [go-appindicator](https://github.com/dawidd6/go-appindicator) - Go bindings for libappindicator3 C library. :star:1
* [gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go. :star:494
* [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) - OSX library to notify about any (pluggable) activity on your machine. :star:1
* [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) - OSX Sleep/Wake notifications in golang.
* [robotgo](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other. :star:4430
* [systray](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area. :star:785
* [trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar. :star:160


## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## Images

*Libraries for manipulating images.*

* [bild](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go. :star:2545
* [bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips. :star:794
* [cameron](https://github.com/aofei/cameron) - An avatar generator for Go. :star:31
* [darkroom](https://github.com/gojek/darkroom) - An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency. :star:34
* [geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string. :star:1012
* [gg](https://github.com/fogleman/gg) - 2D rendering in pure Go. :star:1914
* [gift](https://github.com/disintegration/gift) - Package of image processing filters. :star:1209
* [gltf](https://github.com/qmuntal/gltf) - Efficient and robust glTF 2.0 reader, writer and validator. :star:37
* [go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library. :star:85
* [go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library. :star:50
* [go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go. :star:286
* [go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV. :star:1093
* [go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go. :star:24
* [gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+. :star:2458
* [goimagehash](https://github.com/corona10/goimagehash) - Go Perceptual image hashing package. :star:215
* [goimghdr](https://github.com/corona10/goimghdr) - The imghdr module determines the type of image contained in a file for Go. :star:26
* [govatar](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars. :star:310
* [image2ascii](https://github.com/qeesung/image2ascii) - Convert image to ASCII. :star:290
* [imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API. :star:976
* [imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing. :star:2592
* [imaging](https://github.com/disintegration/imaging) - Simple Go image processing package. :star:2526
* [img](https://github.com/hawx/img) - Selection of image manipulation tools. :star:129
* [ln](https://github.com/fogleman/ln) - 3D line art rendering in Go. :star:2462
* [mergi](https://github.com/noelyahan/mergi) - Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate). :star:70
* [mort](https://github.com/aldor007/mort) - Storage and image processing server written in Go. :star:365
* [mpo](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos. :star:6
* [picfit](https://github.com/thoas/picfit) - An image resizing server written in Go. :star:1068
* [pt](https://github.com/fogleman/pt) - Path tracing engine written in Go. :star:1772
* [resize](https://github.com/nfnt/resize) - Image resizing for Go with common interpolation methods. :star:2125
* [rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD. :star:189
* [smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes. :star:1259
* [steganography](https://github.com/auyer/steganography) - Pure Go Library for LSB steganography. :star:25
* [stegify](https://github.com/DimitarPetrov/stegify) - Go tool for LSB steganography, capable of hiding any file within an image. :star:503
* [svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation. :star:1333
* [tga](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder. :star:23

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* [connectordb](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT. :star:168
* [devices](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io. :star:225
* [eywa](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices. :star:36
* [flogo](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration. :star:1126
* [gatt](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals. :star:816
* [gobot](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things. :star:5696
* [huego](https://github.com/amimof/huego) - An extensive Philips Hue client library for Go. :star:110
* [iot](https://github.com/vaelen/iot/) - IoT is a simple framework for implementing a Google IoT Core device. :star:35
* [mainflux](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server. :star:589
* [periph](https://periph.io/) - Peripherals I/O to interface with low-level board facilities.
* [sensorbee](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT. :star:180

## Job Scheduler

*Libraries for scheduling jobs.*

* [clockwerk](http://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax. :star:63
* [clockwork](https://github.com/whiteShtef/clockwork) - Simple and intuitive job scheduling library in Go. :star:77
* [go-cron](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. :star:177
* [gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly. :star:632
* [JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in. :star:570
* [jobs](https://github.com/albrow/jobs) - Persistent and flexible background jobs library. :star:451
* [leprechaun](https://github.com/kilgaloon/leprechaun) - Job scheduler that supports webhooks, crons and classic scheduling. :star:37
* [scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy. :star:294

## JSON

*Libraries for working with JSON.*

* [ajson](https://github.com/spyzhov/ajson) - Abstract JSON for golang with JSONPath support. :star:13
* [gjo](https://github.com/skanehira/gjo) - Small utility to create JSON objects. :star:62
* [GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code. :star:4903
* [go-jsonerror](https://github.com/ddymko/go-jsonerror) - Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec. :star:7
* [go-respond](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses. :star:23
* [gojq](https://github.com/elgs/gojq) - JSON query in Golang. :star:140
* [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON. :star:2032
* [JayDiff](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go. :star:40
* [JSON-to-Go](https://mholt.github.io/json-to-go/) - Convert JSON to Go struct.
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference. :star:5
* [jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON. :star:55
* [jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects. :star:92
* [jsonhal](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses. :star:9
* [kazaam](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents. :star:133
* [mp](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON. :star:33

## Logging

*Libraries for generating and working with log files.*

* [distillog](https://github.com/amoghe/distillog) - distilled levelled logging (think of it as stdlib + log levels). :star:19
* [glg](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go. :star:51
* [glo](https://github.com/lajosbencz/glo) - PHP Monolog inspired logging facility with identical severity levels. :star:8
* [glog](https://github.com/golang/glog) - Leveled execution logs for Go. :star:2304
* [go-cronowriter](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog. :star:19
* [go-log](https://github.com/subchen/go-log) - Simple and configurable Logging in Go, with level, formatters and writers. :star:9
* [go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers. :star:23
* [go-log](https://github.com/ian-kent/go-log) - Log4j implementation in Go. :star:34
* [go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers. :star:233
* [gologger](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch. :star:39
* [gomol](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs. :star:15
* [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library. :star:32
* [journald](https://github.com/ssgreg/journald) - Go implementation of systemd Journal's native API for logging. :star:19
* [log](https://github.com/aerogo/log) - An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection). :star:4
* [log](https://github.com/apex/log) - Structured logging package for Go. :star:733
* [log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go. :star:267
* [log](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation. :star:22
* [log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang. :star:82
* [log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go. :star:912
* [logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging. :star:9
* [logex](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib. :star:32
* [logger](https://github.com/azer/logger) - Minimalistic logging library for Go. :star:135
* [logmatic](https://github.com/borderstech/logmatic) - Colorized logger for Golang with dynamic log level configuration. :star:6
* [logo](https://github.com/mbndr/logo) - Golang logger to different configurable writers. :star:5
* [logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go. :star:11954
* [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). :star:26
* [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger. :star:248
* [logxi](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy. :star:334
* [lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser. :star:1444
* [mlog](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. :star:19
* [onelog](https://github.com/francoispqt/onelog) - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenario. Also, it is one of the logger with the lowest allocation. :star:331
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail). :star:110
* [rollingwriter](https://github.com/arthurkiller/rollingWriter) - RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation. :star:97
* [seelog](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting. :star:1360
* [spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging. :star:3312
* [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. :star:43
* [tail](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program. :star:1540
* [xlog](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format. :star:7
* [xlog](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching. :star:128
* [zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go. :star:7455
* [zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger. :star:2219

## Machine Learning

*Libraries for Machine Learning.*

* [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang. :star:630
* [CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. :star:644
* [eaopt](https://github.com/MaxHalford/eaopt) - An evolutionary optimization library. :star:621
* [evoli](https://github.com/khezen/evoli) - Genetic Algorithm and Particle Swarm Optimization library. :star:8
* [fonet](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go. :star:33
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms. :star:21
* [go-deep](https://github.com/patrikeh/go-deep) - A feature-rich neural network library in Go. :star:216
* [go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library. :star:99
* [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang. :star:172
* [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang. :star:57
* [gobrain](https://github.com/goml/gobrain) - Neural Networks written in go. :star:385
* [godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods. :star:24
* [goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go. :star:78
* [GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go. :star:6652
* [golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go. :star:39
* [GoMind](https://github.com/surenderthakran/gomind) - A simplistic Neural Network Library in Go. :star:6
* [goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go. :star:1012
* [goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go. :star:144
* [gorgonia](https://github.com/chewxy/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms. :star:2691
* [gorse](https://github.com/zhenghaoz/gorse) - A High Performance Recommender System Package based on Collaborative Filtering for Go. :star:537
* [goscore](https://github.com/asafschers/goscore) - Go Scoring API for PMML. :star:36
* [gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library. :star:875
* [libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14. :star:63
* [mlgo](https://github.com/NullHypothesis/mlgo) - This project aims to provide minimalistic machine learning algorithms in Go. :star:5
* [neat](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT). :star:55
* [neural-go](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation. :star:61
* [ocrserver](https://github.com/otiai10/ocrserver) - A simple OCR API server, seriously easy to be deployed by Docker and Heroku. :star:225
* [onnx-go](https://github.com/owulveryck/onnx-go) - Go Interface to Open Neural Network Exchange (ONNX). :star:148
* [probab](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go. :star:10
* [regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine. :star:249
* [shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go. :star:124
* [tfgo](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python. :star:1187
* [Varis](https://github.com/Xamber/Varis) - Golang Neural Network. :star:23

## Messaging

*Libraries that implement messaging systems.*

* [APNs2](https://github.com/sideshow/apns2) - HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps. :star:2043
* [Beaver](https://github.com/Clivern/Beaver) - A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps. :star:726
* [Benthos](https://github.com/Jeffail/benthos) - A message streaming bridge between a range of protocols. :star:2011
* [Bus](https://github.com/mustafaturan/bus) - Minimalist message bus implementation for internal communication. :star:114
* [Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go. :star:3688
* [Commander](https://github.com/jeroenrinzema/commander) - A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka. :star:21
* [dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus. :star:358
* [drone-line](https://github.com/appleboy/drone-line) - Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI. :star:60
* [emitter](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins. :star:309
* [event](https://github.com/agoalofalife/event) - Implementation of the pattern observer. :star:27
* [EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility. :star:560
* [gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go. :star:8
* [Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io). :star:318
* [go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec. :star:47
* [go-nsq](https://github.com/nsqio/go-nsq) - the official Go package for NSQ. :star:1458
* [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework. :star:2886
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service. :star:11
* [Gollum](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations. :star:768
* [golongpoll](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple. :star:428
* [goose](https://github.com/ian-kent/goose) - Server Sent Events in Go. :star:36
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster. :star:1837
* [gorush](https://github.com/appleboy/gorush) - Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm). :star:3713
* [guble](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence. :star:138
* [hub](https://github.com/leandro-lugaresi/hub) - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges. :star:25
* [jazz](https://github.com/socifi/jazz) - A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages. :star:6
* [machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing. :star:3372
* [mangos](https://github.com/go-mangos/mangos) - Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability. :star:1534
* [melody](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling. :star:1563
* [Mercure](https://github.com/dunglas/mercure) - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events). :star:1507
* [messagebus](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD. :star:65
* [NATS Go Client](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library. :star:2398
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel. :star:50
* [oplog](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs. :star:94
* [pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go. :star:279
* [rabbus](https://github.com/rafaeljesus/rabbus) - A tiny wrapper over amqp exchanges and queues. :star:62
* [rabtap](https://github.com/jandelgado/rabtap) - RabbitMQ swiss army knife cli app. :star:72
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue. :star:55
* [redisqueue](https://github.com/robinjoseph08/redisqueue) - redisqueue provides a producer and consumer of a queue that uses Redis streams. :star:1
* [rmqconn](https://github.com/sbabiv/rmqconn) - RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed.
* [sarama](https://github.com/Shopify/sarama) - Go library for Apache Kafka. :star:4630
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices. :star:1097
* [zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). :star:774

## Microsoft Office

* [unioffice](https://github.com/unidoc/unioffice) - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents. :star:1718

### Microsoft Excel

*Libraries for working with Microsoft Excel.*

* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files. :star:4474
* [go-excel](https://github.com/szyhf/go-excel) - A simple and light reader to read a relate-db-like excel as a table. :star:46
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files. :star:12
* [xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs. :star:3422
* [xlsx](https://github.com/plandem/xlsx) - Fast and safe way to read/update your existing Microsoft Excel files in Go programs. :star:72

## Miscellaneous

### Dependency Injection

*Libraries for working with dependency injection.*

* [alice](https://github.com/magic003/alice) - Additive dependency injection container for Golang. :star:34
* [dig](https://github.com/uber-go/dig) - A reflection based dependency injection toolkit for Go. :star:911
* [fx](https://github.com/uber-go/fx) - A dependency injection based application framework for Go (built on top of dig). :star:752
* [gocontainer](https://github.com/vardius/gocontainer) - Simple Dependency Injection Container. :star:9
* [inject](https://github.com/defval/inject) - A reflection based dependency injection container with simple interface. :star:27
* [linker](https://github.com/logrange/linker) - A reflection based dependency injection and inversion of control library with components lifecycle support. :star:7
* [wire](https://github.com/Fs02/wire) - Strict Runtime Dependency Injection for Golang. :star:19

### Project Layout

*Unofficial set of patterns for structuring projects.*

* [go-sample](https://github.com/zitryss/go-sample) - A sample layout for Go application projects with the real code. :star:23
* [golang-standards/project-layout](https://github.com/golang-standards/project-layout) - Set of common historical and emerging project layout patterns in the Go ecosystem. :star:9159
* [scaffold](https://github.com/catchplay/scaffold) - Scaffold generates starter Go project layout. Lets you focus on business logic implemeted. :star:24

### Strings

*Libraries for working with strings.*

* [strutil](https://github.com/ozgio/strutil) - String utilities. :star:62
* [xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages. :star:619

*These libraries were placed here because none of the other categories seemed to fit.*

* [anagent](https://github.com/mudler/anagent) - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection. :star:11
* [antch](https://github.com/antchfx/antch) - A fast, powerful and extensible web crawling & scraping framework. :star:140
* [archiver](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives. :star:2488
* [autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields. :star:24
* [avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation. :star:9
* [banner](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications. :star:232
* [base64Captcha](https://github.com/mojocn/base64Captcha) - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha. :star:629
* [battery](https://github.com/distatus/battery) - Cross-platform, normalized battery information library. :star:135
* [bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go. :star:96
* [browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/). :star:30
* [captcha](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation. :star:43
* [conv](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types. :star:341
* [datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter. :star:28
* [ffmt](https://github.com/go-ffmt/ffmt) - Beautify data display for Humans. :star:127
* [ghorg](https://github.com/gabrie30/ghorg) - Clone all repos from a GitHub org into a single directory. :star:30
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang. :star:671
* [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
* [go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang. :star:857
* [go-unarr](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives. :star:68
* [gofakeit](https://github.com/brianvoe/gofakeit) - Random data generator written in go. :star:419
* [gommit](https://github.com/antham/gommit) - Analyze git commit messages to ensure they follow defined patterns. :star:75
* [gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). :star:3931
* [gosh](https://github.com/osamingo/gosh) - Provide Go Statistics Handler, Struct, Measure Method. :star:17
* [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS. :star:1226
* [gotoprom](https://github.com/cabify/gotoprom) - Type-safe metrics builder wrapper library for the official Prometheus client. :star:14
* [gountries](https://github.com/pariz/gountries) - Package that exposes country and subdivision data. :star:210
* [health](https://github.com/dimiro1/health) - Easy to use, extensible health check library. :star:362
* [healthcheck](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services. :star:83
* [hostutils](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list. :star:8
* [indigo](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58. :star:51
* [lk](https://github.com/hyperboloide/lk) - A simple licensing library for golang. :star:121
* [llvm](https://github.com/llir/llvm) - Library for interacting with LLVM IR in pure Go. :star:411
* [metrics](https://github.com/pascaldekloe/metrics) - Library for metrics instrumentation and Prometheus exposition. :star:4
* [morse](https://github.com/alwindoss/morse) - Library to convert to and from morse code. :star:50
* [numa](https://github.com/lrita/numa) - NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code. :star:2
* [pdfgen](https://github.com/hyperboloide/pdfgen) - HTTP service to generate PDF from Json requests. :star:34
* [persian](https://github.com/mavihq/persian) - Some utilities for Persian language in go. :star:32
* [sandid](https://github.com/aofei/sandid) - Every grain of sand on earth has its own ID. :star:12
* [shellwords](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell. :star:7
* [shortid](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs. :star:450
* [stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... :star:121
* [turtle](https://github.com/hackebrot/turtle) - Emojis for Go. :star:76
* [url-shortener](https://github.com/pantrif/url-shortener) - A modern, powerful, and robust URL shortener microservice with mysql support. :star:17
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and output handling. :star:4
* [xdg](https://github.com/rkoesters/xdg) - FreeDesktop.org (xdg) Specs implemented in Go. :star:21
* [xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber. :star:40

## Natural Language Processing

*Libraries for working with human languages.*

* [getlang](https://github.com/rylans/getlang) - Fast natural language detection package. :star:74
* [go-eco](https://github.com/ThePaw/go-eco) - Similarity, dissimilarity and distance matrices; diversity, equitability and inequality measures; species richness estimators; coenocline models. :star:4
* [go-i18n](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text. :star:1147
* [go-mystem](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer. :star:23
* [go-nlp](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work. :star:79
* [go-pinyin](https://github.com/mozillazg/go-pinyin) - CN Hanzi to Hanyu Pinyin converter. :star:523
* [go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm. :star:52
* [go-unidecode](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text. :star:56
* [go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings. :star:30
* [gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm. :star:820
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2. :star:15
* [gotokenizer](https://github.com/xujiajun/gotokenizer) - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation) :star:6
* [gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go. :star:67
* [gse](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other. :star:1071
* [icu](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1. :star:19
* [kagome](https://github.com/ikawaha/kagome) - JP morphological analyzer written in pure Go. :star:416
* [libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. :star:10
* [MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. :star:59
* [nlp](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp. :star:353
* [nlp](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis). :star:216
* [paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm. :star:25
* [petrovich](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case. :star:22
* [porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm. :star:8
* [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer. :star:33
* [prose](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. :star:2045
* [RAKE.go](https://github.com/Obaied/RAKE.go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE). :star:45
* [segment](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)
* [sentences](https://github.com/neurosnap/sentences) - Sentence tokenizer:  converts text into a list of sentences. :star:260
* [shamoji](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go. :star:10
* [snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). :star:24
* [stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers. :star:47
* [textcat](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text. :star:60
* [whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc). :star:350
* [when](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules. :star:927

## Networking

*Libraries for working with various layers of the network.*

* [arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826. :star:196
* [buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy. :star:232
* [canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252). :star:135
* [cidranger](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go. :star:387
* [dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. :star:62
* [dns](https://github.com/miekg/dns) - Go library for working with DNS. :star:3806
* [ether](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames. :star:62
* [ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. :star:185
* [fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http. :star:9388
* [fortio](https://github.com/fortio/fortio) - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC. :star:875
* [ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959). :star:525
* [gmqtt](https://github.com/DrmagicE/gmqtt) - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1. :star:89
* [gNxI](https://github.com/google/gnxi) - A collection of tools for Network Management that use the gNMI and gNOI protocols. :star:100
* [go-getter](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL. :star:725
* [go-stun](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389). :star:334
* [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language. :star:1691
* [golibwireshark](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data. :star:15
* [gopacket](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings. :star:2882
* [gopcap](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap. :star:354
* [goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet. :star:9
* [gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions. :star:438
* [gotcp](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications. :star:417
* [grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads. :star:546
* [graval](https://github.com/koofr/graval) - Experimental FTP server framework. :star:24
* [HTTPLab](https://github.com/gchaincl/httplab) - HTTPLabs let you inspect HTTP requests and forge responses. :star:3408
* [iplib](https://github.com/c-robinson/iplib) - Library for working with IP addresses (net.IP, net.IPNet), inspired by python [ipaddress](https://docs.python.org/3/library/ipaddress.html) and ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)
* [jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices. :star:125
* [kcp-go](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol. :star:2245
* [kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol. :star:10674
* [lhttp](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily. :star:513
* [linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces. :star:44
* [llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response. :star:8
* [mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang. :star:551
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* [NFF-Go](https://github.com/intel-go/nff-go) - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF). :star:665
* [packet](https://github.com/aerogo/packet) - Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed. :star:27
* [peerdiscovery](https://github.com/schollz/peerdiscovery) - Pure Go library for cross-platform local peer discovery using UDP multicast. :star:364
* [portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it. :star:43
* [publicip](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress). :star:18
* [quic-go](https://github.com/lucas-clemente/quic-go) - An implementation of the QUIC protocol in pure Go. :star:2917
* [raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface. :star:303
* [sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt. :star:738
* [ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh). :star:1113
* [sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance. :star:113
* [stun](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol. :star:278
* [tcp_server](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster. :star:284
* [tspool](https://github.com/two/tspool) - A TCP Library use worker pool to improve performance and protect your server. :star:5
* [utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation. :star:149
* [water](https://github.com/songgao/water) - Simple TUN/TAP library. :star:841
* [webrtc](https://github.com/pions/webrtc) - A pure Go implementation of the WebRTC API. :star:2263
* [winrm](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines. :star:212
* [xtcp](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication,graceful shutdown,custom protocol. :star:83

### HTTP Clients

*Libraries for making HTTP requests.*

* [gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library. :star:678
* [goreq](https://github.com/smallnest/goreq) - Enhanced simplified HTTP client based on gorequest. :star:98
* [grequests](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library. :star:1415
* [heimdall](https://github.com/gojektech/heimdall) - An enchanced http client with retry and hystrix capabilities. :star:1078
* [pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency. :star:332
* [rq](https://github.com/ddo/rq) - A nicer interface for golang stdlib HTTP client. :star:27
* [sling](https://github.com/dghubble/sling) - Sling is a Go HTTP client library for creating and sending API requests. :star:1004

## OpenGL

*Libraries for using OpenGL in Go.*

* [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow). :star:642
* [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3. :star:734
* [goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). :star:129
* [goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events. :star:57
* [mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM. :star:291

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3. :star:21477
* [go-firestorm](https://github.com/jschoedt/go-firestorm) - A simple ORM for Google/Firebase Cloud Firestore. :star:1
* [go-pg](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance. :star:3001
* [go-queryset](https://github.com/jirfag/go-queryset) - 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM. :star:448
* [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - A flexible and powerful SQL string builder library plus a zero-config ORM. :star:233
* [go-store](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go. :star:93
* [GORM](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly. :star:14677
* [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go. :star:3078
* [grimoire](https://github.com/Fs02/grimoire) - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3). :star:112
* [lore](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go. :star:4
* [Marlow](https://github.com/dadleyy/marlow) - Generated ORM from project structs for compile time safety assurances. :star:67
* [pop/soda](https://github.com/gobuffalo/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. :star:678
* [QBS](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM. :star:539
* [reform](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation. :star:802
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema. :star:2274
* [upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. :star:1849
* [Xorm](https://github.com/go-xorm/xorm) - Simple and powerful ORM for Go. :star:5209
* [Zoom](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis. :star:239

## Package Management

*Official tooling for dependency and package management*

* [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) - Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules.

*Official experimental tooling for package management*

* [dep](https://github.com/golang/dep) - Go dependency tool. :star:12568
* [vgo](https://go.googlesource.com/vgo/) - Versioned Go.

*Unofficial libraries for package and dependency management.*

* [gigo](https://github.com/LyricalSecurity/gigo) - PIP-like dependency tool for golang, with support for private repositories and hashes. :star:197
* [glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip. :star:7784
* [godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies. :star:5651
* [gom](https://github.com/mattn/gom) - Go Manager - bundle for go. :star:1351
* [goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler. :star:777
* [gop](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH. :star:50
* [gopm](https://github.com/gpmgo/gopm) - Go Package Manager. :star:2362
* [govendor](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file. :star:4743
* [gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go. :star:1205
* [johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git. :star:214
* [mvn-golang](https://github.com/raydac/mvn-golang) - plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure. :star:87
* [nut](https://github.com/jingweno/nut) - Vendor Go dependencies. :star:245
* [VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments. :star:115

## Query Language

* [gojsonq](https://github.com/thedevsaddam/gojsonq) - A simple Go package to Query over JSON Data. :star:864
* [graphql](https://github.com/tmc/graphql) - graphql parser + utilities. :star:51
* [graphql](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use. :star:2789
* [graphql-go](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go. :star:5228
* [jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang. :star:201
* [jsonslice](https://github.com/bhmj/jsonslice) - Jsonpath queries with advanced filters. :star:24
* [rql](https://github.com/a8m/rql) - Resource Query Language for REST API. :star:111

## Resource Embedding

* [esc](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them. :star:472
* [fileb0x](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use. :star:424
* [go-embed](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable. :star:16
* [go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go. :star:154
* [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy. :star:1649
* [packr](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries. :star:2120
* [statics](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks. :star:53
* [statik](https://github.com/rakyll/statik) - Embeds static files into a Go executable. :star:2112
* [templify](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries. :star:19
* [vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem. :star:658

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [assocentity](https://github.com/ndabAP/assocentity) - Package assocentity returns the average distance from words to a given entity. :star:4
* [bradleyterry](https://github.com/seanhagen/bradleyterry) - Provides a Bradley-Terry Model for pairwise comparisons.
* [chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types. :star:581
* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - Dataframes for Go for machine-learning and statistics (similar to pandas). :star:77
* [evaler](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator. :star:40
* [ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages. :star:266
* [geom](https://github.com/skelterjohn/geom) - 2D geometry for golang. :star:40
* [go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go. :star:627
* [go-fn](https://github.com/ematvey/go-fn) - Mathematical functions written in Go language, that are not covered by math pkg. :star:11
* [go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language. :star:5
* [gocomplex](https://github.com/varver/gocomplex) - Complex number library for the Go programming language. :star:5
* [goent](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures. :star:13
* [gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams. :star:127
* [gonum](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more. :star:2961
* [gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go. :star:1216
* [goraph](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorith visualization). :star:598
* [gosl](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more. :star:1307
* [GoStats](https://github.com/OGFris/GoStats) - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions. :star:9
* [graph](https://github.com/yourbasic/graph) - Library of basic graph algorithms. :star:233
* [ode](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions. :star:10
* [orb](https://github.com/paulmach/orb) - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support. :star:199
* [pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go. :star:48
* [piecewiselinear](https://github.com/sgreben/piecewiselinear) - Tiny linear interpolation library. :star:5
* [PiHex](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi. :star:9
* [rootfinding](https://github.com/khezen/rootfinding) - root-finding algorithms library for finding roots of quadratic functions. :star:3
* [sparse](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries. :star:69
* [stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library. :star:1342
* [streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data. :star:1314
* [TextRank](https://github.com/DavidBelicza/TextRank) - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support. :star:66
* [triangolatte](https://github.com/tchayen/triangolatte) - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs. :star:11

## Security

*Libraries that are used to help make your application more secure.*

* [acmetool](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal. :star:1693
* [acra](https://github.com/cossacklabs/acra) - Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system. :star:451
* [argon2pw](https://github.com/raja/argon2pw) - Argon2 password hash generation with constant-time password comparison. :star:75
* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) - Auto provision Let's Encrypt certificates and start a TLS server.
* [BadActor](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban. :star:247
* [Cameradar](https://github.com/Ullaakut/cameradar) - Tool and library to remotely hack RTSP streams from surveillance cameras. :star:1824
* [certificates](https://github.com/mvmaasakkers/certificates) - An opinionated tool for generating tls certificates. :star:6
* [go-yara](https://github.com/hillu/go-yara) - Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)". :star:133
* [goArgonPass](https://github.com/dwin/goArgonPass) - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations. :star:11
* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords. :star:30
* [Interpol](https://bitbucket.org/vahidi/interpol) - Rule-based data generator for fuzzing and penetration testing.
* [jwc](https://github.com/khezen/jwc) - JSON Web Cryptography library. :star:5
* [lego](https://github.com/xenolf/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt). :star:3485
* [memguard](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory. :star:1513
* [nacl](https://github.com/kevinburke/nacl) - Go implementation of the NaCL set of API's. :star:451
* [passlib](https://github.com/hlandau/passlib) - Futureproof password hashing library. :star:226
* [secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins. :star:1208
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in. :star:155
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys. :star:195
* [sslmgr](https://github.com/adrianosela/sslmgr) - SSL certificates made easy with a high level wrapper around acme/autocert. :star:7

## Serialization

*Libraries and tools for binary serialization.*

* [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang. :star:40
* [bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go. :star:60
* [bel](https://github.com/32leaves/bel) - Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC. :star:5
* [binstruct](https://github.com/ghostiam/binstruct) - Golang binary decoder for mapping data into the structure. :star:7
* [colfer](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format. :star:472
* [csvutil](https://github.com/jszwec/csvutil) - High Performance, idiomatic CSV record encoding and decoding to native Go structures. :star:306
* [fwencoder](https://github.com/o1egl/fwencoder) - Fixed width file parser (encoding and decoding library) for Go. :star:6
* [go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go. :star:272
* [go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support. :star:1235
* [gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets. :star:2959
* [goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers. :star:5096
* [jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json". :star:5544
* [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures. :star:2434
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions. :star:119
* [structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures. :star:95

## Server Applications

* [algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. :star:1587
* [Caddy](https://github.com/mholt/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use. :star:23180
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [devd](https://github.com/cortesi/devd) - Local webserver for developers. :star:2805
* [discovery](https://github.com/Bilibili/discovery) - A registry for resilient mid-tier load balancing and failover. :star:676
* [etcd](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery. :star:26542
* [Fider](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback. :star:796
* [Flagr](https://github.com/checkr/flagr) - Flagr is an open-source feature flagging and A/B testing service. :star:827
* [flipt](https://github.com/markphelps/flipt) - A self contained feature flag solution written in Go and Vue.js :star:990
* [jackal](https://github.com/ortuman/jackal) - An XMPP server written in Go. :star:718
* [minio](https://github.com/minio/minio) - Minio is a distributed object storage server. :star:17514
* [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) - Nginx log parser and exporter to Prometheus. :star:5
* [nsq](http://nsq.io/) - A realtime distributed messaging platform.
* [psql-streamer](https://github.com/blind-oracle/psql-streamer) - Stream database events from PostgreSQL to Kafka. :star:5
* [riemann-relay](https://github.com/blind-oracle/riemann-relay) - Relay to load-balance Riemann events and/or convert them to Carbon.
* [RoadRunner](https://github.com/spiral/roadrunner) - High-performance PHP application server, load-balancer and process manager. :star:3293
* [yakvs](https://git.sci4me.com/sci4me/yakvs) - Small, networked, in-memory key-value store.

## Template Engines

*Libraries and tools for templating and lexing.*

* [ace](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold. :star:762
* [amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade. :star:824
* [damsel](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others. :star:20
* [ego](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled. :star:416
* [extemplate](https://github.com/dannyvankooten/extemplate) - Tiny wrapper around html/template to allow for easy file-based template inheritance. :star:13
* [fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/). :star:299
* [gofpdf](https://github.com/jung-kurt/gofpdf) - PDF document generator with high level support for text, drawing and images. :star:3078
* [goview](https://github.com/foolin/goview) - Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application. :star:46
* [hero](https://github.com/shiyanhui/hero) - Hero is a handy, fast and powerful go template engine. :star:1206
* [jet](https://github.com/CloudyKit/jet) - Jet template engine. :star:582
* [kasia.go](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation. :star:70
* [liquid](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates. :star:83
* [mustache](https://github.com/hoisie/mustache) - Go implementation of the Mustache template language. :star:968
* [pongo2](https://github.com/flosch/pongo2) - Django-like template-engine for Go. :star:1489
* [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it. :star:1408
* [raymond](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go. :star:341
* [Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang. :star:701
* [Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/). :star:144
* [velvet](https://github.com/gobuffalo/velvet) - Complete handlebars implementation in Go. :star:64

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions. :star:13
    * [badio](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package. :star:9
    * [baloo](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy. :star:648
    * [biff](https://github.com/fulldump/biff) - Bifurcation testing framework, BDD compatible. :star:6
    * [bro](https://github.com/marioidival/bro) - Watch files in directory and run tests for them. :star:26
    * [charlatan](https://github.com/percolate/charlatan) - Tool to generate fake interface implementations for tests. :star:190
    * [commander](https://github.com/SimonBaeumer/commander) - Tool for testing cli applications on windows, linux and osx. :star:32
    * [cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework. :star:83
    * [dbcleaner](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby. :star:87
    * [dsunit](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files. :star:25
    * [endly](https://github.com/viant/endly) - Declarative end to end functional testing. :star:93
    * [flute](https://github.com/suzuki-shunsuke/flute) - HTTP client testing framework. :star:1
    * [frisby](https://github.com/verdverm/frisby) - REST API testing framework. :star:249
    * [ginkgo](http://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
    * [go-carpet](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal. :star:195
    * [go-cmp](https://github.com/google/go-cmp) - Package for comparing Go values in tests. :star:1160
    * [go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code. :star:291
    * [go-testdeep](https://github.com/maxatome/go-testdeep) - Extremely flexible golang deep comparison, extends the go testing package. :star:55
    * [go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests. :star:331
    * [goblin](https://github.com/franela/goblin) - Mocha like testing framework fo Go. :star:626
    * [gocheck](http://labix.org/gocheck) - More advanced testing framework alternative to gotest.
    * [GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload. :star:4895
    * [gocrest](https://github.com/corbym/gocrest) - Composable hamcrest-like matchers for Go assertions. :star:8
    * [godog](https://github.com/DATA-DOG/godog) - Cucumber or Behat like BDD framework for Go. :star:757
    * [gofight](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework. :star:257
    * [gogiven](https://github.com/corbym/gogiven) - YATSPEC-like BDD testing framework for Go. :star:7
    * [gomatch](https://github.com/jfilipczyk/gomatch) - library created for testing JSON against patterns. :star:30
    * [gomega](http://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
    * [GoSpec](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language. :star:111
    * [gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec. :star:51
    * [gosuite](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests. :star:9
    * [gotest.tools](https://github.com/gotestyourself/gotest.tools) - A collection of packages to augment the go testing package and support common patterns. :star:120
    * [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results. :star:26
    * [httpexpect](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing. :star:1141
    * [jsonassert](https://github.com/kinbiko/jsonassert) - Package for verifying that your JSON payloads are serialized correctly. :star:21
    * [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test. :star:49
    * [testcase](https://github.com/adamluzsi/testcase) - Idiomatic testing framework for Behavior Driven Development. :star:9
    * [testfixtures](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications. :star:327
    * [Testify](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package. :star:8151
    * [testmd](https://godoc.org/github.com/tvastar/test/cmd/testmd) - Convert markdown snippets into testable go code.
    * [testsql](https://github.com/zhulongcheng/testsql) - Generate test data from SQL files before testing and clear it after finished. :star:7
    * [Tt](https://github.com/vcaesar/tt) - Simple and colorful test tools. :star:5
    * [wstest](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler. :star:62

* Mock
    * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects. :star:361
    * [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions. :star:1744
    * [go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes. :star:163
    * [gock](https://github.com/h2non/gock) - Versatile HTTP mocking made easy. :star:819
    * [gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language. :star:2857
    * [govcr](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing. :star:82
    * [hoverfly](https://github.com/SpectoLabs/hoverfly) - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI. :star:1438
    * [httpmock](https://github.com/jarcoal/httpmock) - Easy mocking of HTTP responses from external resources. :star:582
    * [minimock](https://github.com/gojuno/minimock) - Mock generator for Go interfaces. :star:263
    * [mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter. :star:22

* Fuzzing and delta-debugging/reducing/shrinking.
    * [go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing system. :star:2888
    * [gofuzz](https://github.com/google/gofuzz) - Library for populating go objects with random values. :star:532
    * [Tavor](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework. :star:212

* Selenium and browser control tools.
    * [cdp](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it. :star:353
    * [chromedp](https://github.com/knq/chromedp) - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol. :star:3593
    * [ggr](https://github.com/aerokube/ggr) - a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs. :star:208
    * [selenoid](https://github.com/aerokube/selenoid) - alternative Selenium hub server that launches browsers within containers. :star:1230

* Fail injection
    * [failpoint](https://github.com/pingcap/failpoint) - An implementation of [failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail) for Golang. :star:389

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
    * [align](https://github.com/Guitarbum722/align) - A general purpose application that aligns text. :star:59
    * [allot](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots. :star:34
    * [bbConvert](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags. :star:5
    * [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go. :star:3896
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer. :star:1251
    * [codetree](https://github.com/aerogo/codetree) - Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure. :star:7
    * [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers. :star:8422
    * [commonregex](https://github.com/mingrammer/commonregex) - A collection of common regular expressions for Go. :star:553
    * [dataflowkit](https://github.com/slotix/dataflowkit) - Web scraping Framework to turn websites into structured data. :star:290
    * [did](https://github.com/ockam-network/did) - DID (Decentralized Identifiers) Parser and Stringer in Go. :star:23
    * [doi](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go. :star:4
    * [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go. :star:37
    * [enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/). :star:8
    * [encdec](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decodersa. :star:3
    * [genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings. :star:53
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
    * [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection). :star:26
    * [go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format. :star:1902
    * [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language. :star:98
    * [go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string. :star:209
    * [go-slugify](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support. :star:29
    * [go-toml](https://github.com/pelletier/go-toml) - Go library for the TOML format with query support and handy cli tools. :star:609
    * [go-vcard](https://github.com/emersion/go-vcard) - Parse and format vCard. :star:25
    * [go-zero-width](https://github.com/trubitsyn/go-zero-width) - Zero-width character detection and removal for Go. :star:41
    * [gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go. :star:1098
    * [gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language. :star:300
    * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - Format bytes to string. :star:307
    * [gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts. :star:29
    * [goq](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery). :star:146
    * [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language. :star:7591
    * [goregen](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions. :star:36
    * [gotext](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go. :star:231
    * [guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text. :star:44
    * [htmlquery](https://github.com/antchfx/htmlquery) - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression. :star:130
    * [inject](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector. :star:1141
    * [ltsv](https://github.com/Wing924/ltsv) - High performance [LTSV (Labeled Tab Separeted Value)](http://ltsv.org/) reader for Go. :star:2
    * [mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. :star:331
    * [sdp](https://github.com/gortc/sdp) - SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)]. :star:69
    * [sh](https://github.com/mvdan/sh) - Shell parser and formatter. :star:2000
    * [slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support. :star:373
    * [Slugify](https://github.com/avelino/slugify) - Go slugify application that handles string. :star:26
    * [syndfeed](https://github.com/zhengchun/syndfeed) - A syndication feed for Atom 1.0 and RSS 2.0. :star:5
    * [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection). :star:2790
* Utility
    * [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) - A sanitization-based swear filter for Go. :star:15
    * [gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go. :star:198
    * [kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms. :star:12
    * [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes. :star:6
    * [parth](https://github.com/codemodus/parth) - URL path segmentation parsing. :star:31
    * [radix](https://github.com/yourbasic/radix) - fast string sorting algorithm. :star:144
    * [Tagify](https://github.com/zoomio/tagify) - Produces a set of tags from given source. :star:1
    * [TySug](https://github.com/Dynom/TySug) - Alternative suggestions with respect to keyboard layouts. :star:3
    * [xj2go](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct. :star:17
    * [xurls](https://github.com/mvdan/xurls) - Extract urls from text. :star:460

## Third-party APIs

*Libraries for accessing third party APIs.*

* [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html). :star:40
* [anaconda](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API. :star:989
* [aws-sdk-go](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language. :star:5032
* [brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API. :star:16
* [cachet](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/). :star:66
* [circleci](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API. :star:41
* [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API. :star:57
* [codeship-go](https://github.com/codeship/codeship-go) - Go client library for interacting with Codeship's API v2. :star:15
* [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) - Go client library for interacting with Coinpaprika's API. :star:12
* [discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API. :star:967
* [ethrpc](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API. :star:169
* [facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API. :star:771
* [fcm](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging. :star:32
* [gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API. :star:43
* [gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface. :star:26
* [gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging. :star:29
* [geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs. :star:306
* [github](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3. :star:4766
* [githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4. :star:503
* [go-chronos](https://github.com/axelspringer/go-chronos) - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler :star:3
* [go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API. :star:9
* [go-imgur](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com)
* [go-jira](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
* [go-marathon](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS. :star:189
* [go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api). :star:16
* [go-sophos](https://github.com/esurdam/go-sophos) - Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies. :star:5
* [go-sptrans](https://github.com/sergioaugrod/go-sptrans) - Go client library for the SPTrans Olho Vivo API. :star:8
* [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph publishing platform API client.
* [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github. :star:100
* [go-twitch](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API. :star:17
* [go-twitter](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs. :star:713
* [go-unsplash](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API. :star:20
* [go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API. :star:39
* [golyrics](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website. :star:31
* [gomalshare](https://github.com/MonaxGT/gomalshare) - Go library MalShare API [malshare.com](http://www.malshare.com/)
* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library. :star:36
* [google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go. :star:1924
* [google-analytics](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting. :star:12
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library. :star:1786
* [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/). :star:6
* [gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. :star:118
* [hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API. :star:110
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP. :star:113
* [igdb](https://github.com/Henry-Sarabia/igdb) - Go client for the [Internet Game Database API](https://api.igdb.com/). :star:52
* [Medium](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API. :star:115
* [megos](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster. :star:57
* [minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage. :star:722
* [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications. :star:30
* [patreon-go](https://github.com/mxpv/patreon-go) - Go library for Patreon API. :star:18
* [paypal](https://github.com/logpacker/PayPal-Go-SDK) - Wrapper for PayPal payment API. :star:300
* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK. :star:1
* [pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API. :star:57
* [rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP. :star:8
* [shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API. :star:19
* [simples3](https://github.com/rhnvrm/simples3) - Simple no frills AWS S3 Library using REST with V4 Signing written in Go. :star:9
* [slack](https://github.com/nlopes/slack) - Slack API in Go. :star:2424
* [smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API. :star:10
* [spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API. :star:17
* [steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers. :star:14
* [stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API. :star:944
* [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API. :star:14
* [TheMovieDb](https://github.com/jbrodriguez/go-tmdb) - Simple golang package to communicate with [themoviedb.org](https://themoviedb.org). :star:12
* [translate](https://github.com/poorny/translate) - Go online translation package. :star:27
* [Trello](https://github.com/adlio/trello) - Go wrapper for the Trello API. :star:101
* [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) - Go wrapper for the TripAdvisor API. :star:1
* [tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API. :star:6
* [uptimerobot](https://github.com/bitfield/uptimerobot) - Go wrapper and command-line client for the Uptime Robot v2 API. :star:35
* [webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket. :star:354
* [wit-go](https://github.com/wit-ai/wit-go) - Go client for wit.ai HTTP API. :star:47
* [ynab](https://github.com/brunomvsouza/ynab.go) - Go wrapper for the YNAB API. :star:12
* [zooz](https://github.com/gojuno/go-zooz) - Go client for the Zooz API. :star:5

## Utilities

*General utilities and tools to make your life easier.*

* [abutil](https://github.com/bahlo/abutil) - Collection of often-used Golang helpers. :star:51
* [apm](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API. :star:129
* [backscanner](https://github.com/icza/backscanner) - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. :star:8
* [blank](https://github.com/Henry-Sarabia/blank) - Verify or remove blanks and whitespace from strings. :star:1
* [boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates. :star:943
* [chyle](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities. :star:108
* [circuit](https://github.com/cep21/circuit) - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern. :star:329
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go. :star:795
* [clockwork](https://github.com/jonboulle/clockwork) - A simple fake clock for golang. :star:220
* [command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher. :star:9
* [copy-pasta](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage. :star:37
* [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics. :star:8829
* [ctxutil](https://github.com/posener/ctxutil) - A collection of utility functions for contexts. :star:7
* [dbt](https://github.com/nikogura/dbt) - A framework for running self-updating signed binaries from a central, trusted repository. :star:13
* [Death](https://github.com/vrecan/death) - Managing go application shutdown with signals. :star:133
* [Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go. :star:210
* [delve](https://github.com/derekparker/delve) - Go debugger. :star:12048
* [dlog](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls. :star:15
* [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy. :star:311
* [evaluator](https://github.com/nullne/evaluator) - Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend. :star:15
* [fastlz](https://github.com/digitalcrab/fastlz) - Wrap over [FastLz](http://fastlz.org/) (free, open-source, portable real-time compression library) for GoLang. :star:12
* [filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature. :star:949
* [filler](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag. :star:14
* [filter](https://github.com/gookit/filter) - provide filtering, sanitizing, and conversion of Go data. :star:12
* [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go. :star:23191
* [gaper](https://github.com/maxcnunes/gaper) - Builds and restarts a Go project when it crashes or some watched file changes. :star:39
* [generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex. :star:19
* [ghokin](https://github.com/antham/ghokin) - Parallelized formatter with no external dependencies for gherkin (cucumber, behat...). :star:12
* [git-time-metric](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git. :star:718
* [go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code. :star:45
* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only). :star:160
* [go-bsdiff](https://github.com/gabstv/go-bsdiff) - Pure Go bsdiff and bspatch libraries and CLI tools. :star:83
* [go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go. :star:433
* [go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...). :star:1188
* [go-health](https://github.com/Talento90/go-health) - Health package simplifies the way you add health check to your services. :star:63
* [go-httpheader](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields. :star:14
* [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) - Go package for working with Problem Details. :star:3
* [go-rate](https://github.com/beefsack/go-rate) - Timed rate limiter for Go. :star:292
* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go. :star:105
* [go-torch](https://github.com/uber/go-torch) - Stochastic flame graph profiler for Go programs. :star:3636
* [go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project. :star:181
* [goback](https://github.com/carlescere/goback) - Go simple exponential backoff package. :star:40
* [godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons. :star:404
* [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox. :star:3745
* [gohper](https://github.com/cosiner/gohper) - Various tools/modules help for development. :star:248
* [golarm](https://github.com/msempere/golarm) - Fire alarms with system events. :star:34
* [golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks. :star:42
* [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs. :star:423
* [goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images. :star:22
* [goreadability](https://github.com/philipjkim/goreadability) - Webpage summary extractor using Facebook Open Graph and arc90's readability. :star:32
* [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible. :star:4506
* [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report. :star:2480
* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features. :star:27
* [gostrutils](https://github.com/ik5/gostrutils) - Collections of string manipulation and conversion functions. :star:16
* [gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go. :star:142
* [gpath](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection. :star:31
* [gubrak](https://github.com/novalagung/gubrak) - Golang utility library with syntactic sugar. It's like lodash, but for golang. :star:140
* [handy](https://github.com/miguelpragier/handy) - Many utilities and helpers like string handlers/formatters and validators. :star:45
* [htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility. :star:482
* [hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal. :star:16978
* [hystrix-go](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker. :star:2019
* [immortal](https://github.com/immortal/immortal) - \*nix cross-platform (OS agnostic) supervisor. :star:603
* [intrinsic](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code. :star:39
* [jump](https://github.com/gsamokovarov/jump) - Jump helps you navigate faster by learning your habits. :star:660
* [koazee](https://github.com/wesovilabs/koazee) - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays. :star:295
* [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go. :star:100
* [mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems. :star:1117
* [mergo](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements. :star:850
* [mimemagic](https://github.com/zRedShift/mimemagic) - Pure Go ultra performant MIME sniffing library/utility. :star:42
* [mimesniffer](https://github.com/aofei/mimesniffer) - A MIME type sniffer for Go. :star:7
* [mimetype](https://github.com/gabriel-vasile/mimetype) - Package for MIME type detection based on magic numbers. :star:122
* [minify](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats. :star:1860
* [minquery](https://github.com/icza/minquery) - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off). :star:50
* [mmake](https://github.com/tj/mmake) - Modern Make. :star:1445
* [moldova](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template. :star:148
* [mole](https://github.com/davrodpin/mole) - cli app to easily create ssh tunnels. :star:1301
* [mssqlx](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind. :star:58
* [multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers. :star:58
* [myhttp](https://github.com/inancgumus/myhttp) - Simple API to make HTTP GET requests with timeout support. :star:34
* [netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services. :star:65
* [okrun](https://github.com/xta/okrun) - go run error steamroller. :star:14
* [olaf](https://github.com/btnguyen2k/olaf) - Twitter Snowflake implemented in Go. :star:1
* [onecache](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc). :star:98
* [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump. :star:2144
* [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool. :star:5471
* [pgo](https://github.com/arthurkushman/pgo) - Convenient functions for PHP community. :star:24
* [pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API. :star:71
* [profile](https://github.com/pkg/profile) - Simple profiling support package for Go. :star:1011
* [rclient](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs. :star:27
* [realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths. :star:3165
* [repeat](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating. :star:56
* [request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™. :star:355
* [rerate](https://github.com/abo/rerate) - Redis-based rate counter and rate limiter for Go. :star:12
* [rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes. :star:153
* [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client. :star:1977
* [retry](https://github.com/kamilsk/retry) - The most advanced functional mechanism to perform actions repetitively until successful. :star:161
* [retry](https://github.com/percolate/retry) - A simple but highly configurable retry package for Go. :star:2
* [retry](https://github.com/thedevsaddam/retry) - Simple and easy retry mechanism package for Go. :star:34
* [retry](https://github.com/shafreeck/retry) - A pretty simple library to ensure your work to be done. :star:10
* [retry-go](https://github.com/rafaeljesus/retry-go) - Retrying made simple and easy for golang. :star:28
* [robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics. :star:135
* [scan](https://github.com/blockloop/scan) - Scan golang `sql.Rows` directly to structs, slices, or primitive types. :star:12
* [serve](https://github.com/syntaqx/serve) - A static http server anywhere you need. :star:191
* [silk](https://github.com/chrispassas/silk) - Read silk netflow files. :star:4
* [sliceconv](https://github.com/Henry-Sarabia/sliceconv) - Slice conversion between primitive types. :star:3
* [slicer](https://github.com/leaanthony/slicer) - Makes working with slices easier. :star:3
* [spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options. :star:786
* [sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package. :star:6812
* [sslice](https://github.com/yaa110/sslice) - Create a slice which is always sorted. :star:5
* [Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB. :star:1355
* [structs](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs. :star:12
* [Task](https://github.com/go-task/task) - simple "Make" alternative. :star:1935
* [toolbox](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer. :star:95
* [tracer](https://github.com/kamilsk/tracer) - Simple, lightweight tracing. :star:8
* [ugo](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go. :star:20
* [UNIS](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go. :star:69
* [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases. :star:4676
* [util](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...). :star:133
* [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection. :star:8260
* [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang. :star:68

## UUID

*Libraries for working with UUIDs.*

* [goid](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs. :star:21
* [nanoid](https://github.com/aidarkhanov/nanoid) - A tiny and efficient Go unique string ID generator. :star:2
* [sno](https://github.com/muyo/sno) - Compact, sortable and fast unique IDs with embedded metadata. :star:15
* [ulid](https://github.com/oklog/ulid) - Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier). :star:1674
* [uniq](https://gitlab.com/skilstak/code/go/uniq) - No hassle safe, fast unique identifiers with commands. 
* [uuid](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier. :star:10
* [uuid](https://github.com/gofrs/uuid) - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid. :star:568
* [wuid](https://github.com/edwingeng/wuid) - An extremely fast unique number generator, 10-135 times faster than UUID. :star:287

## Validation

*Libraries for validation.*

* [checkdigit](https://github.com/osamingo/checkdigit) - Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.). :star:44
* [govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs. :star:3555
* [govalidator](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation. :star:716
* [jio](https://github.com/faceair/jio) - jio is a json schema validator similar to [joi](https://github.com/hapijs/joi). :star:21
* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags. :star:1050
* [terraform-validator](https://github.com/thazelart/terraform-validator) - A norms and conventions validator for Terraform. :star:11
* [validate](https://github.com/gookit/validate) - Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features. :star:95
* [validate](https://github.com/gobuffalo/validate) - This package provides a framework for writing validations for Go applications. :star:19
* [validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving. :star:3524

## Version Control

*Libraries for version control.*

* [gh](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks. :star:70
* [git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2. :star:1365
* [go-git](https://github.com/src-d/go-git) - highly extensible Git implementation in pure Go. :star:4282
* [go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go. :star:71
* [hercules](https://github.com/src-d/hercules) - gaining advanced insights from Git repository history. :star:530
* [hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories. :star:12

## Video

*Libraries for manipulating video.*

* [gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries. :star:532
* [go-astisub](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.). :star:167
* [go-astits](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO. :star:259
* [go-m3u8](https://github.com/quangngotan95/go-m3u8) - Parser and generator library for Apple m3u8 playlists. :star:38
* [goav](https://github.com/giorgisio/goav) - Comphrensive Go bindings for FFmpeg. :star:788
* [gst](https://github.com/ziutek/gst) - Go bindings for GStreamer. :star:152
* [libgosubs](https://github.com/wargarblgarbl/libgosubs) - Subtitle format support for go. Supports .srt, .ttml, and .ass. :star:11
* [libvlc-go](https://github.com/adrg/libvlc-go) - Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player). :star:64
* [v4l](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go. :star:28

## Web Frameworks

*Full stack web frameworks.*

* [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
* [Aero](https://github.com/aerogo/aero) - High-performance web framework for Go, reaches top scores in Lighthouse. :star:158
* [Air](https://github.com/aofei/air) - An ideally refined web framework for Go. :star:332
* [Banjo](https://github.com/nsheremet/banjo) - Very simple and fast web framework for Go. :star:8
* [Beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language. :star:21477
* [Buffalo](http://gobuffalo.io) - Bringing the productivity of Rails to Go!
* [Echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework. :star:14688
* [Fireball](https://github.com/zpatrick/fireball) - More "natural" feeling web framework. :star:49
* [Gem](https://github.com/go-gem/gem) - Simple and fast web framework, friendly to REST API. :star:153
* [Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity. :star:30012
* [Gizmo](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times. :star:2851
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API. :star:3334
* [go-rest](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go. :star:116
* [Goa](https://github.com/goadesign/goa) - Goa provides a holistic approach for developing remote APIs and microservices in Go. :star:3506
* [Golax](https://github.com/fulldump/golax) - A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more. :star:71
* [Golf](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library. :star:235
* [Gondola](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster. :star:314
* [gongular](https://github.com/mustafaakin/gongular) - Fast Go web framework with input mapping/validation and (DI) Dependency Injection. :star:415
* [hiboot](https://github.com/hidevopsio/hiboot) - hiboot is a high performance web application framework with auto configuration and dependency injection support. :star:87
* [Macaron](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go. :star:2818
* [mango](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333. :star:339
* [Microservice](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang. :star:57
* [neo](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API. :star:392
* [nio](https://github.com/go-nio/nio) - Modern, minimal and productive Go HTTP framework. :star:21
* [patron](https://github.com/beatlabs/patron) - Patron is a microservice framework following best cloud practices with a focus on productivity. :star:33
* [Resoursea](https://github.com/resoursea/api) - REST framework for quickly writing resource based services. :star:29
* [REST Layer](http://rest-layer.io) - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
* [Revel](https://github.com/revel/revel) - High-productivity web framework for the Go language. :star:11245
* [rex](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`. :star:27
* [sawsij](https://github.com/jaybill/sawsij) - lightweight, open-source web framework for building high-performance, data-driven web applications. :star:2
* [tango](https://github.com/lunny/tango) - Micro & pluggable web framework for Go. :star:817
* [tigertonic](https://github.com/rcrowley/go-tigertonic) - Go framework for building JSON web services inspired by Dropwizard. :star:995
* [traffic](https://github.com/pilu/traffic) - Sinatra inspired regexp/pattern mux and web framework for Go. :star:518
* [uAdmin](https://github.com/uadmin/uadmin) - Fully featured web framework for Golang, inspired by Django. :star:54
* [utron](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang). :star:2135
* [vox](https://github.com/aisk/vox) - A golang web framework for humans, inspired by Koa heavily. :star:40
* [WebGo](https://github.com/bnkamalesh/webgo) - A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc). :star:73
* [YARF](https://github.com/yarf-framework/yarf) - Fast micro-framework designed to build REST APIs and web services in a fast and simple way. :star:50
* [Zerver](https://github.com/cosiner/zerver) - Zerver is an expressive, modular, feature completed RESTful framework.

### Middlewares

#### Actual middlewares

* [client-timing](https://github.com/posener/client-timing) - An HTTP client for Server-Timing header. :star:13
* [CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API. :star:1223
* [formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST. :star:33
* [go-server-timing](https://github.com/mitchellh/go-server-timing) - Add/parse Server-Timing header. :star:745
* [Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go. :star:791
* [ln-paywall](https://github.com/philippgille/ln-paywall) - Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin). :star:89
* [Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler. :star:1249
* [XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends. :star:72

#### Libraries for creating HTTP middlewares

* [alice](https://github.com/justinas/alice) - Painless middleware chaining for Go. :star:1824
* [catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain"). :star:7
* [chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware"). :star:63
* [go-wrap](https://github.com/go-on/wrap) - Small middlewares package for net/http. :star:59
* [gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs. :star:81
* [interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang. :star:289
* [muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http. :star:208
* [negroni](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang. :star:6333
* [render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses. :star:1268
* [renderer](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go. :star:169
* [rye](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context. :star:94
* [stats](https://github.com/thoas/stats) - Go middleware that stores various information about your web application. :star:537

### Routers

* [alien](https://github.com/gernest/alien) - Lightweight and fast http router from outer space. :star:106
* [bellt](https://github.com/GuilhermeCaruso/bellt) - A simple Go HTTP router. :star:38
* [Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer. :star:1220
* [Bxog](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters. :star:94
* [chi](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context. :star:6041
* [fasthttprouter](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`. :star:749
* [FastRouter](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go. :star:18
* [gocraft/web](https://github.com/gocraft/web) - Mux and middleware package in Go. :star:1396
* [Goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`. :star:769
* [GoRouter](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`. :star:49
* [gowww/router](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface. :star:157
* [httprouter](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework. :star:9725
* [httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter. :star:385
* [lars](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks. :star:375
* [mux](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang. :star:9676
* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs. :star:359
* [pure](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation. :star:86
* [Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers. :star:349
* [vestigo](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications. :star:250
* [violetear](https://github.com/nbari/violetear) - Go HTTP router. :star:95
* [xmux](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support. :star:88
* [xujiajun/gorouter](https://github.com/xujiajun/gorouter) - A simple and fast HTTP router for Go. :star:451

## Windows

* [d3d9](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9. :star:85
* [go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang. :star:551
* [gosddl](https://github.com/MonaxGT/gosddl) - Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL. :star:1

## XML

*Libraries and tools for manipulating XML.*

* [XML-Comp](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags. :star:16
* [xml2map](https://github.com/sbabiv/xml2map) - XML to MAP converter written Golang. :star:15
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module. :star:6
* [xpath](https://github.com/antchfx/xpath) - XPath package for Go. :star:168
* [xquery](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression. :star:145
* [zek](https://github.com/miku/zek) - Generate a Go struct from XML. :star:256

# Tools

*Go software and plugins.*

## Code Analysis

* [apicompat](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes. :star:165
* [dupl](https://github.com/mibk/dupl) - Tool for code clone detection. :star:176
* [errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs. :star:1319
* [gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time. :star:917
* [go-checkstyle](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments. :star:95
* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects. :star:282
* [go-critic](https://github.com/go-critic/go-critic) - source code linter that brings checks that are currently not implemented in other linters. :star:577
* [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) - An easy way to find outdated dependencies of your Go projects. :star:182
* [go-outdated](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages. :star:45
* [goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer. :star:376
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [GolangCI](https://golangci.com/) - GolangCI is an automated Golang code review service for GitHub pull requests. Service is open source and it's free for open source projects.
* [GoLint](https://github.com/golang/lint) - Golint is a linter for Go source code. :star:3154
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple is a linter for Go source code that specialises on simplifying code. :star:2610
* [gostatus](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages. :star:240
* [lint](https://github.com/surullabs/lint) - Run linters as part of go test. :star:63
* [php-parser](https://github.com/z7zmey/php-parser) - A Parser for PHP written in Go. :star:636
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#. :star:2610
* [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) - tarp finds functions and methods without direct unit tests in Go source code. :star:14
* [unconvert](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source. :star:258
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - unused checks Go code for unused constants, variables, functions and types. :star:2610
* [validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags. :star:62

## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
* [go-language-server](https://github.com/theia-ide/go-language-server) - A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol. :star:30
* [go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs. :star:957
* [go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting. :star:1481
* [gocode](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language. :star:4743
* [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - This extension adds benchmark profiling support for the Go language to VS Code.
* [GoSublime](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features. :star:3240
* [gounit-vim](https://github.com/hexdigest/gounit-vim) - Vim plugin for generating Go tests based on the function's or method's signature. :star:17
* [theia-go-extension](https://github.com/theia-ide/theia-go-extension) - Go language support for the Theia IDE. :star:12
* [velour](https://github.com/velour/velour) - IRC client for the acme editor. :star:16
* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save. :star:81
* [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim. :star:10848
* [vscode-go](https://github.com/Microsoft/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language. :star:5131
* [Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes. :star:168

## Go Generate Tools

* [generic](https://github.com/usk81/generic) - flexible data type for Go. :star:28
* [genny](https://github.com/cheekybits/genny) - Elegant generics for Go. :star:969
* [gocontracts](https://github.com/Parquery/gocontracts) - brings design-by-contract to Go by synchronizing the code with the documentation. :star:51
* [gonerics](http://github.com/bouk/gonerics) - Idiomatic Generics in Go. :star:111
* [gotests](https://github.com/cweill/gotests) - Generate Go tests from your source code. :star:2203
* [gounit](https://github.com/hexdigest/gounit) - Generate Go tests using your own templates. :star:29
* [hasgo](https://github.com/DylanMeeus/hasgo) - Generate Haskell inspired functions for your slices. :star:12
* [re2dfa](https://github.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code. :star:168
* [TOML-to-Go](https://xuri.me/toml-to-go) - Translates TOML into a Go type in the browser instantly.

## Go Tools

* [colorgo](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output. :star:98
* [depth](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports. :star:378
* [gb](https://getgb.io/) - An easy to use project based build tool for the Go programming language.
* [generator-go-lang](https://github.com/axelspringer/generator-go-lang) - A [Yeoman](http://yeoman.io) generator to get new Go projects started. :star:13
* [gilbert](https://go-gilbert.github.io) - Build system and task runner for Go projects.
* [go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format. :star:1988
* [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo. :star:37
* [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API. :star:3992
* [godbg](https://github.com/tylerwince/godbg) - Implementation of Rusts `dbg!` macro for quick and easy debugging during development. :star:156
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub. :star:3799
* [richgo](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations. :star:389
* [rts](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses. :star:184

## Software Packages

*Software written in Go.*

### DevOps Tools

* [aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool.
* [aurora](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console. :star:403
* [awsenv](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile. :star:21
* [Blast](https://github.com/dave/blast) - A simple tool for API load testing and batch jobs. :star:167
* [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool. :star:1751
* [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework. :star:2852
* [DepCharge](https://github.com/centerorbit/depcharge) - Helps orchestrating the execution of commands across the many dependencies in larger projects. :star:9
* [dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart). :star:216
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI. :star:24
* [drone-scp](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI. :star:55
* [Dropship](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn. :star:46
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`. :star:100
* [fac](https://github.com/mkchoi212/fac) - Command-line user interface to fix git merge conflicts. :star:1614
* [gaia](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language. :star:3743
* [Gitea](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven. :star:15323
* [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance.
* [go-furnace](https://github.com/go-furnace/go-furnace) - Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean. :star:67
* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update. :star:671
* [gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go. :star:175
* [godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application. :star:219
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages. :star:312
* [govvv](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries. :star:388
* [gox](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool. :star:3364
* [goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging. :star:1623
* [grapes](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease. :star:135
* [GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions. :star:4477
* [Hey](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application. :star:6325
* [kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler. :star:1358
* [kcli](https://github.com/cswank/kcli) - Command line tool for inspecting kafka topics/partitions/messages. :star:78
* [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google. :star:56336
* [lstags](https://github.com/ivanilves/lstags) - Tool and API to sync Docker images across different registries. :star:219
* [lwc](https://github.com/timdp/lwc) - A live-updating version of the UNIX wc command. :star:8
* [manssh](https://github.com/xwjdsh/manssh) - manssh is a command line tool for managing your ssh alias config easily. :star:205
* [Moby](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems. :star:54449
* [Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data. :star:266
* [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB. :star:164
* [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. :star:9245
* [Pewpew](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester. :star:203
* [Pomerium](https://github.com/pomerium/pomerium) - Pomerium is an identity-aware access proxy. :star:513
* [Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies. :star:30
* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3. :star:998
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker). :star:539
* [script](https://github.com/bitfield/script) - Making it easy to write shell-like scripts in Go for DevOps and system administration tasks. :star:922
* [sg](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response. :star:5
* [skm](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily! :star:550
* [StatusOK](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected. :star:1162
* [traefik](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends. :star:23772
* [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000! :star:12202
* [webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server. :star:4093
* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
* [winrm-cli](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines. :star:67

### Other Software

* [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets. :star:1417
* [boxed](https://github.com/tejo/boxed) - Dropbox based blog engine. :star:72
* [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go. :star:193
* [Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications. :star:1787
* [Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections. :star:6178
* [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul. :star:6418
* [DDNS](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend. :star:98
* [Docker](http://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* [Documize](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools. :star:829
* [drive](https://github.com/odeke-em/drive) - Google Drive client for the commandline. :star:4965
* [Duplicacy](https://github.com/gilbertchen/duplicacy) - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication. :star:2692
* [gfile](https://github.com/Antonito/gfile) - Securely transfer files between two computers, without any third party, over WebRTC. :star:501
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH. :star:877
* [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client. :star:375
* [GoBoy](https://github.com/Humpheh/goboy) - Nintendo Game Boy Color emulator written in Go. :star:2105
* [gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go. :star:343
* [GoDNS](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go. :star:433
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at function list. :star:12
* [GoLand](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
* [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time. :star:11368
* [hugo](http://gohugo.io/) - Fast and Modern Static Website Engine.
* [ide](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go. :star:251
* [ipe](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO. :star:277
* [joincap](https://github.com/assafmo/joincap) - Command-line utility for merging multiple pcap files together. :star:122
* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [Leaps](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms. :star:640
* [lgo](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility. :star:1805
* [limetext](http://limetext.org/) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE. :star:5499
* [mockingjay](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests. :star:415
* [myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go. :star:2200
* [naclpipe](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go. :star:20
* [nes](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go. :star:4127
* [orange-cat](https://github.com/noraesae/orange-cat) - Markdown previewer written in Go. :star:178
* [Orbit](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates. :star:128
* [peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. :star:611
* [Pipe](https://github.com/b3log/pipe) - A small and beautiful blogging platform. :star:2967
* [restic](https://github.com/restic/restic) - De-duplicating backup program. :star:7495
* [rkt](https://github.com/coreos/rkt) - App Container runtime that integrates with init systems, is compatible with other container formats like Docker, and supports alternative execution engines like KVM. :star:8748
* [scc](https://github.com/boyter/scc) - Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates. :star:772
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek. :star:8258
* [shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control). :star:415
* [snap](https://github.com/intelsdi-x/snap) - Powerful telemetry framework. :star:1803
* [Snitch](https://github.com/lucasgomide/snitch) - Simple way to notify your team and many tools when someone has deployed any application via Tsuru. :star:15
* [Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers. :star:1990
* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* [term-quiz](https://github.com/crazcalm/term-quiz) - Quizzes for your terminal. :star:17
* [toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests. :star:3946
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [vFlow](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector. :star:600
* [wellington](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass). :star:290

# Resources

*Where to discover new Go libraries.*

## Benchmarks

* [autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions. :star:89
* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results. :star:19
* [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches. :star:122
* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison. :star:1261
* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark. :star:1004
* [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods. :star:866
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language. :star:52
* [golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks) - Tiny collection of Go micro benchmarks. The intent is to compare some language features to others. :star:17
* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities. :star:49
* [gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs. :star:93
* [kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark. :star:14
* [skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark. :star:915
* [speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language. :star:172

## Conferences

* [Capital Go](http://www.capitalgolang.com) - Washington, D.C., USA.
* [dotGo](http://www.dotgo.eu) - Paris, France.
* [GoCon](http://gocon.connpass.com/) - Tokyo, Japan.
* [GoDays](https://www.godays.io/) - Berlin, Germany.
* [GoLab](http://golab.io/) - Florence, Italy.
* [GolangUK](http://golanguk.com/) - London, UK.
* [GopherChina](http://gopherchina.org) - Shanghai, China.
* [GopherCon](http://www.gophercon.com/) - Denver, USA.
* [GopherCon Australia](https://gophercon.com.au/) - Sydney, Australia.
* [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, BR.
* [GopherCon Europe](https://gophercon.is/) - Reykjavik, Iceland.
* [GopherCon India](https://www.gophercon.in/) - Pune, India.
* [GopherCon Israel](https://www.gophercon.org.il/) - Tel Aviv, Israel.
* [GopherCon Russia](https://www.gophercon-russia.ru) - Moscow, Russia.
* [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore.
* [GopherCon Vietnam](https://gophercon.vn/) - Ho Chi Minh City, Vietnam.
* [GothamGo](http://gothamgo.com/) - New York City, USA.
* [GoWayFest](https://goway.io/) - Minsk, Belarus.

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details.
* [Go Bootcamp](http://golangbootcamp.com)
* [Go Succinctly](https://github.com/thedevsir/gosuccinctly) - in Persian. :star:10
* [GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books. :star:6805
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example) :star:5454
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/) :star:2318
* [Writing A Compiler In Go](https://compilerbook.com)
* [Writing An Interpreter In Go](https://interpreterbook.com)

## Gophers

* [Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) - Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster. :star:1543
* [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) - Go gopher Vector Data [.ai, .svg]. :star:31
* [gopher-logos](https://github.com/GolangUA/gopher-logos) - adorable gopher logos. :star:65
* [gopher-stickers](https://github.com/tenntenn/gopher-stickers) :star:440
* [gopher-vector](https://github.com/golang-samples/gopher-vector) :star:341
* [gophericons](https://github.com/shalakhin/gophericons) :star:559
* [gopherize.me](https://github.com/matryer/gopherize.me) - Gopherize yourself. :star:313
* [gophers](https://github.com/ashleymcnamara/gophers) - Gopher artworks by Ashley McNamara. :star:1856
* [gophers](https://github.com/egonelbre/gophers) - Free gophers. :star:1599
* [gophers](https://github.com/rogeralsing/gophers) - random gopher graphics. :star:50
* [gophers](https://github.com/sillecelik/go-gopher) - Gopher amigurumi toy pattern. :star:40

## Meetups

* [Basel Go Meetup](https://www.meetup.com/Basel-Go-Meetup/)
* [Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/)
* [Canberra Gophers](https://www.meetup.com/Canberra-Gophers/)
* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
* [GoJakarta](https://www.meetup.com/GoJakarta/)
* [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
* [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
* [Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/)
* [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
* [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
* [Golang Boston](https://www.meetup.com/bostongo/)
* [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
* [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
* [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
* [Golang Gurgaon, India](https://www.meetup.com/Gurgaon-Go-Meetup/)
* [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/)
* [Golang Korea](https://www.meetup.com/GDG-Golang-Korea/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
* [Golang Pune](https://www.meetup.com/Golang-Pune/)
* [Golang Singapore](https://www.meetup.com/golangsg/)
* [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
* [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
* [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
* [Golang Taipei](https://www.meetup.com/golang-taipei-meetup/)
* [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
* [Golang Казань](https://www.meetup.com/GolangKazan/)
* [Golang Москва](https://www.meetup.com/Golang-Moscow/)
* [Golang Питер](https://www.meetup.com/Golang-Peter/)
* [GoSF - San Francisco, CA](https://www.meetup.com/golangsf)
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*Add the group of your city/country here (send **PR**)*

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangch](https://twitter.com/golangch)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

## Websites

* [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers. :star:14560
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists. :star:24654
* [CodinGame](https://www.codingame.com/) - Learn Go by solving interactive tasks using small games as practical examples.
* [Go Blog](http://blog.golang.org) - The official Go blog.
* [Go Challenge](http://golang-challenge.org/) - Learn Go by solving problems and getting feedback from Go experts.
* [Go Community on Hashnode](https://hashnode.com/n/go) - Community of Gophers on Hashnode.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki. :star:61800
* [Go Report Card](https://goreportcard.com) - A report card for your Go package.
* [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go. :star:36
* [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
* [Golang Flow](https://golangflow.io) - Post Updates, News, Packages and more.
* [Golang News](https://golangnews.com) - Links and news about Go programming.
* [golang-graphics](https://github.com/mholt/golang-graphics) - Collection of Go images, graphics, and art. :star:141
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
* [Gophercises](https://gophercises.com/) - Free coding exercises for budding gophers.
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [justforfunc](https://www.youtube.com/c/justforfunc) - Youtube channel dedicated to Go programming language tips and tricks, hosted by  Francesc Campoy [@francesc](https://twitter.com/francesc).
* [r/Golang](https://www.reddit.com/r/golang) - News about Go.
* [studygolang](https://studygolang.com) - The community of studygolang in China.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.
* [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

### Tutorials

* [50 Shades of Go](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Traps, Gotchas, and Common Mistakes for New Golang Devs.
* [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - Building a Golang site for e-commerce (demo included).
* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go.
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang. :star:31559
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - How to cache slow database queries.
* [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - How to cancel MySQL queries.
* [Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) - A little e-book on Ethereum Development with Go. :star:454
* [Games With Go](http://gameswithgo.org/) - A video series teaching programming and game development.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card. :star:4042
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Go Playground for iOS](https://itunes.apple.com/us/app/go-playground/id1437518275?ls=1&mt=8) - Interactively edit & play Go snippets on your mobile device.
* [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
* [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) - Examples of Golang compared to Node.js for learning. :star:694
* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development. :star:4550
* [Learning Golang - From zero to hero](https://milapneupane.com.np/2019/07/06/learning-golang-from-zero-to-hero/) - Getting started with golang for beginner.
* [package main](https://www.youtube.com/packagemain) - YouTube channel about Programming in Go.
* [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
* [Working with Go](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers. :star:1132
* [Your basic Go](http://yourbasic.org/golang) - Huge collection of tutorials and how to's.


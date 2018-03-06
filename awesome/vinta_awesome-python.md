# Information comes from [vinta/awesome-python](https://github.com/vinta/awesome-python)
# Awesome Python [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Python frameworks, libraries, software and resources.

Inspired by [awesome-php](https://github.com/ziadoz/awesome-php).

- [Awesome Python](#awesome-python)
    - [Admin Panels](#admin-panels)
    - [Algorithms and Design Patterns](#algorithms-and-design-patterns)
    - [Anti-spam](#anti-spam)
    - [Asset Management](#asset-management)
    - [Audio](#audio)
    - [Authentication](#authentication)
    - [Build Tools](#build-tools)
    - [Built-in Classes Enhancement](#built-in-classes-enhancement)
    - [Caching](#caching)
    - [ChatOps Tools](#chatops-tools)
    - [CMS](#cms)
    - [Code Analysis](#code-analysis)
    - [Command-line Tools](#command-line-tools)
    - [Compatibility](#compatibility)
    - [Computer Vision](#computer-vision)
    - [Concurrency and Parallelism](#concurrency-and-parallelism)
    - [Configuration](#configuration)
    - [Cryptography](#cryptography)
    - [Data Analysis](#data-analysis)
    - [Data Validation](#data-validation)
    - [Data Visualization](#data-visualization)
    - [Database Drivers](#database-drivers)
    - [Database](#database)
    - [Date and Time](#date-and-time)
    - [Debugging Tools](#debugging-tools)
    - [Deep Learning](#deep-learning)
    - [DevOps Tools](#devops-tools)
    - [Distribution](#distribution)
    - [Documentation](#documentation)
    - [Downloader](#downloader)
    - [E-commerce](#e-commerce)
    - [Editor Plugins and IDEs](#editor-plugins-and-ides)
    - [Email](#email)
    - [Environment Management](#environment-management)
    - [Files](#files)
    - [Foreign Function Interface](#foreign-function-interface)
    - [Forms](#forms)
    - [Functional Programming](#functional-programming)
    - [Game Development](#game-development)
    - [Geolocation](#geolocation)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [HTML Manipulation](#html-manipulation)
    - [HTTP](#http)
    - [Image Processing](#image-processing)
    - [Implementations](#implementations)
    - [Interactive Interpreter](#interactive-interpreter)
    - [Internationalization](#internationalization)
    - [Job Scheduler](#job-scheduler)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [MapReduce](#mapreduce)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Network Virtualization](#network-virtualization)
    - [Networking](#networking)
    - [News Feed](#news-feed)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Package Repositories](#package-repositories)
    - [Permissions](#permissions)
    - [Processes](#processes)
    - [Queue](#queue)
    - [Recommender Systems](#recommender-systems)
    - [RESTful API](#restful-api)
    - [RPC Servers](#rpc-servers)
    - [Science](#science)
    - [Search](#search)
    - [Serialization](#serialization)
    - [Serverless Frameworks](#serverless-frameworks)
    - [Specific Formats Processing](#specific-formats-processing)
    - [Static Site Generator](#static-site-generator)
    - [Tagging](#tagging)
    - [Template Engine](#template-engine)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [URL Manipulation](#url-manipulation)
    - [Video](#video)
    - [Web Content Extracting](#web-content-extracting)
    - [Web Crawling](#web-crawling)
    - [Web Frameworks](#web-frameworks)
    - [WebSocket](#websocket)
    - [WSGI Servers](#wsgi-servers)
- [Services](#services)
    - [Code Quality](#code-quality)
    - [Continuous Integration](#continuous-integration)
- [Resources](#resources)
    - [Podcasts](#podcasts)
    - [Twitter](#twitter)
    - [Websites](#websites)
    - [Weekly](#weekly)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

- - -

## Admin Panels

*Libraries for administrative interfaces.*

* [Ajenti](https://github.com/ajenti/ajenti) - The admin panel your servers deserve. :star:5076
* [django-suit](http://djangosuit.com/) - Alternative Django Admin-Interface (free only for Non-commercial use).
* [django-xadmin](https://github.com/sshwsfc/xadmin) - Drop-in replacement of Django admin comes with lots of goodies. :star:2685
* [flask-admin](https://github.com/flask-admin/flask-admin) - Simple and extensible administrative interface framework for Flask. :star:2736
* [flower](https://github.com/mher/flower) - Real-time monitor and web admin for Celery. :star:2777
* [Grappelli](http://grappelliproject.com) - A jazzy skin for the Django Admin-Interface.
* [Wooey](https://github.com/wooey/wooey) - A Django app which creates automatic web UIs for Python scripts. :star:998

## Algorithms and Design Patterns

*Python implementation of algorithms and design patterns.*

* [algorithms](https://github.com/nryoung/algorithms) - A module of algorithms for Python. :star:2757
* [PyPattyrn](https://github.com/tylerlaberge/PyPattyrn) - A simple yet effective library for implementing common design patterns. :star:451
* [python-patterns](https://github.com/faif/python-patterns) - A collection of design patterns in Python. :star:14453
* [sortedcontainers](http://www.grantjenks.com/docs/sortedcontainers/) - Fast, pure-Python implementation of SortedList, SortedDict, and SortedSet types.

## Anti-spam

*Libraries for fighting spam.*

* [django-simple-captcha](https://github.com/mbi/django-simple-captcha) - A simple and highly customizable Django app to add captcha images to any Django form. :star:681
* [django-simple-spam-blocker](https://github.com/moqada/django-simple-spam-blocker) - Simple spam blocker for Django. :star:17

## Asset Management

*Tools for managing, compressing and minifying website assets.*

* [django-compressor](https://github.com/django-compressor/django-compressor) - Compresses linked and inline JavaScript or CSS into a single cached file. :star:2000
* [django-pipeline](https://github.com/jazzband/django-pipeline) - An asset packaging library for Django. :star:1225
* [django-storages](https://github.com/jschneier/django-storages) - A collection of custom storage back ends for Django. :star:826
* [fanstatic](http://www.fanstatic.org/en/latest/) - Packages, optimizes, and serves static file dependencies as Python packages.
* [fileconveyor](http://wimleers.com/fileconveyor) - A daemon to detect and sync files to CDNs, S3 and FTP.
* [flask-assets](https://github.com/miracle2k/flask-assets) - Helps you integrate webassets into your Flask app. :star:340
* [jinja-assets-compressor](https://github.com/jaysonsantos/jinja-assets-compressor) - A Jinja extension to compile and compress your assets. :star:75
* [webassets](https://github.com/miracle2k/webassets) - Bundles, optimizes, and manages unique cache-busting URLs for static resources. :star:822

## Audio

*Libraries for manipulating audio.*

* [audiolazy](https://github.com/danilobellini/audiolazy) - Expressive Digital Signal Processing (DSP) package for Python. :star:376
* [audioread](https://github.com/beetbox/audioread) - Cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding. :star:184
* [beets](http://beets.io/) - A music library manager and [MusicBrainz](https://musicbrainz.org/) tagger.
* [dejavu](https://github.com/worldveil/dejavu) - Audio fingerprinting and recognition. :star:3648
* [django-elastic-transcoder](https://github.com/StreetVoice/django-elastic-transcoder) - Django + [Amazon Elastic Transcoder](https://aws.amazon.com/elastictranscoder/). :star:47
* [eyeD3](http://eyed3.nicfit.net/) - A tool for working with audio files, specifically MP3 files containing ID3 metadata.
* [id3reader](https://nedbatchelder.com/code/modules/id3reader.py) - A Python module for reading MP3 meta data.
* [m3u8](https://github.com/globocom/m3u8) - A module for parsing m3u8 file. :star:359
* [mingus](http://bspaans.github.io/python-mingus/) - An advanced music theory and notation package with MIDI file and playback support.
* [mutagen](https://github.com/quodlibet/mutagen) - A Python module to handle audio metadata. :star:262
* [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) - Python Audio Analysis Library: Feature Extraction, Classification, Segmentation and Applications :star:1317
* [pydub](https://github.com/jiaaro/pydub) - Manipulate audio with a simple and easy high level interface. :star:2388
* [pyechonest](https://github.com/echonest/pyechonest) - Python client for the [Echo Nest](http://developer.echonest.com/) API. :star:609
* [talkbox](http://scikits.appspot.com/talkbox) - A Python library for speech/signal processing.
* [TimeSide](https://github.com/Parisson/TimeSide) - Open web audio processing framework. :star:219
* [tinytag](https://github.com/devsnd/tinytag) - A library for reading music meta data of MP3, OGG, FLAC and Wave files. :star:269

## Authentication

*Libraries for implementing authentications schemes.*

* OAuth
    * [Authomatic](https://github.com/authomatic/authomatic) - Simple but powerful framework agnostic authentication/authorization client. :star:848
    * [django-allauth](https://github.com/pennersr/django-allauth) - Authentication app for Django that "just works." :star:3624
    * [django-oauth-toolkit](https://github.com/evonove/django-oauth-toolkit) - OAuth 2 goodies for Django. :star:1207
    * [Flask-OAuthlib](https://github.com/lepture/flask-oauthlib) - OAuth 1.0/a, 2.0 implementation of client and provider for Flask. :star:1193
    * [OAuthLib](https://github.com/idan/oauthlib) - A generic and thorough implementation of the OAuth request-signing logic. :star:1550
    * [python-oauth2](https://github.com/joestump/python-oauth2) - A fully tested, abstract interface to creating OAuth clients and servers. :star:2707
    * [python-social-auth](https://github.com/omab/python-social-auth) - An easy-to-setup social authentication mechanism. :star:2729
    * [rauth](https://github.com/litl/rauth) - A Python library for OAuth 1.0/a, 2.0, and Ofly. :star:1499
    * [sanction](https://github.com/demianbrecht/sanction) - A dead simple OAuth2 client implementation. :star:169
* Others
    * [jose](https://github.com/demonware/jose) - JavaScript Object Signing and Encryption draft implementation. :star:69
    * [PyJWT](https://github.com/jpadilla/pyjwt) - Implementation of the JSON Web Token draft 01. :star:1786
    * [python-jws](https://github.com/brianloveswords/python-jws) - Implementation of JSON Web Signatures draft 02. :star:52
    * [python-jwt](https://github.com/davedoesdev/python-jwt) - Module for generating and verifying JSON Web Tokens. :star:135

## Build Tools

*Compile software from source code.*

* [BitBake](http://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html) - A make-like build tool for embedded Linux.
* [buildout](http://www.buildout.org/en/latest/) - A build system for creating, assembling and deploying applications from multiple parts.
* [PlatformIO](https://github.com/platformio/platformio-core) - A console tool to build code with different development platforms. :star:2254
* [PyBuilder](https://github.com/pybuilder/pybuilder) - A continuous build tool written in pure Python. :star:989
* [SCons](http://www.scons.org/) - A software construction tool.

## Built-in Classes Enhancement

*Libraries for enhancing Python built-in classes.*

* [attrs](https://github.com/python-attrs/attrs) - Replacement for `__init__`, `__eq__`, `__repr__`, etc. boilerplate in class definitions. :star:1396
* [bidict](https://github.com/jab/bidict) - Efficient, Pythonic bidirectional map data structures and related functionality.. :star:194
* [Box](https://github.com/cdgriffith/Box) - Python dictionaries with advanced dot notation access. :star:949
* [dotted](https://github.com/carlosescri/DottedDict) - A library that provides a method of accessing lists and dicts with a dotted path notation. :star:17

## CMS

*Content Management Systems.*

* [django-cms](https://www.django-cms.org/en/) - An Open source enterprise CMS based on the Django.
* [djedi-cms](http://djedi-cms.org/) - A lightweight but yet powerful Django CMS with plugins, inline editing and performance in mind.
* [FeinCMS](http://www.feincms.org/) - One of the most advanced Content Management Systems built on Django.
* [Kotti](http://kotti.pylonsproject.org/) - A high-level, Pythonic web application framework built on Pyramid.
* [Mezzanine](http://mezzanine.jupo.org/) - A powerful, consistent, and flexible content management platform.
* [Opps](http://opps.github.io/opps/) - A Django-based CMS for magazines, newspapers websites and portals with high-traffic.
* [Plone](https://plone.org/) - A CMS built on top of the open source application server Zope.
* [Quokka](http://quokkaproject.org/) - Flexible, extensible, small CMS powered by Flask and MongoDB.
* [Wagtail](https://wagtail.io/) - A Django content management system.
* [Widgy](https://wid.gy/) - Last CMS framework, based on Django.

## Caching

*Libraries for caching data.*

* [Beaker](https://github.com/bbangert/beaker) - A library for caching and sessions for use with web applications and stand-alone Python scripts and applications. :star:350
* [DiskCache](http://www.grantjenks.com/docs/diskcache/) - SQLite and file backed cache backend with faster lookups than memcached and redis.
* [django-cache-machine](https://github.com/django-cache-machine/django-cache-machine) - Automatic caching and invalidation for Django models. :star:688
* [django-cacheops](https://github.com/Suor/django-cacheops) - A slick ORM cache with automatic granular event-driven invalidation. :star:834
* [django-viewlet](https://github.com/5monkeys/django-viewlet) - Render template parts with extended cache control. :star:57
* [dogpile.cache](http://dogpilecache.readthedocs.io/en/latest/) - dogpile.cache is next generation replacement for Beaker made by same authors.
* [HermesCache](https://pypi.python.org/pypi/HermesCache) - Python caching library with tag-based invalidation and dogpile effect prevention.
* [johnny-cache](https://github.com/jmoiron/johnny-cache) - A caching framework for django applications. :star:276
* [pylibmc](https://github.com/lericson/pylibmc) - A Python wrapper around the [libmemcached](http://libmemcached.org/libMemcached.html) interface. :star:375

## ChatOps Tools

*Libraries for chatbot development.*

* [Errbot](http://errbot.io/en/latest/) - The easiest and most popular chatbot to implement ChatOps.

## Code Analysis

*Tools of static analysis, linters and code quality checkers. See: [awesome-static-analysis](https://github.com/mre/awesome-static-analysis).*

* Code Analysis
    * [flake8](https://pypi.python.org/pypi/flake8) - A wrapper around pycodestyle, pyflakes and McCabe.
    * [coala](http://coala.io/) - Language independent and easily extendable code analysis application.
    * [code2flow](https://github.com/scottrogowski/code2flow) - Turn your Python and JavaScript code into DOT flowcharts. :star:467
    * [prospector](https://github.com/landscapeio/prospector) - A tool to analyse Python code. :star:914
    * [pycallgraph](https://github.com/gak/pycallgraph) - A library that visualises the flow (call graph) of your Python application. :star:1019
    * [pylama](https://github.com/klen/pylama) - A code audit tool for Python and JavaScript. :star:406
    * [pylint](https://www.pylint.org/) - A fully customizable source code analyzer.
* Static Type Checkers
    * [mypy](http://mypy-lang.org/) - Check variable types during compile time.
* Static Type Annotations Generators
    * [MonkeyType](https://github.com/Instagram/MonkeyType) - A system for Python that generates static type annotations by collecting runtime types :star:1427

## Command-line Tools

*Libraries for building command-line application.*

* Command-line Application Development
    * [asciimatics](https://github.com/peterbrittain/asciimatics) - Cross-platform, full-screen terminal package (i.e.  mouse/keyboard input and coloured, positioned text output) complete with high-level API for complex animations and special effects. :star:928
    * [cement](http://builtoncement.com/) - CLI Application Framework for Python.
    * [click](http://click.pocoo.org/dev/) - A package for creating beautiful command line interfaces in a composable way.
    * [cliff](https://docs.openstack.org/developer/cliff/) - A framework for creating command-line programs with multi-level commands.
    * [clint](https://github.com/kennethreitz/clint) - Python Command-line Application Tools. :star:2383
    * [colorama](https://pypi.python.org/pypi/colorama) - Cross-platform colored terminal text.
    * [docopt](http://docopt.org/) - Pythonic command line arguments parser.
    * [Gooey](https://github.com/chriskiehl/Gooey) - Turn command line programs into a full GUI application with one line :star:5625
    * [Python-Fire](https://github.com/google/python-fire) - A library for creating command line interfaces from absolutely any Python object. :star:8712
    * [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) - A Library for building powerful interactive command lines. :star:4179
* Productivity Tools
    * [aws-cli](https://github.com/aws/aws-cli) - A universal command-line interface for Amazon Web Services. :star:6106
    * [bashplotlib](https://github.com/glamp/bashplotlib) - Making basic plots in the terminal. :star:795
    * [caniusepython3](https://github.com/brettcannon/caniusepython3) - Determine what projects are blocking you from porting to Python 3. :star:333
    * [cookiecutter](https://github.com/audreyr/cookiecutter) - A command-line utility that creates projects from cookiecutters (project templates). :star:6523
    * [doitlive](https://github.com/sloria/doitlive) - A tool for live presentations in the terminal. :star:2050
    * [howdoi](https://github.com/gleitz/howdoi) - Instant coding answers via the command line. :star:6171
    * [httpie](https://github.com/jakubroztocil/httpie) - A command line HTTP client, a user-friendly cURL replacement. :star:34289
    * [mycli](https://github.com/dbcli/mycli) - A Terminal Client for MySQL with AutoCompletion and Syntax Highlighting. :star:5386
    * [PathPicker](https://github.com/facebook/PathPicker) - Select files out of bash output. :star:3701
    * [percol](https://github.com/mooz/percol) - Adds flavor of interactive selection to the traditional pipe concept on UNIX. :star:2486
    * [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting. :star:6529
    * [SAWS](https://github.com/donnemartin/saws) - A Supercharged AWS CLI. :star:3530
    * [thefuck](https://github.com/nvbn/thefuck) - Correcting your previous console command. :star:34055
    * [try](https://github.com/timofurrer/try) - A dead simple CLI to try out python packages - It's never been easier. :star:414

## Compatibility

*Libraries for migrating from Python 2 to 3.*

* [Python-Future](http://python-future.org/index.html) - The missing compatibility layer between Python 2 and Python 3.
* [Python-Modernize](https://github.com/mitsuhiko/python-modernize) - Modernizes Python code for eventual Python 3 migration. :star:482
* [Six](https://pypi.python.org/pypi/six) - Python 2 and 3 compatibility utilities.

## Computer Vision

*Libraries for computer vision.*

* [OpenCV](http://opencv.org/) - Open Source Computer Vision Library.
* [pyocr](https://github.com/openpaperwork/pyocr) - A wrapper for Tesseract and Cuneiform. :star:807
* [pytesseract](https://github.com/madmaze/pytesseract) - Another wrapper for [Google Tesseract OCR](https://github.com/tesseract-ocr). :star:1249
* [SimpleCV](http://simplecv.org/) - An open source framework for building computer vision applications.

## Concurrency and Parallelism

*Libraries for concurrent and parallel execution.*

* [eventlet](http://eventlet.net/) - Asynchronous framework with WSGI support.
* [gevent](http://www.gevent.org/) - A coroutine-based Python networking library that uses [greenlet](https://github.com/python-greenlet/greenlet).
* [multiprocessing](https://docs.python.org/2/library/multiprocessing.html) - (Python standard library) Process-based "threading" interface.
* [threading](https://docs.python.org/2/library/threading.html) - (Python standard library) Higher-level threading interface.
* [Tomorrow](https://github.com/madisonmay/Tomorrow) - Magic decorator syntax for asynchronous code. :star:1341
* [uvloop](https://github.com/MagicStack/uvloop) - Ultra fast implementation of asyncio event loop on top of libuv. :star:4466

## Configuration

*Libraries for storing and parsing configuration options.*

* [config](https://www.red-dove.com/config-doc/) - Hierarchical config from the author of [logging](https://docs.python.org/2/library/logging.html).
* [ConfigObj](http://www.voidspace.org.uk/python/configobj.html) - INI file parser with validation.
* [ConfigParser](https://docs.python.org/2/library/configparser.html) - (Python standard library) INI file parser.
* [profig](http://profig.readthedocs.org/en/default/) - Config from multiple formats with value conversion.
* [python-decouple](https://github.com/henriquebastos/python-decouple) - Strict separation of settings from code. :star:589

## Cryptography

* [cryptography](https://cryptography.io/en/latest/) - A package designed to expose cryptographic primitives and recipes to Python developers.
* [hashids](https://github.com/davidaurelio/hashids-python) - Implementation of [hashids](http://hashids.org) in Python. :star:711
* [Paramiko](http://www.paramiko.org/) - A Python (2.6+, 3.3+) implementation of the SSHv2 protocol, providing both client and server functionality.
* [Passlib](https://pythonhosted.org/passlib/) - Secure password storage/hashing library, very high level.
* [PyNacl](https://github.com/pyca/pynacl) - Python binding to the Networking and Cryptography (NaCl) library. :star:442

## Data Analysis

*Libraries for data analyzing.*

* [Blaze](https://github.com/blaze/blaze) - NumPy and Pandas interface to Big Data. :star:2297
* [Open Mining](https://github.com/mining/mining) - Business Intelligence (BI) in Pandas interface. :star:855
* [Orange](https://orange.biolab.si/) - Data mining, data visualization, analysis and machine learning through visual programming or scripts.
* [Pandas](http://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.

## Data Validation

*Libraries for validating data. Used for forms in many cases.*

* [Cerberus](https://github.com/pyeve/cerberus) - A lightweight and extensible data validation library. :star:1177
* [colander](https://docs.pylonsproject.org/projects/colander/en/latest/) - Validating and deserializing data obtained via XML, JSON, an HTML form post.
* [jsonschema](https://github.com/Julian/jsonschema) - An implementation of [JSON Schema](http://json-schema.org/) for Python. :star:1520
* [schema](https://github.com/keleshev/schema) - A library for validating Python data structures. :star:1324
* [Schematics](https://github.com/schematics/schematics) - Data Structure Validation. :star:1910
* [valideer](https://github.com/podio/valideer) - Lightweight extensible data validation and adaptation library. :star:189
* [voluptuous](https://github.com/alecthomas/voluptuous) - A Python data validation library. :star:1060

## Data Visualization

*Libraries for visualizing data. See: [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization).*

* [Altair](https://github.com/altair-viz/altair) - Declarative statistical visualization library for Python. :star:1799
* [Bokeh](https://github.com/bokeh/bokeh) - Interactive Web Plotting for Python. :star:7270
* [bqplot](https://github.com/bloomberg/bqplot) - Interactive Plotting Library for the Jupyter Notebook :star:1764
* [ggplot](https://github.com/yhat/ggpy) - Same API as ggplot2 for R. :star:3237
* [Matplotlib](http://matplotlib.org/) - A Python 2D plotting library.
* [Pygal](http://www.pygal.org/en/latest/) - A Python SVG Charts Creator.
* [PyGraphviz](https://pypi.python.org/pypi/pygraphviz) - Python interface to [Graphviz](http://www.graphviz.org/).
* [PyQtGraph](http://www.pyqtgraph.org/) - Interactive and realtime 2D/3D/Image plotting and science/engineering widgets.
* [Seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization using Matplotlib. :star:4640
* [VisPy](https://github.com/vispy/vispy) - High-performance scientific visualization based on OpenGL. :star:1562

## Database

*Databases implemented in Python.*

* [pickleDB](https://pythonhosted.org/pickleDB/) - A simple and lightweight key-value store for Python.
* [PipelineDB](https://www.pipelinedb.com/) - The Streaming SQL Database.
* [TinyDB](https://github.com/msiemens/tinydb) - A tiny, document-oriented database. :star:2076
* [ZODB](http://www.zodb.org/en/latest/) - A native object database for Python. A key-value and object graph database.


## Database Drivers

*Libraries for connecting and operating databases.*

* MySQL - [awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/)
    * [mysqlclient](https://github.com/PyMySQL/mysqlclient-python) - MySQL connector with Python 3 support ([mysql-python](https://sourceforge.net/projects/mysql-python/) fork). :star:973
    * [oursql](https://pythonhosted.org/oursql/) - A better MySQL connector with support for native prepared statements and BLOBs.
    * [PyMySQL](https://github.com/PyMySQL/PyMySQL) - A pure Python MySQL driver compatible to mysql-python. :star:3734
* PostgreSQL - [awesome-postgres](https://github.com/dhamaniasad/awesome-postgres)
    * [psycopg2](http://initd.org/psycopg/) - The most popular PostgreSQL adapter for Python.
    * [queries](https://github.com/gmr/queries) - A wrapper of the psycopg2 library for interacting with PostgreSQL. :star:183
    * [txpostgres](https://github.com/wulczer/txpostgres) - Twisted based asynchronous driver for PostgreSQL. :star:97
* Other Relational Databases
    * [apsw](http://rogerbinns.github.io/apsw/) - Another Python SQLite wrapper.
    * [dataset](https://github.com/pudo/dataset) - Store Python dicts in a database - works with SQLite, MySQL, and PostgreSQL. :star:3022
    * [pymssql](http://www.pymssql.org/en/latest/) - A simple database interface to Microsoft SQL Server.
* NoSQL Databases
    * [cassandra-python-driver](https://github.com/datastax/python-driver) - Python driver for Cassandra. :star:822
    * [HappyBase](https://github.com/wbolster/happybase) - A developer-friendly library for Apache HBase. :star:377
    * [Plyvel](https://github.com/wbolster/plyvel) - A fast and feature-rich Python interface to LevelDB. :star:182
    * [py2neo](http://py2neo.org/2.0/) - Python wrapper client for Neo4j's restful interface.
    * [pycassa](https://github.com/pycassa/pycassa) - Python Thrift driver for Cassandra. :star:501
    * [PyMongo](https://docs.mongodb.com/ecosystem/drivers/python/) - The official Python client for MongoDB.
    * [redis-py](https://github.com/andymccurdy/redis-py) - The Redis Python Client. :star:5853
    * [telephus](https://github.com/driftx/Telephus) - Twisted based client for Cassandra. :star:93
    * [txRedis](https://github.com/deldotdr/txRedis) - Twisted based client for Redis. :star:115

## Date and Time

*Libraries for working with dates and times.*

* [Chronyk](https://github.com/KoffeinFlummi/Chronyk) - A Python 3 library for parsing human-written times and dates. :star:246
* [dateutil](https://github.com/dateutil/dateutil) - Extensions to the standard Python [datetime](https://docs.python.org/2/library/datetime.html) module. :star:579
* [delorean](https://github.com/myusuf3/delorean/) - A library for clearing up the inconvenient truths that arise dealing with datetimes.
* [moment](https://github.com/zachwill/moment) - A Python library for dealing with dates/times. Inspired by [Moment.js](http://momentjs.com/). :star:474
* [Pendulum](https://github.com/sdispater/pendulum) - Python datetimes made easy. :star:2405
* [PyTime](https://github.com/shinux/PyTime) - A easy-use Python module which aims to operate date/time/datetime by string. :star:115
* [pytz](https://launchpad.net/pytz) - World timezone definitions, modern and historical. Brings the [tz database](https://en.wikipedia.org/wiki/Tz_database) into Python.
* [when.py](https://github.com/dirn/When.py) - Providing user-friendly functions to help perform common date and time actions. :star:172
* [maya](https://github.com/kennethreitz/maya) - Datetimes for Humans, Maya is mostly built around the headaches and use-cases around parsing datetime data from websites. :star:2126

## Debugging Tools

*Libraries for debugging code.*

* pdb-like Debugger
    * [ipdb](https://pypi.python.org/pypi/ipdb) - IPython-enabled [pdb](https://docs.python.org/3/library/pdb.html).
    * [pdb++](https://pypi.python.org/pypi/pdbpp/) - Another drop-in replacement for pdb.
    * [pudb](https://pypi.python.org/pypi/pudb) - A full-screen, console-based Python debugger.
    * [remote-pdb](https://github.com/ionelmc/python-remote-pdb) - Remote vanilla PDB (over TCP sockets). :star:71
    * [wdb](https://github.com/Kozea/wdb) - An improbable web debugger through WebSockets. :star:1254
* Profiler
    * [line_profiler](https://github.com/rkern/line_profiler) - Line-by-line profiling. :star:1907
    * [memory_profiler](https://github.com/fabianp/memory_profiler) - Monitor Memory usage of Python code. :star:1303
    * [Pyflame](https://github.com/uber/pyflame) - Attach this Ptracing Profiler to any processes running Python. Perfect for profiling production webservers. :star:1235
    * [profiling](https://github.com/what-studio/profiling) - An interactive Python profiler. :star:2654
    * [vprof](https://github.com/nvdv/vprof) - Visual Python profiler. :star:3108
* Others
    * [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar) - Display various debug information for Django. :star:4639
    * [django-devserver](https://github.com/dcramer/django-devserver) - A drop-in replacement for Django's runserver. :star:1228
    * [flask-debugtoolbar](https://github.com/mgood/flask-debugtoolbar) - A port of the django-debug-toolbar to flask. :star:623
    * [hunter](https://github.com/ionelmc/python-hunter) - Hunter is a flexible code tracing toolkit. :star:273
    * [lptrace](https://github.com/khamidou/lptrace) - [strace](http://man7.org/linux/man-pages/man1/strace.1.html) for Python programs. :star:587
    * [manhole](https://github.com/ionelmc/python-manhole) - Debug service that will accept unix domain socket connections and present the stacktraces for all threads and an interactive prompt. :star:170
    * [pyelftools](https://github.com/eliben/pyelftools) - Parsing and analyzing ELF files and DWARF debugging information. :star:593
    * [pyringe](https://github.com/google/pyringe) - Debugger capable of attaching to and injecting code into Python processes. :star:1441

## Deep Learning

*Frameworks for Neural Networks and Deep Learning. See: [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning).*

* [Caffe](https://github.com/BVLC/caffe) - A fast open framework for deep learning.. :star:23050
* [Keras](https://github.com/fchollet/keras) - A high-level neural networks library and capable of running on top of either TensorFlow or Theano. :star:26308
* [MXNet](https://github.com/dmlc/mxnet) - A deep learning framework designed for both efficiency and flexibility. :star:13258
* [Neupy](http://neupy.com/pages/home.html) - Running and testing different Artificial Neural Networks algorithms.
* [Pytorch](http://pytorch.org/) - Tensors and Dynamic neural networks in Python with strong GPU acceleration.
* [Serpent.AI](https://github.com/SerpentAI/SerpentAI) - Game agent framework. Use any video game as a deep learning sandbox. :star:3944
* [TensorFlow](https://github.com/tensorflow/tensorflow) - The most popular Deep Learning framework created by Google. :star:91356
* [Theano](https://github.com/Theano/Theano) - A library for fast numerical computation. :star:7952

## DevOps Tools

*Software and libraries for DevOps.*

* [Ansible](https://github.com/ansible/ansible) - A radically simple IT automation platform. :star:28796
* [Cloud-Init](http://cloudinit.readthedocs.io/en/latest/) - A multi-distribution package that handles early initialization of a cloud instance.
* [cuisine](https://github.com/sebastien/cuisine) - Chef-like functionality for Fabric. :star:1225
* [Docker Compose](https://docs.docker.com/compose/) - Fast, isolated development environments using [Docker](https://www.docker.com/).
* [Fabric](http://www.fabfile.org/) - A simple, Pythonic tool for remote execution and deployment.
* [Fabtools](https://github.com/fabtools/fabtools) - Tools for writing awesome Fabric files. :star:1137
* [honcho](https://github.com/nickstenning/honcho) - A Python clone of [Foreman](https://github.com/ddollar/foreman), for managing Procfile-based applications. :star:1082
* [OpenStack](https://www.openstack.org/) - Open source software for building private and public clouds.
* [pexpect](https://github.com/pexpect/pexpect) - Controlling interactive programs in a pseudo-terminal like GNU expect. :star:1152
* [psutil](https://github.com/giampaolo/psutil) - A cross-platform process and system utilities module. :star:3412
* [SaltStack](https://github.com/saltstack/salt) - Infrastructure automation and management system. :star:8633
* [supervisor](https://github.com/Supervisor/supervisor) - Supervisor process control system for UNIX. :star:4111

## Distribution

*Libraries to create packaged executables for release distribution.*

* [dh-virtualenv](https://github.com/spotify/dh-virtualenv) - Build and distribute a virtualenv as a Debian package. :star:1141
* [Nuitka](http://nuitka.net/) - Compile scripts, modules, packages to an executable or extension module.
* [py2app](http://pythonhosted.org/py2app/) - Freezes Python scripts (Mac OS X).
* [py2exe](http://www.py2exe.org/) - Freezes Python scripts (Windows).
* [PyInstaller](https://github.com/pyinstaller/pyinstaller) - Converts Python programs into stand-alone executables (cross-platform). :star:3781
* [pynsist](http://pynsist.readthedocs.io/en/latest/) - A tool to build Windows installers, installers bundle Python itself.

## Documentation

*Libraries for generating project documentation.*

* [Sphinx](http://www.sphinx-doc.org/en/latest/) - Python Documentation generator.
    * [awesome-sphinxdoc](https://github.com/yoloseem/awesome-sphinxdoc) :star:385
* [MkDocs](http://www.mkdocs.org/) - Markdown friendly documentation generator.
* [pdoc](https://github.com/BurntSushi/pdoc) - Epydoc replacement to auto generate API documentation for Python libraries. :star:378
* [Pycco](https://github.com/pycco-docs/pycco) - The literate-programming-style documentation generator. :star:585

## Downloader

*Libraries for downloading.*

* [s3cmd](https://github.com/s3tools/s3cmd) - A command line tool for managing Amazon S3 and CloudFront. :star:2578
* [s4cmd](https://github.com/bloomreach/s4cmd) - Super S3 command line tool, good for higher performance. :star:687
* [you-get](http://you-get.org/) - A YouTube/Youku/Niconico video downloader written in Python 3.
* [youtube-dl](http://rg3.github.io/youtube-dl/) - A small command-line program to download videos from YouTube.

## E-commerce

*Frameworks and libraries for e-commerce and payments.*

* [alipay](https://github.com/lxneng/alipay) - Unofficial Alipay API for Python. :star:274
* [Cartridge](https://github.com/stephenmcd/cartridge) - A shopping cart app built using the Mezzanine. :star:556
* [django-oscar](http://oscarcommerce.com/) - An open-source e-commerce framework for Django.
* [django-shop](https://github.com/awesto/django-shop) - A Django based shop system. :star:1505
* [merchant](https://github.com/agiliq/merchant) - A Django app to accept payments from various payment processors. :star:883
* [money](https://github.com/carlospalol/money) - Money class with optional CLDR-backed locale-aware formatting and an extensible currency exchange solution. :star:124
* [python-currencies](https://github.com/Alir3z4/python-currencies) - Display money format and its filthy currencies. :star:33
* [forex-python](https://github.com/MicroPyramid/forex-python) - Foreign exchange rates, Bitcoin price index and currency conversion. :star:123
* [saleor](http://getsaleor.com/) - An e-commerce storefront for Django.
* [shoop](https://www.shuup.com/en/) - An open source E-Commerce platform based on Django.

## Editor Plugins and IDEs

* Emacs
    * [Elpy](https://github.com/jorgenschaefer/elpy) - Emacs Python Development Environment. :star:1155
* Sublime Text
    * [Anaconda](https://github.com/DamnWidget/anaconda) - Anaconda turns your Sublime Text 3 in a full featured Python development IDE. :star:1745
    * [SublimeJEDI](https://github.com/srusskih/SublimeJEDI) - A Sublime Text plugin to the awesome auto-complete library Jedi. :star:796
* Vim
    * [Jedi-vim](https://github.com/davidhalter/jedi-vim) - Vim bindings for the Jedi auto-completion library for Python. :star:3265
    * [Python-mode](https://github.com/python-mode/python-mode) - An all in one plugin for turning Vim into a Python IDE. :star:4026
    * [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) - Includes [Jedi](https://github.com/davidhalter/jedi)-based completion engine for Python. :star:15863
* Visual Studio
    * [PTVS](https://github.com/Microsoft/PTVS) - Python Tools for Visual Studio. :star:1894
* Visual Studio Code
    * [Python](https://github.com/DonJayamanne/pythonVSCode) - An extension with rich support for the Python language, with features including linting, IntelliSense, formatting, refactoring, debugging, unit tests, and jupyter support. :star:1788
    * [Magic Python](https://github.com/MagicStack/MagicPython) - Cutting edge Python syntax highlighter for Sublime Text, Atom, and Visual Studio Code. Used by GitHub to highlight your Python code! :star:956
* IDE
    * [LiClipse](http://www.liclipse.com/) - Free polyglot IDE based on Eclipse. Uses PyDev for Python support.
    * [PyCharm](https://www.jetbrains.com/pycharm/) - Commercial Python IDE by JetBrains. Has free community edition available.
    * [Spyder](https://github.com/spyder-ide/spyder) - Open Source Python IDE. :star:2850

## Email

*Libraries for sending and parsing email.*

* [envelopes](http://tomekwojcik.github.io/envelopes/) - Mailing for human beings.
* [flanker](https://github.com/mailgun/flanker) - A email address and Mime parsing library. :star:1154
* [imbox](https://github.com/martinrusev/imbox) - Python IMAP for Humans. :star:751
* [inbox.py](https://github.com/kennethreitz/inbox.py) - Python SMTP Server for Humans. :star:1386
* [lamson](https://github.com/zedshaw/lamson) - Pythonic SMTP Application Server. :star:629
* [Marrow Mailer](https://github.com/marrow/mailer) - High-performance extensible mail delivery framework. :star:154
* [modoboa](https://github.com/modoboa/modoboa) - A mail hosting and management platform including a modern and simplified Web UI. :star:967
* [Nylas Sync Engine](https://github.com/nylas/sync-engine) - Providing a RESTful API on top of a powerful email sync platform. :star:3436
* [yagmail](https://github.com/kootenpv/yagmail) - Yet another Gmail/SMTP client. :star:996

## Environment Management

*Libraries for Python version and environment management.*

* [Pipenv](https://github.com/kennethreitz/pipenv) - Sacred Marriage of Pipfile, Pip, & Virtualenv. :star:9175
* [p](https://github.com/qw3rtman/p) - Dead simple interactive Python version management. :star:708
* [pyenv](https://github.com/pyenv/pyenv) - Simple Python version management. :star:10227
* [venv](https://docs.python.org/3/library/venv.html) - (Python standard library in Python 3.3+) Creating lightweight virtual environments.
* [virtualenv](https://pypi.python.org/pypi/virtualenv) - A tool to create isolated Python environments.
* [virtualenvwrapper](https://pypi.python.org/pypi/virtualenvwrapper) - A set of extensions to virtualenv.

## Files

*Libraries for file manipulation and MIME type detection.*

* [imghdr](https://docs.python.org/2/library/imghdr.html) - (Python standard library) Determine the type of an image.
* [mimetypes](https://docs.python.org/2/library/mimetypes.html) - (Python standard library) Map filenames to MIME types.
* [path.py](https://github.com/jaraco/path.py) - A module wrapper for [os.path](https://docs.python.org/2/library/os.path.html). :star:781
* [pathlib](https://pathlib.readthedocs.org/en/pep428/) - (Python standard library in Python 3.4+) An cross-platform, object-oriented path library.
* [python-magic](https://github.com/ahupp/python-magic) - A Python interface to the libmagic file type identification library. :star:1056
* [Unipath](https://github.com/mikeorr/Unipath) - An object-oriented approach to file/directory operations. :star:442
* [watchdog](https://github.com/gorakhargosh/watchdog) - API and shell utilities to monitor file system events. :star:2875

## Foreign Function Interface

*Libraries for providing foreign function interface.*

* [cffi](https://pypi.python.org/pypi/cffi) - Foreign Function Interface for Python calling C code.
* [ctypes](https://docs.python.org/2/library/ctypes.html) - (Python standard library) Foreign Function Interface for Python calling C code.
* [PyCUDA](https://mathema.tician.de/software/pycuda/) - A Python wrapper for Nvidia's CUDA API.
* [SWIG](http://www.swig.org/Doc1.3/Python.html) - Simplified Wrapper and Interface Generator.

## Forms

*Libraries for working with forms.*

* [Deform](https://github.com/Pylons/deform) - Python HTML form generation library influenced by the formish form generation library. :star:290
* [django-bootstrap3](https://github.com/dyve/django-bootstrap3) - Bootstrap 3 integration with Django. :star:1960
* [django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms) - A Django app which lets you create beautiful forms in a very elegant and DRY way. :star:3096
* [django-remote-forms](https://github.com/WiserTogether/django-remote-forms) - A platform independent Django form serializer. :star:167
* [WTForms](https://github.com/wtforms/wtforms) - A flexible forms validation and rendering library. :star:770

## Functional Programming

*Functional Programming with Python.*

* [CyToolz](https://github.com/pytoolz/cytoolz/) - Cython implementation of Toolz: High performance functional utilities.
* [fn.py](https://github.com/kachayev/fn.py) - Functional programming in Python: implementation of missing features to enjoy FP. :star:2552
* [funcy](https://github.com/Suor/funcy) - A fancy and practical functional tools. :star:1696
* [Toolz](https://github.com/pytoolz/toolz) - A collection of functional utilities for iterators, functions, and dictionaries. :star:1711

## GUI

*Libraries for working with graphical user interface applications.*

* [curses](https://docs.python.org/2/library/curses.html#module-curses) - Built-in wrapper for [ncurses](http://www.gnu.org/software/ncurses/) used to create terminal GUI applications.
* [Eel](https://github.com/ChrisKnott/Eel) - Little library for making simple Electron-like offline HTML/JS GUI apps, with full access to Python capabilities and libraries. :star:1828
* [enaml](https://github.com/nucleic/enaml) - Creating beautiful user-interfaces with Declaratic Syntax like QML. :star:582
* [Flexx](https://github.com/zoofIO/flexx) - Flexx is a pure Python toolkit for creating GUI's, that uses web technology for its rendering. :star:1521
* [kivy](https://kivy.org/) - A library for creating NUI applications, running on Windows, Linux, Mac OS X, Android and iOS.
* [pyglet](https://bitbucket.org/pyglet/pyglet/wiki/Home) - A cross-platform windowing and multimedia library for Python.
* [PyGObject](https://wiki.gnome.org/Projects/PyGObject) - Python Bindings for GLib/GObject/GIO/GTK+ (GTK+3)
* [PyQt](https://riverbankcomputing.com/software/pyqt/intro) - Python bindings for the [Qt](https://www.qt.io/) cross-platform application and UI framework, with support for both Qt v4 and Qt v5 frameworks.
* [PySide](https://wiki.qt.io/PySide) - Python bindings for the [Qt](http://www.qt.io/) cross-platform application and UI framework, supporting the Qt v4 framework.
* [pywebview](https://github.com/r0x0r/pywebview/) - A lightweight cross-platform native wrapper around a webview component that allows to display HTML content in its own native dedicated window
* [Tkinter](https://wiki.python.org/moin/TkInter) - Tkinter is Python's de-facto standard GUI package.
* [Toga](https://github.com/pybee/toga) - A Python native, OS native GUI toolkit. :star:1448
* [urwid](http://urwid.org/) - A library for creating terminal GUI applications with strong support for widgets, events, rich colors, etc.
* [wxPython](https://wxpython.org/) - A blending of the wxWidgets C++ class library with the Python.

## Game Development

*Awesome game development libraries.*

* [Cocos2d](http://cocos2d.org/) - cocos2d is a framework for building 2D games, demos, and other graphical/interactive applications. It is based on pyglet.
* [Panda3D](https://www.panda3d.org/) - 3D game engine developed by Disney and maintained by Carnegie Mellon's Entertainment Technology Center. Written in C++, completely wrapped in Python.
* [Pygame](http://www.pygame.org/news.html) - Pygame is a set of Python modules designed for writing games.
* [PyOgre](http://www.ogre3d.org/tikiwiki/PyOgre) - Python bindings for the Ogre 3D render engine, can be used for games, simulations, anything 3D.
* [PyOpenGL](http://pyopengl.sourceforge.net/) - Python ctypes bindings for OpenGL and it's related APIs.
* [PySDL2](http://pysdl2.readthedocs.io/en/rel_0_9_5/) - A ctypes based wrapper for the SDL2 library.
* [RenPy](https://www.renpy.org/) - A Visual Novel engine.

## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [django-countries](https://github.com/SmileyChris/django-countries) - A Django app that provides country choices for use with forms, flag icons static files, and a country field for models. :star:491
* [GeoDjango](https://docs.djangoproject.com/en/dev/ref/contrib/gis/) - A world-class geographic web framework.
* [GeoIP](https://github.com/maxmind/geoip-api-python) - Python API for MaxMind GeoIP Legacy Database. :star:166
* [geojson](https://github.com/frewsxcv/python-geojson) - Python bindings and utilities for GeoJSON. :star:301
* [geopy](https://github.com/geopy/geopy) - Python Geocoding Toolbox. :star:1780
* [pygeoip](https://github.com/appliedsec/pygeoip) - Pure Python GeoIP API. :star:474

## HTML Manipulation

*Libraries for working with HTML and XML.*

* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Providing Pythonic idioms for iterating, searching, and modifying HTML or XML.
* [bleach](https://github.com/mozilla/bleach) - A whitelist-based HTML sanitization and text linkification library. :star:1464
* [cssutils](https://pypi.python.org/pypi/cssutils/) - A CSS library for Python.
* [html5lib](https://github.com/html5lib/html5lib-python) - A standards-compliant library for parsing and serializing HTML documents and fragments. :star:670
* [lxml](http://lxml.de/) - A very fast, easy-to-use and versatile library for handling HTML and XML.
* [MarkupSafe](https://github.com/pallets/markupsafe) - Implements a XML/HTML/XHTML Markup safe string for Python. :star:201
* [pyquery](https://github.com/gawel/pyquery) - A jQuery-like library for parsing HTML. :star:1422
* [untangle](https://github.com/stchris/untangle) - Converts XML documents to Python objects for easy access. :star:304
* [WeasyPrint](http://weasyprint.org) - A visual rendering engine for HTML and CSS that can export to PDF.
* [xmldataset](https://xmldataset.readthedocs.io/en/latest/) - Simple XML Parsing.
* [xmltodict](https://github.com/martinblech/xmltodict) - Working with XML feel like you are working with JSON. :star:2822

## HTTP

*Libraries for working with HTTP.*

* [grequests](https://github.com/kennethreitz/grequests) - requests + gevent for asynchronous HTTP requests. :star:2473
* [httplib2](https://github.com/httplib2/httplib2) - Comprehensive HTTP client library. :star:217
* [requests](http://docs.python-requests.org/en/latest/) - HTTP Requests for Humans™.
* [treq](https://github.com/twisted/treq) - Python requests like API built on top of Twisted's HTTP client. :star:400
* [urllib3](https://github.com/shazow/urllib3) - A HTTP library with thread-safe connection pooling, file post support, sanity friendly. :star:1514

## Hardware

*Libraries for programming with hardware.*

* [ino](http://inotool.org/) - Command line toolkit for working with [Arduino](https://www.arduino.cc/).
* [keyboard](https://github.com/boppreh/keyboard) - Hook and simulate global keyboard events on Windows and Linux. :star:917
* [mouse](https://github.com/boppreh/mouse) - Hook and simulate global mouse events on Windows and Linux. :star:60
* [Pingo](http://www.pingo.io/) - Pingo provides a uniform API to program devices like the Raspberry Pi, pcDuino, Intel Galileo, etc.
* [Pyro](http://pyrorobotics.com/) - Python Robotics.
* [PyUserInput](https://github.com/SavinaRoja/PyUserInput) - A module for cross-platform control of the mouse and keyboard. :star:682
* [scapy](https://github.com/secdev/scapy) - A brilliant packet manipulation library. :star:2143
* [wifi](https://github.com/rockymeza/wifi) - A Python library and command line tool for working with WiFi on Linux. :star:216

## Image Processing

*Libraries for manipulating images.*

* [hmap](https://github.com/rossgoodwin/hmap) - Image histogram remapping. :star:150
* [imgSeek](https://sourceforge.net/projects/imgseek/) - A project for searching a collection of images using visual similarity.
* [nude.py](https://github.com/hhatto/nude.py) - Nudity detection. :star:545
* [pagan](https://github.com/daboth/pagan) - Retro identicon (Avatar) generation based on input string and hash. :star:87
* [pillow](https://github.com/python-pillow/Pillow) - Pillow is the friendly [PIL](http://www.pythonware.com/products/pil/) fork. :star:4597
* [pyBarcode](https://pythonhosted.org/pyBarcode/) - Create barcodes in Python without needing PIL.
* [pygram](https://github.com/ajkumar25/pygram) - Instagram-like image filters. :star:63
* [python-qrcode](https://github.com/lincolnloop/python-qrcode) - A pure Python QR Code generator. :star:1294
* [Quads](https://github.com/fogleman/Quads) - Computer art based on quadtrees. :star:711
* [scikit-image](http://scikit-image.org/) - A Python library for (scientific) image processing.
* [thumbor](https://github.com/thumbor/thumbor) - A smart imaging service. It enables on-demand crop, re-sizing and flipping of images. :star:5736
* [wand](https://github.com/dahlia/wand) - Python bindings for [MagickWand](http://www.imagemagick.org/script/magick-wand.php), C API for ImageMagick. :star:753

## Implementations

*Implementations of Python.*

* [CLPython](https://github.com/metawilm/cl-python) - Implementation of the Python programming language written in Common Lisp. :star:237
* [CPython](https://github.com/python/cpython) - **Default, most widely used implementation of the Python programming language written in C.** :star:16405
* [Cython](http://cython.org/) - Optimizing Static Compiler for Python. Uses type mixins to compile Python into C or C++ modules resulting in large performance gains
* [Grumpy](http://grump.io) - More compiler than interpreter as more powerful CPython2.7 replacement (alpha).
* [IronPython](https://github.com/IronLanguages/ironpython3) - Implementation of the Python programming language written in C# targeting the .NET Framework and Mono. :star:566
* [Jython](https://hg.python.org/jython) - Implementation of Python programming language written in Java for the Java virtual machine (JVM).
* [MicroPython](https://github.com/micropython/micropython) - MicroPython - a lean and efficient Python programming language implementation for microcontrollers and constrained systems :star:6110
* [Numba](http://numba.pydata.org/) - Python JIT compiler to LLVM aimed at scientific Python.
* [PeachPy](https://github.com/Maratyszcza/PeachPy) - x86-64 assembler embedded in Python. Can be used as inline assembler for Python or as a stand-alone assembler for Windows, Linux, OS X, Native Client and Go. :star:1105
* [Pyjion](https://github.com/Microsoft/Pyjion) - A JIT for Python based upon CoreCLR. :star:1170
* [PyPy](https://bitbucket.org/pypy/pypy) - Implementation of the Python programming language written in RPython and translated into C. PyPy focuses on speed, efficiency and compatibility with the original CPython interpreter. The interpreter uses black magic to make Python very fast without having to add in additional type information.
* [PySec](https://github.com/ebranca/owasp-pysec) - Hardened version of python that makes it easier for security professionals and developers to write applications more resilient to attacks and manipulations. :star:267
* [Pyston](https://github.com/dropbox/pyston) - A Python implementation built using LLVM and modern JIT techniques with the goal of achieving good performance. :star:4394
* [Stackless Python](https://bitbucket.org/stackless-dev/stackless/wiki/Home) - An enhanced version of the Python programming language which allows programmers to reap the benefits of thread-based programming without the performance and complexity problems associated with conventional threads.

## Interactive Interpreter

*Interactive Python interpreters (REPL).*

* [bpython](https://github.com/bpython/bpython) - A fancy interface to the Python interpreter. :star:967
* [Jupyter Notebook (IPython)](https://jupyter.org) - A rich toolkit to help you make the most out of using Python interactively.
* [ptpython](https://github.com/jonathanslenders/ptpython) - Advanced Python REPL built on top of the [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit). :star:2507

## Internationalization

*Libraries for working with i18n.*

* [Babel](http://babel.pocoo.org/en/latest/) - An internationalization library for Python.
* [PyICU](https://github.com/ovalhub/pyicu) - A wrapper of International Components for Unicode C++ library ([ICU](http://site.icu-project.org/)). :star:56

## Job Scheduler

*Libraries for scheduling jobs.*

* [APScheduler](http://apscheduler.readthedocs.io/en/latest/) - A light but powerful in-process task scheduler that lets you schedule functions.
* [django-schedule](https://github.com/thauber/django-schedule) - A calendaring app for Django. :star:713
* [doit](http://pydoit.org/) - A task runner and build tool.
* [gunnery](https://github.com/gunnery/gunnery) - Multipurpose task execution tool for distributed systems with web-based interface. :star:661
* [Joblib](http://pythonhosted.org/joblib/index.html) - A set of tools to provide lightweight pipelining in Python.
* [Plan](https://github.com/fengsp/plan) - Writing crontab file in Python like a charm. :star:1030
* [schedule](https://github.com/dbader/schedule) - Python job scheduling for humans. :star:4152
* [Spiff](https://github.com/knipknap/SpiffWorkflow) - A powerful workflow engine implemented in pure Python. :star:565
* [TaskFlow](https://docs.openstack.org/developer/taskflow/) - A Python library that helps to make task execution easy, consistent and reliable.

## Logging

*Libraries for generating and working with logs.*

* [Eliot](https://github.com/ScatterHQ/eliot) - Logging for complex & distributed systems. :star:350
* [logbook](http://logbook.readthedocs.io/en/stable/) - Logging replacement for Python.
* [logging](https://docs.python.org/2/library/logging.html) - (Python standard library) Logging facility for Python.
* [raven](https://github.com/getsentry/raven-python) - Python client for Sentry, a log/error tracking, crash reporting and aggregation platform for web applications. :star:1374

## Machine Learning

*Libraries for Machine Learning. See: [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python).*

* [Metrics](https://github.com/benhamner/Metrics) - Machine learning evaluation metrics. :star:782
* [NuPIC](https://github.com/numenta/nupic) - Numenta Platform for Intelligent Computing. :star:5507
* [scikit-learn](http://scikit-learn.org/) - The most popular Python library for Machine Learning.
* [Spark ML](http://spark.apache.org/docs/latest/ml-guide.html) - [Apache Spark](http://spark.apache.org/)'s scalable Machine Learning library.
* [vowpal_porpoise](https://github.com/josephreisinger/vowpal_porpoise) - A lightweight Python wrapper for [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/). :star:137
* [xgboost](https://github.com/dmlc/xgboost) - A scalable, portable, and distributed gradient boosting library. :star:10971

## MapReduce

*Frameworks and libraries for MapReduce.*

* [PySpark](https://pypi.python.org/pypi/pyspark/) - Apache Spark Python API.
* [luigi](https://github.com/spotify/luigi) - A module that helps you build complex pipelines of batch jobs. :star:8728
* [mrjob](https://github.com/Yelp/mrjob) - Run MapReduce jobs on Hadoop or Amazon Web Services. :star:2174
* [streamparse](https://github.com/Parsely/streamparse) - Run Python code against real-time streams of data. Integrates with [Apache Storm](http://storm.apache.org/). :star:1259
* [dask](https://dask.pydata.org/en/latest/) - A flexible parallel computing library for analytic computing.

## Microsoft Windows

*Python programming on Microsoft Windows.*

* [Python(x,y)](http://python-xy.github.io/) - Scientific-applications-oriented Python Distribution based on Qt and Spyder.
* [pythonlibs](http://www.lfd.uci.edu/~gohlke/pythonlibs/) - Unofficial Windows binaries for Python extension packages.
* [PythonNet](https://github.com/pythonnet/pythonnet) - Python Integration with the .NET Common Language Runtime (CLR). :star:1056
* [PyWin32](https://sourceforge.net/projects/pywin32/) - Python Extensions for Windows.
* [WinPython](https://winpython.github.io/) - Portable development environment for Windows 7/8.

## Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*

* [blinker](https://github.com/jek/blinker) - A fast Python in-process signal/event dispatching system. :star:680
* [itsdangerous](https://github.com/pallets/itsdangerous) - Various helpers to pass trusted data to untrusted environments. :star:1353
* [pluginbase](https://github.com/mitsuhiko/pluginbase) - A simple but flexible plugin system for Python. :star:638
* [Pychievements](https://github.com/PacketPerception/pychievements) - A framework for creating and tracking achievements. :star:92
* [Tryton](http://www.tryton.org/) - A general purpose business framework.

## Natural Language Processing

*Libraries for working with human languages.*

* [gensim](https://github.com/RaRe-Technologies/gensim) - Topic Modelling for Humans. :star:6389
* [Jieba](https://github.com/fxsjy/jieba) - Chinese text segmentation. :star:12264
* [langid.py](https://github.com/saffsd/langid.py) - Stand-alone language identification system. :star:984
* [NLTK](http://www.nltk.org/) - A leading platform for building Python programs to work with human language data.
* [Pattern](http://www.clips.ua.ac.be/pattern) - A web mining module for the Python.
* [polyglot](https://github.com/aboSamoor/polyglot) - Natural language pipeline supporting hundreds of languages. :star:760
* [SnowNLP](https://github.com/isnowfy/snownlp) - A library for processing Chinese text. :star:2866
* [spaCy](https://spacy.io/) - A library for industrial-strength natural language processing in Python and Cython.
* [TextBlob](https://github.com/sloria/TextBlob) - Providing a consistent API for diving into common NLP tasks. :star:4842

## Network Virtualization

*Tools and libraries for Virtual Networking and SDN (Software Defined Networking).*

* [Mininet](http://mininet.org/) - A popular network emulator and API written in Python.
* [POX](https://github.com/noxrepo/pox) - An open source development platform for Python-based Software Defined Networking (SDN) control applications, such as OpenFlow SDN controllers. :star:392
* [Pyretic](http://frenetic-lang.org/pyretic/) - A member of the Frenetic family of SDN programming languages that provides powerful abstractions over network switches or emulators.
* [SDX Platform](https://github.com/sdn-ixp/internet2award) - SDN based IXP implementation that leverages Mininet, POX and Pyretic. :star:10

## Networking

*Libraries for networking programming.*

* [asyncio](https://docs.python.org/3/library/asyncio.html) - (Python standard library) Asynchronous I/O, event loop, coroutines and tasks.
* [diesel](https://github.com/dieseldev/diesel) - Greenlet-based event I/O Framework for Python. :star:542
* [pulsar](https://github.com/quantmind/pulsar) - Event-driven concurrent framework for Python. :star:1569
* [pyzmq](http://zeromq.github.io/pyzmq/) - A Python wrapper for the ZeroMQ message library.
* [Twisted](https://twistedmatrix.com/trac/) - An event-driven networking engine.
* [txZMQ](https://github.com/smira/txZMQ) - Twisted based wrapper for the ZeroMQ message library. :star:142
* [NAPALM](https://github.com/napalm-automation/napalm) - Cross-vendor API to manipulate network devices. :star:831

## News Feed

*Libraries for building user's activities.*

* [django-activity-stream](https://github.com/justquick/django-activity-stream) - Generating generic activity streams from the actions on your site. :star:1314
* [Stream-Framework](https://github.com/tschellenbach/Stream-Framework) - Building newsfeed and notification systems using Cassandra and Redis. :star:3526

## ORM

*Libraries that implement Object-Relational Mapping or data mapping techniques.*

* Relational Databases
    * [Django Models](https://docs.djangoproject.com/en/dev/topics/db/models/) - A part of Django.
    * [SQLAlchemy](http://www.sqlalchemy.org/) - The Python SQL Toolkit and Object Relational Mapper.
        * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy) :star:1579
    * [Orator](https://orator-orm.com) -  The Orator ORM provides a simple yet beautiful ActiveRecord implementation.
    * [Peewee](https://github.com/coleifer/peewee) - A small, expressive ORM. :star:4925
    * [PonyORM](https://ponyorm.com/) - ORM that provides a generator-oriented interface to SQL.
    * [pyDAL](https://github.com/web2py/pydal/) - A pure Python Database Abstraction Layer.
    * [python-sql](https://pypi.python.org/pypi/python-sql) - Write SQL queries pythonically.
* NoSQL Databases
    * [django-mongodb-engine](https://github.com/django-nonrel/mongodb-engine) - Django MongoDB Backend. :star:749
    * [flywheel](https://github.com/stevearc/flywheel) - Object mapper for Amazon DynamoDB. :star:101
    * [hot-redis](https://github.com/stephenmcd/hot-redis) - Rich Python data types for Redis. :star:227
    * [MongoEngine](http://mongoengine.org/) - A Python Object-Document-Mapper for working with MongoDB.
    * [PynamoDB](https://github.com/pynamodb/PynamoDB) - A Pythonic interface for [Amazon DynamoDB](https://aws.amazon.com/dynamodb/). :star:602
    * [redisco](https://github.com/kiddouk/redisco) - A Python Library for Simple Models and Containers Persisted in Redis. :star:391
* Others
    * [butterdb](https://github.com/terrible-ideas/butterdb) - A Python ORM for Google Drive Spreadsheets. :star:332
    * [dataset](https://github.com/pudo/dataset) - A JSON-based database. :star:3022

## Package Management

*Libraries for package and dependency management.*

* [pip](https://pip.pypa.io/en/stable/) - The Python package and dependency manager.
    * [Python Package Index](https://pypi.python.org/pypi)
* [conda](https://github.com/conda/conda/) - Cross-platform, Python-agnostic binary package manager.
* [Curdling](http://clarete.li/curdling/) - Curdling is a command line tool for managing Python packages.
* [pip-tools](https://github.com/jazzband/pip-tools) - A set of tools to keep your pinned Python dependencies fresh. :star:2605
* [wheel](http://pythonwheels.com/) - The new standard of Python distribution and are intended to replace eggs.

## Package Repositories

*Local PyPI repository server and proxies.*

* [warehouse](https://github.com/pypa/warehouse) - Next generation Python Package Repository (PyPI). :star:1471
    * [Warehouse](https://pypi.org/)
* [bandersnatch](https://bitbucket.org/pypa/bandersnatch) - PyPI mirroring tool provided by Python Packaging Authority (PyPA).
* [devpi](http://doc.devpi.net/latest/) - PyPI server and packaging/testing/release tool.
* [localshop](https://github.com/jazzband/localshop) - Local PyPI server (custom packages and auto-mirroring of pypi). :star:327

## Permissions

*Libraries that allow or deny users access to data or functionality.*

* [Carteblanche](https://github.com/neuman/python-carteblanche/) - Module to align code with thoughts of users and designers. Also magically handles navigation and permissions.
* [django-guardian](https://github.com/django-guardian/django-guardian) - Implementation of per object permissions for Django 1.2+ :star:1744
* [django-rules](https://github.com/dfunckt/django-rules) - A tiny but powerful app providing object-level permissions to Django, without requiring a database. :star:617

## Processes

*Libraries for starting and communicating with OS processes.*

* [delegator.py](https://github.com/kennethreitz/delegator.py) - [Subprocesses](https://docs.python.org/3.6/library/subprocess.html) for Humans™ 2.0. :star:847
* [sarge](http://sarge.readthedocs.io/en/latest/) - Yet another wrapper for subprocess.
* [sh](https://github.com/amoffat/sh) - A full-fledged subprocess replacement for Python. :star:4327

## Queue

*Libraries for working with event and task queues.*

* [celery](http://www.celeryproject.org/) - An asynchronous task queue/job queue based on distributed message passing.
* [huey](https://github.com/coleifer/huey) - Little multi-threaded task queue. :star:1613
* [mrq](https://github.com/pricingassistant/mrq) - Mr. Queue - A distributed worker task queue in Python using Redis & gevent. :star:670
* [rq](http://python-rq.org/) - Simple job queues for Python.
* [simpleq](https://github.com/rdegges/simpleq) - A simple, infinitely scalable, Amazon SQS based queue. :star:130

## Recommender Systems

*Libraries for building recommender systems.*

* [annoy](https://github.com/spotify/annoy) - Approximate Nearest Neighbors in C++/Python optimized for memory usage. :star:3198
* [fastFM](https://github.com/ibayer/fastFM) - A library for Factorization Machines. :star:547
* [implicit](https://github.com/benfred/implicit) - A fast Python implementation of collaborative filtering for implicit datasets. :star:727
* [libffm](https://github.com/guestwalk/libffm) - A library for Field-aware Factorization Machine (FFM). :star:686
* [LightFM](https://github.com/lyst/lightfm) - A Python implementation of a number of popular recommendation algorithms. :star:1543
* [surprise](http://surpriselib.com) - A scikit for building and analyzing recommender systems.
* [TensorRec](https://github.com/jfkirk/tensorrec) - A Recommendation Engine Framework in TensorFlow. :star:253

## RESTful API

*Libraries for developing RESTful APIs.*

* Django
    * [django-rest-framework](http://www.django-rest-framework.org/) - A powerful and flexible toolkit to build web APIs.
    * [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps.
* Flask
    * [eve](https://github.com/pyeve/eve) - REST API framework powered by Flask, MongoDB and good intentions. :star:4792
    * [flask-api-utils](https://github.com/marselester/flask-api-utils) - Taking care of API representation and authentication for Flask. :star:41
    * [flask-api](http://www.flaskapi.org/) - Browsable Web APIs for Flask.
    * [flask-restful](https://github.com/flask-restful/flask-restful) - Quickly building REST APIs for Flask. :star:3460
    * [flask-restless](https://github.com/jfinkels/flask-restless) - Generating RESTful APIs for database models defined with SQLAlchemy. :star:853
* Pyramid
    * [cornice](https://github.com/Cornices/cornice) - A RESTful framework for Pyramid. :star:321
* Framework agnostic
    * [falcon](http://falconframework.org/) - A high-performance framework for building cloud APIs and web app backends.
    * [hug](https://github.com/timothycrosley/hug) - A Python3 framework for cleanly exposing APIs over HTTP and the Command Line with automatic documentation and validation. :star:4964
    * [restless](https://github.com/toastdriven/restless) - Framework agnostic REST framework based on lessons learned from Tastypie. :star:660
    * [ripozo](https://github.com/vertical-knowledge/ripozo) - Quickly creating REST/HATEOAS/Hypermedia APIs. :star:182
    * [sandman](https://github.com/jeffknupp/sandman) - Automated REST APIs for existing database-driven systems. :star:2296
    * [apistar](https://github.com/encode/apistar) - A smart Web API framework, designed for Python 3. :star:3514

## RPC Servers

*RPC-compatible servers.*

* [SimpleJSONRPCServer](https://github.com/joshmarshall/jsonrpclib/) - This library is an implementation of the JSON-RPC specification.
* [SimpleXMLRPCServer](https://docs.python.org/2/library/simplexmlrpcserver.html) - (Python standard library) Simple XML-RPC server implementation, single-threaded.
* [zeroRPC](https://github.com/0rpc/zerorpc-python) - zerorpc is a flexible RPC implementation based on [ZeroMQ](http://zeromq.org/) and [MessagePack](http://msgpack.org/). :star:2146

## Science

*Libraries for scientific computing.*

* [astropy](http://www.astropy.org/) - A community Python library for Astronomy.
* [bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen) - Providing best-practice pipelines for fully automated high throughput sequencing analysis. :star:543
* [bccb](https://github.com/chapmanb/bcbb) - Collection of useful code related to biological analysis. :star:397
* [Biopython](http://biopython.org/wiki/Main_Page) - Biopython is a set of freely available tools for biological computation.
* [cclib](http://cclib.github.io/) - A library for parsing and interpreting the results of computational chemistry packages.
* [Colour](http://colour-science.org/) - A colour science package implementing a comprehensive number of colour theory transformations and algorithms.
* [NetworkX](https://networkx.github.io/) - A high-productivity software for complex networks.
* [NIPY](http://nipy.org) - A collection of neuroimaging toolkits.
* [NumPy](http://www.numpy.org/) - A fundamental package for scientific computing with Python.
* [Open Babel](http://openbabel.org/wiki/Main_Page) - A chemical toolbox designed to speak the many languages of chemical data.
* [ObsPy](https://github.com/obspy/obspy/wiki/) - A Python toolbox for seismology.
* [PyDy](http://www.pydy.org/) - Short for Python Dynamics, used to assist with workflow in the modeling of dynamic motion.
* [PyMC](https://github.com/pymc-devs/pymc3) - Markov Chain Monte Carlo sampling toolkit. :star:2989
* [RDKit](http://www.rdkit.org/) - Cheminformatics and Machine Learning Software.
* [SciPy](https://www.scipy.org/) - A Python-based ecosystem of open-source software for mathematics, science, and engineering.
* [statsmodels](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python. :star:2655
* [SymPy](https://github.com/sympy/sympy) - A Python library for symbolic mathematics. :star:4650
* [Zipline](https://github.com/quantopian/zipline) - A Pythonic algorithmic trading library. :star:6533
* [SimPy](https://bitbucket.org/simpy/simpy) -  A process-based discrete-event simulation framework.

## Search

*Libraries and software for indexing and performing search queries on data.*

* [django-haystack](https://github.com/django-haystack/django-haystack) - Modular search for Django. :star:2358
* [elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) - The official high-level Python client for Elasticsearch. :star:1692
* [elasticsearch-py](https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html) - The official low-level Python client for [Elasticsearch](https://www.elastic.co/products/elasticsearch).
* [esengine](https://github.com/seek-ai/esengine) - ElasticSearch ODM (Object Document Mapper) for Python. :star:83
* [pysolr](https://github.com/django-haystack/pysolr) - A lightweight Python wrapper for Apache Solr (incl. SolrCloud awareness). :star:435
* [solrpy](https://github.com/edsu/solrpy) - A Python client for [solr](http://lucene.apache.org/solr/). :star:28
* [Whoosh](http://whoosh.readthedocs.io/en/latest/) - A fast, pure Python search engine library.

## Serialization

*Libraries for serializing complex data types*

* [marshmallow](https://github.com/marshmallow-code/marshmallow) - marshmallow is an ORM/ODM/framework-agnostic library for converting complex datatypes, such as objects, to and from native Python datatypes. :star:2318

## Serverless Frameworks

*Frameworks for developing serverless Python code.*

* [apex](https://github.com/apex/apex) - Build, deploy, and manage [AWS Lambda](https://aws.amazon.com/lambda/) functions with ease. :star:6745
* [python-lambda](https://github.com/nficano/python-lambda) - A toolkit for developing and deploying Python code in AWS Lambda. :star:633
* [Zappa](https://github.com/Miserlou/Zappa) - A tool for deploying WSGI applications on AWS Lambda and API Gateway. :star:6306

## Specific Formats Processing

*Libraries for parsing and manipulating specific text formats.*

* General
    * [tablib](https://github.com/kennethreitz/tablib) - A module for Tabular Datasets in XLS, CSV, JSON, YAML. :star:2862
* Office
    * [Marmir](https://github.com/brianray/mm) - Takes Python data structures and turns them into spreadsheets. :star:135
    * [openpyxl](https://openpyxl.readthedocs.io/en/default/) - A library for reading and writing Excel 2010 xlsx/xlsm/xltx/xltm files.
    * [pyexcel](https://github.com/pyexcel/pyexcel) - Providing one API for reading, manipulating and writing csv, ods, xls, xlsx and xlsm files. :star:423
    * [python-docx](https://github.com/python-openxml/python-docx) - Reads, queries and modifies Microsoft Word 2007/2008 docx files. :star:1111
    * [python-pptx](https://github.com/scanny/python-pptx) - Python library for creating and updating PowerPoint (.pptx) files. :star:517
    * [relatorio](http://relatorio.tryton.org/) - Templating OpenDocument files.
    * [unoconv](https://github.com/dagwieers/unoconv) - Convert between any document format supported by LibreOffice/OpenOffice. :star:1145
    * [XlsxWriter](https://xlsxwriter.readthedocs.io) - A Python module for creating Excel .xlsx files.
    * [xlwings](https://www.xlwings.org) - A BSD-licensed library that makes it easy to call Python from Excel and vice versa.
    * [xlwt](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd) - Writing and reading data and formatting information from Excel files. :star:1258
* PDF
    * [PDFMiner](https://github.com/euske/pdfminer) - A tool for extracting information from PDF documents. :star:2664
    * [PyPDF2](https://github.com/mstamy2/PyPDF2) - A library capable of splitting, merging and transforming PDF pages. :star:1748
    * [ReportLab](http://www.reportlab.com/opensource/) - Allowing Rapid creation of rich PDF documents.
* Markdown
    * [Mistune](https://github.com/lepture/mistune) - Fastest and full featured pure Python parsers of Markdown. :star:1152
    * [Python-Markdown](https://github.com/waylan/Python-Markdown) - A Python implementation of John Gruber’s Markdown. :star:1281
* YAML
    * [PyYAML](http://pyyaml.org/) - YAML implementations for Python.
* CSV
    * [csvkit](https://github.com/wireservice/csvkit) - Utilities for converting to and working with CSV. :star:3115
* Archive
    * [unp](https://github.com/mitsuhiko/unp) - A command line tool that can unpack archives easily. :star:289

## Static Site Generator

*Static site generator is a software that takes some text + templates as input and produces HTML files on the output.*

* [Cactus](https://github.com/eudicots/Cactus) - Static site generator for designers. :star:3185
* [Hyde](http://hyde.github.io/) - Jinja2-based static web site generator.
* [Lektor](https://www.getlektor.com/) - An easy to use static CMS and blog engine.
* [Nikola](https://www.getnikola.com/) - A static website and blog generator.
* [Pelican](https://blog.getpelican.com/) - Uses Markdown or ReST for content and Jinja 2 for themes. Supports DVCS, Disqus. AGPL.
* [Tinkerer](http://tinkerer.me/) - Tinkerer is a blogging engine/.static website generator powered by Sphinx.

## Tagging

*Libraries for tagging items.*

* [django-taggit](https://github.com/alex/django-taggit) - Simple tagging for Django. :star:1839

## Template Engine

*Libraries and tools for templating and lexing.*

* [Genshi](https://genshi.edgewall.org/) - Python templating toolkit for generation of web-aware output.
* [Jinja2](https://github.com/pallets/jinja) - A modern and designer friendly templating language. :star:4974
* [Mako](http://www.makotemplates.org/) - Hyperfast and lightweight templating for the Python platform.

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [hypothesis](https://github.com/HypothesisWorks/hypothesis-python) - Hypothesis is an advanced Quickcheck style property based testing library. :star:2506
    * [mamba](http://nestorsalceda.github.io/mamba/) - The definitive testing tool for Python. Born under the banner of BDD.
    * [nose](https://github.com/nose-devs/nose) - A nicer unittest for Python. :star:1183
    * [nose2](https://github.com/nose-devs/nose2) - The successor to nose, based on unittest2. :star:429
    * [pytest](https://docs.pytest.org/latest/) - A mature full-featured Python testing tool.
    * [Robot Framework](https://github.com/robotframework/robotframework) - A generic test automation framework. :star:2041
    * [unittest](https://docs.python.org/2/library/unittest.html) - (Python standard library) Unit testing framework.
* Test Runners
    * [green](https://github.com/CleanCut/green) - A clean, colorful test runner. :star:507
    * [tox](https://tox.readthedocs.io/en/latest/) - Auto builds and tests distributions in multiple Python versions
* GUI / Web Testing
    * [locust](https://github.com/locustio/locust) - Scalable user load testing tool written in Python. :star:6982
    * [PyAutoGUI](https://github.com/asweigart/pyautogui) - PyAutoGUI is a cross-platform GUI automation Python module for human beings. :star:1578
    * [Selenium](https://pypi.python.org/pypi/selenium) - Python bindings for [Selenium](http://www.seleniumhq.org/) WebDriver.
    * [sixpack](https://github.com/seatgeek/sixpack) - A language-agnostic A/B Testing framework. :star:1440
    * [splinter](https://github.com/cobrateam/splinter) - Open source tool for testing web applications. :star:1667
* Mock
    * [doublex](https://pypi.python.org/pypi/doublex) - Powerful test doubles framework for Python.
    * [freezegun](https://github.com/spulec/freezegun) - Travel through time by mocking the datetime module. :star:1360
    * [httmock](https://github.com/patrys/httmock) - A mocking library for requests for Python 2.6+ and 3.2+. :star:337
    * [httpretty](https://github.com/gabrielfalcao/HTTPretty) - HTTP request mock tool for Python. :star:1491
    * [mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.
    * [Mocket](https://github.com/mindflayer/python-mocket) - Socket Mock Framework plus HTTP[S]/asyncio/gevent mocking library with recording/replaying capability. :star:94
    * [responses](https://github.com/getsentry/responses) - A utility library for mocking out the requests Python library. :star:1782
    * [VCR.py](https://github.com/kevin1024/vcrpy) - Record and replay HTTP interactions on your tests. :star:1084
* Object Factories
    * [factory_boy](https://github.com/FactoryBoy/factory_boy) - A test fixtures replacement for Python. :star:1371
    * [mixer](https://github.com/klen/mixer) - Another fixtures replacement. Supported Django, Flask, SQLAlchemy, Peewee and etc. :star:475
    * [model_mommy](https://github.com/vandersonmota/model_mommy) - Creating random fixtures for testing in Django. :star:750
* Code Coverage
    * [coverage](https://pypi.python.org/pypi/coverage) - Code coverage measurement.
* Fake Data
    * [mimesis](https://github.com/lk-geimfari/mimesis) - is a Python library that help you generate fake data. :star:1884
    * [fake2db](https://github.com/emirozer/fake2db) - Fake database generator. :star:1818
    * [faker](https://github.com/joke2k/faker) - A Python package that generates fake data. :star:5687
    * [radar](https://pypi.python.org/pypi/radar) - Generate random datetime / time.
* Error Handler
    * [FuckIt.py](https://github.com/ajalt/fuckitpy) - FuckIt.py uses state-of-the-art technology to make sure your Python code runs whether it has any right to or not. :star:2784

## Text Processing

*Libraries for parsing and manipulating plain texts.*

* General
    * [chardet](https://github.com/chardet/chardet) - Python 2/3 compatible character encoding detector. :star:886
    * [difflib](https://docs.python.org/2/library/difflib.html) - (Python standard library) Helpers for computing deltas.
    * [ftfy](https://github.com/LuminosoInsight/python-ftfy) - Makes Unicode text less broken and more consistent automagically. :star:2181
    * [fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) - Fuzzy String Matching. :star:3975
    * [Levenshtein](https://github.com/ztane/python-Levenshtein/) - Fast computation of Levenshtein distance and string similarity.
    * [pangu.py](https://github.com/vinta/pangu.py) - Spacing texts for CJK and alphanumerics. :star:66
    * [pyfiglet](https://github.com/pwaller/pyfiglet) - An implementation of figlet written in Python. :star:261
    * [pypinyin](https://github.com/mozillazg/python-pinyin) - Convert Chinese hanzi to pinyin. :star:868
    * [shortuuid](https://github.com/skorokithakis/shortuuid) - A generator library for concise, unambiguous and URL-safe UUIDs. :star:868
    * [unidecode](https://pypi.python.org/pypi/Unidecode) - ASCII transliterations of Unicode text.
    * [uniout](https://github.com/moskytw/uniout) - Print readable chars instead of the escaped string. :star:138
    * [xpinyin](https://github.com/lxneng/xpinyin) - A library to translate Chinese hanzi (漢字) to pinyin (拼音). :star:524
* Slugify
    * [awesome-slugify](https://github.com/dimka665/awesome-slugify) - A Python slugify library that can preserve unicode. :star:387
    * [python-slugify](https://github.com/un33k/python-slugify) - A Python slugify library that translates unicode to ASCII. :star:445
    * [unicode-slugify](https://github.com/mozilla/unicode-slugify) - A slugifier that generates unicode slugs with Django as a dependency. :star:260
* Parser
    * [phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) - Parsing, formatting, storing and validating international phone numbers. :star:1762
    * [PLY](http://www.dabeaz.com/ply/) - Implementation of lex and yacc parsing tools for Python
    * [Pygments](http://pygments.org/) - A generic syntax highlighter.
    * [pyparsing](http://pyparsing.wikispaces.com/) - A general purpose framework for generating parsers.
    * [python-nameparser](https://github.com/derek73/python-nameparser) - Parsing human names into their individual components. :star:257
    * [python-user-agents](https://github.com/selwin/python-user-agents) - Browser user agent parser. :star:685
    * [sqlparse](https://github.com/andialbrecht/sqlparse) - A non-validating SQL parser. :star:1172

## Third-party APIs

*Libraries for accessing third party services APIs. See: [List of Python API Wrappers and Libraries](https://github.com/realpython/list-of-python-api-wrappers).*

* [apache-libcloud](https://libcloud.apache.org/) - One Python library for all clouds.
* [boto3](https://github.com/boto/boto3) - Python interface to Amazon Web Services. :star:3071
* [django-wordpress](https://github.com/istrategylabs/django-wordpress) - WordPress models and views for Django. :star:262
* [facebook-sdk](https://github.com/mobolic/facebook-sdk) - Facebook Platform Python SDK. :star:2210
* [facepy](https://github.com/jgorset/facepy) - Facepy makes it really easy to interact with Facebook's Graph API :star:728
* [gmail](https://github.com/charlierguo/gmail) - A Pythonic interface for Gmail. :star:1485
* [google-api-python-client](https://github.com/google/google-api-python-client) - Google APIs Client Library for Python. :star:2000
* [gspread](https://github.com/burnash/gspread) - Google Spreadsheets Python API. :star:3077
* [twython](https://github.com/ryanmcgrath/twython) - A Python wrapper for the Twitter API. :star:1487

## URL Manipulation

*Libraries for parsing URLs.*

* [furl](https://github.com/gruns/furl) - A small Python library that makes parsing and manipulating URLs easy. :star:1231
* [purl](https://github.com/codeinthehole/purl) - A simple, immutable URL class with a clean API for interrogation and manipulation. :star:201
* [pyshorteners](https://github.com/ellisonleao/pyshorteners) - A pure Python URL shortening lib. :star:185
* [short_url](https://github.com/Alir3z4/python-short_url) - Python implementation for generating Tiny URL and bit.ly-like URLs. :star:106
* [webargs](https://github.com/sloria/webargs) - A friendly library for parsing HTTP request arguments, with built-in support for popular web frameworks, including Flask, Django, Bottle, Tornado, and Pyramid. :star:572

## Video

*Libraries for manipulating video and GIFs.*

* [moviepy](http://zulko.github.io/moviepy/) - A module for script-based movie editing with many formats, including animated GIFs.
* [scikit-video](https://github.com/aizvorski/scikit-video) - Video processing routines for SciPy. :star:70

## WSGI Servers

*WSGI-compatible web servers.*

* [bjoern](https://pypi.python.org/pypi/bjoern) - Asynchronous, very fast and written in C.
* [fapws3](http://www.fapws.org/) - Asynchronous (network side only), written in C.
* [gunicorn](https://pypi.python.org/pypi/gunicorn) - Pre-forked, partly written in C.
* [meinheld](https://pypi.python.org/pypi/meinheld) - Asynchronous, partly written in C.
* [netius](https://github.com/hivesolutions/netius) - Asynchronous, very fast. :star:90
* [paste](https://web.archive.org/web/http%3A//pythonpaste.org/) - Multi-threaded, stable, tried and tested.
* [rocket](https://pypi.python.org/pypi/rocket) - Multi-threaded.
* [uWSGI](https://uwsgi-docs.readthedocs.io/en/latest/) - A project aims at developing a full stack for building hosting services, written in C.
* [waitress](https://waitress.readthedocs.io/en/latest/) - Multi-threaded, powers Pyramid.
* [Werkzeug](http://werkzeug.pocoo.org/) - A WSGI utility library for Python that powers Flask and can easily be embedded into your own projects.

## Web Content Extracting

*Libraries for extracting web contents.*

* [Haul](https://github.com/vinta/Haul) - An Extensible Image Crawler. :star:118
* [html2text](https://github.com/Alir3z4/html2text) - Convert HTML to Markdown-formatted text. :star:472
* [lassie](https://github.com/michaelhelmick/lassie) - Web Content Retrieval for Humans. :star:409
* [micawber](https://github.com/coleifer/micawber) - A small library for extracting rich content from URLs. :star:382
* [newspaper](https://github.com/codelucas/newspaper) - News extraction, article extraction and content curation in Python. :star:5950
* [opengraph](https://github.com/erikriver/opengraph) - A Python module to parse the Open Graph Protocol :star:120
* [python-goose](https://github.com/grangier/python-goose) - HTML Content/Article Extractor. :star:2923
* [python-readability](https://github.com/buriy/python-readability) - Fast Python port of arc90's readability tool. :star:1342
* [sanitize](https://github.com/Alir3z4/python-sanitize) - Bringing sanity to world of messed-up data. :star:48
* [sumy](https://github.com/miso-belica/sumy) - A module for automatic summarization of text documents and HTML pages. :star:1298
* [textract](https://github.com/deanmalmgren/textract) - Extract text from any document, Word, PowerPoint, PDFs, etc. :star:2119
* [toapi](https://github.com/gaojiuli/toapi) - Every web site provides APIs :star:2355

## Web Crawling

*Libraries for scraping websites.*

* [cola](https://github.com/chineking/cola) - A distributed crawling framework. :star:1245
* [Demiurge](https://github.com/matiasb/demiurge) - PyQuery-based scraping micro-framework. :star:76
* [feedparser](http://pythonhosted.org/feedparser/) - Universal feed parser.
* [Grab](http://grablib.org/) - Site scraping framework.
* [MechanicalSoup](https://github.com/hickford/MechanicalSoup) - A Python library for automating interaction with websites. :star:2552
* [portia](https://github.com/scrapinghub/portia) - Visual scraping for Scrapy. :star:5877
* [pyspider](https://github.com/binux/pyspider) - A powerful spider system. :star:10817
* [RoboBrowser](https://github.com/jmcarp/robobrowser) - A simple, Pythonic library for browsing the web without a standalone web browser. :star:3043
* [Scrapy](https://scrapy.org/) - A fast high-level screen scraping and web crawling framework.

## Web Frameworks

*Full stack web frameworks.*

* [Bottle](http://bottlepy.org/docs/dev/index.html) - A fast, simple and lightweight WSGI micro web-framework.
* [Dash](https://plot.ly/products/dash/) - Built on top of Flask, React and Plotly aimed at analytical web applications.
    * [awesome-dash](https://github.com/Acrotrend/awesome-dash) :star:33
* [Django](https://www.djangoproject.com/) - The most popular web framework in Python.
    * [awesome-django](https://github.com/rosarior/awesome-django) :star:7037
* [Flask](http://flask.pocoo.org/) - A microframework for Python.
    * [awesome-flask](https://github.com/humiaozuzu/awesome-flask) :star:5001
* [Pyramid](https://pylonsproject.org/) - A small, fast, down-to-earth, open source Python web framework.
    * [awesome-pyramid](https://github.com/uralbash/awesome-pyramid) :star:407
* [Sanic](https://github.com/channelcat/sanic) - Web server that's written to go fast. :star:8706
* [Tornado](http://www.tornadoweb.org/en/latest/) - A Web framework and asynchronous networking library.

## WebSocket

*Libraries for working with WebSocket.*

* [AutobahnPython](https://github.com/crossbario/autobahn-python) - WebSocket & WAMP for Python on Twisted and [asyncio](https://docs.python.org/3/library/asyncio.html). :star:1705
* [Crossbar](https://github.com/crossbario/crossbar/) - Open-source Unified Application Router (Websocket & WAMP for Python on Autobahn).
* [django-channels](https://github.com/django/channels) - Developer-friendly asynchrony for Django :star:2763
* [django-socketio](https://github.com/stephenmcd/django-socketio) - WebSockets for Django. :star:1098
* [WebSocket-for-Python](https://github.com/Lawouach/WebSocket-for-Python) - WebSocket client and server library for Python 2 and 3 as well as PyPy. :star:918

# Services

Online tools and APIs to simplify development.

## Continuous Integration

*See: [awesome-CIandCD](https://github.com/ciandcd/awesome-ciandcd#online-build-system).*

* [CircleCI](https://circleci.com/) - A CI service that can run very fast parallel testing. (GitHub only)
* [Travis CI](https://travis-ci.org) - A popular CI service for your open source and [private](https://travis-ci.com) projects. (GitHub only)
* [Vexor CI](https://vexor.io) - A continuous integration tool for private apps with pay-per-minute billing model.
* [Wercker](http://www.wercker.com/) - A Docker-based platform for building and deploying applications and microservices.

## Code Quality

* [Codacy](https://www.codacy.com/) - Automated Code Review to ship better code, faster.
* [Codecov](https://codecov.io/) - Code coverage dashboard.
* [CodeFactor](https://www.codefactor.io/) - Automated Code Review for Git.
* [Landscape](https://landscape.io/) - Hosted continuous Python code metrics.

# Resources

Where to discover new Python libraries.

## Podcasts

* [From Python Import Podcast](http://frompythonimportpodcast.com/)
* [Podcast.init](https://podcastinit.com/)
* [Python Bytes](https://pythonbytes.fm)
* [Python Testing](http://pythontesting.net)
* [Radio Free Python](http://radiofreepython.com/)
* [Talk Python To Me](https://talkpython.fm/)

## Twitter

* [@codetengu](https://twitter.com/codetengu)
* [@getpy](https://twitter.com/getpy)
* [@importpython](https://twitter.com/importpython)
* [@planetpython](https://twitter.com/planetpython)
* [@pycoders](https://twitter.com/pycoders)
* [@pypi](https://twitter.com/pypi)
* [@pythontrending](https://twitter.com/pythontrending)
* [@PythonWeekly](https://twitter.com/PythonWeekly)
* [@TalkPython](https://twitter.com/talkpython)

## Websites

* [/r/CoolGithubProjects](https://www.reddit.com/r/coolgithubprojects/)
* [/r/Python](https://www.reddit.com/r/python)
* [Awesome Python @LibHunt](https://python.libhunt.com/)
* [Django Packages](https://djangopackages.org/)
* [Full Stack Python](https://www.fullstackpython.com/)
* [PyPI Ranking](http://pypi-ranking.info/alltime)
* [Python 3 Wall of Superpowers](http://python3wos.appspot.com/)
* [Python Hackers](http://www.oss.io/open-source/)
* [Python ZEEF](https://python.zeef.com/alan.richmond)
* [Python 开发社区](https://www.ctolib.com/python/)
* [Trending Python repositories on GitHub today](https://github.com/trending?l=python)

## Weekly

* [CodeTengu Weekly 碼天狗週刊](https://weekly.codetengu.com/)
* [Import Python Newsletter](http://importpython.com/newsletter/)
* [Pycoder's Weekly](http://pycoders.com/)
* [Python Weekly](http://www.pythonweekly.com/)

# Other Awesome Lists

List of lists.

* Monty
    * [awesome](https://github.com/sindresorhus/awesome) :star:79487
    * [awesomo](https://github.com/lk-geimfari/awesomo) :star:5473
    * [lists](https://github.com/jnv/lists) :star:4814
* Python
    * [pycrumbs](https://github.com/kirang89/pycrumbs) :star:2672
    * [python-github-projects](https://github.com/checkcheckzz/python-github-projects) :star:456
    * [python_reference](https://github.com/rasbt/python_reference) :star:1941
    * [pythonidae](https://github.com/svaksha/pythonidae) :star:605
    * [Python Podcasts](https://www.cybrhome.com/topic/python-podcasts)

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/vinta/awesome-python/blob/master/CONTRIBUTING.md) first.

I will keep some pull requests open if I'm not sure whether those libraries are awesome, you could [vote for them](https://github.com/vinta/awesome-python/pulls) by adding :+1: to them. Pull requests will be merged when their votes reach **20**.

- - -

If you have any question about this opinionated list, do not hesitate to contact me [@vinta](https://twitter.com/vinta) on Twitter or open an issue on GitHub.


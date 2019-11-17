# Information comes from [vinta/awesome-python](https://github.com/vinta/awesome-python)
# Awesome Python [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Python frameworks, libraries, software and resources.

Inspired by [awesome-php](https://github.com/ziadoz/awesome-php).

- [Awesome Python](#awesome-python)
    - [Admin Panels](#admin-panels)
    - [Algorithms and Design Patterns](#algorithms-and-design-patterns)
    - [Asynchronous Programming](#asynchronous-programming)
    - [Audio](#audio)
    - [Authentication](#authentication)
    - [Build Tools](#build-tools)
    - [Built-in Classes Enhancement](#built-in-classes-enhancement)
    - [Caching](#caching)
    - [ChatOps Tools](#chatops-tools)
    - [CMS](#cms)
    - [Code Analysis](#code-analysis)
    - [Command-line Interface Development](#command-line-interface-development)
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
    - [Distributed Computing](#distributed-computing)
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
    - [GUI Development](#gui-development)
    - [Hardware](#hardware)
    - [HTML Manipulation](#html-manipulation)
    - [HTTP Clients](#http-clients)
    - [Image Processing](#image-processing)
    - [Implementations](#implementations)
    - [Interactive Interpreter](#interactive-interpreter)
    - [Internationalization](#internationalization)
    - [Job Scheduler](#job-scheduler)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Network Virtualization](#network-virtualization)
    - [News Feed](#news-feed)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Package Repositories](#package-repositories)
    - [Permissions](#permissions)
    - [Processes](#processes)
    - [Recommender Systems](#recommender-systems)
    - [RESTful API](#restful-api)
    - [Robotics](#robotics)
    - [RPC Servers](#rpc-servers)
    - [Science](#science)
    - [Search](#search)
    - [Serialization](#serialization)
    - [Serverless Frameworks](#serverless-frameworks)
    - [Specific Formats Processing](#specific-formats-processing)
    - [Static Site Generator](#static-site-generator)
    - [Tagging](#tagging)
    - [Task Queues](#task-queues)
    - [Template Engine](#template-engine)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [URL Manipulation](#url-manipulation)
    - [Video](#video)
    - [Web Asset Management](#web-asset-management)
    - [Web Content Extracting](#web-content-extracting)
    - [Web Crawling](#web-crawling)
    - [Web Frameworks](#web-frameworks)
    - [WebSocket](#websocket)
    - [WSGI Servers](#wsgi-servers)
- [Resources](#resources)
    - [Podcasts](#podcasts)
    - [Twitter](#twitter)
    - [Websites](#websites)
    - [Weekly](#weekly)
- [Contributing](#contributing)

---

## Admin Panels

*Libraries for administrative interfaces.*

* [ajenti](https://github.com/ajenti/ajenti) - The admin panel your servers deserve. :star:5808
* [django-grappelli](https://grappelliproject.com/) - A jazzy skin for the Django Admin-Interface.
* [django-jet](https://github.com/geex-arts/django-jet) - Modern responsive template for the Django admin interface with improved functionality. :star:2452
* [django-suit](https://djangosuit.com/) - Alternative Django Admin-Interface (free only for Non-commercial use).
* [django-xadmin](https://github.com/sshwsfc/xadmin) - Drop-in replacement of Django admin comes with lots of goodies. :star:4119
* [jet-bridge](https://github.com/jet-admin/jet-bridge) - Admin panel framework for any application with nice UI (ex Jet Django) :star:562
* [flask-admin](https://github.com/flask-admin/flask-admin) - Simple and extensible administrative interface framework for Flask. :star:3920
* [flower](https://github.com/mher/flower) - Real-time monitor and web admin for Celery. :star:3951
* [wooey](https://github.com/wooey/wooey) - A Django app which creates automatic web UIs for Python scripts. :star:1342

## Algorithms and Design Patterns

*Python implementation of algorithms and design patterns.*

* [algorithms](https://github.com/keon/algorithms) - Minimal examples of data structures and algorithms in Python. :star:16301
* [PyPattyrn](https://github.com/tylerlaberge/PyPattyrn) - A simple yet effective library for implementing common design patterns. :star:877
* [python-patterns](https://github.com/faif/python-patterns) - A collection of design patterns in Python. :star:22753
* [sortedcontainers](https://github.com/grantjenks/python-sortedcontainers) - Fast, pure-Python implementation of SortedList, SortedDict, and SortedSet types. :star:1517

## Asynchronous Programming

* [asyncio](https://docs.python.org/3/library/asyncio.html) - (Python standard library) Asynchronous I/O, event loop, coroutines and tasks.
    - [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio) :star:1915
* [uvloop](https://github.com/MagicStack/uvloop) - Ultra fast asyncio event loop. :star:6395
* [Twisted](https://twistedmatrix.com/trac/) - An event-driven networking engine.

## Audio

*Libraries for manipulating audio and its metadata.*

* Audio
    * [audioread](https://github.com/beetbox/audioread) - Cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding. :star:301
    * [dejavu](https://github.com/worldveil/dejavu) - Audio fingerprinting and recognition. :star:4711
    * [mingus](http://bspaans.github.io/python-mingus/) - An advanced music theory and notation package with MIDI file and playback support.
    * [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) - Audio feature extraction, classification, segmentation and applications. :star:2706
    * [pydub](https://github.com/jiaaro/pydub) - Manipulate audio with a simple and easy high level interface. :star:3931
    * [TimeSide](https://github.com/Parisson/TimeSide) - Open web audio processing framework. :star:261
* Metadata
    * [beets](https://github.com/beetbox/beets) - A music library manager and [MusicBrainz](https://musicbrainz.org/) tagger. :star:8983
    * [eyeD3](https://github.com/nicfit/eyeD3) - A tool for working with audio files, specifically MP3 files containing ID3 metadata. :star:176
    * [mutagen](https://github.com/quodlibet/mutagen) - A Python module to handle audio metadata. :star:508
    * [tinytag](https://github.com/devsnd/tinytag) - A library for reading music meta data of MP3, OGG, FLAC and Wave files. :star:367

## Authentication

*Libraries for implementing authentications schemes.*

* OAuth
    * [authlib](https://github.com/lepture/authlib) - JavaScript Object Signing and Encryption draft implementation. :star:1375
    * [django-allauth](https://github.com/pennersr/django-allauth) - Authentication app for Django that "just works." :star:4984
    * [django-oauth-toolkit](https://github.com/evonove/django-oauth-toolkit) - OAuth 2 goodies for Django. :star:1737
    * [oauthlib](https://github.com/idan/oauthlib) - A generic and thorough implementation of the OAuth request-signing logic. :star:1904
    * [python-oauth2](https://github.com/joestump/python-oauth2) - A fully tested, abstract interface to creating OAuth clients and servers. :star:2898
    * [python-social-auth](https://github.com/omab/python-social-auth) - An easy-to-setup social authentication mechanism. :star:2790
* JWT
    * [pyjwt](https://github.com/jpadilla/pyjwt) - JSON Web Token implementation in Python. :star:2992
    * [python-jose](https://github.com/mpdavis/python-jose/) - A JOSE implementation in Python. :star:567
    * [python-jwt](https://github.com/davedoesdev/python-jwt) - A module for generating and verifying JSON Web Tokens. :star:161

## Build Tools

*Compile software from source code.*

* [BitBake](http://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html) - A make-like build tool for embedded Linux.
* [buildout](http://www.buildout.org/en/latest/) - A build system for creating, assembling and deploying applications from multiple parts.
* [PlatformIO](https://github.com/platformio/platformio-core) - A console tool to build code with different development platforms. :star:3513
* [pybuilder](https://github.com/pybuilder/pybuilder) - A continuous build tool written in pure Python. :star:1145
* [SCons](http://www.scons.org/) - A software construction tool.

## Built-in Classes Enhancement

*Libraries for enhancing Python built-in classes.*

* [dataclasses](https://docs.python.org/3/library/dataclasses.html) - (Python standard library) Data classes.
* [attrs](https://github.com/python-attrs/attrs) - Replacement for `__init__`, `__eq__`, `__repr__`, etc. boilerplate in class definitions. :star:2847
* [bidict](https://github.com/jab/bidict) - Efficient, Pythonic bidirectional map data structures and related functionality.. :star:511
* [Box](https://github.com/cdgriffith/Box) - Python dictionaries with advanced dot notation access. :star:1319
* [DottedDict](https://github.com/carlosescri/DottedDict) - A library that provides a method of accessing lists and dicts with a dotted path notation. :star:74

## CMS

*Content Management Systems.*

* [wagtail](https://wagtail.io/) - A Django content management system.
* [django-cms](https://www.django-cms.org/en/) - An Open source enterprise CMS based on the Django.
* [feincms](https://github.com/feincms/feincms) - One of the most advanced Content Management Systems built on Django. :star:767
* [Kotti](https://github.com/Kotti/Kotti) - A high-level, Pythonic web application framework built on Pyramid. :star:338
* [mezzanine](https://github.com/stephenmcd/mezzanine) - A powerful, consistent, and flexible content management platform. :star:3952
* [plone](https://plone.org/) - A CMS built on top of the open source application server Zope.
* [quokka](https://github.com/rochacbruno/quokka) - Flexible, extensible, small CMS powered by Flask and MongoDB. :star:2129

## Caching

*Libraries for caching data.*

* [beaker](https://github.com/bbangert/beaker) - A WSGI middleware for sessions and caching. :star:427
* [django-cache-machine](https://github.com/django-cache-machine/django-cache-machine) - Automatic caching and invalidation for Django models. :star:761
* [django-cacheops](https://github.com/Suor/django-cacheops) - A slick ORM cache with automatic granular event-driven invalidation. :star:1122
* [dogpile.cache](http://dogpilecache.readthedocs.io/en/latest/) - dogpile.cache is next generation replacement for Beaker made by same authors.
* [HermesCache](https://pypi.org/project/HermesCache/) - Python caching library with tag-based invalidation and dogpile effect prevention.
* [pylibmc](https://github.com/lericson/pylibmc) - A Python wrapper around the [libmemcached](https://libmemcached.org/libMemcached.html) interface. :star:417
* [python-diskcache](http://www.grantjenks.com/docs/diskcache/) - SQLite and file backed cache backend with faster lookups than memcached and redis.

## ChatOps Tools

*Libraries for chatbot development.*

* [errbot](https://github.com/errbotio/errbot/) - The easiest and most popular chatbot to implement ChatOps. :star:2131

## Code Analysis

*Tools of static analysis, linters and code quality checkers. Also see [awesome-static-analysis](https://github.com/mre/awesome-static-analysis).*

* Code Analysis
    * [coala](https://github.com/coala/coala/) - Language independent and easily extendable code analysis application. :star:2897
    * [code2flow](https://github.com/scottrogowski/code2flow) - Turn your Python and JavaScript code into DOT flowcharts. :star:664
    * [prospector](https://github.com/PyCQA/prospector) - A tool to analyse Python code. :star:1170
    * [pycallgraph](https://github.com/gak/pycallgraph) - A library that visualises the flow (call graph) of your Python application. :star:1363
* Code Linters
    * [flake8](https://pypi.org/project/flake8/) - A wrapper around `pycodestyle`, `pyflakes` and McCabe.
        * [awesome-flake8-extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions) :star:240
    * [pylint](https://www.pylint.org/) - A fully customizable source code analyzer.
    * [pylama](https://github.com/klen/pylama) - A code audit tool for Python and JavaScript. :star:632
    * [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) - The strictest and most opinionated python linter ever. :star:556
* Code Formatters
    * [black](https://github.com/python/black) - The uncompromising Python code formatter. :star:13489
    * [yapf](https://github.com/google/yapf) - Yet another Python code formatter from Google. :star:9935
* Static Type Checkers, also see [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing)
    * [mypy](http://mypy-lang.org/) - Check variable types during compile time.
    * [pyre-check](https://github.com/facebook/pyre-check) - Performant type checking. :star:3130
* Static Type Annotations Generators
    * [MonkeyType](https://github.com/Instagram/MonkeyType) - A system for Python that generates static type annotations by collecting runtime types :star:2433

## Command-line Interface Development

*Libraries for building command-line applications.*

* Command-line Application Development
    * [cement](http://builtoncement.com/) - CLI Application Framework for Python.
    * [click](http://click.pocoo.org/dev/) - A package for creating beautiful command line interfaces in a composable way.
    * [cliff](https://docs.openstack.org/developer/cliff/) - A framework for creating command-line programs with multi-level commands.
    * [clint](https://github.com/kennethreitz/clint) - Python Command-line Application Tools. :star:2529
    * [docopt](http://docopt.org/) - Pythonic command line arguments parser.
    * [python-fire](https://github.com/google/python-fire) - A library for creating command line interfaces from absolutely any Python object. :star:15682
    * [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) - A library for building powerful interactive command lines. :star:5865
* Terminal Rendering
    * [asciimatics](https://github.com/peterbrittain/asciimatics) - A package to create full-screen text UIs (from interactive forms to ASCII animations). :star:1621
    * [bashplotlib](https://github.com/glamp/bashplotlib) - Making basic plots in the terminal. :star:1293
    * [colorama](https://pypi.org/project/colorama/) - Cross-platform colored terminal text.
    * [tqdm](https://github.com/tqdm/tqdm) - Fast, extensible progress bar for loops and CLI. :star:12303

## Command-line Tools

*Useful CLI-based tools for productivity.*

* Productivity Tools
    * [cookiecutter](https://github.com/audreyr/cookiecutter) - A command-line utility that creates projects from cookiecutters (project templates). :star:10610
    * [doitlive](https://github.com/sloria/doitlive) - A tool for live presentations in the terminal. :star:2600
    * [howdoi](https://github.com/gleitz/howdoi) - Instant coding answers via the command line. :star:7589
    * [PathPicker](https://github.com/facebook/PathPicker) - Select files out of bash output. :star:4254
    * [percol](https://github.com/mooz/percol) - Adds flavor of interactive selection to the traditional pipe concept on UNIX. :star:2835
    * [thefuck](https://github.com/nvbn/thefuck) - Correcting your previous console command. :star:50343
    * [tmuxp](https://github.com/tony/tmuxp) - A [tmux](https://github.com/tmux/tmux) session manager. :star:2577
    * [try](https://github.com/timofurrer/try) - A dead simple CLI to try out python packages - it's never been easier. :star:511
* CLI Enhancements
    * [httpie](https://github.com/jakubroztocil/httpie) - A command line HTTP client, a user-friendly cURL replacement. :star:43765
    * [kube-shell](https://github.com/cloudnativelabs/kube-shell) - An integrated shell for working with the Kubernetes CLI. :star:1448
    * [mycli](https://github.com/dbcli/mycli) - A Terminal Client for MySQL with AutoCompletion and Syntax Highlighting. :star:8169
    * [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting. :star:8278
    * [saws](https://github.com/donnemartin/saws) - A Supercharged [aws-cli](https://github.com/aws/aws-cli). :star:4269

## Compatibility

*Libraries for migrating from Python 2 to 3.*

* [python-future](http://python-future.org/index.html) - The missing compatibility layer between Python 2 and Python 3.
* [python-modernize](https://github.com/mitsuhiko/python-modernize) - Modernizes Python code for eventual Python 3 migration. :star:531
* [six](https://pypi.org/project/six/) - Python 2 and 3 compatibility utilities.

## Computer Vision

*Libraries for computer vision.*

* [OpenCV](https://opencv.org/) - Open Source Computer Vision Library.
* [pytesseract](https://github.com/madmaze/pytesseract) - Another wrapper for [Google Tesseract OCR](https://github.com/tesseract-ocr). :star:2475
* [SimpleCV](http://simplecv.org/) - An open source framework for building computer vision applications.

## Concurrency and Parallelism

*Libraries for concurrent and parallel execution. Also see [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio).*

* [concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) - (Python standard library) A high-level interface for asynchronously executing callables.
* [multiprocessing](https://docs.python.org/3/library/multiprocessing.html) - (Python standard library) Process-based parallelism.
* [eventlet](http://eventlet.net/) - Asynchronous framework with WSGI support.
* [gevent](http://www.gevent.org/) - A coroutine-based Python networking library that uses [greenlet](https://github.com/python-greenlet/greenlet).
* [uvloop](https://github.com/MagicStack/uvloop) - Ultra fast implementation of `asyncio` event loop on top of `libuv`. :star:6395
* [scoop](https://github.com/soravux/scoop) - Scalable Concurrent Operations in Python. :star:411

## Configuration

*Libraries for storing and parsing configuration options.*

* [configobj](https://github.com/DiffSK/configobj) - INI file parser with validation. :star:206
* [configparser](https://docs.python.org/3/library/configparser.html) - (Python standard library) INI file parser.
* [profig](https://profig.readthedocs.io/en/default/) - Config from multiple formats with value conversion.
* [python-decouple](https://github.com/henriquebastos/python-decouple) - Strict separation of settings from code. :star:1153

## Cryptography

* [cryptography](https://cryptography.io/en/latest/) - A package designed to expose cryptographic primitives and recipes to Python developers.
* [paramiko](https://github.com/paramiko/paramiko) - The leading native Python SSHv2 protocol library. :star:5820
* [passlib](https://passlib.readthedocs.io/en/stable/) - Secure password storage/hashing library, very high level.
* [pynacl](https://github.com/pyca/pynacl) - Python binding to the Networking and Cryptography (NaCl) library. :star:652

## Data Analysis

*Libraries for data analyzing.*

* [Blaze](https://github.com/blaze/blaze) - NumPy and Pandas interface to Big Data. :star:2764
* [Open Mining](https://github.com/mining/mining) - Business Intelligence (BI) in Pandas interface. :star:1041
* [Orange](https://orange.biolab.si/) - Data mining, data visualization, analysis and machine learning through visual programming or scripts.
* [Pandas](http://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.
* [Optimus](https://github.com/ironmussa/Optimus) - Agile Data Science Workflows made easy with PySpark. :star:797

## Data Validation

*Libraries for validating data. Used for forms in many cases.*

* [Cerberus](https://github.com/pyeve/cerberus) - A lightweight and extensible data validation library. :star:1870
* [colander](https://docs.pylonsproject.org/projects/colander/en/latest/) - Validating and deserializing data obtained via XML, JSON, an HTML form post.
* [jsonschema](https://github.com/Julian/jsonschema) - An implementation of [JSON Schema](http://json-schema.org/) for Python. :star:2541
* [schema](https://github.com/keleshev/schema) - A library for validating Python data structures. :star:1925
* [Schematics](https://github.com/schematics/schematics) - Data Structure Validation. :star:2284
* [valideer](https://github.com/podio/valideer) - Lightweight extensible data validation and adaptation library. :star:229
* [voluptuous](https://github.com/alecthomas/voluptuous) - A Python data validation library. :star:1548

## Data Visualization

*Libraries for visualizing data. Also see [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization).*

* [Altair](https://github.com/altair-viz/altair) - Declarative statistical visualization library for Python. :star:4303
* [Bokeh](https://github.com/bokeh/bokeh) - Interactive Web Plotting for Python. :star:12151
* [bqplot](https://github.com/bloomberg/bqplot) - Interactive Plotting Library for the Jupyter Notebook :star:2557
* [Dash](https://plot.ly/products/dash/) - Built on top of Flask, React and Plotly aimed at analytical web applications.
    * [awesome-dash](https://github.com/Acrotrend/awesome-dash) :star:568
* [plotnine](https://github.com/has2k1/plotnine) - A grammar of graphics for Python based on ggplot2. :star:1915
* [Matplotlib](http://matplotlib.org/) - A Python 2D plotting library.
* [Pygal](http://www.pygal.org/en/latest/) - A Python SVG Charts Creator.
* [PyGraphviz](https://pypi.org/project/pygraphviz/) - Python interface to [Graphviz](http://www.graphviz.org/).
* [PyQtGraph](http://www.pyqtgraph.org/) - Interactive and realtime 2D/3D/Image plotting and science/engineering widgets.
* [Seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization using Matplotlib. :star:6577
* [VisPy](https://github.com/vispy/vispy) - High-performance scientific visualization based on OpenGL. :star:2157

## Database

*Databases implemented in Python.*

* [pickleDB](https://github.com/patx/pickledb) - A simple and lightweight key-value store for Python. :star:427
* [tinydb](https://github.com/msiemens/tinydb) - A tiny, document-oriented database. :star:3167
* [ZODB](https://github.com/zopefoundation/ZODB) - A native object database for Python. A key-value and object graph database. :star:357

## Database Drivers

*Libraries for connecting and operating databases.*

* MySQL - [awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/)
    * [mysqlclient](https://github.com/PyMySQL/mysqlclient-python) - MySQL connector with Python 3 support ([mysql-python](https://sourceforge.net/projects/mysql-python/) fork). :star:1574
    * [PyMySQL](https://github.com/PyMySQL/PyMySQL) - A pure Python MySQL driver compatible to mysql-python. :star:5516
* PostgreSQL - [awesome-postgres](https://github.com/dhamaniasad/awesome-postgres)
    * [psycopg2](http://initd.org/psycopg/) - The most popular PostgreSQL adapter for Python.
    * [queries](https://github.com/gmr/queries) - A wrapper of the psycopg2 library for interacting with PostgreSQL. :star:214
* Other Relational Databases
    * [pymssql](http://www.pymssql.org/en/latest/) - A simple database interface to Microsoft SQL Server.
    * [SuperSQLite](https://github.com/plasticityai/supersqlite) - A supercharged SQLite library built on top of [apsw](https://github.com/rogerbinns/apsw). :star:607
* NoSQL Databases
    * [cassandra-driver](https://github.com/datastax/python-driver) - The Python Driver for Apache Cassandra. :star:1090
    * [happybase](https://github.com/wbolster/happybase) - A developer-friendly library for Apache HBase. :star:505
    * [kafka-python](https://github.com/dpkp/kafka-python) - The Python client for Apache Kafka. :star:3424
    * [py2neo](https://py2neo.org/) - A client library and toolkit for working with Neo4j.
    * [pymongo](https://github.com/mongodb/mongo-python-driver) - The official Python client for MongoDB. :star:2900
    * [redis-py](https://github.com/andymccurdy/redis-py) - The Python client for Redis. :star:8032
* Asynchronous Clients
    * [motor](https://github.com/mongodb/motor) - The async Python driver for MongoDB. :star:1349

## Date and Time

*Libraries for working with dates and times.*

* [Chronyk](https://github.com/KoffeinFlummi/Chronyk) - A Python 3 library for parsing human-written times and dates. :star:292
* [dateutil](https://github.com/dateutil/dateutil) - Extensions to the standard Python [datetime](https://docs.python.org/3/library/datetime.html) module. :star:1119
* [delorean](https://github.com/myusuf3/delorean/) - A library for clearing up the inconvenient truths that arise dealing with datetimes. :star:1608
* [moment](https://github.com/zachwill/moment) - A Python library for dealing with dates/times. Inspired by [Moment.js](http://momentjs.com/). :star:606
* [Pendulum](https://github.com/sdispater/pendulum) - Python datetimes made easy. :star:3590
* [PyTime](https://github.com/shinux/PyTime) - An easy-to-use Python module which aims to operate date/time/datetime by string. :star:137
* [pytz](https://launchpad.net/pytz) - World timezone definitions, modern and historical. Brings the [tz database](https://en.wikipedia.org/wiki/Tz_database) into Python.
* [when.py](https://github.com/dirn/When.py) - Providing user-friendly functions to help perform common date and time actions. :star:184
* [maya](https://github.com/kennethreitz/maya) - Datetimes for Humans. :star:3055

## Debugging Tools

*Libraries for debugging code.*

* pdb-like Debugger
    * [ipdb](https://github.com/gotcha/ipdb) - IPython-enabled [pdb](https://docs.python.org/3/library/pdb.html). :star:1082
    * [pdb++](https://github.com/antocuni/pdb) - Another drop-in replacement for pdb. :star:326
    * [pudb](https://github.com/inducer/pudb) - A full-screen, console-based Python debugger. :star:1592
    * [wdb](https://github.com/Kozea/wdb) - An improbable web debugger through WebSockets. :star:1427
* Tracing
    * [lptrace](https://github.com/khamidou/lptrace) - [strace](http://man7.org/linux/man-pages/man1/strace.1.html) for Python programs. :star:652
    * [manhole](https://github.com/ionelmc/python-manhole) - Debugging UNIX socket connections and present the stacktraces for all threads and an interactive prompt. :star:266
    * [pyringe](https://github.com/google/pyringe) - Debugger capable of attaching to and injecting code into Python processes. :star:1542
    * [python-hunter](https://github.com/ionelmc/python-hunter) - A flexible code tracing toolkit. :star:433
* Profiler
    * [line_profiler](https://github.com/rkern/line_profiler) - Line-by-line profiling. :star:3154
    * [memory_profiler](https://github.com/fabianp/memory_profiler) - Monitor Memory usage of Python code. :star:42
    * [profiling](https://github.com/what-studio/profiling) - An interactive Python profiler. :star:2927
    * [py-spy](https://github.com/benfred/py-spy) - A sampling profiler for Python programs. Written in Rust. :star:4678
    * [pyflame](https://github.com/uber/pyflame) - A ptracing profiler For Python. :star:2597
    * [vprof](https://github.com/nvdv/vprof) - Visual Python profiler. :star:3548
* Others
    * [icecream](https://github.com/gruns/icecream) - Inspect variables, expressions, and program execution with a single, simple function call. :star:1413
    * [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar) - Display various debug information for Django. :star:5664
    * [django-devserver](https://github.com/dcramer/django-devserver) - A drop-in replacement for Django's runserver. :star:1246
    * [flask-debugtoolbar](https://github.com/mgood/flask-debugtoolbar) - A port of the django-debug-toolbar to flask. :star:715
    * [pyelftools](https://github.com/eliben/pyelftools) - Parsing and analyzing ELF files and DWARF debugging information. :star:908

## Deep Learning

*Frameworks for Neural Networks and Deep Learning. Also see [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning).*

* [caffe](https://github.com/BVLC/caffe) - A fast open framework for deep learning.. :star:29415
* [keras](https://github.com/keras-team/keras) - A high-level neural networks library and capable of running on top of either TensorFlow or Theano. :star:45398
* [mxnet](https://github.com/dmlc/mxnet) - A deep learning framework designed for both efficiency and flexibility. :star:18037
* [pytorch](https://github.com/pytorch/pytorch) - Tensors and Dynamic neural networks in Python with strong GPU acceleration. :star:33689
* [SerpentAI](https://github.com/SerpentAI/SerpentAI) - Game agent framework. Use any video game as a deep learning sandbox. :star:5385
* [tensorflow](https://github.com/tensorflow/tensorflow) - The most popular Deep Learning framework created by Google. :star:137396
* [Theano](https://github.com/Theano/Theano) - A library for fast numerical computation. :star:8983

## DevOps Tools

*Software and libraries for DevOps.*

* [ansible](https://github.com/ansible/ansible) - A radically simple IT automation platform. :star:40375
* [cloudinit](https://cloudinit.readthedocs.io/en/latest/) - A multi-distribution package that handles early initialization of a cloud instance.
* [cuisine](https://github.com/sebastien/cuisine) - Chef-like functionality for Fabric. :star:1243
* [docker-compose](https://docs.docker.com/compose/) - Fast, isolated development environments using [Docker](https://www.docker.com/).
* [fabric](https://github.com/fabric/fabric) - A simple, Pythonic tool for remote execution and deployment. :star:11835
* [fabtools](https://github.com/fabtools/fabtools) - Tools for writing awesome Fabric files. :star:1203
* [honcho](https://github.com/nickstenning/honcho) - A Python clone of [Foreman](https://github.com/ddollar/foreman), for managing Procfile-based applications. :star:1293
* [OpenStack](https://www.openstack.org/) - Open source software for building private and public clouds.
* [pexpect](https://github.com/pexpect/pexpect) - Controlling interactive programs in a pseudo-terminal like GNU expect. :star:1699
* [psutil](https://github.com/giampaolo/psutil) - A cross-platform process and system utilities module. :star:5579
* [saltstack](https://github.com/saltstack/salt) - Infrastructure automation and management system. :star:10411
* [supervisor](https://github.com/Supervisor/supervisor) - Supervisor process control system for UNIX. :star:5769

## Distributed Computing

*Frameworks and libraries for Distributed Computing.*

* Batch Processing
    * [PySpark](https://pypi.org/project/pyspark/) - [Apache Spark](https://spark.apache.org/) Python API.
    * [dask](https://github.com/dask/dask) - A flexible parallel computing library for analytic computing. :star:5869
    * [luigi](https://github.com/spotify/luigi) - A module that helps you build complex pipelines of batch jobs. :star:12479
    * [mrjob](https://github.com/Yelp/mrjob) - Run MapReduce jobs on Hadoop or Amazon Web Services. :star:2462
    * [Ray](https://github.com/ray-project/ray/) - A system for parallel and distributed Python that unifies the machine learning ecosystem. :star:9318
* Stream Processing
    * [faust](https://github.com/robinhood/faust) - A stream processing library, porting the ideas from [Kafka Streams](https://kafka.apache.org/documentation/streams/) to Python. :star:3959
    * [streamparse](https://github.com/Parsely/streamparse) - Run Python code against real-time streams of data via [Apache Storm](http://storm.apache.org/). :star:1391

## Distribution

*Libraries to create packaged executables for release distribution.*

* [dh-virtualenv](https://github.com/spotify/dh-virtualenv) - Build and distribute a virtualenv as a Debian package. :star:1317
* [Nuitka](http://nuitka.net/) - Compile scripts, modules, packages to an executable or extension module.
* [py2app](http://pythonhosted.org/py2app/) - Freezes Python scripts (Mac OS X).
* [py2exe](http://www.py2exe.org/) - Freezes Python scripts (Windows).
* [PyInstaller](https://github.com/pyinstaller/pyinstaller) - Converts Python programs into stand-alone executables (cross-platform). :star:6003
* [pynsist](http://pynsist.readthedocs.io/en/latest/) - A tool to build Windows installers, installers bundle Python itself.

## Documentation

*Libraries for generating project documentation.*

* [sphinx](https://github.com/sphinx-doc/sphinx/) - Python Documentation generator. :star:2931
    * [awesome-sphinxdoc](https://github.com/yoloseem/awesome-sphinxdoc) :star:595
* [pdoc](https://github.com/mitmproxy/pdoc) - Epydoc replacement to auto generate API documentation for Python libraries. :star:613
* [pycco](https://github.com/pycco-docs/pycco) - The literate-programming-style documentation generator. :star:691

## Downloader

*Libraries for downloading.*

* [s3cmd](https://github.com/s3tools/s3cmd) - A command line tool for managing Amazon S3 and CloudFront. :star:3131
* [s4cmd](https://github.com/bloomreach/s4cmd) - Super S3 command line tool, good for higher performance. :star:931
* [you-get](https://you-get.org/) - A YouTube/Youku/Niconico video downloader written in Python 3.
* [youtube-dl](https://rg3.github.io/youtube-dl/) - A small command-line program to download videos from YouTube.

## E-commerce

*Frameworks and libraries for e-commerce and payments.*

* [alipay](https://github.com/lxneng/alipay) - Unofficial Alipay API for Python. :star:318
* [Cartridge](https://github.com/stephenmcd/cartridge) - A shopping cart app built using the Mezzanine. :star:601
* [django-oscar](http://oscarcommerce.com/) - An open-source e-commerce framework for Django.
* [django-shop](https://github.com/awesto/django-shop) - A Django based shop system. :star:2014
* [merchant](https://github.com/agiliq/merchant) - A Django app to accept payments from various payment processors. :star:935
* [money](https://github.com/carlospalol/money) - `Money` class with optional CLDR-backed locale-aware formatting and an extensible currency exchange. :star:173
* [python-currencies](https://github.com/Alir3z4/python-currencies) - Display money format and its filthy currencies. :star:42
* [forex-python](https://github.com/MicroPyramid/forex-python) - Foreign exchange rates, Bitcoin price index and currency conversion. :star:273
* [saleor](http://getsaleor.com/) - An e-commerce storefront for Django.
* [shoop](https://www.shuup.com/en/) - An open source E-Commerce platform based on Django.

## Editor Plugins and IDEs

* Emacs
    * [elpy](https://github.com/jorgenschaefer/elpy) - Emacs Python Development Environment. :star:1501
* Sublime Text
    * [anaconda](https://github.com/DamnWidget/anaconda) - Anaconda turns your Sublime Text 3 in a full featured Python development IDE. :star:2015
    * [SublimeJEDI](https://github.com/srusskih/SublimeJEDI) - A Sublime Text plugin to the awesome auto-complete library Jedi. :star:876
* Vim
    * [jedi-vim](https://github.com/davidhalter/jedi-vim) - Vim bindings for the Jedi auto-completion library for Python. :star:4174
    * [python-mode](https://github.com/python-mode/python-mode) - An all in one plugin for turning Vim into a Python IDE. :star:4822
    * [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) - Includes [Jedi](https://github.com/davidhalter/jedi)-based completion engine for Python. :star:20103
* Visual Studio
    * [PTVS](https://github.com/Microsoft/PTVS) - Python Tools for Visual Studio. :star:2217
* Visual Studio Code
    * [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) - The official VSCode extension with rich support for Python.
* IDE
    * [PyCharm](https://www.jetbrains.com/pycharm/) - Commercial Python IDE by JetBrains. Has free community edition available.
    * [spyder](https://github.com/spyder-ide/spyder) - Open Source Python IDE. :star:4883

## Email

*Libraries for sending and parsing email.*

* [envelopes](http://tomekwojcik.github.io/envelopes/) - Mailing for human beings.
* [flanker](https://github.com/mailgun/flanker) - An email address and Mime parsing library. :star:1358
* [imbox](https://github.com/martinrusev/imbox) - Python IMAP for Humans. :star:861
* [inbox.py](https://github.com/kennethreitz/inbox.py) - Python SMTP Server for Humans. :star:1475
* [lamson](https://github.com/zedshaw/lamson) - Pythonic SMTP Application Server. :star:684
* [Marrow Mailer](https://github.com/marrow/mailer) - High-performance extensible mail delivery framework. :star:175
* [modoboa](https://github.com/modoboa/modoboa) - A mail hosting and management platform including a modern and simplified Web UI. :star:1388
* [Nylas Sync Engine](https://github.com/nylas/sync-engine) - Providing a RESTful API on top of a powerful email sync platform. :star:3481
* [yagmail](https://github.com/kootenpv/yagmail) - Yet another Gmail/SMTP client. :star:1570

## Environment Management

*Libraries for Python version and virtual environment management.*

* [pyenv](https://github.com/pyenv/pyenv) - Simple Python version management. :star:17207
* [pipenv](https://github.com/pypa/pipenv) - Python Development Workflow for Humans. :star:18853
* [poetry](https://github.com/sdispater/poetry) - Python dependency management and packaging made easy. :star:6927
* [virtualenv](https://github.com/pypa/virtualenv) - A tool to create isolated Python environments. :star:3270

## Files

*Libraries for file manipulation and MIME type detection.*

* [mimetypes](https://docs.python.org/3/library/mimetypes.html) - (Python standard library) Map filenames to MIME types.
* [path.py](https://github.com/jaraco/path.py) - A module wrapper for [os.path](https://docs.python.org/3/library/os.path.html). :star:891
* [pathlib](https://docs.python.org/3/library/pathlib.html) - (Python standard library) An cross-platform, object-oriented path library.
* [PyFilesystem2](https://github.com/pyfilesystem/pyfilesystem2) - Python's filesystem abstraction layer. :star:957
* [python-magic](https://github.com/ahupp/python-magic) - A Python interface to the libmagic file type identification library. :star:1479
* [Unipath](https://github.com/mikeorr/Unipath) - An object-oriented approach to file/directory operations. :star:485
* [watchdog](https://github.com/gorakhargosh/watchdog) - API and shell utilities to monitor file system events. :star:3773

## Foreign Function Interface

*Libraries for providing foreign function interface.*

* [cffi](https://pypi.org/project/cffi/) - Foreign Function Interface for Python calling C code.
* [ctypes](https://docs.python.org/3/library/ctypes.html) - (Python standard library) Foreign Function Interface for Python calling C code.
* [PyCUDA](https://mathema.tician.de/software/pycuda/) - A Python wrapper for Nvidia's CUDA API.
* [SWIG](http://www.swig.org/Doc1.3/Python.html) - Simplified Wrapper and Interface Generator.

## Forms

*Libraries for working with forms.*

* [Deform](https://github.com/Pylons/deform) - Python HTML form generation library influenced by the formish form generation library. :star:323
* [django-bootstrap3](https://github.com/dyve/django-bootstrap3) - Bootstrap 3 integration with Django. :star:2162
* [django-bootstrap4](https://github.com/zostera/django-bootstrap4) - Bootstrap 4 integration with Django. :star:634
* [django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms) - A Django app which lets you create beautiful forms in a very elegant and DRY way. :star:3671
* [django-remote-forms](https://github.com/WiserTogether/django-remote-forms) - A platform independent Django form serializer. :star:196
* [WTForms](https://github.com/wtforms/wtforms) - A flexible forms validation and rendering library. :star:1014

## Functional Programming

*Functional Programming with Python.*

* [Coconut](http://coconut-lang.org/) - Coconut is a variant of Python built for simple, elegant, Pythonic functional programming.
* [CyToolz](https://github.com/pytoolz/cytoolz/) - Cython implementation of Toolz: High performance functional utilities. :star:669
* [fn.py](https://github.com/kachayev/fn.py) - Functional programming in Python: implementation of missing features to enjoy FP. :star:2917
* [funcy](https://github.com/Suor/funcy) - A fancy and practical functional tools. :star:2175
* [Toolz](https://github.com/pytoolz/toolz) - A collection of functional utilities for iterators, functions, and dictionaries. :star:2513

## GUI Development

*Libraries for working with graphical user interface applications.*

* [curses](https://docs.python.org/3/library/curses.html) - Built-in wrapper for [ncurses](http://www.gnu.org/software/ncurses/) used to create terminal GUI applications.
* [Eel](https://github.com/ChrisKnott/Eel) - A library for making simple Electron-like offline HTML/JS GUI apps. :star:3080
* [enaml](https://github.com/nucleic/enaml) - Creating beautiful user-interfaces with Declarative Syntax like QML. :star:810
* [Flexx](https://github.com/zoofIO/flexx) - Flexx is a pure Python toolkit for creating GUI's, that uses web technology for its rendering. :star:2139
* [Gooey](https://github.com/chriskiehl/Gooey) - Turn command line programs into a full GUI application with one line. :star:8071
* [kivy](https://kivy.org/) - A library for creating NUI applications, running on Windows, Linux, Mac OS X, Android and iOS.
* [pyglet](https://bitbucket.org/pyglet/pyglet/wiki/Home) - A cross-platform windowing and multimedia library for Python.
* [PyGObject](https://wiki.gnome.org/Projects/PyGObject) - Python Bindings for GLib/GObject/GIO/GTK+ (GTK+3).
* [PyQt](https://riverbankcomputing.com/software/pyqt/intro) - Python bindings for the [Qt](https://www.qt.io/) cross-platform application and UI framework.
* [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI) - Wrapper for tkinter, Qt, WxPython and Remi. :star:2506
* [pywebview](https://github.com/r0x0r/pywebview/) - A lightweight cross-platform native wrapper around a webview component. :star:1583
* [Tkinter](https://wiki.python.org/moin/TkInter) - Tkinter is Python's de-facto standard GUI package.
* [Toga](https://github.com/pybee/toga) - A Python native, OS native GUI toolkit. :star:2140
* [urwid](http://urwid.org/) - A library for creating terminal GUI applications with strong support for widgets, events, rich colors, etc.
* [wxPython](https://wxpython.org/) - A blending of the wxWidgets C++ class library with the Python.

## Game Development

*Awesome game development libraries.*

* [Cocos2d](http://cocos2d.org/) - cocos2d is a framework for building 2D games, demos, and other graphical/interactive applications.
* [Harfang3D](http://www.harfang3d.com) - Python framework for 3D, VR and game development.
* [Panda3D](https://www.panda3d.org/) - 3D game engine developed by Disney.
* [Pygame](http://www.pygame.org/news.html) - Pygame is a set of Python modules designed for writing games.
* [PyOgre](http://www.ogre3d.org/tikiwiki/PyOgre) - Python bindings for the Ogre 3D render engine, can be used for games, simulations, anything 3D.
* [PyOpenGL](http://pyopengl.sourceforge.net/) - Python ctypes bindings for OpenGL and it's related APIs.
* [PySDL2](https://pysdl2.readthedocs.io) - A ctypes based wrapper for the SDL2 library.
* [RenPy](https://www.renpy.org/) - A Visual Novel engine.

## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [django-countries](https://github.com/SmileyChris/django-countries) - A Django app that provides a country field for models and forms. :star:728
* [GeoDjango](https://docs.djangoproject.com/en/dev/ref/contrib/gis/) - A world-class geographic web framework.
* [GeoIP](https://github.com/maxmind/geoip-api-python) - Python API for MaxMind GeoIP Legacy Database. :star:197
* [geojson](https://github.com/frewsxcv/python-geojson) - Python bindings and utilities for GeoJSON. :star:482
* [geopy](https://github.com/geopy/geopy) - Python Geocoding Toolbox. :star:2625
* [pygeoip](https://github.com/appliedsec/pygeoip) - Pure Python GeoIP API. :star:481

## HTML Manipulation

*Libraries for working with HTML and XML.*

* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Providing Pythonic idioms for iterating, searching, and modifying HTML or XML.
* [bleach](https://github.com/mozilla/bleach) - A whitelist-based HTML sanitization and text linkification library. :star:1808
* [cssutils](https://pypi.org/project/cssutils/) - A CSS library for Python.
* [html5lib](https://github.com/html5lib/html5lib-python) - A standards-compliant library for parsing and serializing HTML documents and fragments. :star:807
* [lxml](http://lxml.de/) - A very fast, easy-to-use and versatile library for handling HTML and XML.
* [MarkupSafe](https://github.com/pallets/markupsafe) - Implements a XML/HTML/XHTML Markup safe string for Python. :star:288
* [pyquery](https://github.com/gawel/pyquery) - A jQuery-like library for parsing HTML. :star:1780
* [untangle](https://github.com/stchris/untangle) - Converts XML documents to Python objects for easy access. :star:432
* [WeasyPrint](http://weasyprint.org) - A visual rendering engine for HTML and CSS that can export to PDF.
* [xmldataset](https://xmldataset.readthedocs.io/en/latest/) - Simple XML Parsing.
* [xmltodict](https://github.com/martinblech/xmltodict) - Working with XML feel like you are working with JSON. :star:3697

## HTTP Clients

*Libraries for working with HTTP.*

* [grequests](https://github.com/kennethreitz/grequests) - requests + gevent for asynchronous HTTP requests. :star:3219
* [httplib2](https://github.com/httplib2/httplib2) - Comprehensive HTTP client library. :star:336
* [requests](https://requests.kennethreitz.org/en/master/) - HTTP Requests for Humans.
* [treq](https://github.com/twisted/treq) - Python requests like API built on top of Twisted's HTTP client. :star:481
* [urllib3](https://github.com/shazow/urllib3) - A HTTP library with thread-safe connection pooling, file post support, sanity friendly. :star:2172

## Hardware

*Libraries for programming with hardware.*

* [ino](http://inotool.org/) - Command line toolkit for working with [Arduino](https://www.arduino.cc/).
* [keyboard](https://github.com/boppreh/keyboard) - Hook and simulate global keyboard events on Windows and Linux. :star:1631
* [mouse](https://github.com/boppreh/mouse) - Hook and simulate global mouse events on Windows and Linux. :star:239
* [Pingo](http://www.pingo.io/) - Pingo provides a uniform API to program devices like the Raspberry Pi, pcDuino, Intel Galileo, etc.
* [PyUserInput](https://github.com/SavinaRoja/PyUserInput) - A module for cross-platform control of the mouse and keyboard. :star:879
* [scapy](https://github.com/secdev/scapy) - A brilliant packet manipulation library. :star:4551
* [wifi](https://github.com/rockymeza/wifi) - A Python library and command line tool for working with WiFi on Linux. :star:256

## Image Processing

*Libraries for manipulating images.*

* [hmap](https://github.com/rossgoodwin/hmap) - Image histogram remapping. :star:172
* [imgSeek](https://sourceforge.net/projects/imgseek/) - A project for searching a collection of images using visual similarity.
* [nude.py](https://github.com/hhatto/nude.py) - Nudity detection. :star:689
* [pagan](https://github.com/daboth/pagan) - Retro identicon (Avatar) generation based on input string and hash. :star:169
* [pillow](https://github.com/python-pillow/Pillow) - Pillow is the friendly [PIL](http://www.pythonware.com/products/pil/) fork. :star:6787
* [pyBarcode](https://pythonhosted.org/pyBarcode/) - Create barcodes in Python without needing PIL.
* [pygram](https://github.com/ajkumar25/pygram) - Instagram-like image filters. :star:88
* [python-qrcode](https://github.com/lincolnloop/python-qrcode) - A pure Python QR Code generator. :star:1925
* [Quads](https://github.com/fogleman/Quads) - Computer art based on quadtrees. :star:898
* [scikit-image](http://scikit-image.org/) - A Python library for (scientific) image processing.
* [thumbor](https://github.com/thumbor/thumbor) - A smart imaging service. It enables on-demand crop, re-sizing and flipping of images. :star:7290
* [wand](https://github.com/dahlia/wand) - Python bindings for [MagickWand](http://www.imagemagick.org/script/magick-wand.php), C API for ImageMagick. :star:923

## Implementations

*Implementations of Python.*

* [CPython](https://github.com/python/cpython) - **Default, most widely used implementation of the Python programming language written in C.** :star:27758
* [Cython](http://cython.org/) - Optimizing Static Compiler for Python.
* [CLPython](https://github.com/metawilm/cl-python) - Implementation of the Python programming language written in Common Lisp. :star:277
* [Grumpy](https://github.com/google/grumpy) - More compiler than interpreter as more powerful CPython2.7 replacement (alpha). :star:9848
* [IronPython](https://github.com/IronLanguages/ironpython3) - Implementation of the Python programming language written in C#. :star:992
* [Jython](https://hg.python.org/jython) - Implementation of Python programming language written in Java for the JVM.
* [MicroPython](https://github.com/micropython/micropython) - A lean and efficient Python programming language implementation. :star:9496
* [Numba](http://numba.pydata.org/) - Python JIT compiler to LLVM aimed at scientific Python.
* [PeachPy](https://github.com/Maratyszcza/PeachPy) - x86-64 assembler embedded in Python. :star:1332
* [Pyjion](https://github.com/Microsoft/Pyjion) - A JIT for Python based upon CoreCLR. :star:1283
* [PyPy](https://bitbucket.org/pypy/pypy) - A very fast and compliant implementation of the Python language.
* [Pyston](https://github.com/dropbox/pyston) - A Python implementation using JIT techniques. :star:4483
* [Stackless Python](https://github.com/stackless-dev/stackless) - An enhanced version of the Python programming language. :star:505

## Interactive Interpreter

*Interactive Python interpreters (REPL).*

* [bpython](https://github.com/bpython/bpython) - A fancy interface to the Python interpreter. :star:1331
* [Jupyter Notebook (IPython)](https://jupyter.org) - A rich toolkit to help you make the most out of using Python interactively.
    * [awesome-jupyter](https://github.com/markusschanta/awesome-jupyter) :star:1382
* [ptpython](https://github.com/jonathanslenders/ptpython) - Advanced Python REPL built on top of the [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit). :star:3446

## Internationalization

*Libraries for working with i18n.*

* [Babel](http://babel.pocoo.org/en/latest/) - An internationalization library for Python.
* [PyICU](https://github.com/ovalhub/pyicu) - A wrapper of International Components for Unicode C++ library ([ICU](http://site.icu-project.org/)). :star:102

## Job Scheduler

*Libraries for scheduling jobs.*

* [APScheduler](http://apscheduler.readthedocs.io/en/latest/) - A light but powerful in-process task scheduler that lets you schedule functions.
* [django-schedule](https://github.com/thauber/django-schedule) - A calendaring app for Django. :star:758
* [doit](http://pydoit.org/) - A task runner and build tool.
* [gunnery](https://github.com/gunnery/gunnery) - Multipurpose task execution tool for distributed systems with web-based interface. :star:698
* [Joblib](https://joblib.readthedocs.io/) - A set of tools to provide lightweight pipelining in Python.
* [Plan](https://github.com/fengsp/plan) - Writing crontab file in Python like a charm. :star:1088
* [schedule](https://github.com/dbader/schedule) - Python job scheduling for humans. :star:6740
* [Spiff](https://github.com/knipknap/SpiffWorkflow) - A powerful workflow engine implemented in pure Python. :star:814
* [TaskFlow](https://docs.openstack.org/developer/taskflow/) - A Python library that helps to make task execution easy, consistent and reliable.
* [Airflow](https://airflow.apache.org/) - Airflow is a platform to programmatically author, schedule and monitor workflows.

## Logging

*Libraries for generating and working with logs.*

* [Eliot](https://github.com/ScatterHQ/eliot) - Logging for complex & distributed systems. :star:653
* [logbook](http://logbook.readthedocs.io/en/stable/) - Logging replacement for Python.
* [logging](https://docs.python.org/3/library/logging.html) - (Python standard library) Logging facility for Python.
* [raven](https://github.com/getsentry/raven-python) - Python client for Sentry, a log/error tracking, crash reporting and aggregation platform for web applications. :star:1653

## Machine Learning

*Libraries for Machine Learning. Also see [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python).*

* [H2O](https://github.com/h2oai/h2o-3) - Open Source Fast Scalable Machine Learning Platform. :star:4454
* [Metrics](https://github.com/benhamner/Metrics) - Machine learning evaluation metrics. :star:1224
* [NuPIC](https://github.com/numenta/nupic) - Numenta Platform for Intelligent Computing. :star:6023
* [scikit-learn](http://scikit-learn.org/) - The most popular Python library for Machine Learning.
* [Spark ML](http://spark.apache.org/docs/latest/ml-guide.html) - [Apache Spark](http://spark.apache.org/)'s scalable Machine Learning library.
* [vowpal_porpoise](https://github.com/josephreisinger/vowpal_porpoise) - A lightweight Python wrapper for [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/). :star:152
* [xgboost](https://github.com/dmlc/xgboost) - A scalable, portable, and distributed gradient boosting library. :star:17730

## Microsoft Windows

*Python programming on Microsoft Windows.*

* [Python(x,y)](http://python-xy.github.io/) - Scientific-applications-oriented Python Distribution based on Qt and Spyder.
* [pythonlibs](http://www.lfd.uci.edu/~gohlke/pythonlibs/) - Unofficial Windows binaries for Python extension packages.
* [PythonNet](https://github.com/pythonnet/pythonnet) - Python Integration with the .NET Common Language Runtime (CLR). :star:1823
* [PyWin32](https://github.com/mhammond/pywin32) - Python Extensions for Windows. :star:1841
* [WinPython](https://winpython.github.io/) - Portable development environment for Windows 7/8.

## Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*

* [blinker](https://github.com/jek/blinker) - A fast Python in-process signal/event dispatching system. :star:967
* [boltons](https://github.com/mahmoud/boltons) - A set of pure-Python utilities. :star:4988
* [itsdangerous](https://github.com/pallets/itsdangerous) - Various helpers to pass trusted data to untrusted environments. :star:1869
* [pluginbase](https://github.com/mitsuhiko/pluginbase) - A simple but flexible plugin system for Python. :star:838
* [tryton](http://www.tryton.org/) - A general purpose business framework.

## Natural Language Processing

*Libraries for working with human languages.*

- General
    * [gensim](https://github.com/RaRe-Technologies/gensim) - Topic Modeling for Humans. :star:10098
    * [langid.py](https://github.com/saffsd/langid.py) - Stand-alone language identification system. :star:1461
    * [nltk](http://www.nltk.org/) - A leading platform for building Python programs to work with human language data.
    * [pattern](https://github.com/clips/pattern) - A web mining module for the Python. :star:7210
    * [polyglot](https://github.com/aboSamoor/polyglot) - Natural language pipeline supporting hundreds of languages. :star:1443
    * [pytext](https://github.com/facebookresearch/pytext) - A natural language modeling framework based on PyTorch. :star:5552
    * [PyTorch-NLP](https://github.com/PetrochukM/PyTorch-NLP) - A toolkit enabling rapid deep learning NLP prototyping for research. :star:1505
    * [spacy](https://spacy.io/) - A library for industrial-strength natural language processing in Python and Cython.
    * [stanfordnlp](https://github.com/stanfordnlp/stanfordnlp) - The Stanford NLP Group's official Python library, supporting 50+ languages. :star:2577
- Chinese
    * [jieba](https://github.com/fxsjy/jieba) - The most popular Chinese text segmentation library. :star:20816
    * [pkuseg-python](https://github.com/lancopku/pkuseg-python) - A toolkit for Chinese word segmentation in various domains. :star:4314
    * [snownlp](https://github.com/isnowfy/snownlp) - A library for processing Chinese text. :star:4397
    * [funNLP](https://github.com/fighting41love/funNLP) - A collection of tools and datasets for Chinese NLP. :star:14400

## Network Virtualization

*Tools and libraries for Virtual Networking and SDN (Software Defined Networking).*

* [mininet](https://github.com/mininet/mininet) - A popular network emulator and API written in Python. :star:3115
* [napalm](https://github.com/napalm-automation/napalm) - Cross-vendor API to manipulate network devices. :star:1351
* [pox](https://github.com/noxrepo/pox) - A Python-based SDN control applications, such as OpenFlow SDN controllers. :star:468

## News Feed

*Libraries for building user's activities.*

* [django-activity-stream](https://github.com/justquick/django-activity-stream) - Generating generic activity streams from the actions on your site. :star:1651
* [Stream Framework](https://github.com/tschellenbach/Stream-Framework) - Building news feed and notification systems using Cassandra and Redis. :star:4166

## ORM

*Libraries that implement Object-Relational Mapping or data mapping techniques.*

* Relational Databases
    * [Django Models](https://docs.djangoproject.com/en/dev/topics/db/models/) - The Django ORM.
    * [SQLAlchemy](https://www.sqlalchemy.org/) - The Python SQL Toolkit and Object Relational Mapper.
        * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy) :star:1972
    * [dataset](https://github.com/pudo/dataset) - Store Python dicts in a database - works with SQLite, MySQL, and PostgreSQL. :star:3653
    * [orator](https://github.com/sdispater/orator) -  The Orator ORM provides a simple yet beautiful ActiveRecord implementation. :star:995
    * [orm](https://github.com/encode/orm) - An async ORM. :star:644
    * [peewee](https://github.com/coleifer/peewee) - A small, expressive ORM. :star:7007
    * [pony](https://github.com/ponyorm/pony/) - ORM that provides a generator-oriented interface to SQL. :star:1981
    * [pydal](https://github.com/web2py/pydal/) - A pure Python Database Abstraction Layer. :star:285
* NoSQL Databases
    * [hot-redis](https://github.com/stephenmcd/hot-redis) - Rich Python data types for Redis. :star:254
    * [mongoengine](https://github.com/MongoEngine/mongoengine) - A Python Object-Document-Mapper for working with MongoDB. :star:2960
    * [PynamoDB](https://github.com/pynamodb/PynamoDB) - A Pythonic interface for [Amazon DynamoDB](https://aws.amazon.com/dynamodb/). :star:1063
    * [redisco](https://github.com/kiddouk/redisco) - A Python Library for Simple Models and Containers Persisted in Redis. :star:431

## Package Management

*Libraries for package and dependency management.*

* [pip](https://pip.pypa.io/en/stable/) - The Python package and dependency manager.
    * [PyPI](https://pypi.org/)
    * [pip-tools](https://github.com/jazzband/pip-tools) - A set of tools to keep your pinned Python dependencies fresh. :star:3730
* [conda](https://github.com/conda/conda/) - Cross-platform, Python-agnostic binary package manager. :star:3266

## Package Repositories

*Local PyPI repository server and proxies.*

* [warehouse](https://github.com/pypa/warehouse) - Next generation Python Package Repository (PyPI). :star:2316
* [bandersnatch](https://github.com/pypa/bandersnatch/) - PyPI mirroring tool provided by Python Packaging Authority (PyPA). :star:126
* [devpi](https://github.com/devpi/devpi) - PyPI server and packaging/testing/release tool. :star:328
* [localshop](https://github.com/jazzband/localshop) - Local PyPI server (custom packages and auto-mirroring of pypi). :star:356

## Permissions

*Libraries that allow or deny users access to data or functionality.*

* [django-guardian](https://github.com/django-guardian/django-guardian) - Implementation of per object permissions for Django 1.2+ :star:2442
* [django-rules](https://github.com/dfunckt/django-rules) - A tiny but powerful app providing object-level permissions to Django, without requiring a database. :star:957

## Processes

*Libraries for starting and communicating with OS processes.*

* [delegator.py](https://github.com/amitt001/delegator.py) - [Subprocesses](https://docs.python.org/3/library/subprocess.html) for Humans 2.0. :star:1412
* [sarge](https://sarge.readthedocs.io/en/latest/) - Yet another wrapper for subprocess.
* [sh](https://github.com/amoffat/sh) - A full-fledged subprocess replacement for Python. :star:5100

## Recommender Systems

*Libraries for building recommender systems.*

* [annoy](https://github.com/spotify/annoy) - Approximate Nearest Neighbors in C++/Python optimized for memory usage. :star:6231
* [fastFM](https://github.com/ibayer/fastFM) - A library for Factorization Machines. :star:784
* [implicit](https://github.com/benfred/implicit) - A fast Python implementation of collaborative filtering for implicit datasets. :star:1700
* [libffm](https://github.com/guestwalk/libffm) - A library for Field-aware Factorization Machine (FFM). :star:1325
* [lightfm](https://github.com/lyst/lightfm) - A Python implementation of a number of popular recommendation algorithms. :star:2823
* [spotlight](https://github.com/maciejkula/spotlight) - Deep recommender models using PyTorch. :star:1915
* [Surprise](https://github.com/NicolasHug/Surprise) - A scikit for building and analyzing recommender systems. :star:3590
* [tensorrec](https://github.com/jfkirk/tensorrec) - A Recommendation Engine Framework in TensorFlow. :star:975

## RESTful API

*Libraries for building RESTful APIs.*

* Django
    * [django-rest-framework](http://www.django-rest-framework.org/) - A powerful and flexible toolkit to build web APIs.
    * [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps.
* Flask
    * [eve](https://github.com/pyeve/eve) - REST API framework powered by Flask, MongoDB and good intentions. :star:5892
    * [flask-api](https://github.com/flask-api/flask-api) - Browsable Web APIs for Flask. :star:1102
    * [flask-restful](https://github.com/flask-restful/flask-restful) - Quickly building REST APIs for Flask. :star:5185
* Pyramid
    * [cornice](https://github.com/Cornices/cornice) - A RESTful framework for Pyramid. :star:350
* Framework agnostic
    * [apistar](https://github.com/encode/apistar) - A smart Web API framework, designed for Python 3. :star:5356
    * [falcon](https://github.com/falconry/falcon) - A high-performance framework for building cloud APIs and web app backends. :star:7239
    * [fastapi](https://github.com/tiangolo/fastapi) - A modern, fast, web framework for building APIs with Python 3.6+ based on standard Python type hints. :star:5718
    * [hug](https://github.com/hugapi/hug) - A Python 3 framework for cleanly exposing APIs. :star:6012
    * [sandman2](https://github.com/jeffknupp/sandman2) - Automated REST APIs for existing database-driven systems. :star:1415
    * [sanic](https://github.com/huge-success/sanic) - A Python 3.6+ web server and web framework that's written to go fast. :star:13081
    * [vibora](https://vibora.io/) - Fast, efficient and asynchronous Web framework inspired by Flask.

## Robotics

*Libraries for robotics.*

* [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) - This is a compilation of various robotics algorithms with visualizations. :star:7291
* [rospy](http://wiki.ros.org/rospy) - This is a library for ROS (Robot Operating System).

## RPC Servers

*RPC-compatible servers.*

* [zeroRPC](https://github.com/0rpc/zerorpc-python) - zerorpc is a flexible RPC implementation based on [ZeroMQ](http://zeromq.org/) and [MessagePack](http://msgpack.org/). :star:2534

## Science

*Libraries for scientific computing. Also see [Python-for-Scientists](https://github.com/TomNicholas/Python-for-Scientists)*

* [astropy](http://www.astropy.org/) - A community Python library for Astronomy.
* [bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen) - Providing best-practice pipelines for fully automated high throughput sequencing analysis. :star:705
* [bccb](https://github.com/chapmanb/bcbb) - Collection of useful code related to biological analysis. :star:452
* [Biopython](http://biopython.org/wiki/Main_Page) - Biopython is a set of freely available tools for biological computation.
* [cclib](http://cclib.github.io/) - A library for parsing and interpreting the results of computational chemistry packages.
* [Colour](http://colour-science.org/) - Implementing a comprehensive number of colour theory transformations and algorithms.
* [NetworkX](https://networkx.github.io/) - A high-productivity software for complex networks.
* [NIPY](http://nipy.org) - A collection of neuroimaging toolkits.
* [NumPy](http://www.numpy.org/) - A fundamental package for scientific computing with Python.
* [Open Babel](http://openbabel.org/wiki/Main_Page) - A chemical toolbox designed to speak the many languages of chemical data.
* [ObsPy](https://github.com/obspy/obspy/wiki/) - A Python toolbox for seismology. :star:563
* [PyDy](http://www.pydy.org/) - Short for Python Dynamics, used to assist with workflow in the modeling of dynamic motion.
* [PyMC](https://github.com/pymc-devs/pymc3) - Markov Chain Monte Carlo sampling toolkit. :star:4599
* [QuTiP](http://qutip.org/) - Quantum Toolbox in Python.
* [RDKit](http://www.rdkit.org/) - Cheminformatics and Machine Learning Software.
* [SciPy](https://www.scipy.org/) - A Python-based ecosystem of open-source software for mathematics, science, and engineering.
* [statsmodels](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python. :star:4429
* [SymPy](https://github.com/sympy/sympy) - A Python library for symbolic mathematics. :star:6370
* [Zipline](https://github.com/quantopian/zipline) - A Pythonic algorithmic trading library. :star:10120
* [SimPy](https://bitbucket.org/simpy/simpy) -  A process-based discrete-event simulation framework.

## Search

*Libraries and software for indexing and performing search queries on data.*

* [elasticsearch-py](https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html) - The official low-level Python client for [Elasticsearch](https://www.elastic.co/products/elasticsearch).
* [elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) - The official high-level Python client for Elasticsearch. :star:2655
* [django-haystack](https://github.com/django-haystack/django-haystack) - Modular search for Django. :star:2854
* [pysolr](https://github.com/django-haystack/pysolr) - A lightweight Python wrapper for [Apache Solr](https://lucene.apache.org/solr/). :star:530
* [whoosh](http://whoosh.readthedocs.io/en/latest/) - A fast, pure Python search engine library.

## Serialization

*Libraries for serializing complex data types*

* [marshmallow](https://github.com/marshmallow-code/marshmallow) - A lightweight library for converting complex objects to and from simple Python datatypes. :star:4225
* [pysimdjson](https://github.com/TkTech/pysimdjson) - A Python bindings for [simdjson](https://github.com/lemire/simdjson). :star:190
* [python-rapidjson](https://github.com/python-rapidjson/python-rapidjson) - A Python wrapper around [RapidJSON](https://github.com/Tencent/rapidjson). :star:350
* [ultrajson](https://github.com/esnme/ultrajson) - A fast JSON decoder and encoder written in C with Python bindings. :star:2547

## Serverless Frameworks

*Frameworks for developing serverless Python code.*

* [python-lambda](https://github.com/nficano/python-lambda) - A toolkit for developing and deploying Python code in AWS Lambda. :star:1037
* [Zappa](https://github.com/Miserlou/Zappa) - A tool for deploying WSGI applications on AWS Lambda and API Gateway. :star:9904

## Specific Formats Processing

*Libraries for parsing and manipulating specific text formats.*

* General
    * [tablib](https://github.com/kennethreitz/tablib) - A module for Tabular Datasets in XLS, CSV, JSON, YAML. :star:3571
* Office
    * [openpyxl](https://openpyxl.readthedocs.io/en/stable/) - A library for reading and writing Excel 2010 xlsx/xlsm/xltx/xltm files.
    * [pyexcel](https://github.com/pyexcel/pyexcel) - Providing one API for reading, manipulating and writing csv, ods, xls, xlsx and xlsm files. :star:732
    * [python-docx](https://github.com/python-openxml/python-docx) - Reads, queries and modifies Microsoft Word 2007/2008 docx files. :star:1940
    * [python-pptx](https://github.com/scanny/python-pptx) - Python library for creating and updating PowerPoint (.pptx) files. :star:912
    * [unoconv](https://github.com/unoconv/unoconv) - Convert between any document format supported by LibreOffice/OpenOffice. :star:1696
    * [XlsxWriter](https://github.com/jmcnamara/XlsxWriter) - A Python module for creating Excel .xlsx files. :star:2028
    * [xlwings](https://github.com/ZoomerAnalytics/xlwings) - A BSD-licensed library that makes it easy to call Python from Excel and vice versa. :star:1533
    * [xlwt](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd) - Writing and reading data and formatting information from Excel files. :star:1705
* PDF
    * [PDFMiner](https://github.com/euske/pdfminer) - A tool for extracting information from PDF documents. :star:3905
    * [PyPDF2](https://github.com/mstamy2/PyPDF2) - A library capable of splitting, merging and transforming PDF pages. :star:2840
    * [ReportLab](https://www.reportlab.com/opensource/) - Allowing Rapid creation of rich PDF documents.
* Markdown
    * [Mistune](https://github.com/lepture/mistune) - Fastest and full featured pure Python parsers of Markdown. :star:1615
    * [Python-Markdown](https://github.com/waylan/Python-Markdown) - A Python implementation of John Gruber’s Markdown. :star:1916
* YAML
    * [PyYAML](http://pyyaml.org/) - YAML implementations for Python.
* CSV
    * [csvkit](https://github.com/wireservice/csvkit) - Utilities for converting to and working with CSV. :star:4025
* Archive
    * [unp](https://github.com/mitsuhiko/unp) - A command line tool that can unpack archives easily. :star:348

## Static Site Generator

*Static site generator is a software that takes some text + templates as input and produces HTML files on the output.*

* [mkdocs](https://github.com/mkdocs/mkdocs/) - Markdown friendly documentation generator. :star:8608
* [pelican](https://github.com/getpelican/pelican) - Static site generator that supports Markdown and reST syntax. :star:9212
* [lektor](https://github.com/lektor/lektor) - An easy to use static CMS and blog engine. :star:3169
* [nikola](https://github.com/getnikola/nikola) - A static website and blog generator. :star:1795

## Tagging

*Libraries for tagging items.*

* [django-taggit](https://github.com/jazzband/django-taggit) - Simple tagging for Django. :star:2277

## Task Queues

*Libraries for working with task queues.*

* [celery](http://www.celeryproject.org/) - An asynchronous task queue/job queue based on distributed message passing.
* [huey](https://github.com/coleifer/huey) - Little multi-threaded task queue. :star:2595
* [mrq](https://github.com/pricingassistant/mrq) - A distributed worker task queue in Python using Redis & gevent. :star:788
* [rq](https://github.com/rq/rq) - Simple job queues for Python. :star:5949

## Template Engine

*Libraries and tools for templating and lexing.*

* [Jinja2](https://github.com/pallets/jinja) - A modern and designer friendly templating language. :star:6630
* [Genshi](https://genshi.edgewall.org/) - Python templating toolkit for generation of web-aware output.
* [Mako](http://www.makotemplates.org/) - Hyperfast and lightweight templating for the Python platform.

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [pytest](https://docs.pytest.org/en/latest/) - A mature full-featured Python testing tool.
    * [hypothesis](https://github.com/HypothesisWorks/hypothesis) - Hypothesis is an advanced Quickcheck style property based testing library. :star:3922
    * [nose2](https://github.com/nose-devs/nose2) - The successor to `nose`, based on `unittest2. :star:587
    * [Robot Framework](https://github.com/robotframework/robotframework) - A generic test automation framework. :star:3994
    * [unittest](https://docs.python.org/3/library/unittest.html) - (Python standard library) Unit testing framework.
* Test Runners
    * [green](https://github.com/CleanCut/green) - A clean, colorful test runner. :star:627
    * [mamba](http://nestorsalceda.github.io/mamba/) - The definitive testing tool for Python. Born under the banner of BDD.
    * [tox](https://tox.readthedocs.io/en/latest/) - Auto builds and tests distributions in multiple Python versions
* GUI / Web Testing
    * [locust](https://github.com/locustio/locust) - Scalable user load testing tool written in Python. :star:11357
    * [PyAutoGUI](https://github.com/asweigart/pyautogui) - PyAutoGUI is a cross-platform GUI automation Python module for human beings. :star:3204
    * [Selenium](https://pypi.org/project/selenium/) - Python bindings for [Selenium](http://www.seleniumhq.org/) WebDriver.
    * [sixpack](https://github.com/seatgeek/sixpack) - A language-agnostic A/B Testing framework. :star:1594
    * [splinter](https://github.com/cobrateam/splinter) - Open source tool for testing web applications. :star:2117
* Mock
    * [mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.
    * [doublex](https://pypi.org/project/doublex/) - Powerful test doubles framework for Python.
    * [freezegun](https://github.com/spulec/freezegun) - Travel through time by mocking the datetime module. :star:2166
    * [httmock](https://github.com/patrys/httmock) - A mocking library for requests for Python 2.6+ and 3.2+. :star:391
    * [httpretty](https://github.com/gabrielfalcao/HTTPretty) - HTTP request mock tool for Python. :star:1743
    * [mocket](https://github.com/mindflayer/python-mocket) - A socket mock framework with gevent/asyncio/SSL support. :star:164
    * [responses](https://github.com/getsentry/responses) - A utility library for mocking out the requests Python library. :star:2521
    * [VCR.py](https://github.com/kevin1024/vcrpy) - Record and replay HTTP interactions on your tests. :star:1554
* Object Factories
    * [factory_boy](https://github.com/FactoryBoy/factory_boy) - A test fixtures replacement for Python. :star:1956
    * [mixer](https://github.com/klen/mixer) - Another fixtures replacement. Supported Django, Flask, SQLAlchemy, Peewee and etc. :star:638
    * [model_mommy](https://github.com/vandersonmota/model_mommy) - Creating random fixtures for testing in Django. :star:944
* Code Coverage
    * [coverage](https://pypi.org/project/coverage/) - Code coverage measurement.
* Fake Data
    * [mimesis](https://github.com/lk-geimfari/mimesis) - is a Python library that help you generate fake data. :star:2533
    * [fake2db](https://github.com/emirozer/fake2db) - Fake database generator. :star:1994
    * [faker](https://github.com/joke2k/faker) - A Python package that generates fake data. :star:8775
    * [radar](https://pypi.org/project/radar/) - Generate random datetime / time.

## Text Processing

*Libraries for parsing and manipulating plain texts.*

* General
    * [chardet](https://github.com/chardet/chardet) - Python 2/3 compatible character encoding detector. :star:1206
    * [difflib](https://docs.python.org/3/library/difflib.html) - (Python standard library) Helpers for computing deltas.
    * [ftfy](https://github.com/LuminosoInsight/python-ftfy) - Makes Unicode text less broken and more consistent automagically. :star:2571
    * [fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) - Fuzzy String Matching. :star:6231
    * [Levenshtein](https://github.com/ztane/python-Levenshtein/) - Fast computation of Levenshtein distance and string similarity. :star:714
    * [pangu.py](https://github.com/vinta/pangu.py) - Paranoid text spacing. :star:136
    * [pyfiglet](https://github.com/pwaller/pyfiglet) - An implementation of figlet written in Python. :star:547
    * [pypinyin](https://github.com/mozillazg/python-pinyin) - Convert Chinese hanzi (漢字) to pinyin (拼音). :star:2232
    * [textdistance](https://github.com/orsinium/textdistance) - Compute distance between sequences with 30+ algorithms. :star:1491
    * [unidecode](https://pypi.org/project/Unidecode/) - ASCII transliterations of Unicode text.
* Slugify
    * [awesome-slugify](https://github.com/dimka665/awesome-slugify) - A Python slugify library that can preserve unicode. :star:429
    * [python-slugify](https://github.com/un33k/python-slugify) - A Python slugify library that translates unicode to ASCII. :star:772
    * [unicode-slugify](https://github.com/mozilla/unicode-slugify) - A slugifier that generates unicode slugs with Django as a dependency. :star:286
* Unique identifiers
    * [hashids](https://github.com/davidaurelio/hashids-python) - Implementation of [hashids](http://hashids.org) in Python. :star:988
    * [shortuuid](https://github.com/skorokithakis/shortuuid) - A generator library for concise, unambiguous and URL-safe UUIDs. :star:1154
* Parser
    * [ply](https://github.com/dabeaz/ply) - Implementation of lex and yacc parsing tools for Python. :star:1468
    * [pygments](http://pygments.org/) - A generic syntax highlighter.
    * [pyparsing](https://github.com/pyparsing/pyparsing) - A general purpose framework for generating parsers. :star:485
    * [python-nameparser](https://github.com/derek73/python-nameparser) - Parsing human names into their individual components. :star:372
    * [python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) - Parsing, formatting, storing and validating international phone numbers. :star:2305
    * [python-user-agents](https://github.com/selwin/python-user-agents) - Browser user agent parser. :star:960
    * [sqlparse](https://github.com/andialbrecht/sqlparse) - A non-validating SQL parser. :star:1833

## Third-party APIs

*Libraries for accessing third party services APIs. Also see [List of Python API Wrappers and Libraries](https://github.com/realpython/list-of-python-api-wrappers).*

* [apache-libcloud](https://libcloud.apache.org/) - One Python library for all clouds.
* [boto3](https://github.com/boto/boto3) - Python interface to Amazon Web Services. :star:4982
* [django-wordpress](https://github.com/istrategylabs/django-wordpress) - WordPress models and views for Django. :star:303
* [facebook-sdk](https://github.com/mobolic/facebook-sdk) - Facebook Platform Python SDK. :star:2461
* [google-api-python-client](https://github.com/google/google-api-python-client) - Google APIs Client Library for Python. :star:3079
* [gspread](https://github.com/burnash/gspread) - Google Spreadsheets Python API. :star:4384
* [twython](https://github.com/ryanmcgrath/twython) - A Python wrapper for the Twitter API. :star:1666

## URL Manipulation

*Libraries for parsing URLs.*

* [furl](https://github.com/gruns/furl) - A small Python library that makes parsing and manipulating URLs easy. :star:1716
* [purl](https://github.com/codeinthehole/purl) - A simple, immutable URL class with a clean API for interrogation and manipulation. :star:235
* [pyshorteners](https://github.com/ellisonleao/pyshorteners) - A pure Python URL shortening lib. :star:239
* [webargs](https://github.com/marshmallow-code/webargs) - A friendly library for parsing HTTP request arguments with built-in support for popular web frameworks. :star:906

## Video

*Libraries for manipulating video and GIFs.*

* [moviepy](https://zulko.github.io/moviepy/) - A module for script-based movie editing with many formats, including animated GIFs.
* [scikit-video](https://github.com/aizvorski/scikit-video) - Video processing routines for SciPy. :star:96

## Web Asset Management

*Tools for managing, compressing and minifying website assets.*

* [django-compressor](https://github.com/django-compressor/django-compressor) - Compresses linked and inline JavaScript or CSS into a single cached file. :star:2263
* [django-pipeline](https://github.com/jazzband/django-pipeline) - An asset packaging library for Django. :star:1337
* [django-storages](https://github.com/jschneier/django-storages) - A collection of custom storage back ends for Django. :star:1388
* [fanstatic](http://www.fanstatic.org/en/latest/) - Packages, optimizes, and serves static file dependencies as Python packages.
* [fileconveyor](http://wimleers.com/fileconveyor) - A daemon to detect and sync files to CDNs, S3 and FTP.
* [flask-assets](https://github.com/miracle2k/flask-assets) - Helps you integrate webassets into your Flask app. :star:381
* [webassets](https://github.com/miracle2k/webassets) - Bundles, optimizes, and manages unique cache-busting URLs for static resources. :star:869

## Web Content Extracting

*Libraries for extracting web contents.*

* [html2text](https://github.com/Alir3z4/html2text) - Convert HTML to Markdown-formatted text. :star:803
* [lassie](https://github.com/michaelhelmick/lassie) - Web Content Retrieval for Humans. :star:480
* [micawber](https://github.com/coleifer/micawber) - A small library for extracting rich content from URLs. :star:465
* [newspaper](https://github.com/codelucas/newspaper) - News extraction, article extraction and content curation in Python. :star:8823
* [python-readability](https://github.com/buriy/python-readability) - Fast Python port of arc90's readability tool. :star:1700
* [requests-html](https://github.com/kennethreitz/requests-html) - Pythonic HTML Parsing for Humans. :star:10424
* [sumy](https://github.com/miso-belica/sumy) - A module for automatic summarization of text documents and HTML pages. :star:2110
* [textract](https://github.com/deanmalmgren/textract) - Extract text from any document, Word, PowerPoint, PDFs, etc. :star:2691
* [toapi](https://github.com/gaojiuli/toapi) - Every web site provides APIs. :star:2927

## Web Crawling

*Libraries to automate web scraping.*

* [cola](https://github.com/chineking/cola) - A distributed crawling framework. :star:1373
* [feedparser](https://pythonhosted.org/feedparser/) - Universal feed parser.
* [grab](https://github.com/lorien/grab) - Site scraping framework. :star:1846
* [MechanicalSoup](https://github.com/MechanicalSoup/MechanicalSoup) - A Python library for automating interaction with websites. :star:3345
* [pyspider](https://github.com/binux/pyspider) - A powerful spider system. :star:13823
* [robobrowser](https://github.com/jmcarp/robobrowser) - A simple, Pythonic library for browsing the web without a standalone web browser. :star:3373
* [scrapy](https://scrapy.org/) - A fast high-level screen scraping and web crawling framework.
* [portia](https://github.com/scrapinghub/portia) - Visual scraping for Scrapy. :star:7372

## Web Frameworks

*Traditional full stack web frameworks. Also see [RESTful API](https://github.com/vinta/awesome-python#restful-api)*

* Synchronous
    * [Django](https://www.djangoproject.com/) - The most popular web framework in Python.
        * [awesome-django](https://github.com/shahraizali/awesome-django) :star:190
    * [Flask](http://flask.pocoo.org/) - A microframework for Python.
        * [awesome-flask](https://github.com/humiaozuzu/awesome-flask) :star:7996
    * [Pyramid](https://pylonsproject.org/) - A small, fast, down-to-earth, open source Python web framework.
        * [awesome-pyramid](https://github.com/uralbash/awesome-pyramid) :star:475
    * [Masonite](https://github.com/MasoniteFramework/masonite) - The modern and developer centric Python web framework. :star:1183
* Asynchronous
    * [Tornado](http://www.tornadoweb.org/en/latest/) - A web framework and asynchronous networking library.

## WebSocket

*Libraries for working with WebSocket.*

* [autobahn-python](https://github.com/crossbario/autobahn-python) - WebSocket & WAMP for Python on Twisted and [asyncio](https://docs.python.org/3/library/asyncio.html). :star:2099
* [channels](https://github.com/django/channels) - Developer-friendly asynchrony for Django. :star:4070
* [websockets](https://github.com/aaugustin/websockets) - A library for building WebSocket servers and clients with a focus on correctness and simplicity. :star:2386

## WSGI Servers

*WSGI-compatible web servers.*

* [bjoern](https://github.com/jonashaag/bjoern) - Asynchronous, very fast and written in C. :star:2131
* [gunicorn](https://github.com/benoitc/gunicorn) - Pre-forked, partly written in C. :star:6284
* [uWSGI](https://uwsgi-docs.readthedocs.io/en/latest/) - A project aims at developing a full stack for building hosting services, written in C.
* [waitress](https://github.com/Pylons/waitress) - Multi-threaded, powers Pyramid. :star:660
* [werkzeug](https://github.com/pallets/werkzeug) - A WSGI utility library for Python that powers Flask and can easily be embedded into your own projects. :star:5019

# Resources

Where to discover new Python libraries.

## Podcasts

* [From Python Import Podcast](http://frompythonimportpodcast.com/)
* [Podcast.init](https://podcastinit.com/)
* [Python Bytes](https://pythonbytes.fm)
* [Python Testing](http://pythontesting.net)
* [Radio Free Python](http://radiofreepython.com/)
* [Talk Python To Me](https://talkpython.fm/)
* [Test and Code](https://testandcode.com/)

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
* [@realpython](https://twitter.com/realpython)

## Websites

* [/r/CoolGithubProjects](https://www.reddit.com/r/coolgithubprojects/)
* [/r/Python](https://www.reddit.com/r/python)
* [Awesome Python @LibHunt](https://python.libhunt.com/)
* [Django Packages](https://djangopackages.org/)
* [Full Stack Python](https://www.fullstackpython.com/)
* [Python Cheatsheet](https://www.pythoncheatsheet.org/)
* [Python ZEEF](https://python.zeef.com/alan.richmond)
* [Python 开发社区](https://www.ctolib.com/python/)
* [Real Python](https://realpython.com)
* [Trending Python repositories on GitHub today](https://github.com/trending?l=python)
* [Сообщество Python Программистов](https://python-scripts.com/)

## Weekly

* [CodeTengu Weekly 碼天狗週刊](https://weekly.codetengu.com/)
* [Import Python Newsletter](http://importpython.com/newsletter/)
* [Pycoder's Weekly](http://pycoders.com/)
* [Python Weekly](http://www.pythonweekly.com/)
* [Python Tricks](https://realpython.com/python-tricks/)

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/vinta/awesome-python/blob/master/CONTRIBUTING.md) first.

I will keep some pull requests open if I'm not sure whether those libraries are awesome, you could [vote for them](https://github.com/vinta/awesome-python/pulls) by adding :+1: to them. Pull requests will be merged when their votes reach **20**.

- - -

If you have any question about this opinionated list, do not hesitate to contact me [@vinta](https://twitter.com/vinta) on Twitter or open an issue on GitHub.


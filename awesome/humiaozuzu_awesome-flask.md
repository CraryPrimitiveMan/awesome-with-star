# Information comes from [humiaozuzu/awesome-flask](https://github.com/humiaozuzu/awesome-flask)
# Awesome Flask [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome Flask resources and plugins

- [Awesome Flask](#awesome-flask)
  - [Framework](#framework)
  - [Admin interface](#admin-interface)
  - [Authentication](#authentication)
  - [Authorization](#authorization)
  - [Database](#database)
  - [Database Migrations](#database-migrations)
  - [Session](#session)
  - [Cache](#cache)
  - [Data Validation](#data-validation)
  - [Email](#email)
  - [i18n](#i18n)
  - [Full-text searching](#full-text-searching)
  - [Rate Limiting](#rate-limiting)
  - [Task Queue](#task-queue)
  - [Exception tracking](#exception-tracking)
  - [Tracing](#tracing)
  - [APM](#apm)
  - [Other SDK](#other-sdk)
  - [Frontend](#frontend)
  - [Development (Debugging/Testing/Documentation)](#development-debuggingtestingdocumentation)
  - [Utils](#utils)
- [Resources](#resources)
  - [Tutorials](#tutorials)
  - [Courses](#courses)
  - [Books](#books)
  - [Slides](#slides)
  - [Videos](#videos)
  - [Built with Flask](#built-with-flask)
  - [Boilerplate](#boilerplate)

## Framework

- [Connexion](https://github.com/zalando/connexion) - Swagger/OpenAPI First framework for Python on top of Flask with automatic endpoint validation and OAuth2 support :star:1222
- [Flask-MongoRest](https://github.com/closeio/flask-mongorest) - Restful API framework wrapped around MongoEngine :star:423
- [Eve](https://github.com/pyeve/eve) - REST API framework powered by Flask, MongoDB and good intentions :star:4947
- [Flask-Restless](https://github.com/jfinkels/flask-restless) - A Flask extension for creating simple ReSTful APIs from SQLAlchemy models :star:871
- [Flask-RESTful](https://github.com/flask-restful/flask-restful) - Simple framework for creating REST APIs :star:3628
- [Flask-RestPlus](https://github.com/noirbizarre/flask-restplus) - syntaxic sugar, helpers and automatically generated Swagger documentation. :star:882
- [Flask-Potion](https://github.com/biosustain/potion) - RESTful API framework for Flask and SQLAlchemy :star:412
- [Zappa](https://github.com/Miserlou/Zappa) - Build and deploy server-less Flask applications on AWS Lambda and API Gateway :star:6890

## Admin interface

- [Flask-Admin](https://github.com/flask-admin/flask-admin) - Simple and extensible administrative interface framework for Flask :star:2864

## Authentication

- [Flask-Security](https://github.com/mattupstate/flask-security) - Quick and simple security for Flask applications :star:1147
- [Flask-Login](https://github.com/maxcountryman/flask-login) - Flask user session management :star:1712
- [Flask-User](https://github.com/lingthio/Flask-User) - Customizable user account management for Flask :star:630
- [Flask-HTTPAuth](https://github.com/miguelgrinberg/Flask-HTTPAuth) - Simple extension that provides Basic and Digest HTTP authentication for Flask routes :star:464

## Authorization

- [Authlib](https://github.com/lepture/authlib) - Authlib is an ambitious authentication library for OAuth 1, OAuth 2, OpenID clients, servers and more. :star:429
- [Authomatic](https://github.com/authomatic/authomatic) - Authomatic provides out of the box support for a number of providers using OAuth 1.0a (Twitter, Tumblr and more) and OAuth 2.0 (Facebook, Foursquare, GitHub, Google, LinkedIn, PayPal and more)
- [Flask-Pundit](https://github.com/anurag90x/flask-pundit) - Extension based on Rails' [Pundit](https://github.com/varvet/pundit) gem that provides easy way to organize access control for your models :star:12

## Database

- [Flask-MongoEngine](https://github.com/MongoEngine/flask-mongoengine) - MongoEngine flask extension with WTF model forms support :star:531
- [Flask-SQLAlchemy](https://github.com/mitsuhiko/flask-sqlalchemy) - Adds SQLAlchemy support to Flask :star:2073

## Database Migrations

- [Flask-Migrate](https://github.com/miguelgrinberg/Flask-Migrate) - SQLAlchemy database migrations for Flask applications using Alembic :star:917

## Session

- [Flask-Session](https://github.com/fengsp/flask-session) - Server side session extension for Flask :star:192

## Cache

- [Flask-Caching](https://github.com/sh4nks/flask-caching) - Adds easy cache support to Flask :star:180
- [flask-heroku-cacheify](https://github.com/rdegges/flask-heroku-cacheify) - Automatic Flask cache configuration on Heroku :star:32

## Data Validation

- [Flask-WTF](https://github.com/lepture/flask-wtf) - Simple integration of Flask and WTForms, including CSRF, file upload and Recaptcha integration. :star:754

## Email

- [Flask-Mail](https://github.com/mattupstate/flask-mail/) - Flask-Mail adds SMTP mail sending to your Flask applications

## i18n

- [flask-babel](https://github.com/python-babel/flask-babel) - i18n and l10n support for Flask based on Babel and pytz :star:262

## Full-text searching

- [SQLAlchemy-Searchable](https://github.com/kvesteri/sqlalchemy-searchable) - Full-text searching for Flask-SQLAlchemy (Postgres only)
- [flask_msearch](https://github.com/honmaple/flask-msearch) - Full text search for flask with whoosh :star:41

## Rate Limiting

- [Flask-Limiter](https://github.com/alisaifee/flask-limiter) - Flask-Limiter provides rate limiting features to flask routes :star:311

## Task Queue

- [dramatiq](https://github.com/Bogdanp/dramatiq) - A fast and reliable distributed task processing library for Python 3 :star:763
- [huey](https://github.com/coleifer/huey) - a little task queue for python :star:1717
- [Flask-RQ](https://github.com/mattupstate/flask-rq) - RQ (Redis Queue) integration for Flask applications :star:158
- [celery](https://github.com/celery/celery/) - Distributed Task Queue

## Exception tracking

- [Raven](https://github.com/getsentry/raven-python) - Raven is a Python client for [Sentry](https://sentry.io/welcome/). :star:1409
- [airbrake-python](https://github.com/airbrake/airbrake-python) - Python client for [Airbrake](https://airbrake.io/)

## Tracing

- [flask-zipkin](https://github.com/qiajigou/flask-zipkin) - Distributed tracing with [Zipkin](https://zipkin.io/). :star:19
- [Flask-OpenTracing](https://github.com/opentracing-contrib/python-flask) - Distributed tracing with [OpenTracing](http://opentracing.io/). :star:21

## APM

- [elastic-apm](https://github.com/elastic/apm-agent-python) - Elastic APM agent for Python :star:57

## Other SDK

- [Flask-GoogleMaps](https://github.com/rochacbruno/Flask-GoogleMaps) - Build and embed google maps in our Flask templates :star:367
- [Flask-Gravatar](https://github.com/zzzsochi/Flask-Gravatar) - Small and simple gravatar usage in Flask :star:69
- [Flask-Pusher](https://github.com/iurisilvio/Flask-Pusher) - Pusher integration for Flask :star:5
- [Flask-Azure-Storage](https://github.com/alejoar/Flask-Azure-Storage) - Flask extension that provides integration with Azure Storage :star:5

## Frontend

- [Flask-CORS](https://github.com/corydolphin/flask-cors) - A Flask extension for handling Cross Origin Resource Sharing (CORS), making cross-origin AJAX possible :star:392
- [flask-assets](https://github.com/miracle2k/flask-assets) - Flask webassets integration :star:341
- [flask-s3](https://github.com/e-dard/flask-s3) - Seamlessly serve your static assets of your Flask app from Amazon S3 :star:138
- [Flask-SSLify](https://github.com/kennethreitz/flask-sslify) - Force SSL on your Flask app :star:426
- [Flask-HTMLmin](https://github.com/hamidfzm/Flask-HTMLmin) - Flask html minifier :star:34

## Development (Debugging/Testing/Documentation)

- [Flasgger](https://github.com/rochacbruno/flasgger) - Create API documentation for Flask views using Swagger 2.0 specs :star:703
- [flask-apispec](https://github.com/jmcarp/flask-apispec) - simple self-documenting APIs with flask :star:244
- [flask2postman](https://github.com/numberly/flask2postman) - Generate a Postman collection from your Flask application :star:79
- [flask_profiler](https://github.com/muatik/flask-profiler) - endpoint analyzer/profiler for Flask :star:386
- [Flask-DebugToolbar](https://github.com/mgood/flask-debugtoolbar) - A port of the django debug toolbar to flask :star:637
- [flask-debug-toolbar-mongo](https://github.com/cenkalti/flask-debug-toolbar-mongo) - MongoDB panel for the Flask Debug Toolbar :star:3
- [Flask-Testing](https://github.com/jarus/flask-testing) - Unittest extensions for Flask :star:364
- [pytest-flask](https://github.com/pytest-dev/pytest-flask) - A set of pytest fixtures to test Flask applications :star:157
- [Flask-MonitoringDashboard](https://github.com/flask-dashboard/Flask-MonitoringDashboard) - Automatically monitor the evolving performance of Flask/Python web services. :star:23

## Utils

- [flask-marshmallow](https://github.com/marshmallow-code/flask-marshmallow) Flask + marshmallow for beautiful APIs
- [flask-jsonrpc](https://github.com/cenobites/flask-jsonrpc) - A basic JSON-RPC implementation for your Flask-powered sites :star:134
- [Flask-Bcrypt](https://github.com/maxcountryman/flask-bcrypt) - Flask-Bcrypt is a Flask extension that provides bcrypt hashing utilities for your application :star:201
- [Mixer](https://github.com/klen/mixer) - Mixer is application to generate instances of Django or SQLAlchemy models :star:495
- [Flask-FeatureFlags](https://github.com/trustrachel/Flask-FeatureFlags) - A Flask extension that enables or disables features based on configuration :star:92
- [Flask-Reggie](https://github.com/rhyselsmore/flask-reggie) - Regex Converter for Flask URL Routes :star:42
- [Flask-SocketIO](https://github.com/miguelgrinberg/Flask-SocketIO) - Socket.IO integration for Flask applications :star:2278
- [Flask-Moment](https://github.com/miguelgrinberg/Flask-Moment) - Formatting of dates and times in Flask templates using moment.js :star:189
- [Flask-Paginate](https://github.com/lixxu/flask-paginate) - Pagination support for Flask :star:149

# Resources
## Tutorials

- [How to build a news app that never goes down and costs you practically nothing](http://blog.apps.npr.org/2013/02/14/app-template-redux.html) (by NPR)
- [Building websites in Python with Flask](http://maximebf.com/blog/2012/10/building-websites-in-python-with-flask/)
- [The Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
- [Implementing a RESTful Web API with Python & Flask](http://blog.luisrei.com/articles/flaskrest.html)
- [Discover Flask - Full Stack Web Development with Flask](https://github.com/realpython/discover-flask) :star:3062
- [Flaskr - Intro to Flask, Test Driven Development, and jQuery](https://github.com/mjhea0/flaskr-tdd) :star:1091

## Courses

- [Full Stack Foundations](https://www.udacity.com/course/full-stack-foundations--ud088)
- [Designing RESTful APIs](https://www.udacity.com/course/designing-restful-apis--ud388)

## Books

- [Explore Flask](https://exploreflask.com/en/latest/)
- [Flask Web Development](http://shop.oreilly.com/product/0636920031116.do)
- [Real Python](https://realpython.com)
- [Learning Flask Framework](https://www.packtpub.com/web-development/learning-flask-framework)
- [Flask Blueprints](https://www.packtpub.com/web-development/flask-blueprints)
- [Flask Framework Cookbook](https://www.packtpub.com/web-development/flask-framework-cookbook)
- [Mastering Flask](https://www.packtpub.com/web-development/mastering-flask)
- [Building Web Applications with Flask](https://www.packtpub.com/web-development/building-web-applications-flask)

## Slides

- [Creating beautiful REST APIs with Flask](http://pycoder.net/bospy/presentation.html)
- [Advanced Flask Patterns](https://speakerdeck.com/mitsuhiko/advanced-flask-patterns)
- [Flasky Goodness](https://speakerdeck.com/kennethreitz/flasky-goodness)
- [Domain Driven Design (... with Flask)](https://speakerdeck.com/mikedebo/domain-driven-design-dot-dot-dot-with-flask)
- [In Flask we Trust](https://speakerdeck.com/playpauseandstop/in-flask-we-trust)

## Videos

- [Flask by Example](http://pyvideo.org/video/2608/flask-by-example/)
- [Writing RESTful web services with Flask](http://pyvideo.org/video/2668/writing-restful-web-services-with-flask/)
- [Practical Flask Web Development Tutorials](https://www.youtube.com/playlist?list=PLQVvvaa0QuDc_owjTbIY4rbgXOFkUYOUB)

## Built with Flask

- [zmusic-ng](https://git.zx2c4.com/zmusic-ng/) - ZX2C4 Music provides a web interface for playing and downloading music files using metadata.
- [GuitarFan](https://github.com/lowrain/GuitarFan) - guitar tab :star:40
- [June](https://github.com/pythoncn/june) - ~~python-china.org~~ :star:1075
- [Zerqu](https://github.com/lepture/zerqu) - ZERQU is a content-focused API-based platform. eg: [Python-China](https://python-china.org)
- [motiky](https://github.com/notedit/motiky) :star:39
- [missing](https://github.com/notedit/missing) - a list service called missing :star:8
- [thenewsmeme.com](https://github.com/danjac/newsmeme) :star:73
- [overholt](https://github.com/mattupstate/overholt) - Example Flask application illustrating common practices :star:1393
- [pypress](https://github.com/laoqiu/pypress) - flask team blog :star:525
- [thepast.me](https://github.com/laiwei/thepast) :star:753
- [redispapa](https://github.com/no13bus/redispapa) - another redis monitor by using flask, angular, socket.io :star:363
- [flaskblog](https://github.com/defshine/flaskblog) - a simple blog system based on flask :star:150
- [cleanblog](https://github.com/defshine/cleanblog) - a clean blog system based on flask and mongoengine :star:95
- [Quokka CMS](https://github.com/rochacbruno/quokka) - CMS made with Flask and MongoDB :star:1855
- [chat](https://github.com/lzyy/chat) - a live chat built with python (flask + gevent + apscheduler) + redis :star:283
- [chatapp](https://github.com/vinceprignano/chatapp) - Flask and Angular.js Chat Application using Socket.io :star:157
- [Frozen-Flask](https://github.com/Frozen-Flask/Frozen-Flask) - Freezes a Flask application into a set of static files :star:527
- [mcflyin](https://github.com/wrobstory/mcflyin) - A small timeseries transformation API built on Flask and Pandas :star:70
- [Skylines](https://github.com/skylines-project/skylines) - Live tracking, flight database and competition framework :star:162
- [airflow](https://github.com/apache/incubator-airflow) - Airflow is a system to programmatically author, schedule and monitor data pipelines. :star:7916
- [timesketch](https://github.com/google/timesketch) - Collaborative forensics timeline analysis :star:843
- [changes](https://github.com/dropbox/changes) - A dashboard for your code. A build system. :star:763
- [security_monkey](https://github.com/Netflix/security_monkey) - monitors policy changes and alerts on insecure configurations in an AWS account. :star:2613
- [securedrop](https://github.com/freedomofpress/securedrop)- an open-source whistleblower submission system that media organizations can use to securely accept documents from and communicate with anonymous sources.
- [sync_engine](https://github.com/nylas/sync-engine) - IMAP/SMTP sync system with modern APIs :star:3438
- [cleansweep](https://github.com/AamAadmiParty/cleansweep) - Volunteer & Campaign Management System :star:32
- [indico](https://github.com/indico/indico) - a general-purpose event management web-based solution. It includes a full-blown conference organization workflow as well as tools for meeting management and room booking. It provides as well integration with video-conferencing solutions. :star:317
- [flaskbb](https://github.com/flaskbb/flaskbb) - A classic Forum Software in Python using Flask. :star:1255

## Boilerplate

- [fbone](https://github.com/imwilsonxu/fbone) :star:1496
- [cookiecutter-flask](https://github.com/sloria/cookiecutter-flask) :star:1842
- [Flask-Foundation](https://github.com/JackStouffer/Flask-Foundation) :star:1131
- [flask-rest-template](https://github.com/alexandre/flask-rest-template) :star:56
- [gae-init](https://gae-init.appspot.com) - Flask boilerplate running on Google App Engine
- [Flask-AppBuilder](https://github.com/dpgaspar/Flask-AppBuilder) - Simple and rapid application builder framework, built on top of Flask. includes detailed security, auto form generation, google charts and much more :star:1491


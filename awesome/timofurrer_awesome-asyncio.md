# Information comes from [timofurrer/awesome-asyncio](https://github.com/timofurrer/awesome-asyncio)
# Awesome asyncio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A carefully curated list of awesome Python asyncio frameworks, libraries, software and resources.

The Python [asyncio](https://docs.python.org/3/library/asyncio.html) module introduced to the standard library with Python 3.4 provides infrastructure for writing single-threaded concurrent code using coroutines, multiplexing I/O access over sockets and other resources, running network clients and servers, and other related primitives.

Asyncio is not really a brand-new technology however it appears to be very trending since a few years - especially in the Python community and with the release of Python 3.4 in March 2016.
Thus, it's pretty hard to keep yourself up-to-date with the most awesome packages out there.
Find some of those *awesome* packages here and if you are missing one we count on you to [create an Issue or a Pull Request](https://github.com/timofurrer/awesome-asyncio/blob/master/CONTRIBUTING.md) with your suggestion.

## Contents

* [Web Frameworks](#web-frameworks)
* [Message Queues](#message-queues)
* [Database Drivers](#database-drivers)
* [Networking](#networking)
* [Testing](#testing)
* [Alternative Loops](#alternative-loops)
* [Misc](#misc)
* [Writings](#writings)
* [Talks](#talks)

***

## Web Frameworks

*Libraries to build web applications.*

* [aiohttp](https://github.com/KeepSafe/aiohttp) - Http client/server for asyncio (PEP-3156). :star:6271
* [sanic](https://github.com/channelcat/sanic) - Python 3.5+ web server that's written to go fast. :star:10503
* [Quart](https://gitlab.com/pgjones/quart) - An asyncio web microframework with the same API as Flask.
* [Vibora](https://github.com/vibora-io/vibora) - Performant web framework inspired by Flask. :star:4274
* [cirrina](https://github.com/neolynx/cirrina) - Opinionated asynchronous web framework based on aiohttp. :star:22
* [autobahn](https://github.com/crossbario/autobahn-python) - WebSocket and WAMP supporting asyncio and Twisted, for clients and servers. :star:1898
* [websockets](https://github.com/aaugustin/websockets/) - A library for building WebSocket servers and clients in Python with a focus on correctness and simplicity. :star:1716
* [Tornado](http://www.tornadoweb.org/en/stable/) - Performant web framework and asynchronous networking library.
* [Japronto!](https://github.com/squeaky-pl/japronto) - Experimental http toolkit built on top of uvloop and picohttpparser. :star:6344

## Message Queues

*Libraries to implement applications using message queues.*

* [aioamqp](https://github.com/Polyconseil/aioamqp) - AMQP implementation using asyncio. :star:164
* [aiozmq](https://github.com/aio-libs/aiozmq) - Asyncio (pep 3156) integration with ZeroMQ. :star:279
* [crossbar](https://github.com/crossbario/crossbar) - Crossbar.io is a networking platform for distributed and microservice applications. :star:1558
* [asyncio-nats](https://github.com/nats-io/asyncio-nats) - Client for the NATS messaging system. :star:147
* [aiokafka](https://github.com/aio-libs/aiokafka) - Client for Apache Kafka. :star:221

## Database Drivers

*Libraries to connect to databases.*

* [asyncpg](https://github.com/MagicStack/asyncpg) - Fast PostgreSQL Database Client Library for Python/asyncio. :star:2935
* [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) - Asyncpg with sqlalchemy core support. :star:241
* [aiopg](https://github.com/aio-libs/aiopg/) - Library for accessing a PostgreSQL database. :star:697
* [aiomysql](https://github.com/aio-libs/aiomysql) - Library for accessing a MySQL database :star:639
* [aioodbc](https://github.com/aio-libs/aioodbc) - Library for accessing a ODBC databases. :star:115
* [motor](https://github.com/mongodb/motor) - The async Python driver for MongoDB. :star:1071
* [aioredis](https://github.com/aio-libs/aioredis) - [aio-libs](https://github.com/aio-libs) Redis client (PEP 3156). :star:721
* [asyncio-redis](https://github.com/jonathanslenders/asyncio-redis) - Redis client for Python asyncio (PEP 3156). :star:441
* [aiocouchdb](https://github.com/aio-libs/aiocouchdb) - CouchDB client built on top of aiohttp (asyncio). :star:43
* [aioinflux](https://github.com/plugaai/aioinflux) - InfluxDB client built on top of aiohttp. :star:54
* [aioes](https://github.com/aio-libs/aioes) - Asyncio compatible driver for elasticsearch. :star:95
* [peewee-async](https://github.com/05bit/peewee-async) - ORM implementation based on [peewee](https://github.com/coleifer/peewee) and aiopg. :star:390
* [GINO](https://github.com/fantix/gino) - is a lightweight asynchronous Python ORM based on [SQLAlchemy](https://www.sqlalchemy.org/) core, with [asyncpg](https://github.com/MagicStack/asyncpg) dialect. :star:528

## Networking

*Libraries to communicate in your network.*

* [AsyncSSH](https://github.com/ronf/asyncssh) - Provides an asynchronous client and server implementation of the SSHv2 protocol. :star:743
* [aiodns](https://github.com/saghul/aiodns) - Simple DNS resolver for asyncio :star:188

## Testing

*Libraries to test asyncio based applications.*

* [aiomock](https://github.com/nhumrich/aiomock/) - A python mock library that supports async methods. :star:16
* [asynctest](https://github.com/Martiusweb/asynctest/) - Enhance the standard unittest package with features for testing. asyncio libraries :star:150
* [pytest-asyncio](https://github.com/pytest-dev/pytest-asyncio) - Pytest support for asyncio. :star:308

## Alternative Loops

*Alternative asyncio loop implementations.*

* [uvloop](https://github.com/MagicStack/uvloop) - Ultra fast implementation of asyncio event loop on top of libuv. :star:5249
* [curio](https://github.com/dabeaz/curio) - The coroutine concurrency library. :star:2713

## Misc

*Other awesome asyncio libraries.*

* [aiofiles](https://github.com/Tinche/aiofiles/) - File support for asyncio. :star:595
* [aiodebug](https://github.com/qntln/aiodebug) - A tiny library for monitoring and testing asyncio programs. :star:19
* [aiorun](https://github.com/cjrh/aiorun) - A `run()` function that handles all the usual boilerplate for startup and graceful shutdown. :star:57
* [aiozipkin](https://github.com/aio-libs/aiozipkin) - Distributed tracing instrumentation for asyncio with zipkin :star:95

## Writings

*Documentation, blog posts, and other awesome writing about asyncio.*

* [Official asyncio documentation](https://docs.python.org/3/library/asyncio.html) - Asynchronous I/O, event loop, coroutines and tasks.
* [Short well-written intro to asyncio](http://masnun.com/2015/11/13/python-generators-coroutines-native-coroutines-and-async-await.html) - Generators, Coroutines, Native Coroutines and async/await.
* [Async Through the looking Glass](https://hackernoon.com/async-through-the-looking-glass-d69a0a88b661) - Nice writing about it's worth using asyncio or not for specific use-cases.
* [Asynchronous Python](https://hackernoon.com/asynchronous-python-45df84b82434) - Introduction into asynchronous programming with Python.
* [AsyncIO for the Working Python Developer](https://hackernoon.com/asyncio-for-the-working-python-developer-5c468e6e2e8e) - A gentle introduction to asynchronous programming from basic examples working up to URL fetching.
* [Test limits of Python aiohttp](https://pawelmhm.github.io/asyncio/python/aiohttp/2016/04/22/asyncio-aiohttp.html) - Making 1 million requests with python-aiohttp.

## Talks

*Recordings of awesome talks about asyncio.*

* [Topics of Interest (Python Asyncio)](https://youtu.be/ZzfHjytDceU) | [screencast](https://youtu.be/lYe8W04ERnY) | [slides](https://speakerdeck.com/dabeaz/topics-of-interest-async) - PyCon Brasil 2015 keynote (David Beazley).
* [Python Asynchronous I/O Walkthrough](https://www.youtube.com/playlist?list=PLpEcQSRWP2IjVRlTUptdD05kG-UkJynQT) | [blog post](http://pgbovine.net/python-async-io-walkthrough.htm) - 8-part code walkthrough (Philip Guo).


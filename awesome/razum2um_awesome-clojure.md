# Information comes from [razum2um/awesome-clojure](https://github.com/razum2um/awesome-clojure)
# Awesome Clojure [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

- [Awesome products in Clojure](#awesome-products-in-clojure)
  - [LightTable (IDE)](http://lighttable.com/)
  - [Nightcode (IDE)](https://sekao.net/nightcode/)
  - [Riemann (Monitoring)](http://riemann.io/)
  - [Puppet Server](https://github.com/puppetlabs/puppet-server) :star:175
  - [PuppetDB](https://github.com/puppetlabs/puppetdb) :star:225
  - [Metabase](https://github.com/metabase/metabase) :star:9625
  - [Avi (vim rewrite)](https://github.com/maitria/avi) :star:198
  - [Liquid (Text Editor)](https://github.com/mogenslund/liquid) :star:189
  - [Clojupyter](https://github.com/clojupyter/clojupyter) :star:331
  - [Meo](https://github.com/matthiasn/meo) :star:79
  - [Jepsen](https://github.com/jepsen-io/jepsen) :star:3056
- [Languages written with Clojure](#languages-written-with-clojure)
  - [jank](https://github.com/jeaye/jank) :star:61
  - [lux](https://github.com/LuxLang/lux) :star:936
  - [mal](https://github.com/kanaka/mal/tree/master/clojure)
  - [scheje](https://github.com/turbopape/scheje) :star:75
- [Awesome tools in Clojure](#awesome-tools-in-clojure)
  - [Web Framework](#web-framework)
  - [Dependency injection](#dependency-injection)
  - [Build Automation and Package management](#build-automation-and-package-management)
  - [Version Control Management](#version-control-management)
  - [Date and Time](#date-and-time)
  - [GUI](#gui)
  - [Audio](#audio)
  - [HTTP](#http)
  - [Database](#database)
  - [Connection pools](#connection-pools)
  - [Structural Migrations](#structural-migrations)
  - [Redis](#redis)
  - [JSON](#json)
  - [ORM and SQL generation](#orm-and-sql-generation)
  - [Security](#security)
  - [RESTful API](#restful-api)
  - [Emails](#emails)
  - [HTML Manipulation](#html-manipulation)
  - [Data Validation](#data-validation)
  - [Type System](#type-system)
  - [Pattern Matching](#pattern-matching)
  - [Async processing](#async-processing)
  - [Monads](#monads)
  - [WebSocket](#websocket)
  - [Testing](#testing)
  - [Webdriver automation](#webdriver-automation)
  - [Code Analysis and Linter](#code-analysis-and-linter)
  - [Science and Data Analysis](#science-and-data-analysis)
  - [Machine Learning](#machine-learning)
  - [Computer Vision](#computer-vision)
  - [Natural Language Processing](#natural-language-processing)
  - [Parsing](#parsing)
  - [Reflection](#reflection)
  - [Editor Plugins](#editor-plugins)
  - [Documentation](#documentation)
  - [Literate Programming](#literate-programming)
  - [Archives and Compression](#archives-and-compression)
  - [Miscellaneous](#miscellaneous)
  - [Debugging tools](#debugging)
  - [CI](#ci)
  - [Project Management](#project-management)

- [Resources](#resources)
  - [Guides](#guides)
  - [Websites](#websites)
  - [Twitter](#twitter)
  - [Exercises](#exercises)


## Web Framework

*Actually don't search rails/django here, but compose them by yourself*
  * [Compojure](https://github.com/weavejester/compojure) :star:3388
  * [Web Non-Framework](https://github.com/webnf/webnf) :star:18
  * [Luminus](http://www.luminusweb.net/)
  * [Joodo](https://github.com/slagyr/joodoweb) :star:4
  * [Coils](https://github.com/zubairq/AppShare) :star:281
  * [Duct](https://github.com/weavejester/duct) :star:664
  * [Pedestal](https://github.com/pedestal/pedestal) :star:1880
  * [Datsys](https://github.com/metasoarous/datsys) :star:182
  * [yada](https://github.com/juxt/yada) :star:542
  * [Hoplon](http://hoplon.io/)
  * [Fulcro](https://github.com/fulcrologic/fulcro) :star:259
  * [Coast](http://coastonclojure.com/)

## Dependency injection

*Managed lifecycle of stateful objects*

  * [Component](https://github.com/stuartsierra/component) :star:1501
  * [System](https://github.com/danielsz/system) :star:536
  * [mount](https://github.com/tolitius/mount) :star:758
  * [Integrant](https://github.com/weavejester/integrant) :star:434

## Build Automation and Package management

*Libraries for project build automation and package/dependency management.*

  * [Leiningen](https://github.com/technomancy/leiningen) :star:5879
  * [Boot](https://github.com/boot-clj/boot) :star:1446
  * [lucid.distribute](http://docs.caudate.me/lucidity/lucid-distribute.html)
  * [lucid.package](http://docs.caudate.me/lucidity/lucid-package.html)

## Version Control Management

*Code utilities for interacting with VCS software*

  * [lucid.git](http://docs.caudate.me/lucidity/lucid-git.html)

## Date and Time

*Libraries for working with dates and times.*

  * [clj-time](https://github.com/clj-time/clj-time) :star:622

## GUI

  * [fx-clj](https://github.com/aaronc/fx-clj) :star:91
  * [seesaw](https://github.com/daveray/seesaw) :star:1180

## Audio

  * [Overtone](http://overtone.github.io/)
  * [Alda](https://github.com/alda-lang/alda) :star:2916

## HTTP

*Libraries for working with HTTP.*

  * [clj-http](https://github.com/dakrone/clj-http) :star:1203
  * [http-kit](http://www.http-kit.org/)
  * [ring](https://github.com/ring-clojure/ring) :star:2536
  * [kvlt](https://github.com/nervous-systems/kvlt) :star:70

## Database

*Databases and database client libraries*

  * [Datomic](http://www.datomic.com/)
  * [clojure.jdbc](https://github.com/funcool/clojure.jdbc) :star:98
  * [cravendb](https://github.com/robashton/cravendb) :star:53
  * [Mongo](http://clojuremongodb.info/)
  * [Monglorious](https://baumandm.github.io/monglorious/)
  * [RethinkDB](https://github.com/apa512/clj-rethinkdb) :star:180
  * [Revise (RethinkDB)](https://github.com/bitemyapp/revise) :star:147
  * [ElasticSearch](http://clojureelasticsearch.info/)
  * [Neo4j](http://clojureneo4j.info/)

## Connection pools

*Database connection pools*

  * [hikari-cp](https://github.com/tomekw/hikari-cp) :star:207

## Structural Migrations

*Keeps database and others in sync*

  * [Lobos](https://github.com/budu/lobos) :star:261
  * [Ragtime](https://github.com/weavejester/ragtime) :star:392
  * [Joplin](https://github.com/juxt/joplin) :star:263
  * [Migratus](https://github.com/yogthos/migratus) :star:276
  * [Drift](https://github.com/macourtney/drift) :star:113

## Redis

  * [carmine](https://github.com/ptaoussanis/carmine) :star:778
  * [celtuce](https://github.com/lerouxrgd/celtuce) :star:7

## JSON

  * [cheshire](https://github.com/dakrone/cheshire) :star:1024

## Database Cli

## ORM and SQL generation

*DSL for SQL generation.*
  * [Walkable](https://github.com/walkable-server/walkable) :star:146
  * [Korma](http://sqlkorma.com/)
  * [Specql](https://github.com/tatut/specql/)
  * [stch-library/sql](https://github.com/stch-library/sql) :star:28
  * [sqlingvo](https://github.com/r0man/sqlingvo) :star:163
  * [sqlium](https://github.com/TheLadders/sqlium/)
  * [honeysql](https://github.com/jkk/honeysql) :star:803
  * [Toucan](https://github.com/metabase/toucan) :star:190

## Security

*Authentication, authorization and other security related libraries.*

  * [Buddy](https://github.com/funcool/buddy) :star:601
  * [Friend](https://github.com/cemerick/friend) :star:1119
  * [bolt](https://github.com/juxt/bolt) :star:125

## RESTful API

*Libraries for developing RESTful APIs.*

  * [Liberator](http://clojure-liberator.github.io/liberator/)
  * [compojure-api](https://github.com/metosin/compojure-api) :star:798
  * [Friboo](https://github.com/zalando/friboo) :star:113
  * [yada](https://github.com/juxt/yada) :star:542
  * [router](https://github.com/darkleaf/router) :star:73

## Emails

  * [postal](https://github.com/drewr/postal) :star:424

## HTML Manipulation

*Libraries for working with HTML.*

  * [Enlive](https://github.com/cgrand/enlive/wiki)
  * [hiccup](https://github.com/weavejester/hiccup) :star:1735
  * [clostache](https://github.com/fhd/clostache) :star:270
  * [selmer](https://github.com/yogthos/Selmer) :star:582

## Data Validation

*Libraries for validating data.*

  * [Validateur](http://clojurevalidations.info/)
  * [Prismatic's schema](https://github.com/plumatic/schema) :star:1831
  * [domaintypes](https://github.com/friemen/domaintypes) :star:5
  * [Bouncer](https://github.com/leonardoborges/bouncer) :star:320
  * [clova](https://github.com/markwoodhall/clova) :star:11
  * [Orchestra](https://github.com/jeaye/orchestra) :star:243

## Type System
*Optional type system for Clojure*

  * [core.typed](https://github.com/clojure/core.typed) :star:1004

## Pattern Matching

  * [core.match](https://github.com/clojure/core.match) :star:832
  * [Verbal-Exprejon](https://github.com/GuillaumeBadi/Verbal-Exprejon) :star:90
  * [defun](https://github.com/killme2008/defun) :star:342
  * [cats.match](https://github.com/zalando/cats.match) :star:39
  * [Akar](https://github.com/missingfaktor/akar) :star:164

## Async processing

  * [core.async](https://github.com/clojure/core.async/)
  * [pulsar](https://github.com/puniverse/pulsar) :star:811
  * [lamina](https://github.com/ztellman/lamina) :star:732
  * [aleph](https://github.com/ztellman/aleph) :star:1972

## Monads

  * [cats](https://github.com/funcool/cats) :star:648
  * [algo.monads](https://github.com/clojure/algo.monads) :star:352

## WebSocket

  * [Chord](https://github.com/jarohen/chord) :star:377
  * [Sente](https://github.com/ptaoussanis/sente) :star:1313

## Testing

  * [Expectations](https://github.com/clojure-expectations/expectations) :star:357
  * [Midje](https://github.com/marick/Midje) :star:1376
  * [lucid.unit](http://docs.caudate.me/lucidity/lucid-unit.html)

## Webdriver automation

  * [Etaoin](https://github.com/igrishaev/etaoin) :star:231

## Code Analysis and Linter

  * [Slamhound](https://github.com/technomancy/slamhound) :star:383
  * [eastwood](https://github.com/jonase/eastwood) :star:789
  * [kibit](https://github.com/jonase/kibit) :star:1401
  * [lucid.query](http://docs.caudate.me/lucidity/lucid-query.html)
  * [yagni](https://github.com/venantius/yagni) :star:161
  * [lein-bikeshed](https://github.com/dakrone/lein-bikeshed) :star:147
  * [spectrum](https://github.com/arohner/spectrum) :star:395
  * [cloverage](https://github.com/cloverage/cloverage) :star:294

## Science and Data Analysis

*Libraries, extended REPLs, and other tools for scientific and statistical data
anylysis and visualization.*

  * [Incanter](https://github.com/incanter/incanter) :star:1963
  * [Cascalog](http://cascalog.org/)
  * [Onyx](https://github.com/onyx-platform/onyx) :star:1723
  * [sparklling](https://github.com/gorillalabs/sparkling) :star:327
  * [flambo](https://github.com/yieldbot/flambo) :star:558
  * [Neanderthal](https://github.com/uncomplicate/neanderthal) :star:509
  * [lucid.graph](http://docs.caudate.me/lucidity/lucid-graph.html)
  * [Streaming Histograms](https://github.com/bigmlcom/histogram) :star:137
  * [Gorilla REPL](http://gorilla-repl.org/)  

## Machine Learning

  * [clj-ml](https://github.com/antoniogarrote/clj-ml) :star:138
  * [cortex](https://github.com/thinktopic/cortex) :star:1018
  * [clj-bigml](https://github.com/bigmlcom/clj-bigml) :star:48
  * [Clatern](https://github.com/rinuboney/clatern) :star:67
  * [Deeplearning4j](https://github.com/deeplearning4j/deeplearning4j) :star:8784
  * [Enclog](https://github.com/jimpil/enclog) :star:139
  * [Infer](https://github.com/aria42/infer) :star:171
  * [k9](https://github.com/gigasquid/k9) :star:98
  * [lambda-ml](https://github.com/cloudkj/lambda-ml) :star:39
  * [Statistiker](https://github.com/clojurewerkz/statistiker) :star:53
  * [Synaptic](https://github.com/japonophile/synaptic) :star:88

## Computer Vision

  * [clj-tesseract](https://github.com/antoniogarrote/clj-tesseract) :star:44
  * [vision](http://nakkaya.com/vision.html)

## Natural Language Processing

  * [clojure-opennlp](https://github.com/dakrone/clojure-opennlp) :star:653
  * [postagga](https://github.com/turbopape/postagga) :star:134

## Parsing

  * [Instaparse](https://github.com/Engelberg/instaparse) :star:1932
  * [kern](https://github.com/blancas/kern) :star:157
  * [duckling](https://github.com/wit-ai/duckling) :star:1286
  
## Exceptions and Error Handling
  * [Perseverance](https://github.com/grammarly/perseverance) :star:95
  * [Dire](https://github.com/MichaelDrogalis/dire) :star:474
  
## Reflection
*Libraries for improved code reflection and object introspection

  * [hara.reflect](docs.caudate.me/hara/hara-reflect.html)
  * [lucid.mind](http://docs.caudate.me/lucidity/lucid-mind.html)
  * [lucid.query](http://docs.caudate.me/lucidity/lucid-query.html)

## Editor Plugins

  * [CIDER (Emacs)](https://github.com/clojure-emacs/cider) :star:2376
  * [smartparens (Emacs)](https://github.com/Fuco1/smartparens) :star:975
  * [rainbow-delimiters (Emacs)](https://github.com/Fanael/rainbow-delimiters) :star:243
  * [aggressive-indent (Emacs)](https://github.com/Malabarba/aggressive-indent-mode) :star:394
  * [vim-fireplace (Vim)](https://github.com/tpope/vim-fireplace) :star:1340
  * [vim-redl (Vim)](https://github.com/dgrnbrg/vim-redl) :star:110
  * [vim-leiningen (Vim)](https://github.com/tpope/vim-salve) :star:137
  * [rainbow_parentheses.vim (Vim)](https://github.com/junegunn/rainbow_parentheses.vim) :star:187
  * [Cursive (IntelliJ)](https://cursive-ide.com/)
  * [Parinfer (multiple editors)](http://shaunlebron.github.io/parinfer/)

## Documentation

*Utilities and libraries for (non-LP) code and project documentation*

 * [lucid.publish](http://docs.caudate.me/lucidity/lucid-publish.html)

## Literate Programming

  * [marginalia](https://github.com/gdeer81/marginalia) :star:665
  * [klipse](https://github.com/viebel/klipse) :star:1561

## Archives and Compression

  * [swindon (java.util.zip wrapper)](https://github.com/AeroNotix/swindon) :star:2

## Miscellaneous

 * [clj-tuple](https://github.com/ztellman/clj-tuple) :star:173
 * [slingshot](https://github.com/scgilardi/slingshot) :star:513
 * [lucid.system](http://docs.caudate.me/lucidity/lucid-system.html)
 * [virgil](https://github.com/ztellman/virgil) :star:195
 * [javastar](https://github.com/tailrecursion/javastar) :star:58

## Debugging

  * [debugger](https://github.com/razum2um/clj-debugger) :star:201
  * [debug-repl](https://github.com/GeorgeJahad/debug-repl) :star:141
  * [ritz](https://github.com/pallet/ritz) :star:328
  * [redl](https://github.com/dgrnbrg/redl) :star:33
  * [limit-break](https://github.com/technomancy/limit-break) :star:16
  * [spyscope](https://github.com/dgrnbrg/spyscope) :star:440
  * [aprint](https://github.com/razum2um/aprint) :star:114
  * [packed-printer](https://github.com/cgrand/packed-printer) :star:32
  * [pretty](https://github.com/AvisoNovate/pretty) :star:380
  * [prone](https://github.com/magnars/prone) :star:471
  * [figwheel](https://github.com/bhauman/lein-figwheel) :star:2469
  * [ultra](https://github.com/venantius/ultra) :star:1048

## CI

  * [lambdacd](https://github.com/flosell/lambdacd) :star:529

## Guides

  * [The Clojure Style Guide](https://github.com/bbatsov/clojure-style-guide) :star:2852
  * [Clojure Distilled](http://yogthos.github.io/ClojureDistilled.html)
  * [clojure-cookbook](https://github.com/clojure-cookbook/clojure-cookbook) :star:1943
  * [A Brief Beginner's Guide To Clojure](http://www.unexpected-vortices.com/clojure/brief-beginners-guide/index.html)
  * [Clojure for the Brave and True](http://www.braveclojure.com/)
  * [Clojure from the ground up](https://aphyr.com/tags/Clojure-from-the-ground-up)
  * [Error message catalog](https://github.com/yogthos/clojure-error-message-catalog) :star:341
  * [Clojure by Example](https://kimh.github.io/clojure-by-example/)

## Websites

  * [Clojure](http://clojure.org/)
  * [Clojure Slack](http://clojurians.net/)
  * [clojuredocs](http://clojuredocs.org)
  * [crossclj](https://crossclj.info/)
  * [clojure-doc](http://clojure-doc.org/)
  * [Grimoire](http://conj.io/)
  * [The Clojure Toolbox](http://www.clojure-toolbox.com/)
  * [InstaREPL Online](http://web.clojurerepl.com/)
  * [ZEEF/Clojure](https://clojure.zeef.com/vlad.bokov)
  * [Try Clojure](http://www.tryclj.com/)

## Twitter

  * [oss_clj](https://twitter.com/oss_clj)

## Exercises

  * [Clojure Koans](http://clojurekoans.com)
  * [Wonderland Clojure Katas](https://github.com/gigasquid/wonderland-clojure-katas) :star:580
  * [Clojure Katas](http://clojurekatas.org)
  * [4clojure](http://www.4clojure.com/)
  * [exercism.io](http://exercism.io/languages/clojure)
  * [Clojurecademy](https://clojurecademy.com)
  * [Codewars](https://www.codewars.com/kata/search/clojure)

## Project Management
  
  * [milestones](https://github.com/turbopape/milestones) :star:76


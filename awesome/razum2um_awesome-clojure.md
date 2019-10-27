# Information comes from [razum2um/awesome-clojure](https://github.com/razum2um/awesome-clojure)
# Awesome Clojure [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

- [Awesome products in Clojure](#awesome-products-in-clojure)
  - [LightTable (IDE)](http://lighttable.com/)
  - [Nightcode (IDE)](https://sekao.net/nightcode/)
  - [Maria.cloud (Online IDE for beginners)](https://www.maria.cloud/)
  - [Riemann (Monitoring)](http://riemann.io/)
  - [Precursor (Online prototyping tool)](https://precursorapp.com/)
  - [Puppet Server](https://github.com/puppetlabs/puppet-server) :star:214
  - [PuppetDB](https://github.com/puppetlabs/puppetdb) :star:250
  - [Metabase](https://github.com/metabase/metabase) :star:17371
  - [Metabase Datomic](https://github.com/lambdaisland/metabase-datomic) :star:32
  - [CircleCI](https://circleci.com/)
  - [asciinema](https://asciinema.org/)
  - [Avi (vim rewrite)](https://github.com/maitria/avi) :star:198
  - [Liquid (Text Editor)](https://github.com/mogenslund/liquid) :star:739
  - [Nightlight (Text Editor)](https://github.com/oakes/Nightlight) :star:789
  - [Clojupyter](https://github.com/clojupyter/clojupyter) :star:508
  - [Meo](https://github.com/matthiasn/meo) :star:217
  - [Jepsen](https://github.com/jepsen-io/jepsen) :star:4184
  - [Braid](https://github.com/braidchat/braid): a team-chat app with a novel UI that leads to better conversations
  - [Atea](https://github.com/pkamenarsky/atea): a minimalistic menu bar time tracker for MacOS
  - [Accelerated Text](https://github.com/tokenmill/accelerated-text): a natural language generation environment (backend: Clojure, frontend: JS) :star:38
- [Languages written with Clojure](#languages-written-with-clojure)
  - [jank](https://github.com/jeaye/jank) :star:77
  - [lux](https://github.com/LuxLang/lux) :star:1065
  - [mal](https://github.com/kanaka/mal/tree/master/clojure) :star:6005
  - [scheje](https://github.com/turbopape/scheje) :star:83
  - [eden](https://github.com/benzap/eden) :star:93
- [Awesome tools in Clojure](#awesome-tools-in-clojure)
  - [Advanced datastructures](#advanced-datastructures)
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
  - [GraphQL API](#graphql-api)
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
  - [Text Processing](#text-processing)
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
  - [Terminal UI](#terminal-ui)
  - [Graphviz](#graphviz)

- [Resources](#resources)
  - [Guides](#guides)
  - [Video tutorials](#video-tutorials)
  - [Websites](#websites)
  - [Twitter](#twitter)
  - [Exercises](#exercises)

## Advanced datastructures

  * [Persistent AVL trees](https://github.com/clojure/data.avl): persistent sorted maps and sets with log-time rank queries
  * [Finger Tree](https://github.com/clojure/data.finger-tree): double-list, counted-double-list, counted-sorted-set
  * [Hitchhiker Tree](https://github.com/datacrypt-project/hitchhiker-tree): create fast, snapshottable, massively scalable databases
  * [Hierarchical set](https://github.com/llasram/hier-set) :star:4
  * [Ordered](https://github.com/amalloy/ordered): ordered sets and maps
  * [Lazy Map](https://github.com/Malabarba/lazy-map-clojure): whose values are only calculated when accessed
  * [Duratom](https://github.com/jimpil/duratom), [enduro](https://github.com/alandipert/enduro), [perdure](https://github.com/pesterhazy/perdure): atoms persisted on disk
  * [Durable Queue](https://github.com/Factual/durable-queue): queue persisted on disk
  * [bifurcan](https://github.com/lacuna/bifurcan): linear map/set/list (stores entries contiguously in memory), ;writtern in java, but test suite (read: usage examples) [in clojure](https://github.com/lacuna/bifurcan/blob/master/test/bifurcan) :star:772
  
## Web Framework

*Actually don't search rails/django here, but compose them by yourself*
  * [Compojure](https://github.com/weavejester/compojure) :star:3659
  * [Compojure-api](https://github.com/metosin/compojure-api) :star:967
  * [Web Non-Framework](https://github.com/webnf/webnf) :star:18
  * [Luminus](http://www.luminusweb.net/)
  * [Joodo](https://github.com/slagyr/joodoweb) :star:3
  * [Coils](https://github.com/l4u/coils)
  * [Duct](https://github.com/weavejester/duct) :star:869
  * [Pedestal](https://github.com/pedestal/pedestal) :star:2149
  * [Datsys](https://github.com/metasoarous/datsys) :star:194
  * [yada](https://github.com/juxt/yada) :star:644
  * [Hoplon](http://hoplon.io/)
  * [Fulcro](https://github.com/fulcrologic/fulcro) :star:584
  * [Coast](http://coastonclojure.com/)
  * [Reitit](https://github.com/metosin/reitit) :star:516

## Dependency injection

*Managed lifecycle of stateful objects*

  * [Component](https://github.com/stuartsierra/component) :star:1683
  * [System](https://github.com/danielsz/system) :star:569
  * [mount](https://github.com/tolitius/mount) :star:923
  * [Integrant](https://github.com/weavejester/integrant) :star:648

## Build Automation and Package management

*Libraries for project build automation and package/dependency management.*

  * [Leiningen](https://github.com/technomancy/leiningen) :star:6537
  * [Boot](https://github.com/boot-clj/boot) :star:1622
  * [lucid.distribute](http://docs.caudate.me/lucidity/lucid-distribute.html)
  * [lucid.package](http://docs.caudate.me/lucidity/lucid-package.html)
  * [clojurephant](https://github.com/clojurephant/clojurephant) (Gradle plugin) :star:95
  * [shadow-cljs](https://github.com/thheller/shadow-cljs) (Clojurescript) :star:1072

## Version Control Management

*Code utilities for interacting with VCS software*

  * [lucid.git](http://docs.caudate.me/lucidity/lucid-git.html)

## Date and Time

*Libraries for working with dates and times.*

  * [clj-time](https://github.com/clj-time/clj-time) :star:681
  * [clojure.java-time](https://github.com/dm3/clojure.java-time) - Java 8 Date-Time API :star:247
  * [timewords](https://github.com/tokenmill/timewords) :star:18

## GUI

  * [fx-clj](https://github.com/aaronc/fx-clj) :star:99
  * [seesaw](https://github.com/daveray/seesaw) :star:1292
  * [trikl](https://github.com/lambdaisland/trikl) :star:64

## Audio

  * [Overtone](http://overtone.github.io/)
  * [Alda](https://github.com/alda-lang/alda) :star:3430

## HTTP

*Libraries for working with HTTP.*

  * [clj-http](https://github.com/dakrone/clj-http) :star:1391
  * [http-kit](http://www.http-kit.org/)
  * [ring](https://github.com/ring-clojure/ring) :star:2909
  * [kvlt](https://github.com/nervous-systems/kvlt) :star:71
  * [aleph](https://github.com/ztellman/aleph) :star:2203

## Database

*Databases and database client libraries*

  * [Datomic](http://www.datomic.com/)
  * [Datahike](https://github.com/replikativ/datahike) :star:505
  * [Datascript](https://github.com/tonsky/datascript) :star:3382
  * [Cassandra](https://github.com/mpenet/alia) :star:202
  * [clojure.jdbc](https://github.com/funcool/clojure.jdbc) :star:103
  * [cravendb](https://github.com/robashton/cravendb) :star:56
  * [Mongo](http://clojuremongodb.info/)
  * [Monglorious](https://baumandm.github.io/monglorious/)
  * [RethinkDB](https://github.com/apa512/clj-rethinkdb) :star:190
  * [Revise (RethinkDB)](https://github.com/bitemyapp/revise) :star:146
  * [Spandex (ElasticSearch)](https://github.com/mpenet/spandex) :star:165
  * [Elastisch](http://clojureelasticsearch.info/)
  * [Neo4j](http://clojureneo4j.info/)
  * [Aerospike](https://github.com/AppsFlyer/aerospike-clj) :star:20

## Connection pools

*Database connection pools*

  * [hikari-cp](https://github.com/tomekw/hikari-cp) :star:272
  * [metabase/connection-pool](https://github.com/metabase/connection-pool) :star:2

## Structural Migrations

*Keeps database and others in sync*

  * [Lobos](https://github.com/budu/lobos) :star:263
  * [Ragtime](https://github.com/weavejester/ragtime) :star:449
  * [Joplin](https://github.com/juxt/joplin) :star:295
  * [Migratus](https://github.com/yogthos/migratus) :star:379
  * [Drift](https://github.com/macourtney/drift) :star:115

## Redis

  * [carmine](https://github.com/ptaoussanis/carmine) :star:896
  * [celtuce](https://github.com/lerouxrgd/celtuce) :star:16

## JSON

  * [cheshire](https://github.com/dakrone/cheshire) :star:1155
  * [jsonista](https://github.com/metosin/jsonista) :star:182

## Database Cli

## ORM and SQL generation

*DSL for SQL generation.*
  * [Walkable](https://github.com/walkable-server/walkable) :star:307
  * [Korma](http://sqlkorma.com/)
  * [Specql](https://github.com/tatut/specql/) :star:110
  * [stch-library/sql](https://github.com/stch-library/sql) :star:30
  * [sqlingvo](https://github.com/r0man/sqlingvo) :star:181
  * [sqlium](https://github.com/TheLadders/sqlium/) :star:26
  * [honeysql](https://github.com/jkk/honeysql) :star:1031
  * [Toucan](https://github.com/metabase/toucan) :star:343

## Security

*Authentication, authorization and other security related libraries.*

  * [Buddy](https://github.com/funcool/buddy) :star:698
  * [caesium](https://github.com/lvh/caesium) (libsodium bindings) :star:98
  * [Friend](https://github.com/cemerick/friend) :star:1154
  * [bolt](https://github.com/juxt/bolt) :star:127

## RESTful API

*Libraries for developing RESTful APIs.*

  * [Liberator](http://clojure-liberator.github.io/liberator/)
  * [Compojure-api](https://github.com/metosin/compojure-api) :star:967
  * [Friboo](https://github.com/zalando/friboo) :star:116
  * [yada](https://github.com/juxt/yada) :star:644
  * [router](https://github.com/darkleaf/router) :star:75
  * [reitit](https://github.com/metosin/reitit) :star:516

## GraphQL API

*Libraries for developing GraphQL APIs.*

  * [Lacinia](https://lacinia.readthedocs.io/en/latest/)

## Emails

  * [postal](https://github.com/drewr/postal) :star:465

## HTML Manipulation

*Libraries for working with HTML.*

  * [Enlive](https://github.com/cgrand/enlive/wiki) :star:1481
  * [hiccup](https://github.com/weavejester/hiccup) :star:1968
  * [clostache](https://github.com/fhd/clostache) :star:283
  * [selmer](https://github.com/yogthos/Selmer) :star:683

## Data Validation

*Libraries for validating data.*

  * [Validateur](http://clojurevalidations.info/)
  * [Prismatic's schema](https://github.com/plumatic/schema) :star:1996
  * [domaintypes](https://github.com/friemen/domaintypes) :star:5
  * [Bouncer](https://github.com/leonardoborges/bouncer) :star:346
  * [clova](https://github.com/markwoodhall/clova) :star:11
  * [Orchestra](https://github.com/jeaye/orchestra) :star:477

## Type System
*Optional type system for Clojure*

  * [core.typed](https://github.com/clojure/core.typed) :star:1122

## Pattern Matching

  * [core.match](https://github.com/clojure/core.match) :star:918
  * [Verbal-Exprejon](https://github.com/GuillaumeBadi/Verbal-Exprejon) :star:93
  * [defun](https://github.com/killme2008/defun) :star:396
  * [cats.match](https://github.com/zalando/cats.match) :star:46
  * [Akar](https://github.com/missingfaktor/akar) :star:173
  * [Meander](https://github.com/noprompt/meander) :star:355

## Async processing

  * [core.async](https://github.com/clojure/core.async/) :star:1656
  * [pulsar](https://github.com/puniverse/pulsar) :star:861
  * [manifold](https://github.com/ztellman/manifold) :star:737

## Monads

  * [cats](https://github.com/funcool/cats) :star:780
  * [algo.monads](https://github.com/clojure/algo.monads) :star:376
  * [Fluokitten](https://github.com/uncomplicate/fluokitten) :star:367

## WebSocket

  * [Chord](https://github.com/jarohen/chord) :star:395
  * [Sente](https://github.com/ptaoussanis/sente) :star:1427
  * [aleph](https://github.com/ztellman/aleph) :star:2203

## Testing

  * [Expectations](https://github.com/clojure-expectations/expectations) :star:382
  * [Midje](https://github.com/marick/Midje) :star:1525
  * [lucid.unit](http://docs.caudate.me/lucidity/lucid-unit.html)
  * [test-doubles](https://github.com/GreenPowerMonitor/test-doubles) 
  * [kaocha](https://github.com/lambdaisland/kaocha) :star:340

## Webdriver automation

  * [Etaoin](https://github.com/igrishaev/etaoin) :star:416

## Code Analysis and Linter

  * [Slamhound](https://github.com/technomancy/slamhound) :star:416
  * [eastwood](https://github.com/jonase/eastwood) :star:930
  * [kibit](https://github.com/jonase/kibit) :star:1567
  * [lucid.query](http://docs.caudate.me/lucidity/lucid-query.html)
  * [yagni](https://github.com/venantius/yagni) :star:204
  * [lein-bikeshed](https://github.com/dakrone/lein-bikeshed) :star:165
  * [spectrum](https://github.com/arohner/spectrum) :star:509
  * [cloverage](https://github.com/cloverage/cloverage) :star:372
  * [clj-kondo](https://github.com/borkdude/clj-kondo) :star:513

## Science and Data Analysis

*Libraries, extended REPLs, and other tools for scientific and statistical data
anylysis and visualization.*

  * [Incanter](https://github.com/incanter/incanter) :star:2106
  * [Cascalog](http://cascalog.org/)
  * [Onyx](https://github.com/onyx-platform/onyx) :star:1915
  * [sparklling](https://github.com/gorillalabs/sparkling) :star:379
  * [flambo](https://github.com/yieldbot/flambo) :star:594
  * [Neanderthal](https://github.com/uncomplicate/neanderthal) :star:762
  * [lucid.graph](http://docs.caudate.me/lucidity/lucid-graph.html)
  * [Streaming Histograms](https://github.com/bigmlcom/histogram) :star:147
  * [Gorilla REPL](http://gorilla-repl.org/)  
  * [Bayadera - Bayesian Data Analysis on the GPU](https://github.com/uncomplicate/bayadera) :star:317
  * [ClojureCUDA](https://github.com/uncomplicate/clojurecuda) :star:140
  * [Neanderthal - fast matrix and linear algebra](https://github.com/uncomplicate/neanderthal) :star:762
  * [ClojureCL - parallel computations with OpenCL](https://github.com/uncomplicate/clojurecl) :star:250
  * [Loom - graph library for Clojure](https://github.com/aysylu/loom) :star:671

## Machine Learning

  * [clj-ml](https://github.com/antoniogarrote/clj-ml) :star:148
  * [cortex](https://github.com/originrose/cortex) :star:1173
  * [clj-bigml](https://github.com/bigmlcom/clj-bigml) :star:51
  * [Clatern](https://github.com/rinuboney/clatern) :star:68
  * [Deeplearning4j](https://github.com/deeplearning4j/deeplearning4j) :star:11243
  * [Enclog](https://github.com/jimpil/enclog) :star:139
  * [Infer](https://github.com/aria42/infer) :star:176
  * [k9](https://github.com/gigasquid/k9) :star:102
  * [lambda-ml](https://github.com/cloudkj/lambda-ml) :star:63
  * [Statistiker](https://github.com/clojurewerkz/statistiker) :star:58
  * [Synaptic](https://github.com/japonophile/synaptic) :star:91
  * [clojure-tensorflow](https://github.com/kieranbrowne/clojure-tensorflow) :star:100
  * [dl4clj (deeplearning4j to clojure)](https://github.com/yetanalytics/dl4clj) :star:97
  * [Anglican](https://probprog.github.io/anglican/)

## Computer Vision

  * [clj-tesseract](https://github.com/antoniogarrote/clj-tesseract) :star:48
  * [vision](http://nakkaya.com/vision.html)

## Text Processing

  * [clojure-opennlp](https://github.com/dakrone/clojure-opennlp) :star:694
  * [postagga](https://github.com/turbopape/postagga) :star:147
  * [beagle](https://github.com/tokenmill/beagle) :star:25

## Parsing

  * [Instaparse](https://github.com/Engelberg/instaparse) :star:2181
  * [kern](https://github.com/blancas/kern) :star:188
  * [duckling](https://github.com/wit-ai/duckling) :star:1331
  
## Exceptions and Error Handling
  * [Ex](https://github.com/mpenet/ex) :star:17
  * [Perseverance](https://github.com/grammarly/perseverance) :star:134
  * [Dire](https://github.com/MichaelDrogalis/dire) :star:478
  
## Reflection
*Libraries for improved code reflection and object introspection

  * [hara.reflect](docs.caudate.me/hara/hara-reflect.html)
  * [lucid.mind](http://docs.caudate.me/lucidity/lucid-mind.html)
  * [lucid.query](http://docs.caudate.me/lucidity/lucid-query.html)

## Rule-based Programming
  * [Clara Rules](https://github.com/cerner/clara-rules) :star:887
  * [Arete](https://github.com/yipeeio/arete) :star:8

## Editor Plugins

  * [Calva (VSCode)](https://github.com/BetterThanTomorrow/calva) :star:447
  * [CIDER (Emacs)](https://github.com/clojure-emacs/cider) :star:2787
  * [smartparens (Emacs)](https://github.com/Fuco1/smartparens) :star:1214
  * [rainbow-delimiters (Emacs)](https://github.com/Fanael/rainbow-delimiters) :star:339
  * [aggressive-indent (Emacs)](https://github.com/Malabarba/aggressive-indent-mode) :star:543
  * [vim-cljfmt (Vim)](https://github.com/venantius/vim-cljfmt) :star:131
  * [vim-eastwood (Vim)](https://github.com/venantius/vim-eastwood) :star:80
  * [vim-fireplace (Vim)](https://github.com/tpope/vim-fireplace) :star:1510
  * [vim-redl (Vim)](https://github.com/dgrnbrg/vim-redl) :star:112
  * [vim-leiningen (Vim)](https://github.com/tpope/vim-salve) :star:157
  * [rainbow_parentheses.vim (Vim)](https://github.com/junegunn/rainbow_parentheses.vim) :star:244
  * [vim-iced (Vim)](https://github.com/liquidz/vim-iced) :star:141
  * [Cursive (IntelliJ)](https://cursive-ide.com/)
  * [Parinfer (multiple editors)](http://shaunlebron.github.io/parinfer/)
  * [Bracket Pair Colorizer (VSCode)](https://github.com/kristoft/awesome-clojure.git)

## Documentation

*Utilities and libraries for (non-LP) code and project documentation*

 * [lucid.publish](http://docs.caudate.me/lucidity/lucid-publish.html)

## Literate Programming

  * [marginalia](https://github.com/gdeer81/marginalia) :star:702
  * [klipse](https://github.com/viebel/klipse) :star:1943

## Archives and Compression

  * [swindon (java.util.zip wrapper)](https://github.com/AeroNotix/swindon) :star:2

## Miscellaneous

 * [potemkin](https://github.com/ztellman/potemkin) - reexport vars in another ns / act like a clojure map :star:438
 * [clj-tuple](https://github.com/ztellman/clj-tuple) :star:174
 * [slingshot](https://github.com/scgilardi/slingshot) :star:548
 * [lucid.system](http://docs.caudate.me/lucidity/lucid-system.html)
 * [virgil](https://github.com/ztellman/virgil) :star:239
 * [javastar](https://github.com/tailrecursion/javastar) :star:58
 * [riddley](https://github.com/ztellman/riddley) :star:146
 * [kezban](https://github.com/ertugrulcetin/kezban) :star:29

## Debugging

  * [tools.trace](https://github.com/clojure/tools.trace) :star:279
  * [debugger](https://github.com/razum2um/clj-debugger) :star:233
  * [debug-repl](https://github.com/GeorgeJahad/debug-repl) :star:140
  * [ritz](https://github.com/pallet/ritz) :star:321
  * [redl](https://github.com/dgrnbrg/redl) :star:32
  * [limit-break](https://github.com/technomancy/limit-break) :star:16
  * [spyscope](https://github.com/dgrnbrg/spyscope) :star:492
  * [aprint](https://github.com/razum2um/aprint) :star:123
  * [packed-printer](https://github.com/cgrand/packed-printer) :star:33
  * [pretty](https://github.com/AvisoNovate/pretty) :star:451
  * [prone](https://github.com/magnars/prone) :star:482
  * [figwheel](https://github.com/bhauman/lein-figwheel) :star:2747
  * [ultra](https://github.com/venantius/ultra) :star:1183
  * [mate-clj](https://github.com/AppsFlyer/mate-clj) :star:10

## CI

  * [lambdacd](https://github.com/flosell/lambdacd) :star:622
  
## Project Management
  
  * [milestones](https://github.com/turbopape/milestones) :star:91

## Terminal UI

  * [clojure-lanterna](https://sjl.bitbucket.io/clojure-lanterna/)
  * [triki](https://github.com/lambdaisland/trikl) :star:64
  * [zaffre](https://github.com/aaron-santos/zaffre) :star:31
  * [closh](https://github.com/dundalek/closh) :star:1220
  
## Graphviz

  * [zipper-viz](https://github.com/lambdaisland/zipper-viz) :star:3
  * [dorothy](https://github.com/daveray/dorothy) :star:190
  * [viz.cljc](https://github.com/jebberjeb/viz.cljc) :star:24
  * [fsmviz](https://github.com/jebberjeb/fsmviz) :star:43
  * [rhizome](https://github.com/ztellman/rhizome) :star:393

## Guides

  * [The Clojure Style Guide](https://github.com/bbatsov/clojure-style-guide) :star:3295
  * [Clojure Distilled](http://yogthos.github.io/ClojureDistilled.html)
  * [clojure-cookbook](https://github.com/clojure-cookbook/clojure-cookbook) :star:2215
  * [A Brief Beginner's Guide To Clojure](http://www.unexpected-vortices.com/clojure/brief-beginners-guide/index.html)
  * [Clojure for the Brave and True](http://www.braveclojure.com/)
  * [Clojure from the ground up](https://aphyr.com/tags/Clojure-from-the-ground-up)
  * [Error message catalog](https://github.com/yogthos/clojure-error-message-catalog) :star:404
  * [Clojure by Example](https://kimh.github.io/clojure-by-example/)

## Video tutorials

### YouTube

  * [Misophistful's channel](https://www.youtube.com/user/Misophistful/videos): Understand concepts such as list comprehension, threading macros, generative testing, destructuring, core.match and introductions to Light Table, Datomic and Game development with Clojure
  * [Fred Overflow's channel](https://www.youtube.com/channel/UC9m7D4XKPJqTPCLSBym3BCg/search?query=Clojure): Introductions to Functional programming and TDD with Clojure
  * [Clojure Pills screencast](https://www.youtube.com/channel/UCH0CkLvbv6yEyrUnw9qujpQ/videos): Introduction to Clojure one function at a time
  * [Data persistance with Postgres, Clojure and JDBC](https://www.youtube.com/channel/UCrwwOZ4h2FQhAdTMfjyQfQA/playlists)
  * [Clojure Tutorials by Timothy Baldridge](https://www.youtube.com/channel/UC6yONKYeoE2P3bsahDtsimg/videos): More advanced videos on core.async, tranducers, transients, logic programming and a "Function of the day" series.

## Websites

  * [Clojure](http://clojure.org/)
  * [Clojure Slack](http://clojurians.net/)
  * [clojuredocs](http://clojuredocs.org)
  * [crossclj](https://crossclj.info/)
  * [clojure-doc](http://clojure-doc.org/)
  * [The Clojure Toolbox](http://www.clojure-toolbox.com/)
  * [InstaREPL Online](http://web.clojurerepl.com/)
  * [ZEEF/Clojure](https://clojure.zeef.com/vlad.bokov)
  * [Try Clojure](http://www.tryclj.com/)

## Twitter

  * [oss_clj](https://twitter.com/oss_clj)

## Exercises

  * [Clojure Koans](http://clojurekoans.com)
  * [Wonderland Clojure Katas](https://github.com/gigasquid/wonderland-clojure-katas) :star:698
  * [Clojure Katas](http://clojurekatas.org)
  * [4clojure](http://www.4clojure.com/)
  * [exercism.io](http://exercism.io/languages/clojure)
  * [Clojurecademy](https://clojurecademy.com)
  * [Codewars](https://www.codewars.com/kata/search/clojure)


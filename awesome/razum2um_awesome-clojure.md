# Information comes from [razum2um/awesome-clojure](https://github.com/razum2um/awesome-clojure)
# Awesome Clojure [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

- [Awesome products in Clojure](#awesome-products-in-clojure)
  - [LightTable (IDE)](http://lighttable.com/)
  - [Nightcode (IDE)](https://sekao.net/nightcode/)
  - [Maria.cloud (Online IDE for beginners)](https://www.maria.cloud/)
  - [Riemann (Monitoring)](http://riemann.io/)
  - [Precursor (Online prototyping tool)](https://precursorapp.com/)
  - [Puppet Server](https://github.com/puppetlabs/puppet-server) :star:219
  - [PuppetDB](https://github.com/puppetlabs/puppetdb) :star:252
  - [Metabase](https://github.com/metabase/metabase) :star:19044
  - [Metabase Datomic](https://github.com/lambdaisland/metabase-datomic) :star:39
  - [CircleCI](https://circleci.com/)
  - [asciinema](https://asciinema.org/)
  - [Avi (vim rewrite)](https://github.com/maitria/avi) :star:198
  - [Liquid (Text Editor)](https://github.com/mogenslund/liquid) :star:752
  - [Nightlight (Text Editor)](https://github.com/oakes/Nightlight) :star:793
  - [Clojupyter](https://github.com/clojupyter/clojupyter) :star:538
  - [meins](https://github.com/matthiasn/meins) :star:233
  - [Jepsen](https://github.com/jepsen-io/jepsen) :star:4336
  - [Braid](https://github.com/braidchat/braid): a team-chat app with a novel UI that leads to better conversations
  - [Atea](https://github.com/pkamenarsky/atea): a minimalistic menu bar time tracker for MacOS
  - [Accelerated Text](https://github.com/tokenmill/accelerated-text): a natural language generation environment (backend: Clojure, frontend: JS) :star:94
- [Languages written with Clojure](#languages-written-with-clojure)
  - [jank](https://github.com/jeaye/jank) :star:78
  - [lux](https://github.com/LuxLang/lux) :star:1124
  - [mal](https://github.com/kanaka/mal/tree/master/clojure) :star:6599
  - [scheje](https://github.com/turbopape/scheje) :star:84
  - [eden](https://github.com/benzap/eden) :star:94
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
  * [Hierarchical set](https://github.com/llasram/hier-set) :star:5
  * [Ordered](https://github.com/amalloy/ordered): ordered sets and maps
  * [Lazy Map](https://github.com/Malabarba/lazy-map-clojure): whose values are only calculated when accessed
  * [Duratom](https://github.com/jimpil/duratom), [enduro](https://github.com/alandipert/enduro), [perdure](https://github.com/pesterhazy/perdure): atoms persisted on disk
  * [Durable Queue](https://github.com/Factual/durable-queue): queue persisted on disk
  * [bifurcan](https://github.com/lacuna/bifurcan): linear map/set/list (stores entries contiguously in memory), ;writtern in java, but test suite (read: usage examples) [in clojure](https://github.com/lacuna/bifurcan/blob/master/test/bifurcan) :star:819
  
## Web Framework

*Actually don't search rails/django here, but compose them by yourself*
  * [Compojure](https://github.com/weavejester/compojure) :star:3703
  * [Compojure-api](https://github.com/metosin/compojure-api) :star:992
  * [Web Non-Framework](https://github.com/webnf/webnf) :star:19
  * [Luminus](http://www.luminusweb.net/)
  * [Joodo](https://github.com/slagyr/joodoweb) :star:4
  * [Coils](https://github.com/l4u/coils) :star:2
  * [Duct](https://github.com/weavejester/duct) :star:900
  * [Pedestal](https://github.com/pedestal/pedestal) :star:2197
  * [Datsys](https://github.com/metasoarous/datsys) :star:197
  * [yada](https://github.com/juxt/yada) :star:651
  * [Hoplon](http://hoplon.io/)
  * [Fulcro](https://github.com/fulcrologic/fulcro) :star:672
  * [Coast](http://coastonclojure.com/)
  * [Reitit](https://github.com/metosin/reitit) :star:560

## Dependency injection

*Managed lifecycle of stateful objects*

  * [Component](https://github.com/stuartsierra/component) :star:1713
  * [System](https://github.com/danielsz/system) :star:574
  * [mount](https://github.com/tolitius/mount) :star:948
  * [Integrant](https://github.com/weavejester/integrant) :star:696

## Build Automation and Package management

*Libraries for project build automation and package/dependency management.*

  * [Leiningen](https://github.com/technomancy/leiningen) :star:6616
  * [Boot](https://github.com/boot-clj/boot) :star:1644
  * [lucid.distribute](http://docs.caudate.me/lucidity/lucid-distribute.html)
  * [lucid.package](http://docs.caudate.me/lucidity/lucid-package.html)
  * [clojurephant](https://github.com/clojurephant/clojurephant) (Gradle plugin) :star:99
  * [shadow-cljs](https://github.com/thheller/shadow-cljs) (Clojurescript) :star:1161

## Version Control Management

*Code utilities for interacting with VCS software*

  * [lucid.git](http://docs.caudate.me/lucidity/lucid-git.html)

## Date and Time

*Libraries for working with dates and times.*

  * [clj-time](https://github.com/clj-time/clj-time) :star:690
  * [clojure.java-time](https://github.com/dm3/clojure.java-time) - Java 8 Date-Time API :star:253
  * [timewords](https://github.com/tokenmill/timewords) :star:20

## GUI

  * [fx-clj](https://github.com/aaronc/fx-clj) :star:99
  * [seesaw](https://github.com/daveray/seesaw) :star:1304
  * [trikl](https://github.com/lambdaisland/trikl) :star:70

## Audio

  * [Overtone](http://overtone.github.io/)
  * [Alda](https://github.com/alda-lang/alda) :star:3492

## HTTP

*Libraries for working with HTTP.*

  * [clj-http](https://github.com/dakrone/clj-http) :star:1409
  * [http-kit](http://www.http-kit.org/)
  * [ring](https://github.com/ring-clojure/ring) :star:2977
  * [kvlt](https://github.com/nervous-systems/kvlt) :star:71
  * [aleph](https://github.com/ztellman/aleph) :star:2232

## Database

*Databases and database client libraries*

  * [Datomic](http://www.datomic.com/)
  * [Datahike](https://github.com/replikativ/datahike) :star:604
  * [Datascript](https://github.com/tonsky/datascript) :star:3470
  * [Cassandra](https://github.com/mpenet/alia) :star:204
  * [clojure.jdbc](https://github.com/funcool/clojure.jdbc) :star:103
  * [cravendb](https://github.com/robashton/cravendb) :star:56
  * [Mongo](http://clojuremongodb.info/)
  * [Monglorious](https://baumandm.github.io/monglorious/)
  * [RethinkDB](https://github.com/apa512/clj-rethinkdb) :star:191
  * [Revise (RethinkDB)](https://github.com/bitemyapp/revise) :star:146
  * [Spandex (ElasticSearch)](https://github.com/mpenet/spandex) :star:169
  * [Elastisch](http://clojureelasticsearch.info/)
  * [Neo4j](http://clojureneo4j.info/)
  * [Aerospike](https://github.com/AppsFlyer/aerospike-clj) :star:20

## Connection pools

*Database connection pools*

  * [hikari-cp](https://github.com/tomekw/hikari-cp) :star:293
  * [metabase/connection-pool](https://github.com/metabase/connection-pool) :star:3

## Structural Migrations

*Keeps database and others in sync*

  * [Lobos](https://github.com/budu/lobos) :star:262
  * [Ragtime](https://github.com/weavejester/ragtime) :star:464
  * [Joplin](https://github.com/juxt/joplin) :star:297
  * [Migratus](https://github.com/yogthos/migratus) :star:390
  * [Drift](https://github.com/macourtney/drift) :star:114

## Redis

  * [carmine](https://github.com/ptaoussanis/carmine) :star:906
  * [celtuce](https://github.com/lerouxrgd/celtuce) :star:19

## JSON

  * [cheshire](https://github.com/dakrone/cheshire) :star:1184
  * [jsonista](https://github.com/metosin/jsonista) :star:189

## Database Cli

## ORM and SQL generation

*DSL for SQL generation.*
  * [Walkable](https://github.com/walkable-server/walkable) :star:323
  * [Korma](http://sqlkorma.com/)
  * [Specql](https://github.com/tatut/specql/) :star:114
  * [stch-library/sql](https://github.com/stch-library/sql) :star:32
  * [sqlingvo](https://github.com/r0man/sqlingvo) :star:185
  * [sqlium](https://github.com/TheLadders/sqlium/) :star:26
  * [honeysql](https://github.com/jkk/honeysql) :star:1071
  * [Toucan](https://github.com/metabase/toucan) :star:384

## Security

*Authentication, authorization and other security related libraries.*

  * [Buddy](https://github.com/funcool/buddy) :star:713
  * [caesium](https://github.com/lvh/caesium) (libsodium bindings) :star:101
  * [Friend](https://github.com/cemerick/friend) :star:1158
  * [bolt](https://github.com/juxt/bolt) :star:126

## RESTful API

*Libraries for developing RESTful APIs.*

  * [Liberator](http://clojure-liberator.github.io/liberator/)
  * [Compojure-api](https://github.com/metosin/compojure-api) :star:992
  * [Friboo](https://github.com/zalando/friboo) :star:116
  * [yada](https://github.com/juxt/yada) :star:651
  * [router](https://github.com/darkleaf/router) :star:75
  * [reitit](https://github.com/metosin/reitit) :star:560

## GraphQL API

*Libraries for developing GraphQL APIs.*

  * [Lacinia](https://lacinia.readthedocs.io/en/latest/)

## Emails

  * [postal](https://github.com/drewr/postal) :star:472

## HTML Manipulation

*Libraries for working with HTML.*

  * [Enlive](https://github.com/cgrand/enlive/wiki) :star:1495
  * [hiccup](https://github.com/weavejester/hiccup) :star:2013
  * [clostache](https://github.com/fhd/clostache) :star:284
  * [selmer](https://github.com/yogthos/Selmer) :star:705

## Data Validation

*Libraries for validating data.*

  * [Validateur](http://clojurevalidations.info/)
  * [Prismatic's schema](https://github.com/plumatic/schema) :star:2015
  * [domaintypes](https://github.com/friemen/domaintypes) :star:5
  * [Bouncer](https://github.com/leonardoborges/bouncer) :star:353
  * [clova](https://github.com/markwoodhall/clova) :star:11
  * [Orchestra](https://github.com/jeaye/orchestra) :star:488

## Type System
*Optional type system for Clojure*

  * [core.typed](https://github.com/clojure/core.typed) :star:1131

## Pattern Matching

  * [core.match](https://github.com/clojure/core.match) :star:936
  * [Verbal-Exprejon](https://github.com/GuillaumeBadi/Verbal-Exprejon) :star:92
  * [defun](https://github.com/killme2008/defun) :star:398
  * [cats.match](https://github.com/zalando/cats.match) :star:46
  * [Akar](https://github.com/missingfaktor/akar) :star:173
  * [Meander](https://github.com/noprompt/meander) :star:407

## Async processing

  * [core.async](https://github.com/clojure/core.async/) :star:1686
  * [pulsar](https://github.com/puniverse/pulsar) :star:870
  * [manifold](https://github.com/ztellman/manifold) :star:756

## Monads

  * [cats](https://github.com/funcool/cats) :star:793
  * [algo.monads](https://github.com/clojure/algo.monads) :star:380
  * [Fluokitten](https://github.com/uncomplicate/fluokitten) :star:374

## WebSocket

  * [Chord](https://github.com/jarohen/chord) :star:398
  * [Sente](https://github.com/ptaoussanis/sente) :star:1453
  * [aleph](https://github.com/ztellman/aleph) :star:2232

## Testing

  * [Expectations](https://github.com/clojure-expectations/expectations) :star:386
  * [Midje](https://github.com/marick/Midje) :star:1548
  * [lucid.unit](http://docs.caudate.me/lucidity/lucid-unit.html)
  * [test-doubles](https://github.com/GreenPowerMonitor/test-doubles) 
  * [kaocha](https://github.com/lambdaisland/kaocha) :star:375

## Webdriver automation

  * [Etaoin](https://github.com/igrishaev/etaoin) :star:445

## Code Analysis and Linter

  * [Slamhound](https://github.com/technomancy/slamhound) :star:418
  * [eastwood](https://github.com/jonase/eastwood) :star:941
  * [kibit](https://github.com/jonase/kibit) :star:1581
  * [lucid.query](http://docs.caudate.me/lucidity/lucid-query.html)
  * [yagni](https://github.com/venantius/yagni) :star:205
  * [lein-bikeshed](https://github.com/dakrone/lein-bikeshed) :star:168
  * [spectrum](https://github.com/arohner/spectrum) :star:521
  * [cloverage](https://github.com/cloverage/cloverage) :star:381
  * [clj-kondo](https://github.com/borkdude/clj-kondo) :star:647

## Science and Data Analysis

*Libraries, extended REPLs, and other tools for scientific and statistical data
anylysis and visualization.*

  * [Incanter](https://github.com/incanter/incanter) :star:2121
  * [Cascalog](http://cascalog.org/)
  * [Onyx](https://github.com/onyx-platform/onyx) :star:1933
  * [sparklling](https://github.com/gorillalabs/sparkling) :star:382
  * [flambo](https://github.com/yieldbot/flambo) :star:600
  * [Neanderthal](https://github.com/uncomplicate/neanderthal) :star:786
  * [lucid.graph](http://docs.caudate.me/lucidity/lucid-graph.html)
  * [Streaming Histograms](https://github.com/bigmlcom/histogram) :star:146
  * [Gorilla REPL](http://gorilla-repl.org/)  
  * [Bayadera - Bayesian Data Analysis on the GPU](https://github.com/uncomplicate/bayadera) :star:323
  * [ClojureCUDA](https://github.com/uncomplicate/clojurecuda) :star:146
  * [Neanderthal - fast matrix and linear algebra](https://github.com/uncomplicate/neanderthal) :star:786
  * [ClojureCL - parallel computations with OpenCL](https://github.com/uncomplicate/clojurecl) :star:252
  * [Loom - graph library for Clojure](https://github.com/aysylu/loom) :star:687

## Machine Learning

  * [clj-ml](https://github.com/antoniogarrote/clj-ml) :star:147
  * [cortex](https://github.com/originrose/cortex) :star:1187
  * [clj-bigml](https://github.com/bigmlcom/clj-bigml) :star:51
  * [Clatern](https://github.com/rinuboney/clatern) :star:68
  * [Deeplearning4j](https://github.com/deeplearning4j/deeplearning4j) :star:11428
  * [Enclog](https://github.com/jimpil/enclog) :star:139
  * [Infer](https://github.com/aria42/infer) :star:178
  * [k9](https://github.com/gigasquid/k9) :star:102
  * [lambda-ml](https://github.com/cloudkj/lambda-ml) :star:64
  * [Statistiker](https://github.com/clojurewerkz/statistiker) :star:58
  * [Synaptic](https://github.com/japonophile/synaptic) :star:91
  * [clojure-tensorflow](https://github.com/kieranbrowne/clojure-tensorflow) :star:105
  * [dl4clj (deeplearning4j to clojure)](https://github.com/yetanalytics/dl4clj) :star:98
  * [Anglican](https://probprog.github.io/anglican/)

## Computer Vision

  * [clj-tesseract](https://github.com/antoniogarrote/clj-tesseract) :star:48
  * [vision](http://nakkaya.com/vision.html)

## Text Processing

  * [clojure-opennlp](https://github.com/dakrone/clojure-opennlp) :star:705
  * [postagga](https://github.com/turbopape/postagga) :star:146
  * [beagle](https://github.com/tokenmill/beagle) :star:26

## Parsing

  * [Instaparse](https://github.com/Engelberg/instaparse) :star:2223
  * [kern](https://github.com/blancas/kern) :star:190
  * [duckling](https://github.com/wit-ai/duckling) :star:1332
  * [buran](https://github.com/alekseysotnikov/buran) - RSS/Atom feed consumer and producer :star:19
  
## Exceptions and Error Handling
  * [Ex](https://github.com/mpenet/ex) :star:18
  * [Perseverance](https://github.com/grammarly/perseverance) :star:136
  * [Dire](https://github.com/MichaelDrogalis/dire) :star:479
  
## Reflection
*Libraries for improved code reflection and object introspection

  * [hara.reflect](docs.caudate.me/hara/hara-reflect.html)
  * [lucid.mind](http://docs.caudate.me/lucidity/lucid-mind.html)
  * [lucid.query](http://docs.caudate.me/lucidity/lucid-query.html)

## Rule-based Programming
  * [Clara Rules](https://github.com/cerner/clara-rules) :star:905
  * [Arete](https://github.com/yipeeio/arete) :star:8

## Editor Plugins

  * [Calva (VSCode)](https://github.com/BetterThanTomorrow/calva) :star:514
  * [CIDER (Emacs)](https://github.com/clojure-emacs/cider) :star:2830
  * [smartparens (Emacs)](https://github.com/Fuco1/smartparens) :star:1246
  * [rainbow-delimiters (Emacs)](https://github.com/Fanael/rainbow-delimiters) :star:352
  * [aggressive-indent (Emacs)](https://github.com/Malabarba/aggressive-indent-mode) :star:572
  * [vim-cljfmt (Vim)](https://github.com/venantius/vim-cljfmt) :star:133
  * [vim-eastwood (Vim)](https://github.com/venantius/vim-eastwood) :star:82
  * [vim-fireplace (Vim)](https://github.com/tpope/vim-fireplace) :star:1529
  * [vim-redl (Vim)](https://github.com/dgrnbrg/vim-redl) :star:111
  * [vim-leiningen (Vim)](https://github.com/tpope/vim-salve) :star:165
  * [rainbow_parentheses.vim (Vim)](https://github.com/junegunn/rainbow_parentheses.vim) :star:248
  * [vim-iced (Vim)](https://github.com/liquidz/vim-iced) :star:164
  * [Cursive (IntelliJ)](https://cursive-ide.com/)
  * [Parinfer (multiple editors)](http://shaunlebron.github.io/parinfer/)
  * [Bracket Pair Colorizer (VSCode)](https://github.com/kristoft/awesome-clojure.git)

## Documentation

*Utilities and libraries for (non-LP) code and project documentation*

 * [lucid.publish](http://docs.caudate.me/lucidity/lucid-publish.html)

## Literate Programming

  * [marginalia](https://github.com/gdeer81/marginalia) :star:714
  * [klipse](https://github.com/viebel/klipse) :star:1987

## Archives and Compression

  * [swindon (java.util.zip wrapper)](https://github.com/AeroNotix/swindon) :star:2

## Miscellaneous

 * [potemkin](https://github.com/ztellman/potemkin) - reexport vars in another ns / act like a clojure map :star:444
 * [clj-tuple](https://github.com/ztellman/clj-tuple) :star:174
 * [slingshot](https://github.com/scgilardi/slingshot) :star:556
 * [lucid.system](http://docs.caudate.me/lucidity/lucid-system.html)
 * [virgil](https://github.com/ztellman/virgil) :star:243
 * [javastar](https://github.com/tailrecursion/javastar) :star:58
 * [riddley](https://github.com/ztellman/riddley) :star:149
 * [kezban](https://github.com/ertugrulcetin/kezban) :star:30

## Debugging

  * [tools.trace](https://github.com/clojure/tools.trace) :star:286
  * [debugger](https://github.com/razum2um/clj-debugger) :star:235
  * [debug-repl](https://github.com/GeorgeJahad/debug-repl) :star:142
  * [ritz](https://github.com/pallet/ritz) :star:322
  * [redl](https://github.com/dgrnbrg/redl) :star:32
  * [limit-break](https://github.com/technomancy/limit-break) :star:22
  * [spyscope](https://github.com/dgrnbrg/spyscope) :star:502
  * [aprint](https://github.com/razum2um/aprint) :star:124
  * [packed-printer](https://github.com/cgrand/packed-printer) :star:33
  * [pretty](https://github.com/AvisoNovate/pretty) :star:454
  * [prone](https://github.com/magnars/prone) :star:489
  * [figwheel](https://github.com/bhauman/lein-figwheel) :star:2768
  * [ultra](https://github.com/venantius/ultra) :star:1195
  * [mate-clj](https://github.com/AppsFlyer/mate-clj) :star:20

## CI

  * [lambdacd](https://github.com/flosell/lambdacd) :star:627
  
## Project Management
  
  * [milestones](https://github.com/turbopape/milestones) :star:94

## Terminal UI

  * [clojure-lanterna](https://sjl.bitbucket.io/clojure-lanterna/)
  * [triki](https://github.com/lambdaisland/trikl) :star:70
  * [zaffre](https://github.com/aaron-santos/zaffre) :star:35
  * [closh](https://github.com/dundalek/closh) :star:1269
  
## Graphviz

  * [zipper-viz](https://github.com/lambdaisland/zipper-viz) :star:3
  * [dorothy](https://github.com/daveray/dorothy) :star:192
  * [viz.cljc](https://github.com/jebberjeb/viz.cljc) :star:24
  * [fsmviz](https://github.com/jebberjeb/fsmviz) :star:43
  * [rhizome](https://github.com/ztellman/rhizome) :star:394

## Guides

  * [The Clojure Style Guide](https://github.com/bbatsov/clojure-style-guide) :star:3357
  * [Clojure Distilled](http://yogthos.github.io/ClojureDistilled.html)
  * [clojure-cookbook](https://github.com/clojure-cookbook/clojure-cookbook) :star:2243
  * [A Brief Beginner's Guide To Clojure](http://www.unexpected-vortices.com/clojure/brief-beginners-guide/index.html)
  * [Clojure for the Brave and True](http://www.braveclojure.com/)
  * [Clojure from the ground up](https://aphyr.com/tags/Clojure-from-the-ground-up)
  * [Error message catalog](https://github.com/yogthos/clojure-error-message-catalog) :star:405
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
  * [Wonderland Clojure Katas](https://github.com/gigasquid/wonderland-clojure-katas) :star:713
  * [Clojure Katas](http://clojurekatas.org)
  * [4clojure](http://www.4clojure.com/)
  * [exercism.io](http://exercism.io/languages/clojure)
  * [Clojurecademy](https://clojurecademy.com)
  * [Codewars](https://www.codewars.com/kata/search/clojure)


# Information comes from [hantuzun/awesome-clojurescript](https://github.com/hantuzun/awesome-clojurescript)

<img src="https://avatars2.githubusercontent.com/u/12118456?v=3&s=75"
     align="right"/>

# Awesome ClojureScript

##### A community driven list of ClojureScript books, frameworks, libraries and wrappers.

* * *

  - [Resources](#resources)
      - [Books](#books)
  - [Awesome ClojureScript](#awesome-clojurescript)
      - [Canvas](#canvas)
      - [Client/Server Communication](#clientserver-communication)
      - [Code Analysis](#code-analysis)
      - [Data Serialization](#data-serialization)
      - [Data Visualization](#data-visualization)
      - [Database](#database)
      - [Development](#development)
      - [Document Object Model](#document-object-model)
      - [Documentation](#documentation)
      - [Graphics](#graphics)
      - [HTTP Handler](#http-handler)
      - [Internationalization](#internationalization)
      - [JavaScript Interoperability](#javascript-interoperability)
      - [Miscellaneous](#miscellaneous)
      - [React.js Interface](#reactjs-interface)
      - [Reactive Programming](#reactive-programming)
      - [Routing](#routing)
      - [State Management](#state-management)
      - [Testing](#testing)
      - [Validation](#validation)
      - [Web Framework & Template](#web-framework--template)
      - [WebSockets](#websockets)
  - [Contributing](#contributing)
  - [License](#license)


* * *


## Resources


### Books
- [ClojureScript Unraveled](https://leanpub.com/clojurescript-unraveled) – An open source book about the ClojureScript language that covers all the language features, how to use the compiler and the tooling for building applications and libraries.
- [ClojureScript: Up and Running](https://shop.oreilly.com/product/0636920025139.do) – An introduction to ClojureScript written by big guns of Clojure Stuart Sierra and Luke VanderHart.
- [Etudes for ClojureScript](https://shop.oreilly.com/product/0636920043584.do) – A hands-on-book of 30 companion exercises or études for introducing ClojureScript.
- [Learning ClojureScript](https://www.packtpub.com/web-development/learning-clojurescript) – Master the art of agile single page web application development with ClojureScript.
- [Transforming Data with ClojureScript](https://langintro.com/cljsbook) – A beginner's guide to ClojureScript with interactive examples and exercises, "focusing on the main task that programming does—transforming data".


### Courses
- [ClojureScript Koans](http://clojurescriptkoans.com/) – A great way to start learning Clojure and ClojureScript on the web with interactive challanges.
- [Lambda Island](https://lambdaisland.com/) – A full-stack web development course including front-end with ClojureScript, back-end with Clojure, language essentials, security, internet standards and system administration.
- [Learn Reagent](https://www.learnreagent.com/) – An introduction to ClojureScript with Reagent for developers. 1 hour free content is available. [learn re-frame](https://www.learnreframe.com/) is its follow up.
- [Learning ClojureScript](https://purelyfunctional.tv/) – A 2h 11m long introduction to Clojurescript by O'Really Online Learning. Also available on [Udemy](https://www.udemy.com/course/learning-clojurescript/).


### Videos
- [ClojureScript for Skeptics](https://www.youtube.com/watch?v=gsffg5xxFQI) – Derek Slager's talk for Clojure Conj 2015 where he is Discussing the many reasons why ClojureScript is in fact a very pragmatic language to consider for web development.
- [Interactive programming Flappy Bird in ClojureScript](https://www.youtube.com/watch?v=KZjFVdU8VLI) – A 5 minutes video from 2014 demostrating the power of ClojureScript's developer experience.


## Awesome ClojureScript


### Canvas
- [Monet](https://github.com/rm-hull/monet) – A small ClojureScript library to make it easier to work with canvas and visuals.
- [Quamolit](https://github.com/Quamolit/quamolit) – A tiny declarative animation library , inspired by React.


### Client/Server Communication
- [cljs-ajax](https://github.com/JulianBirch/cljs-ajax) – A simple Ajax client for ClojureScript and Clojure.
- [Fetch](https://github.com/LightTable/fetch) – A ClojureScript library that makes client/server interaction painless.


### Code Analysis
- [kibit](https://github.com/jonase/kibit) – Static code analyzer to find patterns of code that could be rewritten with a more idiomatic function or macro.


### Data Serialization
- [Cljson](https://github.com/tailrecursion/cljson) – Clojure/ClojureScript library for accelerated browser data deserialization.
- [Transit](https://github.com/cognitect/transit-cljs) – A data interchange format and set of libraries for conveying values between applications written in different programming languages.


### Data Visualization
- [C2](https://keminglabs.com/c2) – It lets you declaratively create HTML and SVG markup based on data.


### Database
- [Datascript](https://github.com/tonsky/datascript) – An immutable in-memory database and Datalog query engine in ClojureScript.
- [Jaki](https://github.com/pandeiro/jaki) – A simple ClojureScript CouchDB client.
- [Konserve](https://github.com/replikativ/konserve) – A clojuresque key-value/document store protocol with core.async.
- [specql](https://github.com/tatut/specql) – Library for simple PostgreSQL queries with namespaced keys.


### Development
- [Ambly](https://github.com/omcljs/ambly) – A ClojureScript REPL into iOS JavaScriptCore.
- [cljs-devtools](https://github.com/binaryage/cljs-devtools) – Better presentation of ClojureScript values in Chrome Devtools.
- [Devcards](https://github.com/bhauman/devcards) – Devcards aims to provide a visual REPL experience for ClojureScript.
- [Instaparse](https://github.com/lbradstreet/instaparse-cljs) – It aims to be the simplest way to build parsers in ClojureScript.
- [lein-cljsbuild](https://github.com/emezeske/lein-cljsbuild) – A Leiningen plugin to make ClojureScript development easy.
- [lein-figwheel](https://github.com/bhauman/lein-figwheel) – Leiningen plugin that pushes ClojureScript code changes to the client.
- [Lumo](https://github.com/anmonteiro/lumo) – Fast, cross-platform, standalone ClojureScript environment.
- [Planck](https://github.com/mfikes/planck) – A stand-alone ClojureScript REPL for macOS and Linux based on JavaScriptCore.
- [Ribol](http://docs.caudate.me/ribol/) – Conditional restarts for clojure/clojurescript.
- [shadow-cljs](https://github.com/thheller/shadow-cljs) – ClojureScript compilation made easy
- [Truss](https://github.com/ptaoussanis/truss) – An opinionated assertions API for Clojure/ClojureScript.


### Document Object Model
- [cljs-binding](https://github.com/fluentsoftware/cljs-binding) – It binds html elements to ClojureScript functions.
- [Crate](https://github.com/ibdknox/crate) – A ClojureScript implementation of Hiccup.
- [Dominator](https://github.com/dubiousdavid/dominator) – Virtual-Dom in ClojureScript.
- [Dommy](https://github.com/plumatic/dommy) – A no-nonsense ClojureScript templating and DOM manipulation library.
- [Enfocus](http://ckirkendall.github.io/enfocus-site/) – A DOM manipulation and templating library for ClojureScript inspired by Enlive.
- [Freactive](https://github.com/aaronc/freactive) – A high-performance, pure Clojurescript, declarative DOM library inspired by reagent, om, reflex and hiccup.
- [Hiccups](https://github.com/teropa/hiccups) – A ClojureScript port of the Hiccup.
- [Hickory](https://github.com/davidsantiago/hickory) – It parses HTML into Clojure data structures, so you can analyze, transform, and output back to HTML.
- [json-html](https://github.com/yogthos/json-html) – Provide JSON and get a DOM node with a human representation of that JSON.
- [Kioo](https://github.com/ckirkendall/kioo) – DOM manipulation and templating library for Facebook's React and Om in ClojureScript.
- [Respo](https://github.com/mvc-works/respo) – A responsive DOM library, inspired by React.
- [Sablono](https://github.com/r0man/sablono) – Lisp/Hiccup style templating for Facebook's React in ClojureScript.


### Documentation
- [codox](https://github.com/weavejester/codox) – A tool for generating API documentation from Clojure or ClojureScript source code.


### Graphics
- [geom](https://github.com/thi-ng/geom) – A 2D/3D geometry toolkit for Clojure/Clojurescript.
- [Quil](https://github.com/quil/quil) – A processing and graphics programming library.


### HTTP Handler
- [Castra](https://github.com/hoplon/castra) – An HTTP remote procedure call handler for Clojure.


### Internationalization
- [Tempura](https://github.com/ptaoussanis/tempura) – A Clojure(Script) i18n library, succeeding Tower
- [Tower](https://github.com/ptaoussanis/tower) – A Clojure(Script) i18n & L10n library.


### JavaScript Interoperability
- [CLJSJS](http://cljsjs.github.io/) – An easy way for Clojurescript developers to depend on Javascript libraries.
- [Jayq](https://github.com/ibdknox/jayq) – A ClojureScript wrapper for jQuery.
- [Purnam](https://github.com/zcaudate/purnam) – A ClojureScript library designed to provide better clojurescript/javascript interop, testing and documentation tools.
- [Pylon](https://github.com/bodil/pylon) – A Javascript class system in 100% Clojurescript.


### CSS tools
- [Garden](https://github.com/noprompt/garden) – A library for rendering CSS in Clojure and ClojureScript.
- [stylefy](https://github.com/jarzka/stylefy) – stylefy makes it possible to define UI component styles as Clojure data and attach them into components easily without writing CSS selectors


### Miscellaneous
- [Automat](https://github.com/ztellman/automat) – A Clojure(Script) library for defining and using finite-state automata, inspired by Ragel.
- [Bardo](https://github.com/pleasetrythisathome/bardo) – A Clojure(Script) library for functional interpolation and transitions.
- [core.async](https://github.com/clojure/core.async/) – A Clojure(Script) library designed to provide facilities for async programming and communication.
- [Entanglement](https://github.com/Frozenlock/entanglement) – It creates atoms from other atoms and links the data together.
- [inflections-clj](https://github.com/r0man/inflections-clj) – Rails-like inflection library for Clojure and ClojureScript.
- [Keybind](https://github.com/piranha/keybind) – Library for handling key bindings (shortcuts) in browser.
- [markdown-clj](https://github.com/yogthos/markdown-clj) – Markdown parser in Clojure/ClojureScript.
- [namespacefy](https://github.com/Jarzka/namespacefy) – A simple Clojure(Script) library which aims to make it easy to keep map keys namespaced, no matter where your data comes from.
- [om-tools](https://github.com/plumatic/om-tools) – It aims to provide higher-order abstractions and utilities frequently useful when building components with Om's API.
- [reforms](https://github.com/bilus/reforms) – Beautiful Bootstrap 3 forms for Om and Reagent.
- [reagent-forms](https://github.com/reagent-project/reagent-forms/) – Bootstrap form components for Reagent.
- [Sepal.clj](https://github.com/Cirru/sepal.clj) – A library to generate Clojure code from a vector of strings and vectors with macro system.

### [React.js](https://facebook.github.io/react/) Interface
- [Brutha](https://github.com/weavejester/brutha) – A simple and functional ClojureScript interface to React.
- [cljsx](https://github.com/peterhudec/cljsx) – [JSX](https://reactjs.org/docs/introducing-jsx.html) for Clojure and ClojureScript, also works with [Inferno](https://infernojs.org), [Nerv](https://nerv.aotu.io/), [Preact](https://preactjs.com/), [Snabbdome](https://github.com/snabbdom/snabbdom) and others.
- [hx](https://github.com/Lokeh/hx) – A simple, easy to use library for React development in ClojureScript. 
- [Om](https://github.com/omcljs/om) – A powerful interface to React, makes use of its object oriented structures.
- [Quiescent](https://github.com/levand/quiescent) – It favors functional style, fully stateless.
- [re-com](https://github.com/Day8/re-com) – A ClojureScript library of reusable components for Reagent.
- [Reagent](http://reagent-project.github.io/) – Minimalistic, feature complete.
- [Rum](https://github.com/tonsky/rum) – Decomplected, extensible, simple.


### Reactive Programming
- [Javelin](https://github.com/hoplon/javelin) – A Functional Reactive Programming library for ClojureScript.
- [Manifold-cljs](https://github.com/dm3/manifold-cljs) – A port of [Manifold](https://github.com/ztellman/manifold) to ClojureScript.
- [Reagi](https://github.com/weavejester/reagi) – An FRP library for Clojure and ClojureScript, built on top of core.async.
- [rx-cljs](https://github.com/leonardoborges/rx-cljs) – A ClojureScript wrapper for Reactive Extensions (Rx) for Javascript.
- [Yolk](https://github.com/Cicayda/yolk) – A thin ClojureScript wrapper around bacon.js.


### Routing
- [Bidi](https://github.com/juxt/bidi) – A Clojure(script) data driven routing library.
- [Router](https://github.com/darkleaf/router) – Bidirectional Ring router for Clojure/Script. REST oriented.
- [Secretary](https://github.com/gf3/secretary) – A client-side router for ClojureScript.
- [Silk](https://github.com/DomKM/silk) – An isomorphic routing library for Clojure & ClojureScript.


### State Management
- [component](https://github.com/stuartsierra/component) – Managed lifecycle of stateful objects in Clojure(Script).
- [hodgepodge](http://funcool.github.io/hodgepodge/) – A idiomatic ClojureScript interface to HTML5 Storage.
- [mount](https://github.com/tolitius/mount) – A beautifl idiomatic state management library.
- [plato](https://github.com/eneroth/plato) – Incrementally persists atom state to Local Storage in ClojureScript.
- [storage-atom](https://github.com/alandipert/storage-atom) – ClojureScript atoms backed by HTML5 web storage.
- [Tuck](https://github.com/tatut/tuck) – A micro framework for building Reagent apps that have a clean separation of view code and event processing code. 
- [Waltz](https://github.com/ibdknox/waltz) – A ClojureScript library that helps manage state in client-side applications using non-deterministic finite state machines.


### Testing
- [cljs.test](https://github.com/clojure/clojurescript/wiki/Testing) – Integrated test framework for ClojureScript (merged from [clojurescript.test](https://github.com/cemerick/clojurescript.test)) :star:167
- [Expectations](http://jayfields.com/expectations/) – A minimalist's unit testing framework.
- [Speclj](https://github.com/slagyr/speclj) – A TDD/BDD framework for Clojure and ClojureScript.
- [test.check](https://github.com/clojure/test.check) – A generative property-based testing tool inspired by QuickCheck.


### Validation
- [Bouncer](https://github.com/leonardoborges/bouncer) – A validation DSL for Clojure & Clojurescript applications.
- [form-validator-cljs](https://github.com/kwladyka/form-validator-cljs) – Validate forms with spec and fn.
- [Validateur](http://clojurevalidations.info/) – A Clojure validation library inspired by Ruby's ActiveModel.


### Web Framework & Template
- [atw-om](https://github.com/zaiste/atw-om) – A web application template with Clojure/Compojure, ClojureScript/Om & core.async.
- [Chestnut](https://github.com/plexus/chestnut) – An Application template for ClojureScript/Om with live reloading.
- [Clops](https://github.com/sveri/closp) – An opinionated, full stack and easy to use web framework.
- [descjop](https://github.com/karad/lein_template_descjop) – A template for Web based desktop application with Electron.
- [electron-template](https://github.com/ducky427/electron-template) – A template for creating web based desktop applications with Electron, ClojureScript and Reagent.
- [Fulcro](http://fulcrologic.github.io/fulcro) – A library for development of single-page full-stack web applications in clj/cljs.
- [Hoplon](http://hoplon.io) – Write everything in Clojure and ClojureScript, clientside and serverside.
- [Keechma](http://keechma.com) – Micro frontend framework for ClojureScript and Reagent.
- [Luminus](http://www.luminusweb.net/) – It aims to provide a robust, scalable, and easy to use platform.
- [Macchiato](https://github.com/macchiato-framework/macchiato-core) – It aims to provide an easy to use platform for Node.js.
- [Mies](https://github.com/swannodette/mies) – A minimal ClojureScript project template.
- [Mr-Clean](https://bitbucket.org/sonwh98/mr-clean) – A reagent compatible library without react.js dependency.
- [Precept](https://github.com/CoNarrative/precept) – A declarative programming framework.
- [re-frame](https://github.com/Day8/re-frame) – A Reagent Framework For Writing SPAs, in Clojurescript.
- [Tenzing](http://martinklepsch.github.io/tenzing/) – A ClojureScript template with no backend that uses Boot.
- [WebFUI](https://github.com/drcode/webfui) – Client-Side Web Framework for ClojureScript.


### WebSockets
- [Chord](https://github.com/jarohen/chord) – Designed to bridge the gap between the triad of CLJ/CLJS, web-sockets and core.async.
- [Sente](https://github.com/ptaoussanis/sente) – Clojure(Script) + core.async + WebSockets/Ajax.


* * *


## Contributing
All contributions are welcome. Please read [Contributing](CONTRIBUTING.md) before opening a pull request. tl;dr `-` is for bullets, `–` is for seperators between the link and the description and lists should be alphabetically ordered.


## License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

[Han Tuzun](http://hantuzun.com) has dedicated the work to the public domain by waiving all of his rights to the work worldwide under copyright law, including all related and neighboring rights, to the extent allowed by law.

You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.


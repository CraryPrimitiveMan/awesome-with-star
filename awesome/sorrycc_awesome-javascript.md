# Information comes from [sorrycc/awesome-javascript](https://github.com/sorrycc/awesome-javascript)
# Awesome JavaScript [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome browser-side [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) libraries, resources and shiny things.

* [Awesome JavaScript](#awesome-javascript)
  * [Package Managers](#package-managers)
  * [Loaders](#loaders)
  * [Bundlers](#bundlers)
  * [Testing Frameworks](#testing-frameworks)
  * [QA Tools](#qa-tools)
  * [MVC Frameworks and Libraries](#mvc-frameworks-and-libraries)
  * [Node-Powered CMS Frameworks](#node-powered-cms-frameworks)
  * [Templating Engines](#templating-engines)
  * [Articles/Posts](#articles-and-posts)
  * [Data Visualization](#data-visualization)
    * [Timeline](#timeline)
    * [Spreadsheet](#spreadsheet)
  * [Editors](#editors)
  * [Documentation](#documentation)
  * Utilities
    * [Files](#files)
    * [Functional Programming](#functional-programming)
    * [Reactive Programming](#reactive-programming)
    * [Data Structure](#data-structure)
    * [Date](#date)
    * [String](#string)
    * [Number](#number)
    * [Storage](#storage)
    * [Color](#color)
    * [I18n And L10n](#i18n-and-l10n)
    * [Control Flow](#control-flow)
    * [Routing](#routing)
    * [Security](#security)
    * [Log](#log)
    * [RegExp](#regexp)
    * [Media](#media)
    * [Voice Command](#voice-command)
    * [API](#api)
    * [Streaming](#streaming)
    * [Vision Detection](#vision-detection)
    * [Browser Detection](#browser-detection)
    * [Benchmark](#benchmark)
    * [Machine Learning](#machine-learning)
  * UI
    * [Code Highlighting](#code-highlighting)
    * [Loading Status](#loading-status)
    * [Validation](#validation)
    * [Keyboard Wrappers](#keyboard-wrappers)
    * [Tours And Guides](#tours-and-guides)
    * [Notifications](#notifications)
    * [Sliders](#sliders)
    * [Range Sliders](#range-sliders)
    * [Form Widgets](#form-widgets)
    * [Tips](#tips)
    * [Modals and Popups](#modals-and-popups)
    * [Scroll](#scroll)
    * [Menu](#menu)
    * [Table/Grid](#tablegrid)
    * [Frameworks](#frameworks-1)
    * [Boilerplates](#boilerplates)
  * [Gesture](#gesture)
  * [Maps](#maps)
  * [Typography](#typography)
  * [Animations](#animations)
  * [Image processing](#image-processing)
  * [ES6](#es6)
  * [SDK](#sdk)
  * [Misc](#misc)
  * [Podcasts](#podcasts)
* [Worth Reading](#worth-reading)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

----


## Package Managers
*Host the javascript libraries and provide tools for fetching and packaging them.*

* [npm](https://www.npmjs.com/) - npm is the package manager for javascript.
* [Bower](https://github.com/bower/bower) - A package manager for the web. :star:15294
* [component](https://github.com/componentjs/component) - Client package management for building better web applications. :star:4668
* [spm](https://github.com/spmjs/spm) - Brand new static package manager. :star:915
* [jam](https://github.com/caolan/jam) - A package manager using a browser-focused and RequireJS compatible repository. :star:1534
* [jspm](https://github.com/jspm/jspm-cli) - Frictionless browser package management. :star:3661
* [Ender](https://github.com/ender-js/Ender) - The no-library library. :star:1825
* [volo](https://github.com/volojs/volo) - Create front end projects from templates, add dependencies, and automate the resulting projects. :star:1397
* [Duo](https://github.com/duojs/duo) - Next-generation package manager that blends the best ideas from Component, Browserify and Go to make organizing and writing front-end code quick and painless. :star:3540
* [yarn](https://yarnpkg.com/) - Fast, reliable, and secure dependency management.


## Loaders
*Module or loading system for JavaScript.*

* [RequireJS](https://github.com/requirejs/requirejs) - A file and module loader for JavaScript. :star:11591
* [browserify](https://github.com/substack/node-browserify) - Browser-side require() the node.js way. :star:12002
* [SeaJS](https://github.com/seajs/seajs) - A Module Loader for the Web. :star:7401
* [HeadJS](https://github.com/headjs/headjs) - The only script in your HEAD. :star:4194
* [curl](https://github.com/cujojs/curl) - A small, fast, extensible module loader that handles AMD, CommonJS Modules/1.1, CSS, HTML/text, and legacy scripts. :star:1828
* [lazyload](https://github.com/rgrove/lazyload/) - Tiny, dependency-free async JavaScript and CSS loader.
* [script.js](https://github.com/ded/script.js) - Asyncronous JavaScript loader and dependency manager. :star:2545
* [systemjs](https://github.com/systemjs/systemjs) - AMD, CJS & ES6 spec-compliant module loader. :star:9075
* [LodJS](https://github.com/yanhaijing/lodjs) - Module loader based on AMD :star:289
* [ESL](https://github.com/ecomfe/esl) - Module loader browser first, support lazy define and AMD. :star:752
* [modulejs](https://github.com/lrsjng/modulejs) - Lightweight JavaScript module system. :star:105


## Bundlers

* [browserify](https://github.com/substack/node-browserify) - Browserify lets you require('modules') in the browser by bundling up all of your dependencies. :star:12002
* [webpack](https://github.com/webpack/webpack) - Packs CommonJs/AMD modules for the browser. :star:41501
* [Rollup](https://github.com/rollup/rollup) - Next-generation ES6 module bundler. :star:12878
* [Brunch](https://github.com/brunch/brunch) - Fast front-end web app build tool with simple declarative config. :star:6464
* [Parcel](https://github.com/parcel-bundler/parcel) - Blazing fast, zero configuration web application bundler. :star:22942


## Testing Frameworks

### Frameworks

* [mocha](https://github.com/mochajs/mocha) - Simple, flexible, fun javascript test framework for node.js & the browser. :star:15563
* [jasmine](https://github.com/jasmine/jasmine) - DOM-less simple JavaScript testing framework. :star:13591
* [qunit](https://github.com/jquery/qunit) - An easy-to-use JavaScript Unit Testing framework. :star:3764
* [jest](https://github.com/facebook/jest) - Painless Javascript Unit Testing. :star:18082
* [prova](https://github.com/azer/prova) - Node & Browser test runner based on Tape and Browserify :star:336
* [DalekJS](https://github.com/dalekjs/dalek) - Automated cross browser functional testing with JavaScript :star:721
* [Protractor](https://github.com/angular/protractor) - Protractor is an end-to-end test framework for AngularJS applications. :star:7587
* [tape](https://github.com/substack/tape) - Tap-producing test harness for node and browsers. :star:4624
* [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing for the modern web development stack. :star:4778
* [ava](https://github.com/avajs/ava) - 🚀 Futuristic JavaScript test runner :star:13971

### Assertion

* [chai](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework. :star:5415
* [Enzyme](http://airbnb.io/enzyme/index.html) - Enzyme is a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components' output.
* [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs, and mocks for JavaScript. :star:5978
* [expect.js](https://github.com/Automattic/expect.js) - Minimalistic BDD-style assertions for Node.JS and the browser. :star:1880

### Coverage

* [istanbul](https://github.com/gotwarlost/istanbul) - Yet another JS code coverage tool. :star:7255
* [blanket](https://github.com/alex-seville/blanket) - A simple code coverage library for javascript. Designed to be easy to install and use, for both browser and nodejs. :star:1390
* [JSCover](https://github.com/tntim96/JSCover) - JSCover is a tool that measures code coverage for JavaScript programs. :star:340

### Runner

* [phantomjs](https://github.com/ariya/phantomjs) - Scriptable Headless WebKit. :star:25563
* [slimerjs](https://github.com/laurentj/slimerjs) - A PhantomJS-like tool running Gecko. :star:2706
* [casperjs](https://github.com/casperjs/casperjs) - Navigation scripting & testing utility for PhantomJS and SlimerJS. :star:7199
* [zombie](https://github.com/assaf/zombie) - Insanely fast, full-stack, headless browser testing using node.js. :star:4896
* [totoro](https://github.com/totorojs/totoro) - A simple and stable cross-browser testing tool. :star:542
* [karma](https://github.com/karma-runner/karma) - Spectacular Test Runner for JavaScript. :star:9771
* [nightwatch](https://github.com/nightwatchjs/nightwatch) - UI automated testing framework based on node.js and selenium webdriver. :star:8237
* [intern](https://github.com/theintern/intern) - A next-generation code testing stack for JavaScript. :star:3992
* [yolpo](http://www.yolpo.com) - A statement-by-statement javascript interpreter in the browser.


## QA Tools

* [prettier](https://github.com/prettier/prettier) - Prettier is an opinionated code formatter. :star:25065
* [JSHint](https://github.com/jshint/jshint/) - JSHint is a tool that helps to detect errors and potential problems in your JavaScript code.
* [jscs](https://github.com/jscs-dev/node-jscs) - JavaScript Code Style checker. :star:5152
* [jsfmt](https://github.com/rdio/jsfmt) - For formatting, searching, and rewriting JavaScript. :star:1712
* [jsinspect](https://github.com/danielstjules/jsinspect) - Detect copy-pasted and structurally similar code. :star:1770
* [buddy.js](https://github.com/danielstjules/buddy.js) - Magic number detection for JavaScript. :star:609
* [ESLint](https://github.com/eslint/eslint) - A fully pluggable tool for identifying and reporting on patterns in JavaScript. :star:11548
* [JSLint](https://github.com/douglascrockford/JSLint) - High-standards, strict & opinionated code quality tool, aiming to keep only good parts of the language. :star:3155
* [JavaScript Standard Style](https://github.com/feross/standard) - Opinionated, no-configuration style guide, style checker, and formatter :star:18088


## MVC Frameworks and Libraries

* [angular.js](https://github.com/angular/angular.js) - HTML enhanced for web apps. :star:58583
* [aurelia](http://aurelia.io) - A Javascript client framework for mobile, desktop and web.
* [backbone](https://github.com/jashkenas/backbone) - Give your JS App some Backbone with Models, Views, Collections, and Events. :star:27187
* [ember.js](https://github.com/emberjs/ember.js) - A JavaScript framework for creating ambitious web applications. :star:19034
* [meteor](https://github.com/meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. :star:39894
* [ractive](https://github.com/ractivejs/ractive) - Next-generation DOM manipulation. :star:5516
* [vue](https://github.com/vuejs/vue) - Intuitive, fast & composable MVVM for building interactive interfaces. :star:97091
* [knockout](https://github.com/knockout/knockout) - Knockout makes it easier to create rich, responsive UIs with JavaScript. :star:8907
* [spine](https://github.com/spine/spine) - Lightweight MVC library for building JavaScript applications. :star:3372
* [espresso.js](https://github.com/techlayer/espresso.js) - A minimal javascript library for crafting user interfaces. :star:523
* [canjs](https://github.com/canjs/canjs) - Can do JS, better, faster, easier. :star:1624
* [react](https://facebook.github.io/react/) - A library for building user interfaces. It's declarative, efficient, and extremely flexible. Works with a Virtual DOM.
* [hyperapp](https://github.com/hyperapp/hyperapp) - 1kb JavaScript library for building frontend applications. :star:13938
* [preact](https://github.com/developit/preact) - Fast 3kb React alternative with the same ES6 API. Components & Virtual DOM. :star:19025
* [nativescript](https://github.com/NativeScript/NativeScript) - Build truly native cross-platform iOS and Android apps with JavaScript :star:13778
* [react-native](https://github.com/facebook/react-native) - A framework for building native apps with React. :star:64788
* [riot](https://github.com/riot/riot) - React-like library, but with very small size. :star:13036
* [thorax](https://github.com/walmartlabs/thorax) - Strengthening your Backbone. :star:1360
* [chaplin](https://github.com/chaplinjs/chaplin) - An architecture for JavaScript applications using the Backbone.js library. :star:2953
* [marionette](https://github.com/marionettejs/backbone.marionette) - A composite application library for Backbone.js that aims to simplify the construction of large scale JavaScript applications. :star:7178
* [ripple](https://github.com/ripplejs/ripple) - A tiny foundation for building reactive views. :star:1294
* [rivets](https://github.com/mikeric/rivets) - Lightweight and powerful data binding + templating solution. :star:3102
* [derby](https://github.com/derbyjs/derby) - MVC framework making it easy to write realtime, collaborative applications that run in both Node.js and browsers. :star:4321
    * [derby-awesome](https://github.com/russll/awesome-derby) - A collection of awesome derby components :star:11
* [way.js](https://github.com/gwendall/way.js) - Simple, lightweight, persistent two-way databinding. :star:2850
* [mithril.js](https://github.com/lhorie/mithril.js) - Mithril is a client-side MVC framework (Light-weight, Robust, Fast). :star:8634
* [jsblocks](https://github.com/astoilkov/jsblocks) - jsblocks is better MV-ish framework. :star:2833
* [LiquidLava](http://www.lava-framework.com/) - Transparent MVC framework for building user interfaces.
* [feathers](https://github.com/feathersjs/feathers) - A minimalist real-time JavaScript framework for tomorrow's apps. :star:9169
* [Keo](https://github.com/Wildhoney/Keo) - Functional stateless React components with Shadow DOM support. :star:222
* [atvjs](https://github.com/emadalam/atvjs) - Blazing fast Apple TV application development using pure JavaScript. :star:192

## Node-Powered CMS Frameworks

* [KeystoneJS](https://github.com/keystonejs/keystone) - powerful CMS and web app framework :star:12755
* [Reaction Commerce](https://github.com/reactioncommerce/reaction) - reactive CMS, real-time architecture and design :star:7234
* [Ghost](https://github.com/tryghost/Ghost) - simple, powerful publishing platform :star:25888
* [Apostrophe](https://github.com/punkave/apostrophe) - CMS with content editing and essential services :star:2164
* [We.js](https://github.com/wejs/we/) - framework for real time apps, sites or blogs
* [Hatch.js](https://github.com/inventures/hatchjs) - CMS platform with social features. :star:67
* [TaracotJS](https://github.com/xtremespb/taracotjs-generator/) - fast and minimalist CMS based on Node.js.
* [Nodizecms](https://github.com/nodize/nodizecms) - CMS for CoffeeScript lovers :star:181
* [Cody](https://github.com/jcoppieters/cody) - CMS with WSYWYG editor :star:634
* [PencilBlue](https://github.com/pencilblue/pencilblue/) - CMS and blogging platform

## Templating Engines
*Templating engines allow you to perform string interpolation.*

* [mustache.js](https://github.com/janl/mustache.js) - Minimal templating with {{mustaches}} in JavaScript. :star:12099
* [handlebars.js](https://github.com/wycats/handlebars.js/) - An extension to the Mustache templating language.
* [hogan.js](https://github.com/twitter/hogan.js) - A compiler for the Mustache templating language. :star:4911
* [doT](https://github.com/olado/doT) - The fastest + concise javascript template engine for nodejs and browsers. :star:3902
* [dustjs](https://github.com/linkedin/dustjs/) - Asynchronous templates for the browser and node.js.
* [eco](https://github.com/sstephenson/eco/) - Embedded CoffeeScript templates.
* [JavaScript-Templates](https://github.com/blueimp/JavaScript-Templates) - < 1KB lightweight, fast & powerful JavaScript templating engine with zero dependencies. :star:1380
* [t.js](https://github.com/jasonmoo/t.js) - A tiny javascript templating framework in ~400 bytes gzipped. :star:778
* [Pug](https://github.com/pugjs/pug) - Robust, elegant, feature rich template engine for nodejs. (formerly known as Jade)
* [EJS](https://github.com/mde/ejs) - Effective JavaScript templating. :star:2491
* [xtemplate](https://github.com/xtemplate/xtemplate) - eXtensible Template Engine lib for node and the browser :star:436
* [marko](https://github.com/marko-js/marko) - A fast, lightweight, HTML-based templating engine for Node.js and the browser with async, streaming, custom tags and CommonJS modules as compiled output. :star:6311
* [swig](http://paularmstrong.github.io/swig/) - A simple, powerful, and extendable Node.js and browser-based JavaScript template engine.

## Articles and Posts

* [The JavaScript that you should know](https://medium.com/@pedropolisenso/o-javasscript-que-você-deveria-conhecer-b70e94d1d706) - Article about concepts of JavaScript Functional.
* [How JavaScript works](https://blog.sessionstack.com/tagged/tutorial) - A series of articles about the building blocks of JavaScript.

## Data Visualization
*Data visualization tools for the web.*

* [d3](https://github.com/d3/d3) - A JavaScript visualization library for HTML and SVG. :star:76360
  * [metrics-graphics](https://github.com/mozilla/metrics-graphics) - A library optimized for concise, principled data graphics and layouts. :star:6883
* [pykcharts.js](https://github.com/pykih/PykCharts.js) - Well designed d3.js charting without the complexity of d3.js.
* [three.js](https://github.com/mrdoob/three.js) - JavaScript 3D library. :star:42327
* [Chart.js](https://github.com/chartjs/Chart.js) - Simple HTML5 Charts using the <canvas> tag. :star:37345
* [paper.js](https://github.com/paperjs/paper.js) - The Swiss Army Knife of Vector Graphics Scripting – Scriptographer ported to JavaScript and the browser, using HTML5 Canvas. :star:9307
* [fabric.js](https://github.com/kangax/fabric.js) - Javascript Canvas Library, SVG-to-Canvas (& canvas-to-SVG) Parser. :star:10313
* [peity](https://github.com/benpickles/peity) - Progressive <svg> bar, line and pie charts. :star:4039
* [raphael](https://github.com/DmitryBaranovskiy/raphael) - JavaScript Vector Library. :star:9738
* [echarts](https://github.com/ecomfe/echarts) - Enterprise Charts. :star:28160
* [vis](https://github.com/almende/vis) - Dynamic, browser-based visualization library. :star:6721
* [two.js](https://github.com/jonobr1/two.js) - A renderer agnostic two-dimensional drawing api for the web. :star:5574
* [g.raphael](https://github.com/DmitryBaranovskiy/g.raphael) - Charts for Raphaël. :star:1509
* [sigma.js](https://github.com/jacomyal/sigma.js) - A JavaScript library dedicated to graph drawing. :star:7973
* [arbor](https://github.com/samizdatco/arbor) - A graph visualization library using web workers and jQuery. :star:2475
* [cubism](https://github.com/square/cubism) - A D3 plugin for visualizing time series. :star:4669
* [dc.js](https://github.com/dc-js/dc.js) - Multi-Dimensional charting built to work natively with crossfilter rendered with d3.js :star:6255
* [vega](https://github.com/trifacta/vega) - A visualization grammar. :star:22
* [processing.js](http://processingjs.org/) - Processing.js makes your data visualizations work using web standards and without any plug-ins
* [envisionjs](https://github.com/HumbleSoftware/envisionjs) - Dynamic HTML5 visualization. :star:1581
* [rickshaw](https://github.com/shutterstock/rickshaw) - JavaScript toolkit for creating interactive real-time graphs. :star:6253
* [flot](https://github.com/flot/flot) - Attractive JavaScript charts for jQuery. :star:5571
* [morris.js](https://github.com/morrisjs/morris.js) - Pretty time-series line graphs. :star:6771
* [nvd3](https://github.com/novus/nvd3) - Build re-usable charts and chart components for d3.js :star:6529
* [svg.js](https://github.com/wout/svg.js) - A lightweight library for manipulating and animating SVG. :star:5780
* [heatmap.js](https://github.com/pa7/heatmap.js) - JavaScript Library for HTML5 canvas based heatmaps. :star:4354
* [jquery.sparkline](https://github.com/gwatts/jquery.sparkline) - A plugin for the jQuery javascript library to generate small sparkline charts directly in the browser. :star:1135
* [xCharts](https://github.com/tenxer/xCharts) - A D3-based library for building custom charts and graphs.
* [trianglify](https://github.com/qrohlf/trianglify) - Low poly style background generator with d3.js :star:8388
* [d3-cloud](https://github.com/jasondavies/d3-cloud) - Create word clouds in JavaScript. :star:2549
* [d4](https://github.com/heavysixer/d4) - A friendly reusable charts DSL for D3. :star:412
* [dimple.js](http://dimplejs.org) -  Easy charts for business analytics powered by d3
* [chartist-js](https://github.com/gionkunz/chartist-js) - Simple responsive charts. :star:10773
* [epoch](https://github.com/epochjs/epoch) - A general purpose real-time charting library. :star:4936
* [c3](https://github.com/c3js/c3) - D3-based reusable chart library. :star:7759
* [BabylonJS](https://github.com/BabylonJS/Babylon.js) - A framework for building 3D games with HTML 5 and WebGL. :star:6902
* [recharts](https://github.com/recharts/recharts) - Redefined chart library built with React and D3 :star:9080
* [GraphicsJS](https://www.graphicsjs.org) - A lightweight JavaScript graphics library with the intuitive API, based on SVG/VML technology.

There're also some great commercial libraries, like [amchart](https://www.amcharts.com/), [anychart](http://www.anychart.com), [plotly](https://plot.ly/), and [highchart](http://www.highcharts.com/).


## Timeline

* [TimelineJS v3](https://github.com/NUKnightLab/TimelineJS3) - A Storytelling Timeline built in JavaScript. :star:1452
* [timesheet.js](https://github.com/sbstjn/timesheet.js) - JavaScript library for simple HTML5 & CSS3 time sheets. :star:6479

## Spreadsheet

* [HANDSONTABLE](https://github.com/handsontable/handsontable) - Handsontable is a JavaScript/HTML5 Spreadsheet Library for Developers :star:10024

## Editors

* [ace](https://github.com/ajaxorg/ace) - Ace (Ajax.org Cloud9 Editor). :star:17585
* [CodeMirror](https://github.com/codemirror/CodeMirror) - In-browser code editor. :star:14784
* [esprima](https://github.com/ariya/esprima) - ECMAScript parsing infrastructure for multipurpose analysis. :star:298
* [quill](https://github.com/quilljs/quill) - A cross browser rich text editor with an API. :star:18374
* [medium-editor](https://github.com/yabwe/medium-editor) - Medium.com WYSIWYG editor clone. :star:12337
* [pen](https://github.com/sofish/pen) - enjoy live editing (+markdown). :star:4461
* [jquery-notebook](https://github.com/raphaelcruzeiro/jquery-notebook) - A simple, clean and elegant text editor. Inspired by the awesomeness of Medium. :star:1700
* [bootstrap-wysiwyg](https://github.com/mindmup/bootstrap-wysiwyg) - Tiny bootstrap-compatible WYSIWYG rich text editor. :star:5551
* [ckeditor-releases](https://github.com/ckeditor/ckeditor-releases) - The best web text editor for everyone. :star:416
* [editor](https://github.com/lepture/editor) - A markdown editor. still on development. :star:2546
* [EpicEditor](https://github.com/OscarGodson/EpicEditor) - An embeddable JavaScript Markdown editor with split fullscreen editing, live previewing, automatic draft saving, offline support, and more. :star:4362
* [jsoneditor](https://github.com/josdejong/jsoneditor) - A web-based tool to view, edit and format JSON. :star:4509
* [vim.js](https://github.com/coolwanglu/vim.js) - JavaScript port of Vim with a persistent ~/.vimrc :star:4261
* [Squire](https://github.com/neilj/Squire) - HTML5 rich text editor. :star:3815
* [TinyMCE](https://github.com/tinymce/tinymce) - The JavaScript Rich Text editor. :star:5360
* [trix](https://github.com/basecamp/trix) - A rich text editor for everyday writing. By Basecamp. :star:8699
* [Trumbowyg](https://github.com/Alex-D/Trumbowyg) - A lightweight and amazing WYSIWYG JavaScript editor. :star:2312
* [Draft.js](https://github.com/facebook/draft-js) - A React framework for building text editors. :star:13097
* [bootstrap-wysihtml5](https://github.com/jhollingworth/bootstrap-wysihtml5) - Simple, beautiful wysiwyg editor :star:4246
* [wysihtml5](https://github.com/xing/wysihtml5) - Open source rich text editor based on HTML5 and the progressive-enhancement approach. Uses a sophisticated security concept and aims to generate fully valid HTML5 markup by preventing unmaintainable tag soups and inline styles. :star:6645
* [raptor-editor](https://github.com/PANmedia/raptor-editor) - Raptor, an HTML5 WYSIWYG content editor! :star:518
* [popline](https://github.com/kenshin54/popline) - Popline is an HTML5 Rich-Text-Editor Toolbar :star:1040


## Documentation

* [DevDocs](http://devdocs.io/) is an all-in-one API documentation reader with a fast, organized, and consistent interface.
* [dexy](http://www.dexy.it/) is a free-form literate documentation tool for writing any kind of technical document incorporating code.
* [docco](http://jashkenas.github.io/docco/) is a quick-and-dirty, hundred-line-long, literate-programming-style documentation generator.
* [styledocco](http://jacobrask.github.io/styledocco/) generates documentation and style guide documents from your stylesheets.
* [Ronn](https://github.com/rtomayko/ronn) builds manuals. It converts simple, human readable textfiles to roff for terminal display, and also to HTML for the web.
* [dox](https://github.com/tj/dox) is a JavaScript documentation generator written with node. Dox no longer generates an opinionated structure or style for your docs, it simply gives you a JSON representation, allowing you to use markdown and JSDoc-style tags.
* [jsdox](https://github.com/sutoiku/jsdox) is a JSDoc3 to Markdown documentation generator.
* [ESDoc](https://github.com/esdoc/esdoc) is a good documentation generator for JavaScript.
* [YUIDoc](http://yui.github.io/yuidoc/) is a Node.js application that generates API documentation from comments in source, using a syntax similar to tools like Javadoc and Doxygen.
* [coddoc](http://doug-martin.github.io/coddoc/) is a jsdoc parsing library. Coddoc is different in that it is easily extensible by allowing users to add tag and code parsers through the use of coddoc.addTagHandler and coddoc.addCodeHandler. coddoc also parses source code to be used in APIs.
* [sphinx](http://www.sphinx-doc.org/) a tool that makes it easy to create intelligent and beautiful documentation
* [Using JSDoc](http://usejsdoc.org/)
* [Beautiful docs](http://beautifuldocs.com/) is a documentation viewer based on markdown files.
* [documentation.js](http://documentation.js.org) - API documentation generator with support for ES2015+ and flow annotation.
* [jsduck](https://github.com/senchalabs/jsduck) - API documentation generator made for Sencha JavaScript frameworks, but can be used for other frameworks too. :star:1470


## Files
*Libraries for working with files.*

* [Papa Parse](https://github.com/mholt/PapaParse) - A powerful CSV library that supports parsing CSV files/strings and also exporting to CSV. :star:5482
* [jBinary](https://github.com/jDataView/jBinary) - High-level I/O (loading, parsing, manipulating, serializing, saving) for binary files with declarative syntax for describing file types and data structures. :star:430
* [diff2html](https://github.com/rtfpessoa/diff2html) - Git diff output parser and pretty HTML generator. :star:633
* [jsPDF](https://github.com/MrRio/jsPDF) - JavaScript PDF generation. :star:11081


## Functional Programming
*Functional programming libraries to extend JavaScript’s capabilities.*

* [underscore](https://github.com/jashkenas/underscore) - JavaScript's utility _ belt. :star:23075
* [lodash](https://github.com/lodash/lodash) - A utility library delivering consistency, customization, performance, & extras. :star:32327
* [Sugar](https://github.com/andrewplummer/Sugar) - A Javascript library for working with native objects. :star:3621
* [lazy.js](https://github.com/dtao/lazy.js) - Like Underscore, but lazier. :star:4849
* [ramda](https://github.com/CrossEye/ramda) - A practical functional library for Javascript programmers. :star:39
* [mout](https://github.com/mout/mout) - Modular JavaScript Utilities. :star:869
* [mesh](https://github.com/crcn/mesh.js) - Streamable data synchronization utility. :star:1025
* [preludejs](https://github.com/alanrsoares/prelude-js) - Hardcore Functional Programming for JavaScript. :star:62


## Reactive Programming
*Reactive programming libraries to extend JavaScript’s capabilities.*

* [RxJs](https://github.com/Reactive-Extensions/RxJS) - The Reactive Extensions for JavaScript. :star:19114
* [Bacon](https://github.com/baconjs/bacon.js) - FRP (functional reactive programming) library for Javascript. :star:5913
* [Kefir](https://github.com/pozadi/kefir) - FRP library for JavaScript inspired by Bacon.js and RxJS with focus on high performance and low memory consumption. :star:6
* [Highland](http://highlandjs.org/) - Re-thinking the JavaScript utility belt, Highland manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
* [Most.js](https://github.com/cujojs/most) - high performance FRP library. :star:2757
* [MobX](https://github.com/mobxjs/mobx) - TFRP library for simple, scalable state management. :star:15336
* [Cycle.js](https://cycle.js.org) - A functional and reactive JavaScript library for cleaner code.

## Data Structure
*Data structure libraries to build a more sophisticated application.*

* [immutable-js](https://github.com/facebook/immutable-js) - Immutable Data Collections including Sequence, Range, Repeat, Map, OrderedMap, Set and a sparse Vector. :star:23936
* [mori](https://github.com/swannodette/mori) - A library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript. :star:2953
* [buckets](https://github.com/mauriciosantos/Buckets-JS) - A complete, fully tested and documented data structure library written in JavaScript. :star:856
* [hashmap](https://github.com/flesler/hashmap) - Simple hashmap implementation that supports any kind of keys. :star:301


## Date
*Date Libraries.*

* [moment](https://github.com/moment/moment) - Parse, validate, manipulate, and display dates in javascript. :star:37334
* [moment-timezone](https://github.com/moment/moment-timezone) - Timezone support for moment.js. :star:2680
* [jquery-timeago](https://github.com/rmm5t/jquery-timeago) - A jQuery plugin that makes it easy to support automatically updating fuzzy timestamps (e.g. "4 minutes ago"). :star:3750
* [timezone-js](https://github.com/mde/timezone-js) - Timezone-enabled JavaScript Date object. Uses Olson zoneinfo files for timezone data. :star:810
* [date](https://github.com/MatthewMueller/date) - Date() for humans. :star:1318
* [ms.js](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility. :star:1478
* [countdown.js](https://github.com/gumroad/countdown.js) - Super simple countdowns. :star:385
* [timeago.js](https://github.com/hustcc/timeago.js) - Simple library (less then 2kb) used to format date with `*** time ago` statement. :star:3195
* [fecha](https://github.com/taylorhakes/fecha) - Lightweight date formatting and parsing (~2KB). Meant to replace parsing and formatting functionality of moment.js. :star:1466
* [date-fns](https://github.com/date-fns/date-fns) - Modern JavaScript date utility library. :star:10566

## String
*String Libraries.*

* [voca](https://github.com/panzerdp/voca) - The ultimate JavaScript string library :star:2034
* [selecting](https://github.com/EvandroLG/selecting) - A library that allows you to access the text selected by the user :star:65
* [underscore.string](https://github.com/epeli/underscore.string) - String manipulation extensions for Underscore.js javascript library. :star:3280
* [string.js](https://github.com/jprichardson/string.js) - Extra JavaScript string methods. :star:1623
* [he](https://github.com/mathiasbynens/he) - A robust HTML entity encoder/decoder written in JavaScript. :star:1523
* [multiline](https://github.com/sindresorhus/multiline) - Multiline strings in JavaScript. :star:1438
* [query-string](https://github.com/sindresorhus/query-string) - Parse and stringify URL query strings. :star:2377
* [URI.js](https://github.com/medialize/URI.js/) - Javascript URL mutation library.
* [jsurl](https://github.com/Mikhus/domurl) - Lightweight URL manipulation with JavaScript. :star:417
* [sprintf.js](https://github.com/alexei/sprintf.js) - A sprintf implementation. :star:1640
* [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for urls and other strings. Turn strings into data or data into strings :star:371

## Number

* [Numeral-js](https://github.com/adamwdraper/Numeral-js) - A javascript library for formatting and manipulating numbers. :star:6316
* [chance.js](https://github.com/chancejs/chancejs) - Random generator helper in Javascript. Can generate numbers, strings etc. :star:3274
* [odometer](https://github.com/HubSpot/odometer) - Smoothly transitions numbers with ease. :star:6134
* [accounting.js](https://github.com/josscrowcroft/accounting.js) - A lightweight JavaScript library for number, money and currency formatting - fully localisable, zero dependencies. :star:28
* [money.js](https://github.com/josscrowcroft/money.js) - A tiny (1kb) javascript currency conversion library, for web & nodeJS. :star:8
* [Fraction.js](https://github.com/infusion/Fraction.js) - A rational number library for JavaScript :star:145
* [Complex.js](https://github.com/infusion/Complex.js) - A complex number library for JavaScript :star:113
* [Polynomial.js](https://github.com/infusion/Polynomial.js) - A polynomials library for JavaScript :star:53


## Storage

* [store.js](https://github.com/marcuswestin/store.js) - LocalStorage wrapper for all browsers without using cookies or flash. Uses localStorage, globalStorage, and userData behavior under the hood. :star:11366
* [localForage](https://github.com/mozilla/localForage) - Offline storage, improved. Wraps IndexedDB, WebSQL, or localStorage using a simple but powerful API. :star:12330
* [jStorage](https://github.com/andris9/jStorage) - jStorage is a simple key/value database to store data on browser side. :star:1508
* [cross-storage](https://github.com/zendesk/cross-storage) - Cross domain local storage, with permissions. :star:1364
* [basket.js](https://github.com/addyosmani/basket.js) - A script and resource loader for caching & loading scripts with localStorage. :star:3157
* [bag.js](https://github.com/nodeca/bag.js) - A caching script and resource loader, similar to basket.js, but with additional k/v interface and localStorage / websql / indexedDB support. :star:73
* [basil.js](https://github.com/Wisembly/basil.js) - The missing Javascript smart persistent layer. :star:1905
* [jquery-cookie](https://github.com/carhartl/jquery-cookie) - A simple, lightweight jQuery plugin for reading, writing and deleting cookies. :star:8495
* [js-cookie](https://github.com/js-cookie/js-cookie) - A simple, lightweight JavaScript API for handling browser cookies :star:9679
* [Cookies](https://github.com/ScottHamper/Cookies) - JavaScript Client-Side Cookie Manipulation Library. :star:1746
* [DB.js](https://github.com/aaronpowell/db.js/) - Promise based IndexDB Wrapper library
* [lawnchair.js](https://github.com/brianleroux/lawnchair/) - Simple client-side JSON storage.
* [sql.js](https://github.com/kripken/sql.js) - SQLite compiled to JavaScript through Emscripten. :star:4323


## Color

* [randomColor](https://github.com/davidmerfield/randomColor) - A color generator for JavaScript. :star:4594
* [chroma.js](https://github.com/gka/chroma.js) - JavaScript library for all kinds of color manipulations. :star:5216
* [color](https://github.com/Qix-/color) - JavaScript color conversion and manipulation library. :star:2024
* [colors](https://github.com/mrmrs/colors) - Smarter defaults for colors on the web. :star:8198
* [PleaseJS](https://github.com/Fooidge/PleaseJS) - JavaScript Library for creating random pleasing colors and color schemes. :star:2165
* [TinyColor](https://github.com/bgrins/TinyColor) - Fast, small color manipulation and conversion for JavaScript. :star:2218
* [Vibrant.js](https://github.com/jariz/vibrant.js/) - Extract prominent colors from an image.

## I18n And L10n
*Localization (l10n) and internationalization (i18n) JavaScript libraries.*

* [i18next](https://github.com/i18next/i18next) - internationalisation (i18n) with javascript the easy way. :star:3281
* [polyglot](https://github.com/airbnb/polyglot.js) - tiny i18n helper library. :star:2689
* [babelfish](https://github.com/nodeca/babelfish/) - i18n with human friendly API and built in plurals support.

## Control Flow

* [async](https://github.com/caolan/async) - Async utilities for node and the browser. :star:24100
* [q](https://github.com/kriskowal/q) - A tool for making and composing asynchronous promises in JavaScript. :star:14211
* [step](https://github.com/creationix/step/) - An async control-flow library that makes stepping through logic easy.
* [contra](https://github.com/bevacqua/contra/) - Asynchronous flow control with a functional taste to it.
* [Bluebird](https://github.com/petkaantonov/bluebird/) - fully featured promise library with focus on innovative features and performance.
* [when](https://github.com/cujojs/when) - A solid, fast Promises/A+ and when() implementation, plus other async goodies. :star:3358
* [ObjectEventTarget](https://github.com/gartz/ObjectEventTarget) - Provide a prototype that add support to event listeners (with same behavior of EventTarget from DOMElements available on browsers). :star:9


## Routing

* [director](https://github.com/flatiron/director) - A tiny and isomorphic URL router for JavaScript. :star:5233
* [page.js](https://github.com/visionmedia/page.js) - Micro client-side router inspired by the Express router (~1200 bytes). :star:5846
* [pathjs](https://github.com/mtrpcic/pathjs) - Simple, lightweight routing for web browsers. :star:1070
* [crossroads](https://github.com/millermedeiros/crossroads.js) - JavaScript Routes. :star:1408
* [davis.js](https://github.com/olivernn/davis.js) - RESTful degradable JavaScript routing using pushState. :star:537


## Security

* [DOMPurify](https://github.com/cure53/DOMPurify) - A DOM-only, super-fast, uber-tolerant XSS sanitizer for HTML, MathML and SVG. :star:2394
* [js-xss](https://github.com/leizongmin/js-xss) - Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist. :star:2112
* [xss-filters](https://github.com/yahoo/xss-filters) - Secure XSS Filters by Yahoo :star:789


## Log

* [log](https://github.com/adamschwartz/log) - Console.log with style. :star:2602
* [Conzole](https://github.com/Oaxoa/Conzole) - A debug panel built in javascript that wraps javascript native console object methods and functionality in a panel displayed inside the page. :star:190
* [console.log-wrapper](https://github.com/patik/console.log-wrapper) - Log to the console in any browser with clarity. :star:399
* [loglevel](https://github.com/pimterry/loglevel) - Minimal lightweight logging for JavaScript, adding reliable log level methods to wrap any available console.log methods. :star:1097
* [minilog](http://mixu.net/minilog/) – Lightweight client & server-side logging with Stream-API backends
* [storyboard](http://guigrpa.github.io/storyboard/) - Universal logging library + Chrome extension; it lets you see all client and server tasks triggered by a user action in a single place.

## RegExp
* [RegEx101](https://regex101.com/#javascript) - Online regex tester and debugger for JavaScript. Also supports Python, PHP and PCRE.
* [RegExr](http://regexr.com) - HTML/JS based tool for creating, testing, and learning about Regular Expressions.
* [RegExpBuilder](https://github.com/thebinarysearchtree/regexpbuilderjs) - Create regular expressions using chained methods. :star:1080


## Voice Command

* [annyang](https://github.com/TalAter/annyang) - A JavaScript library for adding voice commands to your site, using speech recognition. :star:4775
* [voix.js](https://github.com/pazguille/voix) - A JavaScript library to add voice commands to your sites, apps or games. :star:518


## API

* [bottleneck](https://github.com/SGrondin/bottleneck) - A powerful rate limiter that makes throttling easy. :star:425
* [oauth-signature-js](https://github.com/bettiolo/oauth-signature-js) - JavaScript OAuth 1.0a signature generator for node and the browser. :star:201
* [amygdala](https://github.com/lincolnloop/amygdala) - RESTful HTTP client for JavaScript powered web applications. :star:400
* [jquery.rest](https://github.com/jpillora/jquery.rest) - A jQuery plugin for easy consumption of RESTful APIs. :star:597
* [Rails Ranger](https://github.com/victor-am/rails-ranger) - An opinionated REST client for Ruby on Rails APIs. :star:15

## Streaming

* [Tailor](https://github.com/zalando/tailor) - Streaming layout service for front-end microservices, inspired by Facebook's BigPipe. :star:614


## Vision Detection

* [tracking.js](https://github.com/eduardolundgren/tracking.js) - A modern approach for Computer Vision on the web. :star:6613
* [ocrad.js](https://github.com/antimatter15/ocrad.js) - OCR in Javascript via Emscripten. :star:2839


## Machine Learning

* [ConvNetJS](https://github.com/karpathy/convnetjs) - Deep Learning in Javascript. Train Convolutional Neural Networks (or ordinary ones) in your browser. :star:9126
* [DN2A](https://github.com/dn2a/dn2a-javascript) - Digital Neural Networks Architecture. :star:455
* [Brain.js](https://github.com/harthur/brain) - Neural networks in JavaScript. :star:8030
* [Mind.js](https://github.com/stevenmiller888/mind) - A flexible neural network library. :star:1304
* [Synaptic.js](https://github.com/cazala/synaptic) - Architecture-free neural network library for node.js and the browser. :star:6136
* [deeplearn.js](https://deeplearnjs.org/) - A hardware-accelerated machine intelligence library for the web.


## Browser Detection

* [bowser](https://github.com/ded/bowser) - a browser detector :star:2847

## Benchmark

* [benchmark.js](https://github.com/bestiejs/benchmark.js) - A benchmarking library. As used on jsPerf.com. :star:3539
* [matcha](https://github.com/logicalparadox/matcha) - A caffeine driven, simplistic approach to benchmarking. :star:480

## Code highlighting

* [Highlight.js](https://github.com/isagalaev/highlight.js) - Javascript syntax highlighter. :star:12337
* [PrismJS](https://github.com/PrismJS/prism) - Lightweight, robust, elegant syntax highlighting. :star:5390


## Loading Status
*Libraries for indicate load status.*

* [Mprogress.js](https://github.com/lightningtgc/MProgress.js) - Create Google Material Design progress linear bars. :star:1531
* [NProgress](http://ricostacruz.com/nprogress/) - Slim progress bars for Ajax'y applications.
* [Spin.js](https://github.com/fgnass/spin.js) - A spinning activity indicator. :star:9023
* [progress.js](https://github.com/usablica/progress.js) - Create and manage progress bar for every objects on the page. :star:2304
* [progressbar.js](https://github.com/kimmobrunfeldt/progressbar.js) - Beautiful and responsive progress bars with animated SVG paths. :star:6408
* [pace](https://github.com/HubSpot/pace) - Automatically add a progress bar to your site. :star:13694
* [topbar](https://github.com/buunguyen/topbar) - Tiny & beautiful site-wide progress indicator. :star:171
* [nanobar](https://github.com/jacoborus/nanobar) - Very lightweight progress bars. No jQuery. :star:2607
* [PageLoadingEffects](https://github.com/codrops/PageLoadingEffects) - Modern ways of revealing new content using SVG animations. :star:577
* [SpinKit](https://github.com/tobiasahlin/SpinKit) - A collection of loading indicators animated with CSS. :star:15009
* [Ladda](https://github.com/hakimel/Ladda) - Buttons with built-in loading indicators. :star:7280
* [css-loaders](https://github.com/lukehaas/css-loaders) - A collection of loading spinners animated with CSS :star:5515

Besides libraries, there're [Collection on Codepen](http://codepen.io/collection/HtAne/), and generators like [Ajaxload](http://www.ajaxload.info/), [Preloaders](http://preloaders.net/) and [CSSLoad](http://cssload.net/).


## Validation

* [Parsley.js](https://github.com/guillaumepotier/Parsley.js) - Validate your forms, frontend, without writing a single line of javascript. :star:8489
* [jquery-validation](https://github.com/jzaefferer/jquery-validation) - jQuery Validation Plugin. :star:8781
* [validator.js](https://github.com/chriso/validator.js) - String validation and sanitization. :star:10598
* [validate.js](https://github.com/rickharrison/validate.js) - Lightweight JavaScript form validation library inspired by CodeIgniter. :star:2334
* [validatr](https://github.com/jaymorrow/validatr/) - Cross Browser HTML5 Form Validation.
* [FormValidation](http://formvalidation.io/) - The best jQuery plugin to validate form fields. Formerly BootstrapValidator.
* [is.js](https://github.com/arasatasaygin/is.js) -  Check types, regexps, presence, time and more. :star:8299
* [FieldVal](https://github.com/FieldVal/fieldval-js) - multipurpose validation library. Supports both sync and async validation. :star:135


## Keyboard Wrappers

* [mousetrap](https://github.com/ccampbell/mousetrap) - Simple library for handling keyboard shortcuts in Javascript. :star:8849
* [keymaster](https://github.com/madrobby/keymaster) - A simple micro-library for defining and dispatching keyboard shortcuts. :star:6046
* [Keypress](https://github.com/dmauro/Keypress) - A keyboard input capturing utility in which any key can be a modifier key. :star:3153
* [KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) - A JavaScript library for binding keyboard combos without the pain of key codes and key combo conflicts. :star:1459
* [jquery.hotkeys](https://github.com/jeresig/jquery.hotkeys) - jQuery Hotkeys lets you watch for keyboard events anywhere in your code supporting almost any key combination. :star:2503
* [jwerty](https://github.com/keithamus/jwerty) - Awesome handling of keyboard events. :star:1217


## Tours And Guides

* [intro.js](https://github.com/usablica/intro.js) - A better way for new feature introduction and step-by-step users guide for your website and project. :star:16739
* [shepherd](https://github.com/HubSpot/shepherd) - Guide your users through a tour of your app. :star:5614
* [bootstrap-tour](https://github.com/sorich87/bootstrap-tour) - Quick and easy product tours with Twitter Bootstrap Popovers. :star:4085
* [tourist](https://github.com/easelinc/tourist) - Simple, flexible tours for your app. :star:1222
* [chardin.js](https://github.com/heelhook/chardin.js) - Simple overlay instructions for your apps. :star:4635
* [pageguide](https://github.com/tracelytics/pageguide) - An interactive guide for web page elements using jQuery and CSS3. :star:885
* [hopscotch](https://github.com/linkedin/hopscotch) - A framework to make it easy for developers to add product tours to their pages. :star:4002
* [joyride](https://github.com/zurb/joyride) - jQuery feature tour plugin. :star:1387
* [focusable](https://github.com/zzarcon/focusable) - Set a spotlight focus on DOM element adding a overlay layer to the rest of the page. :star:1069

## Notifications

* [iziToast](https://github.com/dolce/iziToast) - Elegant, responsive, flexible and lightweight notification plugin with no dependencies. :star:1415
* [messenger](https://github.com/HubSpot/messenger) - Growl-style alerts and messages for your app. :star:4046
* [noty](https://github.com/needim/noty) - jQuery notification plugin. :star:5908
* [pnotify](https://github.com/sciactive/pnotify) - JavaScript notifications for Bootstrap, jQuery UI, and the Web Notifications Draft. :star:3216
* [toastr](https://github.com/CodeSeven/toastr) - Simple javascript toast notifications. :star:8286
* [humane-js](https://github.com/wavded/humane-js) - A simple, modern, browser notification system. :star:2101
* [smoke.js](https://github.com/hxgf/smoke.js) - Framework-agnostic styled alert system for javascript. :star:945
* [notie](https://github.com/jaredreich/notie) - Simple notifications and inputs with no dependencies. :star:5967


## Sliders

* [Swiper](https://github.com/nolimits4web/Swiper) - Mobile touch slider and framework with hardware accelerated transitions. :star:16579
* [slick](https://github.com/kenwheeler/slick) - The last carousel you'll ever need. :star:21776
* [slidesJs](http://www.slidesjs.com) - Is a ressponsive slideshow plug-in for JQuery(1.7.1+) with features like touch and CSS3 transitions
* [FlexSlider](https://github.com/woothemes/FlexSlider) - An awesome, fully responsive jQuery slider plugin. :star:4901
* [unslider](https://github.com/idiot/unslider) - The simplest jQuery slider there is. :star:4262
* [sly](https://github.com/darsain/sly) - JavaScript library for one-directional scrolling with item based navigation support. :star:2838
* [vegas](https://github.com/jaysalvat/vegas) - A jQuery plugin to add beautiful fullscreen backgrounds to your webpages. It even allows Slideshows. :star:1661
* [Sequence](https://github.com/IanLunn/Sequence) - CSS animation framework for creating responsive sliders, presentations, banners, and other step-based applications. :star:3366
* [reveal.js](https://github.com/hakimel/reveal.js) - A framework for easily creating beautiful presentations using HTML. :star:40864
* [impress.js](https://github.com/impress/impress.js) - It's a presentation framework based on the power of CSS3 transforms and transitions in modern browsers and inspired by the idea behind prezi.com. :star:33629
* [bespoke.js](https://github.com/bespokejs/bespoke) - DIY Presentation Micro-Framework :star:4370
* [Strut](https://github.com/tantaman/Strut) - Strut - An Impress.js and Bespoke.js Presentation Editor :star:1482
* [PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe) - JavaScript image gallery for mobile and desktop, modular, framework independent. :star:16594
* [jcSlider](https://github.com/JoanClaret/jcSlider) - A responsive slider jQuery plugin with CSS animations. :star:41
* [basic-jquery-slider](https://github.com/jcobb/basic-jquery-slider) - Simple to use, simple to theme, simple to customise. :star:568
* [jQuery.adaptive-slider](https://github.com/creative-punch/jQuery.adaptive-slider/) - A jQuery plugin for a slider with adaptive colored figcaption and navigation.
* [slidr](https://github.com/bchanx/slidr) - add some slide effects. :star:1503
* [Flickity](https://github.com/metafizzy/flickity) - Touch, responsive, flickable galleries. :star:4729
* [Glide.js](https://github.com/jedrzejchalubek/glidejs) - Responsive and touch-friendly jQuery slider. It's simple, lightweight and fast. :star:3238
* [jQuery.adaptive-slider](https://github.com/creative-punch/jQuery.adaptive-slider/) - A jQuery plugin for a slider with adaptive colored figcaption and navigation.

## Range Sliders

* [Ion.RangeSlider](https://github.com/IonDen/ion.rangeSlider) - Powerful and easily customizable range slider with many options and skin support. :star:1949
* [jQRangeSlider](https://github.com/ghusse/jQRangeSlider) - A javascript slider selector that supports dates. :star:676
* [noUiSlider](https://github.com/leongersen/noUiSlider) - A lightweight, highly customizable range slider without bloat. :star:3379
* [rangeslider.js](https://github.com/andreruffert/rangeslider.js) - HTML5 input range slider element polyfill. :star:1768


## Form Widgets

### Input

* [typeahead.js](https://github.com/twitter/typeahead.js) - A fast and fully-featured autocomplete library. :star:15214
* [tag-it](https://github.com/aehlke/tag-it) - A jQuery UI plugin to handle multi-tag fields as well as tag suggestions/autocomplete. :star:2421
* [At.js](https://github.com/ichord/At.js) - Add Github like mentions autocomplete to your application. :star:4920
* [Placeholders.js](https://github.com/jamesallardice/Placeholders.js) - A JavaScript polyfill for the HTML5 placeholder attribute. :star:964
* [fancyInput](https://github.com/yairEO/fancyInput) - Makes typing in input fields fun with CSS3 effects. :star:1952
* [jQuery-Tags-Input](https://github.com/xoxco/jQuery-Tags-Input) - Magically convert a simple text input into a cool tag list with this jQuery plugin. :star:2158
* [vanilla-masker](https://github.com/BankFacil/vanilla-masker) - A pure javascript mask input. :star:936
* [Ion.CheckRadio](https://github.com/IonDen/ion.checkRadio) - jQuery plugin for styling checkboxes and radio-buttons. With skin support. :star:64
* [awesomplete](https://github.com/LeaVerou/awesomplete) - Ultra lightweight, usable, beautiful autocomplete with zero dependencies. - http://leaverou.github.io/awesomplete/ :star:6084

### Calendar

* [pickadate.js](https://github.com/amsul/pickadate.js) - The mobile-friendly, responsive, and lightweight jQuery date & time input picker. :star:7376
* [bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker) - A datepicker for @twitter bootstrap forked from Stefan Petre's (of eyecon.ro), improvements by @eternicode. :star:10879
* [Pikaday](https://github.com/dbushell/Pikaday) - A refreshing JavaScript Datepicker — lightweight, no dependencies, modular CSS. :star:6129
* [fullcalendar](https://github.com/fullcalendar/fullcalendar) - Full-sized drag & drop event calendar (jQuery plugin). :star:7990
* [rome](https://github.com/bevacqua/rome) - A customizable date (and time) picker. Dependency free, opt-in UI. :star:2796
* [datedropper](https://github.com/felicegattuso/datedropper) -  datedropper is a jQuery plugin that provides a quick and easy way to manage dates for input fields. :star:1706


### Select

* [selectize.js](https://github.com/brianreavis/selectize.js) - Selectize is the hybrid of a textbox and select box. It's jQuery based and it has autocomplete and native-feeling keyboard navigation; useful for tagging, contact lists, etc. :star:11031
* [select2](https://github.com/select2/select2) - a jQuery based replacement for select boxes. It supports searching, remote data sets, and infinite scrolling of results. :star:22420
* [chosen](https://github.com/harvesthq/chosen) - A library for making long, unwieldy select boxes more friendly. :star:21656

### File Uploader

* [jQuery-File-Upload](https://github.com/blueimp/jQuery-File-Upload) - File Upload widget with multiple file selection, drag&amp;drop support, progress bar, validation and preview images, audio and video for jQuery. :star:28808
* [dropzone](https://github.com/enyo/dropzone) - Dropzone is an easy to use drag'n'drop library. It supports image previews and shows nice progress bars. :star:13776
* [flow.js](https://github.com/flowjs/flow.js) - A JavaScript library providing multiple simultaneous, stable, fault-tolerant and resumable/restartable file uploads via the HTML5 File API. :star:2426
* [fine-uploader](https://github.com/FineUploader/fine-uploader) - Multiple file upload plugin with progress-bar, drag-and-drop, direct-to-S3 uploading. :star:7638
* [FileAPI](https://github.com/mailru/FileAPI) - A set of javascript tools for working with files. Multiupload, drag'n'drop and chunked file upload. Images: crop, resize and auto orientation by EXIF. :star:3250
* [plupload](https://github.com/moxiecode/plupload) - A JavaScript API for dealing with file uploads it supports features like multiple file selection, file type filtering, request chunking, client side image scaling and it uses different runtimes to achieve this such as HTML 5, Silverlight and Flash. :star:4891

### Other

* [form](https://github.com/malsup/form) - jQuery Form Plugin. :star:4559
* [Garlic.js](https://github.com/guillaumepotier/Garlic.js) - Automatically persist your forms' text and select field values locally, until the form is submitted. :star:2289
* [Countable](https://github.com/RadLikeWhoa/Countable) - A JavaScript function to add live paragraph-, word- and character-counting to an HTML element. :star:1505
* [card](https://github.com/jessepollak/card) - Make your credit card form better in one line of code. :star:9735
* [stretchy](https://github.com/LeaVerou/stretchy) - Form element autosizing, the way it should be. :star:1169


## Tips

* [tipsy](https://github.com/jaz303/tipsy) - Facebook-style tooltips plugin for jQuery. :star:2062
* [opentip](https://github.com/enyo/opentip) - An open source javascript tooltip based on the prototype framework. :star:1262
* [qTip2](https://github.com/qTip2/qTip2) - Pretty powerful tooltips. :star:2005
* [tooltipster](https://github.com/iamceege/tooltipster) - A jQuery tooltip plugin. :star:2518
* [simptip](https://github.com/arashmanteghi/simptip) - A simple CSS tooltip made with Sass. :star:637
* [jquery-popup-overlay](https://github.com/vast-engineering/jquery-popup-overlay) - jQuery plugin for responsive and accessible modal windows and tooltips. :star:455
* [toolbar](https://github.com/paulkinzett/toolbar) - A tooltip style toolbar jQuery plugin :star:2352
* [hint.css](https://github.com/chinchang/hint.css) - A tooltip library in CSS for your lovely websites. :star:7615

## Modals and Popups

* [Magnific-Popup](https://github.com/dimsemenov/Magnific-Popup) - Light and responsive lightbox script with focus on performance. :star:10248
* [jquery-popbox](https://github.com/gristmill/jquery-popbox) - jQuery PopBox UI Element. :star:448
* [jquery.avgrund.js](https://github.com/voronianski/jquery.avgrund.js) - A jQuery plugin with new modal concept for popups. :star:1829
* [vex](https://github.com/HubSpot/vex) - A modern dialog library which is highly configurable and easy to style. :star:6574
* [bootstrap-modal](https://github.com/jschr/bootstrap-modal) - Extends the default Bootstrap Modal class. Responsive, stackable, ajax and more. :star:5081
* [css-modal](https://github.com/drublic/css-modal) - A modal built out of pure CSS. :star:1726
* [jquery-popup-overlay](https://github.com/vast-engineering/jquery-popup-overlay) - jQuery plugin for responsive and accessible modal windows and tooltips. :star:455
* [SweetAlert](https://github.com/t4t5/sweetalert) - An awesome replacement for JavaScript's alert. :star:18592
* [baguetteBox.js](https://github.com/feimosi/baguetteBox.js) - Simple and easy to use lightbox script written in pure JavaScript. :star:1610
* [colorbox](https://github.com/jackmoore/colorbox) - A light-weight, customizable lightbox plugin for jQuery. :star:4734
* [fancyBox](https://github.com/fancyapps/fancyBox) - A tool that offers a nice and elegant way to add zooming functionality for images, html content and multi-media on your webpages. :star:5563
* [swipebox](https://github.com/brutaldesign/swipebox) - A touchable jQuery lightbox :star:1897
* [jBox](https://github.com/StephanWagner/jBox) - jBox is a powerful and flexible jQuery plugin, taking care of all your popup windows, tooltips, notices and more. :star:935

## Scroll

* [scrollMonitor](https://github.com/stutrek/scrollMonitor) - A simple and fast API to monitor elements as you scroll. :star:2776
* [headroom](https://github.com/WickyNilliams/headroom.js) - Give your pages some headroom. Hide your header until you need it. :star:9829
* [onepage-scroll](https://github.com/peachananr/onepage-scroll) - Create an Apple-like one page scroller website (iPhone 5S website) with One Page Scroll plugin. :star:9312
* [iscroll](https://github.com/cubiq/iscroll) - iScroll is a high performance, small footprint, dependency free, multi-platform javascript scroller. :star:11119
* [skrollr](https://github.com/Prinzhorn/skrollr) - Stand-alone parallax scrolling library for mobile (Android + iOS) and desktop. No jQuery. :star:17960
* [parallax](https://github.com/wagerfield/parallax) - Parallax Engine that reacts to the orientation of a smart device. :star:13005
* [stellar.js](https://github.com/markdalgleish/stellar.js) - Parallax scrolling made easy. :star:4446
* [plax](https://github.com/cameronmcefee/plax) - jQuery powered parallaxing. :star:2346
* [jparallax](https://github.com/stephband/jparallax) - jQuery plugin for creating interactive parallax effect. :star:1151
* [fullPage](https://github.com/alvarotrigo/fullPage.js) - A simple and easy to use plugin to create fullscreen scrolling websites (also known as single page websites). :star:23767
* [ScrollMenu](https://github.com/s-yadav/ScrollMenu) - A new interface to replace old boring scrollbar. :star:181
* [Clusterize.js](https://github.com/NeXTs/Clusterize.js) - Tiny vanilla JS plugin to display large data sets easily. :star:5768


## Menu

* [jQuery-menu-aim](https://github.com/kamens/jQuery-menu-aim) - jQuery plugin to fire events when user's cursor aims at particular dropdown menu items. For making responsive mega dropdowns like Amazon's. :star:7664
* [jQuery contextMenu](https://github.com/swisnl/jQuery-contextMenu) -  contextMenu manager. :star:1755
* [Slideout](https://github.com/mango/slideout) - A responsive touch slideout navigation menu for mobile web apps. :star:7337
* [Slide and swipe](https://github.com/JoanClaret/slide-and-swipe-menu) - A sliding swipe menu that works with touchSwipe library. :star:99


## Table/Grid

* [jTable](https://github.com/hikalkan/jtable) - A jQuery plugin to create AJAX based CRUD tables. :star:903
* [DataTables](https://www.datatables.net/) - (jQuery plug-in) It is a highly flexible tool, based upon the foundations of progressive enhancement, and will add advanced interaction controls to any HTML table.
* [floatThead](https://github.com/mkoryak/floatThead) - (jQuery plug-in) lock any table's header while scrolling within the body. Works on any table and requires no custom html or css. :star:1021
* [Masonry](http://masonry.desandro.com/) - A cascading grid layout library.
* [Packery](http://packery.metafizzy.co/) - A grid layout library that uses a bin-packing algorithm. Useable for draggable layouts.
* [Isotope](http://isotope.metafizzy.co/) - A filterable, sortable, grid layout library. Can implement Masonry, Packery, and other layouts.
* [flexboxgrid](https://github.com/kristoferjoseph/flexboxgrid/) - Grid based on CSS3 flexbox

## Frameworks

* [Semantic UI](http://semantic-ui.com/) - UI Kit with lots of themes and elements
* [w2ui](http://w2ui.com/) - A set of jQuery plugins for front-end development of data-driven web applications.
* [fluidity](https://github.com/mrmrs/fluidity) - The worlds smallest fully-responsive css framework :star:1129
* [Ink](https://github.com/sapo/Ink) - An HTML5/CSS3 framework used at SAPO for fast and efficient website design and prototyping :star:1919

## Boilerplates

 * [html5-boilerplate](https://github.com/h5bp/html5-boilerplate) - A professional front-end template for building fast, robust, and adaptable web apps or sites. :star:40688
 * [mobile-boilerplate](https://github.com/h5bp/mobile-boilerplate) - A front-end template that helps you build fast, modern mobile web apps. :star:4027
 * [webplate](https://github.com/chrishumboldt/webplate) - An awesome front-end framework that lets you stay focused on building your site or app while remaining really easy to use. :star:579
 * [Cerberus](https://github.com/TedGoas/Cerberus) - A few simple, but solid patterns for responsive HTML emails. Even in Outlook. :star:2955
 * [full-page-intro-and-navigation](https://github.com/CodyHouse/full-page-intro-and-navigation) - An intro page with a full width background image, a bold animated menu and an iOS-like blurred effect behind the navigation :star:34
 * [Fluid-Squares](https://github.com/crozynski/Fluid-Squares) - A fluid grid of square units. :star:29
 * [Mobile-First-RWD](https://github.com/bradfrost/Mobile-First-RWD) - An example of a mobile-first responsive web design :star:62
 * [this-is-responsive](https://github.com/bradfrost/this-is-responsive) - This Is Responsive :star:1530
 * [npm run-scripts](https://gist.github.com/addyosmani/9f10c555e32a8d06ddb0) Task automation with NPM run-scripts.

## Gesture

* [hammer.js](https://github.com/hammerjs/hammer.js) - A javascript library for multi-touch gestures. :star:18474
* [touchemulator](https://github.com/hammerjs/touchemulator) - Emulate touch input on your desktop. :star:187
* [Dragula](https://github.com/bevacqua/dragula/) - Drag and drop so simple it hurts


## Maps

* [Leaflet](https://github.com/Leaflet/Leaflet) - JavaScript library for mobile-friendly interactive maps. :star:21779
* [Cesium](https://github.com/AnalyticalGraphicsInc/cesium) - Open Source WebGL virtual globe and map engine. :star:3206
* [gmaps](https://github.com/HPNeo/gmaps) - The easiest way to use Google Maps. :star:6952
* [polymaps](https://github.com/simplegeo/polymaps) - A free JavaScript library for making dynamic, interactive maps in modern web browsers. :star:1504
* [kartograph.js](https://github.com/kartograph/kartograph.js) - Open source JavaScript renderer for Kartograph SVG maps. :star:1518
* [mapbox.js](https://github.com/mapbox/mapbox.js) - Mapbox JavaScript API, a Leaflet Plugin. :star:1540
* [jqvmap](https://github.com/manifestinteractive/jqvmap) - jQuery Vector Map Library. :star:1595
* [OpenLayers3](http://openlayers.org/) - A high-performance, feature-packed library for all your mapping needs.

## Video/Audio

 * [prettyembed.js](https://github.com/mike-zarandona/prettyembed.js) - Prettier embeds for your YouTubes - with nice options like high-res preview images, advanced customization of embed options, and optional FitVids support. :star:1065
 * [html5media](https://github.com/etianen/html5media) -  Enables <video> and <audio> tags in all major browsers. <https://html5media.info/> :star:1095
 * [Play-em JS](https://github.com/adrienjoly/playemjs) -  Play'em is a javascript component that manages a music/video track queue and plays a sequence of songs by embedding several players in a HTML DIV including Youtube, Soundcloud and Vimeo. :star:54
 * [polyplayer](https://github.com/Acconut/polyplayer) - Rule YouTube, Soundcloud and Vimeo player with one API :star:36
 * [flowplayer](https://github.com/flowplayer/flowplayer) -  The HTML5 video player for the web :star:1636
 <https://flowplayer.org/>
 * [mediaelement](https://github.com/johndyer/mediaelement) -  HTML5 <audio> or <video> player with Flash and Silverlight shims that mimics the HTML5 MediaElement API, enabling a consistent UI in all browsers. <http://mediaelementjs.com/> :star:6112
 * [SoundJS](https://github.com/CreateJS/SoundJS) - A library to make working with audio on the web easier. It provides a consistent API for playing audio in different browsers. :star:3397
 * [video.js](https://github.com/videojs/video.js) - Video.js - open source HTML5 & Flash video player :star:21478
 * [FitVids.js](https://github.com/davatron5000/FitVids.js) - A lightweight, easy-to-use jQuery plugin for fluid width video embeds. :star:4631
 * [Ion.Sound](https://github.com/IonDen/ion.sound) - Simple sounds on any web page :star:646
 * [photobooth-js](https://github.com/WolframHempel/photobooth-js) - A widget that allows users to take their avatar pictures on your site :star:581
 * [clappr](https://github.com/clappr/clappr) - An extensible media player for the web http://clappr.io :star:4196

## Typography

 * [FlowType.JS](https://github.com/simplefocus/FlowType.JS) - Web typography at its finest: font-size and line-height based on element width. :star:4523
 * [BigText](https://github.com/zachleat/BigText) - jQuery plugin, calculates the font-size and word-spacing needed to match a line of text to a specific width. :star:849
 * [circletype](https://github.com/peterhry/circletype) - A jQuery plugin that lets you curve type on the web :star:373
 * [slabText](https://github.com/freqDec/slabText/) - A jQuery plugin for producing big, bold & responsive headlines
 * [simple-text-rotator](https://github.com/peachananr/simple-text-rotator) - Add a super simple rotating text to your website with little to no markup :star:695
 * [novacancy.js](https://github.com/chuckyglitch/novacancy.js) - Text Neon Golden effect jQuery plug-in. :star:147
 * [jquery-responsive-text](https://github.com/ghepting/jquery-responsive-text) - Make your text sizing responsive! :star:123
 * [FitText.js](https://github.com/davatron5000/FitText.js) - A jQuery plugin for inflating web type :star:6531
 * [Lettering.js](https://github.com/davatron5000/Lettering.js) - A lightweight, easy to use Javascript `<span>` injector for radical Web Typography :star:5051


## Animations

* [velocity](https://github.com/julianshapiro/velocity) - Accelerated JavaScript animation. :star:14642
* [jquery.transit](https://github.com/rstacruz/jquery.transit) - Super-smooth CSS3 transformations and transitions for jQuery. :star:7438
* [impress.js](https://github.com/impress/impress.js) - Make Prezi-like presentations with CSS3 transformations/transitions in an HTML document. :star:33629
* [bounce.js](https://github.com/tictail/bounce.js) - Create tasty CSS3 powered animations in no time. :star:5555
* [GreenSock-JS](https://github.com/greensock/GreenSock-JS) - High-performance HTML5 animations that work in all major browsers. :star:7713
* [TransitionEnd](https://github.com/EvandroLG/transitionEnd) - TransitionEnd is an agnostic and cross-browser library to work with transitionend event. :star:89
* [Dynamic.js](https://github.com/michaelvillar/dynamics.js) - Javascript library to create physics-based CSS animations. :star:6872
* [the-cube](https://github.com/pstadler/the-cube) - The Cube is an experiment with CSS3 transitions. :star:7
* [Effeckt.css](https://github.com/h5bp/Effeckt.css) - A Performant Transitions and Animations Library :star:11167
* [animate.css](https://github.com/daneden/animate.css) - A cross-browser library of CSS animations. As easy to use as an easy thing. :star:52001
* [textillate](https://github.com/jschr/textillate) - A simple plugin for CSS3 text animations :star:3234
* [move.js](https://github.com/visionmedia/move.js) - CSS3 backed JavaScript animation framework :star:4336
* [animatable](https://github.com/LeaVerou/animatable) - One property, two values, endless possiblities :star:2387
* [shuffle-images](https://github.com/peachananr/shuffle-images) -  The Simplest Way to shuffle through images in a Creative Way http://www.thepetedesign.com/demos/shuffle-images_demo.html :star:190
* [smoothState.js](https://github.com/miguel-perez/smoothState.js) - Unobtrusive page transitions with jQuery. http://smoothstate.com/ :star:4223

## Image Processing

* [lena.js](https://github.com/davidsonfellipe/lena.js) - A Library for image processing with filters and util functions. :star:246
* [pica](https://github.com/nodeca/pica) - High quality image resize (with fast Lanczos filter, implemented in pure JS). :star:1219
* [cropper](https://github.com/fengyuanchen/cropper) - A simple jQuery image cropping plugin. :star:6829


## ES6

* [es6features](https://github.com/lukehoban/es6features) - Overview of ECMAScript 6 features. :star:24222
* [es6-features](https://github.com/rse/es6-features) - ECMAScript 6: Feature Overview & Comparison. :star:4884
* [es6-cheatsheet](https://github.com/DrkSephy/es6-cheatsheet) - ES2015 [ES6] cheatsheet containing tips, tricks, best practices and code snippets. :star:10675
* [ECMAScript 6 compatibility table](http://kangax.github.io/compat-table/es6/) - Compatibility tables for all ECMAScript 6 features on a variety of environments.
* [Babel (Formerly 6to5)](https://github.com/babel/babel) - Turn ES6+ code into vanilla ES5 with no runtime. :star:27987
* [Traceur compiler](https://github.com/google/traceur-compiler) - ES6 features > ES5. Includes classes, generators, promises, destructuring patterns, default parameters & more. :star:7669


## SDK

* [javascript-sdk-design](https://github.com/huei90/javascript-sdk-design) - Javascript SDK design guide extracted from work and personal experience :star:573
* [Spotify SDK](https://github.com/loverajoel/spotify-sdk) - Entity oriented SDK to work with the Spotify Web API. :star:146


## Misc

* [echo](https://github.com/toddmotto/echo) - Lazy-loading images with data-* attributes. :star:3601
* [picturefill](https://github.com/scottjehl/picturefill) - A responsive image polyfill for &lt;picture&gt;, srcset, sizes. :star:9659
* [platform.js](https://github.com/bestiejs/platform.js) - A platform detection library that works on nearly all JavaScript platforms. :star:2006
* [json3](https://github.com/bestiejs/json3) - A modern JSON implementation compatible with nearly all JavaScript platforms. :star:992
* [Logical Or Not](http://gabinaureche.com/logicalornot/) - A game about JavaScript specificities.
* [BitSet.js](https://github.com/infusion/BitSet.js) - A JavaScript Bit-Vector implementation :star:131
* [spoiler-alert](https://github.com/joshbuddy/spoiler-alert) - SPOILER ALERT! A happy little jquery plugin to hide spoilers on your site. :star:475
* [jquery.vibrate.js](https://github.com/illyism/jquery.vibrate.js) - Vibration API Wrappers :star:132
* [list.js](https://github.com/javve/list.js) -  Adds search, sort, filters and flexibility to tables, lists and various HTML elements. Built to be invisible and work on existing HTML. :star:9030
http://www.listjs.com
* [mixitup](https://github.com/patrickkunka/mixitup) - MixItUp - A Filter & Sort Plugin :star:4075
* [grid](https://github.com/hootsuite/grid) - Drag and drop library for two-dimensional, resizable and responsive lists. :star:3392
* [jquery-match-height](https://github.com/liabru/jquery-match-height) - a responsive equal heights plugin for jQuery. :star:2875
* [survey.js](https://github.com/surveyjs/surveyjs) - JavaScript Survey Engine. It uses JSON for survey metadata and results. http://surveyjs.org/ :star:1109
* [Array Explorer](https://github.com/sdras/array-explorer) and [Object Explorer](https://sdras.github.io/object-explorer/) - Resources to help figure out what native JavaScript method would be best to use at any given time

## Podcasts
* [JavaScript Air](https://javascriptair.com/) - The live video broadcast podcast all about JavaScript and the Web platform.
* [Web of Tomorrow](http://www.weboftomorrowpodcast.com/) - Podcast about JavaScript for beginners.
* [Javascript Jabber](https://devchat.tv/js-jabber) - A weekly podcast about JavaScript, including Node.js, Front-End Technologies, Careers, Teams and more.

# Worth Reading
* [braziljs/js-the-right-way](https://github.com/braziljs/js-the-right-way/)
* [JSbooks](https://github.com/revolunet/JSbooks) :star:2112
* [Superhero.js](http://superherojs.com) - A collection of resources about creating, testing and maintaining a large JavaScript code base.
* [SJSJ](https://github.com/HugoGiraudel/SJSJ) - Simplified JavaScript Jargon is a community-driven attempt at explaining the loads of buzzwords making the current JavaScript ecosystem in a few simple words. :star:2090
* [How to Write an Open Source JavaScript Library](https://github.com/sarbbottam/write-an-open-source-js-lib) - A comprehensive guide through a set of steps to publish a JavaScript open source library. :star:112
* [Jaavascript tutorial](https://hackr.io/tutorials/learn-javascript) - Learn Javascript online from a diverse range of user ranked online tutorials.


# Other Awesome Lists
* [sotayamashita/awesome-css](https://github.com/sotayamashita/awesome-css) :star:1590
* [emijrp/awesome-awesome](https://github.com/emijrp/awesome-awesome) :star:1128
* [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) :star:21549
* [sindresorhus/awesome](https://github.com/sindresorhus/awesome) :star:86455
* [jnv/list](https://github.com/jnv/lists) :star:5008
* [gianarb/angularjs](https://github.com/gianarb/awesome-angularjs) :star:2384
* [peterkokot/awesome-dojo](https://github.com/peterkokot/awesome-dojo) :star:62
* [addyosmani/es6-tools](https://github.com/addyosmani/es6-tools) :star:3598
* [ericdouglas/ES6-Learning](https://github.com/ericdouglas/ES6-Learning) :star:4373
* [obetomuniz/awesome-webcomponents](https://github.com/obetomuniz/awesome-webcomponents) :star:148
* [willianjusten/awesome-svg](https://github.com/willianjusten/awesome-svg) :star:3601
* [davidsonfellipe/awesome-wpo](https://github.com/davidsonfellipe/awesome-wpo) :star:6260
* [instanceofpro/awesome-backbone](https://github.com/sadcitizen/awesome-backbone) :star:375
* [enaqx/awesome-react](https://github.com/enaqx/awesome-react) :star:25969
* [bolshchikov/js-must-watch](https://github.com/bolshchikov/js-must-watch) :star:11643
* [peterkokot/awesome-jquery](https://github.com/peterkokot/awesome-jquery) :star:575
* [dinbror/you-might-not-need-jquery-plugins](https://github.com/dinbror/you-might-not-need-jquery-plugins) :star:12
* [MaximAbramchuck/awesome-interviews](https://github.com/MaximAbramchuck/awesome-interview-questions) :star:19252

# Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

# License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [chencheng](https://github.com/sorrycc) has waived all copyright and related or neighboring rights to this work.


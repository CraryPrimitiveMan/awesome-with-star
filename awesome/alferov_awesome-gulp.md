# Information comes from [alferov/awesome-gulp](https://github.com/alferov/awesome-gulp)
# Awesome Gulp [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome [gulp](https://github.com/gulpjs/gulp) resources, plugins, and boilerplates for a better development workflow automation.

*Looking for something else? Take a look at other [awesome lists](https://github.com/sindresorhus/awesome).*

## Contribution
:octocat: All contributions welcome. Feel free to contribute ([guidelines](contributing.md)).

## Contents
- [Legend](#legend)
- [Resources](#resources)
  - [General Resources](#general-resources)
  - [Official Documentation](#official-documentation)
  - [Community](#community)
  - [Tutorials](#tutorials)
    - [Gulp Tutorials](#gulp-tutorials)
    - [Gulp 4 Tutorials](#gulp-4-tutorials)
    - [Gulp with Browserify](#gulp-with-browserify)
    - [Gulp with Angular](#gulp-with-browserify)
    - [Gulp with Angular and Browserify](#gulp-with-angular-and-browserify)
    - [Gulp with Angular and Webpack](#gulp-with-angular-and-webpack)
    - [Gulp with React and Browserify](#gulp-with-react-and-browserify)
    - [Gulp with Ember](#gulp-with-ember)
  - [Miscellaneous Resources](#miscellaneous-resources)
- [Plugins](#plugins)
  - [Compilation](#compilation)
  - [Transpilation](#transpilation)
  - [Concatenation](#concatenation)
  - [Minification](#minification)
  - [Optimization](#optimization)
  - [Injecting Assets](#injecting-assets)
  - [Templating](#templating)
  - [Linting](#linting)
  - [Live Reload](#live-reload)
  - [Caching](#caching)
  - [Flow Control](#flow-control)
  - [Logging](#logging)
  - [Testing](#testing)
  - [Miscellaneous Plugins](#miscellaneous-plugins)
- [Scaffolding](#scaffolding)
  - [Boilerplates](#boilerplates)
  - [Yeoman Generators](#yeoman-generators)
- [Miscellaneous](#miscellaneous)

## Legend
[:no_entry:] - A deprecation notice;

## Resources
### General Resources
* [Official Website](http://gulpjs.com/)
* [Github Repository](https://github.com/gulpjs/gulp) :star:29333
* [Plugin Registry](http://gulpjs.com/plugins/)
* [NPM Module](https://www.npmjs.com/package/gulp)
* [Blacklisted Plugins](https://github.com/gulpjs/plugins/blob/master/src/blackList.json)

### Official Documentation
* [Getting Started](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md)
* [API Documentation](https://github.com/gulpjs/gulp/blob/master/docs/API.md)
* [CLI Documentation](https://github.com/gulpjs/gulp/tree/master/docs#articles)
* [Writing a Plugin](https://github.com/gulpjs/gulp/blob/master/docs/writing-a-plugin/README.md)
* [Recipes](https://github.com/gulpjs/gulp/tree/master/docs/recipes)

### Community
* [StackOverflow](http://stackoverflow.com/questions/tagged/gulp)
* [Twitter](https://twitter.com/gulpjs)

### Tutorials
#### Gulp Tutorials
* [Building with Gulp](https://www.smashingmagazine.com/2014/06/building-with-gulp/)
* [Automate Your Tasks Easily with Gulp.js](https://scotch.io/tutorials/automate-your-tasks-easily-with-gulp-js)
* [Gulp - The Vision, History, and Future of the Project](https://medium.com/@contrahacks/gulp-3828e8126466)
* [Introduction to Gulp.js](http://stefanimhoff.de/tag/gulp/)
* [Video: Learning Gulp](http://leveluptuts.com/tutorials/learning-gulp)
* [Using Gulp to Inject Scripts and Styles Tags Directly into Your HTML](http://blog.johnnyreilly.com/2015/02/using-gulp-in-asp-net-instead-of-web-optimization.html)
* [5 Lessons Learned Using Gulp.js](http://denbuzze.com/post/5-lessons-learned-using-gulpjs/)
* [Automating Linkage: How I Learned to Stop Worrying and Love the Build](http://conan.is/bower/gulp/wiredep/javascript/2014/08/18/automating_linkage-or-how-i-learned-to-stop-worrying-and-love-the-build.html)
* [Setting Up Gulp Tasks for the First Time](https://www.codementor.io/development-process/tutorial/how-to-set-up-gulp-beginner-guide#/)
* [Why You Shouldn’t Create a Gulp Plugin (or, How to Stop Worrying and Learn to Love Existing Node Packages)](http://blog.overzealous.com/post/74121048393/why-you-shouldnt-create-a-gulp-plugin-or-how-to)
* [6 Gulp Best Practices You Can Use Today to Radically Improve Your Development Experience](http://blog.rangle.io/angular-gulp-bestpractices/)
* [Gulp for Beginners](https://css-tricks.com/gulp-for-beginners/)

#### Gulp 4 Tutorials
* [Migrating to Gulp 4 by Example](https://blog.wearewizards.io/migrating-to-gulp-4-by-example)
* [Gulp 4: The new task execution system - gulp.parallel and gulp.series](http://fettblog.eu/gulp-4-parallel-and-series/)

#### Gulp with Browserify
* [Gulp + Browserify, the Gulp-y Way](https://medium.com/@sogko/gulp-browserify-the-gulp-y-way-bb359b3f9623)
* [Gulp + Browserify](https://viget.com/extend/gulp-browserify-starter-faq)
* [Fast Browserify Builds with Watchify](https://github.com/gulpjs/gulp/blob/master/docs/recipes/fast-browserify-builds-with-watchify.md)

#### Gulp with Angular
* [What Every Angular Project Likely Needs - and a Gulp Build to Provide It](http://blog.jhades.org/what-every-angular-project-likely-needs-and-a-gulp-build-to-provide-it/)

#### Gulp with Angular and Browserify
* [Advanced AngularJS Structure with Gulp, Node and Browserify](http://omarfouad.com/blog/2015/03/21/advanced-angularjs-structure-with-gulp-node-and-browserify/)

#### Gulp with Angular and Webpack
* [Angular, Webpack and Gulp for an SPA: Part I](https://luwenhuang.wordpress.com/2015/01/18/refactoring-an-angular-app-to-use-webpack-and-gulp/)
* [Angular, Webpack and Gulp for an SPA: Part II](https://luwenhuang.wordpress.com/2015/01/19/angular-webpack-and-gulp-for-an-spa-part-ii/)
* [Angular, Webpack and Gulp for an SPA: Part III](https://luwenhuang.wordpress.com/2015/01/28/angular-webpack-and-gulp-for-an-spa-part-iii/)

#### Gulp with React and Browserify
* [Browserify and Gulp with React](https://hacks.mozilla.org/2014/08/browserify-and-gulp-with-react/)
* [Taking React to the Next Level: Mixins, Gulp, and Browserify](http://pomax.github.io/1420592591221/taking-react-to-the-next-level-mixins-gulp-and-browserify)

#### Gulp with Ember
* [Improving Your Ember.js Workflow Using Gulp.js](http://www.sitepoint.com/improving-ember-js-workflow-using-gulp-js/)

#### Gulp with WordPress
* [Advanced WordPress Development Using Gulp](https://premium.wpmudev.org/blog/advanced-wordpress-development-using-gulp/)

### Miscellaneous Resources
* [Gulp Cheatsheet](https://github.com/osscafe/gulp-cheatsheet) :star:1386
* [Playground for Gulp Recipes](https://github.com/johnpapa/gulp-patterns) :star:525

## Plugins
### Compilation
* [gulp-sass](https://github.com/dlmanning/gulp-sass) - Sass → CSS with [libsass](https://github.com/sass/libsass). :star:1274
* [gulp-ruby-sass](https://github.com/sindresorhus/gulp-ruby-sass) - Sass → CSS with Ruby Sass. :star:489
* [gulp-compass](https://github.com/appleboy/gulp-compass) - Sass → CSS with Ruby Sass & Compass. :star:177
* [gulp-less](https://github.com/plus3network/gulp-less) - [Less](https://github.com/less/less.js) → CSS. :star:553
* [gulp-stylus](https://github.com/stevelacy/gulp-stylus) - [Stylus](https://github.com/stylus/stylus) → CSS. :star:216
* [gulp-postcss](https://github.com/postcss/gulp-postcss) - Pipe CSS through [PostCSS](https://github.com/postcss/postcss) processors with a single parse. :star:585
* [gulp-coffee](https://github.com/contra/gulp-coffee) - [Coffeescript](https://github.com/jashkenas/coffeescript) → JavaScript. :star:223
* [gulp-typescript](https://github.com/ivogabe/gulp-typescript) - [TypeScript](https://github.com/Microsoft/TypeScript) → JavaScript. :star:624
* [gulp-react](https://github.com/sindresorhus/gulp-react) - Facebook [React](https://github.com/facebook/react) JSX templates → JavaScript. :star:243
* [webpack-stream](https://github.com/shama/webpack-stream) - Run [webpack](https://github.com/webpack/webpack) as a stream to conveniently integrate with gulp. :star:1121

### Transpilation
* [gulp-babel](https://github.com/babel/gulp-babel) - ES6 → ES5 with [babel](https://github.com/babel/babel). :star:1083
* [gulp-traceur](https://github.com/sindresorhus/gulp-traceur) - ES6 → ES5 using [Traceur](https://github.com/google/traceur-compiler). :star:179
* [gulp-regenerator](https://github.com/sindresorhus/gulp-regenerator) - ES6 → ES5 with [Regenerator](https://github.com/facebook/regenerator). :star:19
* [gulp-es6-transpiler](https://github.com/sindresorhus/gulp-es6-transpiler) - [:no_entry:] ES6 → ES5 with [es6-transpiler](https://github.com/termi/es6-transpiler). :star:49
* [gulp-myth](https://github.com/sindresorhus/gulp-myth) - [Myth](https://github.com/segmentio/myth) - a polyfill for future versions of the CSS spec. :star:4418
* [gulp-cssnext](https://github.com/MoOx/gulp-cssnext) - [:no_entry:] Use tomorrow's CSS syntax, today, using [cssnext](https://github.com/MoOx/postcss-cssnext). :star:54

### Concatenation
* [gulp-concat](https://github.com/contra/gulp-concat) - Concatenate files. :star:715

### Minification
* [gulp-clean-css](https://github.com/scniro/gulp-clean-css) - Minify CSS with [clean-css](https://github.com/jakubpawlowicz/clean-css). :star:507
* [gulp-csso](https://github.com/ben-eb/gulp-csso) - Minify CSS with [CSSO](https://github.com/css/csso). :star:219
* [gulp-uglify](https://github.com/terinjokes/gulp-uglify) - Minify JavaScript with [UglifyJS2](https://github.com/mishoo/UglifyJS2). :star:1099
* [gulp-htmlmin](https://github.com/jonschlinkert/gulp-htmlmin) - Minify HTML with [html-minifier](https://github.com/kangax/html-minifier). :star:588
* [gulp-imagemin](https://github.com/sindresorhus/gulp-imagemin) - Minify PNG, JPEG, GIF and SVG images with [imagemin](https://github.com/imagemin/imagemin). :star:1492
* [gulp-svgmin](https://github.com/ben-eb/gulp-svgmin) - Minify SVG files with gulp. :star:311

### Optimization
* [gulp-uncss](https://github.com/ben-eb/gulp-uncss) - Remove unused CSS selectors with [UnCSS](https://github.com/giakki/uncss). :star:979
* [gulp-css-base64](https://github.com/zckrs/gulp-css-base64) - Transform all resources found (those within a url() declaration) in CSS files into base64-encoded data URI strings. :star:62
* [gulp-svg2png](https://github.com/akoenig/gulp-svg2png) - Convert SVGs to PNGs. :star:52
* [gulp-responsive](https://github.com/mahnunchik/gulp-responsive) - Generate images at different sizes. :star:421
* [gulp-svgstore](https://github.com/w0rm/gulp-svgstore) - Combine svg files into one with <symbol> elements. :star:592
* [gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) - Create icon fonts from several SVG icons. :star:714

### Injecting Assets
* [gulp-useref](https://github.com/jonkemp/gulp-useref) - Parse build blocks in HTML files to replace references to non-optimized scripts or stylesheets. :star:676
* [gulp-inject](https://github.com/klei/gulp-inject) - Transform each file to a string and inject each transformed string into placeholders in the target stream files. :star:754
* [wiredep](https://github.com/taptapship/wiredep) - Wire Bower dependencies to your source code. :star:1189

### Templating
* [gulp-angular-templatecache](https://github.com/miickel/gulp-angular-templatecache) - Concatenate and register AngularJS templates in the $templateCache. :star:524
* [gulp-jade](https://github.com/phated/gulp-jade) - [Jade](https://github.com/pugjs/jade) → HTML. :star:470
* [gulp-handlebars](https://github.com/lazd/gulp-handlebars) - [Handlebars](https://github.com/wycats/handlebars.js) templates → JavaScript. :star:152
* [gulp-hb](https://github.com/shannonmoeller/gulp-hb) - [Handlebars](https://github.com/wycats/handlebars.js) templates → HTML. :star:129
* [gulp-nunjucks](https://github.com/sindresorhus/gulp-nunjucks) - [Nunjucks](https://github.com/mozilla/nunjucks) templates → JavaScript. :star:107
* [gulp-dustjs](https://github.com/sindresorhus/gulp-dust) - [Dust](https://github.com/linkedin/dustjs) templates → JavaScript. :star:18
* [gulp-riot](https://github.com/e-jigsaw/gulp-riot) - [Riot](https://github.com/riot/riot) templates → JavaScript. :star:106
* [gulp-markdown](https://github.com/sindresorhus/gulp-markdown) - Markdown → HTML. :star:139
* [gulp-template](https://github.com/sindresorhus/gulp-template) - [Lodash ](https://github.com/lodash/lodash) templates → JavaScript. :star:245
* [gulp-swig](https://github.com/colynb/gulp-swig) - [Swig](https://github.com/paularmstrong/swig) templates → HTML. :star:69
* [gulp-remark](https://github.com/denysdovhan/gulp-remark) - Gulp plugin for [remark](https://github.com/wooorm/remark) - markdown processor powered by plugins :star:1427

### Linting
* [gulp-csslint](https://www.npmjs.com/package/gulp-csslint) - Automated linting of CSS with [CSSLint](https://github.com/CSSLint/csslint).
* [gulp-htmlhint](https://github.com/bezoerb/gulp-htmlhint) - [HTMLHint](https://github.com/yaniswang/HTMLHint) wrapper to validate your HTML. :star:72
* [gulp-jshint](https://github.com/spalger/gulp-jshint) - Detect errors and potential problems in JavaScript with [JSHint](https://github.com/jshint/jshint). :star:426
* [gulp-jscs](https://github.com/jscs-dev/gulp-jscs) - Check JavaScript code style with [jscs](https://github.com/jscs-dev/node-jscs). :star:322
* [gulp-coffeelint](https://github.com/janraasch/gulp-coffeelint) - A style checker that helps keep [CoffeeScript](https://github.com/jashkenas/coffeescript) code clean. :star:54
* [gulp-tslint](https://github.com/panuhorsmalahti/gulp-tslint) - [TypeScript](https://github.com/Microsoft/TypeScript) linter plugin for gulp. :star:110
* [gulp-eslint](https://github.com/adametry/gulp-eslint) - Identify and report on patterns found in ECMAScript/JavaScript code. :star:515
* [gulp-w3cjs](https://github.com/callumacrae/gulp-w3cjs) - Validate HTML with [w3cjs](https://github.com/thomasdavis/w3cjs). :star:54
* [gulp-lesshint](https://github.com/lesshint/gulp-lesshint) - Lint less files with [lesshint](https://github.com/lesshint/lesshint). :star:14
* [gulp-check-unused-css](https://github.com/zalando/gulp-check-unused-css) - Check your HTML templates for unused CSS classes. :star:358

### Live Reload
* [browser-sync](https://github.com/BrowserSync/browser-sync) - Keep multiple browsers & devices in sync when building websites ([recipes](https://github.com/BrowserSync/gulp-browser-sync)). :star:9868
* [gulp-livereload](https://github.com/vohof/gulp-livereload) - Gulp plugin for livereload. :star:769

### Caching
* [gulp-changed](https://github.com/sindresorhus/gulp-changed) - Only pass through changed files. :star:704
* [gulp-cached](https://github.com/contra/gulp-cached) - A simple in-memory file cache. :star:431
* [gulp-remember](https://github.com/ahaurw01/gulp-remember) - Remember and recall files passed through it. :star:148
* [gulp-newer](https://github.com/tschaub/gulp-newer) - Pass through newer source files only. :star:209

### Flow Control
* [merge-stream](https://github.com/grncdr/merge-stream) - Merge multiple streams into one interleaved stream. :star:138
* [streamqueue](https://github.com/nfroidure/StreamQueue) - Pipe queued streams progressively. :star:61
* [run-sequence](https://github.com/OverZealous/run-sequence) - Run a series of dependent gulp tasks in order. :star:952
* [gulp-if](https://github.com/robrich/gulp-if) - Conditionally run a task. :star:589

### Logging
* [gulp-notify](https://github.com/mikaelbr/gulp-notify) - Notification plugin for gulp. :star:574
* [gulp-size](https://github.com/sindresorhus/gulp-size) - Display the size of your project. :star:217
* [gulp-debug](https://github.com/sindresorhus/gulp-debug) - Debug vinyl file streams to see what files are run through your gulp pipeline. :star:208

### Testing
* [gulp-mocha](https://github.com/sindresorhus/gulp-mocha) - Run [Mocha](https://github.com/mochajs/mocha) tests. :star:351
* [gulp-jasmine](https://github.com/sindresorhus/gulp-jasmine) - Run [Jasmine 2](https://github.com/jasmine/jasmine) tests in Node.js. :star:108
* [gulp-protractor](https://github.com/mllrsohn/gulp-protractor) - Gulp wrapper for [Protractor](https://github.com/angular/protractor) tests. :star:134
* [gulp-coverage](https://github.com/dylanb/gulp-coverage) - Coverage reporting for Node.js that is independent of the test runner. :star:61
* [gulp-karma](https://github.com/karma-runner/gulp-karma) - Karma test runner for gulp. :star:320
* [gulp-ava](https://github.com/sindresorhus/gulp-ava)- Run [AVA](https://github.com/sindresorhus/ava) tests with gulp.

### Miscellaneous Plugins
* [gulp-util](https://github.com/gulpjs/gulp-util) - Set of useful utilities. :star:825
* [gulp-plumber](https://github.com/floatdrop/gulp-plumber) - Prevent pipe breaking caused by errors. :star:770
* [gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) - Automatically load in gulp plugins. :star:746
* [main-bower-files](https://github.com/ck86/main-bower-files) - Simplify build process setup by dynamically getting the library files. :star:599
* [autoprefixer](https://github.com/postcss/autoprefixer) - Parse CSS and add vendor prefixes to rules by Can I Use. :star:15184
* [gulp-sourcemaps](https://github.com/floridoo/gulp-sourcemaps) - Provide source map support. :star:947
* [gulp-replace](https://github.com/lazd/gulp-replace) - A string replace plugin for gulp. :star:399
* [gulp-rename](https://github.com/hparra/gulp-rename) - Rename files easily. :star:595
* [gulp-rev](https://github.com/sindresorhus/gulp-rev) - Static asset revisioning by appending content hash to filenames: unicorn.css → unicorn-d41d8cd98f.css. :star:1413
* [del](https://github.com/sindresorhus/del) - Delete files/folders using globs. :star:803
* [gulp-exec](https://github.com/robrich/gulp-exec) - Run a shell command. :star:130
* [gulp-strip-debug](https://github.com/sindresorhus/gulp-strip-debug) - Strip console, alert, and debugger statements from JavaScript code. :star:218
* [gulp-cssimport](https://github.com/unlight/gulp-cssimport) - Parses a CSS file, finds imports, grabs the content of the linked file and replaces the import statement with it. :star:26
* [gulp-inline-css](https://github.com/jonkemp/gulp-inline-css) - Inline your CSS properties into the style attribute in an HTML file. :star:242
* [gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) - Publish contents to Github pages. :star:592
* [gulp-ng-annotate](https://github.com/Kagami/gulp-ng-annotate) - Add AngularJS dependency injection annotations with [ng-annotate](https://github.com/olov/ng-annotate). :star:275
* [gulp-bump](https://github.com/stevelacy/gulp-bump) - Bump any semver JSON version. :star:246
* [gulp-file-include](https://github.com/coderhaoxin/gulp-file-include) - Include files with gulp. :star:499
* [gulp-zip](https://github.com/sindresorhus/gulp-zip) - ZIP compress files. :star:225
* [gulp-git](https://github.com/stevelacy/gulp-git) - Run Git commands with gulp. :star:380
* [gulp-filter](https://github.com/sindresorhus/gulp-filter) - Filter files in a vinyl stream using globbing. :star:284
* [gulp-preprocess](https://github.com/jas/gulp-preprocess) - Preprocess files based on custom context or environment configuration.
* [gulp-eval] (https://github.com/gulp-bem/gulp-eval) - Eval JS-expression or require CommonJS modules and JSON files.

## Scaffolding
### Boilerplates
* [web-starter-kit](https://github.com/google/web-starter-kit) - Google Web Starter Kit. :star:18174
* [gulp-plugin-boilerplate](https://github.com/sindresorhus/gulp-plugin-boilerplate) - Boilerplate to kickstart creating gulp plugins. :star:68
* [polymer-starter-kit](https://github.com/polymerelements/polymer-starter-kit) - A starting point for Polymer 1.0 apps. :star:2476
* [este](https://github.com/este/este) - The most complete React/Flux dev stack and starter kit for isomorphic functional web apps. :star:5414
* [mnml](https://github.com/mrmrs/mnml) - Minimal boilerplate to start a responsive HTML5/Sass project. :star:725
* [kraken](https://github.com/cferdinandi/kraken) - A lightweight, mobile-first boilerplate for front-end web developers. :star:674
* [angularjs-gulp-browserify-boilerplate](https://github.com/jakemmarsh/angularjs-gulp-browserify-boilerplate) - Boilerplate using AngularJS, Sass, gulp, and Browserify. :star:1076
* [hapi-ninja](https://github.com/poeticninja/hapi-ninja) - A Node.js, Hapi, and Swig boilerplate. :star:394
* [laravel-5-boilerplate](https://github.com/rappasoft/laravel-5-boilerplate) - A Laravel 5 boilerplate project. :star:2865
* [react-starterkit](https://github.com/wbkd/react-starterkit) - React starter kit that contains react-router, Reflux, jest, webpack, gulp and Stylus. :star:357

### Yeoman Generators
* [generator-gulp-webapp](https://github.com/yeoman/generator-gulp-webapp) - A gulp generator for modern webapps. :star:3483
* [generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) - Yeoman generator for AngularJS with gulp. :star:3889
* [generator-react-gulp-browserify](https://github.com/randylien/generator-react-gulp-browserify) - A Yeoman Generator for React library. It includes gulp, Browserify, Browsersync and Bootstrap. :star:425
* [generator-node-gulp](https://github.com/youngmountain/generator-node-gulp) - A Node.js module generator including gulp and Mocha. :star:37
* [generator-gulp-bootstrap](https://github.com/niallobrien/generator-gulp-bootstrap) - Yeoman generator for Bootstrap, gulp & libsass. :star:71
* [generator-angulpify](https://github.com/jgoux/generator-angulpify) - Yeoman generator involving AngularJS, gulp and Browserify. :star:147
* [generator-ionic-gulp](https://github.com/tmaximini/generator-ionic-gulp) - A Yeoman generator for Ionic Projects with gulp. :star:140
* [generator-gulp-plugin-boilerplate](https://github.com/sindresorhus/generator-gulp-plugin-boilerplate) - Scaffold out a [gulp plugin boilerplate](https://github.com/sindresorhus/gulp-plugin-boilerplate). :star:47
* [generator-jekyllized](https://github.com/sondr3/generator-jekyllized) - Jekyll workflow with gulp, Sass, AutoPrefixer, asset optimization and cache busting and much more. :star:340

## Miscellaneous
* [elixir](https://github.com/laravel/elixir) - A clean, fluent API for defining basic gulp tasks for your Laravel applications. :star:1096
* [gulp-app](https://github.com/sindresorhus/gulp-app) - Gulp as an app (OS X). :star:976
* [lmn-gulp-tasks](https://github.com/Lostmyname/lmn-gulp-tasks) - Example of gulp tasks unit testing. :star:22
* [gulp-chef](http://gulp-cookery.github.io/gulp-chef/) - An elegant, intuitive way to reuse gulp tasks.

## License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Philipp Alferov](https://github.com/alferov) has waived all copyright and related or neighboring rights to this work.


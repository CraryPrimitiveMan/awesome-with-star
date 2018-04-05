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
* [Github Repository](https://github.com/gulpjs/gulp) :star:29118
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
* [Gulp Cheatsheet](https://github.com/osscafe/gulp-cheatsheet) :star:1385
* [Playground for Gulp Recipes](https://github.com/johnpapa/gulp-patterns) :star:522

## Plugins
### Compilation
* [gulp-sass](https://github.com/dlmanning/gulp-sass) - Sass → CSS with [libsass](https://github.com/sass/libsass). :star:1265
* [gulp-ruby-sass](https://github.com/sindresorhus/gulp-ruby-sass) - Sass → CSS with Ruby Sass. :star:489
* [gulp-compass](https://github.com/appleboy/gulp-compass) - Sass → CSS with Ruby Sass & Compass. :star:178
* [gulp-less](https://github.com/plus3network/gulp-less) - [Less](https://github.com/less/less.js) → CSS. :star:551
* [gulp-stylus](https://github.com/stevelacy/gulp-stylus) - [Stylus](https://github.com/stylus/stylus) → CSS. :star:216
* [gulp-postcss](https://github.com/postcss/gulp-postcss) - Pipe CSS through [PostCSS](https://github.com/postcss/postcss) processors with a single parse. :star:579
* [gulp-coffee](https://github.com/contra/gulp-coffee) - [Coffeescript](https://github.com/jashkenas/coffeescript) → JavaScript. :star:222
* [gulp-typescript](https://github.com/ivogabe/gulp-typescript) - [TypeScript](https://github.com/Microsoft/TypeScript) → JavaScript. :star:621
* [gulp-react](https://github.com/sindresorhus/gulp-react) - Facebook [React](https://github.com/facebook/react) JSX templates → JavaScript. :star:244
* [webpack-stream](https://github.com/shama/webpack-stream) - Run [webpack](https://github.com/webpack/webpack) as a stream to conveniently integrate with gulp. :star:1104

### Transpilation
* [gulp-babel](https://github.com/babel/gulp-babel) - ES6 → ES5 with [babel](https://github.com/babel/babel). :star:1070
* [gulp-traceur](https://github.com/sindresorhus/gulp-traceur) - ES6 → ES5 using [Traceur](https://github.com/google/traceur-compiler). :star:179
* [gulp-regenerator](https://github.com/sindresorhus/gulp-regenerator) - ES6 → ES5 with [Regenerator](https://github.com/facebook/regenerator). :star:19
* [gulp-es6-transpiler](https://github.com/sindresorhus/gulp-es6-transpiler) - [:no_entry:] ES6 → ES5 with [es6-transpiler](https://github.com/termi/es6-transpiler). :star:49
* [gulp-myth](https://github.com/sindresorhus/gulp-myth) - [Myth](https://github.com/segmentio/myth) - a polyfill for future versions of the CSS spec. :star:4418
* [gulp-cssnext](https://github.com/MoOx/gulp-cssnext) - [:no_entry:] Use tomorrow's CSS syntax, today, using [cssnext](https://github.com/MoOx/postcss-cssnext). :star:54

### Concatenation
* [gulp-concat](https://github.com/contra/gulp-concat) - Concatenate files. :star:714

### Minification
* [gulp-clean-css](https://github.com/scniro/gulp-clean-css) - Minify CSS with [clean-css](https://github.com/jakubpawlowicz/clean-css). :star:496
* [gulp-csso](https://github.com/ben-eb/gulp-csso) - Minify CSS with [CSSO](https://github.com/css/csso). :star:218
* [gulp-uglify](https://github.com/terinjokes/gulp-uglify) - Minify JavaScript with [UglifyJS2](https://github.com/mishoo/UglifyJS2). :star:1094
* [gulp-htmlmin](https://github.com/jonschlinkert/gulp-htmlmin) - Minify HTML with [html-minifier](https://github.com/kangax/html-minifier). :star:578
* [gulp-imagemin](https://github.com/sindresorhus/gulp-imagemin) - Minify PNG, JPEG, GIF and SVG images with [imagemin](https://github.com/imagemin/imagemin). :star:1475
* [gulp-svgmin](https://github.com/ben-eb/gulp-svgmin) - Minify SVG files with gulp. :star:311

### Optimization
* [gulp-uncss](https://github.com/ben-eb/gulp-uncss) - Remove unused CSS selectors with [UnCSS](https://github.com/giakki/uncss). :star:981
* [gulp-css-base64](https://github.com/zckrs/gulp-css-base64) - Transform all resources found (those within a url() declaration) in CSS files into base64-encoded data URI strings. :star:60
* [gulp-svg2png](https://github.com/akoenig/gulp-svg2png) - Convert SVGs to PNGs. :star:52
* [gulp-responsive](https://github.com/mahnunchik/gulp-responsive) - Generate images at different sizes. :star:416
* [gulp-svgstore](https://github.com/w0rm/gulp-svgstore) - Combine svg files into one with <symbol> elements. :star:592
* [gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) - Create icon fonts from several SVG icons. :star:712

### Injecting Assets
* [gulp-useref](https://github.com/jonkemp/gulp-useref) - Parse build blocks in HTML files to replace references to non-optimized scripts or stylesheets. :star:673
* [gulp-inject](https://github.com/klei/gulp-inject) - Transform each file to a string and inject each transformed string into placeholders in the target stream files. :star:747
* [wiredep](https://github.com/taptapship/wiredep) - Wire Bower dependencies to your source code. :star:1189

### Templating
* [gulp-angular-templatecache](https://github.com/miickel/gulp-angular-templatecache) - Concatenate and register AngularJS templates in the $templateCache. :star:521
* [gulp-jade](https://github.com/phated/gulp-jade) - [Jade](https://github.com/pugjs/jade) → HTML. :star:466
* [gulp-handlebars](https://github.com/lazd/gulp-handlebars) - [Handlebars](https://github.com/wycats/handlebars.js) templates → JavaScript. :star:151
* [gulp-hb](https://github.com/shannonmoeller/gulp-hb) - [Handlebars](https://github.com/wycats/handlebars.js) templates → HTML. :star:128
* [gulp-nunjucks](https://github.com/sindresorhus/gulp-nunjucks) - [Nunjucks](https://github.com/mozilla/nunjucks) templates → JavaScript. :star:106
* [gulp-dustjs](https://github.com/sindresorhus/gulp-dust) - [Dust](https://github.com/linkedin/dustjs) templates → JavaScript. :star:18
* [gulp-riot](https://github.com/e-jigsaw/gulp-riot) - [Riot](https://github.com/riot/riot) templates → JavaScript. :star:107
* [gulp-markdown](https://github.com/sindresorhus/gulp-markdown) - Markdown → HTML. :star:139
* [gulp-template](https://github.com/sindresorhus/gulp-template) - [Lodash ](https://github.com/lodash/lodash) templates → JavaScript. :star:240
* [gulp-swig](https://github.com/colynb/gulp-swig) - [Swig](https://github.com/paularmstrong/swig) templates → HTML. :star:69

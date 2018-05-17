# Information comes from [sindresorhus/awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs)
<div align="center">
	<div>
		<img width="500" src="media/logo.svg" alt="Awesome Node.js">
	</div>
	<br>
	<p>
		<a href="https://www.patreon.com/sindresorhus">My open source work is supported by the community</a>
	</p>
	<p>
		<sup>Special thanks to:</sup>
		<br>
		<a href="https://github.com/wtgtybhertgeghgtwtg">
			<img src="https://cdn.rawgit.com/sindresorhus/stuff/daa49fabede538ea8a533d75e7e55f4c81e3a972/sponsors/wtgtybhertgeghgtwtg-logo-light.svg" width="260" alt="wtgtybhertgeghgtwtg">
		</a>
	</p>
	<br>
	<br>
	<a href="https://awesome.re">
		<img src="https://awesome.re/badge.svg" alt="Awesome">
	</a>
	<p>
		<sub>Just type <a href="https://node.cool"><code>node.cool</code></a> to go here. Check out my <a href="https://blog.sindresorhus.com">blog</a> and follow me on <a href="https://twitter.com/sindresorhus">Twitter</a>.</sub>
	</p>
	<br>
</div>


## Contents

- [Packages](#packages)
	- [Mad science](#mad-science)
	- [Command-line apps](#command-line-apps)
	- [Functional programming](#functional-programming)
	- [HTTP](#http)
	- [Debugging / Profiling](#debugging--profiling)
	- [Logging](#logging)
	- [Command-line utilities](#command-line-utilities)
	- [Build tools](#build-tools)
	- [Hardware](#hardware)
	- [Templating](#templating)
	- [Web frameworks](#web-frameworks)
	- [Documentation](#documentation)
	- [Filesystem](#filesystem)
	- [Control flow](#control-flow)
	- [Streams](#streams)
	- [Real-time](#real-time)
	- [Image](#image)
	- [Text](#text)
	- [Number](#number)
	- [Math](#math)
	- [Date](#date)
	- [URL](#url)
	- [Data validation](#data-validation)
	- [Parsing](#parsing)
	- [Humanize](#humanize)
	- [Compression](#compression)
	- [Network](#network)
	- [Database](#database)
	- [Testing](#testing)
	- [Security](#security)
	- [Benchmarking](#benchmarking)
	- [Minifiers](#minifiers)
	- [Authentication](#authentication)
	- [Authorization](#authorization)
	- [Email](#email)
	- [Job queues](#job-queues)
	- [Node.js management](#nodejs-management)
	- [Natural language processing](#natural-language-processing)
	- [Process management](#process-management)
	- [Automation](#automation)
	- [AST](#ast)
	- [Static site generators](#static-site-generators)
	- [Content management systems](#content-management-systems)
	- [Forum](#forum)
	- [Blogging](#blogging)
	- [Weird](#weird)
	- [Serialization](#serialization)
	- [Miscellaneous](#miscellaneous)
- [Resources](#resources)
	- [Tutorials](#tutorials)
	- [Discovery](#discovery)
	- [Articles](#articles)
	- [Newsletters](#newsletters)
	- [Videos](#videos)
	- [Podcasts](#podcasts)
	- [Books](#books)
	- [Blogs](#blogs)
	- [Courses](#courses)
	- [Cheatsheets](#cheatsheets)
	- [Tools](#tools)
	- [Community](#community)
	- [Miscellaneous](#miscellaneous)


## Packages

### Mad science

- [webtorrent](https://github.com/feross/webtorrent) - Streaming torrent client for Node.js and the browser. :star:16694
- [peerflix](https://github.com/mafintosh/peerflix) - Streaming torrent client. :star:4759
- [dat](http://dat-data.com) - Real-time replication and versioning for data sets.
- [ipfs](https://github.com/ipfs/js-ipfs) - Distributed file system that seeks to connect all computing devices with the same system of files. :star:2322
- [stackgl](http://stack.gl) - Open software ecosystem for WebGL, built on top of browserify and npm.
- [peerwiki](https://github.com/mafintosh/peerwiki) - All of Wikipedia on BitTorrent. :star:277
- [peercast](https://github.com/mafintosh/peercast) - Stream a torrent video to Chromecast. :star:375
- [BitcoinJS](https://github.com/bitcoinjs/bitcoinjs-lib) - Clean, readable, proven Bitcoin library. :star:2692
- [Bitcore](https://github.com/bitpay/bitcore) - Pure and powerful Bitcoin library. :star:2744
- [PDFKit](https://github.com/devongovett/pdfkit) - PDF generation library. :star:3931
- [turf](https://github.com/Turfjs/turf) - Modular geospatial processing and analysis engine. :star:3591
- [webcat](https://github.com/mafintosh/webcat) - p2p pipe across the web using WebRTC that uses your GitHub private/public key for authentication. :star:368
- [NodeOS](https://github.com/NodeOS/NodeOS) - The first operating system powered by npm. :star:5359
- [limdu](https://github.com/erelsgl/limdu) - Machine-learning framework. :star:886
- [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) - Graph theory (a.k.a. network) modeling and analysis. :star:4275
- [Kadence](https://kadence.github.io/) - Kademlia distributed hash table.
- [seedshot](https://github.com/twobucks/seedshot) - Temporary P2P screenshot sharing from your browser. :star:174
- [js-git](https://github.com/creationix/js-git) - JavaScript implementation of Git. :star:3348
- [skale](https://github.com/skale-me/skale-engine) - High performance distributed data processing engine. :star:260
- [xlsx](https://github.com/sheetjs/js-xlsx) - Pure JS Excel spreadsheet reader and writer. :star:10375
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - Pure JavaScript implementation of Git. :star:1003


### Command-line apps

- [np](https://github.com/sindresorhus/np) - Better `npm publish`. :star:3161
- [npm-name](https://github.com/sindresorhus/npm-name) - Check whether a package name is available on npm. :star:73
- [gh-home](https://github.com/sindresorhus/gh-home) - Open the GitHub page of the repo in the current directory. :star:94
- [npm-home](https://github.com/sindresorhus/npm-home) - Open the npm page of a package. :star:134
- [trash](https://github.com/sindresorhus/trash) - Safer alternative to `rm`. :star:1537
- [speed-test](https://github.com/sindresorhus/speed-test) - Test your internet connection speed and ping. :star:2962
- [emoj](https://github.com/sindresorhus/emoj) - Find relevant emoji from text on the command-line. :star:1493
- [pageres](https://github.com/sindresorhus/pageres) - Capture website screenshots. :star:8328
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:169
- [vtop](https://github.com/MrRio/vtop) - More better top, with nice charts. :star:2747
- [empty-trash](https://github.com/sindresorhus/empty-trash) - Empty the trash. :star:84
- [is-up](https://github.com/sindresorhus/is-up) - Check whether a website is up or down. :star:275
- [is-online](https://github.com/sindresorhus/is-online) - Check if the internet connection is up. :star:391
- [public-ip](https://github.com/sindresorhus/public-ip) - Get your public IP address. :star:301
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - Copy & paste on the terminal. :star:131
- [XO](https://github.com/xojs/xo) - Enforce strict code style using the JavaScript happiness style. :star:3745
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style — One style to rule them all. :star:17795
- [ESLint](http://eslint.org) - The pluggable linting utility for JavaScript.
- [dev-time](https://github.com/samverschueren/dev-time-cli) - Get the current local time of a GitHub user. :star:152
- [David](https://github.com/alanshaw/david) - Tells you when your package npm dependencies are out of date. :star:810
- [http-server](https://github.com/indexzero/http-server) - Simple, zero-config command-line HTTP server. :star:6829
- [Live Server](https://github.com/tapio/live-server) - Development HTTP-server with livereload capability. :star:2129
- [bcat](https://github.com/kessler/node-bcat) - Pipe command output to web browsers. :star:266
- [normit](https://github.com/pawurb/normit) - Google Translate with speech synthesis in your terminal. :star:194
- [fkill](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform. :star:5067
- [pjs](https://github.com/danielstjules/pjs) - Pipeable JavaScript. Quickly filter, map, and reduce from the terminal. :star:332
- [license-checker](https://github.com/davglass/license-checker) - Check licenses of your app's dependencies. :star:617
- [browser-run](https://github.com/juliangruber/browser-run) - Easily run code in a browser environment. :star:311
- [tmpin](https://github.com/sindresorhus/tmpin) - Adds stdin support to any CLI app that accepts file input. :star:107
- [wifi-password](https://github.com/kevva/wifi-password-cli) - Get the current wifi password. :star:124
- [wallpaper](https://github.com/sindresorhus/wallpaper) - Change the desktop wallpaper. :star:486
- [brightness](https://github.com/kevva/brightness-cli) - Change the screen brightness. :star:120
- [torrent](https://github.com/maxogden/torrent) - Download torrents. :star:512
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - Kill all Chrome tabs to improve performance, decrease battery usage, and save memory. :star:225
- [alex](https://github.com/wooorm/alex) - Catch insensitive, inconsiderate writing. :star:2255
- [pen](https://github.com/noraesae/pen) - Live Markdown preview in the browser from your favorite editor. :star:214
- [subdownloader](https://github.com/beatfreaker/subdownloader) - Subtitle downloader for movies and TV series. :star:89
- [dark-mode](https://github.com/sindresorhus/dark-mode) - Toggle the macOS Dark Mode. :star:320
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP location finder. :star:163
- [Jsome](https://github.com/Javascipt/Jsome) - Pretty prints JSON with configurable colors and indentation. :star:114
- [itunes-remote](https://github.com/mischah/itunes-remote) - Interactively control iTunes. :star:317
- [mobicon](https://github.com/samverschueren/mobicon-cli) - Mobile app icon generator. :star:44
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - Mobile app splash screen generator. :star:23
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - Pretty git diff to HTML generator. :star:132
- [Cash](https://github.com/dthree/cash) - Cross-platform Unix shell commands in pure JavaScript. :star:7503
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - Try out npm packages in the terminal. :star:1003
- [jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for source code. :star:732
- [atmo](https://github.com/Raathigesh/Atmo) - Server-side API mocking. :star:684
- [auto-install](https://github.com/siddharthkp/auto-install) - Auto installs dependencies as you code. :star:845
- [lessmd](https://github.com/linuxenko/lessmd) - Markdown in the terminal. :star:83
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - Find out which dependencies are slowing you down. :star:2131
- [localtunnel](https://github.com/localtunnel/localtunnel) - Expose your localhost to the world. :star:6795
- [svg-term-cli](https://github.com/marionebl/svg-term-cli) - Share terminal sessions via SVG. :star:543
- [gtop](https://github.com/aksakalli/gtop) - System monitoring dashboard for the terminal. :star:6759
- [themer](https://github.com/mjswensen/themer) - Generate themes for your editor, terminal, wallpaper, Slack, and more. :star:1590


### Functional programming

- [lodash](https://lodash.com) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections. :star:23645
- [Ramda](https://github.com/ramda/ramda) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data. :star:12041
- [Folktale](http://folktale.origamitower.com) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse.
- [Mout](https://github.com/mout/mout) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead. :star:789
- [Bacon.js](http://baconjs.github.io) - Functional reactive programming.
- [RxJS](http://reactivex.io) - Functional reactive library for transforming, composing, and querying various kinds of data.
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases. :star:4683
- [Kefir.js](https://github.com/kefirjs/kefir) - Reactive library with focus on high performance and low memory usage. :star:1430


### HTTP

- [got](https://github.com/sindresorhus/got) - Nicer interface to the built-in `http` module. :star:2628
- [gh-got](https://github.com/sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API. :star:110
- [axios](https://github.com/mzabriskie/axios) - Promise based HTTP client (works in the browser too). :star:41537
- [request](https://github.com/request/request) - Simplified HTTP request client. :star:19522
- [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities. :star:312
- [download](https://github.com/kevva/download) - Download and extract files effortlessly. :star:679
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP proxy. :star:8708
- [superagent](https://github.com/visionmedia/superagent) - HTTP request library. :star:12748
- [node-fetch](https://github.com/bitinn/node-fetch) - `window.fetch` for Node.js. :star:2988
- [flashheart](https://github.com/bbc/flashheart) - REST client. :star:84
- [http-fake-backend](https://github.com/micromata/http-fake-backend) - Build a fake backend by providing the content of JSON files or JavaScript objects through configurable routes. :star:141
- [cacheable-request](https://github.com/lukechilds/cacheable-request) - Wrap native HTTP requests with RFC compliant cache support. :star:96
- [gotql](https://github.com/khaosdoctor/gotql) - GraphQL request library built on [got](https://github.com/sindresorhus/got). :star:146


### Debugging / Profiling

- [ironNode](https://github.com/s-a/iron-node) - Node.js debugger supporting ES2015 out of the box. :star:2369
- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools. :star:12127
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility. :star:6123
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - Node.js is running but you don't know why? :star:719
- [njsTrace](https://github.com/valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function. :star:212
- [vstream](https://github.com/joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams. :star:53
- [stackman](https://github.com/watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies. :star:163
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables. :star:243
- [0x](https://github.com/davidmarkclements/0x) - Flamegraph profiling. :star:958
- [ctrace](https://github.com/automation-stack/ctrace) - Well-formatted and improved trace system calls and signals. :star:95
- [leakage](https://github.com/andywer/leakage) - Write memory leak tests. :star:1240


### Logging

- [pino](https://github.com/pinojs/pino) - Extremely fast logger inspired by Bunyan. :star:2653
- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library. :star:10255
- [console-log-level](https://github.com/watson/console-log-level) - The most simple logger imaginable with support for log levels and custom prefixes. :star:24
- [storyboard](https://github.com/guigrpa/storyboard) - End-to-end, hierarchical, real-time, colorful logs and stories. :star:452


### Command-line utilities

- [chalk](https://github.com/chalk/chalk) - Terminal string styling done right. :star:8917
- [meow](https://github.com/sindresorhus/meow) - CLI app helper. :star:1286
- [yargs](https://github.com/yargs/yargs) - Command-line parser that automatically generates an elegant user-interface. :star:4525
- [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner. :star:2900
- [get-stdin](https://github.com/sindresorhus/get-stdin) - Easier stdin. :star:162
- [log-update](https://github.com/sindresorhus/log-update) - Log by overwriting the previous output in the terminal. Useful for rendering progress bars, animations, etc. :star:465
- [Ink](https://github.com/vadimdemedes/ink) - React for interactive command-line apps. :star:5862
- [listr](https://github.com/samverschueren/listr) - Terminal task list. :star:1450
- [conf](https://github.com/sindresorhus/conf) - Simple config handling for your app or module. :star:265
- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - ANSI escape codes for manipulating the terminal. :star:190
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels. :star:317
- [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows CMD fallbacks. :star:238
- [boxen](https://github.com/sindresorhus/boxen) - Create boxes in the terminal. :star:342
- [terminal-link](https://github.com/sindresorhus/terminal-link) - Create clickable links in the terminal. :star:101
- [terminal-image](https://github.com/sindresorhus/terminal-image) - Display images in the terminal. :star:207
- [string-width](https://github.com/sindresorhus/string-width) - Get the visual width of a string - the number of columns required to display it. :star:93
- [cli-truncate](https://github.com/sindresorhus/cli-truncate) - Truncate a string to a specific width in the terminal. :star:30
- [first-run](https://github.com/sindresorhus/first-run) - Check if it's the first time the process is run. :star:53
- [vorpal](https://github.com/dthree/vorpal) - Interactive CLI apps. :star:4623
- [blessed](https://github.com/chjj/blessed) - Curses-like library. :star:7401
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt. :star:7018
- [yn](https://github.com/sindresorhus/yn) - Parse yes/no like values. :star:105
- [cli-table](https://github.com/Automattic/cli-table) - Pretty unicode tables. :star:1566
- [drawille](https://github.com/madbence/node-drawille) - Draw on the terminal with unicode braille characters. :star:732
- [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app. :star:963
- [ascii-charts](https://github.com/jstrace/chart) - ASCII bar chart in the terminal. :star:220
- [progress](https://github.com/tj/node-progress) - Flexible ascii progress bar. :star:1828
- [insight](https://github.com/yeoman/insight) - Helps you understand how your tool is being used by anonymously reporting usage metrics to Google Analytics. :star:416
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - Toggle the CLI cursor. :star:41
- [columnify](https://github.com/timoxley/columnify) - Create text-based columns suitable for console output. Supports cell wrapping. :star:297
- [cli-columns](https://github.com/shannonmoeller/cli-columns) - Columnated unicode and ansi-safe text lists. :star:11
- [cfonts](https://github.com/dominikwilkowski/cfonts) - Sexy ASCII fonts for the console. :star:296
- [multispinner](https://github.com/codekirei/node-multispinner) - Multiple, simultaneous, individually controllable CLI spinners. :star:208
- [omelette](https://github.com/f/omelette) - Shell autocompletion helper. :star:705
- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform. :star:2539
- [shelljs](https://github.com/shelljs/shelljs) - Portable Unix shell commands. :star:7828
- [sudo-block](https://github.com/sindresorhus/sudo-block) - Block users from running your app with root permissions. :star:62
- [loud-rejection](https://github.com/sindresorhus/loud-rejection) - Make unhandled promise rejections fail loudly instead of the default silent fail. :star:208
- [sparkly](https://github.com/sindresorhus/sparkly) - Generate sparklines ▁▂▃▅▂▇ :star:269
- [Bit](https://github.com/teambit/bit) - Create, maintain, find and use small modules and components across repositories. :star:1795
- [gradient-string](https://github.com/bokub/gradient-string) - Beautiful color gradients in terminal output. :star:284
- [oclif](https://github.com/oclif/oclif) - CLI framework complete with parser, automatic documentation, testing, and plugins. :star:1902
- [term-size](https://github.com/sindresorhus/term-size) - Reliably get the terminal window size. :star:70


### Build tools

- [parcel](https://github.com/parcel-bundler/parcel) - Blazing fast, zero config web app bundler. :star:22270
- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser. :star:40848
- [rollup](https://github.com/rollup/rollup) - Next-generation ES2015 module bundler. :star:12680
- [gulp](http://gulpjs.com) - Streaming and fast build system that favors code over config.
- [Broccoli](https://github.com/broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions. :star:3109
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow. :star:6450
- [Start](https://github.com/deepsweet/start) - Functional task runner with shareable presets. :star:273
- [ygor](https://github.com/shannonmoeller/ygor) - Promising task runner for when `npm run` isn't enough and everything else is too much. :star:52
- [FuseBox](https://github.com/fuse-box/fuse-box) - Fast build system that combines the power of webpack, JSPM and SystemJS, with first-class TypeScript support. :star:3334
- [pkg](https://github.com/zeit/pkg) - Package your Node.js project into an executable. :star:9863


### Hardware

- [johnny-five](https://github.com/rwaldron/johnny-five) - Firmata based Arduino Framework. :star:9017
- [serialport](https://github.com/voodootikigod/node-serialport) - Access serial ports for reading and writing. :star:3354
- [usb](https://github.com/nonolith/node-usb) - USB library. :star:657
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C serial bus access. :star:118
- [onoff](https://github.com/fivdi/onoff) - GPIO access and interrupt detection. :star:659
- [spi-device](https://github.com/fivdi/spi-device) - SPI serial bus access. :star:37
- [pigpio](https://github.com/fivdi/pigpio) - Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi. :star:304
- [gps](https://github.com/infusion/GPS.js) - NMEA parser for handling GPS receivers. :star:55


### Templating

- [marko](https://github.com/marko-js/marko) - HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags. :star:6230
- [nunjucks](https://github.com/mozilla/nunjucks) - Templating engine with inheritance, asynchronous control, and more (jinja2 inspired). :star:5245
- [handlebars.js](https://github.com/wycats/handlebars.js) - Superset of Mustache templates which adds powerful features like helpers and more advanced blocks. :star:13322
- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language. :star:2426
- [Pug](https://github.com/pugjs/pug) - High-performance template engine heavily influenced by Haml. :star:16628


### Web frameworks

- [Hapi](http://hapijs.com) - Framework for building applications and services.
- [Koa](http://koajs.com) - Framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [Express](http://expressjs.com) - Web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [Feathers](http://feathersjs.com) - Microservice framework built in the spirit of Express.
- [LoopBack](http://loopback.io) - Powerful framework for creating REST APIs and easily connecting to backend data sources.
- [Meteor](https://www.meteor.com) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [Restify](http://restify.com) - Enables you to build correct REST web services.
- [ThinkJS](https://github.com/thinkjs/thinkjs) - Framework with ES2015+ support, WebSockets, REST API. :star:4273
- [ActionHero](https://github.com/actionhero/actionhero) - Framework for making reusable & scalable APIs for TCP sockets, WebSockets, and HTTP clients. :star:1834
- [MERN](http://mern.io) - Easily build production-ready universal apps with MongoDB, Express, React, and webpack.
- [Next.js](https://github.com/zeit/next.js) - Minimalistic framework for server-rendered universal JavaScript web apps. :star:25262
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Minimalistic framework for server-rendered Vue.js apps. :star:12289
- [seneca](https://github.com/senecajs/seneca) - Toolkit for writing microservices. :star:2916
- [AdonisJs](http://adonisjs.com) - A true MVC framework for Node.js built on solid foundations of Dependency Injection and IoC container.
- [Hemera](https://github.com/hemerajs/hemera) - Write reliable and fault-tolerant microservices with [NATS](https://nats.io). :star:508
- [Micro](https://github.com/zeit/micro) - Minimalistic microservice framework with an async approach. :star:6586
- [Moleculer](https://moleculer.services) - Fast & powerful microservices framework.
- [Fastify](https://github.com/fastify/fastify) - Fast and low overhead web framework. :star:7020
- [Nest](https://github.com/nestjs/nest) - Angular-inspired framework for building efficient and scalable server-side apps. :star:5868


### Documentation

- [documentation.js](https://github.com/documentationjs/documentation) - API documentation generator with support for ES2015+ and flow annotation. :star:3750
- [ESDoc](https://github.com/esdoc/esdoc) - Documentation generator targeting ES2015, attaching test code and measuring documentation coverage. :star:2012
- [Docco](http://jashkenas.github.io/docco/) - Documentation generator which produces an HTML document that displays your comments intermingled with your code.
- [JSDoc](http://usejsdoc.org) - API documentation generator similar to JavaDoc or PHPDoc.


### Filesystem

- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs. :star:812
- [globby](https://github.com/sindresorhus/globby) - Glob files with support for multiple patterns. :star:640
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:169
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like `rm -rf`. :star:2446
- [make-dir](https://github.com/sindresorhus/make-dir) - Recursively create directories like `mkdir -p`. :star:270
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Drop-in replacement for the `fs` module with various improvements. :star:736
- [chokidar](https://github.com/paulmillr/chokidar) - Filesystem watcher which stabilizes events from `fs.watch` and `fs.watchFile` as well as using native `fsevents` on macOS. :star:4093
- [find-up](https://github.com/sindresorhus/find-up) - Find a file by walking up parent directories. :star:143
- [proper-lockfile](https://github.com/IndigoUnited/node-proper-lockfile) - Inter-process and inter-machine lockfile utility. :star:46
- [load-json-file](https://github.com/sindresorhus/load-json-file) - Read and parse a JSON file. :star:98
- [write-json-file](https://github.com/sindresorhus/write-json-file) - Stringify and write JSON to a file atomically. :star:85
- [fs-write-stream-atomic](https://github.com/npm/fs-write-stream-atomic) - Like `fs.createWriteStream()`, but atomic. :star:41
- [filenamify](https://github.com/sindresorhus/filenamify) - Convert a string to a valid filename. :star:158
- [lnfs](https://github.com/kevva/lnfs) - Force create symlinks like `ln -fs`. :star:9
- [istextorbinary](https://github.com/bevry/istextorbinary) - Check if a file is text or binary. :star:42
- [fs-jetpack](https://github.com/szwacz/fs-jetpack) - Completely redesigned file system API for convenience in everyday use. :star:386
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module. :star:4142
- [pkg-dir](https://github.com/sindresorhus/pkg-dir) - Find the root directory of an npm package. :star:66
- [filehound](https://github.com/nspragg/filehound) - Flexible and fluent interface for searching the file system. :star:115


### Control flow

- Promises
	- [Bluebird](https://github.com/petkaantonov/bluebird) - Promise library with focus on innovative features and performance. :star:16785
	- [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function. :star:938
	- [delay](https://github.com/sindresorhus/delay) - Delay a promise a specified amount of time. :star:223
	- [promise-memoize](https://github.com/nodeca/promise-memoize) - Memoize promise-returning functions, with expire and prefetch. :star:27
	- [valvelet](https://github.com/lpinca/valvelet) - Limit the execution rate of a promise-returning function. :star:14
	- [p-map](https://github.com/sindresorhus/p-map) - Map over promises concurrently. :star:261
	- [More…](https://github.com/sindresorhus/promise-fun) :star:1678
- Observables
	- [zen-observable](https://github.com/zenparsing/zen-observable) - Implementation of Observables. :star:376
	- [RxJS](https://github.com/ReactiveX/RxJS) - Reactive programming. :star:12480
	- [observable-to-promise](https://github.com/sindresorhus/awesome-observables) - Convert an Observable to a Promise. :star:221
	- [More…](https://github.com/sindresorhus/awesome-observables) :star:221
- Streams
	- [Highland.js](https://github.com/caolan/highland) - Manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams. :star:2939
- Callbacks
	- [each-async](https://github.com/sindresorhus/each-async) - Async concurrent iterator like forEach. :star:101
	- [async](https://github.com/caolan/async) - Provides straight-forward, powerful functions for working with asynchronicity. :star:23949
- Channels
	- [js-csp](https://github.com/ubolonton/js-csp) - Communicating sequential processes for JavaScript (like Clojurescript core.async, or Go). :star:2100


### Streams

- [through2](https://github.com/rvagg/through2) - Tiny wrapper around streams2 Transform to avoid explicit subclassing noise. :star:1354
- [from2](https://github.com/hughsk/from2) - Convenience wrapper for ReadableStream, inspired by `through2`. :star:94
- [get-stream](https://github.com/sindresorhus/get-stream) - Get a stream as a string or buffer. :star:109
- [into-stream](https://github.com/sindresorhus/into-stream) - Convert a buffer/string/array/object into a stream. :star:64
- [duplexify](https://github.com/mafintosh/duplexify) - Turn a writeable and readable stream into a single streams2 duplex stream. :star:129
- [pumpify](https://github.com/mafintosh/pumpify) - Combine an array of streams into a single duplex stream. :star:133
- [peek-stream](https://github.com/mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it. :star:40
- [binary-split](https://github.com/maxogden/binary-split) - Newline (or any delimiter) splitter stream. :star:58
- [byline](https://github.com/jahewson/node-byline) - Super-simple line-by-line Stream reader. :star:254
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - Transform the first chunk in a stream. :star:18
- [pad-stream](https://github.com/sindresorhus/pad-stream) - Pad each line in a stream. :star:5
- [multistream](https://github.com/feross/multistream) - Combine multiple streams into a single stream. :star:138
- [stream-combiner2](https://github.com/substack/stream-combiner2) - Turn a pipeline into a single stream. :star:69
- [readable-stream](https://github.com/nodejs/readable-stream) - Mirror of Streams2 and Streams3 implementations in core. :star:615
- [through2-concurrent](https://github.com/almost/through2-concurrent) - Transform object streams concurrently. :star:57


### Real-time

- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - Highly scalable WebSocket server & client library. :star:9015
- [Socket.io](https://github.com/socketio/socket.io) - Enables real-time bidirectional event-based communication. :star:41451
- [Faye](https://github.com/faye/faye) - Real-time client-server message bus, based on Bayeux protocol. :star:4066
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores. :star:4685
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in. :star:3570
- [deepstream.io](https://github.com/deepstreamIO/deepstream.io-client-js) - Scalable real-time microservice framework. :star:205
- [Kalm](https://github.com/kalm/kalm.js) - Low-level socket router and middleware framework. :star:51
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - Client for MQTT - Pub-sub based messaging protocol for use on top of TCP/IP. :star:3216


### Image

- [sharp](https://github.com/lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images. :star:8258
- [image-type](https://github.com/sindresorhus/image-type) - Detect the image type of a Buffer/Uint8Array. :star:142
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick and ImageMagick wrapper. :star:4952
- [lwip](https://github.com/EyalAr/lwip) - Lightweight image processor which does not require ImageMagick. :star:2082
- [pica](https://github.com/nodeca/pica) - High quality & fast resize (lanczos3) in pure JS. Alternative to canvas drawImage(), when no pixelation allowed. :star:1195
- [jimp](https://github.com/oliver-moran/jimp) - Image processing in pure JavaScript. :star:6174
- [probe-image-size](https://github.com/nodeca/probe-image-size) - Get the size of most image formats without a full download. :star:154


### Text

- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings. :star:1680
- [string-length](https://github.com/sindresorhus/string-length) - Get the real length of a string - by correctly counting astral symbols and ignoring ansi escape codes. :star:56
- [camelcase](https://github.com/sindresorhus/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar. :star:206
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - Escape RegExp special characters. :star:230
- [execall](https://github.com/sindresorhus/execall) - Find multiple RegExp matches in a string. :star:68
- [splice-string](https://github.com/sindresorhus/splice-string) - Remove or replace part of a string like `Array#splice`. :star:13
- [indent-string](https://github.com/sindresorhus/indent-string) - Indent each line in a string. :star:56
- [strip-indent](https://github.com/sindresorhus/strip-indent) - Strip leading whitespace from every line in a string. :star:71
- [detect-indent](https://github.com/sindresorhus/detect-indent) - Detect the indentation of code. :star:109
- [he](https://github.com/mathiasbynens/he) - HTML entity encoder/decoder. :star:1491
- [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage. :star:2033
- [babelfish](https://github.com/nodeca/babelfish) - i18n with very easy syntax for plurals. :star:184
- [matcher](https://github.com/sindresorhus/matcher) - Simple wildcard matching. :star:382
- [unhomoglyph](https://github.com/nodeca/unhomoglyph) - Normalize visually similar unicode characters. :star:11
- [i18next](https://github.com/i18next/i18next) - Internationalization framework. :star:3245


### Number

- [random-int](https://github.com/sindresorhus/random-int) - Generate a random integer. :star:32
- [random-float](https://github.com/sindresorhus/random-float) - Generate a random float. :star:16
- [unique-random](https://github.com/sindresorhus/unique-random) - Generate random numbers that are consecutively unique. :star:51
- [round-to](https://github.com/sindresorhus/round-to) - Round a number to a specific number of decimal places: `1.234` → `1.2`. :star:81


### Math

- [ndarray](https://github.com/scijs/ndarray) - Multidimensional arrays. :star:748
- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library. :star:5796
- [math-clamp](https://github.com/sindresorhus/math-clamp) - Clamp a number. :star:4
- [algebra](https://github.com/fibo/algebra) - Algebraic structures. :star:59
- [multimath](https://github.com/nodeca/multimath) - Core to create fast image math in WebAssembly and JS. :star:24


### Date

- [Luxon](https://github.com/moment/luxon) - Library for working with dates and times. :star:6251
- [date-fns](https://github.com/date-fns/date-fns) - Modern date utility. :star:10205
- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.
- [dateformat](https://github.com/felixge/node-dateformat) - Date formatting. :star:828
- [tz-format](https://github.com/samverschueren/tz-format) - Format a date with timezone: `2015-11-30T10:40:35+01:00`. :star:5
- [cctz](https://github.com/floatdrop/node-cctz) - Fast parsing, formatting, and timezone conversation for dates. :star:51


### URL

- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL. :star:241
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Humanize a URL: http://sindresorhus.com → sindresorhus.com. :star:60
- [url-unshort](https://github.com/nodeca/url-unshort) - Expand shortened URLs. :star:31
- [speakingurl](https://github.com/pid/speakingurl) - Generate a slug from a string with transliteration. :star:934
- [linkify-it](https://github.com/markdown-it/linkify-it) - Link patterns detector with full unicode support. :star:219
- [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for URLs and other strings. :star:366
- [embedza](https://github.com/nodeca/embedza) - Create HTML snippets/embeds from URLs using info from oEmbed, Open Graph, meta tags. :star:33


### Data validation

- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects. :star:7942
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast. :star:813
- [property-validator](https://github.com/nettofarah/property-validator) - Easy property validation for Express. :star:139
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API sanitization and validation. :star:446
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON Schema validator. Supports v5 proposals. :star:3507


### Parsing

- [remark](https://github.com/wooorm/remark) - Markdown processor powered by plugins. :star:1473
- [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser with 100% CommonMark support, extensions and syntax plugins. :star:5343
- [parse5](https://github.com/inikulin/parse5) - Fast full-featured spec compliant HTML parser. :star:1727
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - Strip comments from JSON. :star:354
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - Strip comments from CSS. :star:78
- [parse-json](https://github.com/sindresorhus/parse-json) - Parse JSON with more helpful errors. :star:129
- [URI.js](https://github.com/medialize/URI.js) - URL mutation. :star:5283
- [PostCSS](https://github.com/postcss/postcss) - CSS parser / stringifier. :star:18461
- [JSONStream](https://github.com/dominictarr/JSONStream) - Streaming JSON.parse and stringify. :star:1478
- [neat-csv](https://github.com/sindresorhus/neat-csv) - Fast CSV parser. Callback interface for the above. :star:65
- [csv-parser](https://github.com/mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else. :star:494
- [PEG.js](https://github.com/pegjs/pegjs) - Simple parser generator that produces fast parsers with excellent error reporting. :star:2783
- [x-ray](https://github.com/lapwinglabs/x-ray) - Web scraping utility. :star:4326
- [nearley](https://github.com/Hardmath123/nearley) - Simple, fast, powerful parsing for JavaScript. :star:1823
- [binary-extract](https://github.com/juliangruber/binary-extract) - Extract a value from a buffer of JSON without parsing the whole thing. :star:141
- [Stylecow](https://github.com/stylecow/stylecow) - Parse, manipulate and convert modern CSS to make it compatible with all browsers. Extensible with plugins. :star:125
- [js-yaml](https://github.com/nodeca/js-yaml) - Very fast YAML parser. :star:2971
- [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter. :star:3162
- [Jison](https://github.com/zaach/jison) - Friendly JavaScript parser generator. It shares genes with Bison, Yacc and family. :star:3052
- [google-libphonenumber](https://github.com/seegno/google-libphonenumber) - Parse, format, store and validate phone numbers. :star:483
- [ref](https://github.com/TooTallNate/ref) - Read/write structured binary data in Buffers. :star:277
- [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Read/write Excel XLSX. :star:184
- [Chevrotain](https://github.com/SAP/chevrotain) - Very fast and feature rich parser building toolkit for JavaScript. :star:730
- [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - Validate and parse XML. :star:196


### Humanize

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - Convert bytes to a human readable string: `1337` → `1.34 kB`. :star:361
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`. :star:268
- [ms](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility. :star:1453
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - Errors with less clutter. :star:919
- [read-art](https://github.com/Tjatse/node-readability) - Extract readable content from any page. :star:255


### Compression

- [yazl](https://github.com/thejoshwolfe/yazl) - Zip. :star:146
- [yauzl](https://github.com/thejoshwolfe/yauzl) - Unzip. :star:289
- [Archiver](https://github.com/archiverjs/node-archiver) - Streaming interface for archive generation, supporting ZIP and TAR. :star:1205
- [pako](https://github.com/nodeca/pako) - High speed zlib port to pure js (deflate, inflate, gzip). :star:1625
- [tar-stream](https://github.com/mafintosh/tar-stream) - Streaming tar parser and generator. Also see [tar-fs](https://github.com/mafintosh/tar-fs). :star:205
- [decompress](https://github.com/kevva/decompress) - Decompression module with support for `tar`, `tar.gz` and `zip` files out of the box. :star:215


### Network

- [get-port](https://github.com/sindresorhus/get-port) - Get an available port. :star:229
- [ipify](https://github.com/sindresorhus/ipify) - Get your public IP address. :star:137
- [getmac](https://github.com/bevry/getmac) - Get the computer MAC address. :star:137
- [DHCP](https://github.com/infusion/node-dhcp) - DHCP client and server. :star:108
- [netcat](https://github.com/roccomuso/netcat) - Netcat port in pure JS. :star:184


### Database

- Drivers
	- [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client. Pure JavaScript and native libpq bindings. :star:6100
	- [Redis](https://github.com/luin/ioredis) - Redis client. :star:4137
	- [LevelUP](https://github.com/Level/levelup) - LevelDB. :star:3227
	- [MySQL](https://github.com/mysqljs/mysql) - MySQL client. :star:11976
	- [couchdb-nano](https://github.com/apache/couchdb-nano) - CouchDB client. :star:163
	- [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Aerospike client. :star:147
	- [Couchbase](https://github.com/couchbase/couchnode) - Couchbase client. :star:373
	- [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB driver. :star:6865
- ODM / ORM
	- [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL. :star:14338
	- [Bookshelf](https://github.com/bookshelf/bookshelf) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js. :star:4902
	- [Massive](https://github.com/robconery/massive-js) - PostgreSQL data access tool. :star:2196
	- [Mongoose](https://github.com/Automattic/mongoose) - Elegant MongoDB object modeling. :star:15700
	- [Waterline](https://github.com/balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases. :star:4570
	- [OpenRecord](https://github.com/PhilWaldmann/openrecord) - ORM for PostgreSQL, MySQL, SQLite3 and RESTful datastores. Similar to ActiveRecord. :star:272
	- [orm2](https://github.com/dresende/node-orm2) - ORM for PostgreSQL, MariaDB, MySQL, Amazon Redshift, SQLite, MongoDB. :star:2845
	- [pg-promise](https://github.com/vitaly-t/pg-promise) - PostgreSQL framework for native SQL using promises. :star:1775
	- [Objection.js](https://github.com/Vincit/objection.js) - Lightweight ORM built on the SQL query builder Knex. :star:2691
	- [TypeORM](https://github.com/typeorm/typeorm) - ORM for PostgreSQL, MariaDB, MySQL, SQLite, and more. :star:6300
- Query builder
	- [Knex](https://github.com/tgriesser/knex) - Query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use. :star:6898
- Other
	- [NeDB](https://github.com/louischatriot/nedb) - Embedded persistent database written in JavaScript. :star:8244
	- [Lowdb](https://github.com/typicode/lowdb) - Small JavaScript database powered by Lodash. :star:7868
	- [Keyv](https://github.com/lukechilds/keyv) - Simple key-value storage with support for multiple backends. :star:518
	- [Finale](https://github.com/tommybananas/finale) - RESTful endpoint generator for your Sequelize models. :star:48
	- [database-js](https://github.com/mlaanderson/database-js) - Wrapper for multiple databases with a JDBC-like connection. :star:6


### Testing

- [AVA](https://ava.li) - Futuristic test runner.
- [Mocha](http://mochajs.org) - Feature-rich test framework making asynchronous testing simple and fun.
- [nyc](https://github.com/bcoe/nyc) - Code coverage tool built on istanbul that works with subprocesses. :star:2534
- [tap](https://github.com/isaacs/node-tap) - TAP test framework. :star:1225
- [tape](https://github.com/substack/tape) - TAP-producing test harness. :star:4598
- [power-assert](https://github.com/power-assert-js/power-assert) - Provides descriptive assertion messages through the standard assert interface. :star:1962
- [Mochify](https://github.com/mantoni/mochify.js) - TDD with Browserify, Mocha, PhantomJS and WebDriver. :star:308
- [trevor](https://github.com/vdemedes/trevor) - Run tests against multiple versions of Node.js without switching versions manually or pushing to Travis CI. :star:2027
- [loadtest](https://github.com/alexfernandez/loadtest) - Run load tests for your web application, with an API for automation. :star:1215
- [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs and mocks. :star:5861
- [navit](https://github.com/nodeca/navit) - PhantomJS / SlimerJS wrapper to simplify browser test scripting. :star:41
- [Nock](https://github.com/pgte/nock) - HTTP mocking and expectations. :star:6311
- [intern](https://github.com/theintern/intern) - Code testing stack. :star:3984
- [toxy](https://github.com/h2non/toxy) - Hackable HTTP proxy to simulate failure scenarios and network conditions. :star:2423
- [hook-std](https://github.com/sindresorhus/hook-std) - Hook and modify stdout/stderr. :star:28
- [testen](https://github.com/egoist/testen) - Run tests for multiple versions of Node.js locally with NVM. :star:162
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - Automated UI testing framework based on Selenium WebDriver. :star:8143
- [WebdriverIO](https://github.com/webdriverio/webdriverio) - Automated testing based on the WebDriver protocol. :star:3986
- [Jest](https://github.com/facebook/jest) - Painless JavaScript testing. :star:17563
- [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing. :star:4654
- [abstruse](https://github.com/bleenco/abstruse) - Continuous Integration server. :star:235


### Security

- [snyk](https://github.com/Snyk/snyk) - CLI and build-time tool to find & fix vulnerable npm dependencies. :star:1090
- [upash](https://github.com/simonepri/upash) - Unified API for all password hashing algorithms. :star:95


### Benchmarking

- [Benchmark.js](https://github.com/bestiejs/benchmark.js) - Benchmarking library that supports high-resolution timers and returns statistically significant results. :star:3507
- [matcha](https://github.com/logicalparadox/matcha) - Simplistic approach to benchmarking. :star:478


### Minifiers

- [babili](https://github.com/babel/babili) - ES2015+ aware minifier based on the Babel toolchain. :star:3336
- [UglifyJS2](https://github.com/mishoo/UglifyJS2) - JavaScript minifier. :star:8614
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS minifier. :star:2909
- [minimize](https://github.com/Swaagie/minimize) - HTML minifier. :star:138
- [imagemin](https://github.com/imagemin/imagemin) - Image minifier. :star:2148


### Authentication

- [Passport](https://github.com/jaredhanson/passport) - Simple, unobtrusive authentication. :star:13346
- [Grant](https://github.com/simov/grant) - OAuth middleware for Express, Koa, and Hapi. :star:1472
- [CloudRail](https://github.com/CloudRail/cloudrail-si-node-sdk) - Unified API for social authentication (Facebook, Twitter, Slack, Instagram, …). :star:238


### Authorization

- [CASL](https://github.com/stalniy/casl) - Isomorphic authorization for UI and API. :star:464


### Email

- [Nodemailer](https://github.com/andris9/Nodemailer) - The fastest way to handle email. :star:9460
- [emailjs](https://github.com/eleith/emailjs) - Send text/HTML emails with attachments to any SMTP server. :star:1611
- [email-templates](https://github.com/niftylettuce/email-templates) - Create, preview, and send custom email templates. :star:1996


### Job queues

- [kue](https://github.com/Automattic/kue) - Redis-backed priority job queue. :star:7417
- [bull](https://github.com/OptimalBits/bull) - Persistent job and message queue. :star:2898
- [agenda](https://github.com/rschmukler/agenda) - MongoDB-backed job scheduling. :star:4039
- [idoit](https://github.com/nodeca/idoit) - Redis-backed job queue engine with advanced job control. :star:24
- [node-resque](https://github.com/taskrabbit/node-resque) - Redis-backed job queue. :star:512
- [rsmq](https://github.com/smrchy/rsmq) - Redis-backed message queue. :star:741
- [bee-queue](https://github.com/bee-queue/bee-queue) - High-performance Redis-backed job queue. :star:876


### Node.js management

- [n](https://github.com/tj/n) - Node.js version management. :star:9127
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.js. :star:1136
- [nodeenv](https://github.com/ekalinin/nodeenv) - Node.js virtual environment compatible to Python's virtualenv. :star:878
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Version management for Windows. :star:5822


### Natural language processing

- [retext](https://github.com/wooorm/retext) - An extensible natural language system. :star:1501
- [franc](https://github.com/wooorm/franc) - Detect the language of text. :star:2623
- [leven](https://github.com/sindresorhus/leven) - Measure the difference between two strings using the Levenshtein distance algorithm. :star:341
- [natural](https://github.com/NaturalNode/natural) - Natural language facility. :star:7740


### Process management

- [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager. :star:24698
- [nodemon](https://github.com/remy/nodemon) - Monitor for changes in your app and automatically restart the server. :star:14614
- [node-mac](https://github.com/coreybutler/node-mac) - Run scripts as a native Mac daemon and log to the console app. :star:417
- [node-linux](https://github.com/coreybutler/node-linux) - Run scripts as native system service and log to syslog. :star:341
- [node-windows](https://github.com/coreybutler/node-windows) - Run scripts as a native Windows service and log to the Event viewer. :star:1424
- [supervisor](https://github.com/petruisfan/node-supervisor) - Restart scripts when they crash or restart when a `*.js` file changes. :star:3375
- [Phusion Passenger](https://github.com/phusion/passenger) - Friendly process manager that integrates directly into Nginx. :star:4061


### Automation

- [robotjs](https://github.com/octalmage/robotjs) - Desktop Automation: control the mouse, keyboard and read the screen. :star:6956


### AST

- [Acorn](https://github.com/ternjs/acorn) - Tiny, fast JavaScript parser. :star:3493
- [Babylon](https://github.com/babel/babel/tree/master/packages/babylon) - JavaScript parser used in Babel.


### Static site generators

- [Wintersmith](https://github.com/jnordberg/wintersmith) - Flexible, minimalistic, multi-platform static site generator. :star:3334
- [Assemble](https://github.com/assemble/assemble/) - Static site generator for Node.js, Grunt.js, and Yeoman.
- [DocPad](https://github.com/docpad/docpad) - Static site generator with dynamic abilities and huge plugin ecosystem. :star:2966
- [Phenomic](https://github.com/phenomic/phenomic) - Modern static website generator based on the React and Webpack ecosystem. :star:2980
- [docsify](https://github.com/QingWei-Li/docsify) - Markdown documentation site generator with no statically built HTML files. :star:6159


### Content management systems

- [KeystoneJS](hhttps://github.com/keystonejs/keystone) - CMS and web application platform built on Express and MongoDB.
- [ApostropheCMS](https://github.com/apostrophecms/apostrophe) - Content management system with an emphasis on intuitive front end content editing and administration built on Express and MongoDB. :star:2116
- [Strapi](https://github.com/strapi/strapi) - Content Management Framework (headless-CMS) to build powerful APIs. :star:5031


### Forum

- [nodeBB](https://github.com/NodeBB/NodeBB) - Forum platform for the modern web. :star:8707


### Blogging

- [Ghost](https://github.com/TryGhost/Ghost) - Simple, powerful publishing platform. :star:25583
- [Hexo](https://github.com/hexojs/hexo) - Fast, simple and powerful blogging framework. :star:22068


### Weird

- [cows](https://github.com/sindresorhus/cows) - ASCII cows. :star:285
- [superb](https://github.com/sindresorhus/superb) - Get superb like words. :star:256
- [cat-names](https://github.com/sindresorhus/cat-names) - Get popular cat names. :star:194
- [dog-names](https://github.com/sindresorhus/dog-names) - Get popular dog names. :star:82
- [superheroes](https://github.com/sindresorhus/superheroes) - Get superhero names. :star:165
- [supervillains](https://github.com/sindresorhus/supervillains) - Get supervillain names. :star:69
- [cool-ascii-faces](https://github.com/maxogden/cool-ascii-faces) - Get some cool ascii faces. :star:1578
- [cat-ascii-faces](https://github.com/melaniecebula/cat-ascii-faces) - ₍˄·͈༝·͈˄₎◞ ̑̑ෆ⃛ (=ↀωↀ=)✧ (^･o･^)ﾉ” :star:190
- [nerds](https://github.com/SkyHacks/nerds) - Get data from nerdy topics like Harry Potter, Star Wars, and Pokémon. :star:43


### Serialization

- [snappy](https://github.com/kesla/node-snappy) - Native bindings for Google's Snappy compression library. :star:366
- [protobuf](https://github.com/dcodeIO/protobuf.js) - Implementation of Protocol Buffers. :star:4336
- [compactr](https://github.com/compactr/compactr.js) - Implementation of the Compactr protocol. :star:70


### Miscellaneous

- [execa](https://github.com/sindresorhus/execa) - Better `child_process`. :star:1280
- [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server. :star:15995
- [Electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies. *(You might like [awesome-electron](https://github.com/sindresorhus/awesome-electron))* :star:60107
- [opn](https://github.com/sindresorhus/opn) - Opens stuff like websites, files, executables. :star:1014
- [hasha](https://github.com/sindresorhus/hasha) - Hashing made simple. Get the hash of a buffer/string/stream/file. :star:598
- [dot-prop](https://github.com/sindresorhus/dot-prop) - Get a property from a nested object using a dot path. :star:262
- [onetime](https://github.com/sindresorhus/onetime) - Only run a function once. :star:74
- [mem](https://github.com/sindresorhus/mem) - Memoize functions - an optimization technique used to speed up consecutive function calls by caching the result of calls with identical input. :star:353
- [import-fresh](https://github.com/sindresorhus/import-fresh) - Import a module while bypassing the cache. :star:134
- [strip-bom](https://github.com/sindresorhus/strip-bom) - Strip UTF-8 byte order mark (BOM) from a string/buffer/stream. :star:65
- [os-locale](https://github.com/sindresorhus/os-locale) - Get the system locale. :star:120
- [ssh2](https://github.com/mscdex/ssh2) - SSH2 client and server module. :star:3009
- [adit](https://github.com/markelog/adit) - SSH tunneling made simple. :star:18
- [import-lazy](https://github.com/sindresorhus/import-lazy) - Import a module lazily. :star:142
- [file-type](https://github.com/sindresorhus/file-type) - Detect the file type of a Buffer. :star:647
- [Bottleneck](https://github.com/SGrondin/bottleneck) - Rate limiter that makes throttling easy. :star:415
- [ow](https://github.com/sindresorhus/ow) - Function argument validation for humans. :star:1898
- [webworker-threads](https://github.com/audreyt/node-webworker-threads) - Lightweight Web Worker API implementation with native threads. :star:1744
- [clipboardy](https://github.com/sindresorhus/clipboardy) - Access the system clipboard (copy/paste). :star:399
- [node-pre-gyp](https://github.com/mapbox/node-pre-gyp) - Makes it easy to publish and install Node.js C++ addons from binaries. :star:510
- [opencv](https://github.com/peterbraden/node-opencv) - Bindings for OpenCV. The defacto computer vision library. :star:3384
- [dotenv](https://github.com/motdotla/dotenv) - Load environment variables from .env file. :star:5887
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - Get tags from a remote git repo. :star:29
- [semver](https://github.com/npm/node-semver) - Semantic version parser. :star:2237
- [Faker.js](https://github.com/Marak/Faker.js) - Generate massive amounts of fake data. :star:14179
- [nodegit](https://github.com/nodegit/nodegit) - Native bindings to Git. :star:3398
- [json-strictify](https://github.com/pigulla/json-strictify) - Safely serialize a value to JSON without data loss or going into an infinite loop. :star:3
- [resolve-from](https://github.com/sindresorhus/resolve-from) - Resolve the path of a module like `require.resolve()` but from a given path. :star:56
- [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - Event driven web crawler. :star:1694
- [jsdom](https://github.com/tmpvar/jsdom) - JavaScript implementation of HTML and the DOM. :star:9844
- [hypernova](https://github.com/airbnb/hypernova) - Server-side rendering your JavaScript views. :star:4150
- [@sindresorhus/is](https://github.com/sindresorhus/is) - Type check values. :star:625
- [env-dot-prop](https://github.com/simonepri/env-dot-prop) - Get, set, or delete nested properties of process.env using a dot path. :star:10
- [emittery](https://github.com/sindresorhus/emittery) - Simple and modern async event emitter. :star:690


## Resources

### Tutorials

- [Nodeschool](http://nodeschool.io) - Learn Node.js with interactive lessons.
- [The Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node) - An introduction to Node.js.
- [stream-handbook](https://github.com/substack/stream-handbook) - How to write Node.js programs with streams. :star:11615
- [module-best-practices](https://github.com/mattdesl/module-best-practices) - Some good practices when writing new npm modules. :star:1101
- [The Node Way](http://thenodeway.io) - An entire philosophy of Node.js best practices and guiding principles exists for writing maintainable modules, scalable applications, and code that is actually pleasant to read.
- [You Don't Know Node.js](https://github.com/azat-co/you-dont-know-node) - Introduction to Node.js core features and asynchronous JavaScript. :star:855


### Discovery

- [npms](https://npms.io) - Superb package search with deep analysis of package quality using a [myriad of metrics](https://npms.io/about).
- [npm addict](https://npmaddict.com) - Your daily injection of npm packages.
- [npmcompare.com](https://npmcompare.com) - Compare and discover npm packages.

### Articles

- [Error Handling in Node.js](https://www.joyent.com/node-js/production/design/errors)
- [Teach Yourself Node.js in 10 Steps](https://ponyfoo.com/articles/teach-yourself-nodejs-in-10-steps)
- [Mastering the filesystem in Node.js](https://medium.com/@yoshuawuyts/mastering-the-filesystem-in-node-js-4706b7cb0801)
- [Semver: A Primer](https://nodesource.com/blog/semver-a-primer/)
- [Semver: Tilde and Caret](https://nodesource.com/blog/semver-tilde-and-caret/)
- [Why Asynchronous?](https://nodesource.com/blog/why-asynchronous/)
- [Understanding the Node.js Event Loop](https://nodesource.com/blog/understanding-the-nodejs-event-loop/)
- [Understanding Object Streams](https://nodesource.com/blog/understanding-object-streams/)
- [Art of README](https://github.com/noffle/art-of-readme) - Learn the art of writing quality READMEs. :star:4710

### Newsletters

- [Node Weekly](http://nodeweekly.com) - Weekly e-mail round-up of Node.js news and articles.
- [Node Module Of The Week!](https://nmotw.in) - Weekly dose of hand picked node modules.

### Videos

- [Introduction to Node.js with Ryan Dahl](https://www.youtube.com/watch?v=jo_B4LTHi3I)
- [Hands on with Node.js](https://learn.bevry.me/node/preface)
- [Nodetuts](http://nodetuts.com) - Series of talks, including TCP & HTTP API servers, async programming, and more.

### Books

- [Node.js in Action](https://www.manning.com/books/node-js-in-action-second-edition)
- [Node.js in Practice](http://www.amazon.com/Node-js-Practice-Alex-R-Young/dp/1617290939)
- [Mastering Node](http://visionmedia.github.io/masteringnode/)
- [Node.js 8 the Right Way](https://pragprog.com/book/jwnode2/node-js-8-the-right-way)
- [Professional Node.js: Building Javascript Based Scalable Software](http://www.amazon.com/Professional-Node-js-Building-Javascript-Scalable-ebook/dp/B009L7QETY/)
- [Practical Node.js: Building Real-World Scalable Web Apps](http://practicalnodebook.com)
- [Mixu's Node book](http://book.mixu.net/node/)
- [Web Development with Node and Express](http://shop.oreilly.com/product/0636920032977.do)
- [Pro Express.js](http://proexpressjs.com)
- [Secure Your Node.js Web Application](http://www.amazon.com/Secure-Your-Node-js-Web-Application/dp/1680500856)
- [Express in Action](https://www.manning.com/books/express-in-action)

### Blogs

- [Node.js blog](https://nodejs.org/en/blog/)
- [webapplog.com](http://webapplog.com/tag/node-js/) - Blog posts on Node.js and JavaScript from the author of Practical Node.js and Pro Express.js Azat Mardan.

### Courses

- [Learn to build apps and APIs with Node.js](https://learnnode.com/friend/AWESOME) - Video course by Wes Bos.
- [Real Time Web with Node.js](https://www.codeschool.com/courses/real-time-web-with-node-js)
- [Learn and Understand Node.js](https://www.udemy.com/understand-nodejs)

### Cheatsheets

- [Express.js](https://github.com/azat-co/cheatsheets/blob/master/express4)
- [Stream FAQs](https://github.com/stephenplusplus/stream-faqs) - Answering common questions about streams, covering pagination, events, and more. :star:158

### Tools

- [OctoLinker](https://chrome.google.com/webstore/detail/octolinker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension that linkifies dependencies in package.json, .js, .jsx, .coffee and .md files on GitHub.
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome extension to display npm dependencies at the bottom of a repo's readme.
- [RunKit](http://blog.tonicdev.com/2015/09/30/embedded-tonic.html) - Embed a Node.js environment on any website.
- [RequireBin](http://requirebin.com) - Shareable JavaScript programs powered by npm and browserify.
- [github-npm-stats](https://chrome.google.com/webstore/detail/github-npm-stats/oomfflokggoffaiagenekchfnpighcef) - Chrome extension that displays npm download stats on GitHub.

### Community

- [Gitter](https://gitter.im/nodejs/node)
- [`#node.js` on Freenode](http://webchat.freenode.net/?channels=node.js)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/node.js)
- [Reddit](https://www.reddit.com/r/node)
- [Twitter](https://twitter.com/nodejs)
- [Hashnode](https://hashnode.com/n/nodejs)

### Miscellaneous

- [nodebots](http://nodebots.io) - Robots powered by JavaScript.
- [node-module-boilerplate](https://github.com/sindresorhus/node-module-boilerplate) - Boilerplate to kickstart creating a node module. :star:400
- [generator-nm](https://github.com/sindresorhus/generator-nm) - Scaffold out a node module. :star:543
- [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) - Tips, tricks, and resources for working with Node.js on Microsoft platforms. :star:1889
- [Module Requests & Ideas](https://github.com/sindresorhus/module-requests) - Request a JavaScript module you wish existed or get ideas for modules. :star:399


## Related lists

- [awesome-npm](https://github.com/sindresorhus/awesome-npm) - Resources and tips for using npm. :star:2911
- [awesome-cross-platform-nodejs](https://github.com/bcoe/awesome-cross-platform-nodejs) - Resources for writing and testing cross-platform code. :star:234


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.


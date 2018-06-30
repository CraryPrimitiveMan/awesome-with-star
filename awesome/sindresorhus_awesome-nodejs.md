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

- [webtorrent](https://github.com/feross/webtorrent) - Streaming torrent client for Node.js and the browser. :star:17084
- [peerflix](https://github.com/mafintosh/peerflix) - Streaming torrent client. :star:4811
- [dat](http://dat-data.com) - Real-time replication and versioning for data sets.
- [ipfs](https://github.com/ipfs/js-ipfs) - Distributed file system that seeks to connect all computing devices with the same system of files. :star:2520
- [stackgl](http://stack.gl) - Open software ecosystem for WebGL, built on top of browserify and npm.
- [peerwiki](https://github.com/mafintosh/peerwiki) - All of Wikipedia on BitTorrent. :star:276
- [peercast](https://github.com/mafintosh/peercast) - Stream a torrent video to Chromecast. :star:382
- [BitcoinJS](https://github.com/bitcoinjs/bitcoinjs-lib) - Clean, readable, proven Bitcoin library. :star:2816
- [Bitcore](https://github.com/bitpay/bitcore) - Pure and powerful Bitcoin library. :star:2812
- [PDFKit](https://github.com/devongovett/pdfkit) - PDF generation library. :star:4043
- [turf](https://github.com/Turfjs/turf) - Modular geospatial processing and analysis engine. :star:3700
- [webcat](https://github.com/mafintosh/webcat) - p2p pipe across the web using WebRTC that uses your GitHub private/public key for authentication. :star:373
- [NodeOS](https://github.com/NodeOS/NodeOS) - The first operating system powered by npm. :star:5432
- [Brain.js](https://github.com/BrainJS/brain.js) - Machine-learning framework. :star:5417
- [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) - Graph theory (a.k.a. network) modeling and analysis. :star:4411
- [Kadence](https://kadence.github.io/) - Kademlia distributed hash table.
- [seedshot](https://github.com/twobucks/seedshot) - Temporary P2P screenshot sharing from your browser. :star:175
- [js-git](https://github.com/creationix/js-git) - JavaScript implementation of Git. :star:3386
- [skale](https://github.com/skale-me/skale-engine) - High performance distributed data processing engine. :star:275
- [xlsx](https://github.com/sheetjs/js-xlsx) - Pure JS Excel spreadsheet reader and writer. :star:11043
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - Pure JavaScript implementation of Git. :star:3158


### Command-line apps

- [np](https://github.com/sindresorhus/np) - Better `npm publish`. :star:3262
- [npm-name](https://github.com/sindresorhus/npm-name) - Check whether a package name is available on npm. :star:73
- [gh-home](https://github.com/sindresorhus/gh-home) - Open the GitHub page of the repo in the current directory. :star:94
- [npm-home](https://github.com/sindresorhus/npm-home) - Open the npm page of a package. :star:135
- [trash](https://github.com/sindresorhus/trash) - Safer alternative to `rm`. :star:1562
- [speed-test](https://github.com/sindresorhus/speed-test) - Test your internet connection speed and ping. :star:2988
- [emoj](https://github.com/sindresorhus/emoj) - Find relevant emoji from text on the command-line. :star:1520
- [pageres](https://github.com/sindresorhus/pageres) - Capture website screenshots. :star:8363
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:175
- [vtop](https://github.com/MrRio/vtop) - More better top, with nice charts. :star:2809
- [empty-trash](https://github.com/sindresorhus/empty-trash) - Empty the trash. :star:85
- [is-up](https://github.com/sindresorhus/is-up) - Check whether a website is up or down. :star:279
- [is-online](https://github.com/sindresorhus/is-online) - Check if the internet connection is up. :star:404
- [public-ip](https://github.com/sindresorhus/public-ip) - Get your public IP address. :star:315
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - Copy & paste on the terminal. :star:134
- [XO](https://github.com/xojs/xo) - Enforce strict code style using the JavaScript happiness style. :star:3853
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style — One style to rule them all. :star:18346
- [ESLint](http://eslint.org) - The pluggable linting utility for JavaScript.
- [dev-time](https://github.com/samverschueren/dev-time-cli) - Get the current local time of a GitHub user. :star:153
- [David](https://github.com/alanshaw/david) - Tells you when your package npm dependencies are out of date. :star:820
- [http-server](https://github.com/indexzero/http-server) - Simple, zero-config command-line HTTP server. :star:7070
- [Live Server](https://github.com/tapio/live-server) - Development HTTP-server with livereload capability. :star:2220
- [bcat](https://github.com/kessler/node-bcat) - Pipe command output to web browsers. :star:267
- [normit](https://github.com/pawurb/normit) - Google Translate with speech synthesis in your terminal. :star:193
- [fkill](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform. :star:5175
- [pjs](https://github.com/danielstjules/pjs) - Pipeable JavaScript. Quickly filter, map, and reduce from the terminal. :star:334
- [license-checker](https://github.com/davglass/license-checker) - Check licenses of your app's dependencies. :star:655
- [browser-run](https://github.com/juliangruber/browser-run) - Easily run code in a browser environment. :star:315
- [tmpin](https://github.com/sindresorhus/tmpin) - Adds stdin support to any CLI app that accepts file input. :star:109
- [wifi-password](https://github.com/kevva/wifi-password-cli) - Get the current wifi password. :star:128
- [wallpaper](https://github.com/sindresorhus/wallpaper) - Change the desktop wallpaper. :star:504
- [brightness](https://github.com/kevva/brightness-cli) - Change the screen brightness. :star:124
- [torrent](https://github.com/maxogden/torrent) - Download torrents. :star:514
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - Kill all Chrome tabs to improve performance, decrease battery usage, and save memory. :star:228
- [alex](https://github.com/wooorm/alex) - Catch insensitive, inconsiderate writing. :star:2287
- [pen](https://github.com/noraesae/pen) - Live Markdown preview in the browser from your favorite editor. :star:217
- [subdownloader](https://github.com/beatfreaker/subdownloader) - Subtitle downloader for movies and TV series. :star:91
- [dark-mode](https://github.com/sindresorhus/dark-mode) - Toggle the macOS Dark Mode. :star:333
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP location finder. :star:168
- [Jsome](https://github.com/Javascipt/Jsome) - Pretty prints JSON with configurable colors and indentation. :star:120
- [itunes-remote](https://github.com/mischah/itunes-remote) - Interactively control iTunes. :star:324
- [mobicon](https://github.com/samverschueren/mobicon-cli) - Mobile app icon generator. :star:46
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - Mobile app splash screen generator. :star:26
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - Pretty git diff to HTML generator. :star:137
- [Cash](https://github.com/dthree/cash) - Cross-platform Unix shell commands in pure JavaScript. :star:7530
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - Try out npm packages in the terminal. :star:1009
- [jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for source code. :star:758
- [atmo](https://github.com/Raathigesh/Atmo) - Server-side API mocking. :star:693
- [auto-install](https://github.com/siddharthkp/auto-install) - Auto installs dependencies as you code. :star:867
- [lessmd](https://github.com/linuxenko/lessmd) - Markdown in the terminal. :star:85
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - Find out which dependencies are slowing you down. :star:2161
- [localtunnel](https://github.com/localtunnel/localtunnel) - Expose your localhost to the world. :star:7008
- [svg-term-cli](https://github.com/marionebl/svg-term-cli) - Share terminal sessions via SVG. :star:638
- [gtop](https://github.com/aksakalli/gtop) - System monitoring dashboard for the terminal. :star:6840
- [themer](https://github.com/mjswensen/themer) - Generate themes for your editor, terminal, wallpaper, Slack, and more. :star:1621


### Functional programming

- [lodash](https://lodash.com) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections. :star:24171
- [Ramda](https://github.com/ramda/ramda) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data. :star:12822
- [Folktale](http://folktale.origamitower.com) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse.
- [Mout](https://github.com/mout/mout) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead. :star:929
- [Bacon.js](http://baconjs.github.io) - Functional reactive programming.
- [RxJS](http://reactivex.io) - Functional reactive library for transforming, composing, and querying various kinds of data.
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases. :star:5002
- [Kefir.js](https://github.com/kefirjs/kefir) - Reactive library with focus on high performance and low memory usage. :star:1443


### HTTP

- [got](https://github.com/sindresorhus/got) - Nicer interface to the built-in `http` module. :star:2727
- [gh-got](https://github.com/sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API. :star:112
- [axios](https://github.com/mzabriskie/axios) - Promise based HTTP client (works in the browser too). :star:44087
- [request](https://github.com/request/request) - Simplified HTTP request client. :star:19956
- [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities. :star:314
- [download](https://github.com/kevva/download) - Download and extract files effortlessly. :star:710
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP proxy. :star:8888
- [superagent](https://github.com/visionmedia/superagent) - HTTP request library. :star:12964
- [node-fetch](https://github.com/bitinn/node-fetch) - `window.fetch` for Node.js. :star:3189
- [flashheart](https://github.com/bbc/flashheart) - REST client. :star:85
- [http-fake-backend](https://github.com/micromata/http-fake-backend) - Build a fake backend by providing the content of JSON files or JavaScript objects through configurable routes. :star:150
- [cacheable-request](https://github.com/lukechilds/cacheable-request) - Wrap native HTTP requests with RFC compliant cache support. :star:101
- [gotql](https://github.com/khaosdoctor/gotql) - GraphQL request library built on [got](https://github.com/sindresorhus/got). :star:154


### Debugging / Profiling

- [ironNode](https://github.com/s-a/iron-node) - Node.js debugger supporting ES2015 out of the box. :star:2369
- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools. :star:12190
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility. :star:6327
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - Node.js is running but you don't know why? :star:737
- [njsTrace](https://github.com/valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function. :star:220
- [vstream](https://github.com/joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams. :star:53
- [stackman](https://github.com/watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies. :star:164
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables. :star:244
- [0x](https://github.com/davidmarkclements/0x) - Flamegraph profiling. :star:1019
- [ctrace](https://github.com/automation-stack/ctrace) - Well-formatted and improved trace system calls and signals. :star:97
- [leakage](https://github.com/andywer/leakage) - Write memory leak tests. :star:1251


### Logging

- [pino](https://github.com/pinojs/pino) - Extremely fast logger inspired by Bunyan. :star:2798
- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library. :star:10736
- [console-log-level](https://github.com/watson/console-log-level) - The most simple logger imaginable with support for log levels and custom prefixes. :star:25
- [storyboard](https://github.com/guigrpa/storyboard) - End-to-end, hierarchical, real-time, colorful logs and stories. :star:464
- [signale](https://github.com/klauscfhq/signale) - Hackable console logger with beautiful output. :star:5823


### Command-line utilities

- [chalk](https://github.com/chalk/chalk) - Terminal string styling done right. :star:9321
- [meow](https://github.com/sindresorhus/meow) - CLI app helper. :star:1338
- [yargs](https://github.com/yargs/yargs) - Command-line parser that automatically generates an elegant user-interface. :star:4759
- [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner. :star:3243
- [get-stdin](https://github.com/sindresorhus/get-stdin) - Easier stdin. :star:162
- [log-update](https://github.com/sindresorhus/log-update) - Log by overwriting the previous output in the terminal. Useful for rendering progress bars, animations, etc. :star:481
- [Ink](https://github.com/vadimdemedes/ink) - React for interactive command-line apps. :star:6079
- [listr](https://github.com/samverschueren/listr) - Terminal task list. :star:1620
- [conf](https://github.com/sindresorhus/conf) - Simple config handling for your app or module. :star:277
- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - ANSI escape codes for manipulating the terminal. :star:196
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels. :star:334
- [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows CMD fallbacks. :star:257
- [boxen](https://github.com/sindresorhus/boxen) - Create boxes in the terminal. :star:360
- [terminal-link](https://github.com/sindresorhus/terminal-link) - Create clickable links in the terminal. :star:105
- [terminal-image](https://github.com/sindresorhus/terminal-image) - Display images in the terminal. :star:276
- [string-width](https://github.com/sindresorhus/string-width) - Get the visual width of a string - the number of columns required to display it. :star:98
- [cli-truncate](https://github.com/sindresorhus/cli-truncate) - Truncate a string to a specific width in the terminal. :star:31
- [first-run](https://github.com/sindresorhus/first-run) - Check if it's the first time the process is run. :star:53
- [vorpal](https://github.com/dthree/vorpal) - Interactive CLI apps. :star:4690
- [blessed](https://github.com/chjj/blessed) - Curses-like library. :star:7519
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt. :star:7399
- [yn](https://github.com/sindresorhus/yn) - Parse yes/no like values. :star:112
- [cli-table3](https://github.com/cli-table/cli-table3) - Pretty unicode tables. :star:8
- [drawille](https://github.com/madbence/node-drawille) - Draw on the terminal with unicode braille characters. :star:743
- [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app. :star:995
- [ascii-charts](https://github.com/jstrace/chart) - ASCII bar chart in the terminal. :star:220
- [progress](https://github.com/tj/node-progress) - Flexible ascii progress bar. :star:1865
- [insight](https://github.com/yeoman/insight) - Helps you understand how your tool is being used by anonymously reporting usage metrics to Google Analytics. :star:425
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - Toggle the CLI cursor. :star:43
- [columnify](https://github.com/timoxley/columnify) - Create text-based columns suitable for console output. Supports cell wrapping. :star:301
- [cli-columns](https://github.com/shannonmoeller/cli-columns) - Columnated unicode and ansi-safe text lists. :star:11
- [cfonts](https://github.com/dominikwilkowski/cfonts) - Sexy ASCII fonts for the console. :star:323
- [multispinner](https://github.com/codekirei/node-multispinner) - Multiple, simultaneous, individually controllable CLI spinners. :star:216
- [omelette](https://github.com/f/omelette) - Shell autocompletion helper. :star:720
- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform. :star:2724
- [shelljs](https://github.com/shelljs/shelljs) - Portable Unix shell commands. :star:8041
- [sudo-block](https://github.com/sindresorhus/sudo-block) - Block users from running your app with root permissions. :star:63
- [loud-rejection](https://github.com/sindresorhus/loud-rejection) - Make unhandled promise rejections fail loudly instead of the default silent fail. :star:214
- [sparkly](https://github.com/sindresorhus/sparkly) - Generate sparklines ▁▂▃▅▂▇ :star:272
- [Bit](https://github.com/teambit/bit) - Create, maintain, find and use small modules and components across repositories. :star:3131
- [gradient-string](https://github.com/bokub/gradient-string) - Beautiful color gradients in terminal output. :star:288
- [oclif](https://github.com/oclif/oclif) - CLI framework complete with parser, automatic documentation, testing, and plugins. :star:2076
- [term-size](https://github.com/sindresorhus/term-size) - Reliably get the terminal window size. :star:73


### Build tools

- [parcel](https://github.com/parcel-bundler/parcel) - Blazing fast, zero config web app bundler. :star:23759
- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser. :star:42083
- [rollup](https://github.com/rollup/rollup) - Next-generation ES2015 module bundler. :star:13086
- [gulp](http://gulpjs.com) - Streaming and fast build system that favors code over config.
- [Broccoli](https://github.com/broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions. :star:3122
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow. :star:6484
- [Start](https://github.com/deepsweet/start) - Functional task runner with shareable presets. :star:349
- [ygor](https://github.com/shannonmoeller/ygor) - Promising task runner for when `npm run` isn't enough and everything else is too much. :star:54
- [FuseBox](https://github.com/fuse-box/fuse-box) - Fast build system that combines the power of webpack, JSPM and SystemJS, with first-class TypeScript support. :star:3380
- [pkg](https://github.com/zeit/pkg) - Package your Node.js project into an executable. :star:10231


### Hardware

- [johnny-five](https://github.com/rwaldron/johnny-five) - Firmata based Arduino Framework. :star:9192
- [serialport](https://github.com/voodootikigod/node-serialport) - Access serial ports for reading and writing. :star:3434
- [usb](https://github.com/nonolith/node-usb) - USB library. :star:668
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C serial bus access. :star:123
- [onoff](https://github.com/fivdi/onoff) - GPIO access and interrupt detection. :star:680
- [spi-device](https://github.com/fivdi/spi-device) - SPI serial bus access. :star:39
- [pigpio](https://github.com/fivdi/pigpio) - Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi. :star:330
- [gps](https://github.com/infusion/GPS.js) - NMEA parser for handling GPS receivers. :star:61


### Templating

- [marko](https://github.com/marko-js/marko) - HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags. :star:6394
- [nunjucks](https://github.com/mozilla/nunjucks) - Templating engine with inheritance, asynchronous control, and more (jinja2 inspired). :star:5341
- [handlebars.js](https://github.com/wycats/handlebars.js) - Superset of Mustache templates which adds powerful features like helpers and more advanced blocks. :star:13475
- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language. :star:2581
- [Pug](https://github.com/pugjs/pug) - High-performance template engine heavily influenced by Haml. :star:16841


### Web frameworks

- [Hapi](http://hapijs.com) - Framework for building applications and services.
- [Koa](http://koajs.com) - Framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [Express](http://expressjs.com) - Web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [Feathers](http://feathersjs.com) - Microservice framework built in the spirit of Express.
- [LoopBack](http://loopback.io) - Powerful framework for creating REST APIs and easily connecting to backend data sources.
- [Meteor](https://www.meteor.com) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [Restify](http://restify.com) - Enables you to build correct REST web services.
- [ThinkJS](https://github.com/thinkjs/thinkjs) - Framework with ES2015+ support, WebSockets, REST API. :star:4374
- [ActionHero](https://github.com/actionhero/actionhero) - Framework for making reusable & scalable APIs for TCP sockets, WebSockets, and HTTP clients. :star:1852
- [MERN](http://mern.io) - Easily build production-ready universal apps with MongoDB, Express, React, and webpack.
- [Next.js](https://github.com/zeit/next.js) - Minimalistic framework for server-rendered universal JavaScript web apps. :star:26707
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Minimalistic framework for server-rendered Vue.js apps. :star:13242
- [seneca](https://github.com/senecajs/seneca) - Toolkit for writing microservices. :star:2994
- [AdonisJs](http://adonisjs.com) - A true MVC framework for Node.js built on solid foundations of Dependency Injection and IoC container.
- [Hemera](https://github.com/hemerajs/hemera) - Write reliable and fault-tolerant microservices with [NATS](https://nats.io). :star:536
- [Micro](https://github.com/zeit/micro) - Minimalistic microservice framework with an async approach. :star:6788
- [Moleculer](https://moleculer.services) - Fast & powerful microservices framework.
- [Fastify](https://github.com/fastify/fastify) - Fast and low overhead web framework. :star:7400
- [Nest](https://github.com/nestjs/nest) - Angular-inspired framework for building efficient and scalable server-side apps. :star:6816


### Documentation

- [documentation.js](https://github.com/documentationjs/documentation) - API documentation generator with support for ES2015+ and flow annotation. :star:3861
- [ESDoc](https://github.com/esdoc/esdoc) - Documentation generator targeting ES2015, attaching test code and measuring documentation coverage. :star:2108
- [Docco](http://jashkenas.github.io/docco/) - Documentation generator which produces an HTML document that displays your comments intermingled with your code.
- [JSDoc](http://usejsdoc.org) - API documentation generator similar to JavaDoc or PHPDoc.


### Filesystem

- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs. :star:828
- [globby](https://github.com/sindresorhus/globby) - Glob files with support for multiple patterns. :star:671
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:175
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like `rm -rf`. :star:2543
- [make-dir](https://github.com/sindresorhus/make-dir) - Recursively create directories like `mkdir -p`. :star:305
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Drop-in replacement for the `fs` module with various improvements. :star:752
- [chokidar](https://github.com/paulmillr/chokidar) - Filesystem watcher which stabilizes events from `fs.watch` and `fs.watchFile` as well as using native `fsevents` on macOS. :star:4261
- [find-up](https://github.com/sindresorhus/find-up) - Find a file by walking up parent directories. :star:153
- [proper-lockfile](https://github.com/IndigoUnited/node-proper-lockfile) - Inter-process and inter-machine lockfile utility. :star:49
- [load-json-file](https://github.com/sindresorhus/load-json-file) - Read and parse a JSON file. :star:105
- [write-json-file](https://github.com/sindresorhus/write-json-file) - Stringify and write JSON to a file atomically. :star:89
- [fs-write-stream-atomic](https://github.com/npm/fs-write-stream-atomic) - Like `fs.createWriteStream()`, but atomic. :star:43
- [filenamify](https://github.com/sindresorhus/filenamify) - Convert a string to a valid filename. :star:166
- [lnfs](https://github.com/kevva/lnfs) - Force create symlinks like `ln -fs`. :star:9
- [istextorbinary](https://github.com/bevry/istextorbinary) - Check if a file is text or binary. :star:43
- [fs-jetpack](https://github.com/szwacz/fs-jetpack) - Completely redesigned file system API for convenience in everyday use. :star:400
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module. :star:4347
- [pkg-dir](https://github.com/sindresorhus/pkg-dir) - Find the root directory of an npm package. :star:67
- [filehound](https://github.com/nspragg/filehound) - Flexible and fluent interface for searching the file system. :star:117


### Control flow

- Promises
	- [Bluebird](https://github.com/petkaantonov/bluebird) - Promise library with focus on innovative features and performance. :star:17001
	- [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function. :star:972
	- [delay](https://github.com/sindresorhus/delay) - Delay a promise a specified amount of time. :star:232
	- [promise-memoize](https://github.com/nodeca/promise-memoize) - Memoize promise-returning functions, with expire and prefetch. :star:28
	- [valvelet](https://github.com/lpinca/valvelet) - Limit the execution rate of a promise-returning function. :star:14
	- [p-map](https://github.com/sindresorhus/p-map) - Map over promises concurrently. :star:273
	- [More…](https://github.com/sindresorhus/promise-fun) :star:1801
- Observables
	- [zen-observable](https://github.com/zenparsing/zen-observable) - Implementation of Observables. :star:392
	- [RxJS](https://github.com/ReactiveX/RxJS) - Reactive programming. :star:13431
	- [observable-to-promise](https://github.com/sindresorhus/awesome-observables) - Convert an Observable to a Promise. :star:226
	- [More…](https://github.com/sindresorhus/awesome-observables) :star:226
- Streams
	- [Highland.js](https://github.com/caolan/highland) - Manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams. :star:2965
- Callbacks
	- [each-async](https://github.com/sindresorhus/each-async) - Async concurrent iterator like forEach. :star:101
	- [async](https://github.com/caolan/async) - Provides straight-forward, powerful functions for working with asynchronicity. :star:24216
- Channels
	- [js-csp](https://github.com/ubolonton/js-csp) - Communicating sequential processes for JavaScript (like Clojurescript core.async, or Go). :star:2124


### Streams

- [through2](https://github.com/rvagg/through2) - Tiny wrapper around streams2 Transform to avoid explicit subclassing noise. :star:1381
- [from2](https://github.com/hughsk/from2) - Convenience wrapper for ReadableStream, inspired by `through2`. :star:95
- [get-stream](https://github.com/sindresorhus/get-stream) - Get a stream as a string or buffer. :star:113
- [into-stream](https://github.com/sindresorhus/into-stream) - Convert a buffer/string/array/object into a stream. :star:65
- [duplexify](https://github.com/mafintosh/duplexify) - Turn a writeable and readable stream into a single streams2 duplex stream. :star:131
- [pumpify](https://github.com/mafintosh/pumpify) - Combine an array of streams into a single duplex stream. :star:140
- [peek-stream](https://github.com/mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it. :star:40
- [binary-split](https://github.com/maxogden/binary-split) - Newline (or any delimiter) splitter stream. :star:58
- [byline](https://github.com/jahewson/node-byline) - Super-simple line-by-line Stream reader. :star:255
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - Transform the first chunk in a stream. :star:18
- [pad-stream](https://github.com/sindresorhus/pad-stream) - Pad each line in a stream. :star:5
- [multistream](https://github.com/feross/multistream) - Combine multiple streams into a single stream. :star:138
- [stream-combiner2](https://github.com/substack/stream-combiner2) - Turn a pipeline into a single stream. :star:70
- [readable-stream](https://github.com/nodejs/readable-stream) - Mirror of Streams2 and Streams3 implementations in core. :star:627
- [through2-concurrent](https://github.com/almost/through2-concurrent) - Transform object streams concurrently. :star:57


### Real-time

- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - Highly scalable WebSocket server & client library. :star:9200
- [Socket.io](https://github.com/socketio/socket.io) - Enables real-time bidirectional event-based communication. :star:42410
- [Faye](https://github.com/faye/faye) - Real-time client-server message bus, based on Bayeux protocol. :star:4102
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores. :star:4763
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in. :star:3603
- [deepstream.io](https://github.com/deepstreamIO/deepstream.io-client-js) - Scalable real-time microservice framework. :star:213
- [Kalm](https://github.com/kalm/kalm.js) - Low-level socket router and middleware framework. :star:56
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - Client for MQTT - Pub-sub based messaging protocol for use on top of TCP/IP. :star:3340


### Image

- [sharp](https://github.com/lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images. :star:8689
- [image-type](https://github.com/sindresorhus/image-type) - Detect the image type of a Buffer/Uint8Array. :star:145
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick and ImageMagick wrapper. :star:5056
- [lwip](https://github.com/EyalAr/lwip) - Lightweight image processor which does not require ImageMagick. :star:2096
- [pica](https://github.com/nodeca/pica) - High quality & fast resize (lanczos3) in pure JS. Alternative to canvas drawImage(), when no pixelation allowed. :star:1257
- [jimp](https://github.com/oliver-moran/jimp) - Image processing in pure JavaScript. :star:6461
- [probe-image-size](https://github.com/nodeca/probe-image-size) - Get the size of most image formats without a full download. :star:191


### Text

- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings. :star:1732
- [string-length](https://github.com/sindresorhus/string-length) - Get the real length of a string - by correctly counting astral symbols and ignoring ansi escape codes. :star:55
- [camelcase](https://github.com/sindresorhus/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar. :star:212
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - Escape RegExp special characters. :star:240
- [execall](https://github.com/sindresorhus/execall) - Find multiple RegExp matches in a string. :star:68
- [splice-string](https://github.com/sindresorhus/splice-string) - Remove or replace part of a string like `Array#splice`. :star:13
- [indent-string](https://github.com/sindresorhus/indent-string) - Indent each line in a string. :star:56
- [strip-indent](https://github.com/sindresorhus/strip-indent) - Strip leading whitespace from every line in a string. :star:75
- [detect-indent](https://github.com/sindresorhus/detect-indent) - Detect the indentation of code. :star:110
- [he](https://github.com/mathiasbynens/he) - HTML entity encoder/decoder. :star:1545
- [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage. :star:2076
- [babelfish](https://github.com/nodeca/babelfish) - i18n with very easy syntax for plurals. :star:185
- [matcher](https://github.com/sindresorhus/matcher) - Simple wildcard matching. :star:385
- [unhomoglyph](https://github.com/nodeca/unhomoglyph) - Normalize visually similar unicode characters. :star:12
- [i18next](https://github.com/i18next/i18next) - Internationalization framework. :star:3334


### Number

- [random-int](https://github.com/sindresorhus/random-int) - Generate a random integer. :star:34
- [random-float](https://github.com/sindresorhus/random-float) - Generate a random float. :star:17
- [unique-random](https://github.com/sindresorhus/unique-random) - Generate random numbers that are consecutively unique. :star:57
- [round-to](https://github.com/sindresorhus/round-to) - Round a number to a specific number of decimal places: `1.234` → `1.2`. :star:84


### Math

- [ndarray](https://github.com/scijs/ndarray) - Multidimensional arrays. :star:762
- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library. :star:6699
- [math-clamp](https://github.com/sindresorhus/math-clamp) - Clamp a number. :star:4
- [algebra](https://github.com/fibo/algebra) - Algebraic structures. :star:60
- [multimath](https://github.com/nodeca/multimath) - Core to create fast image math in WebAssembly and JS. :star:27


### Date

- [Luxon](https://github.com/moment/luxon) - Library for working with dates and times. :star:6498
- [date-fns](https://github.com/date-fns/date-fns) - Modern date utility. :star:10988
- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.
- [dateformat](https://github.com/felixge/node-dateformat) - Date formatting. :star:848
- [tz-format](https://github.com/samverschueren/tz-format) - Format a date with timezone: `2015-11-30T10:40:35+01:00`. :star:5
- [cctz](https://github.com/floatdrop/node-cctz) - Fast parsing, formatting, and timezone conversation for dates. :star:53


### URL

- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL. :star:257
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Humanize a URL: http://sindresorhus.com → sindresorhus.com. :star:62
- [url-unshort](https://github.com/nodeca/url-unshort) - Expand shortened URLs. :star:31
- [speakingurl](https://github.com/pid/speakingurl) - Generate a slug from a string with transliteration. :star:946
- [linkify-it](https://github.com/markdown-it/linkify-it) - Link patterns detector with full unicode support. :star:229
- [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for URLs and other strings. :star:376
- [embedza](https://github.com/nodeca/embedza) - Create HTML snippets/embeds from URLs using info from oEmbed, Open Graph, meta tags. :star:35


### Data validation

- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects. :star:8395
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast. :star:823
- [property-validator](https://github.com/nettofarah/property-validator) - Easy property validation for Express. :star:142
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API sanitization and validation. :star:450
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON Schema validator. Supports v5 proposals. :star:3717


### Parsing

- [remark](https://github.com/wooorm/remark) - Markdown processor powered by plugins. :star:1563
- [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser with 100% CommonMark support, extensions and syntax plugins. :star:5590
- [parse5](https://github.com/inikulin/parse5) - Fast full-featured spec compliant HTML parser. :star:1763
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - Strip comments from JSON. :star:365
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - Strip comments from CSS. :star:78
- [parse-json](https://github.com/sindresorhus/parse-json) - Parse JSON with more helpful errors. :star:130
- [URI.js](https://github.com/medialize/URI.js) - URL mutation. :star:5339
- [PostCSS](https://github.com/postcss/postcss) - CSS parser / stringifier. :star:18784
- [JSONStream](https://github.com/dominictarr/JSONStream) - Streaming JSON.parse and stringify. :star:1513
- [neat-csv](https://github.com/sindresorhus/neat-csv) - Fast CSV parser. Callback interface for the above. :star:67
- [csv-parser](https://github.com/mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else. :star:519
- [PEG.js](https://github.com/pegjs/pegjs) - Simple parser generator that produces fast parsers with excellent error reporting. :star:2834
- [x-ray](https://github.com/lapwinglabs/x-ray) - Web scraping utility. :star:4401
- [nearley](https://github.com/Hardmath123/nearley) - Simple, fast, powerful parsing for JavaScript. :star:1844
- [binary-extract](https://github.com/juliangruber/binary-extract) - Extract a value from a buffer of JSON without parsing the whole thing. :star:142
- [Stylecow](https://github.com/stylecow/stylecow) - Parse, manipulate and convert modern CSS to make it compatible with all browsers. Extensible with plugins. :star:125
- [js-yaml](https://github.com/nodeca/js-yaml) - Very fast YAML parser. :star:3083
- [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter. :star:3236
- [Jison](https://github.com/zaach/jison) - Friendly JavaScript parser generator. It shares genes with Bison, Yacc and family. :star:3092
- [google-libphonenumber](https://github.com/seegno/google-libphonenumber) - Parse, format, store and validate phone numbers. :star:504
- [ref](https://github.com/TooTallNate/ref) - Read/write structured binary data in Buffers. :star:283
- [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Read/write Excel XLSX. :star:215
- [Chevrotain](https://github.com/SAP/chevrotain) - Very fast and feature rich parser building toolkit for JavaScript. :star:757
- [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - Validate and parse XML. :star:221


### Humanize

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - Convert bytes to a human readable string: `1337` → `1.34 kB`. :star:368
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`. :star:298
- [ms](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility. :star:1514
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - Errors with less clutter. :star:941
- [read-art](https://github.com/Tjatse/node-readability) - Extract readable content from any page. :star:259


### Compression

- [yazl](https://github.com/thejoshwolfe/yazl) - Zip. :star:151
- [yauzl](https://github.com/thejoshwolfe/yauzl) - Unzip. :star:308
- [Archiver](https://github.com/archiverjs/node-archiver) - Streaming interface for archive generation, supporting ZIP and TAR. :star:1259
- [pako](https://github.com/nodeca/pako) - High speed zlib port to pure js (deflate, inflate, gzip). :star:1703
- [tar-stream](https://github.com/mafintosh/tar-stream) - Streaming tar parser and generator. Also see [tar-fs](https://github.com/mafintosh/tar-fs). :star:214
- [decompress](https://github.com/kevva/decompress) - Decompression module with support for `tar`, `tar.gz` and `zip` files out of the box. :star:224


### Network

- [get-port](https://github.com/sindresorhus/get-port) - Get an available port. :star:243
- [ipify](https://github.com/sindresorhus/ipify) - Get your public IP address. :star:138
- [getmac](https://github.com/bevry/getmac) - Get the computer MAC address. :star:143
- [DHCP](https://github.com/infusion/node-dhcp) - DHCP client and server. :star:114
- [netcat](https://github.com/roccomuso/netcat) - Netcat port in pure JS. :star:195


### Database

- Drivers
	- [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client. Pure JavaScript and native libpq bindings. :star:6238
	- [Redis](https://github.com/luin/ioredis) - Redis client. :star:4329
	- [LevelUP](https://github.com/Level/levelup) - LevelDB. :star:3286
	- [MySQL](https://github.com/mysqljs/mysql) - MySQL client. :star:12302
	- [couchdb-nano](https://github.com/apache/couchdb-nano) - CouchDB client. :star:175
	- [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Aerospike client. :star:149
	- [Couchbase](https://github.com/couchbase/couchnode) - Couchbase client. :star:375
	- [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB driver. :star:6989
- ODM / ORM
	- [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL. :star:14907
	- [Bookshelf](https://github.com/bookshelf/bookshelf) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js. :star:4985
	- [Massive](https://github.com/robconery/massive-js) - PostgreSQL data access tool.
	- [Mongoose](https://github.com/Automattic/mongoose) - Elegant MongoDB object modeling. :star:16137
	- [Waterline](https://github.com/balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases. :star:4645
	- [OpenRecord](https://github.com/PhilWaldmann/openrecord) - ORM for PostgreSQL, MySQL, SQLite3 and RESTful datastores. Similar to ActiveRecord. :star:279
	- [orm2](https://github.com/dresende/node-orm2) - ORM for PostgreSQL, MariaDB, MySQL, Amazon Redshift, SQLite, MongoDB. :star:2860
	- [pg-promise](https://github.com/vitaly-t/pg-promise) - PostgreSQL framework for native SQL using promises. :star:1836
	- [Objection.js](https://github.com/Vincit/objection.js) - Lightweight ORM built on the SQL query builder Knex. :star:2811
	- [TypeORM](https://github.com/typeorm/typeorm) - ORM for PostgreSQL, MariaDB, MySQL, SQLite, and more. :star:6983
- Query builder
	- [Knex](https://github.com/tgriesser/knex) - Query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use. :star:7233
- Other
	- [NeDB](https://github.com/louischatriot/nedb) - Embedded persistent database written in JavaScript. :star:8451
	- [Lowdb](https://github.com/typicode/lowdb) - Small JavaScript database powered by Lodash. :star:8176
	- [Keyv](https://github.com/lukechilds/keyv) - Simple key-value storage with support for multiple backends. :star:544
	- [Finale](https://github.com/tommybananas/finale) - RESTful endpoint generator for your Sequelize models. :star:54
	- [database-js](https://github.com/mlaanderson/database-js) - Wrapper for multiple databases with a JDBC-like connection. :star:8


### Testing

- [AVA](https://ava.li) - Futuristic test runner.
- [Mocha](http://mochajs.org) - Feature-rich test framework making asynchronous testing simple and fun.
- [nyc](https://github.com/bcoe/nyc) - Code coverage tool built on istanbul that works with subprocesses. :star:2673
- [tap](https://github.com/isaacs/node-tap) - TAP test framework. :star:1239
- [tape](https://github.com/substack/tape) - TAP-producing test harness. :star:4650
- [power-assert](https://github.com/power-assert-js/power-assert) - Provides descriptive assertion messages through the standard assert interface. :star:2021
- [Mochify](https://github.com/mantoni/mochify.js) - TDD with Browserify, Mocha, PhantomJS and WebDriver. :star:309
- [trevor](https://github.com/vdemedes/trevor) - Run tests against multiple versions of Node.js without switching versions manually or pushing to Travis CI. :star:2042
- [loadtest](https://github.com/alexfernandez/loadtest) - Run load tests for your web application, with an API for automation. :star:1269
- [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs and mocks. :star:6051
- [navit](https://github.com/nodeca/navit) - PhantomJS / SlimerJS wrapper to simplify browser test scripting. :star:41
- [Nock](https://github.com/pgte/nock) - HTTP mocking and expectations. :star:6485
- [intern](https://github.com/theintern/intern) - Code testing stack. :star:4015
- [toxy](https://github.com/h2non/toxy) - Hackable HTTP proxy to simulate failure scenarios and network conditions. :star:2427
- [hook-std](https://github.com/sindresorhus/hook-std) - Hook and modify stdout/stderr. :star:29
- [testen](https://github.com/egoist/testen) - Run tests for multiple versions of Node.js locally with NVM. :star:162
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - Automated UI testing framework based on Selenium WebDriver. :star:8285
- [WebdriverIO](https://github.com/webdriverio/webdriverio) - Automated testing based on the WebDriver protocol. :star:4083
- [Jest](https://github.com/facebook/jest) - Painless JavaScript testing. :star:18603
- [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing. :star:4941
- [abstruse](https://github.com/bleenco/abstruse) - Continuous Integration server. :star:275


### Security

- [snyk](https://github.com/Snyk/snyk) - CLI and build-time tool to find & fix vulnerable npm dependencies. :star:1123
- [upash](https://github.com/simonepri/upash) - Unified API for all password hashing algorithms. :star:101


### Benchmarking

- [Benchmark.js](https://github.com/bestiejs/benchmark.js) - Benchmarking library that supports high-resolution timers and returns statistically significant results. :star:3590
- [matcha](https://github.com/logicalparadox/matcha) - Simplistic approach to benchmarking. :star:484


### Minifiers

- [babili](https://github.com/babel/babili) - ES2015+ aware minifier based on the Babel toolchain. :star:3421
- [UglifyJS2](https://github.com/mishoo/UglifyJS2) - JavaScript minifier. :star:8813
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS minifier. :star:2940
- [minimize](https://github.com/Swaagie/minimize) - HTML minifier. :star:140
- [imagemin](https://github.com/imagemin/imagemin) - Image minifier. :star:2233


### Authentication

- [Passport](https://github.com/jaredhanson/passport) - Simple, unobtrusive authentication. :star:13643
- [Grant](https://github.com/simov/grant) - OAuth middleware for Express, Koa, and Hapi. :star:1510
- [CloudRail](https://github.com/CloudRail/cloudrail-si-node-sdk) - Unified API for social authentication (Facebook, Twitter, Slack, Instagram, …). :star:241


### Authorization

- [CASL](https://github.com/stalniy/casl) - Isomorphic authorization for UI and API. :star:577


### Email

- [Nodemailer](https://github.com/andris9/Nodemailer) - The fastest way to handle email. :star:9672
- [emailjs](https://github.com/eleith/emailjs) - Send text/HTML emails with attachments to any SMTP server. :star:1631
- [email-templates](https://github.com/niftylettuce/email-templates) - Create, preview, and send custom email templates. :star:2058


### Job queues

- [kue](https://github.com/Automattic/kue) - Redis-backed priority job queue. :star:7563
- [bull](https://github.com/OptimalBits/bull) - Persistent job and message queue. :star:3134
- [agenda](https://github.com/rschmukler/agenda) - MongoDB-backed job scheduling. :star:4211
- [idoit](https://github.com/nodeca/idoit) - Redis-backed job queue engine with advanced job control. :star:26
- [node-resque](https://github.com/taskrabbit/node-resque) - Redis-backed job queue. :star:545
- [rsmq](https://github.com/smrchy/rsmq) - Redis-backed message queue. :star:768
- [bee-queue](https://github.com/bee-queue/bee-queue) - High-performance Redis-backed job queue. :star:951


### Node.js management

- [n](https://github.com/tj/n) - Node.js version management. :star:9413
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.js. :star:1138
- [nodeenv](https://github.com/ekalinin/nodeenv) - Node.js virtual environment compatible to Python's virtualenv. :star:904
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Version management for Windows. :star:6204


### Natural language processing

- [retext](https://github.com/wooorm/retext) - An extensible natural language system. :star:1537
- [franc](https://github.com/wooorm/franc) - Detect the language of text. :star:2668
- [leven](https://github.com/sindresorhus/leven) - Measure the difference between two strings using the Levenshtein distance algorithm. :star:353
- [natural](https://github.com/NaturalNode/natural) - Natural language facility. :star:7889


### Process management

- [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager. :star:25272
- [nodemon](https://github.com/remy/nodemon) - Monitor for changes in your app and automatically restart the server. :star:15058
- [node-mac](https://github.com/coreybutler/node-mac) - Run scripts as a native Mac daemon and log to the console app. :star:425
- [node-linux](https://github.com/coreybutler/node-linux) - Run scripts as native system service and log to syslog. :star:340
- [node-windows](https://github.com/coreybutler/node-windows) - Run scripts as a native Windows service and log to the Event viewer. :star:1465
- [supervisor](https://github.com/petruisfan/node-supervisor) - Restart scripts when they crash or restart when a `*.js` file changes. :star:3415
- [Phusion Passenger](https://github.com/phusion/passenger) - Friendly process manager that integrates directly into Nginx. :star:4100


### Automation

- [robotjs](https://github.com/octalmage/robotjs) - Desktop Automation: control the mouse, keyboard and read the screen. :star:7066


### AST

- [Acorn](https://github.com/ternjs/acorn) - Tiny, fast JavaScript parser. :star:3631
- [babel-parser](https://github.com/babel/babel/tree/master/packages/babel-parser) - JavaScript parser used in Babel.


### Static site generators

- [Wintersmith](https://github.com/jnordberg/wintersmith) - Flexible, minimalistic, multi-platform static site generator. :star:3348
- [Assemble](https://github.com/assemble/assemble/) - Static site generator for Node.js, Grunt.js, and Yeoman.
- [DocPad](https://github.com/docpad/docpad) - Static site generator with dynamic abilities and huge plugin ecosystem. :star:2968
- [Phenomic](https://github.com/phenomic/phenomic) - Modern static website generator based on the React and Webpack ecosystem. :star:3023
- [docsify](https://github.com/QingWei-Li/docsify) - Markdown documentation site generator with no statically built HTML files. :star:6567


### Content management systems

- [KeystoneJS](https://github.com/keystonejs/keystone) - CMS and web application platform built on Express and MongoDB. :star:12879
- [ApostropheCMS](https://github.com/apostrophecms/apostrophe) - Content management system with an emphasis on intuitive front end content editing and administration built on Express and MongoDB. :star:2198
- [Strapi](https://github.com/strapi/strapi) - Content Management Framework (headless-CMS) to build powerful APIs. :star:5886


### Forum

- [nodeBB](https://github.com/NodeBB/NodeBB) - Forum platform for the modern web. :star:8858


### Blogging

- [Ghost](https://github.com/TryGhost/Ghost) - Simple, powerful publishing platform. :star:26005
- [Hexo](https://github.com/hexojs/hexo) - Fast, simple and powerful blogging framework. :star:22625


### Weird

- [cows](https://github.com/sindresorhus/cows) - ASCII cows. :star:290
- [superb](https://github.com/sindresorhus/superb) - Get superb like words. :star:259
- [cat-names](https://github.com/sindresorhus/cat-names) - Get popular cat names. :star:195
- [dog-names](https://github.com/sindresorhus/dog-names) - Get popular dog names. :star:83
- [superheroes](https://github.com/sindresorhus/superheroes) - Get superhero names. :star:166
- [supervillains](https://github.com/sindresorhus/supervillains) - Get supervillain names. :star:71
- [cool-ascii-faces](https://github.com/maxogden/cool-ascii-faces) - Get some cool ascii faces. :star:1592
- [cat-ascii-faces](https://github.com/melaniecebula/cat-ascii-faces) - ₍˄·͈༝·͈˄₎◞ ̑̑ෆ⃛ (=ↀωↀ=)✧ (^･o･^)ﾉ” :star:191
- [nerds](https://github.com/SkyHacks/nerds) - Get data from nerdy topics like Harry Potter, Star Wars, and Pokémon. :star:48


### Serialization

- [snappy](https://github.com/kesla/node-snappy) - Native bindings for Google's Snappy compression library. :star:367
- [protobuf](https://github.com/dcodeIO/protobuf.js) - Implementation of Protocol Buffers. :star:4504
- [compactr](https://github.com/compactr/compactr.js) - Implementation of the Compactr protocol. :star:70


### Miscellaneous

- [execa](https://github.com/sindresorhus/execa) - Better `child_process`. :star:1383
- [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server. :star:16464
- [Electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies. *(You might like [awesome-electron](https://github.com/sindresorhus/awesome-electron))* :star:61878
- [opn](https://github.com/sindresorhus/opn) - Opens stuff like websites, files, executables. :star:1080
- [hasha](https://github.com/sindresorhus/hasha) - Hashing made simple. Get the hash of a buffer/string/stream/file. :star:608
- [dot-prop](https://github.com/sindresorhus/dot-prop) - Get a property from a nested object using a dot path. :star:271
- [onetime](https://github.com/sindresorhus/onetime) - Only run a function once. :star:76
- [mem](https://github.com/sindresorhus/mem) - Memoize functions - an optimization technique used to speed up consecutive function calls by caching the result of calls with identical input. :star:359
- [import-fresh](https://github.com/sindresorhus/import-fresh) - Import a module while bypassing the cache. :star:138
- [strip-bom](https://github.com/sindresorhus/strip-bom) - Strip UTF-8 byte order mark (BOM) from a string/buffer/stream. :star:66
- [os-locale](https://github.com/sindresorhus/os-locale) - Get the system locale. :star:123
- [ssh2](https://github.com/mscdex/ssh2) - SSH2 client and server module. :star:3080
- [adit](https://github.com/markelog/adit) - SSH tunneling made simple. :star:19
- [import-lazy](https://github.com/sindresorhus/import-lazy) - Import a module lazily. :star:144
- [file-type](https://github.com/sindresorhus/file-type) - Detect the file type of a Buffer. :star:679
- [Bottleneck](https://github.com/SGrondin/bottleneck) - Rate limiter that makes throttling easy. :star:438
- [ow](https://github.com/sindresorhus/ow) - Function argument validation for humans. :star:2313
- [webworker-threads](https://github.com/audreyt/node-webworker-threads) - Lightweight Web Worker API implementation with native threads. :star:1782
- [clipboardy](https://github.com/sindresorhus/clipboardy) - Access the system clipboard (copy/paste). :star:414
- [node-pre-gyp](https://github.com/mapbox/node-pre-gyp) - Makes it easy to publish and install Node.js C++ addons from binaries. :star:537
- [opencv](https://github.com/peterbraden/node-opencv) - Bindings for OpenCV. The defacto computer vision library. :star:3457
- [dotenv](https://github.com/motdotla/dotenv) - Load environment variables from .env file. :star:6294
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - Get tags from a remote git repo. :star:29
- [semver](https://github.com/npm/node-semver) - Semantic version parser. :star:2296
- [Faker.js](https://github.com/Marak/Faker.js) - Generate massive amounts of fake data. :star:14675
- [nodegit](https://github.com/nodegit/nodegit) - Native bindings to Git. :star:3477
- [json-strictify](https://github.com/pigulla/json-strictify) - Safely serialize a value to JSON without data loss or going into an infinite loop. :star:3
- [resolve-from](https://github.com/sindresorhus/resolve-from) - Resolve the path of a module like `require.resolve()` but from a given path. :star:61
- [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - Event driven web crawler. :star:1728
- [jsdom](https://github.com/tmpvar/jsdom) - JavaScript implementation of HTML and the DOM. :star:10136
- [hypernova](https://github.com/airbnb/hypernova) - Server-side rendering your JavaScript views. :star:4249
- [@sindresorhus/is](https://github.com/sindresorhus/is) - Type check values. :star:641
- [env-dot-prop](https://github.com/simonepri/env-dot-prop) - Get, set, or delete nested properties of process.env using a dot path. :star:10
- [emittery](https://github.com/sindresorhus/emittery) - Simple and modern async event emitter. :star:709


## Resources

### Tutorials

- [Nodeschool](http://nodeschool.io) - Learn Node.js with interactive lessons.
- [The Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node) - An introduction to Node.js.
- [stream-handbook](https://github.com/substack/stream-handbook) - How to write Node.js programs with streams. :star:11713
- [module-best-practices](https://github.com/mattdesl/module-best-practices) - Some good practices when writing new npm modules. :star:1121
- [The Node Way](http://thenodeway.io) - An entire philosophy of Node.js best practices and guiding principles exists for writing maintainable modules, scalable applications, and code that is actually pleasant to read.
- [You Don't Know Node.js](https://github.com/azat-co/you-dont-know-node) - Introduction to Node.js core features and asynchronous JavaScript. :star:885


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
- [Art of README](https://github.com/noffle/art-of-readme) - Learn the art of writing quality READMEs. :star:4734

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
- [Stream FAQs](https://github.com/stephenplusplus/stream-faqs) - Answering common questions about streams, covering pagination, events, and more. :star:161

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
- [node-module-boilerplate](https://github.com/sindresorhus/node-module-boilerplate) - Boilerplate to kickstart creating a node module. :star:406
- [generator-nm](https://github.com/sindresorhus/generator-nm) - Scaffold out a node module. :star:554
- [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) - Tips, tricks, and resources for working with Node.js on Microsoft platforms. :star:1913
- [Module Requests & Ideas](https://github.com/sindresorhus/module-requests) - Request a JavaScript module you wish existed or get ideas for modules. :star:407


## Related lists

- [awesome-npm](https://github.com/sindresorhus/awesome-npm) - Resources and tips for using npm. :star:2948
- [awesome-cross-platform-nodejs](https://github.com/bcoe/awesome-cross-platform-nodejs) - Resources for writing and testing cross-platform code. :star:242


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.


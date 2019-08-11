# Information comes from [sindresorhus/awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs)
<div align="center">
	<div>
		<img width="500" src="media/logo.svg" alt="Awesome Node.js">
	</div>
	<br>
	<br>
	<br>
	<a href="https://awesome.re">
		<img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
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
	- [Books](#books)
	- [Blogs](#blogs)
	- [Courses](#courses)
	- [Cheatsheets](#cheatsheets)
	- [Tools](#tools)
	- [Community](#community)
	- [Miscellaneous](#miscellaneous)


## Packages

### Mad science

- [webtorrent](https://github.com/feross/webtorrent) - Streaming torrent client for Node.js and the browser. :star:20021
- [peerflix](https://github.com/mafintosh/peerflix) - Streaming torrent client. :star:5202
- [dat](https://github.com/datproject/dat-node) - Real-time replication and versioning for data sets. :star:455
- [ipfs](https://github.com/ipfs/js-ipfs) - Distributed file system that seeks to connect all computing devices with the same system of files. :star:3877
- [stackgl](https://github.com/stackgl) - Open software ecosystem for WebGL, built on top of browserify and npm.
- [peerwiki](https://github.com/mafintosh/peerwiki) - All of Wikipedia on BitTorrent. :star:291
- [peercast](https://github.com/mafintosh/peercast) - Stream a torrent video to Chromecast. :star:432
- [BitcoinJS](https://github.com/bitcoinjs/bitcoinjs-lib) - Clean, readable, proven Bitcoin library. :star:3587
- [Bitcore](https://github.com/bitpay/bitcore) - Pure and powerful Bitcoin library. :star:3330
- [PDFKit](https://github.com/devongovett/pdfkit) - PDF generation library. :star:5472
- [turf](https://github.com/Turfjs/turf) - Modular geospatial processing and analysis engine. :star:4607
- [webcat](https://github.com/mafintosh/webcat) - p2p pipe across the web using WebRTC that uses your GitHub private/public key for authentication. :star:399
- [NodeOS](https://github.com/NodeOS/NodeOS) - The first operating system powered by npm. :star:5999
- [YodaOS](https://github.com/yodaos-project/yodaos) - AI operating system. :star:934
- [Brain.js](https://github.com/BrainJS/brain.js) - Machine-learning framework. :star:9990
- [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) - Graph theory (a.k.a. network) modeling and analysis. :star:5875
- [Kadence](https://gitlab.com/deadcanaries/kadence) - Kademlia distributed hash table.
- [seedshot](https://github.com/twobucks/seedshot) - Temporary P2P screenshot sharing from your browser. :star:179
- [js-git](https://github.com/creationix/js-git) - JavaScript implementation of Git. :star:3576
- [skale](https://github.com/skale-me/skale-engine) - High performance distributed data processing engine. :star:349
- [xlsx](https://github.com/sheetjs/js-xlsx) - Pure JS Excel spreadsheet reader and writer. :star:17131
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - Pure JavaScript implementation of Git. :star:3970


### Command-line apps

- [np](https://github.com/sindresorhus/np) - Better `npm publish`. :star:4568
- [npm-name](https://github.com/sindresorhus/npm-name) - Check a package name's availability on npm. :star:108
- [gh-home](https://github.com/sindresorhus/gh-home) - Open the GitHub page of the repo in the current directory. :star:150
- [npm-home](https://github.com/sindresorhus/npm-home) - Open the npm page of a package. :star:158
- [trash](https://github.com/sindresorhus/trash) - Safer alternative to `rm`. :star:1840
- [speed-test](https://github.com/sindresorhus/speed-test) - Test your internet connection speed and ping. :star:3192
- [emoj](https://github.com/sindresorhus/emoj) - Find relevant emoji from text on the command-line. :star:1821
- [pageres](https://github.com/sindresorhus/pageres) - Capture website screenshots. :star:8858
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:227
- [vtop](https://github.com/MrRio/vtop) - More better top, with nice charts. :star:3362
- [empty-trash](https://github.com/sindresorhus/empty-trash) - Empty the trash. :star:102
- [is-up](https://github.com/sindresorhus/is-up) - Check whether a website is up or down. :star:320
- [is-online](https://github.com/sindresorhus/is-online) - Check if the internet connection is up. :star:768
- [public-ip](https://github.com/sindresorhus/public-ip) - Get your public IP address. :star:426
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - Copy & paste on the terminal. :star:332
- [XO](https://github.com/xojs/xo) - Enforce strict code style using the JavaScript happiness style. :star:4640
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style — One style to rule them all. :star:21794
- [ESLint](https://github.com/eslint/eslint) - The pluggable linting utility for JavaScript. :star:14634
- [dev-time](https://github.com/samverschueren/dev-time-cli) - Get the current local time of a GitHub user. :star:165
- [David](https://github.com/alanshaw/david) - Tells you when your package npm dependencies are out of date. :star:887
- [http-server](https://github.com/indexzero/http-server) - Simple, zero-config command-line HTTP server. :star:8603
- [Live Server](https://github.com/tapio/live-server) - Development HTTP-server with livereload capability. :star:2827
- [bcat](https://github.com/kessler/node-bcat) - Pipe command output to web browsers. :star:283
- [normit](https://github.com/pawurb/normit) - Google Translate with speech synthesis in your terminal. :star:198
- [fkill](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform. :star:5668
- [pjs](https://github.com/danielstjules/pjs) - Pipeable JavaScript. Quickly filter, map, and reduce from the terminal. :star:360
- [license-checker](https://github.com/davglass/license-checker) - Check licenses of your app's dependencies. :star:876
- [browser-run](https://github.com/juliangruber/browser-run) - Easily run code in a browser environment. :star:345
- [tmpin](https://github.com/sindresorhus/tmpin) - Adds stdin support to any CLI app that accepts file input. :star:110
- [wifi-password](https://github.com/kevva/wifi-password-cli) - Get the current wifi password. :star:176
- [wallpaper](https://github.com/sindresorhus/wallpaper) - Change the desktop wallpaper. :star:631
- [brightness](https://github.com/kevva/brightness-cli) - Change the screen brightness. :star:161
- [torrent](https://github.com/maxogden/torrent) - Download torrents. :star:549
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - Kill all Chrome tabs to improve performance, decrease battery usage, and save memory. :star:245
- [alex](https://github.com/wooorm/alex) - Catch insensitive, inconsiderate writing. :star:3096
- [pen](https://github.com/noraesae/pen) - Live Markdown preview in the browser from your favorite editor. :star:278
- [subdownloader](https://github.com/beatfreaker/subdownloader) - Subtitle downloader for movies and TV series. :star:115
- [dark-mode](https://github.com/sindresorhus/dark-mode) - Toggle the macOS Dark Mode. :star:437
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP location finder. :star:210
- [Jsome](https://github.com/Javascipt/Jsome) - Pretty prints JSON with configurable colors and indentation. :star:158
- [itunes-remote](https://github.com/mischah/itunes-remote) - Interactively control iTunes. :star:378
- [mobicon](https://github.com/samverschueren/mobicon-cli) - Mobile app icon generator. :star:72
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - Mobile app splash screen generator. :star:42
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - Pretty git diff to HTML generator. :star:197
- [Cash](https://github.com/dthree/cash) - Cross-platform Unix shell commands in pure JavaScript. :star:7634
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - Try out npm packages in the terminal. :star:1026
- [jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for source code. :star:1350
- [atmo](https://github.com/Raathigesh/Atmo) - Server-side API mocking. :star:773
- [auto-install](https://github.com/siddharthkp/auto-install) - Auto installs dependencies as you code. :star:1021
- [lessmd](https://github.com/linuxenko/lessmd) - Markdown in the terminal. :star:104
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - Find out which dependencies are slowing you down. :star:2444
- [localtunnel](https://github.com/localtunnel/localtunnel) - Expose your localhost to the world. :star:8721
- [svg-term-cli](https://github.com/marionebl/svg-term-cli) - Share terminal sessions via SVG. :star:1414
- [gtop](https://github.com/aksakalli/gtop) - System monitoring dashboard for the terminal. :star:7743
- [themer](https://github.com/mjswensen/themer) - Generate themes for your editor, terminal, wallpaper, Slack, and more. :star:2096
- [carbon-now-cli](https://github.com/mixn/carbon-now-cli) - Beautiful images of your code — from right inside your terminal. :star:4159
- [cash-cli](https://github.com/xxczaki/cash-cli) - Convert between 170 currencies. :star:108
- [taskbook](https://github.com/klauscfhq/taskbook) - Tasks, boards & notes for the command-line habitat. :star:7052
- [discharge](https://github.com/brandonweiss/discharge) - Easily deploy static websites to Amazon S3. :star:382


### Functional programming

- [lodash](https://github.com/lodash/lodash) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js. :star:40802
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections. :star:28044
- [Ramda](https://github.com/ramda/ramda) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data. :star:16842
- [Folktale](https://github.com/origamitower/folktale) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse. :star:1603
- [Mout](https://github.com/mout/mout) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead. :star:1140
- [Bacon.js](https://github.com/baconjs/bacon.js) - Functional reactive programming. :star:6140
- [RxJS](https://github.com/reactivex/rxjs) - Functional reactive library for transforming, composing, and querying various kinds of data. :star:19416
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases. :star:5720
- [Kefir.js](https://github.com/kefirjs/kefir) - Reactive library with focus on high performance and low memory usage. :star:1588


### HTTP

- [got](https://github.com/sindresorhus/got) - Nicer interface to the built-in `http` module. :star:5622
- [gh-got](https://github.com/sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API. :star:135
- [axios](https://github.com/mzabriskie/axios) - Promise based HTTP client (works in the browser too). :star:63109
- [request](https://github.com/request/request) - Simplified HTTP request client. :star:23130
- [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities. :star:357
- [download](https://github.com/kevva/download) - Download and extract files effortlessly. :star:884
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP proxy. :star:10410
- [superagent](https://github.com/visionmedia/superagent) - HTTP request library. :star:14381
- [node-fetch](https://github.com/bitinn/node-fetch) - `window.fetch` for Node.js. :star:4236
- [flashheart](https://github.com/bbc/flashheart) - REST client. :star:107
- [http-fake-backend](https://github.com/micromata/http-fake-backend) - Build a fake backend by providing the content of JSON files or JavaScript objects through configurable routes. :star:203
- [cacheable-request](https://github.com/lukechilds/cacheable-request) - Wrap native HTTP requests with RFC compliant cache support. :star:183
- [gotql](https://github.com/khaosdoctor/gotql) - GraphQL request library built on [got](https://github.com/sindresorhus/got). :star:199
- [global-agent](https://github.com/gajus/global-agent) – Global HTTP/HTTPS proxy agent that is configurable using environment variables.


### Debugging / Profiling

- [ndb](https://github.com/GoogleChromeLabs/ndb) - Improved debugging experience, enabled by Chrome DevTools. :star:9355
- [ironNode](https://github.com/s-a/iron-node) - Node.js debugger supporting ES2015 out of the box. :star:2376
- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools. :star:12449
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility. :star:7876
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - Node.js is running but you don't know why? :star:975
- [njsTrace](https://github.com/valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function. :star:254
- [vstream](https://github.com/joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams. :star:56
- [stackman](https://github.com/watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies. :star:196
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables. :star:265
- [0x](https://github.com/davidmarkclements/0x) - Flamegraph profiling. :star:1565
- [ctrace](https://github.com/automation-stack/ctrace) - Well-formatted and improved trace system calls and signals. :star:104
- [leakage](https://github.com/andywer/leakage) - Write memory leak tests. :star:1384
- [llnode](https://github.com/nodejs/llnode) - Post-mortem analysis tool which allows you to inspect objects and get insights from a crashed Node.js process. :star:726
- [thetool](https://github.com/sfninja/thetool) - Capture different CPU, memory, and other profiles for your app in Chrome DevTools friendly format. :star:55


### Logging

- [pino](https://github.com/pinojs/pino) - Extremely fast logger inspired by Bunyan. :star:4364
- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library. :star:13814
- [console-log-level](https://github.com/watson/console-log-level) - The most simple logger imaginable with support for log levels and custom prefixes. :star:47
- [storyboard](https://github.com/guigrpa/storyboard) - End-to-end, hierarchical, real-time, colorful logs and stories. :star:565
- [signale](https://github.com/klauscfhq/signale) - Hackable console logger with beautiful output. :star:7706


### Command-line utilities

- [chalk](https://github.com/chalk/chalk) - Terminal string styling done right. :star:12769
- [meow](https://github.com/sindresorhus/meow) - CLI app helper. :star:1896
- [yargs](https://github.com/yargs/yargs) - Command-line parser that automatically generates an elegant user-interface. :star:6584
- [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner. :star:5072
- [get-stdin](https://github.com/sindresorhus/get-stdin) - Easier stdin. :star:231
- [log-update](https://github.com/sindresorhus/log-update) - Log by overwriting the previous output in the terminal. Useful for rendering progress bars, animations, etc. :star:681
- [Ink](https://github.com/vadimdemedes/ink) - React for interactive command-line apps. :star:11827
- [listr](https://github.com/samverschueren/listr) - Terminal task list. :star:2218
- [conf](https://github.com/sindresorhus/conf) - Simple config handling for your app or module. :star:455
- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - ANSI escape codes for manipulating the terminal. :star:264
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels. :star:445
- [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows CMD fallbacks. :star:361
- [boxen](https://github.com/sindresorhus/boxen) - Create boxes in the terminal. :star:582
- [terminal-link](https://github.com/sindresorhus/terminal-link) - Create clickable links in the terminal. :star:211
- [terminal-image](https://github.com/sindresorhus/terminal-image) - Display images in the terminal. :star:434
- [string-width](https://github.com/sindresorhus/string-width) - Get the visual width of a string - the number of columns required to display it. :star:155
- [cli-truncate](https://github.com/sindresorhus/cli-truncate) - Truncate a string to a specific width in the terminal. :star:43
- [first-run](https://github.com/sindresorhus/first-run) - Check if it's the first time the process is run. :star:65
- [blessed](https://github.com/chjj/blessed) - Curses-like library. :star:8578
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt. :star:10726
- [yn](https://github.com/sindresorhus/yn) - Parse yes/no like values. :star:161
- [cli-table3](https://github.com/cli-table/cli-table3) - Pretty unicode tables. :star:85
- [drawille](https://github.com/madbence/node-drawille) - Draw on the terminal with unicode braille characters. :star:822
- [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app. :star:1243
- [ascii-charts](https://github.com/jstrace/chart) - ASCII bar chart in the terminal. :star:221
- [progress](https://github.com/tj/node-progress) - Flexible ascii progress bar. :star:2256
- [insight](https://github.com/yeoman/insight) - Helps you understand how your tool is being used by anonymously reporting usage metrics to Google Analytics. :star:475
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - Toggle the CLI cursor. :star:59
- [columnify](https://github.com/timoxley/columnify) - Create text-based columns suitable for console output. Supports cell wrapping. :star:341
- [cli-columns](https://github.com/shannonmoeller/cli-columns) - Columnated unicode and ansi-safe text lists. :star:18
- [cfonts](https://github.com/dominikwilkowski/cfonts) - Sexy ASCII fonts for the console. :star:504
- [multispinner](https://github.com/codekirei/node-multispinner) - Multiple, simultaneous, individually controllable CLI spinners. :star:250
- [omelette](https://github.com/f/omelette) - Shell autocompletion helper. :star:853
- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform. :star:4043
- [shelljs](https://github.com/shelljs/shelljs) - Portable Unix shell commands. :star:10045
- [sudo-block](https://github.com/sindresorhus/sudo-block) - Block users from running your app with root permissions. :star:75
- [loud-rejection](https://github.com/sindresorhus/loud-rejection) - Make unhandled promise rejections fail loudly instead of the default silent fail. :star:244
- [sparkly](https://github.com/sindresorhus/sparkly) - Generate sparklines `▁▂▃▅▂▇`. :star:302
- [Bit](https://github.com/teambit/bit) - Create, maintain, find and use small modules and components across repositories. :star:8346
- [gradient-string](https://github.com/bokub/gradient-string) - Beautiful color gradients in terminal output. :star:374
- [oclif](https://github.com/oclif/oclif) - CLI framework complete with parser, automatic documentation, testing, and plugins. :star:3827
- [term-size](https://github.com/sindresorhus/term-size) - Reliably get the terminal window size. :star:91
- [Cliffy](https://github.com/drew-y/cliffy) - Framework for interactive CLIs. :star:202


### Build tools

- [parcel](https://github.com/parcel-bundler/parcel) - Blazing fast, zero config web app bundler. :star:32643
- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser. :star:50392
- [rollup](https://github.com/rollup/rollup) - Next-generation ES2015 module bundler. :star:16259
- [gulp](https://github.com/gulpjs/gulp) - Streaming and fast build system that favors code over config. :star:31360
- [Broccoli](https://github.com/broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions. :star:3222
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow. :star:6598
- [Start](https://github.com/deepsweet/start) - Functional task runner with shareable presets. :star:480
- [ygor](https://github.com/shannonmoeller/ygor) - Promising task runner for when `npm run` isn't enough and everything else is too much. :star:63
- [FuseBox](https://github.com/fuse-box/fuse-box) - Fast build system that combines the power of webpack, JSPM and SystemJS, with first-class TypeScript support. :star:3810
- [pkg](https://github.com/zeit/pkg) - Package your Node.js project into an executable. :star:14147


### Hardware

- [johnny-five](https://github.com/rwaldron/johnny-five) - Firmata based Arduino Framework. :star:10743
- [serialport](https://github.com/voodootikigod/node-serialport) - Access serial ports for reading and writing. :star:4039
- [usb](https://github.com/nonolith/node-usb) - USB library. :star:831
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C serial bus access. :star:191
- [onoff](https://github.com/fivdi/onoff) - GPIO access and interrupt detection. :star:836
- [spi-device](https://github.com/fivdi/spi-device) - SPI serial bus access. :star:68
- [pigpio](https://github.com/fivdi/pigpio) - Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi. :star:535
- [gps](https://github.com/infusion/GPS.js) - NMEA parser for handling GPS receivers. :star:102


### Templating

- [marko](https://github.com/marko-js/marko) - HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags. :star:9125
- [nunjucks](https://github.com/mozilla/nunjucks) - Templating engine with inheritance, asynchronous control, and more (jinja2 inspired). :star:6198
- [handlebars.js](https://github.com/wycats/handlebars.js) - Superset of Mustache templates which adds powerful features like helpers and more advanced blocks. :star:14681
- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language. :star:3715
- [Pug](https://github.com/pugjs/pug) - High-performance template engine heavily influenced by Haml. :star:18509


### Web frameworks

- [Hapi](https://github.com/hapijs/hapi) - Framework for building applications and services. :star:11342
- [Koa](https://github.com/koajs/koa) - Framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs. :star:26959
- [Express](https://github.com/expressjs/express) - Web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications. :star:45012
- [Feathers](https://github.com/feathersjs/feathers) - Microservice framework built in the spirit of Express. :star:11252
- [LoopBack](https://github.com/strongloop/loopback) - Powerful framework for creating REST APIs and easily connecting to backend data sources. :star:12806
- [Meteor](https://github.com/meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))* :star:41246
- [Restify](https://github.com/restify/node-restify) - Enables you to build correct REST web services. :star:9372
- [ThinkJS](https://github.com/thinkjs/thinkjs) - Framework with ES2015+ support, WebSockets, REST API. :star:4916
- [ActionHero](https://github.com/actionhero/actionhero) - Framework for making reusable & scalable APIs for TCP sockets, WebSockets, and HTTP clients. :star:2013
- [MERN](https://github.com/Hashnode/mern-cli) - Easily build production-ready universal apps with MongoDB, Express, React, and webpack. :star:577
- [Next.js](https://github.com/zeit/next.js) - Minimalistic framework for server-rendered universal JavaScript web apps. :star:39849
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Minimalistic framework for server-rendered Vue.js apps. :star:21679
- [seneca](https://github.com/senecajs/seneca) - Toolkit for writing microservices. :star:3479
- [AdonisJs](http://adonisjs.com) - A true MVC framework for Node.js built on solid foundations of Dependency Injection and IoC container.
- [Hemera](https://github.com/hemerajs/hemera) - Write reliable and fault-tolerant microservices with [NATS](https://nats.io). :star:681
- [Micro](https://github.com/zeit/micro) - Minimalistic microservice framework with an async approach. :star:8604
- [Moleculer](https://moleculer.services) - Fast & powerful microservices framework.
- [Fastify](https://github.com/fastify/fastify) - Fast and low overhead web framework. :star:11494
- [Nest](https://github.com/nestjs/nest) - Angular-inspired framework for building efficient and scalable server-side apps. :star:18435
- [Zeronode](https://github.com/sfast/zeronode) - Minimal building block for reliable and fault-tolerant microservices. :star:92
- [TypeGraphQL](https://github.com/19majkel94/type-graphql) - Modern framework for creating GraphQL APIs with TypeScript, using classes and decorators. :star:2606


### Documentation

- [documentation.js](https://github.com/documentationjs/documentation) - API documentation generator with support for ES2015+ and flow annotation. :star:4713
- [ESDoc](https://github.com/esdoc/esdoc) - Documentation generator targeting ES2015, attaching test code and measuring documentation coverage. :star:2481
- [Docco](https://github.com/jashkenas/docco) - Documentation generator which produces an HTML document that displays your comments intermingled with your code. :star:3415
- [JSDoc](https://github.com/jsdoc3/jsdoc) - API documentation generator similar to JavaDoc or PHPDoc. :star:9597


### Filesystem

- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs. :star:994
- [globby](https://github.com/sindresorhus/globby) - Glob files with support for multiple patterns. :star:1194
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:227
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like `rm -rf`. :star:3323
- [make-dir](https://github.com/sindresorhus/make-dir) - Recursively create directories like `mkdir -p`. :star:384
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Drop-in replacement for the `fs` module with various improvements. :star:874
- [chokidar](https://github.com/paulmillr/chokidar) - Filesystem watcher which stabilizes events from `fs.watch` and `fs.watchFile` as well as using native `fsevents` on macOS. :star:5664
- [find-up](https://github.com/sindresorhus/find-up) - Find a file by walking up parent directories. :star:243
- [proper-lockfile](https://github.com/IndigoUnited/node-proper-lockfile) - Inter-process and inter-machine lockfile utility. :star:85
- [load-json-file](https://github.com/sindresorhus/load-json-file) - Read and parse a JSON file. :star:148
- [write-json-file](https://github.com/sindresorhus/write-json-file) - Stringify and write JSON to a file atomically. :star:127
- [fs-write-stream-atomic](https://github.com/npm/fs-write-stream-atomic) - Like `fs.createWriteStream()`, but atomic. :star:46
- [filenamify](https://github.com/sindresorhus/filenamify) - Convert a string to a valid filename. :star:252
- [lnfs](https://github.com/kevva/lnfs) - Force create symlinks like `ln -fs`. :star:9
- [istextorbinary](https://github.com/bevry/istextorbinary) - Check if a file is text or binary. :star:57
- [fs-jetpack](https://github.com/szwacz/fs-jetpack) - Completely redesigned file system API for convenience in everyday use. :star:484
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module. :star:5986
- [pkg-dir](https://github.com/sindresorhus/pkg-dir) - Find the root directory of an npm package. :star:105
- [filehound](https://github.com/nspragg/filehound) - Flexible and fluent interface for searching the file system. :star:153
- [move-file](https://github.com/sindresorhus/move-file) - Move a file, even works across devices. :star:121
- [tempy](https://github.com/sindresorhus/tempy) - Get a random temporary file or directory path. :star:188


### Control flow

- Promises
	- [Bluebird](https://github.com/petkaantonov/bluebird) - Promise library with focus on innovative features and performance. :star:18474
	- [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function. :star:1184
	- [delay](https://github.com/sindresorhus/delay) - Delay a promise a specified amount of time. :star:337
	- [promise-memoize](https://github.com/nodeca/promise-memoize) - Memoize promise-returning functions, with expire and prefetch. :star:41
	- [valvelet](https://github.com/lpinca/valvelet) - Limit the execution rate of a promise-returning function. :star:21
	- [p-map](https://github.com/sindresorhus/p-map) - Map over promises concurrently. :star:448
	- [More…](https://github.com/sindresorhus/promise-fun) :star:2571
- Observables
	- [zen-observable](https://github.com/zenparsing/zen-observable) - Implementation of Observables. :star:545
	- [RxJS](https://github.com/ReactiveX/RxJS) - Reactive programming. :star:19416
	- [observable-to-promise](https://github.com/sindresorhus/awesome-observables) - Convert an Observable to a Promise. :star:247
	- [More…](https://github.com/sindresorhus/awesome-observables) :star:247
- Streams
	- [Highland.js](https://github.com/caolan/highland) - Manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams. :star:3188
- Callbacks
	- [each-async](https://github.com/sindresorhus/each-async) - Async concurrent iterator like forEach. :star:105
	- [async](https://github.com/caolan/async) - Provides straight-forward, powerful functions for working with asynchronicity. :star:25883
- Channels
	- [js-csp](https://github.com/ubolonton/js-csp) - Communicating sequential processes for JavaScript (like Clojurescript core.async, or Go). :star:2222


### Streams

- [through2](https://github.com/rvagg/through2) - Tiny wrapper around streams2 Transform to avoid explicit subclassing noise. :star:1603
- [from2](https://github.com/hughsk/from2) - Convenience wrapper for ReadableStream, inspired by `through2`. :star:111
- [get-stream](https://github.com/sindresorhus/get-stream) - Get a stream as a string or buffer. :star:178
- [into-stream](https://github.com/sindresorhus/into-stream) - Convert a buffer/string/array/object into a stream. :star:134
- [duplexify](https://github.com/mafintosh/duplexify) - Turn a writeable and readable stream into a single streams2 duplex stream. :star:156
- [pumpify](https://github.com/mafintosh/pumpify) - Combine an array of streams into a single duplex stream. :star:162
- [peek-stream](https://github.com/mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it. :star:45
- [binary-split](https://github.com/maxogden/binary-split) - Newline (or any delimiter) splitter stream. :star:66
- [byline](https://github.com/jahewson/node-byline) - Super-simple line-by-line Stream reader. :star:283
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - Transform the first chunk in a stream. :star:21
- [pad-stream](https://github.com/sindresorhus/pad-stream) - Pad each line in a stream. :star:5
- [multistream](https://github.com/feross/multistream) - Combine multiple streams into a single stream. :star:188
- [stream-combiner2](https://github.com/substack/stream-combiner2) - Turn a pipeline into a single stream. :star:74
- [readable-stream](https://github.com/nodejs/readable-stream) - Mirror of Streams2 and Streams3 implementations in core. :star:764
- [through2-concurrent](https://github.com/almost/through2-concurrent) - Transform object streams concurrently. :star:69


### Real-time

- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - Highly scalable WebSocket server & client library. :star:10792
- [Socket.io](https://github.com/socketio/socket.io) - Enables real-time bidirectional event-based communication. :star:47177
- [Faye](https://github.com/faye/faye) - Real-time client-server message bus, based on Bayeux protocol. :star:4211
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores. :star:5383
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in. :star:3946
- [deepstream.io](https://github.com/deepstreamIO/deepstream.io-client-js) - Scalable real-time microservice framework. :star:242
- [Kalm](https://github.com/kalm/kalm.js) - Low-level socket router and middleware framework. :star:90
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - Client for MQTT - Pub-sub based messaging protocol for use on top of TCP/IP. :star:4704
- [rpc-websockets](https://github.com/elpheria/rpc-websockets) - JSON-RPC 2.0 implementation over WebSockets. :star:186
- [Aedes](https://github.com/mcollina/aedes) - Barebone MQTT server that can run on any stream server. :star:440


### Image

- [sharp](https://github.com/lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images. :star:13658
- [image-type](https://github.com/sindresorhus/image-type) - Detect the image type of a Buffer/Uint8Array. :star:184
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick and ImageMagick wrapper. :star:5765
- [lwip](https://github.com/EyalAr/lwip) - Lightweight image processor which does not require ImageMagick. :star:2213
- [pica](https://github.com/nodeca/pica) - High quality & fast resize (lanczos3) in pure JS. Alternative to canvas drawImage(), when no pixelation allowed. :star:1706
- [jimp](https://github.com/oliver-moran/jimp) - Image processing in pure JavaScript. :star:8747
- [probe-image-size](https://github.com/nodeca/probe-image-size) - Get the size of most image formats without a full download. :star:260
- [qrcode](https://github.com/soldair/node-qrcode) - QR code and bar code generator. :star:3136


### Text

- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings. :star:2131
- [string-length](https://github.com/sindresorhus/string-length) - Get the real length of a string - by correctly counting astral symbols and ignoring ansi escape codes. :star:71
- [camelcase](https://github.com/sindresorhus/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar. :star:350
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - Escape RegExp special characters. :star:318
- [execall](https://github.com/sindresorhus/execall) - Find multiple RegExp matches in a string. :star:75
- [splice-string](https://github.com/sindresorhus/splice-string) - Remove or replace part of a string like `Array#splice`. :star:14
- [indent-string](https://github.com/sindresorhus/indent-string) - Indent each line in a string. :star:72
- [strip-indent](https://github.com/sindresorhus/strip-indent) - Strip leading whitespace from every line in a string. :star:87
- [detect-indent](https://github.com/sindresorhus/detect-indent) - Detect the indentation of code. :star:133
- [he](https://github.com/mathiasbynens/he) - HTML entity encoder/decoder. :star:2208
- [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage. :star:2383
- [babelfish](https://github.com/nodeca/babelfish) - i18n with very easy syntax for plurals. :star:203
- [matcher](https://github.com/sindresorhus/matcher) - Simple wildcard matching. :star:431
- [unhomoglyph](https://github.com/nodeca/unhomoglyph) - Normalize visually similar unicode characters. :star:14
- [i18next](https://github.com/i18next/i18next) - Internationalization framework. :star:4357


### Number

- [random-int](https://github.com/sindresorhus/random-int) - Generate a random integer. :star:48
- [random-float](https://github.com/sindresorhus/random-float) - Generate a random float. :star:19
- [unique-random](https://github.com/sindresorhus/unique-random) - Generate random numbers that are consecutively unique. :star:70
- [round-to](https://github.com/sindresorhus/round-to) - Round a number to a specific number of decimal places: `1.234` → `1.2`. :star:99


### Math

- [ndarray](https://github.com/scijs/ndarray) - Multidimensional arrays. :star:872
- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library. :star:8818
- [math-clamp](https://github.com/sindresorhus/math-clamp) - Clamp a number. :star:6
- [algebra](https://github.com/fibo/algebra) - Algebraic structures. :star:78
- [multimath](https://github.com/nodeca/multimath) - Core to create fast image math in WebAssembly and JS. :star:38


### Date

- [Luxon](https://github.com/moment/luxon) - Library for working with dates and times. :star:8524
- [date-fns](https://github.com/date-fns/date-fns) - Modern date utility. :star:18826
- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.
- [Day.js](https://github.com/iamkun/dayjs) - Immutable date library alternative to Moment.js. :star:22755
- [dateformat](https://github.com/felixge/node-dateformat) - Date formatting. :star:1012
- [tz-format](https://github.com/samverschueren/tz-format) - Format a date with timezone: `2015-11-30T10:40:35+01:00`. :star:6
- [cctz](https://github.com/floatdrop/node-cctz) - Fast parsing, formatting, and timezone conversation for dates. :star:54


### URL

- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL. :star:378
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Humanize a URL: http://sindresorhus.com → sindresorhus.com. :star:179
- [url-unshort](https://github.com/nodeca/url-unshort) - Expand shortened URLs. :star:39
- [speakingurl](https://github.com/pid/speakingurl) - Generate a slug from a string with transliteration. :star:1004
- [linkify-it](https://github.com/markdown-it/linkify-it) - Link patterns detector with full unicode support. :star:308
- [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for URLs and other strings. :star:457
- [embedza](https://github.com/nodeca/embedza) - Create HTML snippets/embeds from URLs using info from oEmbed, Open Graph, meta tags. :star:44


### Data validation

- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects. :star:12738
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast. :star:877
- [property-validator](https://github.com/nettofarah/property-validator) - Easy property validation for Express. :star:146
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API sanitization and validation. :star:456
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON Schema validator. Supports v5, v6 and v7 proposals. :star:6015


### Parsing

- [remark](https://github.com/wooorm/remark) - Markdown processor powered by plugins. :star:2408
- [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser with 100% CommonMark support, extensions and syntax plugins. :star:7834
- [parse5](https://github.com/inikulin/parse5) - Fast full-featured spec compliant HTML parser. :star:2150
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - Strip comments from JSON. :star:431
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - Strip comments from CSS. :star:92
- [parse-json](https://github.com/sindresorhus/parse-json) - Parse JSON with more helpful errors. :star:145
- [URI.js](https://github.com/medialize/URI.js) - URL mutation. :star:5753
- [PostCSS](https://github.com/postcss/postcss) - CSS parser / stringifier. :star:21265
- [JSONStream](https://github.com/dominictarr/JSONStream) - Streaming JSON.parse and stringify. :star:1675
- [neat-csv](https://github.com/sindresorhus/neat-csv) - Fast CSV parser. Callback interface for the above. :star:121
- [csv-parser](https://github.com/mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else. :star:685
- [PEG.js](https://github.com/pegjs/pegjs) - Simple parser generator that produces fast parsers with excellent error reporting. :star:3371
- [x-ray](https://github.com/lapwinglabs/x-ray) - Web scraping utility. :star:5048
- [nearley](https://github.com/Hardmath123/nearley) - Simple, fast, powerful parsing for JavaScript. :star:2245
- [binary-extract](https://github.com/juliangruber/binary-extract) - Extract a value from a buffer of JSON without parsing the whole thing. :star:142
- [Stylecow](https://github.com/stylecow/stylecow) - Parse, manipulate and convert modern CSS to make it compatible with all browsers. Extensible with plugins. :star:135
- [js-yaml](https://github.com/nodeca/js-yaml) - Very fast YAML parser. :star:3948
- [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter. :star:3726
- [Jison](https://github.com/zaach/jison) - Friendly JavaScript parser generator. It shares genes with Bison, Yacc and family. :star:3429
- [google-libphonenumber](https://github.com/seegno/google-libphonenumber) - Parse, format, store and validate phone numbers. :star:712
- [ref](https://github.com/TooTallNate/ref) - Read/write structured binary data in Buffers. :star:338
- [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Read/write Excel XLSX. :star:428
- [Chevrotain](https://github.com/SAP/chevrotain) - Very fast and feature rich parser building toolkit for JavaScript. :star:1132
- [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - Validate and parse XML. :star:517


### Humanize

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - Convert bytes to a human readable string: `1337` → `1.34 kB`. :star:488
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`. :star:398
- [ms](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility. :star:2384
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - Errors with less clutter. :star:1251
- [read-art](https://github.com/Tjatse/node-readability) - Extract readable content from any page. :star:287


### Compression

- [yazl](https://github.com/thejoshwolfe/yazl) - Zip. :star:198
- [yauzl](https://github.com/thejoshwolfe/yauzl) - Unzip. :star:421
- [Archiver](https://github.com/archiverjs/node-archiver) - Streaming interface for archive generation, supporting ZIP and TAR. :star:1643
- [pako](https://github.com/nodeca/pako) - High speed zlib port to pure js (deflate, inflate, gzip). :star:2430
- [tar-stream](https://github.com/mafintosh/tar-stream) - Streaming tar parser and generator. Also see [tar-fs](https://github.com/mafintosh/tar-fs). :star:260
- [decompress](https://github.com/kevva/decompress) - Decompression module with support for `tar`, `tar.gz` and `zip` files out of the box. :star:269


### Network

- [get-port](https://github.com/sindresorhus/get-port) - Get an available port. :star:405
- [ipify](https://github.com/sindresorhus/ipify) - Get your public IP address. :star:163
- [getmac](https://github.com/bevry/getmac) - Get the computer MAC address. :star:196
- [DHCP](https://github.com/infusion/node-dhcp) - DHCP client and server. :star:162
- [netcat](https://github.com/roccomuso/netcat) - Netcat port in pure JS. :star:245


### Database

- Drivers
	- [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client. Pure JavaScript and native libpq bindings. :star:7605
	- [Redis](https://github.com/luin/ioredis) - Redis client. :star:6273
	- [LevelUP](https://github.com/Level/levelup) - LevelDB. :star:3584
	- [MySQL](https://github.com/mysqljs/mysql) - MySQL client. :star:14369
	- [couchdb-nano](https://github.com/apache/couchdb-nano) - CouchDB client. :star:308
	- [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Aerospike client. :star:159
	- [Couchbase](https://github.com/couchbase/couchnode) - Couchbase client. :star:414
	- [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB driver. :star:8078
- ODM / ORM
	- [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL. :star:19577
	- [Bookshelf](https://github.com/bookshelf/bookshelf) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js. :star:5617
	- [Massive](https://github.com/robconery/massive-js) - PostgreSQL data access tool. :star:2543
	- [Mongoose](https://github.com/Automattic/mongoose) - Elegant MongoDB object modeling. :star:19203
	- [Waterline](https://github.com/balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases. :star:5046
	- [OpenRecord](https://github.com/PhilWaldmann/openrecord) - ORM for PostgreSQL, MySQL, SQLite3 and RESTful datastores. Similar to ActiveRecord. :star:423
	- [pg-promise](https://github.com/vitaly-t/pg-promise) - PostgreSQL framework for native SQL using promises. :star:2330
	- [slonik](https://github.com/gajus/slonik) - PostgreSQL client with strict types, detailed logging and assertions. :star:849
	- [Objection.js](https://github.com/Vincit/objection.js) - Lightweight ORM built on the SQL query builder Knex. :star:4280
	- [TypeORM](https://github.com/typeorm/typeorm) - ORM for PostgreSQL, MariaDB, MySQL, SQLite, and more. :star:14432
- Query builder
	- [Knex](https://github.com/tgriesser/knex) - Query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use. :star:10222
- Other
	- [NeDB](https://github.com/louischatriot/nedb) - Embedded persistent database written in JavaScript. :star:10234
	- [Lowdb](https://github.com/typicode/lowdb) - Small JavaScript database powered by Lodash. :star:11154
	- [Keyv](https://github.com/lukechilds/keyv) - Simple key-value storage with support for multiple backends. :star:850
	- [Finale](https://github.com/tommybananas/finale) - RESTful endpoint generator for your Sequelize models. :star:117
	- [database-js](https://github.com/mlaanderson/database-js) - Wrapper for multiple databases with a JDBC-like connection. :star:23
	- [Mongo Seeding](https://github.com/pkosiec/mongo-seeding) - Populate MongoDB databases with JavaScript and JSON files. :star:128


### Testing

- [AVA](https://github.com/avajs/ava) - Futuristic test runner. :star:16661
- [Mocha](https://github.com/mochajs/mocha) - Feature-rich test framework making asynchronous testing simple and fun. :star:18246
- [nyc](https://github.com/bcoe/nyc) - Code coverage tool built on istanbul that works with subprocesses. :star:3634
- [tap](https://github.com/isaacs/node-tap) - TAP test framework. :star:1431
- [tape](https://github.com/substack/tape) - TAP-producing test harness. :star:5091
- [power-assert](https://github.com/power-assert-js/power-assert) - Provides descriptive assertion messages through the standard assert interface. :star:2369
- [Mochify](https://github.com/mantoni/mochify.js) - TDD with Browserify, Mocha, PhantomJS and WebDriver. :star:330
- [trevor](https://github.com/vdemedes/trevor) - Run tests against multiple versions of Node.js without switching versions manually or pushing to Travis CI. :star:2157
- [loadtest](https://github.com/alexfernandez/loadtest) - Run load tests for your web application, with an API for automation. :star:1691
- [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs and mocks. :star:7357
- [navit](https://github.com/nodeca/navit) - PhantomJS / SlimerJS wrapper to simplify browser test scripting. :star:44
- [Nock](https://github.com/pgte/nock) - HTTP mocking and expectations. :star:8332
- [intern](https://github.com/theintern/intern) - Code testing stack. :star:4131
- [toxy](https://github.com/h2non/toxy) - Hackable HTTP proxy to simulate failure scenarios and network conditions. :star:2584
- [hook-std](https://github.com/sindresorhus/hook-std) - Hook and modify stdout/stderr. :star:43
- [testen](https://github.com/egoist/testen) - Run tests for multiple versions of Node.js locally with NVM. :star:172
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - Automated UI testing framework based on Selenium WebDriver. :star:9506
- [WebdriverIO](https://github.com/webdriverio/webdriverio) - Automated testing based on the WebDriver protocol. :star:5125
- [Jest](https://github.com/facebook/jest) - Painless JavaScript testing. :star:26918
- [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing. :star:7258
- [abstruse](https://github.com/bleenco/abstruse) - Continuous Integration server. :star:526
- [CodeceptJS](https://github.com/Codeception/CodeceptJS) - End-to-end testing. :star:2329


### Security

- [upash](https://github.com/simonepri/upash) - Unified API for all password hashing algorithms. :star:438
- [themis](https://github.com/cossacklabs/themis) - Multilanguage framework for making typical encryption schemes easy to use: data at rest, authenticated data exchange, transport protection, authentication, and so on. :star:815
- [GuardRails](https://github.com/apps/guardrails) - GitHub app that provides security feedback in pull requests.
- [rate-limiter-flexible](https://github.com/animir/node-rate-limiter-flexible) - Brute-force and DDoS attack protection. :star:457
- [crypto-hash](https://github.com/sindresorhus/crypto-hash) - Async non-blocking hashing. :star:388


### Benchmarking

- [Benchmark.js](https://github.com/bestiejs/benchmark.js) - Benchmarking library that supports high-resolution timers and returns statistically significant results. :star:4228
- [matcha](https://github.com/logicalparadox/matcha) - Simplistic approach to benchmarking. :star:514


### Minifiers

- [babili](https://github.com/babel/babili) - ES2015+ aware minifier based on the Babel toolchain. :star:3869
- [UglifyJS2](https://github.com/mishoo/UglifyJS2) - JavaScript minifier. :star:10150
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS minifier. :star:3316
- [minimize](https://github.com/Swaagie/minimize) - HTML minifier. :star:145
- [imagemin](https://github.com/imagemin/imagemin) - Image minifier. :star:3296


### Authentication

- [Passport](https://github.com/jaredhanson/passport) - Simple, unobtrusive authentication. :star:16074
- [Grant](https://github.com/simov/grant) - OAuth middleware for Express, Koa, and Hapi. :star:2358
- [CloudRail](https://github.com/CloudRail/cloudrail-si-node-sdk) - Unified API for social authentication (Facebook, Twitter, Slack, Instagram, …). :star:267


### Authorization

- [CASL](https://github.com/stalniy/casl) - Isomorphic authorization for UI and API. :star:1463
- [node-casbin](https://github.com/casbin/node-casbin) - Authorization library that supports access control models like ACL, RBAC and ABAC. :star:565


### Email

- [Nodemailer](https://github.com/andris9/Nodemailer) - The fastest way to handle email. :star:11503
- [emailjs](https://github.com/eleith/emailjs) - Send text/HTML emails with attachments to any SMTP server. :star:1758
- [email-templates](https://github.com/niftylettuce/email-templates) - Create, preview, and send custom email templates. :star:2542


### Job queues

- [bull](https://github.com/OptimalBits/bull) - Persistent job and message queue. :star:6188
- [agenda](https://github.com/rschmukler/agenda) - MongoDB-backed job scheduling. :star:5616
- [idoit](https://github.com/nodeca/idoit) - Redis-backed job queue engine with advanced job control. :star:42
- [node-resque](https://github.com/taskrabbit/node-resque) - Redis-backed job queue. :star:738
- [rsmq](https://github.com/smrchy/rsmq) - Redis-backed message queue. :star:1103
- [bee-queue](https://github.com/bee-queue/bee-queue) - High-performance Redis-backed job queue. :star:1483
- [RedisSMQ](https://github.com/weyoss/redis-smq) - Simple high-performance Redis message queue with real-time monitoring. :star:152
- [sqs-consumer](https://github.com/bbc/sqs-consumer) - Build Amazon Simple Queue Service (SQS) based apps without the boilerplate. :star:683
- [better-queue](https://github.com/diamondio/better-queue) - Simple and efficient job queue when you cannot use Redis. :star:204


### Node.js management

- [n](https://github.com/tj/n) - Node.js version management. :star:11733
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.js. :star:1318
- [nodeenv](https://github.com/ekalinin/nodeenv) - Node.js virtual environment compatible to Python's virtualenv. :star:1088
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Version management for Windows. :star:9707
- [nodenv](https://github.com/nodenv/nodenv) - Version manager that is similar to Ruby's rbenv. It supports auto version switching. :star:965


### Natural language processing

- [retext](https://github.com/wooorm/retext) - An extensible natural language system. :star:1796
- [franc](https://github.com/wooorm/franc) - Detect the language of text. :star:3030
- [leven](https://github.com/sindresorhus/leven) - Measure the difference between two strings using the Levenshtein distance algorithm. :star:449
- [natural](https://github.com/NaturalNode/natural) - Natural language facility. :star:8742
- [nlp.js](https://github.com/axa-group/nlp.js) - Building bots, with entity extraction, sentiment analysis, automatic language identify, and more. :star:2932


### Process management

- [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager. :star:30038
- [nodemon](https://github.com/remy/nodemon) - Monitor for changes in your app and automatically restart the server. :star:18733
- [node-mac](https://github.com/coreybutler/node-mac) - Run scripts as a native Mac daemon and log to the console app. :star:444
- [node-linux](https://github.com/coreybutler/node-linux) - Run scripts as native system service and log to syslog. :star:357
- [node-windows](https://github.com/coreybutler/node-windows) - Run scripts as a native Windows service and log to the Event viewer. :star:1759
- [supervisor](https://github.com/petruisfan/node-supervisor) - Restart scripts when they crash or restart when a `*.js` file changes. :star:3598
- [Phusion Passenger](https://github.com/phusion/passenger) - Friendly process manager that integrates directly into Nginx. :star:4423


### Automation

- [robotjs](https://github.com/octalmage/robotjs) - Desktop Automation: control the mouse, keyboard and read the screen. :star:8154


### AST

- [Acorn](https://github.com/ternjs/acorn) - Tiny, fast JavaScript parser. :star:4971
- [babel-parser](https://github.com/babel/babel/tree/master/packages/babel-parser) - JavaScript parser used in Babel. :star:34139
- [cherow](https://github.com/cherow/cherow) - JavaScript parser with focus on performance and stability. :star:1545


### Static site generators

- [Wintersmith](https://github.com/jnordberg/wintersmith) - Flexible, minimalistic, multi-platform static site generator. :star:3480
- [Assemble](https://github.com/assemble/assemble/) - Static site generator for Node.js, Grunt.js, and Yeoman. :star:3701
- [DocPad](https://github.com/docpad/docpad) - Static site generator with dynamic abilities and huge plugin ecosystem. :star:2995
- [Phenomic](https://github.com/phenomic/phenomic) - Modern static website generator based on the React and Webpack ecosystem. :star:3258
- [docsify](https://github.com/QingWei-Li/docsify) - Markdown documentation site generator with no statically built HTML files. :star:10750


### Content management systems

- [KeystoneJS](https://github.com/keystonejs/keystone) - CMS and web application platform built on Express and MongoDB. :star:14686
- [ApostropheCMS](https://github.com/apostrophecms/apostrophe) - Content management system with an emphasis on intuitive front end content editing and administration built on Express and MongoDB. :star:2763
- [Strapi](https://github.com/strapi/strapi) - Content Management Framework (headless-CMS) to build powerful APIs. :star:16516
- [Tipe](https://github.com/tipeio/tipe) - Developer-first content management system with GraphQL and REST API from a schema file. :star:1961


### Forum

- [nodeBB](https://github.com/NodeBB/NodeBB) - Forum platform for the modern web. :star:10310


### Blogging

- [Ghost](https://github.com/TryGhost/Ghost) - Simple, powerful publishing platform. :star:30603
- [Hexo](https://github.com/hexojs/hexo) - Fast, simple and powerful blogging framework. :star:27590


### Weird

- [cows](https://github.com/sindresorhus/cows) - ASCII cows. :star:330
- [superb](https://github.com/sindresorhus/superb) - Get superb like words. :star:334
- [cat-names](https://github.com/sindresorhus/cat-names) - Get popular cat names. :star:209
- [dog-names](https://github.com/sindresorhus/dog-names) - Get popular dog names. :star:97
- [superheroes](https://github.com/sindresorhus/superheroes) - Get superhero names. :star:192
- [supervillains](https://github.com/sindresorhus/supervillains) - Get supervillain names. :star:92
- [cool-ascii-faces](https://github.com/maxogden/cool-ascii-faces) - Get some cool ascii faces. :star:1690
- [cat-ascii-faces](https://github.com/melaniecebula/cat-ascii-faces) - `₍˄·͈༝·͈˄₎◞ ̑̑ෆ⃛ (=ↀωↀ=)✧ (^･o･^)ﾉ”`. :star:210
- [nerds](https://github.com/SkyHacks/nerds) - Get data from nerdy topics like Harry Potter, Star Wars, and Pokémon. :star:80


### Serialization

- [snappy](https://github.com/kesla/node-snappy) - Native bindings for Google's Snappy compression library. :star:399
- [protobuf](https://github.com/dcodeIO/protobuf.js) - Implementation of Protocol Buffers. :star:5924
- [compactr](https://github.com/compactr/compactr.js) - Implementation of the Compactr protocol. :star:76


### Miscellaneous

- [execa](https://github.com/sindresorhus/execa) - Better `child_process`. :star:2441
- [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server. :star:20098
- [Electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies. *(You might like [awesome-electron](https://github.com/sindresorhus/awesome-electron))* :star:76040
- [open](https://github.com/sindresorhus/open) - Opens stuff like websites, files, executables. :star:1617
- [hasha](https://github.com/sindresorhus/hasha) - Hashing made simple. Get the hash of a buffer/string/stream/file. :star:703
- [dot-prop](https://github.com/sindresorhus/dot-prop) - Get a property from a nested object using a dot path. :star:396
- [onetime](https://github.com/sindresorhus/onetime) - Only run a function once. :star:98
- [mem](https://github.com/sindresorhus/mem) - Memoize functions - an optimization technique used to speed up consecutive function calls by caching the result of calls with identical input. :star:553
- [import-fresh](https://github.com/sindresorhus/import-fresh) - Import a module while bypassing the cache. :star:177
- [strip-bom](https://github.com/sindresorhus/strip-bom) - Strip UTF-8 byte order mark (BOM) from a string/buffer/stream. :star:76
- [os-locale](https://github.com/sindresorhus/os-locale) - Get the system locale. :star:142
- [ssh2](https://github.com/mscdex/ssh2) - SSH2 client and server module. :star:3611
- [adit](https://github.com/markelog/adit) - SSH tunneling made simple. :star:24
- [import-lazy](https://github.com/sindresorhus/import-lazy) - Import a module lazily. :star:180
- [file-type](https://github.com/sindresorhus/file-type) - Detect the file type of a Buffer. :star:1173
- [Bottleneck](https://github.com/SGrondin/bottleneck) - Rate limiter that makes throttling easy. :star:728
- [ow](https://github.com/sindresorhus/ow) - Function argument validation for humans. :star:2793
- [webworker-threads](https://github.com/audreyt/node-webworker-threads) - Lightweight Web Worker API implementation with native threads. :star:2053
- [clipboardy](https://github.com/sindresorhus/clipboardy) - Access the system clipboard (copy/paste). :star:772
- [node-pre-gyp](https://github.com/mapbox/node-pre-gyp) - Makes it easy to publish and install Node.js C++ addons from binaries. :star:684
- [opencv](https://github.com/peterbraden/node-opencv) - Bindings for OpenCV. The defacto computer vision library. :star:3803
- [dotenv](https://github.com/motdotla/dotenv) - Load environment variables from .env file. :star:9594
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - Get tags from a remote git repo. :star:35
- [semver](https://github.com/npm/node-semver) - Semantic version parser. :star:2872
- [Faker.js](https://github.com/Marak/Faker.js) - Generate massive amounts of fake data. :star:19994
- [nodegit](https://github.com/nodegit/nodegit) - Native bindings to Git. :star:4160
- [json-strictify](https://github.com/pigulla/json-strictify) - Safely serialize a value to JSON without data loss or going into an infinite loop. :star:6
- [resolve-from](https://github.com/sindresorhus/resolve-from) - Resolve the path of a module like `require.resolve()` but from a given path. :star:80
- [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - Event driven web crawler. :star:1929
- [jsdom](https://github.com/tmpvar/jsdom) - JavaScript implementation of HTML and the DOM. :star:12673
- [hypernova](https://github.com/airbnb/hypernova) - Server-side rendering your JavaScript views. :star:5205
- [@sindresorhus/is](https://github.com/sindresorhus/is) - Type check values. :star:825
- [env-dot-prop](https://github.com/simonepri/env-dot-prop) - Get, set, or delete nested properties of process.env using a dot path. :star:26
- [emittery](https://github.com/sindresorhus/emittery) - Simple and modern async event emitter. :star:803
- [node-video-lib](https://github.com/gkozlenko/node-video-lib) - Pure JavaScript library for working with MP4 and FLV video files and creating MPEG-TS chunks for HLS streaming. :star:205
- [basic-ftp](https://github.com/patrickjuchli/basic-ftp) – FTP/FTPS client.


## Resources

### Tutorials

- [Node.js Best Practices](https://github.com/i0natan/nodebestpractices) - Summary and curation of the top-ranked content on Node.js best practices, available in multiple languages. :star:31909
- [Nodeschool](https://github.com/nodeschool) - Learn Node.js with interactive lessons.
- [The Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node) - An introduction to Node.js. :star:8317
- [stream-handbook](https://github.com/substack/stream-handbook) - How to write Node.js programs with streams. :star:12554
- [module-best-practices](https://github.com/mattdesl/module-best-practices) - Some good practices when writing new npm modules. :star:1301
- [The Node Way](http://thenodeway.io) - An entire philosophy of Node.js best practices and guiding principles exists for writing maintainable modules, scalable applications, and code that is actually pleasant to read.
- [You Don't Know Node.js](https://github.com/azat-co/you-dont-know-node) - Introduction to Node.js core features and asynchronous JavaScript. :star:1105
- [Portable Node.js guide](https://github.com/ehmicky/portable-node-guide) - Practical guide on how to write portable/cross-platform Node.js code. :star:937

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
- [Art of README](https://github.com/noffle/art-of-readme) - Learn the art of writing quality READMEs. :star:5245
- [Using Express to Quickly Build a GraphQL Server](https://snipcart.com/blog/graphql-nodejs-express-tutorial)

### Newsletters

- [Node Weekly](http://nodeweekly.com) - Weekly e-mail round-up of Node.js news and articles.
- [Node Module Of The Week!](https://nmotw.in) - Weekly dose of hand picked node modules.

### Videos

- [Introduction to Node.js with Ryan Dahl](https://www.youtube.com/watch?v=jo_B4LTHi3I)
- [Hands on with Node.js](https://learn.bevry.me/hands-on-with-node.js/preface)
- [Nodetuts](http://nodetuts.com) - Series of talks, including TCP & HTTP API servers, async programming, and more.
- [V8 Garbage Collector](https://v8.dev/blog/trash-talk) - Trash talk about the V8 garbage collector.

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
- [Practical Modern JavaScript](https://www.amazon.com/Practical-Modern-JavaScript-Dive-Future/dp/149194353X)
- [Mastering Modular JavaScript](https://www.amazon.com/Mastering-Modular-JavaScript-Nicolas-Bevacqua/dp/1491955686/)
- [Get Programming with Node.js](https://www.manning.com/books/get-programming-with-node-js)

### Blogs

- [Node.js blog](https://nodejs.org/en/blog/)
- [webapplog.com](http://webapplog.com/tag/node-js/) - Blog posts on Node.js and JavaScript from the author of Practical Node.js and Pro Express.js Azat Mardan.

### Courses

- [Learn to build apps and APIs with Node.js](https://learnnode.com/friend/AWESOME) - Video course by Wes Bos.
- [Real Time Web with Node.js](https://www.codeschool.com/courses/real-time-web-with-node-js)
- [Learn and Understand Node.js](https://www.udemy.com/understand-nodejs)

### Cheatsheets

- [Express.js](https://github.com/azat-co/cheatsheets/blob/master/express4) :star:1036
- [Stream FAQs](https://github.com/stephenplusplus/stream-faqs) - Answering common questions about streams, covering pagination, events, and more. :star:177
- [Strong Node.js](https://github.com/jesusprubio/strong-node) - Checklist for source code security analysis of a Node.js web service. :star:212

### Tools

- [OctoLinker](https://chrome.google.com/webstore/detail/octolinker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension that linkifies dependencies in package.json, .js, .jsx, .coffee and .md files on GitHub.
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome extension to display npm dependencies at the bottom of a repo's readme.
- [RunKit](http://blog.tonicdev.com/2015/09/30/embedded-tonic.html) - Embed a Node.js environment on any website.
- [RequireBin](http://requirebin.com) - Shareable JavaScript programs powered by npm and browserify.
- [github-npm-stats](https://chrome.google.com/webstore/detail/github-npm-stats/oomfflokggoffaiagenekchfnpighcef) - Chrome extension that displays npm download stats on GitHub.
- [npm semver calculator](https://semver.npmjs.com) - Visually explore what versions of a package a semver range matches.

### Community

- [Gitter](https://gitter.im/nodejs/node)
- [`#node.js` on Freenode](http://webchat.freenode.net/?channels=node.js)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/node.js)
- [Reddit](https://www.reddit.com/r/node)
- [Twitter](https://twitter.com/nodejs)
- [Hashnode](https://hashnode.com/n/nodejs)
- [Discord](https://discordapp.com/invite/96WGtJt)

### Miscellaneous

- [nodebots](http://nodebots.io) - Robots powered by JavaScript.
- [node-module-boilerplate](https://github.com/sindresorhus/node-module-boilerplate) - Boilerplate to kickstart creating a node module. :star:603
- [generator-nm](https://github.com/sindresorhus/generator-nm) - Scaffold out a node module. :star:672
- [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) - Tips, tricks, and resources for working with Node.js on Microsoft platforms. :star:2085
- [Module Requests & Ideas](https://github.com/sindresorhus/module-requests) - Request a JavaScript module you wish existed or get ideas for modules. :star:449


## Related lists

- [awesome-npm](https://github.com/sindresorhus/awesome-npm) - Resources and tips for using npm. :star:3326
- [awesome-cross-platform-nodejs](https://github.com/bcoe/awesome-cross-platform-nodejs) - Resources for writing and testing cross-platform code. :star:763


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](https://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.


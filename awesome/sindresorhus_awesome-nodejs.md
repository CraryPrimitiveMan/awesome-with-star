# Information comes from [sindresorhus/awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs)
# Awesome Node.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://cdn.rawgit.com/gilbarbara/logos/e7b1dc2666c3dabe6c1276abd0a767b6ebd6af43/logos/nodejs-icon.svg" align="right" width="70">](https://nodejs.org)

> A curated list of delightful Node.js [packages](#packages) and [resources](#resources).

Just type [`node.cool`](https://node.cool) to go here ✨

*You might also like [awesome-npm](https://github.com/sindresorhus/awesome-npm).*
*Please read the [contribution guidelines](contributing.md) before contributing.*


---

<p align="center"><sup>🦄 Support <a href="https://github.com/sindresorhus">my open-source work</a> by buying this awesome video course:</sup><br><b><a href="https://learnnode.com/friend/AWESOME">Learn to build apps and APIs with Node.js</a> by Wes Bos</b><br><sub>Try his free <a href="https://javascript30.com/friend/AWESOME">JavaScript 30</a> course for a taste of what to expect & check out his <a href="https://ES6.io/friend/AWESOME">ES6</a>, <a href="https://ReactForBeginners.com/friend/AWESOME">React</a>, <a href="https://SublimeTextBook.com/friend/AWESOME">Sublime</a> courses.</sub></p>

---


<sub>Check out my [blog](https://blog.sindresorhus.com) and say "hi" on [Twitter](https://twitter.com/sindresorhus).</sub>


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
	- [Email](#email)
	- [Job queues](#job-queues)
	- [Node.js management](#nodejs-management)
	- [Polyfills](#polyfills)
	- [Natural language processing](#natural-language-processing)
	- [Process management](#process-management)
	- [Automation](#automation)
	- [AST](#ast)
	- [Static site generators](#static-site-generators)
	- [Content management systems](#content-management-systems)
	- [Forum](#forum)
	- [Blogging](#blogging)
	- [Weird](#weird)
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

- [webtorrent](https://github.com/feross/webtorrent) - Streaming torrent client for Node.js and the browser. :star:15670
- [peerflix](https://github.com/mafintosh/peerflix) - Streaming torrent client. :star:4569
- [dat](http://dat-data.com) - Real-time replication and versioning for data sets.
- [ipfs](https://github.com/ipfs/js-ipfs) - Distributed file system that seeks to connect all computing devices with the same system of files. :star:1737
- [GitTorrent](https://github.com/cjb/GitTorrent) - Peer-to-peer network of Git repositories being shared over BitTorrent. :star:3819
- [stackgl](http://stack.gl) - Open software ecosystem for WebGL, built on top of browserify and npm.
- [peerwiki](https://github.com/mafintosh/peerwiki) - All of Wikipedia on BitTorrent. :star:259
- [peercast](https://github.com/mafintosh/peercast) - Stream a torrent video to Chromecast. :star:362
- [BitcoinJS](http://bitcoinjs.org) - Clean, readable, proven Bitcoin library.
- [Bitcore](https://bitcore.io) - Pure and powerful Bitcoin library.
- [PDFKit](http://pdfkit.org) - PDF generation library.
- [turf](https://github.com/Turfjs/turf) - Modular geospatial processing and analysis engine. :star:3273
- [webcat](https://github.com/mafintosh/webcat) - p2p pipe across the web using WebRTC that uses your GitHub private/public key for authentication. :star:361
- [NodeOS](http://node-os.com) - The first operating system powered by npm.
- [limdu](https://github.com/erelsgl/limdu) - Machine-learning framework. :star:824
- [Cytoscape.js](http://js.cytoscape.org) - Graph theory (a.k.a. network) modeling and analysis.
- [kad](https://github.com/kadtools/kad) - Kademlia distributed hash table. :star:276
- [seedshot](https://github.com/twobucks/seedshot) - Temporary P2P screenshot sharing from your browser. :star:164
- [js-git](https://github.com/creationix/js-git) - JavaScript implementation of Git. :star:3246
- [skale](https://github.com/skale-me/skale-engine) - High performance distributed data processing engine. :star:216


### Command-line apps

- [np](https://github.com/sindresorhus/np) - Better `npm publish`. :star:2800
- [trash](https://github.com/sindresorhus/trash) - Safer alternative to `rm`. :star:1467
- [npm-name](https://github.com/sindresorhus/npm-name) - Check whether a package name is available on npm. :star:67
- [speed-test](https://github.com/sindresorhus/speed-test) - Test your internet connection speed and ping. :star:2883
- [emoj](https://github.com/sindresorhus/emoj) - Find relevant emoji from text on the command-line. :star:1422
- [pageres](https://github.com/sindresorhus/pageres) - Capture website screenshots. :star:8212
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:152
- [vtop](https://github.com/MrRio/vtop) - More better top, with nice charts. :star:2550
- [empty-trash](https://github.com/sindresorhus/empty-trash) - Empty the trash. :star:83
- [is-up](https://github.com/sindresorhus/is-up) - Check whether a website is up or down. :star:268
- [is-online](https://github.com/sindresorhus/is-online) - Check if the internet connection is up. :star:351
- [public-ip](https://github.com/sindresorhus/public-ip) - Get your public IP address. :star:268
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - Copy & paste on the terminal. :star:125
- [ttystudio](https://github.com/chjj/ttystudio) - Record your terminal and compile it to a GIF or APNG without any external dependencies, bash scripts, gif concatenation, etc. :star:2874
- [XO](https://github.com/sindresorhus/xo) - Enforce strict code style using the JavaScript happiness style. :star:3235
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style — One style to rule them all. :star:16035
- [ESLint](http://eslint.org) - The pluggable linting utility for JavaScript.
- [dev-time](https://github.com/samverschueren/dev-time-cli) - Get the current local time of a GitHub user. :star:144
- [David](https://github.com/alanshaw/david) - Tells you when your package npm dependencies are out of date. :star:792
- [http-server](https://github.com/indexzero/http-server) - Simple, zero-config command-line HTTP server. :star:6231
- [Live Server](https://github.com/tapio/live-server) - Development HTTP-server with livereload capability. :star:1870
- [bcat](https://github.com/kessler/node-bcat) - Pipe command output to web browsers. :star:260
- [normit](https://github.com/pawurb/normit) - Google Translate with speech synthesis in your terminal. :star:183
- [slap](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor. :star:4822
- [jsinspect](https://github.com/danielstjules/jsinspect) - Detect copy-pasted and structurally similar code. :star:1633
- [esformatter](https://github.com/millermedeiros/esformatter) - JavaScript code beautifier/formatter. :star:920
- [fkill](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform. :star:1746
- [pjs](https://github.com/danielstjules/pjs) - Pipeable JavaScript. Quickly filter, map, and reduce from the terminal. :star:325
- [license-checker](https://github.com/davglass/license-checker) - Check licenses of your app's dependencies. :star:541
- [browser-run](https://github.com/juliangruber/browser-run) - Easily run code in a browser environment. :star:294
- [tmpin](https://github.com/sindresorhus/tmpin) - Adds stdin support to any CLI app that accepts file input. :star:105
- [modhelp](https://github.com/runvnc/modhelp) - Syntax-highlighted module READMEs in terminal with ANSI-friendly pager. :star:21
- [wifi-password](https://github.com/kevva/wifi-password-cli) - Get the current wifi password. :star:103
- [wallpaper](https://github.com/sindresorhus/wallpaper) - Change the desktop wallpaper. :star:448
- [brightness](https://github.com/kevva/brightness-cli) - Change the screen brightness. :star:108
- [torrent](https://github.com/maxogden/torrent) - Download torrents. :star:499
- [tfa](https://github.com/jasnell/tfa) - Two-factor authentication client. :star:25
- [rtail](https://github.com/kilianc/rtail) - Terminal output to the browser in seconds, using UNIX pipes. :star:1409
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - Kill all Chrome tabs to improve performance, decrease battery usage, and save memory. :star:219
- [alex](https://github.com/wooorm/alex) - Catch insensitive, inconsiderate writing. :star:2104
- [vantage](https://github.com/dthree/vantage) - Distributed, realtime CLI for your live app. :star:3388
- [pen](https://github.com/noraesae/pen) - Live Markdown preview in the browser from your favorite editor. :star:173
- [subdownloader](https://github.com/beatfreaker/subdownloader) - Subtitle downloader for movies and TV series. :star:80
- [dark-mode](https://github.com/sindresorhus/dark-mode) - Toggle the macOS Dark Mode. :star:280
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP location finder. :star:140
- [Jsome](https://github.com/Javascipt/Jsome) - Pretty prints JSON with configurable colors and indentation. :star:95
- [itunes-remote](https://github.com/mischah/itunes-remote) - Interactively control iTunes. :star:296
- [text-meme](https://github.com/beatfreaker/text-meme-cli) - Generate a text meme. :star:51
- [mobicon](https://github.com/samverschueren/mobicon-cli) - Mobile app icon generator. :star:39
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - Mobile app splash screen generator. :star:21
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - Pretty git diff to HTML generator. :star:101
- [Cash](https://github.com/dthree/cash) - Cross-platform Unix shell commands in pure JavaScript. :star:7411
- [vaca](https://github.com/sindresorhus/vaca) - Get a random ASCII 🐮. :star:79
- [gh-home](https://github.com/sindresorhus/gh-home) - Open the GitHub page of the repo in the current directory. :star:91
- [npm-home](https://github.com/sindresorhus/npm-home) - Open the npm page of a package. :star:130
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - Try out npm packages in the terminal. :star:987
- [terminal-recorder](https://github.com/cortezcristian/terminal-recorder) - Record your terminal usage and export it to interactive HTML. :star:88
- [jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for source code. :star:587
- [atmo](https://github.com/Raathigesh/Atmo) - Server-side API mocking. :star:642
- [auto-install](https://github.com/siddharthkp/auto-install) - Auto installs dependencies as you code. :star:789
- [lessmd](https://github.com/linuxenko/lessmd) - Markdown in the terminal. :star:74
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - Find out which dependencies are slowing you down. :star:2001
- [localtunnel](https://github.com/localtunnel/localtunnel) - Expose your localhost to the world. :star:6136
- [svg-term-cli](https://github.com/marionebl/svg-term-cli) - Share terminal sessions via SVG. :star:253


### Functional programming

- [lodash](https://lodash.com) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections. :star:22238
- [mori](http://swannodette.github.io/mori/) - Library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.
- [Ramda](http://ramdajs.com) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data.
- [Folktale](http://folktalejs.org) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse.
- [underscore-contrib](http://documentcloud.github.io/underscore-contrib/) - The brass buckles on Underscore's utility belt.
- [Mout](http://moutjs.com) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead.
- [Bacon.js](http://baconjs.github.io) - Functional reactive programming.
- [RxJS](http://reactivex.io) - Functional reactive library for transforming, composing, and querying various kinds of data.
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases. :star:4546
- [Kefir.js](https://github.com/rpominov/kefir) - Reactive library with focus on high performance and low memory usage.


### HTTP

- [got](https://github.com/sindresorhus/got) - Nicer interface to the built-in `http` module. :star:2333
- [gh-got](https://github.com/sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API. :star:100
- [axios](https://github.com/mzabriskie/axios) - Promise based HTTP client (works in the browser too). :star:34863
- [request](https://github.com/request/request) - Simplified HTTP request client. :star:18301
- [Nock](https://github.com/pgte/nock) - HTTP mocking and expectations library. :star:5826
- [spdy](https://github.com/indutny/node-spdy) - Creates SPDY servers with the same API as the built-in `https` module. :star:2413
- [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities. :star:299
- [download](https://github.com/kevva/download) - Download and extract files effortlessly. :star:624
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP proxy. :star:8281
- [rocky](https://github.com/h2non/rocky) - Featured, middleware-oriented HTTP proxy with traffic replay and intercept. :star:297
- [superagent](https://github.com/visionmedia/superagent) - HTTP request library. :star:12125
- [node-fetch](https://github.com/bitinn/node-fetch) - `window.fetch` for Node.js. :star:2539
- [flashheart](https://github.com/bbc/flashheart) - REST client. :star:76
- [http-fake-backend](https://github.com/micromata/http-fake-backend) - Build a fake backend by providing the content of JSON files or JavaScript objects through configurable routes. :star:122
- [cacheable-request](https://github.com/lukechilds/cacheable-request) - Wrap native HTTP requests with RFC compliant cache support. :star:80


### Debugging / Profiling

- [ironNode](https://github.com/s-a/iron-node) - Node.js debugger supporting ES2015 out of the box. :star:2363
- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools. :star:11967
- [devtool](https://github.com/Jam3/devtool) - Run Node.js programs through Chrome Dev Tools. :star:3767
- [Theseus](https://github.com/adobe-research/theseus) - JavaScript debugger featuring real-time code coverage, retroactive inspection and asynchronous call tree. :star:1355
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility. :star:5496
- [jstrace](https://github.com/jstrace/jstrace) - Dynamic tracing for JavaScript, similar to dtrace, ktap etc. :star:382
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - Node.js is running but you don't know why? :star:643
- [njsTrace](https://github.com/valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function. :star:206
- [vstream](https://github.com/joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams. :star:53
- [stackman](https://github.com/watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies. :star:138
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables. :star:232
- [bugger](https://github.com/buggerjs/bugger) - Provides Chrome Devtools bindings to debug programs in Chrome. :star:154
- [0x](https://github.com/davidmarkclements/0x) - Flamegraph profiling. :star:723
- [ctrace](https://github.com/automation-stack/ctrace) - Well-formatted and improved trace system calls and signals. :star:91
- [leakage](https://github.com/andywer/leakage) - Write memory leak tests. :star:1192


### Logging

- [pino](https://github.com/pinojs/pino) - Extremely fast logger inspired by Bunyan. :star:2253
- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library. :star:9286
- [Bunyan](https://github.com/trentm/node-bunyan) - JSON logging library. :star:4759
- [intel](http://seanmonstar.github.io/intel/) - Logging library (handlers, filters, formatters, console injection).
- [console-log-level](https://github.com/watson/console-log-level) - The most simple logger imaginable with support for log levels and custom prefixes. :star:22
- [storyboard](https://github.com/guigrpa/storyboard) - End-to-end, hierarchical, real-time, colorful logs and stories. :star:415


### Command-line utilities

- [chalk](https://github.com/chalk/chalk) - Terminal string styling done right. :star:7880
- [meow](https://github.com/sindresorhus/meow) - CLI app helper. :star:1101
- [minimist](https://github.com/substack/minimist) - Parse command-line flags. :star:2702
- [get-stdin](https://github.com/sindresorhus/get-stdin) - Easier stdin. :star:144
- [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner. :star:2468
- [log-update](https://github.com/sindresorhus/log-update) - Log by overwriting the previous output in the terminal. Useful for rendering progress bars, animations, etc. :star:414
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt. :star:6131
- [listr](https://github.com/samverschueren/listr) - Terminal task list. :star:1305
- [conf](https://github.com/sindresorhus/conf) - Simple config handling for your app or module. :star:217
- [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app. :star:862
- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - ANSI escape codes for manipulating the terminal. :star:156
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels. :star:278
- [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows CMD fallbacks. :star:204
- [boxen](https://github.com/sindresorhus/boxen) - Create boxes in the terminal. :star:292
- [string-width](https://github.com/sindresorhus/string-width) - Get the visual width of a string - the number of columns required to display it. :star:83
- [cli-truncate](https://github.com/sindresorhus/cli-truncate) - Truncate a string to a specific width in the terminal. :star:24
- [first-run](https://github.com/sindresorhus/first-run) - Check if it's the first time the process is run. :star:43
- [vorpal](https://github.com/dthree/vorpal) - Interactive CLI apps. :star:4397
- [blessed](https://github.com/chjj/blessed) - Curses-like library. :star:7038
- [yn](https://github.com/sindresorhus/yn) - Parse yes/no like values. :star:96
- [cli-table](https://github.com/Automattic/cli-table) - Pretty unicode tables. :star:1454
- [drawille](https://github.com/madbence/node-drawille) - Draw on the terminal with unicode braille characters. :star:704
- [sudo-block](https://github.com/sindresorhus/sudo-block) - Block users from running your app with root permissions. :star:52
- [googleauth](https://github.com/maxogden/googleauth) - Create and load persistent Google authentication tokens for command-line apps. :star:44
- [ascii-charts](https://github.com/jstrace/chart) - ASCII bar chart in the terminal. :star:221
- [progress](https://github.com/tj/node-progress) - Flexible ascii progress bar. :star:1716
- [insight](https://github.com/yeoman/insight) - Helps you understand how your tool is being used by anonymously reporting usage metrics to Google Analytics. :star:398
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - Toggle the CLI cursor. :star:35
- [columnify](https://github.com/timoxley/columnify) - Create text-based columns suitable for console output. Supports cell wrapping. :star:270
- [cli-columns](https://github.com/shannonmoeller/cli-columns) - Columnated unicode and ansi-safe text lists. :star:8
- [cfonts](https://github.com/dominikwilkowski/cfonts) - Sexy ASCII fonts for the console. :star:251
- [multispinner](https://github.com/codekirei/node-multispinner) - Multiple, simultaneous, individually controllable CLI spinners. :star:198
- [omelette](https://github.com/f/omelette) - Shell autocompletion helper. :star:685
- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform. :star:2121
- [shelljs](https://github.com/shelljs/shelljs) - Portable Unix shell commands. :star:7172
- [loud-rejection](https://github.com/sindresorhus/loud-rejection) - Make unhandled promise rejections fail loudly instead of the default silent fail. :star:195
- [sparkly](https://github.com/sindresorhus/sparkly) - Generate sparklines ▁▂▃▅▂▇ :star:264
- [term-img](https://github.com/sindresorhus/term-img) - Display images in your terminal. :star:193
- [yargs](https://github.com/yargs/yargs) - Command-line parser that automatically generates an elegant user-interface. :star:3991
- [DraftLog](https://github.com/ivanseidel/node-draftlog) - Create multiple updatable log lines. Works just like `console.log`. :star:864
- [Bit](https://github.com/teambit/bit) - Create, maintain, find and use small modules and components across repositories. :star:911
- [gradient-string](https://github.com/bokub/gradient-string) - Beautiful color gradients in terminal output. :star:235


### Build tools

- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser. :star:36353
- [rollup](https://github.com/rollup/rollup) - Next-generation ES2015 module bundler. :star:11654
- [gulp](http://gulpjs.com) - Streaming and fast build system that favors code over config.
- [browserify](https://github.com/substack/node-browserify) - Browser-side require() the Node.js way. :star:11711
- [Broccoli](https://github.com/broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions. :star:3093
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow. :star:6340
- [strong-build](https://github.com/strongloop/strong-build) - Build a node app package and prepare to deploy it as a package to production or use git to commit to a deploy branch. :star:44
- [start](https://github.com/start-runner/start) - Simple tasks runner powered by composable functions and promise chaining. :star:213
- [ygor](https://github.com/shannonmoeller/ygor) - Promising task runner for when `npm run` isn't enough and everything else is too much. :star:43
- [grunt](http://gruntjs.com) - Task runner that can perform repetitive tasks like minification, compilation, unit testing, linting, etc.
- [Fly](https://github.com/bucaran/fly) - Modern build system based in co-routines, generators and promises. :star:2078
- [FuseBox](https://github.com/fuse-box/fuse-box) - Fast build system that combines the power of webpack, JSPM and SystemJS, with first-class TypeScript support. :star:3133
- [pkg](https://github.com/zeit/pkg) - Package your Node.js project into an executable. :star:8757


### Hardware

- [johnny-five](https://github.com/rwaldron/johnny-five) - Firmata based Arduino Framework. :star:8586
- [serialport](https://github.com/voodootikigod/node-serialport) - Access serial ports for reading and writing. :star:3148
- [usb](https://github.com/nonolith/node-usb) - USB library. :star:595
- [cylon.js](http://cylonjs.com) - Next generation robotics framework with support for 26 different platforms.
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C serial bus access. :star:107
- [onoff](https://github.com/fivdi/onoff) - GPIO access and interrupt detection. :star:606
- [spi-device](https://github.com/fivdi/spi-device) - SPI serial bus access. :star:31
- [pigpio](https://github.com/fivdi/pigpio) - Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi. :star:259


### Templating

- [marko](https://github.com/marko-js/marko) - HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags. :star:5872
- [nunjucks](https://github.com/mozilla/nunjucks) - Templating engine with inheritance, asynchronous control, and more (jinja2 inspired). :star:4913
- [handlebars.js](https://github.com/wycats/handlebars.js) - Superset of Mustache templates which adds powerful features like helpers and more advanced blocks. :star:12883
- [hogan.js](http://twitter.github.io/hogan.js/) - Twitter's small, fast, phase-separated compiler for Mustache templates.
- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language. :star:2097
- [Pug](https://github.com/pugjs/pug) - High-performance template engine heavily influenced by Haml. :star:15952


### Web frameworks

- [Hapi](http://hapijs.com) - Framework for building applications and services.
- [Koa](http://koajs.com) - Framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [Express](http://expressjs.com) - Web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [Feathers](http://feathersjs.com) - Microservice framework built in the spirit of Express.
- [LoopBack](http://loopback.io) - Powerful framework for creating REST APIs and easily connecting to backend data sources.
- [Meteor](https://www.meteor.com) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [SailsJS](http://sailsjs.org) - An MVC web framework with a modern twist, supporting WebSockets, streams, and a data-driven API.
- [Restify](http://restify.com) - Enables you to build correct REST web services.
- [Interfake](https://github.com/basicallydan/interfake) - Rapid prototyping framework for making mock HTTP APIs, with a Node.js, command-line and HTTP interface. :star:808
- [Catberry](http://catberry.org) - Framework with Flux architecture, isomorphic web-components, and progressive rendering.
- [ThinkJS](https://thinkjs.org) - Framework with ES2015+ support, WebSockets, REST API.
- [ActionHero](http://www.actionherojs.com) - Framework for making reusable & scalable APIs for TCP sockets, WebSockets, and HTTP clients.
- [MERN](http://mern.io) - Easily build production-ready universal apps with MongoDB, Express, React, and webpack.
- [Next.js](https://zeit.co/blog/next) - Minimalistic framework for server-rendered universal JavaScript web apps.
- [Nuxt.js](https://nuxtjs.org) - Minimalistic framework for server-rendered Vue.js apps.
- [seneca](https://github.com/senecajs/seneca) - Toolkit for writing microservices. :star:2752
- [AdonisJs](http://adonisjs.com) - A true MVC framework for Node.js built on solid foundations of Dependency Injection and IoC container.
- [Hemera](https://github.com/hemerajs/hemera) - Write reliable and fault-tolerant microservices with [NATS](https://nats.io). :star:422
- [Micro](https://github.com/zeit/micro) - Minimalistic microservice framework with an async approach. :star:5938


### Documentation

- [Docco](http://jashkenas.github.io/docco/) - Documentation generator which produces an HTML document that displays your comments intermingled with your code.
- [JSDoc](http://usejsdoc.org) - API documentation generator similar to JavaDoc or PHPDoc.
- [dox](https://github.com/tj/dox) - JavaScript documentation generator using Markdown and JSDoc. :star:2035
- [jsdox](https://github.com/sutoiku/jsdox) - JSDoc3 to Markdown documentation generator. :star:196
- [apiDoc](https://github.com/apidoc/apidoc) - Inline documentation for RESTful web APIs. :star:5608
- [documentation.js](http://documentation.js.org) - API documentation generator with support for ES2015+ and flow annotation.
- [YUIDoc](http://yui.github.com/yuidoc/) - Generates API documentation from comments in source.
- [ESDoc](https://esdoc.org) - Documentation generator targeting ES2015, attaching test code and measuring documentation coverage.


### Filesystem

- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs. :star:750
- [globby](https://github.com/sindresorhus/globby) - Glob files with support for multiple patterns. :star:524
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:152
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like `rm -rf`. :star:2209
- [make-dir](https://github.com/sindresorhus/make-dir) - Recursively create directories like `mkdir -p`. :star:245
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Drop-in replacement for the `fs` module with various improvements. :star:694
- [chokidar](https://github.com/paulmillr/chokidar) - Filesystem watcher which stabilizes events from `fs.watch` and `fs.watchFile` as well as using native `fsevents` on macOS. :star:3645
- [find-up](https://github.com/sindresorhus/find-up) - Find a file by walking up parent directories. :star:114
- [proper-lockfile](https://github.com/IndigoUnited/node-proper-lockfile) - Inter-process and inter-machine lockfile utility. :star:40
- [load-json-file](https://github.com/sindresorhus/load-json-file) - Read and parse a JSON file. :star:84
- [write-json-file](https://github.com/sindresorhus/write-json-file) - Stringify and write JSON to a file atomically. :star:75
- [fs-write-stream-atomic](https://github.com/npm/fs-write-stream-atomic) - Like `fs.createWriteStream()`, but atomic. :star:38
- [filenamify](https://github.com/sindresorhus/filenamify) - Convert a string to a valid filename. :star:77
- [lnfs](https://github.com/kevva/lnfs) - Force create symlinks like `ln -fs`. :star:9
- [istextorbinary](https://github.com/bevry/istextorbinary) - Check if a file is text or binary. :star:38
- [fs-jetpack](https://github.com/szwacz/fs-jetpack) - Completely redesigned file system API for convenience in everyday use. :star:357
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module. :star:3514
- [pkg-dir](https://github.com/sindresorhus/pkg-dir) - Find the root directory of an npm package. :star:53
- [sander](https://github.com/rich-harris/sander) - Promise-based replacement for the `fs` module. :star:76
- [filehound](https://github.com/nspragg/filehound) - Flexible and fluent interface for searching the file system. :star:90


### Control flow

- Promises
	- [Bluebird](https://github.com/petkaantonov/bluebird) - Promise library with focus on innovative features and performance. :star:16164
	- [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function. :star:771
	- [delay](https://github.com/sindresorhus/delay) - Delay a promise a specified amount of time. :star:177
	- [promise-memoize](https://github.com/nodeca/promise-memoize) - Memoize promise-returning functions, with expire and prefetch. :star:19
	- [valvelet](https://github.com/lpinca/valvelet) - Limit the execution rate of a promise-returning function. :star:12
	- [p-map](https://github.com/sindresorhus/p-map) - Map over promises concurrently. :star:150
	- [More…](https://github.com/wbinnssmith/awesome-promises) :star:1058
- Observables
	- [zen-observable](https://github.com/zenparsing/zen-observable) - Implementation of Observables. :star:324
	- [RxJS](https://github.com/ReactiveX/RxJS) - Reactive programming. :star:10440
	- [observable-to-promise](https://github.com/sindresorhus/awesome-observables) - Convert an Observable to a Promise. :star:215
	- [More…](https://github.com/sindresorhus/awesome-observables) :star:215
- Generators
	- [co](https://github.com/tj/co) - The ultimate generator based flow-control goodness. :star:9237
	- [bluebird-co](https://github.com/novacrazy/bluebird-co) - High performance yield handlers for Bluebird coroutines. :star:80
	- [iterum](https://github.com/xgbuils/iterum) - Build generator pipelines using Array-like methods. :star:20
- Streams
	- [Highland.js](http://highlandjs.org) - Manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
- Callbacks
	- [each-async](https://github.com/sindresorhus/each-async) - Async concurrent iterator like forEach. :star:99
	- [async](https://github.com/caolan/async) - Provides straight-forward, powerful functions for working with asynchronicity. :star:23218
- Channels
	- [js-csp](https://github.com/ubolonton/js-csp) - Communicating sequential processes for JavaScript (like Clojurescript core.async, or Go). :star:2035
- Other
	- [zone](https://github.com/strongloop/zone) - Provides a way to group and track resources and errors across asynchronous operations. :star:285


### Streams

- [through2](https://github.com/rvagg/through2) - Tiny wrapper around streams2 Transform to avoid explicit subclassing noise. :star:1271
- [from2](https://github.com/hughsk/from2) - Convenience wrapper for ReadableStream, inspired by `through2`. :star:86
- [get-stream](https://github.com/sindresorhus/get-stream) - Get a stream as a string or buffer. :star:93
- [into-stream](https://github.com/sindresorhus/into-stream) - Convert a buffer/string/array/object into a stream. :star:54
- [duplexify](https://github.com/mafintosh/duplexify) - Turn a writeable and readable stream into a single streams2 duplex stream. :star:117
- [pumpify](https://github.com/mafintosh/pumpify) - Combine an array of streams into a single duplex stream. :star:118
- [peek-stream](https://github.com/mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it. :star:37
- [binary-split](https://github.com/maxogden/binary-split) - Newline (or any delimiter) splitter stream. :star:55
- [byline](https://github.com/jahewson/node-byline) - Super-simple line-by-line Stream reader. :star:249
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - Transform the first chunk in a stream. :star:15
- [pad-stream](https://github.com/sindresorhus/pad-stream) - Pad each line in a stream. :star:5
- [multistream](https://github.com/feross/multistream) - Combine multiple streams into a single stream. :star:130
- [stream-combiner2](https://github.com/substack/stream-combiner2) - Turn a pipeline into a single stream. :star:64
- [readable-stream](https://github.com/nodejs/readable-stream) - Mirror of Streams2 and Streams3 implementations in core. :star:582
- [through2-concurrent](https://github.com/almost/through2-concurrent) - Transform object streams concurrently. :star:54
- [graphicsmagick-stream](https://github.com/e-conomic/graphicsmagick-stream) - Fast conversion/scaling of images using a pool of long lived GraphicsMagick processes. :star:60


### Real-time

- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - Highly scalable WebSocket server & client library. :star:8445
- [Socket.io](http://socket.io) - Enables real-time bidirectional event-based communication.
- [SockJS](https://github.com/sockjs/sockjs-node) - Low latency, full duplex, cross-domain channel browser-server, with WebSockets or without. :star:1515
- [Faye](http://faye.jcoglan.com) - Real-time client-server message bus, based on Bayeux protocol.
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores. :star:4436
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in. :star:3425
- [Straw](https://github.com/simonswain/straw) - Real-time dataflow framework. :star:246
- [deepstream.io](https://deepstream.io) - Scalable real-time microservice framework.
- [Kalm](https://github.com/kalm/kalm.js) - Low-level socket router and middleware framework. :star:45
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - Client for MQTT - Pub-sub based messaging protocol for use on top of TCP/IP. :star:2908


### Image

- [sharp](https://github.com/lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images. :star:7261
- [image-type](https://github.com/sindresorhus/image-type) - Detect the image type of a Buffer/Uint8Array. :star:132
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick and ImageMagick wrapper. :star:4690
- [lwip](https://github.com/EyalAr/lwip) - Lightweight image processor which does not require ImageMagick. :star:2028
- [pica](https://github.com/nodeca/pica) - High quality & fast resize (lanczos3) in pure JS. Alternative to canvas drawImage(), when no pixelation allowed. :star:1047
- [jimp](https://github.com/oliver-moran/jimp) - Image processing in pure JavaScript. :star:5428
- [is-progressive](https://github.com/sindresorhus/is-progressive) - Check if a JPEG image is progressive. :star:170
- [probe-image-size](https://github.com/nodeca/probe-image-size) - Get the size of most image formats without a full download. :star:127


### Text

- [Underscore.string](https://github.com/epeli/underscore.string) - Collection of string manipulation utilities. :star:3263
- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings. :star:1537
- [string-length](https://github.com/sindresorhus/string-length) - Get the real length of a string - by correctly counting astral symbols and ignoring ansi escape codes. :star:44
- [camelcase](https://github.com/sindresorhus/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar. :star:174
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - Escape RegExp special characters. :star:199
- [execall](https://github.com/sindresorhus/execall) - Find multiple RegExp matches in a string. :star:61
- [splice-string](https://github.com/sindresorhus/splice-string) - Remove or replace part of a string like `Array#splice`. :star:11
- [indent-string](https://github.com/sindresorhus/indent-string) - Indent each line in a string. :star:52
- [strip-indent](https://github.com/sindresorhus/strip-indent) - Strip leading whitespace from every line in a string. :star:62
- [detect-indent](https://github.com/sindresorhus/detect-indent) - Detect the indentation of code. :star:96
- [he](https://github.com/mathiasbynens/he) - HTML entity encoder/decoder. :star:1349
- [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage. :star:1922
- [babelfish](https://github.com/nodeca/babelfish) - i18n with very easy syntax for plurals. :star:176
- [hanging-indent](https://github.com/codekirei/hanging-indent) - Format a string into a hanging-indented paragraph. :star:2
- [matcher](https://github.com/sindresorhus/matcher) - Simple wildcard matching. :star:286
- [unhomoglyph](https://github.com/nodeca/unhomoglyph) - Normalize visually similar unicode characters. :star:8


### Number

- [random-int](https://github.com/sindresorhus/random-int) - Generate a random integer. :star:26
- [random-float](https://github.com/sindresorhus/random-float) - Generate a random float. :star:15
- [unique-random](https://github.com/sindresorhus/unique-random) - Generate random numbers that are consecutively unique. :star:46
- [round-to](https://github.com/sindresorhus/round-to) - Round a number to a specific number of decimal places: `1.234` → `1.2`. :star:76


### Math

- [ndarray](https://github.com/scijs/ndarray) - Multidimensional arrays. :star:708
- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library. :star:5342
- [math-sum](https://github.com/sindresorhus/math-sum) - Sum numbers. :star:4
- [math-clamp](https://github.com/sindresorhus/math-clamp) - Clamp a number. :star:4
- [algebra](https://github.com/fibo/algebra) - Algebraic structures. :star:50


### Date

- [date-fns](https://github.com/date-fns/date-fns) - Modern date utility. :star:8852
- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.
- [Moment Timezone](http://momentjs.com/timezone/) - IANA Time Zone Database + Moment.js.
- [dateformat](https://github.com/felixge/node-dateformat) - Date formatting. :star:772
- [tz-format](https://github.com/samverschueren/tz-format) - Format a date with timezone: `2015-11-30T10:40:35+01:00`. :star:4
- [cctz](https://github.com/floatdrop/node-cctz) - Fast parsing, formatting, and timezone conversation for dates. :star:49


### URL

- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL. :star:196
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Humanize a URL: http://sindresorhus.com → sindresorhus.com. :star:52
- [url-unshort](https://github.com/nodeca/url-unshort) - Expand shortened URLs. :star:27
- [speakingurl](https://github.com/pid/speakingurl) - Generate a slug from a string with transliteration. :star:889
- [linkify-it](https://github.com/markdown-it/linkify-it) - Link patterns detector with full unicode support. :star:188
- [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for URLs and other strings. :star:327
- [embedza](https://github.com/nodeca/embedza) - Create HTML snippets/embeds from URLs using info from oEmbed, Open Graph, meta tags. :star:31


### Data validation

- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects. :star:6961
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast. :star:774
- [property-validator](https://github.com/nettofarah/property-validator) - Easy property validation for Express. :star:131
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API sanitization and validation. :star:430
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON Schema validator. Supports v5 proposals. :star:2911


### Parsing

- [remark](https://github.com/wooorm/remark) - Markdown processor powered by plugins. :star:1274
- [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser with 100% CommonMark support, extensions and syntax plugins. :star:4691
- [parse5](https://github.com/inikulin/parse5) - Fast full-featured spec compliant HTML parser. :star:1607
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - Strip comments from JSON. :star:326
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - Strip comments from CSS. :star:79
- [parse-json](https://github.com/sindresorhus/parse-json) - Parse JSON with more helpful errors. :star:118
- [URI.js](https://github.com/medialize/URI.js) - URL mutation. :star:5114
- [PostCSS](https://github.com/postcss/postcss) - CSS parser / stringifier. :star:17329
- [JSONStream](https://github.com/dominictarr/JSONStream) - Streaming JSON.parse and stringify. :star:1393
- [neat-csv](https://github.com/sindresorhus/neat-csv) - Fast CSV parser. Callback interface for the above. :star:61
- [csv-parser](https://github.com/mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else. :star:456
- [PEG.js](https://github.com/pegjs/pegjs) - Simple parser generator that produces fast parsers with excellent error reporting. :star:2623
- [x-ray](https://github.com/lapwinglabs/x-ray) - Web scraping utility. :star:4167
- [nearley](https://github.com/Hardmath123/nearley) - Simple, fast, powerful parsing for JavaScript. :star:1710
- [binary-extract](https://github.com/juliangruber/binary-extract) - Extract a value from a buffer of JSON without parsing the whole thing. :star:135
- [json-mask](https://github.com/nemtsov/json-mask) - Tiny language and engine for selecting parts of an object, hiding/masking the rest. :star:489
- [Stylecow](https://github.com/stylecow/stylecow) - Parse, manipulate and convert modern CSS to make it compatible with all browsers. Extensible with plugins. :star:122
- [js-yaml](https://github.com/nodeca/js-yaml) - Very fast YAML parser. :star:2686
- [excel-stream](https://github.com/dominictarr/excel-stream) - Streaming Excel spreadsheet to JSON parser. :star:112
- [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter. :star:2966
- [Jison](http://zaach.github.io/jison/) - Friendly JavaScript parser generator. It shares genes with Bison, Yacc and family.
- [google-libphonenumber](https://github.com/seegno/google-libphonenumber) - Parse, format, store and validate phone numbers. :star:412
- [ref](https://github.com/TooTallNate/ref) - Read/write structured binary data in Buffers. :star:263
- [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Read/write Excel XLSX. :star:114


### Humanize

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - Convert bytes to a human readable string: `1337` → `1.34 kB`. :star:338
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`. :star:253
- [ms](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility. :star:1260
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - Errors with less clutter. :star:872
- [humanize](https://github.com/taijinlee/humanize) - Data formatter for human readability. :star:349
- [read-art](https://github.com/Tjatse/node-readability) - Extract readable content from any page. :star:238


### Compression

- [yazl](https://github.com/thejoshwolfe/yazl) - Zip. :star:126
- [yauzl](https://github.com/thejoshwolfe/yauzl) - Unzip. :star:255
- [Archiver](https://github.com/archiverjs/node-archiver) - Streaming interface for archive generation, supporting ZIP and TAR. :star:1063
- [pako](https://github.com/nodeca/pako) - High speed zlib port to pure js (deflate, inflate, gzip). :star:1459
- [tar-stream](https://github.com/mafintosh/tar-stream) - Streaming tar parser and generator. Also see [tar-fs](https://github.com/mafintosh/tar-fs). :star:192
- [decompress](https://github.com/kevva/decompress) - Decompression module with support for `tar`, `tar.gz` and `zip` files out of the box. :star:194


### Network

- [get-port](https://github.com/sindresorhus/get-port) - Get an available port. :star:193
- [ipify](https://github.com/sindresorhus/ipify) - Get your public IP address. :star:127
- [getmac](https://github.com/bevry/getmac) - Get the computer MAC address. :star:122
- [polo](https://github.com/mafintosh/polo) - Zero-config service discovery. :star:206
- [DHCP](https://github.com/infusion/node-dhcp) - DHCP client and server. :star:84


### Database

- Drivers
	- [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client. Pure JavaScript and native libpq bindings. :star:5664
	- [Redis](https://github.com/luin/ioredis) - Redis client. :star:3745
	- [LevelUP](https://github.com/Level/levelup) - LevelDB. :star:3068
	- [MySQL](https://github.com/mysqljs/mysql) - MySQL client. :star:11099
	- [nano](https://github.com/dscape/nano) - CouchDB client. :star:1121
	- [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Aerospike client. :star:141
	- [Couchbase](https://github.com/couchbase/couchnode) - Couchbase client. :star:365
	- [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB driver. :star:6463
- ODM / ORM
	- [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL. :star:12842
	- [Bookshelf](http://bookshelfjs.org) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js.
	- [Massive](https://github.com/robconery/massive-js) - PostgreSQL data access tool. :star:2028
	- [Mongoose](http://mongoosejs.com) - Elegant MongoDB object modeling.
	- [Waterline](https://github.com/balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases. :star:4386
	- [Iridium](https://github.com/SierraSoftworks/Iridium) - MongoDB ORM with support for promises, distributed caching, preprocessing, validation and plugins. :star:483
	- [OpenRecord](https://github.com/PhilWaldmann/openrecord) - ORM for PostgreSQL, MySQL, SQLite3 and RESTful datastores. Similar to ActiveRecord. :star:143
	- [orm2](https://github.com/dresende/node-orm2) - ORM for PostgreSQL, MariaDB, MySQL, Amazon Redshift, SQLite, MongoDB. :star:2752
	- [firenze](https://github.com/fahad19/firenze) - Adapter-based ORM for MySQL, Memory, Redis, localStorage and more. :star:131
	- [pg-promise](https://github.com/vitaly-t/pg-promise) - PostgreSQL framework for native SQL using promises. :star:1618
	- [Objection.js](https://github.com/Vincit/objection.js) - Lightweight ORM built on the SQL query builder Knex. :star:1725
- Query builder
	- [Knex](http://knexjs.org) - Query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use.
- Other
	- [NeDB](https://github.com/louischatriot/nedb) - Embedded persistent database written in JavaScript. :star:7692
	- [Lowdb](https://github.com/typicode/lowdb) - Small JavaScript database powered by Lodash. :star:7121
	- [Keyv](https://github.com/lukechilds/keyv) - Simple key-value storage with support for multiple backends. :star:441


### Testing

- [AVA](https://ava.li) - Futuristic test runner.
- [Mocha](http://mochajs.org) - Feature-rich test framework making asynchronous testing simple and fun.
- [nyc](https://github.com/bcoe/nyc) - Code coverage tool built on istanbul that works with subprocesses. :star:2188
- [tap](https://github.com/isaacs/node-tap) - TAP test framework. :star:1163
- [tape](https://github.com/substack/tape) - TAP-producing test harness. :star:4383
- [power-assert](https://github.com/power-assert-js/power-assert) - Provides descriptive assertion messages through the standard assert interface. :star:1839
- [Mochify](https://github.com/mantoni/mochify.js) - TDD with Browserify, Mocha, PhantomJS and WebDriver. :star:291
- [trevor](https://github.com/vdemedes/trevor) - Run tests against multiple versions of Node.js without switching versions manually or pushing to Travis CI. :star:1965
- [loadtest](https://github.com/alexfernandez/loadtest) - Run load tests for your web application, with an API for automation. :star:1038
- [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs and mocks. :star:5326
- [navit](https://github.com/nodeca/navit) - PhantomJS / SlimerJS wrapper to simplify browser test scripting. :star:41
- [nock](https://github.com/pgte/nock) - HTTP mocking and expectations. :star:5826
- [intern](https://github.com/theintern/intern) - Code testing stack. :star:3930
- [toxy](https://github.com/h2non/toxy) - Hackable HTTP proxy to simulate failure scenarios and network conditions. :star:2392
- [hook-std](https://github.com/sindresorhus/hook-std) - Hook and modify stdout/stderr. :star:26
- [testen](https://github.com/egoist/testen) - Run tests for multiple versions of Node.js locally with NVM. :star:161
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - Automated UI testing framework based on Selenium WebDriver. :star:7695
- [WebdriverIO](http://webdriver.io) - Automated testing based on the WebDriver protocol.
- [Jest](https://github.com/facebook/jest) - Painless JavaScript testing. :star:15171
- [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing. :star:3894
- [abstruse](https://github.com/bleenco/abstruse) - Continuous Integration server. :star:97


### Security

- [snyk](https://github.com/Snyk/snyk) - CLI and build-time tool to find & fix vulnerable npm dependencies. :star:928
- [nsp](https://github.com/nodesecurity/nsp) - CLI tool to identify known vulnerabilities in your project. :star:1358
- [RegEx-DoS](https://github.com/jagracey/RegEx-DoS) - CLI tool to identify possible regex denial of service (ReDos) vulnerabilities in your project. :star:66
- [credential-plus](https://github.com/simonepri/credential-plus) - Password hashing and verification made easy. :star:34


### Benchmarking

- [Benchmark.js](http://benchmarkjs.com) - Benchmarking library that supports high-resolution timers and returns statistically significant results.
- [matcha](https://github.com/logicalparadox/matcha) - Simplistic approach to benchmarking. :star:467


### Minifiers

- [babili](https://github.com/babel/babili) - ES2015+ aware minifier based on the Babel toolchain. :star:3129
- [UglifyJS2](http://lisperator.net/uglifyjs/) - JavaScript minifier.
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS minifier. :star:2778
- [minimize](https://github.com/Swaagie/minimize) - HTML minifier. :star:132
- [imagemin](https://github.com/imagemin/imagemin) - Image minifier. :star:1889


### Authentication

- [Passport](http://passportjs.org) - Simple, unobtrusive authentication.
- [everyauth](https://github.com/bnoguchi/everyauth) - Authentication and authorization (password, Facebook, etc) for your Connect and Express apps. :star:3427
- [passwordless](https://passwordless.net) - Token-based authentication middleware for Express allowing authentication without passwords.
- [Lockit](https://github.com/zemirco/lockit) - Full featured authentication solution for Express. Supports a variety of databases, predefined routes, email and two-factor authentication. :star:446
- [Grant](https://github.com/simov/grant) - OAuth middleware for Express, Koa, and Hapi. :star:1392
- [CloudRail](https://github.com/CloudRail/cloudrail-si-node-sdk) - Unified API for social authentication (Facebook, Twitter, Slack, Instagram, …). :star:227


### Email

- [Nodemailer](https://github.com/andris9/Nodemailer) - The fastest way to handle email. :star:8923
- [emailjs](https://github.com/eleith/emailjs) - Send text/HTML emails with attachments to any SMTP server. :star:1553
- [email-templates](https://github.com/niftylettuce/email-templates) - Create, preview, and send custom email templates. :star:1833


### Job queues

- [kue](https://github.com/Automattic/kue) - Priority job queue backed by Redis. :star:6975
- [bull](https://github.com/OptimalBits/bull) - Persistent job and message queue. :star:2269
- [agenda](https://github.com/rschmukler/agenda) - Lightweight job scheduling on MongoDB. :star:3676
- [idoit](https://github.com/nodeca/idoit) - Redis-backed job queue engine with advanced job control. :star:18
- [node-resque](https://github.com/taskrabbit/node-resque) - Redis-backed job queue. :star:450


### Node.js management

- [n](https://github.com/tj/n) - Node.js version management. :star:8498
- [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.js. :star:1110
- [nodeenv](https://github.com/ekalinin/nodeenv) - Node.js virtual environment compatible to Python's virtualenv. :star:818
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Version management for Windows. :star:5011


### Polyfills

- Node.js
	- [user-info](https://github.com/sindresorhus/user-info) - Node.js 6 `os.userInfo()` ponyfill. :star:32
	- [buffer-includes](https://github.com/sindresorhus/buffer-includes) - Node.js 5.3 `buffer.includes()` ponyfill. :star:7
	- [deep-strict-equal](https://github.com/sindresorhus/deep-strict-equal) - Test for deep equality - Node.js `assert.deepStrictEqual()` algorithm as a standalone module. :star:20
- JavaScript
	- [harmony-reflect](https://github.com/tvcutsem/harmony-reflect) - ES2015 `Reflect` and `Proxy` polyfill. :star:356
	- [es6-shim](https://github.com/paulmillr/es6-shim) - Collection of ES2015 polyfills. :star:2451


### Natural language processing

- [retext](https://github.com/wooorm/retext) - An extensible natural language system. :star:1407
- [franc](https://github.com/wooorm/franc) - Detect the language of text. :star:2469
- [leven](https://github.com/sindresorhus/leven) - Measure the difference between two strings using the Levenshtein distance algorithm. :star:323
- [natural](https://github.com/NaturalNode/natural) - Natural language facility. :star:7298


### Process management

- [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager. :star:23122
- [nodemon](https://github.com/remy/nodemon) - Monitor for changes in your app and automatically restart the server. :star:13377
- [node-mac](https://github.com/coreybutler/node-mac) - Run scripts as a native Mac daemon and log to the console app. :star:407
- [node-linux](https://github.com/coreybutler/node-linux) - Run scripts as native system service and log to syslog. :star:330
- [node-windows](https://github.com/coreybutler/node-windows) - Run scripts as a native Windows service and log to the Event viewer. :star:1306
- [forever](https://github.com/foreverjs/forever) - Ensures that a given script runs continuously. :star:10700
- [supervisor](https://github.com/petruisfan/node-supervisor) - Restart scripts when they crash or restart when a `*.js` file changes. :star:3301
- [Phusion Passenger](https://www.phusionpassenger.com) - Friendly process manager that integrates directly into Nginx.
- [naught](https://github.com/andrewrk/naught) - Process manager with zero downtime deployment. :star:718


### Automation

- [robotjs](https://github.com/octalmage/robotjs) - Desktop Automation: control the mouse, keyboard and read the screen. :star:6647


### AST

- [Acorn](https://github.com/ternjs/acorn) - Tiny, fast JavaScript parser. :star:3070
- [Rocambole](https://github.com/millermedeiros/rocambole) - Recursively walk and transform JavaScript AST. :star:154


### Static site generators

- [Metalsmith](http://www.metalsmith.io) - Pluggable static site generator.
- [Wintersmith](http://wintersmith.io) - Flexible, minimalistic, multi-platform static site generator.
- [Assemble](http://assemble.io) - Static site generator for Node.js, Grunt.js, and Yeoman.
- [DocPad](https://github.com/docpad/docpad) - Static site generator with dynamic abilities and huge plugin ecosystem. :star:2949
- [Phenomic](https://phenomic.io) - Modern static website generator based on the React and Webpack ecosystem.
- [docsify](https://docsify.js.org) - Markdown documentation site generator with no statically built HTML files.


### Content management systems

- [KeystoneJS](http://keystonejs.com) - CMS and web application platform built on Express and MongoDB.
- [Apostrophe2](http://apostrophenow.org) - Content management system with an emphasis on intuitive front end content editing and administration built on Express and MongoDB.


### Forum

- [nodeBB](https://nodebb.org) - Forum platform for the modern web.


### Blogging

- [ghost](https://ghost.org) - Simple, powerful publishing platform.
- [Hexo](https://hexo.io) - Fast, simple and powerful blogging framework.


### Weird

- [cows](https://github.com/sindresorhus/cows) - ASCII cows. :star:169
- [superb](https://github.com/sindresorhus/superb) - Get superb like words. :star:241
- [cat-names](https://github.com/sindresorhus/cat-names) - Get popular cat names. :star:185
- [dog-names](https://github.com/sindresorhus/dog-names) - Get popular dog names. :star:79
- [superheroes](https://github.com/sindresorhus/superheroes) - Get superhero names. :star:162
- [supervillains](https://github.com/sindresorhus/supervillains) - Get supervillain names. :star:64
- [cool-ascii-faces](https://github.com/maxogden/cool-ascii-faces) - Get some cool ascii faces. :star:1536
- [cat-ascii-faces](https://github.com/melaniecebula/cat-ascii-faces) - ₍˄·͈༝·͈˄₎◞ ̑̑ෆ⃛ (=ↀωↀ=)✧ (^･o･^)ﾉ” :star:181
- [nerds](https://github.com/SkyHacks/nerds) - Get data from nerdy topics like Harry Potter, Star Wars, and Pokémon. :star:34


### Miscellaneous

- [execa](https://github.com/sindresorhus/execa) - Better `child_process`. :star:970
- [cheerio](https://github.com/cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server. :star:14746
- [Electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies. *(You might like [awesome-electron](https://github.com/sindresorhus/awesome-electron))* :star:55749
- [opn](https://github.com/sindresorhus/opn) - Opens stuff like websites, files, executables. :star:846
- [hasha](https://github.com/sindresorhus/hasha) - Hashing made simple. Get the hash of a buffer/string/stream/file. :star:566
- [dot-prop](https://github.com/sindresorhus/dot-prop) - Get a property from a nested object using a dot path. :star:231
- [onetime](https://github.com/sindresorhus/onetime) - Only run a function once. :star:70
- [mem](https://github.com/sindresorhus/mem) - Memoize functions - an optimization technique used to speed up consecutive function calls by caching the result of calls with identical input. :star:325
- [import-fresh](https://github.com/sindresorhus/import-fresh) - Import a module while bypassing the cache. :star:108
- [strip-bom](https://github.com/sindresorhus/strip-bom) - Strip UTF-8 byte order mark (BOM) from a string/buffer/stream. :star:59
- [os-locale](https://github.com/sindresorhus/os-locale) - Get the system locale. :star:110
- [nan](https://github.com/nodejs/nan) - Makes native add-on development for across Node.js versions easier. :star:2084
- [ssh2](https://github.com/mscdex/ssh2) - SSH2 client and server module. :star:2877
- [adit](https://github.com/markelog/adit) - SSH tunneling made simple. :star:17
- [import-lazy](https://github.com/sindresorhus/import-lazy) - Import a module lazily. :star:127
- [file-type](https://github.com/sindresorhus/file-type) - Detect the file type of a Buffer. :star:555
- [Bottleneck](https://github.com/SGrondin/bottleneck) - Rate limiter that makes throttling easy. :star:348
- [webworker-threads](https://github.com/audreyt/node-webworker-threads) - Lightweight Web Worker API implementation with native threads. :star:1594
- [clipboardy](https://github.com/sindresorhus/clipboardy) - Access the system clipboard (copy/paste). :star:334
- [node-pre-gyp](https://github.com/mapbox/node-pre-gyp) - Makes it easy to publish and install Node.js C++ addons from binaries. :star:477
- [opencv](https://github.com/peterbraden/node-opencv) - Bindings for OpenCV. The defacto computer vision library. :star:3208
- [dotenv](https://github.com/motdotla/dotenv) - Load environment variables from .env file. :star:4864
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - Get tags from a remote git repo. :star:29
- [semver](https://github.com/npm/node-semver) - [semver](http://semver.org) parser. :star:2063
- [Faker.js](https://github.com/Marak/Faker.js) - Generate massive amounts of fake data. :star:12824
- [nodegit](https://github.com/nodegit/nodegit) - Native bindings to Git. :star:3199
- [json-strictify](https://github.com/pigulla/json-strictify) - Safely serialize a value to JSON without data loss or going into an infinite loop. :star:2
- [parent-module](https://github.com/sindresorhus/parent-module) - Get the path of the parent module. :star:20
- [resolve-from](https://github.com/sindresorhus/resolve-from) - Resolve the path of a module like `require.resolve()` but from a given path. :star:43
- [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - Event driven web crawler. :star:1632
- [jsdom](https://github.com/tmpvar/jsdom) - JavaScript implementation of HTML and the DOM. :star:9117
- [hypernova](https://github.com/airbnb/hypernova) - Server-side rendering your JavaScript views. :star:3905


## Resources

### Tutorials

- [Nodeschool](http://nodeschool.io) - Learn Node.js with interactive lessons.
- [The Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node) - An introduction to Node.js.
- [stream-handbook](https://github.com/substack/stream-handbook) - How to write Node.js programs with streams. :star:11191
- [browserify-handbook](https://github.com/substack/browserify-handbook) - The definitive guide for browserify. :star:4190
- [module-best-practices](https://github.com/mattdesl/module-best-practices) - Some good practices when writing new npm modules. :star:1023
- [The Node Way](http://thenodeway.io) - An entire philosophy of Node.js best practices and guiding principles exists for writing maintainable modules, scalable applications, and code that is actually pleasant to read.
- [You Don't Know Node.js](https://github.com/azat-co/you-dont-know-node) - Introduction to Node.js core features and asynchronous JavaScript. :star:778


### Discovery

- [npms](https://npms.io) - Superb package search with deep analysis of package quality using a [myriad of metrics](https://npms.io/about).
- [node-modules.com](http://node-modules.com) - An alternative npm search engine with a more intelligent and personal results ranking.
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
- [Art of README](https://github.com/noffle/art-of-readme) - Learn the art of writing quality READMEs. :star:4618

### Newsletters

- [node weekly](http://nodeweekly.com) - Weekly e-mail round-up of Node.js news and articles.
- [nmotw](http://nmotw.in) - Node Module Of The Week, weekly dose of hand picked node modules.

### Videos

- [Introduction to Node.js with Ryan Dahl](https://www.youtube.com/watch?v=jo_B4LTHi3I)
- [Hands on with Node.js](https://learn.bevry.me/node/preface)
- [Full Streams Ahead](http://dry.ly/full-streams-ahead) - Introduction to streams.
- [StrongLoop Talks](https://strongloop.com/node-js/videos/) - Series of talks.
- [thenewboston's Node.js for Beginners](https://www.thenewboston.com/videos.php?cat=355)
- [Nodetuts](http://nodetuts.com) - Series of talks, including TCP & HTTP API servers, async programming, and more.
- [Node Interactive 2015](https://github.com/duffn/nodeinteractive-2015) - List of talks, keynotes and panels from the 2015 Node Interactive conference. :star:36

### Podcasts

- [NodeUp](http://nodeup.com)
- [Mostly Node](http://mostlynode.com)

### Books

- [Node.js in Action](http://www.amazon.com/Node-js-Action-Mike-Cantelon/dp/1617290572)
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
- [HowToNode](http://howtonode.org) - Teaching how to do various tasks in Node.js as well as teach fundamental concepts that are needed to write effective code.
- [webapplog.com](http://webapplog.com/tag/node-js/) - Blog posts on Node.js and JavaScript from the author of Practical Node.js and Pro Express.js Azat Mardan.

### Courses

- [Real Time Web with Node.js](https://www.codeschool.com/courses/real-time-web-with-node-js)
- [Learn and Understand Node.js](https://www.udemy.com/understand-nodejs)
- [Learn to build apps and APIs with Node.js](https://learnnode.com/friend/AWESOME) - Video course by Wes Bos.

### Cheatsheets

- [Express.js](https://github.com/azat-co/cheatsheets/blob/master/express4)
- [Stream FAQs](https://github.com/stephenplusplus/stream-faqs) - Answering common questions about streams, covering pagination, events, and more. :star:152

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
- [node-module-boilerplate](https://github.com/sindresorhus/node-module-boilerplate) - Boilerplate to kickstart creating a node module. :star:387
- [generator-nm](https://github.com/sindresorhus/generator-nm) - Scaffold out a node module. :star:509
- [awesome-cross-platform-nodejs](https://github.com/bcoe/awesome-cross-platform-nodejs) - Resources for writing and testing cross-platform code. :star:220
- [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) - Tips, tricks, and resources for working with Node.js on Microsoft platforms. :star:1833


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.


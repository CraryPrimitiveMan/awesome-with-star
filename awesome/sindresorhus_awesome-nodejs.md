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

- [webtorrent](https://github.com/feross/webtorrent) - Streaming torrent client for Node.js and the browser. :star:15970
- [peerflix](https://github.com/mafintosh/peerflix) - Streaming torrent client. :star:4634
- [dat](http://dat-data.com) - Real-time replication and versioning for data sets.
- [ipfs](https://github.com/ipfs/js-ipfs) - Distributed file system that seeks to connect all computing devices with the same system of files. :star:1895
- [GitTorrent](https://github.com/cjb/GitTorrent) - Peer-to-peer network of Git repositories being shared over BitTorrent. :star:3848
- [stackgl](http://stack.gl) - Open software ecosystem for WebGL, built on top of browserify and npm.
- [peerwiki](https://github.com/mafintosh/peerwiki) - All of Wikipedia on BitTorrent. :star:269
- [peercast](https://github.com/mafintosh/peercast) - Stream a torrent video to Chromecast. :star:365
- [BitcoinJS](http://bitcoinjs.org) - Clean, readable, proven Bitcoin library.
- [Bitcore](https://bitcore.io) - Pure and powerful Bitcoin library.
- [PDFKit](http://pdfkit.org) - PDF generation library.
- [turf](https://github.com/Turfjs/turf) - Modular geospatial processing and analysis engine. :star:3371
- [webcat](https://github.com/mafintosh/webcat) - p2p pipe across the web using WebRTC that uses your GitHub private/public key for authentication. :star:361
- [NodeOS](http://node-os.com) - The first operating system powered by npm.
- [limdu](https://github.com/erelsgl/limdu) - Machine-learning framework. :star:855
- [Cytoscape.js](http://js.cytoscape.org) - Graph theory (a.k.a. network) modeling and analysis.
- [kad](https://github.com/kadtools/kad) - Kademlia distributed hash table. :star:293
- [seedshot](https://github.com/twobucks/seedshot) - Temporary P2P screenshot sharing from your browser. :star:168
- [js-git](https://github.com/creationix/js-git) - JavaScript implementation of Git. :star:3285
- [skale](https://github.com/skale-me/skale-engine) - High performance distributed data processing engine. :star:233


### Command-line apps

- [np](https://github.com/sindresorhus/np) - Better `npm publish`. :star:2887
- [trash](https://github.com/sindresorhus/trash) - Safer alternative to `rm`. :star:1490
- [npm-name](https://github.com/sindresorhus/npm-name) - Check whether a package name is available on npm. :star:70
- [speed-test](https://github.com/sindresorhus/speed-test) - Test your internet connection speed and ping. :star:2909
- [emoj](https://github.com/sindresorhus/emoj) - Find relevant emoji from text on the command-line. :star:1444
- [pageres](https://github.com/sindresorhus/pageres) - Capture website screenshots. :star:8243
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:161
- [vtop](https://github.com/MrRio/vtop) - More better top, with nice charts. :star:2605
- [empty-trash](https://github.com/sindresorhus/empty-trash) - Empty the trash. :star:83
- [is-up](https://github.com/sindresorhus/is-up) - Check whether a website is up or down. :star:270
- [is-online](https://github.com/sindresorhus/is-online) - Check if the internet connection is up. :star:365
- [public-ip](https://github.com/sindresorhus/public-ip) - Get your public IP address. :star:280
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - Copy & paste on the terminal. :star:127
- [ttystudio](https://github.com/chjj/ttystudio) - Record your terminal and compile it to a GIF or APNG without any external dependencies, bash scripts, gif concatenation, etc. :star:2900
- [XO](https://github.com/xojs/xo) - Enforce strict code style using the JavaScript happiness style. :star:3507
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style — One style to rule them all. :star:16845
- [ESLint](http://eslint.org) - The pluggable linting utility for JavaScript.
- [dev-time](https://github.com/samverschueren/dev-time-cli) - Get the current local time of a GitHub user. :star:145
- [David](https://github.com/alanshaw/david) - Tells you when your package npm dependencies are out of date. :star:798
- [http-server](https://github.com/indexzero/http-server) - Simple, zero-config command-line HTTP server. :star:6400
- [Live Server](https://github.com/tapio/live-server) - Development HTTP-server with livereload capability. :star:1940
- [bcat](https://github.com/kessler/node-bcat) - Pipe command output to web browsers. :star:261
- [normit](https://github.com/pawurb/normit) - Google Translate with speech synthesis in your terminal. :star:185
- [slap](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor. :star:4861
- [jsinspect](https://github.com/danielstjules/jsinspect) - Detect copy-pasted and structurally similar code. :star:1683
- [esformatter](https://github.com/millermedeiros/esformatter) - JavaScript code beautifier/formatter. :star:920
- [fkill](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform. :star:1868
- [pjs](https://github.com/danielstjules/pjs) - Pipeable JavaScript. Quickly filter, map, and reduce from the terminal. :star:325
- [license-checker](https://github.com/davglass/license-checker) - Check licenses of your app's dependencies. :star:563
- [browser-run](https://github.com/juliangruber/browser-run) - Easily run code in a browser environment. :star:302
- [tmpin](https://github.com/sindresorhus/tmpin) - Adds stdin support to any CLI app that accepts file input. :star:105
- [modhelp](https://github.com/runvnc/modhelp) - Syntax-highlighted module READMEs in terminal with ANSI-friendly pager. :star:21
- [wifi-password](https://github.com/kevva/wifi-password-cli) - Get the current wifi password. :star:107
- [wallpaper](https://github.com/sindresorhus/wallpaper) - Change the desktop wallpaper. :star:461
- [brightness](https://github.com/kevva/brightness-cli) - Change the screen brightness. :star:110
- [torrent](https://github.com/maxogden/torrent) - Download torrents. :star:506
- [tfa](https://github.com/jasnell/tfa) - Two-factor authentication client. :star:25
- [rtail](https://github.com/kilianc/rtail) - Terminal output to the browser in seconds, using UNIX pipes. :star:1417
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - Kill all Chrome tabs to improve performance, decrease battery usage, and save memory. :star:223
- [alex](https://github.com/wooorm/alex) - Catch insensitive, inconsiderate writing. :star:2168
- [vantage](https://github.com/dthree/vantage) - Distributed, realtime CLI for your live app. :star:3397
- [pen](https://github.com/noraesae/pen) - Live Markdown preview in the browser from your favorite editor. :star:182
- [subdownloader](https://github.com/beatfreaker/subdownloader) - Subtitle downloader for movies and TV series. :star:85
- [dark-mode](https://github.com/sindresorhus/dark-mode) - Toggle the macOS Dark Mode. :star:283
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP location finder. :star:151
- [Jsome](https://github.com/Javascipt/Jsome) - Pretty prints JSON with configurable colors and indentation. :star:101
- [itunes-remote](https://github.com/mischah/itunes-remote) - Interactively control iTunes. :star:299
- [text-meme](https://github.com/beatfreaker/text-meme-cli) - Generate a text meme. :star:56
- [mobicon](https://github.com/samverschueren/mobicon-cli) - Mobile app icon generator. :star:42
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - Mobile app splash screen generator. :star:22
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - Pretty git diff to HTML generator. :star:105
- [Cash](https://github.com/dthree/cash) - Cross-platform Unix shell commands in pure JavaScript. :star:7450
- [vaca](https://github.com/sindresorhus/vaca) - Get a random ASCII 🐮. :star:78
- [gh-home](https://github.com/sindresorhus/gh-home) - Open the GitHub page of the repo in the current directory. :star:94
- [npm-home](https://github.com/sindresorhus/npm-home) - Open the npm page of a package. :star:134
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - Try out npm packages in the terminal. :star:991
- [terminal-recorder](https://github.com/cortezcristian/terminal-recorder) - Record your terminal usage and export it to interactive HTML. :star:91
- [jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for source code. :star:625
- [atmo](https://github.com/Raathigesh/Atmo) - Server-side API mocking. :star:652
- [auto-install](https://github.com/siddharthkp/auto-install) - Auto installs dependencies as you code. :star:814
- [lessmd](https://github.com/linuxenko/lessmd) - Markdown in the terminal. :star:75
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - Find out which dependencies are slowing you down. :star:2034
- [localtunnel](https://github.com/localtunnel/localtunnel) - Expose your localhost to the world. :star:6325
- [svg-term-cli](https://github.com/marionebl/svg-term-cli) - Share terminal sessions via SVG. :star:363
- [gtop](https://github.com/aksakalli/gtop) - System monitoring dashboard for the terminal. :star:6615


### Functional programming

- [lodash](https://lodash.com) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections. :star:22661
- [mori](http://swannodette.github.io/mori/) - Library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.
- [Ramda](http://ramdajs.com) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data.
- [Folktale](http://folktale.origamitower.com) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse.
- [underscore-contrib](http://documentcloud.github.io/underscore-contrib/) - The brass buckles on Underscore's utility belt.
- [Mout](http://moutjs.com) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead.
- [Bacon.js](http://baconjs.github.io) - Functional reactive programming.
- [RxJS](http://reactivex.io) - Functional reactive library for transforming, composing, and querying various kinds of data.
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases. :star:4581
- [Kefir.js](https://github.com/rpominov/kefir) - Reactive library with focus on high performance and low memory usage. :star:1


### HTTP

- [got](https://github.com/sindresorhus/got) - Nicer interface to the built-in `http` module. :star:2418
- [gh-got](https://github.com/sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API. :star:104
- [axios](https://github.com/mzabriskie/axios) - Promise based HTTP client (works in the browser too). :star:36904
- [request](https://github.com/request/request) - Simplified HTTP request client. :star:18676
- [Nock](https://github.com/pgte/nock) - HTTP mocking and expectations library. :star:5938
- [spdy](https://github.com/indutny/node-spdy) - Creates SPDY servers with the same API as the built-in `https` module. :star:2425
- [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities. :star:300
- [download](https://github.com/kevva/download) - Download and extract files effortlessly. :star:644
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP proxy. :star:8421
- [rocky](https://github.com/h2non/rocky) - Featured, middleware-oriented HTTP proxy with traffic replay and intercept. :star:305
- [superagent](https://github.com/visionmedia/superagent) - HTTP request library. :star:12331
- [node-fetch](https://github.com/bitinn/node-fetch) - `window.fetch` for Node.js. :star:2674
- [flashheart](https://github.com/bbc/flashheart) - REST client. :star:81
- [http-fake-backend](https://github.com/micromata/http-fake-backend) - Build a fake backend by providing the content of JSON files or JavaScript objects through configurable routes. :star:126
- [cacheable-request](https://github.com/lukechilds/cacheable-request) - Wrap native HTTP requests with RFC compliant cache support. :star:91


### Debugging / Profiling

- [ironNode](https://github.com/s-a/iron-node) - Node.js debugger supporting ES2015 out of the box. :star:2367
- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools. :star:12013
- [devtool](https://github.com/Jam3/devtool) - Run Node.js programs through Chrome Dev Tools. :star:3771
- [Theseus](https://github.com/adobe-research/theseus) - JavaScript debugger featuring real-time code coverage, retroactive inspection and asynchronous call tree. :star:1354
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility. :star:5657
- [jstrace](https://github.com/jstrace/jstrace) - Dynamic tracing for JavaScript, similar to dtrace, ktap etc. :star:381
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - Node.js is running but you don't know why? :star:655
- [njsTrace](https://github.com/valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function. :star:208
- [vstream](https://github.com/joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams. :star:53
- [stackman](https://github.com/watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies. :star:148
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables. :star:237
- [bugger](https://github.com/buggerjs/bugger) - Provides Chrome Devtools bindings to debug programs in Chrome. :star:154
- [0x](https://github.com/davidmarkclements/0x) - Flamegraph profiling. :star:777
- [ctrace](https://github.com/automation-stack/ctrace) - Well-formatted and improved trace system calls and signals. :star:92
- [leakage](https://github.com/andywer/leakage) - Write memory leak tests. :star:1204


### Logging

- [pino](https://github.com/pinojs/pino) - Extremely fast logger inspired by Bunyan. :star:2358
- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library. :star:9588
- [Bunyan](https://github.com/trentm/node-bunyan) - JSON logging library. :star:4855
- [intel](http://seanmonstar.github.io/intel/) - Logging library (handlers, filters, formatters, console injection).
- [console-log-level](https://github.com/watson/console-log-level) - The most simple logger imaginable with support for log levels and custom prefixes. :star:23
- [storyboard](https://github.com/guigrpa/storyboard) - End-to-end, hierarchical, real-time, colorful logs and stories. :star:423


### Command-line utilities

- [chalk](https://github.com/chalk/chalk) - Terminal string styling done right. :star:8166
- [meow](https://github.com/sindresorhus/meow) - CLI app helper. :star:1141
- [minimist](https://github.com/substack/minimist) - Parse command-line flags. :star:2776
- [get-stdin](https://github.com/sindresorhus/get-stdin) - Easier stdin. :star:147
- [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner. :star:2588
- [log-update](https://github.com/sindresorhus/log-update) - Log by overwriting the previous output in the terminal. Useful for rendering progress bars, animations, etc. :star:429
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt. :star:6402
- [listr](https://github.com/samverschueren/listr) - Terminal task list. :star:1344
- [conf](https://github.com/sindresorhus/conf) - Simple config handling for your app or module. :star:229
- [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app. :star:907
- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - ANSI escape codes for manipulating the terminal. :star:168
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels. :star:295
- [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows CMD fallbacks. :star:212
- [boxen](https://github.com/sindresorhus/boxen) - Create boxes in the terminal. :star:305
- [string-width](https://github.com/sindresorhus/string-width) - Get the visual width of a string - the number of columns required to display it. :star:85
- [cli-truncate](https://github.com/sindresorhus/cli-truncate) - Truncate a string to a specific width in the terminal. :star:26
- [first-run](https://github.com/sindresorhus/first-run) - Check if it's the first time the process is run. :star:48
- [vorpal](https://github.com/dthree/vorpal) - Interactive CLI apps. :star:4494
- [blessed](https://github.com/chjj/blessed) - Curses-like library. :star:7155
- [yn](https://github.com/sindresorhus/yn) - Parse yes/no like values. :star:101
- [cli-table](https://github.com/Automattic/cli-table) - Pretty unicode tables. :star:1502
- [drawille](https://github.com/madbence/node-drawille) - Draw on the terminal with unicode braille characters. :star:713
- [sudo-block](https://github.com/sindresorhus/sudo-block) - Block users from running your app with root permissions. :star:55
- [googleauth](https://github.com/maxogden/googleauth) - Create and load persistent Google authentication tokens for command-line apps. :star:46
- [ascii-charts](https://github.com/jstrace/chart) - ASCII bar chart in the terminal. :star:220
- [progress](https://github.com/tj/node-progress) - Flexible ascii progress bar. :star:1753
- [insight](https://github.com/yeoman/insight) - Helps you understand how your tool is being used by anonymously reporting usage metrics to Google Analytics. :star:401
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - Toggle the CLI cursor. :star:38
- [columnify](https://github.com/timoxley/columnify) - Create text-based columns suitable for console output. Supports cell wrapping. :star:277
- [cli-columns](https://github.com/shannonmoeller/cli-columns) - Columnated unicode and ansi-safe text lists. :star:8
- [cfonts](https://github.com/dominikwilkowski/cfonts) - Sexy ASCII fonts for the console. :star:263
- [multispinner](https://github.com/codekirei/node-multispinner) - Multiple, simultaneous, individually controllable CLI spinners. :star:200
- [omelette](https://github.com/f/omelette) - Shell autocompletion helper. :star:690
- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform. :star:2224
- [shelljs](https://github.com/shelljs/shelljs) - Portable Unix shell commands. :star:7359
- [loud-rejection](https://github.com/sindresorhus/loud-rejection) - Make unhandled promise rejections fail loudly instead of the default silent fail. :star:199
- [sparkly](https://github.com/sindresorhus/sparkly) - Generate sparklines ▁▂▃▅▂▇ :star:266
- [term-img](https://github.com/sindresorhus/term-img) - Display images in your terminal. :star:198
- [yargs](https://github.com/yargs/yargs) - Command-line parser that automatically generates an elegant user-interface. :star:4173
- [DraftLog](https://github.com/ivanseidel/node-draftlog) - Create multiple updatable log lines. Works just like `consol :star:879

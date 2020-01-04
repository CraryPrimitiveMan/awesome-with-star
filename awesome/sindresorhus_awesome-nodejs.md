# Information comes from [sindresorhus/awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs)
<div align="center">
	<div>
		<img width="500" src="media/logo.svg" alt="Awesome Node.js">
	</div>
	<br>
	<hr>
	<p>
		<sup>Special thanks to:</sup>
		<br>
		<br>
		<a href="https://github.com/botpress/botpress">
			<img src="https://sindresorhus.com/assets/thanks/botpress-logo.svg" width="180" alt="Botpress">
		</a>
		<br>
		<sub><b>Botpress is an open-source conversational assistant creation platform.</b></sub>
		<br>
		<sub>They <a href="https://github.com/botpress/botpress/blob/master/.github/CONTRIBUTING.md">welcome contributions</a> from anyone, whether you're into machine learning,<br>want to get started in open-source, or just have an improvement idea.</sub>
		<br>
		<br>
		<br>
		<a href="https://segment.com">
			<img src="media/segment-logo.svg" width="180" alt="Segment">
		</a>
		<br>
		<sup>
			Save time setting up analytics with Segment. <a href="https://segment.com/jobs">We're hiring!</a>
		</sup>
	</p>
	<hr>
	<br>
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
- [Related lists](#related-lists)

## Packages

### Mad science

- [webtorrent](https://github.com/feross/webtorrent) - Streaming torrent client for Node.js and the browser. :star:21105
- [peerflix](https://github.com/mafintosh/peerflix) - Streaming torrent client. :star:5311
- [dat](https://github.com/datproject/dat-node) - Real-time replication and versioning for data sets. :star:477
- [ipfs](https://github.com/ipfs/js-ipfs) - Distributed file system that seeks to connect all computing devices with the same system of files. :star:4164
- [stackgl](https://github.com/stackgl) - Open software ecosystem for WebGL, built on top of browserify and npm.
- [peerwiki](https://github.com/mafintosh/peerwiki) - All of Wikipedia on BitTorrent. :star:296
- [peercast](https://github.com/mafintosh/peercast) - Stream a torrent video to Chromecast. :star:444
- [BitcoinJS](https://github.com/bitcoinjs/bitcoinjs-lib) - Clean, readable, proven Bitcoin library. :star:3746
- [Bitcore](https://github.com/bitpay/bitcore) - Pure and powerful Bitcoin library. :star:3489
- [PDFKit](https://github.com/devongovett/pdfkit) - PDF generation library. :star:5855
- [turf](https://github.com/Turfjs/turf) - Modular geospatial processing and analysis engine. :star:4942
- [webcat](https://github.com/mafintosh/webcat) - p2p pipe across the web using WebRTC that uses your GitHub private/public key for authentication. :star:400
- [NodeOS](https://github.com/NodeOS/NodeOS) - The first operating system powered by npm. :star:6120
- [YodaOS](https://github.com/yodaos-project/yodaos) - AI operating system. :star:987
- [Brain.js](https://github.com/BrainJS/brain.js) - Machine-learning framework. :star:10604
- [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) - Graph theory (a.k.a. network) modeling and analysis. :star:6265
- [Kadence](https://gitlab.com/deadcanaries/kadence) - Kademlia distributed hash table.
- [seedshot](https://github.com/twobucks/seedshot) - Temporary P2P screenshot sharing from your browser. :star:178
- [js-git](https://github.com/creationix/js-git) - JavaScript implementation of Git. :star:3608
- [skale](https://github.com/skale-me/skale-engine) - High performance distributed data processing engine. :star:361
- [xlsx](https://github.com/sheetjs/js-xlsx) - Pure JS Excel spreadsheet reader and writer. :star:19346
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - Pure JavaScript implementation of Git. :star:4180

### Command-line apps

- [np](https://github.com/sindresorhus/np) - Better `npm publish`. :star:4886
- [npm-name](https://github.com/sindresorhus/npm-name) - Check a package name's availability on npm. :star:112
- [gh-home](https://github.com/sindresorhus/gh-home) - Open the GitHub page of the repo in the current directory. :star:152
- [npm-home](https://github.com/sindresorhus/npm-home) - Open the npm page of a package. :star:164
- [trash](https://github.com/sindresorhus/trash) - Safer alternative to `rm`. :star:1919
- [speed-test](https://github.com/sindresorhus/speed-test) - Test your internet connection speed and ping. :star:3264
- [emoj](https://github.com/sindresorhus/emoj) - Find relevant emoji from text on the command-line. :star:1862
- [pageres](https://github.com/sindresorhus/pageres) - Capture website screenshots. :star:8932
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:248
- [vtop](https://github.com/MrRio/vtop) - More better top, with nice charts. :star:3484
- [empty-trash](https://github.com/sindresorhus/empty-trash) - Empty the trash. :star:101
- [is-up](https://github.com/sindresorhus/is-up) - Check whether a website is up or down. :star:326
- [is-online](https://github.com/sindresorhus/is-online) - Check if the internet connection is up. :star:816
- [public-ip](https://github.com/sindresorhus/public-ip) - Get your public IP address. :star:508
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - Copy & paste on the terminal. :star:344
- [XO](https://github.com/xojs/xo) - Enforce strict code style using the JavaScript happiness style. :star:4869
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style — One style to rule them all. :star:23007
- [ESLint](https://github.com/eslint/eslint) - The pluggable linting utility for JavaScript. :star:15584
- [dev-time](https://github.com/samverschueren/dev-time-cli) - Get the current local time of a GitHub user. :star:165
- [David](https://github.com/alanshaw/david) - Tells you when your package npm dependencies are out of date. :star:908
- [http-server](https://github.com/indexzero/http-server) - Simple, zero-config command-line HTTP server. :star:9050
- [Live Server](https://github.com/tapio/live-server) - Development HTTP-server with livereload capability. :star:3004
- [bcat](https://github.com/kessler/node-bcat) - Pipe command output to web browsers. :star:287
- [normit](https://github.com/pawurb/normit) - Google Translate with speech synthesis in your terminal. :star:204
- [fkill](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform. :star:5836
- [pjs](https://github.com/danielstjules/pjs) - Pipeable JavaScript. Quickly filter, map, and reduce from the terminal. :star:368
- [license-checker](https://github.com/davglass/license-checker) - Check licenses of your app's dependencies. :star:961
- [browser-run](https://github.com/juliangruber/browser-run) - Easily run code in a browser environment. :star:349
- [tmpin](https://github.com/sindresorhus/tmpin) - Adds stdin support to any CLI app that accepts file input. :star:111
- [wifi-password](https://github.com/kevva/wifi-password-cli) - Get the current wifi password. :star:189
- [wallpaper](https://github.com/sindresorhus/wallpaper) - Change the desktop wallpaper. :star:666
- [brightness](https://github.com/kevva/brightness-cli) - Change the screen brightness. :star:164
- [torrent](https://github.com/maxogden/torrent) - Download torrents. :star:560
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - Kill all Chrome tabs to improve performance, decrease battery usage, and save memory. :star:250
- [alex](https://github.com/wooorm/alex) - Catch insensitive, inconsiderate writing. :star:3317
- [pen](https://github.com/noraesae/pen) - Live Markdown preview in the browser from your favorite editor. :star:290
- [subdownloader](https://github.com/beatfreaker/subdownloader) - Subtitle downloader for movies and TV series. :star:119
- [dark-mode](https://github.com/sindresorhus/dark-mode) - Toggle the macOS Dark Mode. :star:462
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP location finder. :star:222
- [Jsome](https://github.com/Javascipt/Jsome) - Pretty prints JSON with configurable colors and indentation. :star:166
- [itunes-remote](https://github.com/mischah/itunes-remote) - Interactively control iTunes. :star:387
- [mobicon](https://github.com/samverschueren/mobicon-cli) - Mobile app icon generator. :star:75
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - Mobile app splash screen generator. :star:43
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - Pretty git diff to HTML generator. :star:226
- [Cash](https://github.com/dthree/cash) - Cross-platform Unix shell commands in pure JavaScript. :star:7663
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - Try out npm packages in the terminal. :star:1042
- [jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for source code. :star:1506
- [atmo](https://github.com/Raathigesh/Atmo) - Server-side API mocking. :star:778
- [auto-install](https://github.com/siddharthkp/auto-install) - Auto installs dependencies as you code. :star:1049
- [lessmd](https://github.com/linuxenko/lessmd) - Markdown in the terminal. :star:113
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - Find out which dependencies are slowing you down. :star:2493
- [localtunnel](https://github.com/localtunnel/localtunnel) - Expose your localhost to the world. :star:9366
- [svg-term-cli](https://github.com/marionebl/svg-term-cli) - Share terminal sessions via SVG. :star:1637
- [gtop](https://github.com/aksakalli/gtop) - System monitoring dashboard for the terminal. :star:7983
- [themer](https://github.com/mjswensen/themer) - Generate themes for your editor, terminal, wallpaper, Slack, and more. :star:2276
- [carbon-now-cli](https://github.com/mixn/carbon-now-cli) - Beautiful images of your code — from right inside your terminal. :star:4347
- [cash-cli](https://github.com/xxczaki/cash-cli) - Convert between 170 currencies. :star:126
- [taskbook](https://github.com/klauscfhq/taskbook) - Tasks, boards & notes for the command-line habitat. :star:7337
- [discharge](https://github.com/brandonweiss/discharge) - Easily deploy static websites to Amazon S3. :star:411
- [npkill](https://github.com/voidcosmos/npkill) - Easily find and remove old and heavy node_modules folders. :star:2275

### Functional programming

- [lodash](https://github.com/lodash/lodash) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js. :star:43029
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections. :star:28999
- [Ramda](https://github.com/ramda/ramda) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data. :star:17813
- [Folktale](https://github.com/origamitower/folktale) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse. :star:1710
- [Mout](https://github.com/mout/mout) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead. :star:1168
- [Bacon.js](https://github.com/baconjs/bacon.js) - Functional reactive programming. :star:6205
- [RxJS](https://github.com/reactivex/rxjs) - Functional reactive library for transforming, composing, and querying various kinds of data. :star:20757
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases. :star:5839
- [Kefir.js](https://github.com/kefirjs/kefir) - Reactive library with focus on high performance and low memory usage. :star:1640

### HTTP

- [got](https://github.com/sindresorhus/got) - Nicer interface to the built-in `http` module. :star:6539
- [gh-got](https://github.com/sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API. :star:144
- [axios](https://github.com/mzabriskie/axios) - Promise based HTTP client (works in the browser too). :star:68329
- [request](https://github.com/request/request) - Simplified HTTP request client. :star:23882
- [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities. :star:368
- [download](https://github.com/kevva/download) - Download and extract files effortlessly. :star:926
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP proxy. :star:10808
- [superagent](https://github.com/visionmedia/superagent) - HTTP request library. :star:14761
- [node-fetch](https://github.com/bitinn/node-fetch) - `window.fetch` for Node.js. :star:4556
- [flashheart](https://github.com/bbc/flashheart) - REST client. :star:107
- [http-fake-backend](https://github.com/micromata/http-fake-backend) - Build a fake backend by providing the content of JSON files or JavaScript objects through configurable routes. :star:217
- [cacheable-request](https://github.com/lukechilds/cacheable-request) - Wrap native HTTP requests with RFC compliant cache support. :star:193
- [gotql](https://github.com/khaosdoctor/gotql) - GraphQL request library built on [got](https://github.com/sindresorhus/got). :star:220
- [global-agent](https://github.com/gajus/global-agent) - Global HTTP/HTTPS proxy agent that is configurable using environment variables. :star:57

### Debugging / Profiling

- [ndb](https://github.com/GoogleChromeLabs/ndb) - Improved debugging experience, enabled by Chrome DevTools. :star:9774
- [ironNode](https://github.com/s-a/iron-node) - Node.js debugger supporting ES2015 out of the box. :star:2371
- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools. :star:12492
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility. :star:8374
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - Node.js is running but you don't know why? :star:1038
- [njsTrace](https://github.com/valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function. :star:270
- [vstream](https://github.com/joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams. :star:57
- [stackman](https://github.com/watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies. :star:208
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables. :star:273
- [0x](https://github.com/davidmarkclements/0x) - Flamegraph profiling. :star:1689
- [ctrace](https://github.com/automation-stack/ctrace) - Well-formatted and improved trace system calls and signals. :star:108
- [leakage](https://github.com/andywer/leakage) - Write memory leak tests. :star:1425
- [llnode](https://github.com/nodejs/llnode) - Post-mortem analysis tool which allows you to inspect objects and get insights from a crashed Node.js process. :star:785
- [thetool](https://github.com/sfninja/thetool) - Capture different CPU, memory, and other profiles for your app in Chrome DevTools friendly format. :star:134
- [swagger-stats](https://github.com/slanatech/swagger-stats) - Trace API calls and monitor API performance, health, and usage metrics. :star:359

### Logging

- [pino](https://github.com/pinojs/pino) - Extremely fast logger inspired by Bunyan. :star:4863
- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library. :star:14634
- [console-log-level](https://github.com/watson/console-log-level) - The most simple logger imaginable with support for log levels and custom prefixes. :star:53
- [storyboard](https://github.com/guigrpa/storyboard) - End-to-end, hierarchical, real-time, colorful logs and stories. :star:584
- [signale](https://github.com/klauscfhq/signale) - Hackable console logger with beautiful output. :star:7941

### Command-line utilities

- [chalk](https://github.com/chalk/chalk) - Terminal string styling done right. :star:13745
- [meow](https://github.com/sindresorhus/meow) - CLI app helper. :star:2031
- [yargs](https://github.com/yargs/yargs) - Command-line parser that automatically generates an elegant user-interface. :star:7143
- [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner. :star:5526
- [get-stdin](https://github.com/sindresorhus/get-stdin) - Easier stdin. :star:241
- [log-update](https://github.com/sindresorhus/log-update) - Log by overwriting the previous output in the terminal. Useful for rendering progress bars, animations, etc. :star:728
- [Ink](https://github.com/vadimdemedes/ink) - React for interactive command-line apps. :star:12574
- [listr](https://github.com/samverschueren/listr) - Terminal task list. :star:2360
- [conf](https://github.com/sindresorhus/conf) - Simple config handling for your app or module. :star:510
- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - ANSI escape codes for manipulating the terminal. :star:283
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels. :star:492
- [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows CMD fallbacks. :star:375
- [boxen](https://github.com/sindresorhus/boxen) - Create boxes in the terminal. :star:675
- [terminal-link](https://github.com/sindresorhus/terminal-link) - Create clickable links in the terminal. :star:244
- [terminal-image](https://github.com/sindresorhus/terminal-image) - Display images in the terminal. :star:469
- [string-width](https://github.com/sindresorhus/string-width) - Get the visual width of a string - the number of columns required to display it. :star:170
- [cli-truncate](https://github.com/sindresorhus/cli-truncate) - Truncate a string to a specific width in the terminal. :star:50
- [first-run](https://github.com/sindresorhus/first-run) - Check if it's the first time the process is run. :star:68
- [blessed](https://github.com/chjj/blessed) - Curses-like library. :star:8857
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt. :star:11696
- [yn](https://github.com/sindresorhus/yn) - Parse yes/no like values. :star:178
- [cli-table3](https://github.com/cli-table/cli-table3) - Pretty unicode tables. :star:117
- [drawille](https://github.com/madbence/node-drawille) - Draw on the terminal with unicode braille characters. :star:853
- [update-notifier](https://github.com/yeoman/update-notifier) - Update notifications for your CLI app. :star:1324
- [ascii-charts](https://github.com/jstrace/chart) - ASCII bar chart in the terminal. :star:223
- [progress](https://github.com/tj/node-progress) - Flexible ascii progress bar. :star:2355
- [insight](https://github.com/yeoman/insight) - Helps you understand how your tool is being used by anonymously reporting usage metrics to Google Analytics. :star:483
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - Toggle the CLI cursor. :star:61
- [columnify](https://github.com/timoxley/columnify) - Create text-based columns suitable for console output. Supports cell wrapping. :star:366
- [cli-columns](https://github.com/shannonmoeller/cli-columns) - Columnated unicode and ansi-safe text lists. :star:22
- [cfonts](https://github.com/dominikwilkowski/cfonts) - Sexy ASCII fonts for the console. :star:530
- [multispinner](https://github.com/codekirei/node-multispinner) - Multiple, simultaneous, individually controllable CLI spinners. :star:259
- [omelette](https://github.com/f/omelette) - Shell autocompletion helper. :star:900
- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform. :star:4404
- [shelljs](https://github.com/shelljs/shelljs) - Portable Unix shell commands. :star:10610
- [sudo-block](https://github.com/sindresorhus/sudo-block) - Block users from running your app with root permissions. :star:78
- [loud-rejection](https://github.com/sindresorhus/loud-rejection) - Make unhandled promise rejections fail loudly instead of the default silent fail. :star:253
- [sparkly](https://github.com/sindresorhus/sparkly) - Generate sparklines `▁▂▃▅▂▇`. :star:345
- [Bit](https://github.com/teambit/bit) - Create, maintain, find and use small modules and components across repositories. :star:9725
- [gradient-string](https://github.com/bokub/gradient-string) - Beautiful color gradients in terminal output. :star:399
- [oclif](https://github.com/oclif/oclif) - CLI framework complete with parser, automatic documentation, testing, and plugins. :star:4373
- [term-size](https://github.com/sindresorhus/term-size) - Reliably get the terminal window size. :star:101
- [Cliffy](https://github.com/drew-y/cliffy) - Framework for interactive CLIs. :star:219

### Build tools

- [parcel](https://github.com/parcel-bundler/parcel) - Blazing fast, zero config web app bundler. :star:34223
- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser. :star:52458
- [rollup](https://github.com/rollup/rollup) - Next-generation ES2015 module bundler. :star:17267
- [gulp](https://github.com/gulpjs/gulp) - Streaming and fast build system that favors code over config. :star:31602
- [Broccoli](https://github.com/broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions. :star:3267
- [Brunch](https://github.com/brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow. :star:6637
- [Start](https://github.com/deepsweet/start) - Functional task runner with shareable presets. :star:481
- [ygor](https://github.com/shannonmoeller/ygor) - Promising task runner for when `npm run` isn't enough and everything else is too much. :star:64
- [FuseBox](https://github.com/fuse-box/fuse-box) - Fast build system that combines the power of webpack, JSPM and SystemJS, with first-class TypeScript support. :star:3918
- [pkg](https://github.com/zeit/pkg) - Package your Node.js project into an executable. :star:15077

### Hardware

- [johnny-five](https://github.com/rwaldron/johnny-five) - Firmata based Arduino Framework. :star:11183
- [serialport](https://github.com/voodootikigod/node-serialport) - Access serial ports for reading and writing. :star:4246
- [usb](https://github.com/nonolith/node-usb) - USB library. :star:889
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C serial bus access. :star:209
- [onoff](https://github.com/fivdi/onoff) - GPIO access and interrupt detection. :star:901
- [spi-device](https://github.com/fivdi/spi-device) - SPI serial bus access. :star:75
- [pigpio](https://github.com/fivdi/pigpio) - Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi. :star:592
- [gps](https://github.com/infusion/GPS.js) - NMEA parser for handling GPS receivers. :star:129

### Templating

- [marko](https://github.com/marko-js/marko) - HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags. :star:9343
- [nunjucks](https://github.com/mozilla/nunjucks) - Templating engine with inheritance, asynchronous control, and more (jinja2 inspired). :star:6444
- [handlebars.js](https://github.com/wycats/handlebars.js) - Superset of Mustache templates which adds powerful features like helpers and more advanced blocks. :star:15016
- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language. :star:4082
- [Pug](https://github.com/pugjs/pug) - High-performance template engine heavily influenced by Haml. :star:18886

### Web frameworks

- [Hapi](https://github.com/hapijs/hapi) - Framework for building applications and services. :star:11932
- [Koa](https://github.com/koajs/koa) - Framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs. :star:28228
- [Express](https://github.com/expressjs/express) - Web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications. :star:46789
- [Feathers](https://github.com/feathersjs/feathers) - Microservice framework built in the spirit of Express. :star:11998
- [LoopBack](https://github.com/strongloop/loopback) - Powerful framework for creating REST APIs and easily connecting to backend data sources. :star:12991
- [Meteor](https://github.com/meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor](https://github.com/Urigo/awesome-meteor))* :star:41510
- [Restify](https://github.com/restify/node-restify) - Enables you to build correct REST web services. :star:9614
- [ThinkJS](https://github.com/thinkjs/thinkjs) - Framework with ES2015+ support, WebSockets, REST API. :star:5044
- [ActionHero](https://github.com/actionhero/actionhero) - Framework for making reusable & scalable APIs for TCP sockets, WebSockets, and HTTP clients. :star:2062
- [Next.js](https://github.com/zeit/next.js) - Minimalistic framework for server-rendered universal JavaScript web apps. :star:43675
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Minimalistic framework for server-rendered Vue.js apps. :star:24649
- [seneca](https://github.com/senecajs/seneca) - Toolkit for writing microservices. :star:3611
- [AdonisJs](http://adonisjs.com) - A true MVC framework for Node.js built on solid foundations of Dependency Injection and IoC container.
- [Hemera](https://github.com/hemerajs/hemera) - Write reliable and fault-tolerant microservices with [NATS](https://nats.io). :star:719
- [Micro](https://github.com/zeit/micro) - Minimalistic microservice framework with an async approach. :star:8979
- [Moleculer](https://moleculer.services) - Fast & powerful microservices framework.
- [Fastify](https://github.com/fastify/fastify) - Fast and low overhead web framework. :star:13069
- [Nest](https://github.com/nestjs/nest) - Angular-inspired framework for building efficient and scalable server-side apps. :star:22899
- [Zeronode](https://github.com/sfast/zeronode) - Minimal building block for reliable and fault-tolerant microservices. :star:100
- [TypeGraphQL](https://github.com/19majkel94/type-graphql) - Modern framework for creating GraphQL APIs with TypeScript, using classes and decorators. :star:3500

### Documentation

- [documentation.js](https://github.com/documentationjs/documentation) - API documentation generator with support for ES2015+ and flow annotation. :star:4920
- [ESDoc](https://github.com/esdoc/esdoc) - Documentation generator targeting ES2015, attaching test code and measuring documentation coverage. :star:2540
- [Docco](https://github.com/jashkenas/docco) - Documentation generator which produces an HTML document that displays your comments intermingled with your code. :star:3422
- [JSDoc](https://github.com/jsdoc3/jsdoc) - API documentation generator similar to JavaDoc or PHPDoc. :star:10173

### Filesystem

- [del](https://github.com/sindresorhus/del) - Delete files/folders using globs. :star:1035
- [globby](https://github.com/sindresorhus/globby) - Glob files with support for multiple patterns. :star:1307
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:248
- [rimraf](https://github.com/isaacs/rimraf) - Recursively delete files like `rm -rf`. :star:3552
- [make-dir](https://github.com/sindresorhus/make-dir) - Recursively create directories like `mkdir -p`. :star:388
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Drop-in replacement for the `fs` module with various improvements. :star:925
- [chokidar](https://github.com/paulmillr/chokidar) - Filesystem watcher which stabilizes events from `fs.watch` and `fs.watchFile` as well as using native `fsevents` on macOS. :star:6144
- [find-up](https://github.com/sindresorhus/find-up) - Find a file by walking up parent directories. :star:258
- [proper-lockfile](https://github.com/IndigoUnited/node-proper-lockfile) - Inter-process and inter-machine lockfile utility. :star:96
- [load-json-file](https://github.com/sindresorhus/load-json-file) - Read and parse a JSON file. :star:155
- [write-json-file](https://github.com/sindresorhus/write-json-file) - Stringify and write JSON to a file atomically. :star:137
- [fs-write-stream-atomic](https://github.com/npm/fs-write-stream-atomic) - Like `fs.createWriteStream()`, but atomic. :star:46
- [filenamify](https://github.com/sindresorhus/filenamify) - Convert a string to a valid filename. :star:267
- [lnfs](https://github.com/kevva/lnfs) - Force create symlinks like `ln -fs`. :star:9
- [istextorbinary](https://github.com/bevry/istextorbinary) - Check if a file is text or binary. :star:63
- [fs-jetpack](https://github.com/szwacz/fs-jetpack) - Completely redesigned file system API for convenience in everyday use. :star:515
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Extra methods for the `fs` module. :star:6455
- [pkg-dir](https://github.com/sindresorhus/pkg-dir) - Find the root directory of an npm package. :star:117
- [filehound](https://github.com/nspragg/filehound) - Flexible and fluent interface for searching the file system. :star:167
- [move-file](https://github.com/sindresorhus/move-file) - Move a file, even works across devices. :star:134
- [tempy](https://github.com/sindresorhus/tempy) - Get a random temporary file or directory path. :star:220

### Control flow

- Promises
	- [Bluebird](https://github.com/petkaantonov/bluebird) - Promise library with focus on innovative features and performance. :star:18845
	- [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function. :star:1232
	- [delay](https://github.com/sindresorhus/delay) - Delay a promise a specified amount of time. :star:359
	- [promise-memoize](https://github.com/nodeca/promise-memoize) - Memoize promise-returning functions, with expire and prefetch. :star:42
	- [valvelet](https://github.com/lpinca/valvelet) - Limit the execution rate of a promise-returning function. :star:25
	- [p-map](https://github.com/sindresorhus/p-map) - Map over promises concurrently. :star:486
	- [More…](https://github.com/sindresorhus/promise-fun) :star:2787
- Observables
	- [zen-observable](https://github.com/zenparsing/zen-observable) - Implementation of Observables. :star:588
	- [RxJS](https://github.com/ReactiveX/RxJS) - Reactive programming. :star:20757
	- [observable-to-promise](https://github.com/sindresorhus/awesome-observables) - Convert an Observable to a Promise. :star:260
	- [More…](https://github.com/sindresorhus/awesome-observables) :star:260
- Streams
	- [Highland.js](https://github.com/caolan/highland) - Manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams. :star:3253
- Callbacks
	- [each-async](https://github.com/sindresorhus/each-async) - Async concurrent iterator like forEach. :star:107
	- [async](https://github.com/caolan/async) - Provides straight-forward, powerful functions for working with asynchronicity. :star:26263
- Channels
	- [js-csp](https://github.com/ubolonton/js-csp) - Communicating sequential processes for JavaScript (like Clojurescript core.async, or Go). :star:2250

### Streams

- [through2](https://github.com/rvagg/through2) - Tiny wrapper around streams2 Transform to avoid explicit subclassing noise. :star:1673
- [from2](https://github.com/hughsk/from2) - Convenience wrapper for ReadableStream, inspired by `through2`. :star:117
- [get-stream](https://github.com/sindresorhus/get-stream) - Get a stream as a string or buffer. :star:183
- [into-stream](https://github.com/sindresorhus/into-stream) - Convert a buffer/string/array/object into a stream. :star:142
- [duplexify](https://github.com/mafintosh/duplexify) - Turn a writeable and readable stream into a single streams2 duplex stream. :star:160
- [pumpify](https://github.com/mafintosh/pumpify) - Combine an array of streams into a single duplex stream. :star:175
- [peek-stream](https://github.com/mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it. :star:45
- [binary-split](https://github.com/maxogden/binary-split) - Newline (or any delimiter) splitter stream. :star:72
- [byline](https://github.com/jahewson/node-byline) - Super-simple line-by-line Stream reader. :star:286
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - Transform the first chunk in a stream. :star:21
- [pad-stream](https://github.com/sindresorhus/pad-stream) - Pad each line in a stream. :star:5
- [multistream](https://github.com/feross/multistream) - Combine multiple streams into a single stream. :star:199
- [stream-combiner2](https://github.com/substack/stream-combiner2) - Turn a pipeline into a single stream. :star:74
- [readable-stream](https://github.com/nodejs/readable-stream) - Mirror of Streams2 and Streams3 implementations in core. :star:791
- [through2-concurrent](https://github.com/almost/through2-concurrent) - Transform object streams concurrently. :star:73

### Real-time

- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - Highly scalable WebSocket server & client library. :star:11130
- [Socket.io](https://github.com/socketio/socket.io) - Enables real-time bidirectional event-based communication. :star:48439
- [Faye](https://github.com/faye/faye) - Real-time client-server message bus, based on Bayeux protocol. :star:4234
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores. :star:5527
- [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in. :star:4041
- [deepstream.io](https://github.com/deepstreamIO/deepstream.io-client-js) - Scalable real-time microservice framework. :star:250
- [Kalm](https://github.com/kalm/kalm.js) - Low-level socket router and middleware framework. :star:103
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - Client for MQTT - Pub-sub based messaging protocol for use on top of TCP/IP. :star:5087
- [rpc-websockets](https://github.com/elpheria/rpc-websockets) - JSON-RPC 2.0 implementation over WebSockets. :star:221
- [Aedes](https://github.com/mcollina/aedes) - Barebone MQTT server that can run on any stream server. :star:491

### Image

- [sharp](https://github.com/lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images. :star:15310
- [image-type](https://github.com/sindresorhus/image-type) - Detect the image type of a Buffer/Uint8Array. :star:197
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick and ImageMagick wrapper. :star:5956
- [lwip](https://github.com/EyalAr/lwip) - Lightweight image processor which does not require ImageMagick. :star:2233
- [pica](https://github.com/nodeca/pica) - High quality & fast resize (lanczos3) in pure JS. Alternative to canvas drawImage(), when no pixelation allowed. :star:1856
- [jimp](https://github.com/oliver-moran/jimp) - Image processing in pure JavaScript. :star:9520
- [probe-image-size](https://github.com/nodeca/probe-image-size) - Get the size of most image formats without a full download. :star:299
- [qrcode](https://github.com/soldair/node-qrcode) - QR code and bar code generator. :star:3645

### Text

- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - Convert character encodings. :star:2241
- [string-length](https://github.com/sindresorhus/string-length) - Get the real length of a string - by correctly counting astral symbols and ignoring ansi escape codes. :star:74
- [camelcase](https://github.com/sindresorhus/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar. :star:389
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - Escape RegExp special characters. :star:345
- [execall](https://github.com/sindresorhus/execall) - Find multiple RegExp matches in a string. :star:77
- [splice-string](https://github.com/sindresorhus/splice-string) - Remove or replace part of a string like `Array#splice`. :star:14
- [indent-string](https://github.com/sindresorhus/indent-string) - Indent each line in a string. :star:78
- [strip-indent](https://github.com/sindresorhus/strip-indent) - Strip leading whitespace from every line in a string. :star:92
- [detect-indent](https://github.com/sindresorhus/detect-indent) - Detect the indentation of code. :star:138
- [he](https://github.com/mathiasbynens/he) - HTML entity encoder/decoder. :star:2346
- [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage. :star:2473
- [babelfish](https://github.com/nodeca/babelfish) - i18n with very easy syntax for plurals. :star:208
- [matcher](https://github.com/sindresorhus/matcher) - Simple wildcard matching. :star:440
- [unhomoglyph](https://github.com/nodeca/unhomoglyph) - Normalize visually similar unicode characters. :star:17
- [i18next](https://github.com/i18next/i18next) - Internationalization framework. :star:4638
- [nanoid](https://github.com/ai/nanoid) - Tiny, secure, URL-friendly, unique string ID generator. :star:8213

### Number

- [random-int](https://github.com/sindresorhus/random-int) - Generate a random integer. :star:51
- [random-float](https://github.com/sindresorhus/random-float) - Generate a random float. :star:19
- [unique-random](https://github.com/sindresorhus/unique-random) - Generate random numbers that are consecutively unique. :star:75
- [round-to](https://github.com/sindresorhus/round-to) - Round a number to a specific number of decimal places: `1.234` → `1.2`. :star:111

### Math

- [ndarray](https://github.com/scijs/ndarray) - Multidimensional arrays. :star:895
- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library. :star:9387
- [math-clamp](https://github.com/sindresorhus/math-clamp) - Clamp a number. :star:6
- [algebra](https://github.com/fibo/algebra) - Algebraic structures. :star:83
- [multimath](https://github.com/nodeca/multimath) - Core to create fast image math in WebAssembly and JS. :star:41

### Date

- [Luxon](https://github.com/moment/luxon) - Library for working with dates and times. :star:8907
- [date-fns](https://github.com/date-fns/date-fns) - Modern date utility. :star:20816
- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.
- [Day.js](https://github.com/iamkun/dayjs) - Immutable date library alternative to Moment.js. :star:25133
- [dateformat](https://github.com/felixge/node-dateformat) - Date formatting. :star:1040
- [tz-format](https://github.com/samverschueren/tz-format) - Format a date with timezone: `2015-11-30T10:40:35+01:00`. :star:6
- [cctz](https://github.com/floatdrop/node-cctz) - Fast parsing, formatting, and timezone conversation for dates. :star:54

### URL

- [normalize-url](https://github.com/sindresorhus/normalize-url) - Normalize a URL. :star:408
- [humanize-url](https://github.com/sindresorhus/humanize-url) - Humanize a URL: http://sindresorhus.com → sindresorhus.com. :star:182
- [url-unshort](https://github.com/nodeca/url-unshort) - Expand shortened URLs. :star:39
- [speakingurl](https://github.com/pid/speakingurl) - Generate a slug from a string with transliteration. :star:1015
- [linkify-it](https://github.com/markdown-it/linkify-it) - Link patterns detector with full unicode support. :star:345
- [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for URLs and other strings. :star:471
- [embedza](https://github.com/nodeca/embedza) - Create HTML snippets/embeds from URLs using info from oEmbed, Open Graph, meta tags. :star:44

### Data validation

- [joi](https://github.com/hapijs/joi) - Object schema description language and validator for JavaScript objects. :star:13926
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast. :star:893
- [property-validator](https://github.com/nettofarah/property-validator) - Easy property validation for Express. :star:146
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API sanitization and validation. :star:463
- [ajv](https://github.com/epoberezkin/ajv) - The fastest JSON Schema validator. Supports v5, v6 and v7 proposals. :star:6802

### Parsing

- [remark](https://github.com/wooorm/remark) - Markdown processor powered by plugins. :star:2701
- [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser with 100% CommonMark support, extensions and syntax plugins. :star:8712
- [parse5](https://github.com/inikulin/parse5) - Fast full-featured spec compliant HTML parser. :star:2266
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - Strip comments from JSON. :star:443
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - Strip comments from CSS. :star:95
- [parse-json](https://github.com/sindresorhus/parse-json) - Parse JSON with more helpful errors. :star:166
- [URI.js](https://github.com/medialize/URI.js) - URL mutation. :star:5871
- [PostCSS](https://github.com/postcss/postcss) - CSS parser / stringifier. :star:21994
- [JSONStream](https://github.com/dominictarr/JSONStream) - Streaming JSON.parse and stringify. :star:1698
- [neat-csv](https://github.com/sindresorhus/neat-csv) - Fast CSV parser. Callback interface for the above. :star:138
- [csv-parser](https://github.com/mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else. :star:738
- [PEG.js](https://github.com/pegjs/pegjs) - Simple parser generator that produces fast parsers with excellent error reporting. :star:3528
- [x-ray](https://github.com/lapwinglabs/x-ray) - Web scraping utility. :star:5179
- [nearley](https://github.com/Hardmath123/nearley) - Simple, fast, powerful parsing for JavaScript. :star:2348
- [binary-extract](https://github.com/juliangruber/binary-extract) - Extract a value from a buffer of JSON without parsing the whole thing. :star:145
- [Stylecow](https://github.com/stylecow/stylecow) - Parse, manipulate and convert modern CSS to make it compatible with all browsers. Extensible with plugins. :star:136
- [js-yaml](https://github.com/nodeca/js-yaml) - Very fast YAML parser. :star:4251
- [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter. :star:3866
- [Jison](https://github.com/zaach/jison) - Friendly JavaScript parser generator. It shares genes with Bison, Yacc and family. :star:3564
- [google-libphonenumber](https://github.com/seegno/google-libphonenumber) - Parse, format, store and validate phone numbers. :star:769
- [ref](https://github.com/TooTallNate/ref) - Read/write structured binary data in Buffers. :star:351
- [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - Read/write Excel XLSX. :star:483
- [Chevrotain](https://github.com/SAP/chevrotain) - Very fast and feature rich parser building toolkit for JavaScript. :star:1228
- [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - Validate and parse XML. :star:645

### Humanize

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - Convert bytes to a human readable string: `1337` → `1.34 kB`. :star:524
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`. :star:446
- [ms](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility. :star:2609
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - Errors with less clutter. :star:1302
- [read-art](https://github.com/Tjatse/node-readability) - Extract readable content from any page. :star:294

### Compression

- [yazl](https://github.com/thejoshwolfe/yazl) - Zip. :star:222
- [yauzl](https://github.com/thejoshwolfe/yauzl) - Unzip. :star:449
- [Archiver](https://github.com/archiverjs/node-archiver) - Streaming interface for archive generation, supporting ZIP and TAR. :star:1779
- [pako](https://github.com/nodeca/pako) - High speed zlib port to pure js (deflate, inflate, gzip). :star:2681
- [tar-stream](https://github.com/mafintosh/tar-stream) - Streaming tar parser and generator. Also see [tar-fs](https://github.com/mafintosh/tar-fs). :star:271
- [decompress](https://github.com/kevva/decompress) - Decompression module with support for `tar`, `tar.gz` and `zip` files out of the box. :star:276

### Network

- [get-port](https://github.com/sindresorhus/get-port) - Get an available port. :star:464
- [ipify](https://github.com/sindresorhus/ipify) - Get your public IP address. :star:172
- [getmac](https://github.com/bevry/getmac) - Get the computer MAC address. :star:217
- [DHCP](https://github.com/infusion/node-dhcp) - DHCP client and server. :star:174
- [netcat](https://github.com/roccomuso/netcat) - Netcat port in pure JS. :star:266

### Database

- Drivers
	- [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL client. Pure JavaScript and native libpq bindings. :star:7981
	- [Redis](https://github.com/luin/ioredis) - Redis client. :star:6932
	- [LevelUP](https://github.com/Level/levelup) - LevelDB. :star:3660
	- [MySQL](https://github.com/mysqljs/mysql) - MySQL client. :star:14928
	- [couchdb-nano](https://github.com/apache/couchdb-nano) - CouchDB client. :star:336
	- [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Aerospike client. :star:162
	- [Couchbase](https://github.com/couchbase/couchnode) - Couchbase client. :star:417
	- [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB driver. :star:8353
- ODM / ORM
	- [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL. :star:20795
	- [Bookshelf](https://github.com/bookshelf/bookshelf) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js. :star:5756
	- [Massive](https://github.com/robconery/massive-js) - PostgreSQL data access tool. :star:2548
	- [Mongoose](https://github.com/Automattic/mongoose) - Elegant MongoDB object modeling. :star:20000
	- [Waterline](https://github.com/balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases. :star:5146
	- [OpenRecord](https://github.com/PhilWaldmann/openrecord) - ORM for PostgreSQL, MySQL, SQLite3 and RESTful datastores. Similar to ActiveRecord. :star:440
	- [pg-promise](https://github.com/vitaly-t/pg-promise) - PostgreSQL framework for native SQL using promises. :star:2480
	- [slonik](https://github.com/gajus/slonik) - PostgreSQL client with strict types, detailed logging and assertions. :star:1225
	- [Objection.js](https://github.com/Vincit/objection.js) - Lightweight ORM built on the SQL query builder Knex. :star:4723
	- [TypeORM](https://github.com/typeorm/typeorm) - ORM for PostgreSQL, MariaDB, MySQL, SQLite, and more. :star:16856
	- [MikroORM](https://github.com/mikro-orm/mikro-orm) - TypeScript ORM based on Data Mapper, Unit of Work and Identity Map patterns. Supports MongoDB, PostgreSQL, MySQL and SQLite. :star:482
- Query builder
	- [Knex](https://github.com/tgriesser/knex) - Query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use. :star:11177
- Other
	- [NeDB](https://github.com/louischatriot/nedb) - Embedded persistent database written in JavaScript. :star:10755
	- [Lowdb](https://github.com/typicode/lowdb) - Small JavaScript database powered by Lodash. :star:12085
	- [Keyv](https://github.com/lukechilds/keyv) - Simple key-value storage with support for multiple backends. :star:942
	- [Finale](https://github.com/tommybananas/finale) - RESTful endpoint generator for your Sequelize models. :star:133
	- [database-js](https://github.com/mlaanderson/database-js) - Wrapper for multiple databases with a JDBC-like connection. :star:28
	- [Mongo Seeding](https://github.com/pkosiec/mongo-seeding) - Populate MongoDB databases with JavaScript and JSON files. :star:189

### Testing

- [AVA](https://github.com/avajs/ava) - Futuristic test runner. :star:17317
- [Mocha](https://github.com/mochajs/mocha) - Feature-rich test framework making asynchronous testing simple and fun. :star:18820
- [nyc](https://github.com/bcoe/nyc) - Code coverage tool built on istanbul that works with subprocesses. :star:3944
- [tap](https://github.com/isaacs/node-tap) - TAP test framework. :star:1520
- [tape](https://github.com/substack/tape) - TAP-producing test harness. :star:5209
- [power-assert](https://github.com/power-assert-js/power-assert) - Provides descriptive assertion messages through the standard assert interface. :star:2436
- [Mochify](https://github.com/mantoni/mochify.js) - TDD with Browserify, Mocha, PhantomJS and WebDriver. :star:333
- [trevor](https://github.com/vdemedes/trevor) - Run tests against multiple versions of Node.js without switching versions manually or pushing to Travis CI. :star:2171
- [loadtest](https://github.com/alexfernandez/loadtest) - Run load tests for your web application, with an API for automation. :star:1778
- [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs and mocks. :star:7718
- [navit](https://github.com/nodeca/navit) - PhantomJS / SlimerJS wrapper to simplify browser test scripting. :star:45
- [Nock](https://github.com/pgte/nock) - HTTP mocking and expectations. :star:9006
- [intern](https://github.com/theintern/intern) - Code testing stack. :star:4166
- [toxy](https://github.com/h2non/toxy) - Hackable HTTP proxy to simulate failure scenarios and network conditions. :star:2612
- [hook-std](https://github.com/sindresorhus/hook-std) - Hook and modify stdout/stderr. :star:45
- [testen](https://github.com/egoist/testen) - Run tests for multiple versions of Node.js locally with NVM. :star:175
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - Automated UI testing framework based on Selenium WebDriver. :star:9943
- [WebdriverIO](https://github.com/webdriverio/webdriverio) - Automated testing based on the WebDriver protocol. :star:5399
- [Jest](https://github.com/facebook/jest) - Painless JavaScript testing. :star:29048
- [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing. :star:7718
- [abstruse](https://github.com/bleenco/abstruse) - Continuous Integration server. :star:562
- [CodeceptJS](https://github.com/Codeception/CodeceptJS) - End-to-end testing. :star:2590
- [Puppeteer](https://github.com/GoogleChrome/puppeteer) - Headless Chrome. :star:57277
- [nve](https://github.com/ehmicky/nve) - Run any command on multiple versions of Node.js locally. :star:496

### Security

- [upash](https://github.com/simonepri/upash) - Unified API for all password hashing algorithms. :star:449
- [themis](https://github.com/cossacklabs/the

# Information comes from [sindresorhus/awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs)
<div align="center">
	<div>
		<img width="500" src="media/logo.svg" alt="Awesome Node.js">
	</div>
	<br>
	<p>
		<sup>Special thanks to:</sup>
		<br>
		<br>
		<a href="https://github.com/botpress/botpress">
			<img src="https://sindresorhus.com/assets/thanks/botpress-logo.svg" width="180" alt="Botpress">
		</a>
		<br>
		<p>
			<sup>
				and
			</sup>
		</p>
		<a href="https://segment.com">
			<img src="media/segment-logo.svg" width="180" alt="Segment">
		</a>
		<br>
		<sup>
			Save time setting up analytics with Segment. <a href="https://segment.com/jobs">We're hiring!</a>
		</sup>
	</p>
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


## Packages

### Mad science

- [webtorrent](https://github.com/feross/webtorrent) - Streaming torrent client for Node.js and the browser. :star:20857
- [peerflix](https://github.com/mafintosh/peerflix) - Streaming torrent client. :star:5278
- [dat](https://github.com/datproject/dat-node) - Real-time replication and versioning for data sets. :star:475
- [ipfs](https://github.com/ipfs/js-ipfs) - Distributed file system that seeks to connect all computing devices with the same system of files. :star:4082
- [stackgl](https://github.com/stackgl) - Open software ecosystem for WebGL, built on top of browserify and npm.
- [peerwiki](https://github.com/mafintosh/peerwiki) - All of Wikipedia on BitTorrent. :star:296
- [peercast](https://github.com/mafintosh/peercast) - Stream a torrent video to Chromecast. :star:441
- [BitcoinJS](https://github.com/bitcoinjs/bitcoinjs-lib) - Clean, readable, proven Bitcoin library. :star:3718
- [Bitcore](https://github.com/bitpay/bitcore) - Pure and powerful Bitcoin library. :star:3473
- [PDFKit](https://github.com/devongovett/pdfkit) - PDF generation library. :star:5756
- [turf](https://github.com/Turfjs/turf) - Modular geospatial processing and analysis engine. :star:4868
- [webcat](https://github.com/mafintosh/webcat) - p2p pipe across the web using WebRTC that uses your GitHub private/public key for authentication. :star:400
- [NodeOS](https://github.com/NodeOS/NodeOS) - The first operating system powered by npm. :star:6083
- [YodaOS](https://github.com/yodaos-project/yodaos) - AI operating system. :star:980
- [Brain.js](https://github.com/BrainJS/brain.js) - Machine-learning framework. :star:10463
- [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) - Graph theory (a.k.a. network) modeling and analysis. :star:6190
- [Kadence](https://gitlab.com/deadcanaries/kadence) - Kademlia distributed hash table.
- [seedshot](https://github.com/twobucks/seedshot) - Temporary P2P screenshot sharing from your browser. :star:179
- [js-git](https://github.com/creationix/js-git) - JavaScript implementation of Git. :star:3596
- [skale](https://github.com/skale-me/skale-engine) - High performance distributed data processing engine. :star:359
- [xlsx](https://github.com/sheetjs/js-xlsx) - Pure JS Excel spreadsheet reader and writer. :star:18845
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - Pure JavaScript implementation of Git. :star:4135


### Command-line apps

- [np](https://github.com/sindresorhus/np) - Better `npm publish`. :star:4820
- [npm-name](https://github.com/sindresorhus/npm-name) - Check a package name's availability on npm. :star:112
- [gh-home](https://github.com/sindresorhus/gh-home) - Open the GitHub page of the repo in the current directory. :star:149
- [npm-home](https://github.com/sindresorhus/npm-home) - Open the npm page of a package. :star:163
- [trash](https://github.com/sindresorhus/trash) - Safer alternative to `rm`. :star:1908
- [speed-test](https://github.com/sindresorhus/speed-test) - Test your internet connection speed and ping. :star:3252
- [emoj](https://github.com/sindresorhus/emoj) - Find relevant emoji from text on the command-line. :star:1850
- [pageres](https://github.com/sindresorhus/pageres) - Capture website screenshots. :star:8915
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:238
- [vtop](https://github.com/MrRio/vtop) - More better top, with nice charts. :star:3455
- [empty-trash](https://github.com/sindresorhus/empty-trash) - Empty the trash. :star:103
- [is-up](https://github.com/sindresorhus/is-up) - Check whether a website is up or down. :star:324
- [is-online](https://github.com/sindresorhus/is-online) - Check if the internet connection is up. :star:807
- [public-ip](https://github.com/sindresorhus/public-ip) - Get your public IP address. :star:480
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - Copy & paste on the terminal. :star:341
- [XO](https://github.com/xojs/xo) - Enforce strict code style using the JavaScript happiness style. :star:4824
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style — One style to rule them all. :star:22846
- [ESLint](https://github.com/eslint/eslint) - The pluggable linting utility for JavaScript. :star:15410
- [dev-time](https://github.com/samverschueren/dev-time-cli) - Get the current local time of a GitHub user. :star:165
- [David](https://github.com/alanshaw/david) - Tells you when your package npm dependencies are out of date. :star:901
- [http-server](https://github.com/indexzero/http-server) - Simple, zero-config command-line HTTP server. :star:8946
- [Live Server](https://github.com/tapio/live-server) - Development HTTP-server with livereload capability. :star:2976
- [bcat](https://github.com/kessler/node-bcat) - Pipe command output to web browsers. :star:287
- [normit](https://github.com/pawurb/normit) - Google Translate with speech synthesis in your terminal. :star:203
- [fkill](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform. :star:5809
- [pjs](https://github.com/danielstjules/pjs) - Pipeable JavaScript. Quickly filter, map, and reduce from the terminal. :star:367
- [license-checker](https://github.com/davglass/license-checker) - Check licenses of your app's dependencies. :star:948
- [browser-run](https://github.com/juliangruber/browser-run) - Easily run code in a browser environment. :star:348
- [tmpin](https://github.com/sindresorhus/tmpin) - Adds stdin support to any CLI app that accepts file input. :star:111
- [wifi-password](https://github.com/kevva/wifi-password-cli) - Get the current wifi password. :star:186
- [wallpaper](https://github.com/sindresorhus/wallpaper) - Change the desktop wallpaper. :star:659
- [brightness](https://github.com/kevva/brightness-cli) - Change the screen brightness. :star:162
- [torrent](https://github.com/maxogden/torrent) - Download torrents. :star:556
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - Kill all Chrome tabs to improve performance, decrease battery usage, and save memory. :star:250
- [alex](https://github.com/wooorm/alex) - Catch insensitive, inconsiderate writing. :star:3270
- [pen](https://github.com/noraesae/pen) - Live Markdown preview in the browser from your favorite editor. :star:289
- [subdownloader](https://github.com/beatfreaker/subdownloader) - Subtitle downloader for movies and TV series. :star:116
- [dark-mode](https://github.com/sindresorhus/dark-mode) - Toggle the macOS Dark Mode. :star:458
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP location finder. :star:220
- [Jsome](https://github.com/Javascipt/Jsome) - Pretty prints JSON with configurable colors and indentation. :star:164
- [itunes-remote](https://github.com/mischah/itunes-remote) - Interactively control iTunes. :star:385
- [mobicon](https://github.com/samverschueren/mobicon-cli) - Mobile app icon generator. :star:74
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - Mobile app splash screen generator. :star:43
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - Pretty git diff to HTML generator. :star:218
- [Cash](https://github.com/dthree/cash) - Cross-platform Unix shell commands in pure JavaScript. :star:7652
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - Try out npm packages in the terminal. :star:1039
- [jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for source code. :star:1478
- [atmo](https://github.com/Raathigesh/Atmo) - Server-side API mocking. :star:776
- [auto-install](https://github.com/siddharthkp/auto-install) - Auto installs dependencies as you code. :star:1035
- [lessmd](https://github.com/linuxenko/lessmd) - Markdown in the terminal. :star:111
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - Find out which dependencies are slowing you down. :star:2481
- [localtunnel](https://github.com/localtunnel/localtunnel) - Expose your localhost to the world. :star:9220
- [svg-term-cli](https://github.com/marionebl/svg-term-cli) - Share terminal sessions via SVG. :star:1586
- [gtop](https://github.com/aksakalli/gtop) - System monitoring dashboard for the terminal. :star:7944
- [themer](https://github.com/mjswensen/themer) - Generate themes for your editor, terminal, wallpaper, Slack, and more. :star:2223
- [carbon-now-cli](https://github.com/mixn/carbon-now-cli) - Beautiful images of your code — from right inside your terminal. :star:4314
- [cash-cli](https://github.com/xxczaki/cash-cli) - Convert between 170 currencies. :star:121
- [taskbook](https://github.com/klauscfhq/taskbook) - Tasks, boards & notes for the command-line habitat. :star:7267
- [discharge](https://github.com/brandonweiss/discharge) - Easily deploy static websites to Amazon S3. :star:407
- [npkill](https://github.com/voidcosmos/npkill) - Easily find and remove old and heavy node_modules folders. :star:1870


### Functional programming

- [lodash](https://github.com/lodash/lodash) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js. :star:42560
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections. :star:28818
- [Ramda](https://github.com/ramda/ramda) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data. :star:17618
- [Folktale](https://github.com/origamitower/folktale) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse. :star:1688
- [Mout](https://github.com/mout/mout) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead. :star:1159
- [Bacon.js](https://github.com/baconjs/bacon.js) - Functional reactive programming. :star:6194
- [RxJS](https://github.com/reactivex/rxjs) - Functional reactive library for transforming, composing, and querying various kinds of data. :star:20452
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases. :star:5813
- [Kefir.js](https://github.com/kefirjs/kefir) - Reactive library with focus on high performance and low memory usage. :star:1629


### HTTP

- [got](https://github.com/sindresorhus/got) - Nicer interface to the built-in `http` module. :star:6145
- [gh-got](https://github.com/sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API. :star:143
- [axios](https://github.com/mzabriskie/axios) - Promise based HTTP client (works in the browser too). :star:67139
- [request](https://github.com/request/request) - Simplified HTTP request client. :star:23737
- [wreck](https://github.com/hapijs/wreck) - HTTP Client Utilities. :star:368
- [download](https://github.com/kevva/download) - Download and extract files effortlessly. :star:916
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP proxy. :star:10735
- [superagent](https://github.com/visionmedia/superagent) - HTTP request library. :star:14699
- [node-fetch](https://github.com/bitinn/node-fetch) - `window.fetch` for Node.js. :star:4485
- [flashheart](https://github.com/bbc/flashheart) - REST client. :star:107
- [http-fake-backend](https://github.com/micromata/http-fake-backend) - Build a fake backend by providing the content of JSON files or JavaScript objects through configurable routes. :star:215
- [cacheable-request](https://github.com/lukechilds/cacheable-request) - Wrap native HTTP requests with RFC compliant cache support. :star:193
- [gotql](https://github.com/khaosdoctor/gotql) - GraphQL request library built on [got](https://github.com/sindresorhus/got). :star:213
- [global-agent](https://github.com/gajus/global-agent) – Global HTTP/HTTPS proxy agent that is configurable using environment variables.


### Debugging / Profiling

- [ndb](https://github.com/GoogleChromeLabs/ndb) - Improved debugging experience, enabled by Chrome DevTools. :star:9721
- [ironNode](https://github.com/s-a/iron-node) - Node.js debugger supporting ES2015 out of the box. :star:2372
- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools. :star:12482
- [debug](https://github.com/visionmedia/debug) - Tiny debugging utility. :star:8275
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - Node.js is running but you don't know why? :star:1032
- [njsTrace](https://github.com/valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function. :star:266
- [vstream](https://github.com/joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams. :star:57
- [stackman](https://github.com/watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies. :star:206
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables. :star:270
- [0x](https://github.com/davidmarkclements/0x) - Flamegraph profiling. :star:1655
- [ctrace](https://github.com/automation-stack/ctrace) - Well-formatted and improved trace system calls and signals. :star:107
- [leakage](https://github.com/andywer/leakage) - Write memory leak tests. :star:1414
- [llnode](https://github.com/nodejs/llnode) - Post-mortem analysis tool which allows you to inspect objects and get insights from a crashed Node.js process. :star:774
- [thetool](https://github.com/sfninja/thetool) - Capture different CPU, memory, and other profiles for your app in Chrome DevTools friendly format. :star:131
- [swagger-stats](https://github.com/slanatech/swagger-stats) - Trace API calls and monitor API performance, health, and usage metrics. :star:334


### Logging

- [pino](https://github.com/pinojs/pino) - Extremely fast logger inspired by Bunyan. :star:4760
- [winston](https://github.com/winstonjs/winston) - Multi-transport async logging library. :star:14457
- [console-log-level](https://github.com/watson/console-log-level) - The most simple logger imaginable with support for log levels and custom prefixes. :star:52
- [storyboard](https://github.com/guigrpa/storyboard) - End-to-end, hierarchical, real-time, colorful logs and stories. :star:580
- [signale](https://github.com/klauscfhq/signale) - Hackable console logger with beautiful output. :star:7886


### Command-line utilities

- [chalk](https://github.com/chalk/chalk) - Terminal string styling done right. :star:13534
- [meow](https://github.com/sindresorhus/meow) - CLI app helper. :star:2002
- [yargs](https://github.com/yargs/yargs) - Command-line parser that automatically generates an elegant user-interface. :star:7037
- [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner. :star:5409
- [get-stdin](https://github.com/sindresorhus/get-stdin) - Easier stdin. :star:238
- [log-update](https://github.com/sindresorhus/log-update) - Log by overwriting the previous output in the terminal. Useful for rendering progress bars, animations, etc. :star:710
- [Ink](https://github.com/vadimdemedes/ink) - React for interactive command-line apps. :star:12438
- [listr](https://github.com/samverschueren/listr) - Terminal task list. :star:2330
- [conf](https://github.com/sindresorhus/conf) - Simple config handling for your app or module. :star:495
- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - ANSI escape codes for manipulating the terminal. :star:278
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels. :star:476
- [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows CMD fallbacks. :star:372
- [boxen](https://github.com/sindresorhus/boxen) - Create boxes in the terminal. :star:625
- [terminal-link](https://github.com/sindresorhus/terminal-link) - Create clickable links in the terminal. :star:232
- [terminal-image](https://github.com/sindresorhus/terminal-image) - Display images in the terminal. :star:462
- [string-width](https://github.com/sindresorhus/string-width) - Get the visual width of a string - the number of columns required to display it. :star:165
- [cli-truncate](https://github.com/sindresorhus/cli-truncate) - Truncate a string to a specific width in the terminal. :star:49
- [first-run](https://github.com/sindresorhus/first-run) - Check if it's the first time the process is run. :star:67
- [blessed](https://github.com/chjj/blessed) - Curses-like library. :star:8816
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Interactive command-line prompt. :star:11456
- [yn](https://github.com/sindresorhus/yn) - Parse yes/no like values. :star:172
- [cli-table3](https://github.com/cli-table/cli-table3) - Pretty unicode tables. :star:111
- [drawille](https://github.com/madbence/nod

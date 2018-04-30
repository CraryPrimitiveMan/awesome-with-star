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

- [webtorrent](https://github.com/feross/webtorrent) - Streaming torrent client for Node.js and the browser. :star:16529
- [peerflix](https://github.com/mafintosh/peerflix) - Streaming torrent client. :star:4710
- [dat](http://dat-data.com) - Real-time replication and versioning for data sets.
- [ipfs](https://github.com/ipfs/js-ipfs) - Distributed file system that seeks to connect all computing devices with the same system of files. :star:2232
- [GitTorrent](https://github.com/cjb/GitTorrent) - Peer-to-peer network of Git repositories being shared over BitTorrent. :star:3893
- [stackgl](http://stack.gl) - Open software ecosystem for WebGL, built on top of browserify and npm.
- [peerwiki](https://github.com/mafintosh/peerwiki) - All of Wikipedia on BitTorrent. :star:275
- [peercast](https://github.com/mafintosh/peercast) - Stream a torrent video to Chromecast. :star:373
- [BitcoinJS](http://bitcoinjs.org) - Clean, readable, proven Bitcoin library.
- [Bitcore](https://bitcore.io) - Pure and powerful Bitcoin library.
- [PDFKit](http://pdfkit.org) - PDF generation library.
- [turf](https://github.com/Turfjs/turf) - Modular geospatial processing and analysis engine. :star:3545
- [webcat](https://github.com/mafintosh/webcat) - p2p pipe across the web using WebRTC that uses your GitHub private/public key for authentication. :star:366
- [NodeOS](http://node-os.com) - The first operating system powered by npm.
- [limdu](https://github.com/erelsgl/limdu) - Machine-learning framework. :star:881
- [Cytoscape.js](http://js.cytoscape.org) - Graph theory (a.k.a. network) modeling and analysis.
- [kad](https://github.com/kadtools/kad) - Kademlia distributed hash table. :star:1
- [seedshot](https://github.com/twobucks/seedshot) - Temporary P2P screenshot sharing from your browser. :star:172
- [js-git](https://github.com/creationix/js-git) - JavaScript implementation of Git. :star:3323
- [skale](https://github.com/skale-me/skale-engine) - High performance distributed data processing engine. :star:253


### Command-line apps

- [np](https://github.com/sindresorhus/np) - Better `npm publish`. :star:3125
- [trash](https://github.com/sindresorhus/trash) - Safer alternative to `rm`. :star:1527
- [npm-name](https://github.com/sindresorhus/npm-name) - Check whether a package name is available on npm. :star:72
- [speed-test](https://github.com/sindresorhus/speed-test) - Test your internet connection speed and ping. :star:2947
- [emoj](https://github.com/sindresorhus/emoj) - Find relevant emoji from text on the command-line. :star:1479
- [pageres](https://github.com/sindresorhus/pageres) - Capture website screenshots. :star:8312
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. :star:167
- [vtop](https://github.com/MrRio/vtop) - More better top, with nice charts. :star:2724
- [empty-trash](https://github.com/sindresorhus/empty-trash) - Empty the trash. :star:84
- [is-up](https://github.com/sindresorhus/is-up) - Check whether a website is up or down. :star:275
- [is-online](https://github.com/sindresorhus/is-online) - Check if the internet connection is up. :star:386
- [public-ip](https://github.com/sindresorhus/public-ip) - Get your public IP address. :star:296
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - Copy & paste on the terminal. :star:132
- [ttystudio](https://github.com/chjj/ttystudio) - Record your terminal and compile it to a GIF or APNG without any external dependencies, bash scripts, gif concatenation, etc. :star:2944
- [XO](https://github.com/xojs/xo) - Enforce strict code style using the JavaScript happiness style. :star:3670
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style — One style to rule them all. :star:17594
- [ESLint](http://eslint.org) - The pluggable linting utility for JavaScript.
- [dev-time](https://github.com/samverschueren/dev-time-cli) - Get the current local time of a GitHub user. :star:150
- [David](https://github.com/alanshaw/david) - Tells you when your package npm dependencies are out of date. :star:806
- [http-server](https://github.com/indexzero/http-server) - Simple, zero-config command-line HTTP server.
- [Live Server](https://github.com/tapio/live-server) - Development HTTP-server with livereload capability.
- [bcat](https://github.com/kessler/node-bcat) - Pipe command output to web browsers.
- [normit](https://github.com/pawurb/normit) - Google Translate with speech synthesis in your terminal.
- [slap](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor.
- [jsinspect](https://github.com/danielstjules/jsinspect) - Detect copy-pasted and structurally similar code.
- [esformatter](https://github.com/millermedeiros/esformatter) - JavaScript code beautifier/formatter.
- [fkill](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform.
- [pjs](https://github.com/danielstjules/pjs) - Pipeable JavaScript. Quickly filter, map, and reduce from the terminal.
- [license-checker](https://github.com/davglass/license-checker) - Check licenses of your app's dependencies.
- [browser-run](https://github.com/juliangruber/browser-run) - Easily run code in a browser environment.
- [tmpin](https://github.com/sindresorhus/tmpin) - Adds stdin support to any CLI app that accepts file input.
- [modhelp](https://github.com/runvnc/modhelp) - Syntax-highlighted module READMEs in terminal with ANSI-friendly pager.
- [wifi-password](https://github.com/kevva/wifi-password-cli) - Get the current wifi password.
- [wallpaper](https://github.com/sindresorhus/wallpaper) - Change the desktop wallpaper.
- [brightness](https://github.com/kevva/brightness-cli) - Change the screen brightness.
- [torrent](https://github.com/maxogden/torrent) - Download torrents.
- [tfa](https://github.com/jasnell/tfa) - Two-factor authentication client.
- [rtail](https://github.com/kilianc/rtail) - Terminal output to the browser in seconds, using UNIX pipes.
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - Kill all Chrome tabs to improve performance, decrease battery usage, and save memory.
- [alex](https://github.com/wooorm/alex) - Catch insensitive, inconsiderate writing. :star:2241
- [vantage](https://github.com/dthree/vantage) - Distributed, realtime CLI for your live app. :star:3414
- [pen](https://github.com/noraesae/pen) - Live Markdown preview in the browser from your favorite editor. :star:212
- [subdownloader](https://github.com/beatfreaker/subdownloader) - Subtitle downloader for movies and TV series.
- [dark-mode](https://github.com/sindresorhus/dark-mode) - Toggle the macOS Dark Mode.
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP location finder.
- [Jsome](https://github.com/Javascipt/Jsome) - Pretty prints JSON with configurable colors and indentation.
- [itunes-remote](https://github.com/mischah/itunes-remote) - Interactively control iTunes.
- [text-meme](https://github.com/beatfreaker/text-meme-cli) - Generate a text meme.
- [mobicon](https://github.com/samverschueren/mobicon-cli) - Mobile app icon generator.
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - Mobile app splash screen generator.
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - Pretty git diff to HTML generator.
- [Cash](https://github.com/dthree/cash) - Cross-platform Unix shell commands in pure JavaScript.
- [vaca](https://github.com/sindresorhus/vaca) - Get a random ASCII 🐮.
- [gh-home](https://github.com/sindresorhus/gh-home) - Open the GitHub page of the repo in the current directory.
- [npm-home](https://github.com/sindresorhus/npm-home) - Open the npm page of a package.
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - Try out npm packages in the terminal. :star:1002
- [terminal-recorder](https://github.com/cortezcristian/terminal-recorder) - Record your terminal usage and export it to interactive HTML. :star:94
- [jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for source code. :star:722
- [atmo](https://github.com/Raathigesh/Atmo) - Server-side API mocking.
- [auto-install](https://github.com/siddharthkp/auto-install) - Auto installs dependencies as you code.
- [lessmd](https://github.com/linuxenko/lessmd) - Markdown in the terminal.
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - Find out which dependencies are slowing you down.
- [localtunnel](https://github.com/localtunnel/localtunnel) - Expose your localhost to the world.
- [svg-term-cli](https://github.com/marionebl/svg-term-cli) - Share terminal sessions via SVG.
- [gtop](https://github.com/aksakalli/gtop) - System monitoring dashboard for the terminal.
- [themer](https://github.com/mjswensen/themer) - Generate themes for your editor, terminal, wallpaper, Slack, and more.


### Functional programming

- [lodash](https://lodash.com) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections.
- [mori](http://swannodette.github.io/mori/) - Library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.
- [Ramda](http://ramdajs.com) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data.
- [Folktale](http://folktale.origamitower.com) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse.
- [underscore-contrib](http://documentcloud.github.io/underscore-contrib/) - The brass buckles on Underscore's utility belt.
- [Mout](http://moutjs.com) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead.
- [Bacon.js](http://baconjs.github.io) - Functional reactive programming.
- [RxJS](http://reactivex.io) - Functional reactive library for transforming, composing, and querying various kinds of data.
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases.
- [Kefir.js](https://github.com/rpominov/kefir) - Reactive library with focus on high performance and low memory usage.


### HTTP

- [got](https://github.com/sindresorhus/got) - Nicer interface to the built-in `http` module.
- [gh-got](https://github.com/sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API.

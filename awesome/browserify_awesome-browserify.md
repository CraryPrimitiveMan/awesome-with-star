# Information comes from [browserify/awesome-browserify](https://github.com/browserify/awesome-browserify)
<div align="center"><img src="browserify.png" alt="Browserify!"></div>

# Awesome Browserify [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> :crystal_ball: A curated list of awesome [Browserify](https://github.com/substack/node-browserify) resources, libraries, and tools.

Please help improve this list by [contributing](contributing.md)!

## Contents

- [About](#about)
- [Official Resources](#official-resources)
- [Community Resources](#community-resources)
- [Tutorials](#tutorials)
- [Articles](#articles)
- [Demos](#demos)
- [Videos](#videos)
- [Tools](#tools)
  - [Development Servers](#development-servers)
  - [Plugins](#plugins)
  - [Watchers](#watchers)
  - [CSS Bundlers](#css-bundlers)
  - [Transforms](#transforms)
  - [Node in the Browser](#node-in-the-browser)
  - [Production Tools](#production-tools)

## About

Browserify lets you `require('modules')` in the browser by bundling up all of your dependencies.

You can use a node-style `require()` to organize your browser code and load modules installed by npm. Browserify will recursively analyze all the `require()` calls in your app in order to build a bundle you can serve up to the browser in a single `<script>` tag.

## Official Resources

- [Docs](https://github.com/substack/node-browserify#usage) :star:11851
- [Handbook](https://github.com/substack/browserify-handbook) :star:4211
- [Repo](https://github.com/substack/node-browserify) :star:11851
- [Website](http://browserify.org/)

## Community Resources

- [IRC](http://webchat.freenode.net/?channels=browserify)
- [Twitter](http://twitter.com/browserify)
- [StackOverflow](http://stackoverflow.com/questions/tagged/browserify)

## Tutorials

- [Hello World with Browserify](http://browserify.org/#middle-section)
- [Browserify Adventure](https://github.com/workshopper/browserify-adventure) :star:143
- [A Gentle Browserify Walkthrough](https://ponyfoo.com/articles/a-gentle-browserify-walkthrough)
- [Browserify guide](http://zhaoda.net/2015/10/16/browserify-guide/) (Chinese)

## Articles

- [Introduction to Browserify](https://writingjavascript.org/posts/introduction-to-browserify)
- [Using npm on the client side](http://dontkry.com/posts/code/using-npm-on-the-client-side.html)
- [How Browserify Works](http://benclinkinbeard.com/posts/how-browserify-works/)
- [Gulp + Browserify: The Everything Post](https://www.viget.com/articles/gulp-browserify-starter-faq)
- [Browserify vs Component](http://www.forbeslindesay.co.uk/post/44144487088/browserify-vs-component)
- [Browserify for Webpack users](https://gist.github.com/substack/68f8d502be42d5cd4942)
- [Browserify vs. Webpack](https://mattdesl.svbtle.com/browserify-vs-webpack)

## Demos

- [Canvas Splitter](http://requirebin.com/?gist=maxogden/9576799) by [hughsk](http://github.com/hughsk)
- [Infinite 2D Cave Generator](http://requirebin.com/?gist=maxogden/9557700) by [hughsk](http://github.com/hughsk)
- [2D Velocity Control](http://requirebin.com/?gist=maxogden/9557776) by [sethvincent](http://github.com/sethvincent)

## Videos

- [James Halliday (substack) - LXJS 2013 - Modularidade para todos](https://www.youtube.com/watch?v=DCQNm6yiZh0)
- [Getting Started with Browserify](https://www.youtube.com/watch?v=CTAa8IcQh1U) by [shama](https://github.com/shama/)
- [Transform your Bundles with Browserify](https://www.youtube.com/watch?v=Uk2bgp8OLT8) by [shama](https://github.com/shama/)

## Tools

### Development Servers

- [budo](https://github.com/mattdesl/budo) - Dev server for rapid prototyping. :star:1701
- [beefy](https://github.com/chrisdickinson/beefy) - Local development server that aims to make using browserify fast and fun. :star:777
- [wzrd](https://github.com/maxogden/wzrd) - Super minimal browserify development server. :star:238

### Plugins

- [browserify-hmr](https://github.com/AgentME/browserify-hmr) - Hot Module Replacement plugin for Browserify. :star:362

### Watchers

- [watchify](https://github.com/substack/watchify) - Watch mode for browserify builds. :star:1684
- [persistify](https://github.com/royriojas/persistify) - Wrapper around `browserify` to make incremental builds. :star:76

### CSS bundlers

- [sheetify](https://github.com/stackcss/sheetify) - Modular CSS bundler for browserify. :star:392
- [parcelify](https://github.com/rotundasoftware/parcelify) - Add css to your npm modules consumed with browserify. :star:254
- [css-modulesify](https://github.com/css-modules/css-modulesify) - Browserify plugin to load CSS Modules. :star:394

### Transforms

- [babelify](https://github.com/babel/babelify) - Browserify transform for babel. :star:1513
- [aliasify](https://github.com/benbria/aliasify) - Remap require calls at build time. :star:192
- [brfs](https://github.com/substack/brfs) - `fs.readFileSync()` and `fs.readFile()` static asset browserify transform. :star:515

### Node in the Browser

- [crypto-browserify](https://github.com/crypto-browserify/crypto-browserify) - Port of node's `crypto` module to the browser. :star:293
- [stream-browserify](https://github.com/substack/stream-browserify) - The `stream` module from node core, for browsers! :star:52
- [buffer](https://github.com/feross/buffer) - The `buffer` module from node.js, for the browser. :star:529
- [requirebin](http://requirebin.com/) - Write browser JavaScript programs using modules from NPM.

### Production Tools

- [wzrd.in](https://wzrd.in/) - Browserify CDN. Browserify-as-a-Service!
- [bankai](https://github.com/yoshuawuyts/bankai) - DIY asset server. Serves HTML, CSS and JS as streams. :star:924

## Contributing

Contributions welcome! Please read the [contributing guidelines](contributing.md) before getting started.

## License

The [browserify logo](browserify.png) is by [substack](https://github.com/substack).

All other content is released to the public domain under [CC0-1.0](https://spdx.org/licenses/CC0-1.0.html).

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)


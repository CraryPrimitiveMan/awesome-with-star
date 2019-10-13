# Information comes from [passy/awesome-purescript](https://github.com/passy/awesome-purescript)
# awesome-purescript [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of delightful libraries, tools and other shiny things for PureScript.

## Build Tooling

- [pulp](https://github.com/bodil/pulp) :star:434
- [psvm-js](https://github.com/ThomasCrvsr/psvm-js) - PureScript Version Manager :star:29
- [purescript-psa](https://github.com/natefaubion/purescript-psa) - A pretty, flexible error/warning reporting frontend for `psc` :star:62
- [grunt-purescript](https://github.com/purescript-contrib/grunt-purescript) :star:10
- [gulp-purescript](https://github.com/purescript-contrib/gulp-purescript) :star:35
- [purs-loader](https://github.com/ethul/purs-loader) for webpack
- [psc-package](https://github.com/purescript/psc-package) - A package manager for PureScript based on package sets :star:218

## Preludes

- [purescript-prelude](https://github.com/purescript/purescript-prelude) - The standard Prelude. :star:89
- [purescript-batteries](https://github.com/tfausak/purescript-batteries) - A PureScript prelude with more features. :star:28

## UI Libraries

CSS:

- [purescript-css](https://github.com/slamdata/purescript-css) - A clean, type-safe library for describing, manipulating and rendering CSS. :star:75

React-based:

- [purescript-thermite](https://github.com/paf31/purescript-thermite) - A simple wrapper for ReactJS inspired by `react-blaze`. :star:334
- [purescript-react](https://github.com/purescript-contrib/purescript-react) - React bindings for PureScript :star:315
- [purescript-react-basic](https://github.com/lumihq/purescript-react-basic) - An opinionated set of bindings to the React library, optimizing for the most basic use cases. :star:164
- [purescript-react-basic-hooks](https://github.com/spicydonuts/purescript-react-basic-hooks) - An alternative way to define React components using React's "hooks" APIs. Compatible with `purescript-react-basic`. :star:64
- [purescript-pux](https://github.com/alexmingoia/purescript-pux) - Build type-safe web apps with PureScript. :star:547
- [purescript-spork](https://github.com/natefaubion/purescript-spork) - Elm-like for PureScript. :star:125
- [purescript-concur](https://github.com/ajnsit/purescript-concur) - Concur UI framework. React backend, but can use others. :star:147
- [purescript-presto](https://github.com/juspay/purescript-presto) - Write Apps like Mathematical Equations! :star:108
- [purescript-optic-ui](https://github.com/zrho/purescript-optic-ui) - Write single page web user interfaces declaratively and concisely with the help of lenses and traversals. :star:115
- [purescript-react-explor](https://github.com/paf31/purescript-react-explore) - Experiments with comonads for modelling React UIs. :star:79

Virtual-DOM based:

- [purescript-halogen](https://github.com/slamdata/purescript-halogen) - A declarative, type-safe UI library. :star:1006

Signals/Behaviors/FRP:

- [purescript-flare](https://github.com/sharkdp/purescript-flare) - Applicative-style reactive user interfaces built on top of purescript-signal. :star:260
- [purescript-turbine](https://github.com/funkia/purescript-turbine) - Purely functional frontend framework powered by FRP. :star:55
- [purescript-outwatch](https://github.com/OutWatch/purescript-outwatch) - A functional and reactive UI framework based on Rx and VirtualDom. :star:30
- [purescript-panda](https://github.com/i-am-tom/purescript-panda) - What would TEA look like if we had no VDOM? :star:62
- [purescript-specular](https://github.com/restaumatic/purescript-specular) - A Reflex-Dom inspired UI library for PureScript. :star:73
- [purescript-sdom](https://github.com/paf31/purescript-sdom) - An experiment in replacing the virtual DOM and avoiding diffing. :star:148
- [purescript-purview](https://github.com/paf31/purescript-purview) - A UI library based on the incremental lambda calculus. :star:90

## URL Routers

- [purescript-routing](https://github.com/slamdata/purescript-routing) - A clean, type-safe routing library for PureScript. :star:77
- [purescript-cofree-react-router](https://github.com/coot/purescript-cofree-react-router) - React-Router implemented in PureScript as Cofree Comonad for the Array functor. :star:18
- [purescript-trout](https://github.com/owickstrom/purescript-trout) - Type-level routing for PureScript. :star:31
- [purescript-boomboom](https://github.com/paluh/purescript-boomboom) - Never hard code your urls again. Boomboom them all! :star:5

## Components

- [purescript-halogen-select](https://github.com/citizennet/purescript-halogen-select) - Building blocks for common selection user interfaces like dropdowns, typeaheads, image pickers, and calendars. :star:49
- [purescript-halogen-echarts](https://github.com/slamdata/purescript-halogen-echarts) - A Halogen integration for the popular ECharts charting library :star:4
- [purescript-halogen-day-picker](https://github.com/rnons/purescript-halogen-day-picker) - A day picker for Halogen :star:12
- [purescript-halogen-menu](https://github.com/slamdata/purescript-halogen-menu) - Interactive menus in Halogen :star:7

## Asynchronicity and Parallelism

- [purescript-aff](https://github.com/slamdata/purescript-aff) - An asynchronous effect monad for PureScript. :star:227
- [purescript-affjax](https://github.com/slamdata/purescript-aff) - An asynchronous AJAX library built using Aff. :star:227
- [purescript-queue](https://github.com/athanclark/purescript-queue) - An asynchronous queue library for PureScript. :star:2
- [purescript-signal](https://github.com/bodil/purescript-signal) - An asynchronous signal library for PureScript, similar to Elm. :star:234
- [purescript-zeta](https://github.com/athanclark/purescript-zeta) - An alternative signal implementation in PureScript. :star:3

## Effect Management

- [purescript-eff](https://github.com/purescript/purescript-eff) - The Eff monad, for handling native side effects. :star:37
- [purescript-effect](https://github.com/purescript/purescript-effect) - The Effect monad, for handling native side effects in PureScript v0.12.x. :star:32

## Json Serialization

- [purescript-argonaut](https://github.com/purescript-contrib/purescript-argonaut) - Json encoding and decoding typeclasses. :star:38
- [purescript-simple-json](https://github.com/justinwoo/purescript-simple-json) - Json encoding and decoding through Generics. :star:102

## Binary Serialization

- [purescript-arraybuffer](https://github.com/jacereda/purescript-arraybuffer) - Bindings to the ArrayBuffer JavaScript type. :star:3
- [purescript-arraybuffer-class](https://github.com/athanclark/purescript-arraybuffer-class) - Typeclasses for ArrayBuffer encoding and decoding. :star:2

## Testing

- [purescript-test-unit](https://github.com/bodil/purescript-test-unit) - An asynchronous unit test runner for PureScript. :star:72
- [purescript-quickcheck](https://github.com/purescript/purescript-quickcheck) - An implementation of QuickCheck in PureScript. :star:68
- [purescript-quickcheck-laws](https://github.com/garyb/purescript-quickcheck-laws) - Law tests for core classes. :star:13
- [purescript-benchotron](https://github.com/hdgarrood/purescript-benchotron) - Straightforward benchmarking for PureScript/JavaScript. :star:21

## Learning Resources

- [Video - "PureScript (Maybe This Time We Get JavaScript Right)" by Bodil Stokke](https://www.youtube.com/watch?v=yIlDBPiMb0o)
- [Book - "PureScript by Example" by Phil Freeman](https://leanpub.com/purescript/read)
- [Book (ish) - Jordan's Purescript Reference](https://github.com/JordanMartinez/purescript-jordans-reference) :star:212
- [PureScript for Haskellers by Dennis Gosnell](http://www.arow.info/blog/posts/2015-12-17-purescript-intro.html)
- [Podcast - Functional Geekery Episode 22](https://www.functionalgeekery.com/episode-22-lambdaconf-2015-part-1/)
- [Podcast - JSJ 189](https://devchat.tv/js-jabber/189-jsj-purescript-with-john-a-de-goes-and-phil-freeman)
- [Course (egghead.io) - Functional Programming Concepts in Purescript](https://egghead.io/courses/functional-programming-concepts-in-purescript)

## Discovery

- [Module Linker](https://fiatjaf.alhur.es/module-linker/#/purescript) - Extension that lets you browse docs by just clicking on `import` declarations on GitHub.
- [Pursuit](https://pursuit.purescript.org/)

## Editor and IDE Plugins

See [Editor and tool support](https://github.com/purescript/purescript/wiki/Editor-and-tool-support)

## Community

- [`/r/purescript` subreddit](http://www.reddit.com/r/purescript)
- [`#purescript` on Freenode](http://webchat.freenode.net/?channels=purescript)
- [Stack Overflow `purescript` tag](http://stackoverflow.com/questions/tagged/purescript)
- [Google Group](https://groups.google.com/forum/#!forum/purescript)

## More Resources

- [Purescript Ecosystem](https://github.com/xgrommx/purescript-ecosystem) - Ranked list of popular libraries. :star:75

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Pascal Hartig](https://passy.me/) has waived all copyright and related or neighboring rights to this work.


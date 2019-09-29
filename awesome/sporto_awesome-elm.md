# Information comes from [sporto/awesome-elm](https://github.com/sporto/awesome-elm)

<div align="center">
    <img src="./assets/elm-logo.svg" height="180" width="180" />
    <h1>Awesome Elm</h1>
    <br />
    <br />
</div>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/sporto/awesome-elm.svg)](https://travis-ci.org/sporto/awesome-elm)

> A community driven list of useful Elm tutorials, libraries and software.

Inspired by the [awesome](#more-awesome) list thing. Feel free to <a href="https://github.com/sporto/awesome-elm/blob/master/CONTRIBUTION.md" target="_blank">improve</a> this list.


## Table of Contents
- [Awesome Elm](#awesome-elm)
    - [Examples](#examples)
    - [Learn](#learn)
    - [Articles](#articles)
    - [Videos](#videos)
    - [News](#news)
    - [Podcasts](#podcasts)
    - [Libraries](#libraries)
    - [Testing](#testing)
    - [Tools](#tools)
    - [Editor plugins](#editor-plugins)
    - [Package managers](#package-managers)
    - [Boilerplates](#boilerplates)
    - [Community and Support](#community-and-support)
    - [Conferences](#conferences)
    - [Inspired by Elm](#inspired-by-elm)
    - [Beyond the DOM](#beyond-the-dom)
    - [Who to follow](#who-to-follow)
- [More awesome](#more-awesome)
- <a href="https://github.com/sporto/awesome-elm/blob/master/CONTRIBUTION.md" target="_blank">Contribution Guidelines</a>


## Examples

*Some good apps written in Elm.*

* [Builtwithelm](http://builtwithelm.co/) - Web site built with elm with list of projects and apps built with Elm.
* [Elm SPA Example](http://rtfeldman.github.io/elm-spa-example/) - Full stack Elm app w/ CRUD operations, Auth, routing, pagination and more. [Code](https://github.com/rtfeldman/elm-spa-example) / [Article](https://dev.to/rtfeldman/tour-of-an-open-source-elm-spa)
* [Elm Example App](https://github.com/sporto/elm-example-app) - A small SPA example in Elm to learn the basics :star:439
* [TodoMVC](https://github.com/evancz/elm-todomvc) - Proper implementation of the TodoMVC app. :star:1120
* [TodoMVC with JSON API](https://github.com/andrewsuzuki/elm-todo-rest-api) - Bare-bones, modular, heavily-documented todo app with JSON API persistence. :star:103
* [TodoMVC/Firebase](https://github.com/ThomasWeiser/todomvc-elmfire) - Fork of TodoMVC demonstrating start-app, [The Elm Architecture](https://github.com/evancz/elm-architecture-tutorial) and Firebase as backend. :star:60
* [TodoMVC in Electron](https://github.com/nirgn975/Elmctron) -  Documented and tested implementation of the Elm TodoMVC app in Electron. :star:86
* [Gipher](https://github.com/matthieu-beteille/gipher) - A Tinder-like application for gifs built with elm and firebase! :star:226
* [Collection of examples](https://github.com/halfzebra/elm-examples) - A collection of examples with advanced techniques for real-world Elm apps. :star:197
* [\<elm-ement\>](https://github.com/ohanhi/elm-ement) – Minimal example of a custom element.
* [Elm Playground](http://elm-playground.maciejsmolinski.com/) - Tiny Elm projects implemented for the sake of learning by example.
* [Elm Architecture in Android](https://github.com/glung/elm-architecture-android) - An example Android application implemented with the Elm Architecture using the Kotlin programming language and Anko library. :star:58
* [Elm + Phoenix + Webpack](https://github.com/ronanyeah/elm-phoenix-example) - A minimal Elm + Phoenix setup, using webpack instead of Brunch. :star:52
* [Spotify Mapper](https://github.com/FidelisClayton/elm-spotify-mapper) - Elm app integrated with Spotify Api to search and explore new artists. :star:49
* [Pokelmon](https://github.com/brenopanzolini/pokelmon) - Elm project consuming PokéAPI. :star:15
* [JWT auth with Django + Elm](https://github.com/apirobot/django-elm-auth-with-jwt) - JSON Web Token (JWT) authentication using Django (backend) and Elm (frontend). :star:17
* [Bitcoin BR Chrome Extension](https://github.com/jouderianjr/bitcoin-br-chrome-extension) - Chrome extension built in Elm that shows the bitcoin value in all Brazilian exchanges. :star:2
* [Elmstagram](https://github.com/bkbooth/Elmstagram) - Basic UI Clone of Instagram / Articles - [Part 1](https://benkbooth.com/building-a-basic-ui-clone-of-instagram-using-elm-part-1/) [Part 2](https://benkbooth.com/post/building-a-basic-ui-clone-of-instagram-using-elm-part-2/) [Part 3](https://benkbooth.com/post/building-a-basic-ui-clone-of-instagram-using-elm-part-3/)
* [Kanban Board in Elm](https://github.com/huytd/kanelm) - A kanban board (trello-alike) built with Elm and HTML5 Drag & Drop API :star:256
* [Elm Playground](https://ccamel.github.io/playground-elm/index.html) - Pure SPA (with routing) exploring various aspects of Elm.
* [Elm Hacker News PWA](https://github.com/skrypte/elm-hn-pwa) - A progressive web app built with Elm version 0.18, using the official Hacker-News API
* [Elm Narrative Engine](https://github.com/jschomay/elm-narrative-engine) - A framework for building interactive fiction style stories in Elm. Detailed example [elmnarrativeengine.com](http://elmnarrativeengine.com) shows how to build a "chose your own adventure" game; perfect for beginners. **Elm v.0.19** :star:98

### Games

* [Elm Joust](https://github.com/stefankreitmayer/elm-joust) — a two-player fighting game written in Elm.
* [First Person Elm](https://github.com/jeffcole/first-person-elm) - A demo of first person navigation in 3D using WebGL and ports for browser APIs :star:11
* [Vessel](https://github.com/slawrence/vessel) - A "tunnel" game written in Elm! :star:108
* [Elm shooter](https://github.com/sporto/elm-shooter) - A side scrolling shotter :star:13
* [Sliding Puzzle](https://github.com/moroshko/sliding-puzzle) - Configurable sliding puzzle game written in Elm. :star:52
* [Elm Flatris](https://github.com/w0rm/elm-flatris) - A Flatris clone in Elm language v0.18. :star:397
* [Elm Hangman](https://github.com/puemos/elm-hangman) - The game of Hangman written in Elm. :star:19
* [Seeds](https://github.com/andrewMacmurray/seeds-game) is a "connect the dots" game written in **Elm v.0.19**. Play it online: [seedsgame.com](https://www.seedsgame.com)
* [404 Elm Street](https://github.com/zalando/elm-street-404) - A fun WebGL game built with Elm. :star:174

**[:top: back to top](#table-of-contents)**


## Learn

*Learn what this awesome thing is.*

* [Official tutorial](http://elm-lang.org/docs) — General information and in-depth guide with examples.
* [Elm in Action](https://www.manning.com/books/elm-in-action?a_aid=elm_in_action&a_bid=b15edc5c) — In-depth book for Elm beginners, from Manning Publications.
* [Architecture Tutorial](https://github.com/evancz/elm-architecture-tutorial) - How to create modular Elm code that scales nicely with your app. :star:4056
* [Exercism Elm Track](http://exercism.io/languages/elm) - Collection of Elm exercises.
* [Learn you an Elm](http://learnyouanelm.github.io/) - Elm tutorial with exhaustive examples and descriptions.
* [Beginning Elm](http://elmprogramming.com/) - A gentle introduction to the Elm programming language.
* [Elm Koans](https://github.com/robertjlooby/elm-koans) - Practice exercises for learning Elm. :star:218
* [Learn Elm in Y Minutes](https://learnxinyminutes.com/docs/elm/) - Syntax and features overview. The Elm page on [learnxinyminutes.com](https://learnxinyminutes.com)
* [Elm Maybe - Dealing with null/Nothing](http://rundis.github.io/blog/2016/elm_maybe.html) - Working with the Maybe type, with nicely commented code examples.
* [Programming Elm](https://pragprog.com/book/jfelm/programming-elm) - Thorough book from The Pragmatic Programmers that covers basics and advanced concepts.
* [Elm cheat sheet](https://github.com/izdi/elm-cheat-sheet) - Syntax and features overview. :star:903
* [Ninety-nine Problems, Solved in Elm](https://johncrane.gitbooks.io/ninety-nine-elm-problems/content/) - Adaptations for Elm from Ninety-Nine Haskell Problems.
* [Elm Tutorials on Codementor](https://www.codementor.io/elm/tutorial) - Two tutorials on building web apps with Elm.
* [Elm programming language](https://en.wikibooks.org/wiki/Elm_programming_language) - a brief overview of Elm as a programming language.
* [Elm: A Beginners' Guide to Elm and Data](https://www.sitepoint.com/premium/courses/elm-a-beginners-guide-to-elm-and-data-2940) - Beginners' course to Elm and Data
* [Practical Elm for a Busy Developer](https://korban.net/elm/book) - A non-beginner book about the practical aspects of developing Elm applications.
* [Haskell to Elm](https://github.com/eeue56/haskell-to-elm) - Collection of examples on places where Elm is different to Haskell, targeted at Elm beginners coming from Haskell backgrounds. :star:65
* [A nice app on Elm street](https://madewithlove.be/using-elm-with-react-a-nice-app-on-elm-street) - An introduction to Elm

### Outdated Tutorials and books (Elm 0.18 or earlier)

* [Elm: Building Reactive Web Apps](https://pragmaticstudio.com/elm) - Learn how to build reactive web apps using Elm.
* [Writing native](https://github.com/NoRedInk/take-home/wiki/Writing-Native) - Learn how to create native JavaScript modules for Elm. :star:364
* [Elm: Functional frontend development](https://dennisreimann.de/articles/elm.html) - Series of articles about fundamentals and advanced topics.
* [Elm Tutorial](https://sporto.gitbooks.io/elm-tutorial/content/) - A tutorial on developing single page web applications with Elm.
* [A Concise Introduction to Elm](https://www.cis.upenn.edu/~matuszek/Concise%20Guides/Concise%20Elm.html) - High overview of language features.
* [Elm Seeds](https://elmseeds.thaterikperson.com/) - Short screencasts to teach you the Elm programming language from Erik Person.
* [Elm For Beginners - Video Course](http://courses.knowthen.com/courses/elm-for-beginners) - Build your first Elm Web App.
* [Single-Page Web Apps in Elm](https://www.linkedin.com/pulse/single-page-web-apps-elm-part-one-getting-started-new-kevin-greene) - Five parts tutorial on Elm.
* [Elm FAQ](http://faq.elm-community.org/) - Elm FAQ from [Elm Community](http://elm-community.org/).
* [Elm Tutorial by Auth0](https://auth0.com/blog/creating-your-first-elm-app-part-1/) - A tutorial on building an app in Elm from authentication to calling an API.


**[:top: back to top](#table-of-contents)**


## Articles

*Read the essentials. Check the official Elm blog: [elm-lang.org/blog](http://elm-lang.org/blog)*

### Why Elm?

* [Side-effects of Elm in production](http://nonullpointers.com/posts/2019-05-28-side-effects-of-elm-in-production.html?utm_campaign=Elm%20Weekly&utm_medium=email&utm_source=Revue%20newsletter) - An experience report from Bellroy
* [How Elm Made Our Work Better](http://futurice.com/blog/elm-in-the-real-world) - How a team built a business-critical web app for a customer using Elm.
* [FP with games in Elm](https://github.com/Dobiasd/articles/blob/master/switching_from_imperative_to_functional_programming_with_games_in_Elm.md) - Switching from imperative to functional programming with games in Elm. :star:1274
* [Blazing Fast HTML](http://elm-lang.org/blog/blazing-fast-html) - Virtual DOM in Elm.
* [Elm from a Business Perspective](http://www.gizra.com/content/elm-business-perspective/) - This article discusses topics about Elm from a business perspective
* [Move fast and don’t break things. Running a startup on Elm](https://medium.com/the-ahead-story/move-fast-and-dont-break-things-running-a-startup-on-elm-b5491082fe8b#.c534m1e1t) - Some thoughts on Elm development by a Swedish startup.

### Miscellaneous articles

* [Learning FP the hard way](https://gist.github.com/ohanhi/0d3d83cf3f0d7bbea9db) - Experiences on the Elm language.
* [Blog of Brian Hicks](https://www.brianthicks.com)  - A blog with various topics about Elm.
* [Introduction to The Elm Architecture and How to Build our First Application](https://css-tricks.com/introduction-elm-architecture-build-first-application/) - An article describing the Elm architecture and how to build a simple application
* [Functional Programming for Web Frontend by Jan Luxemburk](https://drive.google.com/file/d/0BzfJvCA4sXjQNjJwd2twQUFOU0k/view) - A Bachelor’s thesis about functional programming for frontend development with the focus on Elm.

### Outdated articles (Not relevant for current Elm architecture)

* [Elm for Web Developers](https://github.com/eeue56/elm-for-web-developers) - A collection of notes for web developers looking into moving to Elm. :star:61
* [Elm & Components](https://medium.com/p/elm-components-3d9c00c6c612) - A blog post describing a possible approach to reducing TEA boilerplate. Useful for component libraries and anyone interested in seeing the amazing things you can do with function types.
* [Composing Features and Behaviours in the Elm Architecture](https://github.com/foxdonut/adventures-reactive-web-dev/tree/master/client-elm#composing-features-and-behaviours-in-the-elm-architecture) - An article describing how to organize code that follows the Elm architecture into independent features, how to communicate between features, and how to group some of these features together to assemble larger features. :star:152
* [Getting Started with Elm](https://medium.com/@diamondgfx/getting-started-with-elm-11d7a53b1a78) - Series of Elm education tutorials.
* [Elm & Guarantees](https://medium.com/@debois/elm-guarantees-92a66679f7bd) - a realistic look at where Elm is and isn’t superior to other options.

**[:top: back to top](#table-of-contents)**


## Videos

*Watch great talks about Elm*

### Playlists

* [Elm Conf 2019](https://www.youtube.com/playlist?list=PLglJM3BYAMPGsAM4QTka7FwJ0xLPS0mkN) - Sep 2019
* [Elm in the Spring 2019](https://www.youtube.com/channel/UC_wKoNegfKbmVIPg7YYKLWQ) - Jun 2019
* [Oslo Elm Day 2019](https://www.youtube.com/playlist?list=PLcAzxXzXQlPbalOfueVbHCRSo26ksIXiF) - Feb 2019
* [Elm Conf 2018](https://www.youtube.com/watch?v=28OdemxhfbU&list=PLglJM3BYAMPHuB7zrYkH2Kin2vQOkr2xW) - All talks from elm-conf 2018
* [Elm Europe 2018](https://www.youtube.com/watch?v=uGlzRt-FYto&list=PL-cYi7I913S-VgTSUKWhrUkReM_vMNQxG) - A playlist of all talks from Elm Europe 2018
* [Elm Conf 2017](https://www.youtube.com/playlist?list=PLglJM3BYAMPFTT61A0Axo_8n0s9n9CixA) - All talks from elm-conf 2017
* [Elm Europe 2017](https://www.youtube.com/watch?v=XpDsk374LDE&list=PL-cYi7I913S8cGyZWdN6YVZ028iS9BfpM) - A playlist of all talks from Elm Europe 2017
* [Elm Conf 2016](https://www.youtube.com/channel/UCOpGiN9AkczVjlpGDaBwQrQ) - All talks from elm-conf 2016

### Miscellaneous videos

* [Dillon Kearns: Types Without Borders | 2018](https://www.youtube.com/watch?v=memIRXFSNkU) - elm-conf 2018 talk about end-to-end type-safety using external schemas like GraphQL.
* [Jamison Dance: Rethinking All Practices - Building Applications in Elm | 2016](https://www.youtube.com/watch?v=txxKx_I39a8) - A talk given at React.js Conf 2016 about what Elm has to teach the JavaScript world and why JS devs should consider trying it.
* [Richard Feldman: Introduction to Elm | 2016](https://www.youtube.com/watch?v=3_M2G9U51GA) - A talk that gives a broad, high-level introduction to Elm.
* [Amitai Burstein: Frontend with Guarantees | 2016](https://www.youtube.com/watch?v=FgaoOgJ5CAU) - A talk from You Gotta Love Frontend 2016
* [Jessica Kerr: Adventures in Elm | 2016](https://www.youtube.com/watch?v=cgXhMc8M4X4) - A talk about the combination of functional programming with Elm at GOTO Chicago 2016.
* [Aaron VonderHaar: Codevember | 2016 ](https://www.youtube.com/playlist?list=PLDA4wlOlLJvXAEsJDje4hdLazsihZiQNf) + [ElmLive](https://www.youtube.com/playlist?list=PLDA4wlOlLJvWSYo3KiEa4q4ETkXpTaKlw) - elm live video examples.
* [Richard Feldman: Making impossible states impossible | 2016](https://www.youtube.com/watch?v=IcgmSRJHu_8) - A talk about modelling data structures in Elm in a way that makes invalid states unrepresentable
* [Richard Feldman: Effects as Data | 2015](https://www.youtube.com/watch?v=6EdXaWfoslc) - A talk about how Elm manages side effects.
* [Richard Feldman: Make the Back-End Team Jealous: Elm in Production | 2015](http://www.youtube.com/watch?v=FV0DXNB94NE) - A talk about Elm and initial steps to use it in production.
* [Evan Czaplicki: Let's be mainstream! User focused design in Elm | 2015](https://www.youtube.com/watch?v=oYk8CKH7OhE) - A talk from the father of Elm about the philosophy behind the language.

### Video tutorials

* [Egghead.io: Elm videos](https://egghead.io/technologies/elm) - Egghead's Elm video training, many of which are free.
* [jadams's training videos](https://www.dailydrip.com/topics/elm) - A neat series of bite-sized Elm training videos, many of which are free.
* [Elm Basics](https://www.youtube.com/watch?v=g48K6ABfRzA) - Walk through all the syntax and basic ideas in Elm as a general programming language.
* [Greg Ziegan: Elm live coding videos ](https://www.youtube.com/channel/UCJt-EkypIn-HoxNhoHqXmIA) - Live coding videos on youtube.

**[:top: back to top](#table-of-contents)**

## News

* [Official Elm News](https://elm-lang.org/news) - Official Elm blog
* [Elm Weekly](http://www.elmweekly.nl/) - A weekly newsletter about Elm
* [Elm News](https://elm-news.com/) - All Elm news in one place
* [Elm Greenwood](https://elm-greenwood.com/) - Elm packages releases
* [Elm Reddit](https://www.reddit.com/r/elm/) - Elm news in Reddit

## Podcasts

*Listen to podcasts about Elm*

* [Elm Town](https://elmtown.github.io/) - A podcast about the people in the Elm community.

### Individual Podcast episodes

* [Elixir Fountain Evan Czaplicki 2016-07-11](https://soundcloud.com/elixirfountain/elixir-fountain-evan-czaplicki-2016-07-11) - Elm with Evan Czaplicki.
* [Functional Geekery 33](https://www.functionalgeekery.com/functional-geekery-episode-33-richard-feldman-and-tessa-kelly/) - Richard Feldman and Tessa Kelly.
* [The Changelog 218](https://changelog.com/218/) - Elm with Evan Czaplicki and Richard Feldman
* [The Changelog 191](https://changelog.com/191/) - Elm and Functional Programming with Richard Feldman.
* [Software Engineering Daily](http://softwareengineeringdaily.com/2015/11/03/elm-with-richard-feldman-and-srinivas-rao/) - Elm with Richard Feldman and Srinivas Rao.
* [JavaScript Jabber 175](https://devchat.tv/js-jabber/175-jsj-elm-with-evan-czaplicki-and-richard-feldman) - Elm with Evan Czaplicki and Richard Feldman.
* [Ruby Rogues 212](https://devchat.tv/ruby-rogues/212-rr-elm-with-richard-feldman-and-evan-czaplicki) - Elm with Richard Feldman and Evan Czaplicki.
* [The Web Platform Podcast 15](http://thewebplatform.libsyn.com/functional-programming-with-elm-clojurescript-om-and-react) - Functional Programming with Elm, ClojureScript, Om, and React.
* [The Web Platform Podcast 76](http://thewebplatformpodcast.com/76-the-elm-programming-language) - The Elm Programming Language.
* [The Web Platform Podcast 108](http://thewebplatformpodcast.com/108-elm-revisited) - Elm Revisited.
* [Full Stack Radio 44](http://www.fullstackradio.com/44) - What the heck is Elm? In this episode, Joel Clermont talks about Elm and functional programming.
* [InfoQ Podcast 2017-04-27](https://www.infoq.com/podcasts/richard-feldman) - Richard Feldman discusses how Elm compares to React.js

**[:top: back to top](#table-of-contents)**

## Libraries

You can find hundreds of high quality packages at:

* [Elm packages](https://package.elm-lang.org/) - The official registry
* [Elm Package Catalog](https://korban.net/elm/catalog) - Find packages in a catalog organized into categories. 
* [Elm finder](https://www.elmfinder.org/) - A directory of reusable libraries and tools for your Elm projects
* [Elm Search](http://klaftertief.github.io/elm-search/) - Search Elm documentation for operators, function signatures, etc.

Here are some notable ones:

* [core](https://github.com/elm/core) - Elm Core Libraries. :star:2264
* [html](https://github.com/elm/html) - Use HTML in Elm, based on the idea of a "virtual DOM". :star:320
* [elm-test](https://github.com/elm-explorations/test) - A unit testing framework for Elm. :star:131
* [http](https://github.com/elm/http) - Make HTTP requests in Elm. :star:122
* [elm-ui](https://github.com/mdgriffith/elm-ui) - UI Library in Elm. :star:542
* [elm-css](https://github.com/rtfeldman/elm-css) - CSS in Elm. :star:984
* [dillonkearns/elm-graphql](https://github.com/dillonkearns/elm-graphql) - Generate code to build guaranteed correct, type-safe API requests to your GraphQL API. :star:423

**[:top: back to top](#table-of-contents)**

## Testing

Tools and libraries to test your Elm applications

* [Elm test](https://github.com/elm-explorations/test) - Unit and fuzz tests :star:131
* [Elm Program test](https://github.com/avh4/elm-program-test/tree/3.0.0) - Test complete Elm programs :star:17

**[:top: back to top](#table-of-contents)**


## Tools

*Useful tools related to Elm.*

* [Elm Live](https://elm-live.com/) - A flexible dev server for Elm. Live reload included!
* [Elm Format](https://github.com/avh4/elm-format) - Automatic Elm code formatter adhering to [Elm Style Guide](http://elm-lang.org/docs/style-guide). :star:1135
* [Elm Oracle](https://github.com/ElmCast/elm-oracle) - Query for information about values in elm source files. Used by most editor plugins. :star:149
* [Elm Analyse](https://github.com/stil4m/elm-analyse) - Linter for the Elm programming language. :star:372
* [type-o-rama](https://github.com/stereobooster/type-o-rama) - JS type systems interportability. :star:177
* [Dependabot](https://dependabot.com) - Automatic update PRs for your elm-package.json.
* [Elm Doc Preview](https://github.com/dmy/elm-doc-preview) - Elm offline documentation previewer. :star:80
* [Elmstatic](https://korban.net/elm/elmstatic) - Elm-based static site generator.
* [elm-pages](http://elm-pages.com) - Static site generator that prerenders HTML and hydrates into an Elm client-side app ([here is a brief comparison with elmstatic](https://elm-pages.com/blog/introducing-elm-pages#comparing-elm-pages-and-elmstatic)).

### Code Generators

* [HTML to Elm](http://mbylstra.github.io/html-to-elm/) - Convert HTML to Elm Html. Useful when porting an app to Elm.
* [OpenApi Generator](https://github.com/OpenAPITools/openapi-generator) - Generate OpenApi types for Elm. :star:3280
* [Elm Typescript Interop](https://github.com/dillonkearns/elm-typescript-interop) - Generate Typescript definitions from Elm. :star:115
* [Quicktype](https://github.com/quicktype/quicktype) - Generate JSON decoders and encoders from JSON :star:3434
* [JSON Schema to Elm](https://github.com/dragonwasrobot/json-schema-to-elm) - Generates Elm types, JSON decoders, JSON encoders and fuzz tests from JSON schema specifications :star:49
* [Elm Bridge](https://github.com/agrafix/elm-bridge) - Generate Elm types from Haskell :star:83

### Run Elm

* [Ellie](https://ellie-app.com/) - The Elm Live Editor
* [Online REPL](http://elmrepl.cuberoot.in) - The ELM Online REPL
* [run-elm](https://github.com/jfairbank/run-elm) — Run Elm code from the command line
* [elm-instant](https://atom.io/packages/elm-instant) - atom package to try your elm code from the editor. Provides a visual REPL and a preview pane.

### Compile and bundle

* [elm-compiler](https://github.com/elm/compiler) - Compiler for the Elm programming language. :star:5417
* [elm-webpack-loader](https://github.com/elm-community/elm-webpack-loader) - Webpack loader for the Elm programming language. :star:490
* [Parcel](https://parceljs.org/elm.html) - Bundle Elm using Parcel
* [grunt-elm](https://github.com/rtfeldman/grunt-elm) - Grunt plugin that compiles Elm files to JavaScript. :star:17

**[:top: back to top](#table-of-contents)**


## Editor plugins

*Tools to support Elm in code editors.*

### Atom

* [atom-linter-elm-make](https://atom.io/packages/linter-elm-make) - Elm code linter for the Atom editor.
* [atom-elm-snippets](https://github.com/chiefGui/atom-elm-snippets) - Elm snippets for Atom. :star:6
* [atom-language-elm](https://atom.io/packages/language-elm) - Syntax highlighting and autocompletion for the Atom editor.
* [elmjutsu](https://atom.io/packages/elmjutsu) - Autocompletion, go to definition, find usages, rename symbol, etc. for the Atom editor.
* [atom-elm-navigator](https://atom.io/packages/elm-navigator) - A side panel that helps to navigate to any function, type definition or port in your project.

### Emacs

* [emacs-elm-mode](https://github.com/jcollard/elm-mode) - Syntax highlighting, Elm REPL, Elm make and Elm format integration for the Emacs editor. :star:317

### IntelliJ

* [elm-plugin](https://github.com/klazuka/intellij-elm) - Elm plugin for IntelliJ IDEA. :star:224

### Sublime Text

* [Elm Syntax Highlighting](https://packagecontrol.io/packages/Elm%20Syntax%20Highlighting) - Syntax Highlighting for Elm in Sublime Text.
* [Elm Language Server](https://github.com/elm-tooling/elm-language-server#sublime) - Language server implementation for Elm :star:142

### Vim/Neovim

* [theJian/elm.vim](https://github.com/theJian/elm.vim) - Elm syntax highlighting. Use with [ale or Neoformat for Neovim](https://github.com/avh4/elm-format/issues/610) since ElmCast/elm-vim does not support Elm 0.19.
* [ElmCast/elm-vim](https://github.com/ElmCast/elm-vim) - Elm 0.18 mode for Vim/Neovim. :star:528
* [vim-elm-help](https://github.com/hoelzro/vim-elm-help) - Offline Elm documentation access in your editor. :star:8
* [emmet-vim](https://github.com/mattn/emmet-vim) - Markup expansion with elm support. :star:4814

### Visual Studio Code

* [ElmLS](https://marketplace.visualstudio.com/items?itemName=Elmtooling.elm-ls-vscode) - Elm Language Server integration
* [Elm Visual Studio Code Support](https://marketplace.visualstudio.com/items?itemName=sbrink.elm) - Syntax highlighting, Snippets, Function information, REPL, Reactor support (Webserver/Debugger) - Starting/Stopping
* [Elmmet: Emmet for Elm (Visual Studio Code)](https://marketplace.visualstudio.com/items?itemName=necinc.elmmet) - Emmetio abbreviation expander into composition of Elm function with elm-format'er inside.
* [HTML to Elm for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=Rubymaniac.vscode-html-to-elm) - VSCode plugin to convert HTML to Elm


### Other

* [elm-light-table](https://github.com/rundis/elm-light) - Syntax highlighting, REPL, autocompletion, package management and much more for Light Table. :star:132

**[:top: back to top](#table-of-contents)**


## Package managers

*Place to share Elm libraries.*

* [elm-package](https://github.com/elm-lang/elm-package) - Command line tool to share Elm libraries. :star:219

**[:top: back to top](#table-of-contents)**


## Boilerplates

*Good starting point for a new Elm project.*

* [create-elm-app](https://github.com/halfzebra/create-elm-app) - Create Elm apps with no build configuration. :star:1327
* [elm-live](https://github.com/wking-io/elm-live) - A flexible dev server for Elm. Live reload included. :star:750
* [elm-webpack-4-starter](https://github.com/romariolopezc/elm-webpack-4-starter) - Elm webpack 4 starter template. :star:102
* [example-elm-hot-webpack](https://github.com/klazuka/example-elm-hot-webpack) - Example showing hot module reloading for Elm 0.19 and Webpack :star:8
* [Elm Batteries](https://github.com/cedricss/elm-batteries) - A project template and generator for Elm, Parcel, Cypress and Netlify   :star:68

### Outdated Boilerplates

* [elm-webpack-starter](https://github.com/moarwick/elm-webpack-starter) - A simple Webpack setup for writing Elm apps. :star:885
* [elm-app-boilerplate](https://github.com/gkubisa/elm-app-boilerplate) - A fully-featured base project for Elm apps: Webpack, HMR, ES6, JS and Elm tests, Semantic UI, sample code and more. :star:119
* [elmkit](https://github.com/khusnetdinov/elmkit) - A lightweight Brunch based setup for web app. Includes Brunch, Hot Module Replacement, Elm, Scss, Elm tests. :star:50
* [elm-boilerplate](https://github.com/guillaumearm/elm-boilerplate) - A simple Makefile able to create Elm app. :star:3
* [elm-init](https://github.com/JustusAdam/elm-init) - Interactive setup for new Elm projects. :star:9
* [elm-new](https://github.com/simonewebdesign/elm-new) - Generate initial project scaffolding based on a template. :star:78
* [elm-webpack-starter-kid](https://github.com/FranzSkuffka/elm-webpack-starter-kid) - A very very basic elm + webpack 4 template. :star:5

**[:top: back to top](#table-of-contents)**


## Community and Support

*Where to find help.*

* [Discourse](https://discourse.elm-lang.org/) - Elm Discourse instance (official forum).
* [Reddit](https://www.reddit.com/r/elm) - Elm board on reddit.
* [IRC](http://webchat.freenode.net/?channels=elm) - Ask questions on elm freenode.
* [Slack](http://elmlang.herokuapp.com/) - Elm slack community.

**[:top: back to top](#table-of-contents)**

## Conferences

* [Elm Conf](https://2019.elm-conf.com/)
* [Elm Europe](https://2019.elmeurope.org/)
* [Elm in the spring](https://www.elminthespring.org/)
* [Oslo Elm day](https://osloelmday.no/)

**[:top: back to top](#table-of-contents)**

## Inspired by Elm

*Projects inspired by Elm*

* [Elchemy](https://github.com/wende/elchemy) - Write Elixir code using statically-typed Elm-like syntax :star:929
* [Elmish](https://github.com/elmish/elmish) - Elm-like abstractions for F# apps :star:443
* [Fabulous](https://github.com/fsprojects/Fabulous) - F# Functional App Development, using declarative dynamic UI :star:456
* [Bolero](https://fsbolero.io/) - F# in WebAssembly using Elmish
* [SwiftUI](https://developer.apple.com/xcode/swiftui/)
* [Redux](https://redux.js.org/introduction/prior-art) - A predictable state container for JavaScript apps.
* [Bucklescript-TEA](https://github.com/OvermindDL1/bucklescript-tea) The Elm Architecture based on OCaml / Reason and [Bucklescript](https://bucklescript.github.io/)

**[:top: back to top](#table-of-contents)**


## Beyond the DOM

*At the moment Elm is heavily targeted towards the browser, here are some experiments on using Elm outside the DOM:*

* [iOS](https://github.com/pzp1997/elm-ios) A POC for using Elm 0.18 for native iOS Applications
* [elmish-wasm](https://github.com/Chadtech/elmish-wasm) A POC for compiling elm to Web Assembly
* [elm-serverless](https://github.com/ktonon/elm-serverless) Run Elm 0.18 on Cloud Functions using the Serverless Frameworks

**[:top: back to top](#table-of-contents)**


## Who to follow

*Follow for fresh updates for free. Use [#elmlang](https://twitter.com/search?q=%23elmlang) or [#elm](https://twitter.com/search?q=%23elm) hashtag.*

<a href="https://twitter.com/elmlang" target="_blank"><img src="https://pbs.twimg.com/profile_images/443551527307718656/cZHhsF-c.png" width="100" /></a> | <a href="https://twitter.com/czaplic" target="_blank"><img src="https://pbs.twimg.com/profile_images/443794371586977792/NxKUNpOQ.jpeg" width="100" /></a> | <a href="https://twitter.com/rtfeldman" target="_blank"><img src="https://pbs.twimg.com/profile_images/635812303342956545/Fo4RyEgH.jpg" width="100" /></a> | <a href="https://twitter.com/elmweekly" target="_blank"><img src="https://s3.amazonaws.com/revue/profiles/images/000/046/579/thumb/elm_weekly_logo.png" width="100" /></a>
--- | --- | --- | ---
[Official Elm](https://twitter.com/elmlang) | [Evan Czaplicki](https://twitter.com/czaplic) | [Richard Feldman](https://twitter.com/rtfeldman) | [Elm Weekly](https://twitter.com/elmweekly)

**[:top: back to top](#table-of-contents)**


## More awesome

*Discover other amazingly awesome lists.*

Awesome Elm is just a part of awesome thing, get more here:

- <a href="https://github.com/sindresorhus/awesome" target="_blank">awesome</a> by [**@sindresorhus**](https://github.com/sindresorhus)
- <a href="https://github.com/bayandin/awesome-awesomeness" target="_blank">awesome-awesomeness</a> by [**@bayandin**](https://github.com/bayandin)


**[:top: back to top](#table-of-contents)**


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)



# Information comes from [BubuAnabelas/awesome-markdown](https://github.com/BubuAnabelas/awesome-markdown)
# Awesome Markdown [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<img src="https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg" align="right" width="208">

> A curated list of delightful Markdown stuff.

Markdown is a markup language created by John Gruber in collaboration with Aaron Swartz. It was designed to be easily converted to HTML and has been extended into different types of implementations.

<!--lint disable no-emphasis-as-heading-->

_Please read the [contribution guidelines](contributing.md) before contributing._

<!--lint enable no-emphasis-as-heading-->

:gem: means **really _awesome/useful_**.<br />
![Globe][globe] means that **it's _webapp/webservice_**.<br />
![Android OS][android-os] means that **runs on _Android_**.<br />
![iOS Logo][ios-logo] means that **runs on _iOS_**.<br />
![Apple][apple] means that **runs on _macOS_**.<br />
![Linux][linux] means that **runs on _Linux_**.<br />
![Windows 8][windows8] means that **runs on _Windows_**.<br />

<!--lint disable no-paragraph-content-indent-->

<!--lint disable alphabetize-lists-->

## Contents

- [CMS / Blogs](#cms--blogs)
- [Libraries](#libraries)
	- [C](#c)
	- [Java](#java)
	- [JavaScript](#javascript)
	- [Perl](#perl)
	- [PHP](#php)
	- [Python](#python)
	- [Ruby](#ruby)
- [Tools](#tools)
	- [Converters](#converters)
	- [Editors](#editors)
	- [Linters](#linters)
	- [Miscellaneous](#miscellaneous)
    - [Presentations](#presentations)
- [Services](#services)
- [Resources](#resources)
	- [Documentation](#documentation)
	- [Tutorials](#tutorials)

---

<!--lint enable alphabetize-lists-->

<!--lint enable no-paragraph-content-indent-->

## CMS / Blogs

> CMS or Blogs which support Markdown by default.

- [Ghost](https://blog.ghost.org/markdown/) - Publishing platform for professional bloggers.
- [Grav](https://getgrav.org/) - Modern Flat-File CMS.
- [Hugo](https://gohugo.io/) - Fast & Modern Static Website Engine.
- [Jekyll](https://jekyllrb.com/) - Transform your plain text into static websites and blogs.
- [Svbtle](https://svbtle.com/) - Blogging platform designed to help you think.

## Libraries

> Libraries for rendering Markdown documents.

### C

- [Hoedown](https://github.com/hoedown/hoedown) - Standards compliant, fast, secure Markdown processing library in C (Sundown fork). :star:736
- [peg-markdown](https://github.com/jgm/peg-markdown) - An implementation of Markdown in C, using a PEG grammar. :star:563
- [Sundown](https://github.com/vmg/sundown) - Standards compliant, fast, secure Markdown processing library in C. :star:1591

### Java

- [commonmark-java](https://github.com/atlassian/commonmark-java) - Java implementation of CommonMark, a specification of the Markdown format. :star:674
- [flexmark-java](https://github.com/vsch/flexmark-java) - Java Implementation of Markdown parser with source level AST. :star:470
- [pegdown](https://github.com/sirthias/pegdown) - A pure-Java Markdown processor based on a parboiled PEG parser supporting a number of extensions. :star:1196

### JavaScript

- [markdown-it](https://github.com/markdown-it/markdown-it) - Markdown parser, done right. 100% CommonMark support, extensions, syntax plugins & high speed. :star:4830
- [markdown-js](https://github.com/evilstreak/markdown-js) - Yet another Markdown parser, this time for JavaScript. :star:6504
- [marked](https://github.com/markedjs/marked) - Full-featured Markdown parser and compiler, written in JavaScript. Built for speed. :star:15463
- [Showdown](https://github.com/showdownjs/showdown) - Showdown is a JavaScript Markdown to HTML converter, based on the original works by John Gruber. :star:6232
- [Snarkdown](https://github.com/developit/snarkdown) - Snarkdown is a dead simple 1kb Markdown parser. :star:814

### Perl

- [Markdown.pl](https://daringfireball.net/projects/downloads/Markdown_1.0.1.zip) :gem: _John Gruber's original Markdown library._

### PHP

- [parsedown](https://github.com/erusev/parsedown) - Better Markdown Parser in PHP. :star:6353
- [php-markdown](https://github.com/michelf/php-markdown) - Parser for Markdown and Markdown Extra derived from the original Markdown.pl by John Gruber. :star:2628

### Python

- [markdown2](https://github.com/trentm/python-markdown2) - Fast and complete implementation of Markdown in Python. :star:1491
- [Mistune](https://github.com/lepture/mistune) - The fastest Markdown parser in pure Python with renderer feature. :star:1144
- [Python-Markdown](https://github.com/Python-Markdown/markdown) - Python implementation of John Gruber's Markdown. :star:1269

### Ruby

- [kramdown](https://github.com/gettalong/kramdown) - kramdown is a fast, pure Ruby Markdown superset converter, using a strict syntax definition and supporting several common extensions. :star:1180
- [Redcarpet](https://github.com/vmg/redcarpet) - Redcarpet is a Ruby library for Markdown processing that smells like butterflies and popcorn. :star:4154

## Tools

### Converters

> Convert Markdown to other formats and vice versa.

- [csvtomd](https://github.com/mplewis/csvtomd) - Convert your CSV files into Markdown tables. ![Apple][apple] ![Linux][linux] ![Windows 8][windows8] :star:416
- [HTML To Markdown for PHP](https://github.com/thephpleague/html-to-markdown) - Convert HTML to Markdown with PHP. :star:709
- [markdown-pdf](https://github.com/alanshaw/markdown-pdf) - Markdown to PDF converter. :star:1221
- [Markdown to PDF](http://www.markdowntopdf.com/) - Simple and useful website for converting Markdown to PDF. ![Globe][globe]
- [Pandoc](http://pandoc.org/) - Universal document converter. ![Apple][apple] ![Linux][linux] ![Windows 8][windows8]
- [Torsimany](https://github.com/PolBaladas/torsimany) - Translate format-independent JSON to stylish, human-readable Markdown. ![Apple][apple] ![Linux][linux] ![Windows 8][windows8] :star:11
- [turndown](https://github.com/domchristie/turndown) - HTML to Markdown converter written in JavaScript. :star:2784
- [yamp](https://github.com/angrykoala/yamp) - Wasy-to-use cli toolbox for markdown-related task. ![Apple][apple] ![Linux][linux] ![Windows 8][windows8] :star:22

### Editors

> Edit and save your Markdown documents.

- [Abricotine](http://abricotine.brrd.fr/) - Lightweight markdown editor built with Electron with built-in realtime preview. ![Apple][apple] ![Linux][linux] ![Windows 8][windows8]
- [Caret](https://caret.io/) - Markdown Editor for Mac and PC. ![Apple][apple] ![Linux][linux] ![Windows 8][windows8]
- [iA Writer](https://ia.net/writer/) - iA Writer is designed to provide the best writing experience on Mac OS, iOS and Android. :gem: _Really simple editor!_ ![Android OS][android-os] ![iOS Logo][ios-logo] ![Apple][apple]
- [MarkRight](https://github.com/dvcrn/markright) - Minimalistic github flavored Markdown editor. ![Apple][apple] ![Linux][linux] ![Windows 8][windows8] :star:908
- [PileMd](https://pilemd.com/) - Markdown Note App. ![Apple][apple] ![Linux][linux] ![Windows 8][windows8]
- [StackEdit](https://stackedit.io/) - In-browser markdown editor. ![Globe][globe]
- [TOAST UI Editor](https://nhnent.github.io/tui.editor/) - Extensible GFM Markdown WYSIWYG Editor ![Globe][globe]
- [Typora](https://typora.io/) - A minimal Markdown editor. ![Apple][apple] ![Linux][linux] ![Windows 8][windows8]

### Linters

> Flag and standarize your Markdown documents.

- [Markdown Lint Tool](https://github.com/markdownlint/markdownlint) - Tool to check Markdown files and flag style issues. :star:450
- [Markdownlint](https://github.com/igorshubovych/markdownlint-cli) - Node.js style checker and lint tool for Markdown/CommonMark files. :star:49
- [textlint](https://textlint.github.io/) - Pluggable linting tool for text and markdown.

### Miscellaneous

> Tools which let you edit, convert, export, _et al._ your Markdown documents.

- [Classeur](http://classeur.io/) - Classeur is a new platform to write simple notes as well as technical documents and blogs. ![Globe][globe]
- [Dillinger](https://dillinger.io/) - Dillinger is a cloud-enabled, mobile-ready, offline-storage, AngularJS powered HTML5 Markdown editor. ![Globe][globe]
- [GitDown](https://github.com/gajus/gitdown) – GitHub's Markdown preprocessor. :octocat:
- [HackMD](https://hackmd.io) - HackMD lets you create realtime collaborative Markdown notes on all platforms. ![Globe][globe]
- [Laverna](https://laverna.cc/) - Laverna is a JavaScript note taking application with Markdown editor and encryption support. :gem: _Markdown notes with encryption!_ ![Globe][globe] ![Apple][apple] ![Linux][linux] ![Windows 8][windows8]
- [Markable.in](https://markable.in/) - Remarkable Markdown Editor. ![Globe][globe]
- [markcat](https://github.com/BubuAnabelas/markcat) - Markdown files terminal viewer. :gem: _`cat` with Markdown highlight._ ![Apple][apple] ![Linux][linux] ![Windows 8][windows8] :star:14
- [Markdown Tables Generator](http://www.tablesgenerator.com/markdown_tables) - Visual Markdown table builder with CSV importing support. ![Globe][globe]
- [remark](https://remark.js.org/) - Markdown processor powered by plugins
- [Socrates](http://socrates.io/) - Serveless realtime Markdown editor and viewer, etherpad-like. ![Globe][globe]

### Presentations

> Create and edit your slides presentations with Markdown.

- [Marp](https://yhatt.github.io/marp/) - Markdown Presentation Writer. :gem: _Like PowerPoint but with Markdown!_ ![Apple][apple] ![Linux][linux] ![Windows 8][windows8]
- [mdp](https://github.com/visit1985/mdp) - Command-line based Markdown presentation tool. :gem: _Like PowerPoint and Vim but with Markdown!_ ![Apple][apple] ![Linux][linux] :star:2935
- [remark](https://remarkjs.com) - A simple, in-browser, Markdown-driven slideshow tool targeted at people who know their way around HTML and CSS. ![Globe][globe]

## Services

> Different services which take advantage of Markdown.

- [Daux.io](http://daux.io) - Daux.io is an documentation generator that uses a simple folder structure and Markdown files to create custom documentation on the fly.
- [GitBook](https://www.gitbook.com/) - GitBook is a modern publishing toolchain. Making both writing and collaboration easy.
- [GitPrint](https://gitprint.com/) - Easily print GitHub Markdown. ![Globe][globe]
- [NoteHub](https://notehub.org/) - Free and Hassle-free Pastebin for Markdown Notes. :gem: _Like Pastebin but with Markdown_ ![Globe][globe]
- [Stacktile](https://stacktile.io/) - Turn a Markdown document into an interactive tutorial.

## Resources

### Documentation

> Documentation and useful information about Markdown.

- [CommonMark](http://commonmark.org/) - Strongly defined, highly compatible specification of Markdown.
- [GitHub Flavored Markdown Specifications](https://github.github.com/gfm/) - The formal spec for GitHub's Markdown, based on CommonMark.
- [Original Specifications](https://daringfireball.net/projects/markdown/) :gem: _The place to start with Markdown!_
- [Pandoc’s Markdown](http://pandoc.org/MANUAL.html#pandocs-markdown) - [Pandoc](http://pandoc.org/) has its own, powerful markdown implementation. It consists of several addional extensions.
- [ScholarlyMarkdown](http://scholarlymarkdown.com/) - ScholarlyMarkdown is a syntax/standard/best-practice of scholarly and academic communication that is web-first, semantic XML-second, and LaTeX/Word a close third.
- [Stack Overflow Markdown Documentation (archived)](https://web.archive.org/web/20160724152503/https://stackoverflow.com/documentation/markdown/topics) - Well organized Markdown documentation.
- [Stack Overflow Markdown Questions](https://stackoverflow.com/questions/tagged/markdown) - Highest voted Markdown questions on Stack Overflow.
- [The text/markdown Media Type (RFC7763)](https://tools.ietf.org/html/rfc7763) - This document registers the `text/markdown` media type for use with Markdown, a family of plain-text formatting syntaxes.
- [Wikipedia Article](https://en.wikipedia.org/wiki/Markdown)

### Tutorials

> Useful links and tutorials.

- [GitHub's Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [how-to-markdown](https://github.com/workshopper/how-to-markdown) - This workshopper will teach you how to use Markdown. :star:100
- [Interactive Markdown Tutorial](https://www.markdowntutorial.com/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) :gem: _Where to look when you don't remember the syntax!_
- [Markdown Guide](https://www.markdownguide.org) - A concise, barebones guide to Markdown.

---

_[Icon pack by Icons8](https://icons8.com)_

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Joaquín Serna](https://github.com/BubuAnabelas) has waived all copyright and related or neighboring rights to this work.

<!--Definitions-->

[globe]: https://maxcdn.icons8.com/Color/PNG/24/Maps/globe-24.png 'Globe'
[android-os]: https://maxcdn.icons8.com/Color/PNG/24/Operating_Systems/android_os_copyrighted-24.png 'Android OS'
[ios-logo]: https://maxcdn.icons8.com/Color/PNG/24/Logos/ios_logo-24.png 'iOS Logo'
[apple]: https://maxcdn.icons8.com/Android_L/PNG/24/Operating_Systems/mac_os-24.png 'Apple'
[linux]: https://maxcdn.icons8.com/Color/PNG/24/Operating_Systems/linux-24.png 'Linux'
[windows8]: https://maxcdn.icons8.com/Color/PNG/24/Operating_Systems/windows8_copyrighted-24.png 'Windows8'


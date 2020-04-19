# Information comes from [nikgraf/awesome-draft-js](https://github.com/nikgraf/awesome-draft-js)
# Awesome Draft.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[Draft.js](https://draftjs.org/) is a framework for building rich text editors in React.

**Table of Contents**

- [Community](https://github.com/nikgraf/awesome-draft-js#community) :star:2104
- [Presentations](https://github.com/nikgraf/awesome-draft-js#presentations) :star:2104
- [Projects on Top of Draft.js](https://github.com/nikgraf/awesome-draft-js#standalone-editors-built-on-draftjs) :star:2104
- [Common Utilities](https://github.com/nikgraf/awesome-draft-js#common-utilities) :star:2104
- [Blog Posts & Articles](https://github.com/nikgraf/awesome-draft-js#blog-posts--articles) :star:2104
- [Live Demos](https://github.com/nikgraf/awesome-draft-js#live-demos) :star:2104
- [Usage in Production](https://github.com/nikgraf/awesome-draft-js#usage-in-production) :star:2104
- [License](https://github.com/nikgraf/awesome-draft-js#license) :star:2104

## Community

* [Slack channel](https://draftjs.herokuapp.com/)

## Presentations
* [Rich Text Editing with React @ React.js Conf 2016 by Isaac Salier-Hellendag ](https://www.youtube.com/watch?v=feUYwoLhE_4)
* [Rich text editing with Draft.js & DraftJS Plugins by Nik Graf](https://www.youtube.com/watch?v=gxNuHZXZMgs)
* [React Ep. 37: Draftjs by What I Learned Today – Atomic Jolt](https://www.youtube.com/watch?v=0k9suXgCtTA)
* [008 - Draft.js Plugins @ React30](https://www.youtube.com/watch?v=w-PqnpMizcQ)
* [Draft.js at HubSpot by Ben Briggs](https://product.hubspot.com/blog/tech-talk-at-night-react-meetup)
* [Draft.js under the hood - React Melbourne meetup](https://www.youtube.com/watch?feature=player_embedded&v=vOZAO3jFSHI)

## Standalone Editors Built on Draft.js

* [Draft WYSIWYG](https://github.com/bkniffler/draft-wysiwyg) - WYSIWYG editor that with drag&drop, resizing & tooltips. :star:441
* [Draft.js Editor](https://github.com/AlastairTaft/draft-js-editor/) - A Rich text editor inspired by Medium & Facebook Notes. :star:140
* [React-RTE](https://github.com/sstur/react-rte/) - A full-featured textarea replacement similar to CKEditor or TinyMCE. :star:2256
* [Facebook Notes Clone(ish)](https://github.com/andrewcoelho/react-text-editor) - Rich text editor similar to Facebook notes. :star:223
* [Megadraft](https://github.com/globocom/megadraft) - A rich text editor with a nice default base of plugins and extensibility. :star:904
* [Medium Draft](https://github.com/brijeshb42/medium-draft) - Medium-like rich text editor with a focus on keyboard shortcuts. :star:1519
* [React-Draft-Wyiswyg](https://github.com/jpuri/react-draft-wysiwyg) - A WYISWYG editor, with various text editing options and corresponding HTML generation. :star:4126
* [Dante 2](https://github.com/michelson/dante2) - Just another Medium clone built on top of DraftJs. :star:743
* [Last Draft](https://github.com/vacenz/last-draft) - A Draft editor built with Draft.js plugins. :star:208
* [Z-Editor](https://github.com/Z-Editor/Z-Editor) - Online Z-notations editor. :star:89
* [Draftail](https://github.com/springload/draftail/) -  A configurable rich text editor based on Draft.js, built for Wagtail. :star:312
* [Braft](https://github.com/margox/braft-editor) - Extensible Draft JS Editor :star:3088

## Plugins and Decorators Built for Draft.js

* [Draft.js Plugins](https://github.com/draft-js-plugins/draft-js-plugins) - A Plugin architecture on top of Draft.js :star:3449
  - [Alignment](https://www.draft-js-plugins.com/plugin/alignment)
  - [Block Breakout](https://github.com/icelab/draft-js-block-breakout-plugin) - Break out of block types as you type. :star:39
  - [Buttons](https://github.com/vacenz/last-draft-js-plugins) :star:81
  - [Color Picker](https://github.com/vacenz/last-draft-js-plugins) :star:81
  - [Counter](https://www.draft-js-plugins.com/plugin/counter) - Character, word & line counting.
  - [Divider](https://github.com/simsim0709/draft-js-plugins/tree/master/draft-js-divider-plugin) :star:2
  - [Drag and Drop](https://www.draft-js-plugins.com/plugin/drag-n-drop)
  - [Embed](https://github.com/vacenz/last-draft-js-plugins) :star:81
  - [Emoji](https://www.draft-js-plugins.com/plugin/emoji) - Slack-like emoji support
  - [EmojiPicker](https://github.com/vacenz/last-draft-js-plugins) :star:81
  - [Focus](https://www.draft-js-plugins.com/plugin/focus)
  - [GifPicker](https://github.com/vacenz/last-draft-js-plugins) :star:81
  - [Hashtags](https://www.draft-js-plugins.com/plugin/hashtag) - Twitter-like hashtag support
  - [Image](https://www.draft-js-plugins.com/plugin/image)
  - [Inline Toolbar](https://www.draft-js-plugins.com/plugin/inline-toolbar)
  - [Katex](https://github.com/letranloc/draft-js-katex-plugin) - Insert and render LaTeX using Katex. :star:22
  - [Link](https://github.com/vacenz/last-draft-js-plugins) :star:81
  - [Linkify](https://www.draft-js-plugins.com/plugin/linkify) - Automatically turn links into anchor-tags.
  - [List](https://github.com/samuelmeuli/draft-js-list-plugin) - Automatic list creation, nested lists :star:7
  - [Markdown Shortcuts](https://github.com/ngs/draft-js-markdown-shortcuts-plugin/) - Markdown syntax shortcuts. :star:209
  - [Mathjax](https://github.com/efloti/draft-js-mathjax-plugin) - Edit math using (La)TeX rendered by Mathjax. :star:67
  - [Mention](https://www.draft-js-plugins.com/plugin/mention) - Twitter-like mention support
  - [Modal](https://github.com/vacenz/last-draft-js-plugins) :star:81
  - [Prism](https://github.com/withspectrum/draft-js-prism-plugin) - Syntax highlight code blocks with Prism. :star:39
  - [Resizeable](https://www.draft-js-plugins.com/plugin/resizeable)
  - [RichButtons](https://github.com/jasonphillips/draft-js-richbuttons-plugin) - Add and customize rich formatting buttons. :star:39
  - [Side Toolbar](https://www.draft-js-plugins.com/plugin/side-toolbar)
  - [Sidebar](https://github.com/vacenz/last-draft-js-plugins) :star:81
  - [Single Line](https://github.com/icelab/draft-js-single-line-plugin) - Restrict to a single line of input. :star:34
  - [Sticker](https://www.draft-js-plugins.com/plugin/sticker) - Facebook-like sticker support
  - [Toolbar](https://github.com/vacenz/last-draft-js-plugins) :star:81
  - [Undo](https://www.draft-js-plugins.com/plugin/undo) - Undo & Redo button.
  - [Video](https://www.draft-js-plugins.com/plugin/video)
* [Draft.js Gutter](https://github.com/seejamescode/draft-js-gutter) - Compliments line number gutter. :star:13
* [Draft.js Basic HTML Editor](https://github.com/dburrows/draft-js-basic-html-editor) - Accept html as its input format, and return html to an onChange. :star:79
* [Draft.js Prism](https://github.com/SamyPesse/draft-js-prism)- Highlight code blocks using Prism.
* [Draft.js Typeahead](https://github.com/dooly-ai/draft-js-typeahead) - Support for typeahead functionality. :star:114
* [Draft Extend](https://github.com/HubSpot/draft-extend) - Build extensible Draft.js editors with configurable plugins and integrated serialization. :star:102
* [Draft.js Code](https://github.com/SamyPesse/draft-js-code) - A collection of low-level utilities for nicer code editing :star:97
* [Draft.js Annotatable](https://github.com/cltk/annotations) - Out of the box annotation system for Draft.js with support for user-created annotations. :star:13
* [Draft.js Regex](https://github.com/YozhikM/draft-regex) - The set of flexible helpers, like regex, blank lines preventing and pasted HTML clearing. :star:20

## Common Utilities

* [BackDraft.js](https://github.com/evanc/backdraft-js) - Function to turn a rawContentBlock into a marked-up string. :star:43
* [Draft.js Exporter](https://github.com/rkpasia/draft-js-exporter) - Export and format the content from Draft.js. :star:32
* [Draft.js: Export ContentState to HTML](https://github.com/sstur/draft-js-utils/tree/master/packages/draft-js-export-html) - Export ContentState to HTML. :star:724
* [Draft.js: Export ContentState to PDFMake](https://github.com/datagenno/draft-js-export-pdfmake) - Export ContentState to PDFMake. :star:7
* [Redraft](https://github.com/lokiuz/redraft) - Renders the result of Draft.js convertToRaw using provided callbacks, works well with React :star:223
* [Draft.js exporter (Ruby)](https://github.com/ignitionworks/draftjs_exporter) - Export Draft.js content state into HTML. :star:16
* [Draft.js exporter (Python)](https://github.com/springload/draftjs_exporter) - Library to convert Draft.js raw ContentState to HTML :star:57
* [Draft.js AST Exporter](https://github.com/icelab/draft-js-ast-exporter) - Export content into an abstract syntax tree (AST). :star:31
* [Draft.js AST Importer](https://github.com/icelab/draft-js-ast-importer)- Import an abstract syntax tree (AST) output from the companion draft-js-ast-exporter.
* [Draft.js Multidecorators](https://github.com/SamyPesse/draft-js-multidecorators) - Combine multiple decorators. :star:29
* [Draft.js SimpleDecorator](https://github.com/Soreine/draft-js-simpledecorator) - Easily create flexible decorators. :star:19
* [DraftJS Utils](https://github.com/jpuri/draftjs-utils) - Set of utility functions for DraftJS. :star:197
* [DraftJs to HTML](https://github.com/jpuri/draftjs-to-html) - Library for generating HTML for DraftJS editor content. :star:206
* [Draft Convert](https://github.com/HubSpot/draft-convert) - Extensibly serialize & deserialize Draft.js ContentState with HTML. :star:364
* [HTML to DraftJS](https://github.com/jpuri/html-to-draftjs) - Convert plain HTML to DraftJS Editor content. :star:98
* [Draft.js Exporter (Go)](https://github.com/ejilay/draftjs) - Export Draft.js content state into HTML. :star:18
* [React Native Draft.js Render](https://github.com/globocom/react-native-draftjs-render) - A React Native render for Draft.js model. :star:331
* [Draft.js filters](https://github.com/thibaudcolas/draftjs-filters) - Filter Draft.js content to preserve only the formatting you allow. :star:31
* [Sticky](https://github.com/nadunindunil/sticky) - A simple note taking and clipboard managing desktop application :star:5

## Blog Posts & Articles

* [Facebook open sources rich text editor framework Draft.js](https://code.facebook.com/posts/1684092755205505/facebook-open-sources-rich-text-editor-framework-draft-js/)
* [This Blog Post Was Written Using Draft.js](https://dev.to/ben/this-blog-post-was-written-using-draftjs)
* [How Draft.js Represents Rich Text Data](https://medium.com/@rajaraodv/how-draft-js-represents-rich-text-data-eeabb5f25cf2#.7gd8psdvi)
* [A Beginner’s Guide to Draft.js](https://medium.com/@adrianli/a-beginner-s-guide-to-draft-js-d1823f58d8cc#.uufeulpl5)
* [Implementing todo list in Draft.js](http://bitwiser.in/2016/08/31/implementing-todo-list-in-draft-js.html)
* [Draft.js Pieces](https://cannibalcoder.com/2016/12/02/draft-js-pieces/)
* [Learning Draft.js](https://reactrocket.com/series/learning-draft-js/) - Series of blog posts on how to develop with draft.js
* [Why Wagtail’s new editor is built with Draft.js](https://wagtail.io/blog/why-wagtail-new-editor-is-built-with-draft-js/)
* [Rethinking rich text pipelines with Draft.js](https://wagtail.io/blog/rethinking-rich-text-pipelines-with-draft-js/)

## Live Demos
* [Draft-js Samples - An app with examples and code explanations](https://github.com/Mair/react-meetup-draftjs) :star:57
* [Draftail Playground](https://draftail-playground.herokuapp.com/) – Wagtail’s Draft.js dependencies as a standalone demo.
* [Draft drag and drop demo for mobile browser](https://github.com/jan4984/draft-dnd-example) :star:12

## Playgrounds for Examples from Official Repository (v.0.10.0)
* [Rich Text Editor](https://codepen.io/Kiwka/pen/YNYvyG)
* [Color Editor](https://codepen.io/Kiwka/pen/oBpVve)
* [Convert from HTML Editor](https://codepen.io/Kiwka/pen/YNYgWa)
* [Entity Editor](https://codepen.io/Kiwka/pen/wgpOoZ)
* [Link Editor](https://codepen.io/Kiwka/pen/ZLvPeO)
* [Media Editor](https://codepen.io/Kiwka/pen/rjpRzj)
* [Plain Text Editor](https://codepen.io/Kiwka/pen/jyYJzb)
* [Decorators Editor - Tweet example](https://codepen.io/Kiwka/pen/KaZERV)

## Usage in Production
* [StoryChief](https://www.storychief.io/)
* [HKW Technosphere Magazine](https://technosphere-magazine.hkw.de/)
* [Douban Read](https://read.douban.com/editor_ng)
* [Dooly](https://www.dooly.ai)
* [Wagtail](https://wagtail.io/)
* [Patreon](https://www.patreon.com/)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Nikolaus Graf](https://github.com/nikgraf/) has waived all copyright and related or neighboring rights to this work.


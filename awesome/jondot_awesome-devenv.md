# Information comes from [jondot/awesome-devenv](https://github.com/jondot/awesome-devenv)
# Awesome Dev Env [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome tools, resources and workflow tips making an awesome development environment.

Inspired by [awesome-go](https://github.com/avelino/awesome-go), which was in turn inspired by [awesome-python](https://github.com/vinta/awesome-python).

### Contributing

[Guidelines](https://github.com/jondot/awesome-devenv/blob/master/CONTRIBUTING.md) tweaked and adapted from `awesome-go` - thanks!

But in short:

* List is alphabetically sorted
* If you think an item shouldn't be here [open an issue](https://github.com/jondot/awesome-devenv/issues/new)


Many thanks to everyone on the [contributor list](https://github.com/jondot/awesome-devenv/graphs/contributors) :)


# Content

_Note: for an OS specific tool, please do your best to mark with `OSX/WIN/*NIX/LIN`_



- [Admins](#admins)
- [Benchmarking](#benchmarking)
- [Data](#data)
- [Diagnostics](#diagnostics)
- [Desktop](#desktop)
- [Dotfiles](#dotfiles)
- [Editors](#editors)
  - [Atom](#atom)
  - [Sublime Text](#sublime-text-3)
  - [Vim](#vim)
  - [IntelliJ](#intellij)
- [Git](#git)
- [Misc](#misc)
- [Notifications](#notifications)
- [Orchestration](#orchestration)
- [Presentation](#presentation)
- [Shell](#shell)
- [Text](#text)
- [Terminal](#terminal)
- [Workflow](#workflow)


## Admins
*Tools to manage databases, permissions, etc.*

* [MongoHub](https://github.com/fotonauts/MongoHub-Mac/releases) - Native OSx client for mongo
* [Robomongo](http://robomongo.org/) - a cross platform Admin for MongoDB


## Benchmarking
*Tools to benchmark your code or services*

* [apachebench (ab)](http://httpd.apache.org/docs/2.2/programs/ab.html)
* [boom](https://github.com/rakyll/boom) :star:4793
* [httperf](http://www.hpl.hp.com/research/linux/httperf/)
* [phantomas](https://github.com/macbre/phantomas) - website perf evaluation tool :star:2069
* [siege](http://www.joedog.org/siege-home/)
* [Vegeta](https://github.com/tsenart/vegeta) :star:7627
* [wrk](https://github.com/wg/wrk) :star:15582
* [redis-faina](https://github.com/Instagram/redis-faina) Instagram's Redis counter/timing stats based on the MONITOR command


## Data
*Tools for handling online and offline data*

* [s3cmd](https://github.com/s3tools/s3cmd) - the S3 CLI tool for Amazon :star:2624


## Diagnostics
*Tools for checking diagnosing your system while you work*

* [glances](https://github.com/nicolargo/glances) :star:9725
* [nmon](http://nmon.sourceforge.net/pmwiki.php)
* [gtop](https://github.com/aksakalli/gtop) :star:6727


## Desktop
*Tools for improving and hacking around with your vanilla desktop*

* [Alfred](http://www.alfredapp.com/) - OSX productivity app `/OSX/`
* [hydra](https://github.com/sdegutis/hydra) - script your desktop :star:29
  `/OSX/`
* [Keycastr](https://github.com/sdeken/keycastr) - show your keys while :star:312
  presenting/casting `/OSX/`


## Dotfiles

* [dotfiles.github.io](https://dotfiles.github.io/) - Collected dotfile resources. Has sections with dotfile bootstraps and lists of frameworks for various shells and editors.
* [Zach Holman's](https://github.com/holman/dotfiles) - oh-my-zsh, osx, Zsh, vi, Ruby, Git, and more :star:4953
* [Mathias Bynens's](https://github.com/mathiasbynens/dotfiles) - .files, including ~/.osx — sensible hacker defaults for OS X :star:18843
* [Thoughtbot's](https://github.com/thoughtbot/dotfiles) - A set of vim, zsh, git, and tmux configuration files :star:4846
* [Paul Miller's](https://github.com/paulmillr/dotfiles) - Colourful & robust OS X configuration files and utilities :star:754


## Editors
*Only awesome tools and addons for your favorite editor*

### Atom

* [atom-beautify](https://github.com/Glavin001/atom-beautify) - Beautify HTML (including Handlebars), CSS (including Sass and Less), JavaScript, and much more in Atom. :star:1227
* [file-icons](https://github.com/DanBrooker/file-icons) - Adds file specific icons to atom for improved visual grepping. :star:853
* [highlight-selected](https://github.com/richrace/highlight-selected) - Double click on a word to highlight it throughout the open file. :star:199
* [minimap](https://github.com/atom-minimap/minimap) - A graphical map (preview) of the full source code. :star:580
* [minimap-git-diff](https://github.com/atom-minimap/minimap-git-diff) - A minimap binding for the Atom git-diff package. :star:19
* [minimap-highlight-selected](https://github.com/atom-minimap/minimap-highlight-selected) - A minimap binding for the highlight-selected package. :star:38
* [atom-project-manager](https://github.com/danielbrodin/atom-project-manager) - Get easy access to all your projects and manage them with project specific settings and options. :star:499
* [atom-tree-view-git-status](https://github.com/subesokun/atom-tree-view-git-status) - Show the Git repository status in the Atom tree-view. :star:18
* [atom-pigments](https://github.com/abe33/atom-pigments) - An Atom package to display colors in project and files. :star:491

### Vim

* [Completor](https://github.com/maralla/completor.vim) - async autocomplete with support for omni and semantic completion. :star:745
* [Powerline](https://github.com/Lokaltog/powerline) - improved status bar for your buffers. :star:8842
* [snipmate](https://github.com/garbas/vim-snipmate) - textual snippets compatiable with Textmate snippets. :star:1667
* [The Ultimate Vim Distribution](http://vim.spf13.com/) - spf13-vim is a distribution of vim plugins and resources for Vim, GVim and MacVim.

### Sublime Text 3

* [AdvancedNewFile](https://github.com/skuroda/Sublime-AdvancedNewFile) - File creation plugin. :star:750
* [Emmet](https://github.com/sergeche/emmet-sublime) :star:5156
* [Git Gutter](https://github.com/jisaacks/GitGutter) - display changed/added lines in the margin of the editor window. :star:3696
* [jsFormat](https://github.com/jdc0589/JsFormat) - Javascript formatting. :star:1325
* [LiveReload](https://github.com/dz0ny/LiveReload-sublimetext2) - LiveReload plugin.
* [MarkdownEditing](https://github.com/SublimeText-Markdown/MarkdownEditing) - Markdown syntax understanding and good color schemes. :star:2374
* [Package Control](https://sublime.wbond.net/installation) - The Sublime Text package manager.
* [RubyTest](https://github.com/maltize/sublime-text-2-ruby-tests) - Plugin for running Ruby tests. :star:741
* [Side Bar Enhancments](https://github.com/titoBouzout/SideBarEnhancements) - Enhancements to Sublime Text sidebar. Files and folders. :star:126
* [Sublime Git](https://github.com/kemayo/sublime-text-git) - Git Integration for Sublime. :star:2766
* [Sublime Linter](https://github.com/SublimeLinter/SublimeLinter3/) - Interactive code linting. :star:1555
* [TrailingSpaces](https://github.com/SublimeText/TrailingSpaces) - Highlight trailing spaces and delete them in a flash. :star:836

### Intellij

* [keymap](https://github.com/jondot/keymaps/) - a hybrid Vim/ReSharper/Intellij keymap


## Git
*Tools and addons for making an awesome Git experience*

* [awesome-github](https://github.com/fffaraz/awesome-github) - Faraz Fallahi maintains a curated list of GitHub & Git resources. :star:203
* [gh](https://github.com/jingweno/gh) - Fast GitHub command line client (hub port to Go)
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - collected git helper scripts :star:288
* [git-extras](https://github.com/visionmedia/git-extras) - GIT utilities -- repo summary, repl, changelog population, author commit percentages and more :star:11325
* [git-it-on](https://github.com/peterhurford/git-it-on.zsh) - ZSH plugin, adds a gitit command that opens the current directory on github in your current branch :star:53
* [git-secret](https://github.com/sobolevn/git-secret) - A bash-tool to store your private data inside a git repository. :star:857
* [git-semver](https://github.com/markchalloner/git-semver) - A git plugin to make Semantic Versioning 2.0.0 and Change Log management easier. :star:151
* [git-sweep](https://github.com/arc90/git-sweep) - safely removes branches that have been merged into the master :star:1722
* [git-up](https://github.com/aanand/git-up) - a better 'git pull' :star:2715
* [hub](https://hub.github.com/) - git CLI wrapper which makes working with GitHub easier
* [scm_breeze](https://github.com/ndbroadbent/scm_breeze) Streamline your git workflow
* [tig](http://jonas.nitro.dk/tig/) - an ncurses-based text-mode interface for git

## Misc
*Useful tools that cannot find a home in other categories*

* [Mockoon](https://mockoon.com) - an API / HTTP REST mocking desktop application

## Notifications
*Tools that notify developers about changes in their work environment*

* [CatLight](https://catlight.io) - status notifier for developers. Checks the status of continuous delivery builds and shows desktop notifications.

## Orchestration
*Tools for orchestrating awesome development environments*

* [azk](https://github.com/azukiapp/azk) - a lightweight open source engine to orchestrate development environments :star:852
* [Nanobox](https://github.com/nanobox-io/nanobox) - A micro-PaaS (μPaaS) for creating consistent, isolated, development environments deployable anywhere https://nanobox.io. :star:1212

## Presentation
*Tools for presenting your work*

* [bespoke.js](https://github.com/markdalgleish/bespoke.js) - DIY Presentation Micro-Framework :star:4353
* [hacker-slides](https://github.com/msoedov/hacker-slides) - Reveal.js based presentation tool :star:59
* [impress.js](https://github.com/impress/impress.js) - presentation framework based on the power of CSS3 transforms and transitions :star:33419
* [remark](https://github.com/gnab/remark) - markdown based presentation on your browser :star:7642
* [reveal.js](https://github.com/hakimel/reveal.js/) - markdown based presentation on your browser
* [deck.js](https://github.com/imakewebthings/deck.js) - markdown based presentation on your browser :star:5272
* [vimdeck](https://github.com/tybenz/vimdeck) - present inside your Vim :star:1142
* [WebSlides](https://github.com/jlantunez/webslides) - Making HTML presentations easy :star:4146

## Shell
*Tools for having an awesome shell environment*

* [awesome-zsh-plugins](https://github.com/unixorn/awesome-zsh-plugins) - List of zsh plugins usable with [zgen](https://github.com/tarjoilija/zgen) and other [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh/) compatible zsh frameworks :star:4118
* [fish-shell](https://github.com/fish-shell/fish-shell) - The user-friendly command line shell :star:9536
* [oh-my-fish](https://github.com/oh-my-fish/oh-my-fish) - Framework for managing your fish shell configuration inspired by oh-my-zsh. :star:3346
* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh/) - A community driven framework for managing zsh configuration.
* [zgen](https://github.com/tarjoilija/zgen) - Faster framework for managing your zsh configuration, backward compatible with oh-my-zsh plugins :star:883
* [zsh](http://www.zsh.org/) - A shell designed for interactive use, although it is also a powerful scripting language.
* [shellcheck](https://github.com/koalaman/shellcheck) - Lint for shell. Will find deprecated and/or dangerous usage in shell scripts :star:10659
* [zsh quickstart kit](https://github.com/unixorn/zsh-quickstart-kit) - Quick intro for getting set up with zsh and zgen :star:144

## Text
*Tools for working with text files - search, replace, processing*

* [ack](https://github.com/petdance/ack2) - the Perl based :star:1332
  better-than-grep tool.
* [ag](https://github.com/ggreer/the_silver_searcher) - A C based code-searching tool similar to ack, but faster :star:14951
* [peco](https://github.com/peco/peco) - interactive filtering, like interactive Grep :star:4518


## Terminal
*Tools and addons for terminal and terminal work*

* [autojump](https://github.com/joelthelion/autojump) - remembers your :star:7197
  folders and jump to them based on partial recall (e.g. `j proj` will jump
to `/home/Users/yourself/projects`.
* [fasd](https://github.com/clvv/fasd) Command-line productivity booster, offers quick access to files and directories.
* [homebrew](http://brew.sh) - Makes it easy to install open source packages on an `OS X` system with a single command.
* [httpie](http://httpie.org/) A command line HTTP client, a user-friendly cURL replacement.
* [iTerm2](http://www.iterm2.com/) - a great terminal replacement `/OSX/`
* [jq](https://stedolan.github.io/jq/) - a lightweight and flexible command-line JSON processor
* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) - the :star:69073
  incredible ZSH addon.
* [Pipe Viewer](http://www.ivarch.com/programs/pv.shtml) - a tool for monitoring the progress of data through a pipeline
* [tmux](https://tmux.github.io/) the awesome terminal multiplexer.


## Workflow
*Tools and addons which improve your daily workflow with code*

* [fswatch](https://github.com/alandipert/fswatch) - a watch tool which :star:2129
  will emit FS events and you can run commands on demand with. Note -
`fswatch-run` too.
* [guard](https://github.com/guard/guard) - FS watch tool with a huge ecosystem of plugins :star:5548
* [LiveReload](http://livereload.com/) - FS watch and preprocessor as a desktop app for `/OSX/` and `/WIN/` with complementary browser extensions
  * [guard-livereload](https://github.com/guard/guard-livereload) - Guard plugin compatible with LiveReload's browser extensions :star:1959
* [watchman](https://github.com/facebook/watchman) - Facebook's better :star:6566
  `watch` - note it works as a service.
* [Zappr](https://github.com/zalando/zappr) - GitHub integration built to enhance your project workflow via enable/disable pull request approval checks. :star:362
* [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy. :star:174


# Information comes from [unixorn/awesome-zsh-plugins](https://github.com/unixorn/awesome-zsh-plugins)
# awesome-zsh-plugins

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Status

[![License](https://img.shields.io/github/license/unixorn/awesome-zsh-plugins.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![Build Status](https://travis-ci.org/unixorn/awesome-zsh-plugins.svg?branch=master)](https://travis-ci.org/unixorn/awesome-zsh-plugins)
[![Join the chat at https://gitter.im/unixorn/awesome-zsh-plugins](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/unixorn/awesome-zsh-plugins?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![GitHub stars](https://img.shields.io/github/stars/unixorn/awesome-zsh-plugins.svg)](https://github.com/unixorn/awesome-zsh-plugins/stargazers)
[![Code Climate](https://codeclimate.com/github/unixorn/awesome-zsh-plugins/badges/gpa.svg)](https://codeclimate.com/github/unixorn/awesome-zsh-plugins)
[![Issue Count](https://codeclimate.com/github/unixorn/awesome-zsh-plugins/badges/issue_count.svg)](https://codeclimate.com/github/unixorn/awesome-zsh-plugins)

A collection of ZSH frameworks, plugins, tutorials & themes inspired by the various awesome list collections out there.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [Frameworks](#frameworks)
  - [alf](#alf)
  - [ansible-role-zsh](#ansible-role-zsh)
  - [ant-zsh](#ant-zsh)
  - [antibody](#antibody)
  - [antigen-hs](#antigen-hs)
  - [antigen](#antigen)
  - [ax-zsh](#ax-zsh)
  - [dotzsh](#dotzsh)
  - [fresh](#fresh)
  - [oh-my-zsh](#oh-my-zsh)
  - [prezto](#prezto)
  - [pumice](#pumice)
  - [Toasty](#toasty)
  - [zeesh](#zeesh)
  - [zgem](#zgem)
  - [zgen](#zgen)
  - [zilsh](#zilsh)
  - [zim](#zim)
  - [zit](#zit)
  - [zoppo](#zoppo)
  - [zpacker](#zpacker)
  - [zplug](#zplug)
  - [zplugin](#zplugin)
  - [ZPM](#zpm)
  - [ZR](#zr)
  - [zshing](#zshing)
  - [ztanesh](#ztanesh)
  - [zulu](#zulu)
- [Tutorials](#tutorials)
  - [Generic ZSH](#generic-zsh)
  - [Antigen](#antigen)
  - [Oh-My-Zsh](#oh-my-zsh)
  - [Prezto](#prezto)
  - [Zgen](#zgen)
- [Plugins](#plugins)
- [Even more completions](#even-more-completions)
- [Themes](#themes)
  - [Fonts](#fonts)
- [Installation](#installation)
  - [Antigen / Antibody](#antigen--antibody)
  - [dotzsh](#dotzsh-1)
  - [Oh-My-Zsh](#oh-my-zsh-1)
  - [Prezto](#prezto-1)
  - [Zgen](#zgen-1)
  - [zplug](#zplug-1)
- [Writing New Plugins](#writing-new-plugins)
- [Other Resources](#other-resources)
  - [ZSH Tools](#zsh-tools)
  - [Other Useful Lists](#other-useful-lists)
  - [Other References](#other-references)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

*Please read the [Contributing Guidelines](Contributing.md) before contributing.*

## Frameworks

These frameworks make customizing your ZSH setup easier.

### [alf](https://github.com/psyrendust/alf)

**Alf** is an out of this world super fast and configurable framework for ZSH; it's modeled after Prezto and Antigen while utilizing Oh-My-Zsh under the covers; and offers standard defaults, aliases, functions, auto completion, automated updates and installable prompt themes and plugins.

### [ansible-role-zsh](https://github.com/viasite-ansible/ansible-role-zsh)

**ansible-role-zsh** is an ansible role with zero-knowledge installation. It uses antigen to manage bundles and oh-my-zsh. Can load bundles conditionally. By default it includes powerlevel9k theme, autosuggestions, syntax-highlighting and fzf-widgets. Fully customizable.

### [ant-zsh](https://github.com/anthraxx/ant-zsh)

**Ant-zsh** is a tiny and lightweight ZSH configuration environment for special customization needs. It includes plugins, themes and a basic convenient setup.

### [antibody](https://github.com/getantibody/antibody)

**Antibody** A faster and simpler antigen written in Golang. More details at [http://getantibody.github.io/](http://getantibody.github.io/).

### [antigen-hs](https://github.com/Tarrasch/antigen-hs)

**antigen-hs** is a replacement for antigen optimized for a low overhead when starting up the shell. It will automatically clone plugins for you.

### [antigen](https://github.com/zsh-users/antigen)

**Antigen** is a small set of functions that help you easily manage your shell (ZSH) plugins, called bundles. The concept is pretty much the same as bundles in a typical vim+pathogen setup. Antigen is to ZSH, what Vundle is to vim. Antigen can load oh-my-zsh themes and plugins and will automatically clone them for you.

### [ax-zsh](https://github.com/alexbarton/ax-zsh)

**Ax-ZSH** is a modular configuration system for ZSH. It provides sane defaults and is extendable by plugins.

### [dotzsh](https://github.com/dotphiles/dotzsh)

**Dotzsh** strives to be platform and version independent. Some functionality may be lost when running under older versions of ZSH, but it should degrade cleanly and allow you to use the same setup on multiple machines of differing OSes without problems.

### [fresh](https://github.com/freshshell/fresh)

**fresh** is a tool to source shell configuration (aliases, functions, etc) from others into your own configuration files. We also support files such as ackrc and gitconfig. Think of it as Bundler for your dot files.

### [oh-my-zsh](https://ohmyz.sh/)

**oh-my-zsh** is a community-driven framework for managing your ZSH configuration. Includes 120+ optional plugins (rails, git, macOS, hub, capistrano, brew, ant, macports, etc), over 120 themes to spice up your morning, and an auto-update tool that makes it easy to keep up with the latest updates from the community.

### [prezto](https://github.com/sorin-ionescu/prezto)

**Prezto** enriches the ZSH command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes.

### [pumice](https://github.com/ryutamaki/pumice)

**Pumice** is a lightweight plugin manager for ZSH.

### [Toasty](https://github.com/5paceToast/toasty-zsh)

**Toasty** is a ZSH framework made to facilitate management, not dictate it.

### [zeesh](https://github.com/zeekay/zeesh)

**Zeesh** is a cross-platform ZSH framework. It's similar to, but incompatible with, [oh-my-zsh](http://ohmyz.sh/). It has a modular plugin architecture making it easy to extend. It has a rich set of defaults, but is designed to be as lightweight as possible.

### [zgem](https://github.com/qoomon/zgem)

**Zgem** is a plugin manager for ZSH that supports loading and updating plugins and themes from git, http and local files.

### [zgen](https://github.com/tarjoilija/zgen)

**Zgen** is a lightweight plugin manager for ZSH inspired by Antigen. The goal is to have a minimal overhead when starting up the shell because nobody likes waiting. The script generates a static `init.zsh` file which does nothing but source your plugins and append them to your `fpath`. This saves startup time by not having to execute time consuming logic (plugin checking, updates, etc). The downside is that you have to refresh the init script manually with `zgen reset` whenever you update your `.zshrc`. Can load [oh-my-zsh](http://ohmyz.sh/)-compatible plugins and themes, and will automagically clone them for you when you add them to your plugin list.

### [zilsh](https://github.com/zilsh/zilsh)

**zilsh** is a ZSH config system that aims to appeal more to power-users and follow the simplistic approach of vim-pathogen.

### [zim](https://github.com/zimfw/zimfw)

**Zim** is a ZSH configuration framework with blazing speed and modular extensions.

### [zit](https://github.com/m45t3r/zit)

**zit** is a plugin manager for ZSH. It is minimal because it implements the bare minimum to be qualified as a plugin manager: it allows the user to install plugins from Git repositories (and Git repositories only, them why the name), source plugins and update them. It does not implement fancy functions like cleanup of removed plugins, automatic compilation of installed plugins, alias for oh-my-zsh/prezto/other ZSH frameworks, building binaries, PATH manipulation and others.

### [zoppo](https://github.com/zoppo/zoppo)

**Zoppo** is the crippled configuration framework for ZSH. As an Italian saying goes: "chi va con lo zoppo, impara a zoppicare", we realized we were walking with a cripple and are now going to become crippled ourselves.

### [zpacker](https://github.com/happyslowly/zpacker)

**Zpacker** is a lightweight ZSH plugin & theme management framework.

### [zplug](https://github.com/zplug/zplug)

**:hibiscus: Zplug** is a next-generation ZSH plugin manager.

- Can manage everything
  - Zsh plugins/UNIX commands on [GitHub](https://github.com) and [Bitbucket](https://bitbucket.org)
  - Gist files ([gist.github.com](https://gist.github.com/discover))
  - Externally managed plugins e.g., [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) and [prezto](https://github.com/sorin-ionescu/prezto) plugins/themes
  - Binary artifacts on [GitHub Releases](https://help.github.com/articles/about-releases/)
  - Local plugins
  - etc. (you can add your [own sources](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md)!)
- Super-fast parallel installation/update
- Support for lazy-loading
- Branch/tag/commit support
- Post-update, post-load hooks
- Dependencies between packages
- Unlike [antigen](https://github.com/zsh-users/antigen), no ZSH plugin file (`*.plugin.zsh`) required
- Interactive interface ([fzf](https://github.com/junegunn/fzf), [peco](https://github.com/peco/peco), [zaw](https://github.com/zsh-users/zaw), and so on)
- Cache mechanism for reducing [the startup time](https://github.com/zplug/zplug#vs)

### [zplugin](https://github.com/zdharma/zplugin)

**Zplugin** is an innovative plugin manager with [semigraphical UI](https://github.com/zdharma/zplugin-crasis), [Turbo Mode](https://github.com/zdharma/zplugin#turbo-mode), a clean fpath, reports, completion management and [services](https://github.com/zservices) support.

### [ZPM](https://github.com/zpm-zsh/zpm)

**ZPM** ( ZSH Plugin Manager ) is a plugin manager for [ZSH](http://www.zsh.org/) similar to vim-plug. ZPM plugins are compatible with [oh-my-zsh](http://ohmyz.sh/). ZPM runs on Linux, macOS, FreeBSD and Android.

### [ZR](https://github.com/jedahan/zr)

**ZR** is a quick, simple ZSH plugin manager written in Rust and easily installable with `cargo install zr`.

### [zshing](https://github.com/zakariaGatter/zshing)

**zshing** is a ZSH plugin manager similar to Vundle/Vim and allows you to...

* keep track of and configure your plugins right in the `.zshrc`
* Install Zsh plugins
* Update Zsh plugins
* Search by name all available Zsh Plugins
* Clean unused plugins up
* run the above actions in a *single command*
* manages the __Source Plugins__ of your installed Plugins

### [ztanesh](https://github.com/miohtama/ztanesh)

**Ztanesh** aims to improve your UNIX command line experience and productivity with the the configuration provided by the ztanesh project: the tools will make your shell more powerful and easier to use.

### [zulu](https://github.com/zulu-zsh/zulu)

**Zulu** is a environment manager for ZSH 5+, which aims to make it easy to manage your shell without writing any code.

* Easily manage your shell environment without editing files.
* Create aliases, functions and environment variables, and have them available to you at the next shell startup.
* Add and remove directories from `$path`, `$fpath` and `$cdpath` with simple commands.
* Install packages, plugins and themes easily, and have them available to you immediately.

## Tutorials

### Generic ZSH

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - Tutorial using a combination of [iTerm 2](https://www.iterm2.com/#/section/home), [ZSH](https://en.wikipedia.org/wiki/Z_shell), [Prezto](https://github.com/sorin-ionescu/prezto), [Tmux](https://tmux.github.io), and [Tmuxinator](https://github.com/tmuxinator/tmuxinator) to make for an extremely productive developer workflow.
* [https://commandlinepoweruser.com](https://commandlinepoweruser.com/) - Wes Bos' videos introducing ZSH and oh-my-zsh.
* [https://wiki.archlinux.org/index.php/zsh](https://wiki.archlinux.org/index.php/zsh) - Arch Linux's ZSH introduction. Not Arch or Linux-specific.
* [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) covers some of the features that ZSH has that Bash doesn't, and using oh-my-zsh.
* [The Text Triumvirate](http://www.drbunsen.org/the-text-triumvirate/) - Seth Brown's tutorial on combining ZSH, [tmux](https://tmux.github.io) and vim.
* [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) - slideshare presentation.
* [ZSH Pony](https://github.com/mika/zsh-pony) - Covers customizing ZSH without a framework. :star:98
* [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - An exhaustive list of ZSH tips by Christian Schneider.

### Antigen

* [https://mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) - Michael Maclean's article about switching from oh-my-zsh to antigen.
* [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) - Josh Davis' introduction to Antigen.

### Oh-My-Zsh

* [ZSH Gem 24](https://www.refining-linux.org/archives/59/ZSH-Gem-24-ZSH-frameworks/) - Part of the 2011 ZSH Advent Calendar. Covers oh-my-zsh and zshuery.

### Prezto

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) - Mike Buss' blog post about using Prezto, [Tmux](https://tmux.github.io) & Tmuxinator.
* [Ditching oh-my-zsh for prezto](https://linhmtran168.github.io/blog/2013/12/15/ditching-oh-my-zsh-for-prezto/) - Linh M. Tran's post about transitioning to Prezto from Oh-My-Zsh.
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert's blog post on migrating to Prezto.

### Zgen

* [zsh-quickstart-kit](https://github.com/unixorn/zsh-quickstart-kit) - A simple quickstart for using ZSH with zgen. This includes a curated collection of plugins, and will automatically configure ZSH to use zgen to load them, configures zgen to periodically automatically update itself, the plugins, and the quickstart kit itself. :star:178

## Plugins

* [256color](https://github.com/chrissicool/zsh-256color) - Enhances the terminal environment with 256 colors. It looks at the chosen TERM environment variable and sees if there is respective ncurses' terminfo with 256 colors available. The result is a multicolor terminal, if available. :star:49
* [abbr-path](https://github.com/felixgravila/zsh-abbr-path) - Adds functionality of the `theme_title_use_abbreviated_path` parameter from some oh-my-fish themes.
* [abbrev-alias](https://github.com/momo-lab/zsh-abbrev-alias) - Provides functionality similar to Vim's abbreviation expansion. :star:18
* [accurev-zsh](https://github.com/dalefukami/accurev-zsh) - ZSH plugin for accurev. :star:1
* [alias-tips](https://github.com/djui/alias-tips) - An oh-my-zsh plugin to help remembering those aliases you defined once. :star:290
* [allergen](https://github.com/stanislas/allergen) - A collection of custom ZSH plugins to use with antigen.
* [almostontop](https://github.com/Valiev/almostontop) - Clears previous command output every time before new command executed in shell. Inspired by alwaysontop plugin for bash. :star:43
* [ansible](https://github.com/sparsick/ansible-zsh) - A plugin for Ansible. :star:8
* [ansiweather](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols. :star:1406
* [antigen-git-rebase](https://github.com/smallhadroncollider/antigen-git-rebase) - Antigen/zsh script to aid with Git rebasing. :star:3
* [antigen-git-store](https://github.com/smallhadroncollider-deprecated/antigen-git-store) - Antigen/zsh script to store Git's current working directory. For working with Git between two computers without forcing arbitrary commits. :star:2
* [anyframe](https://github.com/mollifier/anyframe) - A peco/percol/fzf wrapper plugin for ZSH. :star:132
* [apache2](https://github.com/voronkovich/apache2.plugin.zsh) - Adds aliases and functions for managing Apache2. :star:2
* [app-up](https://github.com/Cloudstek/zsh-plugin-appup) - Adds start, stop, up and down commands when it detects a docker-compose or Vagrant file in the current directory (e.g. your application). Just run up and get coding!
* [apple-touchbar](https://github.com/zsh-users/zsh-apple-touchbar) - Adds MacBook Pro's touchbar support in [iTerm 2](https://iterm2.com). :star:67
* [appup](https://github.com/Cloudstek/zsh-plugin-appup) - Adds `start`, `stop`, `up` and `down` commands when it detects a docker-compose or Vagrant file in the current directory (e.g. your application). Just run `up` and get coding!
* [asciidoctor](https://github.com/sparsick/asciidoctor-zsh) - A plugin for AsciiDoctor. :star:1
* [async](https://github.com/mafredri/zsh-async) - Library for running asynchronous tasks in ZSH without requiring any external tools. Allows you to run multiple asynchronous jobs, enforce unique jobs (multiple instances of the same job will not run), flush all currently running jobs and create multiple workers (each with their own jobs). :star:261
* [atom-plugin](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) - A plugin for Oh My Zsh that lets you launch a file or folder in [Atom](https://atom.io) from [iTerm 2](https://iterm2.com). It's based on the Sublime plugin. Only supports macOS. :star:2
* [atom](https://github.com/kingsj/atom_plugin.zsh) - A plugin for the Atom editor on macOS. :star:1
* [auto-color-ls](https://github.com/gretzky/auto-color-ls) - Automatically list directories with `colorls`. :star:3
* [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh) - Automatic complete-word and list-choices. Originally incr-0.2.zsh by y.fujii <y-fujii at mimosa-pudica.net>. :star:367
* [auto-ls](https://github.com/desyncr/auto-ls) - Automatically `ls` when cding to a new directory. :star:29
* [autoenv-extended](https://github.com/zpm-zsh/autoenv) - Extended version of the zsh-autoenv plugin. :star:71
* [autoenv](https://github.com/Tarrasch/zsh-autoenv) - If a directory contains a `.env` file, it will automatically be executed when you cd into it. :star:337
* [autojump](https://github.com/wting/autojump) - A cd command that learns - easily navigate directories from the command line. Install autojump-zsh for best results. :star:8220
* [autopair](https://github.com/hlissner/zsh-autopair) - A ZSH plugin for auto-closing, deleting and skipping over matching delimiters. Only tested on ZSH 5.0.2 or later. :star:90
* [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)-like fast/unobtrusive autosuggestions for ZSH. :star:7072
* [autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv) - ZSH plugin to automatically switch python virtualenvs when traversing directories. :star:62
* [autoupdate-antigen.zshplugin](https://github.com/unixorn/autoupdate-antigen.zshplugin) - Antigen doesn't do automatic updates like oh-my-zsh. This plugin adds auto updating for antigen, both of antigen and the bundles loaded in your configuration. :star:19
* [autoupdate-oh-my-zsh-plugins](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) - oh-my-zsh doesn't autoupdate non-core plugins, this adds plugin autoupdating to omz. :star:1
* [aws-upload-zsh](https://github.com/borracciaBlu/aws-upload-zsh) - Boost your productivity with aws-upload.
* [aws-vault](https://github.com/blimmer/zsh-aws-vault) - Plugin for [aws-vault](https://github.com/99designs/aws-vault). :star:11
* [base16](https://github.com/chriskempson/base16-shell) - Adds script to allow you to change your shell's default ANSI colors but most importantly, colors 17 to 21 of your shell's 256 colorspace (if supported by your terminal). This script makes it possible to honor the original bright colors of your shell (e.g. bright green is still green and so on) while providing additional base16 colors to applications such as [Vim](https://www.vim.org). :star:1059
* [basex](https://github.com/dirkk/zsh-basex) - Adds several [BaseX](http://basex.org/) aliases for simplified usage. :star:2
* [bash](https://github.com/chrissicool/zsh-bash) - Makes ZSH more Bash compatible. It redefines the source command to act more like Bash does. It also enables Bash completions. :star:15
* [battery_state](https://github.com/Jactry/zsh_battery_state) - Show battery state in right-prompt. :star:2
* [bd](https://github.com/Tarrasch/zsh-bd) - Jump back to a specific directory, without doing `cd ../../..`. :star:265
* [bepoptimist](https://github.com/sheoak/zsh-bepoptimist) - Remap ZSH vi-mode for French [bépo keyboard](http://bepo.fr/wiki/Accueil). :star:1
* [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin) - Add more command aliases for `brew` :star:1
* [bitbucket-git-helpers](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) - Adds helper scripts to allow you to create bitbucket PRs or open a directory in the current branch. :star:11
* [blackbox](https://github.com/StackExchange/blackbox) - Stack Exchange's toolkit for storing keys/credentials securely in a git repository. :star:4447
* [branch-manager](https://github.com/elstgav/branch-manager) - A plugin for managing git branches. :star:7
* [browse-commit](https://github.com/adolfoabegg/browse-commit) - A plugin that lets you open any commit in your browser from the command line. :star:14
* [bumblebee](https://github.com/Niverton/zsh-bumblebee-plugin) - A plugin to toggle optirun in the command line.
* [calc](https://github.com/arzzen/calc.plugin.zsh) - A calculator for ZSH. :star:55
* [caniuse](https://github.com/walesmd/caniuse.plugin.zsh) - Add [Can I Use...](https://caniuse.com) support to ZSH. :star:15
* [careful_rm](https://github.com/MikeDacre/careful_rm) - A wrapper for rm that adds trash/recycling and useful warnings :star:4
* [cd-gitroot](https://github.com/mollifier/cd-gitroot) - A ZSH plugin to cd to the git repository root directory. :star:31
* [cd-reporoot](https://github.com/P4Cu/cd-reporoot) - A ZSH plugin to cd to the google-repo repository root directory.
* [cd-ssh](https://github.com/jeffwalter/zsh-plugin-cd-ssh) - `ssh` to a server when you accidentally `cd` to it.
* [cdbk](https://github.com/MikeDacre/cdbk) - A ZSH plugin to allow easy named directory creation - shortcuts to any directory you want. :star:7
* [cdr](https://github.com/willghatch/zsh-cdr) - Easy setup of cdr for ZSH. :star:7
* [change-case](https://github.com/mtxr/zsh-change-case) - Plugin for fast swap between upper and lower case in your command line. :sunglasses: :star:3
* [clean-project](https://github.com/wwilsman/zsh-clean-project) - Remove files from projects (automatically by default). Useful for keeping `.DS_Store` and `Thumbs.db` files from cluttering your directories. :star:6
* [cmd-architect](https://github.com/psprint/zsh-cmd-architect) - Build commands from what's in history and at prompt, move, delete, add command segments and search history with multi-word queries. :star:47
* [colored-man-pages-mod](https://github.com/zuxfoucault/colored-man-pages_mod) - Forked from [robbyrussell/oh-my-zsh/plugins/colored-man-pages](https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh). Colorizes `man` output. :star:3
* [colored-man-pages](https://github.com/ael-code/zsh-colored-man-pages) - Colorize man pages. :star:7
* [colors (Tarrasch)](https://github.com/Tarrasch/zsh-colors) - Makes it easier to colorize text from the CLI. `red foo` just works. :star:35
* [colors (zpm-zsh)](https://github.com/zpm-zsh/colors) - Colorize output of various programs.
* [command-not-found](https://github.com/Tarrasch/zsh-command-not-found) - mirror of the oh-my-zsh command-not-found plugin so you don't have to include all of omz. :star:13
* [command-time](https://github.com/popstas/zsh-command-time) - Show execution time for long commands in ZSH and [powerlevel9k](https://github.com/bhilburn/powerlevel9k). :star:33
* [completion-generator](https://github.com/RobSis/zsh-completion-generator) - This plugin tries to read the list of options from the help text of programs and generate a completion function automatically. Note that this doesn't do it automatically, you have to explicitly call the generator to create a completion script. :star:94
* [copyzshell](https://github.com/rutchkiwi/copyzshell) - A ZSH plugin to copy your shell configuration to another machine over `ssh`. :star:25
* [crash](https://github.com/molovo/crash) - Adds proper error handling, exceptions and try/catch for ZSH. :star:21
* [crayon-syntax-zsh](https://github.com/gsemet/crayon-syntax-zsh) - ZSH syntax highlighting for the Crayon Plugin for Wordpress.
* [crypto-prices](https://github.com/vincentdnl/zsh-crypto-prices) - Add a [powerlevel9k](https://github.com/bhilburn/powerlevel9k) segment with the current bitcoin price. :star:4
* [crystal](https://github.com/veelenga/crystal-zsh) - A plugin for [Crystal](https://github.com/crystal-lang/crystal). :star:19
* [czhttpd](https://github.com/jsks/czhttpd) - A simple http server written in 99.9% pure ZSH. :star:30
* [deer](https://github.com/Vifon/deer) - A file navigator for ZSH heavily inspired by [ranger](https://ranger.github.io/). :star:230
* [depot-tools](https://github.com/kuoe0/zsh-depot-tools) - Simple oh-my-zsh plugin for installing the chromium depot_tools. Installing this plugin will put all of the chromium depot_tools in your path automatically.
* [diff-so-fancy](https://github.com/zdharma/zsh-diff-so-fancy) - Simplify installing the `diff-so-fancy` project into your user account. :star:11
* [diractions](https://github.com/AdrieanKhisbe/diractions) - Allow you to map a short logical/mnemonic name to directories to quickly access them, or perform actions in them. :star:16
* [dircolors-solarized](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors plugin. :star:45
* [dircycle](https://github.com/michaelxmcbride/zsh-dircycle) - Cycle through the directory stack. :star:6
* [directory-history](https://github.com/tymm/zsh-directory-history) - A per directory history for ZSH. :star:88
* [dirrc](https://github.com/gmatheu/shell-plugins) - Executes `.dirc` when present in a directory you `cd` into. :star:2
* [dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) - Plugin for displaying dirstack info on a single line. :star:1
* [docker-aliases](https://github.com/webyneter/docker-aliases) Docker aliases for everyday use.
* [docker-compose](https://github.com/sroze/docker-compose-zsh-plugin) Show docker container status in your prompt.
* [docker-helpers](https://github.com/unixorn/docker-helpers.zshplugin) - A collection of docker helper scripts. :star:16
* [docker-machine](https://github.com/asuran/zsh-docker-machine) - A docker-machine plugin for ZSH. :star:1
* [docker-run](https://github.com/rawkode/zsh-docker-run) - Go back to running your commands "naturally", we'll handle the container. :star:22
* [dogesh](https://github.com/keithhamilton/oh-my-dogesh) - Dogification plugin. :star:5
* [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) - If you have a `.pyvenv` virtualenv, will automagically switches to it. :star:1
* [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands. :star:15
* [dune-quotes](https://github.com/brokendisk/dune-quotes) - Random Dune quote generator plugin. :star:3
* [dwim](https://github.com/oknowton/zsh-dwim) - zsh-dwim attempts to predict what you will want to do next. It provides a key binding (control-u) that will replace the current (or previous) command line with the command you will want to run next. :star:70
* [ec2ssh](https://github.com/h3poteto/zsh-ec2ssh) - List EC2 instances and `ssh` login to the instances easily. :star:6
* [editing-workbench](https://github.com/psprint/zsh-editing-workbench) - Adds sane, complex command line editing (e.g. incremental history _word_ completion). :star:26
* [elixir-oh-my-zsh](https://github.com/gusaiani/elixir-oh-my-zsh) - Adds shortcuts for Elixir, IEX, Mix, Kiex and Phoenix. :star:103
* [emoji-cli](https://github.com/b4b4r07/emoji-cli) - :scream: Emoji completion on the command line. :star:225
* [emojis](https://github.com/MichaelAquilina/zsh-emojis) - Adds numerous ascii art emojis to your environment in convenient variables. :star:9
* [enhancd](https://github.com/b4b4r07/enhancd) - A simple tool that provides enhanced `cd` command. :star:936
* [escape-backtick](https://github.com/bezhermoso/zsh-escape-backtick) - Quickly insert escaped backticks when double-tapping "`". :star:1
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - A plugin for [exercism.io](http://exercism.io/). :star:5
* [expand-ealias](https://github.com/zigius/expand-ealias.plugin.zsh) - Expand specific aliases with space. :star:8
* [explain-shell](https://github.com/gmatheu/shell-plugins) - Opens commands on [explainshell.com](https://explainshell.com). :star:2
* [extend-history](https://github.com/xav-b/zsh-extend-history) - Extends command history by adding exit code for each command in the history. :star:2
* [fancy-ctrl-z](https://github.com/mdumitru/fancy-ctrl-z) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of OMZ. :star:3
* [fast-syntax-highlighting](https://github.com/zdharma/fast-syntax-highlighting) - Optimized an improved `zsh-users/zsh-syntax-highlighting` – better response times, `zed/vared` can edit `10 kB` functions. :star:332
* [favorite-directories](https://github.com/seletskiy/zsh-favorite-directories) - Fast jumps to your favorite directories. :star:6
* [firebase-zsh](https://github.com/rmrs/firebase-zsh) - Add an indicator in the prompt that you're in a directory with a `firebase.json` file (aka "firebase project"). :star:2
* [fixnumpad-osx](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh/blob/master/fixnumpad-osx.plugin.zsh) - Enables numpad keys of Apple keyboards to be recognized in ZSH. :star:3
* [flow-plugin](https://github.com/sandstorm/oh-my-zsh-flow-plugin) - This plugin makes the flow command available inside every subdirectory of the TYPO3 Flow distribution. :star:38
* [forgit](https://github.com/wfxr/forgit) - Utility tool for git taking advantage of fuzzy finder [fzf](https://github.com/junegunn/fzf). :star:69
* [functional](https://github.com/Tarrasch/zsh-functional) - ZSH higher order functions. :star:88
* [fuzzy-search-and-edit](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) - ZSH plugin for fuzzy searching files and instantly opening a matched file on matched line. :star:16
* [fz](https://github.com/changyuheng/fz) - Seamlessly adds fuzzy search to [z](https://github.com/rupa/z)'s tab completion and lets you easily jump around among your historical directories. :star:183
* [fzf-finder](https://github.com/leophys/zsh-plugin-fzf-finder) - Plugin to have a cool search keybinding with [fzf](https://github.com/junegunn/fzf) and (optionally) [bat](https://github.com/sharkdp/bat). :star:1
* [fzf-marks](https://github.com/urbainvaes/fzf-marks) - Little script to create, navigate and delete bookmarks in Bash and Zsh, using the fuzzy finder [fzf](https://github.com/junegunn/fzf). :star:184
* [fzf-mpd](https://github.com/anders-dc/fzf-mpd/) - A ZSH plugin that allows you to control [mpd](https://www.musicpd.org/) using [fzf](https://github.com/junegunn/fzf). :star:1
* [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) - Adds some ZLE widgets for [fzf](https://github.com/junegunn/fzf). :star:36
* [fzf-z](https://github.com/andrewferrier/fzf-z) - Brings together the *z* plugin and *fzf* to allow you to easily browse recently used directories at any point on the command line. :star:38
* [fzy](https://github.com/aperezdc/zsh-fzy) - Plugin that uses [fzy](https://github.com/jhawthorn/fzy) for certain fuzzy matching operations. :star:17
* [geeknote](https://github.com/s7anley/zsh-geeknote) - Geeknote plugin for ZSH. :star:12
* [geometry-datetime](https://github.com/desyncr/geometry-datetime) - [Geometry](https://github.com/geometry-zsh/geometry) datetime plugin. Shows datetime (`date` unix command) in your prompt.
* [geometry-hydrate](https://github.com/jedahan/geometry-hydrate) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to remind you to hydrate.
* [geometry-npm-package-version](https://github.com/drager/geometry-npm-package-version) - Geometry plugin to display the current folder's npm package version. :star:1
* [geometry-rust-version](https://github.com/drager/geometry-rust-version) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to display the current folder's Rust version when either a `.rs` or `Cargo.toml` is present. :star:1
* [get-jquery](https://github.com/voronkovich/get-jquery.plugin.zsh) - Plugin for fast downloading jQuery library from [code.jquery.com](code.jquery.com). :star:1
* [ghost-zeus](https://github.com/fontno/ghost_zeus) - Lets you use zeus with normal rails commands. :star:3
* [gimme](https://github.com/folixg/gimme-ohmyzsh-plugin) - Manage Go installations with gimme. :star:1
* [git-add-remote](https://github.com/caarlos0/git-add-remote) - Easily add the upstream remote to your git fork. :star:9
* [git-aliases (mdumitru)](https://github.com/mdumitru/git-aliases) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of OMZ. :star:4
* [git-aliases.zsh](https://github.com/peterhurford/git-aliases.zsh) - Creates a lot of useful aliases for combinations of commonly used git commands. :star:40
* [git-complete-urls](https://github.com/rapgenic/zsh-git-complete-urls) - enhance git completion to include in the remotes completion (e.g. from `git clone`) any URL in the clipboard.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - Extra git helper scripts packaged as a plugin. :star:344
* [git-it-on.zsh](https://github.com/peterhurford/git-it-on.zsh) - Adds ability to open a folder in your current branch on GitHub. :star:59
* [git-plugin](https://github.com/rcruzper/zsh-git-plugin) - Adds some functions for git. :star:2
* [git-prompt-useremail](https://github.com/mroth/git-prompt-useremail) - Adds prompt reminders for git user.email. :star:1
* [git-prune](https://github.com/Seinh/git-prune) - Plugin that simplifies deleting merged branches. :star:25
* [git-scripts](https://github.com/packruler/zsh-git-scripts) - Adds `git-squash-branch` and `git-remove-merged` commands. :star:1
* [git-secret](https://github.com/sobolevn/git-secret) - A bash-tool to store your private data inside a git repository. :star:1086
* [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) - Adds git commands to make some common git usages more efficient. :star:6
* [git-sync](https://github.com/caarlos0/zsh-git-sync) - A ZSH plugin to sync git repositories and clean them up. :star:20
* [gitfast](https://github.com/tevren/gitfast-zsh-plugin) - Updated fork of oh-my-zsh gitfast plugin. :star:6
* [gitgo](https://github.com/ltj/gitgo) - Open a Github/Gitlab repository in your browser from the command line (macOS only). :star:1
* [gitignore](https://github.com/voronkovich/gitignore.plugin.zsh) - Plugin for creating `.gitignore` files. :star:27
* [gitio-zsh](https://github.com/denysdovhan/gitio-zsh) - A ZSH plugin for generating a GitHub short URL using [git.io](https://git.io). :star:14
* [gitsync](https://github.com/washtubs/gitsync) - ZSH plugin to improve workflows for one person developing on the same repository on multiple machines. :star:2
* [goenv](https://github.com/bbenne10/goenv) - Antigen plugin to manage `$GOPATH` similarly to Python's virtualenvwrapper. :star:6
* [going_places](https://github.com/or17191/going_places) - A plugin that helps to use, create and maintain a list of shell locations.
* [gpg-agent](https://github.com/axtl/gpg-agent.zsh) - Plugin that tries to do the right thing when it comes to setting up the GPG agent to act as an SSH agent as well on macOS. :star:6
* [gpg-crypt](https://github.com/Czocher/gpg-crypt) - ZSH plugin to encrypt/decrypt files or directories in place. :star:2
* [grep2awk](https://github.com/joepvd/grep2awk) - ZLE widget to transform grep command into awk command. :star:14
* [grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) - Add autocompletion for grunt. :star:8
* [gtm-terminal-plugin](https://github.com/git-time-metric/gtm-terminal-plugin) - terminal plugin for [git time metrics](https://github.com/git-time-metric/gtm/blob/master/README.md). :star:9
* [gvm (dgnest)](https://github.com/dgnest/zsh-gvm-plugin) - gvm (Go version manager) plugin for ZSH. :star:3
* [gvm (yerinle)](https://github.com/yerinle/zsh-gvm) - Provides autocompletion for gvm (Groovy enVironment Manager). :star:1
* [hacker-quotes](https://github.com/oldratlee/hacker-quotes) - Outputs a hacker quote randomly when you open a terminal. :star:28
* [hadoop-plugin](https://github.com/valek/zsh-hadoop-plugin) - Adds some convenience aliases for hadoop functions.
* [hanami-zsh](https://github.com/davydovanton/hanami-zsh) - ZSH plugin for [hanami](http://hanamirb.org) projects. :star:7
* [hints](https://github.com/joepvd/zsh-hints) - Display glob and parameter flags and other non completable info right under your editing buffer. :star:31
* [hipchat](https://github.com/robertzk/hipchat.zsh) - Send hipchat messages from the shell. :star:15
* [histdb](https://github.com/larkery/zsh-histdb) - Stores your history in an SQLite database. :star:467
* [history-search-multi-word](https://github.com/zdharma/history-search-multi-word) - syntax highlighted, multi-word history searcher for ZSH, bound to Ctrl-R, with advanced functions (e.g. bump of history entry to top of history). :star:124
* [history-substring-search](https://github.com/zsh-users/zsh-history-substring-search) - Needs to be loaded after zsh-syntax-highlighting, or they'll both break. You'll also need to bind keys to its functions, details are in the README.md. :star:825
* [history-sync](https://github.com/wulfgarpro/history-sync) - An Oh My Zsh plugin for GPG encrypted, Internet synchronized ZSH history using Git. :star:47
* [history](https://github.com/b4b4r07/zsh-history) - Extend history so that it can be queried by SQL. :star:61
* [hooks](https://github.com/willghatch/zsh-hooks) - Add missing hooks - for plugins and personal use. :star:25
* [host-switch](https://github.com/LockonS/host-switch) - Make it easier to switch in different `/etc/hosts` files during development. :star:2
* [hub-ci-zsh-plugin](https://github.com/raymondjcox/hub-ci-zsh-plugin) - A simple plugin for adding hub ci-status to your ZSH theme.
* [ing](https://github.com/rummik/zsh-ing) - `ping`, but shorter output. :star:2
* [intellij](https://github.com/mgryszko/intellij) - Extract intellij bookmarks into markdown format.
* [interactive-cd](https://github.com/changyuheng/zsh-interactive-cd) - Fish-like interactive tab completion for `cd`. :star:111
* [iosctl](https://github.com/obayer/iosctl) - Quickly access App, Data, and Log of the running simulator. :star:2
* [iterm-tab-color](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) - Adds function to set the tab color in iTerm2 :star:8
* [iterm-tab-colors](https://github.com/tysonwolker/iterm-tab-colors) - Automatically changes iTerm 2 tab color based on the current working directory. :star:20
* [iterm-touchbar](https://github.com/iam4x/zsh-iterm-touchbar) - Display iTerm2 feedback in the MacbookPro TouchBar (Current directory, git branch & status). :star:400
* [iterm2-colors](https://github.com/shayneholmes/zsh-iterm2colors) - Manage your iTerm 2's color scheme from the command line. :star:2
* [iterm2-tabs](https://github.com/gimbo/iterm2-tabs.zsh) - Set colors and titles of iTerm 2 tabs. :star:1
* [jabba](https://github.com/2m/zsh-jabba) - Adds shell integration code and completions for the [jabba](https://github.com/shyiko/jabba) Java version manager. :star:1
* [javaVersions](https://github.com/miguefl/javaVersions) - Change between different java versions with a single command.
* [java-zsh-plugin](https://github.com/Xetius/java-zsh-plugin) - Adds a `setjdk` command so you can switch easily between different versions of the jdk.
* [jdk-switch](https://github.com/LockonS/jdk-switch) - macOS-only plugin for switching between jdk versions. :star:1
* [jenkins-zsh](https://github.com/tomplex/jenkins-zsh) - A jenkins plugin for ZSH, heavily inspired by the excellent jira plugin. :star:3
* [jhipster](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) - Adds commands for [jHipster](https://www.jhipster.tech/). :star:25
* [jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) - Create JIRAs from the command line. :star:4
* [jvm](https://github.com/mgryszko/jvm) - Allows selection of JDK on macOS. :star:4
* [k](https://github.com/supercrabtree/k) - Directory listings for ZSH with git features. :star:973
* [kill-node](https://github.com/vmattos/kill-node) - ZSH plugin for murdering node process families. :star:6
* [kitsunebook](https://github.com/d12frosted/kitsunebook.plugin.zsh) - KitsuneBook plugin for oh-my-zsh.
* [konsole-theme-changer](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - Toggle konsole theme from ZSH.
* [kube-ps1](https://github.com/jonmosco/kube-ps1) - ZSH plugin for kubectl that adds current context and namespace. :star:554
* [kubectl-zsh-plugin](https://github.com/mattbangert/kubectl-zsh-plugin) - ZSH plugin for managing kubectl. :star:3
* [kubernetes](https://github.com/Dbz/zsh-kubernetes) - Add kubernetes helper functions and aliases. :star:15
* [laradock-workspace](https://github.com/rluders/laradock-workspace-zsh) - Provides an interface to [Laradock](http://laradock.io/)'s workspace.
* [laravel](https://github.com/crazybooot/laravel-zsh-plugin) - Add shortcuts for Laravel 5, 5.1, 5.2 & 5.3. :star:7
* [last-working-directory (mdumitru)](https://github.com/mdumitru/last-working-dir) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of OMZ. :star:2
* [lesaint-git](https://github.com/lesaint/lesaint-git) - Replacement git plugin for Oh-My-Zsh-compatible frameworks.
* [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) - Maven plugins for Oh-My-Zsh.
* [linuxbrew](https://github.com/zpm-zsh/linuxbrew) - Zsh plugin for [linuxbrew](http://linuxbrew.sh/). :star:2
* [listbox](https://github.com/gko/listbox) - Listbox element for shell. :star:27
* [locate-sublime-projects-cli](https://github.com/david-treblig/locate-sublime-projects-cli) - Allows searching for Sublime Text projects and opens them in Sublime.
* [loremipsum](https://github.com/pfahlr/zsh_plugin_loremipsum) - Generate lorem ipsum text on the command line. Gets data from lipsum.com.
* [ls](https://github.com/zpm-zsh/ls) - Colorizes the output of `ls`. :star:1
* [lumberjack](https://github.com/molovo/lumberjack) - Lumberjack is a logging interface for shell scripts. :star:20
* [mac-packaging](https://github.com/Temikus/mac-packaging) - A set of common functions used for enterprise Mac packaging with Munki. :star:1
* [macos](https://github.com/joow/macos) - A ZSH plugin for macOS. :star:1
* [mage2docker](https://github.com/lukaszolszewski/mage2docker) - Makes it easy to work with Docker and Magento 2. Speeds up and simplifies common commands like clean cache, setup upgrade, compile di and much more in Magento 2 on containers. :star:7
* [manydots-magic](https://github.com/knu/zsh-manydots-magic) - A zle tweak for emulating `...'==`../..' etc. :star:22
* [markedit](https://github.com/zakariaGatter/MarkEdit) - Mark Files and Edit them With Autocompletion for existing Marks. :star:2
* [markgate](https://github.com/zakariaGatter/MarkGate) - Allows you to mark directories so you can jump directly to them. :star:2
* [maven-plugin](https://github.com/KyleChamberlin/zsh_maven_plugin) - A fork of the oh-my-zsh maven plugin.
* [mercurial](https://github.com/hcgraf/zsh-mercurial) - Extracted from oh-my-zsh so you can use it without oh-my-zsh. :star:2
* [mfunc](https://github.com/hlohm/mfunc) - Allows you to define persistent functions on-the-fly, without the need to add them to your config files. These functions are permanently available until you delete them. :star:4
* [mode-switch.CLI](https://github.com/Gyumeijie/mode-switch.CLI) - A ZSH plugin for switching command line between normal mode and vi mode. :star:1
* [monorepo-plugin](https://github.com/zilongqiu/monorepo-zsh-plugin) - ZSH plugin for monorepo management. :star:2
* [morpho](https://github.com/psprint/zsh-morpho) - Terminal screen savers written in pure ZSH, and also screen saver framework. :star:9
* [msf](https://github.com/sathish09/zsh_plugins/tree/master/msf) - Metasploit handler plugin for starting handler easily. :star:12
* [mylocation](https://github.com/fALKENdk/mylocation) - A plugin to show your current location based on your IP address. :star:5
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) - Colors for mysql tables. :star:52
* [mysql](https://github.com/voronkovich/mysql.plugin.zsh) - Adds some functions for dealing with mysql. :star:11
* [n](https://github.com/gretzky/n.zsh) - Auto-switches node versions based on project environment using [n](https://github.com/tj/n).
* [navigation-tools](https://github.com/psprint/zsh-navigation-tools) - Adds `htop`-like `kill`, directory bookmarks browser, multi-word incremental history searcher and more. :star:183
* [nice-exit-code](https://github.com/bric3/nice-exit-code) - Maps exit status code to human readable string. :star:21
* [nix-shell](https://github.com/chisui/zsh-nix-shell) - Plugin that lets you use ZSH as the default `nix-shell` shell. :star:34
* [node](https://github.com/srijanshetty/node.plugin.zsh) - Srijan Shetty's nodejs plugin for ZSH with caching of nvm completions and autoloading of nvm if present. :star:6
* [nodenv](https://github.com/jsahlen/nodenv.plugin.zsh) - Auto-load nodenv and its completions into the shell.
* [nohup](https://github.com/micrenda/zsh-nohup) - Add `nohup` to the current command pressing `Ctrl-H`. :star:1
* [noreallyjustfuckingstopalready](https://github.com/eventi/noreallyjustfuckingstopalready) - macOS users know the pain of trying to figure out what command actually flushes the DNS cache on their version of macOS, and this plugin makes that annoyance go away. :star:278
* [notes](https://github.com/chipsenkbeil/zsh-notes) - Provides a quick notes editing experience in ZSH. :star:1
* [notify](https://github.com/marzocchi/zsh-notify) - A plugin for ZSH (on macOS and Linux) that posts desktop notifications when a command terminates with a non-zero exit status or when it took more than 30 seconds to complete, if the terminal application is in the background (or the command's terminal tab is inactive). :star:260
* [nvm-auto-use](https://github.com/tomsquest/nvm-auto-use.zsh) - calls `nvm use` automatically whenever you enter a directory that contains an `.nvmrc` file with a string telling nvm which node to use. :star:8
* [nvm-auto](https://github.com/dijitalmunky/nvm-auto) - Aims to alleviate needing to type `nvm use` as much as possible, especially if you often switch between versions of node.js and use `.nvmrc` files in your project to manage what version of node your project needs. :star:26
* [nvm](https://github.com/lukechilds/zsh-nvm) - ZSH plugin for installing, updating and loading nvm. :star:605
* [oh-my-matrix](https://github.com/amstrad/oh-my-matrix) - Turn your terminal into the matrix. :star:1
* [open-create-projects](https://github.com/marcossegovia/open-create-projects) - Open/Create projects in Jetbrains. :star:1
* [open-pr](https://github.com/caarlos0/zsh-open-pr) - A ZSH plugin to open pull requests from command line. :star:37
* [openshift-origin](https://github.com/ryanswart/openshift-origin-zsh-plugin) - Add a few shortcuts to common openshift origin (oc) actions.
* [opera-git-plugin](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) - Git aliases.
* [operator](https://github.com/nivv/operator-theme) - Clean and simple theme, works best with Menlo for Powerline. :star:1
* [opp.zsh](https://github.com/hchbaw/opp.zsh) - Vim's text-objects-ish for ZSH. :star:225
* [opt-path](https://github.com/jreese/zsh-opt-path) - Automatically add `~/opt` subpaths to your `$PATH`. :star:5
* [osx-dev](https://github.com/marshallmick007/osx-dev-zsh-plugin) - This plugin adds some commands for maintaining various server programs on my macOS install. :star:10
* [osx](https://github.com/mwilliammyers/plugin-osx) - Add some common macOS related aliases and functions. :star:12
* [paci](https://github.com/iloginow/zsh-paci) - Plugin for archlinux package managers.
* [pantheon-terminal-notify](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin) - Background notifications for long running commands. Supports Elementary OS Freya. :star:10
* [pctl](https://github.com/ytet5uy4/pctl) - Toggle the environment variables for proxying. :star:5
* [peco-history](https://github.com/jimeh/zsh-peco-history) - Search shell history with Peco when pressing ctrl+r. :star:32
* [percol](https://github.com/robturtle/percol.plugin.zsh) - Interactively and incrementally search history/resume background jobs. :star:4
* [pg](https://github.com/caarlos0-graveyard/zsh-pg) - Adds utility functions to work with PosgreSQL. :star:13
* [phpcs](https://github.com/voronkovich/phpcs.plugin.zsh) - Plugin for [PHP code sniffer](https://github.com/squizlabs/PHP_CodeSniffer). :star:3
* [phpunit](https://github.com/voronkovich/phpunit.plugin.zsh) - Plugin for [PHPUnit](https://phpunit.de/). :star:4
* [pip-app](https://github.com/sharat87/pip-app) - Makes it easy to install python applications into distinct virtualenvs so they don't conflict with any other python requirements on your system. :star:27
* [plugin-ibtool](https://github.com/rgalite/zsh-plugin-ibtool) - Adds ibtool shortcuts to generate localized XIB files. :star:1
* [plugin-rails](https://github.com/paraqles/zsh-plugin-rails) - ZSH plugin for Rails. :star:2
* [plugin-vscode](https://github.com/wuotr/zsh-plugin-vscode) - Plugin for Visual Studio Code, a text editor for macOS, Windows, and Linux. :star:11
* [plugin](https://github.com/darrenbutcher/plugin) - Creates custom oh-my-zsh plugins from a boilerplate template. Very oh-my-zsh centric, the generated plugins will need editing to work with other frameworks. :star:4
* [pretty-time-zsh](https://github.com/sindresorhus/pretty-time-zsh) - Convert seconds to a human readable string: 165392 → 1d 21h 56m 32s. :star:32
* [profile-secrets](https://github.com/gmatheu/shell-plugins) - Securely keep sensitive variables (api tokens, passwords, etc) as part of your terminal init files. Uses gpg to encrypt/decrypt the file with your secrets. :star:2
* [project (gko)](https://github.com/gko/project) - Create node/python/ruby project both locally and on github(private or public repository). :star:8
* [project (voronkovich)](https://github.com/voronkovich/project.plugin.zsh) - Plugin for managing projects. :star:1
* [proxy-plugin](https://github.com/escalate/oh-my-zsh-proxy-plugin) - Aliases to manage proxy shell environment settings. :star:4
* [purs](https://github.com/xcambar/purs) - A [Pure](https://github.com/sindresorhus/pure)-inspired prompt in [Rust](https://www.rust-lang.org/). :star:118
* [pyenv-lazy-load](https://github.com/erikced/zsh-pyenv-lazy-load) - Plugin for lazy-loading pyenv in ZSH. :star:2
* [pyenv-lazy](https://github.com/davidparsson/zsh-pyenv-lazy) - Lazy load pyenv. The initial `eval "$(pyenv init -)"` is executed the first time pyenv is called. :star:1
* [q (cal2195)](https://github.com/cal2195/q) - Vim-like macro registers for your ZSH shell. :star:22
* [q (tomsquest)](https://github.com/tomsquest/q.plugin.zsh) - Tail/remove the temp file for [Q](https://github.com/y0ssar1an/q), the Dirty Debugging Tool.
* [quoter](https://github.com/pxgamer/quoter-zsh) - Display a random quote when opening a new terminal session. :star:3
* [randeme](https://github.com/ex-surreal/randeme) - Chooses a random theme for each session. If you not like the chosen theme you can run `randeme_rm` to never show that theme again. :star:2
* [razer-status-code](https://github.com/michaelmcallister/razer-status-code) - change the colour of your [Razer Mouse](https://openrazer.github.io/) based on the status of the last executed command. Requires OpenRazer linux drivers. :star:1
* [rbenv (ELLIOTTCABLE)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) - A faster fork of the rbenv plugin from oh-my-zsh.
* [rbenv (jsahlen)](https://github.com/jsahlen/rbenv.plugin.zsh) - Variant based on the original oh-my-zsh rbenv plugin.
* [redis](https://github.com/zservices/redis) - Will run `redis-server` pointing it to the `redis.conf` configuration file. This can be used with the [zdharma/zredis](https://github.com/zdharma/zredis) plugin to share variables between shells. :star:2
* [reentry-hook](https://github.com/RobSis/zsh-reentry-hook) - Plugin that re-enters working directory if it has been removed and re-created. :star:4
* [reminder](https://github.com/AlexisBRENON/oh-my-zsh-reminder) - A plugin which displays reminders above every prompt. :star:17
* [revolver](https://github.com/molovo/revolver) - A progress spinner for ZSH scripts. :star:56
* [ripz](https://github.com/jedahan/ripz) - Reminds you of your aliases, so you use them more. Depends on [ripgrep](https://github.com/BurntSushi/ripgrep). :star:14
* [robo-zsh-plugin](https://github.com/shengyou/robo-zsh-plugin) - A ZSH plugin for [Robo](https://robo.li/). :star:3
* [rockz](https://github.com/aperezdc/rockz) - Lua + LuaRocks virtual environment manager based upon VirtualZ. :star:6
* [ruby-switch](https://github.com/LockonS/ruby-switch) - Switch ruby versions and manage the PATH variable at the same time.
* [rvm-zsh](https://github.com/johnhamelink/rvm-zsh) - Initiates RVM and adds rubygem binaries (like compass) accessible in the user's `$PATH`. :star:1
* [safe-paste](https://github.com/oz/safe-paste) - A safe-paste plugin. See Conrad Irwin's [bracketed-paste](https://cirw.in/blog/bracketed-paste) blog post. :star:8
* [saneopt](https://github.com/willghatch/zsh-saneopt) - Sane defaults for ZSH options, in the spirit of vim-sensible. :star:8
* [schroot](https://github.com/fshp/schroot.plugin.zsh) - Show current chroot name in your prompt.
* [select](https://github.com/psprint/zsh-select) - Multi-term searched selection list with approximate matching and uniq mode. :star:7
* [send.zsh](https://github.com/robertzk/send.zsh) - Single command to git add, git commit, and git push for much faster git workflow. :star:11
* [sensei-git](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) - Adds many git aliases and helper shell functions. :star:3
* [setenv](https://github.com/kalpakrg/setenv) - Runs a script when you change directories. :star:3
* [simple-agnoster](https://github.com/iwat/simple-agnoster.zsh-theme) - Powerline-inspired simple theme with git decorations. :star:1
* [simpleserver](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) - Plugin to easily start python SimpleHTTPServer and SimpleHTTPSServer. :star:12
* [smart-cd](https://github.com/dbkaplun/smart-cd) - Runs `ls` and `git status` after chpwd. :star:12
* [snippets](https://github.com/willghatch/zsh-snippets) - Command line snippet expansion. :star:22
* [solarized-man](https://github.com/zlsun/solarized-man) - A modified version of oh-my-zsh's plugin colored-man-pages, optimized for the [solarized dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) theme in terminal. :star:15
* [ssh-connect](https://github.com/gko/ssh-connect) - A simple `ssh` manager. :star:52
* [ssh-plugin](https://github.com/paraqles/zsh-plugin-ssh) - Plugin for `ssh`.
* [startup-timer](https://github.com/paulmelnikow/zsh-startup-timer) - Print the time it takes for the shell to start up. :star:11
* [stashy](https://github.com/MisterRios/stashy) - Plugin that simplifies using `git stash`. :star:1
* [statify](https://github.com/vladmrnv/statify) - Plugin that does basic statistical analysis. :star:2
* [sterror](https://github.com/aphelionz/strerror.plugin.zsh) - Interprets error messages from programs and displays a human readable error message when available. :star:2
* [sublime](https://github.com/valentinocossar/sublime) - Same as the official Sublime plugin for Oh My Zsh, but this opens files in the current Sublime window, if there is one already open. :star:1
* [sudo](https://github.com/hcgraf/zsh-sudo) - The sudo plugin from oh-my-zsh, extracted to a standalone. Toggles `sudo` before the current/previous command by pressing *ESC-ESC* in emacs-mode or vi-command mode. :star:10
* [suffix-alias](https://github.com/srijanshetty/zsh-suffix-alias) - Directly open files in the shell using ZSH's suffix aliases. :star:1
* [symfony](https://github.com/voronkovich/symfony.plugin.zsh) - ZSH plugin for Symfony 2 and 3. :star:3
* [syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - ZSH syntax highlighting with dircolors in realtime. :star:73
* [syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Add syntax highlighting to your ZSH. Make sure you load this _before_ zsh-users/zsh-history-substring-search or they will both break. :star:5912
* [sys-diver-zsh](https://github.com/ToruIwashita/sys-diver-zsh) - A ZSH plugin for directory change or editor startup with only key operations using widgits without typing command. :star:4
* [sysadmin-util](https://github.com/skx/sysadmin-util) - Steve Kemp's collection of tool scripts for sysadmins. :star:514
* [t32](https://github.com/chrissicool/zsh-t32) - Plugin for the Lauterbach Trace32 toolset. It automatically registers fonts and sets all necessary environment variables to run the t32 toolset. :star:2
* [tailf](https://github.com/rummik/zsh-tailf) - Adds `tailf` function with prefixed newlines instead of trailing newlines.
* [taskbook](https://github.com/mastern2k3/taskbook-zsh-plugin) - Auto-completes task numbers for taskbook.
* [terminal-app](https://github.com/the8/terminal-app.zsh) - A plugin for integrating with the new El Capitan Terminal.app features. :star:11
* [terminal-workload-report](https://github.com/LockonS/terminal-workload-report) - A plugin that calculates and displays how many commands have been run via terminal. :star:2
* [terraform](https://github.com/pbar1/zsh-terraform) - Terraform convenience functions and aliases for ZSH.
* [timewarrior](https://github.com/svenXY/timewarrior) - Plugin for [timewarrior](https://timewarrior.net/) a timetracking application. :star:3
* [tipz](https://github.com/molovo/tipz) - Displays your alias if you have an alias for the command you just ran (Similar to [alias-tips](https://github.com/djui/alias-tips)). :star:14
* [titles](https://github.com/jreese/zsh-titles) - Automatic window and tab titles for [tmux](https://tmux.github.io) and xterm-compatible terminals. :star:24
* [tmux-fork](https://github.com/sharktamer/zsh-tmux) Standalone fork of the oh-my-zsh tmux plugin
* [tmux-rename](https://github.com/sei40kr/zsh-tmux-rename) - Rename [tmux](https://tmux.github.io) windows automatically. :star:3
* [tmux-simple](https://github.com/TBSliver/zsh-plugin-tmux-simple) - Simple plugin for using [tmux](https://tmux.github.io) with ZSH. :star:4
* [tmux-vim-integration](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) - Open files in a running Vim (or NeoVim) session, from an adjacent Tmux pane
* [tmux-zsh-vim-titles](https://github.com/MikeDacre/tmux-zsh-vim-titles) - Create unified terminal titles for tmux, ZSH, and Vim/NVIM, modular. :star:5
* [tmux](https://github.com/zpm-zsh/tmux/blob/master/tmux.plugin.zsh) - Plugin for [tmux](https://tmux.github.io)
* [tmuxrepl](https://github.com/csurfer/tmuxrepl) - Simple ZSH plugin to have a R-EP-L tmux session. :star:11
* [travis](https://github.com/denolfe/zsh-travis) - Opens the Travis CI page for the current repo if one exists. :star:3
* [tsm](https://github.com/RobertAudi/tsm) - Adds a [tmux](https://tmux.github.io) Session Manager. :star:8
* [tumult](https://github.com/unixorn/tumult.plugin.zsh) - Adds tools for macOS. :star:60
* [ubuntualiases](https://github.com/GuilleDF/zsh-ubuntualiases) - Ubuntu 16 aliases. :star:1
* [up.zsh](https://github.com/peterhurford/up.zsh) - Adds an up command to cd multiple levels up. :star:18
* [url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter) - A plugin for the ZSH syntax highlighter that turns URLs green if they respond with a "good" status, and red otherwise. Useful for checking URL typos. :star:17
* [uvenv](https://github.com/vincentto13/uvenv.plugin.zsh) - Extends the functionality of the original oh-my-zsh venv module
* [vanilli.sh](https://github.com/yous/vanilli.sh) - A lightweight start point of shell configuration. :star:6
* [velocity](https://github.com/rahulsalvi/velocity-python) - Powerline-based theme elements for ZSH and [tmux](https://tmux.github.io). :star:1
* [venv-lite](https://github.com/gimbo/venv-lite.zsh) - A super-lightweight sort-of-clone of [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/); it pretty much expects you to be using [pyenv](https://github.com/pyenv/pyenv) (though you don't *have* to), and because it's based on the [`venv` module](https://docs.python.org/3/library/venv.html), (creation) only works for python >= 3.3.
* [viexchange](https://github.com/okapia/zsh-viexchange) - Vi mode plugin for easily swapping text between two places in the buffer, like vim-exchange. :star:3
* [vim-mode](https://github.com/softmoth/zsh-vim-mode) - Friendly Vi-mode bindings, adding basic Emacs keys, incremental search, mode indicators and more. :star:9
* [vim-plugin](https://github.com/nviennot/zsh-vim-plugin) - Allows you to do `vim filename:123` to open a file with the cursor at a specific line. :star:11
* [vimman](https://github.com/yonchu/vimman) - View vim plugin manuals (help) like man in ZSH. :star:14
* [vimto](https://github.com/laurenkt/zsh-vimto) - Improved ZSH vim mode (bindkey -v) plugin. :star:15
* [virtualenv-mod](https://github.com/mattcl/virtualenv-mod) - A modified virtualenv ZSH plugin for oh-my-zsh.
* [virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt) - A fork of the virtualenv plugin from upstream. It adds support for customizing the virtualenv prompt in oh-my-zsh themes. :star:34
* [virtualz](https://github.com/aperezdc/virtualz) - Python virtualenv manager inspired by Virtualfish, replaces virtualenvwrapper. :star:6
* [virtuozzo-plugin](https://github.com/TamCore/virtuozzo-zsh-plugin) - An oh-my-zsh plugin for the [virtuozzo](https://docs.virtuozzo.com/master/index.html) bare-metal virtualization system.
* [visit](https://github.com/justinpchang/visit) - Custom plugin for faster navigation. :star:1
* [vox](https://github.com/andrewbonnington/vox.plugin.zsh) - An oh-my-zsh plugin to control [VOX](https://vox.rocks/), a lightweight full-featured audio player for macOS that can play a variety of formats including FLAC and Ogg Vorbis. :star:6
* [vsc](https://github.com/davidtong/vsc.plugin.zsh) - Plugin for Visual Studio Code on macOS. :star:1
* [vscode](https://github.com/qianxinfeng/zsh-vscode) - Plugin for Visual Studio Code. :star:21
* [wack](https://github.com/leoxlin/wack) - Wraps `ack` command.
* [wakatime-zsh-plugin](https://github.com/sobolevn/wakatime-zsh-plugin) - Track how much [time](https://wakatime.com/) you have spent in your terminal. Has per project stats. :star:12
* [wakatime](https://github.com/wbingli/zsh-wakatime) - Automatic time tracking for commands in ZSH using [wakatime](https://wakatime.com/). :star:48
* [warhol](https://github.com/unixorn/warhol.plugin.zsh) - Configures colorization with [grc](https://github.com/garabik/grc). :star:27
* [watson.zsh](https://github.com/bcho/Watson.zsh) - A plugin for the [watson](https://github.com/TailorDev/Watson) time management system. :star:1
* [wd](https://github.com/mfaerevaag/wd) - Warp directory lets you jump to custom directories in ZSH, without using `cd`. Why? Because `cd` seems inefficient when the folder is frequently visited or has a long path. :star:289
* [workon](https://github.com/bryanculver/workon.plugin.zsh) - Simple utility for jumping between projects :star:2
* [yadm](https://github.com/juanrgon/yadm-zsh) - Displays a warning if there are local yadm configuration changes. :star:1
* [yeoman-zsh-plugin](https://github.com/edouard-lopez/yeoman-zsh-plugin) - Edouard Lopez's Yeoman plugin for oh-my-zsh, compatible with yeoman version ≥1.0 (includes options and command auto-completion). :star:39
* [you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use) - ZSH plugin that reminds you to use those aliases you defined. :star:181
* [youtube-dl](https://github.com/joow/youtube-dl) - Simple plugin for [youtube-dl](https://youtube-dl.org/)
* [zaw](https://github.com/zsh-users/zaw) - ZSH anything.el-like widget. :star:422
* [zce](https://github.com/hchbaw/zce.zsh) - Vim’s EasyMotion / Emacs’s ace-jump-mode for ZSH. :star:38
* [zconvey](https://github.com/zdharma/zconvey) - Adds ability to send commands to other Zsh sessions, you can use this to `cd $PWD` on all active Zshells, for example. :star:18
* [zed](https://github.com/eendroroy/zed-zsh) - A simple wrapper for [z](https://github.com/rupa/z) to install as ZSH plugin. :star:5
* [zeit](https://github.com/zeit/zeit.zsh-theme) - Optimized for dark backgrounds, includes `git` status information. :star:82
* [zero](https://github.com/arlimus/zero.zsh) - Zero is both a plugin and a theme. See the github page for installation details. :star:13
* [zgdbm](https://github.com/zdharma/zgdbm) - Adds GDBM as a plugin. :star:1
* [zgen-compinit-tweak](https://github.com/seletskiy/zsh-zgen-compinit-tweak) - Make compinit run only once after all loading is done by zgen. :star:1
* [zhooks](https://github.com/agkozak/zhooks) - Displays the contents of any ZSH hook arrays and the code of any hook functions that have been defined. Useful for debugging. :star:8
* [zinfo_line](https://github.com/kmhjs/zinfo_line) - Makes more information available to ZSH themes. :star:1
* [zjump](https://github.com/qoomon/zjump) - Simplify ZSH directory navigation; jump to already visited, parent or sub folders. :star:5
* [zredis](https://github.com/zdharma/zredis) - Adds Redis database support, with `database_key` <-> `shell_variable` binding. Supports all data types. :star:4
* [zshmarks](https://github.com/jocelynmallon/zshmarks) - A port of Bashmarks (by Todd Werth), a simple command line bookmarking plugin, for oh-my-zsh. :star:162
* [zshrc](https://github.com/freak2geek/zshrc) - Load local `.zshrc` files from your project scopes. :star:3
* [zsnapac](https://github.com/johnramsden/zsh-zsnapac) - Plugin for taking ZFS pre/post upgrade snapshots on Arch Linux.
* [zsnapshot](https://github.com/psprint/zsnapshot) - Adds command to dump the current ZSH state into a file, for later restoration by sourcing the snapshot file. :star:7
* [Ztrace](https://github.com/psprint/ztrace) - Catches output of commands, allows to reuse that output, glue it with history content. :star:8
* [ZUI](https://github.com/zdharma/zui/) - ZSH User Interface library – CGI+DHTML-like rapid TUI application development with ZSH. :star:33

## Even more completions

These plugins add tab completions without adding extra functions or aliases.

* [_url-httplink](https://github.com/Valodim/zsh-_url-httplink) - Extends ZSH's \_urls completion, allowing it to complete urls from html pages. :star:2
* [ansible-server](https://github.com/viasite-ansible/zsh-ansible-server) - Completions for viasite-ansible/ansible-server. :star:1
* [autopkg-zsh-completion](https://github.com/fuzzylogiq/autopkg-zsh-completion) - Completions for autopkg. :star:7
* [aws_manager_plugin](https://github.com/EslamElHusseiny/aws_manager_plugin) - Add completions for the aws_manager CLI. :star:1
* [berkshelf-zsh-plugin](https://github.com/berkshelf/berkshelf-zsh-plugin) - Adds tab completion for berkshelf. :star:17
* [better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - Better tab completion for `npm`. :star:174
* [bosh-zsh-autocompletion](https://github.com/krujos/bosh-zsh-autocompletion) - Adds BOSH autocompletion. :star:2
* [brew-services](https://github.com/vasyharan/zsh-brew-services) - Completion plugin for homebrew services. :star:15
* [cabal-completion](https://github.com/ehamberg/zsh-cabal-completion) - Add tab completion for cabal.
* [cabal](https://github.com/d12frosted/cabal.plugin.zsh) - Adds autocompletion for cabal.
* [carthage](https://github.com/squarefrog/zsh-carthage) - Provides completions and aliases for use with [Carthage](https://github.com/Carthage/Carthage).
* [cf-zsh-autocomplete-plugin](https://github.com/Dannyzen/cf-zsh-autocomplete-plugin) - Adds autocomplete for all [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) commands. :star:26
* [codeception-zsh-plugin](https://github.com/shengyou/codeception-zsh-plugin) - Adds command completion for the Codeception Testing Framework. :star:10
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Displays git info, whether you're logged in via `ssh`, return code of last command. :star:6
* [ctop](https://github.com/gantsign/zsh-plugins/tree/master/ctop) - Tab completions for [ctop](https://github.com/bcicen/ctop) :star:7513
* [dbic](https://github.com/lejeunerenard/dbic-migration-env) - Automatically sets up Environment variables for DBIx::Class::Migration's script and Dancer.
* [docker-enter-completion](https://github.com/primait/docker-enter-completion) - Command completion for [docker-enter](https://github.com/jpetazzo/nsenter). :star:8
* [docker-zsh-completion](https://github.com/felixr/docker-zsh-completion) - Add completions for docker. :star:241
* [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands. :star:15
* [drush_zsh_completion](https://github.com/webflo/drush_zsh_completion) - Drush autocomplete awesomeness for ZSH. :star:40
* [duell](https://github.com/jcxavier/oh-my-zsh-duell) - A ZSH plugin for [duell](https://github.com/gameduell/duell). :star:2
* [etcdctl-zsh](https://github.com/sheax0r/etcdctl-zsh) - Adds etcdctl tab completions. :star:2
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - A plugin for [exercism.io](https://exercism.io/). :star:5
* [extract](https://github.com/thetic/extract) - Fork of the oh-my-zsh extract plugin. :star:2
* [fly-zsh-autocomplete-plugin](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) - Adds autocompletion options for all [Concourse CLI](https://www.concourse.ci/fly-cli.html) commands.
* [gcloud-zsh-completion](https://github.com/littleq0903/gcloud-zsh-completion) - Add completions for the Google Cloud SDK. :star:57
* [git-annex-completion](https://github.com/Schnouki/git-annex-zsh-completion) - Allows tab completion for most git-annex commands. :star:16
* [git-flow-completion](https://github.com/bobthecow/git-flow-completion) - ZSH completion support for git-flow. :star:2187
* [gradle-completion (eriwen)](https://github.com/gradle/gradle-completion) - Bash and ZSH completion support for gradle. :star:426
* [gradle-completion (ninrod)](https://github.com/ninrod/gradle-zsh-completion) - ZSH completion support for gradle. :star:1
* [grid5000-zsh-plugin](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 plugin - adds theme, autocompletions. :star:2
* [gulp-autocompletion-zsh](https://github.com/srijanshetty/gulp-autocompletion-zsh) - Autocompletion for gulp. :star:10
* [gulp](https://github.com/akoenig/gulp.plugin.zsh) - Autocompletion for your gulp.js tasks in the Z-Shell (ZSH). :star:33
* [hashlink](https://github.com/tong/zsh.plugin.hashlink) - Completions for [https://hashlink.haxe.org/](https://hashlink.haxe.org/).
* [haxelib](https://github.com/tong/zsh.plugin.haxelib) - Completions for haxelib. :star:1
* [joe-completion](https://github.com/corvofeng/joe-completion) - Adds completions for [joe](https://github.com/karan/joe) gitignore editor. :star:1
* [jtool-completion](https://github.com/beaugalbraith/jtool-completion) - ZSH completions for jtool.
* [jumpstorm-completion](https://github.com/netresearch/jumpstorm-zsh-plugin) - Adds autocompletion for [jumpstorm](https://github.com/netresearch/jumpstorm) :star:45
* [kafka](https://github.com/Dabz/kafka-zsh-completions) - Completions for Apache [kafka](https://kafka.apache.org)
* [keybase](https://github.com/rbirnie/oh-my-zsh-keybase) - Completions for [keybase](https://keybase.io/docs/command_line). :star:14
* [kompose](https://github.com/gantsign/zsh-plugins/tree/master/kompose) - Add tab completions for [Kompose](http://kompose.io/)
* [kubeadm](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) - Add tab completions for [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/)
* [mx-honey](https://github.com/mukel/mx-honey) - Provides completions for [mx](https://github.com/graalvm/mx); a command-line tool used for the development of Graal projects. It's meant to improve the usual workflow `build unittest benchmark ...` ease discovery and provide handy aliases. :star:3
* [newman](https://github.com/selop/newman-autocomplete) - Provides autocompletion for the [Newman CLI](https://github.com/postmanlabs/newman).
* [nix-zsh-completions](https://github.com/spwhitt/nix-zsh-completions) - Completions for [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/), and [NixOps](https://nixos.org/nixops/). :star:52
* [nova](https://github.com/rbirnie/oh-my-zsh-nova) - Provides auto-complete for nova. :star:7
* [npm-run](https://github.com/akoenig/npm-run.plugin.zsh) - Autocompletion support for `npm run`. :star:31
* [packer](https://github.com/wakeful/zsh-packer) - Adds tab completion for [packer](https://packer.io). :star:4
* [pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc completion plugin. :star:8
* [parallels-zsh-plugin](https://github.com/benclark/parallels-zsh-plugin) - Add completions for Parallels desktop. :star:6
* [pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) - convenience repo to easily obtain [pass](https://www.passwordstore.org/) command completion for ZSH. :star:2
* [pip-completion](https://github.com/srijanshetty/zsh-pip-completion) - Autocompletion plugin for pip. :star:14
* [pipenv (AlexGascon)](https://github.com/AlexGascon/pipenv-oh-my-zsh) - Enables aliases for the most common pipenv commands.
* [pipenv (gangleri)](https://github.com/gangleri/pipenv) - Completions for `pipenv`. :star:7
* [pipenv (owenstranathan)](https://github.com/owenstranathan/pipenv.zsh) - automatically activates a **pipenv** when entering a directory if there is Pipfile in that directory. Includes `pipenv` completions. :star:2
* [racket completion](https://github.com/racket/shell-completion) - Completion for [Racket](http://racket-lang.org). :star:3
* [rake-completion.zshplugin](https://github.com/unixorn/rake-completion.zshplugin) - Add fast tab completion for rakefile targets. :star:9
* [rancher-zsh-completion](https://github.com/go/rancher-zsh-completion) - Add completions for the Rancher CLI. :star:3
* [razor_plugin](https://github.com/dalang/oh-my-zsh_razor_plugin) - Provides autocomplete for [Razor](https://github.com/puppetlabs/Razor).
* [snappy](https://github.com/Arlon1/Snappy_zsh_autocompletion) - Add completions for snappy. :star:1
* [spring-boot-plugin](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) - Adds autocompletions for [spring-boot](http://projects.spring.io/spring-boot/) commands. :star:8
* [ssh-agent](https://github.com/bobsoppe/zsh-ssh-agent) - Manage `ssh-agent`. :star:8
* [ssh-agent](https://github.com/hkupty/ssh-agent) - Automatically starts `ssh-agent` to set up and load whichever credentials you want for `ssh` connections. :star:6
* [ssh](https://github.com/zpm-zsh/ssh) - Add host completion for `ssh`. :star:1
* [surf](https://github.com/beardcoder/surf.plugin.zsh) - Add completions for surf. :star:2
* [test-kitchen-zsh-plugin](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) - Add completions for [Test Kitchen](https://kitchen.ci/). :star:5
* [tmux pane words](https://gist.github.com/blueyed/6856354) - Key bindings to complete words from your [tmux](https://tmux.github.io) pane.
* [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) - Adds autocompletion for [tugboat](https://github.com/petems/tugboat) command. :star:4
* [umake](https://github.com/zlsun/umake) - Tab completion for Ubuntu umake.
* [vert.x-omz-plugin](https://github.com/davidafsilva/vert.x-omz-plugin) - Provides autocomplete features for the [vertx](https://vertx.io/) command.
* [yarn](https://github.com/g-plane/zsh-yarn-autocompletions) - Yarn autocompletions. :star:322
* [zsh-completions](https://github.com/zsh-users/zsh-completions) - A collection of extra completions for ZSH. :star:2309
* [zsh-ipfs](https://github.com/aramboi/zsh-ipfs) - Completions for the [Interplanetary File System](https://ipfs.io). :star:7

## Themes

If you're using [Antigen](https://github.com/zsh-users/antigen), you can test these themes in a running ZSH with `antigen theme githubuser/repo`. If you're using [zgen](https://github.com/tarjoilija/zgen), add them to your `init.zsh` with `zgen load githubuser/reponame`.

* [aaron](https://github.com/aaronjamesyoung/aaron-zsh-theme) - Based on the Sorin theme. :star:2
* [absolute](https://github.com/NelsonBrandao/absolute) - Very clean looking theme with git status, node version and the exit code from the last command. :star:14
* [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) - macOS theme, requires a Powerline-compatible font. :star:1
* [af-magic-mod](https://raw.githubusercontent.com/desyncr/zshrc/master/themes/af-magic-mod.zsh-theme) - af-magic-mod theme.
* [aflah-bhari](https://github.com/AflahB/aflah-bhari-zsh-theme) - Modified version of the [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) theme in oh-my-zsh.
* [aftermath](https://github.com/schanur/aftermath) - Get a nice summary line after each command you run on your shell.
* [agkozak](https://github.com/agkozak/agkozak-zsh-prompt) - Uses two asynchronous methods to keep the ZSH prompt swift while displaying color, ASCII-only indicators of Git branch and changes, SSH connection or lack thereof, exit codes, and vi mode status, along with a customizable, abbreviated, `PROMPT_DIRTRIM`-style path. :star:41
* [agnoster-fcamblor](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) - Solarized [Agnoster](https://gist.github.com/agnoster/3712874) variant with git information. Requires a unicode font and works best with a [solarized](https://github.com/altercation/solarized) terminal. :star:167
* [agnoster-mod](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with a right-prompt. :star:3
* [agnoster-plus](https://github.com/jiahut/agnoster-plus.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant optimized for use with [Solarized Dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) terminal color scheme. Includes git status. :star:2
* [agnoster-refresh](https://github.com/fusion94/Agnoster-refresh) - [Agnoster](https://gist.github.com/agnoster/3712874) variant, includes battery and online status. :star:4
* [agnosterAfro](https://github.com/afrozalm/agnosterAfro) - Based on [Powerline](https://github.com/Lokaltog/vim-powerline) and [Agnoster Theme](https://gist.github.com/agnoster/3712874) and inspired by the [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme). :star:7
* [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - Based on Agnoster, shows battery life, date & time, git status, current directory and user & host information. :star:187
* [alien-minimal](https://github.com/eendroroy/alien-minimal) - Minimalist ZSH theme with git status displayed. :star:45
* [alien](https://github.com/eendroroy/alien) - Powerline-esque ZSH theme that shows git branch and the exit code of the last command. :star:104
* [alpharized](https://github.com/NicoSantangelo/Alpharized) - Optimized to work with [solarized dark](https://github.com/altercation/solarized) terminals. It's a modified version of the [avit theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme). :star:10
* [angry fly](https://github.com/russjohnson/angry-fly-zsh) - Shows git information in the right hand prompt. :star:3
* [aphrodite](https://github.com/win0err/aphrodite-terminal-theme) - Minimalistic theme without visual noise. Displays only the necessary information: current user, hostname, working directory, git branch if exists. Looks great both with dark and white terminals. :star:19
* [aplos](https://github.com/sunquan1991/aplos) - Minimal ZSH prompt with working directory, `git` local info, `git` remote info, time and exit code.
* [asciigit](https://github.com/cemsbr/asciigit) - An ASCII-only theme for `git` users who don't want to use fonts with extra glyphs. :star:2
* [asq](https://github.com/AugustoQueiroz/asq-theme) - Based on [theunraveler](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes#theunraveler).
* [astral](https://github.com/alphabetum/astral) - Theme for dark backgrounds with zen mode.
* [astro](https://github.com/iplaces/astro-zsh-theme/blob/master/README.md) - Based on [`ys`](http://blog.ysmood.org/my-ys-terminal-theme/) theme and `robbyrussell` (default theme) theme. :star:26
* [aterminal](https://github.com/guiferpa/aterminal) - Displays Nodejs, NPM, Docker, Go, Python, Elixir and Ruby information in the prompt. :star:15
* [avit-d2k](https://github.com/fdaciuk/avit-da2k) - Based on the oh-my-zsh [avit](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme) theme, with small changes. :star:11
* [avit-mod](https://github.com/zlsun/avit-mod) - Modified version of oh-my-zsh's [avit](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme) theme.
* [bandit](https://github.com/Holger-Will/zsh_bandit) - Another Powerline variant. :star:2
* [bashi](https://github.com/eli-oat/bashi) - Optimized for Ahmet Sülek's [Flat UI Terminal Theme](https://github.com/ahmetsulek/flat-terminal) and Pasquale D'Silva's [Saturn Terminal Theme](https://github.com/psql/saturn-colors). :star:4
* [beer](https://github.com/tcnksm/oh-my-zsh-beer-theme) - Inspired by [cloud](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/cloud.zsh-theme), but with beer icons. :star:1
* [bender](https://github.com/specious/bender) - Fancy two-line prompt with git integration. :star:2
* [bgnoster](https://github.com/vvvvv/bgnoster.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with unicode symbols baked in.
* [birame](https://github.com/maniat1k/birame) - Based on [bira](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bira.zsh-theme). :star:1
* [bklyn](https://github.com/gporrata/bklyn-zsh) - Variant of [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) with customizations applied. :star:10
* [blackrain](https://github.com/ginfuru/zsh-blackrain) - Another git-aware theme. :star:6
* [blinks-xfan](https://github.com/ixfan/blinks-xfan) - Based on the existing theme blinks. :star:2
* [blokkzh](https://github.com/KorvinSilver/blokkzh) - Theme based on oh-my-zsh's built in [gnzh](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/gnzh.zsh-theme) theme. Requires a font with unicode support.
* [blox](https://github.com/yardnsm/blox-zsh-theme) - A minimal and fast ZSH theme that shows you what you need. It consists of blocks: each block is shown inside a pair of \[square brackets\], and you can add blocks by simply creating a function. :star:35
* [bluehigh](https://github.com/hiroppy/bluehigh.zsh-theme) - Minimal theme, displays `git` information. :star:1
* [bluelines](https://github.com/apbarrero/bluelines) - Clear and blue theme. :star:2
* [boom](https://github.com/the0neWhoKnocks/zsh-theme-boom) - Multiline theme, best on dark backgrounds. :star:2
* [bronze](https://github.com/reujab/bronze) - A cross-shell customizable powerline-like prompt with icons written in go. Requires [nerd-fonts](https://github.com/ryanoasis/nerd-fonts). :star:34
* [brunty](https://github.com/Brunty/omz-brunty) - Brunty theme. :star:3
* [bttf-color](https://github.com/yasuhiroki/bttf-color-zsh) - BTTF color theme. :star:1
* [bullet-train](https://github.com/caiogondim/bullet-train.zsh) - Inspired by the Powerline Vim plugin. It aims for simplicity, showing information only when it's relevant. :star:1973
* [bunnyruni.min](https://github.com/mikeumus/bunnyruni.min) - [@jopcode's](https://github.com/jopcode) [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ZSH theme, modified to just display time and directory. :star:1
* [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) - Simple, clean, and beautiful theme. :star:5
* [bureau](https://github.com/isqua/bureau) - A clear and informative two-lined prompt. Includes git status optimized for large repositories. :star:15
* [candy-light](https://github.com/NicolaiRuckel/oh-my-zsh-candy-light) - Light version of the candy theme. :star:1
* [charged](https://github.com/robwierzbowski/charged-zsh-theme) - A ZSH prompt optimized for the [solarized](https://github.com/altercation/solarized) dark terminal theme. :star:4
* [chi](https://github.com/akinjide/chi) - A ZSH theme optimized for iTerm 2 users on macOS. :star:5
* [ciacho](https://github.com/Ciacho/ciacho-ohmyzsh-theme) - Based on Agnoster. :star:1
* [cinnabar](https://github.com/nvillapiano/zsh-theme---cinnabar) - Shows timestamp, large line breaks, git branch and status.
* [clarity](https://github.com/nbitmage/clarity.zsh) - Designed for for simpleness and extensibility. :star:3
* [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) - Minimal, clean theme with `git` support. :star:29
* [clean (akz92)](https://github.com/akz92/clean) - Minimalist ZSH theme. :star:2
* [clean (BrandonRoehl)](https://github.com/BrandonRoehl/zsh-clean) - A minimalist variant of [pure](https://github.com/sindresorhus/pure). Pure is not clean, clean is not pure. :star:9
* [cloudy](https://github.com/Huvik/Cloudy) - Minimal cloudy ZSH theme. :star:25
* [clover](https://github.com/tzing/clover.zsh-theme) - Inspired by [zeta-zsh-theme](https://github.com/skylerlee/zeta-zsh-theme) and [pure](https://github.com/sindresorhus/pure). :star:1
* [cmder](https://github.com/potasiyam/cmder-zsh-theme) - A ZSH theme that matches the theme of Cmder, a popular terminal emulator for windows. :star:6
* [cobalt2](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos' Cobalt 2 theme for ZSH and iTerm 2. :star:826
* [cobalt2git](https://github.com/alexeimun/cobalt2git) - Cobalt 2 theme with git extensions. :star:1
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Codemachine theme. :star:6
* [codemonkey-on-fire](https://github.com/babette-landmesser/codemonkey-on-fire.zsh-theme) - Inspired by [bashi](https://github.com/eli-oat/bashi), includes a monkey and `git` information in your prompt.
* [colorbira](https://github.com/CristianCantoro/colorbira-zsh-theme) - Allows per-host prompt coloring, displays `rvm`, `virtualenv` and `git` information.
* [comxtohr](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) - Brightly colored theme optimized for dark backgrounds. :star:2
* [cordial](https://github.com/stevelacy/cordial-zsh-theme) - Clean and effective ZSH theme with git and npm support. :star:12
* [cramin](https://github.com/FelipeCRamos/craminzsh) - Minimal interface with support for github plugins, based on [hyperzsh](https://github.com/tylerreckart/hyperzsh). :star:5
* [cute-theme](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - An macOS oh-my-zsh shell theme with Cute emoji based on the Powerline Vim plugin. :star:22
* [czsh](https://github.com/Cellophan/czsh) - [ZSH](https://en.wikipedia.org/wiki/Z_shell) with [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) and the [agnoster theme](https://github.com/agnoster/agnoster-zsh-theme) in a container.
* [darkblood-modular](https://github.com/InAnimaTe/darkblood-modular) - This version of the popular [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) theme has been enhanced with a near complete rewrite enabling modularity and a few new features. :star:1
* [darksoku](https://github.com/TooSchoolForCool/darksoku-zsh-theme) - Darksoku theme is based on the [ys](http://blog.ysmood.org/my-ys-terminal-theme/) and [astro](https://github.com/iplaces/astro-zsh-theme) themes.
* [delta-prompt](https://github.com/cusxio/delta-prompt) - A minimal ZSH prompt. :star:6
* [delta](https://github.com/dongri/delta-zsh-theme) - Another minimal theme with embedded `git` status.
* [dexter](https://github.com/shvenkat/zsh-theme-dexter) - A theme with an emphasis on the right side (hence the name) of the terminal. :star:2
* [dissonance](https://github.com/RyanScottLewis/theme-dissonance-zsh) - Comes with custom LSCOLORS and LS_COLORS settings files, works with both dark and light terminal themes. :star:4
* [diy-ys](https://github.com/aprilnops/zsh-theme) - Variant of [ys](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme) without hostname or time.
* [dmx](https://github.com/domix/dmx.zsh-theme) - Optimized for dark terminal windows. :star:1
* [dp](https://github.com/davidparsson/zsh-dp-theme) - Low contrast theme that shows current git branch, if the repository is dirty and the value of `$PYENV_VERSION`.
* [dracula](https://github.com/dracula/zsh) - A dark theme for Atom, Alfred, Chrome DevTools, iTerm 2, Sublime Text, Textmate, Terminal.app, Vim, Xcode, and ZSH. :star:31
* [dragon](https://github.com/sabertazimi/dragon-zsh-theme) - Minimalistic, includes `git` status information. :star:7
* [dustmod](https://github.com/bmihaila/dustmod) - Derived from the [dst](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/dst.zsh-theme) theme in oh-my-zsh. :star:1
* [eggshausted](https://github.com/inutano/eggshausted) - A `git`-aware theme for people who are tired of getting errors. :star:1
* [emojeer](https://github.com/lxynox/emojeer-ohmyzsh) - Emoji flavored [oh-my-zsh](robbyrussell/oh-my-zsh) theme.
* [endless-dog](https://github.com/qwelyt/endless-dog) - OMZ theme that mimics grml-zsh-config.
* [enormous](https://github.com/leighmcculloch/zsh-theme-enormous) - Takes up an enormous amount of space in the terminal. :star:1
* [eubw](https://github.com/eptaccio/eubw-oh-my-zsh-theme) - A simple theme with `git` information.
* [excess](https://github.com/davydovanton/excess.zsh-theme) - Simple ZSH color theme. :star:3
* [fattyarrow](https://github.com/sohnryang/fattyarrow) - Minimal ZSH prompt that works better on dark backgrounds.
* [feder](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme) - Clean, simple, compatible and meaningful. Tested on Linux, Unix and Windows under ANSI colors.
* [filthy](https://github.com/molovo/filthy) - A disgustingly clean ZSH prompt. :star:22
* [fishy-lite](https://github.com/sudorook/fishy-lite) - Fork of the original [fishy](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#fishy) theme in oh-my-zsh with much of the extraneous stuff cut out to improve load speeds. Includes a battery gauge and git display that can be enabled on the right-hand side of the prompt. :star:1
* [fishy](https://github.com/akinjide/fishy2) - ZSH theme inspired by [original fishy](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#fishy) :star:78089
* [fortuity](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) - Includes status of last command, `git` information and current directory. :star:2
* [friendly-fiesta](https://github.com/bruino/friendly-fiesta) - Fork of terminal-party theme.
* [frisk-arrow](https://github.com/BakeRolls/frisk-arrow) - A theme based on the [frisk](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh-theme.
* [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) - Red version of the frisk theme from oh-my-zsh.
* [frlo](https://github.com/fiorillo/frlo) - Uses your computer's hostname to come up with a (hopefully) unique three-color theme to display in your prompt, so you know at a glance which machine you're logged into. :star:1
* [furio](https://github.com/hectorpalmatellez/furio-theme) - Fork of the Cloud oh-my-zsh theme. with different colors and emojis. :star:16
* [garrett](https://github.com/chauncey-garrett/zsh-prompt-garrett) - Prezto prompt with the information you need the moment you need it. :star:136
* [gawaine](https://github.com/nicolaracco/gawaine.zsh-theme) - Nicola Racco's theme. Requires `rvm` & `git` plugins. :star:3
* [geometry](https://github.com/geometry-zsh/geometry) - A minimal ZSH theme based on Avit and Pure that displays a lot of `git` information and is composable and customizable. :star:453
* [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) Adds host info to the [geometry](https://github.com/geometry-zsh/geometry) theme.
* [girazz](https://github.com/mdentremont/girazz) - A modification to the gnzh theme which adds `vi` mode to the right prompt.
* [git-prompt](https://github.com/olivierverdier/zsh-git-prompt) - Displays information about the current git repository. In particular the branch name, difference with remote branch, number of files staged, changed, etc. :star:1156
* [gitsome](https://github.com/mtully/gitsome) - Super simple prompt with `git` info, optimized for the [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) color scheme. :star:56
* [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) - When in a `git` repo, it shows the location from the `git` repository root folder. When not in a `git` repo, it shows the path relative to home, `~`. :star:53
* [glimmer](https://github.com/martnu/glimmer) - Includes `git` branch, time and user@host. :star:1
* [guri](https://github.com/victorfsf/guri) - A Simple and fast Oh-My-Zsh theme, based on [Pure](https://github.com/sindresorhus/pure)'s design. :star:11
* [hackersaurus](https://github.com/bhilburn/hackersaurus) - A theme with `git` status and exit code of last command run embedded in the prompt. Related to [powerlevel9k](https://github.com/bhilburn/powerlevel9k). :star:9
* [hanpen](https://github.com/kojole/hanpen.zsh-theme) - Shows `git` branch and status, last command exit code, last command execution time if more than `ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`
* [haribo](https://github.com/haribo/omz-haribo-theme) - Simple `git` status + timestamp in prompt. :star:6
* [hcompact](https://github.com/fusion809/zsh-theme) - Displays time, OS (including distro if on Linux), directory and whether running as root.
* [heart](https://github.com/gko/heart-theme) - Heart themed prompt for light backgrounds. :star:3
* [hedgehog](https://gist.github.com/hedgehog1029/dfbb7e66511e2c399157) - Simple, no-nonsense and clean, with support for `git` and return codes.
* [helb](https://github.com/helb/helb.zshtheme) - Loosely based on Gentoo's old bash theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
* [hfulldate](https://github.com/fusion809/zsh-theme) - Displays time, date, OS (including distro if on Linux), directory and whether running as root.
* [hhktony](https://github.com/hhktony/hhktony.zsh-theme) - Inspired by robbyrussell theme + ssh connection status prompt.
* [himself](https://github.com/mwamodojnr/himself) - Optimized for people using `git`, [solarized](https://github.com/altercation/solarized) terminals and unicode-compatible fonts.
* [hipstersmoothie-p9x](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - A variant of [powerlevel9k](https://github.com/bhilburn/powerlevel9k). :star:3
* [honukai-iterm-zsh](https://github.com/oskarkrawczyk/honukai-iterm-zsh) - Honukai theme and colors for oh-my-zsh and iTerm 2. :star:912
* [horizontal](https://github.com/nuimk/horizontal) - Two line prompt with a horizontal separator. :star:1
* [hornix](https://github.com/fusion809/zsh-theme) - Displays time & date, OS (including distro if on Linux), directory and whether running as root.
* [horse-sh](https://github.com/emileswarts/horse-sh) - A very minimal brown/red ZSH theme.
* [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - Simple and clean, includes the return code of the last command executed.
* [hyperzsh](https://github.com/tylerreckart/hyperzsh) - Gives you a comprehensive overview of the branch you're working on and the status of your repository without cluttering your terminal. :star:347
* [iamskok](https://github.com/iamskok/iamskok.zsh-theme) - Works well on a dark background.
* [iggy](https://github.com/eugenk/zsh-prompt-iggy) - A super happy awesome Powerline-style, `git`-aware **prezto only** theme. :star:11
* [igorsilva](https://github.com/igor9silva/zsh-theme) - Shows current directory, customizable delimiter, current branch, `git` status. :star:4
* [imp](https://github.com/igormp/Imp) - Based on [zork](https://github.com/Bash-it/bash-it/wiki/Themes#zork) and optimized for dark backgrounds. :star:5
* [infernus](https://github.com/jshiell/infernus-zsh-theme) - Minimalist theme, better on dark backgrounds.
* [infoline](https://github.com/hevi9/infoline-zsh-theme) - Clean theme that shows `git` status, background jobs, remote host, and other information. :star:4
* [intheloop-powerline](https://github.com/zyphrus/intheloop-powerline) - An extension of the [intheloop](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/intheloop.zsh-theme) theme to use powerline fonts. :star:1
* [itg](https://github.com/itsthatguy/itg.zsh-theme) - itsthatguy's theme. :star:30
* [jc](https://github.com/jclementex/jc-zsh-theme) - For dark terminal backgrounds, includes `git` status information. :star:1
* [jcl](https://github.com/jasonlewis/jcl-zsh-theme) - Loosely based on the ys theme. :star:2
* [jose](https://github.com/tmjoseantonio/shrug-zsh-theme) - Inspired by [beer-theme](https://github.com/tcnksm/oh-my-zsh-beer-theme), includes `git` status. :star:4
* [jovial](https://github.com/zthxxx/jovial) - Shows host, user, path, development environment, `git` branch, which python venv is active. :star:37
* [judgedim](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - Minimalist prompt.
* [just-another](https://github.com/supertassu/another-theme) - Just another theme, with hostname when you're sshed to another machine. :star:1
* [karu](https://github.com/zaari/karu) - Minimalist single line ZSH prompt. :star:1
* [keloran](https://github.com/Keloran/keloran.zsh-theme) - Theme that includes a few features from other themes.
* [kenton](https://github.com/notnek/zsh-theme) - Optimized for dark backgrounds, includes `git` status information. :star:2
* [kevin](https://github.com/KevinParnell/Kevin-zsh) - Colorful theme, includes iTerm 2 color schemes. :star:1
* [kimwz](https://github.com/kimwz/kimwz-oh-my-zsh-theme) - Minimal theme. :star:8
* [kinda-fishy](https://github.com/folixg/kinda-fishy-theme) - Based on Fishy theme, but shows full paths instead of abbreviated directories and only shows user@machine in `ssh` sessions and docker containers :star:2
* [kketcham](https://github.com/prototype27/kketcham) - Theme with nifty colors on the `git` info.
* [klendathu](https://github.com/kegonomics/klendathu) - Uses Powerline iconsolas.
* [kraken](https://github.com/KrakenTheme/kraken-zsh) - A dark theme for ZSH. :star:1
* [kumavis](https://github.com/kumavis/kumavis-zsh-theme) - Agnoster fork optimized for solarized terminals. Requires powerline-compatible font.
* [kw](https://github.com/Kwpolska/kw.zsh-theme) - Colorful theme with `git` and `hg` status information, ability to add host-specific colors to hostname.
* [lagune](https://github.com/noplay/lagune) - a minimal ZSH theme. :star:1
* [lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) - Minimalist prompt that includes `git` information. :star:37
* [lambda-pure](https://github.com/marszall87/lambda-pure) - A minimal ZSH theme, based on Pure, with added NodeJS version. :star:65
* [lambda](https://github.com/halfo/lambda-mod-zsh-theme/) - A ZSH theme optimized for `git` users who use unicode-compatible fonts and terminal applications. :star:340
* [lambdav](https://github.com/vkaracic/lambdav-zsh-theme) - A combination of the Lambda and Fishy themes.
* [lazyprodigy](https://github.com/drewlustro/lazyprodigy-zsh-theme) - Optimized for dark terminals, has variants for local and remote systems. :star:1
* [leafia](https://github.com/Ghostrick/leafia-prompt) - Leafy prezto theme that shows `git` status information. :star:1
* [lewis](https://github.com/lewisflude/oh-my-lewis) - Black, white and red theme. Shows `git` status information.
* [lila](https://github.com/raphaelivan/lila-zsh-theme) - Minimalist theme, best on a dark terminal background.
* [lime](https://github.com/yous/lime) - Simple standalone ZSH theme. :star:12
* [limpide](https://github.com/shooteram/limpide) - Modified version of [miloshadzic](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#miloshadzic) theme which displays parent and current directory.
* [linuxer](https://github.com/patrick330602/linuxer) - Inspired by Yaris Alex Gutierrez's classyTouch, Yad Smood's ys, and Bureau theme. :star:1
* [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt for Bash & ZSH. :star:3538
* [llama](https://github.com/PsychoLlama/llama.zsh-theme) - Minimalist theme used by discerning llamas. :star:6
* [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) - Texas-themed theme based on Sindre Sorhus' pure theme. :star:1
* [magico](https://github.com/IOsonoTAN/magico) - IOsonoTAN's magico theme.
* [materialshell](https://github.com/carloscuesta/materialshell) - A [material design](https://material.io/guidelines/style/color.html) theme for your shell with a good contrast and color pops at the important parts. Designed to be easy on the eyes. :star:575
* [mau](https://github.com/vichargrave/mau) - A ZSH theme with a cat twist. :star:1
* [maxulysse/myzsh](https://github.com/MaxUlysse/myzsh) - Maxime Garcia's myzsh theme.
* [megaprompt](https://github.com/willghatch/zsh-megaprompt) - A maximalist prompt including keyboard mode, ownership info, and other contextual info, with λ as the prompt character. Requires the [hooks](https://github.com/willghatch/zsh-hooks) plugin. :star:3
* [milight](https://github.com/frodoslaw/milight-zsh) - Minimal ZSH prompt with `git` status display, works best with dark terminal backgrounds.
* [min](https://github.com/andrepolischuk/min) - A minimalistic ZSH prompt. :star:9
* [mindful-space](https://github.com/syndbg/mindful-space-zsh-theme) - ZSH theme with space in mind. :star:2
* [minimal2](https://github.com/PatTheMav/minimal2) - A minimal and extensible ZSH theme. Forked from [subnixr's original](https://github.com/subnixr/minimal) and adapted for [Zimfw](https://github.com/zimfw/zimfw). :star:7
* [minimal](https://github.com/subnixr/minimal) - Minimal yet feature-rich theme. :star:109
* [minimalx](https://github.com/lknix/zsh-theme-minimalx) - Inspired by kolo theme from oh-my-zsh. :star:1
* [misa](https://github.com/misalabs/misa.zsh-theme) - Misalabs' ZSH theme. :star:1
* [mixed](https://github.com/dekermendzhy/mixed-zsh-theme) - Optimized for dark backgrounds.
* [molokai-powerline-zsh](https://github.com/prikhi/molokai-powerline-zsh) - Based on [agnoster](https://gist.github.com/agnoster/3712874). :star:8
* [moonline](https://github.com/kagamilove0707/moonline.zsh) - Minimal but easily extensible prompt. :star:8
* [multi-shell-repo-prompt](https://github.com/dotcode/multi-shell-repo-prompt) - Provides useful information (in your prompt) about the repository that you are in. It currently works for [Git](https://git-scm.com/) and [Mercurial](https://www.mercurial-scm.org/), under [ZSH](https://en.wikipedia.org/wiki/Zsh) as well as [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29). :star:11
* [multiline](https://github.com/jan-auer/zsh-multiline) - Powerline-esque theme based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme) :star:1332
* [muslim](https://github.com/nksoff/muslim) - A simple minimal ZSH prompt theme. :star:3
* [nanofish](https://github.com/tweekmonster/nanofish) - Adds fish-style directory prompt to nanotech theme. :star:2
* [neat](https://github.com/andrepolischuk/neat) - Minimalistic prompt inspired by [odin](https://github.com/tylerreckart/Odin) and [pure](https://github.com/sindresorhus/pure). :star:6
* [nerdish](https://github.com/nyarla/zsh-theme-nerdish) - A prompt theme for ZSH with Nerd Fonts. :star:3
* [newt](https://github.com/softmoth/zsh-prompt-newt) - Fat & fast theme – beautiful inside and out, styled segments done right. :star:2
* [nextbike](https://github.com/meierjan/nextbike-zsh-theme) - A very basic theme which just features an macOS bike icon. :star:2
* [ningxia](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) - Based on af-magic.
* [nknu](https://github.com/aanc/oh-my-zsh-nknu-theme) - A simple OMZ theme.
* [nmaxcom](https://github.com/nmaxcom/nmaxcom-zsh-theme) - Minimalist ZSH theme with `git` status decorations. :star:2
* [node](https://github.com/skuridin/oh-my-zsh-node-theme) - OMZ's node theme, broken out to make it easier to use with other plugin managers. :star:43
* [nodeys](https://github.com/marszall87/nodeys-zsh-theme) - Based on ys theme, with added NodeJS version (from NVM plugin). :star:29
* [noon](https://github.com/silky/noon.zsh-theme) - Has light and dark variants, shows `git` information.
* [nothing](https://github.com/eendroroy/nothing) - Lightning fast and really simple because it has almost nothing in it. :star:9
* [nox](https://github.com/kbrsh/nox) - Dark theme, displays the current working directory and git status. :star:7
* [nt9](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme) - Clean, distraction free and `git` focused development theme. Shows path relative to `git` root (or ~ when outside `git` repo), time since last commit, current SHA, branch and branch state. :star:16
* [nuqlezsh](https://github.com/Nuqlear/nuqlezsh.zsh-theme) - Simple theme for prezto and oh-my-zsh. :star:1
* [odin](https://github.com/tylerreckart/odin) - Odin is a `git`-flavored ZSH theme. :star:75
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - An opinionated prompt for bash and ZSH. :star:3011
* [oh-my-via](https://github.com/badouralix/oh-my-via) - Theme for ZSH which mainly forks the historical theme used on VIA servers. :star:16
* [oxide](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) - A Minimalistic and Dark ZSH theme. :star:280
* [ozono](https://github.com/sfabrizio/ozono-zsh-theme) 🌏 OZ0NO - Let's Breathe a clean ZSH.
* [pad](https://github.com/eproxus/pad.zsh-theme) - A concise and colorful oh-my-zsh theme. :star:3
* [page](https://github.com/SLIB53/page-zsh-theme) - A simple theme with VCS support. The prompt shows 1 level of the current working directory, branch, and a color coded curved fat arrow.
* [pastel](https://github.com/iboyperson/pastel) - A ZSH theme inspired by [sugar-free](https://github.com/cbrock/sugar-free). :star:4
* [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) - A clean and simple theme for ZSH inspired and forked from [Lambda (Mod) ZSH Theme](https://github.com/halfo/lambda-mod-zsh-theme). :star:7
* [pieni](https://github.com/zaari/pieni) - Minimalist single line ZSH prompt theme. :star:3
* [plain](https://github.com/jimeh/plain.zsh-theme) - A plain and simple theme for ZSH which shows basic `git` information.
* [planet](https://github.com/borb/planet-zsh) - A slimmed down version of [steef](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/steeef.zsh-theme) from [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh).
* [platypus](https://github.com/fdv/platypus) - Platypus is a simple and convenient theme for oh-my-zsh used by Frédéric de Villamil. :star:1
* [poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho) - RDM's basic oh-my-zsh custom theme. :star:4
* [poor-programmer](https://github.com/vishaltelangre/poor-programmer.zsh-theme) - Programmer's theme with `git` status, ruby version and project path.
* [powerless](https://github.com/martinrotter/powerless) - Tiny & simple pure ZSH prompt inspired by powerline. :star:46
* [powerlevel9k](https://github.com/bhilburn/powerlevel9k) - Powerlevel9k is a theme for ZSH which uses [Powerline Fonts](https://github.com/powerline/fonts). It can be used with vanilla ZSH or ZSH frameworks such as [Oh-My-Zsh](https://github.com/robbyrussell/oh-my-zsh), [Prezto](https://github.com/sorin-ionescu/prezto), [Antigen](https://github.com/zsh-users/antigen), and [many others](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions). :star:6705
* [powerlevelHipstersmoothie](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - Add-on for [powerlevel9k](https://github.com/bhilburn/powerlevel9k). :star:3
* [powerline (jeremy)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) - Another take on a powerline theme. Nicely configurable, but requires at least a 256 color-capable terminal with a powerline-compatible terminal font. :star:935
* [powerline (syui)](https://github.com/syui/powerline.zsh) - A git aware powerline theme.
* [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - Based on [bullet-train](https://github.com/caiogondim/bullet-train.zsh). :star:22
* [powerline-go](https://github.com/justjanne/powerline-go) - A beautiful and useful low-latency prompt, written in golang. :star:889
* [powerline-pills](https://github.com/lucasqueiroz/powerline-pills-zsh) - Created in Ruby, uses powerline characters to simulate pills with useful information. :star:9
* [powerline-shell (b-ryan)](https://github.com/b-ryan/powerline-shell) - Beautiful and useful prompt generator for Bash, ZSH, Fish, and tcsh. :star:4207
* [powerline-shell (banga)](https://github.com/b-ryan/powerline-shell) - A [powerline](https://github.com/Lokaltog/vim-powerline)-like prompt for Bash, ZSH and Fish. Shows important details about git/svn/hg/fossil branch and is easy to customize/extend. :star:4207
* [powerline-train](https://github.com/sherubthakur/powerline-train) - A powerline variant. :star:1
* [powerzeesh](https://github.com/sevaho/Powerzeesh) - A Powerline based ZSH theme. It aims for simplicity, showing information only when it's relevant, optimized for speed and look. Inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [Powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
* [pre](https://github.com/leandromatos/pre-theme) - A collection of themes for Sublime Text, Terminal, iTerm 2 and ZSH. :star:34
* [predawn-shell](https://github.com/jamiewilson/predawn-shell) - Theme for dark terminal themes. :star:35
* [prezto-cloud-prompt](https://github.com/klaude/prezto-cloud-prompt) - Prezto port of oh-my-zsh's cloud prompt. :star:1
* [prezto-lambda](https://github.com/nixolas1/prezto-lambda) - Lambda theme (for prezto).
* [prezto_powerline](https://github.com/davidjrice/prezto_powerline) - Powerline for prezto. Shows git information, RVM version. :star:106
* [prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - A fairly heavyweight ZSH prompt, based on the powerline font from the popular eponymous vim plugin, which works well for a dark background. :star:49
* [punctual](https://github.com/dannynimmo/punctual-zsh-theme) - Easily customizable, influenced by [spaceship](https://github.com/denysdovhan/spaceship-prompt). :star:29
* [pure](https://github.com/sindresorhus/pure) - Pretty, minimal and fast ZSH prompt. :star:5817
* [purify](https://github.com/banminkyoz/purify) - Simple, fast & cool prompt. :star:3
* [purity](https://github.com/petermbenjamin/purity) - Inspired by robbyrussell theme + pure prompt. :star:7
* [qoomon](https://github.com/qoomon/zsh-theme-qoomon) - Optimized for dark backgrounds, includes `git` information. Theme repo includes iTerm 2 and Terminal color settings. :star:1
* [racotecnic](https://github.com/elboletaire/zsh-theme-racotecnic) - Based on af-magic and posh-git. :star:8
* [radium](https://github.com/dimitardimitrov/radium) - Designed for dark terminals, (works best with [Solarized](https://github.com/altercation/solarized) iTerm 2 theme) (prezto). :star:3
* [rafiki](https://github.com/akabiru/rafiki-zsh) - Adds emojis to your ZSH terminal. :star:37
* [random-emoji-robbyrussell](https://github.com/parwat08/random-emoji-robbyrussell) - Based on [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) and `robbyrussell` theme themes.
* [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - Random emoji.
* [remiii](https://github.com/Remiii/remiii.zsh-theme) - Based on agnoster, optimized for [solarized](https://github.com/altercation/solarized) terminal themes. :star:7
* [remolueoend](https://github.com/remolueoend/remolueoend.zsh-theme) - Prezto ZSH theme based on Sorin, using emojis for tracking GIT context.
* [river](https://github.com/revir/river-zsh-config) - Dark theme with `git` information.
* [robbyolivier](https://github.com/YuyeQingshan/robbyolivier) - Based on ideas from the the [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) theme and the project [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt). :star:1
* [robbyrussell-WIP](https://github.com/ecbrodie/robbyrussell-WIP-theme) - Decorates the `robbyrussell` theme with output to indicate a **WIP** commit. :star:1
* [rougarou](https://github.com/RougarouTheme/rougarou-zsh) - A dark theme. :star:1
* [rufus](https://github.com/runarsf/rufus-zsh-theme) - Optimized for dark backgrounds.
* [rummik](https://github.com/rummik/zsh-theme) - @rummik's theme. Supports [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin), and `git` status information in the prompt.
* [rzh](https://github.com/patwhatev/rzh) - Theme with git states indicated by emojis. :star:1
* [saraiva](https://github.com/ruisaraiva19/saraiva-theme) - Includes git status, works well on a dark terminal background. :star:1
* [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - Shows if Vim is running in the background when using `:sh` command.
* [seeker](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - This theme uses many special unicode characters to be fancy, but it may cause some problems without well supported fonts. :star:45
* [seltzer](https://github.com/GrantSeltzer/seltzer.zsh-theme) - Inspired by dieter theme, uses color-coding to provide information.
* [senpai](https://github.com/hiroru/senpai-zsh) - Clean prompt theme for Devops. Includes git information, kubernetes context, AWS profile, GCP project and Azure active cloud. :star:4
* [sepshell](https://github.com/sepehr/sepshell) - Clean and minimal ZSH theme based on the old lost taybalt theme, with `git` bisecting/merging/rebasing modes and configurable prompt symbols. :star:14
* [Seti_UX](https://github.com/ginfuru/iTerm-Seti_UX) - A simple omz-compatible theme with a corresponding iTerm 2 color scheme. :star:1
* [sfz](https://github.com/mreinhardt/sfz-prompt.zsh) - An evolution of lean prompt which itself is a rewrite of pure. :star:1
* [shayan](https://github.com/shayanh/shayan-zsh-theme) - Simple.
* [shellder](https://github.com/simnalamburt/shellder) - Minimal theme with git branch display. Requires a powerline font. :star:153
* [simplezsh](https://github.com/fr0zn/simplezsh) - Minimal theme with git info display.
* [shrug](https://github.com/tmjoseantonio/shrug-zsh-theme) - Simple theme which displays current directory and git information. :star:4
* [sinon](https://github.com/k-kinzal/oh-my-zsh-sinon-theme) - k-kinzal's sinon theme.
* [sk9](https://github.com/skeiter9/sk9-zsh) - Skeiter9's ZSH theme.
* [skeletor-syntax](https://github.com/ramonmcros/skeletor-syntax) - Theme collection for Atom, Prism and ZSH inspired by Skeletor from He-Man and the Masters of the Universe. :star:16
* [sleeplessmind](https://github.com/godbout/sleeplessmind-zsh-theme) - ZSH theme inspired by [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) and [odin](https://github.com/tylerreckart/odin).
* [slimline](https://github.com/mgee/slimline) - Minimal, fast and elegant ZSH prompt. Displays the right information at the right time. :star:30
* [smiley](https://github.com/gsamokovarov/smiley.zsh-theme) - A prompt with happy and sad faces. :star:5
* [sobole](https://github.com/sobolevn/sobole-zsh-theme) - A minimalistic ZSH theme inspired by the old-fashioned hobbies. No verbose gimmicks, no emoji, no fidget spinners, and no other visual noise. :star:45
* [solarized-powerline](https://github.com/houjunchen/solarized-powerline) - Solarized powerline-style theme for ZSH. :star:9
* [solarizsh](https://github.com/paddykontschak/Solarizsh) - Color fix for robbyrussell's oh-my-zsh theme to work with [solarized](https://github.com/altercation/solarized) terminals. :star:3
* [spaceship](https://github.com/denysdovhan/spaceship-prompt) - A ZSH theme with `git`, `nvm`, rvm/rbenv/chruby, python, `ssh` and other useful indicators. :star:5170
* [spowerline](https://mbauhardt.github.io/spowerline/) - Written in scala, inspired by agnoster, [tmux](https://tmux.github.io) powerline, vim powerline and the vim status plugin.
* [staples](https://github.com/dersam/staples) - Based on bureau, displays user@host if connected through SSH. :star:1
* [starboy](https://github.com/prdpx7/Starboy) - A simple ZSH theme
* [statusline](https://github.com/el1t/statusline) - A responsive ZSH theme that provides informational segments when you need them. :star:52
* [steef](https://github.com/danihodovic/steeef) - ZSH steeef theme as a standalone repository. The purpose behind this repo is avoid having a dependency on oh-my-zsh when using the steeef theme. ZSH plugin managers such as Antibody can use the theme without having to use oh-my-zsh. :star:2
* [sugar-free](https://github.com/cbrock/sugar-free) - Based on the [Pure](https://github.com/sindresorhus/pure) and [Candy](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/candy.zsh-theme) themes. :star:3
* [tabaf](https://github.com/bvc3at/tabaf-zsh-theme) - Minimal ZSH theme optimized for dark backgrounds. :star:3
* [tahuri](https://github.com/Tahuri/environment-configuration) - ZSH theme for Arch Linux.
* [termuxer](https://github.com/patrick330602/termuxer) - Theme inspired by agnoster and linuxer. :star:2
* [the-time-lord](https://github.com/jhwhite/the-time-lord) - A theme based on gallifrey.
* [theme-line](https://github.com/yw9381/oh-my-zsh_theme_line) - Colorful theme with `git` status. :star:9
* [theraveler](https://github.com/azah/the-raveler) - Based on theunraveler.
* [topan](https://github.com/fudyartanto/topan-theme-oh-my-zsh) - Includes `git` information; best on dark backgrounds. :star:1
* [tq](https://github.com/kitian616/tq-zsh-theme) - Displays `git` status, time, requires a Powerline font.
* [traffic](https://github.com/fcce/traffic-zsh-theme) - A dark theme for ZSH.
* [trajan](https://github.com/denisinla/trajan-zsh-theme) - A dark theme for ZSH. :star:1
* [trinity](https://github.com/de-luca/Trinity) - A simple theme based on [geometry](https://github.com/geometry-zsh/geometry).
* [tvline](https://github.com/thvitt/tvline) - Derived from [agnoster's theme](https://gist.github.com/agnoster/3712874), adds powerline font enhancements. :star:2
* [ultimate](https://github.com/b4b4r07/ultimate) - Minimalist theme with `git` indicator, vim mode indicator and shortened path. :star:7
* [vanan](https://github.com/avano/vanan-zsh-theme) - Minimalist theme with `git` information for dark terminals.
* [vinhnx](https://github.com/vinhnx/vinhnx.zsh-theme) - Modified from themes/mgutz.zsh-theme.Looks great when using with a [Solarized](https://github.com/altercation/solarized) color scheme. :star:7
* [vira](https://github.com/FernandoTorres/omz-vira) - An update of the bira theme that shows the `vim` bindkey -v status.
* [wade](https://github.com/wadehammes/wade.zsh-theme) - Mashup of the popular ZSH themes [Agnoster](https://gist.github.com/agnoster/3712874) and [Fishy](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/fishy.zsh-theme), with some visual tweaks. :star:4
* [wang-iterm-zsh](https://github.com/0532/wang-iterm-zsh) - Based on the 0532 theme. :star:5
* [webicons](https://github.com/Jmclerck/webicons.zsh-theme) - Includes `git` status, node and yarn versions in prompt. :star:2
* [wild-cherry](https://github.com/mashaal/wild-cherry) - A fairy-tale inspired theme for ZSH, iTerm 2, Sublime, Atom, & Mou. :star:367
* [work-line](https://github.com/afnizarnur/work-line) - Theme with nice emojis. :star:5
* [wynwyn](https://github.com/thaffenden/wynwyn.zsh-theme) - A theme that aims to show you the information you need when you need it. `wynwyn` takes inspiration from the default theme `avit` and the excellent [Spaceship prompt](https://github.com/denysdovhan/spaceship-prompt).
* [xremix](https://github.com/xremix/oh-my-zsh-xremix-theme) - An oh-my-zsh shell theme based on the Jreese theme plugin. :star:1
* [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - Shows the current git commit's shortened hash and message.
* [yairshefi](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme) - Minimal theme with line separated prompts. Based on [Robby Russell's theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) :star:78090
* [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) - Modified from [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) theme and optimized for a dark background.
* [ys-cluster](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme) - [ys](http://ysmood.org/my-ys-terminal-theme/) variant with support for working with batch submission systems for large clusters. Supports Slurm, LSF / IBM Spectrum LSF, and PBS.
* [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) - Clean, simple, compatible and meaningful theme meant for dark backgrounds.
* [ysm](https://github.com/hanbinpro/ysm-zsh-theme) - Simple ZSH theme with `git` status information.
* [yuki](https://github.com/yuki-torii/yuki-zsh-theme) - A dark optimized ZSH theme. :star:5
* [z4rr3t](https://github.com/inimicus/z4rr3t) - Based on sindresorhus' [pure](https://github.com/sindresorhus/pure) theme. :star:1
* [zemm-blinks](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - Customized version of oh-my-zsh [blinks](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/blinks.zsh-theme) with mercurial support and other changes. :star:7
* [zero](https://github.com/arlimus/zero.zsh) - Zero's theme & plugin. Has variants for both light and dark terminal backgrounds. :star:13
* [zeta](https://github.com/skylerlee/zeta-zsh-theme) - Shows username, `git` status information, machine name and the current working directory. :star:91
* [zqt](https://github.com/ladychili/zqt-zsh-theme) - Modified version of oh-my-zsh's [maran](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/maran.zsh-theme) theme. :star:1
* [zsh2000](https://github.com/inspectahstack/zsh2000) - Powerline looking ZSH theme which includes the `rvm` prompt, `git` status and branch, current time, user, hostname, pwd, exit status, whether running as root and background job status. :star:38
* [zshcomrade](https://github.com/landongn/zshcomrade) - A ZSH theme, comrade! :star:6
* [zwsh](https://github.com/naens/zwsh) - A Zpm3/Wordstar mode/theme for ZSH.
* [zys](https://github.com/ZYSzys/zys-zsh-theme) - Similar to agnoster-zsh-theme, designed to disclose information contextually, with a powerline aesthetic. :star:2

### Fonts

Some of the themes listed here require Powerline-compatible fonts, here are a few:

* [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) - A family of fonts that includes some nice monospaced Icons. :star:1541
* [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) - A nice monospaced font, patched with Font-Awesome, Octoicons and Powerline-Glyphs. :star:21
* [Fantasque-sans](https://github.com/belluzj/fantasque-sans) - Another powerline font. :star:3893
* [Hack](https://sourcefoundry.org/hack/) - Another Powerline-compatible font designed specifically for source code.
* [Input Mono](http://input.fontbureau.com/) - A family of fonts designed specifically for code. It offers both monospaced and proportional fonts and includes powerline glyphs.
* [Monoid](https://larsenwork.com/monoid/) - Monoid is customizable and optimized for coding with bitmap-like sharpness at 15px line-height even on low res displays.
* [nerd fonts](https://github.com/ryanoasis/nerd-fonts) - Collection of over 20 patched fonts (over 2,000 variations) & FontForge font patcher python script for Powerline, Font Awesome, Octicons, Devicons, and Vim Devicons. Includes: Droid Sans, Meslo, Source Code, AnonymousPro, Hack, ProFont, Inconsolata, and many more. :star:10699
* [Powerline patched font collection](https://github.com/powerline/fonts) - A collection of a dozen or so fonts patched to include powerline gylphs. :star:13515
* [Terminus](http://files.ax86.net/terminus-ttf/) - TTF version of Terminus that includes powerline glyphs.
* [Iosevka](https://github.com/be5invis/Iosevka) - Coders’ typeface, built from code. Highly customizable. :star:6552

## Installation

### [Antigen](https://github.com/zsh-users/antigen) / [Antibody](https://github.com/getantibody/antibody)

Most of these plugins can be installed by adding `antigen bundle githubuser/reponame` to your .zshrc file. Antigen will handle cloning the plugin for you automatically the next time you start `zsh`. You can also add the plugin to a running ZSH with `antigen bundle githubuser/reponame` for testing before adding it to your `.zshrc`.

[Antibody](https://github.com/getantibody/antibody) works the same, for example, `antibody bundle githubuser/reponame`.

### [dotzsh](https://github.com/dotphiles/dotzsh)

1. Clone new plugins into `.zsh.local/modules`
2. Load the plugin module in `.zshrc`
3. Open a new ZSH terminal window or tab

### [Oh-My-Zsh](http://ohmyz.sh/)

1. `cd ~/.oh-my-zsh/custom/plugins`
2. `git clone repo`
3. Add the repo to your plugin list

### [Prezto](https://github.com/sorin-ionescu/prezto)

1. Clone the plugin into your prezto modules directory
2. Add the plugin to your `.zpreztorc` file
3. Open a new terminal window or tab

### [Zgen](https://github.com/tarjoilija/zgen)

Most of these plugins can be installed by adding `zgen load githubuser/reponame` to your .zshrc file in the same function you're doing your other `zgen load` calls in. Zgen will automatically clone the repositories for you when you do a `zgen save`.

### [zplug](https://github.com/zplug/zplug)

Most of these plugins can be installed by adding `zplug "githubuser/reponame"` to your `.zshrc` file.

## Writing New Plugins

I've documented some recommendations for writing a new plugin [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins.md).

## Other Resources

### ZSH Tools

* [zshdb](https://github.com/rocky/zshdb) - A ZSH debugger :star:138
* [zunit](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH :star:59

### Other Useful Lists

* [awesome-devenv](https://github.com/jondot/awesome-devenv) - A curated list of awesome tools, resources and workflow tips making an awesome development environment :star:1266
* [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) - A curated list of awesome open source sysadmin resources :star:7216
* [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) - A curated list for CLI lovers. :star:6811

Find other useful awesome-* lists at the [awesome collection](https://github.com/sindresorhus/awesome)

### Other References

The [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) and [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) are indispensable.


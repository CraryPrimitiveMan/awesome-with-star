# Information comes from [alebcay/awesome-shell](https://github.com/alebcay/awesome-shell)
```
 █████╗ ██╗    ██╗███████╗███████╗ ██████╗ ███╗   ███╗███████╗
██╔══██╗██║    ██║██╔════╝██╔════╝██╔═══██╗████╗ ████║██╔════╝
███████║██║ █╗ ██║█████╗  ███████╗██║   ██║██╔████╔██║█████╗
██╔══██║██║███╗██║██╔══╝  ╚════██║██║   ██║██║╚██╔╝██║██╔══╝
██║  ██║╚███╔███╔╝███████╗███████║╚██████╔╝██║ ╚═╝ ██║███████╗
╚═╝  ╚═╝ ╚══╝╚══╝ ╚══════╝╚══════╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝
███████╗██╗  ██╗███████╗██╗     ██╗
██╔════╝██║  ██║██╔════╝██║     ██║
███████╗███████║█████╗  ██║     ██║
╚════██║██╔══██║██╔══╝  ██║     ██║
███████║██║  ██║███████╗███████╗███████╗
╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝╚══════╝
```

# Awesome Shell [![Awesome][awesome-badge]][awesome-link]

A curated list of awesome command-line frameworks, toolkits, guides and gizmos. Inspired by awesome-php. This awesome collection is also available on [Unix-Shell.ZEEF.com](https://unix-shell.zeef.com/caleb.xu).
- [Shells](#shells)
- [Command-Line Productivity](#command-line-productivity)
- [Customization](#customization)
- [For Developers](#for-developers)
- [System Utilities](#system-utilities)
- [Downloading and Serving](#downloading-and-serving)
- [Multimedia and File Formats](#multimedia-and-file-formats)
- [Applications](#applications)
- [Games](#games)
- [Shell Package Management](#shell-package-management)
- [Shell Script Development](#shell-script-development)
- [Guides](#guides)
- [**Awesome Zsh**][awesome-zsh]&nbsp; [![Awesome][awesome-badge]][awesome-zsh]
- [**Awesome Fish**][awesome-fish] [![Awesome][awesome-badge]][awesome-fish]
- [Other Awesome Lists](#other-awesome-lists)

## Shells

*Choose your base shell.*

* [bash](https://www.gnu.org/software/bash/) - GNU Project's shell (Bourne Again SHell)
* [elvish](https://elv.sh/) - Friendly, expressive shell features like anonymous functions and data structures
* [fish](https://fishshell.com) - Smart and user-friendly command line shell
* [ksh93](https://github.com/att/ast) - Korn Shell :star:271
* [mksh](https://github.com/MirBSD/mksh) - MirBSD Korn Shell :star:97
* [nushell](https://github.com/nushell/nushell) - A modern shell written in Rust  :star:6106
* [oksh](https://github.com/ibara/oksh) - Portable OpenBSD ksh :star:71
* [osh](https://www.oilshell.org) - Bash compatible, with new/modern Unix shell language called Oil
* [pdksh](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/bin/ksh/) - Public domain Korn shell
* [shell++](https://github.com/alexst07/shell-plus-plus) - Friendly and modern functional and object oriented shell script language :star:38
* [shenv](https://github.com/shenv/shenv) - Simple shell version management :star:15
* [tcsh](https://www.tcsh.org/) - C shell with file name completion and command line editing
* [xiki](http://xiki.org) - Makes the shell console more friendly and powerful
* [xonsh](https://xon.sh) - Python-ish, BASHwards-looking shell language and command prompt
* [yash](https://yash.osdn.jp/) - A POSIX-compliant command line shell with built-in support for completion and prediction based on command history
* [zsh](http://www.zsh.org) - Powerful shell with scripting language

## Command-Line Productivity

*Search, bookmarks, multiplexing, and other tools that make your terminal experience more productive.*

* [AdvancedNewFile](https://github.com/tanrax/terminal-AdvancedNewFile) - Fast creation of files and directories in a recursive way. Inspired by the Vim plugin. :star:90
* [ag](https://github.com/ggreer/the_silver_searcher) - Super fast string search through a directory hierarchy :star:19246
* [aliases](https://github.com/sebglazebrook/aliases) - Contextual, dynamic, organized aliases for bash :star:311
* [aliasme](https://github.com/Jintin/aliasme) - alias helper to change directory quickly :star:73
* [autoenv](https://github.com/inishchith/autoenv) - Directory-based environments :star:4438
* [autojump](https://github.com/wting/autojump) - A cd command that learns - easily navigate directories from the command line :star:10579
* [bashhub](https://github.com/rcaloras/bashhub-client) - :cloud: Bash history in the cloud. Indexed and searchable. :star:671
* [bashmarks](https://github.com/huyng/bashmarks) - Directory bookmarks for the shell :star:1494
* [bd](https://github.com/vigneshwaranr/bd) - Quickly go back to a parent directory :star:823
* [boilr](https://github.com/tmrts/boilr) - A blazingly fast CLI tool for creating projects from boilerplate templates. :star:1021
* [boom](https://github.com/holman/boom) - Store links and snippets in the commandline :star:1158
* [borg](https://github.com/ok-borg/borg) - A terminal based search engine for bash commands :star:1450
* [browsh](https://github.com/browsh-org/browsh) - The modern text-based browser :star:11490
* [Buku](https://github.com/jarun/Buku) - Powerful command-line bookmark manager :star:3170
* [byobu](https://byobu.org/) - Text-based window manager and terminal multiplexer
* [commacd](https://github.com/shyiko/commacd) - A faster way to move around in Bash :star:288
* [CloudClip](https://github.com/skywind3000/CloudClip) - Your own clipboard in the cloud, copy and paste text with gist between different systems :star:47
* [ddgr](https://github.com/jarun/ddgr) - DuckDuckGo from the terminal :star:1677
* [desk](https://github.com/jamesob/desk) - A lightweight workspace manager for the shell :star:2263
* [direnv](https://github.com/direnv/direnv) - An environment switcher for the shell, compare with autoenv :star:5573
* [dnote](https://github.com/dnote/dnote) - A simple, end-to-end encrypted notebook for developers :star:1392
* [enhancd](https://github.com/b4b4r07/enhancd) - :rocket: A next-generation cd command with an interactive filter :star:1337
* [fasd](https://github.com/clvv/fasd) - Command-line productivity booster, offers quick access to files and directories :star:4804
* [fd](https://github.com/sharkdp/fd) - A simple, fast and user-friendly alternative to find. :star:11743
* [foxy](https://github.com/s-p-k/foxy) - Plain text bookmarks for firefox and surf browsers. :star:22
* [fselect](https://github.com/jhspetersson/fselect) - Find files with SQL-like queries. :star:1530
* [funky](https://github.com/bbugyi200/funky) - Extends functionality of shell functions making them more powerful and flexible. :star:399
* [fz](https://github.com/changyuheng/fz) - Seamless fuzzy tab completion for z :star:288
* [fzf](https://github.com/junegunn/fzf) - A command-line fuzzy finder :star:26019
* [googler](https://github.com/jarun/googler) - Google Search, Google Site Search, Google News from the terminal :star:4109
* [googlr](https://github.com/Astranno/googlr) - Command line tool that lets you search Google from your terminal. :star:19
* [goto](https://github.com/iridakos/goto) - A shell utility for navigation to aliased directories supporting auto-completion :star:565
* [has](https://github.com/kdabir/has) - `has` helps you check presence of various command line tools and their versions on path :star:167
* [how2](https://github.com/santinic/how2) - `how2` finds the simplest way to do something in a unix shell. It's like `man`, but you can query it in natural language. :star:5046
* [navi](https://github.com/denisidoro/navi) - An interactive cheatsheet tool for the command-line :star:5358
* [hhighlighter](https://github.com/paoloantinori/hhighlighter) - Colorize words in a command output :star:312
* [hr](https://github.com/LuRsT/hr) - `<hr />` for your terminal :star:1124
* [hss](https://github.com/six-ddc/hss) - An interactive parallel ssh client featuring autocomplete and asynchronous execution :star:183
* [hstr](https://github.com/dvorka/hstr) - Bash History Suggest Box :star:1968
* [jump](https://github.com/gsamokovarov/jump) - Jump helps you navigate your file system faster by learning your habits. :star:755
* [k](https://github.com/supercrabtree/k) - k is a Zsh script to make directory listings more readable, adding Git status, fileweight colors and rotting dates :star:1236
* [k alias](https://github.com/lingtalfi/k) - get kool aliases (and more) working with a simple one-liner :star:13
* [lazy-cd](https://github.com/pedramamini/lazy-cd) - Simple bash commands for bookmarked navigation of the file system, complete with bash-completion. :star:15
* [lf.sh](https://github.com/suewonjp/lf.sh) - Quickly search files with fewer typings and do many more (grepping, copying path to clipboard, etc) :star:21
* [Lmod](https://lmod.readthedocs.io/en/latest/) - Lua-based Environment Modules that enhances Tcl-based modules while being backward compatible (compare to modules)
* [loop](https://github.com/Miserlou/Loop) - Write and control complex loops with as one-liners :star:386
* [marker](https://github.com/pindexis/marker) - Bookmark your shell commands :star:1679
* [mackup](https://github.com/lra/mackup/) - Keep your application settings in sync (OS X/Linux) :star:9381
* [mcfly](https://github.com/cantino/mcfly) - Fly through your shell history. Great Scot! :star:1569
* [modules](http://modules.sourceforge.net/) - Classical Tcl-based Environment Modules managing the shell environment (compare to Lmod, direnv, and autoenv)
* [nnn](https://github.com/jarun/nnn) - File browser and disk usage analyzer with excellent desktop integration :star:7036
* [parallel](http://www.gnu.org/software/parallel/) - Build and execute shell command lines from standard input in parallel
* [pathpicker](https://github.com/facebook/PathPicker) - Accepts inputs like grep, searches, git etc; allows selecting files from the result of the input, which you can then open or provide as argument to a command. :star:4292
* [pdd](https://github.com/jarun/pdd) - Tiny date, time diff calculator with timers :star:177
* [percol](https://github.com/mooz/percol) - Adds flavor of interactive filtering to the traditional pipe concept of UNIX shell :star:2856
* [q](https://github.com/cal2195/q) - Vim like macro registers for your Bash and Zsh Shell :star:33
* [qfc](https://github.com/pindexis/qfc) - File-completion widget for Bash and Zsh :star:491
* [rg](https://github.com/BurntSushi/ripgrep) - ripgrep is a line oriented search tool that combines the usability of The Silver Searcher with the raw speed of GNU grep :star:17432
* [screen](https://www.gnu.org/software/screen/) - GNU terminal multiplexer
* [shell-history](https://github.com/pawamoy/shell-history) - Visualize your shell usage with Highcharts :star:52
* [SHML](https://github.com/odb/shml) - Style framework for the terminal (Shell Markup Language) :star:400
* [slugify](https://github.com/benlinton/slugify) - Command that converts filenames and directories to a web friendly format :star:234
* [sman](https://github.com/tokozedg/sman) - :bug: A command-line snippet manager :star:199
* [spark](https://github.com/holman/spark) - ▁▂▃▅▂▇ in your shell :star:5444
* [shark](https://github.com/jorgebucaran/fish-spark) - ▁▂▃▅ Sparkline Generator :star:186
* [sheet](https://github.com/oscardelben/sheet) -  Text snippets for the command line :star:237
* [spot](https://github.com/rauchg/spot) - Tiny file search utility :star:853
- [snips](https://github.com/srijanshetty/snips) - Commandline tool to manage snippets of code. :star:33
* [sqlline](https://github.com/julianhyde/sqlline) - Shell for issuing SQL to relational databases via JDBC (multiline, completion, highlighting, dialect support) :star:301
* [sshfs](https://github.com/osxfuse/sshfs) - A tool for mounting remote file systems over SSH :star:728
* [sshrc](https://github.com/Russell91/sshrc) - Bring your .bashrc, .vimrc, etc. with you when you SSH :star:4633
* [sudocabulary](https://github.com/badarsh2/Sudocabulary) - Learn English Vocabulary from your terminal :star:124
* [surfraw](https://gitlab.com/surfraw/Surfraw) - browse specific site and search the web from your terminal without browser.
* [task-manager](https://github.com/lingtalfi/task-manager) - Execute all your scripts with just two or three keystrokes. :star:7
* [td-cli](https://github.com/darrikonn/td-cli) - A todo command line manager to organize and manage your todos across multiple projects. :star:77
* [thefuck](https://github.com/nvbn/thefuck) - Fix common shell mistakes by using an easy to remember command :star:51140
* [tldr](https://github.com/raylee/tldr) - A fully-functional bash client for tldr, simplified and community-driven man pages :star:451
* [tmux](http://tmux.github.io/) - Amazing terminal multiplexer
* [undollar](https://github.com/ImFeelingDucky/undollar) - undollar bites the dollar sign off the tip of the command you just pasted into your terminal :star:43
* [up](https://github.com/shannonmoeller/up) - Ascend directories by name or count; for bash, zsh, and fish. :star:103
* [v](https://github.com/rupa/v) - z for vim. :star:349
* [wemux](https://github.com/zolrath/wemux) - Multi-User Tmux Made Easy :star:3245
* [xsv](https://github.com/BurntSushi/xsv) - a fast CSV command line toolkit written in Rust :star:5099
* [z](https://github.com/rupa/z) - z is the new j, yo :star:11022
* [z.lua](https://github.com/skywind3000/z.lua) - A new cd command that helps you navigate faster by learning your habits :star:1346

## Customization

*Custom prompts, color themes, etc.*

* [base16-builder](https://github.com/base16-builder/base16-builder) - Base16-Builder :star:332
* [bash-full-of-colors](https://github.com/slomkowski/bash-full-of-colors) - Powerful prompt with screen, tmux, git support and many more :star:84
* [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) - An informative and fancy Bash prompt for Git users :star:5326
* [bash-powerline](https://github.com/riobard/bash-powerline) - Powerline-style Bash prompt in pure Bash script :star:730
* [bashstrap](https://github.com/barryclark/bashstrap) - A quick way to spruce up OSX terminal :star:1543
* [bullet-train-oh-my-zsh-theme](https://github.com/caiogondim/bullet-train.zsh) - :bullettrain_side: An oh-my-zsh shell theme based on the Powerline Vim plugin :star:2361
* [emojify](https://github.com/mrowa44/emojify) Emoji on the command line :scream:
* [flatui-terminal-theme](https://dribbble.com/shots/1021755-Flat-UI-Terminal-Theme) - Nicer colors for terminal
* [git-prompt](https://github.com/lvv/git-prompt) - Bash prompt with Git, SVN and HG modules :star:326
* [gittify](https://github.com/momeni/gittify) - A colorful Bash prompt + customized Git aliases :star:48
* [Gogh - Color Scheme](https://github.com/Mayccoll/Gogh) - Color Scheme for Gnome Terminal :star:4050
* [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt for Bash & Zsh :star:3870
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) -  Colorization for mysql comand-line client :star:72
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - An opinionated git prompt for bash and zsh :star:3287
* [polyglot](https://github.com/agkozak/polyglot) - An informative Git prompt that works in bash, zsh, ksh, mksh, pdksh, dash, and busybox sh :star:74
* [sexy-bash-prompt](https://github.com/twolfson/sexy-bash-prompt) - Bash prompt with colors, Git statuses, and Git branches :star:983

## For Developers

*Command-line development, version control, and deployment.*

* [ack](https://beyondgrep.com/) - A grep-like search tool optimized for source code.
* [add-gitignore](https://github.com/TejasQ/add-gitignore) - Interactive CLI that generates a .gitignore for your project based on your needs. :star:392
* [bcal](https://github.com/jarun/bcal) - Byte CALculator for storage conversions and calculations :star:236
* [bitwise](https://github.com/mellowcandle/bitwise) - Terminal based interactive bit manipulator in curses. :star:295
* [bocker](https://github.com/p8952/bocker) - Docker implemented in 100 lines of bash :star:5714
* [cloc](https://github.com/AlDanial/cloc) - Count Lines of Code :star:8588
* [doclt](https://github.com/omgimanerd/doclt) - A command line interface to Digital Ocean :star:29
* [dokku](https://github.com/dokku/dokku) - Docker powered mini-Heroku. The smallest PaaS implementation you've ever seen. :star:18519
* [fish-getopts](https://github.com/jorgebucaran/fish-getopts) - CLI parser for fish :star:138
* [forgit](https://github.com/wfxr/forgit) - Utility tool for `git` taking advantage of fuzzy finder fzf. :star:488
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - Many Git extra utilities. Churn, cut-branch, improved-merge and many more. :star:502
* [git-extras](https://github.com/tj/git-extras) - Git utilities -- repo summary, repl, changelog population, author commit percentages and more :star:13322
* [git-open](https://github.com/paulirish/git-open) - Type `git open` to open the GitHub page or website for a repository in your browser :star:2036
* [git-quick-stats](https://github.com/arzzen/git-quick-stats) - Git quick statistics is a simple and efficient way to access various statistics in git repository. :star:3571
* [git-semver](https://github.com/markchalloner/git-semver) - Git plugin for easing semantic versioning and changelog validation :star:249
* [git-sh](https://github.com/rtomayko/git-sh) - A customized Bash environment suitable for Git work :star:708
* [hub](https://github.com/github/hub) - hub helps you win at git. :star:18224
* [licins](https://github.com/dogoncouch/licins) - Insert commented software licenses into source code. :star:13
* [mr](https://myrepos.branchable.com) - Multiple Repository management tool
* [overcommit](https://github.com/sds/overcommit) - A fully configurable and extendable Git hook manager :star:3143
* [pre-commit](https://pre-commit.com) - A framework for managing and maintaining multi-language pre-commit hooks
* [rebound](https://github.com/shobrook/rebound) - Instantly browse Stack Overflow results in your terminal when you get a compiler error :star:3067
* [repren](https://github.com/jlevy/repren) - Command-line search-and-replace and file-renaming swiss army knife :star:243
* [slap](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor that runs on Node.js :star:5313
* [shipit](https://github.com/sapegin/shipit) - Minimalistic SSH deployment :star:494
* [starring](https://github.com/ritz078/starring) - Automatically star the npm-packages that you are using on GitHub. :star:134
* [tag](https://github.com/aykamko/tag) - Instantly jump to your ag matches. :star:526
* [wipe-modules](https://github.com/bntzio/wipe-modules) - A little agent that removes the node_modules folder of non-active projects :star:263
* [xtm](https://github.com/Camji55/xtm) - Command line tool that helps you manage your Xcode project templates. :star:19

## System Utilities

*OS-related tools, including system administration, system debugging, and file and process management.*

* [atop](https://www.atoptool.nl) - ASCII full-screen performance monitor that is capable of reporting the activity of all processes
* [bat](https://github.com/sharkdp/bat) - A `cat` clone with wings :star:17038
* [bmon](https://github.com/tgraf/bmon) - Real-time network bandwidth monitor and rate estimator with human-friendly visual output :star:628
* [catcli](https://github.com/deadc0de6/catcli) -  The command line catalog tool for your offline data :star:53
* [ccat](https://github.com/jingweno/ccat) - ccat is the colorizing cat. It works similar to cat but displays content with syntax highlighting. :star:2665
* [exa](https://github.com/ogham/exa) - A modern version of `ls`. :star:8189
* [progress](https://github.com/Xfennec/progress) - Linux tool to show progress for `cp`, `rm`, `dd`, and more... :star:4817
* [stronghold](https://github.com/alichtman/stronghold) - Easily configure MacOS security settings from the terminal. :star:638
* [glances](https://github.com/nicolargo/glances) - Glances an Eye on your system :star:14797
* [goaccess](https://github.com/allinurl/goaccess) - GoAccess is a real-time web log analyzer and interactive viewer that runs in a terminal in \*nix systems. :star:10489
* [hblock](https://github.com/hectorm/hblock) - Hosts-file based adblocker :star:414
* [histstat](https://github.com/vesche/histstat) - History for netstat :star:67
* [htop](https://github.com/hishamhm/htop) - A ncurses based interactive process viewer which aims to be a better `top` :star:4630
* [lnav](http://lnav.org) - An advanced log file viewer for the small-scale
* [logdissect](https://github.com/dogoncouch/logdissect) - CLI utility and Python API for analyzing log files and other data. :star:57
* [ls++](https://github.com/trapd00r/ls--) - Colorized ls on steroids :star:438
* [lsp](https://github.com/dborzov/lsp) - An improved `ls`, with file descriptions in plain language and intelligent file grouping :star:479
* [mtr](https://github.com/traviscross/mtr) - The functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool. :star:1305
* [ncdu](https://dev.yorhel.nl/ncdu) - NCurses Disk Usage
* [nmtui](https://github.com/NetworkManager/NetworkManager) - Text User Interface for controlling NetworkManager :star:130
* [powertop](https://github.com/fenrus75/powertop) - Battery/Power usage and device stats monitoring command-line tool, with tune-up options. :star:389
* [procdog](https://github.com/jlevy/procdog) - Lightweight command-line control of long-lived processes like servers :star:67
* [quick-secure](https://github.com/marshyski/quick-secure) - Quickly secure and harden UNIX/Linux systems :star:342
* [rng](https://github.com/nickolasburr/rng) - Copy range of lines from file or stdin to stdout. :star:8
* [wifi-wand](https://github.com/keithrbennett/wifiwand) - a Ruby command line application for managing WiFi on MacOS (install by `gem install wifi-wand`) :star:52
* [xiringuito](https://github.com/ivanilves/xiringuito) - SSH-based "VPN for poors" :star:914

## Downloading and Serving

*Self-hosted, lightweight servers and networking tools written in shell scripts.*

* [aria2](https://github.com/aria2/aria2) - aria2 is a lightweight multi-protocol & multi-source, cross platform download utility operated in command-line. It supports HTTP/HTTPS, FTP, BitTorrent and Metalink :star:18033
* [balls](https://github.com/jneen/balls) - Bash on Balls :star:780
* [bashttpd](https://github.com/avleen/bashttpd) - A web server written in Bash :star:1170
* [bitpocket](https://github.com/sickill/bitpocket) - "DIY Dropbox" or "2-way directory (r)sync with proper deletion" :star:976
* [Dropbox-Uploader](https://github.com/andreafabrizi/Dropbox-Uploader) - Dropbox Uploader is a Bash script which can be used to upload, download, list or delete files from Dropbox :star:5885
* [httpie](https://github.com/jakubroztocil/httpie) - HTTPie is a command line HTTP client, a user-friendly cURL replacement :star:45189
* [HTTPLab](https://github.com/gchaincl/httplab) - The interactive web server, let you inspect HTTP requests and forge responses. :star:3504
* [ngincat](https://github.com/jaburns/ngincat) - Tiny Bash HTTP server using netcat :star:147
* [resty](https://github.com/micha/resty) - Little command line REST client that you can use in pipelines :star:2461
* [shell2http](https://github.com/msoap/shell2http) - HTTP-server to execute shell commands. Designed for development, prototyping or remote control :star:482
* [vesper](https://github.com/chris-rock/vesper) - 🍸Vesper is a HTTP framework for Bash/Unix Shell :star:140
* [youtube-dl](https://github.com/ytdl-org/youtube-dl) - Small command-line program to download videos from YouTube.com and other video sites :star:59499

## Multimedia and File Formats

*Tools for handling video and audio files.*

* [adb-export](https://github.com/sromku/adb-export) - Export Android content providers to CSV format :star:66
* [Android-Kitchen](https://github.com/dsixda/Android-Kitchen) - A text-based kitchen for Android ROM customization. Uses shell scripts and works with Cygwin/OS X/Linux :star:879
* [Beets](https://github.com/beetbox/beets) - Music library manager and MusicBrainz tagger :star:9081
* [cmus](https://github.com/cmus/cmus) - Cross-platform cli audio player. :star:3542
* [fx](https://github.com/antonmedv/fx) - Command-line JSON processing tool by anononymus JavaScript functions :star:9267
* [gifgen](https://github.com/lukechilds/gifgen) - Simple high quality GIF encoding :star:337
* [image-scraper](https://github.com/sananth12/ImageScraper) - A cool command line image scraper with a lot of features. :star:551
* [imgp](https://github.com/jarun/imgp) - Blazing fast batch image resizer and rotator :star:591
* [jo](https://github.com/jpmens/jo) - A small utility to create JSON objects from command-line arguments. :star:2670
* [jq](https://github.com/stedolan/jq) - Sed for json data. You can use it to slice and filter and map and transform structured data :star:15939
* [korkut](https://github.com/oguzhaninan/korkut) - Quick and simple image processing at the command line. :star:254
* [mpv](https://mpv.io/) - Lets you play most audio and video formats (using ASCII characters) in the shell as well as in a GUI.
* [nehm](https://github.com/bogem/nehm) - Console tool, which downloads, sets IDv3 tags and adds to your iTunes (if you use it) your SoundCloud likes in convenient way :star:85
* [PiCAST](https://github.com/lanceseidman/PiCAST) - PiCAST turns your $35 Raspberry Pi in to a Chromecast like Device :star:1612
* [sejda](https://github.com/torakiki/sejda/) - Command line manipulation of PDF documents (split, merge, rotate, convert to jpg, extract text, etc) :star:283
* [xidel](https://github.com/benibela/xidel/) - Cli tool to filter, map and create HTML/XML/JSON data with (Turing-complete) XPath and XQuery. :star:240
* [xmlstarlet](http://xmlstar.sourceforge.net/) - Old but powerful tool for command-line XML formatting, filtering, and manipulation.

## Applications

*Command line-based applications or command line access to existing services.*

* [ansiweather](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols :star:1493
* [awless](https://github.com/wallix/awless) - A powerful, innovative and small surface CLI to manage AWS. :star:4479
* [bashblog](https://github.com/cfenollosa/bashblog) - A Bash script that handles blog posting :star:887
* [carbon-now-cli](https://github.com/mixn/carbon-now-cli) - 🎨 Beautiful images of your code — from right inside your terminal. :star:4343
* [choosealicense-cli](https://github.com/lord63/choosealicense-cli) - Choose an OSS license from the comfort of your terminal :star:48
* [cointop](https://github.com/miguelmota/cointop) - The fastest and most interactive terminal based UI application for tracking cryptocurrencies :star:1301
* [facebook-cli](https://github.com/specious/facebook-cli) - Facebook command line tool :star:304
* [fanyi](https://github.com/afc163/fanyi) - Translate English to Chinese in terminal :star:818
* [gcalcli](https://github.com/insanum/gcalcli) - Google Calendar command line interface :star:1924
* [geeknote](https://github.com/VitaliyRodnenko/geeknote) - Command line evernote client :star:2056
* [haxor-news](https://github.com/donnemartin/haxor-news) - Browse Hacker News like a haxor :star:3047
* [hn-cli](https://github.com/rafaelrinaldi/hn-cli) - Browse Hacker News from the comfort of your Terminal :star:440
* [iponmap](https://github.com/nogizhopaboroda/iponmap) - Draw point on world map using ip address :star:222
* [isitup](https://github.com/lord63/isitup) - Check whether a website is up or down :star:41
* [jrnl](https://github.com/jrnl-org/jrnl) - A simple command line journal application that stores your journal in a plain text file :star:3911
* [ledger](https://github.com/ledger/ledger) - Command line accounting :star:3121
* [licen](https://github.com/lord63/licen) - Generate your license. Yet another lice, but implement with Jinja2 and docopt :star:30
* [md2png](https://github.com/weaming/md2png) - Convert markdown to PNG image :star:9
* [moviemon](https://github.com/iCHAIT/moviemon) - Everything about your movies within the command line. :star:146
* [pockyt](https://github.com/arvindch/pockyt) - Read, Manage, and Automate your [Pocket](https://getpocket.com) collection. :star:348
* [pushblast](https://github.com/alebcay/pushblast) - Get PushBullet notifications when a shell program exits :star:91
* [pushbullet-bash](https://github.com/Red5d/pushbullet-bash) - Bash interface to the PushBullet API :star:215
* [ranger](https://github.com/ranger/ranger) - A console file manager with VI key bindings. :star:6744
* [Reddit Terminal Viewer](https://github.com/michael-lazar/rtv) - Browse Reddit from your terminal :star:4404
* [SAWS](https://github.com/donnemartin/saws) - A Supercharged AWS CLI :star:4316
* [taskbook](https://github.com/klaussinani/taskbook) - Tasks, boards & notes for the command-line habitat :star:7303
* [taskwarrior](https://taskwarrior.org/) - A command-line TODO list manager
* [terjira](https://github.com/keepcosmos/terjira) - Command line power tool for Jira :star:628
* [transfer.sh](https://transfer.sh/) — Quickly upload and share files from your shell
* [vl](https://github.com/ellisonleao/vl) - URL link checker on text documents :star:50
* [wego](https://github.com/schachmat/wego) - Weather app for the terminal :star:6148
* [whales](https://github.com/Gueils/whales) - A tool to automatically dockerize your applications :star:206
* [whereami](https://github.com/rafaelrinaldi/whereami) - Get your geolocation information from the CLI :star:125
* [wttr.in](https://github.com/chubin/wttr.in) - :partly_sunny: The right way to check the weather (curl wttr.in) :star:9441

## Games

*All work and no play is a cruddy way to spend your day.*

* [bash2048](https://github.com/mydzor/bash2048) - Bash implementation of 2048 game :star:749
* [minesweeper](https://github.com/feherke/Bash-script/tree/master/minesweeper) - Bash implementation of minesweeper :star:32
* [nudoku](https://github.com/jubalh/nudoku) - ncurses based sudoku game written in C :star:151
* [piu-piu](https://github.com/vaniacer/piu-piu-SH) - Horizontal scroller game in bash with multiplayer mode! :star:583
* [sedtris](https://github.com/uuner/sedtris) - Tetris in sed :star:323
* [sed-scripts](https://github.com/aureliojargas/sed-scripts) - Arkanoid and Sokoban written using sed :star:33
* [SHTAP](https://notimetoplay.org/engines/shtap/) - Reusable text adventure engine for Bash 4
* [tty-solitaire](https://github.com/mpereira/tty-solitaire) - Play solitaire in your terminal! :star:146

## Shell Package Management

*Tools for managing multiple shell configurations. For zsh-specific tools, see the Zsh section.*

* [bash-it](https://github.com/Bash-it/bash-it) - A community Bash framework :star:11027
* [basher](https://github.com/basherpm/basher) - A package manager for shell scripts :star:606
* [bashing](https://github.com/xsc/bashing) - Smashing Bash into Pieces :star:39
* [bpkg](http://www.bpkg.sh/) - JavaScript has npm, Ruby has Gems, Python has pip and now Shell has bpkg
* [dotdrop](https://github.com/deadc0de6/dotdrop) - Save your dotfiles once, deploy them everywhere :star:547
* [dotfiler](https://github.com/svetlyak40wt/dotfiler) – Shell agnostic git based dotfiles package manager, written in Python.
* [fresh](https://github.com/freshshell/fresh) - Keep your dotfiles fresh :star:942
* [homeshick](https://github.com/andsens/homeshick) - Git dotfile synchronizer written in Bash :star:1535
* [shallow-backup](https://github.com/alichtman/shallow-backup) - Easily create lightweight documentation of installed packages, dotfiles, and more :star:493
* [shundle](https://github.com/javier-lopez/shundle) - Plugin manager for shell scripts :star:73
* [vcsh](https://github.com/RichiH/vcsh) - Config manager based on Git :star:1579
* [yadm](https://yadm.io/) - Git-based dotfiles manager supporting encryption, alternates, and bootstrapping

## Shell Script Development

*Tools for writing, improving, or organizing Bash or other shell scripts*

* [ansi](https://github.com/fidian/ansi) - ANSI escape codes in pure bash - change text color, position the cursor, much more :star:282
* [assert.sh](https://github.com/lehmannro/assert.sh) - Bash unit testing framework :star:412
* [bashful](https://github.com/jmcantrell/bashful) - A collection of libraries to simplify writing Bash scripts :star:439
* [Bashlets](https://github.com/reale/bashlets) - A modular extensible toolbox for Bash :star:45
* [bashmanager](https://github.com/lingtalfi/bashmanager) - mini bash framework for creating command line tools :star:67
* [bashwithnails](https://github.com/mindaugasbarysas/bashwithnails) - a Bash framework written just for fun with testing, dependency management & packaging :star:9
* [bash-language-server](https://github.com/mads-hartmann/bash-language-server) - [LSP](https://microsoft.github.io/language-server-protocol/)-based Bash language server :star:382
* [bats](https://github.com/bats-core/bats-core) - Bash Automated Testing System :star:1275
* [crash](https://github.com/molovo/crash) - Proper error handling, exceptions and try/catch for ZSH :star:31
* [Fishtape](https://github.com/jorgebucaran/fishtape) - TAP producer and test harness for fish :star:246
* [composure](https://github.com/erichs/composure) - Compose, document, version and organize your shell functions :star:243
* [dispatch](https://github.com/Mosai/workshop/blob/master/doc/dispatch.md) - A command line argument parser in 50 lines of portable shell script. :star:82
* [is.sh](https://github.com/qzb/is.sh) - An alternative for builtin test command, it will make your "if" statements pretty :star:90
* [lumberjack](https://github.com/molovo/lumberjack) - A logging interface for shell scripts :star:25
* [mo](https://github.com/tests-always-included/mo) - Mustache templates in pure bash :star:316
* [optparse](https://github.com/nk412/optparse) - A BASH wrapper for getopts, for simple command line arguments. :star:114
* [rerun](https://github.com/rerun/rerun) - A modular shell automation framework to organize your keeper scripts :star:369
* [revolver](https://github.com/molovo/revolver) - A reusable progress spinner for shell scripts :star:78
* [phases](https://github.com/sorokine/phases) - Minimally invasive bash preprocessor, select sections of your script to run :star:8
* [semver_bash](https://github.com/cloudflare/semver_bash) - Semantic Versioning in Bash :star:157
* [sh-semver](https://github.com/qzb/sh-semver) - Semver tool for bash - finds versions matching to specified rules :star:20
* [shellcheck](https://github.com/koalaman/shellcheck) - Static analysis tool for shell scripts :star:17561
* [shellfire](https://github.com/shellfire-dev/shellfire) -  A repository of namespaced, composable shell (bash, sh and dash) function libraries :star:1135
* [shpec](https://github.com/rylnd/shpec) - A shell testing framework :star:332
* [shutit](https://ianmiell.github.io/shutit/) - Automation framework based on bash and pexpect
* [sub](https://github.com/basecamp/sub) - A delicious way to organize programs :star:1550
* [ts](https://github.com/thinkerbot/ts) - A shell test script :star:44
* [urchin](https://github.com/tlevine/urchin) - An idiomatic shell testing framework that uses only shell commands :star:185
* [shunit2](https://github.com/kward/shunit2) - A unit test framework for Bash scripts with a flavour of JUnit/PyUnit. :star:825
* [rebash](https://github.com/jandob/rebash) - Scripting library/framework. Features: imports, exceptions, doc-tests ... :star:50
* [zunit](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH :star:95

# Guides

* [Bash Hackers Wiki](https://wiki.bash-hackers.org/)
* [Greg Wooledge's (aka "greycat") wiki](http://mywiki.wooledge.org).
  Specifically [Bash Guide](http://mywiki.wooledge.org/BashGuide), [Bash FAQ](http://mywiki.wooledge.org/BashFAQ) and [Bash Pitfalls](http://mywiki.wooledge.org/BashPitfalls)
* [Google's Shell Style Guide](https://google.github.io/styleguide/shell.xml)
* [The Linux Documentation Project: Bash Programming - Intro/How-to](http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html#toc)
* [The Linux Documentation Project: Advanced Bash Scripting Guide](http://www.tldp.org/LDP/abs/html/)
* [WikiBooks: Bash Shell Scripting](https://en.wikibooks.org/wiki/Bash_Shell_Scripting)
* [Use the Unofficial Bash Strict Mode (Unless You Looove Debugging)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
* [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) :star:66991
* [Learn Enough Command Line to Be Dangerous](https://www.learnenough.com/command-line-tutorial/basics)
* [A guide to learn bash](https://github.com/Idnan/bash-guide) :star:9331

# Other Awesome Lists

Other amazingly awesome lists can be found in [awesome-awesome](https://github.com/emijrp/awesome-awesome) and [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).

### See also

* [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps) :star:5148
* [awesome-fish][awesome-fish]
* [awesome-zsh][awesome-zsh]
* [terminals-are-sexy](https://github.com/k4m4/terminals-are-sexy) :star:8668

[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
[awesome-fish]: https://github.com/jorgebucaran/awesome-fish
[awesome-link]: https://github.com/sindresorhus/awesome
[awesome-zsh]: https://github.com/unixorn/awesome-zsh-plugins


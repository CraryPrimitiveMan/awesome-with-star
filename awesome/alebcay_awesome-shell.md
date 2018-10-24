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
* [shenv](https://github.com/shenv/shenv) - Simple shell version management :star:3
* [xiki](http://xiki.org) - Makes the shell console more friendly and powerful
* [xonsh](https://xonsh.org) - Python-ish, BASHwards-looking shell language and command prompt
* [zsh](http://www.zsh.org) - Powerful shell with scripting language

## Command-Line Productivity

*Search, bookmarks, multiplexing, and other tools that make your terminal experience more productive.*

* [AdvancedNewFile](https://github.com/tanrax/terminal-AdvancedNewFile) - Fast creation of files and directories in a recursive way. Inspired by the Vim plugin. :star:33
* [ag](https://github.com/ggreer/the_silver_searcher) - Super fast string search through a directory hierarchy :star:16207
* [aliases](https://github.com/sebglazebrook/aliases) - Contextual, dynamic, organized aliases for bash :star:186
* [aliasme](https://github.com/Jintin/aliasme) - alias helper to change directory quickly :star:46
* [autoenv](https://github.com/kennethreitz/autoenv) - Directory-based environments :star:4120
* [autojump](https://github.com/wting/autojump) - A cd command that learns - easily navigate directories from the command line :star:8221
* [bashhub](https://github.com/rcaloras/bashhub-client) - :cloud: Bash history in the cloud. Indexed and searchable. :star:527
* [bashmarks](https://github.com/huyng/bashmarks) - Directory bookmarks for the shell :star:1347
* [bd](https://github.com/vigneshwaranr/bd) - Quickly go back to a parent directory :star:761
* [boilr](https://github.com/tmrts/boilr) - A blazingly fast CLI tool for creating projects from boilerplate templates. :star:788
* [boom](https://github.com/holman/boom) - Store links and snippets in the commandline :star:1113
* [borg](https://github.com/ok-borg/borg) - A terminal based search engine for bash commands :star:1378
* [Buku](https://github.com/jarun/Buku) - Powerful command-line bookmark manager :star:2114
* [byobu](http://byobu.co/) - Text-based window manager and terminal multiplexer
* [commacd](https://github.com/shyiko/commacd) - A faster way to move around in Bash :star:218
* [CloudClip](https://github.com/skywind3000/CloudClip) - Your own clipboard in the cloud, copy and paste text with gist between different systems :star:32
* [desk](https://github.com/jamesob/desk) - A lightweight workspace manager for the shell :star:2093
* [direnv](https://github.com/direnv/direnv) - An environment switcher for the shell, compare with autoenv :star:4045
* [enhancd](https://github.com/b4b4r07/enhancd) - :rocket: A next-generation cd command with an interactive filter :star:936
* [fasd](https://github.com/clvv/fasd) - Command-line productivity booster, offers quick access to files and directories :star:4032
* [fd](https://github.com/sharkdp/fd) - A simple, fast and user-friendly alternative to find. :star:7072
* [foxy](https://github.com/s-p-k/foxy) - Plain text bookmarks for firefox and surf browsers. :star:15
* [fz](https://github.com/changyuheng/fz) - Seamless fuzzy tab completion for z :star:183
* [fzf](https://github.com/junegunn/fzf) - A command-line fuzzy finder :star:17475
* [googler](https://github.com/jarun/googler) - Google Search, Google Site Search, Google News from the terminal :star:2790
* [googlr](https://github.com/Camji55/googlr) - Command line tool that lets you search Google from your terminal. :star:1
* [goto](https://github.com/iridakos/goto) - A shell utility for navigation to aliased directories supporting auto-completion :star:428
* [has](https://github.com/kdabir/has) - `has` helps you check presence of various command line tools and their versions on path :star:69
* [how2](https://github.com/santinic/how2) - `how2` finds the simplest way to do something in a unix shell. It's like `man`, but you can query it in natural language. :star:4776
* [hhighlighter](https://github.com/paoloantinori/hhighlighter) - Colorize words in a command output :star:267
* [hr](https://github.com/LuRsT/hr) - `<hr />` for your terminal :star:1077
* [hss](https://github.com/six-ddc/hss) - An interactive parallel ssh client featuring autocomplete and asynchronous execution :star:113
* [hstr](https://github.com/dvorka/hstr) - Bash History Suggest Box :star:1345
* [jump](https://github.com/gsamokovarov/jump) - Jump helps you navigate your file system faster by learning your habits. :star:514
* [k](https://github.com/supercrabtree/k) - k is a Zsh script to make directory listings more readable, adding Git status, fileweight colors and rotting dates :star:973
* [k alias](https://github.com/lingtalfi/k) - get kool aliases (and more) working with a simple one-liner :star:8
* [lazy-cd](https://github.com/pedramamini/lazy-cd) - Simple bash commands for bookmarked navigation of the file system, complete with bash-completion. :star:13
* [lf.sh](https://github.com/suewonjp/lf.sh) - Quickly search files with fewer typings and do many more (grepping, copying path to clipboard, etc) :star:13
* [Lmod](https://lmod.readthedocs.io/en/latest/) - Lua-based Environment Modules that enhances Tcl-based modules while being backward compatible (compare to modules)
* [marker](https://github.com/pindexis/marker) - Bookmark your shell commands :star:779
* [modules](http://modules.sourceforge.net/) - Classical Tcl-based Environment Modules managing the shell environment (compare to Lmod, direnv, and autoenv)
* [nnn](https://github.com/jarun/nnn) - File browser and disk usage analyzer with excellent desktop integration :star:1499
* [parallel](http://www.gnu.org/software/parallel/) - Build and execute shell command lines from standard input in parallel
* [pathpicker](https://github.com/facebook/PathPicker) - Accepts inputs like grep, searches, git etc; allows selecting files from the result of the input, which you can then open or provide as argument to a command. :star:3935
* [percol](https://github.com/mooz/percol) - Adds flavor of interactive filtering to the traditional pipe concept of UNIX shell :star:2619
* [q](https://github.com/cal2195/q) - Vim like macro registers for your Bash and Zsh Shell :star:22
* [qfc](https://github.com/pindexis/qfc) - File-completion widget for Bash and Zsh :star:455
* [rg](https://github.com/BurntSushi/ripgrep) - ripgrep is a line oriented search tool that combines the usability of The Silver Searcher with the raw speed of GNU grep :star:11099
* [shell-history](https://github.com/pawamoy/shell-history) - Visualize your shell usage with Highcharts :star:12
* [SHML](https://github.com/odb/shml) - Style framework for the terminal (Shell Markup Language) :star:362
* [slugify](https://github.com/benlinton/slugify) - Command that converts filenames and directories to a web friendly format :star:214
* [sman](https://github.com/tokozedg/sman) - :bug: A command-line snippet manager :star:174
* [spark](https://github.com/holman/spark) - ▁▂▃▅▂▇ in your shell :star:5198
* [Shark](https://github.com/fisherman/shark) - ▁▂▃▅ Sparkline Generator :star:159
* [sheet](https://github.com/oscardelben/sheet) -  Text snippets for the command line :star:234
* [spot](https://github.com/rauchg/spot) - Tiny file search utility :star:796
- [snips](https://github.com/srijanshetty/snips) - Commandline tool to manage snippets of code. :star:29
* [sshfs](https://github.com/osxfuse/sshfs) - A tool for mounting remote file systems over SSH :star:620
* [sshrc](https://github.com/Russell91/sshrc) - Bring your .bashrc, .vimrc, etc. with you when you SSH :star:4211
* [sudocabulary](https://github.com/badarsh2/Sudocabulary) - Learn English Vocabulary from your terminal :star:102
* [surfraw](https://gitlab.com/surfraw/Surfraw) - browse specific site and search the web from your terminal without browser.
* [task-manager](https://github.com/lingtalfi/task-manager) - Execute all your scripts with just two or three keystrokes. :star:2
* [thefuck](https://github.com/nvbn/thefuck) - Fix common shell mistakes by using an easy to remember command :star:38232
* [tldr](https://github.com/raylee/tldr) - A fully-functional bash client for tldr, simplified and community-driven man pages :star:279
* [tmux](http://tmux.github.io/) - Amazing terminal multiplexer
* [undollar](https://github.com/ImFeelingDucky/undollar) - undollar bites the dollar sign off the tip of the command you just pasted into your terminal :star:15
* [up](https://github.com/shannonmoeller/up) - Ascend directories by name or count; for bash, zsh, and fish. :star:63
* [v](https://github.com/rupa/v) - z for vim. :star:314
* [wemux](https://github.com/zolrath/wemux) - Multi-User Tmux Made Easy :star:3040
* [z](https://github.com/rupa/z) - z is the new j, yo :star:8754

## Customization

*Custom prompts, color themes, etc.*

* [base16-builder](https://github.com/base16-builder/base16-builder) - Base16-Builder :star:287
* [bash-full-of-colors](https://github.com/slomkowski/bash-full-of-colors) - Powerful prompt with screen, tmux, git support and many more :star:59
* [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) - An informative and fancy Bash prompt for Git users :star:4393
* [bash-powerline](https://github.com/riobard/bash-powerline) - Powerline-style Bash prompt in pure Bash script :star:602
* [bashstrap](https://github.com/barryclark/bashstrap) - A quick way to spruce up OSX terminal :star:1494
* [bullet-train-oh-my-zsh-theme](https://github.com/caiogondim/bullet-train.zsh) - :bullettrain_side: An oh-my-zsh shell theme based on the Powerline Vim plugin :star:1973
* [emojify](https://github.com/mrowa44/emojify) Emoji on the command line :scream:
* [flatui-terminal-theme](https://dribbble.com/shots/1021755-Flat-UI-Terminal-Theme) - Nicer colors for terminal
* [git-prompt](https://github.com/lvv/git-prompt) - Bash prompt with Git, SVN and HG modules :star:318
* [gittify](https://github.com/momeni/gittify) - A colorful Bash prompt + customized Git aliases :star:31
* [Gogh - Color Scheme](https://github.com/Mayccoll/Gogh) - Color Scheme for Gnome Terminal :star:2606
* [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt for Bash & Zsh :star:3538
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) -  Colorization for mysql comand-line client :star:52
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - An opinionated git prompt for bash and zsh :star:3011
* [polyglot](https://github.com/agkozak/polyglot) - An informative Git prompt that works in bash, zsh, ksh, mksh, pdksh, dash, and busybox sh :star:29
* [sexy-bash-prompt](https://github.com/twolfson/sexy-bash-prompt) - Bash prompt with colors, Git statuses, and Git branches :star:881

## For Developers

*Command-line development, version control, and deployment.*

* [add-gitignore](https://github.com/TejasQ/add-gitignore) - Interactive CLI that generates a .gitignore for your project based on your needs. :star:241
* [bcal](https://github.com/jarun/bcal) - Byte CALculator for storage conversions and calculations :star:128
* [bocker](https://github.com/p8952/bocker) - Docker implemented in 100 lines of bash :star:5173
* [cloc](https://github.com/AlDanial/cloc) - Count Lines of Code :star:5800
* [doclt](https://github.com/omgimanerd/doclt) - A command line interface to Digital Ocean :star:23
* [dokku](https://github.com/dokku/dokku) - Docker powered mini-Heroku. The smallest PaaS implementation you've ever seen. :star:16350
* [getopts](https://github.com/fisherman/getopts) - CLI parser for fish :star:114
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - Many Git extra utilities. Churn, cut-branch, improved-merge and many more. :star:344
* [git-extras](https://github.com/tj/git-extras) - Git utilities -- repo summary, repl, changelog population, author commit percentages and more :star:11948
* [git-open](https://github.com/paulirish/git-open) - Type `git open` to open the GitHub page or website for a repository in your browser :star:1556
* [git-quick-stats](https://github.com/arzzen/git-quick-stats) - Git quick statistics is a simple and efficient way to access various statistics in git repository. :star:1789
* [git-semver](https://github.com/markchalloner/git-semver) - Git plugin for easing semantic versioning and changelog validation :star:184
* [git-sh](https://github.com/rtomayko/git-sh) - A customized Bash environment suitable for Git work :star:696
* [git-up](https://github.com/aanand/git-up) - Automatically rebase incoming changes instead of merging. Be polite! :star:2697
* [hub](https://github.com/github/hub) - hub helps you win at git. :star:13850
* [licins](https://github.com/dogoncouch/licins) - Insert commented software licenses into source code. :star:7
* [mr](https://myrepos.branchable.com) - Multiple Repository management tool
* [overcommit](https://github.com/brigade/overcommit) - A fully configurable and extendable Git hook manager :star:2563
* [pre-commit](https://pre-commit.com) - A framework for managing and maintaining multi-language pre-commit hooks
* [rebound](https://github.com/shobrook/rebound) - Instantly browse Stack Overflow results in your terminal when you get a compiler error :star:2321
* [repren](https://github.com/jlevy/repren) - Command-line search-and-replace and file-renaming swiss army knife :star:175
* [slap](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor that runs on Node.js :star:4968
* [shipit](https://github.com/sapegin/shipit) - Minimalistic SSH deployment :star:440
* [starring](https://github.com/ritz078/starring) - Automatically star the npm-packages that you are using on GitHub. :star:120
* [tag](https://github.com/aykamko/tag) - Instantly jump to your ag matches. :star:486
* [xtm](https://github.com/Camji55/xtm) - Command line tool that helps you manage your Xcode project templates. :star:18

## System Utilities

*OS-related tools, including system administration, system debugging, and file and process management.*

* [atop](https://www.atoptool.nl) - ASCII full-screen performance monitor that is capable of reporting the activity of all processes
* [catcli](https://github.com/deadc0de6/catcli) -  The command line catalog tool for your offline data :star:25
* [ccat](https://github.com/jingweno/ccat) - ccat is the colorizing cat. It works similar to cat but displays content with syntax highlighting. :star:2374
* [colorex](https://bitbucket.org/linibou/colorex/wiki/Home) - Displays files or sdtin with pretty colors for matched patterns.
* [progress](https://github.com/Xfennec/progress) - Linux tool to show progress for `cp`, `rm`, `dd`, and more... :star:4262
* [stronghold](https://github.com/alichtman/stronghold) - Easily configure MacOS security settings from the terminal. :star:308
* [glances](https://github.com/nicolargo/glances) - Glances an Eye on your system :star:12070
* [goaccess](https://github.com/allinurl/goaccess) - GoAccess is a real-time web log analyzer and interactive viewer that runs in a terminal in \*nix systems. :star:7684
* [hblock](https://github.com/hectorm/hblock) - Hosts-file based adblocker :star:252
* [histstat](https://github.com/vesche/histstat) - History for netstat :star:48
* [htop](https://github.com/hishamhm/htop) - A ncurses based interactive process viewer which aims to be a better `top` :star:3564
* [lnav](http://lnav.org) - An advanced log file viewer for the small-scale
* [logdissect](https://github.com/dogoncouch/logdissect) - CLI utility and Python API for analyzing log files and other data. :star:30
* [ls++](https://github.com/trapd00r/ls--) - Colorized ls on steroids :star:366
* [lsp](https://github.com/dborzov/lsp) - An improved `ls`, with file descriptions in plain language and intelligent file grouping :star:454
* [mtr](https://github.com/traviscross/mtr) - The functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool. :star:1001
* [ncdu](https://dev.yorhel.nl/ncdu) - NCurses Disk Usage
* [powertop](https://github.com/fenrus75/powertop) - Battery/Power usage and device stats monitoring command-line tool, with tune-up options. :star:327
* [procdog](https://github.com/jlevy/procdog) - Lightweight command-line control of long-lived processes like servers :star:59
* [quick-secure](https://github.com/marshyski/quick-secure) - Quickly secure and harden UNIX/Linux systems :star:312
* [rng](https://github.com/nickolasburr/rng) - Copy range of lines from file or stdin to stdout. :star:3
* [wifi-wand](https://github.com/keithrbennett/wifiwand) - a Ruby command line application for managing WiFi on MacOS (install by `gem install wifi-wand`) :star:36
* [xiringuito](https://github.com/ivanilves/xiringuito) - SSH-based "VPN for poors" :star:850

## Downloading and Serving

*Self-hosted, lightweight servers and networking tools written in shell scripts.*

* [aria2](https://github.com/aria2/aria2) - aria2 is a lightweight multi-protocol & multi-source, cross platform download utility operated in command-line. It supports HTTP/HTTPS, FTP, BitTorrent and Metalink :star:11675
* [balls](https://github.com/jneen/balls) - Bash on Balls :star:728
* [bashttpd](https://github.com/avleen/bashttpd) - A web server written in Bash :star:992
* [bitpocket](https://github.com/sickill/bitpocket) - "DIY Dropbox" or "2-way directory (r)sync with proper deletion" :star:941
* [Dropbox-Uploader](https://github.com/andreafabrizi/Dropbox-Uploader) - Dropbox Uploader is a Bash script which can be used to upload, download, list or delete files from Dropbox :star:5495
* [httpie](https://github.com/jakubroztocil/httpie) - HTTPie is a command line HTTP client, a user-friendly cURL replacement :star:37851
* [HTTPLab](https://github.com/gchaincl/httplab) - The interactive web server, let you inspect HTTP requests and forge responses. :star:3167
* [ngincat](https://github.com/jaburns/ngincat) - Tiny Bash HTTP server using netcat :star:138
* [resty](https://github.com/micha/resty) - Little command line REST client that you can use in pipelines :star:2351
* [youtube-dl](https://github.com/rg3/youtube-dl) - Small command-line program to download videos from YouTube.com and other video sites :star:43105

## Multimedia and File Formats

*Tools for handling video and audio files.*

* [adb-export](https://github.com/sromku/adb-export) - Export Android content providers to CSV format :star:61
* [Android-Kitchen](https://github.com/dsixda/Android-Kitchen) - A text-based kitchen for Android ROM customization. Uses shell scripts and works with Cygwin/OS X/Linux :star:829
* [Beets](https://github.com/beetbox/beets) - Music library manager and MusicBrainz tagger :star:8332
* [cmus](https://github.com/cmus/cmus) - Cross-platform cli audio player. :star:2888
* [gifgen](https://github.com/lukechilds/gifgen) - Simple high quality GIF encoding :star:287
* [image-scraper](https://github.com/sananth12/ImageScraper) - A cool command line image scraper with a lot of features. :star:472
* [imgp](https://github.com/jarun/imgp) - Blazing fast batch image resizer and rotator :star:363
* [jq](https://github.com/stedolan/jq) - Sed for json data. You can use it to slice and filter and map and transform structured data :star:12604
* [korkut](https://github.com/oguzhaninan/korkut) - Quick and simple image processing at the command line. :star:178
* [mpv](https://mpv.io/) - Lets you play most audio and video formats (using ASCII characters) in the shell as well as in a GUI.
* [nehm](https://github.com/bogem/nehm) - Console tool, which downloads, sets IDv3 tags and adds to your iTunes (if you use it) your SoundCloud likes in convenient way :star:53
* [PiCAST](https://github.com/lanceseidman/PiCAST) - PiCAST turns your $35 Raspberry Pi in to a Chromecast like Device :star:1530
* [sejda](https://github.com/torakiki/sejda/) - Command line manipulation of PDF documents (split, merge, rotate, convert to jpg, extract text, etc) :star:206
* [xidel](https://github.com/benibela/xidel/) - Cli tool to filter, map and create HTML/XML/JSON data with (Turing-complete) XPath and XQuery. :star:139
* [xmlstarlet](http://xmlstar.sourceforge.net/) - Old but powerful tool for command-line XML formatting, filtering, and manipulation.
* [fx](https://github.com/antonmedv/fx) - Command-line JSON processing tool by anononymus JavaScript functions :star:300

## Applications

*Command line-based applications or command line access to existing services.*

* [ansiweather](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols :star:1406
* [awless](https://github.com/wallix/awless) - A powerful, innovative and small surface CLI to manage AWS. :star:3950
* [bashblog](https://github.com/cfenollosa/bashblog) - A Bash script that handles blog posting :star:758
* [choosealicense-cli](https://github.com/lord63/choosealicense-cli) - Choose an OSS license from the comfort of your terminal :star:43
* [cointop](https://github.com/miguelmota/cointop) - The fastest and most interactive terminal based UI application for tracking cryptocurrencies :star:561
* [facebook-cli](https://github.com/specious/facebook-cli) - Facebook command line tool :star:235
* [fanyi](https://github.com/afc163/fanyi) - Translate English to Chinese in terminal :star:442
* [gcalcli](https://github.com/insanum/gcalcli) - Google Calendar command line interface :star:1489
* [geeknote](https://github.com/VitaliyRodnenko/geeknote) - Command line evernote client :star:1974
* [haxor-news](https://github.com/donnemartin/haxor-news) - Browse Hacker News like a haxor :star:2706
* [hn-cli](https://github.com/rafaelrinaldi/hn-cli) - Browse Hacker News from the comfort of your Terminal :star:415
* [iponmap](https://github.com/nogizhopaboroda/iponmap) - Draw point on world map using ip address :star:173
* [isitup](https://github.com/lord63/isitup) - Check whether a website is up or down :star:31
* [jrnl](https://github.com/maebert/jrnl) - A simple command line journal application that stores your journal in a plain text file :star:3295
* [ledger](https://github.com/ledger/ledger) - Command line accounting :star:2619
* [licen](https://github.com/lord63/licen) - Generate your license. Yet another lice, but implement with Jinja2 and docopt :star:30
* [md2png](https://github.com/weaming/md2png) - Convert markdown to PNG image :star:1
* [moviemon](https://github.com/iCHAIT/moviemon) - Everything about your movies within the command line. :star:122
* [pockyt](https://github.com/arvindch/pockyt) - Read, Manage, and Automate your [Pocket](https://getpocket.com) collection. :star:276
* [pushblast](https://github.com/alebcay/pushblast) - Get PushBullet notifications when a shell program exits :star:90
* [pushbullet-bash](https://github.com/Red5d/pushbullet-bash) - Bash interface to the PushBullet API :star:210
* [ranger](https://github.com/ranger/ranger) - A console file manager with VI key bindings. :star:4289
* [Reddit Terminal Viewer](https://github.com/michael-lazar/rtv) - Browse Reddit from your terminal :star:3233
* [SAWS](https://github.com/donnemartin/saws) - A Supercharged AWS CLI :star:3770
* [taskbook](https://github.com/klauscfhq/taskbook) - Tasks, boards & notes for the command-line habitat :star:5133
* [taskwarrior](https://taskwarrior.org/) - A command-line TODO list manager
* [terjira](https://github.com/keepcosmos/terjira) - Command line power tool for Jira :star:482
* [transfer.sh](https://transfer.sh/) — Quickly upload and share files from your shell
* [vl](https://github.com/ellisonleao/vl) - URL link checker on text documents :star:42
* [wego](https://github.com/schachmat/wego) - Weather app for the terminal :star:5473
* [whales](https://github.com/Gueils/whales) - A tool to automatically dockerize your applications :star:119
* [whereami](https://github.com/rafaelrinaldi/whereami) - Get your geolocation information from the CLI :star:89
* [wttr.in](https://github.com/chubin/wttr.in) - :partly_sunny: The right way to check the weather (curl wttr.in) :star:5897

## Games

*All work and no play is a cruddy way to spend your day.*

* [bash2048](https://github.com/mydzor/bash2048) - Bash implementation of 2048 game :star:667
* [minesweeper](https://github.com/feherke/Bash-script/tree/master/minesweeper) - Bash implementation of minesweeper :star:25
* [nudoku](https://github.com/jubalh/nudoku) - ncurses based sudoku game written in C :star:78
* [piu-piu](https://github.com/vaniacer/piu-piu-SH) - Horizontal scroller game in bash with multiplayer mode! :star:541
* [sedtris](https://github.com/uuner/sedtris) - Tetris in sed :star:266
* [sed-scripts](https://github.com/aureliojargas/sed-scripts) - Arkanoid and Sokoban written using sed :star:28
* [tty-solitaire](https://github.com/mpereira/tty-solitaire) - Play solitaire in your terminal! :star:104

## Shell Package Management

*Tools for managing multiple shell configurations. For zsh-specific tools, see the Zsh section.*

* [bash-it](https://github.com/Bash-it/bash-it) - A community Bash framework :star:8700
* [basher](https://github.com/basherpm/basher) - A package manager for shell scripts :star:416
* [bashing](https://github.com/xsc/bashing) - Smashing Bash into Pieces :star:23
* [bpkg](http://www.bpkg.sh/) - JavaScript has npm, Ruby has Gems, Python has pip and now Shell has bpkg
* [dotdrop](https://github.com/deadc0de6/dotdrop) - Save your dotfiles once, deploy them everywhere :star:252
* [dotfiler](https://github.com/svetlyak40wt/dotfiler) – Shell agnostic git based dotfiles package manager, written in Python.
* [fresh](https://github.com/freshshell/fresh) - Keep your dotfiles fresh :star:860
* [homeshick](https://github.com/andsens/homeshick) - Git dotfile synchronizer written in Bash :star:1292
* [shallow-backup](https://github.com/alichtman/shallow-backup) - Easily create lightweight documentation of installed packages, dotfiles, and more :star:177
* [shundle](https://github.com/javier-lopez/shundle) - Plugin manager for shell scripts :star:67
* [vcsh](https://github.com/RichiH/vcsh) - Config manager based on Git :star:1432
* [yadm](https://thelocehiliosan.github.io/yadm/) - Git-based dotfiles manager supporting encryption, alternates, and bootstrapping

## Shell Script Development

*Tools for writing, improving, or organizing Bash or other shell scripts*

* [ansi](https://github.com/fidian/ansi) - ANSI escape codes in pure bash - change text color, position the cursor, much more :star:174
* [assert.sh](https://github.com/lehmannro/assert.sh) - Bash unit testing framework :star:370
* [bashful](https://github.com/plytophogy/bashful) - A collection of libraries to simplify writing Bash scripts :star:384
* [Bashlets](https://bashlets.sh/) - A modular extensible toolbox for Bash
* [bashmanager](https://github.com/lingtalfi/bashmanager) - mini bash framework for creating command line tools :star:53
* [bashwithnails](https://github.com/mindaugasbarysas/bashwithnails) - a Bash framework written just for fun with testing, dependency management & packaging :star:7
* [bash-language-server](https://github.com/mads-hartmann/bash-language-server) - [LSP](https://microsoft.github.io/language-server-protocol/)-based Bash language server :star:140
* [bats](https://github.com/bats-core/bats-core) - Bash Automated Testing System :star:493
* [crash](https://github.com/molovo/crash) - Proper error handling, exceptions and try/catch for ZSH :star:21
* [Fishtape](https://github.com/fisherman/fishtape) - TAP producer and test harness for fish :star:222
* [composure](https://github.com/erichs/composure) - Compose, document, version and organize your shell functions :star:224
* [dispatch](https://github.com/Mosai/workshop/blob/master/doc/dispatch.md) - A command line argument parser in 50 lines of portable shell script. :star:76
* [is.sh](https://github.com/qzb/is.sh) - An alternative for builtin test command, it will make your "if" statements pretty :star:63
* [lumberjack](https://github.com/molovo/lumberjack) - A logging interface for shell scripts :star:20
* [mo](https://github.com/tests-always-included/mo) - Mustache templates in pure bash :star:230
* [optparse](https://github.com/nk412/optparse) - A BASH wrapper for getopts, for simple command line arguments. :star:99
* [rerun](https://github.com/rerun/rerun) - A modular shell automation framework to organize your keeper scripts :star:347
* [revolver](https://github.com/molovo/revolver) - A reusable progress spinner for shell scripts :star:56
* [phases](https://github.com/sorokine/phases) - Minimally invasive bash preprocessor, select sections of your script to run :star:3
* [semver_bash](https://github.com/cloudflare/semver_bash) - Semantic Versioning in Bash :star:130
* [sh-semver](https://github.com/qzb/sh-semver) - Semver tool for bash - finds versions matching to specified rules :star:13
* [shellcheck](https://github.com/koalaman/shellcheck) - Static analysis tool for shell scripts :star:12547
* [shellfire](https://github.com/shellfire-dev/shellfire) -  A repository of namespaced, composable shell (bash, sh and dash) function libraries :star:1108
* [shpec](https://github.com/rylnd/shpec) - A shell testing framework :star:315
* [shutit](https://ianmiell.github.io/shutit/) - Automation framework based on bash and pexpect
* [sub](https://github.com/basecamp/sub) - A delicious way to organize programs :star:1484
* [ts](https://github.com/thinkerbot/ts) - A shell test script :star:37
* [urchin](https://github.com/tlevine/urchin) - An idiomatic shell testing framework that uses only shell commands :star:167
* [shunit2](https://github.com/kward/shunit2) - A unit test framework for Bash scripts with a flavour of JUnit/PyUnit. :star:573
* [rebash](https://github.com/jandob/rebash) - Scripting library/framework. Features: imports, exceptions, doc-tests ... :star:36
* [zunit](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH :star:59

# Guides

* [Bash Hackers Wiki](http://wiki.bash-hackers.org/)
* [Greg Wooledge's (aka "greycat") wiki](http://mywiki.wooledge.org).
  Specifically [Bash Guide](http://mywiki.wooledge.org/BashGuide), [Bash FAQ](http://mywiki.wooledge.org/BashFAQ) and [Bash Pitfalls](http://mywiki.wooledge.org/BashPitfalls)
* [Google's Shell Style Guide](https://google.github.io/styleguide/shell.xml)
* [The Linux Documentation Project: Bash Programming - Intro/How-to](http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html#toc)
* [The Linux Documentation Project: Advanced Bash Scripting Guide](http://www.tldp.org/LDP/abs/html/)
* [WikiBooks: Bash Shell Scripting](https://en.wikibooks.org/wiki/Bash_Shell_Scripting)
* [Use the Unofficial Bash Strict Mode (Unless You Looove Debugging)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
* [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) :star:36985
* [Learn Enough Command Line to Be Dangerous](https://www.learnenough.com/command-line-tutorial)
* [A guide to learn bash](https://github.com/Idnan/bash-guide) :star:8639

# Other Awesome Lists

Other amazingly awesome lists can be found in [awesome-awesome](https://github.com/emijrp/awesome-awesome) and [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).

### See also

* [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps) :star:2868
* [awesome-fish][awesome-fish]
* [awesome-zsh][awesome-zsh]
* [terminals-are-sexy](https://github.com/k4m4/terminals-are-sexy) :star:6811

[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
[awesome-fish]: https://github.com/fisherman/awesome-fish-shell
[awesome-link]: https://github.com/sindresorhus/awesome
[awesome-zsh]: https://github.com/unixorn/awesome-zsh-plugins


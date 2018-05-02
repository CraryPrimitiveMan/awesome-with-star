# Information comes from [felipebueno/awesome-PICO-8](https://github.com/felipebueno/awesome-PICO-8)
# Awesome PICO-8 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


![PICO-8](http://www.lexaloffle.com/gfx/p8_jelpi.gif)
![tools](http://www.lexaloffle.com/gfx/p8_tracker.gif)
![code](http://www.lexaloffle.com/gfx/p8_cast.gif)

 A curated list of PICO-8 resources, tutorials, tools and more. Inspired by the [awesome](https://github.com/sindresorhus/awesome?1) list thing. You might also like [awesome-lua](https://github.com/LewisJEllis/awesome-lua) and [awesome-love2d](https://github.com/JanWerder/awesome-love2d).

 PICO-8 is a fantasy console for making, sharing and playing tiny games and other computer programs. When you turn it on, the machine greets you with a shell for typing in a subset of [Lua](http://www.lua.org/) commands and provides simple built-in tools for creating your own cartridges.

## Contents

- [Community](#community)
- [Resources](#resources)
- [Tutorials](#tutorials)
- [Tools](#tools)
- [Text Editors Language Support](#text-editors-language-support)
- [Hacks](#hacks---undocumented-pico-8-features)
- [Articles & Posts](#articles--posts)
- [Podcasts](#podcasts)
- [Talks](#talks)
- [Clones](#clones)
- [Contributing](#i-want-to-contribute)
- [License](#license)

## Community

- [Lexaloffle](http://www.lexaloffle.com)
  - [Blog](http://www.lexaloffle.com/bbs/?uid=1)
  - [PICO-8](http://www.lexaloffle.com/pico-8.php)
  - [Forum/BBS](http://www.lexaloffle.com/bbs/?cat=7)
  - [Twitter](https://twitter.com/lexaloffle)
  - [Facebook](https://www.facebook.com/lexaloffle/)
  - [Youtube](https://www.youtube.com/user/lexaloffletv)
- [Subreddit](https://www.reddit.com/r/pico8/)
- [#pico8 on Twitter](http://www.twitter.com/#pico8)
- [#pico8 on Freenode](http://webchat.freenode.net/?randomnick=1&channels=#pico8&prompt=1)
- [Pico-8 Console News](https://twitter.com/pico8console)
- [Pico-8 Wiki](http://pico-8.wikia.com/wiki/Pico-8_Wikia)
- [Slack Team](https://slofile.com/slack/pico-8) - PICO-8 Slack chat.
- [Discord Server](https://discord.gg/EwQ86eq) - PICO-8 Discord chat.

## Resources

- [Official Manual](http://www.lexaloffle.com/pico-8.php?page=manual) - Placeholder dump of pico-8.txt! (Proper manual coming soon).
- [Cheat Sheet](http://neko250.github.io/pico8-api/) - by [Neko250](https://neko250.github.io). Based on the official manual, with edits where found appropriate.
- [PicoZine #1](http://sectordub.itch.io/pico-8-fanzine-1), [#2](http://sectordub.itch.io/pico-8-fanzine-2), [#3](http://sectordub.itch.io/pico-8-fanzine-3) and [#4](https://sectordub.itch.io/-pico-8-zine-4) - PICO-8 Zine is a 48-page fanzine made by and for PICO-8 users.
- [Going from Lua 5.2 to PICO-8's Lua](https://gist.github.com/josefnpat/bfe4aaa5bbb44f572cd0) - This document is here to help folks with a proficiency in Lua understand the limitations and discrepencies between Lua and PICO-8's Lua.
- [Cheat Sheet (printable)](https://ztiromoritz.github.io/pico-8-spick/) - A reduced cheat sheet in a printable format. German and Englisch version available.
- [Cheat Sheet (wallpaper)](https://www.lexaloffle.com/bbs/?tid=28207) - An enhancement of the printable cheat sheet for use as a desktop wallpaper.

## Tutorials

- [Music Tracker Tutorial Series](https://www.youtube.com/playlist?list=PLjZAika8vyZkyOjoCp0EbHeIFZ8MLlhvg) - Making audio with PICO-8.
- [Tron Lightcycle game from scratch](https://youtu.be/ZuaLuMhwcc8) - A quick introduction to PICO-8 writing a game from scratch.
- [A PICO-8 Spaceshooter in 16 GIFs](https://ztiromoritz.github.io/pico-8-shooter/) - Screencaptures of writing a Spaceshooter game step by step.  
- [Token optimization](https://github.com/seleb/PICO-8-Token-Optimizations) - tips&tricks for saving tokens. :star:47
- [Tweetjam, BBS thread](http://www.lexaloffle.com/bbs/?tid=3726) - cards which code fits in a tweet (really useful to learn some fun techniques).
- [Sample code on the BBS](http://www.lexaloffle.com/bbs/?search=sample+code) - the search is not 100% accurate, but some of those cards features some nice tricks you can re-use in your future code.

## Tools

- [Sprite Editor](http://www.lexaloffle.com/bbs/?tid=2462) - External sprite editor compatible with Pico-8 and PicoLove.
- [pico2png](https://github.com/briacp/pico2png) - Spritesheet extraction written in perl. :star:13
- [Spritesheets and tools for the PICO-8 Palette](https://www.reddit.com/r/pico8/comments/3jhmni/spritesheets_and_tools_for_the_pico8_palette/) - Compilation of works assest and tools using the PICO-8 palette.
- [Pico8Utils](https://github.com/josefnpat/pico8utils) - Compilation of lua scripts based on the unix philosophy for working with .p8 files. :star:31
- [picotool](https://github.com/dansanderson/picotool) -  Tools and Python libraries for manipulating Pico-8 game files. :star:136
- [p8dl - Carts Downloader - Python](https://github.com/franciscod/p8dl) - Downloads cartridges into the correct folder (looks at your config.txt). :star:4
- [Pico-8 Carts Downloader - Bash ](https://github.com/kikookoubis/pico-8-carts-bash-downloader) - Downloads cartridge from the BBS (single cart, whole index or dump your favourited entries) & rename them according to their metadata. :star:4
- [p8 responsive webplayer transform](https://github.com/benwiley4000/pico8-responsive-webplayer-transform) - Python script that makes your HTML export page responsive. :star:10
- [Color Palette](http://www.romanzolotarev.com/pico-8-color-palette/) - Hex and RGB colors codes for web.
- [PICO-8 font](https://drive.google.com/file/d/0B97Um39fHXlcWUFRZlBqUndhbXM/view) - by [RhythmLynx](http://www.lexaloffle.com/bbs/?uid=11704).
- [pico-test](https://github.com/jozanza/pico-test) - PICO-8 testing framework. :star:15
- [Lib-Pico8](https://github.com/clowerweb/Lib-Pico8) - A Pico-8 library of useful common functions. :star:69
- [pico8-missing-builtins](https://github.com/adamscott/pico8-missing-builtins) - Provides Lua built-in functions to pico8. :star:10
- [P8Coder](https://github.com/movAX13h/P8Coder) - A programming tool that replaces the lua code in pico-8 cartridges (p8) with the code you write in P8Coder. :star:44
- [Pico-Kit](https://github.com/outkine/pico-kit) - An opinionated collection of Pico-8 helpers that make it easier to get going.  Adds OOP, better debugging, and physics. :star:18
- [picoDeploy](https://github.com/torch2424/picoDeploy) - Deploy Pico-8 carts as standalone applications on desktop (Electron) and mobile (Ionic).  :star:48
- [pico8Grunt](https://github.com/TeamNoComplyGames/pico8Grunt) - A build system for pico8 games, using gruntjs. :star:7
- [PICO-EC](https://github.com/JoebRogers/PICO-EC) - A tiny scene-entity-component library created for the PICO-8 fantasty console. :star:7
- [PICO-Tween](https://github.com/JoebRogers/PICO-Tween) - A small library of tweening/easing functions for use in the PICO-8 fantasy console, inspired by Robert Penner's easing functions. :star:15
- [p8](https://github.com/jozanza/p8) - A dependency manager and build tool. Lets you share code/sprites, `require()` dependencies, and auto-reload carts on save. Works with any external code editor and supports [MoonScript](https://moonscript.org/). :star:14

## Text Editors Language Support

- Visual Studio Code: [vscode-pico8](https://github.com/nathanchere/vscode-pico8)
- Atom: [language-pico8](https://atom.io/packages/language-pico8)
- Sublime: [Sublime PICO-8](https://packagecontrol.io/packages/PICO-8) - PICO-8 plugin for the Sublime Text editor (color scheme, font, build system, code completion, snippets...).
- Vim: [vim-pico8-syntax](https://github.com/justinj/vim-pico8-syntax)

### Programming Fonts

You might be interested to install [pico-8 programming fonts](https://github.com/juanitogan/p8-programming-fonts) they support the pico-8 custom characters as well as various fonts (bitmap and regular anti-aliased fonts). Check the [BBS thread here](http://www.lexaloffle.com/bbs/?tid=28975).

How to install the font(s):

* **Linux:** copy the files on ~/.fonts and `sudo fc-cache -f -v`
* **Windows:** copy the files on c:/windows/fonts/

## Hacks - undocumented PICO-8 features

- [Mouse](http://www.lexaloffle.com/bbs/?tid=3549) - How to retrieve mouse coordinates (with demo).
- [p8keyboard.js](https://github.com/dppc/p8keyboard.js) - Javascript "keyboard adapter" for the Pico-8. Send ASCII characters to a Pico-8 program running in a browser. :star:9
- [SFX Modifications](http://www.lexaloffle.com/bbs/?tid=3561) - Four effects that can only be applied by modifying memory (with demo).
- [Tracker State/Audio Memory Locations](http://www.lexaloffle.com/bbs/?pid=10719#p10719) - How to access and modify audio data as it is playing.

## Hardware

- [PocketC.H.I.P](https://getchip.com/pages/pocketchip) - A portable mini-computer, a game console, a portable synthesizer and a Linux field terminal with PICO-8 pre-installed.

## Articles & Posts

- [Indie Retro News](http://www.indieretronews.com/2015/10/pico-8-8-bit-fantasy-console-from.html) - A great introduction to PICO-8 by [@ABrugsch](https://twitter.com/ABrugsch).
- [Clear Code](http://blog.jvscott.net/post/128051478244/clear-code) - 3 part series on how to write better pico-8 code.

## Podcasts

- [pico chat](http://pico.electrobureau.com/) - A bite-sized podcast about Pico-8 and other tiny games.

## Talks

- [Sharing the love](https://www.youtube.com/watch?v=AmMYWD2Zbso) - Making games with PICO-8. linux conf au 2017 - Hobart, Australia

## Clones
- [TIC-80 by Nesbox](https://nesbox.itch.io/tic) - Tiny Computer, available on HTML 5, Windows, Linux 32/64bit, Android & MacOSX         
- [PicoLove](https://github.com/gamax92/picolove) - Pico-8 Reimplementation in LÖVE. :star:61
- [LIKO-12](https://github.com/RamiLego4Game/LIKO-12) - An open source fantasy computer made using LÖVE with 96kb RAM. :star:331
- [PX8](https://github.com/Gigoteur/PX8) - Open Source Fantasy Console (128x128 pixels) in Rust (with Python/LUA code support). :star:699

## I Want to Contribute!

Great! :smiley:

Please, read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Felipe Bueno](https://twitter.com/felipebueno) has waived all copyright and related or neighboring rights to this work.

See [LICENSE](LICENSE) for more information.


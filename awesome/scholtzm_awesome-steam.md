# Info come from [scholtzm/awesome-steam](https://github.com/scholtzm/awesome-steam)
# Awesome Steam [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of [packages](#packages) and [resources](#resources) regarding [Steam](http://store.steampowered.com/) development.

*Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.*

The purpose of this document is to provide a quick overview over existing packages (libraries, modules etc.) and resources available regarding Steam client automation and WebAPI usage. Whenever you need to start a new project, have a look at the list of packages and see if there is anything useful for your use case. If you need technical details or tutorials, check out the resources section.

## Table of Contents

- [Packages](#packages)
  - [Node.js](#nodejs)
  - [C#](#c)
  - [PHP](#php)
  - [Go](#go)
  - [Python](#python)
  - [C++](#c-1)
  - [Java](#java)
  - [Objective-C](#objective-c)

- [Resources](#resources)
  - [General](#general-1)
  - [Tutorials](#tutorials)
  - [Posts](#posts)
  - [Standalone Tools](#standalone-tools)
  - [Discussion Boards](#discussion-boards)
  - [Third-Party Services](#third-party-services)

## Packages

> 💡 Many of these package repositories provide helpful READMEs and wiki pages, which explain the usage and/or provide examples. Do not forget to check them out when using particular package.

### Node.js

#### General

- [steam](https://github.com/seishun/node-steam) - Interface directly with Steam servers from Node.js. :star:855
- [steam-client](https://github.com/DoctorMcKay/node-steam-client) - API-compatible fork of node-steam's SteamClient. :star:27
- [steam-user](https://github.com/DoctorMcKay/node-steam-user) - Feature-rich easy-to-use Steam client. :star:198
- [vapor](https://github.com/scholtzm/vapor) - Lightweight Steam client framework. :star:95
- [steam-parentbot](https://github.com/dragonbanshee/node-steam-parentbot) - Simple base class for a Steam bot. :star:37

#### WebAPI

- [steam-webapi](https://github.com/DoctorMcKay/node-steam-webapi) - Complete WebAPI wrapper with support for extra HTTP headers sent by Steam. :star:12
- [steamapi](https://github.com/lloti/node-steamapi) - A nice Steam API wrapper. :star:8

#### Trading

- [steam-trade](https://github.com/seishun/node-steam-trade) - Node.js wrapper around Steam live trading. :star:163
- [steam-tradeoffers](https://github.com/Alex7Kom/node-steam-tradeoffers) - Steam Trade Offers for Node.js. :star:277
- [steam-tradeoffer-manager](https://github.com/DoctorMcKay/node-steam-tradeoffer-manager) - Simple and sane Steam trade offer management. :star:239

#### Game Interaction

- [steam-gameserver](https://github.com/DoctorMcKay/node-steam-gameserver) - Steam client handler for Gameserver and AnonGameserver account types. :star:5
- [tf2](https://github.com/DoctorMcKay/node-tf2) - Interact directly with TF2 game coordinator. :star:24
- [csgo](https://github.com/joshuaferrara/node-csgo) - Interact directly with CS:GO game coordinator. :star:217
- [dota2](https://github.com/RJacksonm1/node-dota2) - Interact directly with Dota 2 game coordinator. :star:355

#### Community & Store Automation

- [steamcommunity](https://github.com/DoctorMcKay/node-steamcommunity) - Interact with steamcommunity.com. Also allows to confirm trade offers. :star:184
- [steamstore](https://github.com/DoctorMcKay/node-steamstore) - Interact with store.steampowered.com. :star:32
- [steam-weblogon](https://github.com/Alex7Kom/node-steam-weblogon) - Retrieve SteamCommunity cookies if you are running Steam network client. :star:23
- [steam-web-api-key](https://github.com/Alex7Kom/node-steam-web-api-key) - Automatically registers and retrieves Steam API key. :star:16
- [steam-parental](https://github.com/Alex7Kom/node-steam-parental) - Disable parental lock. :star:3

#### Authentication

- [steam-login](https://github.com/cpancake/steam-login) - Simple Connect / Express Steam authentication library. :star:23
- [passport-steam](https://github.com/liamcurry/passport-steam) - Steam (OpenID) authentication strategy for Passport and Node.js. :star:209
- [meteor-accounts-steam](https://github.com/scholtzm/meteor-accounts-steam) - Steam OpenID integration for Meteor Accounts. :star:12

#### Misc

- [steam-resources](https://github.com/seishun/node-steam-resources) - Steam's enums, protobufs and structs. :star:15
- [steam-crypto](https://github.com/seishun/node-steam-crypto) - Node.js implementation of Steam crypto. :star:12
- [steam-groups](https://github.com/scholtzm/node-steam-groups) - Custom node-steam handler which provides group functions. :star:17
- [steamid](https://github.com/DoctorMcKay/node-steamid) - SteamID usage and conversion made easy. :star:31
- [steam-totp](https://github.com/DoctorMcKay/node-steam-totp) - Easily generate 2FA codes used by Steam. :star:108
- [steam-chat-bot](https://github.com/Steam-Chat-Bot/node-steam-chat-bot) - Simplified interface for a steam chat bot. :star:78
- [vdf](https://github.com/RJacksonm1/node-vdf) - vdf to object and vice versa. :star:17
- [steamrep](https://github.com/scholtzm/node-steamrep) - Check user's SteamRep reputation. :star:10
- [reptf](https://github.com/scholtzm/node-reptf) - Check user's rep.tf reputation. :star:3

### C&#35;

#### General

- [SteamKit2](https://github.com/SteamRE/SteamKit) - .NET library designed to interoperate with Valve's Steam network. :star:1114
- [SteamAuth](https://github.com/geel9/SteamAuth) - A C# library that provides vital Steam Mobile Authenticator functionality. :star:118
- [SteamBot](https://github.com/Jessecar96/SteamBot) - Automated bot software for interacting with steam trade. :star:990
- [SteamTradeOffersBot](https://github.com/waylaidwanderer/SteamTradeOffersBot) - SteamBot fork which focuses on trade offers. :star:40
- [SteamStandardProject](https://github.com/ObsidianMinor/SteamStandardProject) - A collection of .NET Standard libraries using common types that provide functionality in one or more parts of Steam. :star:3

#### Misc

- [BackpackLogin](https://github.com/igeligel/BackpackLogin) - A .NET Standard library for logging into backpack.tf using Steam credentials. :star:4
- [TeamFortressOutpostApi](https://github.com/igeligel/TeamFortressOutpostApi) - A .NET Standard class library which allows user to interact with TF2Outpost. :star:2
- [SteamGaugesApi](https://github.com/igeligel/SteamGaugesApi) - A .NET Standard 2.0 library to automatically use the API of [steamgauges](https://steamgaug.es/). :star:1

### PHP

- [SteamCommunity](https://github.com/waylaidwanderer/PHP-SteamCommunity) - A PHP library for interacting with the Steam Community website. :star:44
- [SteamAuthentication](https://github.com/SmItH197/SteamAuthentication) - Steam OpenID authentication with PHP. :star:275
- [SteamAuthOOP](https://github.com/BlackCetha/SteamAuthOOP) - An object-oriented alternative to SteamAuthentication. :star:17
- [steam-api](https://github.com/DaMitchell/steam-api-php) - A PHP wrapper for the Steam API. :star:62
- [steamid](https://github.com/DoctorMcKay/php-steamid) - SteamID class for PHP. :star:3
- [steam-totp](https://github.com/DoctorMcKay/php-steam-totp) - PHP library to deal with Steam's proprietary TOTP algorithm. :star:11
- [steam-auth](https://github.com/vikas5914/steam-auth) - An alternative Steam authentication library with Composer support. :star:3

### Go

- [steam](https://github.com/Philipp15b/go-steam) - Steam's protocol in Go. :star:174
- [steam-mobileauth](https://github.com/YellowOrWhite/go-steam-mobileauth) - Port of SteamAuth in Go. :star:13

### Python

#### General

- [steam](https://github.com/ValvePython/steam) - Module for various interactions with Steam. :star:143
- [PySteamKit](https://bitbucket.org/AzuiSleet/pysteamkit) - Python port of SteamKit.
- [steamodd](https://github.com/Lagg/steamodd) - Steam tools library. :star:61
- [steampy](https://github.com/bukson/steampy) - Fully automated Steam trade offers library with SteamGuard support. :star:70
- [SteamAPI](https://github.com/smiley/steamapi) - An object-oriented Python 2.7+ library for accessing the Steam Web API. :star:277
- [Steam-Trade](https://github.com/Zwork101/steam-trade) - An asynchronous, event-based trade library. :star:2

#### Game Interaction

- [csgo](https://github.com/ValvePython/csgo) - Python module for interacting with CSGO's Game Coordinator. :star:23
- [dota2](https://github.com/ValvePython/dota2) - Python module for interacting with Dota 2's Game Coordinator. :star:49

#### Misc

- [vpk](https://github.com/ValvePython/vpk) - Python module for working with Valve's Pack format. :star:9
- [vdf](https://github.com/ValvePython/vdf) - Python module for working with Valve's KeyValue format. :star:22

### C++

- [SteamPP](https://github.com/seishun/SteamPP) - C++ library to interoperate with Steam servers. :star:58

### Java

- [SteamKit-Java](https://github.com/Top-Cat/SteamKit-Java) - Java port of SteamKit. :star:34

### Objective-C

- [SteamAuth](https://github.com/michaelchum/SteamAuth) - An iOS wrapper around Steam's OpenID login. :star:3

## Resources

### General

- [Steam WebAPI @ ValveSoftware](https://developer.valvesoftware.com/wiki/Steam_Web_API)
- [Steam WebAPI @ TF2 Wiki](https://wiki.teamfortress.com/wiki/WebAPI)
- [Steam WebAPI Documentation by xpaw](https://lab.xpaw.me/steam_api_documentation.html)
- [Steam as OpenID Provider](http://steamcommunity.com/dev)
- [Steam API Key Registration](http://steamcommunity.com/dev/apikey)
- [Steam Error Codes](https://steamerrors.com/) - List of `EResult` codes with possible explanations.

### Tutorials

- [Creating a Steam Trade Bot with Node.js](https://firepowered.org/developer/create-a-steam-trade-bot-with-nodejs-iojs-updated-for-node-steam-v1-0/)
- [Charred's node.js Guide to Steam Bots](https://github.com/charredgrass/nodejs-bot-guide) :star:41
- [In-depth Steam Bot Guide with Node.js](https://github.com/andrewda/node-steam-guide) :star:201
- [Retrieving 2FA Keys from iOS Device](http://forums.backpack.tf/index.php?/topic/45995-guide-how-to-get-your-shared-secret-from-ios-device-steam-mobile/)

### Posts

- [Item IDs Explained](https://dev.doctormckay.com/topic/332-identifying-steam-items/)
- [Everything Related to Escrow](https://www.reddit.com/r/SteamBot/comments/3udhkd/everything_related_to_escrow/)
- [Understanding Avatar Hash](https://www.reddit.com/r/SteamBot/comments/3cv6k7/problem_downloading_an_avatar_using/)

### Standalone Tools

- [NetHook2](https://github.com/SteamRE/SteamKit/tree/master/Resources/NetHook2) - Intercept Steam client's network messages.
- [NetHook2 Analyzer](https://github.com/SteamRE/SteamKit/tree/master/Resources/NetHookAnalyzer2) - Inspect messages dumped by NetHook2.
- [steam-auth-web-util](http://scholtzm.github.io/steam-auth-web-util/) - Generate 2FA codes directly in your web browser.
- [SteamDesktopAuthenticator](https://github.com/Jessecar96/SteamDesktopAuthenticator) - Desktop implementation of Steam's mobile authenticator app. :star:699

### Discussion Boards

- [/r/SteamBot](https://www.reddit.com/r/SteamBot)
- [/r/SteamBot Discord](https://discord.gg/0i5X3oDHJbDUsiGC)
- [/r/nodesteam](https://www.reddit.com/r/nodesteam)
- [DoctorMcKay's Dev Forum](https://dev.doctormckay.com/)
- [node-steam-forum](https://github.com/steam-forward/node-steam-forum) :star:43

### Third-Party Services

Websites listed below may provide free and/or paid services and are listed alphabetically according to their domain name.

- [backpack.tf](https://backpack.tf/developer) - Provides TF2 prices and Steam market/inventory related services.
- [steamanalyst.com](https://steamanalyst.com/) - Provides CS:GO prices.
- [steamapi.io](https://steamapi.io/) - Provides prices for several games and Steam market/inventory related services.
- [steamapis.com](https://steamapis.com/) - Provides prices for several games and Steam market/inventory related services.
- [steamlytics.xyz](https://steamlytics.xyz/) - Provides CS:GO prices and Steam market/inventory related services.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author and contributors of this text have waived all copyright and related or neighboring rights to this work.


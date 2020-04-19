# Information comes from [rafaskb/awesome-libgdx](https://github.com/rafaskb/awesome-libgdx)
[![Awesome libGDX Logo](logo.png 'Awesome libGDX Logo')](https://libgdx.badlogicgames.com/)

# Awesome libGDX [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/rafaskb/awesome-libgdx#contributing)

> <a href="https://libgdx.badlogicgames.com/"><img src="https://libgdx.badlogicgames.com/img/logo.png" alt="libGDX Logo" align="right" style="margin-right: 25px" height=40></a>
>
> [libGDX](https://libgdx.badlogicgames.com/) is a relatively low level, free, open source cross platform game development framework written in Java.
>
> This list is a curated collection of awesome resources, tools, tutorials, and projects using the [libGDX](https://libgdx.badlogicgames.com/) game framework to help developers make _awesome_ games, conforming to the [Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/master/awesome.md).
>
> Contributions _very welcome_ but first see [Contributing](#contributing).


---


## Contents

- [Resources](#resources)
  - [Artificial Intelligence](#artificial-intelligence)
  - [Controllers](#controllers)
  - [Entity Component System (ECS)](#entity-component-system-ecs)
  - [Physics](#physics)
  - [Services](#services)
  - [Setup and Deployment](#setup-and-deployment)
  - [User Interface](#user-interface)
  - [Visual Effects](#visual-effects)
  - [Others](#others)
- [Tutorials](#tutorials)
  - [Getting Started](#getting-started)
  - [Advanced](#advanced)
- [Assets](#assets)
- [Community](#community)
- [Other Lists](#other-lists)


---


## Resources

_Resources that can be used in libGDX code to boost the framework's capabilities._

### Artificial Intelligence
- [gdx-ai](https://github.com/libgdx/gdx-ai) - Artificial Intelligence framework featuring Steering Behaviors, Formation Motion, Pathfinding, Behavior Trees and Finite State Machines. :star:810

### Controllers
- [Controllers](https://github.com/libgdx/libgdx/wiki/Controllers) - Adds support to gamepads and joysticks. :star:16786
- [gdx-controllerutils](https://github.com/MrStahlfelge/gdx-controllerutils) - Adds Scene2D button input support, user configurable button mappings and hotplugging for LWJGL2. :star:36
- [sdl2gdx](https://github.com/electronstudio/sdl2gdx) - Powerful gamepad implementation using SDL. Supports hundreds of controllers under the same mapping, rumble, and hotplugging. :star:18

### Entity Component System (ECS)
- [Artemis-odb](https://github.com/junkdog/artemis-odb) - High performance java based Entity-Component-System framework. :star:580
- [Ashley](https://github.com/libgdx/ashley) - A Java entity system inspired by Ash & Artemis. :star:612

### Physics
- [Box2D](https://github.com/libgdx/libgdx/wiki/Box2d) - One of the most popular physics libraries for 2D games. :star:16786
- [Bullet](https://github.com/libgdx/libgdx/wiki/Bullet-physics) - 3D Collision Detection and Rigid Body Dynamics Library. :star:16786

### Services
- [gdx-facebook](https://github.com/TomGrill/gdx-facebook) - Provides cross-platform support for Facebook Graph API. :star:59
- [gdx-fireapp](https://github.com/mk-5/gdx-fireapp) - Cross-platform API for Firebase. :star:44
- [gdx-firebase](https://github.com/TomGrill/gdx-firebase) - Cross-platform (only Desktop/Android) API for Firebase. :star:32
- [gdx-gameanalytics](https://github.com/MrStahlfelge/gdx-gameanalytics) - Game Analytics REST API client implementation for libGDX. Works on all backends. :star:16
- [gdx-gamesvcs](https://github.com/MrStahlfelge/gdx-gamesvcs) - Easy integration of gameservices, such as Google Play Games, Apple Game Center, and more. :star:75
- [gdx-pay](https://github.com/libgdx/gdx-pay) - Provides a cross-platform API for InApp purchasing. :star:171
- [steamworks4j](https://github.com/code-disaster/steamworks4j) - A thin wrapper which allows Java applications to access the Steamworks C++ API. :star:287

### Setup and Deployment
- [gdx-liftoff](https://github.com/tommyettinger/gdx-liftoff) - A modern setup tool for libGDX that uses the current Gradle 5.x series. :star:43
- [Packr](https://github.com/libGDX/packr) - Packages your JAR, assets and a JVM for distribution on Windows, Linux and macOS. :star:2043

### User Interface
- [Freetype](https://github.com/libgdx/libgdx/wiki/Gdx-freetype) - Generate BitmapFonts of your desired size on the fly from lightweight .ttf font files. :star:16786
- [gdx-dialogs](https://github.com/TomGrill/gdx-dialogs) - Provides cross-platform support for native dialogs. :star:64
- [gdx-skins](https://github.com/czyzby/gdx-skins) - Free Scene2D GUI skins. :star:338
- [InGameConsole](https://github.com/StrongJoshua/libGDX-inGameConsole) - Allows a developer to add a console (similar to how it is featured in Source games) to their game. :star:100
- [msdf-gdx](https://github.com/maltaisn/msdf-gdx) - Provides lightweight utilities to draw high-quality MSDF (multi-channel signed distance field) text on libGDX. :star:7
- [PieMenu](https://github.com/payne911/PieMenu) - Radial menus for Scene2D that are highly flexible and easy to customize. :star:19
- [Ray3K Skins](https://ray3k.wordpress.com/artwork/) - Free Scene2D.UI skins with example code, custom drawables, and experimental features.
- [Skin Composer](https://github.com/raeleus/skin-composer) - Create skins for libGDX scene2d.ui with a graphical interface. :star:198
- [TenPatch](https://github.com/raeleus/TenPatch) - An alternative to libGDX's 9patch implementation that implements multiple stretch regions. :star:26
- [TypingLabel](https://github.com/rafaskb/typing-label) - A libGDX Label that appears as if it was being typed in real time. :star:84
- [VisUI](https://github.com/kotcrab/vis-ui) - Allows to create nice looking UI in libGDX using scene2d.ui. Note this is not a UI editor. :star:492

### Visual Effects
- [Box2DLights](https://github.com/libgdx/box2dlights) - 2D lighting framework that uses Box2D for raycasting and OpenGL ES 2.0 for rendering. :star:205
- [gdx-vfx](https://github.com/crashinvaders/gdx-vfx) - Flexible post-processing shader visual effects based on libgdx-contribs-postprocessing. :star:57
- [Particle Park](https://github.com/raeleus/Particle-Park) - A showcase of downloadable particle effects with live previews. :star:20
- [Shape Drawer](https://github.com/earlygrey/shapedrawer) - A performant alternative to ShapeRenderer that avoids Batch flushing. :star:58
- [Spine](http://esotericsoftware.com/) - Skeleton-based animation tool that focuses specifically on 2D animation for games.

### Others
- [gdx-dbgagent](https://github.com/PokeMMO/gdx-dbgagent) - Java Agent for debugging common issues, like objects not being disposed and constants such as Color.WHITE being modified.  :star:11
- [gdx-jnigen](https://github.com/libgdx/libgdx/tree/master/extensions/gdx-jnigen) - Small library that allows C/C++ code to be written inline with Java source code. :star:16786
- [gdxGifRecorder](https://github.com/Anuken/GDXGifRecorder) - A utility class that records a GIF and saves it automatically. :star:29
- [KTX](https://github.com/libktx/ktx) - Kotlin extensions and utilities for libGDX. :star:722
- [noise4j](https://github.com/czyzby/noise4j) - Simple map generators based on various procedural content generation tutorials. :star:63
- [Texture Packer GUI](https://github.com/crashinvaders/gdx-texture-packer-gui) - A simple way to pack and manage texture atlases for libGDX game framework. :star:305


## Tutorials

_Tutorials for newbies and seasoned developers alike._

### Getting Started

- [Official libGDX Wiki](https://github.com/libgdx/libgdx/wiki) - Official libGDX wiki that contains a huge amount of information. :star:16786
- [Tann's Hello libGDX](http://tann.space/HelloLibgdx/) - An excellent guide for beginners on how to create a game from scratch.
- [Splash Screens](https://youtu.be/Rnmq_Jv-pe4) - Video tutorial on creating splash screens to display before your game window loads.
- [Creating a Launcher](https://youtu.be/3l5F7f7vfTU) - Video tutorial on using libGDX to make a game launcher.
- [Deploying with JPackage](https://github.com/raeleus/skin-composer/wiki/libGDX-and-JPackage) - A tutorial on deploying libGDX games with JPackage via Gradle commands. :star:198
- [JSON in Game Dev](http://mana-break.blogspot.com/2014/06/power-of-json-in-game-development-items.html) - General tutorial on using JSON for storing data.
- [Progress Bar Design](https://github.com/raeleus/skin-composer/wiki/The-Man-Who-Killed-Hitler-and-then-The-Progress-Bar) - Discusses the pros and cons of different progress bar design techniques with examples. :star:198
- [libGDX External Tutorials](https://github.com/libgdx/libgdx/wiki/External-tutorials) - Big list of official unofficial tutorials. :star:16786

### Advanced

- [Code Hotswapping](https://youtu.be/zKfh6WuaikQ) - Video tutorial on enabling code hotswapping for libGDX projects to increase productivity.
- [Dynamic Textures with Pixmap](https://javadocmd.com/blog/libgdx-dynamic-textures-with-pixmap/) - Details how to create a mask using Pixmaps.
- [iOS Deployment Tutorial](https://link.medium.com/vgYo0mSi3W) - Deploying to iOS in 2019 using RoboVM.
- [Sub-pixel Perfect Smooth Scrolling](http://code-disaster.com/2016/02/subpixel-perfect-smooth-scrolling.html) - Pixel-perfect smooth scrolling.


## Assets

_Collection of free and high quality assets to get your game to the next level._

- [Kenney Assets](https://kenney.nl/) - High quality assets for your game, from 2D and 3D art to sound effects.
- [OpenGameArt.org](https://opengameart.org/) - Repository offering a variety of open content assets.
- [Game-Icons.net](http://game-icons.net/) - Repository containing heaps of cool game related graphics.
- [bfxr.net](https://www.bfxr.net/) - Quickly create unique sound effects by pressing a few buttons, excellent for prototyping.
- [freesound.org](https://freesound.org/) - Huge collaborative database of audio snippets, samples, recordings, bleeps.


## Community

_Get in touch with other libGDX developers to collaborate and get help._

- [Discord](https://discord.gg/4S8pQqc) - An active chat with various leaders from the community available every day. **Recommended**
- [Reddit](https://www.reddit.com/r/libgdx/) - Unofficial subreddit for libGDX. Not a lot of activity.


## Other Lists

_Other awesome lists that might be useful to libGDX developers._

- [Game Networking](https://github.com/MFatihMAR/Awesome-Game-Networking) - A Curated List of Game Network Programming Resources. :star:2451
- [Game Talks](https://github.com/hzoo/awesome-gametalks) - A curated list of gaming talks (development, design, etc). :star:727
- [Java](https://github.com/akullpp/awesome-java) - A curated list of awesome Java frameworks, libraries and software. :star:24383
- [Kotlin](https://github.com/KotlinBy/awesome-kotlin) - A curated list of awesome Kotlin related stuff. :star:8568
- [Magic Tools](https://github.com/ellisonleao/magictools) - A list of Game Development resources to make magic happen. :star:7026
- [Game Accessibility Guidelines](http://gameaccessibilityguidelines.com/) - A straightforward reference for inclusive game design, to ensure that games are just as fun for as wide a range of people as possible. **Recommended**


---


## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.



## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)


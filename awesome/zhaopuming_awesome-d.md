# Information comes from [zhaopuming/awesome-d](https://github.com/zhaopuming/awesome-d)
# Awesome D [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
=========

  A curated list of awesome D frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).
  
  I created this list so that when I needed something in the future, it would be easy to find. Most of the documents and links are collected from the [D forum](http://forum.dlang.org), the [D wiki](http://wiki.dlang.org), and the [D package repository](http://code.dlang.org). Exploring GitHub also helps as many of the libs are hosted there.
  
  If you know an interesting lib/app in D, please tell me by issue or a pull request :-).
  
 
- [Awesome D](#awesome-d)
	- Basic Information
		- [Official Website](#official-website)
		- [People](#people)
		- [Events](#events)
		- [Organizations](#organizations)
	- Documents
		- [Books](#books)
		- [Tutorials](#tutorials)
		- [Blogs](#blogs)
		- [Articles](#articles)
		- [API Doc](#api-docs)
	- Language Related 
		- [Package Management](#package-management)
		- [Compilers](#compilers)
		- [Build Tools](#build-tools)
		- [IDE](#ide)
		- [Lexers, Parsers, Generators](#lexers-parsers-parser-generators)
		- [Preprocessors](#preprocessors)
	- Compiler for other languages
		- [Javascript](#javascript)
	- Common/Utilities
		- [Containers](#containers)
	- Networking/Web Related
		- [Networking](#networking-library)
		- [Web Frameworks](#web-frameworks)
		- [Data&Serialization](#data-serialization)
	- Database
		- [Database clients](#database-clients)
	- GUI
		- [GUI Libs](#gui-libs)
	- OS
		- [Operating Systems](#os)
	- Gaming
		- [Bindings](#game-bindings)
		- [Frameworks](#game-frameworks)
		- [Games](#games)
	- Video
		- [Applications](#video-appilcations)
	- Image Processing
		- [Applications](#image-processing)
	- Scientific
		- [Scientific](#scientific)
	- Machine Learning
		- [Machine Learning](#machine-learning)
	- [Parallel computing](#parallel-computing)
	- Others
		- [Text Processing](#text-processing)
		- [Command Line](#command-line)
		- [Logging](#logging)
		- [Configuration](#configuration)
		- [BlogEngine](#blog-engine)
		- [Testing](#testing)
		
- [Other Awesome Lists](#other-awesome-lists)


## Official Website

*Official Website URLs.*

* [dlang.org](http://dlang.org) - Official website for D.
* [wiki.dlang.org](http://wiki.dlang.org) - Official Wiki for D.
* [code.dlang.org](http://code.dlang.org) - Offical Library/Module Registry for D.
* [Github Organization](https://github.com/dlang) - Official GitHub organization for D. Repo for all official D tools & code.
* [forum.dlang.org](http://forum.dlang.org/) - Official forum. Many interesting discussions occurring on a daily basis.
* [blog.dlang.org](https://dlang.org/blog/) - Official blog.
* [Language Specification](http://dlang.org/spec.html) - D programming language specification.
* [Issue tracking](https://issues.dlang.org/) - Official issue tracking/reporting system for D. If you find bugs in the D compiler and/or libraries, please come and report them!

## People

*The people that made D the language it is.*

* [Walter Bright](http://www.walterbright.com/) - Father of D. Walter Bright is the creator and first implementer of the D programming language and has implemented compilers for several other languages.
* [Andrei Alexandrescu, PhD](http://erdani.com/) - C++ guru. Author of *The D Programming Language* and *Modern C++ Design*. With Walter Bright, Andrei co-designed many important features of D and authored a large part of D's standard library. Andrei works as a trainer in advanced C++ programming and algorithms and is now actively evangelizing D in the organization.
* **YOU** - Please add your information if you've done something interesting in D. It is you, the awesome people that made D awesome. 

## Events

* [DConf](http://dconf.org/) - the premier event where D luminaries exchange knowledge, insight, and inspiration on everything related to the D language and its ecosystem.

## Organizations

*Organizations that contribute to D projects.*

* [D Programming Language](https://github.com/dlang) - Official Organization, hosts DMD, Phobos and other official tools and libs.
* [LDC Developers](https://github.com/ldc-developers) - LDC releated projects.
* [DerelictOrg](https://github.com/DerelictOrg) - A GitHub organization hosting all Derelict bindings including OpenGL and other multimedia/game related library bindings. (OpenGL 3, Bgfx, ENet,  SDL 2, GLFW 3，OpenGLES, Free Image, Assimp3, libtheora, libogg, libvorbis, SFML 2, libpq, PhysicsFS, Open Dynamics Engine, Lua, DevIL, OpenAL, ALURE).
* [DlangScience](https://github.com/DlangScience) -A focal point and first port of call for scientific libraries and tooling for D.
* [Circular Studios](https://github.com/Circular-Studios) - We are a group of game developers at Rochester Institute of Technology building games and game tech. Hosts [Dash](https://github.com/Circular-Studios/Dash), a 3D game engine written in D, and other related libs.
* [d-gamedev-team](https://github.com/d-gamedev-team) - An organization of gamedev related repos, including a D gamedev toolkit called [gfm](https://github.com/d-gamedev-team/gfm) and an [opengl tutorial in D](https://github.com/d-gamedev-team/opengl-tutorials).
* [EMSI](https://github.com/economicmodeling) - A Career building company that uses D as their main language. Hosts their opensource projects.
* [infognition](http://www.infognition.com/company.html) - Infognition is a self-funded and self-sustained company specializing in video processing and compression technologies for end-users and developers. They provide several opensource video related applications & tools written in D, hosted on [bitbucket](https://bitbucket.org/infognition/). They are also porting their main product--[Video Enchanser](http://www.infognition.com/VideoEnhancer/) from C/C++ to D.
* [libmir](https://github.com/libmir) - D's numeric library development team
* [sociomantic labs](https://www.sociomantic.com) - Berlin based company specializing in real-time bidding for online advertising. Main sponsor of the [annual D language conference](http://dconf.org). Has open-sourced large parts of their codebase as part of the [tsunami](https://github.com/sociomantic-tsunami) organization.

## Books
*D related books.* You can find another list of books on the [Books](http://wiki.dlang.org/Books) D wiki page.
* [TDPL](http://www.amazon.com/The-Programming-Language-Andrei-Alexandrescu/dp/0321635361/) - *The D Programming Language* by Andrei Alexandrescu.
* [Programming in D](http://ddili.org/ders/d.en/index.html) - A very detailed book about programming in D by Ali Çehreli  covering many areas of the language. Has a free online version and is suitable for beginners. 
* [D Cookbook](http://www.packtpub.com/application-development/d-cookbook) - A recipe-packed reference guide filled with practical tasks that are concisely explained to develop and broaden the user's abilities with the D programming language. by Adam D. Ruppe. Here is an interesting [review of the book](http://www.bfilipek.com/2014/08/review-of-d-cookbook.html).
* [Learning D](https://www.packtpub.com/application-development/learning-d) - This book is intended for those with some background in a C-family language who want to learn how to apply their knowledge and experience to D. (...) This book will help you get up to speed with the language and avoid common pitfalls that arise when translating C-family experience to D.
* [D Web Development](https://www.packtpub.com/web-development/d-web-development) - Whether you are new to the world of D, or already have developed applications in D, or if you want to leverage the power of D for web development, then this book is ideal for you.

## Tutorials
*D related tutorials.*
* [The Dlang Tour](https://tour.dlang.org/) - An interactive tutorial for D, inspired by Golang Tour.
* [Pragmatic D tutorial](http://qznc.github.io/d-tut/index.html) - This is a pragmatic introduction to the D Programming Language. by Andreas Zwinkau.
* [D Template Tutorial](https://github.com/PhilippeSigaud/D-templates-tutorial) - A tutorial dedicated to D Templates. Very good explanation about templates. Has pdf version. by Philippe Sigaud. :star:174
* [Component programming in D](http://www.drdobbs.com/architecture-and-design/component-programming-in-d/240008321) - An article written by Walter Bright that details how D's functional support leads to a flexible and beautiful component programming style.
* [Component programming with ranges](http://wiki.dlang.org/Component_programming_with_ranges) - A detailed blog post about how to do component programming in a idiomatic D way with ranges, with a full working example.
* [Functional image processing in D](http://blog.thecybershadow.net/2014/03/21/functional-image-processing-in-d/) - A very interesting tutorial about writing an image processing lib in D. Shows the power of D's templates/CTFE/Ranges/UFCS for functional style programming.
* [OpenGL tutorials](https://github.com/d-gamedev-team/opengl-tutorials) - OpenGL tutorials in D. :star:49

### Bare metal / kernel development
* [D Bare bones](http://wiki.osdev.org/D_Bare_Bones) - kernel hello world in D (using GDC compiler)
* [D barebone with ldc2](http://wiki.osdev.org/D_barebone_with_ldc2) - another kernel hello world in D (using LDC compiler)
* [XOmB bare bones](http://wiki.xomb.org/index.php?title=XOmB_Bare_Bones) - an exokernel operating system written in D. [Main page](http://wiki.xomb.org/index.php?title=Main_Page), [github](https://github.com/xomboverlord/xomb/tree/unborn).
* [Bare Metal ARM Cortex-M GDC Cross Compiler](http://wiki.dlang.org/Bare_Metal_ARM_Cortex-M_GDC_Cross_Compiler) - building a bare metal ARM Cortex-M (arm-none-eabi) GDC cross compiler for a Linux host.

## Blogs
*D related blogs.*

* [blog.dlang.org](https://dlang.org/blog/) - Official blog.
* [This week in D](http://arsdnet.net/this-week-in-d) - A weekly overview of activity in the D community and brief advice columns to help you get the most out of the D Programming Language. 
* [Planet D](http://planet.dsource.org) - A repository of co-authored D-specific blogs maintained by Vladimir Panteleev.
* [D Idioms](http://p0nce.github.io/d-idioms/) - A great blog for many useful idioms with D programming.

## Articles
*D related Aritcles.*

* [Purity in D](http://klickverbot.at/blog/2012/05/purity-in-d/) - An article that explains the design principles behind D's purity feature.
* [Hidden treasures in the D standard library](http://nomad.so/2014/08/hidden-treasure-in-the-d-standard-library/) - An article talking about several useful functions and templates in Phobos.
* [Porting D Runtime to ARM](https://github.com/JinShil/D_Runtime_ARM_Cortex-M_study) - A study about porting a minimal D runtime to ARM Cortex-M preprocessors. :star:26
* [D is for Data Science](http://tech.adroll.com/blog/data/2014/11/17/d-is-for-data-science.html) - A great post about how D is suitable for data science, particularly, replacing the role of python scripts for fast prototyping.
* [D Functional Garden](https://garden.dlang.io/)

## Package Management

*Libraries for package and dependency management.*

* [code.dlang.org](http://code.dlang.org/) - Official D library repository. Backed by dub.
* [dub](https://github.com/dlang/dub) - Official package and build management system for D. :star:402

 
## Compilers

*Compile software from source code.*

* [dmd](https://github.com/dlang/dmd) - The reference compiler for the D programming language. Stable, builds insanely fast, very good for learning and rapid prototyping/development. Currently the frontend is implemented in D, and shared between dmd, ldc and gdc, the backend is implemented in C++. :star:1781
* [ldc](https://github.com/ldc-developers/ldc) - The LLVM-based D compiler. Uses the DMD frontend and LLVM backend. Builds slower than dmd, but generates more optimized code than DMD. It supports all the target platforms of LLVM. :star:680
* [gdc](https://github.com/D-Programming-GDC/GDC) - GNU D Compiler. Use DMD frontend and GCC backend. Currently targets the most platforms due to the use of GCC. Generated code runs faster than DMD in most cases, on par with LDC. In the process of integration with the official GCC toolchain. :star:342
* [sdc](https://github.com/SDC-Developers/SDC) - The Stupid D Compiler. Written in D. Grows Smarter every day. :star:151
* [dil](https://code.google.com/p/dil/) - A compiler for the D programming language. Written in D.


## Build Tools

*Manage projects and compile software from source code.*

* [dub](https://github.com/dlang/dub) - De facto official package and build management system for D. Will be included officially soon. :star:402
* [scons-d](http://scons.org/) - Scons has built-in support for building D projects, thanks to Russel Winder.
* [premake](https://github.com/premake/premake-dlang) - Premake has built-in support for D projects :star:2
* [reggae](https://github.com/atilaneves/reggae) - meta build system in D :star:56
* [Makefile](https://github.com/bioinfornatics/MakefileForD) - Makefile template for D projects :star:17
* [cmake-d](https://github.com/dcarp/cmake-d) - CMake D Projects :star:32
* [cook2](https://github.com/gecko0307/Cook2) - Fast incremental build tool intended for projects in D :star:17
* [button](http://jasonwhite.github.io/button/) - A universal build system to build your software at the push of a button.
* [wild](https://github.com/Vild/Wild) - Wild build system, used to build the [PowerNex](https://github.com/Vild/PowerNex) kernel :star:7

## IDE

*Integrated Development Environment.*

* [Mono-D](https://github.com/aBothe/Mono-D) - A D language addon for [Xamarin Studio](http://xamarin.com/)/[MonoDevelop](http://www.monodevelop.com/). With dub support. :star:112
* [Visual D](https://github.com/dlang/visuald) - Visual Studio extension for the D programming language. :star:189
* [DDT](http://ddt-ide.github.io/) - Eclipse plugin for the D programming language.
* [DCD](https://github.com/Hackerpilot/DCD) - Independent auto-complete program for the D programming language. Could be used with editors like vim, emacs, sublime text, textadept, and zeus. See [editors support](https://github.com/Hackerpilot/DCD/wiki/IDEs-and-Editors-with-DCD-support). :star:257
* [Coedit](https://github.com/BBasile/Coedit) - IDE for the D programming language, its compilers, tools and libraries. :star:191
* [Dlang IDE](https://github.com/buggins/dlangide) - D language IDE based on [DlangUI](https://github.com/buggins/dlangui). This is a pure D implementation. :star:236

 
## Lexers, Parsers, Parser Generators

* [libdparse](https://github.com/Hackerpilot/libdparse) - A D language lexer and parser, (possibly) future standard D parser/lexer. :star:61
* [Martin Nowak's Lexer](https://github.com/MartinNowak/lexer) - A lexer generator. :star:9
* [Mono-D's DParser](https://github.com/aBothe/D_Parser) - A D parser written in C# and used in Mono-D. :star:24
* [Pegged](https://github.com/PhilippeSigaud/Pegged) - A Parsing Expression Grammar (PEG) module written in D. :star:343
* [Goldie](https://bitbucket.org/Abscissa/goldie/wiki/Home) - Goldie Parsing System.
* [ctpg](https://github.com/youxkei/ctpg) - Compile-Time Parser (with converter) Generator written in D. :star:40
* [dunnart](https://github.com/pwil3058/dunnart) - LALR(1) Parser Generator written in D. :star:9

## Preprocesors

* [warp](https://github.com/facebookarchive/warp) - A fast preprocessor for C and C++ used in Facebook infrastructure. Written by Walter Bright. :star:451

## Javascript
* [higgs](https://github.com/higgsjs/Higgs) -  Higgs JavaScript Virtual Machine, implemented in D. :star:779


## Containers
* [EMSI containers](https://github.com/economicmodeling/containers) -  Containers that do not use the GC  :star:94
- [memutils](https://github.com/etcimon/memutils) - Overhead allocators, allocator-aware containers and lifetime management for D objects :star:34
- [dlib.container](https://github.com/gecko0307/dlib) - generic data structures (GC-free dynamic and associative arrays and more)
- [std.rcstring](https://github.com/burner/std.rcstring) - A reference counted string implementation for D's build in string construct :star:7

## Web Frameworks

*Networking library*
* [libasync](https://github.com/etcimon/libasync) -  Cross-platform event loop library of asynchronous objects :star:111
* [libhttp2](https://github.com/etcimon/libhttp2) -  HTTP/2 library in D, translated from nghttp2 :star:31
* [collie](https://github.com/huntlabs/collie) -  An asynchronous event-driven network framework written in dlang, like netty framework in D. :star:57

*Full stack web frameworks.*
* [Hunt](http://www.huntframework.com/) - Hunt is a high-level D Programming Language Web framework that encourages rapid development and clean, pragmatic design. It lets you build high-performance Web applications quickly and easily.
* [vibe.d](http://vibed.org/) - Asynchronous I/O Web Framework that doesn’t get in your way, written in D.
* [arsd](https://github.com/adamdruppe/arsd) - Adam D. Ruppe's web framework. :star:327
* [cmsed](https://github.com/rikkimax/Cmsed) - A component library for Vibe that functions as a CMS. :star:16
* [diamond](https://github.com/DiamondMVC/Diamond/) - Powerful MVC / Template Framework inspired by ASP.NET, based on vibe.d

*RPC library*
* [kissrpc](https://github.com/huntlabs/kiss-rpc) - Fast and light, flatbuffers based rpc framework. :star:29
* [Hprose](https://github.com/hprose/hprose-d) - A very newbility RPC Library for D, and it support 25+ languages now. :star:24

## Data serialization
*Json, XML, protobuf and other data serialization libs.*

### Binary Serilization
* [flatbuffers](https://github.com/huntlabs/flatbuffers) - D Programming Language implementation of the google flatbuffers library. :star:12
* [cerealed](https://github.com/atilaneves/cerealed)  - Serialisation library for D 
* [dproto](https://github.com/msoucy/dproto) - Google Protocol Buffer support in D. :star:35

### JSON

* [vibe.data.json](http://vibed.org/api/vibe.data.json/) - JSON functions in Vibe.d. Currently the best implementation I used.
* [fast.json](https://github.com/mleise/fast) -  A library for D that aims to provide the fastest possible implementation of some every day routines. :star:75
* [std.json](http://dlang.org/phobos/std_json.html) - D's standard library JSON module. Needs refinement.
* [painlessjson](https://github.com/BlackEdder/painlessjson) - Convert between D types and std.json. :star:16
* [std.data.json](https://github.com/s-ludwig/std_data_json) - Phobos candidate for JSON serialization (based on Vibed)
* [asdf](https://github.com/tamediadigital/asdf) - Cache oriented string based JSON representation for fast read & writes and serialisatoin. :star:47

### XML

* [orange](https://github.com/jacob-carlborg/orange) - General purpose serializer (currently only supports XML)
* [std.experimental.xml](https://github.com/lodo1995/experimental.xml) - Phobos candidate for a XML serialization :star:24
* [dom.d] - an xml/html DOM based on what Javascript provides in browsers

## Database clients
*Clients and bindings to C bliencts for relational and nosql databases.*

* [entity](https://github.com/huntlabs/entity) - Entity is an object-relational mapping tool for the D programming language. Referring to the design idea of JPA, support PostgreSQL / MySQL / SQLite. :star:19
* [dbal](https://github.com/huntlabs/dbal) - Database Abstraction Layer for dlang, can construct SQL statements. :star:2
* [database](https://github.com/huntlabs/database) - Database abstraction layer for D programing language, support PostgreSQL / MySQL / SQLite. :star:15
* [vibe.d](https://github.com/rejectedsoftware/vibe.d) - Vibe.d has internal support for Redis and MongoDB, which are very stable. Soon, the database drivers will be separated into independent projects. :star:913
* [mysql-native](https://github.com/mysql-d/mysql-native) - A MySQL client implemented in native D. :star:61
* [ddb](https://github.com/pszturmaj/ddb) - Database access for D2. Currently only supports PostgreSQL. :star:41
* [arsd](https://github.com/adamdruppe/arsd) - Adam D. Ruppe's library; in addition to a Web backend, it also has support for database access with database.d, sqlite.d, mysql.d and postgres.d. :star:327
* [ddbc](https://github.com/buggins/ddbc) - DDBC is a DB Connector for D language (similar to JDBC). HibernateD (see below) uses ddbc for database abstraction. :star:47
* [hibernated](https://github.com/buggins/hibernated) - HibernateD is an ORM for D (similar to [Hibernate](http://hibernate.org/)). :star:72
* [dvorm](https://github.com/rikkimax/Dvorm) - An ORM for D with Vibe support. Works with vibe.d and mysql-d, giving it the ability to access MongoDB and MySQL. :star:19
* [Tiny Redis](http://adilbaig.github.io/Tiny-Redis/) - Redis driver for D. Fast, Simple, Stable. Has no dependencies.

## Command Line
* [tilix](https://github.com/gnunn1/tilix) -  A tiling terminal emulator for Linux using GTK+ 3. :star:2327
* [scriptlike](https://github.com/Abscissa/scriptlike) - Utility library to aid writing script-like programs in D. :star:69
* [todod](https://github.com/BlackEdder/todod) - Todod is a command line based todo list manager. It also has support for shell interaction based on [linenoise](https://github.com/antirez/linenoise). :star:8
* [d-colorize](http://code.dlang.org/packages/colorize) - A port of the ruby library [colorize](https://github.com/fazibear/colorize). It add some methods to set color, background color and text effect on console easier using ANSI escape sequences.
* [terminal.d](https://github.com/adamdruppe/arsd/blob/master/terminal.d) - Part of Adam Ruppe's [arsd](https://github.com/adamdruppe/arsd) library supporting cursor and color manipulation on the console.
* [dexpect](https://github.com/grogancolin/dexpect/) -  A D implementation of the expect framework. Handy for bash emulation.
* [Argon](https://github.com/markuslaker/Argon) -  A processor for command-line arguments, an alternative to Getopt, written in D.  :star:9
* [argsd](https://github.com/burner/argsd) - A command line and config file parser for DLang :star:6

## GUI Libs
*Libraries for working with graphical user interface applications.*


* [DLangUI](https://github.com/buggins/dlangui) - Cross Platform GUI for D programming language. My personal favorate, because it is written in D(not a binding), and is cross platform. DLangUI also has a good showcase in the IDE [DLangIDE](https://github.com/buggins/dlangide). :star:422
* [GtkD](https://github.com/gtkd-developers/GtkD) - GtkD is a D binding and OO wrapper of GTK+. GtkD is actively maintained and is currently the most stable GUI lib for D. :star:203
* [DWT](https://github.com/d-widget-toolkit/dwt) - A library for creating cross-platform GUI applications. GWT is a port of the Java SWT library to D. DWT was promoted as a semi-standard GUI library for D, but unfortunately didn't catch up popularity yet. :star:92
* [tkD](https://github.com/nomad-software/tkd) - GUI toolkit for the D programming language based on Tcl/Tk. :star:87
* [dqml](https://github.com/filcuc/dqml) -  Qt Qml bindings for the D programming language. :star:28
* [Sciter-Dport](https://github.com/midiway/sciter-dport) - D bindings for the [Sciter](http://sciter.com) - crossplatform HTML/CSS/script desktop UI toolkit.
* [LibUI](https://github.com/Extrawurst/DerelictLibui) - Dynamic Binding for [libui](https://github.com/andlabs/libui) :star:5199

*Note*: You can also find a list of GUI libs on [wiki.dlang.org](http://wiki.dlang.org/Libraries_and_Frameworks#GUI_Libraries), but not all of the libraries are actively maintained now.

## OS

*Operating Systems written in D*

* [PowerNex](https://github.com/Vild/PowerNex) -  A kernel written in D  :star:376
* [Trinix](https://github.com/Bloodmanovski/Trinix) -  Hybrid operating system for x64 PC written in D :star:71
* [XOmB](https://github.com/xomboverlord/xomb) - An exokernel operating system written in D :star:310

## Game Bindings

*Bindings to game development related C libraries.*

* [DerelictOrg](https://github.com/DerelictOrg) - A GitHub organization hosting all Derelict bindings including:
	* OpenGL 3 (DerelictGL3), 
	* Bgfx (DerelictBgfx), 
	* ENet (DerelictENet),  
	* SDL 2 (DerelictSDL2), 
	* GLFW 3 (DerelictGLFW3), 
	* OpenGLES (DerelictGLES), 
	* Free Image (DerelictFI), 
	* Assimp3 (DerelictASSIMP3), 
	* libtheora (DerelictTheora),  
	* libogg (DerelictOgg), 
	* libvorbis (DerelictVorbis), 
	* SFML 2 (DerelictSFML2), 
	* libpq (DerelictPQ), 
	* PhysicsFS (DerelictPHYSFS), 
	* Open Dynamics Engine (DerelictODE), 
	* Lua (DerelictLua), 
	* DevIL (DerelictIL), 
	* OpenAL (DerelictAL), 
	* ALURE (DerelictALURE).

## Game Frameworks

* [DGame](https://github.com/Dgame/Dgame) - A 2D framework for the D programming Language. see <http://dgame-dev.de/>. :star:72
* [gfm](https://github.com/d-gamedev-team/gfm) - D gamedev toolkit. see <http://d-gamedev-team.github.io/gfm/>. :star:158
* [Dash](https://github.com/Circular-Studios/Dash) - A free and open 3D game engine written in D. see <http://circularstudios.com/dash>. :star:375
* [DSFML](https://github.com/Jebbs/DSFML) - A static binding of SFML in a way that makes sense for D. see <http://dsfml.com/>. :star:88
* [DAllegro5](https://github.com/SiegeLord/DAllegro5/tree/master/allegro5) - D binding/wrapper to Allegro 5, a modern game programming library.
* [Voxelman](https://github.com/MrSmith33/voxelman) -  Plugin-based client-server voxel game engine written in D language :star:95

## Games

* [Spacecraft](https://github.com/Ingrater/Spacecraft) - A 3d multiplayer deathmatch space game written in D 2.0. :star:16
* [Dtanks](https://github.com/kingsleyh/dtanks) - Robot Tank Battle Game. :star:10
* [Atrium] (https://github.com/gecko0307/atrium) - FPS game with physics based puzzles using OpenGL.

## Video applications

* [DerelictGL3](https://github.com/DerelictOrg/DerelictGL3) - A dynamic binding to OpenGL for the D Programming Language. :star:75

## Image Processing

* [ArmageddonEngine](https://github.com/CyberShadow/ae/tree/master/utils/graphics) - Vladimir Panteleev's ae library has a package for image processing in functional style, which is described in the article [Functional Image Processing in D](http://blog.thecybershadow.net/2014/03/21/functional-image-processing-in-d/).
* [Blogsort](https://bitbucket.org/infognition/bsort/) -  A simple Windows app for viewing photos and preparing them for a blog.
* [dlib.image](https://github.com/gecko0307/dlib) - image processing (8 and 16 bits per channel, floating point operations, filtering, FFT, HDRI, graphics formats support including JPEG and PNG)
* [color.d](https://github.com/adamdruppe/arsd/blob/master/color.d) + [bmp.d](https://github.com/adamdruppe/arsd/blob/master/bmp.d), [jpg.d](https://github.com/adamdruppe/arsd/blob/master/jpg.d), [png.d](https://github.com/adamdruppe/arsd/blob/master/png.d) - basic color struct, HSL functions and reading and writing image files

## Machine Learning

* [vectorflow](https://github.com/Netflix/vectorflow) - Nexflix's opensource deep learning framework. :star:917

## Parallel computing

* [DCompute](https://github.com/libmir/dcompute) - [GPGPU with Native D for OpenCL and CUDA](https://dlang.org/blog/2017/07/17/dcompute-gpgpu-with-native-d-for-opencl-and-cuda/)
* [DerelictCUDA](https://github.com/DerelictOrg/DerelictCUDA) - Dynamic bindings to the CUDA library for the D Programming Language. :star:16
* [DerelictCL](https://github.com/DerelictOrg/DerelictCL) - Dynamic bindings to the OpenCL library for the D Programming Language. :star:4

## Scientific
*Scientific programming*

* [scid](https://github.com/DlangScience/scid) -  Scientific library for the D programming language :star:77
* [dstats](https://github.com/DlangScience/dstats) -  A statistics library for D.  :star:17
* [mir](https://github.com/libmir/mir) -  Sandbox for some mir packages: sparse tensors, Hoffman and others. :star:164
* [mir-algorithm](https://github.com/libmir/mir) - N-dimensional arrays (matrixes, tensors), algorithms, general purpose library. :star:164
* [mir-random](https://github.com/libmir/mir-random) -  Advanced Random Number Generators. :star:20
* [decimals](https://github.com/rumbu13/decimal) - Decimal library for D. :star:9

## Text Processing

* [eBay's TSV utilities](https://ebay.github.io/tsv-utils-dlang/) - Command line tools for large delimited data files. Filtering, statistics, sampling, joins and more. Very fast.

## Logging
*Print with care.*

- [std.experimenatal.logger](https://dlang.org/phobos/std_experimental_logger.html) - Phobos's upcoming standard logging facility
- [dlogg](https://github.com/NCrashed/dlogg) - Logging for concurrent applications and daemons with lazy and delayed logging, [logrotate](http://linuxcommand.org/man_pages/logrotate8.html) support. :star:13

## Configuration
*Parsing configuration files*

- [sdlang](https://github.com/Abscissa/SDLang-D) - An SDL (Simple Declarative Language) library for D. :star:57
- [D:YAML](https://github.com/kiith-sa/D-YAML) - YAML parser and emitter for the D programming language. :star:82
- [inifile-D](https://github.com/burner/inifiled) - A compile time ini file parser and writter generator for D :star:16

## Blog Engine
*Hosting blogs yourself*

- [mood](https://github.com/Dicebot/mood) - simple vibe.d based blog engine :star:45

## Testing

- [dunit](https://github.com/nomad-software/dunit) - Advanced unit testing & mocking toolkit :star:57
- [unit-threaded](https://github.com/atilaneves/unit-threaded) - Multi-threaded unit test framework :star:84

## Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesome](https://github.com/emijrp/awesome-awesome) and  [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) projects.


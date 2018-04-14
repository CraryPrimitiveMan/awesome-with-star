# Information comes from [aleksandar-todorovic/awesome-c](https://github.com/aleksandar-todorovic/awesome-c)
# awesome-c [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of C good stuff. This list contains *only* [free software](https://en.wikipedia.org/wiki/Free_software) for code, and sellers who aren't evil for physical resources.

**LOOKING FOR MAINTAINERS:** This list is currently pretty much inactive. I'm looking for maintainers that can make it great again. See [#26](https://github.com/aleksandar-todorovic/awesome-c/issues/26) for more info, but the process is simple: add or fix a couple of things in this list and you'll become a contributor to a 850+ stars list.

This list was previously maintained by [@kozross](https://github.com/kozross). He decided to switch the list to a [new platform](https://notabug.org/koz.ross/awesome-c), so I've decided to fork it so we could keep it on GitHub.

Contents
========

## Contents ##

- [Build Systems](#build-systems)
- [Compilers](#compilers)
- [Compiler libraries](#compiler-libraries)
- [Compression](#compression)
- [Crypto](#crypto)
- [Database](#database)
- [Deep Learning](#deep-learning)
- [Documentation Generation](#documentation-generation)
- [Editors](#editors)
- [Embedded Systems](#embedded-systems)
  - [RTOS](#rtos)
- [Environments](#environments)
- [Frameworks](#frameworks)
- [Game Programming](#game-programming)
  - [Engines](#engines)
  - [Resources](#resources)
- [Generic Programming](#generic-programming)
- [Graphics](#graphics)
  - [Graphic APIs](#graphic-apis)
- [Graphical User Interface](#graphical-user-interface)
- [Hashing](#hashing)
- [Image Processing](#image-processing)
- [JSON](#json)
- [Learning, Reference and Tutorials](#learning-reference-and-tutorials)
  - [Online](#online)
      - [Reference](#reference)
        - [Language Standards](#language-standards)
      - [Beginner](#beginner)
      - [Intermediate](#intermediate)
      - [Advanced](#advanced)
      - [Self-study courses](#self-study-courses)
  - [Physical](#physical)
      - [Reference](#reference-1)
      - [Beginner](#beginner-1)
      - [Intermediate](#intermediate-1)
      - [Advanced](#advanced-1)
- [Macros](#macros)
- [Memory Allocators](#memory-allocators)
- [Multimedia](#multimedia)
- [Networking and Internet](#networking-and-internet)
  - [Web Frameworks](#web-frameworks)
- [Numerical](#numerical)
- [Parallel Programming](#parallel-programming)
- [Parsers](#parsers)
- [Regex](#regex)
- [Serialization](#serialization)
- [Source Code Collections](#source-code-collections)
- [Standard Libraries](#standard-libraries)
- [String Manipulation](#string-manipulation)
- [Testing](#testing)
- [Text Editor Extensions](#text-editor-extensions)
  - [Atom](#atom)
  - [Emacs](#emacs)
  - [Vim](#vim)
- [Tools](#tools)
- [Utilities](#utilities)
- [XML](#xml)

## Build Systems ##

These are tools to automate the building and testing of projects in C.

* [aimake](http://nethack4.org/projects/aimake/) - Build tool designed to avoid complex configurations. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [Autoconf](https://www.gnu.org/software/autoconf/) - Extensible package of M4 macros that produce shell scripts to automatically configure software source code packages. Part of the Autotools. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [Automake](https://www.gnu.org/software/automake/automake.html) - Tool for automatically generating ``Makefile.in`` files compliant with the GNU Coding Standards. Requires the use of Autoconf. Part of the Autotools. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [CMake](https://cmake.org/) - Tools for cross-platform building, testing, and packaging. [[3-clause BSD](https://gitlab.kitware.com/cmake/cmake/raw/master/Copyright.txt)]
* [Jam](https://www.perforce.com/documentation/jam-documentation) - Build system, designed to be easier than make. Understands C build rules implicitly. [[Jam License](https://en.wikipedia.org/wiki/Perforce_Jam#License)]
* [Libtool](https://www.gnu.org/software/libtool/) - Generic library support script. Part of the Autotools. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [Meson](http://mesonbuild.com/) - Extremely fast, user-friendly build system. Based on Ninja. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)]
* [Premake](https://github.com/premake/premake-core) - Build script generator for toolsets like Visual Studio, Xcode, or GNU Make. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] :star:899
* [SCons](http://www.scons.org/) - An easier, more reliable and faster way to build software. [[MIT License](https://raw.githubusercontent.com/atom/atom/master/LICENSE.md)]
* [Ninja](https://github.com/ninja-build/ninja) - Small, simple build system with a focus on speed. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:3331
* [Bazel](https://github.com/bazelbuild/bazel) - Build system for various operating systems and targets. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:8687
* [Buck](https://github.com/facebook/buck) - Build system created and used by Facebook. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:5722
* [Qbs](https://wiki.qt.io/Qbs) - Modern build tool for software projects. [[LGPL3](https://code.qt.io/cgit/qbs/qbs.git/tree/LICENSE.LGPLv3)]
* [qmake](https://doc.qt.io/qt-5/qmake-manual.html) - Build system included with the Qt Framework. [[GNU GPL3 with Qt Exception](https://github.com/qt/qtbase/blob/5.11/LICENSE.GPL3-EXCEPT)]
* [xmake](https://github.com/tboox/xmake) - Cross-platform build utility based on lua. [[Apache 2.0](https://github.com/tboox/xmake/blob/master/LICENSE.md)] :star:843

## Compilers ##

* [Clang](http://clang.llvm.org/) - C compiler for LLVM. Supports C11. [[NCSA](https://directory.fsf.org/wiki/License:IllinoisNCSA)]
* [CompCert](https://github.com/AbsInt/CompCert) - Fully-verified C compiler. Supports almost all of C89. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) or later] :star:493
* [GCC](https://gcc.gnu.org/) - Provides a C compiler as part of its compiler set. Supports C11 and OpenMP. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [PCC](http://pcc.ludd.ltu.se/) - Venerable C compiler. Supports C99. [[Various free licenses](http://pcc.ludd.ltu.se/licenses/)]
* [TCC](https://bellard.org/tcc/) - Tiny C Compiler; a small, fast C compiler. Supports C99 (except complex types). [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only]
* [Intel SPMD](https://github.com/ispc/ispc) - Compiler for a variant of the C language, for single program, multiple data programming :star:926
* [ccache](https://ccache.samba.org/) - Compiler cache designed to speedup recompilation. [[GNU GPL3 or later](https://ccache.samba.org/license.html)]

## Compiler libraries ##

Libraries for use in compilers, interpreters, and low-level based projects.

* [yasm](https://github.com/yasm/yasm) - Yasm Modular Assembler Project. [[2-clause BSD](https://directory.fsf.org/wiki/License:BSD_2Clause)] :star:599

## Compression ##

* [libzip](https://github.com/nih-at/libzip) - A C library for reading, creating, and modifying zip archives. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] :star:81
* [lzo](http://www.oberhumer.com/opensource/lzo/) - Very fast data compression library. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)]
* [zlib](https://github.com/madler/zlib) - Massively-spiffy yet delicately-unobtrusive compression library. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] :star:1344
* [bzip2](http://www.bzip.org/1.0.6/bzip2-1.0.6.tar.gz) - Patent free, high quality data compressor. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]
* [lz4](https://github.com/lz4/lz4) - Fast Compression algorithm. :star:2785
* [snappy](https://github.com/google/snappy) - Fast compression library (implementation in C++, native bindings to C)
* [zstd](https://github.com/facebook/zstd) - Fast real-time compression algorithm [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] :star:7094
* [brotli](https://github.com/google/brotli) - Generic lossless compression algorithm based on LZ77, Huffman coding and 2nd order context modelling [[MIT](https://raw.githubusercontent.com/atom/atom/master/LICENSE.md)] :star:5854
* [quicklz](http://www.quicklz.com/download.html) - Fast compression library. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only]

## Crypto ##

* [GnuTLS](https://www.gnutls.org/) - Secure communication library, implementing SSL, TLS and DTLS. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) or later]
* [libgcrypt](https://www.gnu.org/software/libgcrypt/) - General-purpose cryptography library, with a range of available ciphers. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) or later (code)] and [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) or later (manual and tools)]
* [OpenSSL](https://www.openssl.org/) - Implementation of the SSL and TLS protocols, and also includes a cryptography library. [[Dual Licensed under the OpenSSL License and the SSLeay License](https://www.openssl.org/source/license.html)]
* [libsodium](https://github.com/jedisct1/libsodium) - Modern and easy-to-use crypto library. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:5526
* [libtomcrypt](https://github.com/libtom/libtomcrypt) - Fairly comprehensive, modular and portable cryptographic toolkit. [Public domain] :star:671
* [mbed TLS](https://tls.mbed.org/) - Another crypto implementation for C. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)]
* [libressl](https://www.libressl.org/) - Modernized fork of OpenSSL. [[Various licenses](https://cvsweb.openbsd.org/cgi-bin/cvsweb/~checkout~/src/lib/libssl/LICENSE?rev=1.12)]

## Database ##

This lists databases and data stores with C APIs.

* [BerkeleyDB](https://www.oracle.com/database/berkeley-db/index.html) - Library for a high-performance embedded database for key-value data. [[GNU AGPLv3](https://www.gnu.org/licenses/agpl.html) only]
* [Hiredis](https://github.com/redis/hiredis) - Minimalistic client library for Redis. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] :star:2979
* [LMDB](https://github.com/LMDB/lmdb) - Ultra-fast, ultra-compact key-value embedded data store. [[newOpenLDAP](https://directory.fsf.org/wiki/License:OpenLDAPv2.7)] :star:864
* [MariaDB](https://mariadb.com/) - Robust, scalable and reliable SQL server, designed to be a drop-in replacement for MySQL. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]
* [mongo-c-driver](https://github.com/mongodb/mongo-c-driver) - High-performance client library for [MongoDB](https://www.mongodb.com/). [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:390
* [PostgreSQL](https://www.postgresql.org/) - Powerful object-relational database system. [[PostgreSQL licence](https://opensource.org/licenses/postgresql)]
* [recutils](https://www.gnu.org/software/recutils/) - Set of tools and a C library for accessing human-editable, plaintext database files called recfiles. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [Redis](https://redis.io/) - Advanced key-value store. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]
* [sophia](https://github.com/pmwkaa/sophia) - Modern, embeddable key-value database. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)] :star:1559
* [SQLite](http://www.sqlite.org/index.html) - Self-contained, serverless, zero-configuration, transactional SQL database engine with a C interface. [Public domain]
* [UnQLite](https://unqlite.org/) - Self-contained, serverless, zero-configuration, transactional NoSQL engine with a C interface. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)]

## Deep Learning ##
* [Darknet](https://pjreddie.com/darknet/) - Open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

## Documentation Generation ##

* [Cxref](http://www.gedanken.org.uk/software/cxref/) - Generates documentation of C programs in either LaTeX, HTML, RTF or SGML. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only]
* [DocOnce](https://hplgit.github.io/doconce/doc/web/index.html) - Modestly-tagged markup language that can be used to generate a range of formats. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]
* [Doxygen](http://www.stack.nl/~dimitri/doxygen/index.html) - The de-facto standard tool for generating C documentation from annotated sources. Can generate a large range of formats. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only]
* [GTK-Doc](https://www.gtk.org/gtk-doc/) - Tool for generating C documentation from annotated sources. Has support for the Autotools. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only (code)] or [[GNU FDL1.1](https://www.gnu.org/licenses/old-licenses/fdl-1.1.html)]

## Editors ##

These are specifically fancier, IDE-type editors. If you want a programmer's text editor, look elsewhere. Besides, whatever choice you make most likely supports C anyway.

* [Anjuta DevStudio](http://anjuta.org/) - The GNOME IDE. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only]
* [Atom](https://atom.io/) - Hackable text editor for the 21st century. [[MIT](https://raw.githubusercontent.com/atom/atom/master/LICENSE.md)]
* [Code::Blocks](http://www.codeblocks.org/) - Extensible, configurable IDE supporting C. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) only]
* [CodeLite](https://codelite.org/) - Cross-platform IDE. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only]
* [Eclipse](http://www.eclipse.org/ide/) - IDE written in Java. [[EPL](https://directory.fsf.org/wiki/License:EPLv1.0)]
* [Geany](https://www.geany.org/) - Very small and fast IDE. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) or later]
* [KDevelop](https://www.kdevelop.org/) - The KDE IDE. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only]
* [Qt Creator](https://www.qt.io/qt-features-libraries-apis-tools-and-ide/) - Cross-platform IDE written with C++ and Qt, part of the Qt SDK. Supports Clang Code Model. [[GNU GPL3 with Qt exception](https://github.com/qt-creator/qt-creator/blob/master/LICENSE.GPL3-EXCEPT) only]
* [Visual Studio Code](https://code.visualstudio.com/) - Code editing, redefined. Visual Studio Code.

## Embedded Systems ##

These are projects that allow one to work with microcontrollers and other resource constrained architectures.

### RTOS ###

A real-time operating system (RTOS) is intended to serve real-time applications that process data with low latency delay.

* [Amazon FreeRTOS](https://github.com/aws/amazon-freertos) - RTOS for microcontrollers that makes small, low-power edge devices easy to program. [[MIT](https://github.com/aws/amazon-freertos/blob/master/LICENSE)] :star:471
* [ChibiOS](http://www.chibios.org/dokuwiki/doku.php) - RTOS with complete development environment (HAL, drivers, support files, and tools). [[Various](http://www.chibios.org/dokuwiki/doku.php?id=chibios:licensing:start)]
* [Contiki](https://github.com/contiki-os/contiki) - Connect low-cost, low power microcontrollers to the Internet. [[3-clause BSD](https://github.com/contiki-os/contiki/blob/master/LICENSE)] :star:2697
* [Zephyr Project](https://github.com/zephyrproject-rtos/zephyr) - Scalable real-time RTOS supporting multiple hardware architectures, optimized for resource constrained devices. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:775

## Environments ##

This is a list of technologies designed to bring Windows into the 21st century with respect to support for C.

* [Cygwin](https://cygwin.com/) - Designed to emulate a POSIX-compatible environment extensively under Windows. [[Various free licenses](https://cygwin.com/licensing.html)]
* [MinGW-w64](http://mingw-w64.yaxm.org/doku.php/start) - Minimalist environment for C development on Windows with 64 bit support. [[Various free licenses](http://mingw.org/license)]

## Frameworks ##

This section has big libraries that provide data structures and other stuff you expect of a 'modern' standard library.

* [APR](http://apr.apache.org/) - Apache Portable Runtime; another library of cross-platform utility functions. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)]
* [C Algorithms](https://github.com/fragglet/c-algorithms) - Collection of common algorithms and data structures for C. [[ISC](https://directory.fsf.org/wiki/License:ISC)] :star:1246
* [CPL](http://www.eso.org/sci/software/cpl/) - The Common Pipeline Library; a set of libraries designed to be a comprehensive, efficient and robust software toolkit. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only]
* [EFL](https://www.enlightenment.org?p=about%252Fefl) - Large collection of useful data structures and functions. [Various free licenses]
* [GLib](https://wiki.gnome.org/Projects/GLib) - Library of utility functions and structures, designed to be portable, efficient and powerful. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only]
* [GIO](https://developer.gnome.org/gio/) - Modern and easy-to-use VFS API. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only]
* [GObject](https://developer.gnome.org/gobject/stable/) - Object-oriented system and object model for C. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only]
* [libnih](https://github.com/keybuk/libnih) - Lightweight library of C functions and structures. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only] :star:43
* [libU](http://www.koanlogic.com/libu/) - Small library of basic utilities, including memory allocation, string manipulation and logging. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]
* [PBL](http://www.mission-base.com/peter/source/) - Large library of utilities, featuring data structures, among other things. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) or later (library)] or [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) or later (test code)]
* [qlibc](https://github.com/wolkykim/qlibc) - Simple and powerful C library, designed as a replacement for GLib while focusing on being small and light. [[qLib license](https://github.com/wolkykim/qlibc/blob/master/LICENSE) (similar to [FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)] :star:338
* [stb](https://github.com/nothings/stb) - Range of single-file libraries for C. [Public domain] :star:7139
* [libsrt](https://github.com/faragon/libsrt) - Safe Real-Time library for C. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] :star:171


## Game Programming ##

### Engines ###

These are provided as examples of C game programming code.

* [Corange](https://github.com/orangeduck/Corange) - Game engine in pure C. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)] :star:765
* [Darkplaces](https://icculus.org/twilight/darkplaces/) - Modified version of the Quake2 engine. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only]
* [ioquake3](https://github.com/ioquake/ioq3) - The Quake3 engine, freed at last. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only] :star:910
* [Orx](https://bitbucket.org/orx/orx) - Portable, lightweight, plugin-based, data-driven, 2D-oriented game engine. [[zlib](https://directory.fsf.org/wiki/License:Zlib)]
* [Quake](https://github.com/id-Software/Quake) - The Quake engine. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only] :star:1919
* [Quake2](https://github.com/id-Software/Quake-2) - The Quake2 engine. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only] :star:947
* [Spearmint](https://github.com/zturtleman/spearmint) - Engine designed for FPS games. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later] :star:87

### Resources ###

These are libraries of all sorts that are useful for game programming.

* [Allegro](http://liballeg.org) - Cross-platform, video game development and multimedia library. [[zlib](https://directory.fsf.org/wiki/License:Zlib)]
* [Chipmunk2D](https://github.com/slembcke/Chipmunk2D) - Fast and lightweight 2D game physics library. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:1134
* [CSFML](https://www.sfml-dev.org/download/csfml/) - Binding for [SFML](https://www.sfml-dev.org/index.php) in C. [[zlib](https://directory.fsf.org/wiki/License:Zlib)]
* [FreeGLUT](https://github.com/dcnieho/FreeGLUT) - Alternative to the OpenGL Utility Toolkit. Allows the creation and management of windows with OpenGL contexts. [[X11](https://directory.fsf.org/wiki/License:X11)] :star:191
* [GLFW](http://www.glfw.org/) - Multi-platform library for creating windows with OpenGL contexts. [[zlib](https://directory.fsf.org/wiki/License:Zlib)]
* [libao](https://github.com/timonwong/libao) - Cross-platform audio library with a wide variety of outputs. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) or later] :star:6
* [RetroArch](https://github.com/libretro/RetroArch) - The reference frontend for [libretro](https://www.libretro.com/). [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) only] :star:2204
* [SDL](https://www.libsdl.org/) - Cross-platform library designed to provide low-level access to audio, keyboard, mouse, joystick and graphics hardware via OpenGL. [[zlib](https://directory.fsf.org/wiki/License:Zlib)]
* [SDL2](https://www.libsdl.org/)- Cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL. This is the most current version. [[zlib](https://directory.fsf.org/wiki/License:Zlib)]
* [raylib](https://github.com/raysan5/raylib) - Simple and easy-to-use library to learn videogames programming. [zlib](https://directory.fsf.org/wiki/License:Zlib)

## Generic Programming ##

* [klib](https://github.com/attractivechaos/klib) - Small and lightweight implementations of common algorithms and data structures. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:2057

## Graphics ##

* [Cairo](https://www.cairographics.org/) -2D graphics library. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only] or [[MPLv1.1](https://directory.fsf.org/wiki/License:MPLv1.1)]
* [Cogl](https://github.com/rib/cogl-web/wiki) - GPU graphics and utilities API. [[Expat](https://directory.fsf.org/wiki/License:Expat)]
* [Clutter](https://blogs.gnome.org/clutter/get-it/) - UI library based on OpenGL. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only]
* [giflib](https://sourceforge.net/projects/giflib/) - Library for reading and writing gif images. [[MIT](https://spdx.org/licenses/MIT.html)]
* [heman](https://github.com/prideout/heman) - Tiny library of image utilities dealing with height maps, normal maps, distance fields and the like. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:295
* [libcaca](https://github.com/cacalabs/libcaca) - ASCII renderer for terminal-based interfaces. [[WTFPLv2](http://www.wtfpl.net/txt/copying/)] :star:160
* [libimagequant](https://pngquant.org/lib/) - Small, portable library for high-quality conversion of RGBA images to 8-bit indexed colour images. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)]
* [libjpeg-turbo](https://libjpeg-turbo.org/) - Faster library for reading and writing JPEG files. [[Various free licenses](https://libjpeg-turbo.org/About/License)]
* [libpng](http://www.libpng.org) - The official PNG reference library. [[libpng license](http://www.libpng.org/pub/png/src/libpng-LICENSE.txt)]
* [libxmi](https://www.gnu.org/software/libxmi/) - Function library for rasterizing 2D vector graphics. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [mozjpeg](https://github.com/mozilla/mozjpeg) - Improved JPEG encoder. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] :star:2967

### Graphic APIs ###

* [OpenGL](https://www.opengl.org/) - Industry adopted 2D and 3D graphics API. More resources at [awesome-opengl](https://github.com/eug/awesome-opengl).
* [OpenGL ES](https://www.khronos.org/opengles/) - Industry adopted 2D and 3D graphics API for mobile and embedded devices.
* [OpenGL SC](https://www.khronos.org/openglsc/) - Graphic and compute standard for industry requiring system safety certification.
* [Vulkan](https://www.khronos.org/vulkan/) - Explicit graphic and compute API for modern cross-platform development. More resources at [awesome-vulkan](https://github.com/vinjn/awesome-vulkan).

## Graphical User Interface ##

These are specifically [widget toolkits](https://en.wikipedia.org/wiki/Widget_toolkit).

* [GTK+](https://www.gtk.org/) - Cross-platform widget toolkit. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only]
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/) - Another cross-platform widget toolkit. [[Expat](https://directory.fsf.org/wiki/License:Expat)]
* [Tk](http://www.tcl.tk/) - Basic widget toolkit. Part of Tcl/Tk. [[Tcl/Tk License](http://www.tcl.tk/software/tcltk/license.html)]
* [XForms Toolkit](http://xforms-toolkit.org/) - Widget toolkit designed for the XWindow system. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only]
* [nuklear](https://github.com/vurtun/nuklear) - Single-header ANSI C gui library. [Public domain] :star:9934
* [libui](https://github.com/andlabs/libui) - Simple and portable (but not inflexible) GUI library. [[MIT](https://github.com/andlabs/libui/blob/master/LICENSE)] :star:5193
* [LCUI](http://lcui.org/) - Small C library for building user interfaces with C, XML and CSS. [[MIT](https://github.com/lc-soft/LCUI/blob/develop/LICENSE.TXT)]

## Hashing ##

All hashing related libraries, cryptographic or not.

* [jwHash](https://github.com/watmough/jwHash) - Fast hashtable implementation. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:203
* [xxHash](https://github.com/Cyan4973/xxHash) - Extremely fast non-cryptographic hash algorithm. [[2-clause BSD](https://directory.fsf.org/wiki/License:BSD_2Clause)] :star:1911
* [libcrc](https://github.com/PeterScott/murmur3) - Multi platform CRC library. [[MIT License]](https://raw.githubusercontent.com/atom/atom/master/LICENSE.md)
* [murmur](https://github.com/ispc/ispc) - C implementation of MurMur Hashing [Public domain] :star:926

## Image Processing ##

* [libccv](http://libccv.org) - Modern Computer Vision Library. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]

## JSON ##

* [Jansson](http://www.digip.org/jansson/) - C library for encoding, decoding and manipulating JSON. [[Expat](https://directory.fsf.org/wiki/License:Expat)]
* [jsmn](https://zserge.com/jsmn.html) - Minimalistic JSON parser. [[Expat](https://directory.fsf.org/wiki/License:Expat)]
* [json-c](https://github.com/json-c/json-c/wiki) - Library for working with JSON. [[Expat](https://directory.fsf.org/wiki/License:Expat)]
* [parson](https://github.com/kgabis/parson) - Lightweight JSON library written in C. [[MIT License]](https://raw.githubusercontent.com/atom/atom/master/LICENSE.md)
* [WJElement](https://github.com/netmail-open/wjelement/) - Advanced JSON manipulation library, with support for JSON Schema. [LGPL, any version]
* [YAJL](https://lloyd.github.io/yajl/) - Fast C JSON streaming parser library. [[ISC](https://directory.fsf.org/wiki/License:ISC)]

## Learning, Reference and Tutorials ##

This is a list of resources for learning C programming in general, or something useful relating to C programming.

### Online ###

#### Reference ####

* [SEI CERT C Coding Standard](https://wiki.sei.cmu.edu/confluence/display/c/SEI+CERT+C+Coding+Standard)
* [C FAQ - comp.lang.c Frequently Asked Questions](http://c-faq.com/)
* [Comparison of C/POSIX standard library implementations for GNU/Linux](http://www.etalabs.net/compare_libcs.html)
* [GNU C Reference Manual](https://www.gnu.org/software/gnu-c-manual/)
* [Robert Pike's notes on programming in C](http://www.lysator.liu.se/c/pikestyle.html)
* [Draft ANSI C Rationale](http://port70.net/~nsz/c/c89/rationale/)
* [Draft C99 Rationale](http://port70.net/~nsz/c/c99/C99RationaleV5.10.pdf)

##### Language Standards #####
* [Draft ANSI C (C89) standard](http://port70.net/~nsz/c/c89/c89-draft.txt)
* [Draft C99 standard](http://www.open-std.org/jtc1/sc22/wg14/www/docs/n1256.pdf)
* [Draft C11 standard](http://www.open-std.org/JTC1/SC22/WG14/)

#### Beginner ####

* [Tutorial on pointers](http://home.netcom.com/~tjensen/ptr/pointers.htm)
* [Building C Projects](http://nethack4.org/blog/building-c.html)
* [C Programming Wikibook](https://en.wikibooks.org/wiki/C_Programming)
* [Introduction to 'fun' C](https://gist.github.com/eatonphil/21b3d6569f24ad164365)
* [Learning C with GDB](https://www.recurse.com/blog/5-learning-c-with-gdb)
* [POSIX Threads Programming tutorial](https://computing.llnl.gov/tutorials/pthreads/) (a little dated, but most of it is still valid and useful)
* [The GNU C Programming Tutorial](http://www.crasseux.com/books/ctut.pdf) (online PDF)
* [Templating in C](http://blog.pkh.me/p/20-templating-in-c.html)
* [Programming Community Curated Resources for learning C](https://hackr.io/tutorials/learn-c)

#### Intermediate ####

* [8 gdb tricks you should know](https://blogs.oracle.com/ksplice/8-gdb-tricks-you-should-know)
* [10 C99 tricks](https://blog.noctua-software.com/c-tricks.html)
* [Diving into concurrency: trying out mutexes and atomics](https://jvns.ca/blog/2014/12/14/fun-with-threads/)
* [Introduction to OpenMP](https://www.youtube.com/playlist?list=PLLX-Q6B8xqZ8n8bwjGdzBJ25X2utwnoEG) (video)
* [OpenMP tutorial](https://computing.llnl.gov/tutorials/openMP/) (for the OpenMP3 standard)
* [memcpy vs memmove](https://web.archive.org/web/20170620131430/https://www.tedunangst.com/flak/post/memcpy-vs-memmove)
* [MPI tutorial](https://computing.llnl.gov/tutorials/mpi/)
* [Some unknown features or tricks in C language](https://proprogramming.org/some-unknown-features-or-tricks-in-c-language/)
* [The lost art of C structure packing](http://www.catb.org/esr/structure-packing/)
* [What a C programmer should know about memory](http://marek.vavrusa.com/memory/)
* [What every C programmer should know about undefined behaviour](http://blog.llvm.org/2011/05/what-every-c-programmer-should-know.html)

#### Advanced ####

* [Advanced metaprogramming in C](http://250bpm.com/blog:56)
* [Quick tutorial on implementing and debugging malloc, free, calloc, and realloc](http://danluu.com/malloc-tutorial/)
* [Bit twiddling hacks](https://graphics.stanford.edu/~seander/bithacks.html)
* [I do not know C](https://kukuruku.co/post/i-do-not-know-c/)
* [Implementing smart pointers for the C programming language](https://snai.pe/c/c-smart-pointers/)
* [Inline functions in C](http://www.greenend.org.uk/rjk/tech/inline.html)
* [Metaprogramming custom control structures in C](https://www.chiark.greenend.org.uk/~sgtatham/mp/)
* [Solving the temporary storage problem of C macros](https://github.com/Fedjmike/Fedjmike.github.io/blob/master/_thought/macro-storage-for-inverse-comma.md)
* [Some dark corners of C](https://docs.google.com/presentation/d/1h49gY3TSiayLMXYmRMaAEMl05FaJ-Z6jDOWOz3EsqqQ/edit?pli=1#slide=id.gaf50702c_0153)
* [Writing efficient C and C code optimization](https://www.codeproject.com/articles/6154/writing-efficient-c-and-c-code-optimization)
* [What every programmer should know about memory](https://www.akkadia.org/drepper/cpumemory.pdf)

#### Self-study courses ####

* [C Programming Language Certified Associate preparation course](http://cppinstitute.com/study-resources)

### Physical ###

#### Reference ####

* [C: A Reference Manual 5E](http://careferencemanual.com/) - Full reference book for C99.
* [C Pocket Reference](http://shop.oreilly.com/product/9780596004361.do) - Concise reference book for C99.
* [The C Programming Language 2E](https://en.wikipedia.org/wiki/The_C_Programming_Language) - The original book on C, by its creators.

#### Beginner ####

* [C Primer Plus 6E](https://www.pearson.com/us/higher-education/program/Prata-C-Primer-Plus-6th-Edition/PGM4399.html) - Complete tutorial on programming in C11.
* [C Programming: A Modern Approach](http://knking.com/books/c2/index.html) - Excellent book to learn the basics of C.
* [Head First C](http://shop.oreilly.com/product/0636920015482.do) - 'Head-first' style book for learning C.

#### Intermediate ####

* [21st Century C](http://shop.oreilly.com/product/0636920033677.do) - Very good *second* programming book on C.
* [Understanding and Using C Pointers](http://shop.oreilly.com/product/0636920028000.do) - In-depth resource on pointers in C.
* [ZeroMQ](http://shop.oreilly.com/product/0636920026136.do) - Book for using ZeroMQ with C.

#### Advanced ####

* [Expert C Programming: Deep C Secrets](https://dl.acm.org/citation.cfm?id=179241) - Interesting, in-depth and *entertaining* look at the innards of C.

## Macros ##

* [P99](http://p99.gforge.inria.fr/) - Suite of macros to implement advanced features like default function arguments, scope-bound resources, etc. [[Q Public License](https://tldrlegal.com/license/q-public-license-1.0-(qpl-1.0)#summary)] (Requires C99)

## Memory Allocators ##

Implementations of memory allocators for various systems and platforms.

* [jemalloc](https://github.com/jemalloc/jemalloc) - General purpose malloc(3) implementation that emphasizes :star:2847
fragmentation avoidance and scalable concurrency support, commonly used in production systems [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)]
* [dlmalloc](http://g.oswego.edu/pub/misc/malloc.c) - Doug Lea's malloc(3) implementation, useful for academic and research purposes [Public Domain]
* [Hoard](https://github.com/emeryberger/Hoard) - A Fast, Scalable, and Memory-efficient Malloc for Linux, Windows, Mac, and Solaris [[GNU GPL2](http://www.gnu.org/licenses/gpl.html) only] :star:397
* [nedmalloc](https://github.com/ned14/nedmalloc) - An EXTREMELY FAST portable thread caching malloc(3) implementation written in C [[GNU GPL2](http://www.gnu.org/licenses/gpl.html) only] :star:267
* [rpmalloc](https://github.com/rxi/dyad) - Public domain. cross platform, lock-free memory allocator [Public Domain] :star:955


## Multimedia ##

* [FFMPEG](https://www.ffmpeg.org/) - Complete, cross-platform solution to record, convert and stream audio and video. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) or later] or [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) or later (some parts)]
* [GStreamer](https://gstreamer.freedesktop.org/) - Framework for audio and visual media. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only]
* [lodepng](http://lodev.org/lodepng/) - Simple PNG image decoder and encoder, requiring no other dependencies. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]
* [libsoup](https://wiki.gnome.org/action/show/Projects/libsoup?action=show&redirect=LibSoup) - GNOME HTTP client/server library. Uses GObject. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only]
* [libmpv](https://github.com/mpv-player/mpv) - Music-playing library. Compile with ``./waf configure --disable-cplayer --enable-libmpv-shared`` to not have the music player. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) or later] :star:7678
* [libsoundio](https://github.com/andrewrk/libsoundio) - Library for cross-platform, real-time audio input and output. Has a range of back-ends. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:651


## Networking and Internet ##

* [asnlc](http://lionet.info/asn1c/compiler.html) - Compiler of ASN.1 specifications into C source code. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)]
* [czmq](https://github.com/zeromq/czmq) - High-level binding for ZeroMQ. [[MPL2.0](https://www.gnu.org/licenses/license-list.html#MPL-2.0)] :star:665
* [GNU adns](https://www.gnu.org/software/adns/) - Advanced, easy-to-use, asynch-capable DNS client library and utilities. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [GNU SASL](https://www.gnu.org/software/gsasl/) - Implementation of the Simple Authentication and Security Layer and a few common SASL mechanism. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [GnuTLS](https://www.gnutls.org/) - Secure communication library, implementing SSL, TLS and DTLS. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) or later]
* [gumbo-parser](https://github.com/google/gumbo-parser) - HTML5 parsing library in C99. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:4253
* [http-parser](https://github.com/nodejs/http-parser) - HTTP request/response parser. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:3896
* [ldns](https://www.nlnetlabs.nl/projects/ldns/index.html) - Library to simplify DNS programming. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]
* [libcurl](https://curl.haxx.se/libcurl/) - Client-side URL transfer library, supporting a wide range of formats. [[curl license](https://curl.haxx.se/docs/copyright.html)]
* [LibEtPan](https://github.com/dinhviethoa/libetpan) - Mail library providing an efficient network for IMAP, SMTP, POP and NNTP. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] :star:456
* [libev](http://software.schmorp.de/pkg/libev.html) - Yet another event loop. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)]
* [libuv](https://github.com/libuv/libuv) - Cross-platform asynchronous I/O. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:8936
* [libevent](http://libevent.org/) - Event loop replacement for network servers. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]
* [libgss](https://www.gnu.org/software/gss/) - Generic Security Service. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [libhttpd](http://www.hughes.com.au/products/libhttpd/) - Library to add basic web server capabilities to an application or embedded device. [[GNU GPL2](http://www.gnu.org/licenses/gpl.html) only]
* [libidn](https://www.gnu.org/software/libidn/) - Implementation of the Stringprep, Punycode and IDNA specifications. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [libmicrohttpd](https://www.gnu.org/software/libmicrohttpd/) - Small C library that makes it easy to run an HTTP server as part of another application. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) or later]
* [libvldmail](https://github.com/dertuxmalwieder/libvldmail) - Your friendly e-mail address validation library. [[WTFPLv2](http://www.wtfpl.net/txt/copying/)] :star:11
* [lwan](https://github.com/lpereira/lwan) - Experimental, scalable, high-performance HTTP server. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only] :star:4158
* [mongoose](https://github.com/cesanta/mongoose) - Embedded web server for C. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only] :star:4461
* [nanomsg](https://github.com/nanomsg/nanomsg) - C-based implementation of ZeroMQ. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:4138
* [OpenSSL](https://www.openssl.org/) - Implementation of the SSL and TLS protocols, and also includes a cryptography library. [[Dual Licensed under the OpenSSL License and the SSLeay License](https://www.openssl.org/source/license.html)]
* [oSip](https://www.gnu.org/software/osip/) - SIP implementation in C without additional dependencies. [[GNU LGPLv2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) or later]
* [pig](https://github.com/rafael-santiago/pig) - Linux packet crafting tool. [[GPL2](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)] :star:312
* [s2n](https://github.com/awslabs/s2n) - C99 implementation of the TLS/SSL protocols, designed to be simple, fast and with security as a priority. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:3105
* [socket99](https://github.com/silentbicycle/socket99) - C99 wrapper for the BSD sockets API. [[ISC](https://directory.fsf.org/wiki/License:ISC)] :star:92
* [Tox](https://github.com/irungentoo/toxcore) - Communication platform, designed to be a Skype-killer. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) only] :star:8367
* [twitc](https://github.com/sinemetu1/twitc) - Mini C library for interacting with the Twitter OAuth API. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:21
* [librg](https://github.com/librg/librg) - Library for building simple and elegant cross-platform mmo client-server solutions. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:72
* [dyad](https://github.com/rxi/dyad) - Asynchronous networking library [[MIT License](https://raw.githubusercontent.com/atom/atom/master/LICENSE.md)] :star:955
* [h2o](https://github.com/h2o/h2o) - Optimized HTTP/1, HTTP/2 high performance server/library [[MIT License](https://raw.githubusercontent.com/atom/atom/master/LICENSE.md)] :star:7329

### Web Frameworks ###

* [balde](https://github.com/balde/balde) - Microframework for C based on GLib. [[GNU LGPLv2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only] :star:677
* [onion](https://github.com/davidmoreno/onion) - C library to create simple HTTP servers and Web Applications. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:1358
* [kore](https://github.com/jorisvink/kore) - Easy to use, scalable and secure web application framework for writing web APIs in C. :star:2714
* [klone](https://github.com/koanlogic/klone) - KLone is a fully-featured, multiplatform, web application development framework. :star:115
* [duda](https://github.com/monkey/duda) - Duda I/O is an event-driven and high performant web services framework written in C. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:110

## Numerical ##

* [apophenia](https://github.com/b-k/apophenia) - Library for statistical and scientific computing. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only] :star:126
* [ATLAS](http://math-atlas.sourceforge.net/) - Automatically Tuned Linear Algebra Software. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]
* [BLAS](http://www.netlib.org/blas/) - Basic Linear Algebra Subprograms; a set of routines that provide vector and matrix operations. [[BLAS license](http://www.netlib.org/blas/#_licensing)]
* [Cuba](http://www.feynarts.de/cuba/) - Library for multidimensional numerical integration. [[GNU LGPLv3](http://www.gnu.org/licenses/lgpl.html) only]
* [FFTW](http://www.fftw.org/) - The Fastest Fourier Transform in the West; a highly-optimized fast Fourier transform routine. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) or later]
* [FLINT](http://flintlib.org/) - Fast Library for Number Theory; a library supporting arithmetic with numbers, polynomials, power series and matrices, among others. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) or later]
* [GLPK](https://www.gnu.org/software/glpk/) - GNU Linear Programming Kit; a package designed for solving large-scale linear programming, mixed integer programming and other related problems. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [GMP](https://gmplib.org/) - GNU Multple Precision Arithmetic Library; a library for arbitrary-precision arithmetic. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only] and [[GNU LGPLv3](http://www.gnu.org/licenses/lgpl.html) only]
* [GNU MPC](http://www.multiprecision.org/mpc/) - Library for complex number arithmetic. [[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html) or later]
* [GNU MPFR](http://mpfr.loria.fr/index.html) - Library for arbitrary-precision floating-point arithmetic. [[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html) or later (most recent versions)] or [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) or later (until version 2.4.x)]
* [GNU MPRIA](https://www.gnu.org/software/mpria/) - Portable mathematics library for multi-precision rational interval arithmetic. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [GSL](http://www.gnu.org/software/gsl/) - The GNU Scientific Library; a sophisticated numerical library. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) only]
* [KISS FFT](https://sourceforge.net/projects/kissfft/) - Very simple fast Fourier transform library. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]
* [LAPACKE](http://www.netlib.org/lapack/lapacke.html) - C interface to [LAPACK](http://www.netlib.org/lapack/). [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]
* [PARI/GP](http://pari.math.u-bordeaux.fr/) - Computer algebra system for number theory; includes a compiler to C. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) or later]
* [PETSc](http://www.mcs.anl.gov/petsc/) - Suite of data structures and routines for scalable parallel solution of scientific applications modelled by partial differential equations. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)]
* [SLEPc](http://slepc.upv.es/) - Software library for the solution of large, sparse eigenvalue problems on parallel computers. [[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html) only]
* [Yeppp!](https://bitbucket.org/MDukhan/yeppp) - Very fast, SIMD-optimized mathematical library. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]

## Parallel Programming ##

* [cchan](http://repo.hu/projects/cchan/) - Small library for channel constructs for inter-thread communication. [Public domain]
* [ck](https://github.com/concurrencykit/ck) - Concurrency primitives, safe memory reclamation mechanisms and non-blocking data structures. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)] :star:1272
* [mill](http://libmill.org/) - Go-style concurrency in C. [[X11](https://directory.fsf.org/wiki/License:X11)]
* [libdill](https://github.com/sustrik/libdill) - Structured concurrency in C. [[X11](https://directory.fsf.org/wiki/License:X11)] :star:787
* [MPICH](http://www.mpich.org/) - Another implementation of MPI. [[MPICH licence](http://git.mpich.org/mpich.git/blob_plain/6aab201f58d71fc97f2c044d250389ba86ac1e3c:/COPYRIGHT)]
* [OpenMP](http://www.openmp.org/) - Set of C pragmas designed to allow for easy parallelization of code. [Standard (licensing not applicable)]
* [OpenMPI](https://github.com/open-mpi/ompi) - Message passing interface implementation. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] :star:506
* [PETSc](http://www.mcs.anl.gov/petsc/) - Suite of data structures and routines for scalable parallel solution of scientific applications modelled by partial differential equations. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)]
* [pth](https://www.gnu.org/software/pth/) - Portable implementation for non-preemptive priority-based scheduling for multiple threads of execution. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [pthreads](https://en.wikipedia.org/wiki/POSIX_Threads) - The POSIX thread library. [Standard (no license applicable)]
* [SLEPc](http://slepc.upv.es/) - Software library for the solution of large, sparse eigenvalue problems on parallel computers. [[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html) only]
* [TinyCThread](https://tinycthread.github.io/) - Portable, small implementation of the C11 threads API. [[zlib](https://directory.fsf.org/wiki/License:Zlib)]

## Parsers ##

* [hammer](https://github.com/abiggerhammer/hammer) - Parser combinators for binary formats. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only] :star:186
* [iniparser](https://github.com/ndevilla/iniparser) - Parser for .ini files. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:368
* [libYAML](http://www.pyyaml.org/wiki/LibYAML) - YAML 1.1 parser and emitter. [[Expat](https://directory.fsf.org/wiki/License:Expat)]
* [mpc](https://github.com/orangeduck/mpc) - Parser combinator library. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)] :star:1380
* [libucl](https://github.com/vstakhov/libucl) - Universal configuration library parser. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)] :star:930


## Regex ##

> "Some people, when confronted with a problem, think 'I know, I'll use regular expressions'. Now they have two problems." - Jamie Zawinski.

* [PCRE](http://www.pcre.org/) - Implementation of regexes identical to that of Perl 5. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]
* [SLRE](https://github.com/cesanta/slre) - Super Light Regular Expression library; a very small implementation of a subset of Perl regex syntax. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only] :star:388
* [TRE](https://github.com/laurikari/tre/) - POSIX-compliant, feature-full regex library. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)]

## Serialization ##

* [binn](https://github.com/liteserver/binn) - Binary serialization format meant to be compact, fast and easy-to-use. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:166
* [c-capnproto](https://github.com/jmckaskill/c-capnproto) - Implementation of the Cap'n Proto serialization protocol. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:63
* [cmp](https://github.com/camgunz/cmp) - Implementation of the [MessagePack](https://msgpack.org/) serialization protocol. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:160
* [libavro](http://avro.apache.org/docs/current/api/c/index.html#_introduction_to_avro_c) - C implementation of the Avro data serialization system. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)]
* [mpack](https://github.com/ludocode/mpack) - Another implementation of the [MessagePack](https://msgpack.org/) serialization protocol. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:121
* [netstring-c](https://github.com/liteserver/netstring-c) - Netstring encoder and decoder. [Public Domain] :star:3
* [protobuf-c](https://github.com/protobuf-c/protobuf-c) - Implementation of Google Protocol Buffer in C. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)] :star:876
* [xdr](https://en.wikipedia.org/wiki/External_Data_Representation) - External Data Representation; a standard for data serialization. [Standard (no license applicable)]

Check also: [JSON](#json), [XML](#xml)

## Source Code Collections ##

This contains collections of small source code. If you want something big and integrated, check the Frameworks section.

* [CCAN](http://ccodearchive.net/) - Modelled after Perl's CPAN, this is a big collection of C code that does stuff. The full list is [here](http://ccodearchive.net/list.html). [Various free licenses]
* [clib](https://github.com/clibs/clib) - Something of a package manager for C. Comes with a [bunch of libraries of its own](https://github.com/clibs/clib/wiki/Packages). [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:2838
* [gnulib](https://www.gnu.org/software/gnulib/) - Collection of common GNU code. [Various free licenses]
* [libdjb](http://www.fefe.de/djb/) - Collection of libraries doing various things. [(Apparently) Public domain]

## Standard Libraries ##

This contains standard C libraries.

* [Bionic](https://github.com/aosp-mirror/platform_bionic) - Google's C standard library, developed for Android. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] :star:366
* [dietlibc](http://www.fefe.de/dietlibc/) - C standard library designed for the smallest possible binaries. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only]
* [glibc](http://www.gnu.org/software/libc/) - The GNU C Library; an implementation of the C standard library. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only]
* [musl](http://www.musl-libc.org/) - Standard C library, compatible with POSIX 2008 and C11. Designed for static linking. [[Expat](https://directory.fsf.org/wiki/License:Expat)]

## String Manipulation ##

* [bstrlib](http://bstring.sourceforge.net/) - The Better String Library. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] and [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only]
* [ICU](http://site.icu-project.org/) - International Components for Unicode; a library for Unicode support. [[ICU license](http://source.icu-project.org/repos/icu/icu/tags/latest/LICENSE)]
* [libunistring](https://www.gnu.org/software/libunistring/) - Library for manipulating Unicode strings in C. [[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html) only]
* [libgiconv](https://www.gnu.org/software/libiconv/) - Text conversion library. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only (library)] or [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) only (*iconv* program)]
* [SDS](https://github.com/antirez/sds) - Simple Dynamic Strings; a library for handling C strings in a simpler way, but one that is compatible with normal C string functions. Available via [clib](https://github.com/clibs/clib). [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)] :star:2244
* [shoco](https://github.com/Ed-von-Schleck/shoco) - Compressor for small text strings. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:196
* [smaz](https://github.com/antirez/smaz) - Efficient string compression library. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] :star:645
* [utf8.h](https://github.com/sheredom/utf8.h) - Single header utf8 string functions. [[Unlicense](http://unlicense.org/)] :star:321

## Testing ##

* [CHEAT](https://github.com/Tuplanolla/cheat) - Very simple unit testing framework. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)] :star:131
* [Check](http://check.sourceforge.net/) - Unit testing framework for C. [[GNU LGPL2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only]
* [CMock](https://github.com/ThrowTheSwitch/CMock) - Mock/stub generator for C. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:168
* [cmocka](https://cmocka.org/) - Unit testing framework with support for mock objects. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)]
* [Criterion](https://github.com/Snaipe/Criterion) - KISS, non-intrusive C test framework. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:606
* [CUnit](http://cunit.sourceforge.net/) - Another unit testing framework for C. [[GNU LGPL2.0](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only]
* [Cutest](https://github.com/rafael-santiago/cutest) - Library for unit testing with memory leak detection (Linux, freeBSD and Windows). [[GPL2](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)] :star:15
* [minunit](https://github.com/siu/minunit) - Minimal unit testing framework for C. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:189
* [munit](https://nemequ.github.io/munit/) - Small but full-featured unit testing framework for C with no dependencies. [[MIT License](https://raw.githubusercontent.com/atom/atom/master/LICENSE.md)]
* [Unity](https://github.com/ThrowTheSwitch/Unity) - Simple unit testing framework for C. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:769

## Text Editor Extensions ##

While practically any decent programmer's text editor supports C, there are some extensions that make it more pleasant. This is categorized by editor.

### Atom ###
* [linter-clang](https://github.com/AtomLinter/linter-clang) - Lint C code in Atom, using Clang. [[MIT License](https://raw.githubusercontent.com/atom/atom/master/LICENSE.md)] :star:52
* [linter-gcc](https://github.com/hebaishi/linter-gcc) - Lint C code in Atom, using GCC. [[MIT License](https://raw.githubusercontent.com/atom/atom/master/LICENSE.md)] :star:60

### Emacs ###

* [CEDET](http://cedet.sourceforge.net/) - Collection of Emacs Development Environment Tools; designed to provide IDE-like features to Emacs. Built-in. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [Flycheck](https://github.com/flycheck/flycheck) - Modern syntax checking. For C, it can use either GCC or Clang as a back-end. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later] :star:1527
* [Yasnippet](https://github.com/joaotavora/yasnippet) - Template system, with C templates for common code snippets. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later] :star:1659

### Vim ###

* [Syntastic](https://github.com/vim-syntastic/syntastic) - Syntax checking and linting. [[Do What The Fuck You Want To license](https://github.com/vim-syntastic/syntastic/blob/master/LICENCE)] :star:9009
* [YouCompleteMe](http://valloric.github.io/YouCompleteMe/) - Code completion engine for Vim. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) only]

## Tools ##

This is a list of useful programs to help you write and debug C code which are *not* editors, libraries or compilers.

* [Artistic Style](http://astyle.sourceforge.net/) - Fast and small automatic source code formatter that supports C. [[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html) only]
* [address-sanitizer](https://github.com/google/sanitizers) - Fast memory error detector. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:2292
* [biicode](https://biicode.github.io/biicode/) - Modern dependency manager for C. [[Expat](https://directory.fsf.org/wiki/License:Expat)]
* [c](https://github.com/ryanmjacobs/c) - Compile and execute C "scripts" in one go on the command line. Also has shebang support. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:1571
* [c99sh](https://github.com/RhysU/c99sh) - Run C files using hash-bang. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)] :star:51
* [CBMC](http://www.cprover.org/cbmc/) - C Bounded Model Checker; a tool for verification of array bounds, pointer safety and user-specified assertions. [[Original BSD](https://directory.fsf.org/wiki/License:BSD_4Clause)]
* [cdecl](https://cdecl.org/) - Online service to translate C declarations into English and vice versa. [Public domain]
* [cinclude2dot](https://www.flourish.org/cinclude2dot/) - Graphs include dependencies in a C project using Graphviz. [Any GNU GPL version (due to underspecification in the file)]
* [Complexity](https://www.gnu.org/software/complexity/) - Tool for measuring the complexity of C source code. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [CScout](https://www.spinellis.gr/cscout/) - Source code analyzer and refactoring browser for collections of C programs. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) only]
* [DDD](https://www.gnu.org/software/ddd/ddd.html) - Graphical front-end for a range of command-line debuggers. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [GDB](http://www.gnu.org/software/gdb/) - The GNU Project debugger; a debugger for C. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [Glade](https://glade.gnome.org/) - RAD tool to enable quick development of GTK+ GUIs. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only]
* [GMSL](http://gmsl.sourceforge.net/) - GNU Make Standard Library; a collection of additional functionality for GNU Make. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]
* [GNU Global](https://www.gnu.org/software/global/) - Source code tagging tool which works with C. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) only]
* [gprof](http://www.gnu.org/software/binutils/) - Performance analysis tool. Part of GNU binutils. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [Highlight](http://www.andre-simon.de/index.php) - Converts source code to formatted text with nice highlighting. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) only]
* [include-what-you-use](https://github.com/include-what-you-use/include-what-you-use) - Helps find unecessary inclusions and make suggestions for fixing them. Based on LLVM/Clang (and only works with it). [[NCSA](https://directory.fsf.org/wiki/License:IllinoisNCSA)] :star:986
* [indent](https://www.gnu.org/software/indent/) - Formats C source code automatically to make it easier to read. Also converts from one style of source to another. [[GNU GPLv3](http://www.gnu.org/licenses/gpl.html) or later]
* [rr](http://rr-project.org/) - Debugger that records non-deterministic executions to allow for deterministic debugging. [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)]
* [tup](http://gittup.org/tup/index.html) - Very fast, file-based, cross-platform build system. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only]
* [unifdef](http://dotat.at/prog/unifdef/) - Removes #ifdef and #if directives with their delimited text without touching any other part of the file. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] and [[FreeBSD](https://directory.fsf.org/wiki?title=License:FreeBSD)]
* [Valgrind](http://www.valgrind.org/) - Range of dynamic analysis tools, including a leak checker. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only]

## Utilities ##

This is a 'catch-all' category for anything that doesn't fit well anywhere else.

* [ApeTagLibs](https://github.com/jeremyevans/ape_tag_libs/tree/master/c) - C library for working with APEv2 tags. [[Expat](https://directory.fsf.org/wiki/License:Expat)]
* [bfd](http://sourceware.org/binutils/docs/bfd/) - Library for manipulating binary object files. Part of GNU binutils. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [cf4ocl](https://fakenmc.github.io/cf4ocl/) - The C Framework for OpenCL; a cross-platform object-oriented framework for developing and benchmarking  [OpenCL](https://www.khronos.org/opencl/) projects. [[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html) (library)] or [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) (project code)]
* [CommonMark](https://github.com/commonmark/CommonMark) - C implementation of the CommonMark spec. [[Various free licenses](https://github.com/commonmark/CommonMark/blob/master/LICENSE)] :star:3645
* [CException](https://github.com/ThrowTheSwitch/CException) - C implementation of exceptions. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:67
* [docopt.c](https://github.com/docopt/docopt.c) - C implementation of a command-line option parser. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:240
* [dyncall](http://www.dyncall.org/) - Another foreign function interface library. [[Expat](https://directory.fsf.org/wiki/License:Expat)]
* [FANN](http://leenissen.dk/fann/wp/) - Fast Artifical Neural Network library; an implementation of neural networks. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only]
* [Firm](https://pp.ipd.kit.edu/firm/) - C library that provides a graph-based intermediate representation, optimizations and assembly code generation suitable for use in compilers. Comes with an example C front-end under the same license. [[GNU LGPLv2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) only]
* [gjrand](https://sourceforge.net/projects/gjrand/) - Library of random-number generation routines. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)] or [[GNU GPLv3](http://www.gnu.org/licenses/gpl.html)]
* [GNU FreeIPMI](https://www.gnu.org/software/freeipmi/index.html) - In-band and out-of-band IPMI implementation. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) only]
* [GNU gperf](https://www.gnu.org/software/gperf/) - Perfect hash function generator, given a list of strings. Outputs C code. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [GNU Libffcall](https://www.gnu.org/software/libffcall/) - Collection of libraries for building foreign function interfaces. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [gperftools](https://github.com/gperftools/gperftools) - Collection of utilities for measuring and improving performance. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] :star:2548
* [huffandpuff](https://github.com/adamierymenko/huffandpuff) - Minimal Huffman encoder and decoder. [Public domain] :star:52
* [kdtree](https://github.com/jtsiomb/kdtree) - Simple library for working with KD-trees. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)] :star:151
* [Kitsune](http://kitsune-dsu.com/) - Efficient, general-purpose framework for dynamic software updating. [[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html) or later]
* [libavl](http://adtinfo.org/libavl.html/index.html) - Library containing a range of self-balancing binary trees. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [libbson](https://github.com/mongodb/libbson) - BSON utility library. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:274
* [libCello](http://libcello.org/) - Library introducing higher-level programming to C. [[3-clause BSD](https://directory.fsf.org/wiki/License:BSD_3Clause)]
* [libffi](https://github.com/libffi/libffi) - Portable foreign-function interface library. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:981
* [libgit2](https://libgit2.github.com/) - Pure C implementation of Git. [[GNU GPL2 only, with a linking exception](https://github.com/libgit2/libgit2/blob/master/COPYING)]
* [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice) - Cross-platform protocol library to communicate with iThings. [[GNU LGPLv2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) or later (library)] or [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) or later (tools)] :star:1901
* [libnfc](https://github.com/nfc-tools/libnfc) - Platform-independent Near-Field Communication library. [[GNU LGPL3](http://www.gnu.org/licenses/lgpl.html) only] :star:425
* [libPhenom](http://facebook.github.io/libphenom/index.html) - Eventing framework for building high-scalability and high-performance systems. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)]
* [ncurses](https://www.gnu.org/software/ncurses/) - Coloured terminal UI library. [[GNU GPL3](http://www.gnu.org/licenses/gpl.html) or later]
* [nope.c](https://github.com/riolet/WAFer) - C-language-based, ultra-light software platform for scalable server-side and networking applications (think node.js for C programmers). [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only] :star:656
* [pbc](https://github.com/cloudwu/pbc) - Protocol buffers library. [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:1062
* [rabbitmq-c](https://github.com/alanxz/rabbitmq-c) - Client library for [RabbitMQ](http://www.rabbitmq.com/). [[Expat](https://directory.fsf.org/wiki/License:Expat)] :star:785
* [Ragel](http://www.colm.net/open-source/ragel/) - DSL for state machines that compiles to C. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only]
* [uthash](http://troydhanson.github.io/uthash/) - Hash table implementation, allowing existing structures to be stored in a hash table easily. [[1-clause BSD](http://troydhanson.github.io/uthash/license.html)]
* [cpu_features](https://github.com/google/cpu_features) - A cross platform C99 library to get cpu features at runtime. [[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:1176
* [pblog](https://github.com/google/pblog) - Small, low overhead, structured logging library intended for logging formware events.[[Apache2.0](https://directory.fsf.org/wiki/License:Apache2.0)] :star:10
* [libelf](https://github.com/WolfgangSt/libelf) - ELF object file access library in C. [[GNU GPL2.1](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) only] :star:6
* [mcpp](http://mcpp.sourceforge.net/) - Portable C preprocessor. [[2-clause BSD](https://opensource.org/licenses/BSD-2-Clause)]
* [libusb](http://libusb.info/) - Generic access to USB devices. [[LGPL2.1](https://github.com/libusb/libusb/blob/master/COPYING)]
* [alsa-lib](http://www.alsa-project.org/main/index.php/Main_Page) - Userspace library to interact with ALSA. [[LGPL2.1](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html)]
* [Capstone](https://github.com/aquynh/capstone) - Dissasembly/disassembler framework. [[BSD 3-clause](https://github.com/aquynh/capstone/blob/master/LICENSE.TXT)] :star:2661

## XML ##

> "XML is crap. Really. There are no excuses. XML is nasty to parse for humans, and it's a disaster to parse even for computers. There's just no reason for that horrible crap to exist." - Linus Torvalds

* [Expat](http://www.libexpat.org/) - Stream-oriented XML parser. [[Expat](https://directory.fsf.org/wiki/License:Expat)]
* [libxml2](http://xmlsoft.org/) - Standards-compliant, portable XML parser. [[Expat](https://directory.fsf.org/wiki/License:Expat)]
* [mini-xml](https://github.com/michaelrsweet/mxml) - Small XML reading and writing library. No dependencies aside from C standard library. [[GNU LGPL2.1 with static linking exception](https://github.com/michaelrsweet/mxml/blob/master/COPYING)] :star:78


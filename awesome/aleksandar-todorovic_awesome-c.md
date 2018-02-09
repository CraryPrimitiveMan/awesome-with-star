# Information comes from [aleksandar-todorovic/awesome-c](https://github.com/aleksandar-todorovic/awesome-c)
# awesome-c [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)][387]

A curated list of C good stuff. This list contains *only* [free software][13] for code, and sellers who aren't evil for physical resources.

**LOOKING FOR MAINTAINERS:** This list is currently pretty much inactive. I'm looking for maintainers that can make it great again. See [#26](https://github.com/aleksandar-todorovic/awesome-c/issues/26) for more info, but the process is simple: add or fix a couple of things in this list and you'll become a contributor to a 850+ stars list.

This list was previously maintained by [@kozross](https://github.com/kozross). He decided to switch the list to a [new platform](https://notabug.org/koz.ross/awesome-c), so I've decided to fork it so we could keep it on GitHub.

Contents
========

## Contents ##

- [Build Systems](#build-systems)
- [Compilers](#compilers)
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
- [Multimedia](#multimedia)
- [Networking and Internet](#networking-and-internet)
  - [Web Frameworks](#web-frameworks)
- [Numerical](#numerical)
- [Parallel Programming](#parallel-programming)
- [Regex](#regex)
- [Serialization](#serialization)
- [Source Code Collections](#source-code-collections)
- [Standard Libraries](#standard-libraries)
- [String Manipulation](#string-manipulation)
- [Testing](#testing)
- [Text Editor Extensions](#text-editor-extensions)
  - [Emacs](#emacs)
  - [Vim](#vim)
- [Tools](#tools)
- [Utilities](#utilities)
- [XML](#xml)

## Build Systems ##

These are tools to automate the building and testing of projects in C.

* [aimake][97] - Build tool designed to avoid complex configurations. [[GNU GPL3][LIC1] or later]
* [Autoconf][305] - Extensible package of M4 macros that produce shell scripts to automatically configure software source code packages. Part of the Autotools. [[GNU GPL3][LIC1] or later]
* [Automake][306] - Tool for automatically generating ``Makefile.in`` files compliant with the GNU Coding Standards. Requires the use of Autoconf. Part of the Autotools. [[GNU GPL3][LIC1] or later]
* [CMake][410] - Tools for cross-platform building, testing, and packaging. [[3-clause BSD][LIC2]]
* [Jam][334] - Build system, designed to be easier than make. Understands C build rules implicitly. [[Jam License][LIC3]]
* [Libtool][172] - Generic library support script. Part of the Autotools. [[GNU GPL3][LIC1] or later]
* [Meson][368] - Extremely fast, user-friendly build system. Based on Ninja. [[Apache2.0][LIC4]]
* [Premake][403] - Build script generator for toolsets like Visual Studio, Xcode, or GNU Make. [[3-clause BSD][LIC5]]
* [SCons][420] - An easier, more reliable and faster way to build software. [MIT License][LIC18].

## Compilers ##

* [Clang][38] - C compiler for LLVM. Supports C11. [[NCSA][LIC6]]
* [CompCert][269] - Fully-verified C compiler. Supports almost all of C89. [[GNU GPL2.1][LIC7] or later]
* [GCC][40] - Provides a C compiler as part of its compiler set. Supports C11 and OpenMP. [[GNU GPL3][LIC1] or later]
* [PCC][74] - Venerable C compiler. Supports C99. [[Various free licenses][LIC8]]
* [TCC][58] - Tiny C Compiler; a small, fast C compiler. Supports C99 (except complex types). [[GNU LGPL2.1][LIC9] only]

## Compression ##

* [libzip][408] - A C library for reading, creating, and modifying zip archives. [[3-clause BSD][LIC5]]
* [lzo][338] - Very fast data compression library. [[GNU GPL2.1][LIC7]]
* [zlib][230] - Massively-spiffy yet delicately-unobtrusive compression library. [[3-clause BSD][LIC5]]

## Crypto ##

* [GnuTLS][112] - Secure 

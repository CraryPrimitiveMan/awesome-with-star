# Information comes from [onqtam/awesome-cmake](https://github.com/onqtam/awesome-cmake)
# Awesome CMake [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://rawgit.com/onqtam/awesome-cmake/master/cmake-logo.svg" align="right" width="100">](https://cmake.org/)

> A curated list of awesome [CMake](https://cmake.org/) scripts, modules, examples and others

Your contributions are highly welcome (first see [CONTRIBUTING.md](CONTRIBUTING.md)).

## Contents

- [Community](#community)
- [Resources](#resources)
- [Package Management / Build Systems](#package-management--build-systems)
- [Modules](#modules)
- [Utility Scripts](#utility-scripts)
- [Toolchains](#toolchains)
- [Examples / Templates](#examples--templates)
- [Other](#other)

## Community

* [```#cmake``` on Freenode](http://webchat.freenode.net/?channels=cmake)
* [```/r/cmake``` on Reddit](https://www.reddit.com/r/cmake/)
* [```/r/cpp``` on Reddit](https://www.reddit.com/r/cpp/)
* [Mailing Lists](https://cmake.org/mailing-lists/)
* [Stack Overflow](http://stackoverflow.com/questions/tagged/cmake)

## Resources

* [Latest Documentation](https://cmake.org/cmake/help/latest/)
* [FAQ](https://cmake.org/Wiki/CMake_FAQ)
* [Wiki](https://cmake.org/Wiki/CMake)
* [Webinars](https://cmake.org/webinars/)
* [CGold](https://github.com/ruslo/CGold) - The Hitchhiker’s [Guide](https://cgold.readthedocs.io) to the CMake. [```[BSD2]```][BSD-2-Clause] :star:126
* [Modern CMake](https://github.com/toeb/moderncmake) - Modern CMake **PDF** and samples by the creator of [cmakepp](https://github.com/toeb/cmakepp). [```[MIT]```][MIT] :star:107
* [Article - Easily supporting CMake install and find_package()](http://foonathan.net/blog/2016/03/03/cmake-install.html).
* [Article - Easy dependency management for C++ with CMake and Git](http://foonathan.net/blog/2016/07/07/cmake-dependency-handling.html).
* [Article - Opt-in header-only libraries with CMake](https://steveire.wordpress.com/2016/08/09/opt-in-header-only-libraries-with-cmake/).
* [Article - Ultimate Guide to Modern CMake](https://rix0r.nl/blog/2015/08/13/cmake-guide/).
* [Article - A list of common CMake antipatterns (from 2013 but still relevant)](http://voices.canonical.com/jussi.pakkanen/2013/03/26/a-list-of-common-cmake-antipatterns/).
* [Article - How to Build a CMake-Based Project](http://preshing.com/20170511/how-to-build-a-cmake-based-project/).
* [Article - Learn CMake's Scripting Language in 15 Minutes](http://preshing.com/20170522/learn-cmakes-scripting-language-in-15-minutes/).
* [Article - The architecture of CMake](http://aosabook.org/en/cmake.html).
* [Lecture - Effective CMake - by Daniel Pfeifer, C++Now 2017](https://www.youtube.com/watch?v=bsXLMQ6WgIk).
* [Article - Building Cross-Platform CUDA Applications with CMake](https://devblogs.nvidia.com/parallelforall/building-cuda-applications-cmake/).
* [Tutorial - A step-by-step guide for understanding CMake](https://github.com/Wigner-GPU-Lab/Teaching/tree/master/CMake).
* [Article + Lecture - Embracing Modern CMake - by Stephen Kelly](https://steveire.wordpress.com/2017/11/05/embracing-modern-cmake/).
* [Lecture - CppCon 2017: Mathieu Ropert “Modern CMake for Modular Design”](https://www.youtube.com/watch?v=eC9-iRN2b04).
* [Article - Modern C++ CI (although it uses non-modern CMake like ```include_directories()```)](https://juan-medina.com/2017/07/01/moderncppci/).
* [Article - It's Time To Do CMake Right](https://pabloariasal.github.io/2018/02/19/its-time-to-do-cmake-right/) (one of the best articles about CMake).
* Articles - A series on CMake - by Martin Hořeňovský
    * [Basic CMake usage](https://codingnest.com/basic-cmake/)
    * [Basic CMake, part 2: libraries](https://codingnest.com/basic-cmake-part-2/)
* [Lecture - Introduction to CMake - by Florent Castelli, C++ Sweden 2018](https://www.youtube.com/watch?v=jt3meXdP-QI).
* [Article - Some nice and accurate CMake tips](http://bastian.rieck.me/blog/posts/2018/cmake_tips/)
* [Article - Modern CMake for Library Developers](http://unclejimbo.github.io/2018/06/08/Modern-CMake-for-Library-Developers/)
* [Article - Effective Modern CMake: a great summary of most good practices - by Manuel Binna](https://gist.github.com/mbinna/c61dbb39bca0e4fb7d1f73b0d66a4fd1)

## Package Management / Build Systems

* [hunter](https://github.com/ruslo/hunter) - Cross-platform package manager for C++ (based on CMake ExternalProject). [```[BSD2]```][BSD-2-Clause] :star:1292
* [cget](https://github.com/pfultz2/cget) - CMake package retrieval. This can be used to download and install CMake packages. [```[BOOST]```][BOOST] :star:237
* [cppan](https://cppan.org/) - C++ Archive Network - C++ Package Manager based on CMake, implemented in C++14. [```[APACHE2]```][APACHE2]
* [cpm](https://github.com/iauns/cpm) - C++ Package Manager based on CMake and Git. [```[MIT]```][MIT] :star:638
* [conan](https://github.com/conan-io/conan) - Conan C++ Package Manager, implemented in Python and has a CMake integration backend. [```[MIT]```][MIT] :star:1959
* [fips](https://github.com/floooh/fips) - High-level build system/dependency management for distributed, multi-platform C/C++ projects. [```[MIT]```][MIT] :star:205
* [Ninja](https://github.com/ninja-build/ninja) - Build system that differs from others in two major respects: it is designed to have its input files generated by a higher-level build system (like CMake), and it is designed to run builds as fast as possible. [```[APACHE2]```][APACHE2] :star:3523
* [vcpkg](https://github.com/Microsoft/vcpkg) - A tool to acquire and build C++ open source libraries. Uses CMake internally as a build script language. [```[MIT]```][MIT] :star:3401

## Modules

* [cmake-modules](https://github.com/rpavlik/cmake-modules) - [Ryan Pavlik](https://github.com/rpavlik)'s collection of CMake modules. There are a number of find modules, especially for virtual reality and physical simulation, some utility modules, and some patches or workarounds for CMake itself. [```[BOOST]```][BOOST] :star:484
* [cmake-modules](https://github.com/bilke/cmake-modules) - This is a collection of additional CMake modules. Most of them are from Ryan Pavlik. [```[BOOST]```][BOOST] :star:158
* [CMake](https://github.com/Eyescale/CMake) - [Eyescale](https://github.com/Eyescale)'s common CMake modules. [```[BSD3]```][BSD-3-Clause] :star:83
* [sdl2-cmake-scripts](https://github.com/tcbrindle/sdl2-cmake-scripts) - CMake scripts for finding the SDL2, SDL2_image and SDL2_ttf libraries and headers. [```[BSD2]```][BSD-2-Clause] :star:133
* [vfxcmake](https://github.com/nerdvegas/vfxcmake) - CMake Find modules for common vfx software, and general CMake utility code. [```[LGPL]```][LGPL] :star:75
* [cmake-modules](https://github.com/jedbrown/cmake-modules) - CMake modules for some scientific libraries. [```[BSD2]```][BSD-2-Clause] :star:57
* [cgcmake](https://github.com/chadmv/cgcmake) - CMake modules for common applications related to computer graphics. [```[MIT]```][MIT] :star:48
* [FindMathematica](https://github.com/sakra/FindMathematica) - CMake module for Mathematica. [```[MIT]```][MIT] :star:27
* [extra-cmake-modules](https://github.com/KDE/extra-cmake-modules) - [KDE](https://github.com/KDE)'s extra modules and scripts for CMake. [```[BSD3]```][BSD-3-Clause] :star:28
* [FindICU.cmake](https://github.com/julp/FindICU.cmake) - CMake module to find International Components for Unicode (ICU) Library. [```[BSD2]```][BSD-2-Clause] :star:23
* [FindTBB](https://github.com/justusc/FindTBB) - CMake find module for Intel Threading Building Blocks. [```[MIT]```][MIT] :star:56
* [cmake-modules](https://github.com/hanjianwei/cmake-modules) - [hanjianwei](https://github.com/hanjianwei)'s CMake module collection. [```[MIT]```][MIT] :star:23
* [YCM](https://github.com/robotology/ycm) - Extra CMake Modules for [Yet Another Robot Platform](https://github.com/robotology/yarp) and friends. [```[BSD3]```][BSD-3-Clause] :star:16

## Utility Scripts

These provide a wide range of functionality - from dealing with compiler flags to using tools. Some also contain modules.

* [cotire](https://github.com/sakra/cotire) - Cotire (compile time reducer) is a CMake module that speeds up the build process of CMake based build systems by fully automating techniques as precompiled headers and unity builds for C and C++. [```[MIT]```][MIT] :star:786
* [ucm](https://github.com/onqtam/ucm) - For managing compiler/linker flags, collecting sources, precompiled headers, unity builds and others. [```[MIT]```][MIT] :star:102
* [cmakepp](https://github.com/toeb/cmakepp) - Enhancement Suite for the CMake Build System. [```[MIT]```][MIT] :star:282
* [sugar](https://github.com/ruslo/sugar) - CMake tools and examples: collecting source files, warnings suppression, etc. [```[BSD2]```][BSD-2-Clause] :star:77
* [DownloadProject](https://github.com/Crascit/DownloadProject) - CMake module for downloading an external project's source at configure time. [```[MIT]```][MIT] :star:211
* [buildem](https://github.com/janelia-flyem/buildem) - Modular CMake-based system that leverages ExternalProject to simplify builds. [```[LICENSE]```](https://github.com/janelia-flyem/buildem/blob/master/LICENSE.txt)
* [coveralls-cmake](https://github.com/JoakimSoderberg/coveralls-cmake) - Coveralls JSON coverage generator and uploader for CMake. [```[MIT]```][MIT] :star:66
* [compatibility](https://github.com/foonathan/compatibility) - Improved version of cmake-compile-features. [```[LICENSE]```](https://github.com/foonathan/compatibility/blob/master/LICENSE)
* [cmake-modules](https://github.com/Tronic/cmake-modules) - LibFindMacros development repository and other cool CMake stuff. [```[LICENSE]```](https://github.com/Tronic/cmake-modules/blob/master/LibFindMacros.cmake#L2)
* [GreatCMakeCookOff](https://github.com/UCL/GreatCMakeCookOff) - This is a repository of useful and less than useful CMake recipes. [```[MIT]```][MIT] :star:22
* [cppcheck-target-cmake](https://github.com/polysquare/cppcheck-target-cmake) - Per-target CPPCheck for CMake. [```[MIT]```][MIT] :star:14
* [clang-tidy-target-cmake](https://github.com/polysquare/clang-tidy-target-cmake) - Add clang-tidy checks to a target using CMake. [```[MIT]```][MIT] :star:10
* [cmake-unit](https://github.com/polysquare/cmake-unit) - Unit testing framework for CMake. [```[MIT]```][MIT] :star:29
* [cmake-header-language](https://github.com/polysquare/cmake-header-language) - CMake macro to determine the language of a header file. [```[MIT]```][MIT] :star:2
* [tooling-cmake-util](https://github.com/polysquare/tooling-cmake-util) - Utility and common library for all polysquare CMake tools. [```[MIT]```][MIT] :star:2
* [iwyu-target-cmake](https://github.com/polysquare/iwyu-target-cmake) - CMake integration for include-what-you-use. [```[MIT]```][MIT] :star:3
* [sanitizers-cmake](https://github.com/arsenm/sanitizers-cmake) - CMake module to enable sanitizers for binary targets. [```[MIT]```][MIT] :star:102
* [cmake-precompiled-header](https://github.com/larsch/cmake-precompiled-header) - Visual Studio and GCC precompiled header macro. [```[LICENSE]```](https://github.com/larsch/cmake-precompiled-header/blob/master/PrecompiledHeader.cmake#L31)
* [CMakePCHCompiler](https://github.com/nanoant/CMakePCHCompiler) - CMake precompiled headers via custom compiler extension - with reuse support! [```[MIT]```][MIT] :star:43

# Information comes from [fffaraz/awesome-cpp](https://github.com/fffaraz/awesome-cpp)
# Awesome C++ [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome C++ (or C) frameworks, libraries, resources, and shiny things. Inspired by awesome-... stuff.

- [Awesome C++](#awesome-cpp)
	- [Standard Libraries](#standard-libraries)
	- [Frameworks](#frameworks)
	- [Artificial Intelligence](#artificial-intelligence)
	- [Asynchronous Event Loop](#asynchronous-event-loop)
	- [Audio](#audio)
	- [Biology](#biology)
	- [BitTorrent](#bittorrent)
	- [CLI](#cli)
	- [Compression](#compression)
	- [Concurrency](#concurrency)
	- [Configuration](#configuration)
	- [Containers](#containers)
	- [Cryptography](#cryptography)
	- [CSV](#csv)
	- [Database](#database)
	- [Debug](#debug)
	- [Font](#font)
	- [Game Engine](#game-engine)
	- [GUI](#gui)
	- [Graphics](#graphics)
	- [Image Processing](#image-processing)
	- [Internationalization](#internationalization)
	- [Inter-process communication](#inter-process-communication)
	- [JSON](#json)
	- [Logging](#logging)
	- [Machine Learning](#machine-learning)
	- [Math](#math)
	- [Memory Allocation](#memory-allocation)
	- [Multimedia](#multimedia)
	- [Networking](#networking)
	- [PDF](#pdf)
	- [Physics](#physics)
	- [Reflection](#reflection)
	- [Regular Expression](#regular-expression)
	- [Robotics](#robotics)
	- [Scientific Computing](#scientific-computing)
	- [Scripting](#scripting)
	- [Serialization](#serialization)
	- [Sorting](#sorting)
	- [Video](#video)
	- [Virtual Machines](#virtual-machines)
	- [Web Application Framework](#web-application-framework)
	- [XML](#xml)
	- [Miscellaneous](#miscellaneous)
- [Software](#software)
	- [Compiler](#compiler)
	- [Online Compiler](#online-compiler)
	- [Debugger](#debugger)
	- [Integrated Development Environment](#integrated-development-environment)
	- [Build Systems](#build-systems)
	- [Static Code Analysis](#static-code-analysis)
	- [Coding Style Tools](#coding-style-tools)
- [Resources](#resources)
	- [API Design](#api-design)
	- [Articles](#articles)
	- [Books](#books)
	- [Coding Style](#coding-style)
	- [Podcasts](#podcasts)
	- [Talks](#talks)
	- [Videos](#videos)
	- [Websites](#websites)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Standard Libraries
*C++ Standard Library - including STL Containers, STL Aglorithm, STL Functional, etc.*

* [C++ Standard Library](https://en.wikipedia.org/wiki/C%2B%2B_Standard_Library) - A collection of classes and functions, which are written in the core language and part of the C++ ISO Standard itself.
* [Standard Template Library](https://en.wikipedia.org/wiki/Standard_Template_Library) - The Standard Template Library (STL).
* [C POSIX library](https://en.wikipedia.org/wiki/C_POSIX_library) - A specification of a C standard library for POSIX systems.
* [ISO C++ Standards Committee](https://github.com/cplusplus) - ISO/IEC JTC1/SC22/WG21 - The C++ Standards Committee. [website](http://www.open-std.org/JTC1/SC22/WG21/)
* [The GNU C Library](https://www.gnu.org/software/libc/manual) - The purpose of this manual is to tell you how to use the facilities of the GNU C Library.

## Frameworks
*C++ generic frameworks and libraries.*

* [abseil-cpp](https://github.com/abseil/abseil-cpp) - Abseil C++ Common Libraries. [Apache2] :star:5940
* [Apache C++ Standard Library](http://stdcxx.apache.org/) - STDCXX, A collection of algorithms, containers, iterators, and other fundamental components. [retired] [Apache2]
* [APR](http://apr.apache.org/) - Apache Portable Runtime. Another library of cross-platform utility functions. [Apache2]
* [ASL](http://stlab.adobe.com/) - Adobe Source Libraries provides peer-reviewed and portable C++ source libraries. [MIT]
* [Boost](https://github.com/boostorg) :zap: - A large collection of generic C++ libraries. [Boost] [website](http://www.boost.org/)
* [BDE](https://github.com/bloomberg/bde) - The BDE Development Environment from Bloomberg Labs. [Apache2] :star:1037
* [Cinder](https://libcinder.org/) - A community-developed, free and open source library for professional-quality creative coding. [BSD]
* [Cxxomfort](http://ryan.gulix.cl/fossil.cgi/cxxomfort/) - A small, header-only library that backports various facilities from more recent C++ Standards to C++03 and later. [MIT]
* [Dlib](https://github.com/davisking/dlib) :zap: - A general purpose cross-platform C++ library designed using contract programming and modern C++ techniques. [Boost] [website](http://dlib.net/)
* [EASTL](https://github.com/electronicarts/EASTL) - Electronic Arts Standard Template Library. [BSD] :star:4223
* [ETL](https://github.com/ETLCPP/etl) - Embedded Template Library. [MIT] :star:470
* [ffead-cpp](https://github.com/sumeetchhetri/ffead-cpp) - Framework for Enterprise Application Development. [Apache2] :star:332
* [Folly](https://github.com/facebook/folly) - An open-source C++ library developed and used at Facebook. [Apache2] :star:13746
* [FunctionalPlus](https://github.com/Dobiasd/FunctionalPlus) - Functional Programming Library for C++. Write concise and readable C++ code. [MIT] :star:937
* [GLib](https://wiki.gnome.org/Projects/GLib) - GLib provides the core application building blocks for libraries and applications written in C. [LGPL]
* [JUCE](https://github.com/julianstorer/JUCE) - An all-encompassing C++ class library for developing cross-platform software. [Core-Module: ISC, Rest: GPL2/GPL3/Commercial] [website](http://www.juce.com/)
* [libPhenom](https://github.com/facebook/libphenom) - libPhenom is an eventing framework for building high performance and high scalability systems in C. [Apache2] :star:1637
* [LibSourcey](https://github.com/sourcey/libsourcey) - C++11 evented IO for real-time video streaming and high performance networking applications. [LGPL] :star:990
* [LibU](https://github.com/koanlogic/libu) - A multiplatform utility library written in C. [BSD] :star:264
* [Loki](http://loki-lib.sourceforge.net/) - A C++ library of designs, containing flexible implementations of common design patterns and idioms. [MIT]
* [MiLi](https://bitbucket.org/fudepan/mili/) - Minimal headers-only C++ Library. [Boost]
* [OpenFrameworks](https://github.com/openframeworks/openFrameworks) - A cross platform open source toolkit for creative coding in C++. [MIT] [website](http://www.openframeworks.cc/)
* [Qt](https://www.qt.io/download-open-source/) :zap: - A cross-platform application and UI framework. [GPL/LGPL/Commercial]
* [Reason](http://code.google.com/p/reason/) - A cross platform framework designed to bring the ease of use of Java, .Net, or Python to developers who require the performance and strength of C++. [GPL2]
* [ROOT](https://root.cern.ch/) - A set of OO frameworks with all the functionality needed to handle and analyze large amounts of data in a very efficient way. Used at CERN. [LGPL]
* [STLport](http://www.stlport.org/) - An exemplary version of STL. [Free]
* [STXXL](http://stxxl.sourceforge.net/) - Standard Template Library for Extra Large Data Sets. [Boost]
* [tbox](https://github.com/tboox/tbox) - A glib-like multi-platform c library. [Apache2] [website](http://tboox.org/)
* [Ultimate++](http://www.ultimatepp.org/) - A C++ cross-platform rapid application development framework. [BSD]
* [uSTL](http://msharov.github.io/ustl/) - The small STL library. [MIT]
* [Windows Template Library](http://sourceforge.net/projects/wtl/) - A C++ library for developing Windows applications and UI components. [Public]
* [Yomm2](https://github.com/jll63/yomm2) - Fast, Orthogonal, Open multi-methods. Supersedes [Yomm11](https://github.com/jll63/yomm11) [Boost] :star:108

## Artificial Intelligence

* [ANNetGPGPU](https://github.com/ANNetGPGPU/ANNetGPGPU) - A GPU (CUDA) based Artificial Neural Network library. [LGPL] :star:67
* [btsk](https://github.com/aigamedev/btsk) - Game Behavior Tree Starter Kit. [zlib] :star:295
* [Evolving Objects](http://eodev.sourceforge.net/) - A template-based, ANSI-C++ evolutionary computation library which helps you to write your own stochastic optimization algorithms insanely fast. [LGPL]
* [frugally-deep](https://github.com/Dobiasd/frugally-deep) - Header-only library for using Keras models in C++. [MIT] :star:500
* [Genann](https://github.com/codeplea/genann) - Simple neural network library in C. [zlib] :star:914
* [MXNet](https://github.com/apache/incubator-mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Scala, Go, Javascript and more [website](https://mxnet.apache.org)
* [PyTorch](https://github.com/pytorch/pytorch) - Tensors and Dynamic neural networks in Python with strong GPU acceleration. [website](https://pytorch.org)
* [Recast/Detour](https://github.com/recastnavigation/recastnavigation) - (3D) Navigation mesh generator and pathfinder, mostly for games. [zlib] :star:2869
* [TensorFlow](https://github.com/tensorflow/tensorflow) - An open source software library for numerical computation using data flow graphs [Apache] :star:135819
* [CNTK](https://github.com/Microsoft/CNTK) - Microsoft Cognitive Toolkit (CNTK), an open source deep-learning toolkit. [Boost] :star:16464
* [tiny-dnn](https://github.com/tiny-dnn/tiny-dnn) - A header only, dependency-free deep learning framework in C++11. [BSD] :star:4879
* [Veles](https://github.com/Samsung/veles) - Distributed platform for rapid Deep learning application development. [Apache] :star:882
* [Kaldi](https://github.com/kaldi-asr/kaldi) - Toolkit for speech recognition. [Apache] :star:7322

## Asynchronous Event Loop

* [Asio](https://github.com/chriskohlhoff/asio/) - A cross-platform C++ library for network and low-level I/O programming that provides developers with a consistent asynchronous model using a modern C++ approach. [Boost] [website](http://think-async.com/)
* [Boost.Asio](http://think-async.com/) - A cross-platform C++ library for network and low-level I/O programming. [Boost]
* [C++ Actor Framework](https://github.com/actor-framework/actor-framework) - An Open Source Implementation of the Actor Model in C++. [BSD-3-Clause] [website](http://actor-framework.org/)
* [libev](http://libev.schmorp.de/) - A full-featured and high-performance event loop that is loosely modelled after libevent, but without its limitations and bugs. [BSD and GPL]
* [libevent](http://libevent.org/) - An event notification library. [BSD]
* [libuv](https://github.com/libuv/libuv) - Cross-platform asynchronous I/O. [BSD] :star:13633
* [promise-cpp](https://github.com/xhawk18/promise-cpp) - Header only library that implements Promise/A+ standard. [Anti-996] :star:175
* [uvw](https://github.com/skypjack/uvw) - C++ wrapper for libuv. [MIT] :star:782

## Audio
*Audio, Sound, Music, Digitized Voice Libraries*

* [FMOD](http://www.fmod.org/) - An easy to use crossplatform audio engine and audio content creation tool for games. [Free for non-commercial/Commercial]
* [KFR](https://www.kfrlib.com/) - Fast, modern C++ DSP framework, FFT, FIR/IIR filters, Sample Rate Conversion. [GPL/Commercial]
* [libsndfile](https://github.com/erikd/libsndfile/) - C library with C++ wrapper for reading and writing files containing sampled sound through one standard library interface. [LGPL-2.1] [website](http://www.mega-nerd.com/libsndfile/)
* [libsoundio](https://github.com/andrewrk/libsoundio) - C library for cross-platform real-time audio input and output. [MIT] [website](http://libsound.io/)
* [Maximilian](https://github.com/micknoise/Maximilian) - C++ Audio and Music DSP Library. [MIT] :star:885
* [OpenAL](http://www.openal.org/) - Open Audio Library - A crossplatform audio API. [BSD/LGPL/Commercial]
* [miniaudio](https://github.com/dr-soft/miniaudio) - Single file audio playback and capture library. [Unlicense] :star:558
* [Opus](http://opus-codec.org/) - A totally open, royalty-free, highly versatile audio codec. [BSD]
* [PortAudio](http://www.portaudio.com/) - PortAudio is a free, cross-platform, open-source, audio I/O library. [MIT]
* [SELA](https://github.com/sahaRatul/sela) - SimplE Lossless Audio. [MIT] :star:182
* [SoLoud](https://github.com/jarikomppa/soloud) - Easy, portable audio engine for games. [zlib] :star:701
* [Speex](http://www.speex.org/) - A free codec for free speech. Obsoleted by Opus. [BSD]
* [Tonic](https://github.com/TonicAudio/Tonic) - Easy and efficient audio synthesis in C++. [Unlicense] :star:377
* [Vorbis](http://xiph.org/vorbis/) - Ogg Vorbis is a fully open, non-proprietary, patent-and-royalty-free, general-purpose compressed audio format. [BSD]
* [minimp3](https://github.com/lieff/minimp3) - Public domain, header-only MP3 decoder with clean-room implementation. [CC0] :star:562
* [Verovio](https://github.com/rism-ch/verovio) - Verovio is a fast and lightweight music notation engraving library. [LGPL] [website](https://www.verovio.org)
* [Wav2Letter++](https://github.com/facebookresearch/wav2letter/) - Public domain, a fast open source speech processing toolkit written entirely in C++ and uses the ArrayFire tensor library and the flashlight machine learning library for maximum efficiency [BSD] :star:4005

## Biology
*Bioinformatics, Genomics, Biotech*

* [BioC++](http://biocpp.sourceforge.net/) - C++ Computational Libraries for Bioinformatics. [BSD]
* [Chaste](http://www.cs.ox.ac.uk/chaste/) - An open source C++ library for the computational simulation of mathematical models developed for physiology and biology. [BSD]
* [libsequence](http://molpopgen.github.io/libsequence/) - A C++ library for representing and analyzing population genetics data. [GPL]
* [SeqAn](http://www.seqan.de/) - Algorithms and data structures for the analysis of sequences with the focus on biological data. [BSD/3-clause]
* [Vcflib](https://github.com/ekg/vcflib) - A C++ library for parsing and manipulating VCF files. [MIT] :star:331
* [Wham](https://github.com/zeeev/wham) - Structural variants (SVs) in Genomes by directly applying association tests to BAM files. [MIT] :star:61

## BitTorrent

* [jech/dht](https://github.com/jech/dht) - BitTorrent DHT library in C. [MIT] :star:530
* [libtorrent](https://github.com/arvidn/libtorrent) (a.k.a. libtorrent-rasterbar) - An efficient feature complete C++ bittorrent implementation. [BSD] :star:2012
* [LibTorrent](https://github.com/rakshasa/libtorrent) (a.k.a. libtorrent-rakshasa) - BitTorrent library. [GPL] :star:752
* [libutp](https://github.com/bittorrent/libutp) - uTorrent Transport Protocol library. [MIT] :star:804

## CLI
*Console/Terminal User Interface, Command Line Interface*

 * [Argh!](https://github.com/adishavit/argh) - A minimalist, frustration-free, header-only argument handler. [BSD] :star:490
 * [Taywee/args](https://github.com/taywee/args) - A simple header-only C++ argument parser library. [MIT] :star:653
 * [Boost.Program_options](http://www.boost.org/doc/libs/1_57_0/doc/html/program_options.html) - A library to obtain program options via conventional methods such as command line and config file. [Boost]
 * [Clara](https://github.com/catchorg/Clara) - A simple to use, composable, command line parser for C++ 11 and beyond. [BSL-1.0] :star:614
 * [cli](https://github.com/daniele77/cli) - A cross-platform header only C++14 library for interactive command line interfaces (Cisco style). [Boost] :star:278
 * [CLI11](https://github.com/CLIUtils/CLI11) - Header only single or multi-file C++11 library for simple and advanced CLI parsing. [BSD] :star:822
 * [jarro2783/cxxopts](https://github.com/jarro2783/cxxopts) - Lightweight C++ command line option parser. [MIT] :star:1524
 * [docopt.cpp](https://github.com/docopt/docopt.cpp) - A library to generate option parser from docstring. [MIT/Boost] :star:695
 * [gflags](https://gflags.github.io/gflags/) - Commandline flags module for C++. [BSD]
 * [linenoise](https://github.com/antirez/linenoise) - A small self-contained alternative to readline and libedit. [BSD-2-Clause] :star:2306
 * [linenoise-ng](https://github.com/arangodb/linenoise-ng) - A small, portable GNU readline replacement for Linux, Windows and MacOS which is capable of handling UTF-8 characters. [BSD] :star:249
 * [Ncurses](http://invisible-island.net/ncurses/) - A terminal user interfaces. [MIT]
 * [PDCurses](https://github.com/wmcbrine/PDCurses) - Public domain curses library with both source code and pre-compiled library available. [PublicDomain] :star:402
 * [replxx](https://github.com/AmokHuginnsson/replxx) - A readline and libedit replacement that supports UTF-8, syntax highlighting, hints, works on Unix and Windows. [BSD] :star:298
 * [TCLAP](http://tclap.sourceforge.net) - A mature, stable and feature-rich library for defining and accessing command line arguments in ANSI C++. [MIT]
 * [termbox](https://github.com/nsf/termbox) - A C library for writing text-based user interfaces. [MIT] :star:1538

## Compression
*Compression and Archiving Libraries*

* [bit7z](https://github.com/rikyoz/bit7z) - A C++ static library offering a clean and simple interface to the 7-zip DLLs. [GPLv2] :star:85
* [Brotli](https://github.com/google/brotli) - Brotli compression format. Developed by Google. [MIT] :star:7825
* [bzip2](http://www.bzip.org/) - A freely available, patent free, high-quality data compressor. [BSD]
* [FiniteStateEntropy](https://github.com/Cyan4973/FiniteStateEntropy) - New generation entropy codecs : Finite State Entropy and Huff0. :star:810
* [PhysicsFS](https://icculus.org/physfs/) - A library to provide abstract access to various archives. It is intended for use in video games, and the design was somewhat inspired by Quake 3's file subsystem. [zlib]
* [KArchive](https://quickgit.kde.org/?p=karchive.git) - A library for creating, reading, writing and manipulating file archives like zip and tar. It also provides transparent compression and decompression of data, using formats like gzip, via a subclass of QIODevice. [LGPL]
* [libarchive](https://github.com/libarchive/libarchive) - Multi-format archive and compression library. [New BSD] [website](http://www.libarchive.org/)
* [LZ4](https://github.com/lz4/lz4) - Extremely Fast Compression algorithm. [BSD] [website](http://www.lz4.org/)
* [LZFSE](https://github.com/lzfse/lzfse) - LZFSE compression library and command line tool. Developed by Apple. :star:1492
* [LZHAM](https://code.google.com/p/lzham/) - Lossless data compression library with a compression ratio similar to LZMA but with much faster decompression. [BSD]
* [LZMA](http://www.7-zip.org/sdk.html) :zap: - The default and general compression method of 7z format. [PublicDomain]
* [LZMAT](http://www.matcode.com/lzmat.htm) - An extremely fast real-time lossless data compression library. [GPL]
* [miniz](https://github.com/richgel999/miniz) - Single C source file Deflate/Inflate compression library with zlib-compatible API, ZIP archive reading/writing, PNG writing. [MIT] :star:738
* [Minizip](https://github.com/nmoinvaz/minizip) - Zlib with latest bug fixes that supports PKWARE disk spanning, AES encryption, and IO buffering. [zlib] :star:501
* [smaz](https://github.com/antirez/smaz) - Small strings compression library. [BSD] :star:754
* [Snappy](https://google.github.io/snappy/) - A fast compressor/decompressor. [BSD]
* [ZLib](http://zlib.net/) - A very compact compression library for data streams. [zlib]
* [zlib-ng](https://github.com/Dead2/zlib-ng) - zlib for the "next generation" systems. Drop-In replacement with some serious optimizations. [zlib] :star:528
* [zstd](https://github.com/facebook/zstd) - Zstandard - Fast real-time compression algorithm. Developed by Facebook. [BSD] :star:10834
* [ZZIPlib](http://zziplib.sourceforge.net/) - Provides read access on ZIP-archives. [MPL/LGPL]

## Concurrency
*Concurrency and Multithreading*

* [alpaka](https://github.com/ComputationalRadiationPhysics/alpaka) - Abstraction library for parallel kernel acceleration. [LGPLv3+] :star:78
* [ArrayFire](https://github.com/arrayfire/arrayfire) - A general purpose GPU library. [BSD] :star:2831
* [Async++](https://github.com/Amanieu/asyncplusplus) - A lightweight concurrency framework for C++11, inspired by the Microsoft PPL library and the N3428 C++ standard proposal. [MIT] :star:654
* [Boost.Compute](https://github.com/boostorg/compute) - A C++ GPU Computing Library for OpenCL. [Boost] :star:1033
* [Bolt](https://github.com/HSA-Libraries/Bolt) - A C++ template library optimized for GPUs. [Apache2] :star:323
* [ck](https://github.com/concurrencykit/ck) - Concurrency primitives, safe memory reclamation mechanisms and non-blocking data structures. [BSD] :star:1598
* [concurrentqueue](https://github.com/cameron314/concurrentqueue) - A fast multi-producer, multi-consumer lock-free concurrent queue for C++11. [BSD,Boost] :star:3878
* [Cpp-Taskflow](https://github.com/cpp-taskflow/cpp-taskflow) - Fast C++ Parallel Programming with Task Dependencies. [MIT] :star:2510
* [CUB](https://github.com/NVlabs/cub) - CUB provides state-of-the-art, reusable software components for every layer of the CUDA programming mode. [New BSD] :star:596
* [cupla](https://github.com/ComputationalRadiationPhysics/cupla) - C++ API to run CUDA/C++ on OpenMP, Threads, TBB, ... through Alpaka. [LGPLv3+] :star:18
* [C++React](https://github.com/schlangster/cpp.react) - A reactive programming library for C++11. [Boost] :star:832
* [FiberTaskingLib](https://github.com/RichieSams/FiberTaskingLib) - Task-based multi-threading library that supports task graphs with arbitrary dependencies. [Apache] :star:502
* [Intel Games Task Scheduler](https://github.com/GameTechDev/GTS-GamesTaskScheduler) - A task scheduling framework designed for the needs of game developers. [MIT] :star:223
* [Intel Parallel STL](https://github.com/intel/parallelstl) - Intel® implementation of C++17 STL for C++11 and above. [Apache2] :star:484
* [Intel TBB](https://www.threadingbuildingblocks.org/) - Intel® Threading Building Blocks. [Apache2]
* [junction](https://github.com/preshing/junction) - A library of concurrent data structures in C++. [BSD] :star:984
* [libcds](https://github.com/khizmax/libcds) - A C++ library of Concurrent Data Structures. [BSD] :star:1432
* [Libclsph](https://github.com/libclsph/libclsph) - An OpenCL based GPU accelerated SPH fluid simulation library. [MIT] :star:38
* [libdill](https://github.com/sustrik/libdill/) - Introduces structured concurrency in C. [MIT] :star:1196
* [libdispatch](https://github.com/apple/swift-corelibs-libdispatch) - Grand Central Dispatch (GCD), developed by Apple Inc., is a task parallelism technology based on the thread pool pattern. libdispatch is a library that provides the implementation of GCD's services. [Apache-2.0] [website](https://apple.github.io/swift-corelibs-libdispatch/)
* [libmill](https://github.com/sustrik/libmill/) - Introduces Go-style concurrency in C. [MIT] :star:2358
* [moderngpu](https://github.com/moderngpu/moderngpu) - moderngpu is a productivity library for general-purpose computing on GPUs. It is a header-only C++ library written for CUDA. The unique value of the library is in its accelerated primitives for solving irregularly parallel problems. [FreeBSD & Copyright, Sean Baxter] :star:1006
* [NCCL](https://github.com/NVIDIA/nccl) - Optimized primitives for collective multi-GPU communication. [BSD] :star:1066
* [OpenCL](https://www.khronos.org/opencl/) - The open standard for parallel programming of heterogeneous systems.
* [OpenMP](http://openmp.org/) - The OpenMP API.
* [RaftLib](http://raftlib.io/) - The RaftLib C++ library, streaming/dataflow concurrency via C++ iostream-like operators [Apache2]
* [readerwriterqueue](https://github.com/cameron314/readerwriterqueue) - A fast single-producer, single-consumer lock-free queue for C++. [BSD] :star:1475
* [Thrust](http://thrust.github.io/) - A parallel algorithms library which resembles the C++ Standard Template Library (STL). [Apache2]
* [transwarp](https://github.com/bloomen/transwarp) - A header-only C++ library for task concurrency. [MIT] :star:364
* [HPX](https://github.com/STEllAR-GROUP/hpx/) - A general purpose C++ runtime system for parallel and distributed applications of any scale. [Boost] :star:1289
* [VexCL](https://github.com/ddemidov/vexcl) - A C++ vector expression template library for OpenCL/CUDA. [MIT] :star:573
* [Quantum](https://github.com/bloomberg/quantum) - A powerful C++ coroutine dispatcher framework built on top of [boost::coroutines2](https://www.boost.org/doc/libs/1_65_0/libs/coroutine2/doc/html/index.html). :star:101

## Configuration
*Configuration files, INI files*

* [inih](https://github.com/benhoyt/inih) - Simple .INI file parser in C, good for embedded systems. [BSD-3-Clause] :star:987
* [inih](https://github.com/jtilly/inih) - Single header only C++ version of [inih](https://github.com/benhoyt/inih). [BSD-3-Clause] :star:162
* [iniparser](https://github.com/ndevilla/iniparser) - INI file parser. [MIT] :star:523
* [libconfig](https://github.com/hyperrealm/libconfig) - C, C++ library for processing structured configuration files. [LGPL-2.1] [website](https://hyperrealm.github.io/libconfig/)
* [libconfuse](https://github.com/martinh/libconfuse) - Small configuration file parser library for C. [ISC] :star:268
* [simpleini](https://github.com/brofield/simpleini) - Cross-platform C++ library providing a simple API to read and write INI-style configuration files. [MIT] :star:402

## Containers

* [C++ B-tree](https://code.google.com/p/cpp-btree/) - A template library that implements ordered in-memory containers based on a B-tree data structure. [Apache2]
* [Colony](https://github.com/mattreecebentley/plf_colony) - An unordered "bag"-type container which outperforms std containers in high-modification scenarios while maintaining permanent pointers to non-erased elements regardless of insertion/erasure. [zLib] [website](http://www.plflib.org/colony.htm)
* [dynamic_bitset](https://github.com/pinam45/dynamic_bitset) - A C++17 header-only dynamic bitset. [MIT] :star:27
* [Forest](https://github.com/xorz57/forest) - Template library implementing an AVL, a Binary Search, a KD and a Quad Tree. [MIT] :star:85
* [Hashmaps](https://github.com/goossaert/hashmap) - Implementation of open addressing hash table algorithms in C++. [MIT] :star:197
* [Hopscotch map](https://github.com/Tessil/hopscotch-map) - A fast header-only hash map which uses hopscotch hashing for collisions resolution. [MIT] :star:339
* [LSHBOX](https://github.com/RSIA-LIESMARS-WHU/LSHBOX) - A c++ toolbox of locality-sensitive hashing (LSH), provides several popular LSH algorithms, also support Python and MATLAB. [GPL] :star:217
* [plf::list](https://github.com/mattreecebentley/plf_list) - A std::list implementation which removes range splicing in order to enable cache-friendlier structure, yielding significant performance gains. [zLib] [website](http://www.plflib.org/list.htm)
* [plf::stack](https://github.com/mattreecebentley/plf_stack) - A replacement container for the std::stack container adaptor, with better performance than any std container in a stack context. [zLib] [website](http://www.plflib.org/stack.htm)
* [ring_span lite](https://github.com/martinmoene/ring-span-lite) - A simplified implementation of Arthur O'Dwyer's ring_span implementation ie. a circular buffer view. [MIT] :star:59
* [robin-hood-hashing](https://github.com/martinus/robin-hood-hashing) - Fast & memory efficient hashtable based on robin hood hashing for C++14. [MIT] :star:277
* [robin-map](https://github.com/Tessil/robin-map) - Fast hash map and hash set using robin hood hashing. [MIT] :star:286
* [sparsepp](https://github.com/greg7mdp/sparsepp) - A fast, memory efficient hash map for C++. [BSD 3-clause] :star:916

## Cryptography
*Cryptography and Encryption Libraries*

* [Bcrypt](http://bcrypt.sourceforge.net/) - A cross platform file encryption utility. Encrypted files are portable across all supported operating systems and processors. [BSD]
* [BeeCrypt](http://beecrypt.sourceforge.net/) - A portable and fast cryptography library. [LGPLv2.1+]
* [Botan](http://botan.randombit.net/) - A crypto library for C++. [BSD-2]
* [Crypto++](https://github.com/weidai11/cryptopp) - A free C++ class library of cryptographic schemes. [Boost] [website](http://www.cryptopp.com/)
* [digestpp](https://github.com/kerukuro/digestpp) - C++11 header-only message digest (hash) library. [PublicDomain] :star:72
* [GnuPG](https://www.gnupg.org/) - A complete and free implementation of the OpenPGP standard. [GPL]
* [GnuTLS](http://www.gnutls.org/) - A secure communications library implementing the SSL, TLS and DTLS protocols. [LGPL2.1]
* [Libgcrypt](http://www.gnu.org/software/libgcrypt/) - A general purpose cryptographic library originally based on code from GnuPG. [LGPLv2.1+]
* [LibreSSL](http://www.libressl.org/) - A free version of the SSL/TLS protocol forked from OpenSSL in 2014. [?]
* [libsodium](https://github.com/jedisct1/libsodium) - P(ortable|ackageable) NaCl-based crypto library, opinionated and easy to use. [ISC] :star:7639
* [libhydrogen](https://github.com/jedisct1/libhydrogen) - A lightweight, secure, easy-to-use crypto library suitable for constrained environments. [ISC] :star:513
* [LibTomCrypt](https://github.com/libtom/libtomcrypt) - A fairly comprehensive, modular and portable cryptographic toolkit. [WTFPL] :star:876
* [mbedTLS](https://github.com/ARMmbed/mbedtls) - An open source, portable, easy to use, readable and flexible SSL library, previously known as PolarSSL. [Apache2] [website](https://tls.mbed.org/)
* [Nettle](http://www.lysator.liu.se/~nisse/nettle/) - A low-level cryptographic library. [LGPL]
* [OpenSSL](https://github.com/openssl/openssl) - A robust, commercial-grade, full-featured, and Open Source cryptography library. [Apache] [website](http://www.openssl.org/)
* [retter](https://github.com/MaciejCzyzewski/retter) - A collection of hash functions, ciphers, tools, libraries, and materials related to cryptography. :star:47
* [s2n](https://github.com/awslabs/s2n) - An implementation of the TLS/SSL protocols. [Apache] :star:3525
* [sha1collisiondetection](https://github.com/cr-marcstevens/sha1collisiondetection) - Library and command line tool to detect SHA-1 collision in a file. [MIT] :star:1046
* [Tink](https://github.com/google/tink) - A multi-language, cross-platform library that provides cryptographic APIs that are secure, easy to use correctly, and hard(er) to misuse. [Apache-2.0] :star:8460
* [Tiny AES in C](https://github.com/kokke/tiny-AES-c) - Small portable AES128/192/256 in C. [PublicDomain] :star:1747
* [Themis](https://github.com/cossacklabs/themis) - crypto library for painless data security, providing symmetric and asymmetric encryption, secure sockets with forward secrecy, for mobile and server platforms. [Apache2] :star:860

## CSV
*Libraries for parsing Comma Separated Value (CSV) files*

* [csv](https://github.com/p-ranav/csv) - CSV for modern C++. [MIT] :star:151
* [Fast C++ CSV Parser](https://github.com/ben-strasser/fast-cpp-csv-parser) - Small, easy-to-use and fast header-only library for reading CSV files. [BSD-3-Clause] :star:773
* [Vince's CSV Parser](https://github.com/vincentlaucsb/csv-parser) - A fast, self-contained, streaming C++17 CSV parser with optional type-casting and statistics. [MIT] :star:152

## Database
*Database Libraries, SQL Servers, ODBC Drivers, and Tools*

* [hiberlite](https://github.com/paulftw/hiberlite) - C++ Object-relational mapping for sqlite3. [BSD] :star:507
* [Hiredis](https://github.com/redis/hiredis) - A minimalistic C client library for the Redis database. [BSD] :star:4031
* [LevelDB](https://github.com/google/leveldb) - A fast key-value storage library written at Google that provides an ordered mapping from string keys to string values. [BSD] :star:18918
* [LMDB](http://symas.com/mdb/) - Very fast embedded key/value store with full ACID semantics. [OpenLDAP]
* [LMDB++](https://github.com/bendiken/lmdbxx) - C++11 wrapper for the LMDB embedded database library. [PublicDomain] :star:189
* [MongoDB C Driver](https://github.com/mongodb/mongo-c-driver) - MongoDB client library for C. [Apache2] :star:559
* [MongoDB C++ Driver](https://github.com/mongodb/mongo-cxx-driver) - C++ driver for MongoDB. [Apache2] :star:669
* [MongoDB Libbson](https://github.com/mongodb/libbson) - A BSON utility library. [Apache2] :star:307
* [MySQL++](http://www.tangentsoft.net/mysql++/) - A C++ wrapper for MySQL's C API. [LGPL]
* [nanodbc](https://github.com/nanodbc/nanodbc) - A small C++ wrapper for the native C ODBC API. [MIT] :star:101
* [ODB](https://www.codesynthesis.com/products/odb/) - An open-source, cross-platform, and cross-database object-relational mapping (ORM) system for C++. [GPLv2]
* [redis3m](https://github.com/luca3m/redis3m) - Wrapper of hiredis with clean C++ interface, supporting sentinel and ready to use patterns. [Apache2] :star:158
* [RocksDB](https://github.com/facebook/rocksdb) - Embedded key-value store for fast storage from facebook. [BSD] :star:15081
* [SimDB](https://github.com/LiveAsynchronousVisualizedArchitecture/simdb) - High performance, shared memory, lock free, cross platform, single file, minimal dependencies, C++11 key-value store [Apache2] :star:332
* [SOCI](https://github.com/SOCI/soci) - A database abstraction layer for C++. [BSL-1.0] :star:784
* [SQLite](http://www.sqlite.org/) - A completely embedded, full-featured relational database in a few 100k that you can include right into your project. [PublicDomain]
* [SQLiteC++](https://github.com/SRombauts/SQLiteCpp) - SQLiteC++ (SQLiteCpp) is a smart and easy to use C++ SQLite3 wrapper. [MIT] :star:778
* [sqlite_modern_cpp](https://github.com/SqliteModernCpp/sqlite_modern_cpp) - Header only C++14 wrapper around sqlite library. [MIT] :star:470
* [sqlite_orm](https://github.com/fnc12/sqlite_orm) - SQLite ORM light header only library for modern C++. [BSD-3-Clause] :star:637
* [sqlpp11](https://github.com/rbock/sqlpp11) - A type safe embedded domain specific language for SQL queries and results in C++. [BSD-2-Clause] :star:1411
* [TileDB](https://github.com/TileDB-Inc/TileDB) - Fast Dense and Sparse Multidimensional Array DBMS. [MIT] [website](https://tiledb.io/)
* [upscaledb](https://upscaledb.com) - An embedded "typed" key/value store with a built-in query interface. [GPLv3]

## Debug
*Debugging Libraries, Memory Leak and Resource Leak Detection, Unit Testing*

* [backward-cpp](https://github.com/bombela/backward-cpp) - A beautiful stack trace pretty printer for C++. [MIT] :star:1319
* [benchmark](https://github.com/google/benchmark) - Google provided small microbenchmark support library. [Apache2] :star:3773
* [Boost.Test](http://www.boost.org/doc/libs/master/libs/test/doc/html/index.html) - Boost Test Library. [Boost]
* [check](https://github.com/libcheck/check) - Check is a unit testing framework for C. [LGPL-2.1] [website](https://libcheck.github.io/check/)
* [doctest](https://github.com/onqtam/doctest) - The lightest feature rich C++ single header testing framework. [MIT] :star:2082
* [Catch](https://github.com/philsquared/Catch) - A modern, C++-native, header-only, framework for unit-tests, TDD and BDD. [Boost] :star:10133
* [Catch2](https://github.com/catchorg/Catch2) - A modern, C++-native, header-only, test framework for unit-tests, TDD and BDD. [BSL-1.0] :star:10133
* [Celero](https://github.com/DigitalInBlue/Celero) - C++ Benchmarking Framework. [Apache2] :star:476
* [CppUTest](https://github.com/cpputest/cpputest) - Unit testing and mocking framework for C/C++. [BSD-3-clause] :star:695
* [CUTE](http://cute-test.com) - C++ Unit Testing Easier. [LGPL3]
* [CMocka](https://cmocka.org/) - unit testing framework for C with support for mock objects. [Apache2]
* [CppUnit](http://www.freedesktop.org/wiki/Software/cppunit/) - C++ port of JUnit. [LGPL2]
* [CTest](https://cmake.org/cmake/help/v2.8.8/ctest.html) - The CMake test driver program. [BSD]
* [dbg-macro](https://github.com/sharkdp/dbg-macro) - A dbg(…) macro for C++. [MIT] :star:971
* [Deleaker](http://www.deleaker.com) - A tool for resource leak detection, including memory, GDI and handle leaks.
* [fff](https://github.com/meekrosoft/fff) - A micro-framework for creating fake C functions. [MIT] :star:281
* [Google Mock](https://github.com/google/googletest/blob/master/googlemock/README.md) - A library for writing and using C++ mock classes. [BSD] :star:13265
* [Google Test](https://github.com/google/googletest) - Google C++ Testing Framework. [BSD] :star:13265
* [ig-debugheap](https://github.com/deplinenoise/ig-debugheap) - Multiplatform debug heap useful for tracking down memory errors. [BSD] :star:137
* [libtap](https://github.com/zorgnax/libtap) - Write tests in C. [GPL2] :star:175
* [MemTrack](http://www.almostinfinite.com/memtrack.html) - Tracking memory allocations in C++.
* [microprofile](https://bitbucket.org/jonasmeyer/microprofile/overview) - Profiler with web-view for multiple platforms. [PublicDomain]
* [MinUnit](https://github.com/siu/minunit) - A minimal unit testing framework for C self-contained in a single header file. [MIT] :star:261
* [Mockator](http://www.mockator.com) - Eclipse CDT plug-in for C++ Seams and Mock Objects.
* [Nanotimer](https://github.com/mattreecebentley/plf_nanotimer) - A simple low-overhead cross-platform timer class for benchmarking. [zLib] [website](http://www.plflib.org/nanotimer.htm)
* [Nonius](https://github.com/libnonius/nonius) - A C++ micro-benchmarking framework. [CC] :star:278
* [Remotery](https://github.com/Celtoys/Remotery) - Single C File Profiler with Web Viewer. [Apache2] :star:1341
* [UnitTest++](https://github.com/unittest-cpp/unittest-cpp) - A lightweight unit testing framework for C++. [MIT/X Consortium license] :star:397
* [Unity](https://github.com/ThrowTheSwitch/Unity) - Simple Unit Testing for C. [MIT] :star:1264
* [utest.h](https://github.com/sheredom/utest.h) - Single header unit testing framework for C and C++. [Unlicense] :star:128
* [VLD](http://vld.codeplex.com/) - Visual Leak Detector. A free, robust, open-source memory leak detection system for Visual C++.

## Font
*Libraries for parsing and manipulating font files.*

* [Fontconfig](https://gitlab.freedesktop.org/fontconfig/fontconfig) - Font configuration and customization library. [MIT] [website](https://www.freedesktop.org/wiki/Software/fontconfig/)
* [FreeType](https://www.freetype.org/) - FreeType is a freely available software library to render fonts. [FTL & GPLv2]
* [otfcc](https://github.com/caryll/otfcc) - A C library and utility used for parsing and writing OpenType font files. [Apache-2.0] :star:266

## Game Engine

* [Acid](https://github.com/Equilibrium-Games/Acid) - A high speed C++17 Vulkan game engine. [MIT] :star:456
* [Allegro](http://liballeg.org/) - A cross-platform library mainly aimed for video games and multimedia programming. [zlib]
* [Atomic Game Engine](https://github.com/AtomicGameEngine/AtomicGameEngine) - A multi-platform 2D and 3D engine with a consistent API in C++, C#, JavaScript, and TypeScript. [Commercial] :star:2229
* [Banshee 3D](https://github.com/BearishSun/BansheeEngine) - Modern C++14 game engine with Vulkan support, fully featured editor and C# scripting. [LGPL3/Commercial] :star:2848
* [Cocos2d-x](http://www.cocos2d-x.org/) - A multi-platform framework for building 2d games, interactive books, demos and other graphical applications. [MIT]
* [Corange](https://github.com/orangeduck/Corange) - A game engine written in pure C, SDL and OpenGL. [BSD] :star:1013
* [delta3d](http://sourceforge.net/projects/delta3d/) - A robust simulation platform. [LGPL2]
* [EnTT](https://github.com/skypjack/entt) - Gaming meets modern C++. [MIT] :star:2194
* [GamePlay](https://github.com/gameplay3d/GamePlay) - A cross-platform native C++ game framework for creating 2D/3D mobile and desktop games. [Apache2] :star:2824
* [Godot](https://github.com/godotengine/godot) - A fully featured, open source, MIT licensed, game engine. [MIT] :star:24986
* [Grit](http://www.gritengine.com/) - Community project to build a free game engine for implementing open world 3D games. [MIT]
* [Halley](https://github.com/amzeratul/halley) - A lightweight game engine written in C++14 with a "true" entity-component system. [Apache 2.0] :star:2114
* [KlayGE](https://github.com/gongminmin/KlayGE) - a cross-platform open source game engine with plugin-based architecture. [GPLv2] [website](http://www.klayge.org/)
* [OpenXRay](https://github.com/OpenXRay/xray-16) - a community-modified X-Ray engine used in S.T.A.L.K.E.R. game series. [Modified BSD/non-commercial only] :star:1005
* [Oxygine](http://oxygine.org/) - A cross-platform 2D C++ game engine. [MIT]
* [Panda3D](https://github.com/panda3d/panda3d) - A game engine, a framework for 3D rendering and game development for Python and C++ programs. [Modified BSD] [website](https://www.panda3d.org/)
* [PixelGameEngine](https://github.com/OneLoneCoder/olcPixelGameEngine) - The official distribution of olcPixelGameEngine, a tool used in javidx9's YouTube videos and projects. [OLC3] :star:419
* [Polycode](https://github.com/ivansafrin/Polycode) - A cross-platform framework for creative code in C++ (with Lua bindings). [MIT] [website](http://polycode.org/)
* [raylib](https://github.com/raysan5/raylib) - A simple and easy-to-use library to enjoy videogames programming. [zlib/libpng] [website](http://www.raylib.com/)
* [Spring](https://github.com/spring/spring) - A powerful free cross-platform RTS game engine. [GPLv2/GPLv3] [website](https://springrts.com/)
* [Torque2D](https://github.com/GarageGames/Torque2D) - An open-source and cross-platform C++ engine built for 2D game development. [MIT] [website](https://www.garagegames.com/products/torque-2d)
* [Torque3D](https://github.com/GarageGames/Torque3D) - An open-source C++ engine built for 3D game development. [MIT] [website](https://www.garagegames.com/products/torque-3d)
* [toy engine](https://github.com/hugoam/toy) - toy is a thin and modular c++ game engine and offers simple expressive c++ idioms to design full featured 2D or 3D games in fast iterations. :star:1243
* [Urho3D](https://urho3d.github.io/) - A free lightweight, cross-platform 2D and 3D game engine implemented in C++. Greatly inspired by OGRE and Horde3D. [MIT]

## GUI
*Graphic User Interface*

* [Boden](https://github.com/AshampooSystems/boden) - Native, mobile, cross-platform GUI Framework. [GPL/LGPL/Commercial] [website](https://www.boden.io)
* [CEGUI](http://cegui.org.uk/) - Flexible, cross-platform GUI library.
* [FLTK](http://www.fltk.org/index.php) - Fast, light, cross-platform C++ GUI toolkit. [GPL2]
* [GacUI](https://github.com/vczh-libraries/GacUI) - GPU Accelerated C++ User Interface, with WYSIWYG developing tools, XML supports, built-in data binding and MVVM features. [Ms-PL] :star:1632
* [GTK+](http://www.gtk.org/) - A multi-platform toolkit for creating graphical user interfaces. [LGPL]
* [gtkmm](http://www.gtkmm.org/en/) - The official C++ interface for the popular GUI library GTK+. [LGPL]
* [imgui](https://github.com/ocornut/imgui) - Immediate Mode Graphical User Interface with minimal dependencies. [MIT] :star:17141
* [iup](https://www.tecgraf.puc-rio.br/iup) - Multi-platform toolkit for building graphical user interfaces. [MIT]
* [libRocket](http://librocket.com/) - libRocket is a C++ HTML/CSS game interface middleware. [MIT]
* [libui](https://github.com/andlabs/libui) - Simple and portable (but not inflexible) GUI library in C that uses the native GUI technologies of each platform it supports. [MIT] :star:8971
* [MyGUI](http://mygui.info/) - Fast, flexible and simple GUI. [MIT]
* [nana](http://nanapro.org/en-us/) - Nana is a cross-platform library for GUI programming in modern C++ style. [Boost]
* [NanoGui](https://github.com/wjakob/nanogui) - A minimalistic cross-platform widget library for OpenGL 3.x or higher. [BSD] :star:3022
* [nuklear](https://github.com/vurtun/nuklear) - A single-header ANSI C gui library. [PublicDomain] :star:12985
* [QCustomPlot](http://qcustomplot.com/) - Qt plotting widget without further dependencies. [GPLv3]
* [Qwt](http://qwt.sourceforge.net/) - Qt Widgets for Technical Applications. [Own based on LGPL]
* [QwtPlot3D](http://qwtplot3d.sourceforge.net/) - A feature-rich Qt/OpenGL-based C++ programming library, providing essentially a bunch of 3D-widgets. [zlib]
* [Sciter](http://sciter.com/) - Sciter is an embeddable HTML/CSS/scripting engine aimed to be used as an UI layer of modern desktop applications. [Free/Commercial]
* [wxWidgets](http://wxwidgets.org/) - A C++ library that lets developers create applications for Windows, Mac OS X, Linux and other platforms with a single code base. [Own LGPL]
* [Yue](https://github.com/yue/yue) - A library for creating native cross-platform GUI apps. [LGPLv2] :star:2163

## Graphics

* [assimp](https://github.com/assimp/assimp) - Open Asset Import Library (assimp) is a cross-platform 3D model import library which aims to provide a common API for different 3D asset file formats. [BSD-3-Clause] [website](http://www.assimp.org)
* [bgfx](https://github.com/bkaradzic/bgfx) - A cross-platform rendering library. [BSD] :star:6810
* [Blend2D](https://github.com/blend2d/blend2d) - 2D vector graphics engine powered by a JIT compiler. [Zlib] [website](https://blend2d.com/)
* [bs::framework](https://github.com/GameFoundry/bsf) - Modern C++14 library for the development of real-time graphical applications. [MIT] :star:1411
* [Cairo](http://www.cairographics.org/) - A 2D graphics library with support for multiple output devices. [LGPL2 or Mozilla MPL]
* [Diligent Engine](https://github.com/DiligentGraphics/DiligentEngine) - A modern cross-platform low-level 3D graphics library. [Apache2] :star:801
* [DirectXTK](https://github.com/Microsoft/DirectXTK) - A collection of helper classes for writing DirectX 11.x code in C++. [MIT] :star:1323
* [GLFW](https://github.com/glfw/glfw) - A simple, cross-platform OpenGL wrangling library. [zlib/libpng] :star:5510
* [herebedragons](https://github.com/kosua20/herebedragons) - A basic 3D scene implemented with various engines, frameworks or APIs. [MIT] [website](http://simonrodriguez.fr/dragon/)
* [Horde3D](https://github.com/horde3d/Horde3D) - A small 3D rendering and animation engine. [EPL] :star:862
* [Ion](https://github.com/google/ion) - A small and efficient set of libraries for building cross-platform client or server applications that use 3D graphics. [Apache2] [website](https://google.github.io/ion/)
* [Irrlicht](http://irrlicht.sourceforge.net/) - A high performance realtime 3D engine written in C++. [zlib]
* [libigl](https://github.com/libigl/libigl) - Simple C++ geometry processing library. [MPL2] :star:1955
* [LLGL](https://github.com/LukasBanana/LLGL) - Low Level Graphics Library (LLGL) is a thin abstraction layer for the modern graphics APIs. [BSD-3-Clause] :star:613
* [magnum](https://github.com/mosra/magnum) - Lightweight and modular C++11/C++14 graphics middleware for games and data visualization. [MIT] [website](http://magnum.graphics)
* [NanoVG](https://github.com/memononen/nanovg) - Antialiased 2D vector drawing library on top of OpenGL for UI and visualizations. [Zlib] :star:3229
* [Ogre 3D](http://www.ogre3d.org/) :zap: - A scene-oriented, real-time, flexible 3D rendering engine (as opposed to a game engine) written in C++. [MIT]
* [OpenSceneGraph](http://www.openscenegraph.org/) - An open source high performance 3D graphics toolkit. [OSGPL]
* [OpenSubdiv](https://github.com/PixarAnimationStudios/OpenSubdiv) - Pixar's library for evaluating and rendering subdivision surfaces on CPU and GPU. [Modified Apache2] :star:2243
* [OpenVDB](http://www.openvdb.org/) - Library and tools for storing, editing, and rendering volumetric datasets. [MPL2]
* [Panda3D](http://www.panda3d.org/) - A framework for 3D rendering and game development for Python and C++. [BSD]
* [Partio](https://github.com/wdas/partio) - Library for wrangling particle data, with support for most common file formats. [Modified BSD] :star:294
* [Skia](https://github.com/google/skia) - A complete 2D graphic library for drawing Text, Geometries, and Images. [BSD] [webpage](https://sites.google.com/site/skiadocs/home)
* [TinySpline](https://github.com/msteinbeck/tinyspline) - A small, yet powerful ANSI C library for interpolating, transforming, and querying arbitrary NURBS, B-Splines, and Bézier curves. [MIT] :star:461
* [urho3d](https://github.com/urho3d/Urho3D) - Cross-platform rendering and game engine. [Many different, mostly MIT] :star:2916
* [Yocto/GL](https://github.com/xelatihy/yocto-gl) - Tiny C++ Libraries for Data-Driven Physically-based Graphics. [MIT] :star:876

## Image Processing

* [Boost.GIL](http://www.boost.org/doc/libs/1_56_0/libs/gil/doc/index.html) - Generic Image Library.
* [CImg](http://cimg.eu/) - A small, open source, C++ toolkit for image processing. [Own LGPL or GPL]
* [CxImage](https://www.codeproject.com/Articles/1300/CxImage) - An image processing and conversion library to load, save, display, transform BMP, JPEG, GIF, PNG, TIFF, MNG, ICO, PCX, TGA, WMF, WBMP, JBG, J2K images. [zlib]
* [Dlib](https://github.com/davisking/dlib) :zap: - A modern C++11 machine learning, computer vision, numerical optimization, and deep learning toolkit. [Boost] [website](http://dlib.net/)
* [FreeImage](http://freeimage.sourceforge.net/) - An open source library that supports popular graphics image formats and others as needed by today's multimedia applications. [GPL2 or GPL3]
* [GD](https://github.com/libgd/libgd) - GD Graphics Library, famously used in PHP for image loading/manipulation & thumbnail generation. [custom permissive license, requires mention in user docs] [website](http://libgd.github.io/)
* [DCMTK](http://dicom.offis.de/dcmtk.php.en) - DICOM Toolkit.
* [GDCM](http://gdcm.sourceforge.net/wiki/index.php/Main_Page) - Grassroots DICOM library.
* [ITK](http://www.itk.org/) - An open-source, cross-platform system for image analysis. [Apache2 from ITK 4.0]
* [Leptonica](https://github.com/DanBloomberg/leptonica) - Leptonica is an open source library containing software that is broadly useful for image processing and image analysis applications. [BSD-2-Clause] [website](http://leptonica.org/index.html)
* [libfacedetection](https://github.com/ShiqiYu/libfacedetection) - Open source library for face detection in images. The face detection speed can reach 1500FPS. [BSD] :star:7520
* [libjpeg-turbo](https://github.com/libjpeg-turbo/libjpeg-turbo) - A JPEG image codec that uses SIMD instructions to accelerate baseline JPEG encoding and decoding. [IJG & BSD-3-Clause & zlib] [website](https://libjpeg-turbo.org/)
* [libvips](https://github.com/jcupitt/libvips) - A fast image processing library with low memory needs. [LGPL] [website](http://www.vips.ecs.soton.ac.uk/)
* [Magick++](http://www.imagemagick.org/script/api.php) - ImageMagick program interfaces for C++. [Apache2]
* [MagickWnd](http://www.imagemagick.org/script/api.php) - ImageMagick program interfaces for C. [Apache2]
* [OpenCV](http://opencv.org/) :zap: - Open source computer vision. [BSD]
* [OpenEXR](http://www.openexr.com/) - Cross-platform library for high dynamic range imaging. [Modified BSDF]
* [OpenImageIO](https://github.com/OpenImageIO/oiio) - Powerful image and texture wrangling library with support for a wide number of common lossy and RAW formats. [Modified BSD] :star:976
* [Simd](https://github.com/ermig1979/Simd) - C++ image processing library with using of SIMD: SSE, SSE2, SSE3, SSSE3, SSE4.1, SSE4.2, AVX, AVX2, AVX-512, VMX(Altivec) and VSX(Power7), NEON for ARM. [MIT] :star:850
* [stb-image](https://github.com/nothings/stb/blob/master/stb_image.h) - STB single-header image loading library. [Public Domain] :star:10886
* [tesseract-ocr](https://github.com/tesseract-ocr) - An OCR engine. [Apache2]
* [TinyEXIF](https://github.com/cdcseacave/TinyEXIF) - Tiny ISO-compliant C++ EXIF and XMP parsing library for JPEG. [MIT] :star:32
* [Video++](https://github.com/matt-42/vpp) - A C++14 high performance video and image processing library. [MIT] :star:585
* [VIGRA](https://github.com/ukoethe/vigra) - A generic C++ computer vision library for image analysis. [MIT X11] :star:307
* [VTK](http://www.vtk.org/) - Open-source, freely available software system for 3D computer graphics, image processing and visualization. [BSD]

## Internationalization

* [gettext](http://www.gnu.org/software/gettext/) - GNU 'gettext'. [GPL2]
* [IBM ICU](http://site.icu-project.org/) - A set of C/C++ and Java libraries providing Unicode and Globalization support. [ICU]
* [libiconv](http://www.gnu.org/software/libiconv/) - An encoding conversion library between different character encodings. [GPL]
* [utf8.h](https://github.com/sheredom/utf8.h) - Single header utf8 string functions for C and C++. [Unlicense] :star:597
* [utf8proc](https://github.com/JuliaStrings/utf8proc) - A clean C library for processing UTF-8 Unicode data. [MIT] :star:466

## Inter-process communication

* [Apache Thrift](https://thrift.apache.org/) - Efficient cross-language IPC/RPC, works between C++, Java, Python, PHP, C#, and many more other languages. Originally developed by Facebook. [Apache2]
* [Cap'n Proto](https://github.com/capnproto/capnproto) - Fast data interchange format and capability-based RPC system. [MIT] [website](https://capnproto.org/)
* [gRPC](https://github.com/grpc/grpc) - A high performance, open source, general-purpose RPC framework. [BSD] [website](http://www.grpc.io/)
* [Ice](https://github.com/zeroc-ice/ice) - Comprehensive RPC framework with support for C++, C#, Java, JavaScript, Python and more. [GPLv2] :star:1414
* [libjson-rpc-cpp](https://github.com/cinemast/libjson-rpc-cpp) - JSON-RPC framework for C++ servers and clients. [MIT] :star:548
* [nanomsg](https://github.com/nanomsg/nanomsg) - A simple high-performance implementation of several "scalability protocols". [MIT] [website](http://nanomsg.org/)
* [nng](https://github.com/nanomsg/nng) - nanomsg-next-generation, a light-weight brokerless messaging library. [MIT] [website](https://nanomsg.github.io/nng/)
* [rpclib](https://github.com/rpclib/rpclib) - A modern C++ msgpack-RPC server and client library. [MIT] :star:718
* [simple-rpc-cpp](https://github.com/pearu/simple-rpc-cpp) - A simple RPC wrapper generator to C/C++ functions. [BSD] :star:18
* [WAMP](http://wamp.ws/) - Provides RPC and pub/sub messaging patterns. (various implementations, various languages)
* [xmlrpc-c](http://xmlrpc-c.sourceforge.net/) - A lightweight RPC library based on XML and HTTP. [BSD]

## JSON

* [Boost.PropertyTree](http://www.boost.org/doc/libs/1_55_0/doc/html/property_tree.html) - A property tree parser/generator that can be used to parse XML/JSON/INI/Info files. [Boost]
* [cJSON](https://github.com/DaveGamble/cJSON) - Ultralightweight JSON parser in ANSI C. [MIT] :star:3473
* [frozen](https://github.com/cesanta/frozen) - JSON parser and generator for C/C++. [GPL & GPL2] :star:384
* [Jansson](https://github.com/akheron/jansson) - C library for encoding, decoding and manipulating JSON data. [MIT] :star:2043
* [jbson](https://github.com/chrismanning/jbson) - jbson is a library for building & iterating BSON data, and JSON documents in C++14. [Boost] :star:30
* [JeayeSON](https://github.com/jeaye/jeayeson) - A very sane (header only) C++ JSON library. [BSD] :star:108
* [Jsmn](https://github.com/zserge/jsmn) - A minimalistic JSON parser in C. [MIT] :star:1726
* [json](https://github.com/nlohmann/json) :zap: - JSON for Modern C++. [MIT]
* [JSON++](https://github.com/hjiang/jsonxx) - A JSON parser in C++. [MIT] :star:335
* [json.h](https://github.com/sheredom/json.h) - A simple one header/one source solution to parsing JSON in C and C++. [Unlicense] :star:228
* [json-c](https://github.com/json-c/json-c) - A JSON implementation in C. [MIT] :star:1669
* [JsonCpp](https://github.com/open-source-parsers/jsoncpp) - A C++ library for interacting with JSON. [MIT] :star:4075
* [json-parser](https://github.com/udp/json-parser) - Very low footprint JSON parser written in portable ANSI C. [BSD] :star:945
* [json11](https://github.com/dropbox/json11) - A tiny JSON library for C++11. [MIT] :star:1914
* [json-voorhees](https://github.com/tgockel/json-voorhees) - JSON library for C++. Support for C++11. No dependencies, fast and dev-friendly. [Apache2] :star:117
* [jute](https://github.com/amir-s/jute) - Very simple C++ JSON Parser. [PublicDomain] :star:24
* [libjson](https://github.com/vincenthz/libjson) - A JSON parser and printer library in C. easy to integrate with any model. [LGPL] :star:208
* [libjson](http://sourceforge.net/projects/libjson/) - Lightweight JSON library. [?]
* [LIBUCL](https://github.com/vstakhov/libucl) :zap: - Universal configuration library parser [BSD-2-Clause]
* [parson](https://github.com/kgabis/parson) - Parson is a lighweight json library written in C. [MIT] :star:794
* [PicoJSON](https://github.com/kazuho/picojson) - A header-file-only, JSON parser serializer in C++. [BSD] :star:803
* [qt-json](https://github.com/gaudecker/qt-json) - A simple class for parsing JSON data into a QVariant hierarchy and vice versa. [GPLv3] :star:248
* [QJson](https://github.com/flavio/qjson) - A qt-based library that maps JSON data to QVariant objects. [LGPL2] :star:221
* [RapidJSON](https://github.com/miloyip/rapidjson) :zap: - A fast JSON parser/generator for C++ with both SAX/DOM style API. [MIT]
* [sajson](https://github.com/chadaustin/sajson) - Lightweight, extremely high-performance JSON parser for C++11. [MIT] :star:430
* [simdjson](https://github.com/lemire/simdjson) - Extremely fast JSON library that can parse gigabytes of JSON per second. [Apache-2.0] :star:7493
* [taoJSON](https://github.com/taocpp/json) - Zero-dependency C++ header-only JSON library. [MIT] :star:239
* [ujson](https://bitbucket.org/awangk/ujson) - µjson is a a small, C++11, UTF-8, JSON library. [MIT]
* [YAJL](https://github.com/lloyd/yajl) - A fast streaming JSON parsing library in C. [ISC] :star:1891

## Logging

* [Blackhole](https://github.com/3Hren/blackhole) - Attribute-based logging framework, which is designed to be fast, modular and highly customizable. [MIT] :star:152
* [Boost.Log](http://www.boost.org/doc/libs/1_56_0/libs/log/doc/html/index.html) - Designed to be very modular and extensible. [Boost]
* [Easylogging++](https://github.com/easylogging/easyloggingpp) - Extremely light-weight high performance logging library for C++11 (or higher) applications. [MIT] [website](https://muflihun.github.io/easyloggingpp)
* [G3log](https://github.com/KjellKod/g3log) - Asynchronous logger with Dynamic Sinks. [PublicDomain] :star:519
* [glog](https://github.com/google/glog) - C++ implementation of the Google logging module. :star:3323
* [Log4cpp](http://log4cpp.sourceforge.net/) - A library of C++ classes for flexible logging to files, syslog, IDSA and other destinations. [LGPL]
* [log4cplus](https://github.com/log4cplus/log4cplus) - A simple to use C++ logging API providing thread-safe, flexible, and arbitrarily granular control over log management and configuration. [BSD & Apache2] :star:816
* [loguru](https://github.com/emilk/loguru) - A lightweight C++ logging library. [PublicDomain] :star:741
* [plog](https://github.com/SergiusTheBest/plog) - Portable and simple log for C++ in less than 1000 lines of code. [MPL2] :star:749
* [reckless](https://github.com/mattiasflodin/reckless) - Low-latency, high-throughput, asynchronous logging library for C++. [MIT] :star:282
* [spdlog](https://github.com/gabime/spdlog) - Super fast, header only, C++ logging library. :star:6849
* [templog](http://www.templog.org/) - A very small and lightweight C++ library which you can use to add logging to your C++ applications. [Boost]
* [P7Baical](http://baical.net/p7.html) - An open source and cross-platform library for high-speed sending telemetry & trace data  with minimal usage of CPU and memory. [LGPL]

## Machine Learning

* [Caffe](https://github.com/BVLC/caffe) - A fast framework for neural networks. [BSD] :star:29229
* [CCV](https://github.com/liuliu/ccv) - C-based/Cached/Core Computer Vision Library, A Modern Computer Vision Library. [BSD] :star:6555
* [darknet](https://github.com/pjreddie/darknet) - Open source neural network framework written in C and CUDA. [PublicDomain] [website](https://pjreddie.com/darknet/)
* [Dlib](https://github.com/davisking/dlib) :zap: - A modern C++11 machine learning, computer vision, numerical optimization, and deep learning toolkit. [Boost] [website](http://dlib.net/)
* [Fido](https://github.com/FidoProject/Fido) - A highly-modular C++ machine learning library for embedded electronics and robotics. [MIT] [website](http://fidoproject.github.io/)
* [flashlight](https://github.com/facebookresearch/flashlight) - A fast, flexible machine learning library from Facebook AI Research written entirely in C++ and based on the ArrayFire tensor library. [BSD-3-Clause] [website](https://fl.readthedocs.io/en/latest/)
* [libsvm](https://github.com/cjlin1/libsvm) - A simple, easy-to-use, efficient library for Support Vector Machines. [BSD-3-Clause] [website](https://www.csie.ntu.edu.tw/~cjlin/libsvm/)
* [MeTA](https://github.com/meta-toolkit/meta) - A modern C++ data sciences toolkit. [MIT] [website](https://meta-toolkit.org/)
* [Minerva](https://github.com/dmlc/minerva) - A fast and flexible system for deep learning. [Apache2] :star:670
* [mlpack](https://github.com/mlpack/mlpack) - A scalable c++ machine learning library. [LGPLv3] [website](http://www.mlpack.org/)
* [OpenCV](https://github.com/Itseez/opencv) :zap: - Open Source Computer Vision Library. [BSD] [website](http://opencv.org/)
* [Recommender](https://github.com/GHamrouni/Recommender) - C library for product recommendations/suggestions using collaborative filtering (CF). [BSD] :star:215
* [RNNLIB](https://github.com/szcom/rnnlib) - RNNLIB is a recurrent neural network library for sequence learning problems. [GPLv3] :star:773
* [SHOGUN](https://github.com/shogun-toolbox/shogun) - The Shogun Machine Learning Toolbox. [GPLv3] :star:2525
* [sofia-ml](https://code.google.com/p/sofia-ml/) - The suite of fast incremental algorithms for machine learning. [Apache2]
* [VLFeat](https://github.com/vlfeat/vlfeat) - The VLFeat open source library implements popular computer vision algorithms specialising in image understanding and local featurexs extraction and matching. [BSD-2-Clause] [website](http://www.vlfeat.org/)
* [xgboost](https://github.com/dmlc/xgboost) - Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or GBM) Library, for Python, R, Java, Scala, C++ and more. Runs on single machine, Hadoop, Spark, Flink and DataFlow. [Apache2] :star:17407

## Math

* [Apophenia](https://github.com/b-k/apophenia) - A C library for statistical and scientific computing [GPL2] :star:158
* [Armadillo](https://gitlab.com/conradsnicta/armadillo-code) - Fast C++ library for linear algebra & scientific computing. [Apache2] [website](http://arma.sourceforge.net/)
* [blaze](https://bitbucket.org/blaze-lib/blaze) - high-performance C++ math library for dense and sparse arithmetic. [BSD]
* [Boost.Multiprecision](http://www.boost.org/doc/libs/master/libs/multiprecision/doc/html/index.html) - provides higher-range/precision integer, rational and floating-point types in C++, header-only or with GMP/MPFR/LibTomMath backends. [Boost]
* [ceres-solver](http://ceres-solver.org/) - C++ library for modeling and solving large complicated nonlinear least squares problems from google. [BSD]
* [CGAL](https://github.com/CGAL/cgal) - Collection of efficient and reliable geometric algorithms. [LGPL&GPL] [website](http://www.cgal.org/)
* [cml](http://cmldev.net/) - free C++ math library for games and graphics. [Boost]
* [Dlib](https://github.com/davisking/dlib) :zap: - A modern C++11 machine learning, computer vision, numerical optimization, and deep learning toolkit. [Boost] [website](http://dlib.net/)
* [Eigen](http://eigen.tuxfamily.org/) - A high-level C++ library of template headers for linear algebra, matrix and vector operations, numerical solvers and related algorithms. [MPL2]
* [ExprTK](http://www.partow.net/programming/exprtk/) - The C++ Mathematical Expression Toolkit Library (ExprTk) is a simple to use, easy to integrate and extremely efficient run-time mathematical expression parser and evaluation engine. [MIT]
* [Geometric Tools](https://www.geometrictools.com) - C++ library for computing in the fields of mathematics, graphics, image analysis and physics. [Boost] [website](https://www.geometrictools.com)
* [GLM](https://github.com/g-truc/glm) - Header-only C++ math library that matches and inter-operates with OpenGL's GLSL math. [MIT] [website](https://glm.g-truc.net/)
* [GMTL](http://ggt.sourceforge.net/) - Graphics Math Template Library is a collection of tools implementing Graphics primitives in generalized ways. [GPL2]
* [GMP](https://gmplib.org/) - A C library for arbitrary precision arithmetic, operating on signed integers, rational numbers, and floating-point numbers. [LGPL3 & GPL2]
* [linalg.h](https://github.com/sgorsten/linalg) - Single header, public domain, short vector math library for C++. [Unlicense] :star:439
* [MIRACL](https://github.com/CertiVox/MIRACL) - A Multiprecision Integer and Rational Arithmetic Cryptographic Library. [AGPL] :star:299
* [muparser](http://beltoforion.de/article.php?a=muparser) - muParser is an extensible high performance math expression parser library written in C++. [MIT]
* [LibTomMath](https://github.com/libtom/libtommath) - A free open source portable number theoretic multiple-precision integer library written entirely in C. [PublicDomain & WTFPL] [website](http://www.libtom.net/)
* [linmath.h](https://github.com/datenwolf/linmath.h) - A lean linear math library, aimed at graphics programming. [WTFPL] :star:439
* [lp_solve](https://sourceforge.net/projects/lpsolve) - A library used to formulate and solve linear programming problems. [LGPL] [website](http://lpsolve.sourceforge.net)
* [OpenBLAS](https://github.com/xianyi/OpenBLAS) - An optimized BLAS library based on GotoBLAS2 1.13 BSD version. [BSD 3-clause] [website](http://www.openblas.net/)
* [QuantLib](https://github.com/lballabio/quantlib) - A free/open-source library for quantitative finance. [Modified BSD] [website](http://quantlib.org/)
* [StatsLib](https://github.com/kthohr/stats) - A C++ header-only library of statistical distribution functions. [Apache2] [website](https://www.kthohr.com/statslib.html)
* [SymEngine](https://github.com/symengine/symengine) - Fast symbolic manipulation library, a rewriting of SymPy's core in C++. [MIT] :star:499
* [TinyExpr](https://github.com/codeplea/tinyexpr) - A C library for parsing and evaluating math expressions from strings. [zlib] :star:580
* [Vc](https://github.com/VcDevel/Vc) - SIMD Vector Classes for C++. [BSD] :star:760
* [Versor](http://versor.mat.ucsb.edu/) - A (fast) Generic C++ library for Geometric Algebras, including Euclidean, Projective, Conformal, Spacetime (etc).
* [Wykobi](http://www.wykobi.com/) - A C++ library of efficient, robust and simple to use C++ 2D/3D oriented computational geometry routines. [MIT]
* [xtensor](https://github.com/QuantStack/xtensor) - A C++14 library for numerical analysis with multi-dimensional array expressions, inspired by NumPy syntax. [BSD 3-clause] [website](http://quantstack.net/xtensor)
* [universal](https://github.com/stillwater-sc/universal) - A C++14 header-only library implementing arbitrary posit arithmetic. The posit number system is a tapered floating point that is more efficient than IEEE floating point. Posits enable reproducible computational science. [MIT license] [website](http://www.stillwater-sc.com/assets/content/stillwater-universal-sw.html)

## Memory Allocation

* [Boehm GC](https://github.com/ivmai/bdwgc) - Conservative garbage collector for C and C++. [similar to X11] [website](http://www.hboehm.info/gc/)
* [C Smart Pointers](https://github.com/Snaipe/libcsptr) - Smart pointers for the (GNU) C programming language. [MIT] :star:868
* [Hoard](https://github.com/emeryberger/Hoard) - Fast, Scalable, and Memory-efficient Malloc for Linux, Windows, and Mac. [GPL, commercial] [website](http://hoard.org/)
* [jemalloc](https://github.com/jemalloc/jemalloc) - General purpose malloc(3) implementation that emphasizes fragmentation avoidance and scalable concurrency support. [BSD] [website](http://jemalloc.net/)
* [memory](https://github.com/foonathan/memory) - STL compatible C++ memory allocator library. [ZLib] :star:626
* [memory-allocators](https://github.com/mtrebi/memory-allocators) - Custom memory allocators to improve the performance of dynamic memory allocation. [MIT] :star:558
* [mimalloc](https://github.com/microsoft/mimalloc) - A compact general purpose allocator with excellent performance. [MIT] :star:3394
* [tgc](https://github.com/orangeduck/tgc) - A tiny garbage collector for C written in \~500 LOC. [BSD] :star:367

## Multimedia

* [GStreamer](http://gstreamer.freedesktop.org/) - A library for constructing graphs of media-handling components. [LGPL]
* [libass](https://github.com/libass/libass) - Portable subtitle renderer for the ASS/SSA subtitle format. [ISC]  :star:369
* [libav](https://github.com/libav/libav) - A collection of libraries and tools to process multimedia content such as audio, video, subtitles and related metadata. [LGPL v2.1+ and others] [website](https://www.libav.org/)
* [LIVE555 Streaming Media](http://www.live555.com/liveMedia/) - Multimedia streaming library using open standard protocols (RTP/RTCP, RTSP, SIP). [LGPL]
* [libVLC](https://wiki.videolan.org/LibVLC) - libVLC (VLC SDK) media framework. [GPL]
* [MediaInfoLib](https://github.com/MediaArea/MediaInfoLib) - Convenient unified display of the most relevant technical and tag data for video and audio files. [BSD] :star:208
* [QtAv](https://github.com/wang-bin/QtAV) - A multimedia playback framework based on Qt and FFmpeg to write a player easily. [LGPL] [website](http://wang-bin.github.io/QtAV/)
* [SDL](http://www.libsdl.org/) :zap: - Simple DirectMedia Layer. [zlib]
* [SFML](https://github.com/SFML/SFML) :zap: - Simple and Fast Multimedia Library. [zlib] [website](http://www.sfml-dev.org/)
* [TagLib](https://github.com/taglib/taglib) - A library for reading and editing the metadata of several popular audio formats. [LGPL/MPL] [website](https://taglib.org/)

## Networking

* [ACE](http://www.dre.vanderbilt.edu/~schmidt/ACE.html) - An OO Network Programming Toolkit in C++. [?MIT?]
* [Boost.Asio](http://think-async.com/) :zap: - A cross-platform C++ library for network and low-level I/O programming. [Boost]
* [Boost.Beast](https://github.com/boostorg/beast) :zap: - HTTP and WebSocket built on Boost.Asio in C++11. [BSL-1.0] [website](www.boost.org/libs/beast)
* [Breep](https://github.com/Organic-Code/Breep) - Event based, high-level C++14 peer-to-peer library. [EUPL-1.1 (OSI approved)] :star:66
* [C++ REST SDK](https://github.com/Microsoft/cpprestsdk) - C++ REST SDK (previously named Casablanca). [Apache2] :star:4513
* [Restbed](https://github.com/corvusoft/restbed) - C++11 Asynchronous RESTful framework. [AGPL] :star:1085
* [Restinio](https://github.com/Stiffstream/restinio) - A header-only C++14 library that gives you an embedded HTTP/Websocket server. [BSD] :star:294
* [c-ares](https://github.com/c-ares/c-ares) - A C library for asynchronous DNS requests. [MIT] :star:928
* [cpp-httplib](https://github.com/yhirose/cpp-httplib) - A single file C++11 header-only HTTP/HTTPS sever library. [MIT] :star:1308
* [cpp-netlib](http://cpp-netlib.org/) - A collection of open-source libraries for high level network programming. [Boost]
* [cpp-netlib/uri](https://github.com/cpp-netlib/uri) - URI parser/builder library for C++, compatible with RFC 3986 and RFC 3987. [BSL-1.0] :star:96
* [cpr](https://github.com/whoshuu/cpr) - A modern C++ HTTP requests library with a simple but powerful interface. Modeled after the Python Requests module. [MIT] [website](https://whoshuu.github.io/cpr/)
* [curlcpp](https://github.com/JosephP91/curlcpp) - An object oriented C++ wrapper for CURL(libcurl). [MIT] :star:394
* [DPDK](https://github.com/DPDK/dpdk) - Data Plane Development Kit, libraries and drivers for fast packet processing. [BSD-3-Clause & GPL-2.0] [website](https://www.dpdk.org/)
* [Dyad.c](https://github.com/rxi/dyad) - Asynchronous networking for C. [MIT] :star:1131
* [ENet](https://github.com/lsalzman/enet) - Reliable UDP networking library. [MIT] [website](http://enet.bespin.org/)
* [evpp](https://github.com/Qihoo360/evpp) - C++ high performance networking with TCP/UDP/HTTP protocols. [BSD] :star:1952
* [H2O](https://github.com/h2o/h2o) - An optimized HTTP server with support for HTTP/1.x and HTTP/2. It can also be used as a library. [MIT] :star:8707
* [HTTP Parser](https://github.com/nodejs/http-parser) :zap: - A http request/response parser for C. [MIT]
* [KCP](https://github.com/skywind3000/kcp/blob/master/README.en.md) - A fast and reliable ARQ protocol that helps applications to reduce network latency. [MIT] :star:7053
* [libcurl](http://curl.haxx.se/libcurl/) - Multiprotocol file transfer library. [MIT/X derivate license]
* [libhttpserver](https://github.com/etr/libhttpserver) - C++ library for creating an embedded Rest HTTP server (and more). [LGPL2.1] :star:300
* [Libmicrohttpd](http://www.gnu.org/software/libmicrohttpd/) - GNU libmicrohttpd is a small C library that is supposed to make it easy to run an HTTP server as part of another application. [LGPL v2.1+]
* [libpcap](https://github.com/the-tcpdump-group/libpcap) - A portable C/C++ library for network traffic capture. [BSD] [website](https://www.tcpdump.org/)
* [libquic](https://github.com/devsisters/libquic) - A QUIC protocol library extracted from Chromium's QUIC Implementation. [BSD] :star:1253
* [librdkafka](https://github.com/edenhill/librdkafka) - Apache Kafka client library for C and C++. [BSD-2-Clause] :star:3593
* [libwebsockets](https://github.com/warmcat/libwebsockets) - A lightweight pure C WebSocket implementation that provides both client and server libraries. [LGPL2.1 + static link exception] [website](https://libwebsockets.org/)
* [lwIP](http://savannah.nongnu.org/projects/lwip/) - A lightweight TCP/IP stack. [Modified BSD]
* [Mongoose](https://github.com/cesanta/mongoose) - Extremely lightweight webserver. [GPL2] :star:5755
* [MQTT-C](https://github.com/LiamBindle/MQTT-C) - A portable MQTT C client for embedded systems and PCs alike. [MIT] [website](https://liambindle.ca/MQTT-C)
* [mTCP](https://github.com/mtcp-stack/mtcp) - Highly scalable user-level TCP stack for multicore systems. [Modified BSD] :star:1373
* [Muduo](https://github.com/chenshuo/muduo) - A C++ non-blocking network library for multi-threaded server in Linux. [BSD] :star:6516
* [nghttp2](https://github.com/nghttp2/nghttp2) - HTTP/2 C Library. [MIT] [website](https://nghttp2.org/)
* [Onion](https://github.com/davidmoreno/onion) - HTTP server library in C designed to be lightweight and easy to use. [Apache2/GPL2] :star:1571
* [PF_RING™](https://github.com/ntop/PF_RING) - High-speed packet processing framework. [LGPL-2.1] [website](https://www.ntop.org/products/packet-capture/pf_ring/)
* [PicoHTTPParser](https://github.com/h2o/picohttpparser) - A tiny, primitive, fast HTTP request/response parser. [MIT] :star:1132
* [POCO](https://github.com/pocoproject) :zap: - C++ class libraries and frameworks for building network- and internet-based applications that run on desktop, server, mobile and embedded systems. [Boost] [website](http://pocoproject.org/)
* [Proxygen](https://github.com/facebook/proxygen) - Facebook's collection of C++ HTTP libraries including an easy to use HTTP server. [BSD] :star:6366
* [RakNet](https://github.com/OculusVR/RakNet) - A cross platform, open source, C++ networking engine for game programmers. [BSD] :star:2706
* [restclient-cpp](https://github.com/mrtazz/restclient-cpp) - Simple REST client for C++. It wraps libcurl for HTTP requests. [MIT] :star:985
* [Seasocks](https://github.com/mattgodbolt/seasocks) - Simple, small, C++ embeddable webserver with WebSockets support. [BSD] :star:410
* [Silicon](http://siliconframework.org) - A high performance, middleware oriented C++14 http web framework. [MIT]
* [Tufão](https://github.com/vinipsmaker/tufao) - An asynchronous web framework for C++ built on top of Qt. [LGPL2] :star:453
* [uriparser](https://github.com/uriparser/uriparser) - Strictly RFC 3986 compliant URI parsing and handling library. [BSD-3-Clause] :star:111
* [uWebSockets](https://github.com/uNetworking/uWebSockets) - µWS is one of the most lightweight, efficient & scalable WebSocket & HTTP server implementations available. [Zlib] :star:10926
* [WAFer](https://github.com/riolet/WAFer) - A C language-based ultra-light software platform for scalable server-side and networking applications. Think node.js for C programmers. [GPL2] :star:673
* [Wangle](https://github.com/facebook/wangle) - A client/server application framework to build asynchronous, event-driven modern C++ services. [Apache-2.0] :star:2362
* [wdt](https://github.com/facebook/wdt) - An embeddedable library (and command line tool) aiming to transfer data between 2 systems as fast as possible over multiple TCP paths. [BSD-3-Clause] :star:2372
* [WebSocket++](https://github.com/zaphoyd/websocketpp) - C++/Boost Asio based websocket client/server library. [BSD] :star:3362
* [PcapPlusPlus](https://github.com/seladb/PcapPlusPlus) - a multiplatform C++ network sniffing and packet parsing and crafting framework. [Unlicense] :star:790
* [ZeroMQ](https://github.com/zeromq/libzmq) - High-speed, modular asynchronous communication library. [LGPL] [website](http://zeromq.org/)

## PDF
*Libraries for parsing and manipulating PDF documents.*

* [libharu](https://github.com/libharu/libharu) - A free, cross platform, open-sourced software library for generating PDF. [zlib] :star:922
* [MuPDF](https://mupdf.com/) - A lightweight PDF, XPS, and E-book viewer. [AGPL/Commercial]
* [PoDoFo](http://podofo.sourceforge.net/) - A library to work with the PDF file format. [LGPL]
* [Poppler](https://poppler.freedesktop.org/) - Open-source multi-backend PDF rendering library based on the xpdf-3.0 code base. [GPLv2/GPLv3]
* [Xpdf](https://www.xpdfreader.com/) - Xpdf is a free PDF viewer and toolkit, including a text extractor, image converter, HTML converter, and more. [GPL v2/GPL v3]
* [DynaPDF](http://www.dynaforms.com/) - An easy-to-use PDF generation library. [Commercial]

## Physics
*Dynamics simulation engines*

* [Box2D](https://github.com/erincatto/Box2D) - A 2D physics engine for games. [BSD-like] :star:3569
* [Bullet](https://github.com/bulletphysics/bullet3) - A 3D physics engine for games. [zlib] [website](http://bulletphysics.org)
* [Chipmunk](https://github.com/slembcke/Chipmunk2D) - A fast and lightweight 2D game physics library. [MIT] [website](https://chipmunk-physics.net/)
* [LiquidFun](https://github.com/google/liquidfun) - A 2D physics engine for games. [BSD-like] :star:3795
* [Newton Dynamics](https://github.com/MADEAPPS/newton-dynamics) - An integrated solution for real time simulation of physics environments. [zlib] :star:513
* [ODE](http://www.ode.org/) - Open Dynamics Engine - An open source, high performance library for simulating rigid body dynamics. [BSD&LGPL]
* [ofxBox2d](https://github.com/vanderlin/ofxBox2d) - openFrameworks wrapper for Box2D. [BSD-like] :star:275
* [PhysX](https://github.com/NVIDIAGameWorks/PhysX-3.4) - An open-source realtime physics engine middleware SDK developed by Nvidia as a part of Nvidia GameWorks software suite. [BSD-3-Clause]  :star:2110
* [Project Chrono](https://github.com/projectchrono/chrono) - An open source multi-physics simulation engine. [BSD-3-Clause] [website](https://projectchrono.org/)
* [Simbody](https://github.com/simbody/simbody) - High-performance C++ multibody dynamics/physics library for simulating articulated biomechanical and mechanical systems like vehicles, robots, and the human skeleton. [Apache2] :star:1415
* [Quantum++](https://github.com/vsoftco/qpp) - A modern C++11 quantum computing library. [MIT] :star:171

## Reflection

* [Better Enums](https://github.com/aantron/better-enums) - Reflective enums (to string, iteration). Single header. [BSD] [website](http://aantron.github.io/better-enums/)
* [clReflect](https://bitbucket.org/dwilliamson/clreflect) - C++ Reflection using clang. [MIT]
* [CPFG](https://github.com/cpgf/cpgf) - A C++03 library for reflection, callback and script binding. [Apache2] [website](http://www.cpgf.org/)
* [CPP-Reflection](https://github.com/AustinBrunkhorst/CPP-Reflection) - C++ Reflection using clang. [MIT] :star:384
* [Magic Enum](https://github.com/Neargye/magic_enum) - Header-only C++17 library provides static reflection for enums (to string, from string, iteration), work with any enum type without any macro or boilerplate code. [MIT] :star:536
* [magic_get](https://github.com/apolukhin/magic_get) - std::tuple like methods for user defined types without any macro or boilerplate code. [Boost] :star:646
* [meta](https://github.com/skypjack/meta) - Header-only, non-intrusive and macro-free runtime reflection system in C++. [MIT] :star:186
* [Nameof](https://github.com/Neargye/nameof) - Header-only C++17 library provides nameof macros and functions to obtain the simple name of variable, type, function, macro, and enum. [MIT] :star:521
* [Ponder](https://github.com/billyquith/ponder) - A C++11 library for reflection. [MIT] :star:339
* [RTTR](https://github.com/rttrorg/rttr) - A C++11 library for reflection. [MIT] [website](http://www.rttr.org)
* [visit_struct](https://github.com/cbeck88/visit_struct) - A miniature library for struct-field reflection in C++. [BSL-1.0] :star:182

## Regular Expression

* [CppVerbalExpressions](https://github.com/VerbalExpressions/CppVerbalExpressions) - C++ regular expressions made easy. [MIT] :star:303
* [CTRE](https://github.com/hanickadot/compile-time-regular-expressions) - A Compile time PCRE (almost) compatible regular expression matcher. [MIT] :star:865
* [Hyperscan](https://github.com/intel/hyperscan) - Hyperscan is a high-performance multiple regex matching library by Intel. Provides simultaneous matching of large numbers of regexps (up to tens of thousands). Typically used in a DPI library stack. [BSD] :star:2167
* [Oniguruma](https://github.com/kkos/oniguruma) - A modern and flexible regular expressions library that supports a variety of character encodings. [BSD] :star:938
* [PCRE](http://pcre.org/) - A regular expression C library inspired by the regular expression capabilities in Perl. [BSD]
* [PIRE](https://github.com/yandex/pire) - Perl Incompatible Regular Expressions library by Yandex. Can be really fast (more than 400 MB/s). [LPGL v3.0] :star:289
* [RE2](https://github.com/google/re2) - A software library for regular expressions via a finite-state machine using automata theory. [BSD-3-Clause] :star:4100
* [SLRE](https://github.com/cesanta/slre) - Super Light Regexp engine for C/C++. [GPLv2/Commercial] :star:443
* [sregex](https://github.com/openresty/sregex) - A non-backtracking NFA/DFA-based Perl-compatible regex engine library for matching on large data streams. [BSD] :star:509

## Robotics

* [MOOS-IvP](http://moos-ivp.org) - A set of open source C++ modules for providing autonomy on robotic platforms, in particular autonomous marine vehicles.
* [MRPT](http://www.mrpt.org/) - Mobile Robot Programming Toolkit. [BSD]
* [PCL](https://github.com/PointCloudLibrary/pcl) - Point Cloud Library is a standalone, large scale, open project for 2D/3D image and point cloud processing [BSD] [website](http://www.pointclouds.org/)
* [Robotics Library (RL)](http://www.roboticslibrary.org/) - A self-contained C++ library for robot kinematics, motion planning and control. [BSD]
* [RobWork](https://gitlab.com/sdurobotics/RobWork) - A collection of C++ libraries for simulation and control of robot systems. [Apache2] [website](http://www.robwork.dk/)
* [ROS](http://wiki.ros.org/) - Robot Operating System provides libraries and tools to help software developers create robot applications. [BSD]

## Scientific Computing

* [AMGCL](https://github.com/ddemidov/amgcl) - a header-only C++ library for solving large sparse linear systems with algebraic multigrid. [MIT] :star:257
* [FFTW](http://www.fftw.org/) - A C library for computing the DFT in one or more dimensions. [GPL]
* [GSL](http://www.gnu.org/software/gsl/) - GNU scientific library. [GPL]
* [TileDB](https://github.com/TileDB-Inc/TileDB) - Fast Dense and Sparse Multidimensional Array DBMS. [MIT] [website](https://tiledb.io/)
* [Trilinos](https://github.com/trilinos/Trilinos) - High performance PDE solvers. [BSD] :star:451
* [Torch](https://github.com/torch/torch7) - A scientific computing framework with wide support for machine learning algorithms that puts GPUs first. [BSD-3-Clause] [website](http://torch.ch/)

## Scripting

* [AngelScript](https://www.angelcode.com/angelscript/) - AngelScript is a game-oriented interpreted/compiled scripting language. [zlib]
* [Boost.Python](http://www.boost.org/doc/libs/1_65_1/libs/python/doc/html/index.html) - A C++ library which enables seamless interoperability between C++ and the Python programming language. [Boost]
* [cppimport](https://github.com/tbenthompson/cppimport) - Import C++ files directly from Python! [MIT] :star:812
* [CppSharp](https://github.com/mono/CppSharp) - Tools and libraries to glue C/C++ APIs to high-level languages. [MIT] :star:1597
* [ChaiScript](https://github.com/ChaiScript/ChaiScript/) - An easy to use embedded scripting language for C++. [BSD] [website](http://chaiscript.com/)
* [ctypes.sh](https://github.com/taviso/ctypes.sh) - A foreign function interface for bash. [MIT] :star:1350
* [Cython](https://github.com/cython/cython) - Cython is an optimising static compiler for both the Python programming language and the extended Cython programming language (based on Pyrex). It makes writing C extensions for Python as easy as Python itself. [Apache] [website](http://cython.org/)
* [djinni](https://github.com/dropbox/djinni) - A tool for generating cross-language type declarations and interface bindings. [Apache2] :star:2508
* [Duktape](https://github.com/svaarala/duktape) - An embeddable Javascript engine with compact footprint. [MIT] [website](http://duktape.org)
* [JavaCpp](https://github.com/bytedeco/javacpp) - The missing bridge between Java and native C++. [Apache2] :star:2920
* [libffi](https://github.com/libffi/libffi) - A portable foreign-function interface library. [MIT] [website](https://sourceware.org/libffi/)
* [Lua](http://www.lua.org/) - A minimal and fast scripting engine for configuration files and basic application scripting. [MIT]
* [LuaBridge](https://github.com/vinniefalco/LuaBridge) - A lightweight, dependency-free library for binding Lua to C++. [MIT] :star:829
* [luacxx](https://github.com/dafrito/luacxx) - C++11 API for creating Lua bindings. [MIT] :star:113
* [nbind](https://github.com/charto/nbind) - Magical headers that make your C++ library accessible from JavaScript. [MIT] :star:1584
* [PHP-CPP](https://github.com/CopernicaMarketingSoftware/PHP-CPP) - A library to build PHP extensions with C++. [Apache2] [website](http://www.php-cpp.com/)
* [pybind11](https://github.com/pybind/pybind11) - Seamless operability between C++11 and Python. [BSD] :star:6001
* [SIP](https://riverbankcomputing.com/software/sip/intro) - C or C++ Bindings Generator for Python v2 and v3. [GPL]
* [sol2](https://github.com/ThePhD/sol2) - A C++ <-> Lua API wrapper with advanced features and top notch performance. [MIT] :star:1789
* [SWIG](https://github.com/swig/swig) - A wrapper/interface Generator that let you link your c++ code to Javascript, Perl, PHP, Python, Tcl and Ruby. [GPL/Output not licensed] [website](http://www.swig.org/)
* [V7](https://github.com/cesanta/v7) - An embedded JavaScript engine. [GPL2] :star:1215
* [V8](https://v8.dev) - A fast JavaScript engine by Google that can be embedded into any C++ application. [BSD]
* [ChakraCore](https://github.com/Microsoft/ChakraCore) -A JavaScript engine by Microsoft that can be embedded into nodejs. [MIT]

## Serialization

* [Bitsery](https://github.com/fraillt/bitsery) - Header only C++ binary serialization library. [MIT]  :star:273
* [Bond](https://github.com/Microsoft/bond) - An open source, cross-platform framework for working with schematized data. [MIT] :star:2028
* [Boost.Serialization](https://www.boost.org/doc/libs/master/libs/serialization/doc/index.html) - Boost Serialization Library. [Boost]
* [Cap'n Proto](https://github.com/capnproto/capnproto) - Fast data interchange format and capability-based RPC system. [MIT] [website](https://capnproto.org/)
* [cereal](https://github.com/USCiLab/cereal) - A C++11 library for serialization. [BSD] :star:2063
* [cppcodec](https://github.com/tplgy/cppcodec) - Header-only C++11 library to encode/decode base64, base32 and hex with consistent, flexible API. [MIT] :star:272
* [FlatBuffers](https://github.com/google/flatbuffers) - A Memory efficient serialization library. [Apache2] :star:13094
* [MessagePack](https://github.com/msgpack/msgpack-c) - Efficient binary serialization format "like JSON" for C and C++. [Apache2] [website](http://msgpack.org/)
* [nanopb](https://github.com/nanopb/nanopb) - Small code-size Protocol Buffers implementation in ANSI C. [Zlib] :star:1519
* [protobuf](https://github.com/protocolbuffers/protobuf) - Protocol Buffers - Google's data interchange format. [BSD] :star:37670
* [protobuf-c](https://github.com/protobuf-c/protobuf-c) - Protocol Buffers implementation in C. [BSD] :star:1322
* [SimpleBinaryEncoding](https://github.com/real-logic/simple-binary-encoding) - encoding and decoding application messages in binary format for low-latency applications. [Apache2] :star:1987
* [upb](https://github.com/protocolbuffers/upb) - A small protobuf implementation in C. [BSD] :star:1030
* [YAS](https://github.com/niXman/yas) - Very fast **Y**et **A**nother **S**erialization library supports the binary/text/json formats. [Boost] :star:244

## Sorting

* [pdqsort](https://github.com/orlp/pdqsort) - Pattern-defeating quicksort. [zlib] :star:1026
* [Timsort](https://github.com/gfx/cpp-TimSort) - A templated stable sorting function which outperforms quicksort-based algorithms including std::sort, for reversed or semi-sorted data. [MIT] :star:153

## Video

* [libvpx](http://www.webmproject.org/code/) - VP8/VP9 Codec SDK. [BSD]
* [FFmpeg](https://www.ffmpeg.org/) - A complete, cross-platform solution to record, convert and stream audio and video. [LGPL2/GPL2]
* [libde265](https://github.com/strukturag/libde265) - Open h.265 video codec implementation. [LGPL] [website](http://www.libde265.org/)
* [x265](https://bitbucket.org/multicoreware/x265/wiki/Home) - Open h.265 video codec implementation. [GPL2] [website](https://x265.readthedocs.io/en/default/)
* [OpenH264](https://github.com/cisco/openh264) - Open Source H.264 Codec. [BSD] [website](http://www.openh264.org/)
* [Theora](http://www.theora.org/) - A free and open video compression format. [BSD]
* [Vireo](https://github.com/twitter/vireo/) - A lightweight and versatile video processing library by Twitter. [MIT] :star:661

## Virtual Machines

* [CarpVM](https://github.com/tekknolagi/carp) - "interesting" VM in C. Let's see how this goes. [GPLv3] :star:962
* [MicroPython](https://github.com/micropython/micropython) - Aims to put an implementation of Python 3.x on a microcontroller. [MIT] :star:9312
* [TinyVM](https://github.com/jakogut/tinyvm) - A small, fast, lightweight virtual machine written in pure ANSI C. [MIT] :star:2615

## Web Application Framework

* [Civetweb](https://github.com/civetweb/civetweb) - Provides easy to use, powerful, C/C++ embeddable web server with optional CGI, SSL and Lua support. [MIT] :star:1263
* [CppCMS](http://cppcms.com/) - A Free High Performance Web Development Framework (not a CMS). [LGPLv3]
* [Crow](https://github.com/ipkn/crow) - Crow is C++ micro web framework (inspired by Python Flask). [BSD] :star:5384
* [Cutelyst](https://github.com/cutelyst/cutelyst) - A C++ Web Framework built on top of Qt, using the simple approach of Catalyst (Perl) framework. [LGPLv2.1+] [website](https://cutelyst.org/)
* [Drogon](https://github.com/an-tao/drogon) - A C++14/17 based, high-performance HTTP application framework. [MIT] :star:1082
* [facil.io](https://github.com/boazsegev/facil.io) - Evented, high performance C web framework supporting HTTP, WebSockets, SSE and more. [MIT] [website](http://facil.io)
* [Kore](https://kore.io/) - ultra fast and flexible web server / framework for web applications developed in C. [ISC]
* [libOnion](http://www.coralbits.com/libonion/) - lightweight library to help you create webservers in C programming language. [LGPLv3]
* [lwan](https://github.com/lpereira/lwan) - Experimental, scalable, high performance HTTP server. [GPL2] :star:5058
* [oat++](https://github.com/oatpp/oatpp) - Light, zero-dependency framework to create high-performance web-services. [Apache-2.0] [website](https://oatpp.io/)  :star:1700
* [Pistache](http://pistache.io/) - Pistache is a C++ REST framework written in pure C++11 with no external dependency. [Apache2]
* [QDjango](https://github.com/jlaine/qdjango/) - A web framework written in C++ and built on top of the Qt library. Where possible it tries to follow django's API, hence its name. [LGPL] :star:186
* [TreeFrog Framework](https://github.com/treefrogframework/treefrog-framework) - High-speed and full-stack web application framework based on C++ and Qt, which supports HTTP and WebSocket protocol (with O/R mapping). [BSD] [website](http://www.treefrogframework.org/)
* [Wt](http://www.webtoolkit.eu/wt) - A C++ library for developing web applications. [GPL/Commercial]

## XML
*XML is crap. Really. There are no excuses. XML is nasty to parse for humans, and it's a disaster to parse even for computers. There's just no reason for that horrible crap to exist. - Linus Torvalds*

* [Boost.PropertyTree](http://www.boost.org/doc/libs/1_55_0/doc/html/property_tree.html) - A property tree parser/generator that can be used to parse XML/JSON/INI/Info files. [Boost]
* [Expat](http://www.libexpat.org/) - An XML parser library written in C. [MIT]
* [Libxml2](http://xmlsoft.org/) - The XML C parser and toolkit of Gnome. [MIT]
* [libxml++](http://libxmlplusplus.sourceforge.net/) - An XML Parser for C++. [LGPL2]
* [Mini-XML](https://github.com/michaelrsweet/mxml) - A small XML parsing library written in ANSI C. [LGPL2 with exceptions] :star:173
* [PugiXML](http://pugixml.org/) - A light-weight, simple and fast XML parser for C++ with XPath support. [MIT]
* [RapidXml](http://rapidxml.sourceforge.net/) - An attempt to create the fastest XML parser possible, while retaining useability, portability and reasonable W3C compatibility. [Boost]
* [TinyXML](http://sourceforge.net/projects/tinyxml/) - A simple, small, minimal, C++ XML parser that can be easily integrating into other programs. [zlib]
* [TinyXML2](https://github.com/leethomason/tinyxml2) - A simple, small, efficient, C++ XML parser that can be easily integrating into other programs. [zlib] :star:2827
* [TinyXML++](https://github.com/rjpcomputing/ticpp) - A completely new interface to TinyXML that uses MANY of the C++ strengths. Templates, exceptions, and much better error handling. [MIT] :star:55
* [Xerces-C++](http://xerces.apache.org/xerces-c/) - A validating XML parser written in a portable subset of C++. [Apache2]

## Miscellaneous
*Useful libraries or tools that don't fit in the categories above or maybe just not categorised yet*

* [access_profiler](https://github.com/arvidn/access_profiler) - A tool to count accesses to member variables in c++ programs. [GPL3] :star:58
* [American fuzzy lop](http://lcamtuf.coredump.cx/afl/) a.k.a. afl-fuzz - Crazy fuzzing tool that automatically discovers bugs given time and minimal example input. [Apache2]
* [Better String](http://bstring.sourceforge.net) - An alternative to the string library for C which is more functional and does not have buffer overflow overrun problems. Also includes a C++ wrapper. [BSD, GPL2]
* [Boost.Signals](http://www.boost.org/doc/libs/1_56_0/doc/html/signals.html) - An implementation of a managed signals and slots system. [Boost]
* [CPPItertools](https://github.com/ryanhaining/cppitertools) - Range-based for loop add-ons inspired by the Python builtins and itertools library. [BSD-2-Clause] :star:772
* [DynaMix](https://github.com/iboB/dynamix) - A library which allows you to compose and modify objects at run time. [MIT] :star:430
* [{fmt}](https://github.com/fmtlib/fmt) :zap: - Small, safe and fast formatting library for C++. [Simplified BSD]
* [FastFormat](http://www.fastformat.org) - Fast, Safe C++ Formatting inspired by log4j and Pantheios [Simplified BSD]
* [casacore](https://code.google.com/p/casacore/) - A set of c++ core libraries derived from aips++. [LGPL]
* [QtVerbalExpressions](https://github.com/VerbalExpressions/QtVerbalExpressions) - This Qt lib is based off of the C++ VerbalExpressions library. [MIT] :star:37
* [cxx-prettyprint](https://github.com/louisdx/cxx-prettyprint) - A pretty printing library for C++ containers. [Boost] :star:419
* [icecream-cpp](https://github.com/renatoGarcia/icecream-cpp) - A small printing library for debugging purposes. [MIT] :star:72
* [gcc-poison](https://github.com/leafsr/gcc-poison) - A simple header file for developers to ban unsafe C/C++ functions from applications. :star:149
* [Kangaru](https://github.com/gracicot/kangaru) - A dependency injection container for C++11 and C++14. [MIT] :star:210
* [Klib](https://github.com/attractivechaos/klib) - Small and lightweight implementations of common algorithms and data structures. [MIT] :star:2728
* [libsigc++](http://libsigc.sourceforge.net/) - A typesafe callback system for standard C++. [LGPL]
* [libcpuid](https://github.com/anrieff/libcpuid) - A small C library for x86 CPU detection and feature extraction. [BSD] :star:210
* [libevil](https://github.com/avati/libevil) - The Evil License Manager. [GPLv3] :star:18
* [libnih](https://github.com/keybuk/libnih) - A lightweight library of C functions and structures. [GPL2.1] :star:60
* [libusb](https://libusb.info/) - A universal USB library which allows for portable access to USB devices. [LGPL2]
* [Mach7](https://github.com/solodon4/Mach7) - A Pattern-matching library for C++. [BSD] :star:1046
* [mio](https://github.com/mandreyel/mio) - Cross-platform C++11 header-only library for memory mapped file IO. [MIT] :star:830
* [PEGTL](https://github.com/taocpp/PEGTL) - The Parsing Expression Grammar Template Library. [MIT] :star:916
* [Remote Call Framework](http://www.deltavsoft.com/) - Inter-process communication framework for C++. [GPL2/Commercial]
* [Scintilla](http://scintilla.org/) - A free source code editing component. [MIT]
* [SDS](https://github.com/antirez/sds) - Simple Dynamic Strings library for C. [BSD] :star:2715
* [semver.c](https://github.com/h2non/semver.c) - A semver parser and render in ANSI C. [MIT] :star:128
* [Serial Communication Library](https://github.com/wjwwood/serial) - Cross-platform, Serial Port library written in C++. [MIT] :star:876
* [sigslot](http://sigslot.sourceforge.net/) - C++ Signal/Slot Library. [PublicDomain]
* [SimpleSignal](https://github.com/larspensjo/SimpleSignal) - High performance C++11 signals. [PublicDomain] :star:95
* [Stage](https://github.com/rtv/Stage) - Mobile robot simulator. [GPL2] :star:250
* [stdman](https://github.com/jeaye/stdman) Formatted C++11/14 stdlib man pages (from cppreference). [MIT]
* [stb](https://github.com/nothings/stb) :zap: - A range of single-file libraries for C/C++. [PublicDomain]
* [StrTk](http://www.partow.net/programming/strtk/index.html) - A C++ library consisting of high performance string processing routines. [MIT]
* [Tulip Indicators](https://tulipindicators.org) - A C library of over 100 financial technical analysis indicators. [LGPL]
* [ub-canaries](https://github.com/regehr/ub-canaries) - A collection of C/C++ programs that try to get compilers to exploit undefined behavior. :star:131
* [value-category-cheatsheet](https://github.com/jeaye/value-category-cheatsheet) A PDF cheatsheet for lvalues, rvalues, and the like. [Jank copyleft]
* [VarTypes](https://code.google.com/p/vartypes/) - A feature-rich, object-oriented framework for managing variables in C++ / Qt4. [LGPL]
* [ZBar](http://zbar.sourceforge.net/) - A barcode scanner library, which allows to scan photos/images/video streams for barcodes and return their value. [LGPL2]
* [ZXing](https://github.com/zxing/zxing/) - An open-source, multi-format 1D/2D barcode image processing library implemented in Java, with ports to other languages. [Apache] :star:23801

# Software
*Software for creating a development environment.*

## Compiler
*List of C or C++ compilers*

* [8cc](https://github.com/rui314/8cc) - A Small C Compiler. :star:4416
* [c](https://github.com/ryanmjacobs/c) - Compile and execute C "scripts" in one go! [MIT] :star:1738
* [Clang](http://clang.llvm.org/) - A C compiler for LLVM. Supports C++11/14/1z C11. Developed by LLVM Team. [NCSA]
* [GCC](https://gcc.gnu.org/) - GNU Compiler Collection. Supports C++11/14/1z C11 and OpenMP. [GNU GPL3]
* [PCC](http://pcc.ludd.ltu.se/) - A very old C compiler. Supports C99.
* [Intel C++ Compiler](https://software.intel.com/en-us/c-compilers) - Developed by Intel.
* [LLVM](http://llvm.org/) - Collection of modular and reusable compiler and toolchain technologies.
* [Microsoft Visual C++](https://msdn.microsoft.com/en-us/vstudio/hh386302.aspx) - MSVC, developed by Microsoft.
* [Open WatCom](https://github.com/open-watcom) - Watcom C, C++, and Fortran cross compilers and tools. [Sybase Open Watcom Public License]
* [Oracle Solaris Studio](http://www.oracle.com/technetwork/server-storage/solarisstudio/overview/index.html) - C, C++ and Fortran compiler for SPARC and x86. Supports C++11. Available on Linux and Solaris. [OTN Developer License]
* [TCC](http://bellard.org/tcc/) - Tiny C Compiler. [LGPL]

## Online Compiler
*List of online C or C++ compilers*

* [codepad](http://codepad.org/) - An online compiler/interpreter, and a simple collaboration tool.
* [coliru](http://coliru.stacked-crooked.com/) - Online compiler/shell with support for various C++ compilers.
* [Compiler Explorer](http://gcc.godbolt.org/) - An interactive compiler with assembly output available.
* [CompileOnline](http://www.tutorialspoint.com/codingground.htm) - Compile and Execute C++ online on Linux.
* [Ideone](http://ideone.com/) - An online compiler and debugging tool which allows you to compile source code and execute it online in more than 60 programming languages.
* [repl.it](https://repl.it) - A powerful yet simple tools and platforms for educators, learners, and developers.
* [Rextester](http://rextester.com/runcode) - Online compiler which provides several compilers(Clang, GCC, MSVC) and several editors.
* [Try It Online](https://tio.run/) - TIO is a family of online interpreters for an evergrowing list of practical and recreational programming languages.
* [Wandbox](http://melpon.org/wandbox/) - An online Clang/GCC compiler with Boost available.

## Debugger
*List of C or C++ debuggers*

* [Comparison of debuggers](https://en.wikipedia.org/wiki/Comparison_of_debuggers) - A list of Debuggers from Wikipedia.
* [GDB](https://www.gnu.org/software/gdb/) - GNU Debugger.
* [LLDB](http://lldb.llvm.org/) - The LLDB Debugger.
* [Metashell](https://metashell.readthedocs.org) - An interactive template metaprogramming shell which includes the MDB metadebugger.
* [Valgrind](http://valgrind.org/) - A tool for memory debugging, memory leak detection, and profiling.
* [x64dbg](http://x64dbg.com/) - An open-source x64/x32 debugger for windows.

## Integrated Development Environment
*List of C or C++ nominal IDEs.*

* [Anjuta DevStudio](http://anjuta.org/) - The GNOME IDE. [GPL3]
* [AppCode](http://www.jetbrains.com/objc/) - an IDE for Objective-C, C, C++, and JavaScript development built on JetBrains’ IntelliJ IDEA platform.
* [Cevelop](https://www.cevelop.com) - Cross-platform C and C++ IDE based on Eclipse CDT with additional plug-ins.
* [CLion](http://www.jetbrains.com/clion/) - Cross-platform C and C++ IDE from JetBrains.
* [Code::Blocks](http://www.codeblocks.org/) - A free C, C++ and Fortran IDE.
* [CodeLite](http://codelite.org/) - Another cross-plaform, free C and C++ IDE. [GPL2 with an exception for plugins]
* [color_coded](https://github.com/jeaye/color_coded) - A vim plugin for libclang-based highlighting. [MIT] :star:778
* [Dev-C++](http://sourceforge.net/projects/orwelldevcpp/) - A portable C/C++/C++11 IDE.
* [Eclipse CDT](http://www.eclipse.org/cdt/) - A fully functional C and C++ IDE based on the Eclipse platform.
* [Geany](http://www.geany.org/) - Small, fast, cross-platform IDE. [GPL]
* [IBM VisualAge](http://www-03.ibm.com/software/products/en/visgen) - A family of computer integrated development environments from IBM.
* [Irony-mode](https://github.com/Sarcasm/irony-mode) - A C/C++ minor mode for Emacs powered by libclang. :star:803
* [juCi++](https://gitlab.com/cppit/jucipp) - Cross-platform, lightweight C++ IDE with libclang integration. [MIT]
* [KDevelop](https://www.kdevelop.org/) - A free, open source IDE.
* [Microsoft Visual Studio](https://www.visualstudio.com/) - An IDE from Microsoft.
* [NetBeans](https://netbeans.org/) - An IDE for developing primarily with Java, but also with other languages, in particular PHP, C/C++, and HTML5.
* [Qt Creator](http://www.qt.io/developers/) :zap: - A cross-platform C++, JavaScript and QML IDE which is part of the SDK for Qt.
* [rtags](https://github.com/Andersbakken/rtags) - A c/c++ client/server indexer with for integration with emacs based on clang. :star:1531
* [Xcode](https://developer.apple.com/xcode/) - Developed by Apple.
* [YouCompleteMe](https://github.com/ycm-core/YouCompleteMe) - YouCompleteMe is a fast, as-you-type, fuzzy-search code completion engine for Vim. :star:19930
* [cquery](https://github.com/cquery-project/cquery/) - A C++ code completion engine for vscode, emacs, vim, etc. :star:2195

## Build Systems

* [Bazel](https://bazel.build) - A multi-language, fast and scalable build system from Google. [Apache]
* [Bear](https://github.com/rizsotto/Bear) - A tool to generate compilation database for clang tooling. [GPLv3] :star:1113
* [Buck](https://github.com/facebook/buck) - A fast build system that encourages the creation of small, reusable modules over a variety of platforms and languages including C++ developed and used at Facebook. Written in Java. [Apache] :star:7001
* [clib](https://github.com/clibs/clib) - Package manager for the C programming language. [MIT] :star:3266
* [CMake](https://cmake.org/) - Cross-platform free and open-source software for managing the build process of software using a compiler-independent method. [BSD]
* [C++ Archive Network](https://cppan.org/) - Cross-platform C++ Dependency Manager with a lot of packages available.
* [Cget](https://github.com/pfultz2/cget) - Cmake package retrieval. [Boost] [website](http://cget.readthedocs.io)
* [Conan](https://conan.io/) - C/C++ Package Manager, open sourced. [MIT]
* [CPM](https://github.com/iauns/cpm) - A C++ Package Manager based on CMake and Git. :star:669
* [FASTBuild](http://www.fastbuild.org/docs/home.html) - High performance, open-source build system supporting highly scalable compilation, caching and network distribution.
* [Hunter](https://www.github.com/ruslo/hunter) - CMake driven cross-platform package manager for C++. [BSD-2]
* [MesonBuild](http://mesonbuild.com) - An open source build system meant to be both extremely fast, and, even more importantly, as user friendly as possible.
* [Ninja](https://ninja-build.org/) - A small build system with a focus on speed.
* [Scons](http://www.scons.org/) - A software construction tool configured with a Python script.
* [Sconsolidator](http://www.sconsolidator.com/) - Scons build system integration for Eclipse CDT.
* [Spack](https://spack.io/) - A flexible package manager that supports multiple versions, configurations, platforms, and compilers. [Apache-2.0/MIT]
* [tundra](https://github.com/deplinenoise/tundra) - High-performance code build system designed to give the best possible incremental build times even for very large software projects. :star:280
* [tup](http://gittup.org/tup/) - File-based build system that monitors in the background for changed files.
* [Premake](http://premake.github.io) - A tool configured with a Lua script to generate project files for Visual Studio, GNU Make, Xcode, Code::Blocks, and more across Windows, Mac OS X, and Linux.
* [Vcpkg](https://github.com/microsoft/vcpkg) - C++ library manager for Windows, Linux, and MacOS. [MIT] :star:6855
* [waf](https://github.com/waf-project/waf) - Python-based framework for configuring, compiling and installing applications. [BSD] [website](https://waf.io/)
* [XMake](https://xmake.io/) - A C/C++ cross-platform build utility based on Lua. [Apache]

## Static Code Analysis
*List of tools for improving quality and reducing defects by code analysis*

* [Cppcheck](http://cppcheck.sourceforge.net/) - A tool for static C/C++ code analysis. - [source](https://github.com/danmar/cppcheck) :star:2456
* [CppDepend](https://www.cppdepend.com/) - Simplifies managing a complex C/C++ code base by analyzing and visualizing code dependencies, by defining design rules, by doing impact analysis, and comparing different versions of the code.
* [cpplint](https://github.com/cpplint/cpplint) - A C++ style checker following Google's C++ style guide. :star:332
* [PVS-Studio](http://www.viva64.com/en/pvs-studio/) - A tool for bug detection in the source code of programs, written in C, C++ and C#.
* [cpp-dependencies](https://github.com/tomtom-international/cpp-dependencies) - Tool to check C++ #include dependencies (dependency graphs created in .dot format). [Apache] :star:509
* [include-what-you-use](https://github.com/include-what-you-use/include-what-you-use) - A tool for use with clang to analyze includes in C and C++ source files. [website](https://include-what-you-use.org/)
* [Infer](https://github.com/facebook/infer) - A static analyzer for Java, C and Objective-C. [BSD] :star:10254
* [OCLint](http://oclint.org/) - A static source code analysis tool to improve quality and reduce defects for C, C++ and Objective-C. - [source](https://github.com/oclint/oclint) :star:2980
* [Clang Static Analyzer](http://clang-analyzer.llvm.org/index.html) - A source code analysis tool that finds bugs in C, C++, and Objective-C programs.
* [Linticator](http://linticator.com) - Eclipse CDT integration of Pc-/FlexeLint.
* [List of tools for static code analysis](https://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis#C.2FC.2B.2B) - A list of tools for static code analysis from Wikipedia.

## Coding Style Tools

* [Artistic Style](http://astyle.sourceforge.net/) - A tool to format C/C++/C#/Obj-C/Java code. Also known as astyle.
* [ClangFormat](http://clang.llvm.org/docs/ClangFormat.html) - A tool to format C/C++/Obj-C code.
* [Clang-Tidy](http://clang.llvm.org/extra/clang-tidy.html) - Clang-based C++ linter tool.
* [EditorConfig](https://editorconfig.org/) - EditorConfig helps maintain consistent coding styles across different editors and IDEs.
* [Uncrustify](https://github.com/uncrustify/uncrustify) - Code beautifier. :star:1982

# Resources
*Various resources, such as books, websites, and articles for improving your C++ development skills and knowledge.*

## API Design

* [Beautiful Native Libraries](http://lucumr.pocoo.org/2013/8/18/beautiful-native-libraries/)
* [Designing Qt-Style C++ APIs](https://doc.qt.io/archives/qq/qq13-apis.html)

## Articles
*Fantastic C++ related articles.*

* [CppCon 2019 Presentation Materials](https://github.com/CppCon/CppCon2019) - CppCon 2019 Presentation Materials. :star:330
* [CppCon 2018 Presentation Materials](https://github.com/CppCon/CppCon2018) - CppCon 2018 Presentation Materials. :star:1098
* [CppCon 2017 Presentation Materials](https://github.com/CppCon/CppCon2017) - CppCon 2017 Presentation Materials. :star:1303
* [CppCon 2016 Presentation Materials](https://github.com/CppCon/CppCon2016) - CppCon 2016 Presentation Materials. :star:1592
* [CppCon 2015 Presentation Materials](https://github.com/CppCon/CppCon2015) - CppCon 2015 Presentation Materials. :star:1577
* [CppCon 2014 Presentation Materials](https://github.com/CppCon/CppCon2014) - CppCon 2014 Presentation Materials. :star:2041
* [C++Now 2019 Presentations](https://github.com/boostcon/cppnow_presentations_2019) - Presentation materials presented at C++Now 2019. :star:38
* [C++Now 2018 Presentations](https://github.com/boostcon/cppnow_presentations_2018) - Presentation materials presented at C++Now 2018. :star:111
* [C++Now 2017 Presentations](https://github.com/boostcon/cppnow_presentations_2017) - Presentation materials presented at C++Now 2017. :star:353
* [C++Now 2016 Presentations](https://github.com/boostcon/cppnow_presentations_2016) - Presentation materials presented at C++Now 2016. :star:76
* [C++Now 2015 Presentations](https://github.com/boostcon/cppnow_presentations_2015) - Presentation materials presented at C++Now 2015. :star:194
* [C++Now 2014 Presentations](https://github.com/boostcon/cppnow_presentations_2014) - Presentation materials presented at C++Now 2014. :star:402
* [C++Now 2013 Presentations](https://github.com/boostcon/cppnow_presentations_2013) - Presentation materials presented at C++Now 2013. :star:193
* [C++Now 2012 Presentations](https://github.com/boostcon/cppnow_presentations_2012) - Presentation materials presented at C++Now 2012. :star:161

## Books
*Fantastic C or C++ related books.*

* [List of Free C or C++ Books](https://github.com/fffaraz/awesome-cpp/blob/master/books.md) :star:22090
* [Free C Books](https://github.com/vhf/free-programming-books/blob/master/free-programming-books.md#c) - vhf/free-programming-books/C. :star:129827
* [Free C++ Books](https://github.com/vhf/free-programming-books/blob/master/free-programming-books.md#c-1) - vhf/free-programming-books/C++. :star:129827
* [cppbestpractices](https://github.com/lefticus/cppbestpractices) - Collaborative Collection of C++ Best Practices. :star:2806

## Coding Style

* [C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines) - "Official" set of C++ guidelines, reviewed by the author of C++. :star:24538
* [C++ Dos and Don'ts](http://www.chromium.org/developers/coding-style/cpp-dos-and-donts) - The Chromium Projects > For Developers > Coding Style > C++ Dos and Don'ts.
* [google-styleguide](https://github.com/google/styleguide) - Style guides for Google-originated open-source projects. :star:22040
* [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)
* [GNU Coding Standard](http://www.gnu.org/prep/standards/standards.html)
* [Linux kernel coding style](https://www.kernel.org/doc/Documentation/process/coding-style.rst)
* [LLVM Coding Standards](http://llvm.org/docs/CodingStandards.html)

## Podcasts

* [CppCast](http://cppcast.com) - The first podcast by C++ developers for C++ developers.
* [CppChat](http://cpp.chat) - A (sometimes) weekly look at what's going on in the world of C++ chatting with a guest from the community.

## Talks

* [CppCon Talks](https://www.youtube.com/user/CppCon/videos) :zap: - The C++ conference.
* [Quick game development with C++11/C++14](https://github.com/SuperV1234/cppcon2014) - CppCon 2014 talk by Vittorio Romeo. :star:83
* [Presentation on Hana for C++Now 2015](https://github.com/ldionne/hana-cppnow-2015) :star:8

## Videos
*Fantastic C or C++ related videos.*

* [List of C or C++ YouTube Videos](https://github.com/fffaraz/awesome-cpp/blob/master/videos.md) :star:22090
* [Awesome C Programming Tutorials in Hi Def [HD]](https://www.youtube.com/playlist?list=PLCB9F975ECF01953C) - A collection of detailed C Programming Language Tutorials for Beginners and New Programmers.
* [C++](https://www.youtube.com/playlist?list=PL2F919ADECA5E39A6) - by VoidRealms.
* [C++ Qt Programming](https://www.youtube.com/playlist?list=PL2D1942A4688E9D63) - by VoidRealms.
* [C++ Programming Tutorials Playlist](https://www.youtube.com/playlist?list=PLAE85DE8440AA6B83) - TheNewBoston Official Buckys C++ Programming Tutorials Playlist.
* [C++ Programming Tutorials from thenewboston](https://www.youtube.com/playlist?list=PLF541C2C1F671AEF6) - These are all of thenewboston's C++ programming tutorials.
* [C++ GUI with Qt Playlist](https://www.youtube.com/playlist?list=PLD0D54219E5F2544D) - Official Playlist for thenewboston C++ GUI with Qt tutorials.
* [C Programming Tutorials](https://www.youtube.com/playlist?list=PL78280D6BE6F05D34) - All of TheNewBoston's C programming tutorials are right here.
* [Bo Qian's playlist](https://www.youtube.com/user/BoQianTheProgrammer/playlists) - Boost Library, C++ Standard Library, Modern C++, Advanced C++, Advanced STL, ...

## Websites
*Useful C or C++ related websites.*

* [Standard C++](https://isocpp.org/) :zap: - News, Status & Discussion about Standard C++.
* [CppCon](http://cppcon.org/) - The C++ Conference.
* [C++ reference](http://cppreference.com/) - C++98, C++03, C++11, C++14 reference.
* [cplusplus.com](http://www.cplusplus.com/) - The C++ Resources Network.
* [C FAQ](http://c-faq.com/) - C frequently asked questions.
* [C++ FAQ](http://www.parashift.com/c++-faq/) - C++ frequently asked questions.
* [C++ FQA Lite](http://yosefk.com/c++fqa/) - C++ frequently questioned answers.
* [Guru of the Week](http://www.gotw.ca/gotw/) - A regular series of C++ programming problems created and written by Herb Sutter.
* [Meeting C++](http://meetingcpp.com/)
* [C++ Quiz](http://q.viva64.com/) - C++ quiz in which you propose to find errors in code fragments of open source projects.
* [Udemy C++ Courses and Tutorials](https://www.udemy.com/topic/C-plus-plus-tutorials/)
* [C++ Hints](http://cpphints.com/) - Every business day hints about most often C++ mistakes and ways to solve them from PVS-Studio Team.
* [C++ tutorial](https://hackr.io/tutorials/learn-c-plus-plus) - A user ranked online tutorial bank site displaying multiple courses to learn C++ from.

## Weblogs
*Useful C or C++ related weblogs.*

* [Coding For Speed](https://codingforspeed.com/) - Coding For Speed DOT COM, Less Execution Time.
* [Eric Niebler](http://ericniebler.com/)
* [Sticky Bits](https://blog.feabhas.com/)
* [Paul Fultz II's Blog](http://pfultz2.com/blog/)
* [ridiculousfish](http://ridiculousfish.com/blog/posts/will-it-optimize.html) - Will It Optimize?
* [Embedded in Academia](http://blog.regehr.org/)
* [Simplify C++](https://arne-mertz.de/)
* [Fluent C++](https://www.fluentcpp.com/) 
* [Bartek's Coding Blog](https://www.bfilipek.com/?m=1)
* [Kenny Kerr](https://kennykerr.ca/articles/)
* [Sutter’s Mill](https://herbsutter.com/gotw/)
* [thoughts on cpp](https://thoughts-on-cpp.com/)
* [Vorbrodt's C++ Blog](https://vorbrodt.blog/)
* [foonathan::blog()](https://foonathan.net/index.html)

## Other Awesome Projects
*Collection of useful codes, snippets, ...*

* [algorithms](https://github.com/xtaci/algorithms) - Algorithms & Data Structures in C++. :star:3274
* [c-algorithms](https://github.com/fragglet/c-algorithms) - C algorithms library. :star:1891
* [C++ Awesome Pack](https://github.com/juniandotnet/cpp-awesome-pack) - Contains some awesome c++ codes, packed in one. :star:161
* [30 Seconds of C++](https://github.com/Bhupesh-V/30-seconds-of-cpp) :star:326

# Other Awesome Lists
*Other amazingly awesome lists*

* [lists](https://github.com/jnv/lists) - List of (awesome) lists curated on GitHub. :star:6046
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - A curated list of awesome awesomeness. :star:25047
* [awesome](https://github.com/sindresorhus/awesome) :zap: - A curated list of awesome lists.
* [C++ links](https://github.com/MattPD/cpplinks) - A categorized list of C++ resources. :star:1724
* [Awesome C++](https://getawesomeness.herokuapp.com/get/cpp) - getAwesomeness()'s mirror.
* [Awesome C++](https://cpp.libhunt.com/) - LibHunt's mirror.
* [Awesome C](https://notabug.org/koz.ross/awesome-c) 1
* [Awesome C](https://github.com/aleksandar-todorovic/awesome-c) 2
* [Awesome Modern C++](https://github.com/rigtorp/awesome-modern-cpp) - A collection of resources on modern C++. :star:5393
* [AwesomePerfCpp](https://github.com/fenbf/AwesomePerfCpp) - A curated list of awesome C/C++ performance optimization resources. :star:1636
* [free-programming-books](https://github.com/vhf/free-programming-books) - List of Freely Available Programming Books. :star:129827
* [Inqlude](http://inqlude.org/) - The Qt library archive.
* [papers-we-love](https://github.com/papers-we-love/papers-we-love) - Papers from the computer science community to read and discuss. :star:36455
* [awesome-algorithms](https://github.com/tayllan/awesome-algorithms) - A curated list of awesome places to learn and/or practice algorithms. :star:6681
* [awesome-talks](https://github.com/JanVanRyswyck/awesome-talks) - A lot of screencasts, recordings of user group gatherings and conference talks. :star:2702
* [Projects](https://github.com/karan/Projects) - A list of practical projects that anyone can solve in any programming language. :star:29159
* [Awesome interview questions](https://github.com/MaximAbramchuck/awesome-interviews) - A list of lists of interview questions for the most popular technologies, including C and C++. :star:29566
* [nothings/single_file_libs](https://github.com/nothings/single_file_libs) :zap: - List of single-file C/C++ libraries.

# Contributing
Please take a quick gander at the [contribution guidelines](https://github.com/fffaraz/awesome-cpp/blob/master/CONTRIBUTING.md) for details.
Thanks to all [contributors](https://github.com/fffaraz/awesome-cpp/graphs/contributors); you rock!

#### *If you see a project or link here that is no longer maintained or is not a good fit, please submit a pull request to improve this document. Thank you!*


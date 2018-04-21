# Information comes from [deephacks/awesome-jvm](https://github.com/deephacks/awesome-jvm)
# Awesome JVM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome JVM low level, performance and non-framework related stuff.

- [Awesome JVM](#awesome-jvm)
    - [Bytecode](#bytecode)
    - [Garbage collectors](#garbage-collectors)
    - [Load tools](#load-tools)
    - [Languages](#languages)
    - [Machine Learning](#machine-learning)
    - [Memory and Concurrency](#memory-and-concurrency)
    - [Metaprogramming](#metaprogramming)
    - [Native](#native)
    - [Network](#network)
    - [Nix tools](#nix-tools)
    - [Profilers](#profilers)
    - [Runtimes](#runtimes)
    - [Virtual Machines](#virtual-machines)
- [Resources](#resources)
    - [Communities](#communities)    
    - [Documentation](#documentation)
    - [Media](#media)
    - [People](#people)
- [Contributing](#contributing)


## Bytecode

*Tools for bytecode manipulation and analysis.*

* [asmtools](https://wiki.openjdk.java.net/display/CodeTools/asmtools) - Used to develop tools for the production of Java .class files.
* [Byte Buddy](http://bytebuddy.net) - Code generation library creating Java classes at runtime without the help of a compiler.
* [Jitescript](https://github.com/qmx/jitescript) - Bytecode generation library similar to BiteScript.  :star:149

## Garbage collectors

*Garbage collectors for the JVM.*

* [Azul Pauseless Garbage Collection](https://www.azul.com/files/wp_pgc_zing_v52.pdf) - Providing continuous, pauseless operation for Java applications.
* [Balanced GC](http://www.ibm.com/developerworks/websphere/techjournal/1108_sciampacone/1108_sciampacone.html) - GC policy available in the Java Virtual Machine for IBM WebSphere Application Server V8.
* [Epsilon GC](http://openjdk.java.net/jeps/318) - Completely passive GC implementation with bounded allocation limit, and lowest runtime performance overhead possible.
* [G1](http://www.oracle.com/technetwork/java/javase/tech/g1-intro-jsp-135488.html) - The Garbage-First Garbage Collector.
* [Shenandoah](http://openjdk.java.net/jeps/189) - Ultra-Low-Pause-Time Garbage Collector.
* [The Garbage Collection Handbook](http://gchandbook.org) - Book that addresses new challenges to garbage collection made by recent advances in hardware and software.
* [ZGC](http://mail.openjdk.java.net/pipermail/announce/2017-October/000237.html) - Garbage collector optimized for low latency and very large heaps.

## Load tools

*Tools that generate load and measure the system accurately without coordinated omission*

* [Gatling](http://gatling.io) - Asynchronous non-blocking scenario driven load testing tool for testing HTTP servers.
* [wrk2](https://github.com/giltene/wrk2) - A constant throughput, correct latency recording variant of wrk. :star:1298

## Languages

*Languages running on the JVM.*
* [Ceylon](http://ceylon-lang.org/) - Object-oriented, strong and static programming language with an emphasis on immutability, created by Red Hat.
* [Clojure](http://clojure.org/) - Dialect of Lisp created by Rich Hickey. Dynamically typed with emphasis on functional programming.
* [Erjang](http://www.erjang.org) - A JVM-based Erlang VM.
* [Eta](http://eta-lang.org/) - Pure, lazy, strongly typed functional programming language on the JVM.
* [Frege](https://github.com/Frege/frege) - Pure functional programming language in the spirit of Haskell. :star:3038
* [gojava](https://github.com/sridharv/gojava) - Java bindings for Go packages. :star:154
* [Golo](http://golo-lang.org/) - A simple dynamic language that makes extensive usage of `invokedynamic`.
* [Groovy](http://www.groovy-lang.org/) - Optionally typed and dynamic language, with static-typing and static compilation capabilities.
* [Java](http://www.oracle.com/technetwork/java/javase/overview/index.html) - General-purpose, concurrent, strongly typed, class-based object-oriented language.
* [JRuby](http://jruby.org) - Implementation of the Ruby language on the JVM.
* [JPHP](http://j-php.net) - PHP on the Java VM.
* [Jython](http://www.jython.org) - Python for the Java Platform.
* [Kawa](http://www.gnu.org/software/kawa/) - Extension of the Scheme language, which is in the Lisp family of programming languages.
* [Kotlin](http://kotlinlang.org/) - Statically typed programming language for the JVM, Android and the browser.
* [LuaJ](http://www.luaj.org/luaj/3.0/README.html) - Java-centric implementation of lua vm built to leverage standard Java features.
* [Nashorn](http://openjdk.java.net/projects/nashorn/) - Lightweight high-performance JavaScript runtime in Java with a native JVM.
* [OCaml-Java](http://www.ocamljava.org/) - Supports OCaml language v4. Generates plain Java bytecode and have seamless integration with Java.
* [Rembulan](https://github.com/mjanicek/rembulan) - Rembulan is an implementation of Lua 5.3 for the JVM, written in pure Java with minimal dependencies. :star:105
* [Renjin](http://www.renjin.org/) - JVM-based interpreter for the R language for the statistical analysis
* [Scala](http://www.scala-lang.org/) - Strong and static programming language that combine object-oriented and functional programming ideas.
* [Xtend](http://www.eclipse.org/xtend/) - Flexible and expressive dialect of Java, which compiles into Java 5 source code.

## Machine Learning
* [Deeplearning4j](https://deeplearning4j.org/) - Open-Source, Distributed, Deep Learning Library for the JVM.
* [H2O](https://www.h2o.ai/) - Fast statistical, machine learning & math runtime.
* [Smile](https://github.com/haifengl/smile) - Statistical Machine Intelligence & Learning Engine. :star:3765

## Memory and concurrency

*Tools and data structures for efficient memory layout and concurrent access.*

* [Agera](https://github.com/google/agera) - Reactive Programming for Android by Google. :star:7076
* [Agrona](https://github.com/real-logic/Agrona) - Library of data structures and utility methods that are a common need when building high-performance applications. :star:1039
* [Apache Arrow](http://arrow.apache.org/) - A high-performance cross-system data layer for columnar in-memory analytics.
* [bloofi](https://github.com/lemire/bloofi) - Java implementation of multidimensional Bloom filters :star:57
* [Cap’n Proto](https://capnproto.org/) - Insanely fast data interchange format and capability-based RPC system.
* [caffeine](https://github.com/ben-manes/caffeine) - A high performance caching library for Java 8. :star:3889
* [Chronicle-Bytes](https://github.com/OpenHFT/Chronicle-Bytes) - Low level memory access wrappers. :star:95
* [Chronicle-Queue](https://github.com/OpenHFT/Chronicle-Queue) - Micro second messaging that stores everything to disk. :star:1383
* [Chronicle-Map](https://github.com/OpenHFT/Chronicle-Map) - In-memory key-value store designed for low-latency and/or multi-process applications. :star:1280
* [clj-ds](https://github.com/krukow/clj-ds) - Clojure's data structures modified for use outside of Clojure. :star:210
* [colfer](https://github.com/pascaldekloe/colfer) - Binary serialization format and class generator. :star:357
* [commons-math](http://commons.apache.org/proper/commons-math) - Library of lightweight, self-contained mathematics and statistics components.
* [CuckooFilter4J](https://github.com/MGunlogson/CuckooFilter4J) - Bloom filter replacement for approximated set-membership queries. :star:54
* [cyclops](https://github.com/aol/cyclops) - Integration modules for RxJava, Reactor, FunctionalJava, Guava & Javaslang. :star:408
* [Eclipse Collections](https://github.com/eclipse/eclipse-collections) - Collections framework for Java. :star:540
* [externalsortinginjava](https://github.com/lemire/externalsortinginjava) - Sort very large files using multiple cores and an external-memory algorithm. :star:112
* [failsafe](https://github.com/jhalterman/failsafe) - A lightweight, zero-dependency library for handling failures. :star:2135
* [fasttuple](https://github.com/boundary/fasttuple) - Collections that are laid out adjacently in both on- and off-heap memory. :star:131
* [fast-uuid](https://github.com/jchambers/fast-uuid) - Java library for quickly and efficiently parsing and writing UUIDs. :star:62
* [FlatBuffers](http://google.github.io/flatbuffers/) - Efficient cross platform serialization library for C++, C#, Go, Java, JavaScript, PHP, and Python.
* [geohash](https://github.com/davidmoten/geo) - Java utility methods for geohashing. :star:248
* [gs-collections](https://github.com/goldmansachs/gs-collections) - Goldman Sachs collections framework. :star:1709
* [hollow](https://github.com/Netflix/hollow) - Java library and comprehensive toolset for harnessing small to moderately sized in-memory datasets. :star:654
* [high-scale-lib](https://github.com/boundary/high-scale-lib) - Cliff Click's High Scale Library. :star:296
* [hppc](https://github.com/carrotsearch/hppc) - High Performance Primitive Collections. :star:457
* [injector](https://github.com/belliottsmith/injector) - A new Executor for Java. :star:55
* [java-concurrent-hash-trie-map](https://github.com/romix/java-concurrent-hash-trie-map) - Java port of a concurrent trie hash map implementation from Scala collections. :star:113
* [java-hll](https://github.com/aggregateknowledge/java-hll) - Java library for the HyperLogLog algorithm. :star:201
* [JavaFastPFOR](https://github.com/lemire/JavaFastPFOR) - Library to compress and uncompress arrays of integers very fast. :star:314
* [java-string-similarity](https://github.com/tdebatty/java-string-similarity) - String similarity and distance measures, including Levenshtein edit distance and sibblings, Jaro-Winkler, Longest Common Subsequence, cosine similarity etc. :star:1522
* [JCTools](http://jctools.github.io/JCTools/) - Concurrent data structures currently missing from the JDK.
* [jsoniter](http://jsoniter.com/) - Claims to be the fastest JSON parser ever.
* [jOOL](https://github.com/jOOQ/jOOL) - Useful extensions to Java 8 lambdas. :star:1217
* [Koloboke](https://github.com/OpenHFT/Koloboke) - Java Collections til the last breadcrumb of memory and performance. :star:733
* [LevelDB](https://github.com/dain/leveldb) - Rewrite (port) of LevelDB in Java. :star:866
* [lightweight_trie](https://github.com/bryanduxbury/lightweight_trie) - A very memory-efficient trie (radix tree) implementation. :star:38
* [lmdbjni](https://github.com/deephacks/lmdbjni) - Java API to LMDB (HawtJNI) which is an ultra-fast, ultra-compact key-value embedded data store written in C. :star:177
* [lmdbjava](https://github.com/lmdbjava/lmdbjava) - Java API to LMDB (JNR) which is an ultra-fast, ultra-compact key-value embedded data store written in C. :star:201
* [low-gc-membuffers](https://github.com/cowtowncoder/low-gc-membuffers) - In-memory circular buffers that use direct ByteBuffers to minimize GC overhead. :star:123
* [lwjgl3](https://github.com/LWJGL/lwjgl3) - Java library that enables cross-platform access to popular native APIs useful in the development of graphics (OpenGL), audio (OpenAL) and parallel computing (OpenCL) applications. :star:1679
* [MapDB](http://www.mapdb.org) - Collections backed by off-heap or on-disk storage.
* [mph-table](https://github.com/indeedeng/mph-table) - Minimal Perfect Hash Tables are an immutable key/value store with efficient space utilization and fast reads. :star:33
* [mug](https://google.github.io/mug/) - A small, zero-dep functional util library originating from Google. 
* [netty-buffers](http://netty.io/wiki/using-as-a-generic-library.html#wiki-h2-1) - Memory buffer pool implementation similar to jemalloc.
* [ObjectLayout](http://objectlayout.org) - A layout-optimized Java data structure package.
* [ohc](https://github.com/snazy/ohc) - Java large off heap cache developed for Apache Cassandra 3.0. :star:286
* [okio](https://github.com/square/okio) - Modern Java IO library that do clever things to save CPU and memory. :star:4898
* [onyx-java](https://github.com/onyx-platform/onyx-java) - Mirrors the Onyx Platform core API by providing a Java equivalent for each component of an Onyx workflow. :star:5
* [parquet](https://parquet.apache.org/) - Columnar storage format that uses the record shredding and assembly algorithm described in the Dremel paper.
* [PauselessHashMap](https://github.com/giltene/PauselessHashMap) - A java.util.HashMap compatible map that won't stall puts or gets when resizing. :star:134
* [pcollections](https://github.com/hrldcpr/pcollections) - A Persistent Java Collections Library. :star:450
* [protobuf](https://developers.google.com/protocol-buffers) - Google's data interchange format.
* [Quasar](http://www.paralleluniverse.co/quasar/) - Lightweight threads and actors for the JVM.
* [rtree](https://github.com/davidmoten/rtree) - Immutable in-memory R-tree and R*-tree implementations in Java with reactive api. :star:616
* [Reactive Streams](http://www.reactive-streams.org/) - Standard for asynchronous stream processing with non-blocking back pressure.
* [Reactive Streams Utilities](https://github.com/lightbend/reactive-streams-utils) - Future standard utilities library for Reactive Streams. :star:39
* [RoaringBitmap](https://github.com/RoaringBitmap/RoaringBitmap) - A better compressed bitset in Java. :star:836
* [rollinghashjava](https://github.com/lemire/rollinghashjava) - Rolling hash functions in Java. :star:51
* [Reactor](http://projectreactor.io/) - Reactive data applications on the JVM for Java, Groovy, Clojure and other.
* [RxJava](https://github.com/ReactiveX/RxJava) - Library for composing asynchronous and event-based programs using observable sequences. :star:32482
* [SmoothieMap](https://github.com/OpenHFT/SmoothieMap) - java.util.Map impl with worst put latencies more than 100 times smaller than java.util.HashMap. :star:146
* [Simple Binary Encoding](https://github.com/real-logic/simple-binary-encoding) - High Performance Message Codec. :star:1326
* [splitmap](https://github.com/richardstartin/splitmap/) - A parallel bitmap implementation.
* [DataSketches](https://datasketches.github.io/) - A Java software library of stochastic streaming algorithms.
* [stormpot](https://github.com/chrisvest/stormpot) - A fast object pool for the JVM. :star:124
* [stream-lib](https://github.com/addthis/stream-lib) - A Java library for summarizing data in streams for which it is infeasible to store all events. :star:1789
* [streamvbyte](https://github.com/lemire/streamvbyte) - Fast integer compression in C using the StreamVByte codec. :star:123
* [TraneIO](http://trane.io/) - High-performance implementation of the Future abstraction.
* [transducers-java](https://github.com/cognitect-labs/transducers-java) - Composable algorithmic transformations independent from the context of their input and output sources. :star:100
* [VarInt](https://github.com/bazelbuild/bazel/blob/master/src/main/java/com/google/devtools/build/lib/util/VarInt.java) - No-deps variable int implementation without deps (by Bazel).
* [vavr](http://www.vavr.io/) - Functional Library for Java 8+.
* [wire](https://github.com/square/wire) - Clean, lightweight protocol buffers for Android and Java. :star:2316
* [Zero-Allocation-Hashing](https://github.com/OpenHFT/Zero-Allocation-Hashing) - Hashing any sequences of bytes in Java, including all kinds of primitive arrays, buffers, CharSequences and more. :star:281

## Metaprogramming

*Parsers, interpreters, compilers and source generation targeted for the JVM.*

* [Antlr](http://www.antlr.org/) - Parser generator for reading, processing, executing, or translating structured text or binary files.
* [auto](https://github.com/google/auto) - A collection of source code generators for Java. :star:6495
* [Apache Calcite](http://calcite.apache.org/docs/) - Dynamic data management framework and SQL parser plugin.
* [Checker Framework](http://types.cs.washington.edu/checker-framework/) - Compiler plug-ins that find bugs or verify their absence.
* [compile-testing](https://github.com/google/compile-testing) - Testing tools for javac and annotation processors. :star:428
* [derive4j](https://github.com/derive4j/derive4j) - Algebraic data types constructors, pattern-matching, morphisms, optics and typeclasses. :star:339
* [error-prone](https://github.com/google/error-prone) - Catch common Java mistakes as compile-time errors. :star:3622
* [GHCVM](https://github.com/rahulmutt/ghcvm) - A Haskell to JVM compiler that supports GHC Haskell. :star:1798
* [Graal](http://openjdk.java.net/projects/graal/) - New experimental just-in-time compiler for Java that is integrated with the HotSpot virtual machine.
* [grappa](https://github.com/fge/grappa) - Java fork of Parboiled. Write grammars with no preprocessing phase. :star:60
* [immutables](http://immutables.github.io/) - Generate simple, safe and consistent value objects.
* [javacc](https://javacc.java.net/) - Parser generator for use with Java.
* [javaparser](https://github.com/javaparser/javaparser) - Java 1.8 Parser and Abstract Syntax Tree for Java. :star:1662
* [JavaPoet](https://github.com/square/javapoet) - A Java API for generating .java source files. :star:5153
* [jparsec](https://github.com/jparsec/jparsec) - Builds mini parsers in pure Java a la Haskell Parsec. :star:209
* [JSweet](http://www.jsweet.org/) - A transpiler from Java to TypeScript/JavaScript.
* [MPS](https://www.jetbrains.com/mps/) - Design and build extensible DSLs and editors.
* [lombok](https://projectlombok.org/) - Reduce the amount of boilerplate code that is commonly written for Java classes.
* [parboiled](https://github.com/sirthias/parboiled) - Parsing of arbitrary input text based on parsing expression grammars. :star:1060
* [Sulong](https://github.com/graalvm/sulong) - LLVM IR interpreter written in Java using Truffle and Graal. :star:540
* [TeaVM](https://github.com/konsoletyper/teavm) - Ahead-of-time translating compiler (transpiler) from Java bytecode to JavaScript. :star:868
* [Truffle](https://github.com/graalvm/truffle) - Framework for implementing languages as simple interpreters. :star:3267
* [Xtext](https://eclipse.org/Xtext/) - Framework for development of programming languages and DSLs.

## Native

*Interconnecting JVM and native code* 

* [hawtjni](https://github.com/fusesource/hawtjni) - A JNI code generator based on the JNI generator used in Eclipse SWT. :star:73
* [Java Grinder](https://github.com/mikeakohn/java_grinder) - Compile Java bytecode to microcontroller assembly. :star:231
* [j2v8](https://github.com/eclipsesource/j2v8) - Java API for Google's V8 JavaScript engine. :star:991
* [JavaCPP](https://github.com/bytedeco/javacpp) - JavaCPP provides efficient access to native C++ inside Java. :star:2354
* [jnr-ffi](https://github.com/jnr/jnr-ffi) - Load native libraries without writing JNI code by hand. :star:530
* [jssembly](https://github.com/dvx/jssembly) - Execution of native assembly from Java. :star:110
* [NuProcess](https://github.com/brettwooldridge/NuProcess) - A low-overhead, non-blocking I/O, external Process execution implementation for Java. :star:315
* [Project Panama](http://openjdk.java.net/projects/panama/) - Enriching the connections between the JVM and APIs used by C programmers.

## Network

*Tools for network programming, packet capture, monitoring, testing and resiliency.*

* [Aeron](https://github.com/real-logic/Aeron) - Efficient reliable UDP unicast, UDP multicast, and IPC message transport. :star:3319
* [armeria](https://github.com/line/armeria) - Asynchronous RPC/API client/server library built on top of Java 8, Netty 4.1, HTTP/2, and Thrift. :star:1201
* [Chronicle-Network](https://github.com/OpenHFT/Chronicle-Network) - A High Performance Network library. :star:75
* [comcast](https://github.com/tylertreat/comcast) - Simulating shitty network connections. :star:5429

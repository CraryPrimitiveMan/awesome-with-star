# Information comes from [tindzk/awesome-scala-native](https://github.com/tindzk/awesome-scala-native)
# Awesome Scala Native [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<a href="http://www.scala-native.org/"><img alt="Scala Native" align="right" width="250" height="250" src="logo.png"></a>

[Scala Native](http://www.scala-native.org/) is an optimising ahead-of-time compiler for the [Scala programming language](https://www.scala-lang.org/). Traditionally, a virtual machine, the [JVM](https://en.wikipedia.org/wiki/Java_virtual_machine), was required to run Scala programs. Scala Native taps into the compiler to emit [LLVM intermediate representation](http://llvm.org/docs/LangRef.html) rather than JVM bytecode. Then, the [LLVM](http://llvm.org/) compiler infrastructure is used to produce native libraries and executables. Given that Scala Native executables are stand-alone programs, they generally have a shorter start-up time and low memory consumption. This opens up new avenues to deploy Scala programs where previously the virtual machine would be the limiting factor. For example, developers could write programs for the command line or embedded devices.

## Contents
* [Tutorials and Examples](#tutorials-and-examples)
* [Build Tools](#build-tools)
* [Functional Programming](#functional-programming)
* [Unit Tests](#unit-tests)
* [Bindings](#bindings)
* [File Formats and Parsers](#file-formats-and-parsers)
* [Databases](#databases)
* [Web Development](#web-development)
* [Logging](#logging)
* [Console](#console)
* [Robotics](#robotics)
* [Programs](#programs)
* [Infrastructure](#infrastructure)

## Tutorials and Examples
* [Giter8 template for a minimal Scala Native project](https://github.com/scala-native/scala-native.g8) - Official [Giter8](http://www.foundweekends.org/giter8/) template for a minimal Scala Native project. :star:62
* [Hands on Scala Native](https://github.com/MasseGuillaume/hands-on-scala-native) - Tutorial for implementing a bandwidth monitor with Ncurses. :star:20
* [Starter for Scala Native](https://github.com/GnaneshKunal/scala-native-starter) - Scala Native project that links to a custom C library. :star:24
* [Building C code using sbt-jni](https://github.com/nadavwr/scala-native-sbt-jni-example) - Example for compiling C code in a Scala Native project using [sbt-jni](https://github.com/jodersky/sbt-jni). :star:2
* [Example project with external dependencies](https://github.com/lihaoyi/scala-native-example-app) - Example project that uses external dependencies to generate HTML and run a test suite. :star:45
* [Starter for Gtk+ Projects](https://github.com/jokade/scalanative-gtk-seed.g8) - [Giter8](http://www.foundweekends.org/giter8/) template for Scala Native GUI projects using [Gtk+](https://developer.gnome.org/gtk3/stable/index.html). :star:1

## Build Tools
* [sbt](https://www.scala-sbt.org/) - Scala's standard build tool.
* [Mill](https://github.com/lihaoyi/mill) - Build tool striving for simplicity, inspired by [Bazel](https://www.bazel.build/). :star:1275
* [Bloop](https://github.com/scalacenter/bloop) - Scala build server and command-line tool for fast developer workflows. :star:577
* [Seed](https://github.com/tindzk/seed) - Build tool based on Bloop. Focuses on user experience and cross-platform builds, inspired by [Cargo](https://github.com/rust-lang/cargo). :star:178

## Functional Programming
* [Shapeless](https://github.com/milessabin/shapeless) - Library for generic programming. :star:2928
* [Squants](https://github.com/typelevel/squants) - DSL for quantities, units of measure and dimensional analysis. :star:681
* [scalaz](https://github.com/scalaz/scalaz) - Type classes and instances for data structures. :star:4314
* [nobox](https://github.com/xuwei-k/nobox) - Immutable primitive array wrapper without boxing. :star:28
* [PPrint](https://github.com/lihaoyi/PPrint) - Pretty-print values and types. :star:96
* [SourceCode](https://github.com/lihaoyi/sourcecode) - Implicits providing meta data similar to `__LINE__` in C. :star:405
* [reactify](https://github.com/outr/reactify) - Functional Reactive Programming framework for Scala. :star:67
* [chimney](https://github.com/scalalandio/chimney) - Boilerplate-free data transformations. :star:518

## Unit Tests
* [utest](https://github.com/lihaoyi/utest) - Library for unit tests. :star:396
* [minitest](https://github.com/monix/minitest) - Lightweight testing library. :star:149
* [scalaprops](https://github.com/scalaprops/scalaprops) - Library for property-based testing. :star:254
  * [scalaprops-shapeless](https://github.com/scalaprops/scalaprops-shapeless) - Generation of arbitrary ADT instances. :star:9
  * [scalaprops-cross-example](https://github.com/scalaprops/scalaprops-cross-example) - Cross-platform example. :star:2
* [Makeshift](https://github.com/nadavwr/makeshift) - Library for unit tests. :star:1

## Bindings
* [cmark](https://github.com/sparsetech/cmark-scala) - Bindings for the [cmark](https://github.com/commonmark/cmark) CommonMark parser library. :star:10
* [libuv](https://github.com/TimothyKlim/scala-native-libuv) - Bindings for [libuv](https://github.com/libuv/libuv), a library for asynchronous I/O. :star:7
* [SDL2 and OpenGL](https://github.com/regb/scalanative-graphics-bindings) - Bindings for the graphical frameworks [SDL2](https://www.libsdl.org/) and [OpenGL](https://www.opengl.org/). :star:30
* [Cocoa](https://github.com/jokade/scalanative-cocoa) - Bindings for the macOS graphical framework [Cocoa](https://en.wikipedia.org/wiki/Cocoa_(API)). :star:14
* [GNU Scientific Library](https://github.com/ruivieira/scala-gsl) - Bindings for [GNU Scientific Library (GSL)](https://www.gnu.org/software/gsl/). :star:2
* [BLAS](https://github.com/ekrich/scala-native-ml) - Bindings for [BLAS](http://www.netlib.org/blas/), a library for Linear Algebra. :star:14
* [Gtk+](https://github.com/jokade/scalanative-gtk) - Bindings for the [GTK+](https://www.gtk.org/) graphical toolkit. :star:13
* [libsoup](https://github.com/jokade/scalanative-libsoup) - Bindings for the [libsoup](https://wiki.gnome.org/Projects/libsoup) HTTP client/server library. :star:2
* [libui](https://github.com/lolgab/scalaui) - GUI framework based on [libui](https://github.com/andlabs/libui). :star:42
* [GStreamer](https://github.com/jokade/scalanative-gstreamer) - Bindings for the [GStreamer](https://gstreamer.freedesktop.org) multimedia framework.
* [Qt](https://github.com/jokade/scalanative-qt5) - Bindings for [Qt](https://www.qt.io). :star:1

## File Formats and Parsers
* [msgpack4z](https://github.com/msgpack4z/msgpack4z-native) - Implementation of [MessagePack](https://msgpack.org/), a binary serialisation format. :star:3
* [FastParse](https://github.com/lihaoyi/fastparse) - Library for defining and running parsers. :star:832
* [scalatags](https://github.com/lihaoyi/scalatags) - HTML/XML construction and rendering. :star:614
* [Pine](https://github.com/sparsetech/pine) - HTML/XML parsing, manipulation and rendering. :star:94
* [scala-json](https://github.com/MediaMath/scala-json) - JSON parser. :star:59
* [toml-scala](https://github.com/sparsetech/toml-scala) - [TOML](https://github.com/toml-lang/toml) parser with codec derivation. :star:15
* [argonaut](https://github.com/argonaut-io/argonaut) - Purely functional JSON parser and library. :star:492
* [ScalaPB](https://github.com/scalapb/ScalaPB) - [Protocol Buffer](https://developers.google.com/protocol-buffers/) compiler for Scala. :star:952
  * [scalapb-argonaut](https://github.com/scalapb-json/scalapb-argonaut) - JSON and Protocol Buffer converters for ScalaPB based on [Argonaut](http://argonaut.io/). :star:1
* [sconfig](https://github.com/ekrich/sconfig/) - [HOCON](https://github.com/ekrich/sconfig/blob/master/docs/original/HOCON.md) parser. :star:62

## Databases
* [JDBC](https://github.com/jokade/scalanative-jdbc) - Port of the database access layer [JDBC](https://en.wikipedia.org/wiki/Java_Database_Connectivity) to Scala Native. :star:7
* [SQLite4S](https://github.com/david-bouyssie/sqlite4s) - Port of the Java library [Sqlite4java](https://bitbucket.org/almworks/sqlite4java). Includes bindings for the SQLite native library. :star:5

## Web Development
* [Trail](https://github.com/sparsetech/trail) - Routing library. :star:57

## Logging
* [scribe](https://github.com/outr/scribe) - Fast and simple logging library. :star:243
* [slogging](https://github.com/jokade/slogging) - [Typesafe-logging](https://github.com/lightbend/scala-logging) and [SLF4J](https://www.slf4j.org/)-compatible logging library based on macros. :star:43

## Console
* [fansi](https://github.com/lihaoyi/fansi) - Library for creating [ANSI-coloured strings](https://en.wikipedia.org/wiki/ANSI_escape_code). :star:159
* [scopt](https://github.com/scopt/scopt) - Command-line argument parser. :star:1181
* [scala-optparse-applicative](https://github.com/xuwei-k/optparse-applicative) - Port of Haskell's CLI argument parsing library [optparse-applicative](https://hackage.haskell.org/package/optparse-applicative). :star:10
* [scallop](https://github.com/scallop/scallop) - A simple Scala CLI parsing library. :star:521

## Robotics
* [Potassium](https://github.com/Team846/potassium) - Framework for writing robot software. :star:14
* [WPILib](https://github.com/Team846/scala-native-wpilib) - Reimplementation of the [FIRST Robotics WPILib libraries](http://first.wpi.edu/FRC/roborio/release/docs/java/). :star:5

## Programs
* [sglgears](https://github.com/Milyardo/sglgears) - Port of GL [gears.c](https://github.com/JoakimSoderberg/mesademos/blob/master/src/xdemos/glxgears.c). :star:14
* [k8s-cli](https://github.com/fsat/k8s-cli) - CLI tools to generate [Kubernetes](https://kubernetes.io/) resources for [Akka](https://akka.io/), [Play Framework](https://www.playframework.com/) and [Lagom](https://www.lagomframework.com/)-based applications. :star:3
* [Coursier](https://github.com/coursier/coursier) - Coursier's [`bootstrap` command](https://get-coursier.io/docs/cli-native-bootstrap) generates native launchers. :star:1567

## Infrastructure
* [Seed Docker image](https://hub.docker.com/r/tindzk/seed/tags) - Docker image for cross-platform builds with [Seed](https://github.com/tindzk/seed).
* [scala-native-sbt-docker](https://github.com/ScalaWilliam/scala-native-sbt-docker) - Docker image for Scala Native and sbt. :star:3

## Licence
<a rel="licence" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg" /></a><br />This work is licenced under a <a rel="licence" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International Licence</a>.


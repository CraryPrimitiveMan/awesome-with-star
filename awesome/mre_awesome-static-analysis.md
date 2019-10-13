# Information comes from [mre/awesome-static-analysis](https://github.com/mre/awesome-static-analysis)
 ![Logo](awesome.png)

> Static program analysis is the analysis of computer software that is performed without actually executing programs — [Wikipedia](https://en.wikipedia.org/wiki/Static_program_analysis)

This is a collection of static analysis tools and code quality checkers. Pull requests are very welcome!

* :copyright: stands for proprietary software. All other tools are Open Source.
* :warning: indicates that the community does not recommend to use this tool for
  new projects anymore as it is outdated or no longer maintained.

Also check out the sister project, [awesome-dynamic-analysis](https://github.com/mre/awesome-dynamic-analysis).

# Table of Contents

#### [Programming Languages](#programming-languages-1)

<details>
 <summary>Show languages</summary>
  <!-- Please use HTML syntax here so that it works for Github and mkdocs -->
  <ul>
    <li><a href="#abap">ABAP</a></li>
    <li><a href="#ada">Ada</a></li>
    <li><a href="#awk">Awk</a></li>
    <li><a href="#cc">C/C++</a></li>
    <li><a href="#c">C#</a></li>
    <li><a href="#crystal">Crystal</a></li>
    <li><a href="#dlang">Dlang</a></li>
    <li><a href="#elixir">Elixir</a></li>
    <li><a href="#elm">Elm</a></li>
    <li><a href="#erlang">Erlang</a></li>
    <li><a href="#f">F#</a></li>
    <li><a href="#fortran">Fortran</a></li>
    <li><a href="#go">Go</a></li>
    <li><a href="#groovy">Groovy</a></li>
    <li><a href="#haskell">Haskell</a></li>
    <li><a href="#haxe">Haxe</a></li>
    <li><a href="#java">Java</a></li>
    <li><a href="#javascript">JavaScript</a></li>
    <li><a href="#kotlin">Kotlin</a></li>
    <li><a href="#lua">Lua</a></li>
    <li><a href="#matlab">Matlab</a></li>
    <li><a href="#perl">Perl</a></li>
    <li><a href="#php">PHP</a></li>
    <li><a href="#python">Python</a></li>
    <li><a href="#r">R</a></li>
    <li><a href="#rpg">RPG</a></li>
    <li><a href="#ruby">Ruby</a></li>
    <li><a href="#rust">Rust</a></li>
    <li><a href="#scala">Scala</a></li>
    <li><a href="#shell">Shell</a></li>
    <li><a href="#solidity">Solidity</a></li>
    <li><a href="#sql">SQL</a></li>
    <li><a href="#swift">Swift</a></li>
    <li><a href="#tcl">Tcl</a></li>
    <li><a href="#typescript">TypeScript</a></li>
    <li><a href="#vbscript">VBScript</a></li>
  </ul>
</details>

#### [Multiple languages](#multiple-languages-1)

#### [Other](#other-1)

  - [Build tools](#build-tools)
  - [Binaries](#binaries)
  - [Containers](#containers)
  - [Config Files](#config-files)
  - [Configuration Management](#configuration-management)
  - [CSS](#css)
  - [Gherkin](#gherkin)
  - [HTML](#html)
  - [IDE Plugins](#ide-plugins)
  - [LaTeX](#latex)
  - [Makefiles](#makefiles)
  - [Markdown](#markdown)
  - [Mobile](#mobile)
  - [Packages](#packages)
  - [Supporting Tools](#supporting-tools)
  - [Template Languages](#template-languages)
  - [Translation](#translation)
  - [Web services](#web-services)
  - [Writing](#writing)

#### [More Collections](#more-collections-1)

---

# Programming Languages

## ABAP

* [abaplint](https://github.com/larshp/abaplint) - Linter for ABAP, written in TypeScript. :star:52
* [abapOpenChecks](https://github.com/larshp/abapOpenChecks) - Enhances the SAP Code Inspector with new and customizable checks. :star:94

## Ada

* [Codepeer](http://www.adacore.com/codepeer) - detects run-time and logic errors
* [Polyspace for Ada](https://www.mathworks.com/products/polyspace-ada.html) :copyright: - provide code verification that proves the absence of overflow, divide-by-zero, out-of-bounds array access, and certain other run-time errors in source code.
* [SPARK](http://www.spark-2014.org/about) :copyright: - Static analysis and formal verification toolset for Ada
* [Understand](https://scitools.com/ada-programming-essential/) :copyright: - IDE that provides code analysis, standards testing, metrics, graphing, dependency analysis and more for Ada and VHDL.

## Awk

* [gawk --lint](https://www.gnu.org/software/gawk/manual/html_node/Options.html) - warns about constructs that are dubious or nonportable to other awk implementations.

## C/C++

* [Astrée](https://www.absint.com/astree/index.htm) :copyright: - Sound static analyzer based on abstract interpretation for C/C++, detecting memory, type and concurrency defects, and MISRA violations.
* [CBMC](http://www.cprover.org/cbmc/) - bounded model-checker for C programs, user-defined assertions, standard assertions, several coverage metric analyses
* [clang-tidy](http://clang.llvm.org/extra/clang-tidy/) - clang static analyser
* [CMetrics](https://github.com/MetricsGrimoire/CMetrics) - Measures size and complexity for C files :star:43
* [Codecheker](https://github.com/Ericsson/codechecker) - static analysis of C/C++ code, with web GUI :star:758
* [CodeSonar from GrammaTech](https://www.grammatech.com/products/codesonar) :copyright: - Advanced, whole program, deep path, static analysis of C and C++ with easy-to-understand explanations and code and path visualization.
* [Corrode](https://github.com/jameysharp/corrode) - Semi-automatic translation from C to Rust. Could reveal bugs in the original implementation by showing Rust compiler warnings and errors. :star:1962
* [cppcheck](https://github.com/danmar/cppcheck) - static analysis of C/C++ code :star:2456
* [CppDepend](https://www.cppdepend.com) :copyright: - Measure, query and visualize your code and avoid unexpected issues, technical debt and complexity.
* [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) - automated C++ checker that follows Google's style guide :star:22043
* [cqmetrics](https://github.com/dspinellis/cqmetrics) - quality metrics for C code :star:30
* [CScout](https://www.spinellis.gr/cscout/) - complexity and quality metrics for for C and C preprocessor code
* [flawfinder](http://www.dwheeler.com/flawfinder/) - finds possible security weaknesses
* [flint++](https://github.com/JossWhittle/FlintPlusPlus) - cross-platform, zero-dependency port of flint, a lint program for C++ developed and used at Facebook. :star:228
* [Frama-C](http://frama-c.com/) - a sound and extensible static analyzer for C code
* [Helix QAC](https://www.perforce.com/products/helix-qac) :copyright: - Enterprise-grade static analysis for embedded software. Supports MISRA, CERT, and AUTOSAR coding standards.
* [IKOS](https://github.com/nasa-sw-vnv/ikos) - a sound static analyzer for C/C++ code based on LLVM :star:1184
* [include-gardener](https://github.com/feddischson/include_gardener) - a static analyzer for C/C++/Obj-C to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files. :star:32
* [LDRA](https://ldra.com/) :copyright: - a tool suite including static analysis (TBVISION) to various standards including MISRA C & C++, JSF++ AV, CWE, CERT C, CERT C++ & Custom Rules.
* [oclint](http://oclint.org/) - static analysis of C/C++ code
* [Phasar](https://github.com/secure-software-engineering/phasar) - A LLVM-based static analysis framework which comes with a taint and type state analysis. :star:307
* [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) :copyright: - identifies run-time errors, concurrency issues, security vulnerabilities, and other defects in C and C++ embedded software.
* [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) :copyright: - provide code verification that proves the absence of overflow, divide-by-zero, out-of-bounds array access, and certain other run-time errors in C and C++ source code.
* [scan-build](https://clang-analyzer.llvm.org/scan-build.html) - Analyzes C/C++ code using LLVM at compile-time
* [splint](https://github.com/ravenexp/splint) - Annotation-assisted static program checker :star:104
* [SVF](https://github.com/SVF-tools/SVF) - a static tool that enables scalable and precise interprocedural dependence analysis for C and C++ programs. :star:304
* [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) - Vera++ is a programmable tool for verification, analysis and transformation of C++ source code.

## C# #

* [.NET Analyzers](https://github.com/DotNetAnalyzers) - An organization for the development of analyzers (diagnostics and code fixes) using the .NET Compiler Platform.
* [Code Analysis Rule Collection](https://carc.codeplex.com/) - Contains a set of diagnostics, code fixes and refactorings built on the Microsoft .NET Compiler Platform "Roslyn".
* [code-cracker](https://github.com/code-cracker/code-cracker) - An analyzer library for C# and VB that uses Roslyn to produce refactorings, code analysis, and other niceties. :star:1002
* [CodeRush](https://www.devexpress.com/products/coderush/) :copyright: - Code creation, debugging, navigation, refactoring, analysis and visualization tools that use the Roslyn engine in Visual Studio 2015 and up.
* [CSharpEssentials](https://github.com/DustinCampbell/CSharpEssentials) - C# Essentials is a collection of Roslyn diagnostic analyzers, code fixes and refactorings that make it easy to work with C# 6 language features. :star:154
* [Designite](http://www.designite-tools.com) :copyright: - Designite supports detection of various architecture, design, and implementation smells, computation of various code quality metrics, and trend analysis.
* [Gendarme](http://www.mono-project.com/docs/tools+libraries/tools/gendarme/) - Gendarme inspects programs and libraries that contain code in ECMA CIL format (Mono and .NET).
* [NDepend](http://www.ndepend.com/) :copyright: - Measure, query and visualize your code and avoid unexpected issues, technical debt and complexity.
* [Puma Scan](https://github.com/pumasecurity/puma-scan) - Puma Scan provides real time secure code analysis for common vulnerabilities (XSS, SQLi, CSRF, LDAPi, crypto, deserialization, etc.) as development teams write code in Visual Studio. :star:325
* [Refactoring Essentials](http://vsrefactoringessentials.com/) - The free Visual Studio 2015 extension for C# and VB.NET refactorings, including code best practice analyzers.
* [ReSharper](https://www.jetbrains.com/resharper/) :copyright: - Extends Visual Studio with on-the-fly code inspections for C#, VB.NET, ASP.NET, JavaScript, TypeScript and other technologies.
* [Roslyn Security Guard](https://dotnet-security-guard.github.io/) - Project that focuses on the identification of potential vulnerabilities such as SQL injection, cross-site scripting (XSS), CSRF, cryptography weaknesses, hardcoded passwords and many more.
* [Roslynator](https://github.com/JosefPihrt/Roslynator/) - A collection of 190+ analyzers and 190+ refactorings for C#, powered by Roslyn. :star:1367
* [Security Code Scan](https://security-code-scan.github.io/) - Security code analyzer for C# and VB.NET. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.
* [SonarLint for Visual Studio](https://vs.sonarlint.org/) - SonarLint is an extension for Visual Studio 2015 and 2017 that provides on-the-fly feedback to developers on new bugs and quality issues injected into .NET code.
* [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics) - A collection of static analyzers based on Roslyn that integrates with VS. :star:62
* [Wintellect.Analyzers](https://github.com/Wintellect/Wintellect.Analyzers) - .NET Compiler Platform ("Roslyn") diagnostic analyzers and code fixes. :star:81

## Crystal

* [ameba](https://github.com/veelenga/ameba) - A static code analysis tool for Crystal :star:237
* [crystal](https://crystal-lang.org/) - The Crystal compiler has built-in linting functionality.

## Dlang

* [D-scanner](https://github.com/dlang-community/D-Scanner) - D-Scanner is a tool for analyzing D source code :star:204

## Elixir

* [credo](https://github.com/rrrene/credo) - A static code analysis tool with a focus on code consistency and teaching. :star:3073
* [sobelow](https://github.com/nccgroup/sobelow) - Security-focused static analysis for the Phoenix Framework :star:783

## Elm

* [elm-analyse](https://stil4m.github.io/elm-analyse/) - A tool that allows you to analyse your Elm code, identify deficiencies and apply best practices.

## Erlang

* [elvis](https://github.com/inaka/elvis) - Erlang Style Reviewer :star:352

## F# #

* [FSharpLint](https://github.com/fsprojects/FSharpLint) - Lint tool for F# :star:172

## Fortran

* [i-Code CNES for Fortran](https://github.com/lequal/i-CodeCNES) - An open source static code analysis tool for Fortran 77, Fortran 90 and Shell. :star:28

## Go

* [deadcode](https://github.com/tsenart/deadcode) - Finds unused code. :star:36
* [dingo-hunter](https://github.com/nickng/dingo-hunter) - Static analyser for finding deadlocks in Go. :star:245
* [dupl](https://github.com/mibk/dupl) - Reports potentially duplicated code. :star:179
* [errcheck](https://github.com/kisielk/errcheck) - Check that error return values are used. :star:1341
* [flen](https://github.com/lafolle/flen) - Get info on length of functions in a Go package. :star:46
* [gas](https://github.com/GoASTScanner/gas) - Inspects source code for security problems by scanning the Go AST. :star:2757
* [Go Meta Linter](https://github.com/alecthomas/gometalinter) - Concurrently run Go lint tools and normalise their output. :star:3562
* [go tool vet --shadow](https://golang.org/cmd/vet/#hdr-Shadowed_variables) - Reports variables that may have been unintentionally shadowed.
* [go vet](https://golang.org/cmd/vet/) - Examines Go source code and reports suspicious.
* [go-consistent](https://github.com/Quasilyte/go-consistent) - Analyzer that helps you to make your Go programs more consistent. :star:241
* [go-critic](https://github.com/go-critic/go-critic) - Go source code linter that maintains checks which are currently not implemented in other linters. :star:613
* [go-staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - go vet on steroids, similar to ReSharper for C#. :star:2695
* [go/ast](https://golang.org/pkg/go/ast/) - Package ast declares the types used to represent syntax trees for Go packages.
* [goconst](https://github.com/jgautheron/goconst) - Finds repeated strings that could be replaced by a constant. :star:122
* [gocyclo](https://github.com/fzipp/gocyclo) - Calculate cyclomatic complexities of functions in Go source code. :star:548
* [gofmt -s](https://golang.org/cmd/gofmt/) - Checks if the code is properly formatted and could not be further simplified.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Checks missing or unreferenced package imports.
* [GolangCI-Lint](https://github.com/golangci/golangci-lint) - Alternative to `Go Meta Linter`: GolangCI-Lint is a linters aggregator. :star:3659
* [golint](https://github.com/golang/lint) - Prints out coding style mistakes in Go source code. :star:3234
* [goreporter](https://github.com/wgliang/goreporter) - concurrently runs many linters and normalises their output to a report. :star:2521
* [goroutine-inspect](https://github.com/linuxerwang/goroutine-inspect) - An interactive tool to analyze Golang goroutine dump. :star:220
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - Report simplifications in code. :star:2695
* [gotype](https://golang.org/x/tools/cmd/gotype) - Syntactic and semantic analysis similar to the Go compiler.
* [ineffassign](https://github.com/gordonklaus/ineffassign) - Detect ineffectual assignments in Go code :star:227
* [interfacer](https://github.com/mvdan/interfacer) - Suggest narrower interfaces that can be used. :star:716
* [lll](https://github.com/walle/lll) - Report long lines. :star:34
* [maligned](https://github.com/mdempsky/maligned) -  Detect structs that would take less memory if their fields were sorted. :star:229
* [megacheck](https://github.com/dominikh/go-tools/tree/master/cmd/megacheck) - Run staticcheck, gosimple and unused, sharing work. :star:2695
* [misspell](https://github.com/client9/misspell) - Finds commonly misspelled English words. :star:781
* [nakedret](https://github.com/alexkohler/nakedret) - Finds naked returns. :star:50
* [nargs](https://github.com/alexkohler/nargs) - Finds unused arguments in function declarations. :star:75
* [prealloc](https://github.com/alexkohler/prealloc) - Finds slice declarations that could potentially be preallocated. :star:360
* [revive](https://github.com/mgechev/revive) - Fast, configurable, extensible, flexible, and beautiful linter for Go. Drop-in replacement of golint. :star:1979
* [safesql](https://github.com/stripe/safesql) - Static analysis tool for Golang that protects against SQL injections. :star:436
* [structcheck](https://github.com/opennota/check) - Find unused struct fields. :star:225
* [test](http://golang.org/pkg/testing/) - Show location of test failures from the stdlib testing module.
* [testify](https://github.com/stretchr/testify) - Show location of failed testify assertions. :star:8642
* [unconvert](https://github.com/mdempsky/unconvert) - Detect redundant type conversions. :star:269
* [unimport](https://github.com/alexkohler/unimport) - Finds unnecessary import aliases :star:58
* [unparam](https://github.com/mvdan/unparam) - Find unused function parameters. :star:251
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - Find unused variables. :star:2695
* [varcheck](https://github.com/opennota/check) - Find unused global variables and constants. :star:225

## Groovy

* [CodeNarc](https://github.com/CodeNarc/CodeNarc) - a static analysis tool for Groovy source code, enabling monitoring and enforcement of many coding standards and best practices :star:212

## Haskell

* [HLint](https://github.com/ndmitchell/hlint) - HLint is a tool for suggesting possible improvements to Haskell code. :star:862
* [Weeder](https://github.com/ndmitchell/weeder) - A tool for detecting dead exports or package imports in Haskell code. :star:114

## Haxe

* [Haxe Checkstyle](https://github.com/HaxeCheckstyle/haxe-checkstyle) - A static analysis tool to help developers write Haxe code that adheres to a coding standard. :star:95

## Java
* [Checker Framework](https://github.com/typetools/checker-framework/) - Pluggable type-checking for Java http://checkerframework.org/ :star:537
* [checkstyle](https://github.com/checkstyle/checkstyle) - checking Java source code for adherence to a Code Standard or set of validation rules (best practices) :star:4846
* [ck](https://github.com/mauricioaniche/ck) - calculates Chidamber and Kemerer object-oriented metrics by processing the source Java files :star:69
* [ckjm](http://www.spinellis.gr/sw/ckjm/) - calculates Chidamber and Kemerer object-oriented metrics by processing the bytecode of compiled Java files
* [ClassGraph](https://github.com/classgraph/classgraph) - a classpath and module path scanner for querying or visualizing class metadata or class relatedness :star:1428
* [CogniCrypt](https://www.eclipse.org/cognicrypt/) - checks Java source and byte code for incorrect uses of cryptographic APIs
* [DesigniteJava](http://www.designite-tools.com/designitejava) :copyright: - DesigniteJava supports detection of various architecture, design, and implementation smells along with computation of various code quality metrics.
* [Error-prone](https://github.com/google/error-prone) - Catch common Java mistakes as compile-time errors :star:4871
* [fb-contrib](https://github.com/mebigfatguy/fb-contrib) - A plugin for FindBugs with additional bug detectors :star:97
* [Find Security Bugs](https://find-sec-bugs.github.io/) - IDE/SonarQube plugin for security audits of Java web applications.
* [google-java-format](https://github.com/google/google-java-format) - Google Style Reformat :star:2883
* [Hopper](https://github.com/cuplv/hopper) - A static analysis tool written in scala for languages that run on JVM :star:45
* [HuntBugs](https://github.com/amaembo/huntbugs) - Bytecode static analyzer tool based on Procyon Compiler Tools aimed to supersede FindBugs. :star:296
* [JArchitect](https://www.jarchitect.com) :copyright: - Measure, query and visualize your code and avoid unexpected issues, technical debt and complexity.
* [JBMC](http://www.cprover.org/jbmc/) - bounded model-checker for Java (bytecode), verifies user-defined assertions, standard assertions, several coverage metric analyses
* [NullAway](https://github.com/uber/NullAway) - Type-based null-pointer checker with low build-time overhead; an [Error Prone](http://errorprone.info/) plugin :star:2616
* [OWASP Dependency Check](https://www.owasp.org/index.php/OWASP_Dependency_Check) - Checks dependencies for known, publicly disclosed, vulnerabilities.
* [qulice](https://www.qulice.com/) - combines a few (pre-configured) static analysis tools (checkstyle, PMD, Findbugs, ...).
* [Soot](https://sable.github.io/soot/) - A framework for analyzing and transforming Java and Android applications.
* [Spoon](https://github.com/INRIA/spoon) - Library to write your own static analyses and architectural rule checkers for Java. Can be integrated in Maven and Gradle. :star:820
* [SpotBugs](https://spotbugs.github.io/) - SpotBugs is FindBugs' successor. A tool for static analysis to look for bugs in Java code.
* [Xanitizer](https://xanitizer.com/) - Xanitizer finds security vulnerabilities in Java/Scala web applications.

## JavaScript

* [aether](https://github.com/codecombat/aether) - Lint, analyze, normalize, transform, sandbox, run, step through, and visualize user JavaScript, in node or the browser. :star:171
* [Closure Compiler](https://github.com/google/closure-compiler) - A compiler tool to increase efficiency, reduce size, and provide code warnings in JavaScript files. :star:5177
* [ClosureLinter](https://github.com/google/closure-linter) - ensures that all of your project's JavaScript code follows the guidelines in the Google JavaScript Style Guide. It can also automatically fix many common errors :star:101
* [coffeelint](https://github.com/clutchski/coffeelint) - A style checker that helps keep CoffeeScript code clean and consistent. :star:1035
* [complexity-report](https://github.com/jared-stilwell/complexity-report) - Software complexity analysis for JavaScript projects :star:152
* [DeepScan](https://deepscan.io) :copyright: - An analyzer for JavaScript which targets runtime errors and quality issues rather than coding conventions.
* [escomplex](https://github.com/jared-stilwell/escomplex) - Software complexity analysis of JavaScript-family abstract syntax trees. :star:194
* [eslint](https://github.com/eslint/eslint) - A fully pluggable tool for identifying and reporting on patterns in JavaScript :star:15084
* [Esprima](https://github.com/jquery/esprima) - ECMAScript parsing infrastructure for multipurpose analysis :star:5429
* [flow](https://flow.org/) - A static type checker for JavaScript.
* [jshint](https://github.com/jshint/jshint) :warning: - detect errors and potential problems in JavaScript code and enforce your team's coding conventions
* [JSLint](https://github.com/douglascrockford/JSLint) :warning: - The JavaScript Code Quality Tool
* [JSPrime](https://github.com/dpnishant/jsprime) - static security analysis tool :star:496
* [NodeJSScan](https://github.com/ajinabraham/NodeJsScan) - NodeJsScan is a static security code scanner for Node.js applications. :star:833
* [plato](https://github.com/es-analysis/plato) - Visualize JavaScript source complexity :star:4404
* [Prettier](https://github.com/prettier/prettier) - An opinionated code formatter. :star:33903
* [quality](https://github.com/jden/quality) - zero configuration code and module linting :star:7
* [retire.js](https://github.com/RetireJS/retire.js) - Scanner detecting the use of JavaScript libraries with known vulnerabilities :star:2230
* [standard](http://standardjs.com/) - An npm module that checks for Javascript Styleguide issues
* [tern](https://github.com/ternjs/tern) - A JavaScript code analyzer for deep, cross-editor language support :star:4028
* [xo](https://github.com/xojs/xo) - Opinionated but configurable ESLint wrapper with lots of goodies included. Enforces strict and readable code. :star:4777
* [yardstick](https://github.com/calmh/yardstick) - Javascript code metrics :star:23

## Kotlin

* [detekt](https://github.com/arturbosch/detekt) - Static code analysis for Kotlin code. :star:2370
* [ktlint](https://github.com/shyiko/ktlint) - An anti-bikeshedding Kotlin linter with built-in formatter :star:2769

## Lua

* [luacheck](https://github.com/mpeterv/luacheck) - A tool for linting and static analysis of Lua code. :star:1065

## MATLAB

* [mlint](https://de.mathworks.com/help/matlab/ref/mlint.html) :copyright: - Check MATLAB code files for possible problems.

## Perl

* [Perl::Critic](http://search.cpan.org/~thaljef/Perl-Critic-1.126/lib/Perl/Critic.pm) - Critique Perl source code for best-practices.

## PHP

* [dephpend](https://github.com/mihaeu/dephpend) - Dependency analysis tool :star:365
* [deprecation-detector](https://github.com/sensiolabs-de/deprecation-detector) - Finds usages of deprecated (Symfony) code :star:381
* [deptrac](https://github.com/sensiolabs-de/deptrac) - Enforce rules for dependencies between software layers. :star:949
* [DesignPatternDetector](https://github.com/Halleck45/DesignPatternDetector) - detection of design patterns in PHP code :star:95
* [EasyCodingStandard](https://github.com/Symplify/EasyCodingStandard) - combine [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) and [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) :star:8127
* [exakat](https://github.com/exakat/exakat) - An automated code reviewing engine for PHP :star:296
* [GrumPHP](https://github.com/phpro/grumphp) - checks code on every commit :star:2998
* [Mondrian](https://github.com/Trismegiste/Mondrian) - a set of static analysis and refactoring tools which use graph theory :star:364
* [parallel-lint](https://github.com/JakubOnderka/PHP-Parallel-Lint) - This tool checks syntax of PHP files faster than serial check with a fancier output. :star:587
* [Parse](https://github.com/psecio/parse) - A Static Security Scanner :star:265
* [pdepend](https://pdepend.org/) - Calculates software metrics like cyclomatic complexity for PHP code.
* [phan](https://github.com/etsy/phan) - a modern static analyzer from etsy :star:4561
* [PHP Assumptions](https://github.com/rskuipers/php-assumptions) - Checks for weak assumptions :star:125
* [PHP Coding Standards Fixer](http://cs.sensiolabs.org/) - Fixes your code according to standards like PSR-1, PSR-2, and the Symfony standard.
* [Php Inspections (EA Extended)](https://github.com/kalessil/phpinspectionsea) - A Static Code Analyzer for PHP. :star:1026
* [PHP Refactoring Browser](https://github.com/QafooLabs/php-refactoring-browser) - Refactoring helper :star:563
* [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) - Suggests a next version according to semantic versioning :star:403
* [PHP-Parser](https://github.com/nikic/PHP-Parser) - A PHP parser written in PHP :star:11683
* [PHP-Token-Reflection](https://github.com/Andrewsville/PHP-Token-Reflection) - Library emulating the PHP internal reflection :star:191
* [php7cc](https://github.com/sstalle/php7cc) - PHP 7 Compatibility Checker :star:1518
* [php7mar](https://github.com/Alexia/php7mar) - assist developers in porting their code quickly to PHP 7 :star:739
* [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) - detects violations of a defined set of coding standards :star:6939
* [phpca](https://github.com/wapmorgan/PhpCodeAnalyzer) - Finds usage of non-built-in extensions :star:78
* [phpcf](http://wapmorgan.github.io/PhpCodeFixer/) - Finds usage of deprecated PHP features
* [phpcpd](https://github.com/sebastianbergmann/phpcpd) - Copy/Paste Detector for PHP code. :star:1859
* [phpdcd](https://github.com/sebastianbergmann/phpdcd) - Dead Code Detector (DCD) for PHP code. :star:386
* [PhpDependencyAnalysis](https://github.com/mamuz/PhpDependencyAnalysis) - builds a dependency graph for a project :star:419
* [phpdoc-to-typehint](https://github.com/dunglas/phpdoc-to-typehint) - Add scalar type hints and return types to existing PHP projects using PHPDoc annotations :star:224
* [phpDocumentor](https://www.phpdoc.org/) - Analyzes PHP source code to generate documentation
* [PHPMD](https://phpmd.org/) - finds possible bugs in your code
* [PhpMetrics](http://www.phpmetrics.org/) - Calculates and visualizes various code quality metrics
* [phpmnd](https://github.com/povils/phpmnd) - Helps to detect magic numbers :star:315
* [PHPQA](https://github.com/EdgedesignCZ/phpqa) - A tool for running QA tools (phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics) :star:428
* [phpqa - jakzal](https://github.com/jakzal/phpqa) - Many tools for PHP static analysis in one container :star:657
* [phpqa - jmolivas](https://github.com/jmolivas/phpqa) - PHPQA all-in-one Analyzer CLI tool :star:336
* [phpsa](https://github.com/ovr/phpsa) - Static analysis tool for PHP. :star:649
* [PHPStan](https://github.com/phpstan/phpstan) - PHP Static Analysis Tool - discover bugs in your code without running it! :star:7547
* [Progpilot](https://github.com/designsecurity/progpilot) - A static analysis tool for security purposes :star:131
* [Psalm](https://getpsalm.org/) - Static analysis tool for finding type errors in PHP applications
* [Qafoo Quality Analyzer](https://github.com/Qafoo/QualityAnalyzer) - Visualizes metrics and source code :star:476
* [RIPS](https://www.ripstech.com/) :copyright: - A static source code analyser for vulnerabilities in PHP scripts
* [Tuli](https://github.com/ircmaxell/Tuli) - A static analysis engine :star:178
* [twig-lint](https://github.com/asm89/twig-lint) - twig-lint is a lint tool for your twig files. :star:102
* [WAP](https://www.owasp.org/index.php/OWASP_WAP-Web_Application_Protection) - Tool to detect and correct input validation vulnerabilities in PHP (4.0 or higher) web applications and predicts false positives by combining static analysis and data mining.

## Python

* [bandit](https://github.com/PyCQA/bandit) - a tool to find common security issues in Python code :star:1733
* [bellybutton](https://github.com/hchasestevens/bellybutton) - a linting engine supporting custom project-specific rules :star:163
* [Black](https://github.com/ambv/black) - The uncompromising Python code formatter :star:12890
* [cohesion](https://github.com/mschwager/cohesion) - a tool for measuring Python class cohesion :star:78
* [Dlint](https://github.com/duo-labs/dlint) - a tool for ensuring Python code is secure :star:232
* [jedi](https://github.com/davidhalter/jedi) - autocompletion/static analysis library for Python :star:4041
* [linty fresh](https://github.com/lyft/linty_fresh) - parse lint errors and report them to Github as comments on a pull request :star:176
* [mccabe](https://github.com/PyCQA/mccabe) - check McCabe complexity :star:245
* [mypy](https://github.com/python/mypy) - a static type checker that aims to combine the benefits of duck typing and static typing, frequently used with [MonkeyType](https://github.com/Instagram/MonkeyType) :star:2373
* [py-find-injection](https://github.com/uber/py-find-injection) - find SQL injection vulnerabilities in Python code :star:85
* [pycodestyle](https://github.com/PyCQA/pycodestyle) - (formerly `pep8`) check Python code against some of the style conventions in PEP 8 :star:3813
* [pydocstyle](https://github.com/PyCQA/pydocstyle) - check compliance with Python docstring conventions :star:570
* [pyflakes](https://github.com/pyflakes/pyflakes/) - check Python source files for errors :star:787
* [pylint](https://github.com/PyCQA/pylint) - looks for programming errors, helps enforcing a coding standard and sniffs for some code smells. It additionally includes `pyreverse` (an UML diagram generator) and `symilar` (a similarities checker). :star:2363
* [pyre-check](https://github.com/facebook/pyre-check) - A fast, scalable type checker for large Python codebases :star:3047
* [pyright](https://github.com/Microsoft/pyright) - Static type checker for Python, created to address gaps in existing tools like mypy. :star:4514
* [pyroma](https://github.com/regebro/pyroma) - rate how well a Python project complies with the best practices of the Python packaging ecosystem, and list issues that could be improved :star:74
* [PyT - Python Taint](https://github.com/python-security/pyt) - A static analysis tool for detecting security vulnerabilities in Python web applications. :star:1858
* [pytype](https://github.com/google/pytype) - A static type analyzer for Python code. :star:2205
* [radon](https://github.com/rubik/radon) - a Python tool that computes various metrics from the source code :star:1006
* [vulture](https://github.com/jendrikseipp/vulture) - find unused classes, functions and variables in Python code :star:684
* [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) - the strictest and most opinionated python linter ever :star:448
* [wily](https://github.com/tonybaloney/wily) - a command-line tool for archiving, exploring and graphing the complexity of Python source code :star:414
* [xenon](https://github.com/rubik/xenon) - monitor code complexity using [`radon`](https://github.com/rubik/radon) :star:1006

## Python wrappers

* [ciocheck](https://github.com/ContinuumIO/ciocheck) - linter, formatter and test suite helper. As a linter, it is a wrapper around `pep8`, `pydocstyle`, `flake8`, and `pylint`. :star:21
* [flake8](https://github.com/PyCQA/flake8) - a wrapper around `pyflakes`, `pycodestyle` and `mccabe` :star:690
* [multilint](https://github.com/adamchainz/multilint) - a wrapper around `flake8`, `isort` and `modernize` :star:20
* [prospector](https://github.com/PyCQA/prospector) - a wrapper around `pylint`, `pep8`, `mccabe` and others :star:1161

## R

* [cyclocomp](https://github.com/MangoTheCat/cyclocomp) - Quantifies the cyclomatic complexity of R functions / expressions. :star:21
* [goodpractice](http://mangothecat.github.io/goodpractice/) - Analyses the source code for R packages and provides best-practice recommendations.
* [lintr](https://github.com/jimhester/lintr) - Static Code Analysis for R. :star:635
* [styler](https://styler.r-lib.org/) - Formatting of R source code files and pretty-printing of R code.

## RPG

* [SourceMeter](https://www.sourcemeter.com/resources/rpg/) :copyright: - Static Code Analysis for RPG III and RPG IV versions (including free-form)

## Ruby

* [brakeman](https://github.com/presidentbeef/brakeman) - A static analysis security vulnerability scanner for Ruby on Rails applications :star:5523
* [cane](https://github.com/square/cane) - Code quality threshold checking as part of your build :star:1340
* [dawnscanner](https://github.com/thesp0nge/dawnscanner) - a static analysis security scanner for ruby written web applications. It supports Sinatra, Padrino and Ruby on Rails frameworks. :star:606
* [flay](https://github.com/seattlerb/flay) - Flay analyzes code for structural similarities. :star:575
* [flog](https://github.com/seattlerb/flog) - Flog reports the most tortured code in an easy to read pain report. The higher the score, the more pain the code is in. :star:660
* [laser](https://github.com/michaeledgar/laser) - Static analysis and style linter for Ruby code. :star:390
* [pelusa](https://github.com/codegram/pelusa) - Static analysis Lint-type tool to improve your OO Ruby code :star:447
* [quality](https://github.com/apiology/quality) - Runs quality checks on your code using community tools, and makes sure your numbers don't get any worse over time. :star:145
* [Querly](https://github.com/soutaro/querly) - Pattern Based Checking Tool for Ruby :star:178
* [Railroader](https://railroader.org/) - An open source static analysis security vulnerability scanner for Ruby on Rails applications.
* [reek](https://github.com/troessner/reek) - Code smell detector for Ruby :star:3151
* [RuboCop](https://github.com/rubocop-hq/rubocop) - A Ruby static code analyzer, based on the community Ruby style guide. :star:10323
* [Rubrowser](https://github.com/blazeeboy/rubrowser) - Ruby classes interactive dependency graph generator. :star:462
* [ruby-lint](https://github.com/YorickPeterse/ruby-lint) - Static code analysis for Ruby :star:730
* [rubycritic](https://github.com/whitesmith/rubycritic) - A Ruby code quality reporter :star:2394
* [SandiMeter](https://github.com/makaroni4/sandi_meter) - Static analysis tool for checking Ruby code for Sandi Metz' rules. :star:739
* [Sorbet](https://github.com/sorbet/sorbet) - A fast, powerful type checker designed for Ruby :star:1712

## Rust

* [cargo-audit](https://github.com/RustSec/cargo-audit) - Audit Cargo.lock for crates with security vulnerabilities reported to the [RustSec Advisory Database](https://github.com/RustSec/advisory-db/). :star:399
* [cargo-inspect](https://github.com/mre/cargo-inspect) - Inspect Rust code without syntactic sugar to see what the compiler does behind the curtains. :star:190
* [clippy](https://github.com/Manishearth/rust-clippy) - A code linter to catch common mistakes and improve your Rust code :star:12
* [electrolysis](https://github.com/Kha/electrolysis) - A tool for formally verifying Rust programs by transpiling them into definitions in the Lean theorem prover. :star:210
* [herbie](https://github.com/mcarton/rust-herbie-lint) - Adds warnings or errors to your crate when using a numerically unstable floating point expression. :star:156
* [linter-rust](https://github.com/AtomLinter/linter-rust) - Linting your Rust-files in Atom, using rustc and cargo :star:41
* [Rust Language Server](https://github.com/rust-lang-nursery/rls) - Supports functionality such as 'goto definition', symbol search, reformatting, and code completion, and enables renaming and refactorings. :star:2574
* [rustfix](https://github.com/killercup/rustfix) - read and apply the suggestions made by rustc (and third-party lints, like those offered by clippy). :star:2

## Scala

* [linter](https://github.com/HairyFotr/linter) - Linter is a Scala static analysis compiler plugin which adds compile-time checks for various possible bugs, inefficiencies, and style problems. :star:270
* [Scalastyle](http://www.scalastyle.org) - Scalastyle examines your Scala code and indicates potential problems with it.
* [scapegoat](https://github.com/sksamuel/scapegoat) - Scala compiler plugin for static code analysis :star:327
* [WartRemover](https://github.com/puffnfresh/wartremover) - a flexible Scala code linting tool. :star:889
* [Xanitizer](https://xanitizer.com/) - Xanitizer finds security vulnerabilities in Java/Scala web applications.

## Shell

* [i-Code CNES for Shell](https://github.com/lequal/i-CodeCNES) - An open source static code analysis tool for Shell and Fortran (77 and 90). :star:28
* [shellcheck](https://github.com/koalaman/shellcheck) - ShellCheck, a static analysis tool that gives warnings and suggestions for bash/sh shell scripts :star:16754

## Solidity

* [slither](https://github.com/trailofbits/slither) - Static analysis framework that runs a suite of vulnerability detectors, prints visual information about contract details, and provides an API to easily write custom analyses :star:359
* [solium](https://github.com/duaraghav8/Solium) - Solium is a linter to identify and fix style and security issues in Solidity smart contracts :star:653

## SQL

* [sqlcheck](https://github.com/jarulraj/sqlcheck-old) - Automatically identify anti-patterns in SQL queries :star:1792
* [sqlint](https://github.com/purcell/sqlint) - Simple SQL linter :star:275
* [tsqllint](https://github.com/tsqllint/tsqllint) - T-SQL-specific linter :star:77
* [TSqlRules](https://github.com/ashleyglee/TSqlRules) - TSQL Static Code Analysis Rules for SQL Server :star:13

## Swift

* [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) - A library and command-line formatting tool for reformatting Swift code :star:3309
* [SwiftLint](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions :star:12517
* [Tailor](https://github.com/sleekbyte/tailor) - A static analysis and lint tool for source code written in Apple's Swift programming language. :star:1316

## Tcl

* [Frink](https://catless.ncl.ac.uk/Programs/Frink/) - A Tcl formatting and static check program (can prettify the program, minimise, obfuscate or just sanity check it).
* [Nagelfar](https://sourceforge.net/projects/nagelfar/) - A static syntax checker for Tcl
* [tclchecker](https://github.com/ActiveState/tdk/blob/master/docs/3.0/TDK_3.0_Checker.txt) - A static syntax analysis module (as part of [TDK](https://github.com/ActiveState/tdk)). :star:25

## TypeScript

* [Codelyzer](https://github.com/mgechev/codelyzer) - A set of tslint rules for static code analysis of Angular 2 TypeScript projects. :star:2151
* [TSLint](https://github.com/palantir/tslint) - An extensible linter for the TypeScript language. :star:5440
* [tslint-clean-code](https://github.com/Glavin001/tslint-clean-code) - A set of TSLint rules inspired by the Clean Code handbook. :star:131
* [tslint-microsoft-contrib](https://github.com/Microsoft/tslint-microsoft-contrib) - A set of tslint rules for static code analysis of TypeScript projects maintained by Microsoft. :star:635

## VBScript

* [Test Design Studio](http://patterson-consulting.net/tds) :copyright: - A full IDE with static code analysis for Micro Focus Unified Functional Testing VBScript-based automated tests.

# Multiple languages

* [AppChecker](https://npo-echelon.ru/en/solutions/appchecker.php) :copyright: - Static analysis for C/C++/C#, PHP and Java
* [Application Inspector](https://www.ptsecurity.com/ww-en/products/ai/) :copyright: - Commercial Static Code Analysis which generates exploits to verify vulnerabilities. Supports: Java (including JSP and JSF), C#, VB.Net, ASP.NET, Php, JavaScript, Objective-C, Swift, C\C++, SQL (PL/SQL. T-SQL. MySQL), HTML5
* [AppScan Source](https://www.hcltechsw.com/wps/portal/products/appscan/home) :copyright: - Commercial Static Code Analysis. Supports: Microsoft .NET Framework (C#, ASP.NET, VB.NET), ASP (JavaScript/VBScript), C/C++, COBOL, ColdFusion, JavaScript, JavaServer Pages (JSP), Java™ (including support for Android APIs), Perl, PHP, PL/SQL, T-SQL, Visual Basic 6
* [APPscreener](https://appscreener.us) :copyright: - Static code analysis for binary and source code - Java/Scala, PHP, Javascript, C#, PL/SQL, Python, T-SQL, C/C++, ObjectiveC/Swift, Visual Basic 6.0, Ruby, Delphi, ABAP, HTML5 and Solidity
* [ArchUnit](https://www.archunit.org/) - Unit test your Java or Kotlin architecture
* [Axivion Bauhaus Suite](https://www.axivion.com/en/products-services-9#products_bauhaussuite) :copyright: - Tracks down error-prone code locations, style violations, cloned or dead code, cyclic dependencies and more for C/C++, C#/.NET, Java and Ada 83/Ada 95
* [Checkmarx CxSAST](https://www.checkmarx.com/products/static-application-security-testing/) :copyright: - Commercial Static Code Analysis which doesn't require pre-compilation. Supports: Android (Java), Apex and VisualForce, ASP, C#, C/C++, Go, Groovy, HTML5, Java, JavaScript, Node.js, Objective C, Perl, PhoneGap, PHP, Python, Ruby, Scala, Swift, VB.NET, VB6, VBScript
* [coala](https://coala.io/) - Language independent framework for creating code analysis - supports [over 60 languages](https://coala.io/languages) by default
* [Cobra](http://spinroot.com/cobra/) :copyright: - Structural source code analyzer by NASA's Jet Propulsion Laboratory. Supports C, C++, Ada, and Python.
* [codeburner](https://github.com/groupon/codeburner) - Provides a unified interface to sort and act on the issues it finds :star:80
* [CodeFactor](https://codefactor.io) :copyright: - Static Code Analysis for C#, C, C++, CoffeeScript, CSS, Groovy, GO, JAVA, JavaScript, Less, Python, Ruby, Scala, SCSS, TypeScript.
* [CodeIt.Right](https://submain.com/products/codeit.right.aspx) :copyright: - CodeIt.Right&trade; provides a fast, automated way to ensure that your source code adheres to (your) predefined design and style guidelines as well as best coding practices. Supported languages: C#, VB.NET.
* [CodeScene](https://empear.com/) :copyright: - CodeScene prioritizes technical debt, finds social patterns and identifies hidden risks in your code.
* [cqc](https://github.com/xcatliu/cqc) - Check your code quality for js, jsx, vue, css, less, scss, sass and styl files. :star:293
* [Coverity](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: - Synopsys Coverity supports 20 languages and over 70 frameworks including Ruby on rails, Scala, PHP, Python, JavaScript, TypeScript, Java, Fortran, C, C++, C#, VB.NET.
* [DeepSource](https://deepsource.io/) :copyright: - In-depth static analysis to monitor source code quality and security. Supports Python and Go and can detect 600+ types of issues in verticals of bug risks, security, anti-patterns, performance, documentation and style. Native integration with GitHub.
* [Depends](https://github.com/multilang-depends/depends) - Analyses the comprehensive dependencies of code elements for Java, C/C++, Ruby. :star:49
* [DevSkim](https://github.com/microsoft/devskim) - Regex-based static analysis tool for Visual Studio, VS Code, and Sublime Text - C/C++, C#, PHP, ASP, Python, Ruby, Java, and others. :star:304
* [Fortify](https://software.microfocus.com/en-us/products/static-code-analysis-sast/overview) :copyright: A commercial static analysis platform that supports the scanning of C/C++, C#, VB.NET, VB6, ABAP/BSP, ActionScript, Apex, ASP.NET, Classic ASP, VB Script, Cobol, ColdFusion, HTML, Java, JS, JSP, MXML/Flex, Objective-C, PHP, PL/SQL, T-SQL, Python (2.6, 2.7), Ruby (1.9.3), Swift, Scala, VB, and XML.
* [Goodcheck](https://github.com/sideci/goodcheck) - Regexp based customizable linter :star:85
* [graudit](https://github.com/wireghoul/graudit) - Grep rough audit - source code auditing tool - C/C++, PHP, ASP, C#, Java, Perl, Python, Ruby :star:422
* [Hound CI](https://houndci.com/) - Comments on style violations in GitHub pull requests. Supports Coffeescript, Go, HAML, JavaScript, Ruby, SCSS and Swift.
* [imhotep](https://github.com/justinabrahms/imhotep) - Comment on commits coming into your repository and check for syntactic errors and general lint warnings. :star:210
* [Infer](https://github.com/facebook/infer) - A static analyzer for Java, C and Objective-C :star:10254
* [Klocwork](http://www.klocwork.com/products-services/klocwork) :copyright: - Quality and Security Static analysis for  C/C++, Java and C#
* [Kiuwan](https://www.kiuwan.com/code-security-sast/) :copyright: - Identify and remediate cyber threats in a blazingly fast, collaborative environment, with seamless integration in your SDLC. Python, C\C++, Java, C#, PHP and more
* [oclint](https://github.com/oclint/oclint) - A static source code analysis tool to improve quality and reduce defects for C, C++ and Objective-C :star:2980
* [pfff](https://github.com/facebook/pfff) - Facebook's tools for code analysis, visualizations, or style-preserving source transformation for many languages :star:2391
* [PMD](https://pmd.github.io/) - A source code analyzer for Java, Javascript, PLSQL, XML, XSL and others
* [Pronto](https://github.com/prontolabs/pronto) - Quick automated code review of your changes. Supports more than 40 runners for various languages, including Clang, Elixir, JavaSCript, PHP, Ruby and more :star:2153
* [pre-commit](https://github.com/pre-commit/pre-commit) - A framework for managing and maintaining multi-language pre-commit hooks. :star:3445
* [PT.PM](https://github.com/PositiveTechnologies/PT.PM) - An engine for searching patterns in the source code, based on Unified AST or UST. At present time C#, Java, PHP, PL/SQL, T-SQL, and JavaScript are supported. Patterns can be described within the code or using a DSL. :star:52
* [PVS-Studio](https://www.viva64.com/en/pvs-studio/) :copyright: - a ([conditionally free](https://www.viva64.com/en/b/0614/) for FOSS and individual developers) static analysis of C, C++, C# and Java code. For advertising purposes [you can propose a large FOSS project for analysis by PVS employees](https://github.com/viva64/pvs-studio-check-list). Supports CWE mapping, MISRA and CERT coding standards.
* [Reviewdog](https://github.com/haya14busa/reviewdog) - A tool for posting review comments from any linter in any code hosting service. :star:1256
* [Security Code Scan](https://security-code-scan.github.io/) - Security code analyzer for C# and VB.NET. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.
* [Semmle QL and LGTM](https://semmle.com/) :copyright: - Find security vulnerabilities, variants, and critical code quality issues using queries over source code. Automatic PR code review; free for public GitHub/Bitbucket repo: [LGTM.com](https://LGTM.com).
* [shipshape](https://github.com/google/shipshape) - Static program analysis platform that allows custom analyzers to plug in through a common interface :star:223
* [SonarQube](http://www.sonarqube.org/) - SonarQube is an open platform to manage code quality.
* [STOKE](https://github.com/StanfordPL/stoke) - a programming-language agnostic stochastic optimizer for the x86_64 instruction set. It uses random search to explore the extremely high-dimensional space of all possible program transformations :star:410
* [Synopsys](https://www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: - A commercial static analysis platform that allows for scanning of multiple languages (C/C++, Android, C#, Java, JS, PHP, Python, Node.JS, Ruby, Fortran, and Swift)
* [TscanCode](https://github.com/Tencent/TscanCode) - A fast and accurate static analysis solution for C/C++, C#, Lua codes provided by Tencent. Using GPLv3 license. :star:762
* [Undebt](https://github.com/Yelp/undebt) - Language-independent tool for massive, automatic, programmable refactoring based on simple pattern definitions :star:1592
* [Veracode](http://www.veracode.com/products/static-analysis-sast/static-code-analysis) :copyright: - Find flaws in binaries and bytecode without requiring source. Support all major programming languages: Java, .NET, JavaScript, Swift, Objective-C, C, C++ and more.
* [WALA](http://wala.sourceforge.net/wiki/index.php/Main_Page) - static analysis capabilities for Java bytecode and related languages and for JavaScript
* [WhiteHat Application Security Platform](https://www.whitehatsec.com/products/static-application-security-testing/) :copyright: - WhiteHat Scout (for Developers) combined with WhiteHat Sentinel Source (for Operations) supporting WhiteHat Top 40 and OWASP Top 10. Language support for: Java, C#(.NET), ASP.NET, PHP, JavaScript, Node.js, Objective-C, Android, HTML5, TypeScript. 
* [Wotan](https://github.com/fimbullinter/wotan) - Pluggable TypeScript and JavaScript linter :star:238
* [XCode](https://developer.apple.com/xcode/) :copyright: - XCode provides a pretty decent UI for [Clang's](http://clang-analyzer.llvm.org/xcode.html) static code analyzer (C/C++, Obj-C)

# Other

## Build tools

* [checkmake](https://github.com/mrtazz/checkmake) - Linter / Analyzer for Makefiles :star:263
* [codechecker](https://github.com/Ericsson/codechecker) - a defect database and viewer extension for the Clang Static Analyzer :star:758

## Binaries

* [BinSkim](https://github.com/Microsoft/binskim) - A binary static analysis tool that provides security and correctness results for Windows portable executables. :star:361
* [cwe_checker](https://github.com/fkie-cad/cwe_checker) - cwe_checker finds vulnerable patterns in binary executables. :star:170
* [Jakstab](https://github.com/jkinder/jakstab) - Jakstab is an Abstract Interpretation-based, integrated disassembly and static analysis framework for designing analyses on executables and recovering reliable control flow graphs. :star:96
* [Manalyze](https://github.com/JusticeRage/Manalyze) - A static analyzer, which checks portable executables for malicious content. :star:548
* [Twiggy](https://github.com/rustwasm/twiggy) - Analyzes a binary's call graph to profile code size. The goal is to slim down binaries. :star:448


## Containers

* [anchore](https://anchore.io/) - Discover, analyze, and certify container images
* [clair](https://github.com/coreos/clair) - Vulnerability Static Analysis for Containers :star:5778
* [collector](https://github.com/banyanops/collector) - Run arbitrary scripts inside containers, and gather useful information :star:242
* [dagda](https://github.com/eliasgranderubio/dagda) - Perform static analysis of known vulnerabilities in docker images/containers. :star:588
* [Docker Label Inspector](https://github.com/garethr/docker-label-inspector) - Lint and validate Dockerfile labels :star:72
* [Haskell Dockerfile Linter](https://github.com/lukasmartinelli/hadolint) - A smarter Dockerfile linter that helpsyou build best practice Docker images :star:2655
* [kube-score](https://github.com/zegl/kube-score) - Static code analysis of your Kubernetes object definitions. :star:486


## Config Files

* [dotenv-linter](https://github.com/wemake-services/dotenv-linter) - Linting dotenv files like a charm. :star:112
* [gixy](https://github.com/yandex/gixy) - a tool to analyze Nginx configuration. The main goal is to prevent misconfiguration and automate flaw detection. :star:6138

## Configuration Management

* [ansible-lint](https://github.com/willthames/ansible-lint) - Checks playbooks for practices and behaviour that could potentially be improved :star:1820
* [cfn-lint](https://github.com/awslabs/cfn-python-lint) - AWS Labs CloudFormation linter. :star:889
* [cfn_nag](https://github.com/stelligent/cfn_nag) - A linter for AWS CloudFormation templates. :star:503
* [cookstyle](https://docs.chef.io/cookstyle.html) - Cookstyle is a linting tool based on the RuboCop Ruby linting tool for Chef cookbooks
* [foodcritic](http://www.foodcritic.io/) - A lint tool that checks Chef cookbooks for common problems.
* [Puppet Lint](https://github.com/rodjek/puppet-lint) - Check that your Puppet manifests conform to the style guide. :star:735
* [terrascan](https://github.com/cesar-rodriguez/terrascan) - Collection of security and best practice tests for static code analysis of Terraform templates. :star:255
* [tflint](https://github.com/wata727/tflint) - A Terraform linter for detecting errors that can not be detected by `terraform plan`. :star:1051


## CSS

* [CSS Stats](https://github.com/cssstats/cssstats) - Potentially interesting stats on stylesheets :star:2458
* [CSScomb](https://github.com/csscomb/csscomb.js) - a coding style formatter for CSS. Supports own configurations to make style sheets beautiful and consistent :star:2842
* [CSSLint](https://github.com/CSSLint/csslint) - Does basic syntax checking and finds problematic patterns or signs of inefficiency :star:4459
* [GraphMyCSS.com](https://graphmycss.com) - CSS Specificity Graph Generator
* [Parker](https://github.com/katiefenn/parker) - Stylesheet analysis tool :star:2458
* [Project Wallace CSS Analyzer](https://github.com/projectwallace/css-analyzer) - Analytics for CSS, part of [Project Wallace](https://www.projectwallace.com)
* [sass-lint](https://github.com/sasstools/sass-lint) - A Node-only Sass linter for both sass and scss syntax. :star:1731
* [scsslint](https://github.com/brigade/scss-lint) - Linter for SCSS files :star:3385
* [Specificity Graph](https://github.com/pocketjoso/specificity-graph) - CSS Specificity Graph Generator :star:650
* [Stylelint](http://stylelint.io/) - Linter for SCSS/CSS files

## Gherkin

* [gherkin-lint](https://github.com/vsiakka/gherkin-lint) - A linter for the Gherkin-Syntax written in Javascript. :star:67

## HTML

* [HTML Inspector](https://github.com/philipwalton/html-inspector) - HTML Inspector is a code quality tool to help you and your team write better markup. :star:2339
* [HTML Tidy](http://www.html-tidy.org/) - Corrects and cleans up HTML and XML documents by fixing markup errors and upgrading legacy code to modern standards.
* [HTMLHint](https://github.com/yaniswang/HTMLHint) - A Static Code Analysis Tool for HTML :star:2232
* [Polymer-analyzer](https://github.com/Polymer/polymer-analyzer) - A static analysis framework for Web Components. :star:163


## IDE Plugins

* [ale](https://github.com/w0rp/ale) - Asynchronous Lint Engine for Vim and NeoVim with support for many languages :star:8436
* [Attackflow Extension](https://www.attackflow.com/Extension) :copyright: - Attackflow plugin for Visual Studio, which enables developers to find critical security bugs at real time in the source code without any prior knowledge.
* [DevSkim](https://github.com/Microsoft/DevSkim) - Inline, realtime security analysis. Works with multiple programming languages and IDEs (VS, VS Code, Sublime Text, ...). :star:304
* [Puma Scan](https://github.com/pumasecurity/puma-scan) - Puma Scan provides real time secure code analysis for common vulnerabilities (XSS, SQLi, CSRF, LDAPi, crypto, deserialization, etc.) as development teams write code in Visual Studio. :star:325
* [Security Code Scan](https://security-code-scan.github.io/) - Security code analyzer for C# and VB.NET that integrates into Visual Studio 2015 and newer. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.
* [vint](https://github.com/Kuniwak/vint) - Fast and Highly Extensible Vim script Language Lint implemented by Python. :star:503

## LaTeX

* [ChkTeX](http://www.nongnu.org/chktex/) - A linter for LaTex which catches some typographic errors LaTeX oversees.
* [lacheck](https://www.ctan.org/pkg/lacheck) - A tool for finding common mistakes in LaTeX documents.

## Makefiles

* [portlint](https://www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) - A verifier for FreeBSD and DragonFlyBSD port directories.

## Markdown

* [markdownlint](https://github.com/DavidAnson/markdownlint) - Node.js -based style checker and lint tool for Markdown/CommonMark files. :star:1606
* [mdl](https://github.com/mivok/markdownlint) - A tool to check Markdown files and flag style issues. :star:753

## Mobile

* [android-lint-summary](https://github.com/passy/android-lint-summary) - Combines lint errors of multiple projects into one output, check lint results of multiple sub-projects at once. :star:174
* [FlowDroid](https://github.com/secure-software-engineering/soot-infoflow-android) - static taint analysis tool for Android applications :star:243
* [paprika](https://github.com/GeoffreyHecht/paprika) - A toolkit to detect some code smells in analyzed Android applications. :star:57
* [qark](https://github.com/linkedin/qark) - Tool to look for several security related Android application vulnerabilities :star:2061

## Packages

* [lintian](https://github.com/Debian/lintian) - Static analysis tool for Debian packages :star:39
* [rpmlint](https://github.com/rpm-software-management/rpmlint) - Tool for checking common errors in rpm packages :star:54

## Supporting Tools

* [LibVCS4j](https://github.com/uni-bremen-agst/libvcs4j) - A Java library that allows existing tools to analyse the evolution of software systems by providing a common API for different version control systems and issue trackers. :star:11
* [Violations Lib](https://github.com/tomasbjerre/violations-lib) - Java library for parsing report files from static code analysis. Used by a bunch of Jenkins, Maven and Gradle plugins. :star:63

## Template-Languages

* [ember-template-lint](https://github.com/rwjblue/ember-template-lint) - Linter for Ember or Handlebars templates. :star:183
* [haml-lint](https://github.com/brigade/haml-lint) - Tool for writing clean and consistent HAML :star:220
* [slim-lint](https://github.com/sds/slim-lint) - Configurable tool for analyzing Slim templates :star:142
* [yamllint](https://github.com/adrienverge/yamllint) - Checks YAML files for syntax validity, key repetition and cosmetic problems such as lines length, trailing spaces, and indentation. :star:835

## Translation

* [dennis](https://github.com/willkg/dennis/) - A set of utilities for working with PO files to ease development and improve quality. :star:39

## Writing

* [After the Deadline](https://afterthedeadline.com/) :warning: - spell, style and grammar checker
* [codespell](https://github.com/codespell-project/codespell) - check code for common misspellings :star:235
* [languagetool](https://github.com/languagetool-org/languagetool) - Style and grammar checker for 25+ languages. It finds many errors that a simple spell checker cannot detect. :star:3124
* [misspell-fixer](https://github.com/vlajos/misspell-fixer) - Quick tool for fixing common misspellings, typos in source code :star:114
* [Misspelled Words In Context](https://github.com/jwilk/mwic) - a spell-checker that groups possible misspellings and shows them in their contexts :star:29
* [proselint](https://github.com/amperser/proselint/) - a linter for English prose with a focus on writing style instead of grammar. :star:3204
* [vale](https://github.com/ValeLint/vale) - A customizable, syntax-aware linter for prose. :star:470
* [write-good](https://github.com/btford/write-good) - A linter with a focus on eliminating "weasel words". :star:3759

## Web services
* [Codacy](https://www.codacy.com/) :copyright: - Code Analysis to ship Better Code, Faster.
* [Code Climate](https://codeclimate.com/) :copyright: - The open and extensible static analysis platform, for everyone.
* [Code Inspector](https://www.code-inspector.com) :copyright: - Code quality and technical debt management platform that supports 10+ languages.
* [Codeac](https://www.codeac.io?ref=awesome-static-analysis) :copyright: - Automated code review tool integrates with GitHub, Bitbucket and GitLab (even self-hosted). Available for JavaScript, TypeScript, Python, Ruby, Go, PHP, Java, Docker, and more. (open-source free)
* [CodeFactor](https://codefactor.io) :copyright: - Automated Code Analysis for repos on GitHub or BitBucket.
* [CodeFlow](https://www.getcodeflow.com) :copyright: - Automated code analysis tool to deal with technical depth. Integrates with Bitbucket and Gitlab. (free for Open Source Projects)
* [Embold](https://embold.io) :copyright: - Intelligent software analytics platform that identifies design issues, code issues, duplication and metrics. Supports Java, C, C++, C#, JavaScript, TypeScript, Python, Go, Kotlin and more.
* [kiuwan](https://www.kiuwan.com/) :copyright: - Software Analytics in the Cloud supporting more than 22 programming languages.
* [Landscape](https://landscape.io/) :copyright: - Static code analysis for Python
* [Layered Insight](https://layeredinsight.com/) :copyright: - Container native application protection to provide visibility and control of containerized applications.
* [LGTM.com](https://lgtm.com/) :copyright: - Deep code analysis for GitHub and Bitbucket to find security vulnerabilities and critical code quality issues (using Semmle QL). Automatic code review for pull requests; free for public repositories.
* [Nitpick CI](https://nitpick-ci.com) :copyright: - Automated PHP code review
* [PullRequest](https://www.pullrequest.com) :copyright: - Code review as a service with built-in static analysis
* [QuantifiedCode](https://www.quantifiedcode.com/) - Automated code review & repair
* [Reshift](https://softwaresecured.com/reshift/) :copyright: - A source code analysis tool for detecting and managing Java security vulnerabilities.
* [Scrutinizer](https://scrutinizer-ci.com/) :copyright: - A proprietary code quality checker that can be integrated with GitHub
* [SensioLabs Insight](https://insight.sensiolabs.com/) :copyright: - Detect security risks, find bugs and provide actionable metrics for PHP projects
* [Sider](https://sider.review) :copyright: - An automated code reviewing tool. Improving developers' productivity.
* [Snyk](https://snyk.io/) :copyright: - Vulnerability scanner for dependencies of node.js apps (free for Open Source Projects)
* [SonarCloud](https://sonarcloud.io) :copyright: - Multilanguage cloud-based static code analysis. History, trends, security hot-spots, pull request analysis and more. Free for open source.
* [Teamscale](http://www.teamscale.com/) :copyright: - Static and dynamic analysis tool supporting more than 25 languages and direct IDE integration. Free hosting for Open Source projects available on request. Free academic licenses available.
* [Upsource](https://www.jetbrains.com/upsource/) :copyright: - Code review tool with static code analysis and code-aware navigation for Java, PHP, JavaScript and Kotlin.

# More collections

* [go-tools](https://github.com/dominikh/go-tools) - A collection of tools and libraries for working with Go code, including linters and static analysis :star:2695
* [linters](https://github.com/mcandre/linters) - An introduction to static code analysis :star:272
* [php-static-analysis-tools](https://github.com/exakat/php-static-analysis-tools) - A reviewed list of useful PHP static analysis tools :star:2105
* [Tools for C/C++](https://www.peerlyst.com/posts/a-list-of-static-analysis-tools-for-c-c-peerlyst?utm_source=twitter&utm_medium=social&utm_content=peerlyst_post&utm_campaign=peerlyst_resources) - A list of static analysis tools for C/C++
* [Tools for Tcl](https://wiki.tcl-lang.org/page/Static+syntax+analysis#95329c336da897c3dea8ab434ca30575f4529bf6f514c1519881bd126e1d1423) - A wiki-page with several Tcl checker and static syntax analysis tools.
* [Wikipedia](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis) - A list of tools for static code analysis.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Matthias Endler](https://endler.dev) has waived all copyright and related or neighboring rights to this work.
Title image [Designed by Freepik](http://www.freepik.com).


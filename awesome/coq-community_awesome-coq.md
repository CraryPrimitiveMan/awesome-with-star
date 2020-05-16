# Information comes from [coq-community/awesome-coq](https://github.com/coq-community/awesome-coq)
# Awesome Coq [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="coq-logo.svg" align="right" width="100" title="Awesome Coq is a coq-community project">](https://github.com/coq-community/manifesto)

> A curated list of awesome Coq libraries, plugins, tools, and resources.

The [Coq proof assistant](https://coq.inria.fr) provides a formal language to write mathematical definitions, executable algorithms, and theorems, together with an environment for semi-interactive development of machine-checked proofs.

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## Contents

- [Projects](#projects)
  - [Frameworks](#frameworks)
  - [User Interfaces](#user-interfaces)
  - [Libraries](#libraries)
  - [Package and Build Management](#package-and-build-management)
  - [Plugins](#plugins)
  - [Tools](#tools)
  - [Type Theory and Mathematics](#type-theory-and-mathematics)
  - [Verified Software](#verified-software)
- [Resources](#resources)
  - [Community](#community)
  - [Blogs](#blogs)
  - [Books](#books)
  - [Tutorials and Hints](#tutorials-and-hints)

---

## Projects

### Frameworks

- [CoqEAL](https://github.com/CoqEAL/CoqEAL) - Framework to ease change of data representations in proofs. :star:42
- [Fiat](https://github.com/mit-plv/fiat) - Mostly automated synthesis of correct-by-construction programs. :star:100
- [FreeSpec](https://github.com/ANSSI-FR/FreeSpec) - Framework for modularly verifying programs with effects and effect handlers. :star:40
- [Iris](https://iris-project.org) - Higher-order concurrent separation logic framework.
- [Q\*cert](https://querycert.github.io) - Platform for implementing and verifying query compilers.
- [Verdi](https://github.com/uwplse/verdi) - Framework for formally verifying distributed systems implementations. :star:481
- [VST](https://vst.cs.princeton.edu) - Toolchain for verifying C code inside Coq in a higher-order concurrent, impredicative separation logic that is sound w.r.t. the Clight language of the CompCert compiler.

### User Interfaces

- [CoqIDE](https://coq.inria.fr/refman/practical-tools/coqide.html) - Standalone graphical tool for interacting with Coq.
- [Coqtail](https://github.com/whonore/Coqtail) - Interface for Coq based on the Vim text editor. :star:54
- [Proof General](https://proofgeneral.github.io) - Generic interface for proof assistants based on the extensible, customizable text editor Emacs.
- [Company-Coq](https://github.com/cpitclaudel/company-coq) - IDE extensions for Proof General's Coq mode. :star:272
- [jsCoq](https://github.com/ejgallego/jscoq) - Port of Coq to JavaScript, which enables running Coq projects in a browser. :star:349
- [Jupyter kernel for Coq](https://github.com/EugeneLoy/coq_jupyter) - Coq support for the Jupyter Notebook web environment. :star:39
- [VSCoq](https://github.com/coq-community/vscoq) - Visual Studio Code extension. :star:91

### Libraries

- [ALEA](https://github.com/coq-community/alea) - Library for reasoning on randomized algorithms. :star:2
- [Bignums](https://github.com/coq/bignums) - Library of arbitrary large numbers. :star:16
- [CoLoR](http://color.inria.fr) - Library on rewriting theory, lambda-calculus and termination, with sub-libraries on common data structures extending the Coq standard library.
- [coq-haskell](https://github.com/jwiegley/coq-haskell) - Library smoothing the transition to Coq for Haskell users. :star:129
- [Coq-std++](https://gitlab.mpi-sws.org/iris/stdpp) - Extended alternative standard library for Coq.
- [ExtLib](https://github.com/coq-community/coq-ext-lib) - Collection of theories and plugins that may be useful in other Coq developments. :star:90
- [FCSL-PCM](https://github.com/imdea-software/fcsl-pcm) - Formalization of partial commutative monoids as used in verification of pointer-manipulating programs. :star:12
- [Flocq](http://flocq.gforge.inria.fr) - Formalization of floating-point computations.
- [Formalised Undecidable Problems](https://github.com/uds-psl/coq-library-undecidability) - Library of undecidable problems and reductions between them. :star:30
- [Hahn](https://github.com/vafeiadis/hahn) - Library for reasoning on lists and binary relations. :star:19
- [Metalib](https://github.com/plclub/metalib) - Library for programming language metatheory using locally nameless variable binding representations. :star:42
- [Monae](https://github.com/affeldt-aist/monae) - Monadic effects and equational reasoning. :star:33
- [Paco](http://plv.mpi-sws.org/paco/) - Library for parameterized coinduction.
- [Regular Language Representations](https://github.com/coq-community/reglang) - Translations between different definitions of regular languages, including regular expressions and automata. :star:16
- [Relation Algebra](https://github.com/damien-pous/relation-algebra) - Modular formalization of algebras with heterogeneous binary relations as models. :star:26
- [TLC](http://www.chargueraud.org/softs/tlc/) - Non-constructive alternative to Coq's standard library.

### Package and Build Management

- [coq_makefile](https://coq.inria.fr/refman/practical-tools/utilities.html) - Build tool distributed by Coq and based on generating a makefile.
- [Coq Package Index](https://coq.inria.fr/packages.html) - OPAM-based collection of Coq packages.
- [Docker-Coq](https://github.com/coq-community/docker-coq) - Docker images for many versions of Coq. :star:19
- [Docker-MathComp](https://github.com/math-comp/docker-mathcomp) - Docker images for many combinations of versions of Coq and the Mathematical Components library. :star:4
- [Docker-Coq-action](https://github.com/marketplace/actions/docker-coq-action) - GitHub container action that can be used with docker-coq or docker-mathcomp.
- [Dune](https://github.com/ocaml/dune) - Composable and opinionated build system for Coq and OCaml (former jbuilder). :star:932
- [Nix](https://nixos.org/nix/) - Package manager for Linux and other Unix systems, supporting atomic upgrades and rollbacks.
- [Nix Coq packages](https://nixos.org/nixos/packages.html?channel=nixpkgs-unstable&query=coqPackages) - Collection of Coq-related packages for Nix.
- [OPAM](https://opam.ocaml.org) - Flexible and Git-friendly package manager for OCaml with multiple compiler support.

### Plugins

- [AAC Tactics](https://github.com/coq-community/aac-tactics) - Tactics for rewriting universally quantified equations, modulo associativity and commutativity of some operator. :star:16
- [Coq-Elpi](https://github.com/LPCIC/coq-elpi) - Plugin for the Embeddable Lambda Prolog Interpreter. :star:39
- [CoqHammer](https://github.com/lukaszcz/coqhammer) - General-purpose automated reasoning hammer tool that combines learning from previous proofs with the translation of problems to automated provers and the reconstruction of found proofs. :star:131
- [Equations](https://github.com/mattam82/Coq-Equations) - Function definition package for Coq. :star:137
- [Gappa](https://gitlab.inria.fr/gappa/coq) - Tactic for discharging goals about floating-point arithmetic and round-off errors.
- [Ltac2](https://coq.inria.fr/refman/proof-engine/ltac2.html) - Experimental typed tactic language similar to Coq's classic Ltac language.
- [MetaCoq](https://github.com/MetaCoq/metacoq) - Project formalizing Coq in Coq and providing tools for manipulating Coq terms and developing certified plugins. :star:157
- [Mtac2](https://github.com/Mtac2/Mtac2) - Plugin adding typed tactics for backward reasoning. :star:38
- [Paramcoq](https://github.com/coq-community/paramcoq) - Plugin to generate parametricity translations of Coq terms. :star:31
- [QuickChick](https://github.com/QuickChick/QuickChick) - Plugin for randomized property-based testing. :star:169
- [SMTCoq](https://github.com/smtcoq/smtcoq) - Tool that checks proof witnesses coming from external SAT and SMT solvers. :star:75
- [Unicoq](https://github.com/unicoq/unicoq) - Plugin that replaces the existing unification algorithm with an enhanced one. :star:31

### Tools

- [CFML](https://gitlab.inria.fr/charguer/cfml2) - Tool for proving properties of OCaml programs in separation logic.
- [CoqOfOCaml](https://github.com/clarus/coq-of-ocaml) - Tool for generating idiomatic Coq from OCaml code. :star:96
- [coq-dpdgraph](https://github.com/Karmaki/coq-dpdgraph) - Tool for building dependency graphs between Coq objects. :star:51
- [coq-tools](https://github.com/JasonGross/coq-tools) - Scripts to help construct small reproducing examples of bugs, remove unneeded imports, etc. :star:20
- [Cosette](https://github.com/uwdb/Cosette) - Automated solver for reasoning about SQL query equivalences. :star:509
- [hs-to-coq](https://github.com/antalsz/hs-to-coq) - Converter from Haskell code to equivalent Coq code. :star:262
- [lngen](https://github.com/plclub/lngen) - Tool for generating locally nameless Coq definitions and proofs. :star:20
- [Menhir](http://gallium.inria.fr/~fpottier/menhir/) - Parser generator that can output Coq code for verified parsers.
- [mCoq](https://github.com/EngineeringSoftware/mcoq) - Mutation analysis tool for Coq projects. :star:14
- [Ott](https://www.cl.cam.ac.uk/~pes20/ott/) - Tool for writing definitions of programming languages and calculi that can be translated to Coq.
- [SerAPI](https://github.com/ejgallego/coq-serapi) - Library and tools for (de)serialization of Coq code to and from JSON and S-expressions. :star:69

### Type Theory and Mathematics

- [Analysis](https://github.com/math-comp/analysis) - Library for classical real analysis compatible with Mathematical Components. :star:63
- [Category Theory in Coq](https://github.com/jwiegley/category-theory) - Axiom-free formalization of category theory. :star:520
- [CoRN](https://github.com/coq-community/corn) - Library of constructive real analysis and algebra. :star:87
- [Coquelicot](https://gitlab.inria.fr/coquelicot/coquelicot) - Formalization of classical real analysis compatible with the standard library and focusing on usability.
- [Four Color Theorem](https://github.com/math-comp/fourcolor) - Formal proof of the Four Color Theorem, a landmark result of graph theory. :star:74
- [GeoCoq](https://github.com/GeoCoq/GeoCoq) - Formalization of geometry based on Tarski's axiom system. :star:110
- [Homotopy Type Theory](https://github.com/HoTT/HoTT) - Development of homotopy-theoretic ideas. :star:865
- [Infotheo](https://github.com/affeldt-aist/infotheo) - Formalization of information theory and linear error-correcting codes. :star:33
- [Mathematical Components](http://math-comp.github.io) - Formalization of mathematical theories, focusing in particular on group theory.
- [Math Classes](https://github.com/coq-community/math-classes) - Abstract interfaces for mathematical structures based on type classes. :star:131
- [Odd Order Theorem](https://github.com/math-comp/odd-order) - Formal proof of the Odd Order Theorem, a landmark result of finite group theory. :star:9
- [UniMath](https://github.com/UniMath/UniMath) - Library which aims to formalize a substantial body of mathematics using the univalent point of view. :star:619

### Verified Software

- [CompCert](http://compcert.inria.fr) - High-assurance compiler for almost all of the C language (ISO C99), generating efficient code for the PowerPC, ARM, RISC-V and x86 processors.
- [Fiat-Crypto](https://github.com/mit-plv/fiat-crypto) - Cryptographic primitive code generation. :star:243
- [Incremental Cycles](https://gitlab.inria.fr/agueneau/incremental-cycles) - Verified OCaml implementation of an algorithm for incremental cycle detection in graphs.
- [JSCert](https://github.com/jscert/jscert) - Coq specification of ECMAScript 5 (JavaScript) with verified reference interpreter. :star:183
- [lambda-rust](https://gitlab.mpi-sws.org/iris/lambda-rust) - Formal model of a Rust core language and type system, a logical relation for the type system, and safety proofs for some Rust libraries.
- [Verdi Raft](https://github.com/uwplse/verdi-raft) - Implementation of the Raft distributed consensus protocol, verified in Coq using the Verdi framework. :star:137

## Resources

### Community

- [Official Coq website](https://coq.inria.fr)
- [Official Coq manual](https://coq.inria.fr/refman/)
- [Official Coq Discourse forum](https://coq.discourse.group)
- [Official Coq Gitter chat](https://gitter.im/coq/coq)
- [Official Coq-Club mailing list](https://sympa.inria.fr/sympa/arc/coq-club)
- [Official Coq wiki](https://github.com/coq/coq/wiki) :star:2791
- [Official Coq Twitter](https://twitter.com/CoqLang)
- [coq-community package maintenance project](https://github.com/coq-community/manifesto) :star:50
- [Coq subreddit](https://www.reddit.com/r/coq/)
- [Coq tag on Stack Overflow](https://stackoverflow.com/questions/tagged/coq)
- [Coq tag on Theoretical Computer Science Stack Exchange](https://cstheory.stackexchange.com/questions/tagged/coq)
- [Mathematical Components wiki](https://github.com/math-comp/math-comp/wiki) :star:296

### Blogs

- [Coq Exchange: ideas and experiment reports about Coq](https://project.inria.fr/coqexchange/news/)
- [Gagallium](http://gallium.inria.fr/blog)
- [Gregory Malecha's blog](https://gmalecha.github.io)
- [Guillaume Claret's Coq blog](http://coq-blog.clarus.me)
- [Joachim Breitner's blog posts on Coq](http://www.joachim-breitner.de/blog/tag/Coq)
- [Poleiro: a Coq blog by Arthur Azevedo de Amorim](http://poleiro.info)
- [Ralf Jung's blog posts on Coq](https://www.ralfj.de/blog/categories/coq.html)

### Books

- [Coq'Art](https://www.labri.fr/perso/casteran/CoqArt/) - The first book dedicated to Coq.
- [Software Foundations](https://softwarefoundations.cis.upenn.edu) - Series of Coq-based textbooks on logic, functional programming, and foundations of programming languages, aimed at being accessible to beginners.
- [Certified Programming with Dependent Types](http://adam.chlipala.net/cpdt/) - Textbook about practical engineering with Coq which teaches advanced practical tricks and a very specific style of proof.
- [Program Logics for Certified Compilers](https://www.cambridge.org/us/academic/subjects/computer-science/programming-languages-and-applied-logic/program-logics-certified-compilers) - Book that explains how to construct program logics using separation logic, accompanied by a formal model in Coq which is applied to the Clight programming language and other examples.
- [Formal Reasoning About Programs](http://adam.chlipala.net/frap/) - Book that simultaneously provides a general introduction to formal logical reasoning about the correctness of programs and to using Coq for this purpose.
- [Programs and Proofs](https://ilyasergey.net/pnp/) - Book that gives a brief and practically-oriented introduction to interactive proofs in Coq which emphasizes the computational nature of inductive reasoning about decidable propositions via a small set of primitives from the SSReflect proof language.
- [Computer Arithmetic and Formal Proofs](http://iste.co.uk/book.php?id=1238) - Book that describes how to formally specify and verify floating-point algorithms in Coq using the Flocq library.
- [The Mathematical Components book](https://math-comp.github.io/mcb/) - Book oriented towards mathematically inclined users, focusing on the Mathematical Components library and the SSReflect proof language.

### Tutorials and Hints

- [CodeWars' Coq kata](https://www.codewars.com/kata/search/coq) - Online proving challenges.
- [Coq'Art Exercises and Tutorials](https://github.com/coq-community/coq-art) - Coq code and exercises from the Coq'Art book, including additional tutorials. :star:21
- [Coq in a Hurry](http://cel.archives-ouvertes.fr/inria-00001173) - Introduction to how Coq can be used to define logical concepts and functions and reason about them.
- [Lemma Overloading](https://github.com/coq-community/lemma-overloading) - Demonstration of design patterns for programming and proving with canonical structures. :star:17
- [Mike Nahas's Coq Tutorial](https://mdnahas.github.io/doc/nahas_tutorial.html) - Basics of using Coq to write formal proofs.
- [Tricks in Coq](https://github.com/tchajed/coq-tricks) - Tips, tricks, and features that are hard to discover. :star:233


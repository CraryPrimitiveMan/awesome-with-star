# Information comes from [akullpp/awesome-java](https://github.com/akullpp/awesome-java)
# Awesome Java [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Java frameworks, libraries and software.

## Contents

- [Projects](#projects)
  - [Bean Mapping](#bean-mapping)
  - [Build](#build)
  - [Bytecode Manipulation](#bytecode-manipulation)
  - [Caching](#caching)
  - [Cluster Management](#cluster-management)
  - [Code Analysis](#code-analysis)
  - [Code Coverage](#code-coverage)
  - [Code Generators](#code-generators)
  - [Command-line Argument Parsers](#command-line-argument-parsers)
  - [Compiler-compiler](#compiler-compiler)
  - [Configuration](#configuration)
  - [Constraint Satisfaction Problem Solver](#constraint-satisfaction-problem-solver)
  - [CSV](#csv)
  - [Data structures](#data-structures)
  - [Database](#database)
  - [Date and Time](#date-and-time)
  - [Dependency Injection](#dependency-injection)
  - [Development](#development)
  - [Distributed Applications](#distributed-applications)
  - [Distributed Transactions](#distributed-transactions)
  - [Distribution](#distribution)
  - [Document Processing](#document-processing)
  - [Formal Verification](#formal-verification)
  - [Functional Programming](#functional-programming)
  - [Game Development](#game-development)
  - [Geospatial](#geospatial)
  - [GUI](#gui)
  - [High Performance](#high-performance)
  - [HTTP Clients](#http-clients)
  - [Hypermedia Types](#hypermedia-types)
  - [IDE](#ide)
  - [Imagery](#imagery)
  - [JSON Processing](#json-processing)
  - [JSON](#json)
  - [JVM and JDK](#jvm-and-jdk)
  - [Logging](#logging)
  - [Machine Learning](#machine-learning)
  - [Messaging](#messaging)
  - [Microservice](#microservice)
  - [Miscellaneous](#miscellaneous)
  - [Monitoring](#monitoring)
  - [Native](#native)
  - [Natural Language Processing](#natural-language-processing)
  - [Networking](#networking)
  - [ORM](#orm)
  - [PaaS](#paas)
  - [PDF](#pdf)
  - [Performance analysis](#performance-analysis)
  - [Platform](#platform)
  - [Reactive libraries](#reactive-libraries)
  - [REST Frameworks](#rest-frameworks)
  - [Science](#science)
  - [Search](#search)
  - [Security](#security)
  - [Serialization](#serialization)
  - [Server](#server)
  - [Template Engine](#template-engine)
  - [Testing](#testing)
  - [Utility](#utility)
  - [Version Managers](#version-managers)
  - [Web Crawling](#web-crawling)
  - [Web Frameworks](#web-frameworks)
- [Resources](#resources)
  - [Awesome Lists](#awesome-lists)
  - [Communities](#communities)
  - [Frontends](#frontends)
  - [Influential Books](#influential-books)
  - [Podcasts and Screencasts](#podcasts-and-screencasts)
  - [Twitter](#twitter)
  - [Websites](#websites)
- [Contributing](#contributing)

## Projects

### Bean Mapping

*Frameworks that ease bean mapping.*

- [Dozer](https://github.com/DozerMapper/dozer) - Mapper that copies data from one object to another using annotations and API or XML configuration. :star:1128
- [JMapper](https://jmapper-framework.github.io/jmapper-core) - Uses byte code manipulation for lightning-fast mapping. Supports annotations and API or XML configuration.
- [MapStruct](https://github.com/mapstruct/mapstruct) - Code generator that simplifies mappings between different bean types, based on a convention-over-configuration approach. :star:1164
- [ModelMapper](https://github.com/jhalterman/modelmapper) - Intelligent object mapping library that automatically maps objects to each other. :star:812
- [Orika](https://github.com/orika-mapper/orika) - JavaBean-mapping framework that recursively copies (among other capabilities) data from one object to another. :star:559
- [Selma](https://github.com/xebia-france/selma) - Annotation processor-based bean mapper. :star:158

### Build

*Tools that handle the build cycle and dependencies of an application.*

- [Apache Maven](https://maven.apache.org) - Declarative build and dependency management that favors convention over configuration. It might be preferable to Apache Ant, which uses a rather procedural approach and can be difficult to maintain.
- [Bazel](https://bazel.io) - Tool from Google that builds code quickly and reliably.
- [Buck](https://github.com/facebook/buck) - Encourages the creation of small, reusable modules consisting of code and resources. :star:5888
- [Gradle](https://gradle.org) - Incremental builds programmed via Groovy instead of declaring XML. Works well with Maven's dependency management.

### Bytecode Manipulation

*Libraries to manipulate bytecode programmatically.*

- [ASM](http://asm.ow2.org) - All-purpose, low-level bytecode manipulation and analysis.
- [Byte Buddy](http://bytebuddy.net) - Further simplifies bytecode generation with a fluent API.
- [bytecode-viewer](https://github.com/Konloch/bytecode-viewer) - Java 8 Jar & Android APK reverse engineering suite. :star:9411
- [Byteman](https://byteman.jboss.org) - Manipulate bytecode at runtime via DSL (rules); mainly for testing/troubleshooting.
- [cglib](https://github.com/cglib/cglib) - Bytecode generation library. :star:2060
- [Javassist](https://jboss-javassist.github.io/javassist) - Tries to simplify bytecode editing.

### Caching

*Libraries that provide caching facilities.*

- [Caffeine](https://github.com/ben-manes/caffeine) - High-performance, near-optimal caching library. :star:4155
- [Ehcache](http://www.ehcache.org) - Distributed general-purpose cache.
- [Infinispan](http://infinispan.org) - Highly concurrent key/value datastore used for caching.

### Cluster Management

*Frameworks that can dynamically manage applications inside of a cluster.*

- [Apache Aurora](https://aurora.apache.org) - Mesos framework for long-running services and cron jobs.
- [Apache Mesos](https://mesos.apache.org) - Abstracts CPU, memory, storage, and other compute resources away from machines.
- [Singularity](http://getsingularity.com) - Mesos framework that makes deployment and operations easy. It supports web services, background workers, scheduled jobs, and one-off tasks.

### Code Analysis

*Tools that provide metrics and quality measurements.*

- [Checkstyle](https://github.com/checkstyle/checkstyle) - Static analysis of coding conventions and standards. :star:3739
- [Error Prone](https://github.com/google/error-prone) - Catches common programming mistakes as compile-time errors. :star:3744
- [Infer](https://github.com/facebook/infer) - Modern static analysis tool for verifying the correctness of code. :star:8601
- [jQAssistant](https://jqassistant.org) - Static code analysis with Neo4J-based query language.
- [NullAway](https://github.com/uber/NullAway) - Eliminates NullPointerExceptions with low build-time overhead. :star:2192
- [PMD](https://github.com/pmd/pmd) - Source code analysis for finding bad coding practices. :star:1627
- [SonarJava](https://github.com/SonarSource/sonar-java) - Static analyzer for SonarQube & SonarLint. :star:332
- [Sourcetrail ![c]](https://www.sourcetrail.com) - Visual source code navigator.
- [Spoon](https://github.com/INRIA/spoon) - Library for analyzing and transforming Java source code. :star:528
- [Spotbugs](https://github.com/spotbugs/spotbugs) - Static analysis of bytecode to find potential bugs. :star:752

### Code Coverage

*Frameworks and tools that enable code coverage metrics collection for test suites.*

- [Clover ![c]](https://www.atlassian.com/software/clover/overview) - Relies on source-code instrumentation instead of bytecode instrumentation.
- [Cobertura](https://cobertura.github.io/cobertura) - Relies on offline (or static) bytecode instrumentation and class loading to collect code coverage metrics.
- [JaCoCo](http://eclemma.org/jacoco) - Framework that enables collection of code coverage metrics, using both offline and runtime bytecode instrumentation.

### Code Generators

*Tools that generate patterns for repetitive code in order to reduce verbosity and error-proneness.*

- [ADT4J](https://github.com/sviperll/adt4j) - JSR-269 code generator for algebraic data types. :star:110
- [Auto](https://github.com/google/auto) - Generates factory, service, and value classes. :star:6707
- [FreeBuilder](https://github.com/google/FreeBuilder) - Automatically generates the Builder pattern. :star:689
- [Immutables](https://immutables.github.io) - Annotation processors to generate simple, safe and consistent value objects.
- [JavaPoet](https://github.com/square/javapoet) - API to generate source files. :star:5429
- [JHipster](https://github.com/jhipster/generator-jhipster) - Yeoman source code generator for Spring Boot and AngularJS. :star:10781
- [Joda-Beans](http://www.joda.org/joda-beans) - Small framework that adds queryable properties to Java, enhancing JavaBeans.
- [Lombok](https://projectlombok.org) - Code generator that aims to reduce verbosity.

### Command-line Argument Parsers

*Libraries that make it easy to parse command line options, arguments, etc.*

- [Airline](https://github.com/airlift/airline) - Annotation-based framework for parsing Git-like command-line arguments. :star:673
- [args4j](http://args4j.kohsuke.org) - Small library to parse command-line arguments.
- [JCommander](http://jcommander.org) - Command-line argument-parsing framework with custom types and validation via implementing interfaces.
- [JOpt Simple](https://pholser.github.io/jopt-simple) - Simple parser that uses the POSIX getopt() and GNU getopt_long() syntaxes. Uses a fluent API instead of annotations.
- [picocli](http://picocli.info) - ANSI colors and styles in usage help. Can be included as source to avoid dependency. Annotation-based, POSIX/GNU/any syntax, subcommands, strong typing for both options and positional args.

### Compiler-compiler

*Frameworks that help to create parsers, interpreters or compilers.*

- [ANTLR](http://www.antlr.org) - Complex full-featured framework for top-down parsing.
- [JavaCC](https://javacc.org) - Parser generator that generates top-down parsers. Allows lexical state switching and permits extended BNF specifications.
- [JFlex](http://jflex.de) - A lexical analyzer generator.

### Configuration

*Libraries that provide external configuration.*

- [centraldogma](https://github.com/line/centraldogma) - Highly-available version-controlled service configuration repository based on Git, ZooKeeper and HTTP/2. :star:172
- [cfg4j](https://github.com/cfg4j/cfg4j) - Modern configuration library for distributed apps written in Java. :star:365
- [config](https://github.com/typesafehub/config) - Configuration library for JVM languages. :star:3621
- [dotenv](https://github.com/shyiko/dotenv) - A twelve-factor configuration library for Java. :star:17
- [ini4j](http://ini4j.sourceforge.net) - Provides an API for handling Windows' INI files.
- [KAConf](https://github.com/mariomac/kaconf) - Annotation-based configuration system for Java and Kotlin. :star:30
- [owner](https://github.com/lviggiano/owner) - Reduces boilerplate of properties. :star:605

### Constraint Satisfaction Problem Solver

*Libraries that help with implementing optimization and satisfiability problems.*

- [Choco](http://choco-solver.org) - Off-the-shelf constraint satisfaction problem solver that uses constraint programming techniques.
- [JaCoP](https://github.com/radsz/jacop) - Includes an interface for the FlatZinc language, enabling it to execute MiniZinc models. :star:129
- [OptaPlanner](https://www.optaplanner.org) - Business planning and resource scheduling optimization solver.

### CSV

*Frameworks and libraries that simplify reading/writing CSV data.*

- [jackson-dataformat-csv](https://github.com/FasterXML/jackson-dataformat-csv) - Jackson extension for reading and writing CSV. :star:186
- [opencsv](http://opencsv.sourceforge.net) - Simple CSV parser.
- [Super CSV](https://super-csv.github.io/super-csv) - Powerful CSV parser with support for Dozer, Joda-Time and Java 8.
- [uniVocity-parsers](https://github.com/uniVocity/univocity-parsers) - One of the fastest and most feature-complete parsers. Also comes with parsers for TSV and fixed-width records. :star:511

### Database

*Everything that simplifies interactions with the database.*

- [Apache Phoenix](https://phoenix.apache.org) - High-performance relational database layer over HBase for low-latency applications.
- [Chronicle Map](https://github.com/OpenHFT/Chronicle-Map) - Efficient, in-memory (opt. persisted to disk), off-heap key-value store. :star:1343
- [druid](http://druid.io) - High-performance, column-oriented, distributed data store.
- [eXist](https://github.com/eXist-db/exist) - A NoSQL document database and application platform. :star:205
- [FlexyPool](https://github.com/vladmihalcea/flexy-pool) - Brings metrics and failover strategies to the most common connection pooling solutions. :star:559
- [Flyway](https://flywaydb.org) - Simple database migration tool.
- [H2](https://h2database.com) - Small SQL database notable for its in-memory functionality.
- [HikariCP](https://github.com/brettwooldridge/HikariCP) - High-performance JDBC connection pool. :star:7200
- [JDBI](http://jdbi.org) - Convenient abstraction of JDBC.
- [Jedis](https://github.com/xetorthio/jedis) - Small client for interaction with Redis, with methods for commands. :star:6769
- [Jest](https://github.com/searchbox-io/Jest) - Client for the Elasticsearch REST API. :star:1235
- [jetcd](https://github.com/justinsb/jetcd) - Client library for etcd. :star:129
- [Jinq](https://github.com/my2iu/Jinq) - Typesafe database queries via symbolic execution of Java 8 Lambdas (on top of JPA or jOOQ). :star:500
- [jOOQ](https://www.jooq.org) - Generates typesafe code based on SQL schema.
- [Liquibase](http://www.liquibase.org) - Database-independent library for tracking, managing and applying database schema changes.
- [MapDB](http://www.mapdb.org) - Embedded database engine that provides concurrent collections backed on disk or in off-heap memory.
- [MariaDB4j](https://github.com/vorburger/MariaDB4j) - Launcher for MariaDB that requires no installation or external dependencies. :star:294
- [OrientDB](https://orientdb.com/orientdb) - Embeddable distributed database written on top of Hazelcast.
- [Presto](https://github.com/prestodb/presto) - Distributed SQL query engine for big data. :star:7685
- [Querydsl](http://www.querydsl.com) - Typesafe unified queries.
- [Realm](https://github.com/realm/realm-java) - Mobile database to run directly inside phones, tablets or wearables. :star:9649
- [Redisson](https://github.com/mrniko/redisson) - Allows for distributed and scalable data structures on top of a Redis server. :star:5520
- [requery](https://github.com/requery/requery) - A modern, lightweight but powerful object mapping and SQL generator. Easily map to or create databases, or perform queries and updates from any Java-using platform. :star:2513
- [Speedment](https://github.com/speedment/speedment) - Database access library that utilizes Java 8's Stream API for querying. :star:1420
- [sql2o](https://sql2o.org) - Thin JDBC wrapper that simplifies database access and provides simple mapping of ResultSets to POJOs.
- [Vibur DBCP](https://www.vibur.org) - JDBC connection pool library with advanced performance monitoring capabilities.
- [Xodus](https://jetbrains.github.io/xodus) - Highly concurrent transactional schema-less and ACID-compliant embedded database.

### Data Structures

*Efficient and specific data structures.*

- [Apache Avro](https://avro.apache.org) - Data interchange format with dynamic typing, untagged data, and absence of manually assigned IDs.
- [Apache Orc](https://orc.apache.org) - Fast and efficient columnar storage format for Hadoop-based workloads.
- [Apache Parquet](https://parquet.apache.org) - Columnar storage format based on assembly algorithms from Google's paper on Dremel.
- [Apache Thrift](https://thrift.apache.org) - Data interchange format that originated at Facebook.
- [Big Queue](https://github.com/bulldog2011/bigqueue) - A big, fast and persistent queue based on memory-mapped files. :star:305
- [Persistent Collection](https://pcollections.org) - Persistent and immutable analogue of the Java Collections Framework.
- [Protobuf](https://github.com/google/protobuf) - Google's data interchange format. :star:27076
- [SBE](https://github.com/real-logic/simple-binary-encoding) - Simple Binary Encoding, one of the fastest message formats around. :star:1363
- [Tape](https://github.com/square/tape) - A lightning-fast, transactional, file-based FIFO. :star:2080
- [Wire](https://github.com/square/wire) - Clean, lightweight protocol buffers. :star:2415

### Date and Time

*Libraries related to handling date and time.*

- [Almanac Converter](https://github.com/hypotemoose/almanac-converter) - Simple conversion between different calendar systems. :star:18
- [iCal4j](https://github.com/ical4j/ical4j) - Parse and build iCalendar [RFC 5545](https://tools.ietf.org/html/rfc5545) data models. :star:296
- [ThreeTen-Extra](https://github.com/ThreeTen/threeten-extra) - Additional date-time classes that complement those in JDK 8. :star:158
- [Time4J](https://github.com/MenoData/Time4J) - Advanced date and time library. :star:184

### Dependency Injection

*Libraries that help to realize the [Inversion of Control](https://en.wikipedia.org/wiki/Inversion_of_control) paradigm.*

- [Apache DeltaSpike](https://deltaspike.apache.org) - CDI extension framework.
- [Dagger2](https://google.github.io/dagger) - Compile-time injection framework without reflection.
- [Feather](https://github.com/zsoltherpai/feather) - Ultra-lightweight, JSR-330-compliant dependency injection library. :star:272
- [Governator](https://github.com/Netflix/governator) - Extensions and utilities that enhance Google Guice. :star:631
- [Guice](https://github.com/google/guice) - Lightweight and opinionated framework that completes Dagger. :star:6819
- [HK2](https://javaee.github.io/hk2) - Lightweight and dynamic dependency injection framework.

### Development

*Augmentation of the development process at a fundamental level.*

- [AspectJ](https://eclipse.org/aspectj) - Seamless aspect-oriented programming extension.
- [DCEVM](https://dcevm.github.io) - JVM modification that allows unlimited redefinition of loaded classes at runtime.
- [Faux Pas](https://github.com/zalando/faux-pas) - Library that simplifies error handling by circumventing the issue that none of the functional interfaces in the Java Runtime is allowed by default to throw checked exceptions. :star:44
- [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent) - Unlimited runtime class and resource redefinition. :star:993
- [JavaParser](https://github.com/javaparser/javaparser) - Parse, modify and generate Java code. :star:1797
- [JavaSymbolSolver](https://github.com/javaparser/javasymbolsolver) - A symbol solver for Java. :star:226
- [JRebel ![c]](https://zeroturnaround.com/software/jrebel) - Instantly reloads code and configuration changes without redeploys.
- [NoException](https://noexception.machinezoo.com) - Allows checked exceptions in functional interfaces and converts exceptions to Optional return.

### Distributed Applications

*Libraries and frameworks for writing distributed and fault-tolerant applications.*

- [Apache Geode](https://geode.apache.org) - In-memory data management system that provides reliable asynchronous event notifications and guaranteed message delivery.
- [Apache Storm](https://storm.apache.org) - Realtime computation system.
- [Apache ZooKeeper](https://zookeeper.apache.org) - Coordination service with distributed configuration, synchronization, and naming registry for large distributed systems.
- [Atomix](http://atomix.io/atomix) - Fault-tolerant distributed coordination framework.
- [Axon Framework](http://www.axonframework.org) - Framework for creating CQRS applications.
- [Copycat](http://atomix.io/copycat) - Fault-tolerant state machine replication framework.
- [Dropwizard Circuit Breaker](https://github.com/mtakaki/dropwizard-circuitbreaker) - Circuit breaker design pattern for Dropwizard. :star:31
- [Failsafe](https://github.com/jhalterman/failsafe) - Simple failure handling with retries and circuit breakers. :star:2203
- [Hazelcast ![c]](https://hazelcast.org) - Highly scalable in-memory datagrid with a free open-source version.
- [Hystrix](https://github.com/Netflix/Hystrix) - Provides latency and fault tolerance. :star:14065
- [JGroups](http://www.jgroups.org) - Toolkit for reliable messaging and cluster creation.
- [Orbit](http://www.orbit.cloud) - Virtual actors; adds another level of abstraction to traditional actors.
- [Quasar](https://www.paralleluniverse.co/quasar) - Lightweight threads and actors for the JVM.
- [resilience4j](https://github.com/resilience4j/resilience4j) - Functional fault tolerance library. :star:907
- [ScaleCube](https://github.com/scalecube/scalecube) - Embeddable Cluster-Membership library based on SWIM and gossip protocol. :star:157
- [Zuul](https://github.com/Netflix/zuul) - A gateway service that provides dynamic routing, monitoring, resiliency, security, and more. :star:5442

### Distributed Transactions

*Distributed transactions provide a mechanism for ensuring consistency of data updates in the presence of concurrent access and partial failures.*

- [Atomikos](https://www.atomikos.com) - Provides transactions for REST, SOA and microservices with support for JTA and XA.
- [Bitronix](https://github.com/bitronix/btm) - A simple but complete implementation of the JTA 1.1 API. :star:281
- [Narayana](http://narayana.io) - Provides support for traditional ACID and compensation transactions, also complies with JTA, JTS and other standards.

### Distribution

*Tools that handle the distribution of applications in native formats.*

- [Bintray ![c]](https://bintray.com) - Version control for binaries that handle publishing. Compatible with Maven or Gradle, with a free plan for open-source software as well as several business plans.
- [Boxfuse](https://boxfuse.com) - Deployment of JVM applications to AWS using the principles of immutable infrastructure.
- [Capsule](http://www.capsule.io) - Simple and powerful packaging and deployment. A fat JAR on steroids, or a "Docker for Java" that supports JVM-optimized containers.
- [Central Repository](https://search.maven.org) - Largest binary component repository available as a free service to the open-source community. Default used by Apache Maven, and available in all other build tools.
- [IzPack](http://izpack.org) - Setup authoring tool for cross-platform deployments.
- [JitPack](https://jitpack.io) - Easy-to-use package repository for GitHub. Builds Maven/Gradle projects on demand and publishes ready-to-use packages.
- [Nexus ![c]](https://www.sonatype.com/nexus/solution-overview) - Binary management with proxy and caching capabilities.
- [packr](https://github.com/libgdx/packr) - Packs JARs, assets and the JVM for native distribution on Windows, Linux and Mac OS X. :star:1751
- [really-executable-jars-maven-plugin](https://github.com/brianm/really-executable-jars-maven-plugin) - Maven plugin for making self-executing JARs. :star:86

### Document Processing

*Libraries that assist with processing office document formats.*

- [Apache POI](https://poi.apache.org) - Supports OOXML (XLSX, DOCX, PPTX) as well as OLE2 (XLS, DOC or PPT).
- [documents4j](http://documents4j.com) - API for document format conversion using third-party converters such as MS Word.
- [docx4j](https://www.docx4java.org/trac/docx4j) - Create and manipulate Microsoft Open XML files.

### Formal Verification

*Formal-methods tools: proof assistants, model checking, symbolic execution, etc.*

- [CATG](https://github.com/ksen007/janala2) - Concolic unit testing engine. Automatically generates unit tests using formal methods. :star:57
- [Checker Framework](https://types.cs.washington.edu/checker-framework) - Pluggable type systems. Includes nullness types, physical units, immutability types and more.
- [Daikon](https://plse.cs.washington.edu/daikon) - Detects likely program invariants and generates JML specs based on those invariants.
- [Java Path Finder (JPF)](https://babelfish.arc.nasa.gov/trac/jpf) - JVM formal verification tool containing a model checker and more. Created by NASA.
- [JMLOK 2.0](http://massoni.computacao.ufcg.edu.br/home/jmlok) - Detects inconsistencies between code and JML specification through feedback-directed random tests generation, and suggests a likely cause for each nonconformance detected.
- [KeY](https://key-project.org) - Formal software development tool that aims to integrate design, implementation, formal specification, and formal verification of object-oriented software as seamlessly as possible. Uses JML for specification and symbolic execution for verification.
- [OpenJML](https://openjml.github.io) - Translates JML specifications into SMT-LIB format and passes the proof problems implied by the program to backend solvers.

### Functional Programming

*Libraries that facilitate functional programming.*

- [cyclops-react](https://github.com/aol/cyclops-react) - Monad and stream utilities, comprehensions, pattern matching, functional extensions for all JDK collections, future streams, trampolines and much more. :star:735
- [derive4j](https://github.com/derive4j/derive4j) - Java 8 annotation processor and framework for deriving algebraic data types constructors, pattern-matching and morphisms. :star:347
- [Fugue](https://bitbucket.org/atlassian/fugue) - Functional extensions to Guava.
- [Functional Java](http://www.functionaljava.org) - Implements numerous basic and advanced programming abstractions that assist composition-oriented development.
- [jOOλ](https://github.com/jOOQ/jOOL) - Extension to Java 8 that aims to fix gaps in lambda by providing numerous missing types and a rich set of sequential Stream API additions. :star:1254
- [protonpack](https://github.com/poetix/protonpack) - Collection of stream utilities. :star:340
- [StreamEx](https://github.com/amaembo/streamex) - Enhances Java 8 Streams. :star:877
- [Vavr](http://www.vavr.io) - Functional component library that provides persistent data types and functional control structures.

### Game Development

*Frameworks that support the development of games.*

- [FXGL](https://almasb.github.io/FXGL) - JavaFX Game Development Framework.
- [jMonkeyEngine](http://jmonkeyengine.org) - Game engine for modern 3D development.
- [libGDX](https://libgdx.badlogicgames.com) - All-round cross-platform, high-level framework.
- [LWJGL](https://www.lwjgl.org) - Robust framework that abstracts libraries like OpenGL/CL/AL.

### Geospatial

*Libraries for working with geospatial data and algorithms.*

- [Apache SIS](https://sis.apache.org) - Library for developing geospatial applications.
- [Geo](https://github.com/davidmoten/geo) - GeoHash utilities in Java. :star:251
- [Geotoolkit.org](http://www.geotoolkit.org) - Library for developing geospatial applications. Built on top of the Apache SIS project.
- [GeoTools](http://geotools.org) - Library that provides tools for geospatial data.
- [GraphHopper](https://github.com/graphhopper/graphhopper) - Road-routing engine. Used as a Java library or standalone web service. :star:1637
- [H2GIS](http://www.h2gis.org) - A spatial extension of the H2 database.
- [Jgeohash](https://astrapi69.github.io/jgeohash) - Library for using the GeoHash algorithm.
- [Mapsforge](https://github.com/mapsforge/mapsforge) - Map rendering based on OpenStreetMap data. :star:603
- [Spatial4j](https://github.com/locationtech/spatial4j) - General-purpose spatial/geospatial library. :star:495

### GUI

*Libraries to create modern graphical user interfaces.*

- [JavaFX](https://www.oracle.com/technetwork/java/javase/overview/javafx-overview-2158620.html) - The successor of Swing.
- [Scene Builder](https://gluonhq.com/open-source/scene-builder) - Visual layout tool for JavaFX applications.
- [SWT](https://www.eclipse.org/swt) - The Standard Widget Toolkit, a graphical widget toolkit.

### High Performance

*Everything about high-performance computation, from collections to specific libraries.*

- [Agrona](https://github.com/real-logic/Agrona) - Data structures and utility methods that are common in high-performance applications. :star:1090
- [Disruptor](https://lmax-exchange.github.io/disruptor) - Inter-thread messaging library.
- [Eclipse Collections](https://github.com/eclipse/eclipse-collections) - Collections framework inspired by Smalltalk. :star:659
- [fastutil](http://fastutil.di.unimi.it) - Fast and compact type-specific collections.
- [HPPC](https://labs.carrotsearch.com/hppc.html) - Primitive collections.
- [JCTools](https://github.com/JCTools/JCTools) - Concurrency tools currently missing from the JDK. :star:1464
- [Koloboke](https://github.com/OpenHFT/Koloboke) - Hash sets and hash maps. :star:749

### HTTP Clients

*Libraries that assist with creating HTTP requests and/or binding responses.*

- [Async Http Client](https://github.com/AsyncHttpClient/async-http-client) - Asynchronous HTTP and WebSocket client library. :star:4479
- [Feign](https://github.com/Netflix/feign) - HTTP client binder inspired by Retrofit, JAXRS-2.0, and WebSocket. :star:3065
- [OkHttp](https://square.github.io/okhttp) - HTTP+SPDY client.
- [restQL-core](https://github.com/B2W-BIT/restQL-core) - Microservice query language that fetches information from multiple services. :star:85
- [Retrofit](https://square.github.io/retrofit) - Typesafe REST client.
- [Ribbon](https://github.com/Netflix/ribbon) - Client-side IPC library that is battle-tested in cloud. :star:2173
- [Riptide](https://github.com/zalando/riptide) - Client-side response routing for Spring's RestTemplate. :star:68

### Hypermedia Types

*Libraries that handle serialization to hypermedia types.*

- [JSON-LD](https://github.com/jsonld-java/jsonld-java) - JSON-LD implementation. :star:244
- [Siren4J](https://github.com/eserating/siren4j) - Library for the Siren specification. :star:16

### IDE

*Integrated development environments that try to simplify several aspects of development.*

- [Eclipse](https://www.eclipse.org) - Established open-source project with support for lots of plugins and languages.
- [IntelliJ IDEA ![c]](https://www.jetbrains.com/idea) - Supports many JVM languages and provides good options for Android development. The commercial edition targets the enterprise sector.
- [NetBeans](https://netbeans.org) - Provides integration for several Java SE and EE features, from database access to HTML5.
- [Visual Studio Code](https://code.visualstudio.com/docs/languages/java) - Provides Java support for lightweight projects with a simple, modern workflow by using extensions from the internal marketplace.

### Imagery

*Libraries that assist with the creation, evaluation or manipulation of graphical images.*

- [Imgscalr](https://github.com/thebuzzmedia/imgscalr) - Simple, efficient and hardware-accelerated image-scaling library implemented in pure Java 2D. :star:877
- [Tess4J](https://github.com/nguyenq/tess4j) - A JNA wrapper for Tesseract OCR API. :star:474
- [Thumbnailator](https://github.com/coobird/thumbnailator) - High-quality thumbnail generation library. :star:1456
- [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys) - Collection of plugins that extend the number of supported image file formats. :star:718
- [ZXing](https://github.com/zxing/zxing) - Multi-format 1D/2D barcode image processing library. :star:18991

### JSON

*Libraries for serializing and deserializing JSON to and from Java objects.*

- [DSL-JSON](https://github.com/ngs-doo/dsl-json) - JSON library with advanced compile time databinding. :star:327
- [Genson](https://owlike.github.io/genson) - Powerful and easy-to-use Java-to-JSON conversion library.
- [Gson](https://github.com/google/gson) - Serializes objects to JSON and vice versa. Good performance with on-the-fly usage. :star:12896
- [HikariJSON](https://github.com/brettwooldridge/HikariJSON) - High-performance JSON parser, 2x faster than Jackson. :star:171
- [jackson-modules-java8](https://github.com/FasterXML/jackson-modules-java8) - Set of Jackson modules for Java 8 datatypes and features. :star:147
- [Jackson-datatype-money](https://github.com/zalando/jackson-datatype-money) - Open-source Jackson module to support JSON serialization and deserialization of JavaMoney data types. :star:82
- [Jackson](https://github.com/FasterXML/jackson) - Similar to GSON, but offers performance gains if you need to instantiate the library more often. :star:3943
- [JSON-io](https://github.com/jdereg/json-io) - Convert Java to JSON. Convert JSON to Java. Pretty print JSON. Java JSON serializer. :star:213
- [jsoniter](http://jsoniter.com) - Fast and flexible library with iterator and lazy parsing API.
- [LoganSquare](https://github.com/bluelinelabs/LoganSquare) - JSON parsing and serializing library based on Jackson's streaming API. Outperforms GSON & Jackson's library. :star:3146
- [Moshi](https://github.com/square/moshi) - Modern JSON library, less opinionated and uses built-in types like List and Map. :star:3968
- [Yasson](https://github.com/eclipse/yasson) - Binding layer between classes and JSON documents similar to JAXB. :star:79

### JSON Processing

*Libraries for processing data in JSON format.*

- [fastjson](https://github.com/alibaba/fastjson) - Very fast processor with no additional dependencies and full data binding. :star:13989
- [Jolt](https://github.com/bazaarvoice/jolt) - JSON to JSON transformation tool. :star:592
- [JsonPath](https://github.com/jayway/JsonPath) - Extract data from JSON using XPATH-like syntax. :star:2772
- [JsonSurfer](https://github.com/jsurfer/JsonSurfer) - Streaming JsonPath processor dedicated to processing big and complicated JSON data. :star:96

### JVM and JDK

*Current implementations of the JVM/JDK.*

- [Avian](https://github.com/ReadyTalk/avian) - JVM with both JIT and AOT modes. Includes an iOS port. :star:1120
- [Graal](https://github.com/oracle/graal) - Polyglot virtual machine which can be embedded. :star:5327
- [OpenJ9](https://github.com/eclipse/openj9) - High performance, enterprise calibre, flexibly licensed, openly governed cross platform Java Virtual Machine extending and augmenting the runtime technology components from the Eclipse OMR and OpenJDK project. :star:1285
- [OpenJDK](http://openjdk.java.net) - Open-source implementation for Linux.
- [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm) - VM with non-blocking, concurrent GC for iOS.
- [Zulu OpenJDK 9](https://zulu.org/zulu-9-pre-release-downloads) - Early-access OpenJDK 9 builds for Windows, Linux, and Mac OS X.
- [Zulu OpenJDK](https://www.azul.com/downloads/zulu) - OpenJDK builds for Windows, Linux, and Mac OS X through Java 8.

### Logging

*Libraries that log the behavior of an application.*

- [Apache Log4j 2](https://logging.apache.org/log4j) - Complete rewrite with a powerful plugin and configuration architecture.
- [Graylog](https://www.graylog.org) - Open-source aggregator suited for extended role and permission management.
- [Kibana](https://www.elastic.co/products/kibana) - Analyzes and visualizes log files. Some features require payment.
- [Logback](https://logback.qos.ch) - Robust logging library with interesting configuration options via Groovy.
- [Logbook](https://github.com/zalando/logbook) - Extensible, open-source library for HTTP request and response logging. :star:216
- [Logstash](https://www.elastic.co/products/logstash) - Tool for managing log files.
- [SLF4J](https://www.slf4j.org) - Abstraction layer/simple logging facade.
- [tinylog](http://www.tinylog.org) - Lightweight logging framework with static logger class.
- [Tracer](https://github.com/zalando/tracer) - Call tracing and log correlation in distributed systems. :star:80

### Machine Learning

*Tools that provide specific statistical algorithms for learning from data.*

- [Apache Flink](https://flink.apache.org) - Fast, reliable, large-scale data processing engine.
- [Apache Mahout](https://mahout.apache.org) - Scalable algorithms focused on collaborative filtering, clustering and classification.
- [Apache Spark](https://spark.apache.org) - Data analytics cluster-computing framework.
- [DatumBox](http://www.datumbox.com) - Provides several algorithms and pre-trained models for natural language processing.
- [DeepDive](http://deepdive.stanford.edu) - Creates structured information from unstructured data and integrates it into an existing database.
- [Deeplearning4j](https://deeplearning4j.org) - Distributed and multi-threaded deep learning library.
- [H2O](https://www.h2o.ai) - Analytics engine for statistics over big data.
- [JSAT](https://github.com/EdwardRaff/JSAT) - Algorithms for pre-processing, classification, regression, and clustering with support for multi-threaded execution. :star:432
- [Oryx 2](https://github.com/OryxProject/oryx) - Framework for building real-time, large-scale machine learning applications. Includes end-to-end applications for collaborative filtering, classification, regression, and clustering. :star:1446
- [Smile](https://haifengl.github.io/smile) - The Statistical Machine Intelligence and Learning Engine provides a set of machine learning algorithms and a visualization library.
- [Weka](https://www.cs.waikato.ac.nz/ml/weka) - Collection of algorithms for data mining tasks ranging from pre-processing to visualization.

### Messaging

*Tools that help send messages between clients to ensure protocol independency.*

- [Aeron](https://github.com/real-logic/Aeron) - Efficient, reliable, unicast and multicast message transport. :star:3432
- [Apache ActiveMQ](https://activemq.apache.org) - Message broker that implements JMS and converts synchronous to asynchronous communication.
- [Apache Camel](https://camel.apache.org) - Glues together different transport APIs via Enterprise Integration Patterns.
- [Apache Kafka](https://kafka.apache.org) - High-throughput distributed messaging system.
- [Apache Pulsar](https://pulsar.apache.org) - Distributed pub/sub-messaging system.
- [EventBus](https://github.com/greenrobot/EventBus) - Simple publish/subscribe event bus. :star:18556
- [Hermes](http://hermes.allegro.tech) - Fast and reliable message broker built on top of Kafka.
- [JeroMQ](https://github.com/zeromq/jeromq) - Implementation of ZeroMQ. :star:1494
- [Nakadi](https://github.com/zalando/nakadi) - Provides a RESTful API on top of Kafka. :star:322
- [RocketMQ](https://github.com/alibaba/RocketMQ) - A fast, reliable, and scalable distributed messaging platform.
- [Smack](https://github.com/igniterealtime/Smack) - Cross-platform XMPP client library. :star:1739

### Miscellaneous

*Everything else.*

- [Codename One](https://www.codenameone.com) - Cross-platform solution for writing native mobile apps.
- [CQEngine](https://github.com/npgall/cqengine) - Ultra-fast, SQL-like queries on Java collections. :star:747
- [Design Patterns](https://github.com/iluwatar/java-design-patterns) - Implementation and explanation of the most common design patterns. :star:35082
- [Failsafe](https://github.com/jhalterman/failsafe) - Simple failure handling with retries and circuit breakers. :star:2203
- [FF4J](http://www.ff4j.org) - Feature Flags for Java.
- [FizzBuzz Enterprise Edition](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) - No-nonsense implementation of FizzBuzz made by serious businessmen for serious business purposes. :star:9331
- [J2ObjC](https://github.com/google/j2objc) - Java-to-Objective-C translator for porting Android libraries to iOS. :star:5167
- [JavaX](http://javax.ai1.lol) - Reinventing and extending Java with a focus on simplicity.
- [JBake](http://jbake.org) - Static website generator.
- [JBot](https://github.com/ramswaroop/jbot) - Framework for building chatbots. :star:901
- [Jimfs](https://github.com/google/jimfs) - In-memory file system. :star:1442
- [Joda-Money](http://www.joda.org/joda-money) - Basic currency and money classes and algorithms not provided by the JDK.
- [JPad](http://jpad.io) - Snippet runner.
- [Lanterna](https://github.com/mabe02/lanterna) - Easy console text-GUI library, similar to curses. :star:918
- [LightAdmin](http://lightadmin.org) - Pluggable CRUD UI library for rapid application development.
- [Maven Wrapper](https://github.com/takari/maven-wrapper) - Analogue of Gradle Wrapper for Maven, allows building projects without installing maven. :star:725
- [Membrane Service Proxy](https://github.com/membrane/service-proxy) - An open-source, reverse-proxy framework written in Java. :star:239
- [MinimalFTP](https://github.com/Guichaguri/MinimalFTP) - Lightweight, small and customizable FTP server. :star:21
- [Modern Java - A Guide to Java 8](https://github.com/winterbe/java8-tutorial) - Popular Java 8 guide. :star:9445
- [Modernizer](https://github.com/andrewgaul/modernizer-maven-plugin) - Detect uses of legacy Java APIs. :star:169
- [Multi-OS Engine](https://software.intel.com/en-us/multi-os-engine) - An open-source, cross-platform engine to develop native mobile (iOS, Android, etc.) apps.
- [OpenRefine](http://openrefine.org) - Tool for working with messy data: cleaning, transforming, extending it with web services and linking it to databases.
- [Polyglot for Maven](https://github.com/takari/polyglot-maven) - Extensions for Maven 3.3.1+ that allows writing the POM model in dialects other than XML. :star:562
- [Smooks](https://github.com/smooks/smooks) - Extensible framework for building applications that process data which means bindings, transformations, message processing and enrichment. :star:208
- [Togglz](https://www.togglz.org) - Implementation of the Feature Toggles pattern.
- [TypeTools](https://github.com/jhalterman/typetools) - Tools for resolving generic types. :star:315
- [XMLBeam](https://github.com/SvenEwald/xmlbeam) - Processes XML by using annotations or XPath within code. :star:47
- [OctoLinker](https://github.com/OctoLinker/browser-extension) - Browser extension which allows to navigate through code on GitHub more efficiently. :star:2756

### Microservice

*Tools for creating and managing microservices.*

- [Apollo](https://spotify.github.io/apollo) - Libraries for writing composable microservices.
- [consul-api](https://github.com/Ecwid/consul-api) - Client for the [Consul](https://www.consul.io) API: a distributed, highly available and datacenter-aware registry/discovery service. :star:235
- [Eureka](https://github.com/Netflix/eureka) - REST-based service registry for resilient load balancing and failover. :star:5668
- [Lagom](https://www.lightbend.com/lagom) - Framework for creating microservice-based systems.
- [Micronaut](http://micronaut.io) - Modern full-stack framework with focus on modularity, minimal memory footprint and startup time.

### Monitoring

*Tools that monitor applications in production.*

- [AppDynamics ![c]](https://www.appdynamics.com) - Performance monitor.
- [Automon](https://github.com/stevensouza/automon) - Combines the power of AOP with monitoring and/or logging tools. :star:450
- [BugSnag ![c]](https://www.bugsnag.com) - Exception and error monitoring with an integration of several third party tools for a better workflow and a free hobbyist tier.
- [LeakCanary](https://github.com/square/leakcanary) - Memory leak detection. :star:19748
- [Failsafe Actuator](https://github.com/zalando-incubator/failsafe-actuator) - Out of the box monitoring of Failsafe Circuit Breaker in Spring-Boot environment. :star:28
- [Glowroot](https://glowroot.org) - Open-source Java APM.
- [inspectIT](http://www.inspectit.rocks) - Captures detailed run-time information via hooks that can be changed on the fly. It supports tracing over multiple systems via the OpenTracing API and can correlate the data with end user monitoring.
- [Instrumental ![c]](https://instrumentalapp.com) - Real-time Java application performance monitoring. A commercial service with free development accounts.
- [JavaMelody](https://github.com/javamelody/javamelody) - Performance monitoring and profiling. :star:1450
- [jmxtrans](https://github.com/jmxtrans/jmxtrans) - Connect to multiple JVMs and query them for their attributes via JMX. Its query language is based on JSON, which allows non-Java programmers to access the JVM attributes. Supports different output writes, including Graphite, Ganglia, and StatsD. :star:1378
- [Jolokia](https://jolokia.org) - JMX over REST.
- [Kamon](http://www.kamon.io) - Tool for monitoring applications running on the JVM.
- [Metrics](http://metrics.dropwizard.io) - Expose metrics via JMX or HTTP and send them to a database.
- [New Relic ![c]](https://newrelic.com) - Performance monitor.
- [nudge4j](https://github.com/lorenzoongithub/nudge4j) - Remote developer console from the browser for Java 8 via bytecode injection. :star:118
- [OverOps ![c]](https://www.overops.com) - In-production error monitoring and debugging.
- [Pinpoint](https://github.com/naver/pinpoint) - Open-source APM tool. :star:6234
- [Prometheus](https://prometheus.io) - Provides a multi-dimensional data model, DSL, autonomous server nodes and much more.
- [SPM ![c]](https://sematext.com/spm) - Performance monitor with distributing transaction tracing for JVM apps.
- [Stagemonitor](https://github.com/stagemonitor/stagemonitor) - Open-source performance monitoring and transaction tracing for JVM apps. :star:1294
- [Sysmon](https://github.com/palantir/Sysmon) - Lightweight platform monitoring tool for Java VMs. :star:142
- [zipkin](https://zipkin.io) - Distributed tracing system which gathers timing data needed to troubleshoot latency problems in microservice architectures.

### Native
*For working with platform-specific native libraries.*

- [JavaCPP](https://github.com/bytedeco/javacpp) - Provides efficient and easy access to native C++. :star:2433
- [JNA](https://github.com/java-native-access/jna) - Work with native libraries without writing JNI. Also provides interfaces to common system libraries. :star:4003
- [JNR](https://github.com/jnr/jnr-ffi) - Work with native libraries without writing JNI. Also provides interfaces to common system libraries. Same goals as JNA, but faster, and serves as the basis for the upcoming [Project Panama](http://openjdk.java.net/projects/panama). :star:541

### Natural Language Processing

*Libraries that specialize in processing text.*

- [CogCompNLP](https://github.com/CogComp/cogcomp-nlp) - Provides common annotators for plain text input. :star:235
- [CoreNLP](https://nlp.stanford.edu/software/corenlp.shtml) - Provides a set of fundamental tools for tasks like tagging, named entity recognition, and sentiment analysis.
- [DKPro](https://dkpro.github.io) - Collection of reusable NLP tools for linguistic pre-processing, machine learning, lexical resources, etc.
- [LingPipe](http://alias-i.com/lingpipe) - Toolkit for tasks ranging from POS tagging to sentiment analysis.

### Networking

*Libraries for building network servers.*

- [Comsat](https://github.com/puniverse/comsat) - Integrates standard Java web-related APIs with Quasar fibers and actors. :star:484
- [Dubbo](https://github.com/alibaba/dubbo) - High-performance RPC framework. :star:19699
- [Finagle](https://github.com/twitter/finagle) - Extensible RPC system for constructing high-concurrency servers. It implements uniform client and server APIs for several protocols, and is protocol-agnostic to simplify implementation of new protocols. :star:6530
- [Grizzly](https://javaee.github.io/grizzly) - NIO framework. Used as a network layer in Glassfish.
- [gRPC](https://github.com/grpc/grpc-java) - RPC framework based on protobuf and HTTP/2. :star:4452
- [KryoNet](https://github.com/EsotericSoftware/kryonet) - Provides a clean and simple API for efficient TCP and UDP client/server network communication using NIO and Kryo. :star:1278
- [MINA](https://mina.apache.org) - Abstract, event-driven async I/O API for network operations over TCP/IP and UDP/IP via Java NIO.
- [Netty](https://netty.io) - Framework for building high-performance network applications.
- [Nifty](https://github.com/facebook/nifty) - Implementation of Thrift clients and servers on Netty. :star:815
- [sshj](https://github.com/hierynomus/sshj) - Programatically use SSH, SCP or SFTP. :star:1193
- [Undertow](http://undertow.io) - Web server providing both blocking and non-blocking APIs based on NIO. Used as a network layer in WildFly.
- [urnlib](https://github.com/slub/urnlib) - Represent, parse and encode URNs, as in RFC 2141. :star:8

### ORM

*APIs that handle the persistence of objects.*

- [Apache Cayenne](https://cayenne.apache.org) - Provides a clean, static API for data access. Also includes a GUI Modeler for working with database mappings, and DB reverse engineering and generation.
- [Ebean](https://ebean-orm.github.io) - Provides simple and fast data access.
- [EclipseLink](https://www.eclipse.org/eclipselink) - Supports a number of persistence standards: JPA, JAXB, JCA and SDO.
- [Hibernate](http://hibernate.org/orm) - Robust and widely used, with an active community.
- [MyBatis](http://www.mybatis.org/mybatis-3) - Couples objects with stored procedures or SQL statements.
- [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper) - Simple database and CSV mapper. :star:205

### PaaS

*Java platform as a service.*

- [AWS Elastic Beanstalk ![c]](https://aws.amazon.com/elasticbeanstalk) - AWS-based, with support for Tomcat and Jetty.
- [AWS Lambda ![c]](https://aws.amazon.com/lambda) - Serverless computation.
- [Google App Engine ![c]](https://cloud.google.com) - PaaS on Google's infrastructure.
- [Heroku ![c]](https://www.heroku.com) - Abstract computing environments.
- [Jelastic ![c]](https://jelastic.com) - Supports Tomcat, Jetty, GlassFish, JBoss, TomEE and WildFly.
- [OpenShift Enterprise ![c]](https://www.openshift.com) - On-premise solution.

### PDF

*Tools to help with PDF file creation.*

- [Apache FOP](https://xmlgraphics.apache.org/fop) - Creates PDFs from XSL-FO.
- [Apache PDFBox](https://pdfbox.apache.org) - Toolbox for creating and manipulating PDFs.
- [Dynamic Jasper](http://dynamicjasper.com) - Abstraction layer to JasperReports.
- [DynamicReports](http://dynamicreports.org) - Simplifies JasperReports.
- [flyingsaucer](https://github.com/flyingsaucerproject/flyingsaucer) - XML/XHTML and CSS 2.1 renderer. :star:1053
- [iText ![c]](https://itextpdf.com) - Creates PDF files programmatically.
- [JasperReports](https://community.jaspersoft.com/project/jasperreports-library) - Complex reporting engine.

### Performance analysis

*Tools for performance analysis, profiling and benchmarking.*

- [fastThread ![c]](http://fastthread.io) - Analyze and visualize thread dumps with a free cloud-based upload interface.
- [GCeasy ![c]](http://gceasy.io) - Tool to analyze and visualize GC logs. It provides a free cloud-based upload interface.
- [honest-profiler](https://github.com/RichardWarburton/honest-profiler) - A low-overhead, bias-free sampling profiler. :star:855
- [jHiccup](https://github.com/giltene/jHiccup) - Logs and records platform JVM stalls. :star:411
- [JITWatch](https://github.com/AdoptOpenJDK/jitwatch) - Analyze the JIT compiler optimisations made by the HotSpot JVM. :star:1413
- [JMH](http://openjdk.java.net/projects/code-tools/jmh) - a Java harness for building, running, and analysing nano/micro/milli/macro benchmarks written in Java and other languages targeting the JVM.
- [JProfiler ![c]](https://www.ej-technologies.com/products/jprofiler/overview.html) - Database profiling for JDBC, JPA and NoSQL, with JEE support.
- [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils) - Utilities for latency measurement and reporting. :star:313
- [XRebel ![c]](https://zeroturnaround.com/software/xrebel) - Real-time profiling for web applications, with an in-browser widget.
- [YourKit Java Profiler ![c]](https://www.yourkit.com/features) - Profiler for any application running on the JVM.

### Platform

*Frameworks that are suites of multiple libraries encompassing several categories.*

#### Apache Commons

- [Pool](http://commons.apache.org/proper/commons-pool) - Generic object pooling component.
- [BCEL](http://commons.apache.org/proper/commons-bcel) - Byte Code Engineering Library - analyze, create, and manipulate Java class files.
- [Codec](http://commons.apache.org/proper/commons-codec) - General encoding/decoding algorithms (for example phonetic, base64, URL).
- [Compress](http://commons.apache.org/proper/commons-compress) - Defines an API for working with tar, zip and bzip2 files.
- [IO](http://commons.apache.org/proper/commons-io) - Collection of I/O utilities.
- [Configuration](http://commons.apache.org/proper/commons-configuration) - Reading of configuration/preferences files in various formats.
- [VFS](http://commons.apache.org/proper/commons-vfs) - Virtual File System component for treating files, FTP, SMB, ZIP and such like as a single logical file system.
- [Jelly](http://commons.apache.org/proper/commons-jelly) - XML based scripting and processing engine.
- [CSV](http://commons.apache.org/proper/commons-csv) - Component for reading and writing comma separated value files.
- [JCS](http://commons.apache.org/proper/commons-jcs) - Java Caching System.
- [Email](http://commons.apache.org/proper/commons-email) - Library for sending e-mail from Java.
- [DbUtils](http://commons.apache.org/proper/commons-dbutils) - JDBC helper library.
- [FileUpload](http://commons.apache.org/proper/commons-fileupload) - File upload capability for your servlets and web applications.
- [Lang](http://commons.apache.org/proper/commons-lang) - Provides extra functionality for classes in java.lang.
- [Jexl](http://commons.apache.org/proper/commons-jexl) - Expression language which extends the Expression Language of the JSTL.
- [CLI](http://commons.apache.org/proper/commons-cli) - Command Line arguments parser.
- [Validator](http://commons.apache.org/proper/commons-validator) - Framework to define validators and validation rules in an xml file.
- [Net](http://commons.apache.org/proper/commons-net) - Collection of network utilities and protocol implementations.
- [RNG](https://commons.apache.org/proper/commons-rng) - Commons Rng provides implementations of pseudo-random numbers generators.
- [RDF](https://commons.apache.org/proper/commons-rdf) - Common implementation of RDF 1.1 that could be implemented by systems on the JVM.
- [Weaver](http://commons.apache.org/proper/commons-weaver) - Provides an easy way to enhance (weave) compiled bytecode.
- [BeanUtils](http://commons.apache.org/proper/commons-beanutils) - Easy-to-use wrappers around the Java reflection and introspection APIs.
- [Collections](http://commons.apache.org/proper/commons-collections) - Extends or augments the Java Collections Framework.
- [DBCP](http://commons.apache.org/proper/commons-dbcp) - Database connection pooling services.
- [Math](http://commons.apache.org/proper/commons-math) - Lightweight, self-contained mathematics and statistics components.
- [Exec](http://commons.apache.org/proper/commons-exec) - API for dealing with external process execution and environment management in Java.
- [Logging](https://en.wikipedia.org/wiki/Apache_Commons_Logging) Wrapper around a variety of logging API implementations.
- [OGNL](http://commons.apache.org/proper/commons-ognl) - An Object-Graph Navigation Language.
- [JCI](http://commons.apache.org/proper/commons-jci) - Java Compiler Interface.
- [Daemon](http://commons.apache.org/proper/commons-daemon) - Alternative invocation mechanism for unix-daemon-like java code.
- [Functor](http://commons.apache.org/proper/commons-functor) - A functor is a function that can be manipulated as an object, or an object representing a single, generic function.
- [Digester](http://commons.apache.org/proper/commons-digester) - XML-to-Java-object mapping utility.
- [BSF](http://commons.apache.org/proper/commons-bsf) - Bean Scripting Framework - interface to scripting languages, including JSR-223.
- [Imaging](http://commons.apache.org/proper/commons-imaging) - A pure-Java image library.
- [SCXML](http://commons.apache.org/proper/commons-scxml) - An implementation of the State Chart XML specification aimed at creating and maintaining a Java SCXML engine.
- [JXPath](http://commons.apache.org/proper/commons-jxpath) - Utilities for manipulating Java Beans using the XPath syntax.
- [Chain](http://commons.apache.org/proper/commons-chain) - Chain of Responsibility pattern implementation.
- [Proxy](http://commons.apache.org/proper/commons-proxy) - Library for creating dynamic proxies.
- [BeanUtils2](http://commons.apache.org/sandbox/commons-beanutils2) - Redesign of Commons BeanUtils.
- [ClassScan](http://commons.apache.org/sandbox/commons-classscan) - Find Class interfaces, methods, fields, and annotations without loading.
- [CLI2](http://commons.apache.org/sandbox/commons-cli2) Redesign of Commons CLI.
- [Convert](http://commons.apache.org/sandbox/commons-convert) - Commons-Convert aims to provide a single library dedicated to the task of converting an object of one type to another.
- [Finder](http://commons.apache.org/sandbox/commons-finder) - Java library inspired by the UNIX find command.
- [Flatfile](http://commons.apache.org/sandbox/commons-flatfile) - Java library for working with flat data structures.
- [Graph](http://commons.apache.org/sandbox/commons-graph) - A general purpose Graph APIs and algorithms.
- [I18n](http://commons.apache.org/sandbox/commons-i18n) - Adds the feature of localized message bundles that consist of one or many localized texts that belong together.
- [Id](http://commons.apache.org/sandbox/commons-id) - Id is a component used to generate identifiers.
- [Javaflow](http://commons.apache.org/sandbox/commons-javaflow) - Continuation implementation to capture the state of the application.
- [JNet](http://commons.apache.org/sandbox/commons-jnet) - JNet allows to use dynamically register url stream handlers through the java.net API.
- [Monitoring](http://commons.apache.org/sandbox/commons-monitoring) - Monitoring aims to provide a simple but extensible monitoring solution for Java applications.
- [Nabla](http://commons.apache.org/sandbox/commons-nabla) - Nabla provides automatic differentiation classes that can generate derivative of any function implemented in the Java language.
- [OpenPGP](http://commons.apache.org/sandbox/commons-openpgp) - Interface to signing and verifying data using OpenPGP.
- [Performance](http://commons.apache.org/sandbox/commons-performance) - A small framework for microbenchmark clients, with implementations for Commons DBCP and Pool.
- [Pipeline](http://commons.apache.org/sandbox/commons-pipeline) - Provides a set of pipeline utilities designed around work queues that run in parallel to sequentially process data objects.

#### Other

- [CUBA Platform](https://cuba-platform.com) - High-level framework for developing enterprise applications with a rich web interface, based on Spring, EclipseLink and Vaadin.
- [Light-Java](https://github.com/networknt/light-java) - A fast, lightweight and productive microservices framework with built-in [security](https://github.com/networknt/light-oauth2). :star:773
- [Orienteer](https://github.com/OrienteerBAP/Orienteer) - Open-source business application platform for rapid configuration/development of CRM, ERP, LMS and other applications. :star:87
- [Spring](https://spring.io/projects) - Provides many packages for dependency injection, aspect-oriented programming, security, etc.

### Reactive libraries

*Libraries for developing reactive applications.*

- [Akka](https://akka.io) - Toolkit and runtime for building concurrent, distributed, fault-tolerant and event-driven applications.
- [Reactive Streams](https://github.com/reactive-streams/reactive-streams-jvm) - Provides a standard for asynchronous stream processing with non-blocking backpressure. :star:2487
- [Reactor](https://projectreactor.io) - Library for building reactive fast-data applications.
- [RxJava](https://github.com/ReactiveX/RxJava) - Allows for composing asynchronous and event-based programs using observable sequences. :star:33840
- [vert.x](http://vertx.io) - Polyglot event-driven application framework.

### REST Frameworks

*Frameworks specifically for creating RESTful services.*

- [Dropwizard](https://dropwizard.github.io/dropwizard) - Opinionated framework for setting up modern web applications with Jetty, Jackson, Jersey and Metrics.
- [Jersey](https://jersey.github.io) - JAX-RS reference implementation.
- [Microserver](https://github.com/aol/micro-server) — A convenient, extensible microservices plugin system for Spring & Spring Boot. With more than 30 plugins and growing, it supports both micro-monolith and pure microservices styles.
- [Rapidoid](https://www.rapidoid.org) - A simple, secure and extremely fast framework consisting of an embedded HTTP server, GUI components and dependency injection.
- [rest.li](https://github.com/linkedin/rest.li) - Framework for building robust, scalable RESTful architectures using typesafe bindings and asynchronous, non-blocking IO with an end-to-end developer workflow that promotes clean practices, uniform interface design and consistent data modeling. :star:1804
- [RESTEasy](https://resteasy.jboss.org) - Fully certified and portable implementation of the JAX-RS specification.
- [RestExpress](https://github.com/RestExpress/RestExpress) - Thin wrapper on the JBoss Netty HTTP stack that provides scaling and performance. :star:837
- [Restlet Framework](https://github.com/restlet/restlet-framework-java) - Pioneering framework with powerful routing and filtering capabilities, and a unified client and server API. :star:572
- [Spark](http://sparkjava.com) - Sinatra inspired framework.
- [Crnk](http://www.crnk.io) - Implementation of the JSON API specification to build resource-oriented REST endpoints with sorting, filtering, paging, linking, object graphs, type-safety, bulk updates, integrations and more.
- [Swagger](https://swagger.io) - Standard, language-agnostic interface to REST APIs.

### Science

*Libraries for scientific computing, analysis and visualization.*

- [DataMelt](http://jwork.org/dmelt) - Environment for scientific computation, data analysis and data visualization.
- [Erdos](https://github.com/Erdos-Graph-Framework/Erdos) - Modular, light and easy graph framework for theoretic algorithms. :star:83
- [GraphStream](http://graphstream-project.org) - Library for modeling and analyzing dynamic graphs.
- [JGraphT](https://github.com/jgrapht/jgrapht) - Graph library that provides mathematical graph-theory objects and algorithms. :star:1192
- [JGraphX](https://github.com/jgraph/jgraphx) - Library for visualizing (mainly Swing) and interacting with node-edge graphs. :star:479
- [Mines Java Toolkit](https://github.com/MinesJTK/jtk) - Library for geophysical scientific computation, visualization and digital signal analysis. :star:15
- [Morpheus](http://www.zavtech.com/morpheus/docs) - Provides a versatile two-dimensional memory efficient tabular data structure called a DataFrame to enable efficient in-memory analytics for scientific computing on the JVM.
- [Tablesaw](https://github.com/lwhite1/tablesaw) - Includes a data-frame, an embedded column store, and hundreds of methods to transform, summarize, or filter data. :star:969

### Search

*Engines that index documents for search and analysis.*

- [Apache Lucene](https://lucene.apache.org) - High-performance, full-featured, cross-platform, text search engine library.
- [Apache Solr](https://lucene.apache.org/solr) - Enterprise search engine optimized for high-volume traffic.
- [Elasticsearch](https://www.elastic.co) - Distributed, multitenant-capable, full-text search engine with a RESTful web interface and schema-free JSON documents.

### Security

*Libraries that handle security, authentication, authorization or session management.*

- [Apache Shiro](https://shiro.apache.org) - Performs authentication, authorization, cryptography and session management.
- [Bouncy Castle](https://www.bouncycastle.org/java.html) - All-purpose cryptographic library and JCA provider offering a wide range of functions, from basic helpers to PGP/SMIME operations.
- [Cryptomator](https://cryptomator.org) - Multiplatform, transparent, client-side encryption of files in the cloud.
- [Hdiv](https://github.com/hdiv/hdiv) - Runtime application that repels application security risks included in the OWASP Top 10, including SQL injection, cross-site scripting, cross-site request forgery, data tampering, and brute force attacks. :star:155
- [jjwt](https://github.com/jwtk/jjwt) - JSON web token for Java and Android. :star:3305
- [Keycloak](https://keycloak.jboss.org) - Integrated SSO and IDM for browser apps and RESTful web services.
- [Keyczar](https://github.com/google/keyczar) - Easy-to-use, safe encryption framework with key versioning. :star:1016
- [Keywhiz](https://github.com/square/keywhiz) - System for distributing and managing secrets. :star:1953
- [Nbvcxz](https://github.com/GoSimpleLLC/nbvcxz) - Advanced password strength estimation. :star:122
- [OACC](http://oaccframework.org) - Provides permission-based authorization services.
- [pac4j](https://github.com/pac4j/pac4j) - Security engine. :star:1281
- [PicketLink](http://picketlink.org) - Umbrella project for security and identity management.
- [Vault](https://www.vaultproject.io) - Secures, stores, and tightly controls access to tokens, passwords, certificates, API keys, and other secrets. It handles leasing, key revocation, key rolling, and auditing. Through a unified API, users can access an encrypted Key/Value store and network encryption-as-a-service, or generate AWS IAM/STS credentials, SQL/NoSQL databases, X.509 certificates, SSH credentials, and more.

### Serialization

*Libraries that handle serialization with high efficiency.*

- [FlatBuffers](https://github.com/google/flatbuffers) - Memory-efficient serialization library that can access serialized data without unpacking and parsing it. :star:9587
- [FST](https://github.com/RuedigerMoeller/fast-serialization) - JDK-compatible, high-performance object graph serialization. :star:979
- [Kryo](https://github.com/EsotericSoftware/kryo) - Fast and efficient object graph serialization framework. :star:3448
- [MessagePack](https://github.com/msgpack/msgpack-java) - Efficient binary serialization format. :star:875
- [PHP Serializer](https://github.com/marcospassos/java-php-serializer) - Serializing objects in the PHP serialization format. :star:6

### Server

*Servers specifically used to deploy applications.*

- [Apache Tomcat](https://tomcat.apache.org) - Robust, all-round server for Servlet and JSP.
- [Apache TomEE](https://tomee.apache.org) - Tomcat plus Java EE.
- [Jetty](https://www.eclipse.org/jetty) - Provides a Web server and javax.servlet container, plus support for HTTP/2, WebSocket, OSGi, JMX, JNDI, JAAS and many other integrations.
- [nanohttpd](https://github.com/NanoHttpd/nanohttpd) - Tiny, easily embeddable HTTP server. :star:3835
- [WebSphere Liberty](https://developer.ibm.com/wasdev) - Lightweight, modular server developed by IBM.
- [WildFly](http://www.wildfly.org) - Formerly known as JBoss and developed by Red Hat with extensive Java EE support.

### Template Engine

*Tools that substitute expressions in a template.*

- [Handlebars.java](https://jknack.github.io/handlebars.java) - Logicless and semantic Mustache templates.
- [Jade4J](https://github.com/neuland/jade4j) - Implementation of Pug (formerly known as Jade). :star:613
- [Jtwig](http://jtwig.org) - Modular, configurable and fully tested template engine.
- [Pebble](http://www.mitchellbosecke.com/pebble/home) - Inspired by Twig and separates itself with its inheritance feature and its easy-to-read syntax. It ships with built-in autoescaping for security and it includes integrated support for internationalization.
- [Thymeleaf](http://www.thymeleaf.org) - Aims to be a substitute for JSP and works for XML files.

### Testing

*Tools that test from model to the view.*

#### Asynchronous

*Tools that simplify testing asynchronous services.*

- [Awaitility](https://github.com/jayway/awaitility) - DSL for synchronizing asynchronous operations. :star:1203
- [ConcurrentUnit](https://github.com/jhalterman/concurrentunit) - Toolkit for testing multi-threaded and asynchronous applications. :star:261
- [GreenMail](http://www.icegreen.com/greenmail) - In-memory email server for integration testing. Supports SMTP, POP3 and IMAP including SSL.
- [Hoverfly Java](https://github.com/SpectoLabs/hoverfly-java) - Native bindings for Hoverfly, a proxy which allows you to simulate HTTP services. :star:71
- [REST Assured](https://github.com/jayway/rest-assured) - DSL for easy testing of REST/HTTP services. :star:3147

#### BDD

*Testing for the software development process that emerged from TDD and was heavily influenced by DDD and OOAD.*

- [Cucumber](https://github.com/cucumber/cucumber-jvm) - Provides a way to describe features in a plain language which customers can understand. :star:1722
- [Cukes-REST](https://github.com/ctco/cukes-rest) - A collection of Gherkin steps for REST-service testing using Cucumber. :star:58
- [J8Spec](https://github.com/j8spec/j8spec) - Follows a Jasmine-like syntax. :star:43
- [JBehave](http://jbehave.org) - Extensively configurable framework that describes stories.
- [JGiven](http://jgiven.org) - Provides a fluent API which allows for simpler composition.
- [Lamdba Behave](https://github.com/RichardWarburton/lambda-behave) - Aims to provide a fluent API to write tests in long and descriptive sentences that read like plain English. :star:219

#### Fixtures

*Everything related to the creation and handling of random data.*

- [Beanmother](https://github.com/keepcosmos/beanmother) - Sets up beans from YAML fixtures. :star:61
- [Fixture Factory](https://github.com/six2six/fixture-factory) - Generates fake objects from a template. :star:269
- [JFairy](https://github.com/Codearte/jfairy) - Fake data generator. :star:11
- [Randomized Testing](https://github.com/randomizedtesting/randomizedtesting) - JUnit test runner and plugins for running JUnit tests with pseudo-randomness. :star:124

#### Frameworks

*Provide environments to run tests for a specific use case.*

- [ArchUnit](https://github.com/TNG/ArchUnit) - Test library for specifying and asserting architecture rules. :star:376
- [Apache JMeter](http://jmeter.apache.org) - Functional testing and performance measurements.
- [Arquillian](http://arquillian.org) - Integration and functional testing platform for Java EE containers.
- [Citrus](https://citrusframework.org) - Integration testing framework that focuses on both client- and server-side messaging.
- [Gatling](https://gatling.io) - Load testing tool designed for ease of use, maintainability and high performance.
- [JUnit](http://junit.org) - Common testing framework.
- [Pact JVM](https://github.com/DiUS/pact-jvm) - Consumer-driven contract testing. :star:531
- [PIT](http://pitest.org) - Fast mutation-testing framework for evaluating fault-detection abilities of existing JUnit or TestNG test suites.

#### Matchers

*Libraries that provide custom matchers.*

- [AssertJ](https://joel-costigliola.github.io/assertj) - Fluent assertions that improve readability.
- [JSONAssert](http://jsonassert.skyscreamer.org) - Simplifies testing JSON strings.
- [Truth](https://github.com/google/truth) - Google's assertion and proposition framework. :star:1449

#### Miscellaneous

*Other stuff related to testing.*

- [Mutability Detector](https://github.com/MutabilityDetector/MutabilityDetector) - Reports whether instances of a given class are immutable. :star:167
- [raml-tester](https://github.com/nidi3/raml-tester) - Tests if a request/response matches a given RAML definition. :star:70
- [TestContainers](https://github.com/testcontainers/testcontainers-java) - Provides throwaway instances of common databases, Selenium web browsers, or anything else that can run in a Docker container. :star:1283
- [pojo-tester](http://www.pojo.pl) - Automatically performs tests on basic POJO methods.

#### Mocking

*Tools which mock collaborators to help testing single, isolated units.*

- [JMockit](http://jmockit.org) - Integration testing, API mocking and faking, and code coverage.
- [Mockito](https://github.com/mockito/mockito) - Mocking framework that lets you write tests with a clean and simple API. :star:6985
- [MockServer](https://www.mock-server.com) - Allows mocking of systems integrated with HTTPS.
- [Moco](https://github.com/dreamhead/moco) - Concise web services for stubs and mocks. :star:2185
- [PowerMock](https://github.com/jayway/powermock) - Mocks static methods, constructors, final classes and methods, private methods, and removal of static initializers. :star:1937
- [WireMock](http://wiremock.org) - Stubs and mocks web services.

#### Parameterization

*Simplifies the writing of parameterized tests.*

- [Burst](https://github.com/square/burst) - A unit testing library for varying test data. :star:428
- [junit-dataprovider](https://github.com/TNG/junit-dataprovider) - A TestNG-like data provider/runner for JUnit. :star:174
- [JUnitParams](https://pragmatists.github.io/JUnitParams) - Creates readable and maintainable parametrised tests.

### Utility

*Libraries which provide general utility functions.*

- [cactoos](http://www.cactoos.org) - Collection of object-oriented primitives.
- [CRaSH](http://www.crashub.org) - Provides a shell into a JVM that's running CRaSH. Used by Spring Boot and others.
- [Dex](https://github.com/PatMartin/Dex) - Java/JavaFX tool capable of powerful ETL and data visualization. :star:939
- [Embulk](http://www.embulk.org) - Bulk data loader that helps data transfer between various databases, storages, file formats, and cloud services.
- [fswatch](https://github.com/vorburger/ch.vorburger.fswatch) - Micro library to watch for directory file system changes, simplifying java.nio.file.WatchService :star:6
- [Gephi](https://github.com/gephi/gephi) - Cross-platform for visualizing and manipulating large graph networks. :star:2722
- [Guava](https://github.com/google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and more. :star:24917
- [JADE](http://jade.tilab.com) - Framework and environment for building and debugging multi-agent systems.
- [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions) - Library that helps with constructing difficult regular expressions. :star:1610
- [JGit](https://eclipse.org/jgit) - A lightweight, pure Java library implementing the Git version control system.
- [minio-java](https://github.com/minio/minio-java) - Provides simple APIs to access any Amazon S3-compatible object storage server. :star:100
- [Protégé](https://protege.stanford.edu) - Provides an ontology editor and a framework to build knowledge-based systems.
- [Underscore-java](https://github.com/javadev/underscore-java) - Port of Underscore.js functions. :star:176

### Version Managers

*Utilities that help create the development shell environment and switch between different Java versions.*

- [jabba](https://github.com/shyiko/jabba) - Java Version Manager inspired by nvm. Supports Mac OS X, Linux and Windows. :star:494
- [jenv](https://github.com/gcuisinier/jenv) - Java Version Manager inspired by rbenv. Can configure globally or per project. Tested on Debian and Mac OS X. :star:1941
- [SDKMan](https://github.com/sdkman/sdkman-cli) - Java Version Manager inspired by RVM and rbenv. Supports UNIX-based platforms and Windows. :star:2096

### Web Crawling

*Libraries that analyze the content of websites.*

- [Apache Nutch](https://nutch.apache.org) - Highly extensible, highly scalable web crawler for production environments.
- [Crawler4j](https://github.com/yasserg/crawler4j) - Simple and lightweight web crawler. :star:2967
- [jsoup](https://jsoup.org) - Scrapes, parses, manipulates and cleans HTML.
- [StormCrawler](http://stormcrawler.net) - SDK for building low-latency and scalable web crawlers.
- [webmagic](https://github.com/code4craft/webmagic) - Scalable crawler with downloading, url management, content extraction and persistent. :star:6689

### Web Frameworks

*Frameworks that handle the communication between the layers of a web application.*

- [Apache Tapestry](https://tapestry.apache.org) - Component-oriented framework for creating dynamic, robust, highly scalable web applications.
- [Apache Wicket](https://wicket.apache.org) - Component-based web application framework similar to Tapestry, with a stateful GUI.
- [Blade](https://github.com/biezhi/blade) - Lightweight, modular framework that aims to be elegant and simple. :star:3779
- [Bootique](http://bootique.io) - Minimally opinionated framework for runnable apps.
- [Firefly](http://www.fireflysource.com) - Asynchronous framework for rapid development of high-performance web application.
- [Grails](https://grails.org) - Groovy framework that provides a highly productive environment by favoring convention over configuration, no XML and support for mixins.
- [Jooby](http://jooby.org) - Scalable, fast and modular micro-framework that offers multiple programming models.
- [Ninja](http://www.ninjaframework.org) - Full-stack web framework.
- [Pippo](http://www.pippo.ro) - Small, highly modularized, Sinatra-like framework.
- [Play](https://www.playframework.com) - Built on Akka, it provides predictable and minimal resource consumption (CPU, memory, threads) for highly-scalable applications in Java and Scala.
- [PrimeFaces](https://primefaces.org) - JSF framework with both free and commercial/support versions and frontend components.
- [Ratpack](https://ratpack.io) - Set of libraries that facilitate fast, efficient, evolvable and well-tested HTTP applications.
- [Takes](https://github.com/yegor256/takes) - Opinionated web framework which is built around the concepts of True Object-Oriented Programming and immutability. :star:426
- [Vaadin](https://vaadin.com/home) - Event-driven framework built on top of GWT. Uses server-side architecture with Ajax on the client side.

## Resources

### Awesome Lists

*Awesome lists related to the Java & JVM ecosystem.*

- [Awesome Gradle Plugins](https://github.com/ksoichiro/awesome-gradle) :star:181
- [AwesomeJavaFX](https://github.com/mhrimaz/AwesomeJavaFX) :star:1007
- [Awesome JVM](https://github.com/deephacks/awesome-jvm) :star:855
- [Awesome Microservices](https://github.com/mfornos/awesome-microservices) :star:6190
- [Awesome REST](https://github.com/marmelab/awesome-rest) :star:1776
- [Awesome Selenium](https://github.com/christian-bromann/awesome-selenium) :star:356
- [ciandcd](https://github.com/ciandcd/awesome-ciandcd) :star:688
- [Useful Java Links](https://github.com/Vedenin/useful-java-links) :star:3860

### Communities

*Active discussions.*

- [r/java](https://www.reddit.com/r/java) - Subreddit for the Java community.
- [stackoverflow](https://stackoverflow.com/questions/tagged/java) - Question/answer platform.
- [VirtualJUG](https://virtualjug.com) - Virtual Java User Group.

### Frontends

*Websites that provide a frontend for this list. Please note, there won't be an official website. We don't associate with a particular website and everybody is allowed to create one.*

- [java.libhunt.com](https://java.libhunt.com)

### Influential Books

*Books that made a big impact and are still worth reading.*

- [Core Java Volume I--Fundamentals](https://www.amazon.com/Core-Java-I-Fundamentals-10th/dp/0134177304)
- [Core Java, Volume II--Advanced Features](https://www.amazon.com/Core-Java-II-Advanced-Features-10th/dp/0134177290)
- [Effective Java (3rd Edition)](https://www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997)
- [Java Concurrency in Practice](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
- [Thinking in Java](https://www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)

### Podcasts and Screencasts

*Something to look at or listen to while programming.*

- [Java Off Heap](http://www.javaoffheap.com)
- [Marco Behler's Screencasts](https://www.marcobehler.com/series) - Screencasts about modern Java development.
- [The Java Council](https://virtualjug.com/podcast)
- [The Java Posse](http://www.javaposse.com) - Discontinued as of 02/2015.

### Twitter

*Active accounts to follow. Descriptions from Twitter.*

- [Adam Bien](https://twitter.com/AdamBien) - Freelance author, JavaOne Rockstar speaker, consultant, Java Champion.
- [Aleksey Shipilëv](https://twitter.com/shipilev) - Performance geek, benchmarking czar, concurrency bug hunter.
- [Antonio Goncalves](https://twitter.com/agoncal) - Java Champion, JUG Leader, Devoxx France, Java EE 6/7, JCP, Author.
- [Arun Gupta](https://twitter.com/arungupta) - Java Champion, JavaOne Rockstar, JUG Leader, Devoxx4Kids-er, VP of Developer Advocacy at Couchbase.
- [Brian Goetz](https://twitter.com/BrianGoetz) - Java Language Architect at Oracle.
- [Bruno Borges](https://twitter.com/brunoborges) - Product Manager/Java Jock at Oracle.
- [Chris Richardson](https://twitter.com/crichardson) - Software architect, consultant, and serial entrepreneur, Java Champion, JavaOne Rock Star, *POJOs in Action- author.
- [Ed Burns](https://twitter.com/edburns) - Consulting Member of the Technical Staff at Oracle.
- [Eugen Paraschiv](https://twitter.com/baeldung) - Author of the Spring Security Course.
- [Heinz Kabutz](https://twitter.com/heinzkabutz) - Java Champion, speaker, author of The Java Specialists' Newsletter, concurrency performance expert.
- [Holly Cummins](https://twitter.com/holly_cummins) - Technical Lead of IBM London's Bluemix Garage, Java Champion, developer, author, JavaOne rockstar.
- [James Weaver](https://twitter.com/JavaFXpert) - Java/JavaFX/IoT developer, author and speaker.
- [Java EE](https://twitter.com/Java_EE) - Official Java EE Twitter account.
- [Java Magazine](https://twitter.com/Oraclejavamag) - Official Java Magazine account.
- [Java](https://twitter.com/java) - Official Java Twitter account.
- [Javin Paul](https://twitter.com/javinpaul) - Well-known Java blogger.
- [Josh Long](https://twitter.com/starbuxman) - Spring Advocate at Pivotal, author of O'Reilly's Cloud Native Java- and Building Microservices with Spring Boot, JavaOne Rock Star.
- [Lukas Eder](https://twitter.com/lukaseder) - Java Champion, speaker, JUG.ch co-leader, Founder and CEO Data Geekery (jOOQ).
- [Mario Fusco](https://twitter.com/mariofusco) - RedHatter, JUG coordinator, frequent speaker and author.
- [Mark Heckler](https://twitter.com/MkHeck) - Pivotal Principal Technologist and Developer Advocate, conference speaker, published author, and Java Champion, focusing on Internet of Things and the cloud.
- [Mark Reinhold](https://twitter.com/mreinhold) - Chief Architect, Java Platform Group, Oracle.
- [Markus Eisele](https://twitter.com/myfear) - Java EE evangelist, Red Hat.
- [Martijn Verburg](https://twitter.com/karianna) - London JUG co-leader, speaker, author, Java Champion and much more.
- [Martin Thompson](https://twitter.com/mjpt777) - Pasty faced performance gangster.
- [Monica Beckwith](https://twitter.com/mon_beck) - Performance consultant, JavaOne Rock Star.
- [OpenJDK](https://twitter.com/OpenJDK) - Official OpenJDK account.
- [Peter Lawrey](https://twitter.com/PeterLawrey) - Peter Lawrey, Java performance expert.
- [Randy Shoup](https://twitter.com/randyshoup) - Stitch Fix VP Engineering, speaker, JavaOne Rock Star.
- [Reza Rahman](https://twitter.com/reza_rahman) - Java EE/GlassFish/WebLogic evangelist, author, speaker, open source hacker.
- [Simon Maple](https://twitter.com/sjmaple) - Java Champion, VirtualJUG founder, LJC leader, RebelLabs author.
- [Stephen Colebourne](https://twitter.com/jodastephen) - Java Champion, speaker.
- [Trisha Gee](https://twitter.com/trisha_gee) - Java Champion and speaker.
- [Venkat Subramaniam](https://twitter.com/venkat_s) - Author, University of Houston professor, MicroSoft MVP award recipient, JavaOne Rock Star, Java Champion.

### Websites

*Sites to read.*

- [Google Java Style](https://google.github.io/styleguide/javaguide.html)
- [InfoQ](https://www.infoq.com)
- [Java Algorithms and Clients](https://algs4.cs.princeton.edu/code)
- [Java, SQL, and jOOQ](https://blog.jooq.org)
- [Java.net](https://community.oracle.com/community/java)
- [Javalobby](https://dzone.com/java-jdk-development-tutorials-tools-news)
- [JavaWorld](https://www.javaworld.com)
- [JAXenter](https://jaxenter.com)
- [RebelLabs](https://zeroturnaround.com/rebellabs)
- [The Takipi Blog](http://blog.takipi.com)
- [TheServerSide.com](http://www.theserverside.com)
- [Vanilla Java](https://vanilla-java.github.io)
- [Voxxed](https://www.voxxed.com)

## Contributing

Contributions are very welcome!

Please have a look at the [CONTRIBUTING](https://github.com/akullpp/awesome-java/blob/master/CONTRIBUTING.md) guidelines.

[c]: https://cdn.rawgit.com/akullpp/23246ca832bda82bb505230bf3538e2a/raw/d9bcdb769bf025292f9c6bc1290f01f1fcd1f864/commercial.svg


# Information comes from [akullpp/awesome-java](https://github.com/akullpp/awesome-java)
# Awesome Java [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Java frameworks, libraries and software.

## Contents

- [Projects](#projects)
  - [Bean Mapping](#bean-mapping)
  - [Build](#build)
  - [Bytecode Manipulation](#bytecode-manipulation)
  - [Caching](#caching)
  - [CLI](#cli)
  - [Cluster Management](#cluster-management)
  - [Code Analysis](#code-analysis)
  - [Code Coverage](#code-coverage)
  - [Code Generators](#code-generators)
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
  - [Financial](#financial)
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
  - [Introspection](#introspection)
  - [Job Scheduling](#job-scheduling)
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
  - [Processes](#processes)
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

_Frameworks that ease bean mapping._

- [dOOv](https://github.com/doov-io/doov) - Provides fluent API for typesafe domain model validation and mapping. It uses annotations, code generation and a type safe DSL to make bean validation and mapping fast and easy. :star:46
- [Dozer](https://github.com/DozerMapper/dozer) - Mapper that copies data from one object to another using annotations and API or XML configuration. :star:1627
- [JMapper](https://jmapper-framework.github.io/jmapper-core) - Uses byte code manipulation for lightning-fast mapping. Supports annotations and API or XML configuration.
- [MapStruct](https://github.com/mapstruct/mapstruct) - Code generator that simplifies mappings between different bean types, based on a convention-over-configuration approach. :star:2303
- [ModelMapper](https://github.com/jhalterman/modelmapper) - Intelligent object mapping library that automatically maps objects to each other. :star:1381
- [Orika](https://github.com/orika-mapper/orika) - JavaBean-mapping framework that recursively copies (among other capabilities) data from one object to another. :star:880
- [reMap](https://github.com/remondis-it/remap) - Lambda and method handle-based mapping which requires code and not annotations if objects have different names. :star:60
- [Selma](https://github.com/xebia-france/selma) - Annotation processor-based bean mapper. :star:187

### Build

_Tools that handle the build cycle and dependencies of an application._

- [Apache Maven](https://maven.apache.org) - Declarative build and dependency management that favors convention over configuration. It might be preferable to Apache Ant, which uses a rather procedural approach and can be difficult to maintain.
- [Bazel](https://bazel.io) - Tool from Google that builds code quickly and reliably.
- [Buck](https://github.com/facebook/buck) - Encourages the creation of small, reusable modules consisting of code and resources. :star:7183
- [Gradle](https://gradle.org) - Incremental builds programmed via Groovy instead of declaring XML. Works well with Maven's dependency management.

### Bytecode Manipulation

_Libraries to manipulate bytecode programmatically._

- [ASM](http://asm.ow2.org) - All-purpose, low-level bytecode manipulation and analysis.
- [Byte Buddy](http://bytebuddy.net) - Further simplifies bytecode generation with a fluent API.
- [bytecode-viewer](https://github.com/Konloch/bytecode-viewer) - Java 8 Jar & Android APK reverse engineering suite. (GPL-3.0-only) :star:10853
- [Byteman](https://byteman.jboss.org) - Manipulate bytecode at runtime via DSL (rules); mainly for testing/troubleshooting. (LGPL-2.1-or-later)
- [cglib](https://github.com/cglib/cglib) - Bytecode generation library. :star:3295
- [Javassist](https://jboss-javassist.github.io/javassist) - Tries to simplify bytecode editing.
- [Mixin](https://github.com/SpongePowered/Mixin) - Manipulate bytecode at runtime using real Java code. :star:331
- [Perses](https://github.com/nicolasmanic/perses) - Dynamically injects failure/latency at the bytecode level according to principles of chaos engineering. :star:41

### Caching

_Libraries that provide caching facilities._

- [cache2k](https://cache2k.org) - In-memory high performance caching library.
- [Caffeine](https://github.com/ben-manes/caffeine) - High-performance, near-optimal caching library. :star:7100
- [Ehcache](http://www.ehcache.org) - Distributed general-purpose cache.
- [Infinispan](http://infinispan.org) - Highly concurrent key/value datastore used for caching.

### CLI

_Libraries for everything related to the CLI._

- [ASCII Table](https://github.com/vdmeer/asciitable) - Library to draw tables in ASCII. :star:229
- [Airline](https://github.com/airlift/airline) - Annotation-based framework for parsing Git-like command-line arguments. :star:782
- [args4j](http://args4j.kohsuke.org) - Small library to parse command-line arguments.
- [Jansi](https://github.com/fusesource/jansi) - ANSI escape codes to format console output. :star:677
- [Java ASCII Render](https://github.com/indvd00m/java-ascii-render) - Graphical primitives for the console. :star:94
- [JCommander](http://jcommander.org) - Command-line argument-parsing framework with custom types and validation via implementing interfaces.
- [jbock](https://github.com/h908714124/jbock) - Typesafe, reflection-free, annotation based command-line parser. :star:31
- [Jexer](https://gitlab.com/klamonte/jexer) - Advanced console (and Swing) text user interface (TUI) library, with mouse-draggable windows, built-in terminal window manager, and sixel image support. Looks like [Turbo Vision](https://en.wikipedia.org/wiki/Turbo_Vision).
- [JLine](https://github.com/jline/jline3) - Includes features from modern shells like completion or history. :star:595
- [JOpt Simple](https://jopt-simple.github.io/jopt-simple) - Fluent parser that uses the POSIX#getopt and GNU#getopt_long syntaxes.
- [picocli](http://picocli.info) - ANSI colors and styles in usage help with annotation-based POSIX/GNU/any syntax, subcommands, strong typing for both options and positional args.
- [Text-IO](https://github.com/beryx/text-io) - Aids the creation of full console-based applications. :star:176
- [Lanterna](https://github.com/mabe02/lanterna) - Easy console text-GUI library, similar to curses. (LGPL-3.0-only) :star:1297

### Cluster Management

_Frameworks that can dynamically manage applications inside of a cluster._

- [Apache Aurora](https://aurora.apache.org) - Mesos framework for long-running services and cron jobs.
- [Apache Mesos](https://mesos.apache.org) - Abstracts CPU, memory, storage, and other compute resources away from machines.
- [Singularity](http://getsingularity.com) - Mesos framework that makes deployment and operations easy. It supports web services, background workers, scheduled jobs, and one-off tasks.

### Code Analysis

_Tools that provide metrics and quality measurements._

- [Checkstyle](https://github.com/checkstyle/checkstyle) - Static analysis of coding conventions and standards. (LGPL-2.1-or-later) :star:5043
- [Error Prone](https://github.com/google/error-prone) - Catches common programming mistakes as compile-time errors. :star:5016
- [Infer](https://github.com/facebook/infer) - Modern static analysis tool for verifying the correctness of code. :star:10598
- [jQAssistant](https://jqassistant.org) - Static code analysis with Neo4J-based query language. (GPL-3.0-only)
- [NullAway](https://github.com/uber/NullAway) - Eliminates NullPointerExceptions with low build-time overhead. :star:2682
- [PMD](https://github.com/pmd/pmd) - Source code analysis for finding bad coding practices. :star:2661
- [SonarJava](https://github.com/SonarSource/sonar-java) - Static analyzer for SonarQube & SonarLint. (LGPL-3.0-only) :star:594
- [Sourcetrail](https://www.sourcetrail.com) - Visual source code navigator.
- [Spoon](https://github.com/INRIA/spoon) - Library for analyzing and transforming Java source code. :star:889
- [Spotbugs](https://github.com/spotbugs/spotbugs) - Static analysis of bytecode to find potential bugs. (LGPL-2.1-only) :star:1662

### Code Coverage

_Frameworks and tools that enable code coverage metrics collection for test suites._

- [Clover](https://www.atlassian.com/software/clover/overview) - Relies on source-code instrumentation instead of bytecode instrumentation.
- [Cobertura](https://cobertura.github.io/cobertura) - Relies on offline (or static) bytecode instrumentation and class loading to collect code coverage metrics. (GPL-2.0-only)
- [JaCoCo](http://eclemma.org/jacoco) - Framework that enables collection of code coverage metrics, using both offline and runtime bytecode instrumentation.

### Code Generators

_Tools that generate patterns for repetitive code in order to reduce verbosity and error-proneness._

- [ADT4J](https://github.com/sviperll/adt4j) - JSR-269 code generator for algebraic data types. :star:126
- [Auto](https://github.com/google/auto) - Generates factory, service, and value classes. :star:8395
- [FreeBuilder](https://github.com/google/FreeBuilder) - Automatically generates the Builder pattern. :star:731
- [Immutables](https://immutables.github.io) - Annotation processors to generate simple, safe and consistent value objects.
- [JavaPoet](https://github.com/square/javapoet) - API to generate source files. :star:7708
- [JHipster](https://github.com/jhipster/generator-jhipster) - Yeoman source code generator for Spring Boot and AngularJS. :star:15504
- [Joda-Beans](http://www.joda.org/joda-beans) - Small framework that adds queryable properties to Java, enhancing JavaBeans.
- [Lombok](https://projectlombok.org) - Code generator that aims to reduce verbosity.

### Compiler-compiler

_Frameworks that help to create parsers, interpreters or compilers._

- [ANTLR](http://www.antlr.org) - Complex full-featured framework for top-down parsing.
- [JavaCC](https://javacc.org) - Parser generator that generates top-down parsers. Allows lexical state switching and permits extended BNF specifications.
- [JFlex](http://jflex.de) - A lexical analyzer generator.

### Configuration

_Libraries that provide external configuration._

- [centraldogma](https://github.com/line/centraldogma) - Highly-available version-controlled service configuration repository based on Git, ZooKeeper and HTTP/2. :star:307
- [cfg4j](https://github.com/cfg4j/cfg4j) - Modern configuration library for distributed apps written in Java. :star:499
- [config](https://github.com/typesafehub/config) - Configuration library for JVM languages. :star:4697
- [dotenv](https://github.com/shyiko/dotenv) - A twelve-factor configuration library for Java. :star:33
- [ini4j](http://ini4j.sourceforge.net) - Provides an API for handling Windows' INI files.
- [KAConf](https://github.com/mariomac/kaconf) - Annotation-based configuration system for Java and Kotlin. :star:37
- [owner](https://github.com/lviggiano/owner) - Reduces boilerplate of properties. :star:724

### Constraint Satisfaction Problem Solver

_Libraries that help with implementing optimization and satisfiability problems._

- [Choco](http://www.choco-solver.org) - Off-the-shelf constraint satisfaction problem solver that uses constraint programming techniques.
- [JaCoP](https://github.com/radsz/jacop) - Includes an interface for the FlatZinc language, enabling it to execute MiniZinc models. (AGPL-3.0) :star:160
- [OptaPlanner](https://www.optaplanner.org) - Business planning and resource scheduling optimization solver.

### CSV

_Frameworks and libraries that simplify reading/writing CSV data._

- [jackson-dataformat-csv](https://github.com/FasterXML/jackson-dataformat-csv) - Jackson extension for reading and writing CSV. :star:191
- [opencsv](http://opencsv.sourceforge.net) - Simple CSV parser.
- [Super CSV](https://super-csv.github.io/super-csv) - Powerful CSV parser with support for Dozer, Joda-Time and Java 8.
- [uniVocity-parsers](https://github.com/uniVocity/univocity-parsers) - One of the fastest and most feature-complete parsers. Also comes with parsers for TSV and fixed-width records. :star:684

### Database

_Everything that simplifies interactions with the database._

- [Apache Drill](https://drill.apache.org) - Distributed, schema on-the-fly, ANSI SQL query engine for Big Data exploration.
- [Apache Phoenix](https://phoenix.apache.org) - High-performance relational database layer over HBase for low-latency applications.
- [AranoDB](https://github.com/arangodb/arangodb-java-driver) - ArangoDB Java driver. :star:151
- [Chronicle Map](https://github.com/OpenHFT/Chronicle-Map) - Efficient, in-memory (opt. persisted to disk), off-heap key-value store. :star:1873
- [druid](https://druid.apache.org) - High-performance, column-oriented, distributed data store.
- [eXist](https://github.com/eXist-db/exist) - A NoSQL document database and application platform. (LGPL-2.1-only) :star:262
- [FlexyPool](https://github.com/vladmihalcea/flexy-pool) - Brings metrics and failover strategies to the most common connection pooling solutions. :star:748
- [Flyway](https://flywaydb.org) - Simple database migration tool.
- [H2](https://h2database.com) - Small SQL database notable for its in-memory functionality.
- [HikariCP](https://github.com/brettwooldridge/HikariCP) - High-performance JDBC connection pool. :star:12109
- [jasync-sql](https://github.com/jasync-sql/jasync-sql) - Async DB driver for MySQL and PostgreSQL. :star:752
- [JDBI](http://jdbi.org) - Convenient abstraction of JDBC.
- [Jedis](https://github.com/xetorthio/jedis) - Small client for interaction with Redis, with methods for commands. :star:8848
- [Jest](https://github.com/searchbox-io/Jest) - Client for the Elasticsearch REST API. :star:1889
- [jetcd](https://github.com/justinsb/jetcd) - Client library for etcd. :star:130
- [Jinq](https://github.com/my2iu/Jinq) - Typesafe database queries via symbolic execution of Java 8 Lambdas (on top of JPA or jOOQ). :star:564
- [jOOQ](https://www.jooq.org) - Generates typesafe code based on SQL schema.
- [Leaf](https://github.com/Meituan-Dianping/Leaf) - Distributed ID generate service. :star:2765
- [Liquibase](http://www.liquibase.org) - Database-independent library for tracking, managing and applying database schema changes.
- [MapDB](http://www.mapdb.org) - Embedded database engine that provides concurrent collections backed on disk or in off-heap memory.
- [MariaDB4j](https://github.com/vorburger/MariaDB4j) - Launcher for MariaDB that requires no installation or external dependencies. :star:473
- [OrientDB](https://orientdb.com/orientdb) - Embeddable distributed database written on top of Hazelcast.
- [Presto](https://prestosql.io) - Distributed SQL query engine for big data.
- [Querydsl](http://www.querydsl.com) - Typesafe unified queries.
- [Realm](https://github.com/realm/realm-java) - Mobile database to run directly inside phones, tablets or wearables. :star:10822
- [Redisson](https://github.com/mrniko/redisson) - Allows for distributed and scalable data structures on top of a Redis server. :star:11924
- [requery](https://github.com/requery/requery) - A modern, lightweight but powerful object mapping and SQL generator. Easily map to or create databases, or perform queries and updates from any Java-using platform. :star:2927
- [Speedment](https://github.com/speedment/speedment) - Database access library that utilizes Java 8's Stream API for querying. :star:1772
- [sql2o](https://sql2o.org) - Thin JDBC wrapper that simplifies database access and provides simple mapping of ResultSets to POJOs.
- [Vibur DBCP](https://www.vibur.org) - JDBC connection pool library with advanced performance monitoring capabilities.
- [Xodus](https://jetbrains.github.io/xodus) - Highly concurrent transactional schema-less and ACID-compliant embedded database.

### Data Structures

_Efficient and specific data structures._

- [Apache Avro](https://avro.apache.org) - Data interchange format with dynamic typing, untagged data, and absence of manually assigned IDs.
- [Apache Orc](https://orc.apache.org) - Fast and efficient columnar storage format for Hadoop-based workloads.
- [Apache Parquet](https://parquet.apache.org) - Columnar storage format based on assembly algorithms from Google's paper on Dremel.
- [Apache Thrift](https://thrift.apache.org) - Data interchange format that originated at Facebook.
- [Big Queue](https://github.com/bulldog2011/bigqueue) - A big, fast and persistent queue based on memory-mapped files. :star:366
- [HyperMinHash-java](https://github.com/LiveRamp/HyperMinHash-java) - Probabilistic data structure for computing union, intersection, and set cardinality in loglog space. :star:28
- [Persistent Collection](https://pcollections.org) - Persistent and immutable analogue of the Java Collections Framework.
- [Protobuf](https://github.com/google/protobuf) - Google's data interchange format. :star:39622
- [SBE](https://github.com/real-logic/simple-binary-encoding) - Simple Binary Encoding, one of the fastest message formats around. :star:2113
- [Tape](https://github.com/square/tape) - A lightning-fast, transactional, file-based FIFO. :star:2335
- [Wire](https://github.com/square/wire) - Clean, lightweight protocol buffers. :star:3034

### Date and Time

_Libraries related to handling date and time._

- [Almanac Converter](https://github.com/hypotemoose/almanac-converter) - Simple conversion between different calendar systems. :star:21
- [iCal4j](https://github.com/ical4j/ical4j) - Parse and build iCalendar [RFC 5545](https://tools.ietf.org/html/rfc5545) data models. :star:423
- [ThreeTen-Extra](https://github.com/ThreeTen/threeten-extra) - Additional date-time classes that complement those in JDK 8. :star:235
- [Time4J](https://github.com/MenoData/Time4J) - Advanced date and time library. (LGPL-2.1-only) :star:278

### Dependency Injection

_Libraries that help to realize the [Inversion of Control](https://en.wikipedia.org/wiki/Inversion_of_control) paradigm._

- [Apache DeltaSpike](https://deltaspike.apache.org) - CDI extension framework.
- [Dagger2](https://google.github.io/dagger) - Compile-time injection framework without reflection.
- [Feather](https://github.com/zsoltherpai/feather) - Ultra-lightweight, JSR-330-compliant dependency injection library. :star:297
- [Governator](https://github.com/Netflix/governator) - Extensions and utilities that enhance Google Guice. :star:746
- [Guice](https://github.com/google/guice) - Lightweight and opinionated framework that completes Dagger. :star:8946
- [HK2](https://javaee.github.io/hk2) - Lightweight and dynamic dependency injection framework.
- [JayWire](https://github.com/vanillasource/jaywire) - Lightweight dependency injection framework. (LGPL-3.0-only) :star:46

### Development

_Augmentation of the development process at a fundamental level._

- [AspectJ](https://eclipse.org/aspectj) - Seamless aspect-oriented programming extension.
- [DCEVM](https://dcevm.github.io) - JVM modification that allows unlimited redefinition of loaded classes at runtime. (GPL-2.0-only)
- [Faux Pas](https://github.com/zalando/faux-pas) - Library that simplifies error handling by circumventing the issue that none of the functional interfaces in the Java Runtime is allowed by default to throw checked exceptions. :star:82
- [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent) - Unlimited runtime class and resource redefinition. (GPL-2.0-only) :star:1413
- [JavaParser](https://github.com/javaparser/javaparser) - Parse, modify and generate Java code. :star:2906
- [JavaSymbolSolver](https://github.com/javaparser/javasymbolsolver) - A symbol solver for Java. :star:255
- [Manifold](https://manifold.systems) - Re-energizes Java with powerful features like type-safe metaprogramming, structural typing and extension methods.
- [NoException](https://noexception.machinezoo.com) - Allows checked exceptions in functional interfaces and converts exceptions to Optional return.
- [SneakyThrow](https://github.com/rainerhahnekamp/sneakythrow) - Ignores checked exceptions without bytecode manipulation. Can also be used inside Java 8 stream operations. :star:56

### Distributed Applications

_Libraries and frameworks for writing distributed and fault-tolerant applications._

- [Apache Geode](https://geode.apache.org) - In-memory data management system that provides reliable asynchronous event notifications and guaranteed message delivery.
- [Apache Storm](https://storm.apache.org) - Realtime computation system.
- [Apache ZooKeeper](https://zookeeper.apache.org) - Coordination service with distributed configuration, synchronization, and naming registry for large distributed systems.
- [Atomix](https://atomix.io) - Fault-tolerant distributed coordination framework.
- [Axon Framework](http://www.axonframework.org) - Framework for creating CQRS applications.
- [Dropwizard Circuit Breaker](https://github.com/mtakaki/dropwizard-circuitbreaker) - Circuit breaker design pattern for Dropwizard. (GPL-2.0-only) :star:36
- [Failsafe](https://github.com/jhalterman/failsafe) - Simple failure handling with retries and circuit breakers. :star:3076
- [Hazelcast](https://hazelcast.org) - Highly scalable in-memory datagrid with a free open-source version.
- [JGroups](http://www.jgroups.org) - Toolkit for reliable messaging and cluster creation.
- [Orbit](http://www.orbit.cloud) - Virtual actors; adds another level of abstraction to traditional actors.
- [Quasar](https://www.paralleluniverse.co/quasar) - Lightweight threads and actors for the JVM.
- [resilience4j](https://github.com/resilience4j/resilience4j) - Functional fault tolerance library. :star:4925
- [ScaleCube](https://github.com/scalecube/scalecube) - Embeddable Cluster-Membership library based on SWIM and gossip protocol. :star:403
- [Zuul](https://github.com/Netflix/zuul) - A gateway service that provides dynamic routing, monitoring, resiliency, security, and more. :star:8750

### Distributed Transactions

_Distributed transactions provide a mechanism for ensuring consistency of data updates in the presence of concurrent access and partial failures._

- [Atomikos](https://www.atomikos.com) - Provides transactions for REST, SOA and microservices with support for JTA and XA.
- [Bitronix](https://github.com/bitronix/btm) - A simple but complete implementation of the JTA 1.1 API. :star:361
- [Narayana](http://narayana.io) - Provides support for traditional ACID and compensation transactions, also complies with JTA, JTS and other standards. (LGPL-2.1-only)
- [Seata](https://seata.io) - Delivers high performance and easy to use distributed transaction services under a microservices architecture.

### Distribution

_Tools that handle the distribution of applications in native formats._

- [Boxfuse ![c]](https://boxfuse.com) - Deployment of JVM applications to AWS using the principles of immutable infrastructure.
- [Capsule](http://www.capsule.io) - Simple and powerful packaging and deployment. A fat JAR on steroids, or a "Docker for Java" that supports JVM-optimized containers.
- [Central Repository](https://search.maven.org) - Largest binary component repository available as a free service to the open-source community. Default used by Apache Maven, and available in all other build tools.
- [IzPack](http://izpack.org) - Setup authoring tool for cross-platform deployments.
- [Nexus ![c]](https://www.sonatype.com/nexus/solution-overview) - Binary management with proxy and caching capabilities.
- [packr](https://github.com/libgdx/packr) - Packs JARs, assets and the JVM for native distribution on Windows, Linux and Mac OS X. :star:2011
- [really-executable-jars-maven-plugin](https://github.com/brianm/really-executable-jars-maven-plugin) - Maven plugin for making self-executing JARs. :star:91

### Document Processing

_Libraries that assist with processing office document formats._

- [Apache POI](https://poi.apache.org) - Supports OOXML (XLSX, DOCX, PPTX) as well as OLE2 (XLS, DOC or PPT).
- [documents4j](http://documents4j.com) - API for document format conversion using third-party converters such as MS Word.
- [docx4j](https://www.docx4java.org/trac/docx4j) - Create and manipulate Microsoft Open XML files.
- [zerocell](https://github.com/creditdatamw/zerocell) - Annotation-based API for reading data from Excel sheets into POJOs with focus on reduced overhead. :star:33

### Financial

*Libraries related to the financial domain.*

- [Parity](https://github.com/paritytrading/parity) - Platform for trading venues. :star:388
- [Philadelphia](https://github.com/paritytrading/philadelphia) - Low-latency financial information exchange. :star:167
- [Stripe](https://github.com/stripe/stripe-java) - Integration with the Stripe API :star:464
- [Square](https://github.com/square/connect-java-sdk/) - Integration with the Square API. :star:35

### Formal Verification

_Formal-methods tools: proof assistants, model checking, symbolic execution, etc._

- [CATG](https://github.com/ksen007/janala2) - Concolic unit testing engine. Automatically generates unit tests using formal methods. :star:72
- [Checker Framework](https://checkerframework.org) - Pluggable type systems. Includes nullness types, physical units, immutability types and more. (GPL-2.0-only WITH Classpath-exception-2.0)
- [Daikon](https://plse.cs.washington.edu/daikon) - Detects likely program invariants and generates JML specs based on those invariants.
- [Java Path Finder (JPF)](https://github.com/javapathfinder/jpf-core) - JVM formal verification tool containing a model checker and more. Created by NASA. :star:187
- [JMLOK 2.0](http://massoni.computacao.ufcg.edu.br/home/jmlok) - Detects inconsistencies between code and JML specification through feedback-directed random tests generation, and suggests a likely cause for each nonconformance detected. (GPL-3.0-only)
- [KeY](https://key-project.org) - Formal software development tool that aims to integrate design, implementation, formal specification, and formal verification of object-oriented software as seamlessly as possible. Uses JML for specification and symbolic execution for verification. (GPL-2.0-or-later)
- [OpenJML](https://openjml.github.io) - Translates JML specifications into SMT-LIB format and passes the proof problems implied by the program to backend solvers. (GPL-2.0-only)

### Functional Programming

_Libraries that facilitate functional programming._

- [cyclops-react](https://github.com/aol/cyclops-react) - Monad and stream utilities, comprehensions, pattern matching, functional extensions for all JDK collections, future streams, trampolines and much more. :star:1076
- [derive4j](https://github.com/derive4j/derive4j) - Java 8 annotation processor and framework for deriving algebraic data types constructors, pattern-matching and morphisms. (GPL-3.0-only) :star:482
- [Fugue](https://bitbucket.org/atlassian/fugue) - Functional extensions to Guava.
- [Functional Java](http://www.functionaljava.org) - Implements numerous basic and advanced programming abstractions that assist composition-oriented development.
- [jOOλ](https://github.com/jOOQ/jOOL) - Extension to Java 8 that aims to fix gaps in lambda by providing numerous missing types and a rich set of sequential Stream API additions. :star:1609
- [protonpack](https://github.com/poetix/protonpack) - Collection of stream utilities. :star:395
- [StreamEx](https://github.com/amaembo/streamex) - Enhances Java 8 Streams. :star:1240
- [Vavr](http://www.vavr.io) - Functional component library that provides persistent data types and functional control structures.

### Game Development

_Frameworks that support the development of games._

- [FXGL](https://almasb.github.io/FXGL) - JavaFX Game Development Framework.
- [jMonkeyEngine](http://jmonkeyengine.org) - Game engine for modern 3D development.
- [libGDX](https://libgdx.badlogicgames.com) - All-round cross-platform, high-level framework.
- [LWJGL](https://www.lwjgl.org) - Robust framework that abstracts libraries like OpenGL/CL/AL.

### Geospatial

_Libraries for working with geospatial data and algorithms._

- [Apache SIS](https://sis.apache.org) - Library for developing geospatial applications.
- [Geo](https://github.com/davidmoten/geo) - GeoHash utilities in Java. :star:301
- [Geotoolkit.org](http://www.geotoolkit.org) - Library for developing geospatial applications. Built on top of the Apache SIS project. (LGPL-2.1-only)
- [GeoTools](https://geotools.org) - Library that provides tools for geospatial data. (LGPL-2.1-only)
- [GraphHopper](https://github.com/graphhopper/graphhopper) - Road-routing engine. Used as a Java library or standalone web service. :star:2384
- [H2GIS](http://www.h2gis.org) - A spatial extension of the H2 database. (LGPL-3.0-only)
- [Jgeohash](https://astrapi69.github.io/jgeohash) - Library for using the GeoHash algorithm.
- [Mapsforge](https://github.com/mapsforge/mapsforge) - Map rendering based on OpenStreetMap data. (LGPL-3.0-only) :star:785
- [Spatial4j](https://github.com/locationtech/spatial4j) - General-purpose spatial/geospatial library. :star:636

### GUI

_Libraries to create modern graphical user interfaces._

- [JavaFX](https://wiki.openjdk.java.net/display/OpenJFX/Main) - The successor of Swing.
- [Scene Builder](https://gluonhq.com/open-source/scene-builder) - Visual layout tool for JavaFX applications.
- [SWT](https://www.eclipse.org/swt) - The Standard Widget Toolkit, a graphical widget toolkit.

### High Performance

_Everything about high-performance computation, from collections to specific libraries._

- [Agrona](https://github.com/real-logic/Agrona) - Data structures and utility methods that are common in high-performance applications. :star:1577
- [Disruptor](https://lmax-exchange.github.io/disruptor) - Inter-thread messaging library.
- [Eclipse Collections](https://github.com/eclipse/eclipse-collections) - Collections framework inspired by Smalltalk. :star:1282
- [fastutil](http://fastutil.di.unimi.it) - Fast and compact type-specific collections.
- [HPPC](https://labs.carrotsearch.com/hppc.html) - Primitive collections.
- [JCTools](https://github.com/JCTools/JCTools) - Concurrency tools currently missing from the JDK. :star:2199
- [Koloboke](https://koloboke.com) - Hash sets and hash maps.

### HTTP Clients

_Libraries that assist with creating HTTP requests and/or binding responses._

- [Armeria](https://github.com/line/armeria) - Asynchronous RPC/REST client/server library built on top of Java 8, Netty, HTTP/2, Thrift and gRPC. :star:2378
- [Async Http Client](https://github.com/AsyncHttpClient/async-http-client) - Asynchronous HTTP and WebSocket client library. :star:5290
- [Feign](https://github.com/Netflix/feign) - HTTP client binder inspired by Retrofit, JAXRS-2.0, and WebSocket. :star:5360
- [OkHttp](https://square.github.io/okhttp) - HTTP+SPDY client.
- [Play WS](https://github.com/playframework/play-ws) - Typesafe client with reactive streams and caching. :star:185
- [restQL-core-java](https://github.com/B2W-BIT/restQL-java) - Microservice query language that fetches information from multiple services. :star:36
- [Retrofit](https://square.github.io/retrofit) - Typesafe REST client.
- [Ribbon](https://github.com/Netflix/ribbon) - Client-side IPC library that is battle-tested in cloud. :star:3348
- [Riptide](https://github.com/zalando/riptide) - Client-side response routing for Spring's RestTemplate. :star:126
- [unirest-java](https://github.com/Kong/unirest-java) - Simplified, lightweight HTTP client library. :star:1844

### Hypermedia Types

_Libraries that handle serialization to hypermedia types._

- [JSON-LD](https://github.com/jsonld-java/jsonld-java) - JSON-LD implementation. :star:302
- [Siren4J](https://github.com/eserating/siren4j) - Library for the Siren specification. :star:21

### IDE

_Integrated development environments that try to simplify several aspects of development._

- [Eclipse](https://www.eclipse.org) - Established open-source project with support for lots of plugins and languages.
- [IntelliJ IDEA ![c]](https://www.jetbrains.com/idea) - Supports many JVM languages and provides good options for Android development. The commercial edition targets the enterprise sector.
- [jGRASP](https://www.jgrasp.org) - Created to provide software visualizations that work in conjunction with the debugger such as Control Structure Diagrams, UML class diagrams and Object Viewer.
- [NetBeans](https://netbeans.apache.org) - Provides integration for several Java SE and EE features, from database access to HTML5.
- [Visual Studio Code](https://code.visualstudio.com/docs/languages/java) - Provides Java support for lightweight projects with a simple, modern workflow by using extensions from the internal marketplace.

### Imagery

_Libraries that assist with the creation, evaluation or manipulation of graphical images._

- [Imgscalr](https://github.com/thebuzzmedia/imgscalr) - Simple, efficient and hardware-accelerated image-scaling library implemented in pure Java 2D. :star:993
- [Tess4J](https://github.com/nguyenq/tess4j) - A JNA wrapper for Tesseract OCR API. :star:804
- [Thumbnailator](https://github.com/coobird/thumbnailator) - High-quality thumbnail generation library. :star:2678
- [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys) - Collection of plugins that extend the number of supported image file formats. :star:1005
- [ZXing](https://github.com/zxing/zxing) - Multi-format 1D/2D barcode image processing library. :star:24582
- [image-comparison](https://github.com/romankh3/image-comparison) - Compares two images with the same sizes and shows the differences visually by drawing rectangles. :star:78

### Introspection

_Libraries that help make the Java introspection and reflection API easier and faster to use._

- [ClassGraph](https://github.com/classgraph/classgraph) - ClassGraph (formerly FastClasspathScanner) is an uber-fast, ultra-lightweight, parallelized classpath scanner and module scanner for Java, Scala, Kotlin and other JVM languages. :star:1590
- [jOOR](https://github.com/jOOQ/jOOR) - jOOR stands for jOOR Object Oriented Reflection. It is a simple wrapper for the java.lang.reflect package. :star:2143
- [Mirror](http://projetos.vidageek.net/mirror/mirror) - Mirror was created to bring light to a simple problem, usually named ReflectionUtil, which is on almost all projects that rely on reflection to do advanced tasks.
- [Objenesis](http://objenesis.org) - Allows dynamic instantiation without default constructor, e.g. constructors which have required arguments, side effects or throw exceptions.
- [ReflectASM](https://github.com/EsotericSoftware/reflectasm) - ReflectASM is a very small Java library that provides high performance reflection by using code generation. :star:1033
- [Reflections](https://github.com/ronmamo/reflections) - Reflections scans your classpath, indexes the metadata, allows you to query it on runtime and may save and collect that information for many modules within your project. :star:2991

### Job Scheduling

_Libraries for scheduling background jobs._

- [Quartz](https://github.com/quartz-scheduler/quartz) - Feature-rich, open source job scheduling library that can be integrated within virtually any Java application. :star:3387
- [Sundial](https://github.com/knowm/Sundial) - Lightweight framework to simply define jobs, define triggers and start the scheduler. :star:201
- [Wisp](https://github.com/Coreoz/Wisp) - Simple library with minimal footprint and straightforward API. :star:27
- [db-scheduler](https://github.com/kagkarlsson/db-scheduler) - Persistent and cluster-friendly scheduler. :star:182

### JSON

_Libraries for serializing and deserializing JSON to and from Java objects._

- [DSL-JSON](https://github.com/ngs-doo/dsl-json) - JSON library with advanced compile time databinding. :star:597
- [Genson](https://owlike.github.io/genson) - Powerful and easy-to-use Java-to-JSON conversion library.
- [Gson](https://github.com/google/gson) - Serializes objects to JSON and vice versa. Good performance with on-the-fly usage. :star:17192
- [HikariJSON](https://github.com/brettwooldridge/HikariJSON) - High-performance JSON parser, 2x faster than Jackson. :star:379
- [jackson-modules-java8](https://github.com/FasterXML/jackson-modules-java8) - Set of Jackson modules for Java 8 datatypes and features. :star:259
- [Jackson-datatype-money](https://github.com/zalando/jackson-datatype-money) - Open-source Jackson module to support JSON serialization and deserialization of JavaMoney data types. :star:125
- [Jackson](https://github.com/FasterXML/jackson) - Similar to GSON, but offers performance gains if you need to instantiate the library more often. :star:5262
- [JSON-io](https://github.com/jdereg/json-io) - Convert Java to JSON. Convert JSON to Java. Pretty print JSON. Java JSON serializer. :star:242
- [jsoniter](http://jsoniter.com) - Fast and flexible library with iterator and lazy parsing API.
- [LoganSquare](https://github.com/bluelinelabs/LoganSquare) - JSON parsing and serializing library based on Jackson's streaming API. Outperforms GSON & Jackson's library. :star:3233
- [Moshi](https://github.com/square/moshi) - Modern JSON library, less opinionated and uses built-in types like List and Map. :star:5802
- [Yasson](https://github.com/eclipse/yasson) - Binding layer between classes and JSON documents similar to JAXB. :star:130

### JSON Processing

_Libraries for processing data in JSON format._

- [fastjson](https://github.com/alibaba/fastjson) - Very fast processor with no additional dependencies and full data binding. :star:20496
- [Jolt](https://github.com/bazaarvoice/jolt) - JSON to JSON transformation tool. :star:888
- [JsonPath](https://github.com/jayway/JsonPath) - Extract data from JSON using XPATH-like syntax. :star:4534
- [JsonSurfer](https://github.com/jsurfer/JsonSurfer) - Streaming JsonPath processor dedicated to processing big and complicated JSON data. :star:155

### JVM and JDK

_Current implementations of the JVM/JDK._

- [Adopt Open JDK](https://adoptopenjdk.net) - Community-driven OpenJDK builds, including both HotSpot and OpenJ9.
- [Avian](https://github.com/ReadyTalk/avian) - JVM with JIT, AOT modes and iOS port. :star:1164
- [Corretto](https://aws.amazon.com/corretto) - No-cost, multiplatform, production-ready distribution of OpenJDK by Amazon. (GPL-2.0-only WITH Classpath-exception-2.0)
- [Graal](https://github.com/oracle/graal) - Polyglot embeddable JVM. (GPL-2.0-only WITH Classpath-exception-2.0) :star:11606
- [Liberica JDK](https://www.bell-sw.com/java.html) - Built from OpenJDK, thoroughly tested and passed the JCK. (GPL-2.0-only WITH Classpath-exception-2.0)
- [OpenJ9](https://github.com/eclipse/openj9) - High performance, enterprise-calibre, flexibly licensed, openly-governed cross-platform JVM extending and augmenting the runtime technology components from the Eclipse OMR and OpenJDK project. :star:2194
- [Open JDK](https://openjdk.java.net) - Open JDK community home. (GPL-2.0-only WITH Classpath-exception-2.0)
- [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm) - VM with non-blocking, concurrent GC for iOS. (GPL-2.0-only WITH Classpath-exception-2.0) :star:896
- [RedHat Open JDK](https://developers.redhat.com/products/openjdk/overview) - RedHat's OpenJDK distribution. (GPL-2.0-only WITH Classpath-exception-2.0)
- [SAP Machine](https://sap.github.io/SapMachine) - SAP's no-cost, rigorously tested and JCK-verified OpenJDK friendly fork. (GPL-2.0-only WITH Classpath-exception-2.0)
- [Zulu](https://www.azul.com/downloads/zulu) - OpenJDK builds for Windows, Linux, and Mac OS X. (GPL-2.0-only WITH Classpath-exception-2.0)

### Logging

_Libraries that log the behavior of an application._

- [Apache Log4j 2](https://logging.apache.org/log4j) - Complete rewrite with a powerful plugin and configuration architecture.
- [Graylog](https://www.graylog.org) - Open-source aggregator suited for extended role and permission management. (GPL-3.0-only)
- [Kibana](https://www.elastic.co/products/kibana) - Analyzes and visualizes log files. Some features require payment.
- [Logback](https://logback.qos.ch) - Robust logging library with interesting configuration options via Groovy.
- [Logbook](https://github.com/zalando/logbook) - Extensible, open-source library for HTTP request and response logging. :star:499
- [Logstash](https://www.elastic.co/products/logstash) - Tool for managing log files.
- [p6spy](https://github.com/p6spy/p6spy) - Enables logging for all JDBC transactions without changes to the code. :star:1072
- [SLF4J](https://www.slf4j.org) - Abstraction layer/simple logging facade.
- [tinylog](http://www.tinylog.org) - Lightweight logging framework with static logger class.
- [Tracer](https://github.com/zalando/tracer) - Call tracing and log correlation in distributed systems. :star:126

### Machine Learning

_Tools that provide specific statistical algorithms for learning from data._

- [Apache Flink](https://flink.apache.org) - Fast, reliable, large-scale data processing engine.
- [Apache Mahout](https://mahout.apache.org) - Scalable algorithms focused on collaborative filtering, clustering and classification.
- [Apache Spark](https://spark.apache.org) - Data analytics cluster-computing framework.
- [DatumBox](http://www.datumbox.com) - Provides several algorithms and pre-trained models for natural language processing.
- [DeepDive](http://deepdive.stanford.edu) - Creates structured information from unstructured data and integrates it into an existing database.
- [Deeplearning4j](https://deeplearning4j.org) - Distributed and multi-threaded deep learning library.
- [H2O](https://www.h2o.ai) - Analytics engine for statistics over big data.
- [JSAT](https://github.com/EdwardRaff/JSAT) - Algorithms for pre-processing, classification, regression, and clustering with support for multi-threaded execution. (GPL-3.0-only) :star:603
- [Oryx 2](https://github.com/OryxProject/oryx) - Framework for building real-time, large-scale machine learning applications. Includes end-to-end applications for collaborative filtering, classification, regression, and clustering. :star:1686
- [Smile](https://haifengl.github.io/smile) - The Statistical Machine Intelligence and Learning Engine provides a set of machine learning algorithms and a visualization library.
- [Synapses](https://mrdimosthenis.github.io/Synapses) - Lightweight library for neural networks.
- [Weka](https://www.cs.waikato.ac.nz/ml/weka) - Collection of algorithms for data mining tasks ranging from pre-processing to visualization. (GPL-3.0-only)

### Messaging

_Tools that help send messages between clients to ensure protocol independency._

- [Aeron](https://github.com/real-logic/Aeron) - Efficient, reliable, unicast and multicast message transport. :star:4843
- [Apache ActiveMQ](https://activemq.apache.org) - Message broker that implements JMS and converts synchronous to asynchronous communication.
- [Apache Camel](https://camel.apache.org) - Glues together different transport APIs via Enterprise Integration Patterns.
- [Apache Kafka](https://kafka.apache.org) - High-throughput distributed messaging system.
- [Apache Pulsar](https://pulsar.apache.org) - Distributed pub/sub-messaging system.
- [Apache RocketMQ](https://rocketmq.apache.org) - Fast, reliable, and scalable distributed messaging platform.
- [Apache Qpid](https://qpid.apache.org) - Apache Qpid makes messaging tools that speak AMQP and support many languages and platforms.
- [EventBus](https://github.com/greenrobot/EventBus) - Simple publish/subscribe event bus. :star:22102
- [Hermes](http://hermes.allegro.tech) - Fast and reliable message broker built on top of Kafka.
- [JeroMQ](https://github.com/zeromq/jeromq) - Implementation of ZeroMQ. :star:1809
- [Nakadi](https://github.com/zalando/nakadi) - Provides a RESTful API on top of Kafka. :star:571
- [RabbitMQ Java client](https://github.com/rabbitmq/rabbitmq-java-client) - RabbitMQ client. :star:850
- [Smack](https://github.com/igniterealtime/Smack) - Cross-platform XMPP client library. :star:2047
- [NATS client](https://github.com/nats-io/java-nats) - NATS client. :star:250

### Miscellaneous

_Everything else._

- [Codename One](https://www.codenameone.com) - Cross-platform solution for writing native mobile apps. (GPL-2.0-only WITH Classpath-exception-2.0)
- [CQEngine](https://github.com/npgall/cqengine) - Ultra-fast, SQL-like queries on Java collections. :star:1112
- [Design Patterns](https://github.com/iluwatar/java-design-patterns) - Implementation and explanation of the most common design patterns. :star:54936
- [Failsafe](https://github.com/jhalterman/failsafe) - Simple failure handling with retries and circuit breakers. :star:3076
- [FF4J](https://github.com/ff4j/ff4j) - Feature Flags for Java. :star:695
- [FizzBuzz Enterprise Edition](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) - No-nonsense implementation of FizzBuzz made by serious businessmen for serious business purposes. (No explicit license) :star:12276
- [J2ObjC](https://github.com/google/j2objc) - Java-to-Objective-C translator for porting Android libraries to iOS. :star:5579
- [JavaCV](https://github.com/bytedeco/javacv) - Java interface to OpenCV, FFmpeg, and more. :star:3982
- [JavaX](http://javax.botcompany.de) - Reinventing and extending Java with a focus on simplicity. (No explicit license)
- [JBake](http://jbake.org) - Static website generator.
- [JBot](https://github.com/ramswaroop/jbot) - Framework for building chatbots. (GPL-3.0-only) :star:1078
- [JCuda](http://jcuda.org) - JCuda offers Java bindings for CUDA and CUDA-related libraries.
- [Jimfs](https://github.com/google/jimfs) - In-memory file system. :star:1725
- [Joda-Money](http://www.joda.org/joda-money) - Basic currency and money classes and algorithms not provided by the JDK.
- [JPad](http://jpad.io) - Snippet runner.
- [Maven Wrapper](https://github.com/takari/maven-wrapper) - Analogue of Gradle Wrapper for Maven, allows building projects without installing maven. :star:1201
- [Membrane Service Proxy](https://github.com/membrane/service-proxy) - An open-source, reverse-proxy framework written in Java. :star:307
- [MinimalFTP](https://github.com/Guichaguri/MinimalFTP) - Lightweight, small and customizable FTP server. :star:67
- [Modern Java - A Guide to Java 8](https://github.com/winterbe/java8-tutorial) - Popular Java 8 guide. :star:12593
- [Modernizer](https://github.com/andrewgaul/modernizer-maven-plugin) - Detect uses of legacy Java APIs. :star:213
- [Multi-OS Engine](https://multi-os-engine.org) - An open-source, cross-platform engine to develop native mobile (iOS, Android, etc.) apps.
- [OpenRefine](http://openrefine.org) - Tool for working with messy data: cleaning, transforming, extending it with web services and linking it to databases.
- [PipelinR](https://github.com/sizovs/pipelinr) – Small utility library for using handlers and commands with pipelines.
- [Polyglot for Maven](https://github.com/takari/polyglot-maven) - Extensions for Maven 3.3.1+ that allows writing the POM model in dialects other than XML. :star:676
- [Simple Java Mail](https://github.com/bbottema/simple-java-mail) - Mailing with a clean and fluent API.  :star:640
- [Smooks](https://github.com/smooks/smooks) - Extensible framework for building applications that process data which means bindings, transformations, message processing and enrichment. (LGPL-3.0-only) :star:266
- [Togglz](https://www.togglz.org) - Implementation of the Feature Toggles pattern.
- [TypeTools](https://github.com/jhalterman/typetools) - Tools for resolving generic types. :star:431
- [XMLBeam](https://github.com/SvenEwald/xmlbeam) - Processes XML by using annotations or XPath within code. :star:55
- [OctoLinker](https://github.com/OctoLinker/browser-extension) - Browser extension which allows to navigate through code on GitHub more efficiently. :star:4073
- [yGuard](https://github.com/yWorks/yGuard) - Obfuscation via renaming and shrinking. :star:72

### Microservice

_Tools for creating and managing microservices._

- [Apollo](https://spotify.github.io/apollo) - Libraries for writing composable microservices.
- [consul-api](https://github.com/Ecwid/consul-api) - Client for the Consul API: a distributed, highly available and datacenter-aware registry/discovery service. :star:331
- [Eureka](https://github.com/Netflix/eureka) - REST-based service registry for resilient load balancing and failover. :star:8873
- [Helidon](https://helidon.io) - Two-style approach for writing microservices: Functional-reactive and as an implementation of MicroProfile.
- [Lagom](https://www.lightbend.com/lagom) - Framework for creating microservice-based systems.
- [Micronaut](http://micronaut.io) - Modern full-stack framework with focus on modularity, minimal memory footprint and startup time.
- [Nacos](https://nacos.io) - Dynamic service discovery, configuration and service management platform for building cloud native applications.
- [Quarkus](https://quarkus.io) - Kubernetes stack tailored for the HotSpot and Graal VM.

### Monitoring

_Tools that monitor applications in production._

- [Automon](https://github.com/stevensouza/automon) - Combines the power of AOP with monitoring and/or logging tools. :star:530
- [LeakCanary](https://github.com/square/leakcanary) - Memory leak detection. :star:24268
- [Failsafe Actuator](https://github.com/zalando-incubator/failsafe-actuator) - Out of the box monitoring of Failsafe Circuit Breaker in Spring-Boot environment. :star:41
- [Glowroot](https://glowroot.org) - Open-source Java APM.
- [inspectIT](http://www.inspectit.rocks) - Captures detailed run-time information via hooks that can be changed on the fly. It supports tracing over multiple systems via the OpenTracing API and can correlate the data with end user monitoring.
- [Instrumental ![c]](https://instrumentalapp.com) - Real-time Java application performance monitoring. A commercial service with free development accounts.
- [JavaMelody](https://github.com/javamelody/javamelody) - Performance monitoring and profiling. :star:2111
- [Jaeger client](https://github.com/jaegertracing/jaeger-client-java) - Jaeger client. :star:339
- [jmxtrans](https://github.com/jmxtrans/jmxtrans) - Connect to multiple JVMs and query them for their attributes via JMX. Its query language is based on JSON, which allows non-Java programmers to access the JVM attributes. Supports different output writes, including Graphite, Ganglia, and StatsD. :star:1576
- [Jolokia](https://jolokia.org) - JMX over REST.
- [Kamon ![c]](https://kamon.io) - Tool for monitoring applications running on the JVM.
- [Metrics](http://metrics.dropwizard.io) - Expose metrics via JMX or HTTP and send them to a database.
- [Datadog ![c]](https://www.datadoghq.com) - Modern monitoring & analytics.
- [nudge4j](https://github.com/lorenzoongithub/nudge4j) - Remote developer console from the browser for Java 8 via bytecode injection. :star:141
- [Pinpoint](https://github.com/naver/pinpoint) - Open-source APM tool. :star:9830
- [Prometheus](https://prometheus.io) - Provides a multi-dimensional data model, DSL, autonomous server nodes and much more.
- [SPM ![c]](https://sematext.com/spm) - Performance monitor with distributing transaction tracing for JVM apps.
- [Stagemonitor](https://github.com/stagemonitor/stagemonitor) - Open-source performance monitoring and transaction tracing for JVM apps. :star:1537
- [Sysmon](https://github.com/palantir/Sysmon) - Lightweight platform monitoring tool for Java VMs. :star:148
- [zipkin](https://zipkin.io) - Distributed tracing system which gathers timing data needed to troubleshoot latency problems in microservice architectures.

### Native

_For working with platform-specific native libraries._

- [JavaCPP](https://github.com/bytedeco/javacpp) - Provides efficient and easy access to native C++. :star:3007
- [JNA](https://github.com/java-native-access/jna) - Work with native libraries without writing JNI. Also provides interfaces to common system libraries. :star:5486
- [JNR](https://github.com/jnr/jnr-ffi) - Work with native libraries without writing JNI. Also provides interfaces to common system libraries. Same goals as JNA, but faster, and serves as the basis for the upcoming [Project Panama](http://openjdk.java.net/projects/panama). :star:682

### Natural Language Processing

_Libraries that specialize in processing text._

- [Beagle](https://github.com/tokenmill/beagle) - Stored full-text search query engine. :star:26
- [CogCompNLP](https://github.com/CogComp/cogcomp-nlp) - Provides common annotators for plain text input. (Research and Academic Use License) :star:379
- [CoreNLP](https://nlp.stanford.edu/software/corenlp.shtml) - Provides a set of fundamental tools for tasks like tagging, named entity recognition, and sentiment analysis. (GPL-3.0-or-later)
- [DKPro](https://dkpro.github.io) - Collection of reusable NLP tools for linguistic pre-processing, machine learning, lexical resources, etc.
- [Lingua](https://github.com/pemistahl/lingua) - Natural language detection library, especially suited for short paragraphs of text. :star:119
- [LingPipe](http://alias-i.com/lingpipe) - Toolkit for tasks ranging from POS tagging to sentiment analysis.

### Networking

_Libraries for building network servers._

- [AkkaGRPC](https://github.com/akka/akka-grpc) - Support for building streaming gRPC servers and clients on top of Akka Streams. :star:288
- [Comsat](https://github.com/puniverse/comsat) - Integrates standard Java web-related APIs with Quasar fibers and actors. :star:554
- [Dubbo](https://github.com/alibaba/dubbo) - High-performance RPC framework. :star:30918
- [Finagle](https://github.com/twitter/finagle) - Extensible RPC system for constructing high-concurrency servers. It implements uniform client and server APIs for several protocols, and is protocol-agnostic to simplify implementation of new protocols. :star:7473
- [Grizzly](https://javaee.github.io/grizzly) - NIO framework. Used as a network layer in Glassfish.
- [gRPC](https://github.com/grpc/grpc-java) - RPC framework based on protobuf and HTTP/2. :star:7054
- [KryoNet](https://github.com/EsotericSoftware/kryonet) - Provides a clean and simple API for efficient TCP and UDP client/server network communication using NIO and Kryo. :star:1496
- [MINA](https://mina.apache.org) - Abstract, event-driven async I/O API for network operations over TCP/IP and UDP/IP via Java NIO.
- [Netty](https://netty.io) - Framework for building high-performance network applications.
- [Nifty](https://github.com/facebook/nifty) - Implementation of Thrift clients and servers on Netty. :star:879
- [ServiceTalk](https://github.com/apple/servicetalk) - Framework built on Netty with APIs tailored to specific protocols and support for multiple programming paradigms. :star:429
- [sshj](https://github.com/hierynomus/sshj) - Programatically use SSH, SCP or SFTP. :star:1589
- [TLS Channel](https://github.com/marianobarrios/tls-channel) - Implements a ByteChannel interface over SSLEngine, enabling easy-to-use (socket-like) TLS. :star:75
- [Undertow](http://undertow.io) - Web server providing both blocking and non-blocking APIs based on NIO. Used as a network layer in WildFly. (LGPL-2.1-only)
- [urnlib](https://github.com/slub/urnlib) - Represent, parse and encode URNs, as in RFC 2141. (GPL-3.0-only) :star:14

### ORM

_APIs that handle the persistence of objects._

- [Apache Cayenne](https://cayenne.apache.org) - Provides a clean, static API for data access. Also includes a GUI Modeler for working with database mappings, and DB reverse engineering and generation.
- [Doma 2](https://doma.readthedocs.io) - Database access framework that verifies and generates source code at compile time using annotation processing as well as native SQL templates called two-way SQL.
- [Ebean](https://ebean-orm.github.io) - Provides simple and fast data access.
- [EclipseLink](https://www.eclipse.org/eclipselink) - Supports a number of persistence standards: JPA, JAXB, JCA and SDO.
- [Hibernate](http://hibernate.org/orm) - Robust and widely used, with an active community. (LGPL-2.1-only)
- [MyBatis](http://www.mybatis.org/mybatis-3) - Couples objects with stored procedures or SQL statements.
- [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper) - Simple database and CSV mapper. :star:322

### PaaS

_Java platform as a service._

- [AWS Elastic Beanstalk ![c]](https://aws.amazon.com/elasticbeanstalk) - AWS-based, with support for Tomcat and Jetty.
- [AWS Lambda ![c]](https://aws.amazon.com/lambda) - Serverless computation.
- [Google Cloud ![c]](https://cloud.google.com) - Google's cloud infrastructure.
- [Heroku ![c]](https://www.heroku.com) - Abstract computing environments.
- [Microsoft Azure ![c]](https://azure.microsoft.com) - Microsoft's cloud infrastructure.
- [OpenShift ![c]](https://www.openshift.com) - Provides additionally an on-premise solution.

### PDF

_Tools to help with PDF file creation._

- [Apache FOP](https://xmlgraphics.apache.org/fop) - Creates PDFs from XSL-FO.
- [Apache PDFBox](https://pdfbox.apache.org) - Toolbox for creating and manipulating PDFs.
- [Dynamic Jasper](http://dynamicjasper.com) - Abstraction layer to JasperReports. (LGPL-3.0-only)
- [DynamicReports](https://github.com/dynamicreports/dynamicreports) - Simplifies JasperReports. (LGPL-3.0-only) :star:85
- [flyingsaucer](https://github.com/flyingsaucerproject/flyingsaucer) - XML/XHTML and CSS 2.1 renderer. (LGPL-2.1-or-later) :star:1411
- [iText ![c]](https://itextpdf.com) - Creates PDF files programmatically.
- [JasperReports](https://community.jaspersoft.com/project/jasperreports-library) - Complex reporting engine. (LGPL-3.0-only)
- [Open HTML to PDF](https://github.com/danfickle/openhtmltopdf) - Properly supports modern PDF standards based on flyingsaucer and Apache PDFBox. :star:711
- [OpenPDF](https://github.com/LibrePDF/OpenPDF) - Open-source iText fork. (LGPL-3.0-only & MPL-2.0) :star:1485

### Performance analysis

_Tools for performance analysis, profiling and benchmarking._

- [fastThread ![c]](http://fastthread.io) - Analyze and visualize thread dumps with a free cloud-based upload interface.
- [GCeasy ![c]](http://gceasy.io) - Tool to analyze and visualize GC logs. It provides a free cloud-based upload interface.
- [honest-profiler](https://github.com/jvm-profiling-tools/honest-profiler) - A low-overhead, bias-free sampling profiler. :star:1050
- [jHiccup](https://github.com/giltene/jHiccup) - Logs and records platform JVM stalls. :star:529
- [JITWatch](https://github.com/AdoptOpenJDK/jitwatch) - Analyze the JIT compiler optimisations made by the HotSpot JVM. :star:1918
- [JMH](http://openjdk.java.net/projects/code-tools/jmh) - a Java harness for building, running, and analysing nano/micro/milli/macro benchmarks written in Java and other languages targeting the JVM. (GPL-2.0 only WITH Classpath-exception-2.0)
- [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils) - Utilities for latency measurement and reporting. :star:389

### Platform

_Frameworks that are suites of multiple libraries encompassing several categories._

#### Apache Commons

- [BCEL](http://commons.apache.org/proper/commons-bcel) - Byte Code Engineering Library - analyze, create, and manipulate Java class files.
- [BeanUtils](http://commons.apache.org/proper/commons-beanutils) - Easy-to-use wrappers around the Java reflection and introspection APIs.
- [BeanUtils2](http://commons.apache.org/sandbox/commons-beanutils2) - Redesign of Commons BeanUtils.
- [BSF](http://commons.apache.org/proper/commons-bsf) - Bean Scripting Framework - interface to scripting languages, including JSR-223.
- [Chain](http://commons.apache.org/proper/commons-chain) - Chain of Responsibility pattern implementation.
- [ClassScan](http://commons.apache.org/sandbox/commons-classscan) - Find Class interfaces, methods, fields, and annotations without loading.
- [CLI](http://commons.apache.org/proper/commons-cli) - Command-line arguments parser.
- [CLI2](http://commons.apache.org/sandbox/commons-cli2) Redesign of Commons CLI.
- [Codec](http://commons.apache.org/proper/commons-codec) - General encoding/decoding algorithms (for example phonetic, base64, URL).
- [Collections](http://commons.apache.org/proper/commons-collections) - Extends or augments the Java Collections Framework.
- [Compress](http://commons.apache.org/proper/commons-compress) - Defines an API for working with tar, zip and bzip2 files.
- [Configuration](http://commons.apache.org/proper/commons-configuration) - Reading of configuration/preferences files in various formats.
- [Convert](http://commons.apache.org/sandbox/commons-convert) - Commons-Convert aims to provide a single library dedicated to the task of converting an object of one type to another.
- [CSV](http://commons.apache.org/proper/commons-csv) - Component for reading and writing comma separated value files.
- [Daemon](http://commons.apache.org/proper/commons-daemon) - Alternative invocation mechanism for unix-daemon-like java code.
- [DBCP](http://commons.apache.org/proper/commons-dbcp) - Database connection pooling services.
- [DbUtils](http://commons.apache.org/proper/commons-dbutils) - JDBC helper library.
- [Digester](http://commons.apache.org/proper/commons-digester) - XML-to-Java-object mapping utility.
- [Email](http://commons.apache.org/proper/commons-email) - Library for sending e-mail from Java.
- [Exec](http://commons.apache.org/proper/commons-exec) - API for dealing with external process execution and environment management in Java.
- [FileUpload](http://commons.apache.org/proper/commons-fileupload) - File upload capability for your servlets and web applications.
- [Finder](http://commons.apache.org/sandbox/commons-finder) - Java library inspired by the UNIX find command.
- [Flatfile](http://commons.apache.org/sandbox/commons-flatfile) - Java library for working with flat data structures.
- [Functor](http://commons.apache.org/proper/commons-functor) - A functor is a function that can be manipulated as an object, or an object representing a single, generic function.
- [Graph](http://commons.apache.org/sandbox/commons-graph) - A general purpose Graph APIs and algorithms.
- [I18n](http://commons.apache.org/sandbox/commons-i18n) - Adds the feature of localized message bundles that consist of one or many localized texts that belong together.
- [Id](http://commons.apache.org/sandbox/commons-id) - Id is a component used to generate identifiers.
- [Imaging](http://commons.apache.org/proper/commons-imaging) - A pure-Java image library.
- [IO](http://commons.apache.org/proper/commons-io) - Collection of I/O utilities.
- [Javaflow](http://commons.apache.org/sandbox/commons-javaflow) - Continuation implementation to capture the state of the application.
- [JCI](http://commons.apache.org/proper/commons-jci) - Java Compiler Interface.
- [JCS](http://commons.apache.org/proper/commons-jcs) - Java Caching System.
- [Jelly](http://commons.apache.org/proper/commons-jelly) - XML based scripting and processing engine.
- [Jexl](http://commons.apache.org/proper/commons-jexl) - Expression language which extends the Expression Language of the JSTL.
- [JNet](http://commons.apache.org/sandbox/commons-jnet) - JNet allows to use dynamically register url stream handlers through the java.net API.
- [JXPath](http://commons.apache.org/proper/commons-jxpath) - Utilities for manipulating Java Beans using the XPath syntax.
- [Lang](http://commons.apache.org/proper/commons-lang) - Provides extra functionality for classes in java.lang.
- [Logging](https://en.wikipedia.org/wiki/Apache_Commons_Logging) Wrapper around a variety of logging API implementations.
- [Math](http://commons.apache.org/proper/commons-math) - Lightweight, self-contained mathematics and statistics components.
- [Monitoring](http://commons.apache.org/sandbox/commons-monitoring) - Monitoring aims to provide a simple but extensible monitoring solution for Java applications.
- [Nabla](http://commons.apache.org/sandbox/commons-nabla) - Nabla provides automatic differentiation classes that can generate derivative of any function implemented in the Java language.
- [Net](http://commons.apache.org/proper/commons-net) - Collection of network utilities and protocol implementations.
- [OGNL](http://commons.apache.org/proper/commons-ognl) - An Object-Graph Navigation Language.
- [OpenPGP](http://commons.apache.org/sandbox/commons-openpgp) - Interface to signing and verifying data using OpenPGP.
- [Performance](http://commons.apache.org/sandbox/commons-performance) - A small framework for microbenchmark clients, with implementations for Commons DBCP and Pool.
- [Pipeline](http://commons.apache.org/sandbox/commons-pipeline) - Provides a set of pipeline utilities designed around work queues that run in parallel to sequentially process data objects.
- [Pool](http://commons.apache.org/proper/commons-pool) - Generic object pooling component.
- [Proxy](http://commons.apache.org/proper/commons-proxy) - Library for creating dynamic proxies.
- [RDF](https://commons.apache.org/proper/commons-rdf) - Common implementation of RDF 1.1 that could be implemented by systems on the JVM.
- [RNG](https://commons.apache.org/proper/commons-rng) - Commons Rng provides implementations of pseudo-random numbers generators.
- [SCXML](http://commons.apache.org/proper/commons-scxml) - An implementation of the State Chart XML specification aimed at creating and maintaining a Java SCXML engine.
- [Validator](http://commons.apache.org/proper/commons-validator) - Framework to define validators and validation rules in an xml file.
- [VFS](http://commons.apache.org/proper/commons-vfs) - Virtual File System component for treating files, FTP, SMB, ZIP and such like as a single logical file system.
- [Weaver](http://commons.apache.org/proper/commons-weaver) - Provides an easy way to enhance (weave) compiled bytecode.

#### Other

- [CUBA Platform](https://cuba-platform.com) - High-level framework for developing enterprise applications with a rich web interface, based on Spring, EclipseLink and Vaadin.
- [Light-Java](https://github.com/networknt/light-java) - A fast, lightweight and productive microservices framework with built-in [security](https://github.com/networknt/light-oauth2). :star:2672
- [Orienteer](https://github.com/OrienteerBAP/Orienteer) - Open-source business application platform for rapid configuration/development of CRM, ERP, LMS and other applications. :star:108
- [Spring](https://spring.io/projects) - Provides many packages for dependency injection, aspect-oriented programming, security, etc.

### Processes

_Libraries that help the management of operating system processes._

- [ch.vorburger.exec](https://github.com/vorburger/ch.vorburger.exec) - Convenient API around Apache Commons Exec. :star:11
- [zt-exec](https://github.com/zeroturnaround/zt-exec) - Provides a unified API to Apache Commons Exec and ProcessBuilder. :star:604
- [zt-process-killer](https://github.com/zeroturnaround/zt-process-killer) - Stops processes started from Java or the system processes via PID. :star:87

### Reactive libraries

_Libraries for developing reactive applications._

- [Akka](https://akka.io) - Toolkit and runtime for building concurrent, distributed, fault-tolerant and event-driven applications.
- [Reactive Streams](https://github.com/reactive-streams/reactive-streams-jvm) - Provides a standard for asynchronous stream processing with non-blocking backpressure. :star:3456
- [Reactor](https://projectreactor.io) - Library for building reactive fast-data applications.
- [RxJava](https://github.com/ReactiveX/RxJava) - Allows for composing asynchronous and event-based programs using observable sequences. :star:41666
- [vert.x](https://vertx.io) - Polyglot event-driven application framework.

### REST Frameworks

_Frameworks specifically for creating RESTful services._

- [Dropwizard](https://dropwizard.github.io/dropwizard) - Opinionated framework for setting up modern web applications with Jetty, Jackson, Jersey and Metrics.
- [Elide](http://elide.io) - Opinionated framework for JSON- or GraphQL-APIs based on a JPA data model.
- [javalin](https://javalin.io) - Javalin is just a few thousand lines of code on top of Jetty, which means its performance is almost equivalent to pure Jetty.
- [Jersey](https://jersey.github.io) - JAX-RS reference implementation.
- [Microserver](https://github.com/aol/micro-server) — A convenient, extensible microservices plugin system for Spring & Spring Boot. With more than 30 plugins and growing, it supports both micro-monolith and pure microservices styles.
- [Rapidoid](https://www.rapidoid.org) - A simple, secure and extremely fast framework consisting of an embedded HTTP server, GUI components and dependency injection.
- [rest.li](https://github.com/linkedin/rest.li) - Framework for building robust, scalable RESTful architectures using typesafe bindings and asynchronous, non-blocking IO with an end-to-end developer workflow that promotes clean practices, uniform interface design and consistent data modeling. :star:2005
- [RESTEasy](https://resteasy.jboss.org) - Fully certified and portable implementation of the JAX-RS specification.
- [RestExpress](https://github.com/RestExpress/RestExpress) - Thin wrapper on the JBoss Netty HTTP stack that provides scaling and performance. :star:901
- [Restlet Framework](https://github.com/restlet/restlet-framework-java) - Pioneering framework with powerful routing and filtering capabilities, and a unified client and server API. :star:606
- [Spark](http://sparkjava.com) - Sinatra inspired framework.
- [Crnk](http://www.crnk.io) - Implementation of the JSON API specification to build resource-oriented REST endpoints with sorting, filtering, paging, linking, object graphs, type-safety, bulk updates, integrations and more.
- [springdoc-openapi](https://github.com/springdoc/springdoc-openapi) - Automates the generation of API documentation using Spring Boot projects. :star:294
- [Swagger](https://swagger.io) - Standard, language-agnostic interface to REST APIs.

### Science

_Libraries for scientific computing, analysis and visualization._

- [DataMelt](http://jwork.org/dmelt) - Environment for scientific computation, data analysis and data visualization. (GPL-3.0-or-later)
- [Erdos](https://github.com/Erdos-Graph-Framework/Erdos) - Modular, light and easy graph framework for theoretic algorithms. :star:97
- [GraphStream](http://graphstream-project.org) - Library for modeling and analyzing dynamic graphs.
- [JFreeChart](http://www.jfree.org/jfreechart) - 2D chart library for Swing, JavaFX and server-side applications. (LGPL-2.1-only)
- [JGraphT](https://github.com/jgrapht/jgrapht) - Graph library that provides mathematical graph-theory objects and algorithms. :star:1601
- [JGraphX](https://github.com/jgraph/jgraphx) - Library for visualizing (mainly Swing) and interacting with node-edge graphs. :star:574
- [Mines Java Toolkit](https://github.com/MinesJTK/jtk) - Library for geophysical scientific computation, visualization and digital signal analysis. :star:34
- [Morpheus](http://www.zavtech.com/morpheus/docs) - Provides a versatile two-dimensional memory efficient tabular data structure called a DataFrame to enable efficient in-memory analytics for scientific computing on the JVM.
- [Orson-Charts](https://github.com/jfree/orson-charts) - Generates a wide variety of 3D charts that can be displayed with Swing and JavaFX or exported to PDF, SVG, PNG and JPEG. (GPL-3.0-only) :star:65
- [Tablesaw](https://github.com/lwhite1/tablesaw) - Includes a data-frame, an embedded column store, and hundreds of methods to transform, summarize, or filter data. :star:2014
- [XChart](https://github.com/knowm/XChart) - A light-weight library for plotting data. Many customizable chart types are available. :star:888

### Search

_Engines that index documents for search and analysis._

- [Apache Lucene](https://lucene.apache.org) - High-performance, full-featured, cross-platform, text search engine library.
- [Apache Solr](https://lucene.apache.org/solr) - Enterprise search engine optimized for high-volume traffic.
- [Elasticsearch](https://www.elastic.co) - Distributed, multitenant-capable, full-text search engine with a RESTful web interface and schema-free JSON documents.
- [Indexer4j](https://github.com/haeungun/indexer4j) - Simple and light full text indexing and searching library. :star:33

### Security

_Libraries that handle security, authentication, authorization or session management._

- [Apache Shiro](https://shiro.apache.org) - Performs authentication, authorization, cryptography and session management.
- [Bouncy Castle](https://www.bouncycastle.org/java.html) - All-purpose cryptographic library and JCA provider offering a wide range of functions, from basic helpers to PGP/SMIME operations.
- [Cryptomator](https://cryptomator.org) - Multiplatform, transparent, client-side encryption of files in the cloud. (GPL-3.0-only)
- [Hdiv](https://github.com/hdiv/hdiv) - Runtime application that repels application security risks included in the OWASP Top 10, including SQL injection, cross-site scripting, cross-site request forgery, data tampering, and brute force attacks. :star:181
- [jjwt](https://github.com/jwtk/jjwt) - JSON web token for Java and Android. :star:5877
- [Jwks RSA](https://github.com/auth0/jwks-rsa-java) - JSON Web Key Set parser. :star:78
- [Kalium](https://github.com/abstractj/kalium) - Binding for the Networking and Cryptography (NaCl) library. :star:196
- [Keycloak](https://www.keycloak.org) - Integrated SSO and IDM for browser apps and RESTful web services.
- [Keywhiz](https://github.com/square/keywhiz) - System for distributing and managing secrets. :star:2182
- [Nbvcxz](https://github.com/GoSimpleLLC/nbvcxz) - Advanced password strength estimation. :star:173
- [OACC](http://oaccframework.org) - Provides permission-based authorization services.
- [pac4j](https://github.com/pac4j/pac4j) - Security engine. :star:1728
- [SecurityBuilder](https://github.com/tersesystems/securitybuilder) - Fluent Builder API for JCA and JSSE classes and especially X.509 certificates. :star:32
- [Themis](https://github.com/cossacklabs/themis) - Multi-platform high-level cryptographic library provides easy-to-use encryption for protecting sensitive data: secure messaging with forward secrecy, secure data storage (AES256GCM); suits for building end-to-end encrypted applications. :star:929
- [Tink](https://github.com/google/tink) - Provides a simple and misuse-proof API for common cryptographic tasks. :star:8843
- [Vault](https://www.vaultproject.io) - Secures, stores, and tightly controls access to tokens, passwords, certificates, API keys, and other secrets. It handles leasing, key revocation, key rolling, and auditing. Through a unified API, users can access an encrypted Key/Value store and network encryption-as-a-service, or generate AWS IAM/STS credentials, SQL/NoSQL databases, X.509 certificates, SSH credentials, and more.

### Serialization

_Libraries that handle serialization with high efficiency._

- [FlatBuffers](https://github.com/google/flatbuffers) - Memory-efficient serialization library that can access serialized data without unpacking and parsing it. :star:13695
- [FST](https://github.com/RuedigerMoeller/fast-serialization) - JDK-compatible, high-performance object graph serialization. :star:1223
- [Kryo](https://github.com/EsotericSoftware/kryo) - Fast and efficient object graph serialization framework. :star:4464
- [MessagePack](https://github.com/msgpack/msgpack-java) - Efficient binary serialization format. :star:1062
- [PHP Serializer](https://github.com/marcospassos/java-php-serializer) - Serializing objects in the PHP serialization format. :star:11

### Server

_Servers specifically used to deploy applications._

- [Apache Tomcat](https://tomcat.apache.org) - Robust, all-round server for Servlet and JSP.
- [Apache TomEE](https://tomee.apache.org) - Tomcat plus Java EE.
- [Jetty](https://www.eclipse.org/jetty) - Provides a Web server and javax.servlet container, plus support for HTTP/2, WebSocket, OSGi, JMX, JNDI, JAAS and many other integrations.
- [nanohttpd](https://github.com/NanoHttpd/nanohttpd) - Tiny, easily embeddable HTTP server. :star:5189
- [WildFly](http://www.wildfly.org) - Formerly known as JBoss and developed by Red Hat with extensive Java EE support. (LGPL-2.1-only)

### Template Engine

_Tools that substitute expressions in a template._

- [Handlebars.java](https://jknack.github.io/handlebars.java) - Logicless and semantic Mustache templates.
- [Jade4J](https://github.com/neuland/jade4j) - Implementation of Pug (formerly known as Jade). :star:661
- [Jtwig](http://jtwig.org) - Modular, configurable and fully tested template engine.
- [Pebble](https://pebbletemplates.io) - Inspired by Twig and separates itself with its inheritance feature and its easy-to-read syntax. It ships with built-in autoescaping for security and it includes integrated support for internationalization.
- [Rocker](https://github.com/fizzed/rocker) - Optimized, memory efficient and speedy template engine producing statically typed, plain objects. :star:535
- [Thymeleaf](http://www.thymeleaf.org) - Aims to be a substitute for JSP and works for XML files.

### Testing

_Tools that test from model to the view._

#### Asynchronous

_Tools that simplify testing asynchronous services._

- [Awaitility](https://github.com/jayway/awaitility) - DSL for synchronizing asynchronous operations. :star:1921
- [ConcurrentUnit](https://github.com/jhalterman/concurrentunit) - Toolkit for testing multi-threaded and asynchronous applications. :star:345
- [GreenMail](http://www.icegreen.com/greenmail) - In-memory email server for integration testing. Supports SMTP, POP3 and IMAP including SSL. (GPL-2.0-only)
- [Hoverfly Java](https://github.com/SpectoLabs/hoverfly-java) - Native bindings for Hoverfly, a proxy which allows you to simulate HTTP services. :star:110
- [REST Assured](https://github.com/jayway/rest-assured) - DSL for easy testing of REST/HTTP services. :star:4468

#### BDD

_Testing for the software development process that emerged from TDD and was heavily influenced by DDD and OOAD._

- [Cucumber](https://github.com/cucumber/cucumber-jvm) - Provides a way to describe features in a plain language which customers can understand. :star:2066
- [Cukes-REST](https://github.com/ctco/cukes-rest) - A collection of Gherkin steps for REST-service testing using Cucumber. :star:90
- [J8Spec](https://github.com/j8spec/j8spec) - Follows a Jasmine-like syntax. :star:45
- [JBehave](http://jbehave.org) - Extensively configurable framework that describes stories.
- [JGiven](http://jgiven.org) - Provides a fluent API which allows for simpler composition.
- [Lamdba Behave](https://github.com/RichardWarburton/lambda-behave) - Aims to provide a fluent API to write tests in long and descriptive sentences that read like plain English. :star:236
- [Serenity BDD](https://www.thucydides.info) - Automated Acceptance testing and reporting library that works with Cucumber, JBehave and JUnit to make it easier to write high quality executable specifications.

#### Fixtures

_Everything related to the creation and handling of random data._

- [Beanmother](https://github.com/keepcosmos/beanmother) - Sets up beans from YAML fixtures. :star:91
- [Fixture Factory](https://github.com/six2six/fixture-factory) - Generates fake objects from a template. :star:341
- [jFairy](https://github.com/Devskiller/jfairy) - Fake data generator. :star:591
- [Randomized Testing](https://github.com/randomizedtesting/randomizedtesting) - JUnit test runner and plugins for running JUnit tests with pseudo-randomness. :star:144
- [Java Faker](https://github.com/DiUS/java-faker) - A port of Ruby's fake data generator. :star:1627

#### Frameworks

_Provide environments to run tests for a specific use case._

- [ArchUnit](https://github.com/TNG/ArchUnit) - Test library for specifying and asserting architecture rules. :star:1062
- [Apache JMeter](http://jmeter.apache.org) - Functional testing and performance measurements.
- [Arquillian](http://arquillian.org) - Integration and functional testing platform for Java EE containers.
- [Citrus](https://citrusframework.org) - Integration testing framework that focuses on both client- and server-side messaging.
- [Gatling](https://gatling.io) - Load testing tool designed for ease of use, maintainability and high performance.
- [JUnit](http://junit.org) - Common testing framework.
- [jqwik](https://jqwik.net) - Engine for property-based testing built on JUnit 5.
- [Pact JVM](https://github.com/DiUS/pact-jvm) - Consumer-driven contract testing. :star:711
- [PIT](http://pitest.org) - Fast mutation-testing framework for evaluating fault-detection abilities of existing JUnit or TestNG test suites.

#### Matchers

_Libraries that provide custom matchers._

- [AssertJ](https://joel-costigliola.github.io/assertj) - Fluent assertions that improve readability.
- [Hamcrest](http://hamcrest.org/JavaHamcrest) - Matchers that can be combined to create flexible expressions of intent.
- [JSONAssert](http://jsonassert.skyscreamer.org) - Simplifies testing JSON strings.
- [Truth](https://truth.dev) - Google's fluent assertion and proposition framework.
- [XMLUnit](https://github.com/xmlunit/xmlunit) - Simplifies testing for XML output. :star:203

#### Miscellaneous

_Other stuff related to testing._

- [junit-dataprovider](https://github.com/TNG/junit-dataprovider) - A TestNG-like data provider/runner for JUnit. :star:206
- [Mutability Detector](https://github.com/MutabilityDetector/MutabilityDetector) - Reports whether instances of a given class are immutable. :star:187
- [raml-tester](https://github.com/nidi3/raml-tester) - Tests if a request/response matches a given RAML definition. :star:70
- [TestContainers](https://github.com/testcontainers/testcontainers-java) - Provides throwaway instances of common databases, Selenium web browsers, or anything else that can run in a Docker container. :star:3311
- [pojo-tester](http://www.pojo.pl) - Automatically performs tests on basic POJO methods. (LGPL-3.0-only)

#### Mocking

_Tools which mock collaborators to help testing single, isolated units._

- [JMockit](http://jmockit.github.io) - Integration testing, API mocking and faking, and code coverage.
- [Mockito](https://github.com/mockito/mockito) - Mocking framework that lets you write tests with a clean and simple API. :star:9980
- [MockServer](https://www.mock-server.com) - Allows mocking of systems integrated with HTTPS.
- [Moco](https://github.com/dreamhead/moco) - Concise web services for stubs and mocks. :star:3005
- [PowerMock](https://github.com/jayway/powermock) - Mocks static methods, constructors, final classes and methods, private methods, and removal of static initializers. :star:2907
- [WireMock](http://wiremock.org) - Stubs and mocks web services.

### Utility

_Libraries which provide general utility functions._

- [bucket4j](https://github.com/vladimir-bukhtoyarov/bucket4j) - Rate limiting library based on token-bucket algorithm. :star:683
- [cactoos](http://www.cactoos.org) - Collection of object-oriented primitives.
- [CRaSH](http://www.crashub.org) - Provides a shell into a JVM that's running CRaSH. Used by Spring Boot and others. (LGPL-2.1-or-later)
- [Dex](https://github.com/PatMartin/Dex) - Java/JavaFX tool capable of powerful ETL and data visualization. :star:1177
- [Embulk](http://www.embulk.org) - Bulk data loader that helps data transfer between various databases, storages, file formats, and cloud services.
- [fswatch](https://github.com/vorburger/ch.vorburger.fswatch) - Micro library to watch for directory file system changes, simplifying java.nio.file.WatchService :star:13
- [Gephi](https://github.com/gephi/gephi) - Cross-platform for visualizing and manipulating large graph networks. (GPL-3.0-only) :star:3638
- [Guava](https://github.com/google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and more. :star:35645
- [JADE](http://jade.tilab.com) - Framework and environment for building and debugging multi-agent systems. (LGPL-2.0-only)
- [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions) - Library that helps with constructing difficult regular expressions. :star:1812
- [JGit](https://eclipse.org/jgit) - A lightweight, pure Java library implementing the Git version control system.
- [minio-java](https://github.com/minio/minio-java) - Provides simple APIs to access any Amazon S3-compatible object storage server. :star:237
- [Protégé](https://protege.stanford.edu) - Provides an ontology editor and a framework to build knowledge-based systems.
- [Underscore-java](https://github.com/javadev/underscore-java) - Port of Underscore.js functions. :star:269

### Version Managers

_Utilities that help create the development shell environment and switch between different Java versions._

- [jabba](https://github.com/shyiko/jabba) - Java Version Manager inspired by nvm. Supports Mac OS X, Linux and Windows. :star:1172
- [jenv](https://github.com/gcuisinier/jenv) - Java Version Manager inspired by rbenv. Can configure globally or per project. Tested on Debian and Mac OS X. :star:2872
- [SDKMan](https://github.com/sdkman/sdkman-cli) - Java Version Manager inspired by RVM and rbenv. Supports UNIX-based platforms and Windows. :star:3103

### Web Crawling

_Libraries that analyze the content of websites._

- [Apache Nutch](https://nutch.apache.org) - Highly extensible, highly scalable web crawler for production environments.
- [Crawler4j](https://github.com/yasserg/crawler4j) - Simple and lightweight web crawler. :star:3797
- [jsoup](https://jsoup.org) - Scrapes, parses, manipulates and cleans HTML.
- [StormCrawler](http://stormcrawler.net) - SDK for building low-latency and scalable web crawlers.
- [webmagic](https://github.com/code4craft/webmagic) - Scalable crawler with downloading, url management, content extraction and persistent. :star:8728

### Web Frameworks

_Frameworks that handle the communication between the layers of a web application._

- [Apache Tapestry](https://tapestry.apache.org) - Component-oriented framework for creating dynamic, robust, highly scalable web applications.
- [Apache Wicket](https://wicket.apache.org) - Component-based web application framework similar to Tapestry, with a stateful GUI.
- [Blade](https://github.com/biezhi/blade) - Lightweight, modular framework that aims to be elegant and simple. :star:5154
- [Bootique](https://bootique.io) - Minimally opinionated framework for runnable apps.
- [Firefly](http://www.fireflysource.com) - Asynchronous framework for rapid development of high-performance web application.
- [Grails](https://grails.org) - Groovy framework that provides a highly productive environment by favoring convention over configuration, no XML and support for mixins.
- [Jooby](http://jooby.org) - Scalable, fast and modular micro-framework that offers multiple programming models.
- [Ninja](http://www.ninjaframework.org) - Full-stack web framework.
- [Pippo](http://www.pippo.ro) - Small, highly modularized, Sinatra-like framework.
- [Play](https://www.playframework.com) - Built on Akka, it provides predictable and minimal resource consumption (CPU, memory, threads) for highly-scalable applications in Java and Scala.
- [PrimeFaces](https://primefaces.org) - JSF framework with both free and commercial/support versions and frontend components.
- [Ratpack](https://ratpack.io) - Set of libraries that facilitate fast, efficient, evolvable and well-tested HTTP applications.
- [Takes](https://github.com/yegor256/takes) - Opinionated web framework which is built around the concepts of True Object-Oriented Programming and immutability. :star:599
- [Vaadin Flow](https://vaadin.com/flow) - Event-driven framework that uses standard web components. Server-side architecture with Ajax on the client side.

## Resources

### Awesome Lists

_Awesome lists related to the Java & JVM ecosystem._

- [Awesome Annotation Processing](https://github.com/gunnarmorling/awesome-annotation-processing) :star:127
- [Awesome Gradle Plugins](https://github.com/ksoichiro/awesome-gradle) :star:306
- [AwesomeJavaFX](https://github.com/mhrimaz/AwesomeJavaFX) :star:1805
- [Awesome JVM](https://github.com/deephacks/awesome-jvm) :star:1383
- [Awesome Microservices](https://github.com/mfornos/awesome-microservices) :star:8496
- [Awesome REST](https://github.com/marmelab/awesome-rest) :star:2345
- [Awesome Selenium](https://github.com/christian-bromann/awesome-selenium) :star:550
- [ciandcd](https://github.com/ciandcd/awesome-ciandcd) :star:1016
- [Useful Java Links](https://github.com/Vedenin/useful-java-links) :star:4548
- [Java Concurrency Checklist](https://github.com/code-review-checklists/java-concurrency) :star:560
- [Java Developer Roadmap](https://github.com/s4kibs4mi/java-developer-roadmap) :star:531

### Communities

_Active discussions._

- [r/java](https://www.reddit.com/r/java) - Subreddit for the Java community.
- [stackoverflow](https://stackoverflow.com/questions/tagged/java) - Question/answer platform.
- [VirtualJUG](https://virtualjug.com) - Virtual Java User Group.

### Frontends

_Websites that provide a frontend for this list. Please note, there won't be an official website. We don't associate with a particular website and everybody is allowed to create one._

- [java.libhunt.com](https://java.libhunt.com)

### Influential Books

_Books that made a big impact and are still worth reading._

- [Core Java Volume I--Fundamentals](https://www.amazon.com/Core-Java-I-Fundamentals-10th/dp/0134177304)
- [Core Java, Volume II--Advanced Features](https://www.amazon.com/Core-Java-II-Advanced-Features-10th/dp/0134177290)
- [Effective Java (3rd Edition)](https://www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997)
- [Java Concurrency in Practice](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
- [Thinking in Java](https://www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)

### Podcasts and Screencasts

_Something to look at or listen to while programming._

- [Java Off Heap](http://www.javaoffheap.com)
- [Marco Behler's Screencasts](https://www.marcobehler.com/series) - Screencasts about modern Java development.
- [The Java Council](https://virtualjug.com/#podcast)
- [The Java Posse](http://www.javaposse.com) - Discontinued as of 02/2015.

### Twitter

_Active accounts to follow. Descriptions from Twitter._

- [Adam Bien](https://twitter.com/AdamBien) - Freelance author, JavaOne Rockstar speaker, consultant, Java Champion.
- [Aleksey Shipilëv](https://twitter.com/shipilev) - Performance geek, benchmarking czar, concurrency bug hunter.
- [Antonio Goncalves](https://twitter.com/agoncal) - Java Champion, JUG Leader, Devoxx France, Java EE 6/7, JCP, Author.
- [Arun Gupta](https://twitter.com/arungupta) - Java Champion, JavaOne Rockstar, JUG Leader, Devoxx4Kids-er, VP of Developer Advocacy at Couchbase.
- [Brian Goetz](https://twitter.com/BrianGoetz) - Java Language Architect at Oracle.
- [Bruno Borges](https://twitter.com/brunoborges) - Product Manager/Java Jock at Oracle.
- [Chris Richardson](https://twitter.com/crichardson) - Software architect, consultant, and serial entrepreneur, Java Champion, JavaOne Rock Star, \*POJOs in Action- author.
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
- [Sander Mak](https://twitter.com/Sander_Mak) - Java Champion, author.
- [Simon Maple](https://twitter.com/sjmaple) - Java Champion, VirtualJUG founder, LJC leader, RebelLabs author.
- [Spencer Gibb](https://twitter.com/spencerbgibb) - Software Engineer, Dad, Geek, Co-founder and Lead of Spring Cloud Core @pivotal.
- [Stephen Colebourne](https://twitter.com/jodastephen) - Java Champion, speaker.
- [Trisha Gee](https://twitter.com/trisha_gee) - Java Champion and speaker.
- [Venkat Subramaniam](https://twitter.com/venkat_s) - Author, University of Houston professor, MicroSoft MVP award recipient, JavaOne Rock Star, Java Champion.
- [Vlad Mihalcea](https://twitter.com/vlad_mihalcea) - Java Champion working on Hypersistence Optimizer, database aficionado, author of High-Performance Java Persistence book.

### Websites

_Sites to read._

- [Baeldung](https://www.baeldung.com)
- [Dzone](https://dzone.com)
- [Google Java Style](https://google.github.io/styleguide/javaguide.html)
- [InfoQ](https://www.infoq.com)
- [Java Algorithms and Clients](https://algs4.cs.princeton.edu/code)
- [Java, SQL, and jOOQ](https://blog.jooq.org)
- [Java.net](https://community.oracle.com/community/java)
- [Javalobby](https://dzone.com/java-jdk-development-tutorials-tools-news)
- [JavaWorld](https://www.javaworld.com)
- [JAXenter](https://jaxenter.com)
- [RebelLabs](https://zeroturnaround.com/rebellabs)
- [OverOps Blog](https://blog.overops.com)
- [TheServerSide.com](http://www.theserverside.com)
- [Vanilla Java](https://vanilla-java.github.io)
- [Voxxed](https://www.voxxed.com)

## Contributing

Contributions are very welcome!

Please have a look at the [CONTRIBUTING](https://github.com/akullpp/awesome-java/blob/master/CONTRIBUTING.md) guidelines.

[c]: https://cdn.rawgit.com/akullpp/23246ca832bda82bb505230bf3538e2a/raw/d9bcdb769bf025292f9c6bc1290f01f1fcd1f864/commercial.svg


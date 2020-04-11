# Information comes from [mgramin/awesome-db-tools](https://github.com/mgramin/awesome-db-tools)
# Awesome Database Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Community driven list of database tools

Here we will collect information about awesome useful and awesome experimental tools that simplify working with databases for DBA, DevOps, Developers and mere mortals.

Feel free to add information about your own db-tools or your favorite third-party db-tools.

## Contents
- [IDE](#ide)
- [GUI Managers/Clients](#gui-managersclients)
- [CLI tools](#cli-tools)
- [DB-schema navigation and visualization](#db-schema-navigation-and-visualization)
- [Modelers](#modelers)
- [Migration tools](#migration-tools)
- [Code generation tools](#code-generation-tools)
- [Wrappers](#wrappers)
- [Backup tools](#backup-tools)
- [Replication/Data operation](#replicationdata-operation)
- [Scripts](#scripts)
- [Monitoring/Statistics/Perfomance](#monitoringstatisticsperfomance)
  - [Zabbix](#zabbix)
- [Testing](#testing)
  - [Data generator](#data-generator)
- [Administration](#administration)
- [HA/Failover/Sharding](#hafailoversharding)
- [Kubernetes](#kubernetes)
- [Configuration Tuning](#configuration-tuning)
- [DevOps](#devops)
- [Schema samples](#schema-samples)
- [Reporting](#reporting)
- [Distributions](#distributions)
- [Security](#security)
- [Code formatters](#code-formatters)


## IDE
- [AnySQL Maestro](https://www.sqlmaestro.com/products/anysql/maestro) - Premier multi-purpose admin tool for database management, control and development.
- [Aqua Data Studio](https://www.aquafold.com/aquadatastudio) - Aqua Data Studio is productivity software for Database Developers, DBAs, and Analysts.
- [Database .net](http://fishcodelib.com/Database.htm) - Multiple database management tool with support for 20+ databases.
- [DataGrip](https://www.jetbrains.com/datagrip) - Cross-Platform IDE for Databases & SQL by JetBrains.
- [DBeaver](https://github.com/dbeaver/dbeaver) - Free universal database manager and SQL client. :star:12849
- [dbForge Studio for MySQL](https://www.devart.com/dbforge/mysql/studio) - Universal IDE for MySQL and MariaDB database development, management, and administration.
- [dbForge Studio for Oracle](https://www.devart.com/dbforge/oracle/studio) - Powerful IDE for Oracle management, administration, and development.
- [dbForge Studio for PostgreSQL](https://www.devart.com/dbforge/postgresql/studio) - GUI tool for managing and developing databases and objects.
- [dbForge Studio for SQL Server](https://www.devart.com/dbforge/sql/studio) - Powerful integrated development environment for SQL Server development, management, administration, data analysis, and reporting.
- [dbKoda](https://github.com/SouthbankSoftware/dbkoda) - Modern (JavaScript/Electron framework), open source IDE for MongoDB. It has features to support development, administration and performance tuning on MongoDB databases. :star:711
- [IBExpert](http://www.ibexpert.net/ibe) - Comprehensive GUI tool for Firebird and InterBase.
- [HeidiSQL](https://github.com/HeidiSQL/HeidiSQL) - A lightweight client for managing MySQL, MSSQL and PostgreSQL, written in Delphi. :star:1785
- [MySQL Workbench](https://www.mysql.com/products/workbench) - MySQL Workbench is a unified visual tool for database architects, developers, and DBAs.
- [Navicat](https://www.navicat.com/en/products#navicat) - A database development tool that allows you to simultaneously connect to MySQL, MariaDB, SQL Server, Oracle, PostgreSQL, and SQLite databases from a single application.
- [Oracle SQL Developer](http://www.oracle.com/technetwork/developer-tools/sql-developer) - Oracle SQL Developer is a free, integrated development environment that simplifies the development and management of Oracle Database in both traditional and Cloud deployments.
- [pgAdmin](https://www.pgadmin.org) - The most popular and feature rich Open Source administration and development platform for PostgreSQL, the most advanced Open Source database in the world.
- [pgAdmin3](https://www.bigsql.org/pgadmin3) - Long Term Support for pgAdmin3.
- [PL/SQL Developer](https://www.allroundautomations.com/products/pl-sql-developer) - IDE that is specifically targeted at the development of stored program units for Oracle Databases.
- [PostgreSQL Maestro](https://www.sqlmaestro.com/products/postgresql/maestro) - Complete and powerful database management, admin and development tool for PostgreSQL.
- [Toad](https://www.quest.com/toad/) - Toad is the premier database solution for developers, admins and data analysts. Manage complex database changes with a single database management tool.
- [Toad Edge](https://www.toadworld.com/products/toad-edge) - Simplified database development tool for MySQL and Postgres.
- [TOra](https://github.com/tora-tool/tora) - TOra is an open source SQL IDE for Oracle, MySQL and PostgreSQL dbs. :star:210
- [Valentina Studio](https://www.valentina-db.com/en/valentina-studio-overview) - Create, administer, query and explore Valentina DB, MySQL, MariaDB, PostgreSQL and SQLite databases for FREE.


## GUI Managers/Clients
- [Adminer](https://github.com/vrana/adminer) - Database management in a single PHP file. :star:4096
- [DbVisualizer](https://www.dbvis.com) - Universal database tool for developers, DBAs and analysts.
- [HouseOps](https://github.com/HouseOps/HouseOps) - Enterprise ClickHouse Ops UI for you run querys, monitoring ClickHouse health and make a lot of others thinks. :star:160
- [JackDB](https://www.jackdb.com) - Direct SQL access to all your data, no matter where it lives.
- [OmniDB](https://github.com/OmniDB/OmniDB) - Web tool for database management. :star:2022
- [Pgweb](https://github.com/sosedoff/pgweb) - Web-based database browser for PostgreSQL, written in Go and works on macOS, Linux and Windows machines. :star:6345
- [phpLiteAdmin](https://www.phpliteadmin.org) - Web-based SQLite database admin tool written in PHP with support for SQLite3 and SQLite2.
- [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) - A web interface for MySQL and MariaDB. :star:4860
- [psequel](http://www.psequel.com) - PSequel provides a clean and simple interface for you to perform common PostgreSQL tasks quickly.
- [PopSQL](https://popsql.com) - Modern, collaborative SQL editor for your team.
- [Postico](https://eggerapps.at/postico) - A Modern PostgreSQL Client for the Mac.
- [Robo 3T](https://github.com/Studio3T/robomongo) - Robo 3T (formerly Robomongo) is a shell-centric cross-platform MongoDB management tool. :star:7933
- [Sequel Pro](https://github.com/sequelpro/sequelpro) - Sequel Pro is a fast, easy-to-use Mac database management application for working with MySQL & MariaDB databases. :star:7580
- [SQL Operations Studio](https://github.com/microsoft/sqlopsstudio) - A data management tool that enables working with SQL Server, Azure SQL DB and SQL DW from Windows, macOS and Linux. :star:5684
- [SQLite Expert](http://www.sqliteexpert.com/index.html) - Graphical interface supports all SQLite features.
- [sqlpad](https://github.com/rickbergfalk/sqlpad) - Web-based SQL editor run in your own private cloud. :star:2849
- [SQLPro](https://www.macpostgresclient.com) - A simple, powerful Postgres manager for macOS.
- [SQuirreL](https://sourceforge.net/projects/squirrel-sql) - Graphical SQL client written in Java that will allow you to view the structure of a JDBC compliant database, browse the data in tables, issue SQL commands etc.
- [SQLTools](https://github.com/mtxr/vscode-sqltools) - Database management for VSCode. :star:462
- [SQLyog](https://www.webyog.com/product/sqlyog) - The most complete and easy to use MySQL GUI.
- [Tabix](https://github.com/tabixio/tabix) - SQL Editor & Open source simple business intelligence for Clickhouse. :star:860
- [TablePlus](https://github.com/TablePlus/TablePlus) - Modern, native, and friendly GUI tool for relational databases: MySQL, PostgreSQL, SQLite & more. :star:1838
- [TeamPostgreSQL](http://www.teampostgresql.com) - PostgreSQL Web Administration GUI - use your PostgreSQL databases from anywhere, with rich, lightning-fast AJAX web interface.


## CLI tools
- [ipython-sql](https://github.com/catherinedevlin/ipython-sql) - Connect to a database for issue SQL commands within IPython or IPython Notebook. :star:1196
- [iredis](https://github.com/laixintao/iredis) - A Cli for Redis with AutoCompletion and Syntax Highlighting. :star:943
- [pgcenter](https://github.com/lesovsky/pgcenter) - Top-like admin tool for PostgreSQL. :star:917
- [pg_activity](https://github.com/julmon/pg_activity) - Top like application for PostgreSQL server activity monitoring. :star:1
- [pg_top](https://github.com/markwkm/pg_top) - 'top' for PostgreSQL. :star:80
- [pspg](https://github.com/okbob/pspg) - Postgres Pager. :star:1239
- [SQLcl](http://www.oracle.com/technetwork/developer-tools/sqlcl/overview/index.html) - Oracle SQL Developer Command Line (SQLcl) is a free command line interface for Oracle Database.
- [usql](https://github.com/xo/usql) - A universal command-line interface for PostgreSQL, MySQL, Oracle Database, SQLite3, Microsoft SQL Server, [and many other databases](https://github.com/xo/usql#database-support) including NoSQL and non-relational databases! :star:5838

### dbcli
- [athenacli](https://github.com/dbcli/athenacli) - AthenaCLI is a CLI tool for AWS Athena service that can do auto-completion and syntax highlighting. :star:109
- [litecli](https://github.com/dbcli/litecli) - CLI for SQLite Databases with auto-completion and syntax highlighting. :star:1105
- [mssql-cli](https://github.com/dbcli/mssql-cli) - A command-line client for SQL Server with auto-completion and syntax highlighting. :star:887
- [mycli](https://github.com/dbcli/mycli) - A Terminal Client for MySQL with AutoCompletion and Syntax Highlighting. :star:8579
- [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting. :star:8609
- [vcli](https://github.com/dbcli/vcli) - Vertica CLI with auto-completion and syntax highlighting. :star:72


## DB-schema navigation and visualization
- [dbdiagram.io](https://dbdiagram.io) - Quick and simple tool for help you draw your database relationship diagrams and flow quickly using simple DSL language.
- [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) - Entity Relation Diagrams generation tool. :star:652
- [SchemaCrawler](https://github.com/schemacrawler/SchemaCrawler) - A free database schema discovery and comprehension tool. :star:869
- [Schema Spy](https://github.com/schemaspy/schemaspy) - Generating your database to HTML documentation, including Entity Relationship diagrams. :star:1248
- [tbls](https://github.com/k1LoW/tbls) - CI-Friendly tool for document a database, written in Go. :star:588


## Modelers
- [Navicat Data Modeler](https://www.navicat.com/en/products/navicat-data-modeler) - A powerful and cost-effective database design tool which helps you build high-quality conceptual, logical and physical data models.
- [Oracle SQL Developer Data Modeler](http://www.oracle.com/technetwork/developer-tools/datamodeler/overview/index.html) - Oracle SQL Developer Data Modeler is a free graphical tool that enhances productivity and simplifies data modeling tasks.
- [pgmodeler](https://github.com/pgmodeler/pgmodeler) - Data modeling tool designed for PostgreSQL. :star:1968


## Migration tools
- [2bass](https://github.com/CourseOrchestra/2bass) - Database configuration-as-code tool that utilizes concept of idempotent DDL scripts. :star:22
- [flyway](https://github.com/flyway/flyway) - Database migration tool. :star:4989
- [gh-ost](https://github.com/github/gh-ost) - Online schema migration for MySQL. :star:7605
- [liquibase](https://github.com/liquibase/liquibase) - Database-independent library for tracking, managing and applying database schema changes. :star:2025
- [migra](https://github.com/djrobstep/migra) - Like diff but for PostgreSQL schemas. :star:1671
- [node-pg-migrate](https://github.com/salsita/node-pg-migrate) - Node.js database migration management built exclusively for postgres. (But can also be used for other DBs conforming to SQL standard - e.g. CockroachDB.) :star:671
- [Pyrseas](https://github.com/perseas/Pyrseas) - Provides utilities to describe a PostgreSQL database schema as YAML. :star:267
- [SchemaHero](https://github.com/schemahero/schemahero) - A Kubernetes operator for declarative database schema management (gitops for database schemas). :star:90
- [Sqitch](https://github.com/sqitchers/sqitch) - Sensible database-native change management for framework-free development and dependable deployment. :star:1963


## Code generation tools
- [ddl-generator](https://github.com/catherinedevlin/ddl-generator) - Infers SQL DDL (Data Definition Language) from table data. :star:192
- [scheme2ddl](https://github.com/qwazer/scheme2ddl) - Command line util for export Oracle schema to set of ddl init scripts with ability to filter undesirable information, separate DDL in different files, pretty format output. :star:54


## Wrappers
- [DreamFactory](https://github.com/dreamfactorysoftware/dreamfactory) - A open source REST API backend for mobile, web, and IoT applications. :star:1058
- [Hasura GraphQL Engine](https://github.com/hasura/graphql-engine) - Blazing fast, instant realtime GraphQL APIs on Postgres with fine grained access control, also trigger webhooks on database events. :star:15979
- [jl-sql](https://github.com/avz/jl-sql) - SQL for JSON and CSV streams. :star:44
- [mysql_fdw](https://github.com/EnterpriseDB/mysql_fdw) - PostgreSQL foreign data wrapper for MySQL. :star:299
- [Oracle REST Data Services](http://www.oracle.com/technetwork/developer-tools/rest-data-services) - A mid-tier Java application, ORDS maps HTTP(S) verbs (GET, POST, PUT, DELETE, etc.) to database transactions and returns any results formatted using JSON.
- [Prisma](https://github.com/prismagraphql/prisma) -  Prisma turns your database into a realtime GraphQL API. :star:17021
- [PostgREST](https://github.com/PostgREST/postgrest) - REST API for any Postgres database. :star:14247
- [prest](https://github.com/prest/prest) - Is a way to serve a RESTful API from any databases written in Go. :star:2236
- [restSQL](https://github.com/restsql/restsql) - SQL generator with Java and HTTP APIs, uses a simple RESTful HTTP API with XML or JSON serialization. :star:113
- [resquel](https://github.com/formio/resquel) - Easily convert your SQL database into a REST API. :star:61
- [sandman2](https://github.com/jeffknupp/sandman2) - Automatically generate a RESTful API service for your legacy database. :star:1483
- [sql-boot](https://github.com/CrocInc/sql-boot) - Advanced REST and UI wrapper for your SQL-queries. :star:44


## Backup tools
- [pgbackrest](https://github.com/pgbackrest/pgbackrest) - Reliable PostgreSQL Backup & Restore. :star:577
- [BaRMan](https://github.com/2ndquadrant-it/barman) - Backup and Recovery Manager for PostgreSQL. :star:849


## Replication/Data operation
- [Datasette](https://github.com/simonw/datasette) - A tool for exploring and publishing data. :star:3297
- [dtle](https://github.com/actiontech/dtle) - Distributed Data Transfer Service for MySQL. :star:253
- [pgsync](https://github.com/ankane/pgsync) - Sync Postgres data between databases. :star:1633
- [pg_chameleon](https://github.com/the4thdoctor/pg_chameleon) - MySQL to PostgreSQL replica system written in Python 3. The system use the library mysql-replication to pull the row images from MySQL which are stored into PostgreSQL as JSONB. :star:235
- [PGDeltaStream](https://github.com/hasura/pgdeltastream) - A Golang webserver to stream Postgres changes atleast-once over websockets, using Postgres logical decoding feature. :star:163
- [repmgr](https://github.com/2ndQuadrant/repmgr) - The Most Popular Replication Manager for PostgreSQL. :star:1099


## Scripts
- [pgx_scripts](https://github.com/pgexperts/pgx_scripts) - A collection of useful little scripts for database analysis and administration, created by our team at PostgreSQL Experts. :star:802
- [pgsql-bloat-estimation](https://github.com/ioguix/pgsql-bloat-estimation) - Queries to mesure statistical bloat in indexes and tables for PostgreSQL. :star:213
- [pgWikiDont](https://gitlab.com/depesz/pgWikiDont) - SQL test that checks if your database follows rules from <https://wiki.postgresql.org/wiki/Don't_Do_This>.
- [pg-utils](https://github.com/dataegret/pg-utils) - Useful PostgreSQL utilities. :star:426
- [Postgres cheat sheet](https://postgrescheatsheet.com) - Useful SQL-scripts and commands by <timescale.com>.
- [postgres_dba](https://github.com/NikolayS/postgres_dba) - The missing set of useful tools for Postgres DBAs and all engineers. :star:444
- [postgres_queries_and_commands.sql](https://gist.github.com/rgreenjr/3637525) - Useful PostgreSQL Queries and Commands.
- [TPT](https://github.com/tanelpoder/tpt-oracle) - These sqlplus scripts are for Oracle Database performance optimization & troubleshooting. :star:352


## Monitoring/Statistics/Perfomance
- [ASH Viewer](https://github.com/akardapolov/ASH-Viewer) - Provides a graphical view of active session history data within the Oracle and PostgreSQL DB. :star:66
- [Monyog](https://www.webyog.com/product/monyog) - Agentless & Cost-effective MySQL Monitoring Tool.
- [mssql-monitoring](https://github.com/microsoft/mssql-monitoring) - Monitor your SQL Server on Linux performance using collectd, InfluxDB and Grafana. :star:66
- [Navicat Monitor](https://www.navicat.com/en/products/navicat-monitor) - A safe, simple and agentless remote server monitoring tool that is packed with powerful features to make your monitoring effective as possible.
- [Percona Monitoring and Management](https://github.com/percona/pmm) - Open source platform for managing and monitoring MySQL and MongoDB performance. :star:157
- [pganalyze collector](https://github.com/pganalyze/collector) - Pganalyze statistics collector for gathering PostgreSQL metrics and log data. :star:143
- [postgres-checkup](https://gitlab.com/postgres-ai/postgres-checkup) - New-generation diagnostics tool that allows users to do a deep analysis of the health of Postgres databases.
- [postgres_exporter](https://github.com/wrouesnel/postgres_exporter) - Prometheus exporter for PostgreSQL server metrics. :star:913
- [pgDash](https://pgdash.io) - Measure and track every aspect of your PostgreSQL databases.
- [PgHero](https://github.com/ankane/pghero) - A performance dashboard for Postgres - health checks, suggested indexes, and more. :star:5214
- [pgmetrics](https://github.com/rapidloop/pgmetrics) - Collect and display information and stats from a running PostgreSQL server. :star:479
- [pgMustard](https://www.pgmustard.com) - A user interface for Postgres explain plans, plus tips to improve performance.
- [pgstats](https://github.com/gleu/pgstats) - Collects PostgreSQL statistics, and either saves them in CSV files or print them on the stdout. :star:86
- [pgwatch2](https://github.com/cybertec-postgresql/pgwatch2) - Flexible self-contained PostgreSQL metrics monitoring/dashboarding solution. :star:741
- [Telegraf PostgreSQL plugin](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/postgresql) - Provides metrics for your postgres database. :star:8402

### Zabbix
- [Mamonsu](https://github.com/postgrespro/mamonsu) - Monitoring agent for PostgreSQL. :star:138
- [Orabbix](http://www.smartmarmot.com/wiki/index.php?title=Orabbix) - Orabbix is a plugin designed to work with Zabbix Enterprise Monitor to provide multi-tiered monitoring, performance and availability reporting and measurement for Oracle Databases, along with server performance metrics.
- [pg_monz](https://github.com/pg-monz/pg_monz) - This is the Zabbix monitoring template for PostgreSQL Database. :star:161
- [Pyora](https://github.com/bicofino/Pyora) - Python script to monitor Oracle Databases. :star:90
- [ZabbixDBA](https://github.com/anetrusov/ZabbixDBA) - ZabbixDBA is fast, flexible, and continuously developing plugin to monitor your RDBMS. :star:61


## Testing
- [DbFit](https://github.com/dbfit/dbfit) - A database testing framework that supports easy test-driven development of your database code. :star:178
- [RegreSQL](https://github.com/dimitri/regresql) - Regression Testing your SQL queries. :star:144


### Data generator
- [Databene Benerator](https://sourceforge.net/projects/benerator) - It is a framework for generating realistic and valid high-volume test data for your system under test (avoiding the Datalite anti-pattern).
- [dbForge Data Generator for MySQL](https://www.devart.com/dbforge/mysql/data-generator) - Powerful GUI tool for creating massive volumes of realistic test data.
- [dbForge Data Generator for Oracle](https://www.devart.com/dbforge/oracle/data-generator) - Small but mighty GUI tool for populating Oracle schemas with tons of realistic test data.
- [dbForge Data Generator for SQL Server](https://www.devart.com/dbforge/sql/data-generator) - Powerful GUI tool for a fast generation of meaningful test data for databases.


## Administration
- [pgbadger](https://github.com/dalibo/pgbadger) - A fast PostgreSQL Log Analyzer. :star:15
- [pgbedrock](https://github.com/Squarespace/pgbedrock) - Manage a Postgres cluster's roles, role memberships, schema ownership, and privileges. :star:242
- [pgslice](https://github.com/ankane/pgslice) - Postgres partitioning as easy as pie. :star:642


## HA/Failover/Sharding
- [Citus](https://github.com/citusdata/citus) - Postgres extension that distributes your data and your queries across multiple nodes. :star:4078
- [patroni](https://github.com/zalando/patroni) - A template for PostgreSQL High Availability with ZooKeeper, etcd, or Consul. :star:3154
- [Percona XtraDB Cluster](https://github.com/percona/percona-xtradb-cluster) - A High Scalability Solution for MySQL Clustering and High Availability. :star:213
- [stolon](https://github.com/sorintlab/stolon) - Cloud native PostgreSQL manager for PostgreSQL high availability. :star:2720
- [pg_auto_failover](https://github.com/citusdata/pg_auto_failover) - Postgres extension and service for automated failover and high-availability. :star:328
- [pglookout](https://github.com/aiven/pglookout) - PostgreSQL replication monitoring and failover daemon. :star:115
- [PostgreSQL Automatic Failover](https://github.com/ClusterLabs/PAF) - High-Availibility for Postgres, based on industry references Pacemaker and Corosync. :star:259
- [postgresql_cluster](https://github.com/vitabaks/postgresql_cluster) - PostgreSQL High-Availability Cluster (based on "Patroni" and "DCS(etcd)"). Automating deployment with Ansible. :star:137
- [Vitess](https://github.com/vitessio/vitess) - Database clustering system for horizontal scaling of MySQL through generalized sharding. :star:9790


## Kubernetes
- [KubeDB](https://kubedb.com) - Making running production-grade databases easy on Kubernetes.
- [Postgres operator](https://github.com/zalando/postgres-operator) - The Postgres Operator enables highly-available PostgreSQL clusters on Kubernetes (K8s) powered by Patroni. :star:992
- [Spilo](https://github.com/zalando/spilo) - HA PostgreSQL Clusters with Docker. :star:624
- [StackGres](https://gitlab.com/ongresinc/stackgres) - Enterprise-grade, Full Stack PostgreSQL on Kubernetes.


## Configuration Tuning
- [MySQLTuner-perl](https://github.com/major/MySQLTuner-perl) - Script written in Perl that allows you to review a MySQL installation quickly and make adjustments to increase performance and stability. :star:5935
- [PGConfigurator](https://pgconfigurator.cybertec-postgresql.com) - Free online tool to generate an optimized `postgresql.conf`.
- [pgtune](https://github.com/gregs1104/pgtune) - PostgreSQL configuration wizard. :star:899
- [postgresqltuner.pl](https://github.com/jfcoz/postgresqltuner) - Simple script to analyse your PostgreSQL database configuration, and give tuning advice. :star:1939


## DevOps
- [DBmaestro](https://www.dbmaestro.com) - DBmaestro accelerates release cycles & supports agility across the entire IT ecosystem.
- [Toad DevOps Toolkit](https://www.quest.com/products/toad-devops-toolkit/) - Toad DevOps Toolkit executes key database development functions within your DevOps workflow —without compromising quality, performance or reliability.


## Schema samples
- [Oracle Database Sample Schemas](https://github.com/oracle/db-sample-schemas) - Oracle Database Sample Schemas. :star:310


## Reporting
- [Poli](https://github.com/shzlw/poli) - An easy-to-use SQL reporting application built for SQL lovers. :star:1601


## Distributions
- [DBdeployer](https://github.com/datacharmer/dbdeployer) - Tool that deploys MySQL database servers easily. :star:365
- [dbatools](https://github.com/sqlcollaborative/dbatools) - PowerShell module that you may think of like a command-line SQL Server Management Studio. :star:1217
- [Postgres.app](https://github.com/PostgresApp/PostgresApp) - Full-featured PostgreSQL installation packaged as a standard Mac app. :star:5260
- [BigSQL](https://www.bigsql.org) - A developer-friendly distribution of Postgres.
- [Elephant Shed](https://github.com/credativ/elephant-shed) - Web-based PostgreSQL management front-end that bundles several utilities and applications for use with PostgreSQL. :star:127


## Security
- [Acra](https://github.com/cossacklabs/acra) - Database security suite. Database proxy with field-level encryption, search through encrypted data, SQL injections prevention, intrusion detection, honeypots. Supports client-side and proxy-side ("transparent") encryption. SQL, NoSQL. :star:563


## Code formatters
- [CodeBuff](https://github.com/antlr/codebuff) - Language-agnostic pretty-printing through machine learning. :star:326


## Contributing
- Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.


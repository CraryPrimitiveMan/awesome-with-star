# Information comes from [awesome-spark/awesome-spark](https://github.com/awesome-spark/awesome-spark)
[<img src="https://cdn.rawgit.com/awesome-spark/awesome-spark/f78a16db/spark-logo-trademark.svg" align="right">](https://spark.apache.org/)

# Awesome Spark [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome [Apache Spark](https://spark.apache.org/) packages and resources.

_Apache Spark is an open-source cluster-computing framework. Originally developed at the [University of California](https://www.universityofcalifornia.edu/), [Berkeley's AMPLab](https://amplab.cs.berkeley.edu/), the Spark codebase was later donated to the [Apache Software Foundation](https://www.apache.org/), which has maintained it since. Spark provides an interface for programming entire clusters with implicit data parallelism and fault-tolerance_  ([Wikipedia 2017](#wikipedia-2017)).

Users of Apache Spark may choose between different the Python, R, Scala and Java programming languages to interface with the Apache Spark APIs.

## Contents

- [Packages](#packages)
  - [Language Bindings](#language-bindings)
  - [Notebooks and IDEs](#notebooks-and-ides)
  - [General Purpose Libraries](#general-purpose-libraries)
  - [SQL Data Sources](#sql-data-sources)
  - [Bioinformatics](#bioinformatics)
  - [GIS](#gis)
  - [Time Series Analytics](#time-series-analytics)
  - [Graph Processing](#graph-processing)
  - [Machine Learning Extension](#machine-learning-extension)
  - [Middleware](#middleware)
  - [Utilities](#utilities)
  - [Natural Language Processing](#natural-language-processing)
  - [Streaming](#streaming)
  - [Interfaces](#interfaces)
  - [Testing](#testing)
  - [Workflow Management](#workflow-management)

- [Resources](#resources)
  - [Books](#books)
  - [Papers](#papers)
  - [MOOCS](#moocs)
  - [Workshops](#workshops)
  - [Projects Using Spark](#projects-using-spark)
  - [Blogs](#blogs)
  - [Docker Images](#docker-images)
  - [Miscellaneous](#miscellaneous)


## Packages

### Language Bindings

* [Flambo](https://github.com/yieldbot/flambo) - Clojure DSL. :star:562
* [Mobius](https://github.com/Microsoft/Mobius) - C# bindings. :star:759
* [sparklyr](https://github.com/rstudio/sparklyr) - An alternative R backend, using [`dplyr`](https://github.com/hadley/dplyr). :star:538
* [sparkle](https://github.com/tweag/sparkle) - Haskell on Apache Spark. :star:324

### Notebooks and IDEs

* [Apache Zeppelin](https://zeppelin.incubator.apache.org/) - Web-based notebook that enables interactive data analytics with plugable backends, integrated plotting, and extensive Spark support out-of-the-box.
* [Spark Notebook](https://github.com/andypetrella/spark-notebook) - Scalable and stable Scala and Spark focused notebook bridging the gap between JVM and Data Scientists (incl. extendable, typesafe and reactive charts). :star:2424
* [sparkmagic](https://github.com/jupyter-incubator/sparkmagic) - [Jupyter](https://jupyter.org/) magics and kernels for working with remote Spark clusters, for interactively working with remote Spark clusters through [Livy](https://github.com/cloudera/livy), in Jupyter notebooks. :star:363

### General Purpose Libraries

* [Succinct](http://succinct.cs.berkeley.edu/) - Support for efficient queries on compressed data.


### SQL Data Sources

* [Spark CSV](https://github.com/databricks/spark-csv) - CSV reader and writer (obsolete since Spark 2.0 [[SPARK-12833]](https://issues.apache.org/jira/browse/SPARK-12833)). :star:895
* [Spark Avro](https://github.com/databricks/spark-avro) - [Apache Avro](https://avro.apache.org/) reader and writer. :star:466
* [Spark XML](https://github.com/databricks/spark-xml) - XML parser and writer. :star:179
* [Spark-Mongodb](https://github.com/Stratio/Spark-MongoDB) - MongoDB reader and writer. :star:296
* [Spark Cassandra Connector](https://github.com/datastax/spark-cassandra-connector) - Cassandra support including data source and API and support for arbitrary queries. :star:1425
* [Spark Riak Connector](https://github.com/basho/spark-riak-connector) - Riak TS & Riak KV connector. :star:35
* [Mongo-Spark](https://github.com/mongodb/mongo-spark) - Official MongoDB connector. :star:376
* [OrientDB-Spark](https://github.com/orientechnologies/spark-orientdb) - Official OrientDB connector. :star:6

### Bioinformatics

* [ADAM](https://github.com/bigdatagenomics/adam) - Set of tools designed to analyse genomics data. :star:718
* [Hail](https://github.com/hail-is/hail) - Genetic analysis framework. :star:328

### GIS

* [Magellan](https://github.com/harsha2010/magellan) - Geospatial analytics using Spark. :star:388
* [GeoSpark](https://github.com/Sarwat/GeoSpark) - Cluster computing system for processing large-scale spatial data. :star:302

### Time Series Analytics

* [Spark-Timeseries](https://github.com/cloudera/spark-timeseries) - Scala / Java / Python library for interacting with time series data on Apache Spark. :star:915
* [flint](https://github.com/twosigma/flint) - A time series library for Apache Spark. :star:344

### Graph Processing

* [Mazerunner](https://github.com/neo4j-contrib/neo4j-mazerunner) - Graph analytics platform on top of Neo4j and GraphX. :star:344
* [GraphFrames](https://github.com/graphframes/graphframes) - Data frame based graph API. :star:372
* [neo4j-spark-connector](https://github.com/neo4j-contrib/neo4j-spark-connector) - Bolt protocol based, Neo4j Connector with RDD, DataFrame and GraphX / GraphFrames support. :star:121
* [SparklingGraph](http://sparkling.ml) - Library extending GraphX features with multiple functionalities useful in graph analytics (measures, generators, link prediction etc.).

### Machine Learning Extension

* [dbscan-on-spark](https://github.com/irvingc/dbscan-on-spark) - An Implementation of the DBSCAN clustering algorithm on top of Apache Spark by [irvingc](https://github.com/irvingc) and based on the paper from He, Yaobin, et al. [MR-DBSCAN: a scalable MapReduce-based DBSCAN algorithm for heavily skewed data](https://www.researchgate.net/profile/Yaobin_He/publication/260523383_MR-DBSCAN_a_scalable_MapReduce-based_DBSCAN_algorithm_for_heavily_skewed_data/links/0046353a1763ee2bdf000000.pdf). :star:88
* [Apache SystemML](https://systemml.apache.org/) - Declarative machine learning framework on top of Spark.
* [Mahout Spark Bindings](https://mahout.apache.org/users/sparkbindings/home.html) - linear algebra DSL and optimizer with R-like syntax.
* [spark-sklearn](https://github.com/databricks/spark-sklearn) - Scikit-learn integration with distributed model training. :star:708
* [KeystoneML](http://keystone-ml.org/) - Type safe machine learning pipelines with RDDs.
* [JPMML-Spark](https://github.com/jpmml/jpmml-spark) - PMML transformer library for Spark ML. :star:53
* [Distributed Keras](https://github.com/cerndb/dist-keras) - Distributed deep learning framework with PySpark and Keras. :star:436
* [ModelDB](https://mitdbg.github.io/modeldb) - A system to manage machine learning models for `spark.ml` and [`scikit-learn`](https://github.com/scikit-learn/scikit-learn).
* [Sparkling Water](https://github.com/h2oai/sparkling-water) -  [H2O](http://www.h2o.ai/) interoperability layer. :star:633
* [BigDL](https://github.com/intel-analytics/BigDL) - Distributed Deep Learning library. :star:2475

### Middleware

* [Livy](https://github.com/cloudera/livy) - REST server with extensive language support (Python, R, Scala), ability to maintain interactive sessions and object sharing. :star:757

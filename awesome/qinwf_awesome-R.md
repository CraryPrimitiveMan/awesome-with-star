# Information comes from [qinwf/awesome-R](https://github.com/qinwf/awesome-R)
# Awesome R

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome R packages and tools. Inspired by [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning).

For better navigation, see https://awesome-r.com

<p><img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">
for <a target="_blank" href="https://github.com/rstudio/RStartHere/blob/master/top_downloads_2016/top_packages">Top 50</a> CRAN downloaded packages or repos with 400+
<img class="emoji" alt="star" src="https://awesome-r.com/star.png" height="20" align="absmiddle" width="20"></p>

- [Awesome R](#awesome-)
    - [2017](#2017)
    - [Integrated Development Environments](#integrated-development-environments)
    - [Syntax](#syntax)
    - [Data Manipulation](#data-manipulation)
    - [Graphic Displays](#graphic-displays)
    - [Html Widgets](#html-widgets)
    - [Reproducible Research](#reproducible-research)
    - [Web Technologies and Services](#web-technologies-and-services)
    - [Parallel Computing](#parallel-computing)
    - [High Performance](#high-performance)
    - [Language API](#language-api)
    - [Database Management](#database-management)
    - [Machine Learning](#machine-learning)
    - [Natural Language Processing](#natural-language-processing)
    - [Bayesian](#bayesian)
    - [Optimization](#optimization)
    - [Finance](#finance)
    - [Bioinformatics](#bioinformatics)
    - [Network Analysis](#network-analysis)
    - [Spatial](#spatial)
    - [R Development](#r-development)
    - [Logging](#logging)
    - [Data Packages](#data-packages)
    - [Other Tools](#other-tools)
    - [Other Interpreters](#other-interpreters)
    - [Learning R](#learning-r)
- [Resources](#resources)
    - [Websites](#websites)
    - [Books](#books)
    - [Podcasts](#podcasts)
    - [Reference Cards](#reference-cards)
    - [MOOCs](#moocs)
    - [Lists](#lists)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## 2017

* [prophet](https://github.com/facebookincubator/prophet) - Tool for producing high quality forecasts for time series data that has multiple seasonality with linear or non-linear growth. :star:4834
* [tidyverse](https://github.com/tidyverse/tidyverse) - Easily install and load packages from the tidyverse :star:478
* [purrr](https://github.com/tidyverse/purrr) - A functional programming toolkit for R :star:579
* [hrbrthemes](https://github.com/hrbrmstr/hrbrthemes) -  🔏 Opinionated, typographic-centric ggplot2 themes and theme components :star:337
* [xaringan](https://github.com/yihui/xaringan) - Create HTML5 slides with R Markdown and the JavaScript library :star:366
* [blogdown](https://github.com/rstudio/blogdown) - Create Blogs and Websites with R Markdown :star:633
* [glue](https://github.com/tidyverse/glue) -  Glue strings to data in R. Small, fast, dependency free interpreted string literals. :star:240
* [covr](https://github.com/jimhester/covr) - Test coverage reports for R :star:187
* [lintr](https://github.com/jimhester/lintr) - Static Code Analysis for R :star:413
* [reprex](https://github.com/jennybc/reprex) - Render bits of R code for sharing, e.g., on GitHub or StackOverflow. :star:297
* [reticulate](https://github.com/rstudio/reticulate) - R Interface to Python :star:371
* [tensorflow](https://github.com/rstudio/tensorflow) -  TensorFlow for R :star:964
* [utf8](https://github.com/patperry/r-utf8) - Manipulating and printing UTF-8 text that fixes multiple bugs in R's UTF-8 handling. :star:68

## Integrated Development Environments
*Integrated Development Environment*

* [RStudio <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://www.rstudio.org/) - A powerful and productive user interface for R. Works great on Windows, Mac, and Linux.
* [Emacs + ESS](http://ess.r-project.org/) - Emacs Speaks Statistics is an add-on package for emacs text editors.
* [Sublime Text + R-Box](http://github.com/randy3k/R-Box/) - Add-on package for Sublime Text 2/3.
* [TextMate + r.tmblundle](https://github.com/textmate/r.tmbundle) - Add-on package for TextMate 1/2. :star:22
* [StatET](http://www.walware.de/goto/statet) - An Eclipse based IDE for R.
* [Revolution R Enterprise](http://www.revolutionanalytics.com/get-revolution-r-enterprise) - Revolution R would be offered free to academic users and commercial software would focus on big data, large scale multiprocessor functionality.
* [R Commander](http://socserv.mcmaster.ca/jfox/Misc/Rcmdr/) - A package that provides a basic graphical user interface.
* [IRkernel <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/IRkernel/IRkernel) - R kernel for Jupyter. :star:840
* [Deducer](http://www.deducer.org/pmwiki/pmwiki.php?n=Main.DeducerManual?from=Main.HomePage) - A Menu driven data analysis GUI with a spreadsheet like data editor.
* [Radiant](https://radiant-rstats.github.io/docs) - A platform-independent browser-based interface for business analytics in R, based on the Shiny.
* [Vim-R](https://github.com/vim-scripts/Vim-R-plugin) - Vim plugin for R. :star:115
* [Nvim-R](https://github.com/jalvesaq/Nvim-R) - Neovim plugin for R. :star:295
* [JASP](https://jasp-stats.org/) - A complete package for both Bayesian and Frequentist methods, that is familiar to users of SPSS.
* [Bio7](http://www.bio7.org/) - A IDE contains tools for model creation, scientific image analysis and statistical analysis for ecological modelling.
* [RTVS](http://microsoft.github.io/RTVS-docs/) - R Tools for Visual Studio.
* [Rice](https://github.com/randy3k/Rice) - A modern R console with syntax highlighting. :star:208

## Syntax
*Packages change the way you use R.*

* [magrittr <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/smbache/magrittr) - Let's pipe it. :star:593
* [pipeR](https://github.com/renkun-ken/pipeR) - Multi-paradigm Pipeline Implementation. :star:123
* [lambda.r](https://github.com/zatonovo/lambda.r) - Functional programming and simple pattern matching in R. :star:109
* [purrr](https://github.com/hadley/purrr) - A FP package for R in the spirit of underscore.js. :star:579

## Data Manipulation
*Packages for cooking data.*

* [dplyr <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/hadley/dplyr) - Fast data frames manipulation and database query. :star:2207
* [data.table <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/Rdatatable/data.table) - Fast data manipulation in a short and flexible syntax. :star:1327
* [reshape2  <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/hadley/reshape) - Flexible rearrange, reshape and aggregate data. :star:167
* [readr <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/hadley/readr) - A fast and friendly way to read tabular data into R. :star:582
* [haven](https://github.com/hadley/haven) - Improved methods to import SPSS, Stata and SAS files in R. :star:235
* [tidyr](https://github.com/hadley/tidyr) - Easily tidy data with spread and gather functions. :star:560
* [broom <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/dgrtwo/broom) - Convert statistical analysis objects into tidy data frames. :star:651
* [rlist](https://github.com/renkun-ken/rlist) - A toolbox for non-tabular data manipulation with lists. :star:113
* [jsonlite](https://github.com/jeroenooms/jsonlite) - A robust and quick way to parse JSON files in R. :star:165
* [ff](http://ff.r-forge.r-project.org/) - Data structures designed to store large datasets.
* [lubridate](http://cran.r-project.org/web/packages/lubridate/index.html) - A set of functions to work with dates and times.
* [stringi <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://www.gagolewski.com/software/stringi/) - ICU based string processing package.
* [stringr <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/hadley/stringr) - Consistent API for string processing, built on top of stringi. :star:239
* [bigmemory](http://cran.r-project.org/web/packages/bigmemory/index.html) - Shared memory and memory-mapped matrices. The big\* packages provide additional tools including linear models ([biglm](http://cran.r-project.org/web/packages/biglm/index.html)) and Random Forests ([bigrf](https://github.com/aloysius-lim/bigrf)).
* [fuzzyjoin](https://github.com/dgrtwo/fuzzyjoin) - Join tables together on inexact matching. :star:285
* [tidyverse](https://github.com/hadley/tidyverse) - Easily install and load packages from the tidyverse. :star:478

## Graphic Displays
*Packages for showing data.*

* [ggplot2 <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/hadley/ggplot2) - An implementation of the Grammar of Graphics. :star:2931
* [ggfortify](https://github.com/sinhrks/ggfortify) - A unified interface to ggplot2 popular statistical packages using one line of code. :star:317
* [ggrepel](https://github.com/slowkow/ggrepel) - Repel overlapping text labels away from each other. :star:454
* [ggalt](https://github.com/hrbrmstr/ggalt) - Extra Coordinate Systems, Geoms and Statistical Transformations for ggplot2. :star:308
* [ggtree](https://github.com/GuangchuangYu/ggtree) - Visualization and annotation of phylogenetic tree. :star:210
* [ggtech](https://github.com/ricardo-bion/ggtech) - ggplot2 tech themes and scales :star:173
* [ggplot2 Extensions](https://ggplot2-exts.github.io/ggiraph.html) - Showcases of ggplot2 extensions.
* [lattice](http://lattice.r-forge.r-project.org/) - A powerful and elegant high-level data visualization system.
* [corrplot](https://github.com/taiyun/corrplot) - A graphical display of a correlation matrix or general matrix. It also contains some algorithms to do matrix reordering. :star:120
* [rgl](http://cran.r-project.org/web/packages/rgl/index.html) - 3D visualization device system for R.
* [Cairo](http://cran.r-project.org/web/packages/Cairo/index.html) - R graphics device using cairo graphics library for creating high-quality display output.
* [extrafont](https://github.com/wch/extrafont) - Tools for using fonts in R graphics. :star:141
* [showtext](https://github.com/yixuan/showtext) - Enable R graphics device to show text using system fonts. :star:169
* [animation](http://yihui.name/animation/) - A simple way to produce animated graphics in R, using [ImageMagick](http://imagemagick.org/).
* [gganimate](https://github.com/dgrtwo/gganimate) - Create easy animations with ggplot2. :star:537
* [misc3d](https://cran.r-project.org/web/packages/misc3d/index.html) - Powerful functions to deal with 3d plots, isosurfaces, etc.
* [xkcd](https://cran.r-project.org/web/packages/xkcd/index.html) - Use xkcd style in graphs.
* [imager](http://dahtah.github.io/imager/) - An image processing package based on CImg library to work with images and display them.
* [hrbrthemes](https://github.com/hrbrmstr/hrbrthemes) -  🔏 Opinionated, typographic-centric ggplot2 themes and theme components. :star:337
* [waffle](https://github.com/hrbrmstr/waffle) -  🍁 Make waffle (square pie) charts in R :star:281


## HTML Widgets
*Packages for interactive visualizations.*

* [d3heatmap](https://github.com/rstudio/d3heatmap) - Interactive heatmaps with D3. :star:196
* [DataTables](http://rstudio.github.io/DT/) - Displays R matrices or data frames as interactive HTML tables.
* [DiagrammeR <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/rich-iannone/DiagrammeR) - Create JS graph diagrams and flowcharts in R. :star:926
* [dygraphs](https://github.com/rstudio/dygraphs) - Charting time-series data in R. :star:220
* [formattable](http://renkun.me/formattable/) - Formattable Data Structures.
* [ggvis <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/rstudio/ggvis) - Interactive grammar of graphics for R. :star:623
* [Leaflet](http://rstudio.github.io/leaflet/) - One of the most popular JavaScript libraries interactive maps.
* [MetricsGraphics](http://hrbrmstr.github.io/metricsgraphics/) - Enables easy creation of D3 scatterplots, line charts, and histograms.
* [networkD3](http://christophergandrud.github.io/networkD3/) - D3 JavaScript Network Graphs from R.
* [scatterD3](https://github.com/juba/scatterD3) - Interactive scatterplots with D3. :star:99
* [plotly <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/ropensci/plotly) - Interactive ggplot2 and Shiny plotting with [plot.ly](https://plot.ly). :star:1139
* [rCharts <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/ramnathv/rCharts) - Interactive JS Charts from R. :star:1106
* [rbokeh](http://hafen.github.io/rbokeh/) - R Interface to [Bokeh](http://bokeh.pydata.org/en/latest/).
* [threejs](https://github.com/bwlewis/rthreejs) - Interactive 3D scatter plots and globes. :star:188
* [timevis](https://github.com/daattali/timevis) - Create fully interactive timeline visualizations. :star:219
* [visNetwork](https://github.com/datastorm-open/visNetwork) - Using vis.js library for network visualization. :star:210
* [wordcloud2](https://github.com/Lchiffon/wordcloud2) - R interface to wordcloud2.js. :star:218
* [highcharter](https://github.com/jbkunst/highcharter) - R wrapper for highcharts based on htmlwidgets :star:297

## Reproducible Research
*Packages for literate programming.*

* [knitr <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://yihui.name/knitr/) - Easy dynamic report generation in R.
* [xtable](http://cran.r-project.org/web/packages/xtable/index.html) - Export tables to LaTeX or HTML.
* [rapport](http://rapport-package.info/#intro) - An R templating system.
* [rmarkdown <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://rmarkdown.rstudio.com/) - Dynamic documents for R.
* [slidify <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/ramnathv/slidify) - Generate reproducible html5 slides from R markdown. :star:794
* [Sweave](https://www.statistik.lmu.de/~leisch/Sweave/) - A package designed to write LaTeX reports using R.
* [texreg](http://www.philipleifeld.de/software/texreg/texreg.html) - Formatting statistical models in LaTex and HTML.
* [checkpoint](https://github.com/RevolutionAnalytics/checkpoint) - Install packages from snapshots on the checkpoint server. :star:89
* [brew](https://cran.r-project.org/web/packages/brew/index.html) - Pre-compute data to enhance your report templates. Can be combined with knitr.
* [ReporteRs](http://davidgohel.github.io/ReporteRs/index.html) - An R package to generate Microsoft Word, Microsoft PowerPoint and HTML reports.
* [bookdown](https://bookdown.org/) - Authoring Books with R Markdown.
* [ezknitr](https://github.com/daattali/ezknitr) - Avoid the typical working directory pain when using 'knitr' :star:62

## Web Technologies and Services
*Packages to surf the web.*

* [Web Technologies List](https://github.com/ropensci/webservices) - Information about how to use R and the world wide web together. :star:139
* [shiny <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/rstudio/shiny) - Easy interactive web applications with R. See also [awesome-rshiny](https://github.com/grabear/awesome-rshiny) :star:2704
* [shinyjs](https://github.com/daattali/shinyjs) -  Easily improve the user interaction and user experience in your Shiny apps in seconds. :star:317
* [RCurl](http://cran.r-project.org/web/packages/RCurl/index.html) - General network (HTTP/FTP/...) client interface for R.
* [httr <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/hadley/httr) - User-friendly RCurl wrapper. :star:679
* [httpuv](https://github.com/rstudio/httpuv) - HTTP and WebSocket server library. :star:103
* [XML <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://cran.r-project.org/web/packages/XML/index.html) - Tools for parsing and generating XML within R.
* [rvest <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/hadley/rvest) - Simple web scraping for R, using CSSSelect or XPath syntax. :star:890
* [OpenCPU <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://www.opencpu.org/) - HTTP API for R.
* [Rfacebook](https://github.com/pablobarbera/Rfacebook) - Access to Facebook API via R. :star:294
* [RSiteCatalyst](https://github.com/randyzwitch/RSiteCatalyst) - R client library for the Adobe Analytics. :star:106
* [plumber](https://github.com/trestletech/plumber) - A library to expose existing R code as web API. :star:542

## Parallel Computing
*Packages for parallel computing.*

* [parallel](http://cran.r-project.org/web/views/HighPerformanceComputing.html) - R started with release 2.14.0 which includes a new package parallel incorporating (slightly revised) copies of packages [multicore](http://cran.r-project.org/web/packages/multicore/index.html) and [snow](http://cran.r-project.org/web/packages/snow/index.html).
* [Rmpi](http://cran.r-project.org/web/packages/Rmpi/index.html) - Rmpi provides an interface (wrapper) to MPI APIs. It also provides interactive R slave environment.
* [foreach <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://cran.r-project.org/web/packages/foreach/index.html) - Executing the loop in parallel.
* [future](https://cran.r-project.org/package=future) - A minimal, efficient, cross-platform unified Future API for parallel and distributed processing in R; designed for beginners as well as advanced developers.
* [SparkR <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/amplab-extras/SparkR-pkg) - R frontend for Spark. :star:644
* [DistributedR](https://github.com/vertica/DistributedR) - A scalable high-performance platform from  HP Vertica Analytics Team. :star:144
* [ddR](https://github.com/vertica/ddR) - Provides distributed data structures and simplifies distributed computing in R. :star:103
* [sparklyr](http://spark.rstudio.com/) - R interface for Apache Spark from RStudio.
* [batchtools](https://cran.r-project.org/package=batchtools) - High performance computing with LSF, TORQUE, Slurm, OpenLava, SGE and Docker Swarm.

## High Performance
*Packages for making R faster.*

* [Rcpp <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://rcpp.org/) - Rcpp provides a powerful API on top of R, make function in R extremely faster.
* [Rcpp11](https://github.com/Rcpp11/Rcpp11) - Rcpp11 is a complete redesign of Rcpp, targetting C++11. :star:73
* [compiler](http://stat.ethz.ch/R-manual/R-devel/library/compiler/html/compile.html) - speeding up your R code using the JIT

## Language API
*Packages for other languages.*

* [rJava](http://cran.r-project.org/web/packages/rJava/) - Low-level R to Java interface.
* [jvmr](https://github.com/cran/jvmr) - Integration of R, Java, and Scala. :star:13
* [rJython](http://cran.r-project.org/web/packages/rJython/index.html) - R interface to Python via Jython.
* [rPython](http://cran.r-project.org/web/packages/rPython/index.html) - Package allowing R to call Python.
* [runr](https://github.com/yihui/runr) - Run Julia and Bash from R. :star:76
* [RJulia](https://github.com/armgong/RJulia) - R package Call Julia. :star:121
* [JuliaCall](https://github.com/Non-Contradiction/JuliaCall) - Seamless Integration Between R and Julia. :star:20
* [RinRuby](https://sites.google.com/a/ddahl.org/rinruby-users/) - a Ruby library that integrates the R interpreter in Ruby.
* [R.matlab](http://cran.r-project.org/web/packages/R.matlab/index.html) - Read and write of MAT files together with R-to-MATLAB connectivity.
* [RcppOctave](https://github.com/renozao/RcppOctave) - Seamless Interface to Octave and Matlab. :star:11
* [RSPerl](http://www.omegahat.org/RSPerl/) - A bidirectional interface for calling R from Perl and Perl from R.
* [V8](https://github.com/jeroenooms/V8) - Embedded JavaScript Engine. :star:84
* [htmlwidgets](http://www.htmlwidgets.org/) - Bring the best of JavaScript data visualization to R.
* [rpy2](http://rpy.sourceforge.net/) - Python interface for R.

## Database Management
*Packages for managing data.*

* [RODBC](http://cran.r-project.org/web/packages/RODBC/) - ODBC database access for R.
* [DBI](https://github.com/rstats-db/DBI) - Defines a common interface between the R and database management systems. :star:124
* [elastic](https://github.com/ropensci/elastic) - Wrapper for the Elasticsearch HTTP API :star:178
* [mongolite](https://github.com/jeroenooms/mongolite) - Streaming Mongo Client for R :star:154
* [RMariaDB](https://github.com/rstats-db/RMariaDB) - An R interface to MariaDB (a replacement for the old RMySQL package) :star:35
* [RMySQL](http://cran.r-project.org/web/packages/RMySQL/) - R interface to the MySQL database.
* [ROracle](http://cran.r-project.org/web/packages/ROracle/index.html) - OCI based Oracle database interface for R.
* [RPostgreSQL](https://code.google.com/p/rpostgresql/) - R interface to the PostgreSQL database system.
* [RSQLite](http://cran.r-project.org/web/packages/RSQLite/) - SQLite interface for R
* [RJDBC](http://cran.r-project.org/web/packages/RJDBC/) - Provides access to databases through the JDBC interface.
* [rmongodb](https://github.com/mongosoup/rmongodb) - R driver for MongoDB. :star:57
* [rredis](http://cran.r-project.org/web/packages/rredis/) - Redis client for R.
* [RCassandra](http://cran.r-project.org/web/packages/RCassandra/index.html) - Direct interface (not Java) to the most basic functionality of Apache Cassanda.
* [RHive](https://github.com/nexr/RHive) - R extension facilitating distributed computing via Apache Hive. :star:124
* [RNeo4j](https://github.com/nicolewhite/Rneo4j) - Neo4j graph database driver. :star:207
* [rpostgis](https://github.com/mablab/rpostgis) - R interface to PostGIS database and get spatial objects in R. :star:29

## Machine Learning
*Packages for making R cleverer.*

* [AnomalyDetection <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/twitter/AnomalyDetection) - AnomalyDetection R package from Twitter. :star:2387
* [ahaz](http://cran.r-project.org/web/packages/ahaz/index.html) - Regularization for semiparametric additive hazards regression.
* [arules](http://cran.r-project.org/web/packages/arules/index.html) - Mining Association Rules and Frequent Itemsets
* [bigrf](http://cran.r-project.org/web/packages/bigrf/index.html) - Big Random Forests: Classification and Regression Forests for
Large Data Sets
* [bigRR](http://cran.r-project.org/web/packages/bigRR/index.html) - Generalized Ridge Regression (with special advantage for p >> n
cases)
* [bmrm](http://cran.r-project.org/web/packages/bmrm/index.html) - Bundle Methods for Regularized Risk Minimization Package
* [Boruta](http://cran.r-project.org/web/packages/Boruta/index.html) - A wrapper algorithm for all-relevant feature selection
* [BreakoutDetection <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/twitter/BreakoutDetection) - Breakout Detection via Robust E-Statistics from Twitter. :star:623
* [bst](http://cran.r-project.org/web/packages/bst/index.html) - Gradient Boosting
* [CausalImpact <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/google/CausalImpact) - Causal inference using Bayesian structural time-series models. :star:755
* [C50](http://cran.r-project.org/web/packages/C50/index.html) - C5.0 Decision Trees and Rule-Based Models
* [caret <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://cran.r-project.org/web/packages/caret/index.html) - Classification and Regression Training
* [Clever Algorithms For Machine Learning](https://github.com/jbrownlee/CleverAlgorithmsMachineLearning)
* [CORElearn](http://cran.r-project.org/web/packages/CORElearn/index.html) - Classification, regression, feature evaluation and ordinal
evaluation
* [CoxBoost](http://cran.r-project.org/web/packages/CoxBoost/index.html) - Cox models by likelihood based boosting for a single survival
endpoint or competing risks
* [Cubist](http://cran.r-project.org/web/packages/Cubist/index.html) - Rule- and Instance-Based Regression Modeling
* [e1071](http://cran.r-project.org/web/packages/e1071/index.html) - Misc Functions of the Department of Statistics (e1071), TU Wien
* [earth](http://cran.r-project.org/web/packages/earth/index.html) - Multivariate Adaptive Regression Spline Models
* [elasticnet](http://cran.r-project.org/web/packages/elasticnet/index.html) - Elastic-Net for Sparse Estimation and Sparse PCA
* [ElemStatLearn](http://cran.r-project.org/web/packages/ElemStatLearn/index.html) - Data sets, functions and examples from the book: "The Elements
of Statistical Learning, Data Mining, Inference, and
Prediction" by Trevor Hastie, Robert Tibshirani and Jerome
Friedman
* [evtree](http://cran.r-project.org/web/packages/evtree/index.html) - Evolutionary Learning of Globally Optimal Trees
* [forecast](http://cran.r-project.org/web/packages/forecast/index.html) - Timeseries forecasting using ARIMA, ETS, STLM, TBATS, and neural network models
* [forecastHybrid](http://cran.r-project.org/web/packages/forecastHybrid/index.html) - Automatic ensemble and cross validation of ARIMA, ETS, STLM, TBATS, and neural network models from the "forecast" package
* [prophet <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/facebookincubator/prophet) - Tool for producing high quality forecasts for time series data that has multiple seasonality with linear or non-linear growth. :star:4834
* [FSelector](https://cran.r-project.org/web/packages/FSelector/index.html) - A feature selection framework, based on subset-search or feature ranking approches.
* [frbs](http://cran.r-project.org/web/packages/frbs/index.html) - Fuzzy Rule-based Systems for Classification and Regression Tasks
* [GAMBoost](http://cran.r-project.org/web/packages/GAMBoost/index.html) - Generalized linear and additive models by likelihood based
boosting
* [gamboostLSS](http://cran.r-project.org/web/packages/gamboostLSS/index.html) - Boosting Methods for GAMLSS
* [gbm](http://cran.r-project.org/web/packages/gbm/index.html) - Generalized Boosted Regression Models
* [glmnet <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://cran.r-project.org/web/packages/glmnet/index.html) - Lasso and elastic-net regularized generalized linear models
* [glmpath](http://cran.r-project.org/web/packages/glmpath/index.html) - L1 Regularization Path for Generalized Linear Models and Cox
Proportional Hazards Model
* [GMMBoost](http://cran.r-project.org/web/packages/GMMBoost/index.html) - Likelihood-based Boosting for Generalized mixed models
* [grplasso](http://cran.r-project.org/web/packages/grplasso/index.html) - Fitting user specified models with Group Lasso penalty
* [grpreg](http://cran.r-project.org/web/packages/grpreg/index.html) - Regularization paths for regression models with grouped
covariates
* [h2o <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://cran.r-project.org/web/packages/h2o/index.html) - Deeplearning, Random forests, GBM, KMeans, PCA, GLM
* [hda](http://cran.r-project.org/web/packages/hda/index.html) - Heteroscedastic Discriminant Analysis
* [ipred](http://cran.r-project.org/web/packages/ipred/index.html) - Improved Predictors
* [kernlab](http://cran.r-project.org/web/packages/kernlab/index.html) - kernlab: Kernel-based Machine Learning Lab
* [klaR](http://cran.r-project.org/web/packages/klaR/index.html) - Classification and visualization
* [kohonen](http://cran.r-project.org/web/packages/kohonen/) - Supervised and Unsupervised Self-Organising Maps.
* [lars](http://cran.r-project.org/web/packages/lars/index.html) - Least Angle Regression, Lasso and Forward Stagewise
* [lasso2](http://cran.r-project.org/web/packages/lasso2/index.html) - L1 constrained estimation aka ‘lasso’
* [LiblineaR](http://cran.r-project.org/web/packages/LiblineaR/index.html) - Linear Predictive Models Based On The Liblinear C/C++ Library
* [lme4 <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/lme4/lme4) - Mixed-effects models :star:257
* [LogicReg](http://cran.r-project.org/web/packages/LogicReg/index.html) - Logic Regression
* [maptree](http://cran.r-project.org/web/packages/maptree/index.html) - Mapping, pruning, and graphing tree models
* [mboost](http://cran.r-project.org/web/packages/mboost/index.html) - Model-Based Boosting
* [Machine Learning For Hackers <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/johnmyleswhite/ML_for_Hackers)
* [mlr <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/mlr-org/mlr) - Extensible framework for classification, regression, survival analysis and clustering :star:883
* [mvpart](http://cran.r-project.org/web/packages/mvpart/index.html) - Multivariate partitioning
* [MXNet <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/dmlc/mxnet/tree/master/R-package) - MXNet brings flexible and efficient GPU computing and state-of-art deep learning to R.
* [ncvreg](http://cran.r-project.org/web/packages/ncvreg/index.html) - Regularization paths for SCAD- and MCP-penalized regression
models
* [nnet](http://cran.r-project.org/web/packages/nnet/index.html) - eed-forward Neural Networks and Multinomial Log-Linear Models
* [oblique.tree](http://cran.r-project.org/web/packages/oblique.tree/index.html) - Oblique Trees for Classification Data
* [pamr](http://cran.r-project.org/web/packages/pamr/index.html) - Pam: prediction analysis for microarrays
* [party](http://cran.r-project.org/web/packages/party/index.html) - A Laboratory for Recursive Partytioning
* [partykit](http://cran.r-project.org/web/packages/partykit/index.html) - A Toolkit for Recursive Partytioning
* [penalized](http://cran.r-project.org/web/packages/penalized/index.html) - L1 (lasso and fused lasso) and L2 (ridge) penalized estimation
in GLMs and in the Cox model
* [penalizedLDA](http://cran.r-project.org/web/packages/penalizedLDA/index.html) - Penalized classification using Fisher's linear discriminant
* [penalizedSVM](http://cran.r-project.org/web/packages/penalizedSVM/index.html) - Feature Selection SVM using penalty functions
* [quantregForest](http://cran.r-project.org/web/packages/quantregForest/index.html) - quantregForest: Quantile Regression Forests
* [randomForest](http://cran.r-project.org/web/packages/randomForest/index.html) - randomForest: Breiman and Cutler's random forests for classification and regression.
* [randomForestSRC](http://cran.r-project.org/web/packages/randomForestSRC/index.html) - randomForestSRC: Random Forests for Survival, Regression and Classification (RF-SRC).
* [rattle](http://cran.r-project.org/web/packages/rattle/index.html) - Graphical user interface for data mining in R.
* [rda](http://cran.r-project.org/web/packages/rda/index.html) - Shrunken Centroids Regularized Discriminant Analysis
* [rdetools](http://cran.r-project.org/web/packages/rdetools/index.html) - Relevant Dimension Estimation (RDE) in Feature Spaces
* [REEMtree](http://cran.r-project.org/web/packages/REEMtree/index.html) - Regression Trees with Random Effects for Longitudinal (Panel)
Data
* [relaxo](http://cran.r-project.org/web/packages/relaxo/index.html) - Relaxed Lasso
* [rgenoud](http://cran.r-project.org/web/packages/rgenoud/index.html) - R version of GENetic Optimization Using Derivatives
* [rgp](http://cran.r-project.org/web/packages/rgp/index.html) - R genetic programming framework
* [Rmalschains](http://cran.r-project.org/web/packages/Rmalschains/index.html) - Continuous Optimization using Memetic Algorithms with Local
Search Chains (MA-LS-Chains) in R
* [rminer](http://cran.r-project.org/web/packages/rminer/index.html) - Simpler use of data mining methods (e.g. NN and SVM) in
classification and regression
* [ROCR](http://cran.r-project.org/web/packages/ROCR/index.html) - Visualizing the performance of scoring classifiers
* [RoughSets](http://cran.r-project.org/web/packages/RoughSets/index.html) - Data Analysis Using Rough Set and Fuzzy Rough Set Theories
* [rpart](http://cran.r-project.org/web/packages/rpart/index.html) - Recursive Partitioning and Regression Trees
* [RPMM](http://cran.r-project.org/web/packages/RPMM/index.html) - Recursively Partitioned Mixture Model
* [RSNNS](http://cran.r-project.org/web/packages/RSNNS/index.html) - Neural Networks in R using the Stuttgart Neural Network
Simulator (SNNS)
* [Rsomoclu](https://cran.r-project.org/web/packages/Rsomoclu/index.html) - Parallel implementation of self-organizing maps.
* [RWeka](http://cran.r-project.org/web/packages/RWeka/index.html) - R/Weka interface
* [RXshrink](http://cran.r-project.org/web/packages/RXshrink/index.html) - RXshrink: Maximum Likelihood Shrinkage via Generalized Ridge or Least
Angle Regression
* [sda](http://cran.r-project.org/web/packages/sda/index.html) - Shrinkage Discriminant Analysis and CAT Score Variable Selection
* [SDDA](http://cran.r-project.org/web/packages/SDDA/index.html) - Stepwise Diagonal Discriminant Analysis
* [SuperLearner](https://github.com/ecpolley/SuperLearner) and [subsemble](http://cran.r-project.org/web/packages/subsemble/index.html) - Multi-algorithm ensemble learning packages.
* [svmpath](http://cran.r-project.org/web/packages/svmpath/index.html) - svmpath: the SVM Path algorithm
* [tgp](http://cran.r-project.org/web/packages/tgp/index.html) - Bayesian treed Gaussian process models
* [tree](http://cran.r-project.org/web/packages/tree/index.html) - Classification and regression trees
* [varSelRF](http://cran.r-project.org/web/packages/varSelRF/index.html) - Variable selection using random forests
* [xgboost <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/tqchen/xgboost/tree/master/R-package) - eXtreme Gradient Boosting Tree model, well known for its speed and performance.

## Natural Language Processing
*Packages for Natural Language Processing.*

* [text2vec](https://github.com/dselivanov/text2vec) - Fast Text Mining Framework for Vectorization and Word Embeddings. :star:434
* [tm](http://cran.r-project.org/web/packages/tm/index.html) - A comprehensive text mining framework for R.
* [openNLP](http://cran.r-project.org/web/packages/openNLP/index.html) - Apache OpenNLP Tools Interface.
* [koRpus](http://cran.r-project.org/web/packages/koRpus/index.html) - An R Package for Text Analysis.
* [zipfR](http://cran.r-project.org/web/packages/zipfR/index.html) - Statistical models for word frequency distributions.
* [NLP](http://cran.r-project.org/web/packages/NLP/index.html) - Basic functions for Natural Language Processing.
* [LDAvis](https://github.com/cpsievert/LDAvis) - Interactive visualization of topic models. :star:304
* [topicmodels](https://cran.r-project.org/web/packages/topicmodels/index.html) - Topic modeling interface to the C code developed by by David M. Blei for Topic Modeling (Latent Dirichlet Allocation (LDA), and Correlated Topics Models (CTM)).
* [syuzhet](https://cran.r-project.org/web/packages/syuzhet/index.html) - Extracts sentiment from text using three different sentiment dictionaries.
* [SnowballC](https://cran.rstudio.com/web/packages/SnowballC/index.html) - Snowball stemmers based on the C libstemmer UTF-8 library.
* [quanteda](https://github.com/kbenoit/quanteda) - R functions for Quantitative Analysis of Textual Data. :star:336
* [Topic Models Resources](https://github.com/trinker/topicmodels_learning) - Topic Models learning and R related resources. :star:140
* [NLP for <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f1e8-1f1f3.png" width="20" heigth="20" align="absmiddle" class="emoji" alt=":cn:">](https://github.com/BZRLC/R-notes/blob/master/NLP/readme.md) - NLP related resources in R. @Chinese
* [MonkeyLearn](https://github.com/masalmon/monkeylearn) - 🐒 R package for text analysis with Monkeylearn 🐒. :star:75
* [tidytext](http://tidytextmining.com/index.html) - Implementing tidy principles of Hadley Wickham to text mining.
* [utf8](https://github.com/patperry/r-utf8) - Manipulating and printing UTF-8 text that fixes multiple bugs in R's UTF-8 handling. :star:68

## Bayesian
*Packages for Bayesian Inference.*

* [coda](http://cran.r-project.org/web/packages/coda/index.html) - Output analysis and diagnostics for MCMC.
* [mcmc](http://cran.r-project.org/web/packages/mcmc/index.html) - Markov Chain Monte Carlo.
* [MCMCpack](http://mcmcpack.berkeley.edu/) - Markov chain Monte Carlo (MCMC) Package.
* [R2WinBUGS](http://cran.r-project.org/web/packages/R2WinBUGS/index.html) - Running WinBUGS and OpenBUGS from R / S-PLUS.
* [BRugs](http://cran.r-project.org/web/packages/BRugs/index.html) - R interface to the OpenBUGS MCMC software.
* [rjags](http://cran.r-project.org/web/packages/rjags/index.html) - R interface to the JAGS MCMC library.
* [rstan <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://mc-stan.org/interfaces/rstan.html) - R interface to the Stan MCMC software.

## Optimization
*Packages for Optimization.*

* [lpSolve](https://cran.rstudio.com/web/packages/lpSolve/index.html) - Interface to `Lp_solve` to Solve Linear/Integer Programs.
* [minqa](https://cran.rstudio.com/web/packages/minqa/index.html) - Derivative-free optimization algorithms by quadratic approximation.
* [nloptr](https://cran.rstudio.com/web/packages/nloptr/index.html) - NLopt is a free/open-source library for nonlinear optimization.
* [ompr](https://cran.rstudio.com/web/packages/ompr/index.html) - Model mixed integer linear programs in an algebraic way directly in R.
* [Rglpk](https://cran.rstudio.com/web/packages/Rglpk/index.html) - R/GNU Linear Programming Kit Interface
* [ROI](https://cran.rstudio.com/web/packages/ROI/index.html) - The R Optimization Infrastructure ('ROI') is a sophisticated framework for handling optimization problems in R.

## Finance
*Packages for dealing with money.*

* [quantmod <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://www.quantmod.com/) - Quantitative Financial Modelling & Trading Framework for R.
* [TTR](http://cran.r-project.org/web/packages/TTR/index.html) - Functions and data to construct technical trading rules with R.
* [PerformanceAnalytics](http://cran.r-project.org/web/packages/PerformanceAnalytics/index.html) - Econometric tools for performance and risk analysis.
* [zoo <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://cran.r-project.org/web/packages/zoo/index.html) - S3 Infrastructure for Regular and Irregular Time Series.
* [xts](http://cran.r-project.org/web/packages/xts/index.html) - eXtensible Time Series.
* [tseries](http://cran.r-project.org/web/packages/tseries/index.html) - Time series analysis and computational finance.
* [fAssets](http://cran.r-project.org/web/packages/fAssets/index.html) - Analysing and Modelling Financial Assets.

## Bioinformatics
*Packages for processing biological datasets.*

* [Bioconductor <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://www.bioconductor.org/) - Tools for the analysis and comprehension of high-throughput genomic data.
* [genetics](http://cran.r-project.org/web/packages/genetics/index.html) - Classes and methods for handling genetic data.
* [gap](http://cran.r-project.org/web/packages/gap/index.html) - An integrated package for genetic data analysis of both population and family data.
* [ape](http://cran.r-project.org/web/packages/ape/index.html) - Analyses of Phylogenetics and Evolution.
* [pheatmap](http://cran.r-project.org/web/packages/pheatmap/index.html) - Pretty heatmaps made easy.


## Network Analysis
*Packages to construct, analyze and visualize network data.*

* [Network Analysis List](https://github.com/briatte/awesome-network-analysis) - Network Analysis related resources. :star:867
* [igraph <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://igraph.org/r/) - A collection of network analysis tools.
* [network](https://cran.r-project.org/web/packages/network/index.html) - Basic tools to manipulate relational data in R.
* [sna](https://cran.r-project.org/web/packages/sna/index.html) - Basic network measures and visualization tools.
* [netdiffuseR](https://github.com/USCCANA/netdiffuseR) - Tools for Analysis of Network Diffusion. :star:22
* [networkDynamic](https://cran.r-project.org/web/packages/networkDynamic/) - Support for dynamic, (inter)temporal networks.
* [ndtv](https://cran.r-project.org/web/packages/ndtv/) - Tools to construct animated visualizations of dynamic network data in various formats.
* [statnet](http://statnet.org/) - The project behind many R network analysis packages.
* [ergm](https://cran.r-project.org/web/packages/ergm/index.html) - Exponential random graph models in R.
* [latentnet](https://cran.r-project.org/web/packages/latentnet/index.html) - Latent position and cluster models for network objects.
* [tnet](https://cran.r-project.org/web/packages/tnet/index.html) - Network measures for weighted, two-mode and longitudinal networks.
* [rgexf](https://bitbucket.org/gvegayon/rgexf/wiki/Home) - Export network objects from R to [GEXF](http://gexf.net/format/), for manipulation with network software like [Gephi](https://gephi.org/) or [Sigma](http://sigmajs.org/).
* [visNetwork](https://github.com/datastorm-open/visNetwork) - Using vis.js library for network visualization. :star:210

## Spatial
*Packages to explore the earth.*

* [CRAN Task View: Analysis of Spatial Data](https://cran.r-project.org/web/views/Spatial.html)- Spatial Analysis related resources.
* [Leaflet](http://rstudio.github.io/leaflet/) - One of the most popular JavaScript libraries interactive maps.
* [ggmap](https://github.com/dkahle/ggmap) -  Plotting maps in R with ggplot2. :star:342
* [REmap](https://github.com/Lchiffon/REmap) - R interface to the JavaScript library ECharts for interactive map data visualization. :star:167
* [sp](https://edzer.github.io/sp/) - Classes and Methods for Spatial Data.
* [rgeos](https://cran.r-project.org/web/packages/rgeos/index.html) - Interface to Geometry Engine - Open Source
* [rgdal](https://cran.r-project.org/web/packages/rgdal/index.html) - Bindings for the Geospatial Data Abstraction Library
* [maptools](https://cran.r-project.org/web/packages/maptools/index.html) - Tools for Reading and Handling Spatial Objects
* [gstat](https://github.com/edzer/gstat) - Spatial and spatio-temporal geostatistical modelling, prediction and simulation. :star:33
* [spacetime](https://github.com/edzer/spacetime) - R classes and methods for spatio-temporal data. :star:25
* [RColorBrewer](https://cran.r-project.org/web/packages/RColorBrewer/index.html) - Provides color schemes for maps
* [spatstat](https://github.com/spatstat/spatstat) - Spatial Point Pattern Analysis, Model-Fitting, Simulation, Tests :star:49
* [spdep](https://cran.r-project.org/web/packages/spdep/index.html) - Spatial Dependence: Weighting Schemes, Statistics and Models
* [tigris](https://github.com/walkerke/tigris) - Download and use Census TIGER/Line shapefiles in R :star:92

## R Development
*Packages for packages.*

* [Package Development List](https://github.com/ropensci/PackageDevelopment) - R packages to improve package development. :star:32
* [devtools <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/hadley/devtools) - Tools to make an R developer's life easier. :star:1614
* [testthat <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/hadley/testthat) - An R package to make testing fun. :star:482
* [R6 <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/wch/R6) - simpler, faster, lighter-weight alternative to R's built-in classes. :star:201
* [pryr <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/hadley/pryr) - Make it easier to understand what's going on in R. :star:137
* [roxygen <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/klutometis/roxygen) - Describe your functions in comments next to their definitions. :star:257
* [lineprof](https://github.com/hadley/lineprof) - Visualise line profiling results in R. :star:93
* [packrat](https://github.com/rstudio/packrat) - Make your R projects more isolated, portable, and reproducible. :star:239
* [installr](https://github.com/talgalili/installr/) - Functions for installing softwares from within R (for Windows).
* [import](https://github.com/smbache/import/) - An import mechanism for R.
* [modules](https://github.com/klmr/modules) - An alternative (Python style) module system for R. :star:130
* [Rocker <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/rocker-org) - R configurations for [Docker](https://www.docker.com/).
* [RStudio Addins](https://github.com/daattali/rstudio-addins) - List of RStudio addins. :star:341
* [drat](https://github.com/eddelbuettel/drat) - Creation and use of R repositories on GitHub or other repos. :star:76
* [covr](https://github.com/jimhester/covr) - Test coverage for your R package and (optionally) upload the results to [coveralls](https://coveralls.io/) or [codecov](https://codecov.io/). :star:187
* [lintr](https://github.com/jimhester/lintr) - Static code analysis for R to enforce code style. :star:413
* [staticdocs](https://github.com/hadley/staticdocs) - Generate static html documentation for an R package. :star:293

## Logging
*Packages for Logging*

* [futile.logger](https://github.com/zatonovo/futile.logger) - A logging package in R similar to log4j :star:93
* [log4r](https://github.com/johnmyleswhite/log4r) - A log4j derivative for R :star:43
* [logging](https://cran.r-project.org/web/packages/logging/index.html) - A logging package emulating the python logging package.

## Data Packages
*Handy Data Packages*

* [engsoccerdata](https://github.com/jalapic/engsoccerdata) - English and European soccer results 1871-2016. :star:310
* [gapminder](http://github.com/jennybc/gapminder) - Excerpt from the Gapminder dataset (data about countries throught the past 50 years). :star:99

## Other Tools
*Handy Tools for R*

* [git2r](https://github.com/ropensci/git2r) - Gives you programmatic access to Git repositories from R. :star:118

## Other Interpreters
*Alternative R engines.*

* [CXXR](https://www.cs.kent.ac.uk/projects/cxxr/) - Refactorising R into C++.
* [fastR](https://bitbucket.org/allr/fastr/wiki/Home) - FastR is an implementation of the R Language in Java atop Truffle and Graal.
* [pqR](http://www.pqr-project.org/) - a "pretty quick" implementation of R
* [renjin](http://www.renjin.org/) - a JVM-based interpreter for R.
* [rho](https://github.com/rho-devel/rho) - Refactor the interpreter of the R language into a fully-compatible, efficient, VM for R. :star:128
* [riposte](https://github.com/jtalbot/riposte) - a fast interpreter and JIT for R. :star:78
* [TERR](http://spotfire.tibco.com/discover-spotfire/what-does-spotfire-do/predictive-analytics/tibco-enterprise-runtime-for-r-terr) - TIBCO Enterprise Runtime for R.


## Learning R
*Packages for Learning R.*

* [swirl <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://swirlstats.com/) - An interactive R tutorial directly in your R console.
* [DataScienceR <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/ujjwalkarn/DataScienceR) - a list of R tutorials for Data Science, NLP and Machine Learning. :star:984

# Resources

Where to discover new R-esources.

## Websites

* [R-project](http://www.r-project.org/) - The R Project for Statistical Computing.
* [R Weekly](https://rweekly.org) - Weekly updates about R and Data Science. R Weekly is openly developed on GitHub.
* [R Bloggers](http://www.r-bloggers.com/) - There are people scattered across the Web who blog about R. This is simply an aggregator of many of those feeds.
* [DataCamp](https://www.datacamp.com/) - Learn R data analytics online.
* [Quick-R](http://www.statmethods.net/) - An excellent quick reference.
* [Advanced R <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](http://adv-r.had.co.nz/) - An online version of the Advanced R book.
* [Efficient R Programming](https://csgillespie.github.io/efficientR/) - An online home of the O’Reilly book: Efficient R Programming.
* [CRAN Task Views](http://cran.r-project.org/web/views/) - Task Views for CRAN packages.
* [The R Programming Wikibook](https://en.wikibooks.org/wiki/R_Programming) - A collaborative handbook for R.
* [R-users](https://www.r-users.com/) - A job board for R users (and the people who are looking to hire them)
* [R Cookbook](http://www.cookbook-r.com/) - A problem-oriented website that supports the [R Graphics Cookbook](http://shop.oreilly.com/product/0636920023135.do).
* [tryR](http://tryr.codeschool.com/) - A quick course for getting started with R.
* [RDocumentation](https://www.rdocumentation.org/) - Search through all CRAN, Bioconductor, Github packages and their archives with RDocumentation.

## Books

* [R Books List](https://github.com/RomanTsegelskyi/rbooks) - List of R Books. :star:89
* [The Art of R Programming](http://shop.oreilly.com/product/9781593273842.do) - It's a good resource for systematically learning fundamentals such as types of objects, control statements, variable scope, classes and debugging in R.
* [Free Books](https://cran.r-project.org/other-docs.html) - CRAN Contributed Documentation in many languages.
* [R Cookbook](http://shop.oreilly.com/product/9780596809164.do) - A quick and simple introduction to conducting many common statistical tasks with R.
* Books written as part of the Johns Hopkins Data Science Specialization:
  * [Exploratory Data Analysis with R](https://leanpub.com/exdata) - Basic analytical skills for all sorts of data in R.
  * [R Programming for Data Science](https://leanpub.com/rprogramming) - More advanced data analysis that relies on R programming.
  * [Report Writing for Data Science in R](https://leanpub.com/reportwriting) - R-based methods for reproducible research and report generation.
* [R Packages](http://r-pkgs.had.co.nz/) - A book (in paper and website formats) on writing R packages.
* [R in Action](http://www.manning.com/kabacoff2/) - This book aims at all levels of users, with sections for beginning, intermediate and advanced R ranging from "Exploring R data structures" to running regressions and conducting factor analyses.
* [Use R!](http://www.springer.com/series/6991?detailsPage=titles) - This series of inexpensive and focused books from Springer publish shorter books aimed at practitioners. Books can discuss the use of R in a particular subject area, such as Bayesian networks, ggplot2 and Rcpp.
* [R for SAS and SPSS users](http://r4stats.com/books/free-version/) - An excelllent resource for users already familiar with SAS or SPSS.
* [An Introduction to R](https://cran.r-project.org/doc/manuals/R-intro.pdf) - A very good introductory text on R, also covers some advanced topics.
* [Introduction to Statistical Learning with Application in R](http://www-bcf.usc.edu/~gareth/ISL/) - A simplified and "operational" version of *The Elements of Statistical Learning*. Free softcopy provided by its authors.
* [The R Inferno](http://www.burns-stat.com/pages/Tutor/R_inferno.pdf) - Patrick Burns gives insight into R's ins and outs along with its quirks!
* [R for Data Science](http://r4ds.had.co.nz/) - Free book from RStudio developers with emphasis on data science workflow.
* [Learning R Programming](https://www.packtpub.com/big-data-and-business-intelligence/learning-r-programming) - Learning R as a programming language from basics to advanced topics.
* [Data Munging with R](https://www.manning.com/books/data-munging-with-r) - A gentle introduction to data processing and programming in R, for beginners moving beyond spreadsheets.

## Podcasts

* [Not So Standard Deviations](https://soundcloud.com/nssd-podcast) - The Data Science Podcast.
  * [@Roger Peng](https://twitter.com/rdpeng) and [@Hilary Parker](https://twitter.com/hspter).
* [R World News](http://www.rworld.news/blog/) - R World News helps you keep up with happenings within the R community.
  * [@Bob Rudis](https://twitter.com/hrbrmstr) and [@Jay Jacobs](https://twitter.com/jayjacobs).
* [The R-Podcast](https://r-podcast.org/) - Giving practical advice on how to use R.
  * [@Eric Nantz](https://r-podcast.org/stories/contact.html).
* [R Talk](http://rtalk.org) - News and discussions of statistical software and language R.
  * [@Oliver Keyes](https://twitter.com/quominus), [@Jasmine Dumas](https://twitter.com/jasdumas), [@Ted Hart](https://twitter.com/emhrt_) and [@Mikhail Popov](https://twitter.com/bearloga).
* [R Weekly](https://rweekly.org) - Weekly news updates about the R community.

## Reference Cards

* [R Reference Card 2.0](http://cran.r-project.org/doc/contrib/Baggott-refcard-v2.pdf) - Material from R for Beginners by permission of Emmanuel Paradis (Version 2 by Matt Baggott).
* [Regression Analysis Refcard](http://cran.r-project.org/doc/contrib/Ricci-refcard-regression.pdf) - R Reference Card for Regression Analysis.
* [Reference Card for ESS](http://ess.r-project.org/refcard.pdf) - Reference Card for ESS.
* [R Markdown Cheat sheet](http://shiny.rstudio.com/images/rm-cheatsheet.pdf.zip) - Quick reference guide for writing reports with R Markdown.
* [Shiny Cheat sheet](http://shiny.rstudio.com/images/cheatsheet.pdf.zip) - Quick reference guide for building Shiny apps.
* [ggplot2 Cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/08/ggplot2-cheatsheet.pdf) - Quick reference guide for data visualisation with ggplot2.
* [devtools Cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/06/devtools-cheatsheet.pdf) - Quick reference guide to package development in R.

## MOOCs
*Massive open online courses.*

* [The Analytics Edge](https://www.edx.org/course/analytics-edge-mitx-15-071x-0) - Hands-on introduction to data analysis with R from MITx.
* [Johns Hopkins University Data Science Specialization](https://www.coursera.org/specialization/jhudatascience/1) - 9 courses including: Introduction to R, literate analysis tools, Shiny and some more.
* [HarvardX Biomedical Data Science](http://simplystatistics.org/2014/11/25/harvardx-biomedical-data-science-open-online-training-curriculum-launches-on-january-19/) - Introduction to R for the Life Sciences.
* [Explore Statistics with R](https://www.edx.org/course/explore-statistics-r-kix-kiexplorx-0) - Covers introduction, data handling and statistical analysis in R.

## Lists
*Great resources for learning domain knowledge.*

* [Books](https://github.com/RomanTsegelskyi/rbooks) - List of R Books. :star:89
* [DataScienceR <img class="emoji" alt="heart" src="https://awesome-r.com/heart.png" height="20" align="absmiddle" width="20">](https://github.com/ujjwalkarn/DataScienceR) - a list of R tutorials for Data Science, NLP and Machine Learning. :star:984
* [ggplot2 Extensions](https://ggplot2-exts.github.io/ggiraph.html) - Showcases of ggplot2 extensions.
* [Natural Language Processing <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f1e8-1f1f3.png" width="20" heigth="20" align="absmiddle" class="emoji" alt=":cn:">](https://github.com/BZRLC/R-notes/blob/master/NLP/readme.md) - NLP related resources in R. @Chinese
* [Network Analysis](https://github.com/briatte/awesome-network-analysis) - Network Analysis related resources. :star:867
* [Open Data](https://github.com/ropensci/opendata) - Using R to obtain, parse, manipulate, create, and share open data. :star:123
* [Posts](https://github.com/qinwf/awesome-R/blob/master/posts.md) - Great R blog posts or Rticles.
* [Package Development](https://github.com/ropensci/PackageDevelopment) - R packages to improve package development. :star:32
* [R Project Conferences](https://www.r-project.org/conferences.html) -  Information about useR! Conferences and DSC Conferences.
* [RStartHere](https://github.com/rstudio/RStartHere) - A guide to some of the most useful R packages, organized by workflow. :star:406
* [RStudio Addins](https://github.com/daattali/addinslist) - List of RStudio addins. :star:341
* [Topic Models](https://github.com/trinker/topicmodels_learning) - Topic Models learning and R related resources. :star:140
* [Web Technologies](https://github.com/ropensci/webservices) - Information about how to use R and the world wide web together. :star:139

# Other Awesome Lists

* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)
* [lists](https://github.com/jnv/lists)
* [awesome-rshiny](https://github.com/grabear/awesome-rshiny)

# Contributing
Your contributions are always welcome!

This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License - [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)


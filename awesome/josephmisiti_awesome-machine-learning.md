# Information comes from [josephmisiti/awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)
# Awesome Machine Learning [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome machine learning frameworks, libraries and software (by language). Inspired by `awesome-php`.

If you want to contribute to this list (please do), send me a pull request or contact me [@josephmisiti](https://twitter.com/josephmisiti).
Also, a listed repository should be deprecated if:

* Repository's owner explicitly say that "this library is not maintained".
* Not committed for long time (2~3 years).

Further resources:

* For a list of free machine learning books available for download, go [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/books.md).

* For a list of (mostly) free machine learning courses available online, go [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/courses.md).

* For a list of blogs on data science and  machine learning, go [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/blogs.md).

* For a list of free-to-attend meetups and local events, go [here](https://github.com/josephmisiti/awesome-machine-learning/blob/master/meetups.md).

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [APL](#apl)
    - [General-Purpose Machine Learning](#apl-general-purpose)
- [C](#c)
    - [General-Purpose Machine Learning](#c-general-purpose)
    - [Computer Vision](#c-cv)
- [C++](#cpp)
    - [Computer Vision](#cpp-cv)
    - [General-Purpose Machine Learning](#cpp-general-purpose)
    - [Natural Language Processing](#cpp-nlp)
    - [Speech Recognition](#speech-recognition-1)
    - [Sequence Analysis](#cpp-sequence)
    - [Gesture Recognition](#cpp-gestures)
- [Common Lisp](#common-lisp)
    - [General-Purpose Machine Learning](#common-lisp-general-purpose)
- [Clojure](#clojure)
    - [Natural Language Processing](#clojure-nlp)
    - [General-Purpose Machine Learning](#clojure-general-purpose)
    - [Data Analysis / Data Visualization](#clojure-data-analysis)
- [Crystal](#crystal)
    - [General-Purpose Machine Learning](#crystal-general-purpose)
- [Elixir](#elixir)
    - [General-Purpose Machine Learning](#elixir-general-purpose)
    - [Natural Language Processing](#elixir-nlp)
- [Erlang](#erlang)
    - [General-Purpose Machine Learning](#erlang-general-purpose)
- [Go](#go)
    - [Natural Language Processing](#go-nlp)
    - [General-Purpose Machine Learning](#go-general-purpose)
    - [Data Analysis / Data Visualization](#go-data-analysis)
    - [Facial Detection and Recognition](#go-facial-recognition)
    - [Image Classification](#go-image-classification)
- [Haskell](#haskell)
    - [General-Purpose Machine Learning](#haskell-general-purpose)
- [Java](#java)
    - [Natural Language Processing](#java-nlp)
    - [General-Purpose Machine Learning](#java-general-purpose)
    - [Data Analysis / Data Visualization](#java-data-analysis)
    - [Deep Learning](#java-deep-learning)
- [Javascript](#javascript)
    - [Natural Language Processing](#javascript-nlp)
    - [Data Analysis / Data Visualization](#javascript-data-analysis)
    - [General-Purpose Machine Learning](#javascript-general-purpose)
    - [Misc](#javascript-misc)
- [Julia](#julia)
    - [General-Purpose Machine Learning](#julia-general-purpose)
    - [Natural Language Processing](#julia-nlp)
    - [Data Analysis / Data Visualization](#julia-data-analysis)
    - [Misc Stuff / Presentations](#julia-misc)
- [Lua](#lua)
    - [General-Purpose Machine Learning](#lua-general-purpose)
    - [Demos and Scripts](#lua-demos)
- [Matlab](#matlab)
    - [Computer Vision](#matlab-cv)
    - [Natural Language Processing](#matlab-nlp)
    - [General-Purpose Machine Learning](#matlab-general-purpose)
    - [Data Analysis / Data Visualization](#matlab-data-analysis)
- [.NET](#net)
    - [Computer Vision](#net-cv)
    - [Natural Language Processing](#net-nlp)
    - [General-Purpose Machine Learning](#net-general-purpose)
    - [Data Analysis / Data Visualization](#net-data-analysis)
- [Objective C](#objectivec)
    - [General-Purpose Machine Learning](#objectivec-general-purpose)
- [OCaml](#ocaml)
    - [General-Purpose Machine Learning](#ocaml-general-purpose)
- [Perl](#perl)
    - [Data Analysis / Data Visualization](#perl-data)
	- [General-Purpose Machine Learning](#perl-ml)
- [Perl 6](#perl6)
- [PHP](#php)
    - [Natural Language Processing](#php-nlp)
    - [General-Purpose Machine Learning](#php-general-purpose)
- [Python](#python)
    - [Computer Vision](#python-cv)
    - [Natural Language Processing](#python-nlp)
    - [General-Purpose Machine Learning](#python-general-purpose)
    - [Data Analysis / Data Visualization](#python-data-analysis)
    - [Misc Scripts / iPython Notebooks / Codebases](#python-misc)
    - [Kaggle Competition Source Code](#python-kaggle)
    - [Neural Networks](#python-neural-networks)
    - [Reinforcement Learning](#python-reinforcement-learning)
- [Ruby](#ruby)
    - [Natural Language Processing](#ruby-nlp)
    - [General-Purpose Machine Learning](#ruby-general-purpose)
    - [Data Analysis / Data Visualization](#ruby-data-analysis)
    - [Misc](#ruby-misc)
- [Rust](#rust)
    - [General-Purpose Machine Learning](#rust-general-purpose)
- [R](#r)
    - [General-Purpose Machine Learning](#r-general-purpose)
    - [Data Analysis / Data Visualization](#r-data-analysis)
- [SAS](#sas)
    - [General-Purpose Machine Learning](#sas-general-purpose)
    - [Data Analysis / Data Visualization](#sas-data-analysis)
    - [High Performance Machine Learning (MPP)](#sas-mpp)
    - [Natural Language Processing](#sas-nlp)
    - [Demos and Scripts](#sas-demos)
- [Scala](#scala)
    - [Natural Language Processing](#scala-nlp)
    - [Data Analysis / Data Visualization](#scala-data-analysis)
    - [General-Purpose Machine Learning](#scala-general-purpose)
- [Swift](#swift)
    - [General-Purpose Machine Learning](#swift-general-purpose)
- [TensorFlow](#tensor)
    - [General-Purpose Machine Learning](#tensor-general-purpose)
- [Credits](#credits)

<!-- /MarkdownTOC -->

<a name="apl"></a>
## APL

<a name="apl-general-purpose"></a>
#### General-Purpose Machine Learning
* [naive-apl](https://github.com/mattcunningham/naive-apl) - Naive Bayesian Classifier implementation in APL. :star:15

<a name="c"></a>
## C

<a name="c-general-purpose"></a>
#### General-Purpose Machine Learning
* [Darknet](https://github.com/pjreddie/darknet) - Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation. :star:7415
* [Recommender](https://github.com/GHamrouni/Recommender) - A C library for product recommendations/suggestions using collaborative filtering (CF). :star:168
* [Hybrid Recommender System](https://github.com/SeniorSA/hybrid-rs-trainner) - A hybrid recommender system based upon scikit-learn algorithms. :star:7
* [neonrvm](https://github.com/siavashserver/neonrvm) - neonrvm is an open source machine learning library based on RVM technique. It's written in C programming language and comes with Python programming language bindings. :star:6

<a name="c-cv"></a>
#### Computer Vision

* [CCV](https://github.com/liuliu/ccv) - C-based/Cached/Core Computer Vision Library, A Modern Computer Vision Library. :star:6158
* [VLFeat](http://www.vlfeat.org/) - VLFeat is an open and portable library of computer vision algorithms, which has Matlab toolbox.

### Speech Recognition
* [HTK](http://htk.eng.cam.ac.uk/) -The Hidden Markov Model Toolkit (HTK) is a portable toolkit for building and manipulating hidden Markov models.

<a name="cpp"></a>
## C++

<a name="cpp-cv"></a>
#### Computer Vision

* [DLib](http://dlib.net/imaging.html) - DLib has C++ and Python interfaces for face detection and training general object detectors.
* [EBLearn](http://eblearn.sourceforge.net/) - Eblearn is an object-oriented C++ library that implements various machine learning models
* [OpenCV](http://opencv.org) - OpenCV has C++, C, Python, Java and MATLAB interfaces and supports Windows, Linux, Android and Mac OS.
* [VIGRA](https://github.com/ukoethe/vigra) - VIGRA is a generic cross-platform C++ computer vision and machine learning library for volumes of arbitrary dimensionality with Python bindings. :star:266

<a name="cpp-general-purpose"></a>
#### General-Purpose Machine Learning

* [BanditLib](https://github.com/jkomiyama/banditlib) - A simple Multi-armed Bandit library. :star:91
* [Caffe](http://caffe.berkeleyvision.org)  - A deep learning framework developed with cleanliness, readability, and speed in mind. [DEEP LEARNING]
* [CatBoost](https://github.com/catboost/catboost) - General purpose gradient boosting on decision trees library with categorical features support out of the box. It is easy to install, contains fast inference implementation and supports CPU and GPU (even multi-GPU) computation. :star:2697
* [CNTK](https://github.com/Microsoft/CNTK) - The Computational Network Toolkit (CNTK) by Microsoft Research, is a unified deep-learning toolkit that describes neural networks as a series of computational steps via a directed graph. :star:14308
* [CUDA](https://code.google.com/p/cuda-convnet/) - This is a fast C++/CUDA implementation of convolutional [DEEP LEARNING]
* [CXXNET](https://github.com/antinucleon/cxxnet) - Yet another deep learning framework with less than 1000 lines core code [DEEP LEARNING] :star:1033
* [DeepDetect](https://github.com/beniz/deepdetect) - A machine learning API and server written in C++11. It makes state of the art machine learning easy to work with and integrate into existing applications. :star:1514
* [Distributed Machine learning Tool Kit (DMTK)](http://www.dmtk.io/) - A distributed machine learning (parameter server) framework by Microsoft. Enables training models on large data sets across multiple machines. Current tools bundled with it include: LightLDA and Distributed (Multisense) Word Embedding.
* [DLib](http://dlib.net/ml.html) - A suite of ML tools designed to be easy to imbed in other applications.
* [DSSTNE](https://github.com/amznlabs/amazon-dsstne) - A software library created by Amazon for training and deploying deep neural networks using GPUs which emphasizes speed and scale over experimental flexibility. :star:4096
* [DyNet](https://github.com/clab/dynet) - A dynamic neural network library working well with networks that have dynamic structures that change for every training instance. Written in C++ with bindings in Python. :star:2243
* [encog-cpp](https://code.google.com/archive/p/encog-cpp)
* [Fido](https://github.com/FidoProject/Fido) - A highly-modular C++ machine learning library for embedded electronics and robotics. :star:356
* [igraph](http://igraph.org/c/) - General purpose graph library.
* [Intel(R) DAAL](https://github.com/01org/daal) - A high performance software library developed by Intel and optimized for Intel's architectures. Library provides algorithmic building blocks for all stages of data analytics and allows to process data in batch, online and distributed modes. :star:198
* [LightGBM](https://github.com/Microsoft/LightGBM) - Microsoft's fast, distributed, high performance gradient boosting (GBDT, GBRT, GBM or MART) framework based on decision tree algorithms, used for ranking, classification and many other machine learning tasks. :star:5330
* [libfm](http://www.libfm.org/) - A generic approach that allows to mimic most factorization models by feature engineering.
* [MLDB](https://mldb.ai) - The Machine Learning Database is a database designed for machine learning. Send it commands over a RESTful API to store data, explore it using SQL, then train machine learning models and expose them as APIs.
* [mlpack](http://www.mlpack.org/) - A scalable C++ machine learning library.
* [proNet-core](https://github.com/cnclabs/proNet-core) - A general-purpose network embedding framework: pair-wise representations optimization Network Edit. :star:53
* [ROOT](https://root.cern.ch) - A modular scientific software framework. It provides all the functionalities needed to deal with big data processing, statistical analysis, visualization and storage.
* [shark](http://image.diku.dk/shark/sphinx_pages/build/html/index.html) - A fast, modular, feature-rich open-source C++ machine learning library.
* [Shogun](https://github.com/shogun-toolbox/shogun) - The Shogun Machine Learning Toolbox. :star:2084
* [sofia-ml](https://code.google.com/archive/p/sofia-ml) - Suite of fast incremental algorithms.
* [Stan](http://mc-stan.org/) - A probabilistic programming language implementing full Bayesian statistical inference with Hamiltonian Monte Carlo sampling.
* [Timbl](https://languagemachines.github.io/timbl/) - A software package/C++ library implementing several memory-based learning algorithms, among which IB1-IG, an implementation of k-nearest neighbor classification, and IGTree, a decision-tree approximation of IB1-IG. Commonly used for NLP.
* [Vowpal Wabbit (VW)](https://github.com/JohnLangford/vowpal_wabbit/wiki) - A fast out-of-core learning system.
* [Warp-CTC](https://github.com/baidu-research/warp-ctc) - A fast parallel implementation of Connectionist Temporal Classification (CTC), on both CPU and GPU. :star:3190
* [XGBoost](https://github.com/dmlc/xgboost) - A parallelized optimized general purpose gradient boosting library. :star:11750
* [LKYDeepNN](https://github.com/mosdeo/LKYDeepNN) -  A header-only C++11 Neural Network library. Low dependency, native traditional chinese document. :star:9

<a name="cpp-nlp"></a>
#### Natural Language Processing

* [BLLIP Parser](https://github.com/BLLIP/bllip-parser) - BLLIP Natural Language Parser (also known as the Charniak-Johnson parser). :star:159
* [colibri-core](https://github.com/proycon/colibri-core) - C++ library, command line tools, and Python binding for extracting and working with basic linguistic constructions such as n-grams and skipgrams in a quick and memory-efficient way. :star:75
* [CRF++](https://taku910.github.io/crfpp/) - Open source implementation of Conditional Random Fields (CRFs) for segmenting/labeling sequential data & other Natural Language Processing tasks.
* [CRFsuite](http://www.chokkan.org/software/crfsuite/) - CRFsuite is an implementation of Conditional Random Fields (CRFs) for labeling sequential data.
* [frog](https://github.com/LanguageMachines/frog) - Memory-based NLP suite developed for Dutch: PoS tagger, lemmatiser, dependency parser, NER, shallow parser, morphological analyzer. :star:34
* [libfolia](https://github.com/LanguageMachines/libfolia) - C++ library for the [FoLiA format](http://proycon.github.io/folia/)
* [MeTA](https://github.com/meta-toolkit/meta) - [MeTA : ModErn Text Analysis](https://meta-toolkit.org/) is a C++ Data Sciences Toolkit that facilitates mining big text data. :star:423
* [MIT Information Extraction Toolkit](https://github.com/mit-nlp/MITIE) - C, C++, and Python tools for named entity recognition and relation extraction :star:1800
* [ucto](https://github.com/LanguageMachines/ucto) - Unicode-aware regular-expression based tokenizer for various languages. Tool and C++ library. Supports FoLiA format. :star:31

#### Speech Recognition
* [Kaldi](https://github.com/kaldi-asr/kaldi) - Kaldi is a toolkit for speech recognition written in C++ and licensed under the Apache License v2.0. Kaldi is intended for use by speech recognition researchers. :star:3587

<a name="cpp-sequence"></a>
#### Sequence Analysis
* [ToPS](https://github.com/ayoshiaki/tops) - This is an objected-oriented framework that facilitates the integration of probabilistic models for sequences over a user defined alphabet. :star:30

<a name="cpp-gestures"></a>
#### Gesture Detection
* [grt](https://github.com/nickgillian/grt) - The Gesture Recognition Toolkit (GRT) is a cross-platform, open-source, C++ machine learning library designed for real-time gesture recognition. :star:516

<a name="common-lisp"></a>
## Common Lisp

<a name="common-lisp-general-purpose"></a>
#### General-Purpose Machine Learning

* [mgl](https://github.com/melisgl/mgl/) - Neural networks  (boltzmann machines, feed-forward and recurrent nets), Gaussian Processes.
* [mgl-gpr](https://github.com/melisgl/mgl-gpr/) - Evolutionary algorithms.
* [cl-libsvm](https://github.com/melisgl/cl-libsvm/) - Wrapper for the libsvm support vector machine library.
* [cl-online-learning](https://github.com/masatoi/cl-online-learning) - Online learning algorithms (Perceptron, AROW, SCW, Logistic Regression). :star:31
* [cl-random-forest](https://github.com/masatoi/cl-random-forest) - Implementation of Random Forest in Common Lisp. :star:24

<a name="clojure"></a>
## Clojure

<a name="clojure-nlp"></a>
#### Natural Language Processing

* [Clojure-openNLP](https://github.com/dakrone/clojure-opennlp) - Natural Language Processing in Clojure (opennlp). :star:653
* [Infections-clj](https://github.com/r0man/inflections-clj) - Rails-like inflection library for Clojure and ClojureScript. :star:158

<a name="clojure-general-purpose"></a>
#### General-Purpose Machine Learning

* [Touchstone](https://github.com/ptaoussanis/touchstone) - Clojure A/B testing library. :star:117
* [Clojush](https://github.com/lspector/Clojush) -  The Push programming language and the PushGP genetic programming system implemented in Clojure. :star:233
* [Infer](https://github.com/aria42/infer) - Inference and machine learning in Clojure. :star:171
* [Clj-ML](https://github.com/antoniogarrote/clj-ml) - A machine learning library for Clojure built on top of Weka and friends. :star:138
* [DL4CLJ](https://github.com/engagor/dl4clj/) - Clojure wrapper for Deeplearning4j. :star:79
* [Encog](https://github.com/jimpil/enclog) - Clojure wrapper for Encog (v3) (Machine-Learning framework that specializes in neural-nets). :star:139
* [Fungp](https://github.com/vollmerm/fungp) - A genetic programming library for Clojure. :star:98
* [Statistiker](https://github.com/clojurewerkz/statistiker) - Basic Machine Learning algorithms in Clojure. :star:53
* [clortex](https://github.com/htm-community/clortex) - General Machine Learning library using Numenta’s Cortical Learning Algorithm. :star:167
* [comportex](https://github.com/htm-community/comportex) - Functionally composable Machine Learning library using Numenta’s Cortical Learning Algorithm. :star:136
* [cortex](https://github.com/thinktopic/cortex) - Neural networks, regression and feature learning in Clojure. :star:1018
* [lambda-ml](https://github.com/cloudkj/lambda-ml) - Simple, concise implementations of machine learning techniques and utilities in Clojure. :star:38

<a name="clojure-data-analysis"></a>
#### Data Analysis / Data Visualization

* [Incanter](http://incanter.org/) - Incanter is a Clojure-based, R-like platform for statistical computing and graphics.
* [PigPen](https://github.com/Netflix/PigPen) - Map-Reduce for Clojure. :star:480
* [Envision](https://github.com/clojurewerkz/envision) - Clojure Data Visualisation library, based on Statistiker and D3. :star:68

<a name="crystal"></a>
## Crystal

<a name="crystal-general-purpose"></a>
#### General-Purpose Machine Learning

* [machine](https://github.com/mathieulaporte/machine) - Simple machine learning algorithm. :star:25
* [crystal-fann](https://github.com/bararchy/crystal-fann) - FANN (Fast Artifical Neural Network) binding. :star:65

<a name="elixir"></a>
## Elixir

<a name="elixir-general-purpose"></a>
#### General-Purpose Machine Learning

* [Simple Bayes](https://github.com/fredwu/simple_bayes) - A Simple Bayes / Naive Bayes implementation in Elixir. :star:301

<a name="elixir-nlp"></a>
#### Natural Language Processing

* [Stemmer](https://github.com/fredwu/stemmer) - An English (Porter2) stemming implementation in Elixir. :star:115

<a name="erlang"></a>
## Erlang

<a name="erlang-general-purpose"></a>
#### General-Purpose Machine Learning

* [Disco](https://github.com/discoproject/disco/) - Map Reduce in Erlang.
* [Yanni](https://bitbucket.org/nato/yanni/overview) - ANN neural networks using Erlangs leightweight processes.

<a name="go"></a>
## Go

<a name="go-nlp"></a>
#### Natural Language Processing

* [go-porterstemmer](https://github.com/reiver/go-porterstemmer) - A native Go clean room implementation of the Porter Stemming algorithm. :star:153
* [paicehusk](https://github.com/Rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm. :star:22
* [snowball](https://github.com/tebeka/snowball) - Snowball Stemmer for Go. :star:11
* [Textbox](https://godoc.org/github.com/machinebox/sdk-go/textbox) - Natural langauge processing SDK from Machine Box
* [go-ngram](https://github.com/Lazin/go-ngram) - In-memory n-gram index with compression. :star:86
* [word-embedding](https://github.com/ynqa/word-embedding) - Word Embeddings: the full implementation of word2vec, GloVe in Go. :star:113
* [sentences](https://github.com/neurosnap/sentences) - Golang implementation of Punkt sentence tokenizer. :star:230

<a name="go-general-purpose"></a>
#### General-Purpose Machine Learning

* [gago](https://github.com/MaxHalford/gago) - Multi-population, flexible, parallel genetic algorithm. :star:459
* [Go Learn](https://github.com/sjwhitworth/golearn) - Machine Learning for Go. :star:5474
* [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang. :star:50
* [go-ml](https://github.com/alonsovidales/go_ml) - Linear / Logistic regression, Neural Networks, Collaborative Filtering and Gaussian Multivariate Distribution. :star:162
* [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang. :star:545
* [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / Golang. :star:156
* [Cloudforest](https://github.com/ryanbressler/CloudForest) - Ensembles of decision trees in Go/Golang. :star:585
* [gobrain](https://github.com/goml/gobrain) - Neural Networks written in Go. :star:243
* [GoNN](https://github.com/fxsjy/gonn) - GoNN is an implementation of Neural Network in Go Language, which includes BPNN, RBF, PCN. :star:290
* [MXNet](https://github.com/dmlc/mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more. :star:13791
* [go-mxnet-predictor](https://github.com/songtianyi/go-mxnet-predictor) - Go binding for MXNet c_predict_api to do inference with pre-trained model. :star:38
* [neat](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT). :star:39

<a name="go-data-analysis"></a>
#### Data Analysis / Data Visualization

* [go-graph](https://github.com/StepLg/go-graph) - Graph library for Go/Golang language. :star:89
* [SVGo](http://www.svgopen.org/2011/papers/34-SVGo_a_Go_Library_for_SVG_generation/) - The Go Language library for SVG generation.
* [RF](https://github.com/fxsjy/RF.go) - Random forests implementation in Go. :star:90
* [Glot](https://github.com/arafatk/glot) - Glot is a plotting library for Golang built on top of gnuplot.  :star:226

<a name="go-facial-recognition"></a>
#### Facial Detection and Recognition

* [Facebox](https://godoc.org/github.com/machinebox/sdk-go/facebox) - Facial detection and recognition SDK with one-shot teaching from Machine Box

<a name="go-image-classification"></a>
#### Image Classification

* [Tagbox](https://godoc.org/github.com/machinebox/sdk-go/tagbox) - Image classification SDK with one-shot teaching from Machine Box
* [Nudebox](https://godoc.org/github.com/machinebox/sdk-go/nudebox) - Nudity detection from Machine Box

<a name="haskell"></a>
## Haskell

<a name="haskell-general-purpose"></a>
#### General-Purpose Machine Learning
* [haskell-ml](https://github.com/ajtulloch/haskell-ml) - Haskell implementations of various ML algorithms. :star:49
* [HLearn](https://github.com/mikeizbicki/HLearn) - a suite of libraries for interpreting machine learning models according to their algebraic structure. :star:1390
* [hnn](https://wiki.haskell.org/HNN) - Haskell Neural Network library.
* [hopfield-networks](https://github.com/ajtulloch/hopfield-networks) - Hopfield Networks for unsupervised learning in Haskell. :star:15
* [caffegraph](https://github.com/ajtulloch/dnngraph) - A DSL for deep neural networks. :star:648
* [LambdaNet](https://github.com/jbarrow/LambdaNet) - Configurable Neural Networks in Haskell. :star:357

<a name="java"></a>
## Java

<a name="java-nlp"></a>
#### Natural Language Processing
* [Cortical.io](http://www.cortical.io/) - Retina: an API performing complex NLP operations (disambiguation, classification, streaming text filtering, etc...) as quickly and intuitively as the brain.
* [IRIS](https://github.com/cortical-io/Public/tree/master/iris) - [Cortical.io's](http://cortical.io) FREE NLP, Retina API Analysis Tool (written in JavaFX!) - [See the Tutorial Video](https://www.youtube.com/watch?v=CsF4pd7fGF0).
* [CoreNLP](http://nlp.stanford.edu/software/corenlp.shtml) - Stanford CoreNLP provides a set of natural language analysis tools which can take raw English language text input and give the base forms of words.
* [Stanford Parser](http://nlp.stanford.edu/software/lex-parser.shtml) - A natural language parser is a program that works out the grammatical structure of sentences.
* [Stanford POS Tagger](http://nlp.stanford.edu/software/tagger.shtml) - A Part-Of-Speech Tagger (POS Tagger).
* [Stanford Name Entity Recognizer](http://nlp.stanford.edu/software/CRF-NER.shtml) - Stanford NER is a Java implementation of a Named Entity Recognizer.
* [Stanford Word Segmenter](http://nlp.stanford.edu/software/segmenter.shtml) - Tokenization of raw text is a standard pre-processing step for many NLP tasks.
* [Tregex, Tsurgeon and Semgrex](http://nlp.stanford.edu/software/tregex.shtml) - Tregex is a utility for matching patterns in trees, based on tree relationships and regular expression matches on nodes (the name is short for "tree regular expressions").
* [Stanford Phrasal: A Phrase-Based Translation System](http://nlp.stanford.edu/phrasal/)
* [Stanford English Tokenizer](http://nlp.stanford.edu/software/tokenizer.shtml) - Stanford Phrasal is a state-of-the-art statistical phrase-based machine translation system, written in Java.
* [Stanford Tokens Regex](http://nlp.stanford.edu/software/tokensregex.shtml) - A tokenizer divides text into a sequence of tokens, which roughly correspond to "words".
* [Stanford Temporal Tagger](http://nlp.stanford.edu/software/sutime.shtml) - SUTime is a library for recognizing and normalizing time expressions.
* [Stanford SPIED](http://nlp.stanford.edu/software/patternslearning.shtml) - Learning entities from unlabeled text starting with seed sets using patterns in an iterative fashion.
* [Stanford Topic Modeling Toolbox](http://nlp.stanford.edu/software/tmt/tmt-0.4/) - Topic modeling tools to social scientists and others who wish to perform analysis on datasets.
* [Twitter Text Java](https://github.com/twitter/twitter-text-java) - A Java implementation of Twitter's text processing library. :star:371
* [MALLET](http://mallet.cs.umass.edu/) - A Java-based package for statistical natural language processing, document classification, clustering, topic modeling, information extraction, and other machine learning applications to text.
* [OpenNLP](https://opennlp.apache.org/) - a machine learning based toolkit for the processing of natural language text.
* [LingPipe](http://alias-i.com/lingpipe/index.html) - A tool kit for processing text using computational linguistics.
* [ClearTK](https://code.google.com/archive/p/cleartk) - ClearTK provides a framework for developing statistical natural language processing (NLP) components in Java and is built on top of Apache UIMA.
* [Apache cTAKES](http://ctakes.apache.org/) - Apache clinical Text Analysis and Knowledge Extraction System (cTAKES) is an open-source natural language processing system for information extraction from electronic medical record clinical free-text.
* [ClearNLP](https://github.com/clir/clearnlp) - The ClearNLP project provides software and resources for natural language processing. The project started at the Center for Computational Language and EducAtion Research, and is currently developed by the Center for Language and Information Research at Emory University. This project is under the Apache 2 license. :star:112
* [CogcompNLP](https://github.com/IllinoisCogComp/illinois-cogcomp-nlp) - This project collects a number of core libraries for Natural Language Processing (NLP) developed in the University of Illinois' Cognitive Computation Group, for example `illinois-core-utilities` which provides a set of NLP-friendly data structures and a number of NLP-related utilities that support writing NLP applications, running experiments, etc, `illinois-edison` a library for feature extraction from illinois-core-utilities data structures and many other packages.

<a name="java-general-purpose"></a>
#### General-Purpose Machine Learning

* [aerosolve](https://github.com/airbnb/aerosolve) - A machine learning library by Airbnb designed from the ground up to be human friendly. :star:4329
* [AMIDST Toolbox](http://www.amidsttoolbox.com/) - A Java Toolbox for Scalable Probabilistic Machine Learning.
* [Datumbox](https://github.com/datumbox/datumbox-framework) - Machine Learning framework for rapid development of Machine Learning and Statistical applications. :star:969
* [ELKI](https://elki-project.github.io/) - Java toolkit for data mining. (unsupervised: clustering, outlier detection etc.)
* [Encog](https://github.com/encog/encog-java-core) - An advanced neural network and machine learning framework. Encog contains classes to create a wide variety of networks, as well as support classes to normalize and process data for these neural networks. Encog trains using multithreaded resilient propagation. Encog can also make use of a GPU to further speed processing time. A GUI based workbench is also provided to help model and train neural networks. :star:670
* [FlinkML in Apache Flink](https://ci.apache.org/projects/flink/flink-docs-master/apis/batch/libs/ml/index.html) - Distributed machine learning library in Flink.
* [H2O](https://github.com/h2oai/h2o-3) - ML engine that supports distributed learning on Hadoop, Spark or your laptop via APIs in R, Python, Scala, REST/JSON. :star:3015
* [htm.java](https://github.com/numenta/htm.java) - General Machine Learning library using Numenta’s Cortical Learning Algorithm. :star:241
* [java-deeplearning](https://github.com/deeplearning4j/deeplearning4j) - Distributed Deep Learning Platform for Java, Clojure, Scala. :star:8777
* [Mahout](https://github.com/apache/mahout) - Distributed machine learning. :star:1399
* [Meka](http://meka.sourceforge.net/) - An open source implementation of methods for multi-label classification and evaluation (extension to Weka).
* [MLlib in Apache Spark](http://spark.apache.org/docs/latest/mllib-guide.html) - Distributed machine learning library in Spark
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) - a service for deployment Apache Spark MLLib machine learning models as realtime, batch or reactive web services. :star:171
* [Neuroph](http://neuroph.sourceforge.net/) - Neuroph is lightweight Java neural network framework
* [ORYX](https://github.com/oryxproject/oryx) - Lambda Architecture Framework using Apache Spark and Apache Kafka with a specialization for real-time large-scale machine learning. :star:1418
* [Samoa](https://samoa.incubator.apache.org/) SAMOA is a framework that includes distributed machine learning for data streams with an interface to plug-in different stream processing platforms.
* [RankLib](https://sourceforge.net/p/lemur/wiki/RankLib/) - RankLib is a library of learning to rank algorithms.
* [rapaio](https://github.com/padreati/rapaio) - statistics, data mining and machine learning toolbox in Java. :star:38
* [RapidMiner](https://rapidminer.com) - RapidMiner integration into Java code.
* [Stanford Classifier](http://nlp.stanford.edu/software/classifier.shtml) - A classifier is a machine learning tool that will take data items and place them into one of k classes.
* [SmileMiner](https://github.com/haifengl/smile) - Statistical Machine Intelligence & Learning Engine. :star:3773
* [SystemML](https://github.com/apache/incubator-systemml) - flexible, scalable machine learning (ML) language. :star:672
* [WalnutiQ](https://github.com/WalnutiQ/wAlnut) - object oriented model of the human brain. :star:306
* [Weka](http://www.cs.waikato.ac.nz/ml/weka/) - Weka is a collection of machine learning algorithms for data mining tasks.
* [LBJava](https://github.com/IllinoisCogComp/lbjava/) - Learning Based Java is a modeling language for the rapid development of software systems, offers a convenient, declarative syntax for classifier and constraint definition directly in terms of the objects in the programmer's application. :star:8

#### Speech Recognition
* [CMU Sphinx](http://cmusphinx.sourceforge.net/) - Open Source Toolkit For Speech Recognition purely based on Java speech recognition library.

<a name="java-data-analysis"></a>
#### Data Analysis / Data Visualization

* [Flink](http://flink.apache.org/) - Open source platform for distributed stream and batch data processing.
* [Hadoop](https://github.com/apache/hadoop-mapreduce) - Hadoop/HDFS. :star:59
* [Onyx](https://github.com/onyx-platform/onyx) - Distributed, masterless, high performance, fault tolerant data processing. Written entirely in Clojure. :star:1722
* [Spark](https://github.com/apache/spark) - Spark is a fast and general engine for large-scale data processing. :star:17078
* [Storm](http://storm.apache.org/) - Storm is a distributed realtime computation system.
* [Impala](https://github.com/cloudera/impala) - Real-time Query for Hadoop. :star:1987
* [DataMelt](http://jwork.org/dmelt/) - Mathematics software for numeric computation, statistics, symbolic calculations, data analysis and data visualization.
* [Dr. Michael Thomas Flanagan's Java Scientific Library](http://www.ee.ucl.ac.uk/~mflanaga/java/)

<a name="java-deep-learning"></a>
#### Deep Learning

* [Deeplearning4j](https://github.com/deeplearning4j/deeplearning4j) - Scalable deep learning for industry with parallel GPUs. :star:8777

<a name="javascript"></a>
## Javascript

<a name="javascript-nlp"></a>
#### Natural Language Processing

* [Twitter-text](https://github.com/twitter/twitter-text) - A JavaScript implementation of Twitter's text processing library. :star:1917
* [natural](https://github.com/NaturalNode/natural) - General natural language facilities for node. :star:7686
* [Knwl.js](https://github.com/loadfive/Knwl.js) - A Natural Language Processor in JS. :star:5283
* [Retext](https://github.com/wooorm/retext) - Extensible system for analyzing and manipulating natural language. :star:1492
* [NLP Compromise](https://github.com/nlp-compromise/compromise) - Natural Language processing in the browser. :star:7649


<a name="javascript-data-analysis"></a>
#### Data Analysis / Data Visualization

* [D3.js](https://d3js.org/)
* [High Charts](http://www.highcharts.com/)
* [NVD3.js](http://nvd3.org/)
* [dc.js](http://dc-js.github.io/dc.js/)
* [chartjs](http://www.chartjs.org/)
* [dimple](http://dimplejs.org/)
* [amCharts](https://www.amcharts.com/)
* [D3xter](https://github.com/NathanEpstein/D3xter) - Straight forward plotting built on D3. :star:346
* [statkit](https://github.com/rigtorp/statkit) - Statistics kit for JavaScript. :star:44
* [datakit](https://github.com/nathanepstein/datakit) - A lightweight framework for data analysis in JavaScript :star:294
* [science.js](https://github.com/jasondavies/science.js/) - Scientific and statistical computing in JavaScript.
* [Z3d](https://github.com/NathanEpstein/Z3d) - Easily make interactive 3d plots built on Three.js
* [Sigma.js](http://sigmajs.org/) - JavaScript library dedicated to graph drawing.
* [C3.js](http://c3js.org/)- customizable library based on D3.js for easy chart drawing.
* [Datamaps](http://datamaps.github.io/)- Customizable SVG map/geo visualizations using D3.js.
* [ZingChart](https://www.zingchart.com/)- library written on Vanilla JS for big data visualization.
* [cheminfo](http://www.cheminfo.org/) - Platform for data visualization and analysis, using the [visualizer](https://github.com/npellet/visualizer) project.
* [Learn JS Data](http://learnjsdata.com/)
* [AnyChart](http://www.anychart.com/)
* [FusionCharts](http://www.fusioncharts.com/)


<a name="javascript-general-purpose"></a>
#### General-Purpose Machine Learning

* [Convnet.js](http://cs.stanford.edu/people/karpathy/convnetjs/) - ConvNetJS is a Javascript library for training Deep Learning models[DEEP LEARNING]
* [Clusterfck](http://harthur.github.io/clusterfck/) - Agglomerative hierarchical clustering implemented in Javascript for Node.js and the browser.
* [Clustering.js](https://github.com/emilbayes/clustering.js) - Clustering algorithms implemented in Javascript for Node.js and the browser. :star:30
* [Decision Trees](https://github.com/serendipious/nodejs-decision-tree-id3) - NodeJS Implementation of Decision Tree using ID3 Algorithm. :star:160
* [DN2A](https://github.com/dn2a/dn2a-javascript) - Digital Neural Networks Architecture. :star:457
* [figue](https://code.google.com/archive/p/figue) - K-means, fuzzy c-means and agglomerative clustering.
* [Gaussian Mixture Model](https://github.com/lukapopijac/gaussian-mixture-model) - Unsupervised machine learning with multivariate Gaussian mixture model. :star:14
* [Node-fann](https://github.com/rlidwka/node-fann) - FANN (Fast Artificial Neural Network Library) bindings for Node.js :star:182
* [Keras.js](https://github.com/transcranial/keras-js) - Run Keras models in the browser, with GPU support provided by WebGL 2. :star:3974
* [Kmeans.js](https://github.com/emilbayes/kMeans.js) - Simple Javascript implementation of the k-means algorithm, for node.js and the browser. :star:41
* [LDA.js](https://github.com/primaryobjects/lda) - LDA topic modeling for Node.js :star:192
* [Learning.js](https://github.com/yandongliu/learningjs) - Javascript implementation of logistic regression/c4.5 decision tree :star:53
* [Machine Learning](http://joonku.com/project/machine_learning) - Machine learning library for Node.js
* [machineJS](https://github.com/ClimbsRocks/machineJS) - Automated machine learning, data formatting, ensembling, and hyperparameter optimization for competitions and exploration- just give it a .csv file! :star:385
* [mil-tokyo](https://github.com/mil-tokyo) - List of several machine learning libraries.
* [Node-SVM](https://github.com/nicolaspanel/node-svm) - Support Vector Machine for Node.js :star:259
* [Brain](https://github.com/harthur/brain) - Neural networks in JavaScript **[Deprecated]** :star:8034
* [Brain.js](https://github.com/harthur-org/brain.js) - Neural networks in JavaScript - continued community fork of [Brain](https://github.com/harthur/brain). :star:4955
* [Bayesian-Bandit](https://github.com/omphalos/bayesian-bandit.js) - Bayesian bandit implementation for Node and the browser. :star:39
* [Synaptic](https://github.com/cazala/synaptic) - Architecture-free neural network library for Node.js and the browser. :star:6032
* [kNear](https://github.com/NathanEpstein/kNear) - JavaScript implementation of the k nearest neighbors algorithm for supervised learning. :star:36
* [NeuralN](https://github.com/totemstech/neuraln) - C++ Neural Network library for Node.js. It has advantage on large dataset and multi-threaded training. :star:272
* [kalman](https://github.com/itamarwe/kalman) - Kalman filter for Javascript. :star:89
* [shaman](https://github.com/luccastera/shaman) - Node.js library with support for both simple and multiple linear regression. :star:100
* [ml.js](https://github.com/mljs/ml) - Machine learning and numerical analysis tools for Node.js and the Browser! :star:934
* [Pavlov.js](https://github.com/NathanEpstein/Pavlov.js) - Reinforcement learning using Markov Decision Processes. :star:492
* [MXNet](https://github.com/dmlc/mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more. :star:13791
* [deeplearnjs](https://github.com/PAIR-code/deeplearnjs) - A hardware-accelerated machine intelligence library for the web :star:7393
* [JSMLT](https://github.com/jsmlt/jsmlt) - Machine learning toolkit with classification and clustering for Node.js; supports visualization (see [visualml.io](https://visualml.io)). :star:9
* [xgboost-node](https://github.com/nuanio/xgboost-node) - Run XGBoost model and make predictions in Node.js. :star:11

<a name="javascript-misc"></a>
#### Misc

* [stdlib](https://github.com/stdlib-js/stdlib) - A standard library for JavaScript and Node.js, with an emphasis on numeric computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more. :star:1153
* [sylvester](https://github.com/jcoglan/sylvester) - Vector and Matrix math for JavaScript. :star:997
* [simple-statistics](https://github.com/simple-statistics/simple-statistics) - A JavaScript implementation of descriptive, regression, and inference statistics. Implemented in literate JavaScript with no dependencies, designed to work in all modern browsers (including IE) as well as in Node.js. :star:1767
* [regression-js](https://github.com/Tom-Alexander/regression-js) - A javascript library containing a collection of least squares fitting methods for finding a trend in a set of data. :star:449
* [Lyric](https://github.com/flurry/Lyric) - Linear Regression library. :star:43
* [GreatCircle](https://github.com/mwgg/GreatCircle) - Library for calculating great circle distance. :star:54
* [MLPleaseHelp](https://github.com/jgreenemi/MLPleaseHelp) - MLPleaseHelp is a simple ML resource search engine. You can use this search engine right now at [https://jgreenemi.github.io/MLPleaseHelp/](https://jgreenemi.github.io/MLPleaseHelp/), provided via Github Pages. :star:4

<a name="julia"></a>
## Julia

<a name="julia-general-purpose"></a>
#### General-Purpose Machine Learning

* [MachineLearning](https://github.com/benhamner/MachineLearning.jl) - Julia Machine Learning library. :star:81
* [MLBase](https://github.com/JuliaStats/MLBase.jl) - A set of functions to support the development of machine learning algorithms. :star:105
* [PGM](https://github.com/JuliaStats/PGM.jl) - A Julia framework for probabilistic graphical models. :star:40
* [DA](https://github.com/trthatcher/DiscriminantAnalysis.jl) - Julia package for Regularized Discriminant Analysis. :star:5
* [Regression](https://github.com/lindahua/Regression.jl) - Algorithms for regression analysis (e.g. linear regression and logistic regression). :star:49
* [Local Regression](https://github.com/JuliaStats/Loess.jl) - Local regression, so smooooth!. :star:13
* [Naive Bayes](https://github.com/nutsiepully/NaiveBayes.jl) - Simple Naive Bayes implementation in Julia. :star:3
* [Mixed Models](https://github.com/dmbates/MixedModels.jl) - A Julia package for fitting (statistical) mixed-effects models. :star:111
* [Simple MCMC](https://github.com/fredo-dedup/SimpleMCMC.jl) - basic mcmc sampler implemented in Julia. :star:9
* [Distance](https://github.com/JuliaStats/Distance.jl) - Julia module for Distance evaluation. :star:27
* [Decision Tree](https://github.com/bensadeghi/DecisionTree.jl) - Decision Tree Classifier and Regressor. :star:106
* [Neural](https://github.com/compressed/BackpropNeuralNet.jl) - A neural network in Julia. :star:40
* [MCMC](https://github.com/doobwa/MCMC.jl) - MCMC tools for Julia. :star:23
* [Mamba](https://github.com/brian-j-smith/Mamba.jl) - Markov chain Monte Carlo (MCMC) for Bayesian analysis in Julia. :star:156
* [GLM](https://github.com/JuliaStats/GLM.jl) - Generalized linear models in Julia. :star:176
* [Gaussian Processes](https://github.com/STOR-i/GaussianProcesses.jl) - Julia package for Gaussian processes. :star:60
* [Online Learning](https://github.com/lendle/OnlineLearning.jl) :star:13
* [GLMNet](https://github.com/simonster/GLMNet.jl) - Julia wrapper for fitting Lasso/ElasticNet GLM models using glmnet. :star:48
* [Clustering](https://github.com/JuliaStats/Clustering.jl) - Basic functions for clustering data: k-means, dp-means, etc. :star:93
* [SVM](https://github.com/JuliaStats/SVM.jl) - SVM's for Julia. :star:29
* [Kernel Density](https://github.com/JuliaStats/KernelDensity.jl) - Kernel density estimators for julia. :star:40
* [Dimensionality Reduction](https://github.com/JuliaStats/DimensionalityReduction.jl) - Methods for dimensionality reduction. :star:21
* [NMF](https://github.com/JuliaStats/NMF.jl) - A Julia package for non-negative matrix factorization. :star:40
* [ANN](https://github.com/EricChiang/ANN.jl) - Julia artificial neural networks. :star:56
* [Mocha](https://github.com/pluskid/Mocha.jl) - Deep Learning framework for Julia inspired by Caffe. :star:1037
* [XGBoost](https://github.com/dmlc/XGBoost.jl) - eXtreme Gradient Boosting Package in Julia. :star:95
* [ManifoldLearning](https://github.com/wildart/ManifoldLearning.jl) - A Julia package for manifold learning and nonlinear dimensionality reduction. :star:27
* [MXNet](https://github.com/dmlc/mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more. :star:13791
* [Merlin](https://github.com/hshindo/Merlin.jl) - Flexible Deep Learning Framework in Julia. :star:113
* [ROCAnalysis](https://github.com/davidavdav/ROCAnalysis.jl) - Receiver Operating Characteristics and functions for evaluation probabilistic binary classifiers. :star:11
* [GaussianMixtures](https://github.com/davidavdav/GaussianMixtures.jl) - Large scale Gaussian Mixture Models. :star:24
* [ScikitLearn](https://github.com/cstjean/ScikitLearn.jl) - Julia implementation of the scikit-learn API. :star:183
* [Knet](https://github.com/denizyuret/Knet.jl) - Koç University Deep Learning Framework. :star:538

<a name="julia-nlp"></a>
#### Natural Language Processing

* [Topic Models](https://github.com/slycoder/TopicModels.jl) - TopicModels for Julia. :star:29
* [Text Analysis](https://github.com/johnmyleswhite/TextAnalysis.jl) - Julia package for text analysis. :star:162


<a name="julia-data-analysis"></a>
#### Data Analysis / Data Visualization

* [Graph Layout](https://github.com/IainNZ/GraphLayout.jl) - Graph layout algorithms in pure Julia. :star:41
* [LightGraphs](https://github.com/JuliaGraphs/LightGraphs.jl) - Graph modeling and analysis. :star:193
* [Data Frames Meta](https://github.com/JuliaStats/DataFramesMeta.jl) - Metaprogramming tools for DataFrames. :star:112
* [Julia Data](https://github.com/nfoti/JuliaData) - library for working with tabular data in Julia. :star:5
* [Data Read](https://github.com/WizardMac/ReadStat.jl) - Read files from Stata, SAS, and SPSS. :star:50
* [Hypothesis Tests](https://github.com/JuliaStats/HypothesisTests.jl) - Hypothesis tests for Julia. :star:64
* [Gadfly](https://github.com/GiovineItalia/Gadfly.jl) - Crafty statistical graphics for Julia. :star:1154
* [Stats](https://github.com/JuliaStats/Stats.jl) - Statistical tests for Julia. :star:4
* [RDataSets](https://github.com/johnmyleswhite/RDatasets.jl) - Julia package for loading many of the data sets available in R. :star:73
* [DataFrames](https://github.com/JuliaStats/DataFrames.jl) - library for working with tabular data in Julia. :star:457
* [Distributions](https://github.com/JuliaStats/Distributions.jl) - A Julia package for probability distributions and associated functions. :star:296
* [Data Arrays](https://github.com/JuliaStats/DataArrays.jl) - Data structures that allow missing values. :star:53
* [Time Series](https://github.com/JuliaStats/TimeSeries.jl) - Time series toolkit for Julia. :star:100
* [Sampling](https://github.com/lindahua/Sampling.jl) - Basic sampling algorithms for Julia.

<a name="julia-misc"></a>
#### Misc Stuff / Presentations

* [DSP](https://github.com/JuliaDSP/DSP.jl) - Digital Signal Processing (filtering, periodograms, spectrograms, window functions). :star:91
* [JuliaCon Presentations](https://github.com/JuliaCon/presentations) - Presentations for JuliaCon. :star:66
* [SignalProcessing](https://github.com/davidavdav/SignalProcessing.jl) - Signal Processing tools for Julia. :star:3
* [Images](https://github.com/JuliaImages/Images.jl) - An image library for Julia. :star:183

<a name="lua"></a>
## Lua

<a name="lua-general-purpose"></a>
#### General-Purpose Machine Learning

* [Torch7](http://torch.ch/)
  * [cephes](https://github.com/deepmind/torch-cephes) - Cephes mathematical functions library, wrapped for Torch. Provides and wraps the 180+ special mathematical functions from the Cephes mathematical library, developed by Stephen L. Moshier. It is used, among many other places, at the heart of SciPy. :star:32
  * [autograd](https://github.com/twitter/torch-autograd) - Autograd automatically differentiates native Torch code. Inspired by the original Python version. :star:533
  * [graph](https://github.com/torch/graph) - Graph package for Torch. :star:33
  * [randomkit](https://github.com/deepmind/torch-randomkit) - Numpy's randomkit, wrapped for Torch. :star:29
  * [signal](http://soumith.ch/torch-signal/signal/) - A signal processing toolbox for Torch-7. FFT, DCT, Hilbert, cepstrums, stft.
  * [nn](https://github.com/torch/nn) - Neural Network package for Torch. :star:1061
  * [torchnet](https://github.com/torchnet/torchnet) - framework for torch which provides a set of abstractions aiming at encouraging code re-use as well as encouraging modular programming. :star:930
  * [nngraph](https://github.com/torch/nngraph) - This package provides graphical computation for nn library in Torch7. :star:271
  * [nnx](https://github.com/clementfarabet/lua---nnx) - A completely unstable and experimental package that extends Torch's builtin nn library. :star:94
  * [rnn](https://github.com/Element-Research/rnn) - A Recurrent Neural Network library that extends Torch's nn. RNNs, LSTMs, GRUs, BRNNs, BLSTMs, etc. :star:885
  * [dpnn](https://github.com/Element-Research/dpnn) - Many useful features that aren't part of the main nn package. :star:189
  * [dp](https://github.com/nicholas-leonard/dp) - A deep learning library designed for streamlining research and development using the Torch7 distribution. It emphasizes flexibility through the elegant use of object-oriented design patterns. :star:354
  * [optim](https://github.com/torch/optim) - An optimization library for Torch. SGD, Adagrad, Conjugate-Gradient, LBFGS, RProp and more. :star:186
  * [unsup](https://github.com/koraykv/unsup) - A package for unsupervised learning in Torch. Provides modules that are compatible with nn (LinearPsd, ConvPsd, AutoEncoder, ...), and self-contained algorithms (k-means, PCA). :star:87
  * [manifold](https://github.com/clementfarabet/manifold) - A package to manipulate manifolds. :star:102
  * [svm](https://github.com/koraykv/torch-svm) - Torch-SVM library. :star:40
  * [lbfgs](https://github.com/clementfarabet/lbfgs) - FFI Wrapper for liblbfgs. :star:2
  * [vowpalwabbit](https://github.com/clementfarabet/vowpal_wabbit) - An old vowpalwabbit interface to torch. :star:1
  * [OpenGM](https://github.com/clementfarabet/lua---opengm) - OpenGM is a C++ library for graphical modeling, and inference. The Lua bindings provide a simple way of describing graphs, from Lua, and then optimizing them with OpenGM. :star:6
  * [sphagetti](https://github.com/MichaelMathieu/lua---spaghetti) - Spaghetti (sparse linear) module for torch7 by @MichaelMathieu :star:1
  * [LuaSHKit](https://github.com/ocallaco/LuaSHkit) - A lua wrapper around the Locality sensitive hashing library SHKit :star:2
  * [kernel smoothing](https://github.com/rlowrance/kernel-smoothers) - KNN, kernel-weighted average, local linear regression smoothers. :star:3
  * [cutorch](https://github.com/torch/cutorch) - Torch CUDA Implementation. :star:275
  * [cunn](https://github.com/torch/cunn) - Torch CUDA Neural Network Implementation. :star:177
  * [imgraph](https://github.com/clementfarabet/lua---imgraph) - An image/graph library for Torch. This package provides routines to construct graphs on images, segment them, build trees out of them, and convert them back to images. :star:18
  * [videograph](https://github.com/clementfarabet/videograph) - A video/graph library for Torch. This package provides routines to construct graphs on videos, segment them, build trees out of them, and convert them back to videos. :star:8
  * [saliency](https://github.com/marcoscoffier/torch-saliency) - code and tools around integral images. A library for finding interest points based on fast integral histograms. :star:3
  * [stitch](https://github.com/marcoscoffier/lua---stitch) - allows us to use hugin to stitch images and apply same stitching to a video sequence. :star:3
  * [sfm](https://github.com/marcoscoffier/lua---sfm) - A bundle adjustment/structure from motion package. :star:3
  * [fex](https://github.com/koraykv/fex) - A package for feature extraction in Torch. Provides SIFT and dSIFT modules. :star:8
  * [OverFeat](https://github.com/sermanet/OverFeat) - A state-of-the-art generic dense feature extractor. :star:528
  * [wav2letter](https://github.com/facebookresearch/wav2letter) - a simple and efficient end-to-end Automatic Speech Recognition (ASR) system from Facebook AI Research. :star:1546
* [Numeric Lua](http://numlua.luaforge.net/)
* [Lunatic Python](http://labix.org/lunatic-python)
* [SciLua](http://scilua.org/)
* [Lua - Numerical Algorithms](https://bitbucket.org/lucashnegri/lna)
* [Lunum](https://github.com/jzrake/lunum) :star:25

<a name="lua-demos"></a>
#### Demos and Scripts
* [Core torch7 demos repository](https://github.com/e-lab/torch7-demos).
  * linear-regression, logistic-regression
  * face detector (training and detection as separate demos)
  * mst-based-segmenter
  * train-a-digit-classifier
  * train-autoencoder
  * optical flow demo
  * train-on-housenumbers
  * train-on-cifar
  * tracking with deep nets
  * kinect demo
  * filter-bank visualization
  * saliency-networks
* [Training a Convnet for the Galaxy-Zoo Kaggle challenge(CUDA demo)](https://github.com/soumith/galaxyzoo) :star:36
* [Music Tagging](https://github.com/mbhenaff/MusicTagging) - Music Tagging scripts for torch7. :star:12
* [torch-datasets](https://github.com/rosejn/torch-datasets) - Scripts to load several popular datasets including: :star:35
  * BSR 500
  * CIFAR-10
  * COIL
  * Street View House Numbers
  * MNIST
  * NORB
* [Atari2600](https://github.com/fidlej/aledataset) - Scripts to generate a dataset with static frames from the Arcade Learning Environment. :star:17



<a name="matlab"></a>
## Matlab

<a name="matlab-cv"></a>
#### Computer Vision

* [Contourlets](http://www.ifp.illinois.edu/~minhdo/software/contourlet_toolbox.tar) - MATLAB source code that implements the contourlet transform and its utility functions.
* [Shearlets](http://www.shearlab.org/software) - MATLAB code for shearlet transform.
* [Curvelets](http://www.curvelet.org/software.html) - The Curvelet transform is a higher dimensional generalization of the Wavelet transform designed to represent images at different scales and different angles.
* [Bandlets](http://www.cmap.polytechnique.fr/~peyre/download/) - MATLAB code for bandlet transform.
* [mexopencv](http://kyamagu.github.io/mexopencv/) - Collection and a development kit of MATLAB mex functions for OpenCV library.

<a name="matlab-nlp"></a>
#### Natural Language Processing

* [NLP](https://amplab.cs.berkeley.edu/an-nlp-library-for-matlab/) - An NLP library for Matlab.

<a name="matlab-general-purpose"></a>
#### General-Purpose Machine Learning

* [Training a deep autoencoder or a classifier
on MNIST digits](http://www.cs.toronto.edu/~hinton/MatlabForSciencePaper.html) - Training a deep autoencoder or a classifier
on MNIST digits[DEEP LEARNING].
* [Convolutional-Recursive Deep Learning for 3D Object Classification](http://www.socher.org/index.php/Main/Convolutional-RecursiveDeepLearningFor3DObjectClassification) - Convolutional-Recursive Deep Learning for 3D Object Classification[DEEP LEARNING].
* [t-Distributed Stochastic Neighbor Embedding](http://homepage.tudelft.nl/19j49/t-SNE.html) - t-Distributed Stochastic Neighbor Embedding (t-SNE) is a (prize-winning) technique for dimensionality reduction that is particularly well suited for the visualization of high-dimensional datasets.
* [Spider](http://people.kyb.tuebingen.mpg.de/spider/) - The spider is intended to be a complete object orientated environment for machine learning in Matlab.
* [LibSVM](http://www.csie.ntu.edu.tw/~cjlin/libsvm/#matlab) - A Library for Support Vector Machines.
* [ThunderSVM](https://github.com/zeyiwen/thundersvm) - An Open-Source SVM Library on GPUs and CPUs :star:663
* [LibLinear](http://www.csie.ntu.edu.tw/~cjlin/liblinear/#download) - A Library for Large Linear Classification.
* [Machine Learning Module](https://github.com/josephmisiti/machine-learning-module) - Class on machine w/ PDF, lectures, code :star:376
* [Caffe](http://caffe.berkeleyvision.org)  - A deep learning framework developed with cleanliness, readability, and speed in mind.
* [Pattern Recognition Toolbox](https://github.com/covartech/PRT)  - A complete object-oriented environment for machine learning in Matlab.
* [Pattern Recognition and Machine Learning](https://github.com/PRML/PRMLT) - This package contains the matlab implementation of the algorithms described in the book Pattern Recognition and Machine Learning by C. Bishop. :star:2380
* [Optunity](http://optunity.readthedocs.io/en/latest/) - A library dedicated to automated hyperparameter optimization with a simple, lightweight API to facilitate drop-in replacement of grid search. Optunity is written in Python but interfaces seamlessly with MATLAB.
* [MXNet](https://github.com/apache/incubator-mxnet/) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more.


<a name="matlab-data-analysis"></a>
#### Data Analysis / Data Visualization

* [matlab_gbl](https://www.cs.purdue.edu/homes/dgleich/packages/matlab_bgl/) - MatlabBGL is a Matlab package for working with graphs.
* [gamic](http://www.mathworks.com/matlabcentral/fileexchange/24134-gaimc---graph-algorithms-in-matlab-code) - Efficient pure-Matlab implementations of graph algorithms to complement MatlabBGL's mex functions.

<a name="net"></a>
## .NET

<a name="net-cv"></a>
#### Computer Vision

* [OpenCVDotNet](https://code.google.com/archive/p/opencvdotnet) - A wrapper for the OpenCV project to be used with .NET applications.
* [Emgu CV](http://www.emgu.com/wiki/index.php/Main_Page) - Cross platform wrapper of OpenCV which can be compiled in Mono to e run on Windows, Linus, Mac OS X, iOS, and Android.
* [AForge.NET](http://www.aforgenet.com/framework/) - Open source C# framework for developers and researchers in the fields of Computer Vision and Artificial Intelligence. Development has now shifted to GitHub.
* [Accord.NET](http://accord-framework.net) - Together with AForge.NET, this library can provide image processing and computer vision algorithms to Windows, Windows RT and Windows Phone. Some components are also available for Java and Android.

<a name="net-nlp"></a>
#### Natural Language Processing

* [Stanford.NLP for .NET](https://github.com/sergey-tihon/Stanford.NLP.NET/) - A full port of Stanford NLP packages to .NET and also available precompiled as a NuGet package.

<a name="net-general-purpose"></a>
#### General-Purpose Machine Learning

* [Accord-Framework](http://accord-framework.net/) -The Accord.NET Framework is a complete framework for building machine learning, computer vision, computer audition, signal processing and statistical applications.
* [Accord.MachineLearning](http://www.nuget.org/packages/Accord.MachineLearning/) - Support Vector Machines, Decision Trees, Naive Bayesian models, K-means, Gaussian Mixture models and general algorithms such as Ransac, Cross-validation and Grid-Search for machine-learning applications. This package is part of the Accord.NET Framework.
* [DiffSharp](http://diffsharp.github.io/DiffSharp/) - An automatic differentiation (AD) library providing exact and efficient derivatives (gradients, Hessians, Jacobians, directional derivatives, and matrix-free Hessian- and Jacobian-vector products) for machine learning and optimization applications. Operations can be nested to any level, meaning that you can compute exact higher-order derivatives and differentiate functions that are internally making use of differentiation, for applications such as hyperparameter optimization.
* [Vulpes](https://github.com/fsprojects/Vulpes) - Deep belief and deep learning implementation written in F# and leverages CUDA GPU execution with Alea.cuBase. :star:108
* [Encog](http://www.nuget.org/packages/encog-dotnet-core/) -  An advanced neural network and machine learning framework. Encog contains classes to create a wide variety of networks, as well as support classes to normalize and process data for these neural networks. Encog trains using multithreaded resilient propagation. Encog can also make use of a GPU to further speed processing time. A GUI based workbench is also provided to help model and train neural networks.
* [Neural Network Designer](https://sourceforge.net/projects/nnd/) - DBMS management system and designer for neural networks. The designer application is developed using WPF, and is a user interface which allows you to design your neural network, query the network, create and configure chat bots that are capable of asking questions and learning from your feed back.  The chat bots can even scrape the internet for information to return in their output as well as to use for learning.
* [Infer.NET](http://infernet.azurewebsites.net/) - Infer.NET is a framework for running Bayesian inference in graphical models. One can use Infer.NET to solve many different kinds of machine learning problems, from standard problems like classification, recommendation or clustering through to customised solutions to domain-specific problems. Infer.NET has been used in a wide variety of domains including information retrieval, bioinformatics, epidemiology, vision, and many others.

<a name="net-data-analysis"></a>
#### Data Analysis / Data Visualization

* [numl](http://www.nuget.org/packages/numl/) - numl is a machine learning library intended to ease the use of using standard modeling techniques for both prediction and clustering.
* [Math.NET Numerics](http://www.nuget.org/packages/MathNet.Numerics/) - Numerical foundation of the Math.NET project, aiming to provide methods and algorithms for numerical computations in science, engineering and every day use. Supports .Net 4.0, .Net 3.5 and Mono on Windows, Linux and Mac; Silverlight 5, WindowsPhone/SL 8, WindowsPhone 8.1 and Windows 8 with PCL Portable Profiles 47 and 344; Android/iOS with Xamarin.
* [Sho](https://www.microsoft.com/en-us/research/project/sho-the-net-playground-for-data/?from=http%3A%2F%2Fresearch.microsoft.com%2Fen-us%2Fprojects%2Fsho%2F) - Sho is an interactive environment for data analysis and scientific computing that lets you seamlessly connect scripts (in IronPython) with compiled code (in .NET) to enable fast and flexible prototyping. The environment includes powerful and efficient libraries for linear algebra as well as data visualization that can be used from any .NET language, as well as a feature-rich interactive shell for rapid development.

<a name="objectivec"></a>
## Objective C

<a name="objectivec-general-purpose"></a>
### General-Purpose Machine Learning

* [YCML](https://github.com/yconst/YCML) - A Machine Learning framework for Objective-C and Swift (OS X / iOS). :star:114
* [MLPNeuralNet](https://github.com/nikolaypavlov/MLPNeuralNet) - Fast multilayer perceptron neural network library for iOS and Mac OS X. MLPNeuralNet predicts new examples by trained neural network. It is built on top of the Apple's Accelerate Framework, using vectorized operations and hardware acceleration if available. :star:919
* [MAChineLearning](https://github.com/gianlucabertani/MAChineLearning) - An Objective-C multilayer perceptron library, with full support for training through backpropagation. Implemented using vDSP and vecLib, it's 20 times faster than its Java equivalent. Includes sample code for use from Swift. :star:37
* [BPN-NeuralNetwork](https://github.com/Kalvar/ios-BPN-NeuralNetwork) - It implemented 3 layers neural network ( Input Layer, Hidden Layer and Output Layer ) and it named Back Propagation Neural Network (BPN). This network can be used in products recommendation, user behavior analysis, data mining and data analysis. :star:33
* [Multi-Perceptron-NeuralNetwork](https://github.com/Kalvar/ios-Multi-Perceptron-NeuralNetwork) - it implemented multi-perceptrons neural network (ニューラルネットワーク) based on Back Propagation Neural Network (BPN) and designed unlimited-hidden-layers. :star:22
* [KRHebbian-Algorithm](https://github.com/Kalvar/ios-KRHebbian-Algorithm) - It is a non-supervisor and self-learning algorithm (adjust the weights) in neural network of Machine Learning. :star:11
* [KRKmeans-Algorithm](https://github.com/Kalvar/ios-KRKmeans-Algorithm) - It implemented K-Means the clustering and classification algorithm. It could be used in data mining and image compression. :star:17
* [KRFuzzyCMeans-Algorithm](https://github.com/Kalvar/ios-KRFuzzyCMeans-Algorithm) - It implemented Fuzzy C-Means (FCM) the fuzzy clustering / classification algorithm on Machine Learning. It could be used in data mining and image compression. :star:9

<a name="ocaml"></a>
## OCaml

<a name="ocaml-general-purpose"></a>
### General-Purpose Machine Learning

* [Oml](https://github.com/hammerlab/oml/) - A general statistics and machine learning library. :star:109
* [GPR](http://mmottl.github.io/gpr/) - Efficient Gaussian Process Regression in OCaml.
* [Libra-Tk](http://libra.cs.uoregon.edu) - Algorithms for learning and inference with discrete probabilistic models.
* [TensorFlow](https://github.com/LaurentMazare/tensorflow-ocaml) - OCaml bindings for TensorFlow. :star:149

<a name="perl"></a>
## Perl

<a name="perl-data"></a>
### Data Analysis / Data Visualization

* [Perl Data Language](https://metacpan.org/pod/Paws::MachineLearning),
a pluggable architecture for data and image processing, which can
be
[used for machine learning](https://github.com/zenogantner/PDL-ML). 

<a name="perl-ml"></a>
### General-Purpose Machine Learning

* [MXnet for Deep Learning, in Perl](https://github.com/dmlc/mxnet/tree/master/perl-package),
also [released in CPAN](https://metacpan.org/pod/AI::MXNet).
* [Paws::MachineLearning](https://metacpan.org/pod/Paws::MachineLearning),
using AWS machine learning platform from Perl.
* [Algorithm::SVMLight](https://metacpan.org/pod/Algorithm::SVMLight),
  implementation of Support Vector Machines with SVMLight under it.
  
* Several machine learning and artificial intelligence models are
  included in the [`AI`](https://metacpan.org/search?size=20&q=AI)
  namespace. For instance, you can
  find [Naïve Bayes](https://metacpan.org/pod/AI::NaiveBayes). 

<a name="perl6"></a>
## Perl 6

*
  [Support Vector Machines](https://github.com/titsuki/p6-Algorithm-LibSVM)
* [Naïve Bayes](https://github.com/titsuki/p6-Algorithm-NaiveBayes) :star:1

### Data Analysis / Data Visualization

* [Perl Data Language](https://metacpan.org/pod/Paws::MachineLearning),
a pluggable architecture for data and image processing, which can
be
[used for machine learning](https://github.com/zenogantner/PDL-ML). 

### General-Purpose Machine Learning

<a name="php"></a>
## PHP

<a name="php-nlp"></a>
### Natural Language Processing

* [jieba-php](https://github.com/fukuball/jieba-php) - Chinese Words Segmentation Utilities. :star:564

<a name="php-general-purpose"></a>
### General-Purpose Machine Learning

* [PHP-ML](https://github.com/php-ai/php-ml) - Machine Learning library for PHP. Algorithms, Cross Validation, Neural Network, Preprocessing, Feature Extraction and much more in one library. :star:5668
* [PredictionBuilder](https://github.com/denissimon/prediction-builder) - A library for machine learning that builds predictions using a linear regression. :star:83

<a name="python"></a>
## Python

<a name="python-cv"></a>
#### Computer Vision

* [Scikit-Image](https://github.com/scikit-image/scikit-image) - A collection of algorithms for image processing in Python. :star:2216
* [SimpleCV](http://simplecv.org/) - An open source computer vision framework that gives access to several high-powered computer vision libraries, such as OpenCV. Written on Python and runs on Mac, Windows, and Ubuntu Linux.
* [Vigranumpy](https://github.com/ukoethe/vigra) - Python bindings for the VIGRA C++ computer vision library. :star:266
* [OpenFace](https://cmusatyalab.github.io/openface/) - Free and open source face recognition with deep neural networks.
* [PCV](https://github.com/jesolem/PCV) - Open source Python module for computer vision. :star:1312
* [face_recognition](https://github.com/ageitgey/face_recognition) - Face recognition library that recognize and manipulate faces from Python or from the command line. :star:12976
* [dockerface](https://github.com/natanielruiz/dockerface) - Easy to install and use deep learning Faster R-CNN face detection for images and video in a docker container. :star:106
* [Detectron](https://github.com/facebookresearch/Detectron) - FAIR's software system that implements state-of-the-art object detection algorithms, including Mask R-CNN. It is written in Python and powered by the Caffe2 deep learning framework. :star:13669

<a name="python-nlp"></a>
#### Natural Language Processing

* [NLTK](http://www.nltk.org/) - A leading platform for building Python programs to work with human language data.
* [Pattern](http://www.clips.ua.ac.be/pattern) - A web mining module for the Python programming language. It has tools for natural language processing, machine learning, among others.
* [Quepy](https://github.com/machinalis/quepy) - A python framework to transform natural language questions to queries in a database query language. :star:939
* [TextBlob](http://textblob.readthedocs.io/en/dev/) - Providing a consistent API for diving into common natural language processing (NLP) tasks. Stands on the giant shoulders of NLTK and Pattern, and plays nicely with both.
* [YAlign](https://github.com/machinalis/yalign) - A sentence aligner, a friendly tool for extracting parallel sentences from comparable corpora. :star:88
* [jieba](https://github.com/fxsjy/jieba#jieba-1) - Chinese Words Segmentation Utilities.
* [SnowNLP](https://github.com/isnowfy/snownlp) - A library for processing Chinese text. :star:3076
* [spammy](https://github.com/prodicus/spammy) - A library for email Spam filtering built on top of nltk :star:79
* [loso](https://github.com/victorlin/loso) - Another Chinese segmentation library. :star:71
* [genius](https://github.com/duanhongyi/genius) - A Chinese segment base on Conditional Random Field. :star:170
* [KoNLPy](http://konlpy.org) - A Python package for Korean natural language processing.
* [nut](https://github.com/pprett/nut) - Natural language Understanding Toolkit. :star:117
* [Rosetta](https://github.com/columbia-applied-data-science/rosetta) - Text processing tools and wrappers (e.g. Vowpal Wabbit)
* [BLLIP Parser](https://pypi.python.org/pypi/bllipparser/) - Python bindings for the BLLIP Natural Language Parser (also known as the Charniak-Johnson parser).
* [PyNLPl](https://github.com/proycon/pynlpl) - Python Natural Language Processing Library. General purpose NLP library for Python. Also contains some specific modules for parsing common NLP formats, most notably for [FoLiA](http://proycon.github.io/folia/), but also ARPA language models, Moses phrasetables, GIZA++ alignments. :star:311
* [python-ucto](https://github.com/proycon/python-ucto) - Python binding to ucto (a unicode-aware rule-based tokenizer for various languages). :star:23
* [python-frog](https://github.com/proycon/python-frog) - Python binding to Frog, an NLP suite for Dutch. (pos tagging, lemmatisation, dependency parsing, NER)
* [python-zpar](https://github.com/EducationalTestingService/python-zpar) - Python bindings for [ZPar](https://github.com/frcchang/zpar), a statistical part-of-speech-tagger, constiuency parser, and dependency parser for English. :star:34
* [colibri-core](https://github.com/proycon/colibri-core) - Python binding to C++ library for extracting and working with with basic linguistic constructions such as n-grams and skipgrams in a quick and memory-efficient way. :star:75
* [spaCy](https://github.com/honnibal/spaCy/) - Industrial strength NLP with Python and Cython. :star:9049
* [PyStanfordDependencies](https://github.com/dmcc/PyStanfordDependencies) - Python interface for converting Penn Treebank trees to Stanford Dependencies. :star:41
* [Distance](https://github.com/doukremt/distance) - Levenshtein and Hamming distance computation. :star:57
* [Fuzzy Wuzzy](https://github.com/seatgeek/fuzzywuzzy) - Fuzzy String Matching in Python. :star:4131
* [jellyfish](https://github.com/jamesturk/jellyfish) - a python library for doing approximate and phonetic matching of strings. :star:839
* [editdistance](https://pypi.python.org/pypi/editdistance) - fast implementation of edit distance.
* [textacy](https://github.com/chartbeat-labs/textacy) - higher-level NLP built on Spacy. :star:738
* [stanford-corenlp-python](https://github.com/dasmith/stanford-corenlp-python) - Python wrapper for [Stanford CoreNLP](https://github.com/stanfordnlp/CoreNLP) :star:4692
* [CLTK](https://github.com/cltk/cltk) - The Classical Language Toolkit. :star:365
* [rasa_nlu](https://github.com/golastmile/rasa_nlu) - turn natural language into structured data. :star:2976
* [yase](https://github.com/PPACI/yase) - Transcode sentence (or other sequence) to list of word vector . :star:5
* [Polyglot](https://github.com/aboSamoor/polyglot) - Multilingual text (NLP) processing toolkit. :star:804
* [DrQA](https://github.com/facebookresearch/DrQA) - Reading Wikipedia to answer open-domain questions. :star:2197
* [Dedupe](https://github.com/dedupeio/dedupe) - A python library for accurate and scaleable fuzzy matching, record deduplication and entity-resolution. :star:1646

<a name="python-general-purpose"></a>
#### General-Purpose Machine Learning
* [CNTK](https://github.com/Microsoft/CNTK) - Microsoft Cognitive Toolkit (CNTK), an open source deep-learning toolkit. Documentation can be found [here](https://docs.microsoft.com/cognitive-toolkit/). :star:14308
* [auto_ml](https://github.com/ClimbsRocks/auto_ml) - Automated machine learning for production and analytics. Lets you focus on the fun parts of ML, while outputting production-ready code, and detailed analytics of your dataset and results. Includes support for NLP, XGBoost, CatBoost, LightGBM, and soon, deep learning.  :star:736
* [machine learning](https://github.com/jeff1evesque/machine-learning) - automated build consisting of a [web-interface](https://github.com/jeff1evesque/machine-learning#web-interface), and set of [programmatic-interface](https://github.com/jeff1evesque/machine-learning#programmatic-interface) API, for support vector machines.  Corresponding dataset(s) are stored into a SQL database, then generated model(s) used for prediction(s), are stored into a NoSQL datastore. :star:167
* [XGBoost](https://github.com/dmlc/xgboost) - Python bindings for eXtreme Gradient Boosting (Tree) Library. :star:11750
* [Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) - Book/iPython notebooks on Probabilistic Programming in Python. :star:14842
* [Featureforge](https://github.com/machinalis/featureforge) A set of tools for creating and testing machine learning features, with a scikit-learn compatible API.
* [MLlib in Apache Spark](http://spark.apache.org/docs/latest/mllib-guide.html) - Distributed machine learning library in Spark
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) - a service for deployment Apache Spark MLLib machine learning models as realtime, batch or reactive web services. :star:171
* [scikit-learn](http://scikit-learn.org/) - A Python module for machine learning built on top of SciPy.
* [metric-learn](https://github.com/all-umass/metric-learn) - A Python module for metric learning. :star:398
* [SimpleAI](https://github.com/simpleai-team/simpleai) Python implementation of many of the artificial intelligence algorithms described on the book "Artificial Intelligence, a Modern Approach". It focuses on providing an easy to use, well documented and tested library.
* [astroML](http://www.astroml.org/) - Machine Learning and Data Mining for Astronomy.
* [graphlab-create](https://turi.com/products/create/docs/) - A library with various machine learning models (regression, clustering, recommender systems, graph analytics, etc.) implemented on top of a disk-backed DataFrame.
* [BigML](https://bigml.com) - A library that contacts external servers.
* [pattern](https://github.com/clips/pattern) - Web mining module for Python. :star:6227
* [NuPIC](https://github.com/numenta/nupic) - Numenta Platform for Intelligent Computing. :star:5566
* [Pylearn2](https://github.com/lisa-lab/pylearn2) - A Machine Learning library based on [Theano](https://github.com/Theano/Theano). :star:2580
* [keras](https://github.com/fchollet/keras) - Modular neural network library based on [Theano](https://github.com/Theano/Theano). :star:28754
* [Lasagne](https://github.com/Lasagne/Lasagne) - Lightweight library to build and train neural networks in Theano. :star:3423
* [hebel](https://github.com/hannes-brt/hebel) - GPU-Accelerated Deep Learning Library in Python. :star:1177
* [Chainer](https://github.com/pfnet/chainer) - Flexible neural network framework. :star:3722
* [prophet](https://facebookincubator.github.io/prophet) - Fast and automated time series forecasting framework by Facebook.
* [gensim](https://github.com/RaRe-Technologies/gensim) - Topic Modelling for Humans. :star:6855
* [topik](https://github.com/ContinuumIO/topik) - Topic modelling toolkit. :star:88
* [PyBrain](https://github.com/pybrain/pybrain) - Another Python Machine Learning Library. :star:2533
* [Brainstorm](https://github.com/IDSIA/brainstorm) - Fast, flexible and fun neural networks. This is the successor of PyBrain. :star:1277
* [Surprise](http://surpriselib.com) - A scikit for building and analyzing recommender systems.
* [Crab](https://github.com/muricoca/crab) - A flexible, fast recommender engine. :star:927
* [python-recsys](https://github.com/ocelma/python-recsys) - A Python library for implementing a Recommender System. :star:1027
* [thinking bayes](https://github.com/AllenDowney/ThinkBayes) - Book on Bayesian Analysis. :star:914
* [Image-to-Image Translation with Conditional Adversarial Networks](https://github.com/williamFalcon/pix2pix-keras) - Implementation of image to image (pix2pix) translation from the paper by [isola et al](https://arxiv.org/pdf/1611.07004.pdf).[DEEP LEARNING] :star:39
* [Restricted Boltzmann Machines](https://github.com/echen/restricted-boltzmann-machines) -Restricted Boltzmann Machines in Python. [DEEP LEARNING]
* [Bolt](https://github.com/pprett/bolt) - Bolt Online Learning Toolbox. :star:81
* [CoverTree](https://github.com/patvarilly/CoverTree) - Python implementation of cover trees, near-drop-in replacement for scipy.spatial.kdtree :star:22
* [nilearn](https://github.com/nilearn/nilearn) - Machine learning for NeuroImaging in Python. :star:391
* [neuropredict](https://github.com/raamana/neuropredict) - Aimed at novice machine learners and non-expert programmers, this package offers easy (no coding needed) and comprehensive machine learning (evaluation and full report of predictive performance WITHOUT requiring you to code) in Python for NeuroImaging and any other type of features. This is aimed at absorbing the much of the ML workflow, unlike other packages like nilearn and pymvpa, which require you to learn their API and code to produce anything useful. :star:31
* [imbalanced-learn](http://contrib.scikit-learn.org/imbalanced-learn/) - Python module to perform under sampling and over sampling with various techniques.
* [Shogun](https://github.com/shogun-toolbox/shogun) - The Shogun Machine Learning Toolbox. :star:2084
* [Pyevolve](https://github.com/perone/Pyevolve) - Genetic algorithm framework. :star:272
* [Caffe](http://caffe.berkeleyvision.org)  - A deep learning framework developed with cleanliness, readability, and speed in mind.
* [breze](https://github.com/breze-no-salt/breze) - Theano based library for deep and recurrent neural networks. :star:90
* [pyhsmm](https://github.com/mattjj/pyhsmm) - library for approximate unsupervised inference in Bayesian Hidden Markov Models (HMMs) and explicit-duration Hidden semi-Markov Models (HSMMs), focusing on the Bayesian Nonparametric extensions, the HDP-HMM and HDP-HSMM, mostly with weak-limit approximations. :star:339
* [mrjob](https://pythonhosted.org/mrjob/) - A library to let Python program run on Hadoop.
* [SKLL](https://github.com/EducationalTestingService/skll) - A wrapper around scikit-learn that makes it simpler to conduct experiments. :star:412
* [neurolab](https://github.com/zueve/neurolab) - https://github.com/zueve/neurolab :star:124
* [Spearmint](https://github.com/JasperSnoek/spearmint) - Spearmint is a package to perform Bayesian optimization according to the algorithms outlined in the paper: Practical Bayesian Optimization of Machine Learning Algorithms. Jasper Snoek, Hugo Larochelle and Ryan P. Adams. Advances in Neural Information Processing Systems, 2012. :star:1071
* [Pebl](https://github.com/abhik/pebl/) - Python Environment for Bayesian Learning.
* [Theano](https://github.com/Theano/Theano/) - Optimizing GPU-meta-programming code generating array oriented optimizing math compiler in Python.
* [TensorFlow](https://github.com/tensorflow/tensorflow/) - Open source software library for numerical computation using data flow graphs.
* [yahmm](https://github.com/jmschrei/yahmm/) - Hidden Markov Models for Python, implemented in Cython for speed and efficiency.
* [python-timbl](https://github.com/proycon/python-timbl) - A Python extension module wrapping the full TiMBL C++ programming interface. Timbl is an elaborate k-Nearest Neighbours machine learning toolkit. :star:11
* [deap](https://github.com/deap/deap) - Evolutionary algorithm framework. :star:1897
* [pydeep](https://github.com/andersbll/deeppy) - Deep Learning In Python. :star:1246
* [mlxtend](https://github.com/rasbt/mlxtend) - A library consisting of useful tools for data science and machine learning tasks. :star:1466
* [neon](https://github.com/NervanaSystems/neon) - Nervana's [high-performance](https://github.com/soumith/convnet-benchmarks) Python-based Deep Learning framework [DEEP LEARNING]. :star:3476
* [Optunity](http://optunity.readthedocs.io/en/latest/) - A library dedicated to automated hyperparameter optimization with a simple, lightweight API to facilitate drop-in replacement of grid search.
* [Neural Networks and Deep Learning](https://github.com/mnielsen/neural-networks-and-deep-learning) - Code samples for my book "Neural Networks and Deep Learning" [DEEP LEARNING]. :star:6682
* [Annoy](https://github.com/spotify/annoy) - Approximate nearest neighbours implementation. :star:3444
* [skflow](https://github.com/tensorflow/skflow) - Simplified interface for TensorFlow, mimicking Scikit Learn. :star:3165
* [TPOT](https://github.com/rhiever/tpot) - Tool that automatically creates and optimizes machine learning pipelines using genetic programming. Consider it your personal data science assistant, automating a tedious part of machine learning. :star:3906
* [pgmpy](https://github.com/pgmpy/pgmpy) A python library for working with Probabilistic Graphical Models.
* [DIGITS](https://github.com/NVIDIA/DIGITS) - The Deep Learning GPU Training System (DIGITS) is a web application for training deep learning models. :star:3086
* [Orange](http://orange.biolab.si/) - Open source data visualization and data analysis for novices and experts.
* [MXNet](https://github.com/dmlc/mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more. :star:13791
* [milk](https://github.com/luispedro/milk) - Machine learning toolkit focused on supervised classification. :star:578
* [TFLearn](https://github.com/tflearn/tflearn) - Deep learning library featuring a higher-level API for TensorFlow. :star:7966
* [REP](https://github.com/yandex/rep) - an IPython-based environment for conducting data-driven research in a consistent and reproducible way. REP is not trying to substitute scikit-learn, but extends it and provides better user experience. :star:508
* [rgf_python](https://github.com/fukatani/rgf_python) - Python bindings for Regularized Greedy Forest (Tree) Library. :star:129
* [skbayes](https://github.com/AmazaspShumik/sklearn-bayes) - Python package for Bayesian Machine Learning with scikit-learn API. :star:272
* [fuku-ml](https://github.com/fukuball/fuku-ml) - Simple machine learning library, including Perceptron, Regression, Support Vector Machine, Decision Tree and more, it's easy to use and easy to learn for beginners. :star:209
* [Xcessiv](https://github.com/reiinakano/xcessiv) - A web-based application for quick, scalable, and automated hyperparameter tuning and stacked ensembling. :star:1034
* [PyTorch](https://github.com/pytorch/pytorch) - Tensors and Dynamic neural networks in Python with strong GPU acceleration :star:14549
* [ML-From-Scratch](https://github.com/eriklindernoren/ML-From-Scratch) - Implementations of Machine Learning models from scratch in Python with a focus on transparency. Aims to showcase the nuts and bolts of ML in an accessible way. :star:8159
* [Edward](http://edwardlib.org/) - A library for probabilistic modeling, inference, and criticism. Built on top of TensorFlow.
* [xRBM](https://github.com/omimo/xRBM) - A library for Restricted Boltzmann Machine (RBM) and its conditional variants in Tensorflow. :star:30
* [CatBoost](https://github.com/catboost/catboost) - General purpose gradient boosting on decision trees library with categorical features support out of the box. It is easy to install, well documented and supports CPU and GPU (even multi-GPU) computation. :star:2697
* [stacked_generalization](https://github.com/fukatani/stacked_generalization) - Implementation of machine learning stacking technic as handy library in Python. :star:72
* [modAL](https://cosmic-cortex.github.io/modAL) - A modular active learning framework for Python, built on top of scikit-learn.
* [Cogitare](https://github.com/cogitare-ai/cogitare): A Modern, Fast, and Modular Deep Learning and Machine Learning framework for Python. 
* [Parris](https://github.com/jgreenemi/Parris) - Parris, the automated infrastructure setup tool for machine learning algorithms. :star:305
* [neonrvm](https://github.com/siavashserver/neonrvm) - neonrvm is an open source machine learning library based on RVM technique. It's written in C programming language and comes with Python programming language bindings. :star:6
* [Turi Create](https://github.com/apple/turicreate)  - Machine learning from Apple. Turi Create simplifies the development of custom machine learning models. You don't have to be a machine learning expert to add recommendations, object detection, image classification, image similarity or activity classification to your app.

<a name="python-data-analysis"></a>
#### Data Analysis / Data Visualization

* [SciPy](http://www.scipy.org/) - A Python-based ecosystem of open-source software for mathematics, science, and engineering.
* [NumPy](http://www.numpy.org/) - A fundamental package for scientific computing with Python.
* [Numba](http://numba.pydata.org/) - Python JIT (just in time) complier to LLVM aimed at scientific Python by the developers of Cython and NumPy.
* [NetworkX](https://networkx.github.io/) - A high-productivity software for complex networks.
* [igraph](http://igraph.org/python/) - binding to igraph library - General purpose graph library.
* [Pandas](http://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.
* [Open Mining](https://github.com/mining/mining) - Business Intelligence (BI) in Python (Pandas web interface)
* [PyMC](https://github.com/pymc-devs/pymc) - Markov Chain Monte Carlo sampling toolkit. :star:667
* [zipline](https://github.com/quantopian/zipline) - A Pythonic algorithmic trading library. :star:6829
* [PyDy](http://www.pydy.org/) - Short for Python Dynamics, used to assist with workflow in the modeling of dynamic motion based around NumPy, SciPy, IPython, and matplotlib.
* [SymPy](https://github.com/sympy/sympy) - A Python library for symbolic mathematics. :star:4803
* [statsmodels](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python. :star:2795
* [astropy](http://www.astropy.org/) - A community Python library for Astronomy.
* [matplotlib](http://matplotlib.org/) - A Python 2D plotting library.
* [bokeh](https://github.com/bokeh/bokeh) - Interactive Web Plotting for Python. :star:7545
* [plotly](https://plot.ly/python/) - Collaborative web plotting for Python and matplotlib.
* [vincent](https://github.com/wrobstory/vincent) - A Python to Vega translator. :star:2045
* [d3py](https://github.com/mikedewar/d3py) - A plotting library for Python, based on [D3.js](https://d3js.org/). :star:1277
* [PyDexter](https://github.com/D3xterjs/pydexter) - Simple plotting for Python. Wrapper for D3xterjs; easily render charts in-browser. :star:31
* [ggplot](https://github.com/yhat/ggpy) - Same API as ggplot2 for R. :star:3287
* [ggfortify](https://github.com/sinhrks/ggfortify) - Unified interface to ggplot2 popular R packages. :star:345
* [Kartograph.py](https://github.com/kartograph/kartograph.py) - Rendering beautiful SVG maps in Python. :star:946
* [pygal](http://pygal.org/en/stable/) - A Python SVG Charts Creator.
* [PyQtGraph](https://github.com/pyqtgraph/pyqtgraph) - A pure-python graphics and GUI library built on PyQt4 / PySide and NumPy. :star:1066
* [pycascading](https://github.com/twitter/pycascading) :star:222
* [Petrel](https://github.com/AirSage/Petrel) - Tools for writing, submitting, debugging, and monitoring Storm topologies in pure Python. :star:251
* [Blaze](https://github.com/blaze/blaze) - NumPy and Pandas interface to Big Data. :star:2348
* [emcee](https://github.com/dfm/emcee) - The Python ensemble sampling toolkit for affine-invariant MCMC. :star:802
* [windML](http://www.windml.org) - A Python Framework for Wind Energy Analysis and Prediction.
* [vispy](https://github.com/vispy/vispy) - GPU-based high-performance interactive OpenGL 2D/3D data visualization library. :star:1629
* [cerebro2](https://github.com/numenta/nupic.cerebro2) A web-based visualization and debugging platform for NuPIC.
* [NuPIC Studio](https://github.com/htm-community/nupic.studio) An all-in-one NuPIC Hierarchical Temporal Memory visualization and debugging super-tool!
* [SparklingPandas](https://github.com/sparklingpandas/sparklingpandas) Pandas on PySpark (POPS).
* [Seaborn](http://seaborn.pydata.org/) - A python visualization library based on matplotlib.
* [bqplot](https://github.com/bloomberg/bqplot) - An API for plotting in Jupyter (IPython). :star:1857
* [pastalog](https://github.com/rewonc/pastalog) - Simple, realtime visualization of neural network training performance. :star:377
* [caravel](https://github.com/airbnb/superset) - A data exploration platform designed to be visual, intuitive, and interactive. :star:18918
* [Dora](https://github.com/nathanepstein/dora) - Tools for exploratory data analysis in Python. :star:412
* [Ruffus](http://www.ruffus.org.uk) - Computation Pipeline library for python.
* [SOMPY](https://github.com/sevamoo/SOMPY) - Self Organizing Map written in Python (Uses neural networks for data analysis). :star:227
* [somoclu](https://github.com/peterwittek/somoclu) Massively parallel self-organizing maps: accelerate training on multicore CPUs, GPUs, and clusters, has python API.
* [HDBScan](https://github.com/lmcinnes/hdbscan) - implementation of the hdbscan algorithm in Python - used for clustering :star:32
* [visualize_ML](https://github.com/ayush1997/visualize_ML) - A python package for data exploration and data analysis. :star:153
* [scikit-plot](https://github.com/reiinakano/scikit-plot) - A visualization library for quick and easy generation of common plots in data analysis and machine learning. :star:1135
* [Bowtie](https://github.com/jwkvam/bowtie) - A dashboard library for interactive visualizations using flask socketio and react. :star:565
* [lime](https://github.com/marcotcr/lime) - Lime is about explaining what machine learning classifiers (or models) are doing. It is able to explain any black box classifier, with two or more classes. :star:3715

<a name="python-misc"></a>
#### Misc Scripts / iPython Notebooks / Codebases
* [BioPy](https://github.com/jaredthecoder/BioPy) - Biologically-Inspired and Machine Learning Algorithms in Python. :star:16
* [pattern_classification](https://github.com/rasbt/pattern_classification) :star:3151
* [thinking stats 2](https://github.com/Wavelets/ThinkStats2) :star:5
* [hyperopt](https://github.com/hyperopt/hyperopt-sklearn) :star:571
* [numpic](https://github.com/numenta/nupic) :star:5566
* [2012-paper-diginorm](https://github.com/dib-lab/2012-paper-diginorm) :star:6
* [A gallery of interesting IPython notebooks](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks)
* [ipython-notebooks](https://github.com/ogrisel/notebooks) :star:455
* [data-science-ipython-notebooks](https://github.com/donnemartin/data-science-ipython-notebooks) - Continually updated Data Science Python Notebooks: Spark, Hadoop MapReduce, HDFS, AWS, Kaggle, scikit-learn, matplotlib, pandas, NumPy, SciPy, and various command lines. :star:12388
* [decision-weights](https://github.com/CamDavidsonPilon/decision-weights) :star:25
* [Sarah Palin LDA](https://github.com/Wavelets/sarah-palin-lda) - Topic Modeling the Sarah Palin emails. :star:8
* [Diffusion Segmentation](https://github.com/Wavelets/diffusion-segmentation) - A collection of image segmentation algorithms based on diffusion methods. :star:2
* [Scipy Tutorials](https://github.com/Wavelets/scipy-tutorials) - SciPy tutorials. This is outdated, check out scipy-lecture-notes. :star:1
* [Crab](https://github.com/marcelcaraciolo/crab) - A recommendation engine library for Python. :star:83
* [BayesPy](https://github.com/maxsklar/BayesPy) - Bayesian Inference Tools in Python. :star:63
* [scikit-learn tutorials](https://github.com/GaelVaroquaux/scikit-learn-tutorial) - Series of notebooks for learning scikit-learn. :star:93
* [sentiment-analyzer](https://github.com/madhusudancs/sentiment-analyzer) - Tweets Sentiment Analyzer :star:41
* [sentiment_classifier](https://github.com/kevincobain2000/sentiment_classifier) - Sentiment classifier using word sense disambiguation. :star:125
* [group-lasso](https://github.com/fabianp/group_lasso) - Some experiments with the coordinate descent algorithm used in the (Sparse) Group Lasso model. :star:19
* [jProcessing](https://github.com/kevincobain2000/jProcessing) - Kanji / Hiragana / Katakana to Romaji Converter. Edict Dictionary & parallel sentences Search. Sentence Similarity between two JP Sentences. Sentiment Analysis of Japanese Text. Run Cabocha(ISO--8859-1 configured) in Python. :star:93
* [mne-python-notebooks](https://github.com/mne-tools/mne-python-notebooks) - IPython notebooks for EEG/MEG data processing using mne-python. :star:10
* [Neon Course](https://github.com/NervanaSystems/neon_course) - IPython notebooks for a complete course around understanding Nervana's Neon. :star:84
* [pandas cookbook](https://github.com/jvns/pandas-cookbook) - Recipes for using Python's pandas library. :star:2939
* [climin](https://github.com/BRML/climin) - Optimization library focused on machine learning, pythonic implementations of gradient descent, LBFGS, rmsprop, adadelta and others. :star:142
* [Allen Downey’s Data Science Course](https://github.com/AllenDowney/DataScience) - Code for Data Science at Olin College, Spring 2014. :star:29
* [Allen Downey’s Think Bayes Code](https://github.com/AllenDowney/ThinkBayes) - Code repository for Think Bayes. :star:914
* [Allen Downey’s Think Complexity Code](https://github.com/AllenDowney/ThinkComplexity) - Code for Allen Downey's book Think Complexity. :star:71
* [Allen Downey’s Think OS Code](https://github.com/AllenDowney/ThinkOS) - Text and supporting code for Think OS: A Brief Introduction to Operating Systems. :star:342
* [Python Programming for the Humanities](http://www.karsdorp.io/python-course/) - Course for Python programming for the Humanities, assuming no prior knowledge. Heavy focus on text processing / NLP.
* [GreatCircle](https://github.com/mwgg/GreatCircle) - Library for calculating great circle distance. :star:54
* [Optunity examples](http://optunity.readthedocs.io/en/latest/notebooks/index.html) - Examples demonstrating how to use Optunity in synergy with machine learning libraries.
* [Dive into Machine Learning  with Python Jupyter notebook and scikit-learn](https://github.com/hangtwenty/dive-into-machine-learning) - "I learned Python by hacking first, and getting serious *later.* I wanted to do this with Machine Learning. If this is your style, join me in getting a bit ahead of yourself." :star:8134
* [TDB](https://github.com/ericjang/tdb) - TensorDebugger (TDB) is a visual debugger for deep learning. It features interactive, node-by-node debugging and visualization for TensorFlow. :star:1288
* [Suiron](https://github.com/kendricktan/suiron/) - Machine Learning for RC Cars.
* [Introduction to machine learning with scikit-learn](https://github.com/justmarkham/scikit-learn-videos) - IPython notebooks from Data School's video tutorials on scikit-learn. :star:1667
* [Practical XGBoost in Python](http://education.parrotprediction.teachable.com/p/practical-xgboost-in-python) - comprehensive online course about using XGBoost in Python.
* [Introduction to Machine Learning with Python](https://github.com/amueller/introduction_to_ml_with_python) - Notebooks and code for the book "Introduction to Machine Learning with Python" :star:2071
* [Pydata book](https://github.com/wesm/pydata-book) - Materials and IPython notebooks for "Python for Data Analysis" by Wes McKinney, published by O'Reilly Media :star:5564

<a name="python-neural-networks"></a>
#### Neural Networks
* [NeuralTalk](https://github.com/karpathy/neuraltalk) - NeuralTalk is a Python+numpy project for learning Multimodal Recurrent Neural Networks that describe images with sentences. :star:4692
* [Neuron](https://github.com/molcik/python-neuron) - Neuron is simple class for time series predictions. It's utilize LNU (Linear Neural Unit), QNU (Quadratic Neural Unit), RBF (Radial Basis Function), MLP (Multi Layer Perceptron), MLP-ELM (Multi Layer Perceptron - Extreme Learning Machine) neural networks learned with Gradient descent or LeLevenberg–Marquardt algorithm. :star:15
* [Data Driven Code](https://github.com/atmb4u/data-driven-code) - Very simple implementation of neural networks for dummies in python without using any libraries, with detailed comments. :star:17

<a name="python-kaggle"></a>
#### Kaggle Competition Source Code
* [wiki challenge](https://github.com/hammer/wikichallenge) - An implementation of Dell Zhang's solution to Wikipedia's Participation Challenge on Kaggle. :star:9
* [kaggle insults](https://github.com/amueller/kaggle_insults) - Kaggle Submission for "Detecting Insults in Social Commentary". :star:137
* [kaggle_acquire-valued-shoppers-challenge](https://github.com/MLWave/kaggle_acquire-valued-shoppers-challenge) - Code for the Kaggle acquire valued shoppers challenge. :star:60
* [kaggle-cifar](https://github.com/zygmuntz/kaggle-cifar) - Code for the CIFAR-10 competition at Kaggle, uses cuda-convnet. :star:42
* [kaggle-blackbox](https://github.com/zygmuntz/kaggle-blackbox) - Deep learning made easy. :star:122
* [kaggle-accelerometer](https://github.com/zygmuntz/kaggle-accelerometer) - Code for Accelerometer Biometric Competition at Kaggle. :star:11
* [kaggle-advertised-salaries](https://github.com/zygmuntz/kaggle-advertised-salaries) - Predicting job salaries from ads - a Kaggle competition. :star:58
* [kaggle amazon](https://github.com/zygmuntz/kaggle-amazon) - Amazon access control challenge. :star:25
* [kaggle-bestbuy_big](https://github.com/zygmuntz/kaggle-bestbuy_big) - Code for the Best Buy competition at Kaggle. :star:7
* [kaggle-bestbuy_small](https://github.com/zygmuntz/kaggle-bestbuy_small) :star:4
* [Kaggle Dogs vs. Cats](https://github.com/kastnerkyle/kaggle-dogs-vs-cats) - Code for Kaggle Dogs vs. Cats competition. :star:62
* [Kaggle Galaxy Challenge](https://github.com/benanne/kaggle-galaxies) - Winning solution for the Galaxy Challenge on Kaggle. :star:432
* [Kaggle Gender](https://github.com/zygmuntz/kaggle-gender) - A Kaggle competition: discriminate gender based on handwriting. :star:14
* [Kaggle Merck](https://github.com/zygmuntz/kaggle-merck) - Merck challenge at Kaggle. :star:6
* [Kaggle Stackoverflow](https://github.com/zygmuntz/kaggle-stackoverflow) - Predicting closed questions on Stack Overflow. :star:43
* [kaggle_acquire-valued-shoppers-challenge](https://github.com/MLWave/kaggle_acquire-valued-shoppers-challenge) - Code for the Kaggle acquire valued shoppers challenge. :star:60
* [wine-quality](https://github.com/zygmuntz/wine-quality) - Predicting wine quality. :star:13

<a name="python-reinforcement-learning"></a>
#### Reinforcement Learning
* [DeepMind Lab](https://github.com/deepmind/lab) - DeepMind Lab is a 3D learning environment based on id Software's Quake III Arena via ioquake3 and other open source software. Its primary purpose is to act as a testbed for research in artificial intelligence, especially deep reinforcement learning. :star:4965
* [Gym](https://github.com/openai/gym) - OpenAI Gym is a toolkit for developing and comparing reinforcement learning algorithms. :star:11621
* [Serpent.AI](https://github.com/SerpentAI/SerpentAI) - Serpent.AI is a game agent framework that allows you to turn any video game you own into a sandbox to develop AI and machine learning experiments. For both researchers and hobbyists.  :star:4170
* [Universe](https://github.com/openai/universe) - Universe is a software platform for measuring and training an AI's general intelligence across the world's supply of games, websites and other applications. :star:6757
* [ViZDoom](https://github.com/mwydmuch/ViZDoom) - ViZDoom allows developing AI bots that play Doom using only the visual information (the screen buffer). It is primarily intended for research in machine visual learning, and deep reinforcement learning, in particular. :star:627

<a name="ruby"></a>
## Ruby

<a name="ruby-nlp"></a>
#### Natural Language Processing

* [Awesome NLP with Ruby](https://github.com/arbox/nlp-with-ruby) - Curated link list for practical natural language processing in Ruby. :star:746
* [Treat](https://github.com/louismullie/treat) -  Text REtrieval and Annotation Toolkit, definitely the most comprehensive toolkit I’ve encountered so far for Ruby. :star:1309
* [Ruby Linguistics](https://deveiate.org/projects/Linguistics) -  Linguistics is a framework for building linguistic utilities for Ruby objects in any language. It includes a generic language-independent front end, a module for mapping language codes into language names, and a module which contains various English-language utilities.
* [Stemmer](https://github.com/aurelian/ruby-stemmer) - Expose libstemmer_c to Ruby. :star:235
* [Ruby Wordnet](https://deveiate.org/projects/Ruby-WordNet/) - This library is a Ruby interface to WordNet.
* [Raspel](https://sourceforge.net/projects/raspell/) - raspell is an interface binding for ruby.
* [UEA Stemmer](https://github.com/ealdent/uea-stemmer) - Ruby port of UEALite Stemmer - a conservative stemmer for search and indexing. :star:44
* [Twitter-text-rb](https://github.com/twitter/twitter-text-rb) - A library that does auto linking and extraction of usernames, lists and hashtags in tweets. :star:623

<a name="ruby-general-purpose"></a>
#### General-Purpose Machine Learning

* [Awesome Machine Learning with Ruby](https://github.com/arbox/machine-learning-with-ruby) - Curated list of ML related resources for Ruby. :star:987
* [Ruby Machine Learning](https://github.com/tsycho/ruby-machine-learning) - Some Machine Learning algorithms, implemented in Ruby. :star:30
* [Machine Learning Ruby](https://github.com/mizoR/machine-learning-ruby) :star:14
* [jRuby Mahout](https://github.com/vasinov/jruby_mahout) - JRuby Mahout is a gem that unleashes the power of Apache Mahout in the world of JRuby. :star:168
* [CardMagic-Classifier](https://github.com/cardmagic/classifier) - A general classifier module to allow Bayesian and other types of classifications. :star:631
* [rb-libsvm](https://github.com/febeling/rb-libsvm) - Ruby language bindings for LIBSVM which is a Library for Support Vector Machines. :star:257
* [Random Forester](https://github.com/asafschers/random_forester) - Creates Random Forest classifiers from PMML files. :star:32

<a name="ruby-data-analysis"></a>
#### Data Analysis / Data Visualization

* [rsruby](https://github.com/alexgutteridge/rsruby) - Ruby - R bridge. :star:325
* [data-visualization-ruby](https://github.com/chrislo/data_visualisation_ruby) - Source code and supporting content for my Ruby Manor presentation on Data Visualisation with Ruby. :star:68
* [ruby-plot](https://www.ruby-toolbox.com/projects/ruby-plot) - gnuplot wrapper for Ruby, especially for plotting ROC curves into SVG files.
* [plot-rb](https://github.com/zuhao/plotrb) - A plotting library in Ruby built on top of Vega and D3. :star:39
* [scruffy](http://www.rubyinside.com/scruffy-a-beautiful-graphing-toolkit-for-ruby-194.html) - A beautiful graphing toolkit for Ruby.
* [SciRuby](http://sciruby.com/)
* [Glean](https://github.com/glean/glean) - A data management tool for humans. :star:116
* [Bioruby](https://github.com/bioruby/bioruby) :star:319
* [Arel](https://github.com/nkallen/arel) :star:253

<a name="ruby-misc"></a>
#### Misc

* [Big Data For Chimps](https://github.com/infochimps-labs/big_data_for_chimps) :star:166
* [Listof](https://github.com/kevincobain2000/listof) - Community based data collection, packed in gem. Get list of pretty much anything (stop words, countries, non words) in txt, json or hash. [Demo/Search for a list](http://kevincobain2000.github.io/listof/)


<a name="rust"></a>
## Rust

<a name="rust-general-purpose"></a>
#### General-Purpose Machine Learning
* [deeplearn-rs](https://github.com/tedsta/deeplearn-rs) - deeplearn-rs provides simple networks that use matrix multiplication, addition, and ReLU under the MIT license. :star:165
* [rustlearn](https://github.com/maciejkula/rustlearn) - a machine learning framework featuring logistic regression, support vector machines, decision trees and random forests. :star:272
* [rusty-machine](https://github.com/AtheMathmo/rusty-machine) - a pure-rust machine learning library. :star:653
* [leaf](https://github.com/autumnai/leaf) - open source framework for machine intelligence, sharing concepts from TensorFlow and Caffe.  Available under the MIT license. [**[Deprecated]**](https://medium.com/@mjhirn/tensorflow-wins-89b78b29aafb#.s0a3uy4cc)
* [RustNN](https://github.com/jackm321/RustNN) - RustNN is a feedforward neural network library. :star:282


<a name="r"></a>
## R

<a name="r-general-purpose"></a>
#### General-Purpose Machine Learning

* [ahaz](http://cran.r-project.org/web/packages/ahaz/index.html) - ahaz: Regularization for semiparametric additive hazards regression.
* [arules](http://cran.r-project.org/web/packages/arules/index.html) - arules: Mining Association Rules and Frequent Itemsets
* [biglasso](https://cran.r-project.org/web/packages/biglasso/index.html) - biglasso: Extending Lasso Model Fitting to Big Data in R.
* [bigrf](http://cran.r-project.org/web/packages/bigrf/index.html) - bigrf: Big Random Forests: Classification and Regression Forests for Large Data Sets.
* [bigRR](http://cran.r-project.org/web/packages/bigRR/index.html) - bigRR: Generalized Ridge Regression (with special advantage for p >> n cases).
* [bmrm](http://cran.r-project.org/web/packages/bmrm/index.html) - bmrm: Bundle Methods for Regularized Risk Minimization Package.
* [Boruta](http://cran.r-project.org/web/packages/Boruta/index.html) - Boruta: A wrapper algorithm for all-relevant feature selection.
* [bst](http://cran.r-project.org/web/packages/bst/index.html) - bst: Gradient Boosting.
* [C50](http://cran.r-project.org/web/packages/C50/index.html) - C50: C5.0 Decision Trees and Rule-Based Models.
* [caret](http://caret.r-forge.r-project.org/) - Classification and Regression Training: Unified interface to ~150 ML algorithms in R.
* [caretEnsemble](http://cran.r-project.org/web/packages/caretEnsemble/index.html) - caretEnsemble: Framework for fitting multiple caret models as well as creating ensembles of such models.
* [CatBoost](https://github.com/catboost/catboost) - General purpose gradient boosting on decision trees library with categorical features support out of the box for R. :star:2697
* [Clever Algorithms For Machine Learning](https://github.com/jbrownlee/CleverAlgorithmsMachineLearning) :star:246
* [CORElearn](http://cran.r-project.org/web/packages/CORElearn/index.html) - CORElearn: Classification, regression, feature evaluation and ordinal evaluation.
* [CoxBoost](http://cran.r-project.org/web/packages/CoxBoost/index.html) - CoxBoost: Cox models by likelihood based boosting for a single survival endpoint or competing risks
* [Cubist](http://cran.r-project.org/web/packages/Cubist/index.html) - Cubist: Rule- and Instance-Based Regression Modeling.
* [e1071](http://cran.r-project.org/web/packages/e1071/index.html) - e1071: Misc Functions of the Department of Statistics (e1071), TU Wien
* [earth](http://cran.r-project.org/web/packages/earth/index.html) - earth: Multivariate Adaptive Regression Spline Models
* [elasticnet](http://cran.r-project.org/web/packages/elasticnet/index.html) - elasticnet: Elastic-Net for Sparse Estimation and Sparse PCA.
* [ElemStatLearn](http://cran.r-project.org/web/packages/ElemStatLearn/index.html) - ElemStatLearn: Data sets, functions and examples from the book: "The Elements of Statistical Learning, Data Mining, Inference, and Prediction" by Trevor Hastie, Robert Tibshirani and Jerome Friedman Prediction" by Trevor Hastie, Robert Tibshirani and Jerome Friedman.
* [evtree](http://cran.r-project.org/web/packages/evtree/index.html) - evtree: Evolutionary Learning of Globally Optimal Trees.
* [forecast](http://cran.r-project.org/web/packages/forecast/index.html) - forecast: Timeseries forecasting using ARIMA, ETS, STLM, TBATS, and neural network models.
* [forecastHybrid](http://cran.r-project.org/web/packages/forecastHybrid/index.html) - forecastHybrid: Automatic ensemble and cross validation of ARIMA, ETS, STLM, TBATS, and neural network models from the "forecast" package.
* [fpc](http://cran.r-project.org/web/packages/fpc/index.html) - fpc: Flexible procedures for clustering.
* [frbs](http://cran.r-project.org/web/packages/frbs/index.html) - frbs: Fuzzy Rule-based Systems for Classification and Regression Tasks.
* [GAMBoost](http://cran.r-project.org/web/packages/GAMBoost/index.html) - GAMBoost: Generalized linear and additive models by likelihood based boosting.
* [gamboostLSS](http://cran.r-project.org/web/packages/gamboostLSS/index.html) - gamboostLSS: Boosting Methods for GAMLSS.
* [gbm](http://cran.r-project.org/web/packages/gbm/index.html) - gbm: Generalized Boosted Regression Models.
* [glmnet](http://cran.r-project.org/web/packages/glmnet/index.html) - glmnet: Lasso and elastic-net regularized generalized linear models.
* [glmpath](http://cran.r-project.org/web/packages/glmpath/index.html) - glmpath: L1 Regularization Path for Generalized Linear Models and Cox Proportional Hazards Model.
* [GMMBoost](http://cran.r-project.org/web/packages/GMMBoost/index.html) - GMMBoost: Likelihood-based Boosting for Generalized mixed models.
* [grplasso](http://cran.r-project.org/web/packages/grplasso/index.html) - grplasso: Fitting user specified models with Group Lasso penalty.
* [grpreg](http://cran.r-project.org/web/packages/grpreg/index.html) - grpreg: Regularization paths for regression models with grouped covariates.
* [h2o](http://cran.r-project.org/web/packages/h2o/index.html) - A framework for fast, parallel, and distributed machine learning algorithms at scale -- Deeplearning, Random forests, GBM, KMeans, PCA, GLM.
* [hda](http://cran.r-project.org/web/packages/hda/index.html) - hda: Heteroscedastic Discriminant Analysis.
* [Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)
* [ipred](http://cran.r-project.org/web/packages/ipred/index.html) - ipred: Improved Predictors.
* [kernlab](http://cran.r-project.org/web/packages/kernlab/index.html) - kernlab: Kernel-based Machine Learning Lab.
* [klaR](http://cran.r-project.org/web/packages/klaR/index.html) - klaR: Classification and visualization.
* [lars](http://cran.r-project.org/web/packages/lars/index.html) - lars: Least Angle Regression, Lasso and Forward Stagewise.
* [lasso2](http://cran.r-project.org/web/packages/lasso2/index.html) - lasso2: L1 constrained estimation aka ‘lasso’.
* [LiblineaR](http://cran.r-project.org/web/packages/LiblineaR/index.html) - LiblineaR: Linear Predictive Models Based On The Liblinear C/C++ Library.
* [LogicReg](http://cran.r-project.org/web/packages/LogicReg/index.html) - LogicReg: Logic Regression.
* [Machine Learning For Hackers](https://github.com/johnmyleswhite/ML_for_Hackers) :star:3302
* [maptree](http://cran.r-project.org/web/packages/maptree/index.html) - maptree: Mapping, pruning, and graphing tree models.
* [mboost](http://cran.r-project.org/web/packages/mboost/index.html) - mboost: Model-Based Boosting.
* [medley](https://www.kaggle.com/forums/f/15/kaggle-forum/t/3661/medley-a-new-r-package-for-blending-regression-models?forumMessageId=21278) - medley: Blending regression models, using a greedy stepwise approach.
* [mlr](http://cran.r-project.org/web/packages/mlr/index.html) - mlr: Machine Learning in R.
* [mvpart](http://cran.r-project.org/web/packages/mvpart/index.html) - mvpart: Multivariate partitioning.
* [ncvreg](http://cran.r-project.org/web/packages/ncvreg/index.html) - ncvreg: Regularization paths for SCAD- and MCP-penalized regression models.
* [nnet](http://cran.r-project.org/web/packages/nnet/index.html) - nnet: Feed-forward Neural Networks and Multinomial Log-Linear Models.
* [oblique.tree](http://cran.r-project.org/web/packages/oblique.tree/index.html) - oblique.tree: Oblique Trees for Classification Data.
* [pamr](http://cran.r-project.org/web/packages/pamr/index.html) - pamr: Pam: prediction analysis for microarrays.
* [party](http://cran.r-project.org/web/packages/party/index.html) - party: A Laboratory for Recursive Partytioning.
* [partykit](http://cran.r-project.org/web/packages/partykit/index.html) - partykit: A Toolkit for Recursive Partytioning.
* [penalized](http://cran.r-project.org/web/packages/penalized/index.html) - penalized: L1 (lasso and fused lasso) and L2 (ridge) penalized estimation in GLMs and in the Cox model.
* [penalizedLDA](http://cran.r-project.org/web/packages/penalizedLDA/index.html) - penalizedLDA: Penalized classification using Fisher's linear discriminant.
* [penalizedSVM](http://cran.r-project.org/web/packages/penalizedSVM/index.html) - penalizedSVM: Feature Selection SVM using penalty functions.
* [quantregForest](http://cran.r-project.org/web/packages/quantregForest/index.html) - quantregForest: Quantile Regression Forests.
* [randomForest](http://cran.r-project.org/web/packages/randomForest/index.html) - randomForest: Breiman and Cutler's random forests for classification and regression.
* [randomForestSRC](http://cran.r-project.org/web/packages/randomForestSRC/index.html) - randomForestSRC: Random Forests for Survival, Regression and Classification (RF-SRC).
* [rattle](http://cran.r-project.org/web/packages/rattle/index.html) - rattle: Graphical user interface for data mining in R.
* [rda](http://cran.r-project.org/web/packages/rda/index.html) - rda: Shrunken Centroids Regularized Discriminant Analysis.
* [rdetools](http://cran.r-project.org/web/packages/rdetools/index.html) - rdetools: Relevant Dimension Estimation (RDE) in Feature Spaces.
* [REEMtree](http://cran.r-project.org/web/packages/REEMtree/index.html) - REEMtree: Regression Trees with Random Effects for Longitudinal (Panel) Data.
* [relaxo](http://cran.r-project.org/web/packages/relaxo/index.html) - relaxo: Relaxed Lasso.
* [rgenoud](http://cran.r-project.org/web/packages/rgenoud/index.html) - rgenoud: R version of GENetic Optimization Using Derivatives
* [rgp](http://cran.r-project.org/web/packages/rgp/index.html) - rgp: R genetic programming framework.
* [Rmalschains](http://cran.r-project.org/web/packages/Rmalschains/index.html) - Rmalschains: Continuous Optimization using Memetic Algorithms with Local Search Chains (MA-LS-Chains) in R.
* [rminer](http://cran.r-project.org/web/packages/rminer/index.html) - rminer: Simpler use of data mining methods (e.g. NN and SVM) in classification and regression.
* [ROCR](http://cran.r-project.org/web/packages/ROCR/index.html) - ROCR: Visualizing the performance of scoring classifiers.
* [RoughSets](http://cran.r-project.org/web/packages/RoughSets/index.html) - RoughSets: Data Analysis Using Rough Set and Fuzzy Rough Set Theories.
* [rpart](http://cran.r-project.org/web/packages/rpart/index.html) - rpart: Recursive Partitioning and Regression Trees.
* [RPMM](http://cran.r-project.org/web/packages/RPMM/index.html) - RPMM: Recursively Partitioned Mixture Model.
* [RSNNS](http://cran.r-project.org/web/packages/RSNNS/index.html) - RSNNS: Neural Networks in R using the Stuttgart Neural Network Simulator (SNNS).
* [RWeka](http://cran.r-project.org/web/packages/RWeka/index.html) - RWeka: R/Weka interface.
* [RXshrink](http://cran.r-project.org/web/packages/RXshrink/index.html) - RXshrink: Maximum Likelihood Shrinkage via Generalized Ridge or Least Angle Regression.
* [sda](http://cran.r-project.org/web/packages/sda/index.html) - sda: Shrinkage Discriminant Analysis and CAT Score Variable Selection.
* [SDDA](http://cran.r-project.org/web/packages/SDDA/index.html) - SDDA: Stepwise Diagonal Discriminant Analysis.
* [SuperLearner](https://github.com/ecpolley/SuperLearner) and [subsemble](http://cran.r-project.org/web/packages/subsemble/index.html) - Multi-algorithm ensemble learning packages.
* [svmpath](http://cran.r-project.org/web/packages/svmpath/index.html) - svmpath: svmpath: the SVM Path algorithm.
* [tgp](http://cran.r-project.org/web/packages/tgp/index.html) - tgp: Bayesian treed Gaussian process models.
* [tree](http://cran.r-project.org/web/packages/tree/index.html) - tree: Classification and regression trees.
* [varSelRF](http://cran.r-project.org/web/packages/varSelRF/index.html) - varSelRF: Variable selection using random forests.
* [XGBoost.R](https://github.com/tqchen/xgboost/tree/master/R-package) - R binding for eXtreme Gradient Boosting (Tree) Library.
* [Optunity](http://optunity.readthedocs.io/en/latest/) - A library dedicated to automated hyperparameter optimization with a simple, lightweight API to facilitate drop-in replacement of grid search. Optunity is written in Python but interfaces seamlessly to R.
* [igraph](http://igraph.org/r/) - binding to igraph library - General purpose graph library.
* [MXNet](https://github.com/dmlc/mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more. :star:13791
* [TDSP-Utilities](https://github.com/Azure/Azure-TDSP-Utilities) - Two data science utilities in R from Microsoft: 1) Interactive Data Exploration, Analysis, and Reporting (IDEAR) ; 2) Automated Modeling and Reporting (AMR). :star:192

<a name="r-data-analysis"></a>
#### Data Analysis / Data Visualization

* [ggplot2](http://ggplot2.org/) - A data visualization package based on the grammar of graphics.

<a name="sas"></a>
## SAS

<a name="sas-general-purpose"></a>
#### General-Purpose Machine Learning

* [Visual Data Mining and Machine Learning](https://www.sas.com/vdmml) - Interactive, automated, and programmatic modeling with the latest machine learning algorithms in and end-to-end analytics environment, from data prep to deployment. Free trial available.
* [Enterprise Miner](https://www.sas.com/en_us/software/enterprise-miner.html) - Data mining and machine learning that creates deployable models using a GUI or code.
* [Factory Miner](https://www.sas.com/en_us/software/factory-miner.html) - Automatically creates deployable machine learning models across numerous market or customer segments using a GUI.

<a name="sas-data-analysis"></a>
#### Data Analysis / Data Visualization

* [SAS/STAT](https://www.sas.com/en_us/software/analytics/stat.html) - For conducting advanced statistical analysis.
* [University Edition](https://www.sas.com/en_us/software/university-edition.html) - FREE! Includes all SAS packages necessary for data analysis and visualization, and includes online SAS courses.

<a name="sas-mpp"></a>
#### High Performance Machine Learning

* [High Performance Data Mining](https://www.sas.com/en_us/software/analytics/high-performance-data-mining.html) - Data mining and machine learning that creates deployable models using a GUI or code in an MPP environment, including Hadoop.
* [High Performance Text Mining](https://www.sas.com/en_us/software/analytics/high-performance-text-mining.html) - Text mining using a GUI or code in an MPP environment, including Hadoop.

<a name="sas-nlp"></a>
#### Natural Language Processing

* [Contextual Analysis](https://www.sas.com/en_us/software/analytics/contextual-analysis.html) - Add structure to unstructured text using a GUI.
* [Sentiment Analysis](https://www.sas.com/en_us/software/analytics/sentiment-analysis.html) - Extract sentiment from text using a GUI.
* [Text Miner](https://www.sas.com/en_us/software/analytics/text-miner.html) - Text mining using a GUI or code.

<a name="sas-demos"></a>
#### Demos and Scripts

* [ML_Tables](https://github.com/sassoftware/enlighten-apply/tree/master/ML_tables) - Concise cheat sheets containing machine learning best practices.
* [enlighten-apply](https://github.com/sassoftware/enlighten-apply) - Example code and materials that illustrate applications of SAS machine learning techniques. :star:91
* [enlighten-integration](https://github.com/sassoftware/enlighten-integration) - Example code and materials that illustrate techniques for integrating SAS with other analytics technologies in Java, PMML, Python and R. :star:42
* [enlighten-deep](https://github.com/sassoftware/enlighten-deep) - Example code and materials that illustrate using neural networks with several hidden layers in SAS. :star:13
* [dm-flow](https://github.com/sassoftware/dm-flow) - Library of SAS Enterprise Miner process flow diagrams to help you learn by example about specific data mining topics. :star:38


<a name="scala"></a>
## Scala

<a name="scala-nlp"></a>
#### Natural Language Processing

* [ScalaNLP](http://www.scalanlp.org/) - ScalaNLP is a suite of machine learning and numerical computing libraries.
* [Breeze](https://github.com/scalanlp/breeze) - Breeze is a numerical processing library for Scala. :star:2542
* [Chalk](https://github.com/scalanlp/chalk) - Chalk is a natural language processing library. :star:251
* [FACTORIE](https://github.com/factorie/factorie) - FACTORIE is a toolkit for deployable probabilistic modeling, implemented as a software library in Scala. It provides its users with a succinct language for creating relational factor graphs, estimating parameters and performing inference. :star:526
* [Montague](https://github.com/Workday/upshot-montague) - Montague is a semantic parsing library for Scala with an easy-to-use DSL. :star:32

<a name="scala-data-analysis"></a>
#### Data Analysis / Data Visualization

* [MLlib in Apache Spark](http://spark.apache.org/docs/latest/mllib-guide.html) - Distributed machine learning library in Spark
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) - a service for deployment Apache Spark MLLib machine learning models as realtime, batch or reactive web services. :star:171
* [Scalding](https://github.com/twitter/scalding) - A Scala API for Cascading. :star:2988
* [Summing Bird](https://github.com/twitter/summingbird) - Streaming MapReduce with Scalding and Storm. :star:1938
* [Algebird](https://github.com/twitter/algebird) - Abstract Algebra for Scala. :star:1654
* [xerial](https://github.com/xerial/xerial) - Data management utilities for Scala. :star:16
* [PredictionIO](https://github.com/apache/incubator-predictionio) - PredictionIO, a machine learning server for software developers and data engineers. :star:11244
* [BIDMat](https://github.com/BIDData/BIDMat) - CPU and GPU-accelerated matrix library intended to support large-scale exploratory data analysis. :star:250
* [Flink](http://flink.apache.org/) - Open source platform for distributed stream and batch data processing.
* [Spark Notebook](http://spark-notebook.io) - Interactive and Reactive Data Science using Scala and Spark.

<a name="scala-general-purpose"></a>
#### General-Purpose Machine Learning

* [DeepLearning.scala](http://deeplearning.thoughtworks.school/) - Creating statically typed dynamic neural networks from object-oriented & functional programming constructs.
* [Conjecture](https://github.com/etsy/Conjecture) - Scalable Machine Learning in Scalding. :star:350
* [brushfire](https://github.com/stripe/brushfire) - Distributed decision tree ensemble learning in Scala. :star:369
* [ganitha](https://github.com/tresata/ganitha) - Scalding powered machine learning. :star:111
* [adam](https://github.com/bigdatagenomics/adam) - A genomics processing engine and specialized file format built using Apache Avro, Apache Spark and Parquet. Apache 2 licensed. :star:716
* [bioscala](https://github.com/bioscala/bioscala) - Bioinformatics for the Scala programming language :star:96
* [BIDMach](https://github.com/BIDData/BIDMach) - CPU and GPU-accelerated Machine Learning Library. :star:841
* [Figaro](https://github.com/p2t2/figaro) - a Scala library for constructing probabilistic models. :star:608
* [H2O Sparkling Water](https://github.com/h2oai/sparkling-water) - H2O and Spark interoperability. :star:624
* [FlinkML in Apache Flink](https://ci.apache.org/projects/flink/flink-docs-master/apis/batch/libs/ml/index.html) - Distributed machine learning library in Flink.
* [DynaML](https://github.com/transcendent-ai-labs/DynaML) - Scala Library/REPL for Machine Learning Research. :star:143
* [Saul](https://github.com/IllinoisCogComp/saul/) - Flexible Declarative Learning-Based Programming. :star:50
* [SwiftLearner](https://github.com/valdanylchuk/swiftlearner/) - Simply written algorithms to help study ML or write your own implementations.
* [Smile](http://haifengl.github.io/smile/) - Statistical Machine Intelligence and Learning Engine.

<a name="swift"></a>
## Swift

<a name="swift-general-purpose"></a>
#### General-Purpose Machine Learning

* [Bender](https://github.com/xmartlabs/Bender) - Fast Neural Networks framework built on top of Metal. Supports TensorFlow models. :star:1493
* [Swift AI](https://github.com/collinhundley/Swift-AI) - Highly optimized artificial intelligence and machine learning library written in Swift. :star:5332
* [BrainCore](https://github.com/aleph7/BrainCore) - The iOS and OS X neural network framework. :star:365
* [swix](https://github.com/stsievert/swix) - A bare bones library that :star:541
  includes a general matrix language and wraps some OpenCV for iOS development.
* [DeepLearningKit](http://deeplearningkit.org/) an Open Source Deep Learning Framework for Apple’s iOS, OS X and tvOS.
  It currently allows using deep convolutional neural network models trained in Caffe on Apple operating systems.
* [AIToolbox](https://github.com/KevinCoble/AIToolbox) - A toolbox framework of AI modules written in Swift:  Graphs/Trees, Linear Regression, Support Vector Machines, Neural Networks, PCA, KMeans, Genetic Algorithms, MDP, Mixture of Gaussians. :star:676
* [MLKit](https://github.com/Somnibyte/MLKit) - A simple Machine Learning Framework written in Swift. Currently features Simple Linear Regression, Polynomial Regression, and Ridge Regression. :star:99
* [Swift Brain](https://github.com/vlall/Swift-Brain) - The first neural network / machine learning library written in Swift. This is a project for AI algorithms in Swift for iOS and OS X development. This project includes algorithms focused on Bayes theorem, neural networks, SVMs, Matrices, etc... :star:312
* [Perfect TensorFlow](https://github.com/PerfectlySoft/Perfect-TensorFlow) - Swift Language Bindings of TensorFlow. Using native TensorFlow models on both macOS / Linux. :star:134
* [Awesome CoreML](https://github.com/NilStack/awesome-CoreML-models) - A curated list of pretrained CoreML models. :star:351
* [Awesome Core ML Models](https://github.com/likedan/Awesome-CoreML-Models) - A curated list of machine learning models in CoreML format. :star:2656

<a name="tensor"></a>
## TensorFlow

<a name="tensor-general-purpose"></a>
#### General-Purpose Machine Learning
* [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) - A list of all things related to TensorFlow. :star:11447

<a name="credits"></a>
## Credits

* Some of the python libraries were cut-and-pasted from [vinta](https://github.com/vinta/awesome-python)
* The few go reference I found where pulled from [this page](https://github.com/golang/go/wiki/Projects)


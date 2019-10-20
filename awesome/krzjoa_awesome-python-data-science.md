# Information comes from [krzjoa/awesome-python-data-science](https://github.com/krzjoa/awesome-python-data-science)
<div align="center">
	<a href="https://krzjoa.github.io/awesome-python-data-science/"><img width="250" height="250" src="img/py-datascience.png" alt="pyds"></a>
	<br>
	<br>
	<br>
</div>

<h1 align="center">
	Awesome Python Data Science
</h1>
<div align="center"><a href="https://github.com/sindresorhus/awesome">
<img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome" border="0">
</a>
</div>
</br>

> Probably the best curated list of data science software in Python

## Contents
* [Machine Learning](#machine-learning)
* [Deep Learning](#deep-learning)
* [Data Manipulation](#data-manipulation)
* [Feature Engineering](#feature-engineering)
* [Visualization](#visualization)
* [Model Explanation](#model-explanation)
* [Reinforcement Learning](#reinforcement-learning)
* [Probabilistic Methods](#probabilistic-methods)
* [Genetic Programming](#genetic-programming)
* [Optimization](#optimization)
* [Natural Language Processing](#natural-language-processing)
* [Computer Audition](#computer-audition)
* [Computer Vision](#computer-vision)
* [Statistics](#statistics)
* [Distributed Computing](#distributed-computing)
* [Experimentation](#experimentation)
* [Evaluation](#evaluation)
* [Computations](#computations)
* [Spatial Analysis](#spatial-analysis)
* [Quantum Computing](#quantum-computing)
* [Conversion](#conversion)

## Machine Learning

### General Purpouse Machine Learning
* [scikit-learn](http://scikit-learn.org/stable/) - Machine learning in Python. <img height="20" src="img/sklearn_big.png" alt="sklearn">
* [Shogun](http://www.shogun-toolbox.org/) - Machine learning toolbox.
* [xLearn](https://github.com/aksnzhy/xlearn) - High Performance, Easy-to-use, and Scalable Machine Learning Package. :star:2528
* [cuML](https://github.com/rapidsai/cuml) - RAPIDS Machine Learning Library. <img height="20" src="img/sklearn_big.png" alt="sklearn"> <img height="20" src="img/gpu_big.png" alt="GPU accelerated"> :star:762
* [modAL](https://github.com/cosmic-cortex/modAL) - Modular active learning framework for Python3. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:547
* [Sparkit-learn](https://github.com/lensacom/sparkit-learn) - PySpark + scikit-learn = Sparkit-learn. <img height="20" src="img/sklearn_big.png" alt="sklearn"> <img height="20" src="img/spark_big.png" alt="Apache Spark based"> :star:984
* [mlpack](https://github.com/mlpack/mlpack) - A scalable C++ machine learning library (Python bindings). :star:2974
* [dlib](https://github.com/davisking/dlib) - Toolkit for making real world machine learning and data analysis applications in C++ (Python bindings). :star:8041
* [MLxtend](https://github.com/rasbt/mlxtend) - Extension and helper modules for Python's data analysis and machine learning libraries. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:2567
* [hyperlearn](https://github.com/danielhanchen/hyperlearn) - 50%+ Faster, 50%+ less RAM usage, GPU support re-written Sklearn, Statsmodels. <img height="20" src="img/sklearn_big.png" alt="sklearn"> <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:1104
* [Reproducible Experiment Platform (REP)](https://github.com/yandex/rep) - Machine Learning toolbox for Humans. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:576
* [scikit-multilearn](https://github.com/scikit-multilearn/scikit-multilearn) - Multi-label classification for python. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:432
* [seqlearn](https://github.com/larsmans/seqlearn) - Sequence classification toolkit for Python. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:502
* [pystruct](https://github.com/pystruct/pystruct) - Simple structured learning framework for Python. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:611
* [sklearn-expertsys](https://github.com/tmadl/sklearn-expertsys) - Highly interpretable classifiers for scikit learn, producing easily understood decision rules instead of black box models. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:420
* [RuleFit](https://github.com/christophM/rulefit) - Implementation of the rulefit. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:135
* [metric-learn](https://github.com/all-umass/metric-learn) - Metric learning algorithms in Python. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:855
* [pyGAM](https://github.com/dswah/pyGAM) - Generalized Additive Models in Python. :star:394

### Time Series
* [tslearn](https://github.com/rtavenar/tslearn) - Machine learning toolkit dedicated to time-series data. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:752
* [tick](https://github.com/X-DataInitiative/tick) - Module for statistical learning, with a particular emphasis on time-dependent modelling.  <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:247
* [Prophet](https://github.com/facebook/prophet) - Automatic Forecasting Procedure. :star:9453
* [PyFlux](https://github.com/RJT1990/pyflux) - Open source time series library for Python. :star:1620
* [bayesloop](https://github.com/christophmark/bayesloop) - Probabilistic programming framework that facilitates objective model selection for time-varying parameter models. :star:63
* [luminol](https://github.com/linkedin/luminol) - Anomaly Detection and Correlation library. :star:654

### Automated Machine Learning
* [TPOT](https://github.com/rhiever/tpot) - Automated Machine Learning tool that optimizes machine learning pipelines using genetic programming. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:6351
* [auto-sklearn](https://github.com/automl/auto-sklearn) - An automated machine learning toolkit and a drop-in replacement for a scikit-learn estimator. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:3971
* [MLBox](https://github.com/AxeldeRomblay/MLBox) - A powerful Automated Machine Learning python library. :star:925

### Ensemble Methods
* [ML-Ensemble](http://ml-ensemble.com/) - High performance ensemble learning. <img height="20" src="img/sklearn_big.png" alt="sklearn">
* [Stacking](https://github.com/ikki407/stacking) - Simple and useful stacking library, written in Python. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:138
* [stacked_generalization](https://github.com/fukatani/stacked_generalization) - Library for machine learning stacking generalization. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:93
* [vecstack](https://github.com/vecxoz/vecstack) - Python package for stacking (machine learning technique). <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:421

### Imbalanced Datasets
* [imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn) - Module to perform under sampling and over sampling with various techniques. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:3851
* [imbalanced-algorithms](https://github.com/dialnd/imbalanced-algorithms) - Python-based implementations of algorithms for learning on imbalanced data. <img height="20" src="img/sklearn_big.png" alt="sklearn"> <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:135

### Random Forests
* [rpforest](https://github.com/lyst/rpforest) - A forest of random projection trees. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:178
* [sklearn-random-bits-forest](https://github.com/tmadl/sklearn-random-bits-forest) - Wrapper of the Random Bits Forest program written by (Wang et al., 2016).<img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:7
* [rgf_python](https://github.com/fukatani/rgf_python) - Python Wrapper of Regularized Greedy Forest. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:265

### Extreme Learning Machine
* [Python-ELM](https://github.com/dclambert/Python-ELM) - Extreme Learning Machine implementation in Python. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:381
* [Python Extreme Learning Machine (ELM)](https://github.com/acba/elm) - A machine learning technique used for classification/regression tasks. :star:38
* [hpelm](https://github.com/akusok/hpelm) - High performance implementation of Extreme Learning Machines (fast randomized neural networks). <img height="20" src="img/gpu_big.png" alt="GPU accelerated"> :star:139

### Kernel Methods
* [pyFM](https://github.com/coreylynch/pyFM) - Factorization machines in python. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:719
* [fastFM](https://github.com/ibayer/fastFM) - A library for Factorization Machines. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:779
* [tffm](https://github.com/geffy/tffm) - TensorFlow implementation of an arbitrary order Factorization Machine. <img height="20" src="img/sklearn_big.png" alt="sklearn"> <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:673
* [liquidSVM](https://github.com/liquidSVM/liquidSVM) - An implementation of SVMs. :star:38
* [scikit-rvm](https://github.com/JamesRitchie/scikit-rvm) - Relevance Vector Machine implementation using the scikit-learn API. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:141
* [ThunderSVM](https://github.com/Xtra-Computing/thundersvm) - A fast SVM Library on GPUs and CPUs. <img height="20" src="img/sklearn_big.png" alt="sklearn"> <img height="20" src="img/gpu_big.png" alt="GPU accelerated"> :star:1057

### Gradient Boosting
* [XGBoost](https://github.com/dmlc/xgboost) - Scalable, Portable and Distributed Gradient Boosting. <img height="20" src="img/sklearn_big.png" alt="sklearn"> <img height="20" src="img/gpu_big.png" alt="GPU accelerated"> :star:17479
* [LightGBM](https://github.com/Microsoft/LightGBM) - A fast, distributed, high performance gradient boosting. <img height="20" src="img/sklearn_big.png" alt="sklearn"> <img height="20" src="img/gpu_big.png" alt="GPU accelerated"> :star:9743
* [CatBoost](https://github.com/catboost/catboost) - An open-source gradient boosting on decision trees library. <img height="20" src="img/sklearn_big.png" alt="sklearn"> <img height="20" src="img/gpu_big.png" alt="GPU accelerated"> :star:4495
* [ThunderGBM](https://github.com/Xtra-Computing/thundergbm) - Fast GBDTs and Random Forests on GPUs. <img height="20" src="img/sklearn_big.png" alt="sklearn"> <img height="20" src="img/gpu_big.png" alt="GPU accelerated"> :star:454

## Deep Learning

### PyTorch
* [PyTorch](https://github.com/pytorch/pytorch) - Tensors and Dynamic neural networks in Python with strong GPU acceleration. <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:32867
* [torchvision](https://github.com/pytorch/vision) - Datasets, Transforms and Models specific to Computer Vision. <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:4654
* [torchtext](https://github.com/pytorch/text) - Data loaders and abstractions for text and NLP. <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:1975
* [torchaudio](https://github.com/pytorch/audio) - An audio library for PyTorch. <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:661
* [ignite](https://github.com/pytorch/ignite) - High-level library to help with training neural networks in PyTorch. <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:2234
* [PyToune](https://github.com/GRAAL-Research/pytoune) - A Keras-like framework and utilities for PyTorch. :star:258
* [skorch](https://github.com/dnouri/skorch) - A scikit-learn compatible neural network library that wraps pytorch. <img height="20" src="img/sklearn_big.png" alt="sklearn"> <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:2557
* [PyTorchNet](https://github.com/pytorch/tnt) - An abstraction to train neural networks. <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:1036
* [Aorun](https://github.com/ramon-oliveira/aorun) - Intend to implement an API similar to Keras with PyTorch as backend. <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:59
* [pytorch_geometric](https://github.com/rusty1s/pytorch_geometric) - Geometric Deep Learning Extension Library for PyTorch. <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:5436

### TensorFlow
* [TensorFlow](https://github.com/tensorflow/tensorflow) - Computation using data flow graphs for scalable machine learning by Google. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:136145
* [TensorLayer](https://github.com/zsdonghao/tensorlayer) - Deep Learning and Reinforcement Learning Library for Researcher and Engineer. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:5595
* [TFLearn](https://github.com/tflearn/tflearn) - Deep learning library featuring a higher-level API for TensorFlow. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:9291
* [Sonnet](https://github.com/deepmind/sonnet) - TensorFlow-based neural network library. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:7973
* [tensorpack](https://github.com/ppwwyyxx/tensorpack) - A Neural Net Training Interface on TensorFlow. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:4890
* [Polyaxon](https://github.com/polyaxon/polyaxon) - A platform that helps you build, manage and monitor deep learning models. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:2181
* [NeuPy](https://github.com/itdxer/neupy) - NeuPy is a Python library for Artificial Neural Networks and Deep Learning (previously: <img height="20" src="img/theano_big.png" alt="Theano compatible">). <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:590
* [tfdeploy](https://github.com/riga/tfdeploy) - Deploy tensorflow graphs for fast evaluation and export to tensorflow-less environments running numpy. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:347
* [tensorflow-upstream](https://github.com/ROCmSoftwarePlatform/tensorflow-upstream) - TensorFlow ROCm port. <img height="20" src="img/tf_big2.png" alt="sklearn"> <img height="20" src="img/amd_big.png" alt="Possible to run on AMD GPU"> :star:312
* [TensorFlow Fold](https://github.com/tensorflow/fold) - Deep learning with dynamic computation graphs in TensorFlow. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:1776
* [tensorlm](https://github.com/batzner/tensorlm) - Wrapper library for text generation / language models at char and word level with RNN. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:59
* [TensorLight](https://github.com/bsautermeister/tensorlight) - A high-level framework for TensorFlow. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:9
* [Mesh TensorFlow](https://github.com/tensorflow/mesh) - Model Parallelism Made Easier. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:331
* [Ludwig](https://github.com/uber/ludwig) - A toolbox, that allows to train and test deep learning models without the need to write code. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:5877

### Keras
* [Keras](https://keras.io) - A high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano.  <img height="20" src="img/keras_big.png" alt="Keras compatible">
* [keras-contrib](https://github.com/keras-team/keras-contrib) - Keras community contributions. <img height="20" src="img/keras_big.png" alt="Keras compatible"> :star:1240
* [Hyperas](https://github.com/maxpumperla/hyperas) - Keras + Hyperopt: A very simple wrapper for convenient hyperparameter. <img height="20" src="img/keras_big.png" alt="Keras compatible"> :star:1754
* [Elephas](https://github.com/maxpumperla/elephas) - Distributed Deep learning with Keras & Spark. <img height="20" src="img/keras_big.png" alt="Keras compatible"> :star:1288
* [Hera](https://github.com/keplr-io/hera) - Train/evaluate a Keras model, get metrics streamed to a dashboard in your browser. <img height="20" src="img/keras_big.png" alt="Keras compatible"> :star:489
* [Spektral](https://github.com/danielegrattarola/spektral) - Deep learning on graphs. <img height="20" src="img/keras_big.png" alt="Keras compatible"> :star:444
* [qkeras](https://github.com/google/qkeras) - A quantization deep learning library. <img height="20" src="img/keras_big.png" alt="Keras compatible"> :star:67

### MXNet
* [MXNet](https://github.com/apache/incubator-mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler. <img height="20" src="img/mxnet_big.png" alt="MXNet based"> :star:17896
* [Gluon](https://github.com/gluon-api/gluon-api) - A clear, concise, simple yet powerful and efficient API for deep learning (now included in MXNet). <img height="20" src="img/mxnet_big.png" alt="MXNet based"> :star:2308
* [MXbox](https://github.com/Lyken17/mxbox) - Simple, efficient and flexible vision toolbox for mxnet framework. <img height="20" src="img/mxnet_big.png" alt="MXNet based"> :star:31
* [gluon-cv](https://github.com/dmlc/gluon-cv) - Provides implementations of the state-of-the-art  deep learning models in computer vision. <img height="20" src="img/mxnet_big.png" alt="MXNet based"> :star:3086
* [gluon-nlp](https://github.com/dmlc/gluon-nlp) - NLP made easy. <img height="20" src="img/mxnet_big.png" alt="MXNet based"> :star:1783
* [Xfer](https://github.com/amzn/xfer) - Transfer Learning library for Deep Neural Networks. <img height="20" src="img/mxnet_big.png" alt="MXNet based"> :star:130
* [MXNet](https://github.com/ROCmSoftwarePlatform/mxnet) - HIP Port of MXNet. <img height="20" src="img/mxnet_big.png" alt="MXNet based"> <img height="20" src="img/amd_big.png" alt="Possible to run on AMD GPU"> :star:27

### Chainer
* [Chainer](https://github.com/chainer/chainer) - A flexible framework for neural networks. :star:5104
* [ChainerCV](https://github.com/chainer/chainercv) - A Library for Deep Learning in Computer Vision. :star:1249
* [ChainerMN](https://github.com/chainer/chainermn) - Scalable distributed deep learning with Chainer. :star:196

### Theano
**WARNING: Theano development has been stopped**
* [Theano](https://github.com/Theano/Theano) - A Python library that allows you to define, optimize, and evaluate mathematical expressions.<img height="20" src="img/theano_big.png" alt="Theano compatible"> :star:8949
* [Lasagne](https://github.com/Lasagne/Lasagne) - Lightweight library to build and train neural networks in Theano. <img height="20" src="img/theano_big.png" alt="Theano compatible"> :star:3679
* [nolearn](https://github.com/dnouri/nolearn) - A scikit-learn compatible neural network library (mainly for Lasagne). <img height="20" src="img/theano_big.png" alt="Theano compatible"> <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:931
* [Blocks](https://github.com/mila-udem/blocks) - A Theano framework for building and training neural networks. <img height="20" src="img/theano_big.png" alt="Theano compatible"> :star:1146
* [scikit-neuralnetwork](https://github.com/aigamedev/scikit-neuralnetwork) - Deep neural networks without the learning cliff. <img height="20" src="img/sklearn_big.png" alt="sklearn">  <img height="20" src="img/theano_big.png" alt="Theano compatible"> :star:1157
* [platoon](https://github.com/mila-udem/platoon) - Multi-GPU mini-framework for Theano. <img height="20" src="img/theano_big.png" alt="Theano compatible"> :star:197
* [Theano-MPI](https://github.com/uoguelph-mlrg/Theano-MPI) - MPI Parallel framework for training deep learning models built in Theano. <img height="20" src="img/theano_big.png" alt="Theano compatible"> :star:53

### Others
* [CNTK](https://github.com/Microsoft/CNTK) - Microsoft Cognitive Toolkit (CNTK), an open source deep-learning toolkit. :star:16476
* [Neon](https://github.com/NervanaSystems/neon) - Intel® Nervana™ reference deep learning framework committed to best performance on all hardware. :star:3789
* [Tangent](https://github.com/google/tangent) - Source-to-Source Debuggable Derivatives in Pure Python. :star:1969
* [autograd](https://github.com/HIPS/autograd) - Efficiently computes derivatives of numpy code. :star:4317
* [Myia](https://github.com/mila-udem/myia) - Deep Learning framework (pre-alpha). :star:270
* [nnabla](https://github.com/sony/nnabla) - Neural Network Libraries by Sony. :star:2263
* [Caffe](https://github.com/BVLC/caffe) - A fast open framework for deep learning. :star:29261
* [Caffe2](https://github.com/pytorch/pytorch/tree/master/caffe2) -  A lightweight, modular, and scalable deep learning framework (now a part of PyTorch). :star:32867
* [hipCaffe](https://github.com/ROCmSoftwarePlatform/hipCaffe) - The HIP port of Caffe. <img height="20" src="img/amd_big.png" alt="Possible to run on AMD GPU"> :star:119

## Data Manipulation

### Data Containers
* [pandas](https://pandas.pydata.org/pandas-docs/stable/) - Powerful Python data analysis toolkit.
* [cuDF](https://github.com/rapidsai/cudf) - GPU DataFrame Library. <img height="20" src="img/pandas_big.png" alt="pandas compatible"> <img height="20" src="img/gpu_big.png" alt="GPU accelerated"> :star:2103
* [blaze](https://github.com/blaze/blaze) - NumPy and pandas interface to Big Data. <img height="20" src="img/pandas_big.png" alt="pandas compatible"> :star:2741
* [pandasql](https://github.com/yhat/pandasql) -  Allows you to query pandas DataFrames using SQL syntax. <img height="20" src="img/pandas_big.png" alt="pandas compatible"> :star:774
* [pandas-gbq](https://github.com/pydata/pandas-gbq) - pandas Google Big Query. <img height="20" src="img/pandas_big.png" alt="pandas compatible"> :star:164
* [xpandas](https://github.com/alan-turing-institute/xpandas) - Universal 1d/2d data containers with Transformers .functionality for data analysis by [The Alan Turing Institute](https://www.turing.ac.uk/). :star:18
* [pysparkling](https://github.com/svenkreiss/pysparkling) - A pure Python implementation of Apache Spark's RDD and DStream interfaces. <img height="20" src="img/spark_big.png" alt="Apache Spark based"> :star:202
* [Arctic](https://github.com/manahl/arctic) - High performance datastore for time series and tick data. :star:1706
* [datatable](https://github.com/h2oai/datatable) - Data.table for Python. <img height="20" src="img/R_big.png" alt="R inspired/ported lib"> :star:677
* [koalas](https://github.com/databricks/koalas) - pandas API on Apache Spark. <img height="20" src="img/pandas_big.png" alt="pandas compatible"> :star:1304
* [modin](https://github.com/modin-project/modin) - Speed up your pandas workflows by changing a single line of code. <img height="20" src="img/pandas_big.png" alt="pandas compatible"> :star:2818
* [swifter](https://github.com/jmcarpenter2/swifter) - A package which efficiently applies any function to a pandas dataframe or series in the fastest available manner. :star:589
* [pandas_flavor](https://github.com/Zsailer/pandas_flavor) - A package which allow to write your own flavor of Pandas easily. :star:100

### Pipelines
* [pdpipe](https://github.com/shaypal5/pdpipe) - Sasy pipelines for pandas DataFrames. :star:292
* [SSPipe](https://sspipe.github.io/) - Python pipe (|) operator with support for DataFrames and Numpy and Pytorch.
* [pandas-ply](https://github.com/coursera/pandas-ply) - Functional data manipulation for pandas. <img height="20" src="img/pandas_big.png" alt="pandas compatible"> :star:169
* [Dplython](https://github.com/dodger487/dplython) - Dplyr for Python. <img height="20" src="img/R_big.png" alt="R inspired/ported lib"> :star:695
* [sklearn-pandas](https://github.com/scikit-learn-contrib/sklearn-pandas) - pandas integration with sklearn. <img height="20" src="img/sklearn_big.png" alt="sklearn"> <img height="20" src="img/pandas_big.png" alt="pandas compatible"> :star:1996
* [Dataset](https://github.com/analysiscenter/dataset) - Helps you conveniently work with random or sequential batches of your data and define data processing. :star:116
* [pyjanitor](https://github.com/ericmjl/pyjanitor) - Clean APIs for data cleaning. <img height="20" src="img/pandas_big.png" alt="pandas compatible"> :star:379
* [meza](https://github.com/reubano/meza) - A Python toolkit for processing tabular data. :star:352
* [Prodmodel](https://github.com/prodmodel/prodmodel) - Build system for data science pipelines. :star:31

## Feature Engineering

### General
* [Featuretools](https://github.com/Featuretools/featuretools) - Automated feature engineering. :star:4224
* [skl-groups](https://github.com/dougalsutherland/skl-groups) - A scikit-learn addon to operate on set/"group"-based features. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:39
* [Feature Forge](https://github.com/machinalis/featureforge) - A set of tools for creating and testing machine learning feature. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:364
* [few](https://github.com/lacava/few) - A feature engineering wrapper for sklearn. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:38
* [scikit-mdr](https://github.com/EpistasisLab/scikit-mdr) - A sklearn-compatible Python implementation of Multifactor Dimensionality Reduction (MDR) for feature construction. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:103
* [tsfresh](https://github.com/blue-yonder/tsfresh) - Automatic extraction of relevant features from time series. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:4240

### Feature Selection
* [scikit-feature](https://github.com/jundongl/scikit-feature) - Feature selection repository in python. :star:824
* [boruta_py](https://github.com/scikit-learn-contrib/boruta_py) - Implementations of the Boruta all-relevant feature selection method. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:597
* [BoostARoota](https://github.com/chasedehan/BoostARoota) - A fast xgboost feature selection algorithm. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:122
* [scikit-rebate](https://github.com/EpistasisLab/scikit-rebate) - A scikit-learn-compatible Python implementation of ReBATE, a suite of Relief-based feature selection algorithms for Machine Learning. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:210

## Visualization
* [Matplotlib](https://github.com/matplotlib/matplotlib) - Plotting with Python. :star:10203
* [seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization using matplotlib. :star:6487
* [Bokeh](https://github.com/bokeh/bokeh) - Interactive Web Plotting for Python. :star:11783
* [HoloViews](https://github.com/ioam/holoviews) - Stop plotting your data - annotate your data and let it visualize itself. :star:1346
* [prettyplotlib](https://github.com/olgabot/prettyplotlib) - Painlessly create beautiful matplotlib plots. :star:1487
* [python-ternary](https://github.com/marcharper/python-ternary) - Ternary plotting library for python with matplotlib. :star:240
* [missingno](https://github.com/ResidentMario/missingno) - Missing data visualization module for Python. :star:1827
* [chartify](https://github.com/spotify/chartify/) - Python library that makes it easy for data scientists to create charts. :star:2241
* [physt](https://github.com/janpipek/physt) - Improved histograms. :star:88
* [animatplot](https://github.com/t-makaro/animatplot) - A python package for animating plots build on matplotlib. :star:324

## Model Explanation
* [Alibi](https://github.com/SeldonIO/alibi) - Algorithms for monitoring and explaining machine learning models. :star:337
* [anchor](https://github.com/marcotcr/anchor) - Code for "High-Precision Model-Agnostic Explanations" paper. :star:480
* [aequitas](https://github.com/dssg/aequitas) - Bias and Fairness Audit Toolkit. :star:167
* [Contrastive Explanation](https://github.com/MarcelRobeer/ContrastiveExplanation) - Contrastive Explanation (Foil Trees). <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:17
* [yellowbrick](https://github.com/DistrictDataLabs/yellowbrick) - Visual analysis and diagnostic tools to facilitate machine learning model selection. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:2421
* [scikit-plot](https://github.com/reiinakano/scikit-plot) - An intuitive library to add plotting functionality to scikit-learn objects. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:1723
* [shap](https://github.com/slundberg/shap) - A unified approach to explain the output of any machine learning model. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:6752
* [ELI5](https://github.com/TeamHG-Memex/eli5) - A library for debugging/inspecting machine learning classifiers and explaining their predictions. :star:1694
* [Lime](https://github.com/marcotcr/lime) - Explaining the predictions of any machine learning classifier. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:6604
* [FairML](https://github.com/adebayoj/fairml) - FairML is a python toolbox auditing the machine learning models for bias. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:244
* [L2X](https://github.com/Jianbo-Lab/L2X) - Code for replicating the experiments in the paper *Learning to Explain: An Information-Theoretic Perspective on Model Interpretation*. :star:57
* [PDPbox](https://github.com/SauceCat/PDPbox) - Partial dependence plot toolbox. :star:368
* [pyBreakDown](https://github.com/MI2DataLab/pyBreakDown) - Python implementation of R package breakDown. <img height="20" src="img/sklearn_big.png" alt="sklearn"><img height="20" src="img/R_big.png" alt="R inspired/ported lib"> :star:31
* [PyCEbox](https://github.com/AustinRochford/PyCEbox) - Python Individual Conditional Expectation Plot Toolbox. :star:85
* [Skater](https://github.com/datascienceinc/Skater) - Python Library for Model Interpretation. :star:837
* [model-analysis](https://github.com/tensorflow/model-analysis) - Model analysis tools for TensorFlow. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:865
* [themis-ml](https://github.com/cosmicBboy/themis-ml) - A library that implements fairness-aware machine learning algorithms. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:51
* [treeinterpreter](https://github.com/andosa/treeinterpreter) - Interpreting scikit-learn's decision tree and random forest predictions. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:510
* [AI Explainability 360](https://github.com/IBM/AIX360) - Interpretability and explainability of data and machine learning models. :star:366
* [Auralisation](https://github.com/keunwoochoi/Auralisation) - Auralisation of learned features in CNN (for audio). :star:35
* [CapsNet-Visualization](https://github.com/bourdakos1/CapsNet-Visualization) - A visualization of the CapsNet layers to better understand how it works. :star:322
* [lucid](https://github.com/tensorflow/lucid) - A collection of infrastructure and tools for research in neural network interpretability. :star:3130
* [Netron](https://github.com/lutzroeder/Netron) - Visualizer for deep learning and machine learning models (no Python code, but visualizes models from most Python Deep Learning frameworks). :star:6594
* [FlashLight](https://github.com/dlguys/flashlight) - Visualization Tool for your NeuralNetwork. :star:30
* [tensorboard-pytorch](https://github.com/lanpa/tensorboard-pytorch) - Tensorboard for pytorch (and chainer, mxnet, numpy, ...). :star:5717
* [mxboard](https://github.com/awslabs/mxboard) - Logging MXNet data for visualization in TensorBoard. <img height="20" src="img/mxnet_big.png" alt="MXNet based"> :star:296

## Reinforcement Learning
* [OpenAI Gym](https://github.com/openai/gym) - A toolkit for developing and comparing reinforcement learning algorithms. :star:18477
* [Coach](https://github.com/NervanaSystems/coach) - Easy experimentation with state of the art Reinforcement Learning algorithms. :star:1494
* [garage](https://github.com/rlworkgroup/garage) - A toolkit for reproducible reinforcement learning research. :star:494
* [OpenAI Baselines](https://github.com/openai/baselines) - High-quality implementations of reinforcement learning algorithms. :star:8622
* [Stable Baselines](https://github.com/hill-a/stable-baselines) - A set of improved implementations of reinforcement learning algorithms based on OpenAI Baselines. :star:1294
* [RLlib](https://ray.readthedocs.io/en/latest/rllib.html) - Scalable Reinforcement Learning.
* [Horizon](https://github.com/facebookresearch/Horizon) - A platform for Applied Reinforcement Learning. :star:2179
* [TF-Agents](https://github.com/tensorflow/agents) - A library for Reinforcement Learning in TensorFlow. <img height="20" src="img/tf_big2.png" alt="sklearn">   :star:946
* [TensorForce](https://github.com/reinforceio/tensorforce) - A TensorFlow library for applied reinforcement learning. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:2466
* [TRFL](https://github.com/deepmind/trfl) - TensorFlow Reinforcement Learning. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:2757
* [Dopamine](https://github.com/google/dopamine) - A research framework for fast prototyping of reinforcement learning algorithms. :star:8443
* [keras-rl](https://github.com/keras-rl/keras-rl) - Deep Reinforcement Learning for Keras. <img height="20" src="img/keras_big.png" alt="Keras compatible"> :star:4213
* [ChainerRL](https://github.com/chainer/chainerrl) - A deep reinforcement learning library built on top of Chainer. :star:746

## Distributed Computing
* [Horovod](https://github.com/uber/horovod) - Distributed training framework for TensorFlow, Keras, PyTorch, and Apache MXNet. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:7699
* [PySpark](https://spark.apache.org/docs/0.9.0/python-programming-guide.html) - Exposes the Spark programming model to Python. <img height="20" src="img/spark_big.png" alt="Apache Spark based">
* [Veles](https://github.com/Samsung/veles) - Distributed machine learning platform. :star:882
* [Jubatus](https://github.com/jubatus/jubatus) - Framework and Library for Distributed Online Machine Learning. :star:697
* [DMTK](https://github.com/Microsoft/DMTK) - Microsoft Distributed Machine Learning Toolkit. :star:2728
* [PaddlePaddle](https://github.com/PaddlePaddle/Paddle) - PArallel Distributed Deep LEarning. :star:10060
* [dask-ml](https://github.com/dask/dask-ml) - Distributed and parallel machine learning. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:542
* [Distributed](https://github.com/dask/distributed) - Distributed computation in Python. :star:885

## Probabilistic Methods
* [pomegranate](https://github.com/jmschrei/pomegranate) - Probabilistic and graphical models for Python. <img height="20" src="img/gpu_big.png" alt="GPU accelerated"> :star:2078
* [pyro](https://github.com/uber/pyro) - A flexible, scalable deep probabilistic programming library built on PyTorch. <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:5680
* [ZhuSuan](http://zhusuan.readthedocs.io/en/latest/) - Bayesian Deep Learning. <img height="20" src="img/tf_big2.png" alt="sklearn">
* [PyMC](https://github.com/pymc-devs/pymc) - Bayesian Stochastic Modelling in Python. :star:840
* [PyMC3](http://docs.pymc.io/) - Python package for Bayesian statistical modeling and Probabilistic Machine Learning. <img height="20" src="img/theano_big.png" alt="Theano compatible">
* [sampled](https://github.com/ColCarroll/sampled) - Decorator for reusable models in PyMC3. :star:43
* [Edward](http://edwardlib.org/) - A library for probabilistic modeling, inference, and criticism. <img height="20" src="img/tf_big2.png" alt="sklearn">
* [InferPy](https://github.com/PGM-Lab/InferPy) - Deep Probabilistic Modelling Made Easy.  <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:89
* [GPflow](http://gpflow.readthedocs.io/en/latest/?badge=latest) - Gaussian processes in TensorFlow. <img height="20" src="img/tf_big2.png" alt="sklearn">
* [PyStan](https://github.com/stan-dev/pystan) - Bayesian inference using the No-U-Turn sampler (Python interface). :star:721
* [gelato](https://github.com/ferrine/gelato) - Bayesian dessert for Lasagne. <img height="20" src="img/theano_big.png" alt="Theano compatible"> :star:85
* [sklearn-bayes](https://github.com/AmazaspShumik/sklearn-bayes) - Python package for Bayesian Machine Learning with scikit-learn API. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:362
* [skggm](https://github.com/skggm/skggm) - Estimation of general graphical models. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:146
* [pgmpy](https://github.com/pgmpy/pgmpy) - A python library for working with Probabilistic Graphical Models. :star:1205
* [skpro](https://github.com/alan-turing-institute/skpro) - Supervised domain-agnostic prediction framework for probabilistic modelling by [The Alan Turing Institute](https://www.turing.ac.uk/). <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:79
* [Aboleth](https://github.com/data61/aboleth) - A bare-bones TensorFlow framework for Bayesian deep learning and Gaussian process approximation. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:117
* [PtStat](https://github.com/stepelu/ptstat) - Probabilistic Programming and Statistical Inference in PyTorch. <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:105
* [PyVarInf](https://github.com/ctallec/pyvarinf) - Bayesian Deep Learning methods with Variational Inference for PyTorch. <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:278
* [emcee](https://github.com/dfm/emcee) - The Python ensemble sampling toolkit for affine-invariant MCMC. :star:955
* [hsmmlearn](https://github.com/jvkersch/hsmmlearn) - A library for hidden semi-Markov models with explicit durations. :star:32
* [pyhsmm](https://github.com/mattjj/pyhsmm) - Bayesian inference in HSMMs and HMMs. :star:429
* [GPyTorch](https://github.com/cornellius-gp/gpytorch) - A highly efficient and modular implementation of Gaussian Processes in PyTorch. <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:1532
* [MXFusion](https://github.com/amzn/MXFusion) - Modular Probabilistic Programming on MXNet. <img height="20" src="img/mxnet_big.png" alt="MXNet based"> :star:84
* [sklearn-crfsuite](https://github.com/TeamHG-Memex/sklearn-crfsuite) - A scikit-learn inspired API for CRFsuite. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:276

## Genetic Programming
* [gplearn](https://github.com/trevorstephens/gplearn) - Genetic Programming in Python. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:711
* [DEAP](https://github.com/DEAP/deap) - Distributed Evolutionary Algorithms in Python. :star:3176
* [karoo_gp](https://github.com/kstaats/karoo_gp) - A Genetic Programming platform for Python with GPU support. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:105
* [monkeys](https://github.com/hchasestevens/monkeys) - A strongly-typed genetic programming framework for Python. :star:88
* [sklearn-genetic](https://github.com/manuel-calzolari/sklearn-genetic) - Genetic feature selection module for scikit-learn. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:80

<a name="opt"></a>
## Optimization
* [Spearmint](https://github.com/HIPS/Spearmint) - Bayesian optimization. :star:1280
* [BoTorch](https://github.com/pytorch/botorch) - Bayesian optimization in PyTorch. <img height="20" src="img/pytorch_big2.png" alt="PyTorch based/compatible"> :star:1254
* [SMAC3](https://github.com/automl/SMAC3) - Sequential Model-based Algorithm Configuration. :star:417
* [Optunity](https://github.com/claesenm/optunity) - Is a library containing various optimizers for hyperparameter tuning. :star:326
* [hyperopt](https://github.com/hyperopt/hyperopt) - Distributed Asynchronous Hyperparameter Optimization in Python. :star:3879
* [hyperopt-sklearn](https://github.com/hyperopt/hyperopt-sklearn) - Hyper-parameter optimization for sklearn. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:918
* [sklearn-deap](https://github.com/rsteca/sklearn-deap) - Use evolutionary algorithms instead of gridsearch in scikit-learn. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:534
* [sigopt_sklearn](https://github.com/sigopt/sigopt_sklearn) - SigOpt wrappers for scikit-learn methods. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:70
* [Bayesian Optimization](https://github.com/fmfn/BayesianOptimization) - A Python implementation of global optimization with gaussian processes. :star:3415
* [SafeOpt](https://github.com/befelix/SafeOpt) - Safe Bayesian Optimization. :star:55
* [scikit-optimize](https://github.com/scikit-optimize/scikit-optimize) - Sequential model-based optimization with a `scipy.optimize` interface. :star:1529
* [Solid](https://github.com/100/Solid) - A comprehensive gradient-free optimization framework written in Python. :star:503
* [PySwarms](https://github.com/ljvmiranda921/pyswarms) - A research toolkit for particle swarm optimization in Python. :star:465
* [Platypus](https://github.com/Project-Platypus/Platypus) - A Free and Open Source Python Library for Multiobjective Optimization. :star:187
* [GPflowOpt](https://github.com/GPflow/GPflowOpt) - Bayesian Optimization using GPflow. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:192
* [POT](https://github.com/rflamary/POT) - Python Optimal Transport library. :star:470
* [Talos](https://github.com/autonomio/talos) - Hyperparameter Optimization for Keras Models. :star:1046
* [nlopt](https://github.com/stevengj/nlopt) - Library for nonlinear optimization (global and local, constrained or unconstrained). :star:598

## Natural Language Processing
* [NLTK](https://github.com/nltk/nltk) -  Modules, data sets, and tutorials supporting research and development in Natural Language Processing. :star:8253
* [CLTK](https://github.com/cltk/cltk) - The Classical Language Toolkik. :star:555
* [gensim](https://radimrehurek.com/gensim/) - Topic Modelling for Humans.
* [PSI-Toolkit](http://psi-toolkit.amu.edu.pl/) - A natural language processing toolkit.
* [pyMorfologik](https://github.com/dmirecki/pyMorfologik) - Python binding for <a href="https://github.com/morfologik/morfologik-stemming">Morfologik</a>. :star:14
* [skift](https://github.com/shaypal5/skift) - Scikit-learn wrappers for Python fastText. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:189
* [Phonemizer](https://github.com/bootphon/phonemizer) - Simple text to phonemes converter for multiple languages. :star:190
* [flair](https://github.com/zalandoresearch/flair) - Very simple framework for state-of-the-art NLP. :star:7424
* [spaCy](https://spacy.io/) - Industrial-Strength Natural Language Processing.

## Computer Audition
* [librosa](https://github.com/librosa/librosa) - Python library for audio and music analysis. :star:3068
* [Yaafe](https://github.com/Yaafe/Yaafe) - Audio features extraction. :star:165
* [aubio](https://github.com/aubio/aubio) - A library for audio and music analysis. :star:1493
* [Essentia](https://github.com/MTG/essentia) - Library for audio and music analysis, description and synthesis. :star:1269
* [LibXtract](https://github.com/jamiebullock/LibXtract) - A simple, portable, lightweight library of audio feature extraction functions. :star:174
* [Marsyas](https://github.com/marsyas/marsyas) - Music Analysis, Retrieval and Synthesis for Audio Signals. :star:296
* [muda](https://github.com/bmcfee/muda) - A library for augmenting annotated audio data. :star:129
* [madmom](https://github.com/CPJKU/madmom) - Python audio and music signal processing library. :star:501

## Computer Vision
* [OpenCV](https://github.com/opencv/opencv) - Open Source Computer Vision Library. :star:39175
* [scikit-image](https://github.com/scikit-image/scikit-image) - Image Processing SciKit (Toolbox for SciPy). :star:3302
* [imgaug](https://github.com/aleju/imgaug) - Image augmentation for machine learning experiments. :star:7229
* [imgaug_extension](https://github.com/cadenai/imgaug_extension) - Additional augmentations for imgaug. :star:3
* [Augmentor](https://github.com/mdbloice/Augmentor) - Image augmentation library in Python for machine learning. :star:3540
* [albumentations](https://github.com/albu/albumentations) - Fast image augmentation library and easy to use wrapper around other libraries. :star:3574

## Statistics
* [pandas_summary](https://github.com/mouradmourafiq/pandas-summary) - Extension to pandas dataframes describe function. <img height="20" src="img/pandas_big.png" alt="pandas compatible"> :star:279
* [Pandas Profiling](https://github.com/pandas-profiling/pandas-profiling) - Create HTML profiling reports from pandas DataFrame objects. <img height="20" src="img/pandas_big.png" alt="pandas compatible"> :star:3563
* [statsmodels](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python. :star:4328
* [stockstats](https://github.com/jealous/stockstats) - Supply a wrapper ``StockDataFrame`` based on the ``pandas.DataFrame`` with inline stock statistics/indicators support. :star:458
* [weightedcalcs](https://github.com/jsvine/weightedcalcs) - A pandas-based utility to calculate weighted means, medians, distributions, standard deviations, and more. :star:68
* [scikit-posthocs](https://github.com/maximtrp/scikit-posthocs) - Pairwise Multiple Comparisons Post-hoc Tests. :star:96
* [Alphalens](https://github.com/quantopian/alphalens) - Performance analysis of predictive (alpha) stock factors. :star:1075

## Distributed Computing
* [Horovod](https://github.com/uber/horovod) - Distributed training framework for TensorFlow, Keras, PyTorch, and Apache MXNet. <img height="20" src="img/tf_big2.png" alt="sklearn"> :star:7699
* [PySpark](https://spark.apache.org/docs/0.9.0/python-programming-guide.html) - Exposes the Spark programming model to Python. <img height="20" src="img/spark_big.png" alt="Apache Spark based">
* [Veles](https://github.com/Samsung/veles) - Distributed machine learning platform. :star:882
* [Jubatus](https://github.com/jubatus/jubatus) - Framework and Library for Distributed Online Machine Learning. :star:697
* [DMTK](https://github.com/Microsoft/DMTK) - Microsoft Distributed Machine Learning Toolkit. :star:2728
* [PaddlePaddle](https://github.com/PaddlePaddle/Paddle) - PArallel Distributed Deep LEarning. :star:10060
* [dask-ml](https://github.com/dask/dask-ml) - Distributed and parallel machine learning. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:542
* [Distributed](https://github.com/dask/distributed) - Distributed computation in Python. :star:885

## Experimentation
* [Sacred](https://github.com/IDSIA/sacred) - A tool to help you configure, organize, log and reproduce experiments. :star:2302
* [Xcessiv](https://github.com/reiinakano/xcessiv) - A web-based application for quick, scalable, and automated hyperparameter tuning and stacked ensembling. :star:1204
* [Persimmon](https://github.com/AlvarBer/Persimmon) - A visual dataflow programming language for sklearn. :star:167
* [Ax](https://github.com/facebook/Ax) - Adaptive Experimentation Platform. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:884

## Evaluation
* [recmetrics](https://github.com/statisticianinstilettos/recmetrics) - Library of useful metrics and plots for evaluating recommender systems. :star:82
* [Metrics](https://github.com/benhamner/Metrics) - Machine learning evaluation metric. :star:1198
* [sklearn-evaluation](https://github.com/edublancas/sklearn-evaluation) - Model evaluation made easy: plots, tables and markdown reports. <img height="20" src="img/sklearn_big.png" alt="sklearn"> :star:273
* [AI Fairness 360](https://github.com/IBM/AIF360) - Fairness metrics for datasets and ML models, explanations and algorithms to mitigate bias in datasets and models. :star:725

## Computations
* [numpy](http://www.numpy.org/) - The fundamental package needed for scientific computing with Python.
* [Dask](https://github.com/dask/dask) - Parallel computing with task scheduling. <img height="20" src="img/pandas_big.png" alt="pandas compatible"> :star:5724
* [bottleneck](https://github.com/kwgoodman/bottleneck) - Fast NumPy array functions written in C. :star:414
* [CuPy](https://github.com/cupy/cupy) - NumPy-like API accelerated with CUDA. :star:3607
* [scikit-tensor](https://github.com/mnick/scikit-tensor) - Python library for multilinear algebra and tensor factorizations. :star:363
* [numdifftools](https://github.com/pbrod/numdifftools) - Solve automatic numerical differentiation problems in one or more variables. :star:99
* [quaternion](https://github.com/moble/quaternion) - Add built-in support for quaternions to numpy. :star:260
* [adaptive](https://github.com/python-adaptive/adaptive) - Tools for adaptive and parallel samping of mathematical functions. :star:397

## Spatial Analysis
* [GeoPandas](https://github.com/geopandas/geopandas) - Python tools for geographic data. <img height="20" src="img/pandas_big.png" alt="pandas compatible"> :star:1756
* [PySal](https://github.com/pysal/pysal) - Python Spatial Analysis Library. :star:644

## Quantum Computing
* [PennyLane](https://github.com/XanaduAI/pennylane) - Quantum machine learning, automatic differentiation, and optimization of hybrid quantum-classical computations. :star:356
* [QML](https://github.com/qmlcode/qml) - A Python Toolkit for Quantum Machine Learning. :star:93

## Conversion
* [sklearn-porter](https://github.com/nok/sklearn-porter) - Transpile trained scikit-learn estimators to C, Java, JavaScript and others. :star:714
* [ONNX](https://github.com/onnx/onnx) - Open Neural Network Exchange. :star:7216
* [MMdnn](https://github.com/Microsoft/MMdnn) -  A set of tools to help users inter-operate among different deep learning frameworks. :star:4088

## Contributing
Contributions are welcome! :sunglasses: </br>
Read the <a href=https://github.com/krzjoa/awesome-python-datascience/blob/master/CONTRIBUTING.md>contribution guideline</a>.

## License
This work is licensed under the Creative Commons Attribution 4.0 International License - [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

<div align="center">
	<a href="other/deprecated.md">Deprecated Libs</a>&nbsp;&nbsp;&nbsp;
	<a href="other/waiting-room.md">Waiting Room</a>&nbsp;&nbsp;&nbsp;
<div>


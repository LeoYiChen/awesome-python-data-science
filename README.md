<div align="center">
	<img width="250" height="250" src="img/py-datascience.png" alt="pyds">
	<br>
	<br>
	<br>
</div>

<h1 align="center">
	Awesome Python Data Science
</h1>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[skl]: https://raw.githubusercontent.com/krzjoa/awesome-python-datascience/master/img/skl.png "scikit-learn compatible"
[th]: https://raw.githubusercontent.com/krzjoa/awesome-python-datascience/master/img/th.png "Theano based"
[tf]: https://raw.githubusercontent.com/krzjoa/awesome-python-datascience/master/img/tf2.png "TensorFlow based"
[pt]: https://raw.githubusercontent.com/krzjoa/awesome-python-datascience/master/img/pt2.png "PyTorch based"
[cp]: https://raw.githubusercontent.com/krzjoa/awesome-python-datascience/master/img/cupy.png "CuPy based"
[mx]: https://raw.githubusercontent.com/krzjoa/awesome-python-datascience/master/img/mxnet.png "MXNet based"
[R]: https://raw.githubusercontent.com/krzjoa/awesome-python-datascience/master/img/R.png "R inspired/ported lib"
[gpu]: https://raw.githubusercontent.com/krzjoa/awesome-python-datascience/master/img/gpu.png "GPU accelerated"
[sp]: https://raw.githubusercontent.com/krzjoa/awesome-python-datascience/master/img/spark.png "Apache Spark based"
[amd]: https://raw.githubusercontent.com/krzjoa/awesome-python-datascience/master/img/amd.png "AMD based"
[pd]: https://raw.githubusercontent.com/krzjoa/awesome-python-datascience/master/img/pandas.png "pandas based"

#### Contents:
* [Machine Learning](#ml)
  * [General Purpouse ML](#ml-gen)
  * [Time Series](#ml-ts)
  * [Automated Machine Learning](#ml-automl)
  * [Ensemble Methods](#ml-ens)
  * [Imbalanced Datasets](#imb)
  * [Random Forests](#ml-rf)
  * [Extreme Learning Machine](#ml-elm)
  * [Kernel Methods](#ml-fm)
  * [Gradient Boosting](#ml-gbt)
* [Deep Learning](#dl)
  * [Keras](#dl-keras)
  * [TensorFlow](#dl-tf)
  * [Theano](#dl-theano)
  * [PyTorch](#dl-pytorch)
  * [MXnet](#dl-mxnet)
  * [Caffe](#dl-caffe)
  * [Chainer](#dl-chainer)
  * [Others](#dl-others)
* [Data Manipulation](#data-man)
  * [Data Containers](#dm-cont)
  * [Pipelines](#dm-pipe)
* [Feature Engineering](#feat-eng)
  * [General](#fe-general)
  * [Feature Selection](#fe-selection)
* [Visualization](#vis)
* [Model Explanation](#expl)
* [Reinforcement Learning](#rl)
* [Distributed Computing](#dist)
* [Probabilistic Methods](#bayes)
* [Genetic Programming](#gp)
* [Optimization](#opt)
* [Natural Language Processing](#nlp)
* [Computer Audition](#ca)
* [Computer Vision](#cv)
* [Statistics](#stat)
* [Experimentation](#tools)
* [Evaluation](#eval)
* [Computations](#compt)
* [Spatial Analysis](#spatial)
* [Quantum Computing](#quant)
* [Conversion](#conv)

###### Legend:
![alt text][skl] - [scikit-learn](http://scikit-learn.org/stable/) compatible (or inspired) API <br/>
![alt text][pd] - [pandas](https://github.com/pandas-dev/pandas) compatible or based on <br/>
![alt text][th] - [Theano](http://deeplearning.net/software/theano/) based project <br/>
![alt text][tf] - [TensorFlow](https://www.tensorflow.org/) based project <br/>
![alt text][pt] - [PyTorch](http://pytorch.org/) based project <br/>
![alt text][cp] - [CuPy](https://github.com/cupy/cupy/) based project <br/>
![alt text][R] - [R](https://www.r-project.org/about.html) inspired/ported lib<br/>
![alt text][mx] - [MXNet](https://mxnet.apache.org/) based project <br/>
![alt text][sp] - [Apache Spark](https://spark.apache.org/) based project <br/>
![alt text][gpu] - GPU-accelerated computations (if not based on Theano, Tensorflow, PyTorch, CuPy etc.)  <br/>
![alt text][amd] - possible to run on [AMD](http://www.amd.com/en/home) GPU

<a name="ml"></a>
## Machine Learning

<a name="ml-gen"></a>
### General Purpouse Machine Learning
* [scikit-learn](http://scikit-learn.org/stable/) ![alt text][skl] - Machine learning in Python.
* [Shogun](http://www.shogun-toolbox.org/) - Machine learning toolbox.
* [xLearn](https://github.com/aksnzhy/xlearn) - High Performance, Easy-to-use, and Scalable Machine Learning Package.
* [cuML](https://github.com/rapidsai/cuml) ![alt text][skl] ![alt text][gpu]  - RAPIDS Machine Learning Library.
* [Reproducible Experiment Platform (REP)](https://github.com/yandex/rep) ![alt text][skl] - Machine Learning toolbox for Humans.
* [modAL](https://github.com/cosmic-cortex/modAL) ![alt text][skl] -  Modular active learning framework for Python3.
* [Sparkit-learn](https://github.com/lensacom/sparkit-learn) ![alt text][skl] ![alt text][sp] - PySpark + Scikit-learn = Sparkit-learn.
* [mlpack](https://github.com/mlpack/mlpack) - A scalable C++ machine learning library (Python bindings).
* [dlib](https://github.com/davisking/dlib) - Toolkit for making real world machine learning and data analysis applications in C++ (Python bindings).
* [MLxtend](https://github.com/rasbt/mlxtend) ![alt text][skl] - Extension and helper modules for Python's data analysis and machine learning libraries.
* [scikit-multilearn](https://github.com/scikit-multilearn/scikit-multilearn) ![alt text][skl] - Multi-label classification for python.
* [seqlearn](https://github.com/larsmans/seqlearn) ![alt text][skl] - Sequence classification toolkit for Python.
* [pystruct](https://github.com/pystruct/pystruct) ![alt text][skl] - Simple structured learning framework for Python.
* [sklearn-expertsys](https://github.com/tmadl/sklearn-expertsys) ![alt text][skl] - Highly interpretable classifiers for scikit learn, producing easily understood decision rules instead of black box models.
* [RuleFit](https://github.com/christophM/rulefit) ![alt text][skl] - Implementation of the rulefit.
* [metric-learn](https://github.com/all-umass/metric-learn) ![alt text][skl]  - Metric learning algorithms in Python.
* [pyGAM](https://github.com/dswah/pyGAM) - Generalized Additive Models in Python.
* [Other...](https://github.com/krzjoa/awesome-python-datascience/blob/master/other/general-ml.md)

<a name="ml-ts"></a>
### Time Series
* [tslearn](https://github.com/rtavenar/tslearn) ![alt text][skl] - Machine learning toolkit dedicated to time-series data.
* [tick](https://github.com/X-DataInitiative/tick) ![alt text][skl] - Module for statistical learning, with a particular emphasis on time-dependent modelling.  
* [Prophet](https://github.com/facebook/prophet) - Automatic Forecasting Procedure.
* [PyFlux](https://github.com/RJT1990/pyflux) - Open source time series library for Python.
* [bayesloop](https://github.com/christophmark/bayesloop) - Probabilistic programming framework that facilitates objective model selection for time-varying parameter models.
* [luminol](https://github.com/linkedin/luminol) - Anomaly Detection and Correlation library.

<a name="ml-automl"></a>
### Automated Machine Learning
* [TPOT](https://github.com/rhiever/tpot) ![alt text][skl] -  Automated Machine Learning tool that optimizes machine learning pipelines using genetic programming.
* [auto-sklearn](https://github.com/automl/auto-sklearn) ![alt text][skl] - An automated machine learning toolkit and a drop-in replacement for a scikit-learn estimator.
* [MLBox](https://github.com/AxeldeRomblay/MLBox) - A powerful Automated Machine Learning python library.

<a name="ml-ens"></a>
### Ensemble Methods
* [ML-Ensemble](http://ml-ensemble.com/) ![alt text][skl] -  High performance ensemble learning.
* [Stacking](https://github.com/ikki407/stacking) ![alt text][skl] - Simple and useful stacking library, written in Python.
* [stacked_generalization](https://github.com/fukatani/stacked_generalization) ![alt text][skl] - Library for machine learning stacking generalization.
* [vecstack](https://github.com/vecxoz/vecstack) ![alt text][skl]  - Python package for stacking (machine learning technique).

<a name="imb"></a>
### Imbalanced Datasets
* [imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn) ![alt text][skl]  - Module to perform under sampling and over sampling with various techniques.
* [imbalanced-algorithms](https://github.com/dialnd/imbalanced-algorithms) ![alt text][skl] ![alt text][tf]  - Python-based implementations of algorithms for learning on imbalanced data.

<a name="ml-rf"></a>
### Random Forests
* [rpforest](https://github.com/lyst/rpforest) ![alt text][skl]  - A forest of random projection trees.
* [Random Forest Clustering](https://github.com/joshloyal/RandomForestClustering)![alt text][skl] - Unsupervised Clustering using Random Forests.
* [sklearn-random-bits-forest](https://github.com/tmadl/sklearn-random-bits-forest)![alt text][skl] - Wrapper of the Random Bits Forest program written by (Wang et al., 2016).
* [rgf_python](https://github.com/fukatani/rgf_python) ![alt text][skl] - Python Wrapper of Regularized Greedy Forest.

<a name="ml-elm"></a>
### Extreme Learning Machine
* [Python-ELM](https://github.com/dclambert/Python-ELM) ![alt text][skl]  - Extreme Learning Machine implementation in Python.
* [Python Extreme Learning Machine (ELM)](https://github.com/acba/elm) - a machine learning technique used for classification/regression tasks.
* [hpelm](https://github.com/akusok/hpelm) ![alt text][gpu]  - High performance implementation of Extreme Learning Machines (fast randomized neural networks).

<a name="ml-fm"></a>
### Kernel Methods
* [pyFM](https://github.com/coreylynch/pyFM) ![alt text][skl] - Factorization machines in python.
* [fastFM](https://github.com/ibayer/fastFM) ![alt text][skl] - A library for Factorization Machines.
* [tffm](https://github.com/geffy/tffm) ![alt text][skl] ![alt text][tf] - TensorFlow implementation of an arbitrary order Factorization Machine.
* [liquidSVM](https://github.com/liquidSVM/liquidSVM) - An implementation of SVMs.
* [scikit-rvm](https://github.com/JamesRitchie/scikit-rvm) ![alt text][skl] - Relevance Vector Machine implementation using the scikit-learn API.
* [ThunderSVM](https://github.com/Xtra-Computing/thundersvm) ![alt text][skl] ![alt text][gpu] - A fast SVM Library on GPUs and CPUs.

<a name="ml-gbt"></a>
### Gradient Boosting
* [XGBoost](https://github.com/dmlc/xgboost) ![alt text][skl] ![alt text][gpu]  - Scalable, Portable and Distributed Gradient Boosting.
* [LightGBM](https://github.com/Microsoft/LightGBM) ![alt text][skl] ![alt text][gpu] - A fast, distributed, high performance gradient boosting by [Microsoft](https://www.microsoft.com).
* [CatBoost](https://github.com/catboost/catboost) ![alt text][skl] ![alt text][gpu] - An open-source gradient boosting on decision trees library by [Yandex](https://www.yandex.com/).
* [ThunderGBM](https://github.com/Xtra-Computing/thundergbm) ![alt text][skl] ![alt text][gpu] - Fast GBDTs and Random Forests on GPUs.
* [Other...](https://github.com/krzjoa/awesome-python-datascience/blob/master/other/gbm.md)

<a name="dl"></a>
## Deep Learning

<a name="dl-keras"></a>
### Keras
* [Keras](https://keras.io) - A high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano.
* [keras-contrib](https://github.com/keras-team/keras-contrib) - Keras community contributions.
* [Hyperas](https://github.com/maxpumperla/hyperas) - Keras + Hyperopt: A very simple wrapper for convenient hyperparameter.
* [Elephas](https://github.com/maxpumperla/elephas) - Distributed Deep learning with Keras & Spark.
* [Hera](https://github.com/keplr-io/hera) - Train/evaluate a Keras model, get metrics streamed to a dashboard in your browser.
* [dist-keras](https://github.com/cerndb/dist-keras) ![alt text][sp] - Distributed Deep Learning, with a focus on distributed training.
* [Spektral](https://github.com/danielegrattarola/spektral) - Deep learning on graphs.
* [qkeras](https://github.com/google/qkeras) - A quantization deep learning library.
* [Keras add-ons...](https://github.com/krzjoa/awesome-python-datascience/blob/master/addons/keras_addons.md)

<a name="dl-tf"></a>
### TensorFlow
* [TensorFlow](https://github.com/tensorflow/tensorflow) ![alt text][tf] - Computation using data flow graphs for scalable machine learning by Google.
* [TensorLayer](https://github.com/zsdonghao/tensorlayer) ![alt text][tf] - Deep Learning and Reinforcement Learning Library for Researcher and Engineer.
* [TFLearn](https://github.com/tflearn/tflearn) ![alt text][tf] - Deep learning library featuring a higher-level API for TensorFlow.
* [Sonnet](https://github.com/deepmind/sonnet) ![alt text][tf] - TensorFlow-based neural network library by [DeepMind](https://deepmind.com/).
* [TensorForce](https://github.com/reinforceio/tensorforce) ![alt text][tf] - A TensorFlow library for applied reinforcement learning.
* [tensorpack](https://github.com/ppwwyyxx/tensorpack) ![alt text][tf] - A Neural Net Training Interface on TensorFlow
* [Polyaxon](https://github.com/polyaxon/polyaxon) ![alt text][tf] - A platform that helps you build, manage and monitor deep learning models.
* [NeuPy](https://github.com/itdxer/neupy) ![alt text][tf] - NeuPy is a Python library for Artificial Neural Networks and Deep Learning (previously: ![alt text][th]).
* [tfdeploy](https://github.com/riga/tfdeploy) ![alt text][tf] - Deploy tensorflow graphs for fast evaluation and export to tensorflow-less environments running numpy.
* [hiptensorflow](https://github.com/ROCmSoftwarePlatform/hiptensorflow) ![alt text][tf] ![alt text][amd] - ROCm/HIP enabled Tensorflow.
* [TensorFlow Fold](https://github.com/tensorflow/fold) ![alt text][tf] - Deep learning with dynamic computation graphs in TensorFlow.
* [tensorlm](https://github.com/batzner/tensorlm) ![alt text][tf] - Wrapper library for text generation / language models at char and word level with RNN.
* [TensorLight](https://github.com/bsautermeister/tensorlight) ![alt text][tf]  - A high-level framework for TensorFlow.
* [Mesh TensorFlow](https://github.com/tensorflow/mesh) ![alt text][tf] - Model Parallelism Made Easier.
* [Ludwig](https://github.com/uber/ludwig) ![alt text][tf] - A toolbox, that allows to train and test deep learning models without the need to write code.

<a name="dl-theano"></a>
### Theano
**WARNING: Theano development has been stopped**
* [Theano](https://github.com/Theano/Theano)![alt text][th] - A Python library that allows you to define, optimize, and evaluate mathematical expressions.
* [Lasagne](https://github.com/Lasagne/Lasagne) ![alt text][th] - Lightweight library to build and train neural networks in Theano [Lasagne add-ons...](https://github.com/krzjoa/awesome-python-datascience/blob/master/addons/lasagne_addons.md)
* [nolearn](https://github.com/dnouri/nolearn) ![alt text][th] ![alt text][skl] - A scikit-learn compatible neural network library (mainly for Lasagne).
* [Blocks](https://github.com/mila-udem/blocks) ![alt text][th] - A Theano framework for building and training neural networks.
* [platoon](https://github.com/mila-udem/platoon) ![alt text][th] - Multi-GPU mini-framework for Theano.
* [scikit-neuralnetwork](https://github.com/aigamedev/scikit-neuralnetwork) ![alt text][skl]  ![alt text][th] - Deep neural networks without the learning cliff.
* [Theano-MPI](https://github.com/uoguelph-mlrg/Theano-MPI) ![alt text][th] - MPI Parallel framework for training deep learning models built in Theano.

<a name="dl-pytorch"></a>
### PyTorch
* [PyTorch](https://github.com/pytorch/pytorch) ![alt text][pt]  - Tensors and Dynamic neural networks in Python with strong GPU acceleration.
* [torchvision](https://github.com/pytorch/vision)  ![alt text][pt] - Datasets, Transforms and Models specific to Computer Vision.
* [torchtext](https://github.com/pytorch/text) ![alt text][pt] - Data loaders and abstractions for text and NLP.
* [torchaudio](https://github.com/pytorch/audio) ![alt text][pt] - An audio library for PyTorch.
* [ignite](https://github.com/pytorch/ignite) ![alt text][pt]  - High-level library to help with training neural networks in PyTorch.
* [PyToune](https://github.com/GRAAL-Research/pytoune) - A Keras-like framework and utilities for PyTorch.
* [skorch](https://github.com/dnouri/skorch) ![alt text][skl] ![alt text][pt]  - A scikit-learn compatible neural network library that wraps pytorch.
* [PyTorchNet](https://github.com/pytorch/tnt) ![alt text][pt]  - An abstraction to train neural networks
* [Aorun](https://github.com/ramon-oliveira/aorun) ![alt text][pt] - Intend to implement an API similar to Keras with PyTorch as backend.
* [pytorch_geometric](https://github.com/rusty1s/pytorch_geometric) ![alt text][pt] - Geometric Deep Learning Extension Library for PyTorch.

<a name="dl-mxnet"></a>
### MXNet
* [MXNet](https://github.com/apache/incubator-mxnet) ![alt text][mx] - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler.
* [Gluon](https://github.com/gluon-api/gluon-api) ![alt text][mx] - A clear, concise, simple yet powerful and efficient API for deep learning (now included in MXNet).
* [MXbox](https://github.com/Lyken17/mxbox) ![alt text][mx] - Simple, efficient and flexible vision toolbox for mxnet framework.
* [gluon-cv](https://github.com/dmlc/gluon-cv) ![alt text][mx] - Provides implementations of the state-of-the-art  deep learning models in computer vision.
* [gluon-nlp](https://github.com/dmlc/gluon-nlp) ![alt text][mx] - NLP made easy.
* [Xfer](https://github.com/amzn/xfer) ![alt text][mx] - Transfer Learning library for Deep Neural Networks.
* [MXNet](https://github.com/ROCmSoftwarePlatform/mxnet) ![alt text][mx] ![alt text][amd]  - HIP Port of MXNet.

<a name="dl-caffe"></a>
### Caffe
* [Caffe](https://github.com/BVLC/caffe) - a fast open framework for deep learning.
* [Caffe2](https://github.com/caffe2/caffe2) -  A lightweight, modular, and scalable deep learning framework.
* [hipCaffe](https://github.com/ROCmSoftwarePlatform/hipCaffe) ![alt text][amd] - The HIP port of Caffe.
<!--a name="dl-cntk"></a-->
<a name="dl-chainer"></a>
### Chainer
* [ChainerRL](https://github.com/chainer/chainerrl) - A deep reinforcement learning library built on top of Chainer.
* [Chainer](https://github.com/chainer/chainer) - A flexible framework for neural networks.
* [ChainerCV](https://github.com/chainer/chainercv) - A Library for Deep Learning in Computer Vision.
* [ChainerMN](https://github.com/chainer/chainermn) - Scalable distributed deep learning with Chainer.
* [scikit-chainer](https://github.com/lucidfrontier45/scikit-chainer) ![alt text][skl] - Scikit-learn like interface to chainer.
* [chainer_sklearn](https://github.com/corochann/chainer_sklearn) ![alt text][skl] - Sklearn (Scikit-learn) like interface for Chainer.

<a name="dl-others"></a>
### Others
* [CNTK](https://github.com/Microsoft/CNTK) - Microsoft Cognitive Toolkit (CNTK), an open source deep-learning toolkit.
* [Neon](https://github.com/NervanaSystems/neon) - Intel® Nervana™ reference deep learning framework committed to best performance on all hardware.
* [Tangent](https://github.com/google/tangent) - Source-to-Source Debuggable Derivatives in Pure Python.
* [autograd](https://github.com/HIPS/autograd) - Efficiently computes derivatives of numpy code.
* [Myia](https://github.com/mila-udem/myia) - Deep Learning framework (pre-alpha).
* [nnabla](https://github.com/sony/nnabla) - Neural Network Libraries by Sony.

<a name="data-man"></a>
## Data Manipulation

<a name="dm-cont"></a>
### Data Containers
* [pandas](https://pandas.pydata.org/pandas-docs/stable/) - Powerful Python data analysis toolkit.
* [cuDF](https://github.com/rapidsai/cudf) ![alt text][pd] ![alt text][gpu] - GPU DataFrame Library.
* [blaze](https://github.com/blaze/blaze) ![alt text][pd] - NumPy and Pandas interface to Big Data.
* [pandasql](https://github.com/yhat/pandasql) ![alt text][pd] -  Allows you to query pandas DataFrames using SQL syntax.
* [pandas-gbq](https://github.com/pydata/pandas-gbq) ![alt text][pd] - Pandas Google Big Query.
* [xpandas](https://github.com/alan-turing-institute/xpandas) - Universal 1d/2d data containers with Transformers .functionality for data analysis by [The Alan Turing Institute](https://www.turing.ac.uk/).
* [pysparkling](https://github.com/svenkreiss/pysparkling) ![alt text][sp] - A pure Python implementation of Apache Spark's RDD and DStream interfaces.
* [Arctic](https://github.com/manahl/arctic) - High performance datastore for time series and tick data.
* [datatable](https://github.com/h2oai/datatable) ![alt text][R] - Data.table for Python.
* [koalas](https://github.com/databricks/koalas) ![alt text][pd] - Pandas API on Apache Spark.

<a name="dm-pipe"></a>
### Pipelines
* [Fuel](https://github.com/mila-udem/fuel) - Data pipeline framework for machine learning.
* [pdpipe](https://github.com/shaypal5/pdpipe) - Sasy pipelines for pandas DataFrames.
* [SSPipe](https://sspipe.github.io/) - Python pipe (|) operator with support for DataFrames and Numpy and Pytorch.
* [meza](https://github.com/reubano/meza) - A Python toolkit for processing tabular data.
* [pandas-ply](https://github.com/coursera/pandas-ply) ![alt text][pd] - Functional data manipulation for pandas.
* [Dplython](https://github.com/dodger487/dplython) ![alt text][R] - Dplyr for Python.
* [sklearn-pandas](https://github.com/scikit-learn-contrib/sklearn-pandas) ![alt text][skl] ![alt text][pd]  - Pandas integration with sklearn.
* [quinn](https://github.com/MrPowers/quinn) ![alt text][sp]  - pyspark methods to enhance developer productivity.
* [Dataset](https://github.com/analysiscenter/dataset) - Helps you conveniently work with random or sequential batches of your data and define data processing.
* [swifter](https://github.com/jmcarpenter2/swifter) - A package which efficiently applies any function to a pandas dataframe or series in the fastest available manner.
* [pyjanitor](https://github.com/ericmjl/pyjanitor) ![alt text][pd] - Clean APIs for data cleaning.
* [modin](https://github.com/modin-project/modin) ![alt text][pd] - Speed up your Pandas workflows by changing a single line of code.
* [Prodmodel](https://github.com/prodmodel/prodmodel) - Build system for data science pipelines.


<a name="feat-eng"></a>
## Feature Engineering

<a name="fe-general"></a>
### General
* [Featuretools](https://github.com/Featuretools/featuretools) - Automated feature engineering.
* [skl-groups](https://github.com/dougalsutherland/skl-groups) ![alt text][skl] - Scikit-learn addon to operate on set/"group"-based features.
* [Feature Forge](https://github.com/machinalis/featureforge) ![alt text][skl] - A set of tools for creating and testing machine learning feature.
* [few](https://github.com/lacava/few) ![alt text][skl] - A feature engineering wrapper for sklearn.
* [scikit-mdr](https://github.com/EpistasisLab/scikit-mdr) ![alt text][skl] - A sklearn-compatible Python implementation of Multifactor Dimensionality Reduction (MDR) for feature construction..
* [tsfresh](https://github.com/blue-yonder/tsfresh) ![alt text][skl] - Automatic extraction of relevant features from time series.

<a name="fe-selection"></a>
### Feature Selection
* [scikit-feature](https://github.com/jundongl/scikit-feature) -  Feature selection repository in python.
* [boruta_py](https://github.com/scikit-learn-contrib/boruta_py) ![alt text][skl] -  Implementations of the Boruta all-relevant feature selection method.
* [BoostARoota](https://github.com/chasedehan/BoostARoota) ![alt text][skl] - A fast xgboost feature selection algorithm.
* [scikit-rebate](https://github.com/EpistasisLab/scikit-rebate) ![alt text][skl] - A scikit-learn-compatible Python implementation of ReBATE, a suite of Relief-based feature selection algorithms for Machine Learning.

<a name="vis"></a>
## Visualization
* [Matplotlib](https://github.com/matplotlib/matplotlib) - Plotting with Python.
* [seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization using matplotlib.
* [Bokeh](https://github.com/bokeh/bokeh) - Interactive Web Plotting for Python.
* [HoloViews](https://github.com/ioam/holoviews) - Stop plotting your data - annotate your data and let it visualize itself.
* [Alphalens](https://github.com/quantopian/alphalens) - Performance analysis of predictive (alpha) stock factors by [Quantopian](https://www.quantopian.com/).
* [prettyplotlib](https://github.com/olgabot/prettyplotlib) - Painlessly create beautiful matplotlib plots.
* [python-ternary](https://github.com/marcharper/python-ternary) - Ternary plotting library for python with matplotlib.
* [missingno](https://github.com/ResidentMario/missingno) - Missing data visualization module for Python.


<a name="expl"></a>
## Model Explanation
* [Alibi](https://github.com/SeldonIO/alibi) - Algorithms for monitoring and explaining machine learning models.
* [Auralisation](https://github.com/keunwoochoi/Auralisation) - Auralisation of learned features in CNN (for audio).
* [CapsNet-Visualization](https://github.com/bourdakos1/CapsNet-Visualization) - A visualization of the CapsNet layers to better understand how it works.
* [lucid](https://github.com/tensorflow/lucid) - A collection of infrastructure and tools for research in neural network interpretability.
* [Netron](https://github.com/lutzroeder/Netron) - Visualizer for deep learning and machine learning models (no Python code, but visualizes models from most Python Deep Learning frameworks).
* [FlashLight](https://github.com/dlguys/flashlight) - Visualization Tool for your NeuralNetwork.
* [tensorboard-pytorch](https://github.com/lanpa/tensorboard-pytorch) - Tensorboard for pytorch (and chainer, mxnet, numpy, ...).
* [anchor](https://github.com/marcotcr/anchor) - Code for "High-Precision Model-Agnostic Explanations" paper.
* [aequitas](https://github.com/dssg/aequitas) - Bias and Fairness Audit Toolkit.
* [Contrastive Explanation](https://github.com/MarcelRobeer/ContrastiveExplanation) ![alt text][skl] - Contrastive Explanation (Foil Trees).
* [yellowbrick](https://github.com/DistrictDataLabs/yellowbrick) ![alt text][skl]- Visual analysis and diagnostic tools to facilitate machine learning model selection.
* [scikit-plot](https://github.com/reiinakano/scikit-plot) ![alt text][skl] - An intuitive library to add plotting functionality to scikit-learn objects.
* [shap](https://github.com/slundberg/shap) ![alt text][skl] - A unified approach to explain the output of any machine learning model.
* [ELI5](https://github.com/TeamHG-Memex/eli5) - A library for debugging/inspecting machine learning classifiers and explaining their predictions.
* [Lime](https://github.com/marcotcr/lime) ![alt text][skl] - Explaining the predictions of any machine learning classifier.
* [FairML](https://github.com/adebayoj/fairml) ![alt text][skl] - FairML is a python toolbox auditing the machine learning models for bias.
* [L2X](https://github.com/Jianbo-Lab/L2X) - Code for replicating the experiments in the paper *Learning to Explain: An Information-Theoretic Perspective on Model Interpretation*.
* [PDPbox](https://github.com/SauceCat/PDPbox) - Partial dependence plot toolbox.
* [pyBreakDown](https://github.com/MI2DataLab/pyBreakDown) ![alt text][skl] - Python implementation of R package breakDown.
* [PyCEbox](https://github.com/AustinRochford/PyCEbox) - Python Individual Conditional Expectation Plot Toolbox.
* [Skater](https://github.com/datascienceinc/Skater) - Python Library for Model Interpretation.
* [model-analysis](https://github.com/tensorflow/model-analysis) ![alt text][tf] - Model analysis tools for TensorFlow.
* [themis-ml](https://github.com/cosmicBboy/themis-ml) ![alt text][skl] - A library that implements fairness-aware machine learning algorithms.
* [treeinterpreter](https://github.com/andosa/treeinterpreter) ![alt text][skl] - Interpreting scikit-learn's decision tree and random forest predictions.
* [mxboard](https://github.com/awslabs/mxboard) - Logging MXNet data for visualization in TensorBoard.
* [AI Explainability 360](https://github.com/IBM/AIX360) - Interpretability and explainability of data and machine learning models.

<a name="rl"></a>
## Reinforcement Learning
* [OpenAI Gym](https://github.com/openai/gym) - A toolkit for developing and comparing reinforcement learning algorithms.

<a name="dist"></a>
## Distributed Computing
* [Horovod](https://github.com/uber/horovod) ![alt text][tf] - Distributed training framework for TensorFlow, Keras, PyTorch, and Apache MXNet.
* [PySpark](https://spark.apache.org/docs/0.9.0/python-programming-guide.html) ![alt text][sp] - Exposes the Spark programming model to Python.
* [Veles](https://github.com/Samsung/veles) - Distributed machine learning platform by [Samsung](https://github.com/Samsung).
* [Jubatus](https://github.com/jubatus/jubatus) - Framework and Library for Distributed Online Machine Learning.
* [DMTK](https://github.com/Microsoft/DMTK) - Microsoft Distributed Machine Learning Toolkit.
* [PaddlePaddle](https://github.com/PaddlePaddle/Paddle) - PArallel Distributed Deep LEarning by [Baidu](https://www.baidu.com/).
* [dask-ml](https://github.com/dask/dask-ml) ![alt text][skl] - Distributed and parallel machine learning.
* [Distributed](https://github.com/dask/distributed) - Distributed computation in Python.

<a name="bayes"></a>
## Probabilistic Methods
* [pomegranate](https://github.com/jmschrei/pomegranate) ![alt text][cp] - Probabilistic and graphical models for Python.
* [pyro](https://github.com/uber/pyro) ![alt text][pt] - A flexible, scalable deep probabilistic programming library built on PyTorch.
* [ZhuSuan](http://zhusuan.readthedocs.io/en/latest/) ![alt text][tf] - Bayesian Deep Learning.
* [PyMC](https://github.com/pymc-devs/pymc) - Bayesian Stochastic Modelling in Python.
* [PyMC3](http://docs.pymc.io/) ![alt text][th] - Python package for Bayesian statistical modeling and Probabilistic Machine Learning.
* [sampled](https://github.com/ColCarroll/sampled) - Decorator for reusable models in PyMC3.
* [Edward](http://edwardlib.org/) ![alt text][tf] - A library for probabilistic modeling, inference, and criticism.
* [InferPy](https://github.com/PGM-Lab/InferPy)  ![alt text][tf]  - Deep Probabilistic Modelling Made Easy.
* [GPflow](http://gpflow.readthedocs.io/en/latest/?badge=latest) ![alt text][tf]  - Gaussian processes in TensorFlow.
* [PyStan](https://github.com/stan-dev/pystan) - Bayesian inference using the No-U-Turn sampler (Python interface).
* [gelato](https://github.com/ferrine/gelato) ![alt text][th] - Bayesian dessert for Lasagne.
* [sklearn-bayes](https://github.com/AmazaspShumik/sklearn-bayes) ![alt text][skl]  - Python package for Bayesian Machine Learning with scikit-learn API.
* [skggm](https://github.com/skggm/skggm) ![alt text][skl] - Estimation of general graphical models.
* [pgmpy](https://github.com/pgmpy/pgmpy) - A python library for working with Probabilistic Graphical Models.
* [skpro](https://github.com/alan-turing-institute/skpro) ![alt text][skl] - Supervised domain-agnostic prediction framework for probabilistic modelling by [The Alan Turing Institute](https://www.turing.ac.uk/).
* [Aboleth](https://github.com/data61/aboleth) ![alt text][tf]  - A bare-bones TensorFlow framework for Bayesian deep learning and Gaussian process approximation.
* [PtStat](https://github.com/stepelu/ptstat) ![alt text][pt] - Probabilistic Programming and Statistical Inference in PyTorch.
* [PyVarInf](https://github.com/ctallec/pyvarinf) ![alt text][pt] - Bayesian Deep Learning methods with Variational Inference for PyTorch.
* [emcee](https://github.com/dfm/emcee) - The Python ensemble sampling toolkit for affine-invariant MCMC.
* [hsmmlearn](https://github.com/jvkersch/hsmmlearn) - A library for hidden semi-Markov models with explicit durations.
* [pyhsmm](https://github.com/mattjj/pyhsmm) - Bayesian inference in HSMMs and HMMs.
* [GPyTorch](https://github.com/cornellius-gp/gpytorch) ![alt text][pt] - A highly efficient and modular implementation of Gaussian Processes in PyTorch.
* [MXFusion](https://github.com/amzn/MXFusion) ![alt text][mx] - Modular Probabilistic Programming on MXNet
* [sklearn-crfsuite](https://github.com/TeamHG-Memex/sklearn-crfsuite) ![alt text][skl] - Scikit-learn inspire.d API for CRFsuite.

<a name="gp"></a>
## Genetic Programming
* [gplearn](https://github.com/trevorstephens/gplearn) ![alt text][skl] - Genetic Programming in Python.
* [DEAP](https://github.com/DEAP/deap) - Distributed Evolutionary Algorithms in Python.
* [karoo_gp](https://github.com/kstaats/karoo_gp) ![alt text][tf] - A Genetic Programming platform for Python with GPU support.
* [monkeys](https://github.com/hchasestevens/monkeys) - A strongly-typed genetic programming framework for Python.
* [sklearn-genetic](https://github.com/manuel-calzolari/sklearn-genetic) ![alt text][skl] - Genetic feature selection module for scikit-learn.

<a name="opt"></a>
## Optimization
* [Spearmint](https://github.com/HIPS/Spearmint) - Bayesian optimization.
* [BoTorch](https://github.com/pytorch/botorch) ![alt text][pt] - Bayesian optimization in PyTorch.
* [SMAC3](https://github.com/automl/SMAC3) - Sequential Model-based Algorithm Configuration.
* [Optunity](https://github.com/claesenm/optunity) - Is a library containing various optimizers for hyperparameter tuning.
* [hyperopt](https://github.com/hyperopt/hyperopt) - Distributed Asynchronous Hyperparameter Optimization in Python.
* [hyperopt-sklearn](https://github.com/hyperopt/hyperopt-sklearn) ![alt text][skl]  - Hyper-parameter optimization for sklearn.
* [sklearn-deap](https://github.com/rsteca/sklearn-deap) ![alt text][skl] - Use evolutionary algorithms instead of gridsearch in scikit-learn.
* [sigopt_sklearn](https://github.com/sigopt/sigopt_sklearn) ![alt text][skl] - SigOpt wrappers for scikit-learn methods.
* [Bayesian Optimization](https://github.com/fmfn/BayesianOptimization) - A Python implementation of global optimization with gaussian processes.
* [SafeOpt](https://github.com/befelix/SafeOpt) - Safe Bayesian Optimization.
* [scikit-optimize](https://github.com/scikit-optimize/scikit-optimize) - Sequential model-based optimization with a `scipy.optimize` interface.
* [Solid](https://github.com/100/Solid) - A comprehensive gradient-free optimization framework written in Python.
* [PySwarms](https://github.com/ljvmiranda921/pyswarms) - A research toolkit for particle swarm optimization in Python.
* [Platypus](https://github.com/Project-Platypus/Platypus) - A Free and Open Source Python Library for Multiobjective Optimization.
* [GPflowOpt](https://github.com/GPflow/GPflowOpt) ![alt text][tf] - Bayesian Optimization using GPflow.
* [POT](https://github.com/rflamary/POT) - Python Optimal Transport library.
* [Talos](https://github.com/autonomio/talos) - Hyperparameter Optimization for Keras Models.
* [nlopt](https://github.com/stevengj/nlopt) - Library for nonlinear optimization (global and local, constrained or unconstrained).

<a name="nlp"></a>
## Natural Language Processing
* [NLTK](https://github.com/nltk/nltk) -  Modules, data sets, and tutorials supporting research and development in Natural Language Processing.
* [CLTK](https://github.com/cltk/cltk) - The Classical Language Toolkik.
* [gensim](https://radimrehurek.com/gensim/) - Topic Modelling for Humans.
* [PSI-Toolkit](http://psi-toolkit.amu.edu.pl/) - A natural language processing toolkit by [Adam Mickiewicz University](https://zpjn.wmi.amu.edu.pl/en/) in Poznań.
* [pyMorfologik](https://github.com/dmirecki/pyMorfologik) - Python binding for [Morfologik](https://github.com/morfologik/morfologik-stemming) (Polish morphological analyzer).
* [skift](https://github.com/shaypal5/skift) ![alt text][skl] - Scikit-learn wrappers for Python fastText.
* [Phonemizer](https://github.com/bootphon/phonemizer) - Simple text to phonemes converter for multiple languages.
* [flair](https://github.com/zalandoresearch/flair) - Very simple framework for state-of-the-art NLP by [Zalando Research](https://research.zalando.com/).

<a name="ca"></a>
## Computer Audition
* [librosa](https://github.com/librosa/librosa) - Python library for audio and music analysis.
* [Yaafe](https://github.com/Yaafe/Yaafe) - Audio features extraction.
* [aubio](https://github.com/aubio/aubio) - A library for audio and music analysis.
* [Essentia](https://github.com/MTG/essentia) - Library for audio and music analysis, description and synthesis.
* [LibXtract](https://github.com/jamiebullock/LibXtract) - A simple, portable, lightweight library of audio feature extraction functions.
* [Marsyas](https://github.com/marsyas/marsyas) - Music Analysis, Retrieval and Synthesis for Audio Signals.
* [muda](https://github.com/bmcfee/muda) - A library for augmenting annotated audio data.
* [madmom](https://github.com/CPJKU/madmom) - Python audio and music signal processing library.
* [more: Python for Scientific Audio](https://github.com/faroit/awesome-python-scientific-audio)

<a name="cv"></a>
## Computer Vision
* [OpenCV](https://github.com/opencv/opencv) - Open Source Computer Vision Library.
* [scikit-image](https://github.com/scikit-image/scikit-image) - Image Processing SciKit (Toolbox for SciPy).
* [imgaug](https://github.com/aleju/imgaug) - Image augmentation for machine learning experiments.
* [imgaug_extension](https://github.com/cadenai/imgaug_extension) - Additional augmentations for imgaug.
* [Augmentor](https://github.com/mdbloice/Augmentor) - Image augmentation library in Python for machine learning.
* [albumentations](https://github.com/albu/albumentations) - Fast image augmentation library and easy to use wrapper around other libraries.

<a name="stat"></a>

## Statistics
* [pandas_summary](https://github.com/mouradmourafiq/pandas-summary) ![alt text][pd] - Extension to pandas dataframes describe function.
* [Pandas Profiling](https://github.com/pandas-profiling/pandas-profiling) ![alt text][pd] - Create HTML profiling reports from pandas DataFrame objects.
* [statsmodels](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python
* [stockstats](https://github.com/jealous/stockstats) - Supply a wrapper ``StockDataFrame`` based on the ``pandas.DataFrame`` with inline stock statistics/indicators support.
* [simplestatistics](https://github.com/sheriferson/simplestatistics) - Simple statistical functions implemented in readable Python.
* [weightedcalcs](https://github.com/jsvine/weightedcalcs) - pandas-based utility to calculate weighted means, medians, distributions, standard deviations, and more.
* [scikit-posthocs](https://github.com/maximtrp/scikit-posthocs) - Pairwise Multiple Comparisons Post-hoc Tests.
* [pysie](https://github.com/chen0040/pysie) - Provides python implementation of statistical inference engine.

<a name="tools"></a>
## Experimentation
* [Sacred](https://github.com/IDSIA/sacred) - A tool to help you configure, organize, log and reproduce experiments by [IDSIA](http://www.idsia.ch/).
* [Xcessiv](https://github.com/reiinakano/xcessiv) - A web-based application for quick, scalable, and automated hyperparameter tuning and stacked ensembling.
* [Persimmon](https://github.com/AlvarBer/Persimmon)  ![alt text][skl] - A visual dataflow programming language for sklearn.
* [Ax](https://github.com/facebook/Ax) - Adaptive Experimentation Platform  .

<a name="eval"></a>
## Evaluation
* [recmetrics](https://github.com/statisticianinstilettos/recmetrics) - Library of useful metrics and plots for evaluating recommender systems.
* [kaggle-metrics](https://github.com/krzjoa/kaggle-metrics) - Metrics for Kaggle competitions.
* [Metrics](https://github.com/benhamner/Metrics) - Machine learning evaluation metric.
* [sklearn-evaluation](https://github.com/edublancas/sklearn-evaluation) - Scikit-learn model evaluation made easy: plots, tables and markdown reports.
* [AI Fairness 360](https://github.com/IBM/AIF360) - Fairness metrics for datasets and ML models, explanations and algorithms to mitigate bias in datasets and models.

<a name="compt"></a>
## Computations
* [numpy](http://www.numpy.org/) - The fundamental package needed for scientific computing with Python.
* [Dask](https://github.com/dask/dask) - Parallel computing with task scheduling. ![alt text][pd]
* [bottleneck](https://github.com/kwgoodman/bottleneck) - Fast NumPy array functions written in C.
* [minpy](https://github.com/dmlc/minpy) - NumPy interface with mixed backend execution.
* [CuPy](https://github.com/cupy/cupy) - NumPy-like API accelerated with CUDA.
* [scikit-tensor](https://github.com/mnick/scikit-tensor) - Python library for multilinear algebra and tensor factorizations.
* [numdifftools](https://github.com/pbrod/numdifftools) - Solve automatic numerical differentiation problems in one or more variables.
* [quaternion](https://github.com/moble/quaternion) - Add built-in support for quaternions to numpy.
* [adaptive](https://github.com/python-adaptive/adaptive) - Tools for adaptive and parallel samping of mathematical functions.

<a name="spatial"></a>
## Spatial Analysis
* [GeoPandas](https://github.com/geopandas/geopandas) - Python tools for geographic data. ![alt text][pd]
* [PySal](https://github.com/pysal/pysal) - Python Spatial Analysis Library.

<a name="quant"></a>
## Quantum Computing
* [QML](https://github.com/qmlcode/qml) - A Python Toolkit for Quantum Machine Learning.

<a name="conv"></a>
## Conversion
* [sklearn-porter](https://github.com/nok/sklearn-porter) - Transpile trained scikit-learn estimators to C, Java, JavaScript and others.
* [ONNX](https://github.com/onnx/onnx) - Open Neural Network Exchange.
* [MMdnn](https://github.com/Microsoft/MMdnn) -  A set of tools to help users inter-operate among different deep learning frameworks.

[Deprecated libs](https://github.com/krzjoa/awesome-python-datascience/blob/master/other/deprecated.md)
[Waiting room](https://github.com/krzjoa/awesome-python-datascience/blob/master/other/waiting-room.md)

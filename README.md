[![Maintenance](https://img.shields.io/badge/Maintained%3F-YES-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
![GitHub](https://img.shields.io/badge/Release-PROD-yellow.svg)
![GitHub](https://img.shields.io/badge/Languages-MULTI-blue.svg)
![GitHub](https://img.shields.io/badge/License-MIT-lightgrey.svg)

# Awesome machine learning operations

* This repository contains a curated list of awesome open source libraries that will help you deploy, monitor, version and scale your machine learning.

## Quick links to sections in this page

Click in one of the links below to navigate this page:

||||
|-|-|-|
|[🔍 Explaining predictions & models](#1-explaining-black-box-models-and-datasets) |[🔏 Privacy preserving ML](#2-privacy-preserving-machine-learning) | [📜 Model & data versioning](#3-model-and-data-versioning)|
|[🏁 Model Orchestration](#4-model-deployment-and-orchestration-frameworks)|[🌀 Feature engineering](#5-feature-engineering-automation)|[🤖 Neural Architecture Search](#6-neural-architecture-search)|
| [📓 Reproducible Notebooks](#7-data-science-notebook-frameworks) | [📊 Visualisation frameworks](#8-industrial-strength-visualisation-libraries) | [🔠 Industry-strength NLP](#9-industrial-strength-nlp) |
| [🧵 Data pipelines & ETL](#10-data-pipeline-etl-frameworks) | [🗞️ Data storage](#11-data-storage-optimisation) | [📡 Functions as a service](#12-function-as-a-service-frameworks) |
| [🗺️ Computation distribution](#13-computation-load-distribution-frameworks) | [📥 Model serialisation](#14-model-serialisation-formats) | [🎁 Compiler optimisation](#15-compiler-optimisation-frameworks)  |
| [💸 Commercial ML](#16-commercial-data-science-platforms) | [💰 Commercial ETL](#17-commercial-etl-platforms)| |

## What are the libraries you will find in this repo?

This repo contains libraries to scale your machine learning capabilities. You can find an overview of this topic in [Alejandro Saucedo's](https://twitter.com/AxSaucedo) talk at the 2019 FOSDEM conference on [Tools to scale your production machine learning](https://www.youtube.com/watch?v=Ynb6X0KZKxY).

<table>
  <tr>
    <td width="30%">
        This repository covers multiple different areas around machine learning operations. This can be visualised on the diagram on the right.
    </td>
    <td width="70%">
        <img src="images/mlops1.png">
    </td>
  </tr>
</table>

# Main Contributors

* **Alejandro Saucedo** - Github: [AxSauze](https://github.com/axsauze/) - Twitter: [@AxSaucedo](https://twitter.com/AxSaucedo) - Linkedin: [/in/AxSaucedo](https://uk.linkedin.com/in/axsaucedo)


## Main Contents

### 1. Explaining Black Box Models and Datasets
* [XAI - eXplainableAI](https://github.com/EthicalML/xai) - An eXplainability toolbox for machine learning.
* [SHAP](https://github.com/slundberg/shap) - SHapley Additive exPlanations is a unified approach to explain the output of any machine learning model.
* [LIME](https://github.com/marcotcr/lime) - Local Interpretable Model-agnostic Explanations for machine learning models. 
* [ELI5](https://github.com/TeamHG-Memex/eli5) - "Explain Like I'm 5" is a Python package which helps to debug machine learning classifiers and explain their predictions.
* [Tensorboard's WhatIf](https://pair-code.github.io/what-if-tool/) - Tensorboard screen to analyse the interactions between inference results and data inputs.

### 2. Privacy Preserving Machine Learning
* [Tensorflow Privacy](https://github.com/tensorflow/privacy) - A Python library that includes implementations of TensorFlow optimizers for training machine learning models with differential privacy.
* [TF-Encrypted](https://github.com/mortendahl/tf-encrypted) - A Python library built on top of TensorFlow for researchers and practitioners to experiment with privacy-preserving machine learning.
* [PySyft](https://github.com/OpenMined/PySyft) - A Python library for secure, private Deep Learning. PySyft decouples private data from model training, using Multi-Party Computation (MPC) within PyTorch.
* [Uber SQL Differencial Privacy](https://github.com/uber/sql-differential-privacy) - Uber's open source framework that enforces differential privacy for general-purpose SQL queries.
* [Intel Homomorphic Encryption Backend](https://github.com/NervanaSystems/he-transformer) - The Intel HE transformer for nGraph is a Homomorphic Encryption (HE) backend to the Intel nGraph Compiler, Intel's graph compiler for Artificial Neural Networks.



### 3. Model and Data Versioning
* [Data Version Control (DVC)](https://dvc.org/) - A git fork that allows for version management of models
* [ModelDB](https://mitdbg.github.io/modeldb/) - Framework to track all the steps in your ML code to keep track of what version of your model obtained which accuracy, and then visualise it and query it via the UI
* [Pachyderm](https://github.com/pachyderm/pachyderm) - Open source distributed processing framework build on Kubernetes focused mainly on dynamic building of production machine learning pipelines - [(Video)](https://www.youtube.com/watch?v=LamKVhe2RSM)
* [steppy](https://github.com/neptune-ml/steppy) - Lightweight, Python3 library for fast and reproducible machine learning experimentation. Introduces simple interface that enables clean machine learning pipeline design.
* [Quilt Data](https://quiltdata.com/) - Versioning, reproducibility and deployment of data and models.
* [ModelChimp](https://www.modelchimp.com/) - Framework to track and compare all the results and parameters from machine learning models [(Video)](https://vimeo.com/271246650)
* [PredictionIO](https://predictionio.apache.org/) - An open source Machine Learning Server built on top of a state-of-the-art open source stack for developers and data scientists to create predictive engines for any machine learning task
* [MLflow](https://github.com/mlflow/mlflow) - Open source platform to manage the ML lifecycle, including experimentation, reproducibility and deployment.
* [Sacred](https://github.com/IDSIA/sacred) - Tool to help you configure, organize, log and reproduce machine learning experiments.
* [Catalyst](https://github.com/catalyst-team/catalyst) - High-level utils for PyTorch DL & RL research. It was developed with a focus on reproducibility, fast experimentation and code/ideas reusing. 
* [FGLab](https://github.com/Kaixhin/FGLab) - Machine learning dashboard, designed to make prototyping experiments easier.
* [Studio.ML](https://www.studio.ml/) - Model management framework which minimizes the overhead involved with scheduling, running, monitoring and managing artifacts of your machine learning experiments.

### 4. Model Deployment and Orchestration Frameworks
* [Seldon](https://github.com/SeldonIO/seldon-core) - Open source platform for deploying and monitoring machine learning models in kubernetes - [(Video)](https://www.youtube.com/watch?v=pDlapGtecbY)
* [Redis-ML](https://github.com/RedisLabsModules/redis-ml) - Module available from unstable branch that supports a subset of ML models as Redis data types
* [Model Server for Apache MXNet (MMS)](https://github.com/awslabs/mxnet-model-server) - A model server for Apache MXNet from Amazon Web Services that is able to run MXNet models as well as Gluon models (Amazon's SageMaker runs a custom version of MMS under the hood)
* [Tensorflow Serving](https://www.tensorflow.org/serving/) - High-performant framework to serve Tensofrlow models via grpc protocol able to handle 100k requests per second per core
* [Clipper](http://clipper.ai/) - Model server project from Berkeley's Rise Rise Lab which includes a standard RESTful API and supports TensorFlow, Scikit-learn and Caffe models
* [DeepDetect](https://github.com/beniz/deepdetect) - Machine Learning production server for TensorFlow, XGBoost and Cafe models written in C++ and maintained by Jolibrain
* [MLeap](https://github.com/combust/mleap) - Standardisation of pipeline and model serialization for Spark, Tensorflow and sklearn
* [OpenScoring](https://github.com/openscoring/openscoring) - REST web service for scoring PMML models built and maintained by OpenScoring.io
* [Open Platform for AI](https://github.com/Microsoft/pai) - Platform that provides complete AI model training and resource management capabilities.
* [NVIDIA TensorRT](https://docs.nvidia.com/deeplearning/sdk/tensorrt-developer-guide/index.html) - Model server created by NVIDIA that runs models in ONNX format, including frameworks such as TensorFlow and MATLAB
* [Kubeflow](https://github.com/kubeflow/kubeflow) - A cloud native platform for machine learning based on Google’s internal machine learning pipelines.
* [Polyaxon](https://github.com/polyaxon/polyaxon) - A platform for reproducible and scalable machine learning and deep learning on kubernetes. - [(Video)](https://www.youtube.com/watch?v=Iexwrka_hys)

### 5. Feature Engineering Automation
* [auto-sklearn](https://automl.github.io/auto-sklearn/stable/) - Framework to automate algorithm and hyperparameter tuning for sklearn
* [TPOT](https://epistasislab.github.io/tpot/) - Automation of sklearn pipeline creation (including feature selection, pre-processor, etc)
* [tsfresh](https://github.com/blue-yonder/tsfresh) - Automatic extraction of relevant features from time series
* [Featuretools](https://www.featuretools.com/) - An open source framework for automated feature engineering
* [Colombus](http://i.stanford.edu/hazy/victor/columbus/) - A scalable framework to perform exploratory feature selection implemented in R
* [automl](https://github.com/ClimbsRocks/automl) - Automated feature engineering, feature/model selection, hyperparam. optimisation


### 6. Neural Architecture Search
* [Neural Network Intelligence](https://github.com/Microsoft/nni) - NNI (Neural Network Intelligence) is a toolkit to help users run automated machine learning (AutoML) experiments.
* [Autokeras](https://github.com/jhfjhfj1/autokeras) - AutoML library for Keras based on ["Auto-Keras: Efficient Neural Architecture Search with Network Morphism"](https://arxiv.org/abs/1806.10282).
* [ENAS-PyTorch](https://github.com/carpedm20/ENAS-pytorch) - Efficient Neural Architecture Search (ENAS) in PyTorch based [on this paper](https://arxiv.org/abs/1802.03268).
* [Neural Architecture Search with Controller RNN](https://github.com/titu1994/neural-architecture-search) - Basic implementation of Controller RNN from [Neural Architecture Search with Reinforcement Learning](https://arxiv.org/abs/1611.01578) and [Learning Transferable Architectures for Scalable Image Recognition](https://arxiv.org/abs/1707.07012).
* [ENAS via Parameter Sharing] - Efficient Neural Architecture Search via Parameter Sharing by [authors of paper](https://arxiv.org/abs/1802.03268).
* [ENAS-Tensorflow](https://github.com/MINGUKKANG/ENAS-Tensorflow) - Efficient Neural Architecture search via parameter sharing(ENAS) micro search Tensorflow code for windows user.

### 7. Data Science Notebook Frameworks
* [Jupyter Notebooks](http://jupyter.org/) - Web interface python sandbox environments for reproducible development
* [Stencila](https://github.com/stencila/stencila) - Stencila is a platform for creating, collaborating on, and sharing data driven content. Content that is transparent and reproducible.
* [RMarkdown](https://github.com/rstudio/rmarkdown) - The rmarkdown package is a next generation implementation of R Markdown based on Pandoc.
* [H2O Flow](https://www.h2o.ai/download/) - Jupyter notebook-like inteface for H2O to create, save and re-use "flows"

### 8. Industrial Strength Visualization libraries
* [Plotly Dash](https://github.com/plotly/dash) - Dash is a Python framework for building analytical web applications without the need to write javascript.
* [Plotly.py](https://github.com/plotly/plotly.py) - An interactive, open source, and browser-based graphing library for Python.
* [Pixiedust](https://github.com/pixiedust/pixiedust) - PixieDust is a productivity tool for Python or Scala notebooks, which lets a developer encapsulate business logic into something easy for your customers to consume.
* [ggplot2](https://github.com/tidyverse/ggplot2) - An implementation of the grammar of graphics for python. 
* [seaborn](https://github.com/mwaskom/seaborn) - Seaborn is a Python visualization library based on matplotlib. It provides a high-level interface for drawing attractive statistical graphics.
* [Bokeh](https://github.com/bokeh/bokeh) - Bokeh is an interactive visualization library for Python that enables beautiful and meaningful visual presentation of data in modern web browsers.
* [matplotlib](https://github.com/matplotlib/matplotlib) - A Python 2D plotting library which produces publication-quality figures in a variety of hardcopy formats and interactive environments across platforms. 
* [pygal](https://github.com/Kozea/pygal) - pygal is a dynamic SVG charting library written in python
* [Geoplotlib](https://github.com/andrea-cuttone/geoplotlib) - geoplotlib is a python toolbox for visualizing geographical data and making maps
* [Missigno](https://github.com/ResidentMario/missingno) - missingno provides a small toolset of flexible and easy-to-use missing data visualizations and utilities that allows you to get a quick visual summary of the completeness (or lack thereof) of your dataset.


### 9. Industrial strenght NLP
* [SpaCy](https://github.com/explosion/spaCy) - Industrial-strength natural language processing library built with python and cython by the explosion.ai team.
* [Flair](https://github.com/zalandoresearch/flair) - Simple framework for state-of-the-art NLP developed by Zalando which builds directly on PyTorch.
* [Wav2Letter++](https://code.fb.com/ai-research/wav2letter/) - A speech to text system developed by Facebook's FAIR teams.

### 10. Data Pipeline ETL Frameworks
* [Apache Airflow](https://airflow.apache.org/) - Data Pipeline framework built in Python, including scheduler, DAG definition and a UI for visualisation
* [Luigi](https://github.com/spotify/luigi) - Luigi is a Python module that helps you build complex pipelines of batch jobs, handling dependency resolution, workflow management, visualisation, etc
* [Genie](https://github.com/Netflix/genie) - Job orchestration engine to interface and trigger the execution of jobs from Hadoop-based systems
* [Oozie](http://oozie.apache.org/) - Workflow scheduler for Hadoop jobs
* [Apache Nifi](https://github.com/apache/nifi) - Apache NiFi was made for dataflow. It supports highly configurable directed graphs of data routing, transformation, and system mediation logic.


### 11. Data Storage Optimisation
* [EdgeDB](https://edgedb.com/) - NoSQL interface for Postgres that allows for object interaction to data stored
* [BayesDB](http://probcomp.csail.mit.edu/bayesdb/) - Database that allows for built-in non-parametric Bayesian model discovery and queryingi for data on a database-like interface - [(Video)](https://www.youtube.com/watch?v=2ws84s6iD1o)
* [Apache Arrow](https://arrow.apache.org/) - In-memory columnar representation of data compatible with Pandas, Hadoop-based systems, etc
* [Apache Parquet](https://parquet.apache.org/) - On-disk columnar representation of data compatible with Pandas, Hadoop-based systems, etc
* [Apache Kafka](https://kafka.apache.org/) - Distributed streaming platform framework
* [ClickHouse](https://clickhouse.yandex/) - ClickHouse is an open source column oriented database management system supported by Yandex - [(Video)](https://www.youtube.com/watch?v=zbjub8BQPyE)
* [Alluxio](https://www.alluxio.org/docs/1.8/en/Overview.html) - A virtual distributed storage system that bridges the gab between computation frameworks and storage systems.


### 12. Function as a Service Frameworks
* [OpenFaaS](https://github.com/openfaas/faas) - Serverless functions framework with RESTful API on Kubernetes
* [Fission](https://github.com/fission/fission) - (Early Alpha) Serverless functions as a service framework on Kubernetes
* [Hydrosphere ML Lambda](https://github.com/Hydrospheredata/hydro-serving) - Open source model management cluster for deploying, serving and monitoring machine learning models and ad-hoc algorithms with a FaaS architecture
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) - Serverless proxy for Apache Spark clusters
* [Apache OpenWhisk](https://github.com/apache/incubator-openwhisk) - Open source, distributed serverless platform that executes functions in response to events at any scale. 



### 13. Computation load distribution frameworks
* [Hadoop Open Platform-as-a-service (HOPS)](https://www.hops.io/) - A multi-tenency open source framework with RESTful API for data science on Hadoop which enables for Spark, Tensorflow/Keras, it is Python-first, and provides a lot of features
* [PyWren](http://pywren.io) - Answer the question of the "cloud button" for python function execution. It's a framework that abstracts AWS Lambda to enable data scientists to execute any Pyhton function - [(Video)](https://www.youtube.com/watch?v=OskQytBBdJU)
* [NumPyWren](https://github.com/Vaishaal/numpywren) - Scientific computing framework build on top of pywren to enable numpy-like distributed computations
* [BigDL](https://bigdl-project.github.io/) - Deep learning framework on top of Spark/Hadoop to distribute data and computations across a HDFS system
* [Horovod](https://github.com/uber/horovod) - Uber's distributed training framework for TensorFlow, Keras, and PyTorch
* [Apache Spark MLib](https://spark.apache.org/mllib/) - Apache Spark's scalable machine learning library in Java, Scala, Python and R
* [Dask](http://dask.pydata.org/en/latest/) - Distributed parallel processing framework for Pandas and NumPy computations - [(Video)](https://www.youtube.com/watch?v=RA_2qdipVng)



### 14. Model serialisation formats
* [ONNX](https://github.com/onnx/onnx) - Open Neural Network Exchange Format
* [Neural Network Exchange Format (NNEF)](https://www.khronos.org/nnef) - A standard format to store models across Torch, Caffe, TensorFlow, Theano, Chainer, Caffe2, PyTorch, and MXNet
* [PFA](http://dmg.org/pfa/index.html) - Created by the same organisation as PMML, the Predicted Format for Analytics is an emerging standard for statistical models and data transformation engines.
* [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) - The Predictive Model Markup Language standard in XML - ([Video](https://www.youtube.com/watch?v=_5pZm2PZ8Q8))_
* [MMdnn](https://github.com/Microsoft/MMdnn) - Cross-framework solution to convert, visualize and diagnose deep neural network models. 
* [Java PMML API](https://github.com/jpmml) - Java libraries for consuming and producing PMML files containing models from different frameworks, including:
    * [sklearn2pmml](https://github.com/jpmml/jpmml-sklearn)
    * [pyspark2pmml](https://github.com/jpmml/pyspark2pmml)
    * [r2pmml](https://github.com/jpmml/r2pmml)
    * [sparklyr2pmml](https://github.com/jpmml/sparklyr2pmml)


### 15. Compiler optimisation frameworks
* [Numba](https://github.com/numba/numba) - A compiler for Python array and numerical functions


### 16. Commercial Data-science Platforms
* [Comet.ml](http://comet.ml) - Machine learning experiment management. Free for open source and students [(Video)](https://www.youtube.com/watch?v=xaybRkapeNE)
* [Skytree 16.0](http://skytree.net) - End to end machine learning platform [(Video)](https://www.youtube.com/watch?v=XuCwpnU-F1k)
* [Algorithmia](https://algorithmia.com/) - Cloud platform to build, deploy and serve machine learning models [(Video)](https://www.youtube.com/watch?v=qcsrPY0koyY)
* [y-hat](https://www.yhat.com/) - Deployment, updating and monitoring of predictive models in multiple languages [(Video)](https://www.youtube.com/watch?v=YiEjaWwzS_w)
* [Amazon SageMaker](https://aws.amazon.com/sagemaker/) - End-to-end machine learning development and deployment interface where you are able to build notebooks that use EC2 instances as backend, and then can host models exposed on an API
* [Google Cloud Machine Learning Engine](https://cloud.google.com/ml-engine/) - Managed service that enables developers and data scientists to build and bring machine learning models to production.
* [Microsoft Azure Machine Learning service](https://azure.microsoft.com/en-us/services/machine-learning-service/) - Build, train, and deploy models from the cloud to the edge.
* [IBM Watson Machine Learning](https://www.ibm.com/cloud/machine-learning) - Create, train, and deploy self-learning models using an automated, collaborative workflow.
* [neptune.ml](https://neptune.ml) - community-friendly platform supporting data scientists in creating and sharing machine learning models. Neptune facilitates teamwork, infrastructure management, models comparison and reproducibility.
* [Datmo](https://datmo.com/) - Workflow tools for monitoring your deployed models to experiment and optimize models in production.
* [Valohai](https://valohai.com/) - Machine orchestration, version control and pipeline management for deep learning.
* [Dataiku](https://www.dataiku.com/) - Collaborative data science platform powering both self-service analytics and the operationalization of machine learning models in production.
* [MCenter](https://www.parallelm.com/product/) - MLOps platform automates the deployment, ongoing optimization, and governance of machine learning applications in production.
* [Skafos](https://metismachine.com/products/) - Skafos platform bridges the gap between data science, devops and engineering; continuous deployment, automation and monitoring.
* [SKIL](https://skymind.ai/platform) - Software distribution designed to help enterprise IT teams manage, deploy, and retrain machine learning models at scale.
* [MLJAR](https://mljar.com/) - Platform for rapid prototyping, developing and deploying machine learning models.
* [MissingLink](https://missinglink.ai/) - MissingLink helps data engineers streamline and automate the entire deep learning lifecycle.
* [DataRobot](https://www.datarobot.com/) - Automated machine learning platform which enables users to build and deploy machine learning models.
* [RiseML](https://riseml.com/) - Machine Learning Platform for Kubernetes: RiseML simplifies running machine learning experiments on bare metal and cloud GPU clusters of any size.
* [Datatron](https://datatron.com/) - Machine Learning Model Governance Platform for all your AI models in production for large Enterprises.

### 17. Commercial ETL Platforms
* [Talend Studio](https://www.talend.com/)

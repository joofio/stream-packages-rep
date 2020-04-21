# Stream Packages for R
A curated repository of stream packages for R grouped by type.


### Interface  
* [stream](https://github.com/mhahsler/stream) - Infrastructure for Data Stream Mining [CRAN](https://cran.r-project.org/web/packages/stream/index.html)  

* [streamMOA](https://github.com/mhahsler/streamMOA) - streamMOA - Interface for MOA Stream Clustering Algorithms - R package.
 An extension package for stream. [CRAN](https://cran.r-project.org/web/packages/streamMOA/index.html)  

* [RMOA](https://github.com/jwijffels/RMOA) - To interface R with MOA (Massive On-line Analysis open-sourced framework that allows to build and run experiments of machine learning or data mining on evolving data streams).
 RMOA focusses on classification models [CRAN](https://cran.r-project.org/web/packages/RMOA/index.html)  

* [streamR](https://github.com/pablobarbera/streamR) - Access to Twitter Streaming API via R.
 This package includes a series of functions that give R users access to Twitter's Streaming API, as well as a tool that parses the captured tweets and transforms them in R data frames, which can then be used in subsequent analyses. [CRAN](https://cran.r-project.org/web/packages/streamR/index.html)  

* [Rstorm](https://rdrr.io/cran/RStorm/man/RStream-package.html) - Package RStorm implements a streaming architecture modeled on Storm for easy development and testing of streaming algorithms in [R]. RStorm is not intended as a production package, but rather a development tool for streaming algorithms. [CRAN](https://cran.r-project.org/web/packages/RStorm/index.html)  


### integration/wrapper

* [streamR](https://github.com/pablobarbera/streamR) - Access to Twitter Streaming API via R.
 This package includes a series of functions that give R users access to Twitter's Streaming API, as well as a tool that parses the captured tweets and transforms them in R data frames, which can then be used in subsequent analyses. [CRAN](https://cran.r-project.org/web/packages/streamR/index.html)  
* [rEMM](http://s2.smu.edu/IDA/TRACDS/) - Implements TRACDS (Temporal Relationships between Clusters for Data Streams), a generalization of Extensible Markov Model (EMM). TRACDS adds a temporal or order model to data stream clustering by superimposing a dynamically adapting Markov Chain. Also provides an implementation of EMM (TRACDS on top of tNN data stream clustering). Development of this package was supported in part by NSF IIS-0948893 and R21HG005912 from the National Human Genome Research Institute. [CRAN](https://cran.r-project.org/web/packages/rEMM/index.html)  
* [RcppStreams](https://github.com/cran/RcppStreams) - Rcpp' Integration of the 'Streamulus' 'DSEL' for Stream Processing
 This package connects 'Streamulus' to R by providing both the header files and all examples. [CRAN](https://cran.r-project.org/web/packages/RcppStreams/index.html)  
* [AWR.Kinesis](https://github.com/daroczig/AWR.Kinesis) - Amazon 'Kinesis' Consumer Application for Stream Processing
 Fetching data from Amazon 'Kinesis' Streams using the Java-based 'MultiLangDaemon' interacting with Amazon Web Services ('AWS') for easy stream processing from R.
 This R package is a wrapper around and an interface to the Amazon Kinesis Client Library (KCL) MultiLangDaemon, which is part of the Amazon KCL for Java. [CRAN](https://cran.r-project.org/web/packages/AWR.Kinesis/index.html)  
* [HadoopStreaming](https://github.com/cran/HadoopStreaming) - Utilities for using R scripts in Hadoop streaming
 Provides a framework for writing map/reduce scripts for use in Hadoop Streaming. Also facilitates operating on data in a streaming fashion, without Hadoop. [CRAN](https://cran.r-project.org/web/packages/HadoopStreaming/index.html)  "
* [MIDASwrappeR](https://github.com/pteridin/MIDASwrappeR) - Microcluster-Based Detector of Anomalies in Edge Streams
 Finds Anomalies in Dynamic/Time-Evolving Graphs 
 Detects Microcluster Anomalies (suddenly arriving groups of suspiciously similar edges e.g. DoS attack) 
 Theoretical Guarantees on False Positive Probability 
 Constant Memory (independent of graph size) 
 Constant Update Time (real-time anomaly detection to minimize harm) [CRAN](https://cran.r-project.org/web/packages/MIDASwrappeR/index.html)  
* [ndjson](https://gitlab.com/hrbrmstr/ndjson) - Wicked-Fast Streaming 'JSON' ('ndjson') Reader
 Streaming ‘JSON’ (‘ndjson’) has one ‘JSON’ record per-line and many
 modern ‘ndjson’ files contain large numbers of records. These constructs
 may not be columnar in nature, but it is often useful to read in these
 files and “flatten” the structure out to enable working with the data in
 an R ‘data.frame’-like context. [CRAN](https://cran.r-project.org/web/packages/ndjson/index.html)  
 
 ### data stream classification
 
* [eventstream](https://sevvandi.github.io/eventstream/index.html) - Streaming Events and their Early Classification.
 Implements event extraction and early classification of events in data streams in R. 
 The goal of eventstream is to extract and classify events in contiguous spatio-temporal data streams of 2 or 3 dimensions. [CRAN](https://cran.r-project.org/web/packages/eventstream/index.html)  
* [SSOSVM](https://github.com/andrewthomasjones/SSOSVM) - Stream Suitable Online Support Vector Machines
 The Stochastic majorization-minimization (SMM) algorithm framework allows for the training of SVMs on streamed data.
 This package utilizes the SMM framework to provide functions for training SVMs with hinge loss, squared-hinge loss, and logistic loss. [CRAN](https://cran.r-project.org/web/packages/SSOSVM/index.html)  
 
 
 ### Drift Detection

* [gStream](https://rdrr.io/cran/gStream/man/gStream-package.html) - Graph-Based Sequential Change-Point Detection for Streaming Data
 Uses an approach based on k-nearest neighbor information to sequentially detect change-points. [CRAN](https://cran.r-project.org/web/packages/gStream/index.html)  

* [ffstream](http://www.deanbodenham.com/ffstream/) - Forgetting Factor Methods for Change Detection in Streaming Data
 An implementation of the adaptive forgetting factor scheme described in Bodenham and Adams (2016) which adaptively estimates the mean and variance of a stream in order to detect multiple changepoints in streaming data. [CRAN](https://cran.r-project.org/web/packages/ffstream/index.html)  

* [changepoint](https://github.com/rkillick/changepoint/) - Methods for Changepoint Detection
Implements various mainstream and specialised changepoint methods for finding single and multiple changepoints within data. Many popular non-parametric and frequentist methods are included. The cpt.mean(), cpt.var(), cpt.meanvar() functions should be your first point of call.
 [CRAN](https://cran.r-project.org/web/packages/changepoint/index.html)  
 
 
 
 ### modelling
* [RMOA](https://github.com/jwijffels/RMOA) - To interface R with MOA (Massive On-line Analysis open-sourced framework that allows to build and run experiments of machine learning or data mining on evolving data streams).
 RMOA focusses on classification models [CRAN](https://cran.r-project.org/web/packages/RMOA/index.html) 
 
* [rRAP](https://github.com/cran/rRAP) - Real-Time Adaptive Penalization for Streaming Lasso Models
 An implementation of the Real-time Adaptive Penalization (RAP) algorithm through which to iteratively update a regularization parameter in a streaming context. [CRAN](https://cran.r-project.org/web/packages/rRAP/index.html)  
 
 

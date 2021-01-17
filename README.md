## Blockchain Analytic Tools

### [Santiment](https://santiment.net/)
[github.com/santiment](https://github.com/santiment)  
Multichain analytic platform for social, market and onchain data
##### [Sanbase](https://app.santiment.net/)
On-chain, social, development activity, prices and volume data and charts
##### [SanAPI](https://neuro.santiment.net/)
Custom-built and unique terabytes of processed on-chain, social, github and fundamental data sets
##### [SanSheets](https://sheets.santiment.net/)
On-chain, social, development activity, prices and volume data

### [BitQuery](https://bitquery.io/)  
[github.com/bitquery](https://github.com/bitquery)  
##### [Bloxy](https://bloxy.info/)
[github.com/bloxy-info](https://github.com/bloxy-info)  
The best Ethereum analitycal browser
##### [BitQuery GraphQL](https://bitquery.io/labs/graphql)  
[github.com/bitquery/activecube-graphql](https://github.com/bitquery/activecube-graphql)  
GraphQL tool for Multichain data
##### [BitQuery Explorer](https://explorer.bitquery.io/)
[github.com/bitquery/explorer](https://github.com/bitquery/explorer)  
Multichain browser with little analytical tools

### [Google BigQuery Public Blockchain Datasets](https://console.cloud.google.com/bigquery?p=blockchain-etl)
[blockchain-etl](https://github.com/blockchain-etl)  
Public Blockchain Datasets with the ability to query using Google BigQuery

### [Blockchain ETL](https://github.com/blockchain-etl)  
[blockchain-etl](https://github.com/blockchain-etl)  
ETL tools for blockchain data

### [Nansen](https://nansen.ai/)  
Labeling analytic tool for Ethereum



## Graph Analytic Tools

### [ClickHouse](https://clickhouse.tech/)
[github.com/ClickHouse/ClickHouse](https://github.com/ClickHouse/ClickHouse)  
ClickHouse is a fast open-source OLAP database management system.
It is column-oriented and allows to generate analytical reports using SQL queries in real-time.  
This tool has become the standard for the analysis of blockchain data, it combines high speed and flexibility.

### [Spark](https://spark.apache.org/)
[github.com/apache/spark](https://github.com/apache/spark)  

#### [GraphFrames](https://graphframes.github.io/graphframes)
[github.com/graphframes/graphframes](https://github.com/graphframes/graphframes)  
GraphFrames is a package for Apache Spark which provides DataFrame-based Graphs. It provides high-level APIs in Scala, 
Java, and Python. It aims to provide both the functionality of GraphX and extended functionality taking advantage 
of Spark DataFrames. This extended functionality includes motif finding, DataFrame-based serialization, and highly 
expressive graph queries.
#### [GraphX](https://spark.apache.org/docs/latest/graphx-programming-guide.html)
[github.com/apache/spark/tree/master/graphx](https://github.com/apache/spark/tree/master/graphx)  
GraphX is a new component in Spark for graphs and graph-parallel computation. At a high level, GraphX extends 
the Spark RDD by introducing a new Graph abstraction: a directed multigraph with properties attached to each vertex 
and edge.  
There is only the Scala API and does not have a Python API.

### [Apache Giraph](https://giraph.apache.org/)  
Apache Giraph is an iterative graph processing system built for high scalability. For example, it is currently used 
at Facebook to analyze the social graph formed by users and their connections. Giraph originated as the open-source 
counterpart to Pregel, the graph processing architecture developed at Google and described in a 2010 
[paper](http://dl.acm.org/citation.cfm?id=1807184).

### [neo4j](https://neo4j.com/)
[github.com/neo4j](https://github.com/neo4j)  
The well-known graph database has wide functionality for graph analysis. The free version has significant limitations 
and can be recommended for analyzing graphs with a total number of edges and vertices of less than 10M. 
I do not recommend using it in a production.

### [Amazon Neptune](https://aws.amazon.com/nosql/graph/)
[github.com/aws](https://github.com/aws?q=neptune&type=&language=)  
[github.com/awslabs/amazon-neptune-tools](https://github.com/awslabs/amazon-neptune-tools)  
[github.com/aws-samples/amazon-neptune-samples](https://github.com/aws-samples/amazon-neptune-samples)  
Amazon Neptune is a purpose-built, high-performance graph database engine optimized for storing billions 
of relationships and querying the graph with milliseconds latency. Neptune supports the popular graph models property 
graph and W3C's Resource Description Framework (RDF), and it also supports their respective query languages, Apache 
TinkerPop Gremlin and SPARQL, to allow you to build queries that efficiently navigate highly connected datasets. 

## Graph Visualization and Analytic Tools

### [NetworkX](https://networkx.github.io/)  
[github.com/networkx](https://github.com/networkx/networkx)  
NetworkX is a Python package for the creation, manipulation, and study of the structure, dynamics, and functions 
of complex networks.  
Commonly used to visualize graphs.

### [ipycytoscape](https://ipycytoscape.readthedocs.io/en/latest/)  
[github.com/QuantStack/ipycytoscape](https://github.com/QuantStack/ipycytoscape)  
Visualize graphs using Cytoscape.js in a Jupyter Notebook.  
You can either create graphs using the ipycytoscape API or create them from NetworkX, JSON and Pandas Dataframes.

### [Gephi](https://gephi.org/)  
[github.com/gephi/gephi](https://github.com/gephi/gephi)  
Gephi is the leading visualization and exploration App for all kinds of graphs and networks.

### [Plotly / Dash Network visualisation](plotly.com/python/network-graphs)  
[github.com/plotly](https://github.com/plotly)  
Easy way to build webApp with network visualization

## Visualization and Analytic Tools for Big Graphs (more than 1M edges)

### [LargeVis](https://github.com/lferry007/LargeVis)  
[github.com/lferry007/LargeVis](https://github.com/lferry007/LargeVis)  
This is the official implementation of the LargeVis model by the original authors, which is used to visualize 
large-scale and high-dimensional data (Tang, Liu, Zhang and Mei). It now supports visualizing both high-dimensional 
feature vectors and networks. The package also contains a very efficient algorithm for constructing K-nearest neighbor 
graph (K-NNG).  

### [VERSE](tsitsul.in/publications/verse/) 
[github.com/xgfs/verse](https://github.com/xgfs/verse)  
Versatile Graph Embeddings from Similarity Measures  

### [cuGraph](https://github.com/rapidsai/cugraph)  
[github.com/rapidsai/cugraph](https://github.com/rapidsai/cugraph)  
cuGraph Graph Analytics Library is a collection of **GPU** accelerated graph algorithms.

## Data Science Analytic Tools

### [Machine Learning Financial Laboratory (mlfinlab)](https://mlfinlab.readthedocs.io/)
[github.com/hudson-and-thames/mlfinlab](https://github.com/hudson-and-thames/mlfinlab)  
MlFinlab is a python package which helps portfolio managers and traders who want to leverage the power of machine 
learning by providing reproducible, interpretable, and easy to use tools. 

### [Joblib](https://joblib.readthedocs.io/)
[github.com/joblib/joblib](https://github.com/joblib/joblib)  
Joblib is a set of tools to provide lightweight pipelining in Python. Joblib is optimized to be fast and robust 
on large data in particular and has specific optimizations for numpy arrays.

### [Dask](https://dask.org/)
[github.com/dask/dask](https://github.com/dask/dask)  
Dask is a flexible library for parallel computing in Python. You can use numpy-like or pandas-like syntax.

### [Dataset Search](https://datasetsearch.research.google.com/)
Google Dataset Search allows to find a data you are interested in.

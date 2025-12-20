# my_sparkPy_notebookes
A personal collection of PySpark notebooks from the book...what I've worked on and practical examples intended to help others learn and reuse common Spark patterns and techniques.

These notebooks are hands-on examples and explanatory notes that demonstrate core Apache Spark (PySpark) patterns and APIs. 

Notebooks
- `nb1-rdd-creation/nb1-rdd-creation.ipynb`: Creating RDDs from Python collections and external files; `parallelize`, `textFile`, and partition basics.
- `nb2-rdd-basics/nb2-rdd-basics.ipynb`: Core RDD transformations and actions (`map`, `filter`, `flatMap`, `reduce`, `collect`, `take`).
- `nb3-rdd-sampling/nb3-rdd-sampling.ipynb`: Sampling techniques and practical examples (random sampling, stratified sampling, seeds).
- `nb4-rdd-set/nb4-rdd-set.ipynb`: Set-like operations on RDDs: `union`, `intersection`, `distinct`, and `subtract`.
- `nb5-rdd-aggregations/nb5-rdd-aggregations.ipynb`: Aggregation patterns (`reduceByKey`, `aggregate`, `fold`, `countByKey`) and performance notes.
- `nb6-rdd-key-value/nb6-rdd-key-value.ipynb`: Key-value RDD idioms (`groupByKey`, `reduceByKey`, `join`, `cogroup`) and use cases.
- `nb7-mllib-statistics/nb7-mllib-statistics.ipynb`: Exploratory statistics with MLlib: summary statistics, correlations, sampling summaries.
- `nb8-mllib-logit/nb8-mllib-logit.ipynb`: Logistic regression example using MLlib (data preparation, model training, evaluation).
- `nb9-mllib-trees/nb9-mllib-trees.ipynb`: Tree-based models (decision trees / random forests) with training and basic evaluation.
- `nb10-sql-dataframes/nb10-sql-dataframes.ipynb`: Spark SQL and DataFrame API: reading data, queries, schema inference, and basic transformations.
- `spark-py-notebooks-master/`: A larger upstream/master copy of example notebooks (kept for reference).

Getting started
- Install PySpark and Jupyter: `pip install pyspark jupyterlab`
- Launch Jupyter in the repo root and open any notebook: `jupyter lab`

Notes
- Notebooks assume a local PySpark environment; adjust Spark config for cluster use.
- Intended for learning and demonstration rather than production-ready pipelines.

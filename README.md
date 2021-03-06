# OSQF2015: Market Risk Analytics and Aggregation with Python & Spark

Accompanying material to my talk at the conference "Open Source in Quantitative Finance" in Eschborn, Germany, June 5th 2015.
http://osqf.tpq.io

### Abstract
Risk Management is driven by distinct but interdependent processes (e.g. VaR calculation, stress testing). Although posing different non-functional requirements — such as performance, frequency and data volume — these processes must be functionally consistent. Such diverse requirements are usually contradictory, inevitably leading to complexity.

We evaluate, with concrete coded examples, existing open source tools from the Risk Analytics and complexity handling point of view. The examples use mainly the PyData (e.g. Pandas, Bokeh) stack and the Apache Spark framework.


### Content
It consists of a set of notebooks:
- [Data Preparation](notebooks/DataPreparation.ipynb)
- Tools introduction
- Model
- [VaRSpark](notebooks/SparkVaR.ipynb)


### Setup

You will need two conda environments:

conda env create
pip install -r requirements.txt
source activate osqf

conda env create -f=finspark.yml
pip install -r requirements.txt
source activate finspark
 
### References

- 



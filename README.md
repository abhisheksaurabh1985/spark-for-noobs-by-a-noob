# Jupyter Notebooks to Practice Spark

## Introduction
This tutorial is a work-in-progress for practising PySpark using Jupyter notebooks. Though I've provided some explanation on some of the basic concepts of Spark, such explanations by no means should be construed as complete. I will add more explanations as and when I get the time to revisit the work already done. I'd appreciate if people following this repo can provide me some feedback so that I can make necessary corrections. 

## Pre-requisites:
Python, Jupyter Notebook, Basics of distributed computing (theoretical understanding should be enough) 

## Thanks
A big thanks to [this](https://github.com/jadianes/spark-py-notebooks) tutorial which too was created with the same intent. It helped me a lot to understand the concepts by giving me something to play around with. Additionally, thanks to numerous quora users who explain the technical jargons in the most lucid terms. 

## Spark Installation Notes
I followed [this](https://medium.com/@GalarnykMichael/install-spark-on-ubuntu-pyspark-231c45677de0) link to install Spark, with the following difference. 
* As opposed to using Anaconda distribution for Python, I went ahead with the installation which comes with Ubuntu. I am not a huge fan of *Anaconda* and prefer to install the Python libraries as and when required. 
* I installed Spark 2.2.0.
* Note that this version of Spark, does not work with Oracle Java 9. It works with Java 8. While installing Java, you'll be prompted to install version 9. DO NOT install 9. It took me quite some time to figure this out:-)  

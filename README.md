# PYSpark
pyspark


Steps to Configure:-

## 1.
Download spark-2.4.4-bin-hadoop2.7 tar file from https://spark.apache.org/downloads.html
## 2.
Open Commanad Prompt
setx SPARK_HOME D:\app\spark-2.4.4-bin-hadoop2.7

setx HADOOP_HOME D:\app\spark-2.4.4-bin-hadoop2.7

setx SPARK_DRIVER_PYTHON ipython Or setx SPARK_DRIVER_PYTHON ipython jupyter

setx SPARK_DRIVER_PYTHON_OPTS notebook

## 3.
to Open Jupyter notebook

open another Command prompt

goto D:\app\spark-2.4.4-bin-hadoop2\bin folder

type pySpark --master local[2]



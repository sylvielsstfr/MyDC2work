# README.md


## to lauch jupyter notebook pyspark

PYSPARK_DRIVER_PYTHON_OPTS='/opt/anaconda/bin/jupyter-notebook --no-browser --port=24335' pyspark --master mesos://134.158.75.63:5050 --conf spark.mesos.principal=l
sst --conf spark.mesos.secret=secret --conf spark.mesos.role=lsst --conf spark.executorEnv.HADOOP_CONF_DIR=/opt/hadoop-2/etc/Hadoop --driver-memory 20g --total-executor-cores 85 --executor-cores 17 --executor-memory 29g


PYSPARK_DRIVER_PYTHON_OPTS='/opt/anaconda/bin/jupyter-notebook --no-browser --port=24335' pyspark --master mesos://134.158.75.63:5050 --conf spark.mesos.principal=l
sst --conf spark.mesos.secret=secret --conf spark.mesos.role=lsst --conf spark.executorEnv.HADOOP_CONF_DIR=/opt/hadoop-2/etc/Hadoop --driver-memory 20g --total-executor-cores 85 --executor-cores 17 --executor-memory 29g


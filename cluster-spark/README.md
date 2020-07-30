# README.md

- creation date : July 30th 2020


## Connect to spark cluster
      PORT=24335

      ssh -L $PORT:vm-75222.lal.in2p3.fr:$PORT -Y sylvie.dagoret-campagne@vm-75222.lal.in2p3.fr


## to lauch jupyter notebook pyspark



     PYSPARK_DRIVER_PYTHON_OPTS='/opt/anaconda/bin/jupyter-notebook --no-browser --port=24335' pyspark --master mesos://134.158.75.63:5050 --conf spark.mesos.principal=l
sst --conf spark.mesos.secret=secret --conf spark.mesos.role=lsst --conf spark.executorEnv.HADOOP_CONF_DIR=/opt/hadoop-2/etc/Hadoop --driver-memory 20g --total-executor-cores 85 --executor-cores 17 --executor-memory 29g


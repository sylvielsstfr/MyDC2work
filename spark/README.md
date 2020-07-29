# Work on CosmoDC2 and Run DC2 2.2XXXX to derive Cl with Spark

- author : Sylvie Dagoret-Campagne
- affliliation : IJCLab/in2p3/CNRS (ex LAL)
- creation date : July 29th 2020

# kernel use desc-pyspark (Spark version 3 from July 27th 2020, from Julien Peloton)

# List of notebook

## object_spark_1_intro_Run1.1.ipynb :
 
- example of Julien  Peloton on DC2analysis tutorial to show how to access data from DC2 Run1.1

## object_spark_1_intro_Run2.2i.ipynb :

- adaptation of **object_spark_1_intro_Run1.1.ipynb** to Run 2.2i

## galtruth_spark.ipynb 

- where is the truth

## ComputeClGal_Run2.2i_spark.ipynb:

- start to compute CL (very begginning with healpix). Read parquet DC2 data from "/global/cfs/cdirs/lsst/shared/DC2-prod/Run2.2i/dpdd/Run2.2i-dr6b/dc2_object_run2.2i_dr6b"

## ComputeClGal_CosmoDC2_spark.ipynb

- start to compute CL (very begginning with healpix), Reald CosmoDC2 summary parquet files from "/global/cfs/cdirs/lsst/shared/DC2-prod/Run2.2i/truth/galtruth"



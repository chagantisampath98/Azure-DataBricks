# Azure-DataBricks

Optimize performance of spark dataframes:
1. repartition
2. coalese
3. use reduceByKey() instead of groupByKey()
4. use cache()
5. try to avoid UDF's
6. use kryo serialization instead of java serialization (we need to add property)

different ways to create RDD:
1. spark.sparkContext.parallelize()
2. spark.sparkContext.textFile()
3. spark.emptyRDD()

different ways and types to create a data frame:
1. spark.read.csv()
2. spark.read.orc()
3. spark.read.json()
4. spark.read.parquet()
5. spark.read.jdbc()
6. spark.table()

creating d-stream:
scc.queueStream(list[rdd1, rdd2, .... , rddn])

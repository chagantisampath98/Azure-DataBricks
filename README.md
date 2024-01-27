# Azure-DataBricks

Optimize performance of spark dataframes:
1. repartition
2. coalese
3. use reduceByKey() instead of groupByKey()
4. use cache()
5. try to avoid UDF's
6. use kryo serialization instead of java serialization (we need to add property)

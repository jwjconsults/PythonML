Premiered Dec 6, 2022  Data Science, Machine Learning and Python programming learning by Vytautas
To build and train a Machine Learning (#ML) model with Spark is not hard. With this tutorial we will build a simple Binary Classification ML model with Spark. We will use Logistic Regression built-in Spark algorithm, and then evaluate it by getting performance metrics from the model.

There are some different from we do it in Scikit-Learn. Spark provides a built-in SparkML engine with rich #SparkML API which you can leverage to build your unique Machine Learning model.

In this tutorial we are using SparkUI v.3.2.1 with pyspark-shell.

The critical points you should pay your attention to is:
- Datatypes (DTypes)
- String Indexer and One-Hot-Encoding for categorical features.
- Vector Assembler.

All these parts are explained and demonstrated in details in this tutorial. Also, you will learn what is SparkContext and SparkSession (differences between them). Therefore you will be able to check Data schema and handle data types in Spark DataFrame, selected features within your data. As required for ML modelling, you will also learn how to split your data into train and test sets. 

Here you also learn how to setup ML stages with Spark and build a custom ML Pipeline to build your Machine Learning Model with Spark.

At the end, you will learn hot to get model performance metrics, such as Precision, Recall, or ROC curve values.

The tutorial is prepared with Jupyter Notebook, using Python programming language, so all the steps are executed with #pyspark .

Spark API  and SparkML API method used in the tutorial (incl. documentation):
- Spark Datatypes (https://spark.apache.org/docs/latest/...)
- PySpark SQL DataFrame Random Split (https://spark.apache.org/docs/3.1.3/a...)
- StringIndexer (https://spark.apache.org/docs/latest/...)
- OneHotEncoder (https://spark.apache.org/docs/3.1.1/a...)
- VectorAssembler (https://spark.apache.org/docs/latest/...)
- Spark DataFrame aggregation (https://spark.apache.org/docs/latest/...)
- Count Distinct values from Spark DataFrame (https://spark.apache.org/docs/3.1.2/a...)
- Group by to check feature distribution (https://spark.apache.org/docs/latest/...)
- SparkML Pipelines (https://spark.apache.org/docs/latest/...)
- Logistic Regression in Spark (https://spark.apache.org/docs/1.6.1/m...)

# Intrusion-detection-system-using-RDD-and-Pyspark-in-Databricks

Input Data - kddcup.data_10_percent.gz 10% subset. (2.1M; 75M Uncompressed) from 
http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html

- Used urllib library to extract KDD Cup 99 data from their web repository and load it in Spark’s RDD in data bricks filesystem. 
- Performed feature extraction, exploratory data ana1ysis and data visualization using RDD and Data Frame.
- Applied numerous classification algorithms (Logistic Regression, Decision Trees, Random Forest, SVM) to compare performance based on the AUC-ROC curve on the data bricks system.
- Logistic regression gave best test AUC of 0.99 and accuracy of 99%.

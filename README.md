# AWS SageMaker Spark MNIST 

This project was apart of my cloud computing course with Noah Gift, at Duke University. The project entailed using a distributed computing platform and performing a task suited to the platform. I choose to use AWS SageMaker spark and ran K-means and XGBoost on MNIST data. 

## Use this notebook in SageMaker 

1. Create notebook instance or upload this notebook.


2. Run the following command in terminal to ensure you have all the necessary packages. (Might not be necessary.)

```
spark-shell --packages com.amazonaws:sagemaker-spark_2.11:spark_2.2.0-1.0
```

3. Run the notebook with the conda_python3 kernel.


## Resources
[Tutorial](https://sagemaker-examples.readthedocs.io/en/latest/sagemaker-spark/pyspark_mnist/pyspark_mnist_kmeans.html)
<br>
[SageMaker Spark Repo](https://github.com/aws/sagemaker-spark)

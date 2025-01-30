# BigDataEngineering
This repository was created to upload the final project from the Big Data Engineering course of the Computational Biology Msc

This project was done by Álvaro Arrayás Ruíz and Jaime Castro Cernadas. 

The objective is to create a model that can identify pneumonia cases from X-Ray images, delivering a meaningful Spark-based solution.
Data was obtained from the kaggle challenge: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

Issues encountered in this project:

The use of BigDL was not possible due to compatibilíty reasons between the python, pyspark and BigDL versions. Several solutions were tried, but due to Google Collab crash issues we were unable to finally implement BigDL.

To create the model, Keras and TensorFlow was used to convert the images into a valid np array that could be used by the pyspark.ml library. 

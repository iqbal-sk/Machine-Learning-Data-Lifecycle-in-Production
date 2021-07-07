# Machine-Learning-Data-Lifecycle-in-Production
Usage of TFDV, TFX API for data lifecycle in ML

# Data Validation with TFDV (Tensorflow DataValidation)
Examining the characteristics of your data is an important part of building a production-grade machine learning system. Improving data quality will help drive your model's performance by detecting possible issues such as malformed values, distribution skew, and unfair bias. In the "Data Validation with TFDV.ipynb", performed common data validation steps to examine the Diabetes dataset. This includes:

- Generating and visualizing statistics
- Inferring and updating a dataset schema
- Detecting, visualizing, and fixing anomalies
- Examining slices of the dataset

# Feature Engineering with Tensorflow Extended
In "Feature Engineeering with TFX.ipynb" notebook, built a data pipeline using the TFX components. The final output will be a transformed dataset and graph generated by the Transform component.

# Sample Final Data Pipeline Components for Production ML
In this "Data Pipeline Components for Production ML (for covertype dataset).ipynb" notebook, wrote code to handle the first three steps of a production machine learning project - Data ingestion, Data Validation, and Data Transformation.

Specifically, I built the production data pipeline by:

- Performing feature selection
- Ingesting the dataset
- Generating the statistics of the dataset
- Creating a schema as per the domain knowledge
- Creating schema environments
- Visualizing the dataset anomalies
- Preprocessing, transforming and engineering your features
- Tracking the provenance of your data pipeline using ML Metadata

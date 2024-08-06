# End to End Machine Learning Model (Model/Flask/Docker)
This repository contains a machine learning model that predicts job packages based on students' CGPA. Utilizing Python, Pandas, Scikit-Learn, and Joblib, the model employs a RandomForestRegressor to accurately capture the relationship between CGPA and job packages.

Placement Prediction Model

This repository contains a machine learning model built using Python's Flask framework and Docker for deployment. The model predicts the placement package of a student based on their CGPA.

Key Features:

Model: Random Forest Regressor
Data: The model is trained on a dataset containing CGPA and corresponding placement package information.
Deployment: The model is deployed as a Flask application within a Docker container for easy deployment and scalability.
Prediction: Users can input a CGPA and receive a predicted placement package.

Dependencies:

* Python
* Flask
* Pandas
* NumPy
* Scikit-learn
* Joblib
* Docker

Additional Information:

Model performance: Include metrics such as R-squared, Mean Squared Error, and Mean Absolute Error to evaluate the model's accuracy.
Data preprocessing: Describe any data cleaning or feature engineering steps performed.
Model limitations: Discuss the model's limitations, such as relying solely on CGPA for prediction.
Exposed: Port = 8000.

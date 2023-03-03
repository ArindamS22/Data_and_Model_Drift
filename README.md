Detection of Data and Model Drift in Production
This repository contains code for detecting and monitoring data and model drift in production for image processing or image segmentation task using vision transfomers(ViT)

Introduction
Data and model drift are major challenges in machine learning production systems. Over time, data distributions may shift or become biased, and models may become outdated or perform poorly on new data. Detecting and monitoring drift is critical to maintaining model accuracy and ensuring that ML systems remain effective over time.

Contents
This repository includes the following components:

data_drift_detection.py: A Python script that detects changes in data distributions over time.
model_drift_detection.py: A Python script that detects changes in model performance over time.
requirements.txt: A list of required Python libraries.
LICENSE: The license under which this code is distributed.
Usage
To use the drift detection scripts, follow these steps:

Install the required libraries by running pip install -r requirements.txt.
Use data_drift_detection.py to detect changes in data distributions. This script takes two CSV files where we will have one column named as inputs which will contain the absoulte path of images: a baseline file that represents the original data distribution and a new file that represents the current data distribution. The script outputs a report that summarizes the changes between the two distributions.
Use model_drift_detection.py to detect changes in model performance. This script takes same inputs as above and outputs a report that summarizes why you need to retrain the model or whether your current model is enough.
Contributions to this repository are welcome. If you find a bug or have a feature request, please create an issue on this repository. If you would like to contribute code, please fork this repository and create a pull request.


Credits
This repository was created by Arindam Sarkar and is maintained by Arindam Sarkar.





 

# Weather Prediction Using Satellite Data with Machine Learning
Introduction
This project aims to predict weather patterns using satellite data and various Machine Learning algorithms. The primary focus is on utilizing satellite data collected by WorldWeatherOnline.com, which incorporates both satellite observations and ground-based sensor data. By analyzing this time series dataset, spanning over 10+ years with hourly data, we aim to forecast live temperatures using different ML models, such as Linear Regression, Decision Tree, and Random Forest.

Data Collection
The dataset used in this project was obtained from WorldWeatherOnline.com, a reliable source that gathers comprehensive weather data from satellites and ground-based sensors. The data covers a significant time span, making it ideal for training and testing our ML models.

Feature Selection
We employed a correlation heat map to identify the most relevant features for weather prediction. By analyzing the correlations between different variables in the dataset, we could select the best features to be used as inputs for our ML models. This step ensures that we focus on the most influential factors affecting weather conditions.

Machine Learning Models
We implemented the following Machine Learning algorithms for weather prediction:

Linear Regression: This simple yet effective model establishes a linear relationship between input features and the target variable (temperature). It provides a baseline for comparison with more complex models.

Decision Tree: Decision Trees are powerful models that recursively split the data based on different features, forming a tree-like structure. They are capable of handling both numerical and categorical data, making them well-suited for this project.

Random Forest: Random Forest is an ensemble learning method that combines multiple decision trees to achieve more accurate predictions. It reduces overfitting and enhances the robustness of the model.

Live Temperature Prediction
By training our ML models on the selected features, we achieve the capability to make live temperature predictions. This means that given current or near-real-time weather data from satellites, our models can provide forecasts for temperatures at specific locations.

Google Colab
This project was developed using Google Colab, an excellent platform for running Jupyter notebooks in the cloud. The benefit of using Google Colab is that it provides access to powerful GPUs and TPUs, allowing for faster training of Machine Learning models.

Repository Structure
The repository is organized as follows:

/data: This directory contains the dataset used in the project. 

/notebooks: Each ML model has a notebook showcasing the training and evaluation process. The notebooks used in Google Colab can be found here.

/src: This directory contains the source code for data preprocessing, feature selection, and model training.

/models: After training, the ML models will be saved in this directory for future use.

/results: Model evaluation results, visualizations, and any output files will be stored here.

README.md: This file you are currently reading, provides an overview of the project and its details.

How to Contribute
Contributions to this project are welcome! If you have any suggestions for improvements, bug fixes, or additional ML models to explore, feel free to open an issue or submit a pull request.

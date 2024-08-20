# Heart Disease Prediction  

## Overview  

The Heart Disease Prediction project is a machine learning application aimed at predicting the likelihood of heart disease in patients based on various health parameters. This project utilizes a dataset containing patient data, which is processed and analyzed using machine learning algorithms to provide insights into cardiovascular health.  

## Table of Contents  

- [Motivation](#motivation)  
- [Dataset](#dataset)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Models](#models)  
- [Results](#results)  
- [Contributing](#contributing)  
- [License](#license)  

## Motivation  

Cardiovascular diseases are a leading cause of death globally. Early prediction can aid in taking preventive measures to ensure better health outcomes. This project aims to provide a user-friendly tool for healthcare professionals and researchers to assess heart disease risk based on patient data.  

## Dataset  

The dataset used in this project is derived from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease). It contains various features relevant to heart disease such as:  

- Age  
- Sex  
- Chest pain type  
- Resting blood pressure  
- Serum cholesterol  
- Fasting blood sugar  
- Resting electrocardiographic results  
- Maximum heart rate achieved  
- Angina  
- ST depression  
- Slope of peak exercise ST segment  
- Number of major vessels (0-3) colored by fluoroscopy  
- Thalassemia  
- Target variable (1 = heart disease; 0 = no heart disease)  

## Installation  

To set up this project locally, follow the steps below:  

1. **Clone this repository:**  
   ```bash  
   git clone https://github.com/yourusername/heart-disease-prediction.git  
Navigate into the project directory:
cd heart-disease-prediction  
Install required packages:
It is recommended to use a virtual environment. You can install the required libraries using:
pip install -r requirements.txt  
Usage
To run the heart disease prediction model, execute the following command:

python predict.py  
You will be prompted to enter patient data, and the model will output the likelihood of heart disease based on the provided parameters.

Models
This project employs several machine learning models to predict heart disease, including:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Support Vector Machine (SVM)
The performance of each model is evaluated using accuracy and other metrics to determine the best predictive model.

Results
Results and evaluation metrics, including confusion matrices and classification reports, can be found in the results folder. The best model and its parameters are discussed in the Jupyter Notebook located in the notebooks directory.

Contributing
Contributions are welcome! If you would like to contribute to this project, please fork the repository and create a pull request. Make sure to update documentation and tests as necessary.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments
UCI Machine Learning Repository for providing the dataset.
Various open-source libraries that made this project possible.

# SMS Spam Mail Detection Model

## Overview
SMS Spam mail Detection is a machine learning model that takes an SMS as input and predicts whether the message is a spam or not spam message. The model is built using Python and deployed on the web using Streamlit.

## Technology Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Streamlit

## Features
- Data collection
- Data cleaning and preprocessing
- Exploratory Data Analysis
- Model building and selection
- Web deployment using Streamlit
- Cyber Security


### Model Building and Selection
Multiple classifier models were tried, including NaiveBayes, random forest, KNN, decision tree, logistic regression, ExtraTreesClassifier, and SVC. The best classifier was chosen based on precision, with a precision of 100% achieved.

### Web Deployment
The model was deployed on the web using Streamlit. The user interface has a simple input box where the user can input a message, and the model will predict whether it is spam or not spam.


## Usage
To use the SMS Spam mail Detection model on your own machine, follow these steps:

+ Clone this repository.
+ Install the required Python packages using 
```
pip install -r requirements.txt.
```
+ Run the model using 
```
streamlit run app.py.
```
+ Visit localhost:8501 on your web browser to access the web app.

## Contributions
Contributions to this project are welcome. If you find any issues or have any suggestions for improvement, please open an issue or a pull request on this repository.



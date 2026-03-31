# AIML-PROJECT

# Heart Disease Prediction System

## Overview

This project is a machine learning-based system that predicts whether a person is likely to have heart disease based on medical attributes.

It uses a Random Forest Classifier trained on a structured dataset to perform binary classification:

* 0-No heart disease
* 1-Heart disease present

## Features

* Data preprocessing pipeline (handling missing values, encoding)
* Binary classification model
* Model evaluation with multiple metrics
* Sample prediction demonstration


## Dataset

* Source: Kaggle Heart Disease Dataset
* File used: `heart_disease_uci.csv`


## Tech Stack

* Python
* Pandas
* Scikit-learn
* KaggleHub


## How It Works

1. Load dataset
2. Clean and preprocess data
3. Encode categorical features
4. Split into training and testing sets
5. Train Random Forest model
6. Evaluate performance
7. Make predictions


## Installation & Setup

### Step 1: Clone the repository

```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
```

### Step 2: Install dependencies

```bash
pip install pandas scikit-learn kagglehub
```

### Step 3: Run

```bash
python main.py
```


## Output

* Accuracy score
* Classification report
* Sample prediction result


## Example Output

```
Accuracy: 0.84

Prediction: Heart Disease Detected
```


## Limitations

* Small dataset
* No hyperparameter tuning
* Not suitable for clinical use


## Future Improvements

* Add web interface (Flask/Django)
* Use larger datasets
* Improve model performance
* Add explainable AI


## Author

Tanisha Deshpande

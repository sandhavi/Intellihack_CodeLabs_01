# Weather Forecasting Using Machine Learning

## Overview
This repository contains a comprehensive analysis and implementation of machine-learning techniques to predict rainfall based on historical weather data. By leveraging classification algorithms, we aim to provide accurate predictions to assist in agricultural planning and other weather-dependent activities.

## Objectives
- **Data Cleaning and Preprocessing**: Address missing values, duplicates, and incorrect data types to ensure data quality.
- **Feature Engineering**: Develop temporal, lagged, rolling, and interaction features to enhance model performance.
- **Exploratory Data Analysis (EDA)**: Understand relationships between weather features and the target variable.
- **Model Development and Evaluation**: Train and compare multiple models (Logistic Regression, Random Forest, Gradient Boosting, SVM) using performance metrics.
- **Predict Rain Probability**: Provide the final output that includes the predicted probability of rain.

## Dataset
The dataset comprises 300 days of daily weather observations with the following features:
- `avg_temperature`: Number of purchases made by the customer
- `humidity`: Daily humidity (%)
- `avg_wind_speed`: Average wind speed (km/h)
- `rain_or_not`: Binary label (1 = Rain, 0 = No Rain)
- `date`: Date of observation

## Installation and Setup

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Git

### Clone the Repository
```bash
git clone https://github.com/sandhavi/Intellihack_CodeLabs_01
cd Intellihack_CodeLabs_01
```

### Create a Virtual Environment (Optional but Recommended)
```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

### Install Dependencies
on terminal
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Dependencies
The following Python libraries are required:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

## Repository Structure
```
├── Reports
|  ├── IntelliHack_CodeLabs_01_1.pdf
|  ├── IntelliHack_CodeLabs_01_2.pdf
|  ├── IntelliHack_CodeLabs_01.pdf
├── IntelliHack_CodeLabs_01_1.ipynb
├── IntelliHack_CodeLabs_01_2.ipynb
├── README.md                            
├── rain_prediction_model.pkl             
├── weather_data.csv                                                      
```

## Analysis Workflow
1. **Data Preprocessing**: Cleaning, handling missing values, and feature engineering
2. **Exploratory Data Analysis**: Understanding feature distributions and correlations
3. **Model Development**: Implementing and training models like Logistic Regression, Random Forest, Gradient Boosting, and SVM.
4. **Model Evaluation**: Assessing models using metrics such as accuracy, precision, recall, F1 score, and ROC AUC.
5. **Hyperparameter Tuning**: Optimizing model parameters using GridSearchCV.
6. **Predict Rain Probability**: Generating and visualizing the predicted probabilities of rain.

## Contributors
- Team: CodeLabs
- Task Number: Task-02

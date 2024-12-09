
# **Predicting High-Risk Groups for Obesity Based on Demographics and Lifestyle**
This project is part of the Introduction to Artificial Intelligence (AAI-501-02) course in the Applied Artificial Intelligence Program at the University of San Diego (USD).

**-- Project Status: In-Progress**

### Installation

To run this project on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/isralennon/MSAAI501.git```
2. Run with Jypiter: https://jupyter.org/install 

## Jupyter Notebook File Location
Our Jupyter Notebook file can be found in subfolder FinalProject under file name Obesity_Risk_Prediction_Model.ipynb.

## Project Intro/Objective
This project aims to develop a classification model to identify individuals at high risk for obesity based on their demographic and lifestyle characteristics. By analyzing eating habits, physical activity levels, and other relevant factors, the model will predict obesity risk categories, enabling public health organizations to allocate resources more effectively and design targeted obesity prevention programs. Given the increasing rates of obesity globally and its associated health costs, an early identification tool can be instrumental in reducing public health burdens and improving individual health outcomes.

### Contributors
- Alexander J Padin
- Jamshed Nabizaba
- Israel Romero Olvera

### Technologies
- Python
- Jupyter Notebook

## Project Description

#### Dataset
- **Source**: https://www.kaggle.com/datasets/fatemehmehrparvar/obesity-levels/data
- **Size**: The dataset contains *2111*  rows and *17* columns.

#### Models Used
- **Random Forest:** An ensemble model that builds multiple decision trees and combines them for more stable and accurate predictions.
- **Support Vector Machine (SVM):** Finds the hyperplane that best separates classes in the feature space, maximizing the margin between classes.
- **Logistic Regression:** A linear model that predicts class probabilities based on feature values.
- **Decision Tree:** A model that splits data into decision nodes based on feature values, creating an interpretable path to classification.


#### Project Steps:

1. **Import Libraries**: Import necessary Python libraries for data manipulation, visualization, and machine learning. Common libraries include `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn`.
2. **Load Data**: Load the dataset into a Pandas DataFrame. Inspect the data structure to understand the features, target variable, and data types.
3. **Data Preprocessing**: Prepare the data for analysis by handling missing values and encoding categorical variables.
4. **Exploratory Data Analysis (EDA)**: Visualize and analyze the data to identify patterns, correlations, and distributions among features. 
5. **Data Splitting and Scaling**: Split the dataset into training, validation, and test sets to allow for proper model evaluation. 
6. **Model Selection and Training**: Select and train various machine learning models (e.g., Logistic Regression, Decision Tree, Random Forest, SVM).
7. **Model Evaluation**: Assess the performance of each model using metrics such as accuracy, precision, recall, F1-score, and confusion matrices.
8. **Conclusion**: Summarize findings, including the best-performing model and key insights. 

#### License
This project is licensed under the GNU License - see the [LICENSE.txt](LICENSE.txt) file for details.


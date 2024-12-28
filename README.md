# Titanic-Survival-Prediction-
This project analyzes the Titanic dataset to uncover patterns and insights related to survival rates. The notebook performs exploratory data analysis (EDA), data visualization, and predictive modeling to understand the factors influencing passenger survival.
Dataset

The dataset used for this analysis is the Titanic dataset provided by Kaggle. It includes:

PassengerID: Unique identifier for each passenger

Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

Name: Name of the passenger

Sex: Gender

Age: Age of the passenger

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Ticket: Ticket number

Fare: Ticket fare

Cabin: Cabin number (if available)

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Setup and Requirements

Prerequisites

Ensure you have the following installed:

Python 3.7+

Jupyter Notebook

Libraries: pandas, numpy, matplotlib, seaborn, sklearn

Installation

# Clone the repository
git clone https://github.com/yourusername/titanic-analysis.git

# Navigate to the project directory
cd titanic-analysis

# Install required packages
pip install -r requirements.txt

Analysis Steps

Data Loading:

Load the dataset into a pandas DataFrame.

Exploratory Data Analysis (EDA):

Understand the structure of the dataset.

Handle missing values and perform data cleaning.

Generate summary statistics.

Data Visualization:

Create visualizations to identify trends and relationships between features.

Visualize survival rates based on gender, class, age, and other factors.

Feature Engineering:

Derive new features to enhance predictive modeling.

Model Building:

Train machine learning models (e.g., Logistic Regression, Random Forest) to predict survival.

Evaluate model performance using accuracy, precision, recall, and F1-score.

Key Findings

Gender and class significantly influenced survival rates.

Passengers in 1st class had higher survival probabilities than those in 2nd or 3rd class.

Women and children were more likely to survive than men.

How to Run

Open the Jupyter Notebook:

jupyter notebook Titanic.ipynb

Execute the cells sequentially to follow the analysis workflow.

Technologies Used

Python: Core programming language

Pandas: Data manipulation and analysis

Matplotlib/Seaborn: Data visualization

Scikit-learn: Machine learning

Future Work

Enhance the feature engineering process.

Experiment with advanced machine learning models like Gradient Boosting or Neural Networks.

Create a web application for real-time survival predictions.


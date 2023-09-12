# data-analysis-datathon2023-competition
I performed an extensive data analysis on the competition dataset, covering EDA (Exploratory Data Analysis), Data Visualization and ML (Machine Learning) processes

## Table of Contents
- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building](#model-building)
- [Results](#results)
- [Conclusion](#conclusion)


## Introduction
This project aims to predict the target variable of "Öbek İsmi" in train dataset and make prediction at test dataset. We used Python and various data analysis libraries such as Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn to analyze the data and build predictive models.


## Exploratory Data Analysis
- Explored the distribution of all features with a histogram.
- Visualized the correlation between each feature1 and feature2 using a scatter plot.


## Data Preprocessing
- Handled missing values
- Encoded categorical variable
- Scaled numerical features

## Model Building
- Trained several machine learning models including Random Forest, CatBoost, and LightGBM.
- Tuned hyperparameters using GridSearchCV.
- Evaluated models based on accuracy, precision, recall, and F1 score.


## Usage
To use the code in this project, follow these steps:

Clone the Repository:

Open your terminal or command prompt.

Navigate to the directory where you want to clone the repository.

Run the following command to clone the repository to your local machine:

'''bash
  git clone https://github.com/ahmetdzdrr/data-analysis-datathon2023-competition.git
  
Install Required Dependencies:

Navigate to the project directory on your local machine using the terminal or command prompt.

Create a virtual environment (optional but recommended):

'''bash
  python -m venv venv


Activate the virtual environment:

On Windows:

'''bash
  venv\Scripts\activate
  
On macOS and Linux:

'''bash
source venv/bin/activate

Install the required dependencies using pip:

'''bash
  pip install -r requirements.txt


Run the Script:

After cloning the repository and installing the dependencies, you can run the main script by executing the following command:

'''bash
  python script_name.py



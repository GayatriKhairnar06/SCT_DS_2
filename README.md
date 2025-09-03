# Titanic Survival Prediction – Data Cleaning & EDA

This project explores the Kaggle Titanic dataset by performing data cleaning and exploratory data analysis (EDA). The goal is to understand relationships between variables, identify survival patterns, and prepare data for machine learning models.

📂 Dataset

The dataset comes from the Kaggle Titanic Competition
.

train.csv → Training data with passenger details + survival labels

test.csv → Test data (without labels)

gender_submission.csv → Sample submission file

🧹 Data Cleaning

Steps performed:

Filled missing Age values with median.

Filled missing Embarked values with mode.

Dropped Cabin (too many missing values).

Removed duplicate rows.

📊 Exploratory Data Analysis (EDA)

Key analyses and plots:

Survival Distribution (balanced vs imbalanced)

Gender vs Survival → Women survived more often than men

Age Distribution → Most passengers were 20–40 years old

Age vs Survival → Younger passengers had slightly better chances

Passenger Class vs Survival → Higher survival in 1st class

Correlation Heatmap → Survival positively correlated with Fare & Sex

📌 Insights

Women had a much higher chance of survival.

First-class passengers survived at higher rates than those in third class.

Younger passengers (especially children) had better survival chances.

Higher fare values indicated better survival probability.

⚙️ Tech Stack

Python 3.x

Pandas, NumPy – Data manipulation

Matplotlib, Seaborn – Visualization

Jupyter Notebook – Analysis

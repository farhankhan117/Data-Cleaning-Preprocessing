🚢 Titanic Dataset – Data Cleaning & Preprocessing
🎯 Objective
Explore and preprocess the Titanic dataset to understand the structure, handle missing values, encode categorical variables, scale numerical features, and remove outliers to prepare the data for machine learning applications.

🛠️ Tools & Libraries
Python

Pandas, NumPy

Matplotlib, Seaborn


🔍 Summary of Steps
Loaded the dataset and examined its structure and statistical summary

Filled missing values:

Age filled with median

Embarked filled with mode

Dropped Cabin column due to excessive missing data

Categorical Encoding:

Label encoded Sex (binary)

One-hot encoded Embarked (multi-class)

Scaled numerical features Age and Fare using StandardScaler

Detected and removed outliers in Fare (>300) using boxplot

Finalized a clean and structured dataset for further modeling

✅ Conclusion
The Titanic dataset has been cleaned and preprocessed effectively:

No missing values remain

Categorical variables are properly encoded

Numerical features are standardized

Outliers in fare values have been removed

The resulting dataset is well-prepared for building predictive models or conducting deeper analysis.

📁 Project Files
Titanic-Dataset.csv – Raw dataset

titanic_cleaning.ipynb – Code for data cleaning and preprocessing

README.md – Project summary and documentation

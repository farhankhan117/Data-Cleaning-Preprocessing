# Titanic Dataset - Data Cleaning and Preprocessing

## Objective  
Explore and preprocess the Titanic dataset to handle missing values, encode categorical variables, scale numerical features, and remove outliers to prepare data for modeling.

## Tools & Libraries  
- **Python, Pandas, NumPy**  
- **Matplotlib, Seaborn**  
  

## Summary of Steps  
- Loaded dataset and examined its structure and basic statistics  
- Filled missing values: replaced **Age** with median, **Embarked** with mode, and dropped **Cabin** column due to excessive missing data  
- Applied label encoding on **Sex** and one-hot encoding on **Embarked**  
- Standardized numerical columns **Age** and **Fare**  
- Detected and removed outliers in **Fare** (>300) using boxplot visualization  
- Created a cleaned and processed dataset ready for machine learning tasks  

## Conclusion  
The dataset is now clean, with no missing values and correctly encoded categorical variables. Outliers have been handled, and numerical features standardized, making the dataset suitable for further analysis and model building.

## Project Files  
- `Titanic-Dataset.csv` - Raw data  
- `titanic_cleaning.ipynb` - Data cleaning and preprocessing code  
- `README.md` - This summary

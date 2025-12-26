# 🚢 Titanic Dataset – Data Cleaning and Preprocessing

## 🎯 Objective
Explore and preprocess the Titanic dataset to handle missing values, encode categorical variables, scale numerical features, and remove outliers to prepare the data for machine learning models.

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔍 Summary of Steps
### 1. Data Exploration
- Loaded the dataset
- Inspected data structure, data types, and basic statistics

### 2. Handling Missing Values
- Replaced missing values in **Age** with the median
- Replaced missing values in **Embarked** with the mode
- Dropped the **Cabin** column due to excessive missing data

### 3. Encoding Categorical Variables
- Applied **Label Encoding** to the **Sex** column
- Applied **One-Hot Encoding** to the **Embarked** column

### 4. Feature Scaling
- Standardized numerical features:
  - **Age**
  - **Fare**

### 5. Outlier Detection & Removal
- Identified outliers in **Fare** using boxplot visualization
- Removed records with **Fare > 300**

### 6. Final Dataset
- Created a clean and processed dataset
- Dataset is now ready for modeling and further analysis

---

## ✅ Conclusion
The Titanic dataset has been successfully cleaned and preprocessed:
- No missing values remain
- Categorical variables are properly encoded
- Numerical features are standardized
- Outliers have been handled

The dataset is now suitable for machine learning tasks and predictive modeling.

---

## 📁 Project Files
- `Titanic-Dataset.csv` – Raw dataset  
- `Data_Cleaning_and_Preprocessing.ipynb` – Data cleaning and preprocessing notebook  
- `README.md` – Project documentation  

---

## 🚀 Next Steps
- Perform Exploratory Data Analysis (EDA)
- Train classification models (Logistic Regression, Random Forest, etc.)
- Evaluate model performance using accuracy and ROC-AUC



---

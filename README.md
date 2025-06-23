# Task-1-Data-Cleaning-and-preprocessingAdd commentMore actions
Titanic dataset cleaning and preprocessing with Python

**Dataset**
File: Titanic-Dataset.csv
Location: Loaded from Google Drive
Columns Used: Age, Fare, Sex, Embarked, SibSp, Parch (among others)

**Tools & Libraries**
Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn (StandardScaler, LabelEncoder)

**Steps Performed**
1. Imported the dataset and displayed shape, head, and info.
2. Checked for missing values and handled them using:
    Median for numerical (Age)
    Mode for categorical (Embarked)
3.Dropped unused column (Cabin, if it existed)
4.Encoded categorical columns:
   Sex: female → 0, male → 1
   Embarked: C → 0, Q → 1, S → 2
5..Normalized numerical columns:
   Age and Fare scaled using StandardScaler
6.Visualized outliers using boxplots
7.Removed outliers using the IQR method for:
   Age, Fare, SibSp, Parch
8.Replotted boxplots after cleaning to confirm removal

**Output**
Cleaned dataset shape: shown after outlier removal
Boxplots before and after cleaning
Ready for use in machine learning models

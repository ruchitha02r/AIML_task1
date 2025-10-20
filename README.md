# Titanic Dataset - Data Preprocessing

📋 Project Overview
Data preprocessing and exploratory analysis of the Titanic dataset to prepare it for machine learning models.

📊 Dataset
- **891 passengers** with 12 features
- **Target**: Survival (0 = No, 1 = Yes)
- Mixed data types: numerical, categorical, and text

🛠️ Preprocessing Steps

1. **Missing Values**
- `Age`: Filled with median
- `Embarked`: Filled with mode ('S') 
- `Cabin`: Dropped (77% missing)

2. **Feature Encoding**
- `Sex`: Label encoded (female=0, male=1)
- `Embarked`: One-hot encoded
- Dropped: `Name`, `Ticket`

3. **Feature Scaling**
Standardized: `Age`, `Fare`, `SibSp`, `Parch`

4. **Outlier Detection**
- IQR method identified outliers in all numerical features
- Z-score analysis: 27 outlier rows

📈 Key Insights
- **Survival rate**: 38%
- **Missing values handled**: Age (177), Embarked (2), Cabin (dropped)
- **Outliers detected**: Age (66), Fare (116), SibSp (46), Parch (213)

🚀 Usage
Run `task1.ipynb` to reproduce the analysis.

**Ready for machine learning models!**

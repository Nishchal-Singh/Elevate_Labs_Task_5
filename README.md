# Elevate_Labs_Task_5
# Titanic Dataset – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project is part of **Task 5: Data Analysis** and focuses on performing Exploratory Data Analysis (EDA) on the Titanic dataset.  
The aim is to explore patterns, detect anomalies, and identify key factors that influenced passenger survival during the Titanic disaster of 1912.  

The analysis includes:
- Data cleaning and handling missing values  
- Feature engineering (e.g., FamilySize, Title, Deck)  
- Descriptive statistics and visualizations  
- Examination of relationships between features and survival  
- Summary of findings and recommendations for predictive modeling  

---

## Key Analysis Steps

Data Overview: .info(), .describe(), .value_counts()

Univariate Analysis: Histograms, boxplots

Bivariate Analysis: Survival by Sex, Pclass, Embarked

Multivariate Analysis: Pairplot, correlation heatmap

Data Issues Addressed: Missing values, outliers, skewness

Feature Engineering: FamilySize, Title, Deck extraction, Age and Fare binning

## 📑 Findings (Highlights)

Females and children had significantly higher survival rates.

1st class passengers survived more often than 3rd class passengers.

Higher fares were strongly associated with survival.

Missing Age and Cabin values required imputation or transformation.

## 🚀 Next Steps

Apply predictive modeling (e.g., logistic regression, decision trees).

Use engineered features (FamilySize, Title, Deck) in models.

Drop or combine highly correlated features to avoid multicollinearity.

## Conclusion

The exploratory data analysis of the Titanic dataset revealed several important insights into the factors influencing passenger survival. Demographic attributes such as sex and age, alongside travel-related features such as class and fare, showed clear associations with survival outcomes. Females, children, and first-class passengers exhibited higher survival rates, while third-class male passengers had the lowest survival probabilities.

The analysis also highlighted data quality issues, including missing values in Age and Cabin, as well as the presence of skewness in the Fare variable. Appropriate handling through imputation, feature engineering (e.g., family size, passenger title, deck extraction), and transformation improved the dataset’s suitability for further modeling.

Overall, the EDA not only provided descriptive insights into passenger survival patterns but also laid the foundation for predictive modeling by identifying key predictors and potential multicollinearity concerns.

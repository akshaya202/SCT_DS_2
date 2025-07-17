Titanic Dataset EDA & Data Cleaning
1. Overview
This project analyzes the Titanic passenger dataset to uncover factors influencing survival.

2. Data Cleaning
Dropped cabin,body,home.dest  due to high missing rate
Imputed age with median
Imputed embarked with mode
Filled remaining null values

3. Feature Engineering
Added family_size = sibsp + parch
Created alone (1 if no family aboard, else 0)

4. Univariate Analysis
Age: positively skewed (median-biased); mostly 20–30-year-olds
Fare: wide right tail, indicating few high-paying passengers

5. Bivariate Analysis
Sex: females ~75% survival; males ~20%
Passenger Class: 1st class >2nd class >3rd class survival rates
Fare & Survival: survivors paid more on average
Age & Survival: children and 20–50-year-old women had higher survival
Family/Alone: traveling alone lowers survival; medium families do better

6. Correlations
Strong positive correlation: fare ↔ survival
Moderate: pclass ↔ survival
Weak: age/family_size vs survival

7. Key Patterns
women have high survival rate than male
Women and children first have high survival rate
Wealth and class strongly influenced lifeboat access
Traveling alone was a disadvantage


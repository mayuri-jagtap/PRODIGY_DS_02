# Titanic EDA Project

This project showcases "Exploratory Data Analysis (EDA) and data cleaning" on the Titanic dataset from the Kaggle competition:- [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic).



# Objective

To explore the Titanic dataset, handle missing data, analyze trends, and visualize relationships between features such as passenger class, gender, age, and survival status.



# Dataset Information

- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- File Used: `train.csv`
- Reason: It contains all the features and the target variable `Survived`, which is essential for analysis.

---

# Technologies & Libraries Used

- Python (Jupyter Notebook)
- Pandas
- NumPy
- Matplotlib
- Seaborn



# Key Explorations & Visualizations

- Survival distribution by gender and class
- Age distribution and survival correlation
- Correlation heatmap of numeric features
- Handling missing data in `Age`, `Embarked`
- Dropping high-missing-value column `Cabin`



# Key Observations

-  Females had a significantly higher survival rate than males.
-  First-class passengers were more likely to survive than those in lower classes.
-  Children and younger passengers showed higher survival chances.
-  The `Cabin` column was dropped due to a large number of missing values.
-  Missing values in `Age` and `Embarked` were filled using median and mode, respectively.



# Repository Contents

| File Name                    | Description                                  |
|------------------------------|--------------------------------------------- |
| `Titanic-EDA-Project.ipynb`  | Jupyter Notebook with EDA and visualizations |
| `train.csv`                  | Titanic dataset used for analysis            |
| `README.md`                  | Project overview and documentation           |



# Learning Outcomes

- Gained hands-on experience with data cleaning techniques
- Practiced data visualization using Matplotlib and Seaborn
- Learned how to identify trends and correlations within real-world datasets





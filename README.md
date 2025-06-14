# Titanic-Dataset---Exploratory-Data-Analysis-hist-
https://www.kaggle.com/code/ajay9020/titanic-dataset-exploratory-data-analysis-hist?scriptVersionId=245356846
🚢 Titanic - Exploratory Data Analysis (EDA)
This project performs an in-depth Exploratory Data Analysis (EDA) on the Titanic dataset using Python, with a focus on:

Understanding feature distributions

Identifying and imputing missing values

Detecting outliers

Exploring survival relationships based on gender, class, age, fare, and family size

🔍 Key Features
Missing value handling using Iterative Imputer with a Random Forest Regressor

Visual analysis using:

📊 Histograms (for age, fare)

📦 Box plots (for outlier detection)

🔥 Heatmaps (missing data, correlation)

🧮 Count plots and cat plots (for survival across categories)

Feature engineering (e.g., age_group, family_size)

Clear, visually appealing Seaborn plots to support insights

📁 Dataset
The dataset is loaded directly from the Seaborn library:

python
Copy
Edit
sns.load_dataset('titanic')
📊 Libraries Used
pandas, numpy

seaborn, matplotlib

sklearn.impute.IterativeImputer

sklearn.ensemble.RandomForestRegressor

📌 How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/yourusername/titanic-eda.git
cd titanic-eda
Run the notebook:

bash
Copy
Edit
jupyter notebook Titanic_EDA.ipynb
📈 Sample Visuals


📚 Insights Gained
Females had a significantly higher survival rate.

1st-class passengers were more likely to survive.

Children (age < 18) had better chances of survival.

Fare had a strong positive correlation with survival likelihood.

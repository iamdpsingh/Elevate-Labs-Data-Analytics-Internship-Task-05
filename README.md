# Elevate-Labs-Data-Analytics-Internship-Task-05
Task 5: Exploratory Data Analysis (EDA)

# Task 5: Exploratory Data Analysis (EDA)

## 📊 Objective

To perform Exploratory Data Analysis (EDA) on a dataset (Titanic dataset or any relevant dataset) to uncover meaningful insights through statistical summaries and visualizations.

---

## 🧰 Tools & Libraries

- **Python**
- **Jupyter Notebook**
- **Pandas** – for data manipulation
- **Seaborn** – for visualizations
- **Matplotlib** – for plotting
- **NumPy** – for numerical operations

---

## 📂 Dataset

**Name**: Titanic Dataset  
**Source**: [Kaggle - Titanic dataset ]([https://www.kaggle.com/competitions/titanic/data](https://www.kaggle.com/datasets/brendan45774/test-file))

---

## 🔍 EDA Workflow

### 1. **Loading Data**
- Read the dataset using `pandas.read_csv()`
- Display the first few records using `df.head()`

### 2. **Understanding Data**
- Use `df.info()`, `df.describe()` to get a summary
- Check unique value counts with `value_counts()`
- Identify and handle missing values

### 3. **Univariate Analysis**
- Histograms for numerical columns
- Countplots for categorical columns
- Boxplots to detect outliers

### 4. **Bivariate & Multivariate Analysis**
- `sns.heatmap()` to analyze correlations
- `sns.pairplot()` for relationship visualizations
- Scatter plots, violin plots, and bar plots for feature interaction

### 5. **Handling Missing Data**
- Dropped or filled missing values using strategies like:
  - Median imputation for `Age`
  - Dropping `Cabin` due to excessive nulls

---

## 📈 Key Visuals

- Age distribution
- Survival rate by gender and class
- Correlation heatmap of numeric features
- Fare distribution and relationship to survival
- Violin plot of Age and Survival by Gender

---

## 📌 Observations

- **Sex**: Females had higher survival rates
- **Pclass**: 1st class passengers were more likely to survive
- **Age**: Children and younger adults survived more
- **Fare**: Higher fare correlated with better survival odds
- **Missing Data**: ‘Cabin’ had many missing values and was dropped

---

## 🧾 Deliverables

- ✅ Jupyter Notebook (`task 05.ipynb`)
- ✅ Exported PDF Report of EDA
- ✅ This `README.md` file with summary and methodology

---

## 🎯 Outcome

- Gained hands-on experience in data cleaning, visualization, and summarization
- Learned to identify patterns, trends, and anomalies in a dataset
- Built skills in using Pandas, Matplotlib, and Seaborn for EDA

---



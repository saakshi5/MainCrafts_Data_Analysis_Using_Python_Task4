# MainCrafts_Data_Analysis_Using_Python_Task4
Titanic Dashboard

## 📌 Project Overview

This project presents a Mini Data Visualization Dashboard built using Python, Matplotlib, and Seaborn. The goal of this task was to perform Exploratory Data Analysis (EDA) on the Titanic dataset and communicate key insights through clear and meaningful visualizations.

The notebook includes data cleaning, simple feature engineering, grouped analysis, and multiple visualizations with concise insights.

---

## 📂 Dataset Used

**Dataset:** Titanic Dataset
**Source:** Kaggle – Titanic Machine Learning Competition
**File Used:** `Titanic-Dataset.csv`

### Dataset Description

The dataset contains passenger information such as:

* Passenger Class (Pclass)
* Name
* Sex
* Age
* SibSp (siblings/spouses aboard)
* Parch (parents/children aboard)
* Fare
* Embarked (port of embarkation)
* Survival status (Survived)

---

## 🧹 Data Cleaning Performed

* Filled missing **Age** values using mean imputation
* Dropped **Cabin** column due to excessive missing values
* Filled missing **Embarked** values using mode
* Created new features:

  * `FamilySize = SibSp + Parch`
  * `AgeGroup` (Child, Teen, Young Adult, Adult, Senior)

---

## 📊 Visualizations Included

* Survival Rate by Gender
* Survival Rate by Passenger Class
* Age Distribution (Histogram)
* Survival Rate by Family Size
* Survival Rate by Age Group
* Correlation Heatmap

Each visualization includes short, clear insights for better storytelling.

---

## ▶️ How to Run This Project (Google Colab)

### Step 1: Open Google Colab

Go to: [https://colab.research.google.com](https://colab.research.google.com)

### Step 2: Upload the Notebook

Upload:

```
Titanic_Visualization_Dashboard_Task4.ipynb
```

### Step 3: Upload Dataset

Upload:

```
Titanic-Dataset.csv
```

### Step 4: Install Required Libraries (if needed)

```python
pip install pandas numpy matplotlib seaborn
```

### Step 5: Run All Cells

Click:

```
Runtime → Run All
```
---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## 🎯 Key Learnings

* Handling real-world missing data
* Feature engineering
* Groupby analysis
* Creating professional visual dashboards
* Communicating insights effectively

---

## 📎 Author

Sakshi Sataye
Data Science Internship – Task 4


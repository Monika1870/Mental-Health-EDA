# 🧠 Mental Health in the Workplace – Exploratory Data Analysis

An end-to-end Exploratory Data Analysis (EDA) project on a large-scale Mental Health Survey dataset to understand how demographic, occupational, lifestyle, and family-related factors influence mental health and treatment-seeking behavior.

The project focuses on transforming raw survey data into meaningful insights through data cleaning, preprocessing, visualization, and structured analysis.

---

## 📌 Project Overview

Mental health is one of the most important yet often overlooked aspects of workplace well-being. Organizations need a better understanding of the factors that influence stress, mental health awareness, and willingness to seek professional treatment.

This project performs a structured Exploratory Data Analysis on **292,405 survey responses** to identify patterns related to:

- Mental health treatment
- Family history
- Occupation
- Stress levels
- Mood swings
- Indoor lifestyle
- Social interaction
- Gender

The notebook follows a complete EDA workflow—from understanding the data to drawing actionable insights.

---

## 🎯 Objectives

- Explore the structure and quality of the dataset.
- Clean inconsistent and duplicate records.
- Standardize categorical variables.
- Perform univariate, bivariate, and multivariate analysis.
- Identify factors associated with treatment-seeking behavior.
- Generate insights using statistical visualizations.

---

## 📊 Dataset Information

- **Rows:** 292,405
- **Columns:** 17
- **Data Type:** Categorical survey data
- **Domain:** Mental Health

---

## 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Removed duplicate records.
- Identified missing values.
- Standardized inconsistent gender labels into:
  - Male
  - Female
  - Other
- Ignored the Timestamp column because it contained inconsistent date formats and was not required for the analysis.
- Verified data quality before visualization.

---

## 📈 Exploratory Data Analysis

### 1️⃣ Univariate Analysis

Analyzed the distribution of individual variables including:

- Gender
- Treatment
- Growing Stress
- Family History
- Occupation

Key observations include:

- Majority of respondents are male.
- Treatment responses are almost evenly split.
- Many respondents selected "Maybe" for stress.
- Most respondents have no family history of mental illness.
- Housewives, students, and corporate employees form a large portion of the dataset.

---

### 2️⃣ Bivariate Analysis

Studied relationships between two variables.

Analysis includes:

- Family History vs Treatment
- Days Indoors vs Growing Stress
- Occupation vs Mood Swings
- Social Weakness vs Mental Health
- Gender vs Mental Health Discussion

Major findings:

- Family history strongly influences treatment-seeking.
- Staying indoors alone does not explain stress levels.
- Students exhibit comparatively higher mood swings.
- Most people are uncomfortable discussing mental health regardless of gender.

---

### 3️⃣ Multivariate Analysis

Investigated interactions among multiple variables using heatmaps and grouped visualizations.

Key analyses include:

- Occupation × Family History × Treatment
- Family History × Habit Changes × Growing Stress

Major findings:

- Family history has a stronger influence on treatment than occupation.
- Individuals unsure about changes in their habits tend to report higher stress.
- Mental health history and behavioral changes together explain stress patterns better than occupation alone.

---

## 📌 Key Insights

- Family history is the strongest predictor of treatment-seeking behavior.
- Occupation has relatively little impact on whether individuals seek treatment.
- Students show higher levels of mood swings than most occupational groups.
- Stress cannot be explained solely by time spent indoors.
- Mental health discussions remain uncomfortable across all genders.
- Behavioral changes combined with family history provide better insight into stress growth.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Repository Structure

```
Mental-Health-EDA/
│
├── Mental_Health_EDA.ipynb
├── images/
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

Clone the repository

```bash
git clone https://github.com//Monika1870/Mental-Health-EDA.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Mental_Health_EDA.ipynb
```

---

## 📷 Visualizations

The notebook includes multiple visualizations such as:

- Count plots
- Bar charts
- Heatmaps
- Cross-tab visualizations
- Distribution analysis

These visualizations help uncover hidden relationships within the survey responses.

---

## 🚀 Future Improvements

- Build a predictive model for treatment recommendation.
- Develop an interactive Power BI or Tableau dashboard.
- Explore feature importance using Machine Learning models.

---

## 👩 Author

**Monika Gautam**


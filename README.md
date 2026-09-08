# 📊 Data Science Internship Projects

A collection of hands-on **Data Science and Data Analytics projects** completed during my internship at **SkillCraft Technology (SCT)**.

The projects cover the complete data science workflow, including **data preprocessing, exploratory data analysis, data visualization, geospatial analysis, statistical analysis, and machine learning classification** using Python.

---

## 🚀 Internship Overview

During this internship, I worked on multiple real-world datasets to develop practical skills in:

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Data Visualization
* Geospatial Data Analysis
* Feature Engineering
* Categorical Encoding
* Machine Learning
* Classification
* Model Evaluation
* Business-oriented Data Interpretation

---

# 🗂️ Projects

## 1. 🌍 World Population Analysis

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, GeoPandas

Analyzed global population data to understand population distribution, population density, and differences across countries and continents.

### Dataset

The dataset contains information for **234 countries and territories**, including:

* Country / Territory
* Capital
* Continent
* Population from 1970–2022
* Area
* Population Density
* Population Growth Rate
* World Population Percentage

### Key Tasks

* Loaded and inspected the dataset
* Performed data-quality checks
* Analyzed descriptive statistics
* Compared population across continents
* Analyzed population density
* Examined population growth
* Created geographical visualizations
* Merged population data with geographic boundary data using GeoPandas
* Created a world population choropleth map

### Visualizations

* Population distribution by continent
* Population density distribution
* World population map
* Population comparisons

### Skills Demonstrated

`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `GeoPandas` `EDA` `Geospatial Analysis`

---

# 2. 🚢 Titanic Exploratory Data Analysis

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn

Performed exploratory data analysis on a Titanic passenger dataset to investigate the relationship between passenger characteristics and survival.

### Dataset

The dataset contains **1,000 passenger records** with features such as:

* Passenger ID
* Passenger Class
* Name
* Sex
* Age
* Siblings / Spouses
* Parents / Children
* Ticket
* Fare
* Embarkation Port
* Survival Status

### Key Analysis

* Inspected dataset structure
* Checked missing values
* Checked data types
* Analyzed survival distribution
* Studied survival by passenger class
* Analyzed age distribution
* Compared age between survivors and non-survivors
* Investigated age and fare relationships
* Created pair plots
* Analyzed survival rates across different passenger characteristics

### Visualizations

* Survival count plot
* Survival by passenger class
* Age distribution
* Age vs. survival box plot
* Pair plot
* Age vs. fare scatter plot
* Survival rate by age

### Key Insights

The analysis explored how factors such as **passenger class, age, fare and other passenger characteristics** were associated with survival.

### Skills Demonstrated

`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `EDA` `Data Visualization` `Statistical Analysis`

---

# 3. 🏦 Bank Marketing Prediction

**Tools:** Python, Pandas, NumPy, Scikit-learn

Built a **binary classification model** to predict whether a bank customer would subscribe to a term deposit.

This was the primary machine learning project of the internship.

---

## 🎯 Business Problem

Banks conduct marketing campaigns to encourage customers to subscribe to term deposits.

The objective was to predict:

```text
Will the customer subscribe to a term deposit?
```

Target variable:

```text
y
```

where:

```text
yes → Customer subscribes
no  → Customer does not subscribe
```

---

## 📊 Dataset

The dataset contains approximately **45,000 customer records** and **17 features**.

Features include:

### Customer Information

* Age
* Job
* Marital Status
* Education

### Financial Information

* Default
* Account Balance
* Housing Loan
* Personal Loan

### Campaign Information

* Contact Method
* Contact Day
* Contact Month
* Call Duration
* Campaign Contacts

### Previous Campaign Information

* Days Since Previous Contact
* Previous Contacts
* Previous Campaign Outcome

---

## 🔧 Data Preprocessing

The following preprocessing steps were performed:

* Loaded the semicolon-separated dataset
* Inspected dataset structure
* Checked missing values
* Identified categorical features
* Encoded categorical variables
* Separated features and target
* Split data into training and testing sets

### Train/Test Split

```text
80% → Training
20% → Testing
```

A fixed random state was used to make the experiment reproducible.

---

## 🤖 Machine Learning Model

### Decision Tree Classifier

A Decision Tree classification model was trained to predict customer subscription behavior.

Workflow:

```text
Raw Data
   ↓
Data Inspection
   ↓
Preprocessing
   ↓
Categorical Encoding
   ↓
Feature / Target Separation
   ↓
Train-Test Split
   ↓
Decision Tree Classifier
   ↓
Prediction
   ↓
Model Evaluation
```

---

## 📈 Model Performance

The model achieved approximately:

### **87.4% Accuracy**

However, accuracy was not considered in isolation because the target classes were imbalanced.

The classification report was also evaluated using:

* Precision
* Recall
* F1-score

The model performed considerably better on the majority class than on customers who actually subscribed.

This highlights an important machine-learning lesson:

> **Accuracy alone can be misleading when the target classes are imbalanced.**

---

## 🔍 Potential Improvements

Possible improvements to the model include:

* Class weighting
* SMOTE / oversampling
* Hyperparameter tuning
* Random Forest
* Gradient Boosting
* XGBoost
* Logistic Regression
* One-hot encoding
* ROC-AUC and PR-AUC evaluation

---

## 💡 Business Application

A successful prediction model could help banks:

* Identify potential customers
* Prioritize marketing calls
* Improve campaign targeting
* Reduce unnecessary outreach
* Allocate marketing resources more efficiently

### Skills Demonstrated

`Python` `Pandas` `NumPy` `Scikit-learn` `Data Preprocessing` `Classification` `Decision Trees` `Model Evaluation`

---

# 4. 🚗 Road Accident Data Analysis

**Tools:** Python, Pandas, Matplotlib, Seaborn

Analyzed state-wise road accident statistics from **2016 to 2019** to identify trends, high-accident regions, and relationships between accident-related indicators.

---

## 📊 Dataset

The dataset contains information for **37 Indian States/Union Territories**.

Variables include:

* Road accidents in 2016
* Road accidents in 2017
* Road accidents in 2018
* Road accidents in 2019
* 2019 accident rank
* Share of total accidents
* Accident rate per lakh population
* Accident rate per 10,000 vehicles
* Accident rate per road length
* Population and road/vehicle-related indicators

---

## 🔧 Data Preparation

Performed:

* Dataset inspection
* Data-type verification
* Duplicate detection
* Missing-value analysis
* Column selection
* Column renaming
* Data preparation for visualization

### Data Quality

* Duplicate records were checked
* Missing values were identified
* Numerical variables were prepared for correlation analysis

---

## 📈 Analysis Performed

### Accident Trends

Analyzed accident counts from:

```text
2016 → 2017 → 2018 → 2019
```

to understand how accident levels changed over time.

---

### Top 10 States in 2019

Identified the states/UTs with the highest accident counts in 2019.

---

### Correlation Analysis

Calculated correlations between numerical variables to investigate relationships among:

* Accident counts
* Population-based accident rates
* Vehicle-based accident rates
* Road-related accident indicators
* Share of total accidents

---

## 📊 Visualizations

The project includes:

* Road accident trend line chart
* Top 10 states bar chart
* Correlation matrix
* Correlation heatmap

### Skills Demonstrated

`Python` `Pandas` `Matplotlib` `Seaborn` `EDA` `Correlation Analysis` `Data Visualization`

---

# 🛠️ Technology Stack

## Programming

* Python

## Data Analysis

* Pandas
* NumPy

## Visualization

* Matplotlib
* Seaborn

## Geospatial Analysis

* GeoPandas

## Machine Learning

* Scikit-learn

## Development Environment

* Jupyter Notebook

---

# 📚 Key Skills Developed

Through these projects, I gained practical experience in:

### Data Analysis

* Data inspection
* Data cleaning
* Data preprocessing
* Descriptive statistics
* Grouping and aggregation
* Missing-value analysis
* Duplicate detection

### Exploratory Data Analysis

* Distribution analysis
* Trend analysis
* Correlation analysis
* Relationship analysis
* Feature exploration

### Data Visualization

* Bar charts
* Line charts
* Histograms
* Box plots
* Scatter plots
* Pair plots
* Heatmaps
* Choropleth maps

### Machine Learning

* Feature/target separation
* Categorical encoding
* Train-test splitting
* Classification
* Decision Trees
* Model prediction
* Model evaluation
* Precision
* Recall
* F1-score

---

# 🔄 End-to-End Data Science Workflow

The internship projects followed a practical workflow:

```text
                 Raw Dataset
                      ↓
              Data Understanding
                      ↓
               Data Inspection
                      ↓
             Data Preprocessing
                      ↓
        ┌─────────────┴─────────────┐
        ↓                           ↓
 Exploratory Analysis          Feature Engineering
        ↓                           ↓
 Data Visualization            ML Preparation
        ↓                           ↓
        └─────────────┬─────────────┘
                      ↓
                Model Building
                      ↓
                Model Evaluation
                      ↓
               Business Insights
```

---

# 📁 Repository Structure

```text
SCT_DS_TASKS/
│
├── Task-1/
│   ├── SCT_DS_TASK_1.ipynb
│   └── world_population.csv
│
├── Task-2/
│   ├── SCT_DS_TASK_2.ipynb
│   └── Titanic-Dataset.csv
│
├── Task-3/
│   ├── SCT_DS_TASKS_3.ipynb
│   └── bank-full.csv
│
├── Task-4/
│   ├── SCT_DS_TASKS_4.ipynb
│   └── ROAD ACCIDENT DATASET.csv
│
└── README.md
```

---

# 🎯 Internship Outcome

This internship strengthened my foundation in **Data Science and Analytics** by giving me practical experience working with different types of datasets and analytical problems.

The projects allowed me to progress from:

**Data Exploration → EDA → Visualization → Statistical Analysis → Machine Learning**

and develop hands-on experience with the Python data science ecosystem.

---

## 👨‍💻 Author

**Sivasakthi R**

B.Tech — Artificial Intelligence and Data Science

### Interests

* Data Analytics
* Data Science
* Machine Learning
* Artificial Intelligence
* Business Intelligence

---

⭐ **If you find this repository useful, feel free to explore the individual notebooks and projects.**

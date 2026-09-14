# SkillCraft Technology – Data Science Internship

This repository contains the projects and tasks completed during my **Data Science Internship at SkillCraft Technology**.

The projects demonstrate practical experience in **Python, data analysis, data visualization, exploratory data analysis (EDA), and machine learning** using real-world datasets.

---

## 👨‍💻 Internship Details

- **Organization:** SkillCraft Technology
- **Role:** Data Science Intern
- **Domain:** Data Science
- **Duration:** 1 Month
- **Tools:** Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Google Colab

---

## 📂 Tasks Completed

### 📊 Task 1 – Data Visualization

**Objective:**  
Create a bar chart or histogram to visualize the distribution of a categorical or continuous variable.

**Work Done:**
- Used the World Bank population dataset.
- Analyzed population data for different countries.
- Created a bar chart showing the **Top 10 Most Populated Countries in 2025**.
- Used Pandas and Matplotlib for data processing and visualization.

**Key Learning:**
- Data loading and preprocessing
- Data filtering
- Sorting and ranking
- Creating bar charts
- Data visualization

**Notebook:** `SCT_DS_Task1.ipynb`

---

### 🚢 Task 2 – Data Cleaning and Exploratory Data Analysis

**Objective:**  
Perform data cleaning and exploratory data analysis to identify relationships, patterns, and trends.

**Dataset:** Titanic Passenger Dataset

**Work Done:**
- Loaded and explored the Titanic dataset.
- Identified missing values.
- Handled missing values in `Age` and `Embarked`.
- Removed the `Cabin` column due to extensive missing data.
- Analyzed survival based on:
  - Gender
  - Passenger class
  - Age
  - Fare
- Created visualizations using Matplotlib and Seaborn.

**Key Insight:**  
Gender and passenger class showed strong relationships with passenger survival, while fare also showed a noticeable relationship.

**Notebook:** `SCT_DS_Task2.ipynb`

---

### 🌳 Task 3 – Decision Tree Classifier

**Objective:**  
Build a machine learning model to predict whether a customer will subscribe to a bank term deposit.

**Dataset:** Bank Marketing Dataset

**Work Done:**
- Performed data preprocessing.
- Encoded categorical variables using one-hot encoding.
- Split the dataset into training and testing sets.
- Built a Decision Tree Classifier.
- Evaluated the model using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix
- Analyzed feature importance.

**Model Performance:**
- Accuracy: **89.84%**
- Precision for Purchase Class: **64%**
- Recall for Purchase Class: **30%**
- F1-score for Purchase Class: **41%**

**Important Features:**
1. `duration`
2. `poutcome_success`
3. `housing_yes`
4. `age`
5. `pdays`

**Notebook:** `SCT_DS_Task3.ipynb`

---

### 🚗 Task 4 – Traffic Accident Analysis

**Objective:**  
Analyze traffic accidents based on time, severity, weather conditions, locations, and road-related factors.

**Dataset:** US Accidents (2016–2023)

**Work Done:**
- Analyzed accident frequency by hour of the day.
- Studied accident severity.
- Analyzed weather conditions during accidents.
- Identified accident hotspots using geographic coordinates.
- Analyzed road-related features such as:
  - Traffic Signals
  - Crossings
  - Junctions
  - Stops
- Created visualizations using Matplotlib.
- Used memory-efficient chunk-based processing for the large dataset.

**Key Findings:**
- The highest number of accidents occurred at **7 AM**.
- **Severity 2** accidents were the most common.
- **Fair** weather was the most frequently recorded weather condition.
- Traffic signals were the most common analyzed road feature associated with accidents.

**Notebook:** `SCT_DS_Task4.ipynb`

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Google Colab**
- **Jupyter Notebook**

---

## 📁 Repository Structure

```text
SkillCraft-Data-Science-Internship/
│
├── SCT_DS_Task1.ipynb
├── SCT_DS_Task2.ipynb
├── SCT_DS_Task3.ipynb
├── SCT_DS_Task4.ipynb
└── README.md

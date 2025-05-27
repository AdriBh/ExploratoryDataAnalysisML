# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

Welcome to the Titanic EDA project! This repository contains a comprehensive exploratory analysis of the famous Titanic dataset, helping uncover patterns and relationships among key features and their impact on survival rates.

## 📁 Dataset

The dataset used in this analysis is the classic [Titanic dataset](https://www.kaggle.com/c/titanic/data) provided by Kaggle. It includes information such as:
- Passenger demographics (age, sex, family size)
- Ticket fare and class
- Embarkation port
- Survival status

---

## 🧠 Objectives

The main goal of this project is to perform exploratory data analysis to understand the dataset better and identify:
- Which features most significantly affect survival
- Relationships and correlations among features
- Insights useful for building predictive models

---

## 📊 Summary of Findings

1. **Gender and Survival** 👩‍🦱👨‍🦰  
   - Women had a **higher survival rate** than men.
   - There is a **negative correlation** between `Sex` and `Survived`.

2. **Passenger Class** 🏰  
   - **1st class** passengers had a **better chance of survival** compared to 2nd and 3rd classes.
   - Socioeconomic status played a significant role.

3. **Fare vs. Pclass** 💰  
   - A **negative correlation** exists between `Fare` and `Pclass`.
   - Higher-class passengers paid more and had better survival chances.

4. **Feature Correlations (via Heatmap)** 🔥  
   - Notable correlations:
     - `SibSp` ↔ `Parch` (Family-based travel)
     - `SibSp` ↔ `Fare` (Group ticketing)
     - `Fare` ↔ `Pclass` (Fare cost by class)
     - `Parch` ↔ `Sex` (Possible demographic patterns)

---

---

## 🛠️ Tools & Libraries

- Python 🐍
- Pandas 🐼
- NumPy 🔢
- Matplotlib 📈
- Seaborn 🖌️
- Jupyter Notebook 📒

---



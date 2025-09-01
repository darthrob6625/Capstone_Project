# 📈 Predicting California Open Enrollment

### 📖 Notebooks
- [Jupyter Notebook 1 of 2 : Data Preparation & Analysis](capstone_1_of_2.ipynb)
- [Jupyter Notebook 2 of 2 : Classification Modeling](capstone_2_of_2.ipynb) 

## 🙋🏻‍♂️ Project Contributor
This project was prepared by  [Robert Meza](https://www.linkedin.com/in/robmeza/) as the Capstone Project for the Machine Learning and Artificial Intelligence Professional Certificate Program at the University of California, Berkeley, March 2025 cohort.

I have been employed by the State of California since May 2009, serving in senior technical and leadership roles. I hold a Bachelor of Science in Computer Science (2008) and a Master of Business Administration (2014) from California State University, Sacramento. From 2009 to 2016, I held a senior technical position with the California Department of Technology. Since July 2016, I have served primarily as a Senior Information Technology Manager at the California Public Employees’ Retirement System (CalPERS).

## 📘 Project Overview

### 🔹Background
CalPERS is the largest pension fund for public sector employees in the United States, managing net assets of approximately $506.6 billion. CalPERS administers retirement benefits to 2.3 million members and beneficiaries and provides health benefits to 1.5 million members and their dependents.

### 🔹Open Enrollment
As part of its annual Open Enrollment period, members may modify their CalPERS health coverage. These modifications include selecting a different health plan, adding or removing dependents, canceling existing coverage, and enrolling in a CalPERS health plan as a new member.

### 🔹Objective 
The objective of this Capstone Project is to develop a high-performance predictive model to determine a CalPERS member’s health plan selection during the Open Enrollment period by leveraging a range of relevant features. Key features under consideration include geographic location, age, number of dependents, etc. Because members are limited to a predefined set of health plans within California, machine learning classification techniques will serve as the initial methodological framework.

### 🔹Data Source
CalPERS has provided data exports with all personal identifiers removed and properly masked. The analysis will use data from 2020 through 2024 to determine the optimal range for model performance. These datasets contain 20–25 features and include more than four million records. Due to the 25 MB file upload limit, some preliminary cleaning and consolidation were performed prior to upload.

### 🔹Data Assumptions
Due to the file upload size restriction, the dataset was reduced to a manageable subset using the following filters and assumptions, derived from the original 4-million-record dataset.
- Each CalPERS member in this dataset is an active employee of the State of California
- Each CalPERS member in this dataset is not retired
- Dataset reduced from 4M to 1M, five years of data from 2020-24, 200K samples per year

## ↗️ Expected Results

Informed by the evaluation of the aforementioned classification models and preliminary feedback from office hours sessions and my assigned advisor, the objective of this project is to produce a predictive model with an accuracy exceeding 75 percent. Initial training and testing of a decision tree model yielded strong results, with optimal performance achieved in configurations containing 10–20 leaves. The ultimate goal is to develop a model capable of achieving accuracy rates approaching 90 percent while incorporating strategies to mitigate overfitting. This model is intended to accurately predict a member’s health plan selection with a high degree of reliability, consistent with the outlined methodology.

##  📋 Project Workflow
1. Data check
2. Exploratory Data Analysis (EDA)
3. Preprocessing
4. Feature Selection
5. Classification Modeling - Logistic Regression, Decision Tree, KNN, and … 
7. Results & Analysis
   
## 📌 Key Findings
- ✅
- ✅
- ✅
- ✅
- ✅
  
## 🎖 Future Work
- Expand the dataset by incorporating an additional 10 years of historical data
- Refine feature selection by removing currently high-performing features in order to evaluate alternative predictors
- Engineer new features that may yield improved model performance
- Address class imbalance by applying techniques to reduce the effects of unbalanced data distributions
- Develop a web application to operationalize and showcase the predictive models

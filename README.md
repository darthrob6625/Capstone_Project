# 📈 Predicting California Open Enrollment

### 📖 Notebooks
- [Jupyter Notebook 1 of 2 : Data Preparation & Analysis](capstone_1_of_2.ipynb)
- [Jupyter Notebook 2 of 2 : Classification Modeling](capstone_2_of_2.ipynb)
- [Jupyter Notebook Bonus : Classification Modeling Without Strong Feature](capstone_bonus.ipynb) 

## 🙋🏻‍♂️ Project Contributor
This project was prepared by  [Robert Meza](https://www.linkedin.com/in/robmeza/) as the Capstone Project for the Machine Learning and Artificial Intelligence Professional Certificate Program at the University of California, Berkeley, March 2025 cohort.

I have been employed by the State of California since May 2009, serving in senior technical and leadership roles. I hold a Bachelor of Science in Computer Science (2008) and a Master of Business Administration (2014) from California State University, Sacramento. From 2009 to 2016, I held a senior technical position with the California Department of Technology. Since July 2016, I have served primarily as a Senior Information Technology Manager at the California Public Employees’ Retirement System (CalPERS).

## 🚨 Disclaimer
The analysis and findings presented in this project are solely my own work and do not represent, reflect, or speak on behalf of CalPERS or any other organization. This project is conducted strictly as an academic exercise for educational purposes. Some of the underlying data used in this analysis may have been modified, reduced, or otherwise transformed for the purposes of research and demonstration.

## 📘 Project Overview

### Background
CalPERS is the largest pension fund for public sector employees in the United States, managing net assets of approximately $500 billion. CalPERS administers retirement benefits to over 2 million members and beneficiaries and provides health benefits to 1.5 million members and their dependents.

### Open Enrollment
As part of its annual Open Enrollment period, members may modify their CalPERS health coverage. These modifications include selecting a different health plan, adding or removing dependents, canceling existing coverage, and enrolling in a CalPERS health plan as a new member.

### Objective 
The objective of this Capstone Project is to develop a high-performance predictive model to determine a CalPERS member’s health plan selection during the Open Enrollment period by leveraging a range of relevant features. Key features under consideration include geographic location, age, number of dependents, etc. Because members are limited to a predefined set of health plans within California, machine learning classification techniques will serve as the initial methodological framework.

### Data Source
CalPERS provided data exports with all personal identifiers removed and properly masked. The analysis draws on data from 2020 through 2024 to identify the optimal range for model performance. These datasets contain between 20 and 25 features and comprise more than four million records. <ins>To address the 25 MB file upload limit, preliminary cleaning and consolidation were performed prior to upload.</ins> The original dataset of approximately 4 million records (2020–2024) was reduced to 1 million records for exploratory data analysis (EDA) and feature selection, and a further stratified sample of 400,000 records was used for data modeling

## ↗️ Expected Results

The ultimate goal is to develop a model capable of achieving accuracy rates approaching 90 percent while incorporating strategies to mitigate overfitting. This model is intended to accurately predict a member’s health plan selection with a high degree of reliability, consistent with the outlined methodology.

##  📋 Project Workflow
1. Data check
2. Exploratory Data Analysis (EDA)
3. Preprocessing
4. Feature Selection
5. Classification Modeling 
7. Results & Analysis
   
## 🧮 Classification Models

| Classification Model | Simple Model Accuracy (Test) | Improvement Model Accuracy | % Diff | 
| --- | --- | --- | --- |
| Logistic Regression | 46.2% | 68.0% | +21.8% | 
| K-Nearest Neighbors | 90.2%  | 71.7% | -18.5% | 
| Decision Trees | 100% | 99.5% | -0.5% |
| Support Vector Machines | 46.2% | 79.3% | +33.1% |

## 📌 Findings
- ✅ For LR, there was a significant improvement of +20% in model performance, resulting in an accuracy of 68%.
- ✅ The KNN model initially achieved a high score due to a strong feature. However, limiting the neighbor number yielded a more realistic accuracy of around 70%. This suggests that the data is most likely unbalanced.
- ✅ The DT model initially achieved a perfect score due to a strong feature. This suggests that the data is most likely unbalanced.
- ✅ For SVM, there was a significant improvement of +30% in model performance, resulting in an accuracy of about 80%.
  
## 🎖 Future Work
- Expand the dataset by incorporating an additional 10 years of historical data
- Refine feature selection by removing currently high-performing features in order to evaluate alternative predictors
- Engineer new features that may yield improved model performance
- Address class imbalance by applying techniques to reduce the effects of unbalanced data distributions
- Develop a web application to operationalize and showcase the predictive models

## 🧮 Bonus - Classification Models with Removal of Strong Feature

| Classification Model | Simple Model Accuracy (Test) | Improvement Model Accuracy | % Diff | 
| --- | --- | --- | --- |
| Logistic Regression | 46.6% | 68.4% | +21.8% | 
| K-Nearest Neighbors | 56.6%  | 67.2% | +10.6% | 
| Decision Trees | 53.8% | 50.7% | -3.1% |
| Support Vector Machines | 46.2% | 68.5% | +22.3% |

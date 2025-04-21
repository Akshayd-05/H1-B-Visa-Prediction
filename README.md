## H1B Visa Sponsorship Prediction

This repository contains the project files for the "H1B Visa Sponsorship Prediction" project. This project utilizes a dataset of over 33,000 job postings from LinkedIn to analyze and predict the likelihood of H1B visa sponsorship, focusing on various factors that influence an employer's decision to sponsor a visa.

Project Overview The project involves a comprehensive analysis using machine learning algorithms including Decision Trees, Random Forests, XGBoost, LightGBM, and Logistic Regression to determine the predictors that most significantly affect visa sponsorship decisions. The aim is to assist job seekers, particularly those needing visa sponsorship, in gauging the likelihood of obtaining sponsorship based on job posting characteristics.

Repository Contents Data Analysis Notebooks: Jupyter notebooks containing the data analysis, model building, and validation processes. Data Files: CSV files used for the analysis, including the main dataset derived from LinkedIn job postings. 

## 🚀 Features

- 📋 Interactive Web App for user input
- 🔍 Predicts H1B Visa sponsorship probability
- 📊 Cleaned and engineered dataset
- ⚙️ Trained LightGBM Classifier Model
- 🌐 Hosted and served using Streamlit

---

## 🛠️ Tech Stack

- **Python 3.9+**
- **Pandas**
- **LightGBM**
- **Scikit-learn**
- **Streamlit**
- **Regex & Requests**

---

## 📈 Model & Approach

- ✅ Preprocessing: Cleaned categorical variables, scaled numerical features.
- 🧠 Model: `LGBMClassifier` was selected due to its performance on tabular data and speed.
- 🔍 Features used:
  - Salary
  - Job Position & Experience Level
  - Work Type (Full Time / Internship)
  - Company Listed or Not
  - Supervisor Role, Domain, Views, etc.
  
- 🎯 Target: Whether a company is likely to **sponsor** an H1B visa (`Yes`/`No`).


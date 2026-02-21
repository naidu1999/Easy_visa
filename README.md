# Easy_visa
# 🌍 EasyVisa – US Visa Approval Prediction Using Machine Learning

## 📖 Project Overview

Business organizations in the United States are experiencing a growing demand for skilled human resources. To meet workforce shortages, US employers often hire foreign workers under immigration programs governed by the **Immigration and Nationality Act (INA)**.

The **Office of Foreign Labor Certification (OFLC)** processes hundreds of thousands of visa applications every year. Due to the increasing volume of applications, manually reviewing each case has become time-consuming and inefficient.

To address this challenge, OFLC partnered with **EasyVisa**, a data-driven solutions firm, to develop a **Machine Learning–based system** that can help predict whether a visa application is likely to be **certified or denied**.

In this project, I worked as a **Data Scientist at EasyVisa**, analyzing historical visa application data and building classification models to assist in faster and more accurate visa decision-making.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Predict whether a visa application will be **certified or denied**
- Identify the key factors that influence visa approval decisions
- Recommend applicant profiles that have higher chances of visa certification
- Reduce manual effort and improve efficiency in the visa approval process

---

## 🗂 Dataset Description

The dataset contains historical visa application records, including information about both **employees and employers**.

Each row in the dataset represents **one visa application** processed by OFLC.

---

## 📘 Data Dictionary

| Feature | Description |
|------|------------|
| case_id | Unique ID of each visa application |
| continent | Continent of the employee |
| education_of_employee | Education level of the employee |
| has_job_experience | Whether the employee has prior job experience |
| requires_job_training | Whether job training is required |
| no_of_employees | Number of employees in the employer’s company |
| yr_of_estab | Year the employer’s company was established |
| region_of_employment | Intended region of employment in the US |
| prevailing_wage | Average wage for similar occupation in the region |
| unit_of_wage | Wage unit (Hourly, Weekly, Monthly, Yearly) |
| full_time_position | Full-time or part-time position |
| case_status | Target variable (Certified / Denied) |

---

## 🛠 Tools & Technologies Used

- **Programming Language:** Python  
- **Environment:** Google Colab / Jupyter Notebook  
- **Libraries Used:**
  - pandas – data manipulation
  - numpy – numerical operations
  - matplotlib & seaborn – data visualization
  - scikit-learn – machine learning models and evaluation

---

## 🔍 Project Workflow & Work Done

The project was completed in a structured and systematic manner.

---

### 1️⃣ Data Understanding & Cleaning

- Loaded and inspected the dataset
- Checked data types and dataset shape
- Identified missing values and inconsistencies
- Verified target variable distribution (Certified vs Denied)

This step ensured data quality before modeling.

---

### 2️⃣ Exploratory Data Analysis (EDA)

EDA was performed to understand patterns and trends in visa approvals.

Key analysis included:
- Distribution of certified vs denied cases
- Impact of education level on visa approval
- Influence of job experience and training requirements
- Effect of prevailing wage and employment type
- Employer-related factors such as company size and establishment year

Various plots such as **bar charts, count plots, box plots, and histograms** were used to support insights.

---

### 3️⃣ Data Preprocessing

- Removed non-predictive columns such as `case_id`
- Encoded categorical variables using appropriate encoding techniques
- Converted wage units into a consistent numerical format
- Split the dataset into training and testing sets

---

### 4️⃣ Model Building

Multiple classification models were developed to predict visa approval status, including:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier  
- (Optional) Gradient-based models (XGBoost avoided due to time complexity)

Each model was trained using the training dataset.

---

### 5️⃣ Model Evaluation

The models were evaluated using:
- Accuracy score
- Confusion matrix
- Precision, Recall, and F1-score

Model performance was compared to select the most effective model for prediction.

---

## 📊 Key Insights from the Analysis

- Visa approval is strongly influenced by **education level** and **job experience**
- Higher **prevailing wages** increase the likelihood of certification
- Full-time job positions have higher approval rates than part-time roles
- Employers with larger organizations and older establishments show better approval outcomes
- Certain regions of employment show higher certification trends

---

## 💡 Business Recommendations

Based on the analysis and model results, the following recommendations are proposed:

- Prioritize applicants with higher education and relevant job experience
- Encourage employers to offer competitive prevailing wages
- Focus on full-time job roles for better approval chances
- Use the prediction model to shortlist high-probability cases for faster processing
- Reduce manual review workload using automated ML-based screening

---

## 📁 Repository Structure
EasyVisa-Visa-Approval-Prediction/
│
├── EasyVisa.ipynb
├── EasyVisa.html
└── README.md
└── Easy_visa.csv


---

## 📌 Conclusion

This project demonstrates how **Machine Learning classification techniques** can be effectively applied to real-world government and immigration challenges. By predicting visa approval outcomes, the solution helps improve decision-making efficiency, reduce processing time, and support data-driven policy execution.

The project covers the complete data science lifecycle—from data exploration to model deployment insights—making it a strong end-to-end ML project.

---

## 👤 Author

**Rahul Naidu**  
B.Tech – Computer Science (2022)  
Aspiring Data Scientist / Business Analyst  

---

⭐ If you found this project useful, feel free to star the repository!

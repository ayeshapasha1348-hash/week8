# Customer Churn Prediction & Retention Strategy Analysis
End-to-end customer churn analysis with EDA, statistical testing, logistic regression modeling, and business retention strategy using Python.

# Week 8 Capstone Project

## Customer Churn Prediction & Retention Strategy Analysis 

---

## Project Overview

This capstone project demonstrates a **complete end-to-end business data analysis workflow** focused on understanding and reducing **customer churn**.
The analysis transforms raw customer data into **statistical insights,predictive modeling,and actionable business recommendations** that support data-driven decision-making.

This project serves as the **final deliverable of a 2-month data analytics internship** and is designed to be **portfolio-ready for academic evaluation,placements,and interviews**.

---

##  Business Problem

Customer churn directly impacts **revenue stability,customer lifetime value,and business growth**.
Organizations must identify **why customers leave** and take **proactive retention actions**.

### Core Question

**What factors drive customer churn,and how can businesses reduce churn using data analysis and predictive modeling?**

---

##  Project Objectives

* Perform **end-to-end data analysis** from raw data to business insights
* Identify **key drivers influencing customer churn**
* Validate churn patterns using **statistical hypothesis testing**
* Build a **predictive churn classification model**
* Provide **actionable retention strategies** and implementation guidance
* Produce **professional documentation,reports,and presentation**

---

##  Dataset Information

### Primary Dataset

**customer_churn.csv**

* **Rows:** 500
* **Key Features:**

  * Tenure
  * MonthlyCharges
  * TotalCharges
  * Contract
  * PaymentMethod
  * PaperlessBilling
  * SeniorCitizen
  * Churn

### Data Quality Checks

* Duplicate records removed
* Missing values verified
* Correct data types ensured

This ensured **reliable statistical and predictive analysis**.

---

##  Tools & Technologies

* **Python**
* **Pandas & NumPy** → Data manipulation
* **Seaborn & Matplotlib** → Visualization
* **SciPy** → Statistical hypothesis testing
* **Scikit-learn** → Logistic regression modeling
* **Jupyter Notebook** → Reproducible analysis

---

##  Analytical Workflow

### 1️ Data Preparation

* Cleaned dataset
* Removed duplicates
* Validated structure and data types

### 2️ Exploratory Data Analysis (EDA)

Created **5+ professional visualizations**:

* Churn distribution
* Tenure vs churn
* Monthly charges vs churn
* Contract type vs churn
* Correlation heatmap

---

### 3️ Statistical Analysis

Performed **hypothesis testing** to verify:

* Whether churned customers pay **significantly different monthly charges**

Result:

* **Statistically significant difference found (p < 0.05)**
* Confirms pricing influence on churn behavior

---

### 4️ Predictive Modeling

Built a **Logistic Regression classification model** using:

* Tenure
* MonthlyCharges
* TotalCharges

Model outputs:

* Accuracy score
* Confusion matrix
* Classification report

This enables **early churn prediction and proactive retention**.

---

##  Key Insights

* **High monthly charges → higher churn probability**
* **Low tenure customers → highest churn risk**
* **Month-to-month contracts → weakest retention**
* Statistical testing confirms **pricing impact is significant**
* Predictive model enables **data-driven churn prevention**

---

##  Business Recommendations

### Retention Strategy

1. Provide **loyalty discounts** for high charge customers
2. Encourage migration to **long term contracts**
3. Target **new customers (first 6 months)** with engagement campaigns
4. Deploy **predictive churn alerts** for proactive intervention

### Expected Business Impact

* Reduced churn rate
* Increased customer lifetime value
* Improved long term revenue stability

---

##  Project Structure

```
week8-capstone-customer-churn/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   ├── 1_data_cleaning.ipynb
│   ├── 2_eda.ipynb
│   └── 3_analysis.ipynb
│
├── reports/
│   ├── executive_summary.pdf
│   └── technical_report.pdf
│
├── presentations/
│   └── business_presentation.pptx
│
├── capstone_analysis.ipynb
├── requirements.txt
└── README.md
```

---

##  Setup Instructions

### Step 1 - Install Python

Download from:
[https://www.python.org/downloads/](https://www.python.org/downloads/)

Enable **“Add Python to PATH.”**

---

### Step 2 - Install Dependencies

```bash
python -m pip install pandas numpy matplotlib seaborn scipy scikit-learn
```

---

### Step 3 - Run the Notebook

```bash
jupyter notebook
```

Open:

```
capstone_analysis.ipynb
```

Run all cells sequentially.

---

##  Testing & Validation

* Missing values check
* Duplicate removal verification
* Statistical test validation
* Model performance evaluation

Ensures **accuracy,reproducibility,and reliability**.

---

##  Deliverables Included

* **Executive Summary (1 page)** → Business overview
* **Technical Report (5–10 pages)** → Detailed analysis
* **Presentation Slides (10–15 slides)** → Stakeholder communication
* **Complete Code Repository** → Reproducible workflow

---

##  Learning Outcomes

Through this capstone project,I learned to:

* Perform **real-world end-to-end business analysis**
* Apply **statistics to validate business hypotheses**
* Build **predictive machine learning models**
* Convert **data insights into business strategy**
* Create **professional analytics documentation & portfolio projects**

---


## Author

**Zainab Khan**
Final-Year BCA Student
Aspiring **Data Analyst / Data Scientist**

---

## Acknowledgment

This capstone marks the successful completion of a
**2-month structured data analytics internship journey**,
covering Python, data analysis, visualization,statistics,and real-world business analytics.

---



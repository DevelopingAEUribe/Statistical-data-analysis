# Statistical-data-analysis

# 📊 Megaline Telecom Plan Revenue Analysis

## Overview

This project involves an in-depth analysis for **Megaline**, a telecom provider offering two prepaid plans: **Surf** and **Ultimate**. The goal is to identify which plan generates more revenue by analyzing customer behavior from a dataset of 500 users.

This insight helps Megaline's commercial department optimize marketing spend and adjust advertising efforts.

---

## 📁 Project Files

- `megaline_calls.csv`: Call data per user
- `megaline_internet.csv`: Internet usage per session
- `megaline_messages.csv`: Text message records
- `megaline_plans.csv`: Details of Surf and Ultimate plans
- `megaline_users.csv`: User demographics and plan info

---

## 🎯 Project Goals

- Analyze user behavior and monthly usage
- Calculate monthly revenue per user
- Compare revenue from Surf vs. Ultimate plans
- Determine if users from the NY-NJ area differ in revenue generation
- Provide actionable recommendations based on data insights

---

## 🛠 Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **SciPy** (for hypothesis testing)

---

## 📌 Project Steps

### Step 1: Data Preparation
- Loaded and inspected all datasets
- Converted data types, handled missing values
- Cleaned and merged data for monthly aggregation

### Step 2: Feature Engineering
- Rounded call durations to the nearest minute (per policy)
- Aggregated internet data per month and rounded up to GB
- Calculated monthly usage and revenue by user

### Step 3: Data Analysis
- Analyzed usage statistics by plan
- Visualized distributions for minutes, messages, and data
- Described customer behavior per plan

### Step 4: Hypothesis Testing
Tested two hypotheses:

1. **Plan Revenue Hypothesis**  
   - H₀: There is no difference in average revenue between Surf and Ultimate users  
   - H₁: There is a difference  
   - Method: Two-sample t-test

2. **Region Revenue Hypothesis**  
   - H₀: Revenue from NY-NJ users is equal to users from other regions  
   - H₁: Revenue is different  
   - Method: Two-sample t-test

### Step 5: Conclusion
- Summarized key findings and business insights
- Recommended the more profitable plan
- Identified trends in usage behavior

---

## ✅ Key Insights

- Identified the plan that generates more revenue
- Found user behavior trends that affect plan profitability
- Provided data-driven recommendations for marketing strategy

---

## 📎 How to Use

1. Clone this repository
2. Open the Jupyter Notebook (`.ipynb`) in your local environment
3. Run the notebook cells step-by-step to reproduce the analysis

---

## 📬 Contact

For questions or feedback, feel free to reach out to [Your Name].


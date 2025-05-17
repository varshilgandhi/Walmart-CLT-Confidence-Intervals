# Walmart – Confidence Intervals & Central Limit Theorem (CLT) Analysis

This project investigates whether spending habits differ significantly across customer segments at Walmart. Using inferential statistics such as confidence intervals and the Central Limit Theorem (CLT), we analyze purchase behavior across gender, marital status, and age group.

---

## 📊 Problem Statement

Walmart’s management wants to know if men and women, or married and unmarried customers, spend differently on Black Friday. Based on a sample dataset of purchase transactions, we calculate statistical confidence intervals to generalize findings to a population of 50 million customers per segment.

---

## 📁 Dataset Overview

The dataset includes:
- `User_ID`, `Product_ID`
- `Gender`, `Age`, `Occupation`, `City_Category`
- `StayInCurrentCityYears`, `Marital_Status`
- `Purchase` (amount spent)

---

## 🛠️ Tools & Concepts Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scipy Stats
- Confidence Intervals
- Central Limit Theorem
- Hypothesis Framing

---

## 📈 Project Workflow

1. **Exploratory Data Analysis**
   - Checked missing values, outliers, and data types
   - Visualized gender-wise, age-wise, and marital-status-wise spending patterns

2. **CLT & Confidence Intervals**
   - Computed sample means from bootstrap samples
   - Constructed 90%, 95%, and 99% confidence intervals for mean purchase amounts
   - Compared overlaps in confidence intervals

3. **Segmented Analysis**
   - Gender: Male vs Female
   - Marital Status: Married vs Unmarried
   - Age: Binned into 0–17, 18–25, 26–35, 36–50, 51+

4. **Interpretation & Business Insight**
   - Evaluated overlapping intervals to determine significance
   - Modeled implications for targeting strategies

---

## 📌 Key Insights

- Male and female spending habits show **slight but significant** differences.
- Confidence intervals **do not always overlap**, suggesting segmentation opportunities.
- Married individuals tend to spend more than unmarried ones.
- Customers aged **26–35 and 36–50** showed the highest average purchase values.
- CLT provided reliable population-level estimation from samples.

---

## 💡 Business Recommendations

- **Segment campaigns by age and marital status**, not just gender.
- **Personalized promotions** can be crafted for high-spending segments.
- Continue monitoring these trends seasonally using CLT to update strategies.
- Use **non-overlapping confidence intervals** to justify targeted offers.

---

## 📂 Files Included

- `Walmart_CLT_ConfidenceInterval.ipynb` – Jupyter notebook
- `Walmart_data.csv` – Dataset
- `README.md` – Project documentation

---

## 🔗 Links

- [Portfolio Project Page](https://www.datascienceportfol.io/varshilgandhi308)
- [GitHub Repo](https://github.com/varshilgandhi/Walmart-CLT-Confidence-Intervals)

---

## 🤝 Let’s Connect

Feedback or suggestions? Find me on [LinkedIn](https://www.linkedin.com/in/varshil-gandhi-08470b200/)

# Lasso for Marketing ROI

## 📖 Introduction
Companies spend across multiple marketing channels such as TV, radio, social media, and print.  
However, not all channels equally contribute to sales growth. Identifying the most effective ones is critical for maximizing **Return on Investment (ROI)**.  

This project applies **Linear Regression (OLS)** and **Lasso Regression** to a marketing dataset.  
While OLS includes all variables, Lasso performs automatic feature selection by shrinking irrelevant coefficients to zero, helping businesses allocate marketing budgets more efficiently.  

---

## 📌 Project Overview
This project analyzes marketing spend across different channels to determine which ones actually drive sales.  
We compare **Ordinary Least Squares (OLS)** regression with **Lasso Regression** to identify the most important marketing channels.

- **OLS (Linear Regression)** fits all features, even irrelevant ones.
- **Lasso Regression (L1 Regularization)** shrinks some coefficients to **zero**, performing feature selection automatically.  
This makes Lasso especially useful for **ROI analysis**, where not all marketing channels contribute meaningfully to sales.

---

## 📊 Dataset
- **Source:** [Google Drive Link](https://drive.google.com/file/d/1QLZcuDnzzrXUwLnsekWdWWnosyNWx-Dv/view?usp=sharing)  
- **Features:**
  - `TV_spend`
  - `radio_spend`
  - `social_media_spend`
  - `newspaper_spend`
  - `billboard_spend`
  - `influencer_spend`
  - `email_spend`
- **Target:**
  - `sales_k` (sales in thousands)

---

## ✅ Results & Insights

- **OLS** includes all features, even weak contributors, which makes interpretation less clear.  
- **Lasso** automatically sets coefficients of less important channels (e.g., `email_spend`, `newspaper_spend`) to **zero**, improving clarity.  
- This means marketing teams can quickly identify and focus on **high-ROI channels** such as TV, radio, and social media.  

---

## 🎯 Conclusion

Lasso regression improves interpretability by performing built-in feature selection.  
While OLS fits all features regardless of their importance, Lasso highlights the **true sales drivers**, helping businesses allocate budgets more effectively.  
This makes Lasso a more practical choice for **ROI-focused marketing analysis**, as it filters out noise and emphasizes actionable insights.# Polynomial-Ridge-Lasso-Regression-Task

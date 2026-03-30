# Marketing Campaign Analysis: Facebook vs AdWords

## 1. Problem Statement

The goal of this project is to analyze and compare the performance of two digital marketing platforms — **Facebook and AdWords** — to determine:

- Which platform drives better conversions  
- Whether the difference in performance is statistically significant  
- What factors influence conversions  
- How future performance can be predicted  

---

## 2. Data Overview

The dataset contains campaign-level metrics for both platforms, including:

- Ad Views  
- Clicks  
- Conversions  
- Cost  
- Click Through Rate (CTR)  
- Conversion Rate  
- Cost Per Click (CPC)  

The data enables both **comparative analysis** and **predictive modeling**.

Link to raw dataset is [THIS](dataset/marketing_campaign.csv)  
Link to cleaned datatset is [THIS](dataset/cleaned_data.csv)  

---

## 3. Tools Used

- **Python**  
- **Pandas** → Data manipulation  
- **NumPy** → Numerical operations  
- **Matplotlib / Seaborn** → Visualization  
- **SciPy** → Statistical testing (T-test)  
- **Scikit-learn** → Regression modeling  

---

## 4. Python Scripts

Each Python script has detailed documentation in markdown, including observations and conclusions.

- [**1_data_cleaning.ipynb**](python_scripts/1_data_cleaning.ipynb)  
  - Handles preprocessing, formatting, and preparation of raw campaign data  

- [**2_AB_testing.ipynb**](python_scripts/2_AB_testing.ipynb)  
  - Performs statistical testing (T-test) to compare Facebook vs AdWords conversions  

- [**3_regression_analysis.ipynb**](python_scripts/3_regression_analysis.ipynb)  
  - Builds a regression model to analyze the relationship between clicks and conversions  

- [**4_time_series_analysis.ipynb**](python_scripts/4_time_series_analysis.ipynb)  
  - Examines trends and patterns in campaign performance over time  

---

## 5. Findings and Insights

- **Facebook significantly outperforms AdWords**:
  - Mean conversions: **11.74 (Facebook) vs 5.98 (AdWords)**  
  - ~**96% higher conversions** on Facebook  

- **Statistical significance confirmed**:
  - p-value ≈ **9.35 × 10⁻¹³⁴**  
  - Strong evidence that performance difference is not due to chance  

- **Clicks strongly influence conversions**:
  - R² Score: **76.35%**  
  - Indicates that ~**76% of conversion variability is explained by clicks**  

- **Prediction capability established**:
  - 50 clicks → ~13 conversions  
  - 100 clicks → ~19 conversions  

- **Model accuracy is reliable**:
  - Mean Squared Error: **2.02** (low prediction error)  

- **Key business insight**:
  - Higher impressions (AdWords) do not guarantee better outcomes  
  - **Conversion efficiency is higher on Facebook**

---

## Conclusion

This project demonstrates how **data analysis and statistical testing** can be used to:

- Identify high-performing marketing channels  
- Validate decisions using statistical evidence  
- Build predictive insights for campaign optimization

For detailed documentation: [Link to Report](documentation/Marketing_Campaign_Analysis_Report.pdf)

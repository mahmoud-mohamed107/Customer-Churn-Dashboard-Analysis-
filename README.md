# Customer Churn Dashboard Analysis

## Project Overview

This dashboard provides a comprehensive view of customer churn performance and behavioral insights to support data-driven decision-making in retention strategies.  
It consolidates key KPIs and visual analytics that explain why customers leave, which groups are most at risk, and how satisfaction and engagement levels influence churn.

The analysis focuses on:
- Measuring overall churn performance.  
- Understanding churn variation across customer segments.  
- Assessing the impact of satisfaction, tenure, and payment methods on churn.  
- Identifying actionable insights to enhance customer loyalty.  

---

## Objective

The main objective of this project is to help the business reduce churn and improve customer lifetime value by:  
- Identifying the customer segments most likely to churn.  
- Evaluating the influence of satisfaction and complaints on retention.  
- Understanding how transactional behavior, such as coupon use, correlates with churn.  
- Supporting management with clear visual insights to guide retention strategies.  

---

## Dashboard Design and Methodology

### 1. Data Preparation
- Cleaned and validated customer-level data to ensure consistent IDs, city tiers, and payment modes.  
- Derived key metrics such as Churn Rate, Average Tenure, and Complaint Rate.  
- Merged behavioral (coupons, payments) and experiential (satisfaction, complaints) data into one analytical layer.  

### 2. Dashboard Structure
The dashboard was designed for executive storytelling — starting from general KPIs and moving toward deeper diagnostic visuals.

- **Top KPI Cards:** Summarize overall performance, including Total Customers, Churn Rate, Average Satisfaction, Average Tenure, and Complaint Rate.  
- **Middle Section (Comparative Analysis):** Analyzes churn across customer segments such as city tiers, payment methods, and tenure.  
- **Bottom Section (Behavioral Patterns):** Examines coupon usage and satisfaction interactions that drive churn behavior.  

---

## Tools and Technologies
- Power BI for visualization and dashboard design.  
- Excel and SQL for data cleaning and transformation.  
- DAX for calculated measures and KPI logic.  

---

## Dashboard Insights

### 1. Overall Performance
- **Total Customers:** 5,630  
- **Churn Rate:** 16.8% — a moderate but concerning level.  
- **Average Satisfaction:** 3.0 — neutral, showing potential disengagement.  
- **Average Tenure:** 9 months — indicates short-term customer relationships.  
- **Complaint Rate:** 28.5% — relatively high, aligning with churn patterns.  

**Insight:**  
The churn pattern suggests early-stage disengagement likely caused by poor service experience and unmet expectations.

---

### 2. Churn by City Tier
- **Tier 3 cities** show the highest churn proportion.  
- **Tier 1 customers** are relatively more loyal and stable.  

**Interpretation:**  
This difference highlights a potential service quality or accessibility gap in smaller cities that may require targeted support or local engagement strategies.

---

### 3. Churn by Payment Method
- **Debit Card users (~45%)** represent the largest churn group.  
- **E-wallet users** show stronger retention, likely due to convenience, ease of use, and digital incentives.  

**Insight:**  
Encouraging digital payment adoption and offering tailored loyalty rewards for debit users could reduce churn rates.

---

### 4. Churn by Tenure
- The **first quarter (Q1)** shows the highest churn (≈42%).  
- After Q1, retention stabilizes above 90%.  

**Interpretation:**  
Early customer experience strongly influences long-term loyalty.  
Focusing on onboarding and first 90-day engagement can significantly reduce churn.

---

### 5. Coupon Usage and Churn
- Customers who used **1–2 coupons** exhibit higher churn than those who used none — suggesting short-term or incentive-only engagement.  
- **Heavy coupon users (3–4)** are fewer but show mixed patterns — they stay longer yet are highly price-sensitive.  

**Insight:**  
A balanced coupon strategy that rewards loyalty rather than one-time discounts may help improve retention quality and customer value.

---

## Hypothesis Development and Analytical Reasoning

At first glance, the churn spike in **Q1** — combined with the timing of promotional campaigns — led to an initial assumption:  
> “Maybe customers are *deal hunters* who joined for discounts and left once the offers ended.”

However, deeper analysis challenged this idea.

When we cross-referenced churn with **complaint rates (28.5%)**, **city-tier differences (Tier 3 being the highest churn)**, and **payment method dissatisfaction (debit card users at 45% churn)**, a different story emerged:  
the churn was **not driven by opportunistic customers**, but by **service and experience gaps**.

### Final Hypothesis
> Customers didn’t leave because they were deal hunters they left because the service didn’t meet their expectations.

The promotional offers accelerated the exposure of these weaknesses:  
new users were attracted through discounts, but their early experience (onboarding, support, or transaction friction) was poor, leading them to churn quickly — especially during the first quarter.

---

## Key Takeaways
- **The root cause of churn is service quality, not discount fatigue.**  
- **Tier 3 customers** face accessibility and support challenges.  
- **Debit card users** experience friction that increases drop-off risk.  
- **The first 90 days** are the critical window for retention success.  

---

## Final Insight
>  Discounts attract customers service retains them.  

The data shows that marketing incentives successfully drove acquisition, but inconsistent service delivery and operational weaknesses caused those same customers to leave.  
By improving **early-stage experience**, **enhancing Tier 3 service infrastructure**, and **promoting seamless digital payments**, the company can significantly reduce churn and strengthen long-term customer loyalty.  

---

## (Recommendations)
1. **Improve the first 90-day experience** through faster delivery, proactive support, and tailored offers.  
2. **Enhance service delivery in Tier 3 cities** by improving local support quality and infrastructure.  
3. **Encourage digital payment adoption** via cashback incentives and loyalty programs.  
4. **Monitor complaint patterns** monthly to track progress on service improvements.  

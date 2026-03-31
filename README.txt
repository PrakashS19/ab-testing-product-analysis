# A/B Testing & Product Experiment Analysis

## 📌 Overview
This project evaluates the impact of a new onboarding experience on user conversion and revenue in a SaaS product.

The goal was to determine whether the variant improves key business metrics and should be rolled out.

---

## ❓ Business Problem
Does the new onboarding flow improve:
- User activation (conversion rate)?
- Revenue per user?

---

## 📊 Dataset
- 10,000 users
- Control vs Variant split
- Features:
  - user_id
  - group (Control / Variant)
  - signup_date
  - activated (0/1)
  - revenue

---

## 🧰 Tools Used
- Python (statsmodels for hypothesis testing)
- SQL (SQLite for aggregation)
- Power BI (dashboard & visualization)

---

## 📈 Key Metrics
- Conversion Rate
- Revenue per User (ARPU)
- Absolute Uplift
- Statistical Significance (p-value)

---

## 🔍 Analysis

### Conversion Rate
- Control: 29.1%
- Variant: 39.7%
- Uplift: +10.6 percentage points

### Revenue Impact
- Variant users generated higher ARPU compared to control

### Statistical Testing
- Proportions Z-Test
- p-value < 0.05 → statistically significant

---

## ✅ Conclusion
The variant onboarding significantly improves both conversion and revenue metrics.

👉 Recommendation: Roll out the variant to all users.

---

## 📊 Dashboard Preview
![Dashboard](screenshots/dashboard1.png)



---

## 🚀 Key Learnings
- Applied A/B testing methodology to product decisions  
- Validated results using statistical testing  
- Built business-focused dashboards for stakeholders  

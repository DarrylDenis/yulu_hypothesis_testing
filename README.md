# yulu_hypothesis_testing
This analysis explores key behavioral and environmental factors influencing ride patterns in the Yulu bike-sharing dataset. 


# 🚲 Yulu Electric Cycle Demand Analysis – Statistical Testing & Inference

## 📌 Project Overview

This project analyzes the demand for **shared electric cycles** in the Indian market, specifically for **Yulu**, a micro-mobility company. The goal is to identify which **factors significantly impact cycle usage** and how well those factors explain variations in demand. The analysis is based on statistical hypothesis testing and bivariate analysis techniques.

---

## 🎯 Objective

* Determine if **season, weather, working day, and other factors** affect the number of cycles rented
* Identify which variables are most significant in predicting total rental demand
* Use **statistical tests** to validate assumptions and draw meaningful business inferences
* Help Yulu make **data-driven operational and marketing decisions**

---

## 📂 Dataset Description

* `datetime`: Timestamp of rental
* `season`: 1 = Spring, 2 = Summer, 3 = Fall, 4 = Winter
* `holiday`: Whether the day is a holiday (1 = Yes, 0 = No)
* `workingday`: 1 = Working day, 0 = Weekend/holiday
* `weather`: Weather conditions on a 1 to 4 scale
* `temp`, `atemp`: Actual and "feels like" temperature (in °C)
* `humidity`: Humidity percentage
* `windspeed`: Wind speed
* `casual`, `registered`: User type counts
* `count`: Total cycle demand (target variable)

---

## 🧰 Tools & Concepts Used

* **Python Libraries**: Pandas, Matplotlib, Seaborn, Scipy, Statsmodels
* **Bivariate Analysis**: Boxplots, bar charts, group comparisons
* **Hypothesis Testing**:

  * **T-test**: To test difference in means (e.g., working day vs. non-working day)
  * **ANOVA**: To test differences in demand across seasons and weather conditions
  * **Chi-square test**: To check dependence between categorical predictors (e.g., weather & season)
* **Assumption Testing** (optional): Shapiro-Wilk test (normality), Levene’s test (equal variance)
* **Significance Testing**: α = 0.05 used throughout to accept/reject null hypotheses

---

## 📊 Key Questions Answered

* Is the **average number of rentals** different on working days compared to weekends/holidays?
* Does **season** significantly influence the number of cycles rented?
* Is the **demand different across various weather conditions**?
* Are **season and weather interdependent** variables?

---

## ✅ Insights & Recommendations

* **Working days showed higher demand** than weekends, suggesting more utility-based commuting.
* **Seasonality** had a clear impact on rentals, with certain seasons showing spikes in usage—valuable for supply planning.
* **Weather conditions** were strongly associated with demand, reinforcing the need for operational flexibility during poor weather.
* Chi-square analysis indicated that **season and weather are interrelated**, which can help in better forecasting demand patterns.

---

## 📌 Business Impact

* Helps Yulu **optimize fleet allocation and pricing** strategies based on expected demand
* Supports **seasonal and weather-aware marketing campaigns**
* Enables **data-backed decision-making** for expansion, partnerships, and operational planning

---

This project demonstrates the use of **statistical methods for real-world business analysis**, showing how data can drive smarter decisions even with basic assumptions and limited features.




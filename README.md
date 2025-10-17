# 🚗 Market Entry Analysis for ABG Motors

## 📘 Project Overview

This project evaluates whether **ABG Motors**, a Japanese automobile manufacturer, should enter the **Indian automotive market**. The analysis leverages **data-driven modeling and predictive analytics** to support a strategic market entry decision.

Using **historical Japanese market data** as the training base, a **logistic regression classification model** was developed to predict car purchase likelihood. The model was then applied to an **Indian customer dataset** to project potential sales and assess market viability.

---

## 🎯 Objectives

1. **Sales Forecast Validation** – Estimate potential car sales in India and compare with ABG Motors’ break-even threshold of **12,000 cars/year**.
2. **Model Development** – Build and validate a **logistic regression model** using Japanese customer data.
3. **Model Transferability** – Test the model on Indian data to check if consumer behavior patterns align across the two markets.
4. **Strategic Recommendation** – Provide evidence-based insights for the company’s market entry decision.

---

## 🧠 Methodology

* **Tools Used:** Python, Microsoft Excel, Tableau
* **Techniques:** Logistic Regression, Exploratory Data Analysis (EDA), Data Visualization, Model Validation
* **Datasets:**

  * **Japanese Dataset:** 40,000 customer records with purchase outcomes
  * **Indian Dataset:** 70,000 potential customer records for projection

---

## 📊 Key Findings

* **Model Accuracy:** 97.98%
* **AUC Score:** 0.74
* **Projected Sales in India:** **35,209 cars**, exceeding the target of 12,000 cars by **~293%**
* **Top Predictors:**

  * Annual income (strongest positive impact)
  * Age of current car (replacement cycle indicator)
  * Customer age (negative correlation with purchase likelihood)
  * Gender (males 26.7% more likely to buy)

---

## 🌏 Insights

* Indian and Japanese markets show **similar demographic and behavioral trends**, validating model transferability.
* Indian market characterized by:

  * Balanced gender representation
  * Strong middle-to-upper income segments
  * Purchase readiness linked to maintenance cycles

---

## ✅ Conclusion

The analysis strongly supports **ABG Motors’ entry into the Indian market**, with projected sales well above the break-even threshold.
The logistic regression model effectively demonstrated cross-market applicability, providing **quantitative backing** for strategic decision-making.

**Final Recommendation:**

> Proceed with market entry through a phased expansion strategy focused on major metropolitan areas, with continuous performance monitoring and model recalibration.

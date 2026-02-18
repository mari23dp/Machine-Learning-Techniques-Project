# Customer Behavior Analysis for Product Strategy  
### Product Analytics Project  
** Developed by: Mariana Diaz, Juan Diego Reyes and Isaac Janica **

---

## Overview

This project applies machine learning techniques to analyze customer purchasing behavior and identify the key drivers that influence conversion outcomes.

Rather than focusing purely on predictive accuracy, the objective was to extract actionable insights that could inform product and growth strategy decisions.

The analysis was conducted using structured transactional and behavioral data.

---

## Business Objective

To support product decision-making by:

- Identifying which user attributes most strongly influence purchase behavior
- Understanding high-impact behavioral patterns
- Providing insights that can inform acquisition, retention, and monetization strategies

---

## Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## Analytical Approach

### 1. Data Preparation

- Feature engineering
- Dataset structuring for classification
- Train-test split for model validation

### 2. Predictive Modeling

A tree-based classification model was trained to predict purchase behavior using behavioral, transactional, and demographic features.

### 3. Model Performance

- **Training Accuracy:** 93.89%
- **Test Accuracy:** 93.85%

The small gap between training and testing accuracy indicates strong generalization and model stability.

---

## Key Product Insights

### 🔎 Top Predictive Drivers

| Feature | Importance |
|----------|------------|
| ingresos_anuales | 0.2466 |
| frecuencia_compras_mensual | 0.1609 |
| productos_adquiridos_accesorios | 0.1443 |
| fuente_trafico_redes sociales | 0.1399 |
| valor_total_gastado | 0.1380 |
| fuente_trafico_email | 0.1164 |

### 📌 Insights for Product & Growth

- **Income level and purchase frequency** are the strongest predictors of purchasing behavior.
- **Traffic source (social media and email)** plays a critical role in conversion.
- **Historical total spend** is a strong indicator of future purchasing likelihood.
- Some demographic variables (age, device type) showed minimal predictive power, suggesting behavioral data is more impactful than static attributes.

---

## Strategic Implications

From a Product Analytics perspective:

- Marketing efforts could prioritize high-frequency buyers with higher income levels.
- Social and email acquisition channels show strong conversion influence.
- Segmentation strategies should focus more on behavioral metrics than demographic features.
- Product personalization efforts can leverage purchase frequency and past spend.

---

## Project Structure


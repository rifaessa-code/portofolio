# Binary Logistic Regression — Determinants of Timeliness of Financial Reporting

This project conducts a **Binary Logistic Regression** analysis to examine how **Profitability (X1)**, **Firm Size (X2)**, and **Leverage (X3)** influence the **Timeliness of Financial Reporting (Y)**.  
The dependent variable (Y) is categorical:  
- **1 = Timely Reporting**  
- **0 = Not Timely Reporting**

The analysis was performed using **SPSS**.

---

## 🔍 Objective
To determine whether profitability, firm size, and leverage significantly affect the likelihood that a company submits its financial report on time.

---

## 📊 Dataset
- **Variables:**
  - **X1:** Profitability  
  - **X2:** Firm Size  
  - **X3:** Leverage  
  - **Y:** Timeliness of Financial Reporting (binary: timely / not timely)

---

## 🛠️ Software Used
- **SPSS** for binary logistic regression modeling and diagnostic tests.

---

## 🧪 Analysis Steps

### 1. Overall Model Fit  
Evaluates whether the independent variables collectively improve the prediction of the dependent variable.  
Common indicators:  
- **–2 Log Likelihood (–2LL)** comparison  
- **Chi-square significance**  
A significant improvement indicates the model fits better than the null model.

---

### 2. Goodness of Fit  
Assesses how well the model matches the observed data.  
Tests used:  
- **Hosmer and Lemeshow Test**  
  - Model is considered **fit** if *p-value > 0.05*.

---

### 3. Coefficient of Determination  
Measured using:  
- **Cox & Snell R²**  
- **Nagelkerke R²**  
These values indicate how much variation in financial reporting timeliness is explained by the predictors.

---

### 4. Regression Coefficient Test  
Examines the effect of each independent variable on the likelihood of timely reporting.  
Includes:  
- **Regression Coefficients (β)**  
- **Wald Test** for significance  
- **Odds Ratio (Exp(B))**  

Interpretation:  
- Exp(B) > 1 indicates **increased likelihood** of timely reporting.  
- Exp(B) < 1 indicates **decreased likelihood**.

---

## 📈 Logistic Regression Model

The model takes the form:

\[
\ln\left(\frac{p}{1-p}\right) = a + b_1X_1 + b_2X_2 + b_3X_3
\]

Where:  
- **p** = probability of timely financial reporting  
- **a** = constant  
- **b₁, b₂, b₃** = logistic regression coefficients  

---

Update this README once your SPSS results are available.


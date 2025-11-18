# Multiple Linear Regression — Sales Promotion & Consumer Motivation on Purchase Decision

This project performs a **Multiple Linear Regression** analysis to examine the influence of **Sales Promotion (X1)** and **Consumer Motivation (X2)** on **Purchase Decision (Y)**.  
The analysis was conducted using **SPSS** with a sample size of **100 respondents**.

---

## 🔍 Objective
To analyze how sales promotion and consumer motivation simultaneously and partially affect customers’ purchase decisions, and to measure how strongly both independent variables explain the dependent variable.

---

## 📊 Dataset
- **Sample size:** 100 respondents  
- **Variables:**
  - **X1:** Sales Promotion  
  - **X2:** Consumer Motivation  
  - **Y:** Purchase Decision  
- All variables were measured using Likert-scale questionnaire items.

---

## 🛠️ Software Used
- **SPSS** for statistical testing and model estimation.

---

## 🧪 Analysis Steps

### 1. Validity Test  
Determines whether each questionnaire item accurately measures its respective construct.  
Items with **r-hitung > r-tabel** are considered **valid**.

### 2. Reliability Test  
Conducted using **Cronbach’s Alpha**.  
A value above **0.70** indicates that items for each variable are **reliable**.

### 3. Normality Test  
Performed using Normal p-p plot.  
Data is considered normal if **the plots follow the linear line**.

### 4. Multicollinearity Test  
Assesses whether the independent variables are highly correlated with each other.  
Criteria:
- **VIF < 10**  
- **Tolerance > 0.10**  
Indicates **no multicollinearity**.

### 5. Heteroscedasticity Test  
Checked using:
- Scatterplot of residuals  

If no clear pattern appears, the data is **homoscedastic**.

---

## 📈 Multiple Linear Regression Model

The estimated regression equation follows:

\[
Y = a + b_1X_1 + b_2X_2
\]

Where:  
- **a** = constant  
- **b₁** = coefficient for Sales Promotion  
- **b₂** = coefficient for Consumer Motivation  

### Statistical Outputs:
- **t-test:**  
  Measures the partial effect of each independent variable on Purchase Decision.

- **F-test:**  
  Evaluates the simultaneous influence of Sales Promotion and Consumer Motivation on Purchase Decision.

- **Coefficient of Determination (R²):**  
  Indicates the proportion of variation in Purchase Decision explained by both independent variables.

---

## 📝 Output Summary  
*(Fill this section after completing the SPSS analysis)*  
- **Coefficients (b₁, b₂): b₁=0,299 and b₂=0,282 **  
- **t-test significance: 0,000 and 0,004**  
- **F-test significance:0,000**  
- **R² value:0,310**  

---

Feel free to update this README with your actual statistical outputs.

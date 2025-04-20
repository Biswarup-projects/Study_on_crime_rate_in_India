---

# 📊 A Study on Crime Rates in India: Socio-Economic & Regional Factors

This repository contains the analysis and code for my BSc Statistics (Honours) dissertation on **crime rate variations in India**, with a focus on socio-economic and regional predictors using multiple regression models.

---

## 🎓 Academic Context

- It is my B.sc Statistics honours dissertation project done under the supervision of Professor Masumi Bose (ISI Kolkata).

---

## 🎯 Research Objectives

1. Analyze socio-economic indicators (GDP, unemployment, inflation) and their influence on crime.
2. Understand regional disparities in crime incidence across Indian states.
3. Identify statistically significant predictors of IPC and SLL crime rates.

---

## 🗂 Dataset Summary

- **Sources**:
  - *Crimes in India 2021*, NCRB
  - *Handbook of Statistics on Indian States 2021-22*, RBI
- **Observations**: 33 Indian states and UTs  
- **Variables**:
  - **Response**:  
    - `Y1`: IPC Crime Rate per lakh  
    - `Y2`: SLL Crime Rate per lakh  
  - **Predictors**:  
    - `X1`: Rural unemployment rate  
    - `X2`: Urban unemployment rate  
    - `X3`: GDP (log)  
    - `X4`: NSDP (log)  
    - `X5`: General inflation (CPI)  
    - `X6`: Food & beverage inflation (CPI)  
    - `X7`, `X8`: Dummy variables based on population tier  

---

## 📈 Statistical Methods

- **Multiple Linear Regression**
- **Regression Diagnostics**:
  - Outlier Detection (Residuals, Cook’s Distance)
  - Multicollinearity (VIFs, Correlation Matrix)
  - Heteroscedasticity Tests (Glejser, Goldfeld–Quandt)
- **Model Refinement**:
  - Refitting after outlier removal
  - Predictor significance testing
- **Goodness-of-Fit**:
  - R², Adjusted R²
  - Partial & Multiple Correlation Coefficients

---

## 📌 Key Findings

- **GDP (X3)** is the only statistically significant predictor for both IPC and SLL crime rates.
- **Adjusted R²** for the best model (Case 1): 0.4042  
- Most predictors showed weak or no significant explanatory power, indicating the complexity of crime determinants in India.

---

## 📁 Project Files

- `Dissertation_Crime_Rate_India.pdf` – Full report  
- `codes/` – Code used for statistical analysis (Minitab & R/Python)  
- `data/` – Cleaned dataset used in analysis  
- `README.md` – This documentation  

---

## 🔗 References

- Goon, Gupta, Dasgupta – *Fundamentals of Statistics* (Vol 1 & 2)  
- NCRB: *Crimes in India 2021*  
- RBI: *Handbook of Statistics on Indian States*  
- Online repositories and research articles (linked in PDF)

---

## 📜 License

This project is for academic, educational, and non-commercial use only.

---

## 🧠 Author
- **Biswarup Majumdar**  
- Data Science Enthusiast | [LinkedIn](https://linkedin.com/in/biswarup-majumdar)

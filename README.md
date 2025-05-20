# 💸 Optimized Budget Allocation using Machine Learning & Power BI

This project demonstrates how Machine Learning (specifically, Genetic Algorithms) can be applied to optimize business budget allocations across multiple categories, reducing overspending while maximizing operational efficiency. Insights were presented via an interactive Power BI dashboard.

---

## 🎯 Project Objectives

- Create a realistic dataset for business budget categories  
- Apply a Genetic Algorithm to optimize budget distribution  
- Visualize real vs. optimized spending using Power BI  
- Deliver actionable insights for stakeholders on resource efficiency  

---

## 📊 Dataset Features

The dataset includes the following fields:

- `Category` – Budget area (e.g., Marketing, R&D, Salaries)  
- `Real_Spending_USD` – Actual historical spend per category  
- `Optimized_Budget_USD` – ML-derived optimal allocation  
- `Sentiment` – Market tone related to each category  

---

## 🧬 Machine Learning Methodology

### Genetic Algorithm (GA) Steps:
- Generate initial population of budget combinations  
- Define a **fitness function** to minimize the gap between actual and optimized spending  
- Apply **selection**, **crossover**, and **mutation** to evolve solutions  
- Use RMSE to evaluate performance (final RMSE: `6942.74`)  

### Tools Used:
- Python (NumPy, Pandas, DEAP, Matplotlib)  
- Jupyter Notebook

---

## 📈 Power BI Dashboard Features

### Page 1: Overview
- **KPI Cards**: Total Budget, Biggest/Smallest Categories  
- **Pie Chart**: Optimized Budget Distribution  
- **Clustered Bar Chart**: Real vs Optimized per category  

### Page 2: Interactivity
- Category filters and drill-downs  
- Visual comparison of spending discrepancies  
- Insights into savings opportunities  

---

## 📌 Key Achievements

- Built a GA-based model for real-world budget optimization  
- Delivered visual storytelling via Power BI  
- Reduced manual guesswork in budget planning  
- Enhanced transparency and decision-making

---




# Factor Analysis Project (USL Case Study)

This project performs **Factor Analysis** to identify latent variables (underlying factors) that explain correlations among observed variables.  
The analysis helps reduce dimensionality, uncover hidden structures in data, and support data-driven decision-making.

---

## 📌 Project Overview

Factor Analysis is a multivariate statistical technique used to:
- Reduce a large set of variables into smaller, interpretable factors
- Identify underlying constructs influencing observed data
- Improve interpretability and downstream modeling

In this project, exploratory factor analysis (EFA) is applied to a structured dataset to extract meaningful factors and interpret them from a business/statistical perspective.

---

## 🎯 Objectives

- Examine correlations among variables
- Test data suitability using KMO and Bartlett’s Test
- Extract latent factors using factor analysis
- Interpret factor loadings and communalities
- Reduce dimensionality while retaining maximum information

---

## 🗂️ Files in the Repository

- `USL_Factor_Analysis.ipynb` → Main Jupyter Notebook with full analysis  
- `Factor_analysis_dataset.csv` → Dataset used for factor analysis  
- `README.md` → Project documentation  
- `requirements.txt` → Python dependencies  

---

## 🔧 Methodology

1. **Data Preparation**
   - Import and inspect dataset
   - Handle missing values (if any)
   - Standardize variables

2. **Suitability Testing**
   - Kaiser-Meyer-Olkin (KMO) test
   - Bartlett’s Test of Sphericity

3. **Factor Extraction**
   - Eigenvalue analysis
   - Scree plot interpretation
   - Selection of optimal number of factors

4. **Factor Rotation**
   - Varimax rotation for better interpretability

5. **Interpretation**
   - Factor loadings
   - Communalities
   - Naming and interpreting extracted factors

---

## 📊 Key Outcomes

- Reduced multiple correlated variables into a smaller number of factors
- Identified key dimensions driving variation in the dataset
- Improved interpretability of complex variable relationships

---

## 🛠️ Tools & Technologies

- Python
- Pandas & NumPy
- Scikit-learn
- FactorAnalyzer
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🚀 How to Run the Project

1. Clone this repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the notebook:
   ```bash
   jupyter notebook USL_Factor_Analysis.ipynb
   ```

---

## 👤 Author

**Pragya Gupta**  
MBA | Data Analytics | Business Intelligence

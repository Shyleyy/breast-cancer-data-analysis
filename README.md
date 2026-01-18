<img src="../images/Breast_Cancer_data_Exploration.png" alt="Breast Cancer Data Exploration Banner">
# Breast Cancer Data Analysis 

## Project Overview
This project focuses on analyzing breast cancer data to uncover insights related to tumor characteristics, patient survival, and other factors affecting prognosis. Through, many different visualizations and statistical approaches, the analysis is to help in understanding patterns and trends of breast cancer progression.

---

## Key Objectives 
- Analyze the relationship between tumor size and survival months.
- Visualize data distributions by age groups, tumor sizes, and survival patterns.
- Identify trends in patient status (Alive vs Deceased) across various factors like age and tumor size.
- Summerize findings and observations to assist in understanding patterns in breast cancer progression.

---

## Tools & Technologies
**Programming Language:** Python
**Libraries:**
- Pandas (Data manipulation)
- Matplotlib and Seaborn (Data visualization)
- NumPy (Numerical operations)
**Environment:** Jupyer Notebook for development and visualization.


---
## Data Insights
### **1. Age Group Analysis**
- Bar chart highlights the largest patient age group being the 50s, while the 30s are the smallest

### **2. Tumor Size Distribution** 
- Histogram shows patient distribution by tumor sizes.
- Scatterplot shows larger tumors correlate with shorter survival durations.

### **3. Survival Trends**
- Scatterplot revealed survival months for patients grouped by status (Alive vs Deceased).
- Patients with smaller tumors often hafe longer survival durations.


---
## Project Stucture
```
├── data/
│   └── breast_cancer_data.csv    # Dataset used for analysis.
├── notebook/
│   └── breast-cancer-notebook.ipynb            # Jupyter Notebook with analysis and visualizations.
├── plots/
│   └── graphs/                   # Generated plots and graphs.
├── README.md                     # Project overview and details.
```

---

## key Files
- **`data/breast_cancer_data.csv`:** Contains raw data for analysis, including tumor sizes, survival months, patient status, and age groups.
- **`notebook/breast-cancer-notebook.ipynb`:** Python notebook performing the data analysis and generating visualizations.
---

## Outputs
- **Visualizations:** Includes histogram, scatterplot, and bar chart highlighting relationships between tumor size, patient status, and survival months.
- **Key Findings:** Summarized insights on survival durations, tumor sizes, and age group patterns.

---
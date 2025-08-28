# AICTE-Energy_Efficiency_Project
Supervised  Machine Learning Project on predicting building energy efficiency(AICTE Training).

# Energy Efficiency Prediction (Week 1: Up to Data Splitting)
**Domain:** Sustainable Energy & Efficiency  
**Author:** Varshitha 
**AICTE Student Id:** STU6854504c8e28b1750356044
**AICTE Internship Id:** INTERNSHIP_17513641056863b20937d78

**Week 1 Deliverable:** Supervised ML project up to **Data Splitting**  

---

## Project Overview
This project aims to predict **Heating Load (Y1)** of residential buildings using **8 design features**.  
Accurate predictions help architects and engineers design **energy-efficient buildings**, reduce wastage, and plan HVAC systems efficiently.  

**Supervised Machine Learning Task:** Regression (predict continuous values of energy load).  

**Sustainability Impact:**
- Lower energy demand → less electricity/fuel usage → reduced CO₂ emissions.
- Early-stage design guidance for efficient building design.

---

## Dataset
**Source:** UCI Machine Learning Repository – Energy Efficiency Dataset (ID: 242)  
- [Dataset Link](https://archive.ics.uci.edu/dataset/242/energy+efficiency)  
- **Instances:** 768  
- **Features:** 8 input variables  
- **Targets:** Y1 (Heating Load), Y2 (Cooling Load)  
- **File:** `ENB2012_data.xlsx`  
- **License:** CC BY 4.0  

**Feature Description:**
| Feature | Description |
|---------|-------------|
| Relative_Compactness | Overall compactness of the building shape |
| Surface_Area | Outer surface area of the building |
| Wall_Area | Total area of walls |
| Roof_Area | Roof area |
| Overall_Height | Height of the building |
| Orientation | Encoded integer for building orientation |
| Glazing_Area | Fraction of area that is glazed (windows) |
| Glazing_Distribution | Encoded distribution of glazing over building sides |

**Targets:**
- **Heating_Load (Y1)** – Heat energy required  
- **Cooling_Load (Y2)** – Cooling energy required  

---

## Week 1 Workflow (Completed)
1. **Define the Problem** – Predict Heating Load (Y1).  
2. **Data Collection & Understanding** – Download dataset from UCI, inspect shape, columns, summary stats.  
3. **Data Preprocessing** – Renamed columns, checked for nulls/duplicates, confirmed data types.  
4. **Data Splitting** – Divided into **80% train** and **20% test** sets.

**Tools Used:**
- Python (Pandas, NumPy, Matplotlib)  
- Jupyter Notebook  

---

## How to Run
1. Download `ENB2012_data.xlsx` from the [UCI dataset page](https://archive.ics.uci.edu/dataset/242/energy+efficiency)  
2. Open the notebook `Energy_Efficiency_Project.ipynb` in **Jupyter Notebook**  
3. Run all cells from top to bottom to load, preprocess, and split the data.  

---

## Next Steps (Week 2+)
- **Week 2:** Algorithm selection and baseline model training (Linear Regression, Random Forest, etc.)  
- **Week 3:** Model evaluation (RMSE, R²), hyperparameter tuning  
- **Week 4:** Final evaluation on test data, simple deployment (e.g., Streamlit app)  

---

## References
- Tsanas, A. & Xifara, A. (2012). *Energy Efficiency* [Dataset]. UCI Machine Learning Repository. DOI: 10.24432/C51307  
- License: **CC BY 4.0** (credit required)

# Neuroblastoma Survival Analysis - TARGET-NBL Dataset

## Overview
This project performs **Exploratory Data Analysis (EDA)** and **Survival Analysis** on the **TARGET Neuroblastoma** dataset. The focus is on understanding clinical features, molecular markers, and survival outcomes in paediatric neuroblastoma patients.

**Dataset**: Processed TARGET-NBL (Therapeutically Applicable Research to Generate Effective Treatments - Neuroblastoma)

## Dataset Features
- `age_at_diagnosis_days`
- `Overall.Survival.Time.in.Days` / `Event.Free.Survival.Time.in.Days`
- `MYCN_amplification` (key prognostic factor)
- `Ploidy.Value`
- `superenhancer_0ATRX_1MES_2MYCN` (molecular subtype)
- `Histology_favorable_or_not`
- `vital_status_1dead_0alive`
- Tumour composition metrics (`Percent.Tumor`, `Percent.Necrosis`, etc.)

## Key Insights
- MYCN amplification is associated with worse survival.
- Favourable histology and specific superenhancer subtypes show better outcomes.
- Age at diagnosis and ploidy are important clinical variables.
- Clear separation visible in survival curves by risk groups.

## Project Contents
- `neuroblastoma_analysis.ipynb` → Main analysis notebook (Colab)
- `TARGET_NBL_cleaned.csv` → Cleaned dataset
- Kaplan-Meier survival curves
- Correlation analysis and visualisations

## Technologies
- **Python**  
- pandas, numpy  
- matplotlib, seaborn  
- lifelines (Survival Analysis)

## How to Reproduce
1. Clone this repository
2. Open `neuroblastoma_analysis.ipynb` in Google Colab
3. Upload the original or cleaned CSV
4. Run the notebook

## Future Improvements (Planned)
- Cox Proportional Hazards regression
- Machine Learning models for risk prediction (XGBoost, Random Forest)
- Interactive dashboard with Plotly or Streamlit
- Integration with genomic/mutation data

## Author
**Erick**  
Data Analyst | Bioinformatics Enthusiast  

Feel free to reach out or suggest improvements!

---


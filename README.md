# AI-Driven-Heart-Failure-Analysis

# Heart Failure Risk Assessment  
**A Data Science and AI-driven approach to analyze survival and mortality risk factors in heart failure patients.**

## Overview  
This project explores clinical data to identify key predictors of heart failure outcomes. Using data science techniques and machine learning, it provides insights into gender-specific survival patterns, helping inform personalized healthcare interventions.

## Features  
- **Data Wrangling**: Integration and preprocessing of clinical datasets, including gender-specific mortality and survival data.  
- **Exploratory Analysis**: Statistical and visual analyses to uncover trends in heart failure outcomes.  
- **Predictive Modeling**: Machine learning algorithms to assess survival probabilities and key risk factors.  
- **Visual Insights**: Detailed visualizations to compare survival trends by gender and other clinical metrics.

## Dataset  
The analysis uses several datasets:  
- `heart_failure_clinical_records.csv`: Comprehensive dataset of heart failure patients.  
- `survivors.csv`: Patients who survived heart failure.  
- `deaths.csv`: Patients who did not survive.  
- `Male.csv` and `Female.csv`: Gender-specific subsets for survivors and non-survivors.  

### Key Features in Data  
- **Demographics**: Age, gender  
- **Clinical Metrics**: Ejection fraction, serum creatinine, serum sodium  
- **Outcomes**: Survival or mortality status

## Requirements  
- Python 3.8 or higher  
- Required Python libraries (install via `requirements.txt`):  
  ```bash
  pandas  
  numpy  
  matplotlib  
  seaborn  
  scikit-learn  

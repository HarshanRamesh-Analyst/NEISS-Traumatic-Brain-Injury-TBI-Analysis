# NEISS Traumatic Brain Injury (TBI) Analysis
![Alt text](IMAGES/TBI)
## Overview
This project analyzes data from the National Electronic Injury Surveillance System (NEISS) to identify trends and risk factors for Traumatic Brain Injuries (TBIs) among elderly populations. The analysis focuses on head-related injuries and aims to develop actionable insights for reducing TBI incidents through targeted safety measures and predictive modeling.

## Objectives
- Identify patterns in TBI incidents across various demographics and settings.
- Develop predictive models to highlight high-risk scenarios and populations.
- Recommend evidence-based safety measures to reduce the frequency and severity of TBIs.

## Key Results
- Head injuries account for 71% of internal injuries among elderly individuals, with hospitalization rates at 33%.
- Predictive models achieved **64.4% accuracy** in identifying high-risk factors such as multi-injury scenarios and public location incidents.
- Implementing safety measures could potentially reduce TBI cases by 1,200 annually over the next five years.

## Project Components

### Data
- **Source:** National Electronic Injury Surveillance System (NEISS)
- **Key Variables:** Age, body part, diagnosis, injury location, and product association.

### Analysis
1. **Exploratory Data Analysis (EDA):**
   - Investigated trends by age, gender, location, and injury type.
   - Visualized key patterns in TBI occurrences.
2. **Modeling:**
   - Logistic Regression and Random Forest models for risk prediction.
   - Feature importance analysis to identify primary risk factors.
3. **Recommendations:**
   - Proposed interventions based on data insights.
   - Projected a 20% reduction in TBIs with targeted measures.

### Deliverables
- **Reports:** Comprehensive findings and recommendations.
- **Presentations:** Visual summary of the project insights.
- **Code:** Scripts for data processing, analysis, and modeling.

## Repository Structure
The repository is organized as follows:

```plaintext
NEISS_TBI_Analysis/
├── README.md
├── data/
│   ├── DataDictionary_EDA_Matrix.xlsx
│   ├── NEISS_data_cleaned.csv
│   └── raw_data/
│       └── NEISS_original_data.csv
├── analysis/
│   ├── EDA/
│   │   ├── Capstone_EDA.html
│   │   └── Capstone_EDA.ipynb
│   ├── models/
│   │   ├── Logistic_Regression.ipynb
│   │   ├── Random_Forest.ipynb
│   │   └── Model_Comparison.md
│   └── visualizations/
│       ├── age_injury_trends.png
│       ├── location_risk_analysis.png
│       └── gender_risk_insights.png
├── presentations/
│   ├── NEISS_Presentation.pdf
│   └── NEISS_Presentation.pptx
├── reports/
│   ├── Capstone_Final_Report.pdf
│   ├── Capstone_Final_Report.html
│   └── Executive_Summary.md
└── scripts/
    ├── data_cleaning.py
    ├── feature_engineering.py
    ├── model_training.py
    └── visualization.py


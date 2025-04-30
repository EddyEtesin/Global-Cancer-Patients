# Global Cancer Patients Analysis (2015-2024)

## Overview
This project analyzes a dataset containing information about global cancer patients from 2015 to 2024. The dataset includes various attributes such as patient demographics, cancer types, stages, treatment costs, and factors like genetic risk, air pollution, alcohol use, smoking, and obesity levels. The goal is to explore trends, correlations, and insights that can help understand the impact of different factors on cancer severity and treatment.

## Dataset Description
The dataset contains 50,000 records with the following columns:
- `Patient_ID`: Unique identifier for each patient.
- `Age`: Age of the patient.
- `Gender`: Gender of the patient (Male/Female).
- `Country_Region`: Country or region of the patient.
- `Year`: Year of diagnosis.
- `Genetic_Risk`: Genetic risk score.
- `Air_Pollution`: Air pollution exposure level.
- `Alcohol_Use`: Alcohol consumption level.
- `Smoking`: Smoking habit level.
- `Obesity_Level`: Obesity level.
- `Cancer_Type`: Type of cancer (e.g., Lung, Leukemia, Breast, Colon, Skin, etc.).
- `Cancer_Stage`: Stage of cancer (Stage 0 to Stage IV).
- `Treatment_Cost_USD`: Cost of treatment in USD.
- `Survival_Years`: Estimated survival years.
- `Target_Severity_Score`: Severity score of the cancer.

## Key Questions Explored
1. **Which cancer types are most common globally and by country?**
   - Analyzed the distribution of cancer types globally and across different countries.

2. **What is the average treatment cost by cancer type or stage?**
   - Calculated the average treatment cost for each cancer type and stage.

3. **How does genetic risk correlate with cancer severity or survival years?**
   - Examined the correlation between genetic risk, severity score, and survival years.

4. **Is there a relationship between air pollution levels and certain cancer types?**
   - Visualized air pollution levels across different cancer types to identify potential patterns.

5. **Do smoking, alcohol use, or obesity levels significantly influence cancer stage at diagnosis?**
   - Investigated correlations between lifestyle factors (smoking, alcohol use, obesity) and cancer stage.

6. **Which countries have the highest average severity scores?**
   - Identified countries with the highest average severity scores.

7. **How has the number of cancer cases changed from 2015 to 2024?**
   - Plotted the trend of cancer cases over the years.

## Key Findings
- **Common Cancer Types**: The most common cancer types globally include Lung, Leukemia, Breast, Colon, and Skin cancers.
- **Treatment Costs**: The average treatment cost varies significantly by cancer type and stage, with some stages requiring more expensive treatments.
- **Genetic Risk**: Genetic risk shows a moderate correlation with the severity score but a weak correlation with survival years.
- **Air Pollution**: Certain cancer types, such as Lung cancer, show higher air pollution exposure levels.
- **Lifestyle Factors**: Smoking, alcohol use, and obesity levels do not show strong correlations with cancer stage at diagnosis.
- **Severity by Country**: The USA has the highest average severity score among the countries in the dataset.
- **Trend Over Years**: The number of cancer cases has shown fluctuations over the years, with some years experiencing higher incidences.

## Visualizations
- **Boxplot**: Air pollution levels by cancer type.
- **Line Chart**: Yearly cancer cases from 2015 to 2024.

## Tools and Libraries Used
- **Python**: Primary programming language for analysis.
- **Pandas**: Data manipulation and analysis.
- **Seaborn/Matplotlib**: Data visualization.
- **Scipy**: Statistical analysis.

## How to Use This Project
1. **Clone the Repository**: 
   ```bash
   git clone [repository_url]
   cd global_cancer_patients_analysis
   ```
2. **Install Dependencies**:
   ```bash
   pip install pandas seaborn matplotlib scipy
   ```
3. **Run the Notebook**:
   Open the Jupyter notebook `global_cancer_patients_2015_2024.ipynb` and execute the cells to reproduce the analysis.

## Future Work
- Explore more detailed correlations between environmental factors and cancer types.
- Incorporate additional datasets for broader insights.
- Develop predictive models to estimate treatment costs or survival years based on patient attributes.

## Author
[Ediomo Etesin, ediomoetesin40@gmail.com]

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Feel free to contribute or provide feedback to improve this analysis!

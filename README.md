# Osteoporosis Risk Analysis & Data Validation Study
## By Ofolebe Cyndi

![image alt](https://github.com/Cyndi-24/Osteoporosis-Risk-Analysis-and-Data-Validation-Power-BI/blob/main/osteoporosis%20project/images/osteoporosis%20image.png)

# Project Overview 

Healthcare dashboards are only valuable when the data behind them can be trusted. This project uses Power BI to analyse a synthetic osteoporosis dataset while checking whether the records are realistic, consistent, and suitable for meaningful interpretation.

During the analysis, several concerns were identified, including male records marked as postmenopausal and patterns that appeared unusually balanced across different groups. These issues were clearly documented so the dashboard findings would not be mistaken for real-world clinical evidence.

The project demonstrates data cleaning, validation, analysis, dashboard development, and responsible communication of data limitations.
# Objectives
The project aimed to:
* Build an interactive healthcare dashboard using Power BI.
* Analyse osteoporosis prevalence and associated risk factors.
* Validate the quality of the dataset before generating insights.
* Identify biological inconsistencies and potential modelling issues.
* Demonstrate transparent reporting by documenting data limitations.
  
# Tools Used
* Microsoft Power BI 
* Power Query
* DAX
* Microsoft Excel
* Data Validation Techniques
  
# Skills Demonstrated
* Healthcare Data Analytics and Interpretation
* Power BI Dashboard Development
* Power Query
* DAX Measures
* KPI Design
* Data Cleaning
![image alt](https://github.com/Cyndi-24/Osteoporosis-Risk-Analysis-and-Data-Validation-Power-BI/blob/main/osteoporosis%20project/images/datac_leaning.png)
  
* Data Validation
* Exploratory Data Analysis


# Dashboard Features
## Executive Dashboard - Showing Patient DemographicS

![image alt](https://github.com/Cyndi-24/Osteoporosis-Risk-Analysis-and-Data-Validation-Power-BI/blob/main/osteoporosis%20project/images/Demo_Analysis.png)

 Analytical Questions
1. What is the overall burden of osteoporosis in the study population?
   
Finding:The dataset contained 1,958 participants with an overall osteoporosis prevalence of 50%.
Interpretation:The prevalence appeared unusually balanced, prompting further investigation into the dataset's structure.

2. Which demographic groups appear to have the highest osteoporosis burden?
   
Finding: Older adults showed higher osteoporosis prevalence, while racial and gender distributions appeared almost perfectly balanced.
Interpretation: Although the age trend aligns with clinical expectations, the demographic balance suggested the dataset might be synthetic.

3. How are patients distributed across risk categories?
   
Finding: The population was almost evenly divided between the two categories.
Business Value Risk stratification helps healthcare professionals prioritise preventive interventions and resource allocation.

## Data Validation Dashboard 
### Developed specifically for quality assessment shifts the focus from "What does the data show?" to "Can the data be trusted?"

![image alt](https://github.com/Cyndi-24/Osteoporosis-Risk-Analysis-and-Data-Validation-Power-BI/blob/main/osteoporosis%20project/images/risk_analysis.png)

Analytical Questions
1. Are the clinical variables biologically consistent?

Finding:Records were identified where male patients were labelled as postmenopausal.

Interpretation:This indicates data entry errors or synthetic noise generation which could lead to faulty clinical conclusions ,thus makking data validation necessary prior to analysis

2. Are risk factors distributed realistically across age groups?

Finding:Every risk factor showed identical distributions across age groups.
Interpretation:Real-world healthcare data rarely exhibits such uniformity, indicating synthetic generation or oversampling.

3. Does corticosteroid use appear to influence osteoporosis prevalence?

Finding: Patients using corticosteroids showed a slightly higher prevalence of osteoporosis. 

Interpretation:This aligns with established clinical evidence, although conclusions should be interpreted cautiously because the dataset is synthetic.

4. Is the dataset suitable for predictive modelling?

Finding: The dataset was clean and suitable for practicing machine learning workflows, but not representative of real-world clinical populations.

# Clinical Findings

* Osteoporosis prevalence increases significantly among older age groups.
* Patients using corticosteroids showed slightly higher osteoporosis prevalence.
* Family history and lifestyle factors remain important contributors to osteoporosis risk.
  
# Data Quality Findings/Dataset Limitations

During validation, several issues were identified.
* Biological inconsistencies
Examples included impossible combinations such as male patients labelled as postmenopausal.
* Artificial class balance
Several demographic variables showed almost perfectly balanced distributions, suggesting synthetic data generation rather than naturally occurring clinical populations.
* Uniform risk factor intensity
Risk factors displayed identical distributions across age groups, reducing clinical realism.
These findings demonstrate why validating data quality is essential before communicating analytical results.

# Recommendation
* The dataset is appropriate for demonstrating analytical techniques, dashboard development, and modelling workflows but it should not be used to draw epidemiological or clinical conclusions.
* For future synthetic dataset, automated validation scripts should run prior dashboard development to flag biological anomalies early.

# Conclusion
This study demonstrates that the visual dashboard development must always be built on a foundation of rigorous data auditing. While the synthetic osteoporosis dataset successfully serves its purpose as a functional prototype for Power BI visualization, the discovery of logic errors such as "postmenopausal males" highlights the necessity of automated quality checks within the data pipeline.

Utilizing synthetic dataset for dashboard prototyping is a crucial industry standard for maintaining HIPPA compliance and accelerating BI development, the  generation scripts must accurately model linear relationship between features to ensure that prototype visuals structure reflect realistic healthcare patterns prior to deployment 

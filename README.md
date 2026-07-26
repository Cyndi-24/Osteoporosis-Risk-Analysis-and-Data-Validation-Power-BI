# Osteoporosis-Risk-Analysis-Data-Validation-using-Power-BI
By Ofolebe Cyndi
Project Overview 
This project demonstrates an end-to-end healthcare analytics workflow using Power BI, with a strong emphasis on data quality assessment, validation, and responsible interpretation of synthetic healthcare data.
Rather than simply building dashboards, this project investigates the reliability of the dataset before drawing analytical conclusions. During the analysis, multiple biological inconsistencies and structural issues were identified, documented, and incorporated into the final interpretation.
This project showcases both technical Power BI skills and analytical thinking expected in healthcare and business intelligence roles.
🎯 Objectives
The project aimed to:
Build an interactive healthcare dashboard using Power BI.
Analyse osteoporosis prevalence and associated risk factors.
Validate the quality of the dataset before generating insights.
Identify biological inconsistencies and potential modelling issues.
Demonstrate transparent reporting by documenting data limitations.
ns.
🛠 Tools Used
Power BI Desktop
Power Query
DAX
Microsoft Excel
Data Validation Techniques
Skills Demonstrated
Healthcare Data Analytics
Power BI Dashboard Development
Power Query
DAX Measures
KPI Design
Data Cleaning
Data Validation
Exploratory Data Analysis
Business Intelligence Reporting
Healthcare Data Interpretation
📊 Dashboard Features
Executive Dashboard - Showing Patient Demographics 
Data Validation Dashboard
A second dashboard was developed specifically for quality assessment.
Executive Dashboard: Business Questions
1. What is the overall burden of osteoporosis in the study population?
Approach
Calculated the total number of participants.
Computed the overall prevalence rate.
Created KPI cards to provide a quick summary of the population.
Finding
The dataset contained 1,958 participants with an overall osteoporosis prevalence of 50%.
Interpretation The prevalence appeared unusually balanced, prompting further investigation into the dataset's structure.
2. Which demographic groups appear to have the highest osteoporosis burden?
Approach
Compared prevalence across age groups.
Analysed gender distribution.
Evaluated racial distribution.
Finding Older adults showed higher osteoporosis prevalence, while racial and gender distributions appeared almost perfectly balanced.
Interpretation Although the age trend aligns with clinical expectations, the demographic balance suggested the dataset might be synthetic.
3. How are patients distributed across risk categories?
Approach
Classified patients into High Risk and Low/Moderate Risk groups.
Visualised the distribution using KPI cards.
Finding The population was almost evenly divided between the two categories.
Business Value Risk stratification helps healthcare professionals prioritise preventive interventions and resource allocation.
Data Validation Dashboard: Analytical Questions
This second dashboard shifts the focus from "What does the data show?" to "Can the data be trusted?"
1. Are the clinical variables biologically consistent?
Approach
Reviewed categorical variables for medically impossible combinations.
Cross-checked demographic and clinical attributes.
Finding Records were identified where male patients were labelled as postmenopausal.
Recommendation These records should be corrected or excluded before any clinical modelling or reporting.
2. Are risk factors distributed realistically across age groups?
Approach
Compared the intensity of each risk factor across all age categories using a heat map.
Finding Every risk factor showed identical distributions across age groups.
Interpretation Real-world healthcare data rarely exhibits such uniformity, indicating synthetic generation or oversampling.
3. Does corticosteroid use appear to influence osteoporosis prevalence?
Approach
Compared prevalence between corticosteroid users and non-users.
Finding Patients using corticosteroids showed a slightly higher prevalence of osteoporosis.
Interpretation This aligns with established clinical evidence, although conclusions should be interpreted cautiously because the dataset is synthetic.
4. Is the dataset suitable for predictive modelling?
Approach
Assessed class balance.
Examined missing values.
Reviewed variable consistency.
Finding The dataset was clean and suitable for practising machine learning workflows, but not representative of real-world clinical populations.

Key Insights
Clinical Findings
Osteoporosis prevalence increases significantly among older age groups.
Patients using corticosteroids showed slightly higher osteoporosis prevalence.
Family history and lifestyle factors remain important contributors to osteoporosis risk.
Data Quality Findings
During validation, several issues were identified.
✅ Biological inconsistencies
Examples included impossible combinations such as male patients labelled as postmenopausal.
✅ Artificial class balance
Several demographic variables showed almost perfectly balanced distributions, suggesting synthetic data generation rather than naturally occurring clinical populations.
✅ Uniform risk factor intensity
Risk factors displayed identical distributions across age groups, reducing clinical realism.
These findings demonstrate why validating data quality is essential before communicating analytical results.

Recommendation The dataset is appropriate for demonstrating analytical techniques, dashboard development, and modelling workflows. It should not be used to draw epidemiological or clinical conclusio
⚠ Dataset Limitations
This project uses a synthetic dataset created for analytical practice.
Therefore:
Results should not be interpreted as real-world epidemiological findings.
Some demographic distributions were artificially balanced.
Certain clinical variables contained biologically implausible values.

The project focuses on analytical
methodology rather than clinical inference.
Many Power BI portfolios simply showcase charts. This project demonstrates something more valuable: analytical judgement. By identifying biological inconsistencies, validating the dataset, and transparently documenting its limitations, you show that you understand a core principle of analytics

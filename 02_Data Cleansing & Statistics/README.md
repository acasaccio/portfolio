# Data Cleansing and Statistics Projects

## Overview

Welcome to the Data Cleansing and Statistics section of my portfolio. This repository contains comprehensive projects focusing on statistical analyses in both R and Python, addressing critical issues in healthcare quality measurement and opioid treatment in the United States. Here, I showcase my ability to work with large datasets, combine data across multiple sources, perform data cleansing, and conduct thorough analyses to provide valuable insights and actionable recommendations.

## Contents

### Statistics Final - Quality of Care

This project explores key performance metrics in clinician quality of care within the healthcare industry. The analysis compares internal health system results with national benchmarks, examines internal factors impacting clinician performance, and provides recommendations for quality improvement.

#### Documents:

- **Project Approach and Code:** Detailed document outlining the statistical methods and R coding techniques used in the project.
- **Final Paper:** Comprehensive paper presenting the findings, analyses, and recommendations based on the project.

### Data Cleansing - Opioid Treatment Analysis

This project focuses on Medicare providers and opioid prescribing patterns in the United States. The analysis aims to understand prescribing behaviors and their impact on public health, using various data sources, including APIs and flat files.

#### Documents:

- **Opioid Treatment Proposal:** Detailed proposal outlining the project scope, objectives, and data sources.
- **Opioid Usage and Deaths Approach and Code:** Scripts used for data cleansing, analysis, and visualization.
- **Final Report:** Comprehensive report presenting the findings, analyses, and recommendations based on the project.
- **Output and Graphs:** Visualizations generated during the data exploration phase.

### Project Details

#### Quality of Care Project (R Coding)

##### Introduction

In today's healthcare industry, understanding clinician quality of care key performance metrics is essential for Ambulatory Quality Directors. These metrics help in drawing conclusions about clinics and clinicians, selecting measure-based interventions, and establishing high-level quality strategies to drive better patient outcomes.

##### Problem Statement

How can performance data help an Ambulatory Quality Director establish a measurable, attainable, and actionable quality improvement approach for the upcoming year?

##### Project Goal

Develop a clear recommendation for a high-level quality approach, armed with data analyses against false narratives, and provide insights into specific clinicians and clinics that could benefit from increased attention and guidance.

##### Research Questions

1. How does clinician performance compare to national benchmarks and internal targets?
2. Are there patterns of performance associated with specific locations?
3. Are there patterns of performance associated with patient panel sizes?
4. What is the relationship between clinician roles (MD, NP, PA) and their performance?
5. Are there any outlier clinicians or practices?
6. How can the insights be translated into actionable strategies for quality improvement?

##### Analysis and Approach

The analysis involves comparing internal de-identified clinician quality results with CMS benchmarking data, examining the impact of clinic environments and patient panel sizes, and creating a regression model to predict clinician performance.

##### Key Findings and Recommendations

- Set 2024 Target Goals at the 75th percentile of current performance.
- Share 2024 Stretch Goals at the 90th percentile with high-performers.
- Perform site visits to both high and low-performing clinics to identify scalable practices and address specific challenges.
- Review physician oversight policies for mid-level clinicians to ensure adequate support.
- Use a communication plan to address incorrect narratives and encourage data-driven decision-making.

##### Limitations and Future Work

- The dataset only covers 2023, limiting the scope of the analysis.
- Further iterations and professional consultation could enhance the models and understanding of advanced statistical techniques.

#### Opioid Treatment Analysis (Python Coding)

##### Introduction

In the healthcare industry, understanding opioid prescribing patterns among Medicare providers is crucial for addressing the opioid crisis. This project analyzes Medicare Part D prescribing data, opioid treatment program participation, and overdose death rates to uncover patterns and provide insights for policy and intervention strategies.

##### Data Sources

1. **Opioid Treatment Program Providers**: Information on providers participating in the Opioid Treatment Program.
2. **CMS Program Statistics – Medicare Deaths**: Medicare mortality rates for beneficiaries.
3. **CDC Drug Overdose Death Rates**: Overdose death rates by drug type, sex, age, and race.
4. **Medicare Part D Prescribers – by Provider and Drug**: Prescription drugs provided to Medicare beneficiaries by physicians.
5. **Medicare Part D Prescribers – by Geography and Drug**: Prescription drugs provided to Medicare beneficiaries by geography.
6. **Wikipedia – United States Drug Overdose Death Rates and Totals over Time**: Tables of drug overdose death rates.

##### Analysis and Approach

The project involves data import, cleaning, and transformation using Python and SQLite. The analysis focuses on identifying prescribing patterns, examining the impact of the Opioid Treatment Program, and uncovering trends in opioid-related mortality.

##### Key Findings and Recommendations

- **Prescribing Patterns**: Analysis of prescribing behaviors and their correlation with opioid treatment program participation.
- **Geographic Trends**: Insights into regional variations in opioid prescribing and overdose death rates.
- **Impact of Treatment Programs**: Evaluation of the effectiveness of opioid treatment programs in changing prescribing behaviors.

##### Ethical Considerations

The project adheres to ethical standards in data handling, ensuring privacy and confidentiality. The analysis considers the impact of data transformations and acknowledges the limitations and potential biases introduced during the data cleansing process.

## How to Use

To view the contents:

1. **Project Approach and Code**: Explore the statistical methods and coding techniques used in the projects.
2. **Final Papers**: Read the comprehensive papers for detailed findings, analyses, and recommendations.
3. **Python Code**: Review the scripts used for data analysis and visualization.
4. **Output and Graphs**: Explore the visualizations generated during the projects.

Feel free to contact me for any questions or further information.

Thank you for exploring my Data Science Projects! Continue to check out other sections of my portfolio for more advanced work and projects.

### Bias in Mortgage Lending

#### Introduction
This project aims to investigate bias in mortgage lending practices using the Loan Application Register dataset for the year 2020. With 6 million rows and 99 columns covering various attributes such as loan details, borrower demographics, property characteristics, and approval outcomes, we seek to understand the factors influencing loan denial and assess any underlying biases.

#### Dataset: 
https://ffiec.cfpb.gov/data-publication/snapshot-national-loan-level-dataset/2020
https://drive.google.com/drive/folders/1PU_dOnsjxaUn2_csBGJAanW6SPVwd1W_?usp=sharing

#### Data Exploration and Preprocessing
Through meticulous data cleaning and preprocessing, we prepare the dataset for analysis. This involves removing irrelevant columns, categorizing features such as debt-to-income ratio and applicant's race, and transforming continuous variables like income and loan values through logarithmic transformations.

#### Regression Analysis and Prediction
Utilizing logistic regression models, we analyze the associations between applicant attributes and loan approval outcomes. We assess the significance of features such as race, gender, and income levels in determining loan approval or denial. Additionally, we employ predictive modeling techniques to predict loan approval outcomes based on applicant characteristics.

#### Evaluation of Bias
To evaluate bias in mortgage lending, we utilize fairness metrics such as Odds Ratio, Demographic Parity Difference, and Equalized Odds Difference. These metrics help identify disparities in loan approval rates based on protected attributes like race and gender. We visualize the impact of these biases through bar plots and statistical analyses.

#### Bias Mitigation
To mitigate biases in loan approval predictions, we implement post-processing techniques. Specifically, we employ the equalized odds constraint and optimization of prediction thresholds to ensure fair treatment across different demographic groups. By adjusting decision thresholds based on sensitive features, we aim to achieve equitable outcomes in loan approval predictions for all applicants.

#### Conclusion
This project contributes to discussions on fair lending practices and algorithmic fairness in mortgage lending. By uncovering and addressing biases in loan approval processes, we strive to promote fairer and more equitable lending practices in the mortgage industry, ultimately aiming to reduce disparities and promote financial inclusion.


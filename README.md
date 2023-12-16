# Portfolio of Collaborative Research Projects: Data Analysis and Prediction Models

This portfolio contains three projects that represent a blend of exploratory data analysis and advanced statistical modeling, developed through collaborations with scientific colleagues from Brown University. Each project addresses significant issues in public health and predictive modeling.

## Project Summaries

### Project 1: Analyzing the Impact of Smoking During Pregnancy and Environmental Tobacco Smoke Exposure on Growth of Adolescents
**Collaborator:** Dr. Lauren Micalizzi, Department of Behavioral and Social Sciences, Brown University

#### Overview
This project delves into the exploratory data analysis of smoking during pregnancy and postpartum periods. It investigates the effects of prenatal and postnatal smoking on adolescents' externalizing behaviors, substance use, and self-regulation.

### Project 2: Prediction Model for Tracheostomy Needs or Mortality in Neonates with Severe Bronchopulmonary Dysplasia
**Collaborator:** Dr. Chris Schmid, Biostatistics Department, Brown University

#### Overview
Focused on infants with severe bronchopulmonary dysplasia, this study develops multiple logistic regression models to predict the necessity of tracheostomy. The project compares variable selection methods, including lasso and forward stepwise selection, and evaluates predictive accuracy and model performance matrices. It offers guidance on indication criteria and the timing of
tracheostomy placement. 

### Project 3: Evaluating the Transportability of a Cardiovascular Risk Model Across Different Populations
**Collaborator:** Dr. Jon Steingrimsson, Biostatistics Department, Brown University

#### Overview
Driven by applying prediction models in specific target populations, this project aims to assess generalizability of cardiovascular disease (CVD) risk model from the Framingham Heart Study to
other target populations that only covariates are available. It involves tailoring prediction models based on source population data and assessing their performance in target populations in terms of estimated Brier scores. It conducts a simulation study by generating three different simulation cases with 2000 runs and compares the estimated Briers scores with estimations from the true target population.

## Contributions and Findings

- **Project 1:** Demonstrated a strong correlation between smoking during pregnancy and negative outcomes in adolescence, and postnatal smoking exposure adversely associated with adolescents' externalizing behaviors.
- **Project 2:** Established a robust predictive model for tracheostomy and mortality, showcasing the superiority of the forward stepwise selection method over lasso with the highest AUC of 91.6%.
- **Project 3:** Achieved the lowest average Brier score of 0.1813 for males and 0.0326 for females in simulated populations, outperforming the true target population scores of 0.1885 for males and 0.0408 for females.

## Data Privacy

Data sets used in three projects provided by the Institution are confidential and proprietary information, which can only be shared with the instructor Dr. Alice Paul, students, and TA of the course. Data Privacy Agreement is entered by the signed student participating in PHP 2550 Practical Data Analysis, represented by Dr. Alice Paul.

## Tools and Technologies

- Statistical Analysis Software:
  - RStudio Version 2023.09.1+494
  - R Version 4.2.1 (2022-06-23)
- Data Visualization Tools:
  - tidyverse_1.3.2
  - dplyr_2.2.1
  - gtsummary_1.7.0
  - mice_3.15.0
  - flextable_0.9.3
  - corrplot_0.92
  - ggplot2_3.4.2
  - psych_2.2.9
  - GGally_2.1.2
  - gridExtra_2.3
  - kableExtra_1.3.4
  - hrbrthemes_0.8.0
  - gt_0.9.0
  - webshot_0.5.4
  - data.table_1.14.2
- Regression Modeling, Variable Selection Methods and Simulation:
  - glmnet_4.1-7
  - MASS_7.3-57t
  - caret_6.0-93
  - riskCommunicator_1.0.1
  - fitdistrplus_1.1-8
  - logspline_2.1.21

## Guideline for Repository
In this repository, you can find a pdf report inside `Report` folder along with the corresponding R markdown file inside `Codes` folder. Due to concision of public report, we did not choose to include all analyses in the report. You can find the full R markdown report file inside `Codes` folder. All images and tables in the public report can be found in `Images` and `Tables` folders. All the required packages and version information can be found in this README file.

Each project is organized into its own folder within this repository. The structure of these folders is as follows:

- `Project 1`
  - `Tables` - Contains all the tables generated during the analysis.
  - `Images` - Includes all images and figures produced.
  - `Codes` - Stores all R scripts used for analysis and visualization.
  - `Report` - A comprehensive report of the project in PDF format.

- `Project 2`
  - Similar structure as Project 1.

- `Project 3`
  - Similar structure as Project 1 and 2.

Please navigate to the respective project folder to access its content, including data analyses, visualizations, scripts, and reports.



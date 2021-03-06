# Injury_Severity_Classification
Injury Severity Classification for Insurance Premium Pricing Analysis

# Executive Summary
## Business Understanding: 
The Stark Insurance company is constantly looking for new way to use analytics to improve the company’s performance. A new proposed project using predictive analytics combined with National Highway Traffic Safety Administration data promises to be able to predict injury severity among the current pool of insurance customer and future application for car insurance. The Goal of predicting high vs low injury severity will allow the company to better assess risk and price medical portion of our customer’s car insurance premiums. The project will follow the CRISP-DM methodology, and the project team is comprised of a cross section of the company executives and data science teams. 
## Data Understanding: 
The data used for the project is Crash Report Sampling System data from the National Highway Traffic Safety Commission. The data was divided into 4 tables: Accident, Person Vehicle. The fourth table, Distract, was not relevant to the study. Selecting variables from these 3 tables was accomplished by only selecting variables that are currently collected by car insurance companies about their customers, vehicles, or historical crash data from their customer pool. This selection methodology allowed the team to limit variables for this project to 21 variables that met the selection criteria for the project. 
## Data Preparation:  
Data preparation removed/reduce noise from the data set. Table Joining, Data Filtering, Rule Engine (transformations, binning) were used for initial data preparation in KNIME. Final prep for modeling required the following KINIME transformations depending on model type: Number to String, String to Number, Domain Calculator and Normalizer nodes. 
## Modeling: 
Decision Tree, Random Forest, Neural Network and Support Vector Machine classification predictive models predicted INJ_SEV of vehicle occupants. The model that performed the best and met or exceeded all evaluation criteria was Random Forest model with Accuracy: 83.29%, Sensitivity: 98.206%, Specificity: 17.933% with high explanatory value. 
## Evaluation: 
The Random forest model was the only model of the four that met or exceeded all four of the selection criteria outlined in business understanding for the project to move forward. The model has a low false negative rate and high accuracy which will help the insurance company reduce risk in pricing medical portion of its current and future customers medical premium portion of their car insurance premium.
## Deployment: 
Since the Random Forest model met all criteria for the project, Tony and the Stark Board of Directors chose to move the project into deployment. Peter Parker and his application development team will take over the project on 5.7.20 and work in three team simultaneously integrating the model into the Stark Insurance CRM, Premium Pricing System and JARVIS Data Warehouse.  

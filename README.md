# Startup Funding Prediction Model (Capstone 1)

## Proposal
For my first capstone project I decided to use Crunchbase data to build a model to see if it was possible to predict whether or not a company would be funded in the following year based on data at a given time.

## Problem Statement
It is difficult to truly understand what it takes to start a company and successfully raise capital as there are an endless amount of variables many of which cannot accurately be quantified.  Using data provided by Crunchbase I hope to gain some level of understanding of the startup funding.

## Approach
The first challenge was to make sense of the data and select features that the model would use to predict the success of the company in question.  The final data used consists 111 numeric and 3000 text features summarizing everything from company and investor details and backgrounds to investment rounds and macro economic trends.  To build a model that could handle the wide variety of features I chose to test two different models: Random Forest Classifier and Gradient Boosting Classifier.

## Results
**Best Model:** Random Forest Classifier

**Accuracy:** 0.94<br>
**Precision:** 0.91<br>
**AUC Score:** 0.975

## Languages & Libraries
**Languages:** Python, SQL<br>
**Libraries:** Pandas, Numpy, SciPy, Sklearn, Seaborn, Matplotlib

## Final Presentation:
https://github.com/daikiminaki/Capstone_Project_Crunchbase_Funding_Prediction_Model/blob/master/Capstone_1_Final_Presentation.pdf

## Final Report:
https://github.com/daikiminaki/Capstone_Project_Crunchbase_Funding_Prediction_Model/blob/master/Capstone_1_Final_Report.pdf

# Notebooks:
## Data Cleaning:
https://github.com/daikiminaki/Capstone_Project_Crunchbase_Funding_Prediction_Model/blob/master/notebooks/1_crunchbase_data_cleaning.ipynb

## Data Wrangling
https://github.com/daikiminaki/Capstone_Project_Crunchbase_Funding_Prediction_Model/blob/master/notebooks/2_crunchbase_data_wrangling.ipynb

## EDA 1: Investments
https://github.com/daikiminaki/Capstone_Project_Crunchbase_Funding_Prediction_Model/blob/master/notebooks/3a_crunchbase_eda_investments.ipynb

## EDA 2: Investors
https://github.com/daikiminaki/Capstone_Project_Crunchbase_Funding_Prediction_Model/blob/master/notebooks/3b_crunchbase_eda_investors.ipynb

## EDA 3: Industry/Category
https://github.com/daikiminaki/Capstone_Project_Crunchbase_Funding_Prediction_Model/blob/master/notebooks/3c_crunchbase_eda_categories.ipynb

## Machine Learning & Final Analysis:
https://github.com/daikiminaki/Capstone_Project_Crunchbase_Funding_Prediction_Model/blob/master/notebooks/4_crunchbase_machine_learning.ipynb

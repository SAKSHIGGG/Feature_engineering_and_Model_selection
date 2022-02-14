## Data Description
The actual concrete compressive strength (MPa) for a given mixture under a specific age (days) was determined from laboratory. The data has 8 quantitative input variables, 1 quantitaive output variable and 1030 instances(observations).  

## Context
The concrete compressive strength is a highly nonlinear function of age and ingredients. These ingredients include cement, blast furnace slag, fly ash, water, superplasticizer, coarse aggregate and fine aggregate.

## Objective
Modeling of strength of high performance concrete using Machine Learning

## Steps and tasks
1. Exploratory data quality report  
   a. Univariate analysis - data types and description of the independent attributes, analysis of the body of distributions / tails, missing values, outliers.   
   b. Bi-variate analysis between the predictor variables and between the predictor variables & target column. Presence of leverage points. Visualize the analysis using boxplots and pair plots, histogram or density curves.   
   c. Pick one strategy to address the presence outliers and missing values and perform necessary imputation.    
   
2. Feature Engineering techniques  
   a. Identify opportunities (if any) to create a composite feature, drop a feature etc.  
   b. Decide on complexity of the model, should it be simple linear model in terms of parameters or would a quadratic or higher degree help  
   c. Explore for gaussians. If data is likely to be a mix of gaussians, explore individual clusters and present your findings in terms of the independent attributes and their suitability to predict strength.   
      
3. Create the model  
   a. Obtain feature importance for the individual features and present your findings  
   
4. Tuning the model  
   a. Algorithms that you think will be suitable  
   b. Techniques employed to squeeze that extra performance out of the model without making it overfit or underfit   
   c. Model performance range at 95% confidence interval
      
   

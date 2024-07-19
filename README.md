# Maximizing Home Value: Data-Insights on the Impact of Renovations in King County

**Author**: Keziah Gicheha, Dave Omondi, Pamela Okinyo, Charles Ndegwa, Brian Kipng'eno **(Group 12)**

## Overview
This project aims to provide actionable insights for a real estate agency on how home renovations can increase the estimated value of homes in King County. The business problem addressed is the need to advise homeowners on the most impactful renovations to maximize their property's value. Using the King County House Sales dataset, which includes features such as bedrooms, bathrooms, living area square footage, and more, we employ multiple linear regression and other statistical methods to analyze the relationship between these features and home prices. Our results indicate that certain renovations, particularly those that include increasing living area and upgrading amenities, the number of bathrooms and bedrooms, significantly boost home value. Based on these findings, we recommend prioritizing specific types of renovations to achieve the highest return on investment for homeowners.

## Business Problem
The primary business problem is the need for a real estate agency to provide data-driven advice to homeowners on how home renovations can enhance the value of their properties. Homeowners often invest in renovations without clear guidance on which improvements will yield the highest return on investment. By addressing this pain point, the agency can offer more valuable services to clients, enhancing customer satisfaction and potentially increasing the agency's market share.

## Data
Using **kc_house_data.csv**, which contains _King County House Sales dataset_. The data provides insights into various aspects of house sales such as property features and sale prices.

## Methods
This project uses Linear modeling to infer over the relationship between the features in the dataset's ability predict property value. The steps taken for this approach is:
+ Inspecting and Cleaning the Data
+ Data Preparation
+ Exploratory Data Analysis (EDA)
  1. Univariate Analysis
  2. Bivariate Analysis
+ Plotting Categorical Values
+ Data Modelling
    - Preprocessing
    - Baseline Model
       - Interpretation of Results
    - First Iteration
       - Check Assumptions
       - Interpretation of Results
    - Second Iteration
        - Check Assumptions
        - Interpretation of Results
    - Third Iteration
        - Check Assumptions
        - Interpretation of Results
    - Final model
        - Check Assumptions
        - Interpretation of Results
+ Model Validation
+ Contribution of Predictors
+ Conclusion
+ Recommendations
+ Next Steps
    
## Results
   ### Exploratory Data Analysis (EDA)
     #### Univariate Analysis
     
     #### Bivariate Analysis 
     
   ### Data Modelling
     #### Preprocessing
           
     #### Baseline Model
     
     #### Final Model
     
   ### Model Validation
   
   ### Contributions of Predictors
     

## Conclusions
After several iterations of refining the model, the final model showed significant improvements:

**Final Model Performance** - The _R-Squared_ value improved to **_0.83_**, indicating that **_83%_** of the variance in house prices can be explained by the model's features. The _RMSE_ of the final model **(0.7995)** was significantly lower than the initial baseline model **(256860.6115)**, indicating better predictive performance

### Next Steps
Further analyses could yield additional insights to further improve results:
1. Feature Engineering - Create new features such as price per square foot, age of the property, and distance to key amenities. Consider the impact of renovations by calculating the difference between yr_built and yr_renovated.
2. Geospatial Analysis - Use latitude and longitude data to visualize property locations and analyze spatial patterns. Identify hotspots for high-value properties and areas with potential for growth.

## For More Information






## Repository Structure

```
├── data
├── images
├── README.md
├── Presentation.pdf
└── a_analysis.ipynb
```

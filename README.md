# project_6_capstone

### Problem Statement

Rodents have always been a big health issue in NYC especially for the restaurant industry. Restaurant consulting services are provided to restaurants owners for helping them solve issues in various aspects of their business. Location is one of most important factors for new restaurants. 

In this project, we are going to focus on Manhattan area with two datasets [Rodent Inspection in NYC](https://data.cityofnewyork.us/Health/Rodent-Inspection/p937-wjvj) and [Restaurant Inspection](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j ) from New York City Department of Health and Mental Hygiene (DOHMH). We are going to predict rats inspection results for certain areas where restaurants are concentrated. 
The models we are going to us in this project: 
1. Linear regression model with "Rodent Inspection in NYC" dataset.
2. Time series in centain area:  
    - ARIMAX: We are going to consider features in "Restaurant Inspection" as eXogenous "X".   
    - Random Forest  
3. CNN  




### Limitation   
- Thousands of restaurants start business and go out of business every year; only restaurants in an active status are included in the dataset.  
- Note that if a property/taxlot does not appear in the file, that does not indicate an absence of rats - rather just that it has not been inspected.   
- Neighborhoods with higher rates of active rat signs may not actually have higher rat populations but simply have more inspections.

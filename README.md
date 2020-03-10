# project_6_capstone

### Problem Statement

Rodents have always been a big health issue in NYC. Real estate companies consider rats as a factor of devaluate housing prices; restaurateurs believe that rats issue is the matter of survival in the industry.   

In this project, we are going to build a time series model to predict rats sightings for one zip code area NY 10002 which is lower east side include Manhattan Chinatown where a lot of restaurants located. We are building this model based on data from January, 2010 to December 2018. This model could help New York City Department of Health and Mental Hygiene (DOHMH) schedule rodent inspections without depending on 311 calls.   

We are using SARIMAX model which is a time series model incorporating Seasonality "S"and eXogenous features"X". The exogenous features are the number of restaurants and population based on zip code. We are going to split our data to training data from January, 2010 to December, 2016 and testing data from January, 2017 to December, 2018, and evaluate our model based on mean squared error(MSE).  

We are focus on Manhattan area using several datasets include [Rodent Inspection in NYC](https://data.cityofnewyork.us/Health/Rodent-Inspection/p937-wjvj) and [Rat Sightings](https://data.cityofnewyork.us/Social-Services/Rat-Sightings/3q43-55fe) from DOHMH and census data from United States Census Bureau.    




### Limitation   
  
- Note that if a property/taxlot does not appear in the file, that does not indicate an absence of rats - rather just that it has not been inspected.   
- Neighborhoods with higher rates of active rat signs may not actually have higher rat populations but simply have more inspections.

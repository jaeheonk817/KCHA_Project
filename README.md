# KCHA_Project

# Overview
This data science project uses multiple linear regression analysis techniques to build a reliable, statistically significant model for predicting housing prices in Kings County, Seattle. The data will contain home sale prices from May 2014 to May 2015, from King County's government records. The stakeholder is KCHA, Kings County Housing authority, a public agency that provides affordable housing options and services to low-income families, individuals, and seniors in King County. Their particular concern is providing homes for a family of five or more people. This project will help them to make data-driven well-informed decisions on making future services and polices.

# Business Problem
## Who is King County Housing Authority?
The KCHA is a public agency that provides affordable housing options and services to low-income families, individuals, and seniors in King County. They aim to help improve the quality of life for residents in the area by providing safe, decent, and affordable housing options, as well as supportive services and programs.
## What are their headaches?
- The metropolitan area has a severe shortage of affordable housing, and KCHA is working to address this issue, possibly due to the concentration of large corporate campuses in the Seattle area.
- However, the presence of these high-earning populations and corporate campuses makes it challenging to acquire new affordable housing units, requiring extreme precise mathematical precision.
- The housing market in Seattle is experiencing significant turbulence:
  - Housing prices have seen a sharp increase following the pandemic.
  - Rising interest rates are driving up mortgage rates.
  - The potential for an economic recession adds to the uncertain outlook of the housing market.    
  - The presence of nearby tech campuses and potential for tech lay-offs further complicates the situation.
- KCHA asked to provide a housing price prediction model that can accomodate a family of any size.

# Data Understanding
## Data 1: Home Sales Prices of King County in 2021 and 2022
This data was gathered from King County's official government website https://kingcounty.gov/. This is our primary dataset and it contains detailed information about features of the houses sold.
## Data 2: Reported Incidents in King County up to 2019
This data was gathered from King County's official government website https://kingcounty.gov/. This is our supporting dataset and it contains detailed information about reported incidents in King County all the way to 2019. This information can be useful in creating new columns that tell how many incidents occurred in different regions.
## Data 3: Reported Offenses in King County from 2020
This data was gathered from King County's official government website https://kingcounty.gov/. This is our supporting dataset and it contains detailed information about reported offenses in King County since 2020. This information can be useful in creating new columns that tell how many offenses occurred in different regions.
## Data 4: Population, City, County by Zipcode
This data was gathered from King County's official government website https://kingcounty.gov/. This is our supporting dataset and it contains a conversion table for zipcode, population and city.

# Data Preparation
In this step, missing values were filled based on the data's nature and distribution shape. Some new columns were created to capture more insights that can be used in the prediction model later. Each column was classified as numerica data, nominal data or ordinal data and went throuch specific preparation process accordingly.

# Evaluation / Modeling
Different multi-linear regression models aiming for price prediction were made. With trial and error, each subsequent model was improved.

![image](https://user-images.githubusercontent.com/122312679/220419704-92edb1ae-3148-40a1-bcf2-1a761ecbec32.png)
![image](https://user-images.githubusercontent.com/122312679/220419755-49597dc7-84af-481b-b16b-d7e56d9759d9.png)

# Final Model / Conclusion
The fifth model was chosen as the final model. While the sixth model had higher r-squared, there was greater errors beyond acceptable threshold. The fifth model was performing as well as the sixth model, with much lower prediction errors.

# Next Step
More datasets will be collected in search for new predictor variables that can increase the accuracy of prediction and decrease the errors in prediction

# financial-well-being-analysis
An analysis of a CFPB Dataset to determine the factors that lead to an individual's feeling of financial well being

# Problem Statement: Which factors lead to an individual's financial well being

The goal of my analysis is to determine the primary factors that lead to higher levels of financial well-being for individuals.  To accomplish this objective, I am using data collected from the Consumer Financial Protection Bureau’s (CFPB), National Financial Well-Being survey. This survey uses CFPB’s validated financial well-being scale to measure the financial well-being of a national sample of adults selected to reflect the U.S. population. This survey includes measures of individual and household characteristics, income and employment, savings and safety nets, financial experiences, and other factors hypothesized to influence adults’ levels of financial well-being. The dataset is available at the following link https://www.consumerfinance.gov/data-research/financial-well-being-survey-data/ and the data set user guide is within this repo. It is entitled "cfpb_nfwbs-puf-user-guide.pdf". 

# Notebook Link
The link to the Jupiter notebook that contains my analysis can be found here. https://github.com/etaliafe/financial-well-being-analysis/blob/main/CFPB_Financial_Well_Being.ipynb        

# Analysis
My analysis was conducted using three different models (Linear Regression, Ridge Regression, and Support Vector Regression).  Each of these models were measured based on their accuracy (measured with Mean Squared Error) to predict the highest Financial Well Being level for a given individual. The models all scored similarly in their ability to predict a high financial well being level. I then examined the individual factors used within each of the models and selected the factors that had the most positive influence on an individual's financial well being. Based on this analysis the three primary factors were 1) Whether or not the given individual feels as if it is not difficult to make ends meet, 2) Whether the individual feels as if they could come up with $2000 to quickly manage an unexpected expense, and 3) Whether or not the individual is retired from working. Not surprisingly, the factor of whether or not an individual feels as if they are making ends meet was the most significant indicator of higher financial well-being levels.      

# Next Steps & Recommendations
My analysis was based on the General Population sample. As a next step I would recommend examining other population samples such as the Age 62+ oversample and the Race/ethnicity oversample to determine if the same factors determined for the General Population apply to those populations. I would also recommend using additional modeling techniques (i.e. generating polynomial features) to determine additional factors that may be useful for predicting and individuals Financial Well Being.




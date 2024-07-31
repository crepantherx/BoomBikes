# Bike Sharing Assignment
> Building a multiple linear regression model for the prediction of demand for shared bikes of BoomBikes.

## Problem Statement

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. It wishes to use this dataset to understand the factors affecting the demand for these shared bikes in the American market so that it can prepare itself to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

## The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Technologies Used
- numpy - version 1.24.3
- pandas - version 1.5.3
- matplotlib - version 3.7.1
- seaborn - version 0.12.2
- statsmodels - version 0.14.2
- sklearn - version 1.5.1  

## Conclusion
Significant variables to predict the demand for shared bikes:

- 'year'
- 'workingday'
- Seasons ('spring', 'summer', 'winter')
- Months - January, September ('jan', 'sep')
- Saturday ('sat')
- Weather situation ('Misty','light_snowrain')

And How well these variables describe the bike demands is given by the below rule:

cnt = 0.4506 * const + 0.2569 * yr + 0.0576 * Saturday + 0.0562 * workingday + 0.0406 * winter + -0.09 * Mist + -0.1268 * Dec + -0.17 * Nov + -0.2647 * Light + -0.3099 * spring

## Summary
Following files have been included as part of solution:
1. README.md file sharing the brief Problem Description.
2. Sudhir_Singh_LR_BoomBikes.ipynb file showing building of Multiple Linear Regression Model on the dataset.
3. Sudhir_Singh_LR_BoomBikes.pdf file having subjective questions and their answers.
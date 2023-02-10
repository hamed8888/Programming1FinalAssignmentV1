research Questions:

In this analysis we try to find if is there a relation between age, sex, income level and depression level
and how does it changed from 2014 to 2019. there is a hypothesis that as income decreases, 
depression level will increase

In addition we sarch to find if is there a relation between age, sex, education level and depression level 
and how does it changed from 2014 to 2019. the hypothesis here is that as we see an increase of education level
depression values will decrease

The final question is checking how income and education affect depression level? in other word 
we tried to join the two dataframs of income and education levels based on same age group, sex, country 
and of course depression values to see which income quantiles and income levels match with each other

to do this we rounded values of depression rates (to integer numbers) and for each year, 2014, and 2019 we 
extractd a dataframe.

the final interactive bar plots show mean Education levels based on different income quantiles for same values of depression values
the results show that for same value of depressoion percentage as income quantile increases for a given country, age group and sex 
the education level increases too, so it seems that this independent variables have a direct effect on depression level


About the Data:

First dataset (DepressionByEducationLevel) contains amount of depression symptoms with a percentage number among people of different education level from diffent european countries.
The second dataset shows again the percentages of depression which is categorized based on different income level. both datasets include data of two different years(2014 and 2019).

Data Sources: https://ec.europa.eu/eurostat/cache/metadata/en/hlth_det_esms.htm

other links
countries geojson source: https://www.kaggle.com/datasets/ktochylin/world-countries

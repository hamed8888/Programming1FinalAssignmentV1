Programming 1 Final Assignment

About the Project:

In this Project, we try to find if is there a relation between age, sex, income level, and depression level,
and what is the geographical span and severity of this depression among countries. 
it is expected that as income decreases, depression levels will increase.

In addition (using the second dataset) we search to find if is there a relation between age, sex, education level, and depression level 
and look at its geographical span and severity. 
here expectation is that as we see an increase in education level, depression values will decrease.

After doing these preparatory analyses on the two datasets we reach the research question 
which is checking for a given depression level how income and education change. in another word 
we try to see if is there a relation between income and education (direct or reverse relation) for a specific value of depression.
the hypothesis is that for a given value of depression, for same person sex, from the same age group and country as one of education 
or income increases, the other increases as well.
to do this we categorized (rounded) values of depression rates and for each year, 2014 and 2019, extracted a data frame including 
depression, income, and ds levels in a row to check possible relations. the question is answered with regression analysis for both of the
years.

Built With:
    - Python 3.9.13

dependencies and installation:

1- download the source from github repository
2- install these libraries using the terminal command line:
    - pip install bokeh
    - pip install folium
    - pip install pycountry
    - pip install plotly-express
3- download datasource number 1 (Current depressive symptoms by sex, age, and educational attainment level) 
    preferably in .tsv format from given url (https://ec.europa.eu/eurostat/databrowser/view/hlth_ehis_mh1e$DV_463/default/table?lang=en)
    and set its address in the config file (key in the config file: DepressionByEducationLevel) 
4- download datasource number 2 (Current depressive symptoms by sex, age, and educational income quintile)
    preferably in .tsv format from given url(https://ec.europa.eu/eurostat/databrowser/view/hlth_ehis_mh1e$DV_464/default/table?lang=en)
    and set its address in the config file (key in the config file: DepressionByIncomeLevel) 
5- download world-countries.json from given url (https://www.kaggle.com/datasets/ktochylin/world-countries)
    and set its address in the config file (key in the config file: world-countries)
6- run the project

About the Data:

The first dataset (Current depressive symptoms by sex, age, and educational attainment level) contains percentages of depression symptoms among people of different education levels
in a number of European countries. The second dataset (Current depressive symptoms by sex, age, and income quintile) shows again the percentages of depression symptoms 
for different income levels. both datasets include data from two different years(2014 and 2019) and included with age and sex of the 
participants. 

Data Sources:

1- Current depressive symptoms by sex, age, and educational attainment level:
https://ec.europa.eu/eurostat/databrowser/view/hlth_ehis_mh1e$DV_463/default/table?lang=en
2- Current depressive symptoms by sex, age, and income quintile:
https://ec.europa.eu/eurostat/databrowser/view/hlth_ehis_mh1i$DV_464/default/table?lang=en

countries geojson source: 
https://www.kaggle.com/datasets/ktochylin/world-countries

License:
Distributed under the Mozilla license. See LICENSE for more information.

Questions?
Email: Hamed.goodarzy@gmail.com
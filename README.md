# American Cancer Statistics

## Description

Large cancer datasets from the Centers for Disease Control and Prevention were analyzed to identify trend in cancer rates, focusing on gender, location, age, and race. 

## Analysis
### Hypothesis 1: Cancer rates are increasing - both for the number of incidents as well as the mortality rates
Incidents counts (per 100,000) were investigated including all races, ages, and states to determine the overall rate of cancer incidence. A boxplot was created to show the distribution and any potential outliers for the incidence counts per year. The data is also shown in a graphical representation with a linear regression line. The results of the data suggest that incidence rates are increasing slightly year over year. This increase may be due to new detection methods and technologies. It was noticed that there was a decrease in the number of cancer incidents in 2020, which was most likely due to the pandemic. Correlation analysis between the incidence count and year indicated a very weak positive correlation (r = 0.31). 
![Boxplot USA Population Adjusted Incidence Count By Year for Male and Females](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/boxplot_Incidence_Male%20and%20Female.png?raw=true)
![USA Population Adjusted Incidence Count By Year for Male and Females](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/scatter_Incidence_Male%20and%20Female.png?raw=true)

Mortality counts (per 100,000) were also investigated and visualized in the same manner. The data suggests that mortality rates are slightly decreasing. This slight decrease may be due to the availablity of new treatments and early detection technologies. Correlation analysis between mortality count and year indicated a extremely weak negative correlation or no correlation (r = 0.09). 
![boxplot_Mortality_Male and Female.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/boxplot_Mortality_Male%20and%20Female.png?raw=true)
![scatter_Mortality_Male and Female.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/scatter_Mortality_Male%20and%20Female.png?raw=true)

Based on the data it can conlcuded that cancer rates are slightly increasing while mortality rates are slightly decreasing. 
### Dependencies

import pandas as pd\
from matplotlib import pyplot as plt\
import scipy.stats as stats\
from scipy.stats import linregress\
import numpy as np\
import seaborn as sns\
import warnings


### Data Source

Centers for Disease Control, US Cancer Statistics.
https://www.cdc.gov/cancer/uscs/dataviz/download_data.htm
![image](https://github.com/cassidyschul/American_cancer_stats/assets/150754166/3dfb8ade-5bcf-4d71-876e-8d4e720d9404)

## Presentation
https://docs.google.com/presentation/d/16uDzYJyzhzR3JSWRfEXCCcfPQvvrbWO4cvrNInJ52ks/edit?usp=sharing

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

Based on the data it can be conlcuded that cancer rates are slightly increasing while mortality rates are slightly decreasing. 

### Hypothesis 2: Gender does have an impact on cancer rates and type
Both incidence and mortality rates (per 100,000) were investigated seperately for males and females to determine the impact of gender on cancer rates. Boxplots and scatter plots were created to show any trends.
![boxplot_Incidence_Female.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/boxplot_Incidence_Female.png?raw=true)
![boxplot_Incidence_Male.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/boxplot_Incidence_Male.png?raw=true)
![scatter_Incidence_Female.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/scatter_Incidence_Female.png?raw=true)
![scatter_Incidence_Male.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/scatter_Incidence_Male.png?raw=true)

Based on the incidence count data for both males and females, the incidence rates are increasing for both genders. Correlation analysis between the incidence count and year indicated a weak positive correlation (r = 0.39) for females and a very weak positive correlation (r = 0.22) for males. 

![boxplot_Mortality_Female.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/boxplot_Mortality_Female.png?raw=true)
![boxplot_Mortality_Male.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/boxplot_Mortality_Male.png?raw=true)
![scatter_Mortality_Female.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/scatter_Mortality_Female.png?raw=true)
![scatter_Mortality_Male.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/scatter_Mortality_Male.png?raw=true)

The mortality count data for both genders shows that mortality rates are slightly decreasing for both genders. Correlation analysis between the mortality count and year indicated a very weak negative correlation for females (r = 0.13) and males (r = 0.06). 

Bar charts were created to compare incidence and mortality counts between females and males based on the cancer site. 
![bar_all_years_Incidence.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/bar_all_years_Incidence.png?raw=true)
![bar_all_years_Mortality.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/bar_all_years_Mortality.png?raw=true)

Statistical analysis using the independent t-test was performed to determine if there was significant difference between male and female average incidence and mortality counts. The results indicated that there is not a significant difference between female and male for both incidence average counts for each cancer site (T statistic = 0.341, p value = 0.735) and mortality average counts for each cancer site (T- statistic = 0.417, p value = 0.679). 

### Hypothesis 3: Location does have an impact on cancer rates

Both average incidence and mortality rates (per 100,000) were analyzed seperately for each state to determine if location influences cancer rates. Bar charts were created to visualize the data. 

![Incidence_rate_location.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/Incidence_rate_location.png?raw=true)
![Mortality_rate_location.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/Mortality_rate_location.png?raw=true)

Individuals living in Maine, Florida, West Virginia, Pennsylvania, and Rhode Island have a higher cancer incidence rates compared to those living in California, Colorado, Texas, Alaska, and Utah. People living in West Virginia, Maine, Pennsylvania, Kentucky, and Arkansas have a higher cancer mortality rates compared to those living in California, Texas, Colorado, Alaska, and Utah. California, Colorado, Texas, Alaska, and Utah all have the lowest incidence and mortality rates. West Virginia, Maine, and Pennsylvania have both high incidence and mortality rates. Based on the data shown in the bar charts, location does impact cancer rates.

### Hypothesis 4: Age does have an impact on cancer rates

Both incidence and mortality rates were investigated for each age range. The data was visualized in bar and line graphs. 
![cancer incidence bar plot.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/cancer%20incidence%20bar%20plot.png?raw=true)
![cancer incidence line plot.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/cancer%20incidence%20line%20plot.png?raw=true)
![cancer mortality bar plot.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/cancer%20mortality%20bar%20plot.png?raw=true)
![cancer mortality line plot.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/cancer%20mortality%20line%20plot.png?raw=true)

As shown in the incidence and mortality rate visualizations, as the age increases the cancer incidence rate and mortality rate increases. Age does have an impact on cancer rates. 

### Hypothesis 5: Race does have an impact on cancer rates

A bar chart was created to visualize the incidence counts based on race. 
![Distribution_Race.png](https://github.com/cassidyschul/American_cancer_stats/blob/main/Figures/Distribution_Race.png?raw=true)

Based on the data, race does have an impact on cancer rates. 


### Data Source

Centers for Disease Control, US Cancer Statistics.
https://www.cdc.gov/cancer/uscs/dataviz/download_data.htm
![image](https://github.com/cassidyschul/American_cancer_stats/assets/150754166/3dfb8ade-5bcf-4d71-876e-8d4e720d9404)

## Presentation
https://docs.google.com/presentation/d/16uDzYJyzhzR3JSWRfEXCCcfPQvvrbWO4cvrNInJ52ks/edit?usp=sharing

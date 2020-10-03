# COVID-19 Mortality Study

# Purpose
This is an exploratory data analysis project into the mortality rate of COVID-19, in the United States, using the latest data available from the CDC.

# Key Findings
While I am far from a qualified virologist to postulate on anything remoted virology-related, I found it interesting that the mortality rate is far from static over time. While a generally distrubited vaccine has yet to be available, the observed mortality rate has generally decreased across all age groups on a month over month basis. No hypothesis testing for causality has occured in this EDA.

# Mortality for all sex, race and ethnicity, grouped by age:
![alt text](https://github.com/homesmac/COVID_19_Mortality_Study/blob/main/mortality_study_images/all_ages_df.png)

# Ages < 40:
![alt text](https://github.com/homesmac/COVID_19_Mortality_Study/blob/main/mortality_study_images/under_40.png)

# Ages >= 40:
![alt text](https://github.com/homesmac/COVID_19_Mortality_Study/blob/main/mortality_study_images/40_plus.png)

# All ages:
![alt text](https://github.com/homesmac/COVID_19_Mortality_Study/blob/main/mortality_study_images/all_ages.png)

# White, Non-Hispanic, Male, 70-79 years old
![alt text](https://github.com/homesmac/COVID_19_Mortality_Study/blob/main/mortality_study_images/white_male_70s.PNG)

![alt text](https://github.com/homesmac/COVID_19_Mortality_Study/blob/main/mortality_study_images/white_male_70s_plot.PNG)

# Ambiguities:
* 42.30% race is 'Unknown'
* 0.15% sex is 'Missing' or 'Other'
* 0.11% age_group is 'Unknown'
* 50.64% death_yn is 'Missing' or 'Unknown'
* 3.53% current_status is 'Probable Case'

# Next Steps
Incorporate comorbidity data also available from CDC, however a hurdle remains as the data is not split by demographics available in this study.

# Contact
Jonathan McWilliams\
jonathan dot g dot mcwilliams at gmail\
linkedin.com/in/jonathan-mcwilliams\

Source: Data provided by CDC Case Surveillance Task Force available at https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data/vbim-akqf \
Date current as of: 2020/10/02



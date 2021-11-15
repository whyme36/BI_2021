# LeetCode

## Data
The data used are from kaggle: https://www.kaggle.com/kwullum/fatal-police-shootings-in-the-us?select=PoliceKillingsUS.csv

The dataset consists of information on people killed by police in the US in police intervention. The whole dataset consists of 5 datasets in which we can observe data on poverty rate, high school graduation, median household income, racial demographics, and gender. The main dataset rocks personal data on people shot by police, name, date of death, type of weapon, what and if it was armed, age, race, place of residence. The dataset was collected since January 1, 2015 by the Washington Post, the newspaper obtained data from law enforcement websites, local reports, social media, and by monitoring independent databases.

We chose race as the Y variable, from which we created a binary variable used in the models (victim was white -1, if not white -0)

As X variables we used: age, date, signs_of_mental_illness, Median Income,poverty_rate, percent_completed_hs, share_white, share_black, share_native_american, share_asian, share_hispanic, threat_level, threat_level, gender

#Purpose
Use of approaches:

* Propensity score weighting
* Propensity score matching
* Mass imputation





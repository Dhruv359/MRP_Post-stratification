## MRP_Post-stratification

Paper uses Multilevel Level Regression With Post-stratification to build a model to predict the overall popular vote in the 2023 Federal Elections in Canada based on 10 Canadian Provinces. The Paper considers 6 political parties(Liberal, Conservative, Bloc, Greens, NDP, Peoples) and uses Multilevel Level Regression Model made from the Survey data which is then postratified to an unrepresentative sample from the Census Data. 

- Survey  Data : CES_2019 survey data contains about 4021 rows and 278 variables. It is an annual survey, with data being collected between 2019-09-10 and 2019-11-21. It targets Canadian Citizens and Permanent Residents over 18 years compiling a rich set of data about Canadians’ demographics, opinions and thought process on a wide variety of social, economic, and political issues.
- Census Data : The GSS dataset corresponds to the census dataset used in this research paper. It contains 20602 observations and 81 variables. The target population includes all non-institutionalized persons 15 years of age and older, currently residing in the 10 provinces of Canada. Data was obtained from Uoft@CHASS. The Census data cannot be attached due to privacy obligations. To obtain the data : http://www.chass.utoronto.ca


## Propensity Score Matching with Nearest Neighbour Paper 

A paper that examines the unidirectional casual effect of Income on Job Satisfaction amongst working class Americans. Using the 2020 Public Stack Overflow Survey data, the technique of Propensity Score Matching is implemented with the Nearest Neighbor approach which creates treatment and control groups to find the strength of the association between Income and Job Satisfaction by calculating the ATT. The paper proves a weak causal relationship between Income and Job Satisfaction and ends with possible caveats in the approach used.
  #### Associated file: JobSatisfaction_Income.pdf

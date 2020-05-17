# Autolib-Hypothesis-Testing
## (By Lean Nyaboke)
17/05/2020

## BUSINESS UNDERSTANDING
Autolib' was an electric car sharing service which was inaugurated in Paris, France, in December 2011. It was operated by the Bolloré industrial group, and complemented the city's bike sharing scheme, Velib’, which was set up in 2007. 
The Autolib' scheme maintained a fleet of all-electric  Bolloré Bluecars for public use on a paid subscription basis, employing a citywide network of parking and charging stations.
As of 3 July 2016, 3,980 Bluecars had been registered for the service, and the scheme had more than 126,900 registered subscribers. Autolib' furthermore offered 1,084 electric car stations in Paris agglomeration with 5,935 charging points.
According to Sylvian Géron, writer in the L’ecole de Paris, Autolib’ is a rather crazy entrepreneurial venture. It was started by Vincent Bolloré who launched a project to create an electric battery about fifteen years ago.

## PROBLEM STATEMENT
The management would like to get some insights on the usage of bluecars  and identify whether the Blue cars taken in postal code 75015 are the same as Blue Cars taken in Postal Code 75016.

The dataset to be analysed is http://bit.ly/DSCoreAutolibDataset and the random variable to be analysed is ‘BlueCars_taken_sum’ which is the number of bluecars used on a daily basis.

Hypothesis : The mean number of Bluecars are picked up in postal code 75015 and 75016.

NULL HYPOTHESIS: The average number of Blue cars taken from Postal code 75015 Paris over weekend is the same as those taken in Postal Code 75016.
ALTERNATE HYPOTHESIS: The average number of Blue cars taken from Postal code 75015 Paris over the weekend is not the same as those taken in Postal Code 75016. 

Ho : μ of 75015 = μ of 75016

Ha : μ of 75015 ≠ μ of 75016

## DATA DESCRIPTION
In France,postal codes are used to identify the location of a place. First two digits represent the district, and the last three are for subdivisions (town or neighborhood). The dataset provided has 104 distinct postal codes.
Postal code 75015 The 15th arrondissement of Paris is one of the 20 of the Capital city of France. In spoken French, this arrondissement is referred to as quinzieme The land area of this arrondissement is 8.502 km2 This is the most populous arrondissement of Paris, with 225,362 inhabitants at the last census in 1999. With 144,667 jobs at the same census, the 15th is also very dense in business activities. This arrondissement is home to many families and is known in Paris as one of the quietest sections in Paris. The majority of the arrondissement is relatively unfrequented by tourists, a rarity for one of the world's most visited cities.
Postal code 75016 The 16th arrondissement of Paris is16.00 km ². The population of Paris 16e Arrondissement was 161 817 in 1999 and 159 706 in 2007. The population density of Paris 16e Arrondissement is 9 981.63 inhabitants per km². The number of housing of Postal code 75016 was 101 667 in 2007. These homes of Paris 16e Arrondissement consist of 80 253 main residences, 8 731 second or occasional homes and 12 683 vacant homes.
The data was provided by Dalberg Insights. The data collection procedures were not outlined.

## Hypothesis Testing Procedure
The hypothesis will be testing the mean number of Bluecars are picked up in postal code 75015 and 75016.The Population standard deviation is 185.
I will be using the Z-test for a mean, since my sample is going to be more than 30 and the population standard deviation is known. 
I will be comparing two means from the two specific postal codes.
The level of significance used is 0.05


## Hypothesis Testing Results
Results Test statistic = 1.0054054054054054
P-Value = 0.8426491609483767
At 0.05 significance level the p-value is greater than the significance level. Therefore we accept the null hypothesis.

## Summary and Conclusions
Given the above results, we may conclude that there is enough evidence to accept the null hypothesis that both areas have the same average number of Bluecars being picked during the weekend.

## Resources
Google colab notebook: https://colab.research.google.com/drive/1Rhjc4fZ5kBZghkpjXXTQwMNPhvqDZsma?usp=sharing


## Contact Info

leannyaboke@gmail.com


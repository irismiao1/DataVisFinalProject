# Data Visualization Final Project

## 05-499 Final Project Article Draft
By: Ellen Kahng, Jaemin Lee, Iris Miao, Darren Mok


Hate crimes, or crimes motivated by a negative bias against an individual’s identity such as race, religion, sexual orientation, etc., have become an unfortunate presence in our society. In the year 2016, in the 10 days after the presidential election, an influx of hate crimes were reported to the Southern Poverty Law Center.

An analysis of the hate crime data collected from the SPLC revealed that the number of hate crimes in a given state was correlated to income inequality. To examine this problem, various analytical data visualizations were created, with the intent of understanding and uncovering data that could provide valuable insight on hate crime numbers.



A linear regression was created comparing the median household income values for each of the 50 states and the District of Columbia to the number of hate crimes per 100,000 population. The data was collected from the hate crime reports collected by the Southern Poverty Law Center (SPLC) between November 9-18, 2016. The states were grouped into 1 of 5 geographic regions, bringing to light a slight relation between various regions and their median income levels. The linear regression was found to have a slope of about 9.576e-6 and a p-value of 0.0157, illustrating a non-zero correlation between household income and number of hate crimes. The scatter plot also easily demonstrates any possible outliers at a quick glance, exposing previously concealed data.

This data reveals that hate crimes were not uniformly distributed across the United States, but instead had greater occurrences in certain states compared to others, and also occurred a range of different household incomes.

To delve further into why some states have significantly higher reported numbers of hate crimes, other possibly related socioeconomic data was collected for each state. 


A pairs plot was created using the data to calculate the correlation values between different socioeconomic variables, including the number of hate crimes per 100,000 population (gathered from SPLC), the median household income, the share of the population that is unemployed, and the share of U.S. voters who voted for Trump in the 2016 presidential election.

The correlation values found indicate that all variables examined do affect the number of hate crimes in a given state, although some, such as household income or share of voters for Trump, might have more influence over others, such as unemployment rates.



The heat map above shows the relationship between the share of the population that is unemployed (seasonally adjusted) and the number of hate crimes per 100,000 population (gathered from SPLC). Again, the data points are indicative of each U.S. state, while being grouped into different geographic regions.

The high density of hate crimes around 0.1-0.4 provides information on a sort of average for the number of hate crimes occurring in different states. Additionally, the data points themselves show a non-zero correlation between the two variables, with a majority of the data points being located further to the right of the graph, indicative of a higher share of unemployment.

This data doesn’t provide concrete evidence for our overarching questions, as correlation does not necessarily imply causation. In addition, the data collected is representative of an entire state, whereas various cities, counties, towns, etc. may have differing numbers of hate crimes in relation to the state as a whole. However, the assumption that the number of hate crimes can be related to various forms of income inequality can be proven with these graphs.

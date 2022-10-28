## Project 2 by Jason Chuang


## Problem Statement

A home buyer is always concern about whether they are paying a fair value for their dream house. There could be many factors that determine the valuation of house and it will be very overwhelming for the average home buyer to understand. Besides macroeconomic factors such as interest rate for motgage, there are also demand side factors, such as taste and preference, that will affect the final price. However, It will be good if there are some key factors pertaining to the house, that home buyers can refer as a guide. 

The target audience for this analysis is potential home buyers who are looking for property in the Ames region. The objective of this analysis is to identify key factors pertaining to the house, that affect the valuation. As a result, this will be useful for them in price negotiation.


## Background

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

The Ames Housing dataset was compiled by Dean De Cock for use in data science education. You are tasked with creating a regression model based on the Ames Housing Dataset. This model will predict the price of a house at sale. The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses.


## Data Source
Ames Iowa Housing dataset from Kaggle ([*source*](https://www.kaggle.com/competitions/dsi-us-11-project-2-regression-challenge))


## Data Dictionary

|Variable|Type|Description|
|:---|:---|:---|
act17_participation|float64|ACT|ACT Participation Rate (%) in 2017 by state| 


## Summary of Findings

1. It's not a Zero-sum Game

- In 2019, 36 states had a combined ACT-SAT paricipation of more than 100%. This suggests that it is common for students to take both tests. In comparison between 2017 and 2019, 24 states had increased participate rate, 21 declined, and 6 remained unchanged. This suggests the students still find ACT or SAT relevant.

 - Implication
In States which have high ACT participation rate, we could still explained the benefits of doing SAT as well as this could increase their chances of submitting a more favourable test result.


2. ACT Landscape

- ACT Stronghold
13 US States had 100% participation rate for ACT from 2017 to 2019.They are Alabama, Arkansas, Kentucky, Louisiana, Mississippi, Montana, Nevada, North Carolina, Oklahoma, Tennessee, Utah, Wisconsin and Wyoming.

- Losing Ground
While SAT remained fairly popular, it seems that participation is declining in several states. In comparison between 2017 and 2019, 4 states had increased participate rate, 32 declined, and 15 remained unchanged.

- Implication
Find out more about the reasons for the decline if it is purely due to the de-emphasis for ACT/SAT requirement to get into college.

3. SAT Landscape

- SAT Stronghold
3 US States had 100% participation rate for ACT from 2017 to 2019.They are Connecticut, Delaware and Michigan.

- Gaining Fans
Colorado (11%:2017) and Illinois (9%:2017) turned 100% in 2019. In comparison between 2017 and 2019, 36 states had increased ACT participation rate, 5 declined, and 10 remained unchanged.

- Implication
Simiarly, we could find out more the reason for the increase in participation and hence come out with strategies how we can sustain this trend. We should also pay attention to those states with decline participation rate.


4. The ACT and SAT Divide by Geography
It seems that SAT is more popular among the coastal states while ACT is more in the inland states.

- Implication
If these is any geographical strategy (e.g. placement of supporting office for students who wants more information), this could be a good reference.

5. Correlation Participation and Average Score
States that have higher participation rate in ACT and SAT respectively, tend to have lower average score.

- Implication
Other research suggests that for states with low participation, it is often the case that the students are taking both tests and likely to be more prepared for the tests, hence the higher average score.

6. Correlation Percentage of Graduates
Although the relationship is not that strong, it seems that States with higher percentage of people with degree or higher are more likely to have participation rate in SAT. District of Columbia (DC) is a strong outlier with 63% graduates , 32% and 94% participation rate in 2019 for ACT and SAT respectively.

- Implication
Further research would be needed to ascertain this relationship as this might be driven by other factors. In the mean time, we could consider positioning SAT as having a more preferred choice for states that produce more graduates.

## Conclusions and Recommendations

Based on your exploration of the data, what are you key takeaways and recommendations? Make sure to answer your question of interest or address your problem statement here.

1. Think Win-Win for States with High ACT Participation Rates (e.g. Arkansas, Louisiana, Tennessee)
There are students who take both tests with the hope that it will increase their chance of securing a place in their desired college. While it is practical not to focus on states that have very high ACT participation rate (i.e. > 90%), there is growth oppportunity to get students to do both. States such as Arkansas, Louisiana and Tennessee have increased SAT participation rate despite having 100% for ACT. These are some states for consideration.

2. Maintaining Our Fans (SAT High Participation Rate) (e.g. Connecticut, Delaware and Michigan)
It is still unclear the longer-term impact on ACT and SAT that most colleges are de-emphasizing it, therefore it is recommended to continue engaging key decision makers who decide making SAT compulsory or free for students so that there will be continual support.

3. Growth Opportunities for the In-betweens (e.g. New Jersey, Maryland, Massachusetts)
There are quite a few states which do not have overwhelming preference for one test over another, and they have shown increased participation rate in SAT. These are good growth opportunities for SAT.

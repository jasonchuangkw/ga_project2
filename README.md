## Project 2 by Jason Chuang


## Problem Statement

A home buyer is always concern about whether they are paying a fair value for their dream house. There could be many factors that determine the valuation of house and it will be very overwhelming for the average home buyer to understand. Besides macroeconomic factors such as interest rate for motgage, there are also demand side factors, such as taste and preference, that will affect the final price. However, It will be good if there are some key factors pertaining to the house, that home buyers can refer as a guide. 

The target audience for this analysis is potential home buyers who are looking for property in the Ames region. The objective of this analysis is to identify key factors pertaining to the house, that affect the valuation. As a result, this will be useful for them in price negotiation.


## Background

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

The Ames Housing dataset was compiled by Dean De Cock for use in data science education. You are tasked with creating a regression model based on the Ames Housing Dataset. This model will predict the price of a house at sale. The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses.


## Data Source
Ames Iowa Housing dataset from Kaggle ([*source*](https://www.kaggle.com/competitions/dsi-us-11-project-2-regression-challenge))


## Data Dictionary (By Alphabetical Order)

|Variable|Type|Description|Impact of Variable|Standardised Coefficient|
|:---|:---|:---|:---|---:|
|Bldg Type_Duplex|Categorical|Type of dwelling|Negative|-4,289.61|
|Bsmt Unf SF|Numeric|Unfinished square feet of basement area|Negative|-1,075.30|
|BsmtFin Type 1_LwQ|Categorical|Quality of basement finished area (Low)|Negative|-5,367.75|
|BsmtFin Type 1_None|Categorical|Quality of basement finished area (No Basement)|Negative|-16,230.00|
|BsmtFin Type 1_Rec|Categorical|Quality of basement finished area (Average)|Negative|-30,870.00|
|BsmtFin Type 1_Unf|Categorical|Quality of basement finished area (Unfinished)|Negative|-12,450.00|
|BsmtFin Type 2_LwQ|Categorical|Quality of second finished area (Low)|Negative|-20,060.00|
|BsmtFin Type 2_Rec|Categorical|Quality of second finished area (Average Rec Room)|Negative|-9,072.82|
|Condition 1_Artery|Categorical|Proximity to main road or railroad (Adjacent to arterial street)|Negative|-8,877.90|
|Condition 1_Feedr|Categorical|Proximity to main road or railroad (Adjacent to feeder street)|Negative|-18,910.00|
|Condition 1_PosN|Categorical|Proximity to main road or railroad (Near positive off-site feature--park, greenbelt, etc)|Positive|-9,366.03|
|Exterior 1st_BrkFace|Categorical|Exterior covering on house (Brick Face)|Positive|13,280.00|
|Exterior 1st_CemntBd|Categorical|Exterior covering on house (Cement Board)|Positive|10,660.00|
|Exterior 2nd_HdBoard|Categorical|Exterior covering on house (Hard Board)|Negative|14,090.00|
|Exterior 2nd_Stucco|Categorical|Exterior covering on house (Imitation Stucco)|Negative|-6,497.07|
|Functional_Sev|Categorical|Home functionality rating (Severely Damaged)|Negative|-11,670.00|
|Gr Liv Area|Numeric|Above grade (ground) living area square feet|Positive|-77,330.00|
|Heating_OthW|Categorical|Type of heating (Hot water or steam heat other than gas)|Negative|67.83|
|House Style_2Story|Categorical|Style of dwelling (Two story)|Negative|-97,860.00|
|Land Contour_Bnk|Categorical|Flatness of the property (Quick and significant rise from street grade to building)|Negative|-16,460.00|
|Land Contour_HLS|Categorical|Flatness of the property (Significant slope from side to side)|Positive|-13,030.00|
|Land Slope_Mod|Categorical|Slope of property (Moderate Slope)|Positive|12,450.00|
|Lot Config_CulDSac|Categorical|Lot configuration (Cul-de-sac)|Positive|15,550.00|
|Lot Shape_IR2|Categorical|General shape of property(Moderately Irregular)|Positive|11,000.00|
|MS SubClass_120|Categorical|The building class (PUD (Planned Unit Development) - 1946 & NEWER)|Negative|13,140.00|
|MS SubClass_150|Categorical|The building class (1/2 STORY PUD - ALL AGESR)|Negative|-23,670.00|
|MS SubClass_160|Categorical|The building class (PUD - 1946 & NEWER)|Negative|-93,130.00|
|MS SubClass_90|Categorical|The building class (DUPLEX - ALL STYLES AND AGES)|Negative|-23,920.00|
|MS Zoning_RL|Categorical|Identifies the general zoning classification of the sale (Low Density)|Positive|-5,367.75|
|Misc Feature_Elev|Categorical|Miscellaneous feature not covered in other categories (Elevator)|Negative|15,490.00|
|Neighborhood_BrDale|Categorical|Physical locations within Ames city limits (Briardale)|Positive|-386,100.00|
|Neighborhood_Edwards|Categorical|Physical locations within Ames city limits (Edwards)|Negative|16,450.00|
|Neighborhood_GrnHill|Categorical|Physical locations within Ames city limits (Green Hills)|Positive|-10,900.00|
|Neighborhood_NWAmes|Categorical|Physical locations within Ames city limits (Northwest Ames)|Negative|121,900.00|
|Neighborhood_NoRidge|Categorical|Physical locations within Ames city limits (Northridge)|Positive|-7,582.85|
|Neighborhood_NridgHt|Categorical|Physical locations within Ames city limits (Northridge Heights)|Positive|29,130.00|
|Neighborhood_Somerst|Categorical|Physical locations within Ames city limits (Somerset)|Positive|48,570.00|
|Neighborhood_StoneBr|Categorical|Physical locations within Ames city limits (Stone Brook)|Positive|25,330.00|
|Overall Cond|Rating|Overall condition rating|Positive|43,130.00|
|Overall Qual|Rating|Overall material and finish quality|Negative|474.78|
|Overall Qual^2|Rating|Overall material and finish quality (to the Power of 2)|Positive|1,865.89|
|Roof Matl_WdShngl|Categorical|Roof material (Wood Shingles)|Positive|41,010.00|
|Roof Style_Hip|Categorical|Type of roof (Hip)|Positive|9,325.90|
|Sale Type_COD|Categorical|Type of sale (Court Officer Deed/Estate)|Negative|-11,540.00|
|Sale Type_Con|Categorical|Type of sale (Contract 15% Down payment regular terms)|Positive|41,500.00|
|Sale Type_New|Categorical|Type of sale (Home just constructed and sold)|Positive|28,340.00|




## Summary of Findings





## Conclusions and Recommendations



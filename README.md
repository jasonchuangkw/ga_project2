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
|Bldg Type_Duplex|Categorical|Type of dwelling (Duplex)|Negative|-4,109.03|
|Bsmt Unf SF|Numeric|Unfinished square feet of basement area|-4,693.38|
|BsmtFin Type 1_LwQ|Categorical|Quality of basement finished area (Low)|-14,780.00|
|BsmtFin Type 1_None|Categorical|Quality of basement finished area (No Basement)|-39,240.00|
|BsmtFin Type 1_Rec|Categorical|Quality of basement finished area (Average)|-10,580.00|
|BsmtFin Type 1_Unf|Categorical|Quality of basement finished area (Unfinished)|-18,560.00|
|BsmtFin Type 2_LwQ|Categorical|Quality of second finished area (Low)|-8,778.94|
|BsmtFin Type 2_Rec|Categorical|Quality of second finished area (Average Rec Room)|-8,744.48|
|Condition 1_Artery|Categorical|Proximity to main road or railroad (Adjacent to arterial street)|-20,320.00|
|Condition 1_Feedr|Categorical|Proximity to main road or railroad (Adjacent to feeder street)|-10,110.00|
|Condition 1_PosN|Categorical|Proximity to main road or railroad (Near positive off-site feature--park, greenbelt, etc)|11,180.00|
|Exterior 1st_BrkFace|Categorical|Exterior covering on house (Brick Face)|10,040.00|
|Exterior 1st_CemntBd|Categorical|Exterior covering on house (Cement Board)|11,050.00|
|Exterior 2nd_HdBoard|Categorical|Exterior covering on house (Hard Board)|-4,833.01|
|Exterior 2nd_Stucco|Categorical|Exterior covering on house (Imitation Stucco)|-11,050.00|
|Functional_Sev|Categorical|Home functionality rating (Severely Damaged)|-71,100.00|
|Gr Liv Area|Numeric|Above grade (ground) living area square feet|35,240.00|
|Heating_OthW|Categorical|Type of heating (Hot water or steam heat other than gas)|-96,300.00|
|House Style_2Story|Categorical|Style of dwelling (Two story)|-16,550.00|
|Land Contour_Bnk|Categorical|Flatness of the property (Quick and significant rise from street grade to building)|-12,970.00|
|Land Contour_HLS|Categorical|Flatness of the property (Significant slope from side to side)|9,884.51|
|Land Slope_Mod|Categorical|Slope of property (Moderate Slope)|14,190.00|
|Lot Config_CulDSac|Categorical|Lot configuration (Cul-de-sac)|10,400.00|
|Lot Shape_IR2|Categorical|General shape of property(Moderately Irregular)|13,370.00|
|Misc Feature_Elev|Categorical|The building class (PUD (Planned Unit Development) - 1946 & NEWER)|-421,900.00|
|MS SubClass_120|Categorical|The building class (1/2 STORY PUD - ALL AGESR)|-17,650.00|
|MS SubClass_150|Categorical|The building class (PUD - 1946 & NEWER)|-88,020.00|
|MS SubClass_160|Categorical|The building class (DUPLEX - ALL STYLES AND AGES)|-18,440.00|
|MS SubClass_90|Categorical|Identifies the general zoning classification of the sale (Low Density)|-4,109.03|
|MS Zoning_RL|Categorical|Miscellaneous feature not covered in other categories (Elevator)|20,020.00|
|Neighborhood_BrDale|Categorical|Physical locations within Ames city limits (Briardale)|18,550.00|
|Neighborhood_Edwards|Categorical|Physical locations within Ames city limits (Edwards)|-11,370.00|
|Neighborhood_GrnHill|Categorical|Physical locations within Ames city limits (Green Hills)|128,800.00|
|Neighborhood_NoRidge|Categorical|Physical locations within Ames city limits (Northwest Ames)|22,980.00|
|Neighborhood_NridgHt|Categorical|Physical locations within Ames city limits (Northridge)|39,960.00|
|Neighborhood_NWAmes|Categorical|Physical locations within Ames city limits (Northridge Heights)|-7,504.97|
|Neighborhood_Somerst|Categorical|Physical locations within Ames city limits (Somerset)|27,040.00|
|Neighborhood_StoneBr|Categorical|Physical locations within Ames city limits (Stone Brook)|33,440.00|
|Overall Cond|Rating|Overall condition rating|72,380.00|
|Overall Qual|Rating|Overall material and finish quality|-39,470.00|
|Overall Qual^2|Rating|Overall material and finish quality (to the Power of 2)|3,591.41|
|Roof Matl_WdShngl|Categorical|Roof material (Wood Shingles)|29,300.00|
|Roof Style_Hip|Categorical|Type of roof (Hip)|8,173.70|
|Sale Type_COD|Categorical|Type of sale (Court Officer Deed/Estate)|-10,400.00|
|Sale Type_Con|Categorical|Type of sale (Contract 15% Down payment regular terms)|42,320.00|
|Sale Type_New|Categorical|Type of sale (Home just constructed and sold)|28,380.00|


## Summary of Findings





## Conclusions and Recommendations



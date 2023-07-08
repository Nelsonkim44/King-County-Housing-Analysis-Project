![image](https://github.com/Nelsonkim44/King-County-Housing-Analysis-Project/assets/133017240/329445dd-e455-4322-aa62-b499949351f6)
1. Introduction
   
(i) Objectives

The aim of this project is to analyze King County housing data to find out which features that affect the sale price of houses in the area. I shall utilize linear regression model to achieve this. As a result, I will be able to find out the crucial features which can be considered when doing renovations so that the Housing Agents can get better prices from the sale of houses.After the analysis I will put down couple of recommendations and hand them over to the House Agent who has contracted me so that they can boost the price and sales volumes of the houses in the King County WA.

(ii) Problem Statement
I have been hired to advice a real estate agency on whether home renovations have any significant impact on the value of homes. There are set of features to be considered when doing the renovations so I have to do statistical analysis and come up with a list of them which have the greatest impact on the house prices.

(iii) Business Understanding

Real estate industry is a capital intensive industry which requires thorough analysis and planning at various stages. Various housing Agencies lack technical knowledge on some data analysis problems and that is why I have been contracted by this Housing Agency to help them analyse the crucial factors they should consider most when doing house renovations. Moreover, the Housing agency may be interested in advising their clients who are home owners and would like to understand more on ways of maintaining their homes. The agency will not only use the model I will develop to know the key renovation features but also use it to determine future pricing. The real estate industry is very competitive and thus this Agency will rely so much on this report in terms of understanding the best house features which most buyers prefer based on the King county Data provided. Consequently, they will have a competitive edge in terms of quality home construction, upgrding and also valuation.

2.Data Understanding
The data set being used in this analysis can be accessed in this repository under the file 'kc_house_data.csv'.The other additional dataset explains the meaning of each column of the csv data. For clarity I can rewrite the columns again as:

id - Unique ID for each home sold
date - Date of the home sale
price - Price of each home sold
bedrooms - Number of bedrooms
bathrooms - Number of bathrooms, where .5 accounts for a room with a toilet but no shower
sqft_living - Square footage of the apartments interior living space
sqft_lot - Square footage of the land space
floors - Number of floors
waterfront - A dummy variable for whether the apartment was overlooking the waterfront or not
view - An index from 0 to 4 of how good the view of the property was
condition - An index from 1 to 5 on the condition of the apartment,
grade - An index from 1 to 13, where 1-3 falls short of building construction and design, 7 has an average level of construction and design, and 11-13 have a high quality level of construction and design.
sqft_above - The square footage of the interior housing space that is above ground level
sqft_basement - The square footage of the interior housing space that is below ground level
yr_built - The year the house was initially built
yr_renovated - The year of the house’s last renovation
zipcode - What zipcode area the house is in
lat - Lattitude
long - Longitude
sqft_living15 - The square footage of interior housing living space for the nearest 15 neighbors
sqft_lot15 - The square footage of the land lots of the nearest 15 neighbors
![image](https://github.com/Nelsonkim44/King-County-Housing-Analysis-Project/assets/133017240/d2519641-1d27-4013-959e-ece6ac357c74)

Conclusion

Houses sold between February and April Fetched higher prices.

For every one unit increase in the number of bathrooms, the predicted price of the house increases by 4.33%, holding all other variables constant.

For every one unit increase in the square footage of living space, the predicted price of the house increases by 27.85%, holding all other variables constant.

For every one unit increase in the square footage of the lot, the predicted price of the house increases by 6.36%, holding all other variables constant.

For every one unit increase in the condition rating of the house, the predicted price of the house increases by 5.20%, holding all other variables constant.

For every one unit increase in the grade rating of the house, the predicted price of the house increases by 8.64%, holding all other variables constant.

For every one unit increase in the square footage of living space in nearby houses, the predicted price of the house increases by 14.48%, holding all other variables constant.

For every one unit increase in the age of the house at the time of sale, the predicted price of the house increases by 0.04%, holding all other variables constant.

For houses with a waterfront view, the predicted price of the house increases by 43.16% compared to houses without a waterfront view, holding all other variables constant.

In conclusion, the beast features in housing in King County Area are: waterfront view, square footage of the living room and the house grading.

Recommendations to the  House Agent

The Agency company should consider developing or advise their clients to construct homes with good ambience having waterfront view.
The agency company should aim at constructing houses with bigger square footage as they have higher demand and value.
The agency company should focus on developing houses with the best grades such as: Very good grade, Excellent Grade, Luxury and Mansion Houses.

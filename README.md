# 6-SENSE AGENCY HOUSE PRICE PREDICTION MODEL  
![house_image](https://github.com/kithinji007/Six-Sense-Agency-Hse-price-prediction-model/blob/main/house_image.jpg)

## Objective
The main goal of this research project is to identify and analyze the key factors that have a significant influence on house prices in King County. 
To achieve this objective, the research will address the following questions:
Q1: What is the correlation between house price and other predictor variables?
Q2: Which combinations of features provide the most accurate predictions for housing prices?
Q3: Do renovations of a house contribute to a higher house pricing?

### Business Overview
The objective of this project is to deliver valuable insights to a real estate agency operating in King County, Washington, USA. The agency's primary goal is to offer homeowners recommendations regarding predictor variable's potential impact on property value. By providing this information, the agency aims to guide clients in making informed decisions that can maximize their return on investment when selling their homes.

### Data Understanding
The dataset utilized in this project was obtained in CSV format from Kaggle, consisting of  21 variables, 21,597 records. It includes the following features: id, date, price, bedrooms, bathrooms, sqft_living, sqft_loft, floors, waterfront, view, condition, grade, sqft_above, sqft_basement, yr_built, yr_renovated, zipcode, latitude, and longitude.
![data](https://github.com/kithinji007/Six-Sense-Agency-Hse-price-prediction-model/blob/main/data.png)
Key Predictors: Square foot of living, house grade, condition of the house, No. of floors, bedrooms and bathrooms,  presence of a waterfront, year renovated, year the house was built, and Sales price being the target variable

### Data Correlation
![Heatmap](https://github.com/kithinji007/Six-Sense-Agency-Hse-price-prediction-model/blob/main/Heatmap.png)
sqft_living, bathrooms, grade and sqft_above have multicollinearity of  0.7 and above.  This information is useful in deciding which variables  to use in our model to avoid inaccuracies. Square fit leaving has the highest correlation with price

### Modelling
![Model](https://github.com/kithinji007/Six-Sense-Agency-Hse-price-prediction-model/blob/main/Model.png)
From the plot we can now say that it follows the normality assumption. The spread/dispersion of residuals is more relatively consistent. We have a close to perfect goodness of fit. Our r-squared of about 76% explains the variance in price. This shows that a larger proportion of the variability in price is accounted for by the predictor variables.

### Conclusions
Square foot of living, grade, square foot above, bathrooms and view are the top 5 factors showing very high influence in the price of a house.
The higher the house grade, the more price it fetches. Houses with average condition and above tend to fetch high prices. This could be because of  several factors e.g. a house with average condition and above could have been renovated, recently build or have a higher square foot of living. 
From our analysis we can almost conclusively say that renovations have increased the quality of the house thereby increasing in price.

### Recommendations
Encourage renovations to improve the overall condition and raise the property's grade as this has a great impact on the value of a house.  
Highlight the significant impact of square footage of living space on house prices and use this information to justify higher listing prices for properties with more extensive square footage.  
The number of bathrooms and bedrooms also have a positive correlation with the value of a house. Therefore, during renovation adding a bedroom would increase the value of the house!

### Python Library Tools
Pandas <br>
Numpy <br>
Seaborn <br>
Matplotlib<br>
Scikit Learn<br>
Statsmodel<br>
Plotly

# Exploratory Data Analysis on housing data
In which Indian city, the flats are most expensive?

A data analysis and visualisation was performed on a housing dataset to find out which city has the highest median cost per sqft with respect to flats.

The dataset has around 14000+ rows of data having properties from various Indian cities like Chennai, Mumbai, Bangalore, Delhi, Pune, Kolkata and Hyderabad.

Columns: \
Name: Property Name, \
Property Title: Property Ad Title, \
Price: Property Price \
Location: Property Located Locality and Region \
Total Area: Total SQFT of the property \
Price Per SQFT: Price of Per SQFT of the property \
Description: Small paragraph about the property \
Baths: Number of baths in the property \
Balcony: Whether the Property has balcony or not 


Technology used: **Numpy, Pandas, Matplotlib and Seaborn**

## Results:
![](/result.jpg)

1. The median of price per sqft is much higher in Mumbai compared to other cities.
2. Also the boxplot of Mumbai is more spread out when compared to other cities which are comparitively tighter. This indicates Mumbai has wider range of values of price per sqft when compared to other cities.

The median values for various cities are as follows: 
| City      | Median |
| ----------| ----------- |
| Bangalore     | 5571.0             |
| Chennai       | 5550.0             |
| Hyderabad     |     5774.5         |
| Kolkata       |     4211.0         |
| Mumbai        |        17273.0     |
| New Delhi     |      7301.0        |
| Pune          |      5714.0        |
| Thane         |      9006.0        |

# Supervised-learning using pyspark
# Predict Housing Prices

## Introduction

Housing prices depend on many factors, like the size of the house, number of bedrooms and bathrooms, location, and condition. Predicting prices can help buyers, sellers, and real estate agents make better decisions.  

In this project, I use **supervised learning** to predict house prices. Since the target variable (`price`) is numeric, this is a **regression problem**. I use **Multiple Linear Regression (MLR)** to see how different features affect house prices.  

The dataset I use has information about houses sold, including:  

- `id`: Unique identifier for each house  
- `date`: Date the house was sold  
- `price`: Sale price (target variable)  
- `bedrooms`: Number of bedrooms  
- `bathrooms`: Number of bathrooms  
- `sqft_living`: Living space in square feet  
- `sqft_lot`: Lot size in square feet  
- `floors`: Number of floors  
- `waterfront`: Waterfront property (0 = no, 1 = yes)  
- `view`: View quality rating  
- `condition`: Condition rating  
- `grade`: Construction and design grade  
- `sqft_above`: Living space above ground  
- `sqft_basement`: Basement area  
- `yr_built`: Year built  
- `yr_renovated`: Year renovated (0 if never)  
- `zipcode`: ZIP code  
- `lat`: Latitude  
- `long`: Longitude  
- `sqft_living15`: Living space of 15 nearest houses  
- `sqft_lot15`: Lot size of 15 nearest houses  

You can find the dataset here: [house-data.csv](https://raw.githubusercontent.com/grzegorzgajda/spark-examples/master/spark-examples/data/house-data.csv) (Grzegorz Gajda, 2020). 

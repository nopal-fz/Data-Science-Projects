# Ford Car Price Prediction
![2023-ford-everest-titanium](https://github.com/nopal-fz/Data-Science-Projects/assets/145373069/8bc6698c-42c2-4ad4-a65e-9a27a52ff92c)
## Project Overview:
The Ford Car Price Prediction Project aims to estimate the price of Ford cars by utilizing a data set containing important car features. These features include model, production year, condition, mileage, fuel type, engine volume, transmission type, and tax. With a total of 17,966 rows and 9 columns, this project seeks to identify the key variables that have the most significant impact on car prices on the Belarusian market.

## Data Dictionary:

| Variable        | Description                                                |
|-----------------|------------------------------------------------------------|
| model           | Ford Car model                                             |
| price           | Price in USD (target variable)                             |
| year            | Year of production                                         |
| mileage         | Mileage in kilometers                                      |
| fuel type       | Type of fuel (electro, petrol, diesel)                     |
| transmission    | Type of transmission                                       |
| tax             | Annual tax                                                 |
| Mpg             | Miles per gallon                                           |
| EngineSize      | Car of engine size                                         |

## Impact:
Through exploratory data analysis, several important insights were discovered found that there had been a significant
increase in car prices at the beginning of 2016. Car Using hybrid fuel with a semi-automatic transmission is more expensive
than a diesel car with a manual transmission. However, there are more cars with manual transmissions than cars with automatic transmissions
or automatic transmission. Sports segment cars have the highest prices among all segments, for example other segments cost more or less the same.

For a predictive modelling, A decision tree regression model is used to predict car prices. The model is able to predict cars price with 89.06% accuracy.
The most important feature to predict the price of a car is found in the year and volume of the engine.

This project offers valuable insights to Ford car buyers, helping them make informed decisions in the dynamic automotive market.

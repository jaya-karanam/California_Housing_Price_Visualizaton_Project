# California_Housing_Price_Visualizaton_Project
This project answers 10 most important questions related to California House Price using Python libraries such as Pandas, Matplotlib and Seaborn.

# Q1. What is the average median income of the data set and check the distribution of data using appropriate plots. Please explain the distribution of the plot.
## Inference :
* The x axis represents median income for households within a block and y axis represents its count.
* The histogram and distribution plot shows that the data is slightly right skewed.
* The mean : 3.870671, min : 0.499900, 25% : 2.563400, median : 3.534800, 75% : 4.743250, max : 15.000100.
* Median income's middle 50 percentile data lies between 2.56 and 4.74, first 25 percentile of data have close values between 0.49 to 2.56 but last 25 percentile * data have huge gap between 4.74 to 15.
* Classification: (measured in tens of thousands of US Dollars) (i) Lower income group : 0.49 to 2.56, (ii) Middle income group : 2.56 to 4.74, (iii) High income group : 4.74 to 15.
# Q2. Draw an appropriate plot to see the distribution of housing_median_age and explain your observations.
## Inference :
* The x axis represents median age of a house within a block and y axis represents its count
* The histogram and distribution plot shows that the data is multimodal distributed.
* The mean : 28.639486, min : 1.000000, 25% : 18.000000, median : 29.000000, 75% : 37.000000, max : 52.000000.
* The housing_median_age middle 50 percentile data lies between 18 and 37. First 25 percentile are between 1 and 18 years and Last 25 percentile between 37 and 52 years.
* Classification: (i) New age houses : 1 to 18 years old, (ii) Middle age houses : 18 to 37 years old, (iii) Old age houses : 37 to 52 years old.
# Q3. Show with the help of visualization, how median_income and median_house_values are related?
## Inference :
* The x axis represents median income for households within a block of houses (measured in tens of thousands of US Dollars) and y axis represents median house value for households within a block (measured in US Dollars).
* The scatter plot forms a big cluster with few outliers.
* As median income of households increases the median house value of the block is also increasing (linear relationship).
* The coorelation value between the columns is 0.688 (average positive linear correlation).
# Q4. Create a data set by deleting the corresponding examples from the data set for which total_bedrooms are not available.
## Inference :
All columns of housing dataframe have non-null values (i.e) 20640 values but total_bedrooms have only 20433 non-null values and remaining are null values.

# Q5. Create a data set by filling the missing data with the mean value of the total_bedrooms in the original data set.
## Inference :
The count of all columns including total_bedrooms are 20640 (i.e) No null values are present.

# Q6. Write a programming construct (create a user defined function) to calculate the median value of the data set wherever required.
## Output :
* Enter the column name to find median: median_house_value
* The median value for median_house_value is : 179700.0
# Q7. Plot latitude versus longitude and explain your observations.
## Inference :
* The relationship plot is scatter plot with x axis taken as latitude and y axis taken as longitude.
* Clearly, their is a decline trend (correlation = -0.92, Strongly negative linear relationship).
* As latitude increases, the longitude of the house is decreasing.
* Resulting in houses located at far north as well as far west.
# Q8. Create a data set for which the ocean_proximity is ‘Near ocean’.
## Inference :
There are 2658 blocks which have ocean_proximity 'NEAR OCEAN'.

# Q9. Find the mean and median of the median income for the data set created in question 8.
## Inference :
* Mean value of median_income column of nearocean_housing dataframe = 4.0057848006019565.
* Median value of median_income column of nearocean_housing dataframe = 3.64705.
# Q10. Please create a new column named total_bedroom_size. If the total bedrooms is 10 or less, it should be quoted as small. If the total bedrooms is 11 or more but less than 1000, it should be medium, otherwise it should be considered large.
## Inference :
There are 55 small, 18495 medium and 1883 large bedroom size are there in blocks.

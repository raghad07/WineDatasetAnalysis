# WineDatasetAnalysis


## Step 1: Read CSV file into a DataFrame
import pandas as pd

data_set = pd.read_csv('winemag-data-assignment-2.csv')

## Step 2: Print the Describe and info of the DataFrame
data_set.describe()
data_set.info()

## Step 3: Drop the columns (Description, Region_2, Taster_name, Taster_twitter_handle, Title, Province)
data_set.drop(['description', 'region_2', 'taster_name', 'taster_twitter_handle', 'title', 'province'], axis=1, inplace=True)

## Step 4: Convert text values to numerical values in (Country, Region_1, Variety, Winery)
# Define the function to convert text to numerical values

## Step 5: Fill in missing values in (price) using the mean value and in (points) using the median value
# Fill missing values in 'price' column
# Fill missing values in 'points' column

## Step 6: Split the data into inputs/features (x) and output/target (y)
# Split the data into x (features) and y (target)

## Step 7: Print the Describe and info of the dataset by the descriptive statistics tools
# Print descriptive statistics: mean, mode, sum, maximum, standard deviation, minimum, median

## Step 8: Plot histogram of the dataset
# Plot histogram using matplotlib

## Step 9: Save the modified DataFrame to a CSV file
# Save DataFrame to CSV file


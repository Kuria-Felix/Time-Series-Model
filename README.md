# Time-Series-Model
Using the Craigslist Vehicles Dataset my aim was to create a time series model

# DATA CLEANING STEPS
-> The first step involves Removing columns that can’t be filled like the county column which was empty and columns like ‘id’, ’URL,’ region’, ‘region_url’, ‘image_url’, ‘lat’, 
‘size’, and ’long’ that we wouldn't be needing for this analysis. <br>
->The second step was to fill in missing data values in the dataset. This was done by filling in missing values with the median for numerical columns and the mode for categorical columns. <br>
-> The third step involved converting the 'posting_date' column to a datetime data type. <br>
->The fourth step involved creating a datetime index for the dataset by Utilizing the 'posting_date' column.<br>

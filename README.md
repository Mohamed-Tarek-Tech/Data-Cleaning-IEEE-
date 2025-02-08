# Data-Cleaning-IEEE
In this data, I tried to clean the cloumns that contain NaN values.
First, I drop the duplicated row from my data.
Second, there are several string columns that contain NaN values in them, so I drop them.
And then, I convert all the NaN values that are in the numerical columns with the mean and median value of these cloumns.
Finally, I print the data and information of it to see is there any Nan vlue in my data or not, using { .info() } method.

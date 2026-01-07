LAB 1
Install Jupyter.
Load the Iris dataset using scikit-learn and convert it into a Pandas DataFrame.
Display the first 5 rows of the dataset.
Display the last 5 rows of the dataset.
Display the first 20 rows of the dataset.
Display the last 20 rows of the dataset.
Find the number of rows and columns in the dataset.
Print the column names of the dataset.
Check the data type of each column.
Display a summary of the dataset using info().
Generate statistical summary of the dataset using describe().
Find the mean, median, and standard deviation of sepal_length.
Find the minimum and maximum values of petal_width.
Check whether the dataset contains missing values.
Count the number of samples for each species.
Select the first 10 rows using iloc.
Select only the columns sepal_length and sepal_width.
Select rows where sepal_length is greater than 6.0.
Select all samples that belong to the species Iris-virginica.
Using loc, extract rows 20 to 30 and columns petal_length and petal_width.
Filter rows where petal_length is greater than 5.0.
Filter rows where sepal_width is less than 3.0.
petal_width.
Filter rows where petal_length is greater than 5.0.
Filter rows where sepal_width is less than 3.0.
Apply multiple conditions:
sepal_length > 6.0 AND petal_width > 2.0
Count how many samples satisfy the above condition.
Sort the dataset by sepal_length in ascending order.
Sort the dataset by petal_width in descending order.
Display the top 5 rows after sorting by petal_length.
Group the dataset by species.
Compute the mean of all numerical features for each species.
Compute the maximum petal length for each species.
Find which species has the largest average sepal length.
Create a new column sepal_area = sepal_length × sepal_width.
Use apply() to convert all column names to uppercase.
Use applymap() to calculate the length of each numeric value (after converting to string).
Round all numerical values to 2 decimal places.
Rename column sepal_length to SL.
Drop the column sepal_area.
Make a copy of the dataset.
Reset the index of the DataFrame.
Check for duplicate rows in the dataset.

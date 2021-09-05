# Collecting-files-in-a-dataframe
Collecting all the data from ,, data '' folder into one dataframe.

The data has the following structure:

1) recorded for each user who made purchases, every day
2) each date has its own folder, inside it there are folders for each user
3) inside each folder there is a data.csv file, where the data is stored


Schematically it looks like this:


![image](https://user-images.githubusercontent.com/74469579/132140311-2ab7424a-0425-4716-889c-96a91e7453ec.png)

TASK

To collect all the data from the ,, data '' folder into one dataframe that has the following columns: columns from the files themselves (product_id, quantity), as well as the user's name( name ), and the date of these purchases (date, corresponds to the name of the folder where the folder with the user is located)

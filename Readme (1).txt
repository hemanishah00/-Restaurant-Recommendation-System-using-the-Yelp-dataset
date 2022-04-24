Clean User:After uploading our database, we query out the user data. Then we proceed to cleaning the data:
1) Dropping out the 'elite' column as it is mostly composed of null values.
2) We aggregate all the compliments and review types into a single column for reducing the size.
3) We then convert the 'friends' column into a list for easy processing.

Baseline Model: We have again loaded the model from database. Then after calculating the values for the average ratings,user and item bias, we are calculating the Mean Squared Error.

https://www.kaggle.com/ibtsam/baseline-model
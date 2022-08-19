# Movies-ETL
# Purpose:
     Amazing prime wants its data to be updated on a daily basis. For this reason an automated pipeline had to be created that would take new data, performs the appropriate transformations, and would load data into existing tables. The, process in the last adds data to SQL database.
# Results:
    1. First, we created three data frames from  wikipedia data, kaggle metadata and ratings data in function_test_file
    2. Next we refractored, exracted and transformed the winkipedia data so that it could merge with kaggle data.
    3. After, this step we merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies dataframe. Finally, we merge the MovieLens rating data DataFrame with the movies dataframe to create another datframe which includes movies with ratings.
    4. Finally the final clean csv files are added to PostgreSQL. Here we check the count of rows in movies file as seen in figure
![movies_count](Resource/movies_count.png) 
    and count of rows for ratings file.
![ratings_count](Resource/Ratings_count.png) 

# Summary:
   This assignment of data cleaning and then adding it to another data base teaches us how big data sets could be cleaned in steps and made useful and presentable for its user.
   One point to keep in mind is that data sets are subject to periodic changes, so sometimes we may have to add extra cleaning steps or we may have to take into consideration of files having changes in column or rows, like having additional rows or less columns.
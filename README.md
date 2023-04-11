
'''Worked on a Hotel bookings analysis Project that contains a .csv file with 3820480 cells in it. This dataset contains a total of rows 119390 and 32 columns. In this, I have divided data manipulation workflow into three category Data Collection, Data cleaning and manipulation, and EDA(Exploratory Data Analysis). As Further moved i.e Data collection first step is to find different columns which are done by coding .head(), .tail(), .info(), .describe(), .columns, .index, .size, .shape and some other methods used for data collection, some of the names of the columns are updated here i.e hotel,is_canceled,lead_time,arrival_date_year,arrival_date_month,arrival_date_week_number,arrival_date_day_of_month,stays_in_weekend_nights.As further moved I found the unique values of each column and generate a list in tabular form and also check the dataset type of each columns’ find some columns, not inaccurate data types which correct it later done in Data cleaning part and as well as duplicates data items must be removed as I encountered duplicates items equal to 1023808 (31994 rows × 32 columns) which is dropped from dataset later using .drop_duplicates() 


Before visualizing any data from the data set data wrangling should be performed. For that, I checked for null values of all the columns. After checking, when we get a column with more null values, we drop that column by using the 'drop' method. When we find the minimal number of null values, fill these null values with necessary values as per requirement by using .fillna()


Different charts are used for data visualization to attain better insights and business objectives.

'''

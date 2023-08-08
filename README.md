 BLACK_FRIDAY_SALES_ANALYSIS_USING_PYTHON
 ![image](https://github.com/AnnuNITW/BLACK_FRIDAY_SALES_ANALYSIS_USING_PYTHON/assets/115100166/f3b5c083-09a4-4260-8872-54d02b67955e)


Description:
This project focuses on analyzing Friday sales data to gain insights and perform exploratory data analysis using python.
Our main goal will be to do various kind of analysis and get inferences which will be able to help to provide valuable insights on the market .

Importing Dependencies:
We have importing following python libraries Numpy,Pandas,Matplotlib,Seaborn.

Data Description:
The dataset used for this analysis contains Friday sales data for a specific period. The data is provided in CSV format and includes the 
following columns:
 1) User_Id : Id of a person,
 2) Product_Id : Id of each product,
 3) Gender : Gender of each person,
 4) Age : Age of each person,
 5) Occupation : Occupation of each person,
 6) City_Category : City from which person belongs ,
 7) Stay_In_Current_City : City from which person currently stay ,
 8) Marital_Status : Married person was represented by 1 and unmarried by 0,
 9) Product_Category_1 : Products belong from Product Category 1,
 10) Product_Category_2 : Products belong from Product Category 2,
 11) Product_Category_3 : Products belong from Product Category 3,
 12) Purchase : Amount spend by Customer

 DATASET LINK : https://www.kaggle.com/datasets/sdolezel/black-friday    

In this Dataset there are 5,50,068 rows and 12 columns.
 
Data Cleaning:
In our data set there are 2 columns  Product_Category_2 and Product_Category_3 contains null values , to remove these null values we use dropna() 
function .

We are going to divide the project into 7 parts:

> Dataset Walkthrough ,
> Analyzing Columns ,
> Analyzing Gender ,
> Analysing Age & Marital Status ,
> Multi Column Analysis ,
> Occupation and Products Analysis ,
> Combining Gender & Marital Status

Dataset Walkthrough : 
Here we basically check out the basic things regarding out such as column names ,data types of columns , if there any null values present inside 
our dataset . To remove null values,  we use dropna() function as discussed earlier

Analysing Columns : 
In this section we have mainly used the unique() and nunique() functions to know the number of unique values present in every individual columns.
Analyzing individual columns tells us about the different kind of unique values present in our dataset.

Analysing Gender : 
In this section we basically analyze Gender Column .In Gender Column have male and female values.We have even used  groupby function to see which 
gender is purchasing more in our dataset .So we have presented them with the hepl of pie chart and bar plot in a nice manner.

Analyzing Age & Marital Status:
we can again use the groupby function to see which age group is making the maximum number of order in our dataset. We can also see which age group 
has the highest purchasing amount in our dataset and can plot all the inferences with the help of pie chart and bar plots. After doing some basic 
analysis on Marital Status we can see that 60% of the people in our dataset is unmarried and 40% of them are married. We have even displayed them 
in pie chart forms for better understanding.
 
Multi Column Analysis:
We will use the Seaborn library to visualise them and present them in a more beautiful manner. We have done analysis with the help of Age and Gender
columns and presented them with the help of the Seaborn library. We have also added legends which is basically the hue parameter within the seaborn 
function. So we can basically do analysis for any number of columns based on our choice with the help of the seaborn library.

Occupation and Products Analysis:
Now we can again use groupby ,countplot function  using seaborn library  for data visualisation of Occupation and Products Analysis.Using the 
countplot we can get various insights about which kind of data is present the most in our dataset. We have also plotted normal bar plots
with the help of groupby function to get information such as which Product_ID has got the maximum purchasing amount in our dataset.

Combining Gender & Marital Status:
 Here we have combined the Gender and Martial Status. Hence using seaborn we are able to perform various kinds of data visualizations
 and get meaningful insights of our data when Gender and Martial Status is combined with the help of mainly the countplot.
 
 Conclusion :
 We have analysed the things about these two columns. we have make a new column based on their gender and marital status. we have combined the data
 and make a new column and based on that we have analyzed that men_unmarried spending the most in Black Friday Sales, then comes men_married ,then 
 comes female_unmarried then comes female_married .So this will help us to promote our products and same manner.So we are going to spend most amount
 in our promotion to the male candidates those who are unmarried.
 

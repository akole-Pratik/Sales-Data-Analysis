# Sales-Data-Analysis
Project Name: SuperStore Sales Analysis

Table Of content:
1) Purpose to choose this project
2) Methods and graphs used in this projects
3) Workdone
4) Conclusion
5) Result


1) Purpose to choose this project
   To analyze and answer business questions about 4 years worth sales data. From this data i want to know year -wise sales and profit 
   of company and the growth of the company. This dataset is used for EDA data analysis purpose.


2) Methods and graphs used in this project: head(),tail(), shape,info(),isnull(),describe(),groupby(),appply(), etc.
  For plotting i used matplotlib and seaborn:
  i) line plot
 ii) bar plot
iii) count plot
 
3) Workdone:
-> Firstly import all the required libraries
-> After importing libraries, read dataset which is in the form of excel using read_excel.
-> by using isnull(), check all the null values in the dataset.
-> For getting descriptive statistics summery use describe() method that gave me a mean, median, max, min, etc values 
   over different columns.
-> now to find out EDA(Exploratory Data Analysis) I have answered 5 questions through analysis mainly using pandas and matplotlib library.

  Q1. What is overall sales trend? 
  Q2. Which are the top 10 products by sales?
  Q3. Which are the most selling products?
  Q4. Which is the most preferable ship mode?
  Q5. Which are the most profitable category and sub-category

-> by using groupby method find overall sales trand and profit.

4) Conclusion
-> From above analysis if we carefully observe the data we conclude that, In the initial four months the sales are quite low
-> From month of June to December sales get increasing (great sales amount from June to December).
-> Sales are too higher in the months of November and December.
-> most sales products are from technology category.
-> Standard class is the most preferred ship mode of all the people out of 51 thousand records we have for over four years.


5) Result
   In the light of evidence, we conclude that Initial four months sales are not that much high but after months sales are increasing 
   drastically. so if we see overall pattern which means sales are increasing and profit are also increasing and company is growing.

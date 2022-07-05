# Kickstarter Analysis
Performing analysis on Kickstarter data to uncover trends.

## 1. Overview of Project

Louise’s is fundraising for her play "Fever". She wants to know the how the campaign outcomes is related to their lunched date and funding goals. The purpose of this project is to analysis the campaigns fared in relation to their launch dates and their funding goals using the Kickstarter campaigns from 2009 to 2017.


## 2. Analysis of Outcomes Based on Launch Date

  ### 2.1 Approach

The first part of of this project focus on the "Theatre" category. It investigated the relation between campaigns outcomes and their launch dates. A pivot table is created for the Kickstarter dataset with filters on "Theatre" category and and lunch year. In the pivot table, the number of successful, failed, or canceled projects are counted by lunch month. Then, a pivot chart is created to show the relationship between the number of successful, failed, or canceled projects and the lunch month. 


  ### 2.2 Results

The number of successful projects is related most to lunch month. It is increasing from January to May and decreasing from May to December, with the largest number in May and the lowest number in December. The number of failed projects lunched in the middle of year is larger. There is no strong relation between the number of canceled projects and lunch month. The number of canceled projects is about the same with different lunch month.


## 3. Analysis of Outcomes Based on Goals

  ### 3.1 Approach

In the second part, connection between outcomes and funding goals is analyzed for the “plays” subcategory. The funding goals are divided into 12 dollar-amount ranges. In each range, the number of successful, failed and canceled projects are counted. Then, the percentages of successful, failed and canceled projects are calculated. Those percentages for each range are demonstrated together in a line chart.


  ### 3.2 Results

The percentages of cancled project are zero for all ranges. The successful percentages are higher in the range "less than 1000" and in the range "between 2000 to 4999", which are 76% and 75% seperately. The percentage of failed projects will increase with increasing funding goals. The Projects with funding goal between 45000 to 49999 have the highest failed rate, which is 100%.  


## 4. Challenges and Difficulties

The most difficult step in this project is convert and separate original lunch date in the dataset into month and year. The organization of project categories and sub categories is challenging as well.


## 5. Summary and Limitations

In conclusion, projects lunched in May with funding goals less than 5000 have the highest successful rate. The percentage of failed projects will increase with higher funding goals. The number of canceled project is not strongly related to lunch month and funding goals. 

In the first part of analysis, the number of failed projects and successful projects lunched in May are both largest since the total number of projects in largest in May as well. Thus, to better understanding the connection between lunch month and outcomes, additional calculation such as the percentage of successful, failed and canceled projects is need. A graph of those percentage and lunch month is recommended as well.

In this dataset, the number of total projects for "plays" subcategory are not enough. In the second part of analysis, there is only 1 project with goals over 50000 dollars for "plays" subcategory. More projects could be included in the dataset. Additional analysis could be performed for other categories/subcategories. Graphs of outcomes vs. goals for different category is recommended.

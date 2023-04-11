## Project title - Analyze Supermarket Data Across the Country - Company XYZ.
![sales (7).png](attachment:b5ae6573-2c23-4007-b936-422b848df8e4.png)

This project aims to develop actionable growth strategy for Company XYZ, which owns a supermarket chain across the country, by understanding and analysing sales records got across its branches in a three month period.


## The Dataset
The dataset comprised of csv file imported directly from the [Github link](https://github.com/Ustacky-dev/Pandas-Analytics-Project). Each file contain sales information from the three supermaket location in Lagos, Abuja and Portharcourt, recorded over three months. Contained in these datasets included:
- **Invoice ID**
- **Branch:** This contains letters between A to C to identify the location of the supermarket
- **City:** Locations of the supermarkets
- **Customer type:** The type of customer, between normal and member.
- **Gender:** Sex of customers, male and female only.
- **Product line:** There were categories like: health and beauty, home and lifetyle, sports and travel, electronic accessories, food and beverages and fashion accessories
- **Unit price:**
- **Quantity:** The quantity of goods purchased per customer.
- **Tax 5%:** Tax deduction of goods purchased
- **Total:** Total money received per sale
- **Date:** Period of product purchase
- **Time:**
- **Payment:** Means of payment: Epay, cash and card
- **cogs:** Cost of goods-This amount includes the cost of the materials and labor directly used to create or purchase products.
- **Gross margn percentage**
- **Gross income**
- **Ratings**

## Step 1- Loading the dataset
In this step the dataset from each branch was combined into one data set. We bagan by loading library packages before using the ".read_csv()" and "pd.concat"

## Step 2- Data Exploration
In this step we expored the datasets using inbuilt pandas function. We checked for missing values and did a brief statistical summary to get a little insight on the data. 

## Step 3- Dealing with Datetime
It was obbserved that the 'date' and 'time' colums were not in the appropriate data type. This was corrected using the 'to_datatime()' method. We went further to create other columns from the 'date' and 'time' column containing; 'day', 'month', 'year' and 'hour of each purchase.

## Step 4- Unique Values in columns
In this step we got a list of categorical columns. We iterated through the columns and checked if each elements was an object datatype. We went further to check each of these elements making sure all values were unique, free errors.

## Step 5- Aggregation with GroupBy
Groupby objects was created using the 'City column' together with other columns to gain further insights into the data. Further analysis were carried out to get the 'City' with the; most and least generated gross income; highest unit price and most quantity of products purchased

## Step 6- Data Visualization:
About twelve(12) data visualization were created to explain the analysed data. This brought about a better and far more easy to understand illustration of key information needed by the major stakeholders to make data informed decision 

To-Do - Explain the insights you were able to uncover from the analysing the datasets.

##  Key findings and recommendation
Some of the key insights got the analysis process include:
- All location had the same gross profit margin.
- PortHarcourt branch generated the highest gross income
- Portharcout branch had more funds spent in cost of goods. The managemment can have a review on the operations to know why more resources are spent in the supply chain and procurement unit, and see if actions can be taken to cut cost and increase profit margin.
- Abuja branch was observed to be the least rated branch. 
- Fashion accessories had both genders as a target audience with the female audience a little bit more than the males. Females generally love fashion shopping. Some women take shopping as a hobby while men mostly go fashion shopping on a need-to-do basis. It was observed the fashion accessories had the least quantity of product sold while having one of the highest unit price after sports and travel category. If the unit price can be reviewed or a more quality or affordable products can be acquired, this might improve the sales of the fashion accessories thereby increasing profit margin.<br><br>
![image](https://user-images.githubusercontent.com/58696972/180283606-2b0fbe65-ae1c-4253-9507-33442404abb8.png) <br><br>

![image](https://user-images.githubusercontent.com/58696972/180284608-ee6eb41c-9910-4fce-a736-90b2589ebea8.png)

![image](https://user-images.githubusercontent.com/58696972/180284671-8636c515-1d05-467a-b0ba-0ffa72398ecf.png)



## Further findings and recommendation:

Company XYZ has a lot of product lines that are highly sought after by literally everyone. Increasing its marketing effort will help in boosting sales. Taking advantage of social media platform (instagram, teitter, facebook etc) is one way to reach a broader audience, especially the teens (genz's) 

It was also observed that a significant number of people used Epay and card method of payment. Company XYZ, can take advantage of innovative technologies to expand its sales. A website can be created where products can be advertised and sold online with a delivery system in place. The management can also go further to register with popular brands like; Glovo, Jumia, Asos, Konga etc to advertise and sell  products.

For future analysis, record sales that spans for a year or more period can be analysed to gain better insights and develop more actionable strategies to boost sales and beat competitions.




## Project title - Analyze Supermarket Data Across the Country - Company XYZ.
![image](https://github.com/user-attachments/assets/9491b474-92aa-4394-8c5d-ea5b29859dfc)


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
![image](https://github.com/user-attachments/assets/6f774633-e2a8-4ace-8078-58d72d48bc28) <br><br>

![image](https://github.com/user-attachments/assets/79ef74e0-741d-4354-a9b7-98a286e26206)

![image](https://github.com/user-attachments/assets/eb6a971c-81b7-43b8-be9a-e74d1b6e0efc)



## Further findings and recommendation:

To significantly boost sales and capitalize on market trends, Company XYZ should prioritize the following strategies:

1. Strengthen Digital Marketing Efforts:

Social Media Engagement: Develop a robust social media strategy, focusing on platforms like Instagram, TikTok, and YouTube to connect with younger demographics. Create engaging content, run targeted ad campaigns, and leverage influencer partnerships to increase brand visibility.
Content Marketing: Produce high-quality content (blog posts, articles, videos) to attract and educate potential customers. Optimize content for search engines to improve organic website traffic.
Email Marketing: Implement a targeted email marketing campaign to nurture leads, promote products, and drive conversions.

2. Expand E-commerce Capabilities:

User-Friendly Website: Develop a user-friendly e-commerce website with seamless navigation, secure payment options, and a smooth checkout process.
Mobile Optimization: Ensure the website is fully optimized for mobile devices to cater to the growing number of mobile shoppers.
Strategic Partnerships: Collaborate with online marketplaces like Amazon and eBay to reach a wider audience and increase sales.

3. Leverage Data Analytics:

Sales Data Analysis: Regularly analyze sales data to identify trends, customer preferences, and areas for improvement.
Customer Segmentation: Segment customers based on demographics, behavior, and purchase history to tailor marketing efforts and product recommendations.
Predictive Analytics: Utilize predictive analytics to forecast future sales, optimize inventory levels, and make data-driven decisions.

4. Enhance Customer Experience:

Excellent Customer Service: Provide exceptional customer service through multiple channels (phone, email, chat) to build customer loyalty.
Efficient Delivery: Partner with reliable logistics providers to ensure timely and accurate delivery of products.
Loyalty Programs: Implement loyalty programs to reward repeat customers and encourage repeat purchases.

By implementing these recommendations, Company XYZ can significantly increase its sales, strengthen its brand reputation, and gain a competitive edge in the market




# -Analysis-and-linear-regression-on-Sephora-Dataset
Abstract:Our second project in the Data Science Course with SDAIA Academy
. The project was about using web scraping methods to collect more than 9,000 data records from any website we choose.
We decided to choose the Sephora dataset because we need to think about beauty brands and analyze it more
. The project will analyze Sephora product pages and visualize the price of the products, also try to select which 
categories of products teem to perform better. Additionally, an attempt will be made to 
understand the relationship between ratings, price, categories. Lastly, this 
analysis of the product’s ingredients based on preset categories is made, 
this type of analysis can be relevant and helpful for marketing and formulation teams in cosmetic companies.



Design:
In this project we used the Sephora brand dataset to collect and analysis data and use them to help marketing and formulation teams in cosmetic companies understanding this data by visualizing the rating of the products, top brands and relationship between price and other features.
Data :
The Sephora dataset is interesting for this type of analysis for a few reasons such as It is very recent There are 9168 observations and 21 different variables in varying data types. And down there a summary table of the variables, their data types and a short definition of the dataset that we will work on it:
1
 Feature
id
brand
category
name
size
rating numberofreviews love
price
value_price
URL MarketingFlags
MarketingFlags_content options
details
howtouse
ingredients online_only exclusive limited_edition limitedtimeoffer
Algorithms:
 Feature selection
Type
int object Object Object Object float int
int float float object bool
object object object object object int
int int int
Description
The product ID at Sephora's website
The brand of the product at Sephora's website
The category of the product at Sephora's website
The name of the product at Sephora's website
The size of the product
The rating of the product
The number of reviews of the product
The number of people loving the product
The price of the product
The value price of the product (for discounted products
The URL link of the product
The Marketing Flags of the product from the website if they were exclusive or sold online only
The kinds of Marketing Flags of the product
The options available on the website for the product like colors and sizes The details of the product available on the website
The instructions of the product if available
The ingredients of the product if available
If the product is sold online only
If the product is sold exclusively on Sephora's website
If the product is limited edition
If the product has a limited time offer
 Feature engineering Visualization:
 Scatter plot: Represent relationship between price and value price
 Heatmap: Represent the relationship between all features
 Bar plot: Represent Top ten brands.
Tools:
Technologies :Python,Jupyter Notebook Libraires : Pandas, Numpy ,Seaborn ,Sklearn.

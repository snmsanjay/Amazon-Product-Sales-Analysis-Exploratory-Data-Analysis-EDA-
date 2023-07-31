# Amazon Sales Exploratory Data Analysis (EDA)
  ## Introduction

This project is an Exploratory Data Analysis (EDA) of Amazon sales data. The dataset contains information about 1K+ Amazon products, including their ratings, reviews, prices, and other related attributes.
The goal of this project is to explore and visualize the data to gain insights into product sales trends and customer preferences.

  ## Dataset Description
The dataset comprises the following features:

1. product_id: Product ID
2. product_name: Name of the Product
3. category: Category of the Product
4. discounted_price: Discounted Price of the Product
5. actual_price: Actual Price of the Product
6. discount_percentage: Percentage of Discount for the Product
7. rating: Rating of the Product
8. rating_count: Number of people who voted for the Amazon rating
9. about_product: Description about the Product
10. user_id: ID of the user who wrote a review for the Product
11. user_name: Name of the user who wrote a review for the Product
12. review_id: ID of the user review
13. review_title: Short review
14. review_content: Long review
15. img_link: Image Link of the Product
16. product_link: Official Website Link of the Product

     ## Requirements
1. Python
2. Pandas
3. Numpy
4. Matplotlib
5. Seaborn

 ## Data cleaning and preprocessing 
1. The dataset is read from a CSV file using Pandas.
2. Certain characters like ,, ₹, and % are removed from the discounted_price, actual_price, discount_percentage, and rating_count columns to convert them to numeric values.
3. The rating column contains a character | which is replaced by 4 to convert it to a float.
4. Duplicated data is checked and removed if present.
5. The category column is preprocessed to remove extra information and symbols like &.

 ## Exploratory Data analysis

 The EDA comprises several visualizations to gain insights from the data:
 *Products Demand in Price Range*: A strip plot showing the demand for products in different price ranges 
  for each category.
 *Ratings of Products In Categories*: A box plot showing the distribution of product ratings in different 
 categories.
 *Top Discount Percentage Categories*: A bar plot displaying the categories with the highest discount 
 percentages.
 *Total Sales of Categories*: A bar plot showing the total sales of products in different categories.
 *Correlation Matrix*: A heatmap displaying the correlation between different variables in the dataset.
 *Pairplot*: A pair plot showing the relationships between 'sales', 'actual_price', 'discounted_price', and 
 'rating_count'.
 
   ## Conclusion
  The EDA provides valuable insights into Amazon sales data, including trends in product demand, ratings, 
  and discounts. The visualizations help understand customer preferences and the performance of different 
  product categories. Feel free to explore the Jupyter Notebook to dig deeper into the analysis and 
  customize it according to your requirements.

   ## Acknowledgment 
  This dataset was sourced from Kaggle. Special thanks to the data provider for sharing the data.
 

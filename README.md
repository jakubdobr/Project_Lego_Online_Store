# LEGO_Analysis

Project Overview
This project provides a detailed analysis of sales data from the website krecik.sklep.pl, focusing on LEGO products and others products. The aim of the analysis was to extract valuable insights, such as the most popular products, revenue trends over time, and order patterns, in order to make data-driven decisions.

# Technologies Used
## **Python**:
  - **Pandas**
    - Pandas was employed for data manipulation and analysis. It was particularly useful in cleaning the dataset, handling missing values, and performing aggregations. Pandas' groupby() function was extensively used to          calculate monthly revenues and summarize data such as the most frequently ordered products.
    -**Example tasks included:**:
    -  Loading the dataset from a CSV file and exploring its structure using functions like pd.read_csv() and df.describe().
    -  Cleaning and transforming product names using string manipulation and regular expressions.
    -  Aggregating data to calculate total monthly revenue and the number of orders containing LEGO products.

  - **Matplotlib**
    - Matplotlib was used to create visualizations that helped uncover trends in the data. Line plots were generated to track monthly revenue changes, while bar charts highlighted the most popular products and cities            contributing to sales.
    - Visualizations helped to make the analysis more interpretable and actionable, allowing for the identification of seasonal trends and best-selling products.
    - Specific plots included:
      - Monthly revenue trends for both overall sales and LEGO-specific sales.
      - Top 10 products by number of orders and total revenue.
      
  - **Regular Expressions (regex)** 
    - Regular expressions were used to identify orders containing LEGO products by searching for specific patterns in product names. This was necessary because some product names were inconsistent, and regular expressions       provided a powerful way to detect LEGO-related items based on key terms such as “LEGO” or certain product codes.
    - Regex allowed for efficient filtering of the data, ensuring that only relevant rows (i.e., orders containing LEGO products) were analyzed for specific insights.

  - **Jupyter Notebook**
    - Jupyter Notebook was the main environment for conducting the analysis. It provided an interactive platform to write code, visualize data, and document the analysis process in real-time.
    - Jupyter's ability to combine code execution with markdown allowed for a seamless integration of code snippets, charts, and explanations, making the analysis easier to follow.
    - It was particularly useful for iteratively refining the analysis and quickly testing different approaches to data manipulation and visualization.

# Data Analysis Process
The analysis focused on several key areas:

  1.**LEGO Orders**: Counted orders containing LEGO products based on specific patterns in product names.
  2.**Order Size**: Identified the top 10 largest orders by product count.
  3.**Revenue Analysis**: Grouped and calculated monthly revenues, both overall and specifically for LEGO products.
  4.**Product Trends**: Determined which LEGO sets were most frequently purchased, based on product codes.

#Results:
+ **Oders number**: 837
+ **Most expensive order**: 3549.92 PLN
+ **Largest product count in an order**: 15 items
+ **Average monthly earnings**: 10,020.09 PLN
+ **Average monthly earnings from LEGO sets**: 8,854.37 PLN
+ **Best month in terms of revenue**: June 2023, with total earnings of 18,399.0 PLN
+ **Best-selling LEGO sets**: LEGO 6008 and LEGO 32171, with 16 orders each
+ **Top cities for sales**: Warsaw, Wrocław, Cracow, Poznań, Łódź

#Conclusions
The analysis provided several valuable insights:

+ **Order Count**: Out of a total of 837 orders, 669 were for LEGO products. This shows that while LEGO sets are a significant source of income, other products also contribute to the website’s overall revenue.
+ **Peak Sales**: The highest revenue months occurred during winter and summer holidays, likely driven by gift purchases during Christmas and additional summer attractions for children.
+ **Popular Products**: The LEGO products with the highest order numbers were LEGO 6008 and LEGO 32171, each with 16 orders. Interestingly, LEGO 32171 is not a traditional LEGO set but a pin used to connect various structural elements.
+ **Actionable Insights**: The cities with the highest sales are Warsaw, Wrocław, and Cracow. One potential strategy to further increase sales is to enhance targeted advertising in these cities. For example, building a billboard in Warsaw could significantly expand the website's sales reach.





s

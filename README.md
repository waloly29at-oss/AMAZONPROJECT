# Amazon Product Analysis

## Project Overview
This project explores product data collected from Amazon in order to understand what factors may influence product popularity.
Online marketplaces contain thousands of products with different prices, ratings, and discounts. Businesses need to understand what drives customer engagement and what makes some products more popular than others.
In this project, we performed Exploratory Data Analysis (EDA) on an Amazon products dataset to identify patterns in product pricing, ratings, popularity, and category distribution.
This project was created as a practice project while learning Data Analysis using Python.

## Project Objectives
The main goals of this project were:
* Understand the structure of the dataset
* Clean and prepare the data for analysis
* Explore patterns in product prices and ratings
* Identify factors that may influence product popularity
* Visualize insights using charts and graphs

## Dataset Description
The dataset contains information about products listed on Amazon, including:
* Product name
* Product category and subcategory
* Product price
* Discounted price
* Discount percentage
* Customer rating
* Number of reviews
* Product description and review content
These variables help analyze both product characteristics and customer behavior.

## Data Cleaning
Before performing the analysis, several data preparation steps were required:
* Handling missing values in some columns
* Converting price columns from text format to numeric values
* Removing rows with inconsistent formatting
* Ensuring columns such as rating and review counts were correctly formatted
These steps ensured that the dataset could be analyzed correctly.

## Exploratory Data Analysis (EDA)
To better understand the dataset, several visualizations were created.
The analysis focused on identifying patterns in:
* Product prices
* Customer ratings
* Product popularity
* Category distribution
* Market demand by price range
Visualizations were used to help reveal trends that might not be obvious from raw data.

## Key Insights
After analyzing the dataset, several insights were discovered.

### Price Distribution
Most products fall within the lower price range, suggesting that affordable products dominate the marketplace.

### Market Demand by Price Category
Products priced under 5000 showed the highest popularity scores, indicating that customers are more engaged with lower-priced products.

### Category Distribution
Certain product categories appear more frequently than others, especially electronic accessories.

### Popularity by Subcategory
Some subcategories show higher popularity even when they contain fewer products, indicating strong customer demand in those areas.

### Price vs Rating
There is no strong relationship between price and rating, which suggests that more expensive products are not necessarily rated higher.

## Business Recommendations
Based on the analysis, several recommendations can be made:
1. Businesses should focus on offering affordable products, since lower-priced items attract more engagement.
2. Companies should invest more in high-demand product categories.
3. Expanding product offerings in popular niche subcategories may increase sales.
4. Maintaining high product quality and customer satisfaction can help improve ratings and visibility.

## Tools and Technologies Used
This project was developed using the following tools:
* Python
* Jupyter Notebook
* Pandas&numpy
* Matplotlib
* Seaborn

## Visualizations
The following visualizations were created during the analysis:
* Price Distribution of Products
* Market Demand by Price Category
* Product Percentage by Subcategory
* Popularity by Subcategory
* Relationship Between Rating and Popularity
* Effect of Discount on Product Popularity
These visualizations helped support the insights discovered during the analysis.

## Project Structure
Amazon-Product-Analysis
│
├── data
│   └── amazon.csv
│
├── notebook
│   └── amazon_analysis.ipynb
│
├── images
│   ├── price_distribution.png
│   ├── price_category_demand.png
│   ├── subcategory_distribution.png
│   ├── subcategory_popularity.png
│   ├── rating_vs_popularity.png
│   └── discount_vs_popularity.png
│
└── README.md
## Future Improvements
Possible future improvements for this project include:
* Building an interactive dashboard to visualize real-time data.
* Performing deeper statistical analysis to find hidden correlations.
* Applying machine learning models to predict product popularity based on historical data.
* Expanding the dataset to include more product categories for a more comprehensive market view.

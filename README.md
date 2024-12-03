# Nigeria Housing Market Analysis

## Overview: <br/>
This project performs an in-depth analysis and visualization of Nigeria's real estate market, focusing on various property types, price distribution, and regional variations. The dataset comprises housing price data across different Nigerian states and towns, with additional details about property types, such as Detached Duplex, Terraced Duplexes, Semi-Detached Duplex, and Detached Bungalows. This project aims to understand the distribution of real estate prices, identify trends, and provide valuable insights into the pricing patterns across various regions and property types.

## Objective: <br/>
•	To analyze the price distribution of different property types across Nigerian states and towns. <br/>
•	To calculate and visualize the correlation between various features in the real estate dataset. <br/>
•	To provide insights on the pricing trends based on different property types, states, and towns.

## Methodology:

### 1.	Data Preprocessing: <br/>
o	The dataset was cleaned by filtering properties with prices between 250 million and 1 billion NGN, and specific property types (Detached Duplex, Terraced Duplex, Semi-Detached Duplex, Detached Bungalow). <br/>
o	The data was filtered to exclude entries from Anambra State. <br/>

### 2.	Price Conversion: <br/>
Prices were converted from NGN to millions of NGN for better readability and analysis.

### 3.	Visualizing Price Distribution: <br/>
o	Bar charts were used to visualize the mean price distribution by state and apartment type. <br/>
o	Histograms were plotted to show the overall distribution of prices.

### 4.	Correlation Analysis: <br/>
o	The correlation between various numeric features (such as price and other property attributes) was calculated using Pearson's correlation coefficient. <br/>
o	A heatmap was used to visualize the correlation matrix for better insight into how features are related.

### 5.	Individual Property Type Analysis: <br/>
o	The dataset was filtered by property type to perform analysis on specific categories like Detached Duplex, Terraced Duplex, Semi-Detached Duplex, and Detached Bungalow. <br/>
o	For each property type, the following was analyzed: <br/>
	Mean price per state: Bar chart visualization for price distribution across states. <br/>
	Mean price per town: Filtered towns where the mean price was greater than or equal to 250 million NGN. <br/>
	Price distribution: Histogram to visualize the price frequency. <br/>
	Correlation analysis: Pearson correlation between relevant features and visualization of correlations through a heatmap.

## Functions:

### 1.	mean_price_by_state(dataframe): <br/>
Calculates and visualizes the mean price by state in a bar chart. Helps identify states with higher or lower average prices.

### 2.	price_distribution(dataframe): <br/>
Plots a histogram of property prices to understand the frequency distribution and concentration of prices within the dataset.

### 3.	mean_price_by_town(dataframe): <br/>
Calculates the mean price by town and visualizes it, focusing on towns with prices greater than or equal to 250 million NGN.

### 4.	correl(dataframe): <br/>
Computes and prints the correlation matrix for all numeric columns in the dataset. This function highlights the relationship between different features.

### 5.	correlHeatMap(dataframe): <br/>
Generates a heatmap visualization of the correlation matrix. Aids in understanding the strength of correlations between features.

## Data Filters Applied: <br/>
•	Price Range: The dataset was filtered for properties priced between 250 million NGN and 1 billion NGN. <br/>
•	Apartment Type: Only the following property types were considered: Detached Duplex, Terraced Duplex, Semi-Detached Duplex, and Detached Bungalow. <br/>
•	State: All entries from Anambra State were excluded for the analysis.

## Visualizations: <br/>
1.	Mean Price Distribution by State: Visualizes the average price of properties in each state, helping to identify where expensive properties are concentrated. <br/>
2.	Price Distribution Histogram: Shows the frequency of various price ranges, which can be useful to understand market concentration. <br/>
3.	Mean Price by Apartment Type: Compares the average prices of different property types, providing insights into which types are more expensive. <br/>
4.	Correlation Heatmap: Displays the relationships between features in the dataset, highlighting the strength of correlations with color intensity.

## Insights: <br/>
•	State-wise Pricing: States like Delta, Lagos and Abuja exhibit higher property prices compared to other states, which may be indicative of better infrastructure and economic development. <br/>
•	Apartment Type Pricing: According to the dataset, Detached Bungalows are more expensive than Detached Duplexes, Terraced Duplexes and Semi-Detached Bungalows, which is consistent with general property trends. <br/>
•	Market Trends: The dataset reveals valuable insights into the real estate market in Nigeria, allowing investors and stakeholders to make informed decisions based on property prices and market demand. <br/>
•	Correlation: The correlation heatmap indicates relationships between certain features, such as number of bedrooms and price, suggesting that more bedrooms tend to have higher prices.

## Conclusion <br/>
This project provides a clear visualization of the real estate market in Nigeria, helping businesses, investors, and policymakers understand the market dynamics and make data-driven decisions. Though the project serves as a personal project to showcase data science, data analytics and visualization skills, it holds potential for businesses to understand trends in the real estate sector. <br/>
For more robust and tailored analysis and visualizations, feel free to contact me for personalized services.

Abdullahi Olalekan Abdulmumeen <br/>
Applied Data Scientist <br/>
Olalekanabdulmumeen3@gmail.com

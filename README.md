This project involves analyzing and visualizing the relationship between mobile phone features and price range. The dataset contains details about mobile specifications such as battery power, clock speed, internal memory, screen resolution, RAM, and more, alongside a target variable, "price_range," that categorizes phones into different price brackets.

Key Steps and Insights:

Data Exploration:

The training dataset has 2,000 entries, and the test dataset has 1,000 entries with no missing values.
Variables such as battery power, RAM, and screen dimensions show significant variance across phones.
Initial Data Visualization:

A countplot of price_range reveals a balanced dataset across the price categories.
Pairplot and scatterplot visualizations show clusters of phones based on internal memory, weight, and price range. Phones with higher internal memory and lower weight are generally in the higher price categories.
Correlation and Insights:

Internal Memory vs Mobile Weight: The scatterplot shows a mixed correlation with no clear linear relationship between these features.
Price Range Clusters: Phones in specific price ranges tend to group in areas of the plot, suggesting that certain features like memory and weight influence the pricing structure.
Outliers: Some outlier phones with unusually high or low features may warrant further investigation.
Feature Importance for Price Prediction:

Visualizations of other features like pixel height, RAM, number of cores, and screen size also show distinct clusters in terms of price range. Higher RAM, larger screens, and higher resolution correlate with more expensive phones.
This analysis helps in understanding how different phone specifications contribute to pricing and suggests potential features for building a price prediction model

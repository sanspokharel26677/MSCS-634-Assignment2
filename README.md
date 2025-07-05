# MSCS-634-Assignment2

# Lab 1: Data Visualization, Preprocessing, and Statistical Analysis

## Purpose of the Lab
The purpose of this lab is to explore a small retail dataset using essential data preprocessing and statistical analysis techniques. This includes scaling numerical data, categorizing values, and visualizing insights to better understand patterns in the dataset.

##  Key Insights from Visualization and Statistics

- **Histograms** helped reveal the distribution of key numerical variables like `UnitsSold`, `UnitPrice`, and `Revenue`. These showed skewness and potential outliers.
- **Boxplots** clearly illustrated outliers in `UnitsSold`, `UnitPrice`, and `Revenue`, especially for extreme values.
- **Bar chart by Category** showed that the `Groceries` category had the highest total `UnitsSold`.
- **Central Tendency Measures** such as mean, median, and mode gave useful insight into the average behavior of sales data.
- **Dispersion Measures** showed a high variance and range in the `Revenue` field, indicating uneven distribution.
- **Correlation Matrix** revealed strong correlation between `UnitPrice`, `Revenue`, and `UnitPrice_Scaled`.

## Preprocessing Techniques Used

- **Min-Max Scaling** was applied to `UnitPrice` to bring values to a 0–1 range.
- **Discretization** was used to categorize `UnitsSold` into `Low`, `Medium`, and `High`.

## Challenges and Decisions

- The small dataset size (only 5 rows) limited deeper statistical inferences.
- Some preprocessing techniques like scaling might not be very impactful due to the limited size but were implemented to demonstrate understanding.
- Visualization layout and axis adjustments were carefully managed for clarity and readability.

## Conclusion

This lab helped reinforce important data preprocessing and analysis steps such as scaling, categorization, and visual exploration. These are foundational for more advanced tasks like machine learning or large-scale data mining.

# Bangalore-House-Price-Analysis-Report

1. Introduction
This analysis examines property prices in Bangalore, focusing on price per square foot to detect and manage outliers using statistical methods.
The dataset contains 13,200 records with features such as location, size, total square footage, number of bathrooms, and price.

3. Exploratory Data Analysis (EDA)
Missing Values: No missing values were found in the dataset.

Summary Statistics:

Average price per square foot: ₹7,920

Minimum price per square foot: ₹267

Maximum price per square foot: ₹12,000,000

Distribution Analysis: The histogram shows a right-skewed distribution, indicating extreme high values.

3. Outlier Detection & Removal
Four methods were applied:

Mean & Standard Deviation: Removed values beyond 3 standard deviations.

Percentile Method: Kept values between 5th and 95th percentile.

Interquartile Range (IQR): Removed values outside 1.5 times the IQR.

Z-Score Method: Eliminated values with Z-score > 3.

4. Box Plot Comparison
A box plot was used to compare the effectiveness of each method. The IQR method provided the best balance between retaining meaningful data and removing extreme outliers.

5. Normality Check & Transformation
Histogram Analysis: The price per square foot column was highly skewed.

Transformation Applied: Log transformation improved normality.

Skewness & Kurtosis Before Transformation: High skewness and kurtosis.

After Transformation: Reduced skewness, making the data more normally distributed.

6. Correlation Analysis
Heatmap Findings: Strong correlation between total square footage and price.

Scatter Plot Observations: Larger properties tend to have higher price per square foot, but extreme values distort trends.

7. Conclusion
Outlier Removal: The IQR method was the most effective.

Data Transformation: Log transformation improved normality.

Key Insights: Larger properties generally have higher price per square foot, but extreme values distort trends.

This analysis provides a structured approach to understanding Bangalore's real estate market.
